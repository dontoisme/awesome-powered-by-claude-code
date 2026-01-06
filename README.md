# Awesome Powered by Claude Code

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of apps designed to **run via Claude Code** as the runtime/interface.

**This is NOT another list of tools FOR Claude Code.** This is a registry of apps that USE Claude Code as the engine — where Claude is the interface you interact with, and local data/services provide persistence.

---

## What "Powered by Claude Code" Means

```
🤖 Powered by Claude Code
```

Apps in this list share a common pattern:
- **Claude Code is the runtime** — You interact through Claude, not a traditional GUI
- **Local-first data** — SQLite, files, or external services (Notion, etc.)
- **SKILL.md or CLAUDE.md** — Instructions that teach Claude how to operate the app
- **Optional CLI** — Binary that Claude executes for data operations

This is analogous to:
- npm → apps for Node.js runtime
- PyPI → apps for Python runtime
- **This list → apps for Claude Code runtime**

---

## Contents

- [Finance & Money](#finance--money)
- [Productivity & Time](#productivity--time)
- [Career & Job Search](#career--job-search)
- [Personal Development](#personal-development)
- [Health & Fitness](#health--fitness)
- [Knowledge Management](#knowledge-management)
- [Communication & Scheduling](#communication--scheduling)
- [Developer Tools](#developer-tools)

---

## Finance & Money

| App | Description | Author |
|-----|-------------|--------|
| [just-fucking-cancel](https://github.com/rohunvora/just-fucking-cancel) | Audits your subscriptions from bank CSV exports, helps you decide what to cancel, and optionally automates the cancellation via browser | [@rohunvora](https://github.com/rohunvora) |
| [Claude-Budget-Workspace-Template](https://github.com/danielrosehill/Claude-Budget-Workspace-Template) | Household budget management with 6 specialized agents: Budget-Architect, Expense-Analyst, Goal-Tracker, Transaction-Processor, Report-Generator, Financial-Advisor | [@danielrosehill](https://github.com/danielrosehill) |

## Productivity & Time

| App | Description | Author |
|-----|-------------|--------|
| [pomodoro](https://github.com/jakedahn/pomodoro) | Reference implementation of the System Skill Pattern — Pomodoro timer with CLI + SKILL.md + SQLite that learns your productivity patterns over time | [@jakedahn](https://github.com/jakedahn) |

## Career & Job Search

| App | Description | Author |
|-----|-------------|--------|
| [resume-tailoring-skill](https://github.com/varunr89/resume-tailoring-skill) | AI-powered resume customization with multi-job batch processing, confidence-scored matching, and interview prep reports | [@varunr89](https://github.com/varunr89) |
| [cc-job-tailor](https://github.com/javiera-vasquez/cc-job-tailor) | Analyzes job postings, extracts weighted requirements, and automatically selects your most relevant experience | [@javiera-vasquez](https://github.com/javiera-vasquez) |
| [claude-resume-assistant](https://github.com/JoshuaOliphant/claude-resume-assistant) | Resume customization with ATS optimization and iterative refinement | [@JoshuaOliphant](https://github.com/JoshuaOliphant) |

## Personal Development

| App | Description | Author |
|-----|-------------|--------|
| [Claude-Skill-Developmental-Coach](https://github.com/koreyba/Claude-Skill-Developmental-Coach) | Personal development coaching using Spiral Dynamics and Cook-Greuter frameworks, with session persistence in Notion | [@koreyba](https://github.com/koreyba) |

## Health & Fitness

| App | Description | Author |
|-----|-------------|--------|
| [workout-tracker-next](https://github.com/fredhsu/workout-tracker-next) | Workout tracking web app, "mostly vibe coded using Claude Code" | [@fredhsu](https://github.com/fredhsu) |

## Knowledge Management

| App | Description | Author |
|-----|-------------|--------|
| [obsidian-claude-pkm](https://github.com/ballred/obsidian-claude-pkm) | Complete PKM system combining Obsidian with Claude Code — daily notes, custom agents, skills, modular rules | [@ballred](https://github.com/ballred) |
| [mcp-knowledge-graph](https://github.com/shaneholloman/mcp-knowledge-graph) | Persistent memory through a local knowledge graph — entities, relations, and observations across conversations | [@shaneholloman](https://github.com/shaneholloman) |
| [noteplan-mcp](https://github.com/mnedoszytko/noteplan-mcp) | MCP server for NotePlan — control markdown notes and tasks through Claude | [@mnedoszytko](https://github.com/mnedoszytko) |
| [notebooklm-skill](https://github.com/PleasePrompto/notebooklm-skill) | Query your NotebookLM documents with citation-backed answers via Claude Code | [@PleasePrompto](https://github.com/PleasePrompto) |

## Communication & Scheduling

| App | Description | Author |
|-----|-------------|--------|
| [personal-assistant-plugin](https://github.com/kjenney/personal-assistant-plugin) | Gmail + Google Calendar integration — manage emails, coordinate meetings through Claude | [@kjenney](https://github.com/kjenney) |
| [outlookctl](https://github.com/gmickel/outlookctl) | Outlook Classic automation with Claude Code Skill — email triage, drafting, calendar management | [@gmickel](https://github.com/gmickel) |
| [google-calendar-mcp](https://github.com/nspady/google-calendar-mcp) | Google Calendar MCP server — multi-account, smart scheduling, recurring events | [@nspady](https://github.com/nspady) |

## Developer Tools

| App | Description | Author |
|-----|-------------|--------|
| [Claudex](https://github.com/kunwar-shah/claudex) | Browse and explore Claude Code conversation history with SQLite FTS5 search and analytics | [@kunwar-shah](https://github.com/kunwar-shah) |
| [claude-code-token-tracker](https://github.com/anirudhhgupta/claude-code-token-tracker) | Comprehensive token usage analytics with real-time monitoring and SQLite persistence | [@anirudhhgupta](https://github.com/anirudhhgupta) |
| [ccusage](https://github.com/ryoppippi/ccusage) | Analyze Claude Code token usage and costs from local JSONL files | [@ryoppippi](https://github.com/ryoppippi) |

---

## The System Skill Pattern

Many apps in this list follow the **System Skill Pattern** documented at [shruggingface.com](https://www.shruggingface.com/blog/the-system-skill-pattern):

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  CLI Binary │ ←── │  SKILL.md   │ ←── │   SQLite    │
│  (commands) │     │ (tutorial)  │     │   (state)   │
└─────────────┘     └─────────────┘     └─────────────┘
        ↑                   ↑                   ↑
        └───────────────────┴───────────────────┘
                    Claude Code Runtime
```

**Components:**
1. **CLI Binary** — Self-contained executable Claude can invoke
2. **SKILL.md** — Markdown tutorial explaining the system's mental model
3. **SQLite Database** — Persistent single-file state

**The magic:** Each interaction adds data. Claude learns patterns over time.

---

## Add Your App

See [CONTRIBUTING.md](CONTRIBUTING.md) for submission guidelines.

**Requirements:**
- Claude Code must be the primary interface (not just used for development)
- App must have local data persistence or meaningful state
- Must include SKILL.md, CLAUDE.md, or equivalent instructions
- Actually works (we test submissions)

---

## Badge

Add this badge to your README to show your app is powered by Claude Code:

```markdown
[![Powered by Claude Code](https://img.shields.io/badge/Powered%20by-Claude%20Code-orange?logo=anthropic)](https://github.com/YOUR_USERNAME/awesome-powered-by-claude-code)
```

[![Powered by Claude Code](https://img.shields.io/badge/Powered%20by-Claude%20Code-orange?logo=anthropic)](https://github.com/YOUR_USERNAME/awesome-powered-by-claude-code)

---

## Related Resources

**This list is different from:**
- [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) — Commands, workflows, CLAUDE.md files FOR Claude Code
- [awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) — Skill templates and resources
- [awesome-vibe-coding](https://github.com/filipecalegario/awesome-vibe-coding) — Tools and references for AI-assisted coding

**Pattern documentation:**
- [The System Skill Pattern](https://www.shruggingface.com/blog/the-system-skill-pattern) — Architecture guide
- [Claude Code Best Practices](https://www.anthropic.com/engineering/claude-code-best-practices) — Official Anthropic guide

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
