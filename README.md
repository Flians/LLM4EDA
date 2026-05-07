# LLM4EDA: Large Language Models for Electronic Design Automation

A curated collection of papers on applying Large Language Models (LLMs) to Electronic Design Automation (EDA), organized by research topic and year.

## Table of Contents

- [LLM4EDA: Large Language Models for Electronic Design Automation](#llm4eda-large-language-models-for-electronic-design-automation)
  - [Table of Contents](#table-of-contents)
  - [RTL \& Verilog Code Generation](#rtl--verilog-code-generation)
  - [EDA Agents \& Automation Frameworks](#eda-agents--automation-frameworks)
  - [Analog Circuit Design](#analog-circuit-design)
  - [Verification, Debugging \& Testing](#verification-debugging--testing)
  - [Physical Design](#physical-design)
  - [High-Level Synthesis (HLS)](#high-level-synthesis-hls)
  - [Logic Synthesis](#logic-synthesis)
  - [Security, Trust \& IP Protection](#security-trust--ip-protection)
  - [Hardware Accelerator \& Chip Design](#hardware-accelerator--chip-design)
  - [Surveys, Benchmarks \& Evaluations](#surveys-benchmarks--evaluations)
  - [Abbreviations](#abbreviations)
  - [Contributing](#contributing)

---

## RTL & Verilog Code Generation

| Paper | Venue | Year |
|-------|-------|------|
| VerilogEval: Evaluating Large Language Models for Verilog Code Generation | arXiv | 2023 |
| ChipGPT: How far are we from natural language hardware design | arXiv | 2023 |
| VeriGen: A Large Language Model for Verilog Code Generation | arXiv | 2023 |
| RTLCoder: Outperforming GPT-3.5 in Design RTL Generation with Our Open-Source Dataset and Lightweight Solution | arXiv | 2023 |
| RTLLM: An Open-Source Benchmark for Design RTL Generation with Large Language Model | ICCAD | 2023 |
| AutoChip: Automating HDL Generation Using LLM Feedback | arXiv | 2023 |
| CodeV: Empowering LLMs for Verilog Generation through Multi-Level Summarization | arXiv | 2024 |
| BetterV: Controlled Verilog Generation with Discriminative Guidance | ICML | 2024 |
| Zero-Shot RTL Code Generation with Attention Sink Augmented Large Language Models | arXiv | 2024 |
| From English to ASIC Hardware Implementation with Large Language Model | arXiv | 2024 |
| SpecLLM: Exploring Generation and Review of VLSI Design Specification with Large Language Model | arXiv | 2024 |
| CraftRTL: High-quality Synthetic Data Generation for Verilog Code Models with Correct-by-Construction Non-Textual Representations and Targeted Code Repair | arXiv | 2024 |
| Make Every Move Count: LLM-based High-Quality RTL Code Generation Using MCTS | arXiv | 2024 |
| RTLFixer: Automatically Fixing RTL Syntax Errors with Large Language Models | DAC | 2024 |
| Data is all you need: Finetuning LLMs for Chip Design via an Automated design-data augmentation framework | DAC | 2024 |
| Spec2RTL-Agent: Automated Hardware Code Generation from Complex Specifications Using LLM Agent Systems | arXiv | 2025 |
| ScaleRTL: Scaling LLMs with reasoning data and test-time compute for accurate RTL code generation | arXiv | 2025 |
| CodeV-R1: Reasoning-Enhanced Verilog Generation | arXiv | 2025 |
| ComplexVCoder: An LLM-Driven Framework for Systematic Generation of Complex Verilog Code | arXiv | 2025 |
| VeriCoder: Enhancing LLM-Based RTL Code Generation through Functional Correctness Validation | arXiv | 2025 |
| Free and fair hardware: A pathway to copyright infringement-free verilog generation using LLMs | arXiv | 2025 |
| A data-centric chip design agent framework for verilog code generation | TODAES | 2025 |
| ChipSeek-R1: Generating Human-Surpassing RTL with LLM via Hierarchical Reward-Driven Reinforcement Learning | arXiv | 2025 |
| Insights from Verification: Training a Verilog Generation LLM with Reinforcement Learning with Testbench Feedback | arXiv | 2025 |
| BugGen: A Self-Correcting Multi-Agent LLM Pipeline for Realistic RTL Bug Synthesis | arXiv | 2025 |
| VeriOpt: PPA-Aware High-Quality Verilog Generation via Multi-Role LLMs | arXiv | 2025 |
| RTL++: Graph-enhanced LLM for RTL Code Generation | arXiv | 2025 |
| VFlow: Discovering Optimal Agentic Workflows for Verilog Generation | arXiv | 2025 |
| ChipSeek: Optimizing Verilog Generation via EDA-Integrated Reinforcement Learning | arXiv | 2025 |
| DeepRTL2: A Versatile Model for RTL-Related Tasks | arXiv | 2025 |
| Chain-of-Descriptions: Improving Code LLMs for VHDL Code Generation and Summarization | arXiv | 2025 |
| QiMeng-CRUX: Narrowing the Gap between Natural Language and Verilog via Core Refined Understanding eXpression | arXiv | 2025 |

## EDA Agents & Automation Frameworks

| Paper | Venue | Year |
|-------|-------|------|
| ChatEDA: A Large Language Model Powered Autonomous Agent for EDA | MLCAD | 2023 |
| ChatEDA: A Large Language Model Powered Autonomous Agent for EDA | TCAD | 2024 |
| Divergent Thoughts toward One Goal: LLM-based Multi-Agent Collaboration System for Electronic Design Automation | NAACL | 2025 |
| Automated Multi-Agent Workflows for RTL Design | NeurPS | 2025 |
| JARVIS: A multi-agent code assistant for high-quality EDA script generation | arXiv | 2025 |
| AutoEDA: Enabling EDA Flow Automation through Microservice-Based LLM Agents | arXiv | 2025 |
| EDA-Copilot: A RAG-Powered Intelligent Assistant for EDA Tools | TODAES | 2025 |
| Large Language Models for EDA: From Assistants to Agents | Foundations and Trends in EDA | 2025 |
| ModelGen: Automating semiconductor parameter extraction with large language model agents | TODASE | 2025 |
| MCP4EDA: LLM-Powered Model Context Protocol RTL-to-GDSII Automation with Backend Aware Synthesis Optimization | arXiv | 2025 |
| DUET: Agentic Design Understanding via Experimentation and Testing | arXiv | 2025 |

## Analog Circuit Design

| Paper | Venue | Year |
|-------|-------|------|
| Chip-Chat: Challenges and Opportunities in Conversational Hardware Design | MLCAD | 2023 |
| LaMAGIC: Language-Model-Based Topology Generation for Analog Integrated Circuits | ICML | 2024 |
| AnalogCoder: Analog Circuit Design via Training-Free Code Generation | arXiv | 2024 |
| LADAC: Large Language Model-driven Auto-Designer for Analog Circuits | TechRxiv | 2024 |
| ADO-LLM: Analog Design Bayesian Optimization with In-Context Learning of Large Language Models | arXiv | 2024 |
| Human Language to Analog Layout Using GLayout Layout Automation Framework | MLCAD | 2024 |
| Atelier: An Automated Analog Circuit Design Framework via Multiple Large Language Model-based Agents | TechRxiv | 2024 |
| AnalogXpert: Automating Analog Topology Synthesis by Incorporating Circuit Design Expertise into Large Language Models | arXiv | 2024 |
| Artisan: Automated Operational Amplifier Design via Domain-specific Large Language Model | DAC | 2024 |
| AMSnet-KG: A Netlist Dataset for LLM-based AMS Circuit Auto-Design Using Knowledge Graph RAG | arXiv | 2024 |
| DocEDA: Automated Extraction and Design of Analog Circuits from Documents with Large Language Model | arXiv | 2024 |
| CircuitSynth: Leveraging Large Language Models for Circuit Topology Synthesis | LAD | 2024 |
| LLM-Enhanced Bayesian Optimization for Efficient Analog Layout Constraint Generation | arXiv | 2024 |
| LayoutCopilot: An LLM-Powered Multi-Agent Collaborative Framework for Interactive Analog Layout Design | TCAD | 2025 |
| AnalogCoder-Pro: Unifying Analog Circuit Generation and Optimization via Multi-modal LLMs | arXiv | 2025 |
| LLM-IMC: Automating analog in-memory computing architecture generation with large language models | FCCM | 2025 |
| AUTOCIRCUIT-RL: Reinforcement Learning-Driven LLM for Automated Circuit Topology Generation | ICML | 2025 |

## Verification, Debugging & Testing

| Paper | Venue | Year |
|-------|-------|------|
| ConfiBench: Automatic Testbench Generation with Confidence-Based Scenario Mask and Testbench Ensemble using LLMs for HDL Design | MLCAD | 2024 |
| Domain-Adapted LLMs for VLSI Design and Verification: A Case Study on Formal Verification | VTS | 2024 |
| LLM-assisted Generation of Hardware Assertions | arXiv | 2023 |
| Using LLMs to Facilitate Formal Verification of RTL | arXiv | 2024 |
| AssertLLM: Generating and Evaluating Hardware Verification Assertions from Design Specifications via Multi-LLMs | arXiv | 2024 |
| LLM-Aided Testbench Generation and Bug Detection for Finite-State Machines | arXiv | 2024 |
| VeriDebug: A Unified LLM for Verilog Debugging via Contrastive Embedding and Guided Correction | arXiv | 2025 |
| From Concept to Practice: an Automated LLM-aided UVM Machine for RTL Verification | arXiv | 2025 |
| LLM-assisted Bug Identification and Correction for Verilog HDL | TODASE | 2025 |
| MARVEL: Multi-agent RTL vulnerability extraction using large language models | arXiv | 2025 |

## Physical Design

| Paper | Venue | Year |
|-------|-------|------|
| Large Language Model (LLM) for Standard Cell Layout Design Optimization | LAD | 2024 |
| HyperPlace: Harnessing a Large Language Model for Efficient Hyperparameter Optimization in GPU-Accelerated VLSI Placement | TODASE | 2025 |
| Evolution of Optimization Algorithms for Global Placement via Large Language Models | arXiv | 2025 |
| LEGALM 2.0: A Versatile Augmented Lagrangian Method-Based Methodology for Mixed-Cell-Height Legalization | TCAD | 2025 |
| LLM-Enhanced GPU-Optimized Physical Design at Scale | ICCAD | 2025 |
| ChatPattern: Layout Pattern Customization via Natural Language | arXiv | 2024 |

## High-Level Synthesis (HLS)

| Paper | Venue | Year |
|-------|-------|------|
| HLSPilot: LLM-based High-Level Synthesis | ICCAD | 2024 |
| SynthAI: A Multi Agent Generative AI Framework for Automated Modular HLS Design Generation | arXiv | 2024 |
| Hierarchical mixture of experts: Generalizable learning for high-level synthesis | AAAI | 2025 |

## Logic Synthesis

| Paper | Venue | Year |
|-------|-------|------|
| GenEDA: Unleashing Generative Reasoning on Netlist via Multimodal Encoder-Decoder Aligned Foundation Model | arXiv | 2025 |

## Security, Trust & IP Protection

| Paper | Venue | Year |
|-------|-------|------|
| NETLAM: An Automated LLM Framework to Generate and Evaluate Stealthy Hardware Trojans | arXiv | 2025 |
| RTLMarker: Protecting LLM-Generated RTL Copyright via a Hardware Watermarking Framework | ASPDAC | 2025 |
| VeriLeaky: Navigating IP protection vs utility in fine-tuning for LLM-driven verilog coding | arXiv | 2025 |
| SALAD: Systematic assessment of machine unlearning on LLM-aided hardware design | arXiv | 2025 |
| LLM4SecHW: Leveraging Domain-Specific Large Language Model for Hardware Debugging | arXiv | 2023 |
| LLMs for Hardware Security: Boon or Bane? | arXiv | 2024 |

## Hardware Accelerator & Chip Design

| Paper | Venue | Year |
|-------|-------|------|
| GPT4AIGChip: Towards Next-Generation AI Accelerator Design Automation via Large Language Models | ICCAD | 2023 |
| ChatCPU: An Agile CPU Design and Verification Platform with LLM | DAC | 2024 |
| ChipNeMo: Domain-Adapted LLMs for Chip Design | arXiv | 2024 |
| An Agile Framework for Efficient LLM Accelerator Development and Model Inference | ICCAD | 2024 |
| The Survey of Chiplet-based Integrated Architecture: An EDA perspective | ASPDAC | 2024 |
| ChipMind: LLMs for Agile Chip Design | VTS | 2025 |
| TPU-Gen: LLM-Driven Custom Tensor Processing Unit Generator | arXiv | 2025 |
| Autocomp: LLM-driven code optimization for tensor accelerators | arXiv | 2025 |
| QiMeng: Fully Automated Hardware and Software Design for Processor Chip | arXiv | 2025 |
| QiMeng-GEMM: Automatically Generating High-Performance Matrix Multiplication Code by Exploiting Large Language Models | AAAI | 2025 |
| QiMeng-Attention: SOTA Attention Operator is generated by SOTA Attention Algorithm | ACL | 2025 |
| QiMeng-TensorOp: One-Line Prompt is Enough for High-Performance Tensor Operator Generation with Hardware Primitives | IJCAI | 2025 |
| Large Processor Chip Model | SCIS | 2025 |
| LLMShare: Optimizing LLM Inference Serving with Hardware Architecture Exploration | DAC | 2025 |
| QiMeng-CPU-v2: Automated Superscalar Processor Design by Learning Data Dependencies | IJCAI | 2025 |

## Surveys, Benchmarks & Evaluations

| Paper | Venue | Year |
|-------|-------|------|
| LLM4EDA: Emerging Progress in Large Language Models for Electronic Design Automation | arXiv | 2023 |
| Large Language Models for EDA: Future or Mirage? | ISPD | 2024 |
| The Dawn of AI-Native EDA: Promises and Challenges of Large Circuit Models | arXiv | 2024 |
| A Survey of Research in Large Language Models for Electronic Design Automation | TODAES | 2025 |
| Revisiting VerilogEval: A Year of Improvements in Large-Language Models for Hardware Code Generation | TODAES | 2025 |
| Large circuit models: opportunities and challenges | SCIS | 2024 |
| RocketPPA: Ultra-fast LLM-based PPA estimator at code-level abstraction | arXiv | 2025 |
| HeuriGym: An agentic benchmark for LLM-crafted heuristics in combinatorial optimization | arXiv | 2025 |
| OpenLLM-RTL: Open Dataset and Benchmark for LLM-Aided Design RTL Generation | - | 2024 |
| Customized Retrieval Augmented Generation and Benchmarking for EDA Tool Documentation QA | ICCAD | 2024 |
| Benchmarking Large Language Models for Automated Verilog RTL Code Generation | arXiv | 2023 |
| CreativEval: Evaluating Creativity of LLM-Based Hardware Code Generation | arXiv | 2024 |
| Evaluating LLMs for Hardware Design and Test | arXiv | 2024 |
| TuRTLe: A Unified Evaluation of LLMs for RTL Generation | arXiv | 2025 |
| Large Language Model for Verilog Code Generation: Literature Review and the Road Ahead | arXiv | 2025 |
| SLDB: An End-To-End Heterogeneous System-on-Chip Benchmark Suite for LLM-Aided Design | arXiv | 2025 |

## Miscellaneous

| Paper | Venue | Year |
|-------|-------|------|
| CodeI/O: Condensing Reasoning Patterns via Code Input-Output Prediction | arXiv | 2025 |
| SchemaCoder: Automatic log schema extraction coder with residual Q-tree boosting | arXiv | 2025 |
| EDA Corpus: A Large Language Model Dataset for Enhanced Interaction with OpenROAD | arXiv | 2024 |

## Related Resources

- [Awesome-LLM4EDA](https://github.com/Thinklab-SJTU/Awesome-LLM4EDA) — A comprehensive collection of LLM4EDA papers by ThinkLab SJTU
- [QiMeng Project](https://qimeng-ict.github.io/) — Automated hardware/software co-design using LLMs

## Abbreviations

| Abbreviation | Full Name |
|-------------|-----------|
| DAC | Design Automation Conference |
| ICCAD | International Conference on Computer-Aided Design |
| ICML | International Conference on Machine Learning |
| AAAI | AAAI Conference on Artificial Intelligence |
| ACL | Association for Computational Linguistics |
| NAACL | North American Chapter of the ACL |
| IJCAI | International Joint Conference on Artificial Intelligence |
| ASPDAC | Asia and South Pacific Design Automation Conference |
| ISPD | International Symposium on Physical Design |
| FCCM | IEEE Symposium on Field-Programmable Custom Computing Machines |
| MLCAD | Machine Learning for CAD |
| LAD | Workshop on Logic and Architecture Design |
| VTS | IEEE VLSI Test Symposium |
| NeurPS | Neural Processing Systems (workshop) |
| TODAES | ACM Transactions on Design Automation of Electronic Systems |
| TODASE | ACM Transactions on Design Automation of Electronic Systems |
| TCAD | IEEE Transactions on Computer-Aided Design |
| SCIS | Science China Information Sciences |

## Contributing

Feel free to submit PRs to add new papers or improve categorization. Please keep entries consistent with the existing format: paper title, venue, year.

---

*Last updated: 2026-05*
