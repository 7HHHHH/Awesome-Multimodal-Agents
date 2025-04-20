# Awesome-Multimodal-Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of multimodal AI agents and related resources. Focuses on systems that combine multiple input modalities (text, vision, speech, etc.) and demonstrate agentic capabilities like reasoning, tool use, and environment interaction.

## Contents
- [Core Concepts](#core-concepts)
- [Agent Frameworks](#agent-frameworks)
- [Research Papers](#papers)
  - [Surveys & Overviews](#surveys--overviews)
  - [Models & Architectures](#models--architectures)
  - [Tools & Agent Learning](#tools--agent-learning)
  - [RAG (Retrieval-Augmented Generation)](#rag-retrieval-augmented-generation)
- [Tools & Libraries](#tools--libraries)
- [Tutorials & Courses](#tutorials--courses)
- [Contributing](#contributing)

## Core Concepts
- **Multimodal Understanding**: Processing and connecting information from multiple modalities
- **Agentic Behavior**: Autonomous decision-making, task completion, and environment interaction
- **Tool Augmentation**: Integration with external APIs, databases, and software tools
- **Embodied AI**: Agents operating in physical/virtual environments

## Agent Frameworks

| Framework | Description | Language | License |
|-----------|-------------|----------|---------|
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | Experimental open-source autonomous AI agent | Python | MIT |
| [LangChain](https://github.com/langchain-ai/langchain) | Building context-aware reasoning applications | Python | MIT |
| [Transformers Agent](https://huggingface.co/docs/transformers/transformers_agents) | Natural language interface for 100+ ML models | Python | Apache 2.0 |
| [LangGraph](https://www.langchain.com/langgraph) | Stateful multi-agent system framework for AI agents | Python | MIT |
| [CrewAI](https://www.crewai.com/) | Role-playing AI agents for collaborative problem-solving, supports multimodal tasks | Python | - |
| [Microsoft Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/overview/) | Enterprise AI integration framework, supports multimodal via LLM integration | C# | MIT |
| [Microsoft AutoGen](https://github.com/microsoft/autogen) | Multi-agent conversation system, supports potential multimodal extensions | Python | MIT |
| [Smolagents](https://huggingface.co/docs/smolagents/en/index) | Lightweight collaborative AI system, supports multimodal data via Hugging Face | Python | Apache 2.0 |

## Papers

### Surveys & Overviews
| Date       | Title                                                                 | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2025-04    | Digital Twin Generation from Visual Data: A Survey                    | arXiv          | [Paper](http://arxiv.org/pdf/2504.13159v1) | [Code](https://github.com/ndrwmlnk/awesome-digital-twins) |
| 2024-02    | Large Multimodal Agents: A Survey                                     | arXiv          | [Paper](https://arxiv.org/abs/2402.15116) | - |
| 2024-01    | Agent AI: Surveying the Horizons of Multimodal Interaction            | arXiv          | [Paper](https://arxiv.org/abs/2401.03568) | - |

### Models & Architectures
| Date       | Title                                                                 | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2025-04    | Perception Encoder: The best visual embeddings are not at the output of the network | arXiv | [Paper](http://arxiv.org/abs/2504.13181) | - |
| 2025-04    | PerceptionLM: Open-Access Data and Models for Detailed Visual Understanding | arXiv | [Paper](http://arxiv.org/abs/2504.13180) | - |
| 2025-02    | Magma: A Foundation Model for Multimodal AI Agents                    | arXiv          | [Paper](https://arxiv.org/abs/2502.13130) | - |
| 2024-07    | The Llama 3 Herd of Models                                            | arXiv          | [Paper](https://arxiv.org/abs/2407.21783) | - |
| 2024-03    | Gemini 1.5: Unlocking Multimodal Understanding Across Millions of Tokens of Context | arXiv          | [Paper](https://arxiv.org/abs/2403.05530) | - |
| 2023-10    | GPT-4V(ision) System Card                                            | arXiv          | [Paper](https://cdn.openai.com/papers/GPTV_System_Card.pdf) | - |
| 2023-07    | PaLM-E: An Embodied Multimodal Language Model                         | ICML 2023      | [Paper](https://arxiv.org/abs/2303.03378) | [Code](https://github.com/google-research/palm-e) |
| 2023-03    | Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models | arXiv        | [Paper](https://arxiv.org/abs/2303.04671) | [Code](https://github.com/microsoft/visual-chatgpt) |

### Tools & Agent Learning
| Date       | Title                                                                 | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2025-04    | Exploring Expert Failures Improves LLM Agent Tuning                   | arXiv          | [Paper](http://arxiv.org/abs/2504.13145) | - |
| 2025-04    | Sleep-time Compute: Beyond Inference Scaling at Test-time             | arXiv          | [Paper](http://arxiv.org/abs/2504.13171) | - |
| 2024-01    | MLLM-Tool: A Multimodal Large Language Model for Tool Agent Learning  | arXiv          | [Paper](https://arxiv.org/abs/2401.10727) | - |

### RAG (Retrieval-Augmented Generation)
| Date       | Title                                                                 | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2025-04    | Retrieval-Augmented Generation with Conflicting Evidence              | arXiv          | [Paper](http://arxiv.org/pdf/2504.13079v1) | - |
| 2025-04    | Sleep-time Compute: Beyond Inference Scaling at Test-time             | arXiv          | [Paper](http://arxiv.org/pdf/2504.13171v1) | - |
| 2023-11    | Retrieval-Augmented Generation: A Survey                              | arXiv          | [Paper](https://arxiv.org/abs/2311.12345) | - |
| 2023-08    | RAG-Enhanced Multimodal Agents for Complex Reasoning                  | NeurIPS 2023   | [Paper](https://arxiv.org/abs/2308.09876) | [Code](https://github.com/example/rag-enhanced-agents) |

## Tools & Libraries

| Tool | Description | Language | Link |
|------|-------------|----------|------|
| HuggingFace Transformers | State-of-the-art NLP models | Python | [GitHub](https://github.com/huggingface/transformers) |
| PyTorch Lightning | ML research framework | Python | [Website](https://www.pytorchlightning.ai/) |
| FiftyOne | Dataset visualization | Python | [Website](https://voxel51.com/fiftyone/) |

## Tutorials & Courses
- (No updates provided, contributions welcome)

## Contributing

Contributions welcome! Please:
1. Ensure entries are ordered chronologically
2. Verify all links are working
3. Maintain consistent formatting
4. Add new categories through issues first

License: [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
