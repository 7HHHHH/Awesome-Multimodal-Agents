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
  - [Agent Learning & Optimization](#agent-learning--optimization)
  - [Vision-Language Understanding](#vision-language-understanding)
  - [Event-based Processing](#event-based-processing)
- [Tools & Libraries](#tools--libraries)
- [Tutorials & Courses](#tutorials--courses)
- [Contributing](#contributing)

## Core Concepts
- **Multimodal Understanding**: Processing and connecting information from multiple modalities
- **Agentic Behavior**: Autonomous decision-making, task completion, and environment interaction
- **Tool Augmentation**: Integration with external APIs, databases, and software tools
- **Embodied AI**: Agents operating in physical/virtual environments

## Agent Frameworks
- **LangChain**: Framework for developing applications powered by language models
- **AutoGPT**: Experimental open-source attempt to make GPT-4 fully autonomous
- **BabyAGI**: AI agent framework using language models for task management
- **MetaGPT**: Framework for building autonomous AI agents through multi-agent collaboration

## Papers

### Surveys & Overviews
| Date       | Title | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2025-04    | Safety in Large Reasoning Models: A Survey                           | arXiv          | [Paper](https://arxiv.org/pdf/2504.17704v1) | - |
| 2025-04    | Digital Twin Generation from Visual Data: A Survey                    | arXiv          | [Paper](https://arxiv.org/pdf/2504.13159v1) | [Code](https://github.com/ndrwmlnk/awesome-digital-twins) |
| 2025-04    | Hadamard Product in Deep Learning: Introduction, Advances and Challenges | arXiv       | [Paper](https://arxiv.org/pdf/2504.13112v1) | - |
| 2024-02    | Large Multimodal Agents: A Survey                                     | arXiv          | [Paper](https://arxiv.org/abs/2402.15116) | - |
| 2023-12    | A Survey on Multimodal Large Language Models                          | arXiv          | [Paper](https://arxiv.org/abs/2311.00201) | [Code](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) |
| 2023-10    | The Rise and Potential of Large Language Model Based Agents           | arXiv          | [Paper](https://arxiv.org/abs/2309.07864) | - |

### Models & Architectures
| Date       | Title                                                                 | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2025-05    | GENMO: A GENeralist Model for Human MOtion | arXiv | [Paper](http://arxiv.org/pdf/2505.01425v1) | - |
| 2025-04    | Token-Shuffle: Towards High-Resolution Image Generation with Autoregressive Models | arXiv | [Paper](http://arxiv.org/pdf/2504.17789v1) | - |
| 2024-04    |PerceptionLM: Open-Access Data and Models for Visual Understanding| arXiv| [Paper](https://arxiv.org/abs/2504.13180) | - |
| 2023-09    | GPT-4V: A Comprehensive Survey                         | arXiv          | [Paper](https://arxiv.org/abs/2311.00419) | - |
| 2023-08    | Visual Instruction Tuning                | NeurIPS        | [Paper](https://arxiv.org/abs/2304.08485) | [Code](https://github.com/haotian-liu/LLaVA) |
| 2023-07    | PaLM-E: An Embodied Multimodal Language Model                | arXiv          | [Paper](https://arxiv.org/abs/2303.03378) | - |

### Tools & Agent Learning
| Date       | Title | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2025-05    | FalconWing: An Open-Source Platform for Ultra-Light Fixed-Wing Aircraft Research | arXiv | [Paper](http://arxiv.org/pdf/2505.01383v1) | [Code](https://github.com/zhu-xlab) |
| 2025-04    | Step1X-Edit: A Practical Framework for General Image Editing          | arXiv          | [Paper](http://arxiv.org/pdf/2504.17761v1) | - |
| 2023-11    | Tool Learning with Foundation Models                                   | NeurIPS        | [Paper](https://arxiv.org/abs/2304.08354) | [Code](https://github.com/OpenBMB/ToolBench) |
| 2023-09    | Language Models as Zero-Shot Tool Learners                            | NeurIPS        | [Paper](https://arxiv.org/abs/2308.04548) | - |
| 2023-08    | Large Language Models as Tool Makers                                   | arXiv          | [Paper](https://arxiv.org/abs/2305.17126) | [Code](https://github.com/ctlllll/llm-toolmaker) |

### RAG (Retrieval-Augmented Generation)
| Date       | Title                                                                 | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2024-10    | VisRAG: Vision-based Retrieval-augmented Generation on Multi-modality Documents | ICLR | [Paper](https://arxiv.org/pdf/2410.10594) | [Code](https://github.com/openbmb/visrag)|
| 2025-05    | VDocRAG: Retrieval-Augmented Generation over Visually-Rich Documents | arXiv | [Paper](Preprint) | - |
| 2025-05    | ViDoRAG: Visual Document Retrieval-Augmented Generation via Dynamic Iterative Reasoning Agents | arXiv | [Paper](Preprint) | - |
| 2025-05    | VisDoM: Multi-Document QA with Visually Rich Elements Using Multimodal Retrieval-Augmented Generation | arXiv | [Paper](Preprint) | - |
| 2025-05    | Retrieval-Augmented Personalization for Multimodal Large Language Models | CVPR | [Paper](https://arxiv.org/abs/2410.13360) | [Code](https://github.com/Hoar012/RAP-MLLM) |
| 2025-04    | Retrieval-Augmented Generation with Conflicting Evidence             | arXiv          | [Paper](https://arxiv.org/pdf/2504.13079v1) | - |
| 2025-04    | InstructRAG: Leveraging RAG on Instruction Graphs for LLM-Based Task Planning | arXiv    | [Paper](https://arxiv.org/pdf/2504.13032v1) | - |
| 2023-12    | Self-RAG: Learning to Retrieve, Generate and Iterate                   | arXiv          | [Paper](https://arxiv.org/abs/2310.11511) | - |
| 2023-11    | In-Context Retrieval-Augmented Language Models                         | arXiv          | [Paper](https://arxiv.org/abs/2302.00083) | - |
| 2023-10    | A Survey on Retrieval-Augmented Text Generation                        | arXiv          | [Paper](https://arxiv.org/abs/2312.10997) | - |

### Agent Learning & Optimization
| Date       | Title                                                                 | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2025-05    | SIME: Enhancing Policy Self-Improvement with Modal-level Exploration | arXiv | [Paper](http://arxiv.org/pdf/2505.01396v1) | [Code](https://github.com/ericjin2002/SIME) |
| 2025-05    |Evaluating Explanations: An Explanatory Virtues Framework for Mechanistic Interpretability| arXiv | [Paper](http://arxiv.org/pdf/2505.01372v1) | - |
| 2025-04    | Conformal Segmentation in Industrial Surface Defect Detection with Statistical Guarantees | arXiv | [Paper](http://arxiv.org/pdf/2504.17721v1) | - |
| 2024-04    | Exploring Expert Failures Improves LLM Agent Tuning                   | arXiv          | [Paper](https://arxiv.org/abs/2504.13145) | - |
| 2024-04    | Sleep-time Compute: Beyond Inference Scaling at Test-time             | arXiv          | [Paper](https://arxiv.org/abs/2504.13171) | - |
| 2024-04    | It's All Connected: Test-Time Memorization and Attentional Bias       | arXiv          | [Paper](https://arxiv.org/abs/2504.13173) | - |

### Vision-Language Understanding
| Date       | Title                | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2024-04    | PerceptionLM: Open-Access Data and Models                             | arXiv          | [Paper](https://arxiv.org/abs/2504.13180) | - |
| 2024-04    | Perception Encoder: Visual Embeddings in Network Layers               | arXiv          | [Paper](https://arxiv.org/abs/2504.13181) | - |
| 2024-04    | Low-hallucination Synthetic Captions for Vision-Language Models       | arXiv          | [Paper](https://arxiv.org/abs/2504.13123) | - |
| 2024-04    | Object-Driven Narrative in AR: A Scenario-Metaphor Framework with VLM Integration | arXiv | [Paper](https://arxiv.org/abs/2504.13119) | - |

### Event-based Processing
| Date       | Title                                                                 | Venue          | Paper | Code |
|------------|-----------------------------------------------------------------------|----------------|-------|------|
| 2025-04    | Plasma State Monitoring and Disruption Characterization using Multimodal VAEs | arXiv | [Paper](http://arxiv.org/pdf/2504.17710v1) | - |
| 2024-04    | EventVAD: Training-Free Event-Aware Video Anomaly Detection           | arXiv          | [Paper](https://arxiv.org/abs/2504.13092) | - |
| 2024-04    | Novel Demonstration Generation with Gaussian Splatting                | arXiv          | [Paper](https://arxiv.org/abs/2504.13175) | - |

## Contributing
Please feel free to open a pull request to contribute! Guidelines:
- Ensure additions are high quality and relevant
- Follow the established format
- Add a brief description for new categories
