# LLM4EDA: Large Language Models for Electronic Design Automation

A curated collection of papers on applying Large Language Models (LLMs) to Electronic Design Automation (EDA), organized by research topic and year.

## Table of Contents

- [LLM4EDA: Large Language Models for Electronic Design Automation](#llm4eda-large-language-models-for-electronic-design-automation)
  - [Table of Contents](#table-of-contents)
  - [RTL \& Verilog Code Generation](#rtl--verilog-code-generation)
  - [Verification, Debugging \& Testing](#verification-debugging--testing)
  - [High-Level Synthesis (HLS)](#high-level-synthesis-hls)
  - [Logic Synthesis](#logic-synthesis)
  - [Physical Design](#physical-design)
  - [Analog Circuit Design](#analog-circuit-design)
  - [Agentic Design Automation](#agentic-design-automation)
  - [Security, Trust \& IP Protection](#security-trust--ip-protection)
  - [Hardware Accelerator \& Chip Design](#hardware-accelerator--chip-design)
  - [Surveys, Benchmarks \& Evaluations](#surveys-benchmarks--evaluations)
  - [Abbreviations](#abbreviations)
  - [Contributing](#contributing)

---

## RTL & Verilog Code Generation

| Paper | Affiliation | Venue | Year |
|-------|-------------|-------|------|
| HDLFORGE: A two-stage multi-agent framework for efficient verilog code generation | USC | arXiv | 2026 |
| AutoVeriFix+: High-correctness RTL generation via trace-aware causal fix and verification | HKUST(GZ) | arXiv | 2026 |
| Dr. RTL: Autonomous Agentic RTL Optimization through Tool-Grounded Self-Improvement | HKUST | arXiv | 2026 |
| ChipCraftBrain: Validation-First RTL Generation via Multi-Agent Orchestration | ChipCraftX | arXiv | 2026 |
| MGEMMV: A multimodal LLM framework for GEMM verilog generation from circuit diagrams | NJU | IEEE TCAS-I | 2026 |
| Spec2RTL-Agent: Automated Hardware Code Generation from Complex Specifications Using LLM Agent Systems | NVIDIA | arXiv | 2025 |
| ScaleRTL: Scaling LLMs with reasoning data and test-time compute for accurate RTL code generation | NVIDIA | arXiv | 2025 |
| QiMeng-CodeV-R1: Reasoning-Enhanced Verilog Generation | ICT-CAS | NeurIPS | 2025 |
| ComplexVCoder: An LLM-Driven Framework for Systematic Generation of Complex Verilog Code | Shandong Univ | arXiv | 2025 |
| VeriCoder: Enhancing LLM-Based RTL Code Generation through Functional Correctness Validation | Stanford | arXiv | 2025 |
| Free and fair hardware: A pathway to copyright infringement-free verilog generation using LLMs | TAMU | arXiv | 2025 |
| A data-centric chip design agent framework for verilog code generation | ICT-CAS | TODAES | 2025 |
| ChipSeek-R1: Generating Human-Surpassing RTL with LLM via Hierarchical Reward-Driven Reinforcement Learning | ICT-CAS | arXiv | 2025 |
| VeriOpt: PPA-Aware High-Quality Verilog Generation via Multi-Role LLMs | UCF | ICCAD | 2025 |
| RTL++: Graph-enhanced LLM for RTL Code Generation | UCF | arXiv | 2025 |
| VFlow: Discovering Optimal Agentic Workflows for Verilog Generation | SJTU | arXiv | 2025 |
| ChipSeek: Optimizing Verilog Generation via EDA-Integrated Reinforcement Learning | ICT-CAS | arXiv | 2025 |
| DeepRTL2: A Versatile Model for RTL-Related Tasks | CUHK | ACL Findings | 2025 |
| Chain-of-Descriptions: Improving Code LLMs for VHDL Code Generation and Summarization | IBM | arXiv | 2025 |
| QiMeng-CRUX: Narrowing the Gap between Natural Language and Verilog via Core Refined Understanding eXpression | ICT-CAS | AAAI | 2026 |
| HDLCoRe: A training-free framework for mitigating hallucinations in LLM-generated HDL code | USC | arXiv | 2025 |
| Veritas: Deterministic verilog code synthesis from LLM-generated conjunctive specifications | NYU | arXiv | 2025 |
| OpenRTLSet: A fully open-source dataset for large language model-based verilog code generation | UIUC | ICLAD | 2025 |
| A2HCoder: An LLM-driven coding agent for hierarchical algorithm-to-HDL translation | UTS | arXiv | 2025 |
| Data is all you need: Finetuning LLMs for Chip Design via an Automated design-data augmentation framework | ICT-CAS | DAC | 2024 |
| CodeV: Empowering LLMs for Verilog Generation through Multi-Level Summarization | ShanghaiTech | arXiv | 2024 |
| BetterV: Controlled Verilog Generation with Discriminative Guidance | CUHK | ICML | 2024 |
| Zero-Shot RTL Code Generation with Attention Sink Augmented Large Language Models | Ozyegin Univ | arXiv | 2024 |
| From English to ASIC Hardware Implementation with Large Language Model | SUTD | arXiv | 2024 |
| SpecLLM: Exploring Generation and Review of VLSI Design Specification with Large Language Model | HKUST | arXiv | 2024 |
| CraftRTL: High-quality Synthetic Data Generation for Verilog Code Models with Correct-by-Construction Non-Textual Representations and Targeted Code Repair | NVIDIA | arXiv | 2024 |
| Make Every Move Count: LLM-based High-Quality RTL Code Generation Using MCTS | TAMU | arXiv | 2024 |
| ChipGPT: How far are we from natural language hardware design | ICT-CAS | arXiv | 2023 |
| VeriGen: A Large Language Model for Verilog Code Generation | NYU | TODAES | 2024 |
| RTLCoder: Outperforming GPT-3.5 in Design RTL Generation with Our Open-Source Dataset and Lightweight Solution | HKUST | arXiv | 2023 |
| AutoChip: Automating HDL Generation Using LLM Feedback | NYU | arXiv | 2023 |
| A Deep Learning Framework for Verilog Autocompletion Towards Design and Verification Automation | KU Leuven | arXiv | 2023 |

## Verification, Debugging & Testing

| Paper | Affiliation | Venue | Year |
|-------|-------------|-------|------|
| CoverAssert: Iterative LLM Assertion Generation Driven by Functional Coverage | ICT-CAS | arXiv | 2026 |
| Assertain: Automated Security Assertion Generation Using Large Language Models | UF | arXiv | 2026 |
| Fixbench-RTL: A comprehensive benchmark for evaluating LLMs on RTL debugging | USTC | AsianHOST | 2025 |
| LAUDE: LLM-assisted unit test generation and debugging of hardware designs | UIC | arXiv | 2026 |
| VeriRAG: A retrieval-augmented framework for automated RTL testability repair | CUHK | arXiv | 2026 |
| VeriDebug: A Unified LLM for Verilog Debugging via Contrastive Embedding and Guided Correction | CityU | arXiv | 2025 |
| From Concept to Practice: an Automated LLM-aided UVM Machine for RTL Verification | SEU | arXiv | 2025 |
| LLM-assisted Bug Identification and Correction for Verilog HDL | DFKI | TODAES | 2025 |
| MARVEL: Multi-agent RTL vulnerability extraction using large language models | NYU | arXiv | 2025 |
| BugGen: A Self-Correcting Multi-Agent LLM Pipeline for Realistic RTL Bug Synthesis | TAMU | MLCAD | 2025 |
| Insights from Verification: Training a Verilog Generation LLM with Reinforcement Learning with Testbench Feedback | CityU | arXiv | 2025 |
| Spec2Assertion: Automatic pre-RTL assertion generation using large language models | TAMU | arXiv | 2025 |
| LISA: LLM informed systemverilog assertion generation with RAG and chain-of-thought | ISI | ISVLSI | 2025 |
| AssertionForge: Enhancing formal verification assertion generation with structured reasoning | NVIDIA | arXiv | 2025 |
| ConfiBench: Automatic Testbench Generation with Confidence-Based Scenario Mask and Testbench Ensemble using LLMs for HDL Design | TUM | MLCAD | 2024 |
| Domain-Adapted LLMs for VLSI Design and Verification: A Case Study on Formal Verification | NVIDIA | VTS | 2024 |
| Using LLMs to Facilitate Formal Verification of RTL | Princeton | arXiv | 2023 |
| AssertLLM: Generating and Evaluating Hardware Verification Assertions from Design Specifications via Multi-LLMs | HKUST | arXiv | 2024 |
| LLM-Aided Testbench Generation and Bug Detection for Finite-State Machines | NYU | arXiv | 2024 |
| RTLFixer: Automatically Fixing RTL Syntax Errors with Large Language Models | NVIDIA | DAC | 2024 |
| Self-HWDebug: Automation of LLM Self-Instructing for Hardware Security Verification | UCF | ISVLSI | 2024 |
| LLM-assisted Generation of Hardware Assertions | TAMU | arXiv | 2023 |
| VerilogEval: Evaluating Large Language Models for Verilog Code Generation | NVIDIA | arXiv | 2023 |
| RTLLM: An Open-Source Benchmark for Design RTL Generation with Large Language Model | NVIDIA | ICCAD | 2023 |

## High-Level Synthesis (HLS)

| Paper | Affiliation | Venue | Year |
|-------|-------------|-------|------|
| Bench4HLS: End-to-end evaluation of LLMs in high-level synthesis code generation | UCF | DATE | 2026 |
| Hierarchical mixture of experts: Generalizable learning for high-level synthesis | PKU | AAAI | 2025 |
| LIFT: LLM-based pragma insertion for HLS via GNN supervised fine-tuning | UC | arXiv | 2025 |
| ChatHLS: Towards systematic design automation and optimization for high-level synthesis | SEU | arXiv | 2025 |
| HLSPilot: LLM-based High-Level Synthesis | Huawei | ICCAD | 2024 |
| SynthAI: A Multi Agent Generative AI Framework for Automated Modular HLS Design Generation | IMF | arXiv | 2024 |

## Logic Synthesis

| Paper | Affiliation | Venue | Year |
|-------|-------------|-------|------|
| MappingEvolve: LLM-driven code evolution for technology mapping | CUHK | DAC | 2026 |
| Autonomous Evolution of EDA Tools: Multi-Agent Self-Evolved ABC | NVIDIA | arXiv | 2026 |
| GenEDA: Unleashing Generative Reasoning on Netlist via Multimodal Encoder-Decoder Aligned Foundation Model | HKUST | arXiv | 2025 |
| LLSM: LLM-enhanced logic synthesis model with EDA-guided CoT prompting | SJTU | ASPDAC | 2025 |
| LLM4Netlist: LLM-enabled step-based netlist generation from natural language | SZU | IEEE JETCAS | 2025 |

## Physical Design

| Paper | Affiliation | Venue | Year |
|-------|-------------|-------|------|
| ModuPlace: LLM-assisted modular PCB placement via preference-optimized constraint graph generation | CUHK | DAC | 2026 |
| Expert-level Leaf Cell Layout Generation via Preference-Optimized LLM | CUHK | ICML | 2026 |
| TOPCELL: Topology Optimization of Standard Cell via LLMs | UMD | arXiv | 2026 |
| Standard Cell Layout Generation: Methodological Evolution and Architectural Exploration with LLMs | Kookmin Univ | ASPDAC | 2026 |
| HyperPlace: Harnessing a Large Language Model for Efficient Hyperparameter Optimization in GPU-Accelerated VLSI Placement | NTHU | TODAES | 2025 |
| Evolution of Optimization Algorithms for Global Placement via Large Language Models | CUHK | arXiv | 2025 |
| LEGALM 2.0: A Versatile Augmented Lagrangian Method-Based Methodology for Mixed-Cell-Height Legalization | PKU | TCAD | 2025 |
| LLM-Enhanced GPU-Optimized Physical Design at Scale | NVIDIA | ICCAD | 2025 |
| Large Language Model (LLM) for Standard Cell Layout Design Optimization | NVIDIA | LAD | 2024 |
| ChatPattern: Layout Pattern Customization via Natural Language | CUHK | arXiv | 2024 |

## Analog Circuit Design

| Paper | Affiliation | Venue | Year |
|-------|-------------|-------|------|
| AutoSizer: Automatic sizing of analog and mixed-signal circuits via large language models | BNL | arXiv | 2026 |
| LaMAGIC2: Advanced circuit formulations for language-model-based topology generation | IBM | ICML | 2025 |
| LayoutCopilot: An LLM-Powered Multi-Agent Collaborative Framework for Interactive Analog Layout Design | PKU | TCAD | 2025 |
| AnalogCoder-Pro: Unifying Analog Circuit Generation and Optimization via Multi-modal LLMs | UT Austin | arXiv | 2025 |
| LLM-IMC: Automating analog in-memory computing architecture generation with large language models | NJIT | FCCM | 2025 |
| AUTOCIRCUIT-RL: Reinforcement Learning-Driven LLM for Automated Circuit Topology Generation | IBM | ICML | 2025 |
| EasySize: Elastic analog circuit sizing via LLM-guided heuristic search | SJTU | arXiv | 2025 |
| Towards Generative AI for Analog and RF IC Design: From Specification to GDSII | UT Austin | ICCAD | 2025 |
| LaMAGIC: Language-Model-Based Topology Generation for Analog Integrated Circuits | UT Austin | ICML | 2024 |
| AnalogCoder: Analog Circuit Design via Training-Free Code Generation | HKU | AAAI | 2025 |
| LADAC: Large Language Model-driven Auto-Designer for Analog Circuits | NJU | TechRxiv | 2024 |
| ADO-LLM: Analog Design Bayesian Optimization with In-Context Learning of Large Language Models | UCSB | arXiv | 2024 |
| Human Language to Analog Layout Using GLayout Layout Automation Framework | UMich | MLCAD | 2024 |
| Atelier: An Automated Analog Circuit Design Framework via Multiple Large Language Model-based Agents | FDU | TechRxiv | 2024 |
| AnalogXpert: Automating Analog Topology Synthesis by Incorporating Circuit Design Expertise into Large Language Models | PKU | arXiv | 2024 |
| Artisan: Automated Operational Amplifier Design via Domain-specific Large Language Model | FDU | DAC | 2024 |
| AMSnet-KG: A Netlist Dataset for LLM-based AMS Circuit Auto-Design Using Knowledge Graph RAG | EIT | TODAES | 2025 |
| DocEDA: Automated Extraction and Design of Analog Circuits from Documents with Large Language Model | SEU | arXiv | 2024 |
| CircuitSynth: Leveraging Large Language Models for Circuit Topology Synthesis | IBM | LAD | 2024 |
| LLM-Enhanced Bayesian Optimization for Efficient Analog Layout Constraint Generation | UT Austin | arXiv | 2024 |

## Agentic Design Automation

| Paper | Affiliation | Venue | Year |
|-------|-------------|-------|------|
| Retrieve, schedule, reflect: LLM agents for chip QoR optimization | HKUST | arXiv | 2026 |
| Exploring the agentic frontier of verilog code generation | NYU | arXiv | 2026 |
| LEGO: An LLM Skill-Based Front-End Design Generation Platform | PKU | arXiv | 2026 |
| Divergent Thoughts toward One Goal: LLM-based Multi-Agent Collaboration System for Electronic Design Automation | CUHK | NAACL | 2025 |
| Automated Multi-Agent Workflows for RTL Design | UT Austin | NeurIPS (ML for Systems) | 2025 |
| JARVIS: A multi-agent code assistant for high-quality EDA script generation | NVIDIA | arXiv | 2025 |
| AutoEDA: Enabling EDA Flow Automation through Microservice-Based LLM Agents | Duke | arXiv | 2025 |
| EDA-Copilot: A RAG-Powered Intelligent Assistant for EDA Tools | Hunan Univ | TODAES | 2025 |
| Large Language Models for EDA: From Assistants to Agents | CUHK | Foundations and Trends in EDA | 2025 |
| ModelGen: Automating semiconductor parameter extraction with large language model agents | EIT | TODAES | 2025 |
| MCP4EDA: LLM-Powered Model Context Protocol RTL-to-GDSII Automation with Backend Aware Synthesis Optimization | UMD | arXiv | 2025 |
| DUET: Agentic Design Understanding via Experimentation and Testing | Southmountain Research | arXiv | 2025 |
| ChatLS: Multimodal retrieval-augmented generation and chain-of-thought for logic synthesis | CUHK | DAC | 2025 |
| RapidGPT: Your Ultimate HDL Pair-Designer | RapidSilicon | VS Code Marketplace | 2024 |
| ChatEDA: A Large Language Model Powered Autonomous Agent for EDA | CUHK | TCAD | 2024 |
| New Interaction Paradigm for Complex EDA Software Leveraging GPT | Warwick | arXiv | 2023 |
| ChatEDA: A Large Language Model Powered Autonomous Agent for EDA | CUHK | MLCAD | 2023 |

## Security, Trust & IP Protection

| Paper | Affiliation | Venue | Year |
|-------|-------------|-------|------|
| TrojanGYM: A detector-in-the-loop LLM for adaptive RTL hardware trojan insertion | NYUAD | arXiv | 2026 |
| NETLAM: An Automated LLM Framework to Generate and Evaluate Stealthy Hardware Trojans | IIT Kharagpur | ACNS (Workshops) | 2025 |
| RTLMarker: Protecting LLM-Generated RTL Copyright via a Hardware Watermarking Framework | ICT-CAS | ASPDAC | 2025 |
| VeriLeaky: Navigating IP protection vs utility in fine-tuning for LLM-driven verilog coding | NYUAD | arXiv | 2025 |
| SALAD: Systematic assessment of machine unlearning on LLM-aided hardware design | NYUAD | arXiv | 2025 |
| TrojanLoC: LLM-based framework for RTL trojan localization | NYU | arXiv | 2025 |
| LATENT: LLM-augmented trojan insertion and evaluation framework for analog circuits | ASU | arXiv | 2025 |
| LLMs for Hardware Security: Boon or Bane? | TAMU | arXiv | 2024 |
| DIVAS: An LLM-based End-to-End Framework for SoC Security Analysis and Policy-based Protection | UF | arXiv | 2023 |
| LLM for SoC Security: A Paradigm Shift | UF | IEEE Access | 2024 |
| Generating Secure Hardware using ChatGPT Resistant to CWEs | IIT Kharagpur | CSCML | 2023 |
| Unlocking Hardware Security Assurance: The Potential of LLMs | UTD | arXiv | 2023 |
| Fixing Hardware Security Bugs with Large Language Models | NYU | arXiv | 2023 |
| LLM4SecHW: Leveraging Domain-Specific Large Language Model for Hardware Debugging | NYU | arXiv | 2023 |

## Hardware Accelerator & Chip Design

| Paper | Affiliation | Venue | Year |
|-------|-------------|-------|------|
| AutoFlows++: Hierarchical Message Flow Mining for System on Chip Designs | USF | arXiv | 2026 |
| ChipMind: LLMs for Agile Chip Design | ASU | VTS | 2025 |
| TPU-Gen: LLM-Driven Custom Tensor Processing Unit Generator | NJIT | arXiv | 2025 |
| Autocomp: LLM-driven code optimization for tensor accelerators | UC Berkeley | arXiv | 2025 |
| QiMeng: Fully Automated Hardware and Software Design for Processor Chip | ICT-CAS | arXiv | 2025 |
| QiMeng-GEMM: Automatically Generating High-Performance Matrix Multiplication Code by Exploiting Large Language Models | ICT-CAS | AAAI | 2025 |
| QiMeng-Attention: SOTA Attention Operator is generated by SOTA Attention Algorithm | ICT-CAS | ACL | 2025 |
| QiMeng-TensorOp: One-Line Prompt is Enough for High-Performance Tensor Operator Generation with Hardware Primitives | ISCAS | IJCAI | 2025 |
| Large Processor Chip Model | ICT-CAS | SCIS | 2025 |
| LLMShare: Optimizing LLM Inference Serving with Hardware Architecture Exploration | HKU | DAC | 2025 |
| QiMeng-CPU-v2: Automated Superscalar Processor Design by Learning Data Dependencies | ICT-CAS | IJCAI | 2025 |
| ChatCPU: An Agile CPU Design and Verification Platform with LLM | SEU | DAC | 2024 |
| ChipNeMo: Domain-Adapted LLMs for Chip Design | NVIDIA | arXiv | 2024 |
| An Agile Framework for Efficient LLM Accelerator Development and Model Inference | ZJU | ICCAD | 2024 |
| The Survey of Chiplet-based Integrated Architecture: An EDA perspective | CUHK | ASPDAC | 2024 |
| Chip-Chat: Challenges and Opportunities in Conversational Hardware Design | NYU | MLCAD | 2023 |
| GPT4AIGChip: Towards Next-Generation AI Accelerator Design Automation via Large Language Models | NVIDIA | ICCAD | 2023 |

## Surveys, Benchmarks & Evaluations

| Paper | Affiliation | Venue | Year |
|-------|-------------|-------|------|
| ChipBench: A next-step benchmark for evaluating LLM performance in AI-aided chip design | UCSD | arXiv | 2026 |
| A Survey of Research in Large Language Models for Electronic Design Automation | UF | TODAES | 2025 |
| Revisiting VerilogEval: A Year of Improvements in Large-Language Models for Hardware Code Generation | NVIDIA | TODAES | 2025 |
| RocketPPA: Ultra-fast LLM-based PPA estimator at code-level abstraction | USC | arXiv | 2025 |
| TuRTLe: A Unified Evaluation of LLMs for RTL Generation | BSC | MLCAD | 2025 |
| Large Language Model for Verilog Code Generation: Literature Review and the Road Ahead | NPU | arXiv | 2025 |
| SLDB: An End-To-End Heterogeneous System-on-Chip Benchmark Suite for LLM-Aided Design | Columbia | arXiv | 2025 |
| MMCircuitEval: A comprehensive multimodal circuit-focused benchmark for evaluating LLMs | CUHK | arXiv | 2025 |
| Survey and benchmarking of large language models for RTL code generation: The state of the art | UNC Charlotte | arXiv | 2025 |
| SynCircuit: Automated generation of new synthetic RTL circuits can enable better LLMs | HKUST | DAC | 2025 |
| Comprehensive verilog design problems: A next-generation benchmark dataset for LLMs | NVIDIA | arXiv | 2025 |
| Lowering the Bar: How Large Language Models Can be Used as a Copilot by Hardware Hackers | NYU | IEEE S&P | 2025 |
| Large Language Models for EDA: Future or Mirage? | CUHK | ISPD | 2024 |
| The Dawn of AI-Native EDA: Promises and Challenges of Large Circuit Models | CUHK | arXiv | 2024 |
| Large circuit models: opportunities and challenges | CUHK | SCIS | 2024 |
| OpenLLM-RTL: Open Dataset and Benchmark for LLM-Aided Design RTL Generation | HKUST | ICCAD | 2024 |
| Customized Retrieval Augmented Generation and Benchmarking for EDA Tool Documentation QA | CUHK | ICCAD | 2024 |
| CreativEval: Evaluating Creativity of LLM-Based Hardware Code Generation | TAMU | arXiv | 2024 |
| Evaluating LLMs for Hardware Design and Test | NYU | arXiv | 2024 |
| LLM4EDA: Emerging Progress in Large Language Models for Electronic Design Automation | SJTU | arXiv | 2023 |
| Benchmarking Large Language Models for Automated Verilog RTL Code Generation | NYU | arXiv | 2023 |






## Abbreviations

| Abbreviation | Full Name |
|-------------|-----------|
| DAC | Design Automation Conference |
| ICCAD | International Conference on Computer-Aided Design |
| ICML | International Conference on Machine Learning |
| AAAI | AAAI Conference on Artificial Intelligence |
| ACL | Association for Computational Linguistics |
| NAACL | North American Chapter of the ACL |
| ACL Findings | Findings of the Association for Computational Linguistics |
| IJCAI | International Joint Conference on Artificial Intelligence |
| ASPDAC | Asia and South Pacific Design Automation Conference |
| ISPD | International Symposium on Physical Design |
| FCCM | IEEE Symposium on Field-Programmable Custom Computing Machines |
| MLCAD | Machine Learning for CAD |
| LAD | Workshop on Logic and Architecture Design |
| VTS | IEEE VLSI Test Symposium |
| AsianHOST | Asian Hardware Oriented Security and Trust Symposium |
| DATE | Design, Automation and Test in Europe Conference |
| NeurIPS | Conference on Neural Information Processing Systems |
| ACNS | Applied Cryptography and Network Security |
| CSCML | Cyber Security, Cryptology, and Machine Learning |
| IEEE Access | IEEE Access |
| ISVLSI | IEEE Computer Society Annual Symposium on VLSI |
| IEEE S&P | IEEE Security & Privacy |
| TODAES | ACM Transactions on Design Automation of Electronic Systems |
| TCAD | IEEE Transactions on Computer-Aided Design |
| SCIS | Science China Information Sciences |
| TechRxiv | TechRxiv Preprint Server |
| GLSVLSI | Great Lakes Symposium on VLSI |

## Contributing

Feel free to submit PRs to add new papers or improve categorization.

---

*Last updated: 2026-05*