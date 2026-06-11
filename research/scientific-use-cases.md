# Scientific & Research Use Cases for Dynamic Workflows

## Overview
This document catalogs research projects, frameworks, surveys, and benchmark efforts that apply dynamic (agentic) workflows to scientific and research problems. Each entry includes the project title, URL, method family, specific use case, and why it belongs in an awesome-dynamic-workflows collection.

---

## 1. Survey & Reference Repositories

### IBM / awesome-agentic-workflow-optimization
- **URL**: https://github.com/IBM/awesome-agentic-workflow-optimization
- **Paper**: https://arxiv.org/abs/2603.22386 ("From Static Templates to Dynamic Runtime Graphs: A Survey of Workflow Optimization for LLM Agents")
- **Method Family**: Survey / curated paper list
- **Use Case**: Comprehensive taxonomy covering static workflow optimization (template search, node-level config, joint structure-config) and dynamic optimization (selection/pruning, construct-then-execute, in-execution editing)
- **Why It Belongs**: The most complete single reference for the workflow optimization landscape; indispensable for any dynamic-workflows reading list

### xz1220 / awesome-dynamic-workflows
- **URL**: https://github.com/xz1220/awesome-dynamic-workflows
- **Method Family**: Community index
- **Use Case**: Collection of Open Dynamic Workflow (ODW) compatible workflow scripts and runtimes
- **Why It Belongs**: Companion index focused on portable, runtime-independent dynamic workflow artifacts

---

## 2. Scientific Multi-Agent Frameworks (Code-Driven & Autonomous)

### GenoMAS
- **URL**: https://github.com/Liu-Hy/GenoMAS
- **Paper**: https://arxiv.org/abs/2507.21035
- **Method Family**: Multi-agent code-driven workflow with typed messaging, notebook-style execution, and role-specific agents (Data Engineer, Code Reviewer, Domain Expert, Statistician)
- **Use Case**: Automated gene expression analysis—plans, writes, executes, debugs, and backtracks across multi-step transcriptomic data pipelines (GEO/TCGA datasets); achieves 60.38% F1 on GenoTEX benchmark
- **Why It Belongs**: Demonstrates how dynamic multi-agent workflows can robustly automate a complex scientific analysis pipeline with minimal human intervention

### Mimosa-AI
- **URL**: https://github.com/HolobiomicsLab/Mimosa-AI
- **Paper**: https://arxiv.org/abs/2603.28986
- **Method Family**: Self-evolving multi-agent system; MCP-based tool discovery; Darwinian single-incumbent local search for workflow mutation
- **Use Case**: Autonomous scientific research—reproduced a metabolomics paper end-to-end (raw .mzML → molecular network); evaluated on ScienceAgentBench (43.1% success rate with iterative learning)
- **Why It Belongs**: Shows evolution of multi-agent workflow structure across iterations, a key dynamic workflow capability for open-ended research tasks

### DeepLense AI Scientist (DLens)
- **URL**: https://github.com/ML4SCI/DeepLense-AI-Scientist
- **Method Family**: Multi-agent framework built on Pydantic AI; divide-and-conquer agent design with optional ReAct loops for complex multi-tool use
- **Use Case**: Autonomous scientific workflows in gravitational lensing research—orchestrates data analysis, model training, and inference with locally hosted LLMs
- **Why It Belongs**: Illustrates domain-specific dynamic workflows in astrophysics, with clean separation of agent responsibilities and reproducible pipelines

### PARAMETR-Bench
- **URL**: https://github.com/otheiner/PARAMETR-Bench
- **Method Family**: Contamination-resistant evaluation benchmark for multimodal LLM agents on real scientific analysis workflows
- **Use Case**: Rigorous assessment of LLM agents on procedural scientific tasks using meta-rubrics
- **Why It Belongs**: Provides evaluation methodology for dynamic workflows in scientific settings, essential for benchmarking and comparing approaches

---

## 3. Reproducibility & Execution Semantics

### R-LAM (Reproducibility-Constrained Large Action Models)
- **URL**: https://github.com/suriyasureshok/rlam
- **Method Family**: Immutable action schemas, deterministic execution, DAG-based execution traces, replay & forking
- **Use Case**: Scientific workflow automation with strict guarantees on auditability, determinism, and replayability—designed for LAM-driven execution
- **Why It Belongs**: Addresses the critical reproducibility challenge that blocks adoption of dynamic AI workflows in regulated or high-stakes research domains

### ProAgent
- **URL**: https://arxiv.org/abs/2311.10751
- **Method Family**: From Robotic Process Automation to Agentic Process Automation
- **Use Case**: Workflow automation for business & research processes; dynamic agent creation and task delegation
- **Why It Belongs**: Bridges RPA and agentic workflows, showing a direct path from static automation to dynamic, agent-driven scientific pipelines

---

## 4. Notable Papers from the IBM Survey Relevant to Science

The following papers (curated from IBM's awesome list) are especially relevant for researchers building dynamic workflows:

| Paper | Year | Method | Relevance |
|-------|------|--------|-----------|
| [AFlow: Automating Agentic Workflow Generation](https://openreview.net/forum?id=z5uVAKwmjf) | 2025 | Offline template search | Automates workflow design for any task, including scientific analysis pipelines |
| [DyFlow: Dynamic Workflow Framework for Agentic Reasoning](https://arxiv.org/abs/2509.26062) | 2025 | In-execution editing | Enables workflows that restructure themselves mid-execution based on intermediate results—critical for exploratory science |
| [EvoFlow: Evolving Diverse Agentic Workflows on the Fly](https://arxiv.org/abs/2502.07373) | 2025 | In-execution editing | Evolutionary approach to workflow generation, directly applicable to iterative research tasks |
| [ScoreFlow: Mastering LLM Agent Workflows via Score-Based Preference Optimization](https://arxiv.org/abs/2502.04306) | 2025 | Construct-then-execute | Learns optimal workflow structures from preference data; useful for optimizing scientific workflows over time |
| [Workflow-R1: Group Sub-sequence Policy Optimization](https://arxiv.org/abs/2602.01202) | 2026 | Construct-then-execute | Reinforcement learning for multi-turn workflow construction; promising for long-horizon research tasks |
| [AutoFlow: Automated Workflow Generation for LLM Agents](https://arxiv.org/abs/2407.12821) | 2024 | Construct-then-execute | Pioneering automated workflow generation; strong baseline for science automation |
| [RobustFlow: Towards Robust Agentic Workflow Generation](https://arxiv.org/abs/2509.21834) | 2025 | Construct-then-execute | Focus on failure recovery and robustness—key for unsupervised scientific runs |

---

## 5. Summary Assessment

| Category | Count | Representative Projects |
|----------|-------|------------------------|
| Survey / Awesome Lists | 2 | IBM/awesome-agentic-workflow-optimization, xz1220/awesome-dynamic-workflows |
| Scientific Multi-Agent Frameworks | 4 | GenoMAS, Mimosa-AI, DLens, PARAMETR-Bench |
| Reproducibility & Execution Semantics | 2 | R-LAM, ProAgent |
| Key Papers (from survey) | 8 | AFlow, DyFlow, EvoFlow, ScoreFlow, Workflow-R1, AutoFlow, RobustFlow, Maestro |

All sources were collected from GitHub repositories, arXiv papers, and the IBM survey. These entries represent the most significant current work at the intersection of dynamic/agentic workflows and scientific research.
