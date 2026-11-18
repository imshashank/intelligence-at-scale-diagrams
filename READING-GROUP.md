# A reading group for the first three chapters of Intelligence at Scale

Use the free chapters of *Intelligence at Scale* by [Shashank Agarwal](https://www.linkedin.com/in/shashankagarwal2/) for three 45-minute discussions. Each meeting pairs one chapter with an original paper and a task that leaves the group with something to compare. The exercises are designed for software engineers and students who are beginning to read about neural networks. Only the last meeting uses code, and it runs with standard Python.

## Session 1 — Reconstruct what changed with AlexNet

Read [How It All Started](https://intelligenceatscale.ai/chapters/how-it-all-started), paying attention to the separate roles of data, hardware, and model design. Then read the introduction and architecture section of the [2012 AlexNet paper](https://papers.nips.cc/paper_files/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf).

- **First 10 minutes.** Each reader names one change in the experiment and one thing the authors held fixed when measuring it.
- **Next 20 minutes.** Sketch a table with a row for the training data, the GPU implementation, and the architecture. For each row, record what the paper directly measured, the comparison it used, and what would need a separate experiment to isolate.
- **Last 15 minutes.** Explain top-1 and top-5 error on a small example. Suppose a classifier ranks the correct label third. Count that example as a top-1 error and a top-5 success. Ask what the metric reveals when classes are similar and whether a result for one task supports a claim about a different one.

Leave with the comparison table and a citation beside each number. Match the evaluation split and metric before comparing figures from two passages of the paper.

## Session 2 — Draw the information path in two translators

Read [Before the Transformer](https://intelligenceatscale.ai/chapters/before-the-transformer) and the model overview of [Bahdanau, Cho, and Bengio’s neural translation paper](https://arxiv.org/abs/1409.0473). Sketch a source sentence with four tokens and a two-token target sentence. Use arrows to show which pieces of model state contribute to each target position.

- **First 10 minutes.** Make one sketch where the decoder receives a single fixed encoder summary. Mark the path by which information from the first source token reaches the second target token.
- **Next 20 minutes.** Make another sketch where the decoder uses a different attention distribution over source positions at each target step. Use four weights that sum to one. Changing the weights for the second target step should change which source positions contribute most to its context vector.
- **Last 15 minutes.** Ask which parts of the diagram remain sequential and which parts can be computed together. Label any arrow that depends on the current decoder state.

Leave with both sketches. The comparison gives the group a concrete way to discuss what attention changed before the Transformer replaced recurrence in its encoder and decoder stacks.

## Session 3 — Check which tokens a decoder can see

Read [Attention Is All You Need](https://intelligenceatscale.ai/chapters/the-transformer-revolution) and the attention section of the [original Transformer paper](https://arxiv.org/abs/1706.03762). The collection’s [self-attention figure](diagrams/part-1-the-foundation/03-the-transformer-revolution/self-attention-example.jpg) gives the group a visual starting point.

- **First 10 minutes.** Label query positions on the rows of a 4 × 4 grid and key positions on the columns. Mark which pairs a causal mask permits.
- **Next 20 minutes.** Run the code below and compare its grid with the paper’s model description. Each `1` marks an allowed query–key pair. Count the allowed pairs and discuss why the count differs from a full grid.
- **Last 15 minutes.** Draw a second grid for eight positions. Predict its count, then modify the Python example. Explain why the count describes visibility while the model’s learned parameters determine the weights on the allowed pairs.

```python
def causal_visibility(positions):
    return [
        [int(key <= query) for key in range(positions)]
        for query in range(positions)
    ]


if __name__ == "__main__":
    positions = 4
    mask = causal_visibility(positions)
    for row in mask:
        print(" ".join(map(str, row)))
    allowed_pairs = sum(map(sum, mask))
    print(f"{allowed_pairs} of {positions ** 2} pairs are visible")
```

The four-position grid has 10 of 16 pairs visible. At eight positions, the causal grid permits 36 of 64. These counts illustrate a mask. Actual memory use and runtime depend on the attention implementation and batching.

## Bring the three sessions together

Ask each participant to submit one page with three items. The first is a measured claim and the experiment that supports it. The second is a sketch that makes a model dependency visible. The third is a small worked example whose output another reader can reproduce. Review those artifacts together before moving from the free preview to later topics.

For a class or study-group handout that uses a figure, consult the [diagram reuse and attribution guide](REUSING-DIAGRAMS.md).
