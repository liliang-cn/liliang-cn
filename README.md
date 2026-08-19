# Hi, I'm Liang Li 👋

**AI infrastructure engineer.** I build the plumbing that makes AI agents actually
work in production — agent frameworks, vector & knowledge-graph memory, MCP tool
servers, and local-LLM integration. Mostly **Go** and **Rust**.

📍 Chengdu, China · 🌐 Remote · 💬 中文 / English

> **🟢 Available for full-time remote & contract work** — AI agents, RAG & knowledge
> graphs, MCP integrations, and LLM-powered automation. If you need an LLM wired
> into your real systems (not just a chatbot), let's talk → **ll_faw@hotmail.com**

---

## What I build

### 📊 Governed data access for AI agents
- **[dataintelligence](https://github.com/liliang-cn/dataintelligence)** ⭐ — a governed semantic layer + MCP gateway that makes your data warehouse safe for AI agents. Agents ask for a *metric by dimensions* — never raw SQL — so wrong joins, wrong grains, and fan-out inflation are blocked structurally, not by prompting. Built on the libraries below: agent-go, cortexdb, eval-go, and semantic-go.
- **[semantic-go](https://github.com/liliang-cn/semantic-go)** — the semantic-layer compiler underneath: declare metrics/dimensions/joins once in YAML, compile to fan-out/chasm-safe SQL.

### 🤖 Agent frameworks & orchestration
- **[harness-rs](https://github.com/liliang-cn/harness-rs)** — a Rust agent framework: ReAct loop, pluggable tools & skills, cross-session recall, a self-evolving learning loop, scheduler, sandbox, and an MCP client/server. Published on crates.io as the `harness-rs-*` crates.
- **[agent-go](https://github.com/liliang-cn/agent-go)** — an AI Agent SDK designed for Go developers (teams, tasks, memory, MCP, tool calling).
- **[tagit](https://github.com/liliang-cn/tagit)** — an open-source, self-hosted Claude Tag: @mention an AI agent in your team chat, get auditable work back.
- **[oss-agent](https://github.com/liliang-cn/oss-agent)** — a product-agnostic platform for AI ops & support agents over an OSS project: GraphRAG knowledge base, ReAct agent, and a deterministic red-line safety wall. The whole domain comes from one `domain.toml`.
- **[agentcli](https://github.com/liliang-cn/agentcli)** — an app-agnostic Go core for driving the Claude Code / Codex / Gemini CLIs: command building, stream-json parsing, usage accounting, PTY runner, hooks.

### 🧪 Evaluation — know when your agent is wrong
- **[eval-go](https://github.com/liliang-cn/eval-go)** — a native-Go LLM/RAG/agent evaluation framework: deterministic + LLM-as-judge metrics, `go test` integration, red-teaming, CI regression gates. The Go answer to DeepEval/RAGAS.
- **[testtui](https://github.com/liliang-cn/testtui)** — test TUIs, CLIs and agentic terminal apps via PTY + VT100 emulation: declarative YAML cases, an AI layer (harness-rs), and an MCP server.

### 🖥️ Rendering agent output
- **[superai-desktop](https://github.com/liliang-cn/superai-desktop)** — a cross-platform Wails v2 desktop assistant and full showcase of agent-go: sandbox + browser + vision + autonomy + graph memory + skills, plus an SSE emotion protocol that drives external 2D/3D avatars (Live2D / VRM / Unity).
- **[aigui](https://github.com/liliang-cn/aigui)** — a framework-agnostic TypeScript SDK that renders streaming LLM output as live UI: progressive markdown, cards, charts, math, and diagrams, with React / Vue / vanilla adapters.

### 🧠 Memory, knowledge graphs & RAG
- **[cortexdb](https://github.com/liliang-cn/cortexdb)** ⭐ — a pure-Go, single-file AI memory & knowledge-graph library: vector + hybrid (BM25/FTS5) search, GraphRAG, and one-pass structured-data import. Zero external services, fully embedded.
- **[askdoc](https://github.com/liliang-cn/askdoc)** — ask questions over your own documents (RAG).

### 🔌 MCP servers — connect anything to an AI agent
- **[mcp-swagger-server](https://github.com/liliang-cn/mcp-swagger-server)** — turn any Swagger / OpenAPI spec into ready-to-use MCP tools.
- **[mcp-websearch-server](https://github.com/liliang-cn/mcp-websearch-server)** — multi-engine web search with content extraction.
- **[mcp-sqlite-server](https://github.com/liliang-cn/mcp-sqlite-server)** · **[mcp-snapshot-server](https://github.com/liliang-cn/mcp-snapshot-server)**

### ⚙️ Local-LLM & infrastructure tooling
- **[ollama-go](https://github.com/liliang-cn/ollama-go)** — a Go client library for Ollama.
- **[lmstudio-go](https://github.com/liliang-cn/lmstudio-go)** — a Go client for LM Studio: chat, embeddings, tool calling, model management.
- **[ollama-queue](https://github.com/liliang-cn/ollama-queue)** — a high-performance task queue for Ollama models.
- **[gosible](https://github.com/liliang-cn/gosible)** · **[dispatch](https://github.com/liliang-cn/dispatch)** — infrastructure & multi-server automation in Go.

---

## Tech I work with

`Go` · `Rust` · `TypeScript / React` · LLMs (OpenAI-compatible, Anthropic, Gemini, Ollama, LM Studio) · RAG & vector search · knowledge graphs · **MCP (Model Context Protocol)** · SQLite

## Let's work together

I'm best at taking an LLM from "demo" to "running unattended inside your
systems": ingest your data, wire up the tools/APIs it needs (via MCP), and ship
an agent that does the work — on a schedule, with guardrails.

📧 **ll_faw@hotmail.com** · 🐙 [github.com/liliang-cn](https://github.com/liliang-cn)
