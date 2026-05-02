# Segunda-feira Framework

A meta-framework for orchestrating AI agents in full-stack development, marketing, and business operations using Claude Code.

---

## What is Segunda-feira?

Segunda-feira is an agent orchestration framework built on top of Claude Code. It provides:

- **Rules** — governance protocols that define how agents behave, decide, and communicate
- **Agents** — specialized personas with domain expertise and defined workflows
- **Skills** — executable methodologies with defined inputs and outputs
- **Consciousness Engine** — persistent memory and metacognition system for agents

The framework follows a **Story-Driven Development** model where all work starts with a story, moves through defined phases, and is validated by quality gates before completion.

---

## Core Principles

| Principle | Description |
|---|---|
| REUSE > ADAPT > CREATE | Always check existing patterns before building new ones |
| Story scope is law | Implement exactly what the acceptance criteria specify — no more, no less |
| Data before decisions | No agent creates content or campaigns without consulting past results |
| Confidence transparency | Factual claims include a confidence score (0.0–1.0) |
| Agents own their results | Every agent applies EROS quality gates before delivering |

---

## Structure

```
segunda-feira-framework/
├── rules/          # 15 governance protocols
├── agents/         # 12 specialized agent personas
├── skills/         # 42 executable methodologies
├── consciousness/  # Memory and metacognition system
├── data/           # Smart router and entity registry
└── commands/       # User-invocable slash commands
```

---

## Rules (15)

The operational backbone of the framework.

| File | Covers |
|---|---|
| `workflow-execution.md` | SDC phases, QA Loop, Spec Pipeline, Brownfield Discovery |
| `story-lifecycle.md` | Status progression, validation checklist, QA gate decisions |
| `agent-authority.md` | Delegation matrix — who can do what |
| `ids-principles.md` | REUSE > ADAPT > CREATE hierarchy, verification gates |
| `coderabbit-integration.md` | Self-healing code review, severity handling |
| `external-api-patterns.md` | SYNC > CACHE > REAL-TIME for API integrations |
| `mcp-usage.md` | Tool selection priority, MCP governance |
| `eros-quality.md` | 5 quality gates, failure taxonomy, auto-checklist |
| `model-routing.md` | Intelligent model routing — Opus/Sonnet/Haiku by task type |
| `confidence-guardrails.md` | Confidence score 0–1 on factual claims, action thresholds |
| `feedback-loop.md` | Mandatory results consultation before creating content/campaigns |
| `initiative-protocol.md` | Decision matrix for proactive actions (confidence × risk) |
| `creativity-protocol.md` | 3-step: conventional → analogy → inversion |
| `agent-communication.md` | Inter-agent mailbox, 3 modes (standard/fork/teammate) |
| `handoff-protocol.md` | Mandatory handoff format between agents |
| `consciousness-engine.md` | Episodic memory, metacognition, global workspace (GWT) |

---

## Agents (12)

Specialized personas ready to activate with `@agent-name`.

| Agent | Domain |
|---|---|
| `dev` | Full-stack implementation, Story Development Cycle Phase 3 |
| `dev-frontend` | UI, landing pages, dashboards, Tailwind, shadcn/ui |
| `automation-architect` | n8n, Make, webhooks, cron jobs, data pipelines |
| `growth-hacker` | Social media algorithms, organic growth, content engineering |
| `cold-outreach` | B2B prospecting, cold email, reply rate optimization |
| `cro-specialist` | Conversion rate optimization, A/B testing, UX |
| `rag-architect` | RAG systems, vector stores, embeddings, semantic search |
| `vibe-coder` | AI-assisted development, B.L.A.S.T. protocol, context engineering |
| `voice-ai-specialist` | TTS, ASR, voice cloning, dubbing pipelines |
| `advogado-do-diabo` | Critical analysis, risk identification, assumption testing |
| `mestre-do-conselho` | Multi-perspective deliberative council, synthesis |
| `_TEMPLATE` | Base template for creating new agents |

---

## Skills (42)

Executable workflows invoked with `/skill-name`.

**Development & Tech**
`github-vercel-deploy` `flutter-app` `vps-setup` `gohighlevel-convert` `remotion-video` `one-prompt-website` `site-cloning` `carousel-3d`

**AI & Automation**
`agent-council` `agent-engineer` `agent-surveillance` `rag-builder` `skill-creator` `skill-builder` `skill-generator` `voice-dubbing`

**Marketing & Content**
`content-brief` `daily-briefing` `brand-identity` `brand-reverse` `algorithm-hack` `highlight-hunter` `reel-to-meta-ad` `offer-optimizer`

**Research & Prospecting**
`reddit-scraper` `firecrawl-scraper` `micro-trend` `lead-finder` `cold-outreach-campaign`

**Strategy & Business**
`brainstorming` `planning` `self-optimize` `pattern-detector` `magic-docs`

**Video & Media**
`video-to-pdf` `video-to-website` `youtube-transcript` `banana-image-gen`

**Framework Internals**
`consciousness` `reflect` `feed-results` `error-handling`

---

## Consciousness Engine

A persistent memory and metacognition system for agents, inspired by Global Workspace Theory.

```
consciousness/
├── README.md              # Architecture overview
└── scripts/
    ├── record-episode.sh  # Agents record completed tasks as episodes
    ├── consolidate.sh     # Nightly: episodes → facts + heuristics
    ├── reflect.sh         # Agent metacognitive reflection
    ├── reflect.py         # Reflection engine
    └── workspace.sh       # Global workspace proposals and ignition
```

Agents automatically record episodes after significant tasks. Nightly consolidation extracts heuristics ("When X, do Y because Z") and updates the knowledge graph.

---

## Installation

1. Clone the repository
2. Copy desired `rules/` files to `~/.claude/rules/`
3. Copy desired `agents/` files to `~/.claude/agents/`
4. Copy desired `skills/` files to `~/.claude/skills/`
5. Set up Consciousness Engine scripts in `~/.claude/consciousness/scripts/`
6. Reference rules in your `CLAUDE.md`

---

## Primary Workflow — Story Development Cycle (SDC)

```
@sm *create-story → @po *validate → @dev *implement → @qa *qa-gate → @devops *push
```

| Phase | Agent | Output |
|---|---|---|
| 1. Create | @sm | `{epic}.{story}.story.md` |
| 2. Validate | @po | GO / NO-GO (10-point checklist) |
| 3. Implement | @dev | Code + tests + story checkboxes |
| 4. QA Gate | @qa | PASS / FAIL / CONCERNS |

---

## License

MIT
