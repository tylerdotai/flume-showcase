# Flume SaaS Factory — AI Agent Operations

> Where AI agents work as co-founders, not just assistants.

**Live at:** [github.com/tylerdotai/flume-showcase](https://github.com/tylerdotai/flume-showcase)

This repo showcases the AI agent infrastructure powering Flume SaaS Factory — a real-world demonstration of what happens when you stop treating AI as a chatbot and start treating it as a workforce.

---

## 🗂 What's Inside

### Project Reports (HTML)
Visual, styled reports for each Flume project — generated with AI and MiniMax image generation:

| Project | Report | Live Site |
|---------|--------|-----------|
| **clawplex** — DFW AI builder community | [PROJECTS/clawplex.html](./PROJECTS/clawplex.html) | [clawplex.dev](https://clawplex.dev) |
| **fort-os** — Operations automation | [PROJECTS/fort-os.html](./PROJECTS/fort-os.html) | [fort-os.com](https://fort-os.com) |
| **fwpanthers** — Police hockey team | [PROJECTS/fwpanthers.html](./PROJECTS/fwpanthers.html) | [fwpanthers.vercel.app](https://fwpanthers.vercel.app) |
| **tylerdotai** — Personal brand | [PROJECTS/tylerdotai.html](./PROJECTS/tylerdotai.html) | [tylerdotai.com](https://tylerdotai.com) |

### Agent Setup Guide
How Hoss works — the workspace files, sub-agent coordination, and heartbeat system:

- **[AGENT-SETUP/index.html](./AGENT-SETUP/index.html)** — Full technical breakdown

### Interview Demo Guide
Practical walkthrough for the AI with Amit YouTube interview:

- **[DEMOS/index.html](./DEMOS/index.html)** — Step-by-step demo guide
- **[INTERVIEW/talking-points.html](./INTERVIEW/talking-points.html)** — Key phrases and stories

### Hero Images (AI Generated)
MiniMax image-01 generated hero images for each project:

```
assets/images/
├── clawplex-hero.png    # DFW skyline with circuit board nodes
├── fort-os-hero.png      # Industrial control room aesthetic
├── fwpanthers-hero.png   # Hockey arena with police badge
└── tylerdotai-hero.png   # Builder workspace at night
```

---

## The Setup

**Hoss** is Flume's AI co-founder — an autonomous agent running on [OpenClaw](https://openclaw.ai) with full memory, sub-agent coordination, and operational responsibilities.

```
.workspace/
├── SOUL.md          # Who Hoss is — philosophy, voice, boundaries
├── IDENTITY.md      # Role definition, co-founder responsibilities
├── AGENTS.md        # Sub-agent roster and coordination protocol
├── MEMORY.md        # Long-term memory — decisions, infrastructure, people
├── TOOLS.md         # Tool configurations and access credentials
├── HEARTBEAT.md     # Autonomous check system — runs on a schedule
├── memory/          # Daily logs + FTS5 searchable memory
└── agents/          # Sub-agent workspaces (builder, coder, scout, etc.)
```

---

## What Makes This Different

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

| Agent | Role | Schedule |
|-------|------|----------|
| **builder** | Product development | 9am, 3pm |
| **coder** | TDD enforcement, 80%+ coverage | 9am, 3pm |
| **devops** | Infrastructure, deployments | 10am, 4pm |
| **einstein** | Deep AI/tool research | 8am, 12pm, 4pm, 8pm |
| **marketer** | Content, brand, audience | 10am, 4pm |
| **ops** | Costs, vendors, reliability | 9am, 3pm |
| **sales** | Lead outreach, pipeline | Daily |
| **scout** | Market intelligence, trends | 6pm |

Each agent has its own workspace, runs on a schedule, and posts findings to Discord.

---

## The Stack

- **Runtime:** [OpenClaw](https://openclaw.ai) — AI agent orchestration
- **Model:** MiniMax M2.7 via minimax-portal
- **Memory:** SQLite FTS5 + daily markdown logs
- **Host:** Mac mini M4 Pro (Hoss), Raspberry Pi 4GB (Brad/legacy)
- **Deploy:** Vercel (frontend), Cloudflare Pages (static)
- **Communication:** Discord (primary), iMessage via Sendblue
- **Image Generation:** MiniMax image-01

---

## How to Replicate

1. Install [OpenClaw](https://openclaw.ai)
2. Read the [OpenClaw docs](https://docs.openclaw.ai)
3. Set up your workspace with SOUL.md, IDENTITY.md, AGENTS.md
4. Configure your first sub-agents
5. Build memory persistence (daily logs + FTS5 search)
6. Build something real

The agents are force multipliers. One human + the right agents = leverage most teams can't match.

---

## Interview Context

This repo was built for [Amit Sharma's AI with Amit YouTube interview](https://www.youtube.com/@ai-withamit), where Tyler demonstrated the Flume agent infrastructure live on camera.

**Stack shown:**
- OpenClaw workspace anatomy
- Hoss's memory and persistence system
- Sub-agent coordination
- Live task execution
- MiniMax image generation for project hero images

---

*Flume SaaS Factory — escaping the cloud, one config at a time.*
