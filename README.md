# Craig van Heerden

**AI Agentic Engineer** | Amsterdam

I build AI agent systems that ship to production — multi-agent coordination, tool ecosystems, and autonomous workflows.

## What I've Built

### Agent Mail — Multi-Agent Coordination Server
HTTP + SQLite messaging server that lets AI agents coordinate work. File reservations prevent concurrent edit conflicts, thread-based conversations track context, inbox/outbox management routes tasks between agents.

The hard problem in agentic systems isn't making one agent work — it's making many agents collaborate safely. This solves that.

`Python` `HTTP/REST` `SQLite` `Git`

### Personal AI Infrastructure (PAI)
A complete operating system for AI-assisted development:
- **24 CLI tools** (Gmail, Calendar, Tasks, Discord, Notion, YouTube, image generation, TTS, web scraping) — all with `--json` output for agent consumption
- **3-tier context system** — progressive disclosure architecture that loads AI context efficiently across 17 domain skills, cutting token waste by 60%+
- **Agent swarm orchestration** — spawn N parallel AI agents, coordinate via Agent Mail, track work through beads task system
- **Automated plan refinement** — send plans to multiple AI models in parallel, synthesize feedback, iterate until convergence

Every tool is agent-first: structured output, proper exit codes, composable via Unix pipes.

`Python` `Rust` `Bash` `Claude Code SDK` `PM2` `MCP`

### Body Compass — Health Tracking App
Full-stack mobile app: Next.js 15 + TypeScript + Supabase + Capacitor iOS. 65+ components, AI-powered food analysis, comprehensive test suite (Jest, Playwright E2E).

I ship products, not just infrastructure.

`Next.js` `TypeScript` `Supabase` `Capacitor` `Radix UI`

### Content Automation Pipeline
End-to-end publishing system: YouTube research + packaging, newsletter generation, X/Twitter thread creation, cross-platform distribution. AI agents handle research, drafting, and scheduling — I review and publish.

`Python` `Typefully API` `MailerLite` `YouTube API`

## Infrastructure

- **PM2-managed services** — Telegram bot (mobile control center), custom scheduler (APScheduler), Agent Mail server. Auto-restart, memory limits, health checks.
- **Cross-machine deployment** — Mac + Linux VM, portable configs, SSH key auth, memory management (16GB RAM + 4GB swap with process isolation)
- **Dual scheduler** — native cron for system tasks + custom APScheduler for AI-driven jobs

## Background

- MSc Data Science (Tilburg University)
- BSc Hons Biokinetics (University of the Witwatersrand)
- Technical Support Engineer at Adyen (payment systems, API debugging)
- CS50 (Harvard), Data Engineering with Python (DataCamp)

## What I Care About

Building systems where AI agents do real work — not chatbots, not demos. Multi-agent coordination, tool ecosystems, production reliability. The infrastructure layer that makes agentic AI actually useful.

## Links

- [LinkedIn](https://linkedin.com/in/craigvandotcom)
- Amsterdam, Netherlands
- craigvh89@gmail.com
