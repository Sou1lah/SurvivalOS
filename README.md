# 🚀 AI Agent Development - Ultimate Starter Kit

Welcome to the AI Agent Development Starter Kit. This workspace has been initialized with a curated set of verified repositories addressing core agent challenges: **Architecture**, **Memory**, **Token Optimization**, **Context Compression**, and **Continuous Diagnostics**.

All resources are cloned and organized in the [`refrence/resources/`](./refrence/resources/) directory.

---

## 🗺️ Workspace Map

```
Survival app/
├── refrence/
│   └── resources/
│       ├── agent-memory/                      # SQLite-first memory layer with BM25/vector search
│       ├── agent-skills-for-context-eng.../  # 15 conditional context-engineering skills
│       ├── agent-stack/                       # Token-efficient workspace setup tool
│       ├── agent-trace-ops/                   # Latency & token tool-call chain optimizer
│       ├── agentmemory/                       # Comprehensive memory framework (Short/Long/Episodic/Semantic)
│       ├── bee-agent-framework/               # Production multi-agent framework (TS/Python)
│       ├── claude-agent-framework/            # Pre-built agent patterns (Critic-Actor, Pipeline, etc.)
│       ├── context-compress/                  # Semantic compression of instructions & CLAUDE.md
│       ├── ham/                               # Hierarchical agent memory context-scoping
│       ├── headroom/                          # Local-first context compression layer proxy
│       ├── Intelligent-Memory-Management.../  # Plug-and-play memory with Qdrant & importance scoring
│       ├── mem/                               # Local-first ChromaDB universal agent memory
│       ├── multi-agent-ai-architecture/       # Scalable service-oriented plugin architecture
│       ├── repomix/                           # Codepack packager for LLM ingestion
│       ├── soul-agent-framework/              # Markdown-driven agent configurations (SOUL/skills)
│       ├── token-optimizer/                   # Ghost-token remover and session compaction optimizer
│       └── TokenJam/                          # Diagnostic token & cost optimization tool
├── agents.md                                  # Antigravity agent & token laws
└── README.md                                  # This guide
```

---

## 🧭 Navigation Pathways

Select your development pathway to determine how to leverage these resources:

### 🎒 Pathway A: Editor-Based Agents (e.g., Cursor, Claude Code, Aider)
If you are developing inside an IDE assistant and want to reduce cost/bloat:
- **Optimization Hooks**: Use `token-optimizer` to prune retry loops, redundant system prompts, and verbose terminal outputs.
- **Instruction Scoping**: Set up `context-compress` to strip boilerplate from your `CLAUDE.md` and custom instructions, and run `ham` to split files by directory.
- **Workspace Packer**: Use `repomix` to package parts of your repository into single files for manual upload to chat windows or LLMs.

### 🌐 Pathway B: Custom Autonomous Backends (e.g., Custom SDKs, Multi-Agent Platforms)
If you are building your own agent system (using frameworks like LangChain, AutoGen, or custom run loops):
- **Middleware Proxy**: Run `headroom` as a proxy layer between your backend and the LLM API to compress JSON payloads, logs, and agent outputs automatically.
- **Agent Architectures**: Model your agent structure on `claude-agent-framework` (Debate, Specialist Pool, Critic-Actor patterns) or the service-oriented contracts in `multi-agent-ai-architecture`.
- **Dynamic Context**: Integrate `agent-skills-for-context-engineering` to dynamically load system prompt instructions only when matching conditions are met.

