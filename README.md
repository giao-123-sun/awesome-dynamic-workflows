# Awesome Dynamic Workflows

<div align="center">
  <p><em>A curated list of open-source projects, industry use cases, scientific research, tools, and frameworks related to <strong>dynamic workflows for AI agents</strong>.</em></p>
  <p>
    <a href="https://github.com/sindresorhus/awesome"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
    <a href="https://github.com/giao-123-sun/awesome-dynamic-workflows"><img src="https://img.shields.io/badge/Last%20updated-June%202026-brightgreen" alt="Last updated"></a>
    <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/contributions-welcome-orange.svg" alt="Contributions welcome"></a>
  </p>
</div>

Dynamic workflows decompose complex tasks into manageable phases where agents run in parallel, share context via structured artifacts, reuse cached computation, and adapt their execution graph based on intermediate results. This paradigm powers cost-efficient, observable, and scalable multi-agent systems.

> **Not sure where to start?** See [Open-Source Implementations](#open-source-implementations) for frameworks, [Industry Use Cases](#industry-use-cases) for real-world patterns, or [Scientific & Research Use Cases](#scientific--research-use-cases) for cutting-edge research.

## Contents

- [Open-Source Implementations](#open-source-implementations)
  - [Workflow Engines & Orchestrators](#workflow-engines--orchestrators)
  - [Multi-Agent Frameworks](#multi-agent-frameworks)
  - [Dynamic / Graph Workflow Libraries](#dynamic--graph-workflow-libraries)
  - [Low-Code / Visual Platforms](#low-code--visual-platforms)
  - [Agentic Coding Agents](#agentic-coding-agents)
  - [Cache-First Dynamic Workflows](#cache-first-dynamic-workflows)
- [Industry Use Cases](#industry-use-cases)
- [Scientific & Research Use Cases](#scientific--research-use-cases)
- [Workflow Optimization](#workflow-optimization)
- [Tooling & Observability](#tooling--observability)
- [Related Awesome Lists](#related-awesome-lists)
- [Selection Criteria & Freshness](#selection-criteria--freshness)
- [Data Sources](#data-sources)
- [Legend](#legend)
- [How to Contribute](#how-to-contribute)

---

## Open-Source Implementations

### Workflow Engines & Orchestrators

- **[Temporal](https://github.com/temporalio/temporal)** — Durable execution engine with replay, retries, and long-running workflow support. Battle-tested at scale. `MIT` `star13k` `Go`
- **[Prefect](https://github.com/PrefectHQ/prefect)** — Python workflow orchestration for data pipelines with dynamic scheduling, caching, and observability. `Apache-2.0` `star18k` `Python`
- **[Conductor OSS](https://github.com/conductor-oss/conductor)** — Netflix-originated DAG-based workflow engine with dynamic forks, LLM tasks, and MCP tools. `Apache-2.0` `star32k` `Java`
- **[Orra](https://github.com/orra-dev/orra)** — AI-driven plan generation, durable execution, and automatic service discovery for agent workflows. `MPL-2.0` `star0.2k` `Go`
- **[Titan Orchestrator](https://github.com/ramn51/titan-orchestrator)** — Zero-dependency distributed orchestrator bridging DevOps pipelines and dynamic agentic AI workflows. `Apache-2.0` `star35` `Go`

### Multi-Agent Frameworks

- **[AutoGen](https://github.com/microsoft/autogen)** (Microsoft) — Pioneering multi-agent conversation framework with dynamic team formation, tool use, and code execution. `MIT` `star35k` `Python`
- **[CrewAI](https://github.com/crewAIInc/crewAI)** — Role-based multi-agent orchestration with sequential/parallel execution, tool integration, and memory. `MIT` `star25k` `Python`
- **[Microsoft Agent Framework](https://github.com/microsoft/agent-framework)** — Production-grade graph-based orchestration with checkpointing, HITL, and OpenTelemetry. `MIT` `star11k` `C#`
- **[Solace Agent Mesh](https://github.com/SolaceLabs/solace-agent-mesh)** — Event-driven multi-agent framework using pub/sub A2A protocol for dynamic agent discovery and delegation. `Apache-2.0` `star4.9k` `Python`
- **[LangGraph](https://github.com/langchain-ai/langgraph)** — Graph-based stateful orchestration for LLM applications with cycles, branching, and persistence. `MIT` `star34k` `Python`
- **[GraphBit](https://github.com/InfinitiBit/graphbit)** — High-performance agentic framework with Rust core (68x lower CPU, 140x lower memory). Used by Grant Thornton. `Apache-2.0` `star559` `Rust`

### Dynamic / Graph Workflow Libraries

- **[Open Dynamic Workflows](https://github.com/Suraj1235/open-dynamic-workflows)** — Script-as-orchestrator engine where agents run as independent subprocesses with phases and dependencies. `MIT` `star3` `TypeScript`
- **[Open Dynamic Workflow (Rust)](https://github.com/ChaosRealmsAI/open-dynamic-workflow)** — Open re-implementation of Claude Code's Dynamic Workflow in Rust. `MIT` `star7` `Rust`
- **[Claude Code Workflow](https://github.com/catlog22/Claude-Code-Workflow)** — JSON-driven multi-agent development framework with CLI orchestration, skill system, and terminal dashboard. `MIT` `star2.1k` `TypeScript`
- **[Junjo](https://github.com/mdrideout/junjo)** — Pure Python graph workflow library for building dynamic LLM-driven DAGs. `Apache-2.0` `star20` `Python`
- **[Branch-Thinking MCP](https://github.com/ssdeanx/branch-thinking-mcp)** — MCP server for managing parallel reasoning branches, semantic cross-references, and persistent tasks. `MIT` `star15` `Python`

### Low-Code / Visual Platforms

- **[n8n](https://github.com/n8n-io/n8n)** — Popular low-code workflow automation with visual builder and AI/LLM nodes. `Sustainable Use License` `star55k` `TypeScript`
- **[CraftGen](https://github.com/craftgen/craftgen)** — Open-source no-code AI agent platform with visual canvas for graph-based workflows. `AGPL-3.0` `star314` `TypeScript`

### Agentic Coding Agents

- **[Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview)** — Terminal-native agentic coding tool by Anthropic; understands codebases and executes multi-step tasks. `Proprietary` `--` `--`
- **[Whale (DeepSeek-Code-Whale)](https://github.com/usewhale/DeepSeek-Code-Whale)** — TUI/CLI agent with ~98% prompt cache hit, dynamic workflows in JavaScript, MCP support. `MIT` `star634` `TypeScript`
- **[Patchwork](https://github.com/patched-codes/patchwork)** — Composable patchflows for automated PR review, bug fixing, security patching, and dependency upgrades. `AGPL-3.0` `star1.5k` `Python`

### Cache-First Dynamic Workflows

- **[CFDW (Cache-First Dynamic Workflows)](https://github.com/giao-123-sun/Deepseek-Dynamic-Workflow)** — Cache-first adapter for Open Dynamic Workflows. Native DeepSeek agent, ReasoniX harness, stable Repomix prefix, usage ledger, and workflow dashboard. Demonstrates >80% cache hit rate across multi-agent runs. `Non-commercial` `--` `TypeScript`

---

## Industry Use Cases

*See [data/industry-use-cases.md](data/industry-use-cases.md) for full details with evidence and sources.*

| Category | Project | Pattern | Key Advantage |
|----------|---------|---------|---------------|
| Software Dev | [Patchwork](https://github.com/patched-codes/patchwork) | Composable patchflows for PR review | Production-ready CLI agent |
| Software Dev | [Open Dynamic Workflow (Rust)](https://github.com/ChaosRealmsAI/open-dynamic-workflow) | JS scripts, heterogeneous executors | 3x token savings |
| Enterprise | [Solace Agent Mesh](https://github.com/SolaceLabs/solace-agent-mesh) | Event-driven pub/sub | Scalable decoupled multi-agent |
| Enterprise | [GraphBit](https://github.com/InfinitiBit/graphbit) | Rust-core agent framework | 68x lower CPU, 140x lower memory |
| Infrastructure | [Titan Orchestrator](https://github.com/ramn51/titan-orchestrator) | Bridge DevOps + AI workflows | Gradual adoption |
| Data & Analytics | [Microsoft Data Foundation Accelerator](https://github.com/microsoft/agentic-applications-for-unified-data-foundation-solution-accelerator) | Agentic AI on Fabric | Natural language data queries |

---

## Scientific & Research Use Cases

*See [data/research-use-cases.md](data/research-use-cases.md) for full details with evidence and sources.*

| Project | Domain | Pattern | Evidence |
|---------|--------|---------|----------|
| [GenoMAS](https://github.com/Liu-Hy/GenoMAS) | Genomics | Multi-agent code-driven analysis | 60.38% F1 on GenoTEX |
| [Mimosa-AI](https://github.com/HolobiomicsLab/Mimosa-AI) | Metabolomics | Self-evolving multi-agent system | 43.1% on ScienceAgentBench |
| [DeepLense AI Scientist](https://github.com/ML4SCI/DeepLense-AI-Scientist) | Astrophysics | Divide-and-conquer agents for lensing | Reproducible pipeline |
| [R-LAM](https://github.com/suriyasureshok/rlam) | Reproducibility | Immutable action schemas, DAG traces | Auditability for regulated science |

---

## Workflow Optimization

- **[IBM/awesome-agentic-workflow-optimization](https://github.com/IBM/awesome-agentic-workflow-optimization)** — Comprehensive survey and curated list of workflow optimization papers for LLM agents. arXiv:2603.22386. `Apache-2.0` `star62`
- **[GATES](https://github.com/yashenCS/GATES)** — Cost-aware dynamic workflow scheduling via Graph Attention Networks (IJCAI 2025). `Apache-2.0` `star26`

## Tooling & Observability

- **[CFDW Dashboard](https://github.com/giao-123-sun/Deepseek-Dynamic-Workflow)** — Static HTML dashboard showing per-agent tokens, tools, cache hit rate, runtime, and artifact paths.
- **[ReasoniX](https://reasonix.ai)** — Per-agent harness for complex tool use, cost control, and transcript recording. Integrates with ODW as custom adapter.
- **[Repomix](https://github.com/yamadashy/repomix)** — Stable workspace prefix generator to improve prompt cache consistency across multi-agent runs.

## Related Awesome Lists

- [IBM/awesome-agentic-workflow-optimization](https://github.com/IBM/awesome-agentic-workflow-optimization) — Research papers on workflow optimization.
- [xz1220/awesome-dynamic-workflows](https://github.com/xz1220/awesome-dynamic-workflows) — Community index of ODW-compatible workflow scripts.
- [awesome-llm-agents](https://github.com/kxxt/awesome-llm-agents) — General LLM agent resources.

---

## Selection Criteria & Freshness

### Inclusion Requirements

- **Relevance**: The project must relate to dynamic workflows for AI agents, not static pipeline automation or single-agent chatbots.
- **Open Source**: Prefer actively maintained projects with clear licenses. Proprietary tools may be listed if they significantly advance the ecosystem.
- **Maturity**: Evidence of real use (GitHub stars, production deployment, publications) is a plus but not required for promising research.
- **Documentation**: Projects should have a README or equivalent that explains the dynamic workflow pattern.
- **Anti-patterns**: Exclude simple task queues, single-agent chatbots, proprietary SaaS-only, abandoned projects, and static workflows without runtime adaptation.

### Freshness Policy

This list is reviewed and updated on a quarterly basis. Last review: **June 2026**. Entries with stale data (outdated stars, broken links) are corrected during review. New submissions are accepted via PR at any time. The `research/` directory contains raw agent notes captured during compilation; these may not reflect the latest project state.

## Data Sources

- **`data/`** — Structured, verified outputs (JSON, Markdown) suitable for direct consumption. These are maintained and updated as part of the curation cycle.
- **`research/`** — Raw agent research notes used to compile the curated lists. These are snapshots taken at compilation time and may contain unverified or time-sensitive observations. They are provided for transparency and traceability.

## Legend

| Symbol | Meaning |
|--------|---------|
| `starN` | GitHub star count (approximate) |
| License | Project license (e.g., MIT, Apache-2.0, AGPL-3.0) |
| Language | Primary implementation language |
| `--` | Not applicable or not disclosed |

For scientific entries, "Evidence" indicates evaluation metrics or reproducibility claims from the original work.

---

## How to Contribute

See [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines. Contributions are welcome via pull requests. Please ensure each addition includes a URL, license, brief description, and reason for inclusion.

---

*Maintained by the CFDW community. This list is a living document — please [open issues](https://github.com/giao-123-sun/awesome-dynamic-workflows/issues) or [submit PRs](https://github.com/giao-123-sun/awesome-dynamic-workflows/pulls) to suggest additions or corrections.*