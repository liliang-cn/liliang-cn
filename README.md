# Hi, I'm Liang Li 👋

**AI infrastructure engineer.** I build the plumbing that makes AI agents actually
work in production — agent frameworks, vector & knowledge-graph memory, MCP tool
servers, and local-LLM integration. Mostly **Go** and **Rust**.

📍 Chengdu, China · 🌐 Remote · 💬 中文 / English

> **🟢 Available for freelance / contract work** — AI agents, RAG & knowledge
> graphs, MCP integrations, and LLM-powered automation. If you need an LLM wired
> into your real systems (not just a chatbot), let's talk → **ll_faw@hotmail.com**

---

## What I build

### 🤖 Agent frameworks & orchestration
- **[harness-rs](https://github.com/liliang-cn/harness-rs)** — a Rust agent framework: ReAct loop, pluggable tools & skills, cross-session recall, a self-evolving learning loop, scheduler, sandbox, and an MCP client/server. Published on crates.io as the `harness-rs-*` crates.
- **[agent-go](https://github.com/liliang-cn/agent-go)** — an AI Agent SDK designed for Go developers (teams, tasks, memory, MCP, tool calling).
- **[roma](https://github.com/liliang-cn/roma)** — Runtime Orchestrator for Multi-Agents.

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
