# Open-Source Dynamic Workflow & Agent Workflow Implementations

Research conducted as part of Phase A of awesome-dynamic-workflows-research.
Sources: GitHub repos, official READMEs, and web searches.

## Category Legend

- **WF**: Workflow Orchestration Engine
- **MA**: Multi-Agent Framework
- **AG**: Agent Framework (single/multi)
- **DW**: Dynamic/Graph Workflow
- **OP**: Workflow Optimization / Research
- **LP**: Low-Code / No-Code Platform

---

## 1. Microsoft Agent Framework

- **Repo**: [microsoft/agent-framework](https://github.com/microsoft/agent-framework)
- **Stars**: ~11,250 | **License**: MIT | **Lang**: Python, .NET
- **Category**: MA / WF
- **What makes it dynamic**: Graph-based multi-agent orchestration with sequential, concurrent, handoff, and group collaboration patterns. Supports checkpointing, streaming, human-in-the-loop, and time-travel debugging.
- **Why include**: Production-grade framework from Microsoft with extensive samples, observability (OpenTelemetry), and deployment options (hosted, A2A). Strong documentation and community.
- **URL**: https://github.com/microsoft/agent-framework

## 2. Solace Agent Mesh

- **Repo**: [SolaceLabs/solace-agent-mesh](https://github.com/SolaceLabs/solace-agent-mesh)
- **Stars**: ~4,870 | **License**: Apache-2.0 | **Lang**: Python
- **Category**: MA (Event-Driven)
- **What makes it dynamic**: Event-driven architecture using Solace messaging allows dynamic agent discovery, task delegation, and multi-step workflows with minimal coupling. Agents communicate via A2A protocol over event mesh.
- **Why include**: True scalability and reliability via event broker; built-in support for Slack, Teams, REST, Web UI; extensible with plugins; built on Google ADK.
- **URL**: https://github.com/SolaceLabs/solace-agent-mesh

## 3. Claude Code Workflow (CCW)

- **Repo**: [catlog22/Claude-Code-Workflow](https://github.com/catlog22/Claude-Code-Workflow)
- **Stars**: ~2,100 | **License**: MIT | **Lang**: TypeScript
- **Category**: MA / DW
- **What makes it dynamic**: JSON-driven multi-agent cadence-team development framework with intelligent CLI orchestration (Gemini/Qwen/Codex). Features skill-based workflows, session lifecycle management, terminal dashboard, and team architecture with inner loop execution.
- **Why include**: Practical CLI-first multi-agent framework for coding tasks; supports multiple LLM backends; modular skill system with 37+ skills.
- **URL**: https://github.com/catlog22/Claude-Code-Workflow

## 4. Orra

- **Repo**: [orra-dev/orra](https://github.com/orra-dev/orra)
- **Stars**: ~243 | **License**: MPL-2.0 | **Lang**: Go (Plan Engine), SDKs in Python/JS
- **Category**: WF / MA (Infrastructure)
- **What makes it dynamic**: Plan Engine with AI-driven plan generation, automatic service discovery, durable execution with state persistence, pre-validated execution plans, revert state on failure, health monitoring, audit logs.
- **Why include**: Focus on resilience and error recovery; designed to work with any agent framework; production-ready infrastructure for complex unpredictable workflows.
- **URL**: https://github.com/orra-dev/orra

## 5. CraftGen

- **Repo**: [craftgen/craftgen](https://github.com/craftgen/craftgen)
- **Stars**: ~314 | **License**: AGPL-3.0 | **Lang**: TypeScript
- **Category**: LP / DW
- **What makes it dynamic**: Open-source no-code AI agent platform with visual canvas for building graph-based workflows. Uses actor model for dynamic graph-based solutions. Supports hundreds of LLMs, agent capabilities (Function Calling/ReAct), custom tools, code interpreter, and real-time monitoring.
- **Why include**: Accessible to non-technical users; visual workflow builder; self-hostable; extensive model support.
- **URL**: https://github.com/craftgen/craftgen

## 6. LangGraph (LangChain)

- **Repo**: [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) (official)
- **Stars**: ~5,000+ (part of LangChain ecosystem) | **License**: MIT
- **Category**: DW / AG
- **What makes it dynamic**: Graph-based orchestration tool for building stateful, multi-actor LLM applications. Supports cycles, branching, persistence, human-in-the-loop, and streaming.
- **Why include**: Industry standard for graph-based agent workflows; extensive documentation; used by many projects as underlying runtime.
- **URL**: https://github.com/langchain-ai/langgraph

## 7. CrewAI

- **Repo**: [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI)
- **Stars**: ~25,000+ | **License**: MIT | **Lang**: Python
- **Category**: MA
- **What makes it dynamic**: Multi-agent orchestration framework with role-based agents, task delegation, and sequential/parallel workflow execution. Supports tool integration, memory, and human input.
- **Why include**: Most popular multi-agent framework; large community; simple API; good for prototyping and production.
- **URL**: https://github.com/crewAIInc/crewAI

## 8. AutoGen (Microsoft)

- **Repo**: [microsoft/autogen](https://github.com/microsoft/autogen)
- **Stars**: ~35,000+ | **License**: MIT | **Lang**: Python, .NET
- **Category**: MA
- **What makes it dynamic**: Multi-agent conversation framework enabling dynamic agent team formation, multi-turn conversations, tool use, and code execution.
- **Why include**: Pioneering multi-agent framework; strong research origins; supports diverse conversation patterns.
- **URL**: https://github.com/microsoft/autogen

## 9. Temporal

- **Repo**: [temporalio/temporal](https://github.com/temporalio/temporal)
- **Stars**: ~13,000+ | **License**: MIT (client SDKs), MIT/Proprietary (server)
- **Category**: WF (Durable Execution)
- **What makes it dynamic**: Workflow engine for durable execution with automatic retries, state persistence, and long-running workflow support. Agents/tasks defined as workflows with custom logic.
- **Why include**: Battle-tested production workflow engine; supports multiple languages; good for mission-critical agent orchestration.
- **URL**: https://github.com/temporalio/temporal

## 10. Prefect

- **Repo**: [PrefectHQ/prefect](https://github.com/PrefectHQ/prefect)
- **Stars**: ~18,000+ | **License**: Apache-2.0 | **Lang**: Python
- **Category**: WF (Data/ML Pipelines)
- **What makes it dynamic**: Workflow orchestration for data pipelines with dynamic task scheduling, retries, caching, and observability. Can be extended for AI agent workflows.
- **Why include**: Excellent for data-intensive workflows; mature ecosystem; strong monitoring and UI.
- **URL**: https://github.com/PrefectHQ/prefect

## 11. n8n

- **Repo**: [n8n-io/n8n](https://github.com/n8n-io/n8n)
- **Stars**: ~55,000+ | **License**: Sustainable Use License (fair-code) | **Lang**: TypeScript
- **Category**: LP (Automation)
- **What makes it dynamic**: Low-code workflow automation with visual builder. Supports AI nodes (LLM, embeddings, etc.) and can orchestrate agent-based workflows.
- **Why include**: Extremely popular; easy to use; large node library; can handle AI agent workflows with community nodes.
- **URL**: https://github.com/n8n-io/n8n

## 12. Open Dynamic Workflows (ODW)

- **Repo**: [Suraj1235/open-dynamic-workflows](https://github.com/Suraj1235/open-dynamic-workflows)
- **Stars**: ~3 | **License**: MIT | **Lang**: JavaScript
- **Category**: DW / MA
- **What makes it dynamic**: Script-as-orchestrator engine for dynamic multi-agent workflows. Each agent runs as an independent subprocess, with phases and dependencies managed by the runtime. Supports fan-out, parallel execution, and custom adapters.
- **Why include**: The core engine CFDW is built on; lightweight; truly dynamic (agents are spawned per phase); ideal for cache-first strategies.
- **URL**: https://github.com/Suraj1235/open-dynamic-workflows

## 13. IBM/awesome-agentic-workflow-optimization

- **Repo**: [IBM/awesome-agentic-workflow-optimization](https://github.com/IBM/awesome-agentic-workflow-optimization)
- **Stars**: ~62 | **License**: Apache-2.0 | **Lang**: N/A (curated list + survey paper)
- **Category**: OP
- **What makes it dynamic**: Survey paper "From Static Templates to Dynamic Runtime Graphs: A Survey of Workflow Optimization for LLM Agents." Curated list of papers, methods, and systems for optimizing dynamic agent workflows.
- **Why include**: Provides academic grounding; helps identify state-of-the-art in workflow optimization (scheduling, caching, cost-awareness).
- **URL**: https://github.com/IBM/awesome-agentic-workflow-optimization

## 14. GATES

- **Repo**: [yashenCS/GATES](https://github.com/yashenCS/GATES)
- **Stars**: ~26 | **License**: Apache-2.0 | **Lang**: Python
- **Category**: OP
- **What makes it dynamic**: Cost-aware dynamic workflow scheduling via Graph Attention Networks and Evolution Strategy (IJCAI 2025). Optimizes task-to-worker assignment in dynamic workflows.
- **Why include**: Research on optimizing cost in dynamic multi-agent workflows; relevant to cache-first strategies.
- **URL**: https://github.com/yashenCS/GATES

## 15. Junjo

- **Repo**: [mdrideout/junjo](https://github.com/mdrideout/junjo)
- **Stars**: ~20 | **License**: Apache-2.0 | **Lang**: Python
- **Category**: DW / AG
- **What makes it dynamic**: AI graph workflow library for building dynamic LLM-driven workflows. Pure Python, no-code-ish, with support for complex DAG structures.
- **Why include**: Simple graph-based workflow definition; good for prototyping LLM chains with dynamic branching.
- **URL**: https://github.com/mdrideout/junjo

## 16. Branch-Thinking MCP

- **Repo**: [ssdeanx/branch-thinking-mcp](https://github.com/ssdeanx/branch-thinking-mcp)
- **Stars**: ~15 | **License**: MIT | **Lang**: TypeScript
- **Category**: AG / DW
- **What makes it dynamic**: MCP server for managing parallel branches of thought, semantic cross-references, and persistent tasks. Dynamic scoring, AI-generated insights, batch operations, and visual graph navigation.
- **Why include**: Novel approach to parallel reasoning branches; integrates with MCP ecosystem.
- **URL**: https://github.com/ssdeanx/branch-thinking-mcp

---

## Summary Statistics

| # | Project | Stars | License | Category | Primary Language |
|---|---------|-------|---------|----------|-----------------|
| 1 | Microsoft Agent Framework | ~11,250 | MIT | MA/WF | Python, .NET |
| 2 | Solace Agent Mesh | ~4,870 | Apache-2.0 | MA | Python |
| 3 | Claude Code Workflow | ~2,100 | MIT | MA/DW | TypeScript |
| 4 | Orra | ~243 | MPL-2.0 | WF/MA | Go, Python, JS |
| 5 | CraftGen | ~314 | AGPL-3.0 | LP/DW | TypeScript |
| 6 | LangGraph | ~5,000+ | MIT | DW/AG | Python |
| 7 | CrewAI | ~25,000+ | MIT | MA | Python |
| 8 | AutoGen | ~35,000+ | MIT | MA | Python |
| 9 | Temporal | ~13,000+ | MIT | WF | Go, many SDKs |
| 10 | Prefect | ~18,000+ | Apache-2.0 | WF | Python |
| 11 | n8n | ~55,000+ | Fair-code | LP | TypeScript |
| 12 | Open Dynamic Workflows | ~3 | MIT | DW/MA | JavaScript |
| 13 | IBM awesome-agentic-workflow-optimization | ~62 | Apache-2.0 | OP | N/A |
| 14 | GATES | ~26 | Apache-2.0 | OP | Python |
| 15 | Junjo | ~20 | Apache-2.0 | DW/AG | Python |
| 16 | Branch-Thinking MCP | ~15 | MIT | AG/DW | TypeScript |

---

## Key Takeaways for awesome-dynamic-workflows

1. **Established frameworks** (AutoGen, CrewAI, LangGraph, Microsoft Agent Framework) provide general multi-agent orchestration.
2. **Production workflow engines** (Temporal, Prefect, n8n) can be adapted for AI agent workflows but lack native agent semantics.
3. **Dynamic workflow optimization** is an active research area (IBM survey, GATES) focusing on scheduling and cost reduction.
4. **Event-driven architectures** (Solace Agent Mesh) offer scalability and loose coupling for multi-agent systems.
5. **Cache-first dynamic workflow** (ODW + CFDW) occupies a unique niche: lightweight, cost-optimized with prompt caching, and observable via dashboard.
6. **Skill-based and role-based systems** (CCW, Swarms, Lux) allow modular agent composition.
7. **Low-code platforms** (CraftGen, n8n) lower the barrier for non-developers to build AI workflows.

This list should be kept current as the ecosystem evolves rapidly. PRs and issues welcome.
