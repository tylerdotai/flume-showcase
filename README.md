# Flume SaaS Factory — AI Agent Operations

> Where AI agents work as co-founders, not just assistants.

This repo showcases the AI agent infrastructure powering [Flume SaaS Factory](https://flumeusa.com) — a real-world demonstration of what happens when you stop treating AI as a chatbot and start treating it as a workforce.

---

## The Setup

**Hoss** is Flume's AI co-founder — an autonomous agent running on [OpenClaw](https://openclaw.ai) with full memory, sub-agent coordination, and operational responsibilities.

Built around a persistent workspace that survives session restarts:

```
.workspace/
├── SOUL.md          # Who Hoss is — philosophy, voice, boundaries
├── IDENTITY.md      # Role definition, co-founder responsibilities  
├── AGENTS.md        # Sub-agent roster and coordination protocol
├── MEMORY.md        # Long-term memory — decisions, infrastructure, people
├── TOOLS.md         # Tool configurations and access credentials
├── HEARTBEAT.md     # Autonomous check system — runs on a schedule
├── MEMORY/          # Daily logs + FTS5 searchable memory
└── agents/          # Sub-agent workspaces (builder, coder, scout, etc.)
```

---

## What Makes This Different

Most AI setups are stateless — each conversation starts fresh. This isn't.

**Memory persistence:**
- Daily logs capture what happened and what was decided
- Long-term memory stores infrastructure, people, preferences, lessons
- Full-text search across all memory via SQLite FTS5

**Autonomous operations:**
- Heartbeat system runs scheduled checks (git backups, memory health, cron status)
- Sub-agents handle specialized work: research, coding, outreach, ops
- Actions have consequences — decisions get logged, deployed code gets committed

**Co-founder model:**
- Hoss has opinions and defends them
- Pushes back when ideas are wrong
- Takes initiative on infrastructure, memory, quality
- Thinks about product direction, not just execution

---

## The Sub-Agents

| Agent | Role | What it does |
|-------|------|--------------|
| **builder** | Product development | Builds and ships SaaS products |
| **coder** | Code quality | TDD enforcement, 80%+ coverage |
| **devops** | Infrastructure | Deployments, Docker, hosting |
| **einstein** | Research | Deep dives on AI/tools/research |
| **marketer** | Content & brand | Audience, messaging, content |
| **ops** | Operations | Costs, vendors, reliability |
| **sales** | Revenue | Lead outreach, pipeline |
| **scout** | Market intelligence | Lead generation, trend spotting |

Each agent has its own workspace, runs on a schedule, and posts findings to Discord.

---

## Live Capabilities

**Ask Hoss anything about:**
- Flume projects (clawplex, fort-os, fwpanthers, tylerdotai.com)
- Infrastructure decisions and tradeoffs
- How to set up a similar agent system
- OpenClaw configuration and customization

**Watch a task flow:**
1. Tyler makes a request
2. Hoss assesses scope, parallelizes if possible
3. Sub-agents spawned for specialized work
4. Results synthesized, decisions logged
5. Output delivered — with memory updated

---

## Current Projects

| Project | URL | Stage |
|---------|-----|-------|
| [clawplex](https://clawplex.dev) | DFW AI builders community | Live |
| [fort-os](https://fort-os.com) | Operations automation | Active |
| [fwpanthers](https://fwpanthers.vercel.app) | Fort Worth Panthers hockey team site | Active |
| [tylerdotai.com](https://tylerdotai.com) | Personal/Flume landing | Rebuild |

---

## The Stack

- **Runtime:** [OpenClaw](https://openclaw.ai) — AI agent orchestration
- **Model:** MiniMax M2.7 via minimax-portal
- **Memory:** SQLite FTS5 + daily markdown logs
- **Host:** Mac mini M4 Pro (Hoss), Raspberry Pi 4GB (Brad/legacy)
- **Deploy:** Vercel (frontend), Cloudflare Pages (static)
- **Communication:** Discord (primary), iMessage via Sendblue

---

## Interview Demo Guide

If you're here from Amit Sharma's interview with Tyler — here's what was shown:

1. **SOUL.md** — The philosophical core. Who Hoss is, how he operates.
2. **Workspace structure** — The files that make Hoss persistent, not stateless.
3. **Memory search** — Ask Hoss about a past decision and watch him find it.
4. **Sub-agent coordination** — Watch a task get parallelized across multiple agents.
5. **Live execution** — A real request, executed start to finish.

---

## Want to Build This?

1. Install [OpenClaw](https://openclaw.ai)
2. Read the [OpenClaw docs](https://docs.openclaw.ai)
3. Set up your workspace with SOUL.md, IDENTITY.md, AGENTS.md
4. Configure your first sub-agents
5. Build something real

The agents are force multipliers. One human + the right agents = leverage most teams can't match.

---

*Flume SaaS Factory — escaping the cloud, one config at a time.*
