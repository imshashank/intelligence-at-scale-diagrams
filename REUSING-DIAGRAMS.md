# Reusing the Intelligence at Scale diagrams

This collection includes 84 diagrams by [Shashank Agarwal](https://www.linkedin.com/in/shashankagarwal2/). The book’s chapters explain the concepts in context. The diagrams are available for noncommercial teaching materials and other uses permitted by their Creative Commons license. [Browse the original collection](README.md) · [Read the book preview](https://intelligenceatscale.ai/chapters)

## Find a figure that fits the lesson

| Teaching goal | Original figure | Suggested context |
| --- | --- | --- |
| Show how tokens relate to one another | [Self-attention example](diagrams/part-1-the-foundation/03-the-transformer-revolution/self-attention-example.jpg) | Give students a sentence with an ambiguous pronoun. Ask them what context would change its interpretation. |
| Explain how a transformer represents word order | [Positional encoding](diagrams/part-1-the-foundation/03-the-transformer-revolution/positional-encoding.jpg) | Compare two sentences that contain the same words in a different order. |
| Compare model families | [Encoder vs. decoder](diagrams/part-1-the-foundation/03-the-transformer-revolution/encoder-vs-decoder.jpg) | Contrast which tokens each side can attend to when reading or generating a sequence. |

Chapter 3 gives the original explanations and several related diagrams. [Attention Is All You Need](https://intelligenceatscale.ai/chapters/the-transformer-revolution)

## Credit a figure next to the image

Save [the self-attention figure](diagrams/part-1-the-foundation/03-the-transformer-revolution/self-attention-example.jpg) as `self-attention-example.jpg` beside your lesson’s HTML file. This example adds a caption with the creator, original file, and license. Update the alternate text and surrounding explanation to reflect what your lesson draws from the diagram.

```html
<figure>
  <img
    src="self-attention-example.jpg"
    alt="A self-attention example linking an ambiguous pronoun to earlier words."
  >
  <figcaption>
    <a href="https://github.com/imshashank/intelligence-at-scale-diagrams/blob/main/diagrams/part-1-the-foundation/03-the-transformer-revolution/self-attention-example.jpg">Self-attention example</a>
    from <cite>Intelligence at Scale</cite>, © 2026 Shashank Agarwal.
    <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a>.
  </figcaption>
</figure>
```

Include a sentence near the image that explains the relationship students should notice. For a denser figure, provide a longer equivalent explanation in the lesson itself. [W3C guidance on complex images](https://www.w3.org/WAI/tutorials/images/complex/)

If you crop, translate, or annotate a diagram, identify the change beside the original credit. Keep the attribution and license link when sharing the figure, and apply the same or a Creative Commons-compatible license to adaptations you distribute. The collection’s license covers the diagrams in this repository. [Creative Commons deed](https://creativecommons.org/licenses/by-nc-sa/4.0/) · [Full legal code](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en)