### 🪐 Pathway C: Google Antigravity & Agentic Workspaces
If you are developing inside Google Antigravity or running agent-first workflows:
- **Agent Rules**: Configure [agents.md](file:///home/wael/Survival%20app/agents.md) in your workspace root to auto-enforce token boundaries, progressive file discovery, and sub-agent directory scoping.
- **Resource Routing**: Direct your agents to resolve features locally inside `./refrence/resources/` instead of spinning up external web searches or parsing deep files recursively.

---

## 🧠 Memory Management Repositories

| Repository | GitHub Link | Main Use-Case / Features |
| :--- | :--- | :--- |
| **agentmemory** | [hanishkeloth/agentmemory](https://github.com/hanishkeloth/agentmemory) | Multi-type memory (Short-term, Long-term, Episodic, Semantic, Procedural) with semantic search & auto-consolidation. |
| **agent-memory** | [smysle/agent-memory](https://github.com/smysle/agent-memory) | SQLite-first memory layer. Hybrid BM25/vector search, semantic decay, memory links, and provenance tracking. CLI/MCP/HTTP support. |
| **mem** | [obicho/mem](https://github.com/obicho/mem) | Local-first ChromaDB universal memory supporting auto-chunking, multi-modal files (PDFs, chats, image captioning). |
| **Intelligent Memory Management** | [SRafi007/Intelligent-Memory-Management...](https://github.com/SRafi007/Intelligent-Memory-Management-for-AI-Applications) | Qdrant vectorized long-term & TTL short-term memory with deduplication, importance scoring, and visualization. |

---

## 🏗️ Architecture & Frameworks

| Repository | GitHub Link | Key Architecture Patterns |
| :--- | :--- | :--- |
| **bee-agent-framework** | [syntax-syndicate/bee-agent-framework](https://github.com/syntax-syndicate/bee-agent-framework) | Production multi-agent framework featuring workflow serialization, caching, requirements agents, RAG, and MCP protocols. |
| **claude-agent-framework** | [uukuguy/claude-agent-framework](https://github.com/uukuguy/claude-agent-framework) | **7 Pre-built Patterns**: Research, Pipeline, Critic-Actor, Specialist Pool, Debate, Reflexion, and MapReduce. |
| **soul-agent-framework** | [mingrath/soul-agent-framework](https://github.com/mingrath/soul-agent-framework) | Markdown-driven configurations (`SOUL.md`, `MEMORY.md`, `AGENTS.md`) using a two-tier memory architecture. |
| **multi-agent-ai-architecture** | [Zeeshan138063/multi-agent-ai-architecture](https://github.com/Zeeshan138063/multi-agent-ai-architecture) | Scalable service-oriented design with async messaging, hot-swappable components, and interface-driven contracts. |

---

## ⚡ Token & Context Optimization

| Repository | GitHub Link | Core Optimization Techniques |
| :--- | :--- | :--- |
| **agent-stack** | [drmahdikazempour/agent-stack](https://github.com/drmahdikazempour/agent-stack) | One-command token setup generating codebase maps, output compression (ANSI/duplicate folding), and structural savings. |
| **TokenJam** | [Metabuilder-Labs/TokenJam](https://github.com/Metabuilder-Labs/TokenJam) | Telemetry analyzer targeting prompt caching breakpoints, deterministic script suggestions, model downsizing, and drift alerts. |
| **ham** | [kromahlusenii-ops/ham](https://github.com/kromahlusenii-ops/ham) | Hierarchical Agent Memory that scopes context per directory level, saving thousands of start-context tokens. |
| **agent-trace-ops** | [peerbot-ai/agent-trace-ops](https://github.com/peerbot-ai/agent-trace-ops) | Tool-call chain analyzer proposing parameterized scripts, file refactoring, and makefile optimizations to cut cost/latency. |

---

## 🗜️ Context Compression & Prompt Optimizers

| Repository | GitHub Link | Core Optimization Techniques |
| :--- | :--- | :--- |
| **headroom** | [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) | Local proxy layer that compresses outputs/JSON by 60-95% using Content-Compressed Retrieval (CCR) and reversibility. |
| **context-compress** | [vidanov/context-compress](https://github.com/vidanov/context-compress) | Dynamic compression of steering prompt markdown instruction files via validation and A/B testing loops. |
| **token-optimizer** | [alexgreensh/token-optimizer](https://github.com/alexgreensh/token-optimizer) | Removes "ghost tokens" from context compactions, compacts stale loop state, and monitors token/cost savings deltas. |
| **agent-skills-for-context-engineering** | [muratcankoylan/agent-skills-for-context-engineering](https://github.com/muratcankoylan/agent-skills-for-context-engineering) | Collection of 15 contextual optimization skills that load conditionally to keep LLM context clean and poison-free. |
| **repomix** | [yamadashy/repomix](https://github.com/yamadashy/repomix) | Codebase packer tool that strips whitespace and outputs a single, highly structured, LLM-digestible code representation. |

---

## 🛠️ Getting Started Quick Commands

### 1. Bundle Your Codebase with `repomix`
Create a structured package of your codebase to feed into external LLMs or chat consoles:
```bash
npx repomix
```

### 2. Compress Prompt Files with `context-compress`
Optimize a system prompt or instruction markdown file down to its semantic core:
```bash
cd refrence/resources/context-compress
python -m context_compress compress --file /path/to/CLAUDE.md
```

### 3. Setup Proxy Compression with `headroom`
Run headroom-ai locally to proxy and intercept API calls to compress large text inputs:
```bash
pip install headroom-ai
# Start local headroom daemon
headroom start
```

### 4. Optimize Workspace with `agent-stack`
Set up code maps, `.claudeignore`, and token configurations for the current codebase:
```bash
npx @drmahdikazempour/agent-stack init --all
```

### 5. Context Directory Scoping with `ham`
Generate local, scoped memory contexts across directories to prune starting prompts:
```bash
go ham
```

### 6. Profiling Costs & Telemetry with `TokenJam`
Launch the local optimization dashboard:
```bash
pipx install tokenjam
tj onboard --claude-code
tj serve
```
Access the dashboard at [http://127.0.0.1:7391/](http://127.0.0.1:7391/).
# SurvivalOS
