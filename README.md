# Intelligence at Scale — the diagrams

All 84 original diagrams from **[Intelligence at Scale: LLMs, Agents, and the Future of AI](https://intelligenceatscale.ai)** by Shashank Agarwal, organised by chapter, free to use under [CC BY-NC-SA 4.0](LICENSE).

Each diagram explains one idea from the book: how transformers work, what an agent actually is, why multi-agent chains break, how to evaluate and observe LLMs in production, and where the field is heading. They were drawn for the book, not scraped from papers, so they say exactly what the surrounding chapter says.

- **Use them** in talks, courses, blog posts and internal docs. Credit "Shashank Agarwal, *Intelligence at Scale*" and link back here. Non-commercial, share-alike.
- **Read the book**: Kindle, paperback and hardcover on Amazon → **[intelligenceatscale.ai/buy](https://intelligenceatscale.ai/buy)** (routes you to Amazon.in or Amazon.com). The first three chapters are free at [intelligenceatscale.ai](https://intelligenceatscale.ai).
- **Files**: 1200 px JPEGs in `diagrams/<part>/<chapter>/`, plus [`diagrams.json`](diagrams.json) with caption, chapter and path for every image. Open an issue if you need a particular diagram at full resolution.

## Contents

- Part I — The Foundation
  - [Chapter 1: How It All Started](#chapter-1-how-it-all-started) (3)
  - [Chapter 2: Before the Transformer](#chapter-2-before-the-transformer) (3)
  - [Chapter 3: Attention Is All You Need](#chapter-3-attention-is-all-you-need) (4)
  - [Chapter 4: The OpenAI Saga](#chapter-4-the-openai-saga) (3)
  - [Chapter 5: Inside the Machine](#chapter-5-inside-the-machine) (8)
  - [Chapter 6: The NVIDIA Story](#chapter-6-the-nvidia-story) (3)
  - [Chapter 7: The New Landscape](#chapter-7-the-new-landscape) (4)
- Part II — Building AI Agents
  - [Chapter 8: Prompt Engineering and Context Engineering](#chapter-8-prompt-engineering-and-context-engineering) (3)
  - [Chapter 9: What Is an Agent?](#chapter-9-what-is-an-agent) (3)
  - [Chapter 10: Building AI Agents](#chapter-10-building-ai-agents) (5)
  - [Chapter 11: Multi-Agent Systems](#chapter-11-multi-agent-systems) (3)
  - [Chapter 12: The Agent Toolbox](#chapter-12-the-agent-toolbox) (4)
- Part III — AI in the Real World
  - [Chapter 13: Production AI: Deployment, Monitoring, and Evaluation](#chapter-13-production-ai-deployment-monitoring-and-evaluation) (4)
  - [Chapter 14: The AI Landscape](#chapter-14-the-ai-landscape) (3)
  - [Chapter 15: The AI Coding Revolution](#chapter-15-the-ai-coding-revolution) (3)
  - [Chapter 16: AI and Society](#chapter-16-ai-and-society) (3)
  - [Chapter 17: The Builder's Playbook](#chapter-17-the-builders-playbook) (3)
- Part IV — Beyond Text
  - [Chapter 18: Image AI — From GANs to Diffusion](#chapter-18-image-ai--from-gans-to-diffusion) (4)
  - [Chapter 19: Voice and Music AI](#chapter-19-voice-and-music-ai) (3)
  - [Chapter 20: Video AI — The Next Frontier](#chapter-20-video-ai--the-next-frontier) (2)
- Part V — The Future
  - [Chapter 21: The Multi-Agent Future](#chapter-21-the-multi-agent-future) (6)
  - [Chapter 22: The Age of Intelligence](#chapter-22-the-age-of-intelligence) (7)

## Part I — The Foundation

### Chapter 1: How It All Started

**The Four Threads That Created AI**

![The Four Threads That Created AI](diagrams/part-1-the-foundation/01-how-it-all-started/four-threads-convergence.jpg)

**AI Research Timeline: From McCulloch-Pitts (1943) to AlexNet (2012)**

![AI Research Timeline: From McCulloch-Pitts (1943) to AlexNet (2012)](diagrams/part-1-the-foundation/01-how-it-all-started/ai-research-timeline.jpg)

**CPU vs GPU: Why AI Needs Parallel Processing**

![CPU vs GPU: Why AI Needs Parallel Processing](diagrams/part-1-the-foundation/01-how-it-all-started/cpu-vs-gpu-architecture.jpg)

### Chapter 2: Before the Transformer

**Word Embeddings: Meaning as Geometry in Vector Space**

![Word Embeddings: Meaning as Geometry in Vector Space](diagrams/part-1-the-foundation/02-before-the-transformer/word-embeddings-space.jpg)

**The Sequential Bottleneck: RNNs vs Transformers**

![The Sequential Bottleneck: RNNs vs Transformers](diagrams/part-1-the-foundation/02-before-the-transformer/sequential-bottleneck.jpg)

**Evolution of Sequence Models**

![Evolution of Sequence Models](diagrams/part-1-the-foundation/02-before-the-transformer/sequence-model-evolution.jpg)

### Chapter 3: Attention Is All You Need

**Self-Attention: How the model learns what 'it' refers to**

![Self-Attention: How the model learns what 'it' refers to](diagrams/part-1-the-foundation/03-the-transformer-revolution/self-attention-example.jpg)

**Positional Encoding: How Transformers Know Word Order**

![Positional Encoding: How Transformers Know Word Order](diagrams/part-1-the-foundation/03-the-transformer-revolution/positional-encoding.jpg)

**The Transformer Architecture**

![The Transformer Architecture](diagrams/part-1-the-foundation/03-the-transformer-revolution/transformer-architecture.jpg)

**Encoder vs Decoder: BERT sees everything, GPT predicts forward**

![Encoder vs Decoder: BERT sees everything, GPT predicts forward](diagrams/part-1-the-foundation/03-the-transformer-revolution/encoder-vs-decoder.jpg)

### Chapter 4: The OpenAI Saga

**The GPT Scaling Ladder**

![The GPT Scaling Ladder](diagrams/part-1-the-foundation/04-the-openai-saga/gpt-scaling-ladder.jpg)

**ChatGPT reached 100 million users in 2 months**

![ChatGPT reached 100 million users in 2 months](diagrams/part-1-the-foundation/04-the-openai-saga/chatgpt-growth-comparison.jpg)

**OpenAI's Structural Evolution: From nonprofit to $840B valuation**

![OpenAI's Structural Evolution: From nonprofit to $840B valuation](diagrams/part-1-the-foundation/04-the-openai-saga/openai-structural-evolution.jpg)

### Chapter 5: Inside the Machine

**From Words to Numbers: The Tokenization Pipeline**

![From Words to Numbers: The Tokenization Pipeline](diagrams/part-1-the-foundation/05-inside-the-machine/tokenization-pipeline.jpg)

**Neural Network: Inputs Flow Through Layers of Equations to Produce an Output**

![Neural Network: Inputs Flow Through Layers of Equations to Produce an Output](diagrams/part-1-the-foundation/05-inside-the-machine/neural-network-equations.jpg)

**The Forward Pass: How an LLM Processes Input Text**

![The Forward Pass: How an LLM Processes Input Text](diagrams/part-1-the-foundation/05-inside-the-machine/forward-pass.jpg)

**Neural Network Training Loop**

![Neural Network Training Loop](diagrams/part-1-the-foundation/05-inside-the-machine/training-loop.jpg)

**Matrix Multiplication Visual: How weights and inputs combine**

![Matrix Multiplication Visual: How weights and inputs combine](diagrams/part-1-the-foundation/05-inside-the-machine/matrix-multiplication-visual.jpg)

**Everything Is Matrix Multiplication**

![Everything Is Matrix Multiplication](diagrams/part-1-the-foundation/05-inside-the-machine/everything-is-matmul.jpg)

**RLHF: Teaching LLMs to Follow Instructions**

![RLHF: Teaching LLMs to Follow Instructions](diagrams/part-1-the-foundation/05-inside-the-machine/rlhf-pipeline.jpg)

**Temperature: Controlling LLM Creativity**

![Temperature: Controlling LLM Creativity](diagrams/part-1-the-foundation/05-inside-the-machine/temperature-sampling.jpg)

### Chapter 6: The NVIDIA Story

**NVIDIA's CUDA Ecosystem: The moat that competitors can't cross**

![NVIDIA's CUDA Ecosystem: The moat that competitors can't cross](diagrams/part-1-the-foundation/06-the-nvidia-story/cuda-ecosystem.jpg)

**The AI Supply Chain**

![The AI Supply Chain](diagrams/part-1-the-foundation/06-the-nvidia-story/ai-supply-chain.jpg)

**Huang's Law: 10x Hardware × 10x Software × 10x Algorithms = 1000x**

![Huang's Law: 10x Hardware × 10x Software × 10x Algorithms = 1000x](diagrams/part-1-the-foundation/06-the-nvidia-story/huangs-law.jpg)

### Chapter 7: The New Landscape

**China's AI Ecosystem: Players and Structural Advantages**

![China's AI Ecosystem: Players and Structural Advantages](diagrams/part-1-the-foundation/07-the-new-landscape/china-ai-ecosystem.jpg)

**When to Fine-Tune vs. Prompt vs. Use an SLM**

![When to Fine-Tune vs. Prompt vs. Use an SLM](diagrams/part-1-the-foundation/07-the-new-landscape/fine-tuning-decision-matrix.jpg)

**The Three Frontiers of AI Scaling**

![The Three Frontiers of AI Scaling](diagrams/part-1-the-foundation/07-the-new-landscape/three-scaling-frontiers.jpg)

**The Model Landscape in Early 2026**

![The Model Landscape in Early 2026](diagrams/part-1-the-foundation/07-the-new-landscape/model-landscape.jpg)

## Part II — Building AI Agents

### Chapter 8: Prompt Engineering and Context Engineering

**Anatomy of a Production System Prompt**

![Anatomy of a Production System Prompt](diagrams/part-2-building-agents/08-prompt-engineering/system-prompt-anatomy.jpg)

**The ReAct Loop: Thought → Action → Observation**

![The ReAct Loop: Thought → Action → Observation](diagrams/part-2-building-agents/08-prompt-engineering/react-loop.jpg)

**The Context Window as RAM: What the Model Sees**

![The Context Window as RAM: What the Model Sees](diagrams/part-2-building-agents/08-prompt-engineering/context-window-ram.jpg)

### Chapter 9: What Is an Agent?

**AI Agent Architecture**

![AI Agent Architecture](diagrams/part-2-building-agents/09-what-is-an-agent/agent-architecture.jpg)

**The RAG Pipeline: From documents to context-aware answers**

![The RAG Pipeline: From documents to context-aware answers](diagrams/part-2-building-agents/09-what-is-an-agent/rag-pipeline.jpg)

**Tool Calling: The LLM decides what to call, your code executes it**

![Tool Calling: The LLM decides what to call, your code executes it](diagrams/part-2-building-agents/09-what-is-an-agent/tool-calling-sequence.jpg)

### Chapter 10: Building AI Agents

**No-Code Workflows: Prototype vs. Production Reality**

![No-Code Workflows: Prototype vs. Production Reality](diagrams/part-2-building-agents/10-building-ai-agents/nocode-workflow-comparison.jpg)

**Agent Framework Comparison: Philosophy, Complexity, Best For**

![Agent Framework Comparison: Philosophy, Complexity, Best For](diagrams/part-2-building-agents/10-building-ai-agents/framework-comparison-table.jpg)

**Agent Memory Architecture: Short-Term and Long-Term**

![Agent Memory Architecture: Short-Term and Long-Term](diagrams/part-2-building-agents/10-building-ai-agents/memory-architecture.jpg)

**LangGraph State Machine**

![LangGraph State Machine](diagrams/part-2-building-agents/10-building-ai-agents/langgraph-state-machine.jpg)

**The Agent Loop**

![The Agent Loop](diagrams/part-2-building-agents/10-building-ai-agents/agent-loop.jpg)

### Chapter 11: Multi-Agent Systems

**Multi-Agent Patterns**

![Multi-Agent Patterns](diagrams/part-2-building-agents/11-multi-agent-systems/multi-agent-patterns.jpg)

**The Supervisor Pattern: Central Coordinator Delegates and Reviews**

![The Supervisor Pattern: Central Coordinator Delegates and Reviews](diagrams/part-2-building-agents/11-multi-agent-systems/supervisor-routing-loop.jpg)

**Chain Accuracy: The Math That Breaks Multi-Agent Systems**

![Chain Accuracy: The Math That Breaks Multi-Agent Systems](diagrams/part-2-building-agents/11-multi-agent-systems/chain-accuracy-math.jpg)

### Chapter 12: The Agent Toolbox

**Agent Communication Stack**

![Agent Communication Stack](diagrams/part-2-building-agents/12-the-agent-toolbox/agent-communication-stack.jpg)

**MCP Architecture**

![MCP Architecture](diagrams/part-2-building-agents/12-the-agent-toolbox/mcp-architecture.jpg)

**MCP vs A2A: Two protocols for two different problems**

![MCP vs A2A: Two protocols for two different problems](diagrams/part-2-building-agents/12-the-agent-toolbox/mcp-vs-a2a.jpg)

**Agent Context Window: What Fills the Mind of an Agent**

![Agent Context Window: What Fills the Mind of an Agent](diagrams/part-2-building-agents/12-the-agent-toolbox/agent-context-window.jpg)

## Part III — AI in the Real World

### Chapter 13: Production AI: Deployment, Monitoring, and Evaluation

**Production AI Architecture: From API Gateway to Observability**

![Production AI Architecture: From API Gateway to Observability](diagrams/part-3-ai-in-the-real-world/13-production-ai/production-architecture.jpg)

**The Production Rollout Playbook: Shadow Mode to Full Deployment**

![The Production Rollout Playbook: Shadow Mode to Full Deployment](diagrams/part-3-ai-in-the-real-world/13-production-ai/deployment-playbook.jpg)

**Traces and Spans: How observability works for AI agents**

![Traces and Spans: How observability works for AI agents](diagrams/part-3-ai-in-the-real-world/13-production-ai/traces-and-spans.jpg)

**Evaluation Loop**

![Evaluation Loop](diagrams/part-3-ai-in-the-real-world/13-production-ai/eval-loop.jpg)

### Chapter 14: The AI Landscape

**The AI Stack**

![The AI Stack](diagrams/part-3-ai-in-the-real-world/14-the-ai-landscape/ai-stack-layers.jpg)

**The AI Titans: Who owns hardware, models, and apps**

![The AI Titans: Who owns hardware, models, and apps](diagrams/part-3-ai-in-the-real-world/14-the-ai-landscape/ai-titans-matrix.jpg)

**The LLM Wrapper Trap: What Dies vs What Survives**

![The LLM Wrapper Trap: What Dies vs What Survives](diagrams/part-3-ai-in-the-real-world/14-the-ai-landscape/llm-wrapper-trap.jpg)

### Chapter 15: The AI Coding Revolution

**The AI Coding Evolution: From Autocomplete to Autonomous Agents**

![The AI Coding Evolution: From Autocomplete to Autonomous Agents](diagrams/part-3-ai-in-the-real-world/15-the-ai-coding-revolution/ai-coding-evolution.jpg)

**The Disciplined AI Coding Workflow**

![The Disciplined AI Coding Workflow](diagrams/part-3-ai-in-the-real-world/15-the-ai-coding-revolution/ai-coding-workflow.jpg)

**The Context Stack: How AI coding tools see your project**

![The Context Stack: How AI coding tools see your project](diagrams/part-3-ai-in-the-real-world/15-the-ai-coding-revolution/context-stack.jpg)

### Chapter 16: AI and Society

**AI Regulation: Four Approaches**

![AI Regulation: Four Approaches](diagrams/part-3-ai-in-the-real-world/16-ai-and-society/ai-regulation-comparison.jpg)

**The Training Data Legal Battle: Major AI copyright lawsuits**

![The Training Data Legal Battle: Major AI copyright lawsuits](diagrams/part-3-ai-in-the-real-world/16-ai-and-society/training-data-lawsuits.jpg)

**The Deepfake Arms Race: Generation vs Detection Asymmetry**

![The Deepfake Arms Race: Generation vs Detection Asymmetry](diagrams/part-3-ai-in-the-real-world/16-ai-and-society/deepfake-arms-race.jpg)

### Chapter 17: The Builder's Playbook

**LLM Pricing Curve**

![LLM Pricing Curve](diagrams/part-3-ai-in-the-real-world/17-the-builders-playbook/llm-pricing-curve.jpg)

**The Performance Curves: Everything Improving at Once**

![The Performance Curves: Everything Improving at Once](diagrams/part-3-ai-in-the-real-world/17-the-builders-playbook/performance-curves.jpg)

**AI-Native Team Workflow: Signal → Research → Design → Ship**

![AI-Native Team Workflow: Signal → Research → Design → Ship](diagrams/part-3-ai-in-the-real-world/17-the-builders-playbook/ai-native-team-workflow.jpg)

## Part IV — Beyond Text

### Chapter 18: Image AI — From GANs to Diffusion

**How GANs Work: Generator vs Discriminator**

![How GANs Work: Generator vs Discriminator](diagrams/part-4-beyond-text/18-image-ai/gan-architecture.jpg)

**How Diffusion Models Work**

![How Diffusion Models Work](diagrams/part-4-beyond-text/18-image-ai/diffusion-process.jpg)

**The Transformer Convergence: One Architecture for Everything**

![The Transformer Convergence: One Architecture for Everything](diagrams/part-4-beyond-text/18-image-ai/modality-convergence.jpg)

**Image AI Timeline: From GANs (2014) to native generation (2025)**

![Image AI Timeline: From GANs (2014) to native generation (2025)](diagrams/part-4-beyond-text/18-image-ai/image-ai-timeline.jpg)

### Chapter 19: Voice and Music AI

**The Voice AI Pipeline**

![The Voice AI Pipeline](diagrams/part-4-beyond-text/19-voice-and-music-ai/voice-ai-pipeline.jpg)

**Voice AI Latency Breakdown: STT + LLM + TTS + Network = ~700ms**

![Voice AI Latency Breakdown: STT + LLM + TTS + Network = ~700ms](diagrams/part-4-beyond-text/19-voice-and-music-ai/voice-ai-latency.jpg)

**Music AI: How Text Becomes Sound**

![Music AI: How Text Becomes Sound](diagrams/part-4-beyond-text/19-voice-and-music-ai/music-ai-architecture.jpg)

### Chapter 20: Video AI — The Next Frontier

**Video AI: The declining cost curve from Sora to real-time generation**

![Video AI: The declining cost curve from Sora to real-time generation](diagrams/part-4-beyond-text/20-video-ai/video-ai-cost-curve.jpg)

**How Video AI Generation Works**

![How Video AI Generation Works](diagrams/part-4-beyond-text/20-video-ai/video-dit-architecture.jpg)

## Part V — The Future

### Chapter 21: The Multi-Agent Future

**Enterprise Multi-Agent Architecture**

![Enterprise Multi-Agent Architecture](diagrams/part-5-the-future/21-multi-agent-future/enterprise-agent-clusters.jpg)

**The AI Company Org Chart: 1 human + 6 agents = a functioning company**

![The AI Company Org Chart: 1 human + 6 agents = a functioning company](diagrams/part-5-the-future/21-multi-agent-future/ai-company-org-chart.jpg)

**Agent Spawning Hierarchy: Supervisors creating specialists on demand**

![Agent Spawning Hierarchy: Supervisors creating specialists on demand](diagrams/part-5-the-future/21-multi-agent-future/agent-spawning-hierarchy.jpg)

**The AI Security Arms Race: Offensive vs Defensive AI**

![The AI Security Arms Race: Offensive vs Defensive AI](diagrams/part-5-the-future/21-multi-agent-future/security-arms-race.jpg)

**The Autonomy Spectrum**

![The Autonomy Spectrum](diagrams/part-5-the-future/21-multi-agent-future/autonomy-spectrum.jpg)

**OpenClaw Architecture: Gateway server with agent loop, file-based memory, and spawned sub-agents**

![OpenClaw Architecture: Gateway server with agent loop, file-based memory, and spawned sub-agents](diagrams/part-5-the-future/21-multi-agent-future/openclaw-architecture.jpg)

### Chapter 22: The Age of Intelligence

**AGI: The Definition Matters More Than the Timeline**

![AGI: The Definition Matters More Than the Timeline](diagrams/part-5-the-future/22-the-age-of-intelligence/agi-definitions.jpg)

**AGI Predictions: Expert Timeline**

![AGI Predictions: Expert Timeline](diagrams/part-5-the-future/22-the-age-of-intelligence/agi-timeline.jpg)

**Quadratic vs Linear Scaling: Why transformers struggle with long sequences**

![Quadratic vs Linear Scaling: Why transformers struggle with long sequences](diagrams/part-5-the-future/22-the-age-of-intelligence/quadratic-vs-linear-scaling.jpg)

**Beyond the Transformer: Competing Architectures**

![Beyond the Transformer: Competing Architectures](diagrams/part-5-the-future/22-the-age-of-intelligence/architecture-comparison.jpg)

**Technology Waves: Every major disruption created more jobs than it destroyed**

![Technology Waves: Every major disruption created more jobs than it destroyed](diagrams/part-5-the-future/22-the-age-of-intelligence/technology-waves.jpg)

**The Abundance Cascade: How AI and Robotics Drive Costs Toward Zero**

![The Abundance Cascade: How AI and Robotics Drive Costs Toward Zero](diagrams/part-5-the-future/22-the-age-of-intelligence/abundance-cascade.jpg)

**Intelligence as a Utility: From Privilege to Universal Access**

![Intelligence as a Utility: From Privilege to Universal Access](diagrams/part-5-the-future/22-the-age-of-intelligence/intelligence-as-utility.jpg)

## About the author

[Shashank Agarwal](https://www.linkedin.com/in/shashankagarwal2/) was on the original AWS SageMaker launch team, built ML-powered personalisation at Amazon Prime Video, and now runs [Noveum AI](https://noveum.ai) (AI agent observability and evaluation) and [api.market](https://api.market). He is based in Bengaluru.

## License

Diagrams © 2026 Shashank Agarwal, released under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). The book text is not included here and remains all rights reserved.
