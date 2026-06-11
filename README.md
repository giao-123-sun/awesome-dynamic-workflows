# Awesome Dynamic Workflows

A curated list of open-source projects, industry use cases, scientific research, tools, and frameworks related to **dynamic workflows for AI agents**.

Dynamic workflows decompose complex tasks into manageable phases where agents run in parallel, share context via structured artifacts, reuse cached computation, and adapt their execution graph based on intermediate results. This paradigm powers cost-efficient, observable, and scalable multi-agent systems.

> **Note**: The `research/` directory contains raw agent research notes used to compile the curated lists. The `data/` directory contains verified, structured outputs (JSON, Markdown) suitable for direct consumption. Please contribute corrections or additions via PR.

## Categories

- [Open-Source Implementations](#open-source-implementations)
- [Industry Use Cases](#industry-use-cases)
- [Scientific & Research Use Cases](#scientific--research-use-cases)
- [Workflow Optimization](#workflow-optimization)
- [Tooling & Observability](#tooling--observability)
- [Related Awesome Lists](#related-awesome-lists)

---

## Open-Source Implementations

### Workflow Engines & Orchestrators
- **[Temporal](https://github.com/temporalio/temporal)** — Durable execution engine with replay, retries, and long-running workflow support. Battle-tested at scale. ~13k stars.
- **[Prefect](https://github.com/PrefectHQ/prefect)** — Python workflow orchestration for data pipelines with dynamic scheduling, caching, and observability. ~18k stars.
- **[Conductor OSS](https://github.com/conductor-oss/conductor)** — Netflix-originated DAG-based workflow engine with dynamic forks, LLM tasks, and MCP tools. ~32k stars. Apache-2.0.
- **[Orra](https://github.com/orra-dev/orra)** — AI-driven plan generation, durable execution, and automatic service discovery for agent workflows. ~243 stars. MPL-2.0.

### Multi-Agent Frameworks
- **[AutoGen](https://github.com/microsoft/autogen)** (Microsoft) — Pioneering multi-agent conversation framework with dynamic team formation, tool use, and code execution. ~35k stars. MIT.
- **[CrewAI](https://github.com/crewAIInc/crewAI)** — Role-based multi-agent orchestration with sequential/parallel execution, tool integration, and memory. ~25k stars. MIT.
- **[Microsoft Agent Framework](https://github.com/microsoft/agent-framework)** — Production-grade graph-based orchestration with checkpointing, HITL, and OpenTelemetry. ~11k stars. MIT.
- **[Solace Agent Mesh](https://github.com/SolaceLabs/solace-agent-mesh)** — Event-driven multi-agent framework using pub/sub A2A protocol for dynamic agent discovery and delegation. ~4.8k stars. Apache-2.0.
- **[LangGraph](https://github.com/langchain-ai/langgraph)** — Graph-based stateful orchestration for LLM applications with cycles, branching, and persistence. ~34k stars. MIT.

### Dynamic / Graph Workflow Libraries
- **[Open Dynamic Workflows](https://github.com/Suraj1235/open-dynamic-workflows)** — Script-as-orchestrator engine where agents run as independent subprocesses with phases and dependencies. Lightweight, custom adapters, cache-friendly. MIT.
- **[Open Dynamic Workflow (Rust)](https://github.com/ChaosRealmsAI/open-dynamic-workflow)** — Open re-implementation of Claude Code's Dynamic Workflow in Rust. JavaScript workflow scripts with agent(), parallel(), pipeline(), token budgets, git-worktree isolation, and pandacode executor. MIT.
- **[Claude Code Workflow](https://github.com/catlog22/Claude-Code-Workflow)** — JSON-driven multi-agent development framework with CLI orchestration, skill system, and terminal dashboard. ~2.1k stars. MIT.
- **[Junjo](https://github.com/mdrideout/junjo)** — Pure Python graph workflow library for building dynamic LLM-driven DAGs. Apache-2.0.
- **[Branch-Thinking MCP](https://github.com/ssdeanx/branch-thinking-mcp)** — MCP server for managing parallel reasoning branches, semantic cross-references, and persistent tasks. MIT.

### Low-Code / Visual Platforms
- **[n8n](https://github.com/n8n-io/n8n)** — Popular low-code workflow automation with visual builder and AI/LLM nodes. ~55k stars. Sustainable Use License.
- **[CraftGen](https://github.com/craftgen/craftgen)** — Open-source no-code AI agent platform with visual canvas for graph-based workflows. AGPL-3.0.

### Agentic Coding Agents
- **[Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview)** — Terminal-native agentic coding tool by Anthropic; understands codebases and executes multi-step tasks.
- **[Whale (DeepSeek-Code-Whale)](https://github.com/usewhale/DeepSeek-Code-Whale)** — TUI/CLI agent with ~98% prompt cache hit, dynamic workflows in JavaScript, MCP support. ~634 stars. MIT.

### Cache-First Dynamic Workflows
- **[CFDW (Cache-First Dynamic Workflows)](https://github.com/giao-123-sun/Deepseek-Dynamic-Workflow)** — Cache-first adapter for Open Dynamic Workflows. Native DeepSeek agent, ReasoniX harness, stable Repomix prefix, usage ledger, and workflow dashboard. Demonstrates >80% cache hit rate across multi-agent runs. Non-commercial license.

---

## Industry Use Cases

*See [data/industry-use-cases.md](data/industry-use-cases.md) for full details.*

| Category | Project | Pattern | Key Advantage |
|----------|---------|---------|---------------|
| Software Dev | [Patchwork](https://github.com/patched-codes/patchwork) | Composable patchflows for PR review, bug fixing, security | Production-ready CLI/CI/CD agent |
| Software Dev | [Open Dynamic Workflow (Rust)](https://github.com/ChaosRealmsAI/open-dynamic-workflow) | JS scripts, heterogeneous executors | 3× token savings vs built-in tool |
| Enterprise | [Solace Agent Mesh](https://github.com/SolaceLabs/solace-agent-mesh) | Event-driven pub/sub | Scalable decoupled multi-agent |
| Enterprise | [GraphBit](https://github.com/InfinitiBit/graphbit) | Rust-core agent framework | 68× lower CPU, 140× lower memory |
| Infrastructure | [Titan Orchestrator](https://github.com/ramn51/titan-orchestrator) | Bridge DevOps pipelines + AI workflows | Gradual adoption |
| Data & Analytics | [Microsoft Data Foundation Accelerator](https://github.com/microsoft/agentic-applications-for-unified-data-foundation-solution-accelerator) | Agentic AI on Fabric | Natural language data queries |

---

## Scientific & Research Use Cases

*See [data/research-use-cases.md](data/research-use-cases.md) for full details.*

| Project | Domain | Pattern | Evidence |
|---------|--------|---------|----------|
| [GenoMAS](https://github.com/Liu-Hy/GenoMAS) | Genomics | Multi-agent code-driven analysis | 60.38% F1 on GenoTEX |
| [Mimosa-AI](https://github.com/HolobiomicsLab/Mimosa-AI) | Metabolomics | Self-evolving multi-agent system | 43.1% on ScienceAgentBench |
| [DeepLense AI Scientist](https://github.com/ML4SCI/DeepLense-AI-Scientist) | Astrophysics | Divide-and-conquer agents for lensing | Reproducible pipeline |
| [R-LAM](https://github.com/suriyasureshok/rlam) | Reproducibility | Immutable action schemas, DAG traces | Auditability for regulated science |

---

## Workflow Optimization

- **[IBM/awesome-agentic-workflow-optimization](https://github.com/IBM/awesome-agentic-workflow-optimization)** — Comprehensive survey and curated list of workflow optimization papers for LLM agents. arXiv:2603.22386.
- **[GATES](https://github.com/yashenCS/GATES)** — Cost-aware dynamic workflow scheduling via Graph Attention Networks (IJCAI 2025).

## Tooling & Observability

- **[CFDW Dashboard](https://github.com/giao-123-sun/Deepseek-Dynamic-Workflow)** — Static HTML dashboard showing per-agent tokens, tools, cache hit rate, runtime, and artifact paths.
- **[ReasoniX](https://reasonix.ai)** — Per-agent harness for complex tool use, cost control, and transcript recording. Integrates with ODW as custom adapter.
- **[Repomix](https://github.com/yamadashy/repomix)** — Stable workspace prefix generator to improve prompt cache consistency across multi-agent runs.

## Related Awesome Lists

- [IBM/awesome-agentic-workflow-optimization](https://github.com/IBM/awesome-agentic-workflow-optimization) — Research papers on workflow optimization.
- [xz1220/awesome-dynamic-workflows](https://github.com/xz1220/awesome-dynamic-workflows) — Community index of ODW-compatible workflow scripts.
- [awesome-llm-agents](https://github.com/kxxt/awesome-llm-agents) — General LLM agent resources.

---

## How to Contribute

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. Contributions are welcome via pull requests. Please ensure each addition includes a URL, license, brief description, and reason for inclusion.

## Selection Criteria

- **Relevance**: The project must relate to dynamic workflows for AI agents, not static pipeline automation or single-agent chatbots.
- **Open Source**: Prefer actively maintained projects with clear licenses.
- **Maturity**: Evidence of real use (GitHub stars, production deployment, publications) is a plus but not required for promising research.
- **Documentation**: Projects should have a README or equivalent that explains the dynamic workflow pattern.
- **Anti-patterns**: Exclude simple task queues, single-agent chatbots, proprietary SaaS-only, abandoned projects, and static workflows without runtime adaptation.

---

*Maintained by the CFDW community. This list is a living document — please open issues or PRs to suggest additions or corrections.*
