# Taxonomy of Dynamic Workflow Applications

A classification system for organizing an awesome list of dynamic workflow tools, frameworks, and practices.

## 1. Core Categories

### 1.1 Workflow Engines & Orchestrators

Durable execution engines that manage state, retries, and scaling of distributed workflows.

**Examples:**
- **Conductor OSS** — Netflix-originated, DAG-based, supports dynamic forks, LLM tasks, MCP tools, durable execution (Apache 2.0, Java)
- **Temporal** — Durable execution with replay, long-running workflows, SDKs in multiple languages
- **Flyte 2** — ML pipeline orchestration, pure Python, async task execution, K8s-native (Apache 2.0, Python/Go)
- **Prefect** — Python workflow orchestration for data pipelines with dynamic scheduling (Apache 2.0, Python)

**Inclusion criteria:**
- Durable state persistence across failures
- Declarative or programmatic workflow definition
- Support for retries, timeouts, and recovery
- Horizontal scalability

**Quality signals:**
- Production deployments at scale
- Active maintenance with regular releases
- Comprehensive documentation and SDKs

### 1.2 Agent Frameworks & Multi-Agent Systems

Frameworks for building autonomous agents that can reason, use tools, and collaborate.

**Examples:**
- **OpenAI Agents SDK** — Lightweight multi-agent orchestration, handoffs, guardrails, sandbox agents (MIT, Python)
- **Langflow** — Visual builder for AI agents, drag-and-drop components, multi-agent orchestration (MIT, Python)
- **Jido** — Elixir agent framework, immutable state, directive-based effects, OTP-native, FSM strategies (Apache 2.0, Elixir)
- **OpenRath** — Torch-like API for dynamic multi-agent workflows (BSD-3-Clause, Python)
- **Ruflo** — Meta-harness for Claude, multi-agent swarms, adaptive memory, self-learning (MIT, TypeScript)
- **AutoGen** — Multi-agent conversation framework with dynamic team formation (MIT, Python)
- **CrewAI** — Role-based multi-agent orchestration (MIT, Python)
- **Microsoft Agent Framework** — Graph-based production-grade orchestration (MIT, Python/.NET)

**Inclusion criteria:**
- Agent abstraction with instructions, tools, and memory
- Multi-agent coordination (handoffs, broadcasts, hierarchies)
- Provider-agnostic or supports multiple LLMs
- Observable execution (tracing, debugging)

### 1.3 Low-Code / Visual Workflow Platforms

GUI-driven tools for building automations without coding.

**Examples:**
- **Dify** — Production platform for agentic workflow development, visual LLM app builder (TypeScript)
- **ToolJet** — Open-source internal tool builder with workflow automation, drag-and-drop UI (AGPL-3.0, JavaScript)
- **n8n** — Technical workflow automation with visual editor (Sustainable Use License, TypeScript)
- **CraftGen** — Open-source no-code AI agent platform with visual canvas (AGPL-3.0, TypeScript)

**Inclusion criteria:**
- Visual drag-and-drop interface
- Integration with common APIs and services
- Self-hostable or cloud option
- Extensibility via custom nodes/code

### 1.4 Agentic Coding Agents & Terminal Workflows

CLI-based AI agents that assist with coding, code review, and automation directly in the terminal.

**Examples:**
- **Claude Code** — Agentic coding tool by Anthropic, terminal-native, understands codebase, executes routine tasks
- **Whale (DeepSeek-Code-Whale)** — ~98% prompt cache hit, DeepSeek-native, TUI/CLI, dynamic workflows in JavaScript, MCP support (MIT, Go)
- **Antigravity Awesome Skills** — 1500+ agentic skills for Claude Code, Cursor, Codex CLI, Gemini CLI (MIT, Python)
- **Patchwork** — Composable patchflows for CLI/CI/CD code automation (AGPL-3.0, Python)

**Inclusion criteria:**
- Terminal or IDE-integrated agent
- Codebase understanding (read/write/edit files)
- Multi-step task execution
- Extensible via skills/plugins

### 1.5 Dynamic Workflow Scripts & Research

Repositories focused on the concept of "dynamic workflows" as a research or experimental topic.

**Examples:**
- **Open Dynamic Workflows** — Script-as-orchestrator engine (MIT, JavaScript)
- **CFDW (Cache-First Dynamic Workflows)** — Cache-first adapter for ODW with usage ledger and dashboard (Non-commercial, TypeScript)
- **Claude Code Workflow** — JSON-driven multi-agent development framework (MIT, TypeScript)

**Inclusion criteria:**
- Explicitly uses "dynamic workflow" terminology
- Novel approach or pattern
- Reproducible examples or research artifacts

## 2. Anti-Patterns (Exclusion Rules)

- **Simple task queues** (e.g., Celery without DAG) — lacks orchestration semantics
- **Single-agent chatbots** — no multi-agent coordination
- **Proprietary SaaS-only** — no open-source or self-hostable option
- **Abandoned projects** — no commits in 12+ months unless historically significant
- **Static workflow definitions only** — no runtime adaptation, dynamic branching, or on-the-fly changes

## 3. Quality Signals for Inclusion

| Signal | Description | Weight |
|--------|-------------|--------|
| Stars ≥ 100 | Community interest | Low |
| Active commits (last 3 months) | Maintenance | Medium |
| Documentation / README quality | Onboarding ease | High |
| License clarity | Legal usability | High |
| Production use evidence | Maturity | High |
| Multi-language SDKs | Integration breadth | Medium |
| Extensibility (plugins, MCP, API) | Customizability | Medium |
| Benchmark / metrics reported | Performance transparency | Medium |

## 4. Additional Dimensions for Classification

- **Backend language** (Go, Java, Python, Elixir, TypeScript, …)
- **Deployment model** (Self-hosted, Cloud, Hybrid)
- **Protocol support** (MCP, A2A, REST, gRPC)
- **LLM provider support** (OpenAI, Anthropic, DeepSeek, Gemini, Ollama, …)
- **Persistence backend** (Postgres, Redis, SQLite, S3, …)
- **License** (MIT, Apache 2.0, AGPL, Other)
- **Primary use case** (ML/Data, Automation, Agent, Research, Coding)

## 5. How to Use This Taxonomy

When adding an entry to the awesome list:
1. Identify the **primary category** (1.1–1.5)
2. Check **anti-patterns** — exclude if any apply
3. Evaluate **quality signals** — should have at least 3 high/medium signals
4. Fill **additional dimensions** for filtering and comparison
5. Write a concise description highlighting unique value

---

*Generated by CFDW research agent for awesome-dynamic-workflows. Updated by synthesis agent.*
