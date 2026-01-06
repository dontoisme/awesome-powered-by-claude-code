# Awesome Powered by Claude Code

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

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

| App | Stars | Description |
|-----|-------|-------------|
| [just-fucking-cancel](https://github.com/rohunvora/just-fucking-cancel) | ![Stars](https://img.shields.io/github/stars/rohunvora/just-fucking-cancel?style=flat) | Audits your subscriptions from bank CSV exports, helps you decide what to cancel, and optionally automates the cancellation via browser |
| [Claude-Budget-Workspace-Template](https://github.com/danielrosehill/Claude-Budget-Workspace-Template) | ![Stars](https://img.shields.io/github/stars/danielrosehill/Claude-Budget-Workspace-Template?style=flat) | Household budget management with 6 specialized agents: Budget-Architect, Expense-Analyst, Goal-Tracker, Transaction-Processor, Report-Generator, Financial-Advisor |

## Productivity & Time

| App | Stars | Description |
|-----|-------|-------------|
| [pomodoro](https://github.com/jakedahn/pomodoro) | ![Stars](https://img.shields.io/github/stars/jakedahn/pomodoro?style=flat) | Reference implementation of the System Skill Pattern — Pomodoro timer with CLI + SKILL.md + SQLite that learns your productivity patterns over time |

## Career & Job Search

| App | Stars | Description |
|-----|-------|-------------|
| [resume-tailoring-skill](https://github.com/varunr89/resume-tailoring-skill) | ![Stars](https://img.shields.io/github/stars/varunr89/resume-tailoring-skill?style=flat) | AI-powered resume customization with multi-job batch processing, confidence-scored matching, and interview prep reports |
| [cc-job-tailor](https://github.com/javiera-vasquez/cc-job-tailor) | ![Stars](https://img.shields.io/github/stars/javiera-vasquez/cc-job-tailor?style=flat) | Analyzes job postings, extracts weighted requirements, and automatically selects your most relevant experience |
| [claude-resume-assistant](https://github.com/JoshuaOliphant/claude-resume-assistant) | ![Stars](https://img.shields.io/github/stars/JoshuaOliphant/claude-resume-assistant?style=flat) | Resume customization with ATS optimization and iterative refinement |

## Personal Development

| App | Stars | Description |
|-----|-------|-------------|
| [Claude-Skill-Developmental-Coach](https://github.com/koreyba/Claude-Skill-Developmental-Coach) | ![Stars](https://img.shields.io/github/stars/koreyba/Claude-Skill-Developmental-Coach?style=flat) | Personal development coaching using Spiral Dynamics and Cook-Greuter frameworks, with session persistence in Notion |

## Health & Fitness

| App | Stars | Description |
|-----|-------|-------------|
| [workout-tracker-next](https://github.com/fredhsu/workout-tracker-next) | ![Stars](https://img.shields.io/github/stars/fredhsu/workout-tracker-next?style=flat) | Workout tracking web app, "mostly vibe coded using Claude Code" |

## Knowledge Management

| App | Stars | Description |
|-----|-------|-------------|
| [obsidian-claude-pkm](https://github.com/ballred/obsidian-claude-pkm) | ![Stars](https://img.shields.io/github/stars/ballred/obsidian-claude-pkm?style=flat) | Complete PKM system combining Obsidian with Claude Code — daily notes, custom agents, skills, modular rules |
| [mcp-knowledge-graph](https://github.com/shaneholloman/mcp-knowledge-graph) | ![Stars](https://img.shields.io/github/stars/shaneholloman/mcp-knowledge-graph?style=flat) | Persistent memory through a local knowledge graph — entities, relations, and observations across conversations |
| [noteplan-mcp](https://github.com/mnedoszytko/noteplan-mcp) | ![Stars](https://img.shields.io/github/stars/mnedoszytko/noteplan-mcp?style=flat) | MCP server for NotePlan — control markdown notes and tasks through Claude |
| [notebooklm-skill](https://github.com/PleasePrompto/notebooklm-skill) | ![Stars](https://img.shields.io/github/stars/PleasePrompto/notebooklm-skill?style=flat) | Query your NotebookLM documents with citation-backed answers via Claude Code |

## Communication & Scheduling

| App | Stars | Description |
|-----|-------|-------------|
| [personal-assistant-plugin](https://github.com/kjenney/personal-assistant-plugin) | ![Stars](https://img.shields.io/github/stars/kjenney/personal-assistant-plugin?style=flat) | Gmail + Google Calendar integration — manage emails, coordinate meetings through Claude |
| [outlookctl](https://github.com/gmickel/outlookctl) | ![Stars](https://img.shields.io/github/stars/gmickel/outlookctl?style=flat) | Outlook Classic automation with Claude Code Skill — email triage, drafting, calendar management |
| [google-calendar-mcp](https://github.com/nspady/google-calendar-mcp) | ![Stars](https://img.shields.io/github/stars/nspady/google-calendar-mcp?style=flat) | Google Calendar MCP server — multi-account, smart scheduling, recurring events |

## Developer Tools

| App | Stars | Description |
|-----|-------|-------------|
| [Claudex](https://github.com/kunwar-shah/claudex) | ![Stars](https://img.shields.io/github/stars/kunwar-shah/claudex?style=flat) | Browse and explore Claude Code conversation history with SQLite FTS5 search and analytics |
| [claude-code-token-tracker](https://github.com/anirudhhgupta/claude-code-token-tracker) | ![Stars](https://img.shields.io/github/stars/anirudhhgupta/claude-code-token-tracker?style=flat) | Comprehensive token usage analytics with real-time monitoring and SQLite persistence |
| [ccusage](https://github.com/ryoppippi/ccusage) | ![Stars](https://img.shields.io/github/stars/ryoppippi/ccusage?style=flat) | Analyze Claude Code token usage and costs from local JSONL files |

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

### Dark Style (Recommended)
```markdown
[![Powered by Claude Code](https://raw.githubusercontent.com/dontoisme/awesome-powered-by-claude-code/main/badges/powered-by-claude-code-dark.svg)](https://github.com/dontoisme/awesome-powered-by-claude-code)
```

[![Powered by Claude Code](https://raw.githubusercontent.com/dontoisme/awesome-powered-by-claude-code/main/badges/powered-by-claude-code-dark.svg)](https://github.com/dontoisme/awesome-powered-by-claude-code)

### Shields.io Alternative
```markdown
[![Powered by Claude Code](https://img.shields.io/badge/Powered%20by-Claude%20Code-orange?logo=anthropic)](https://github.com/dontoisme/awesome-powered-by-claude-code)
```

See [badges/](badges/) for more styles.

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

## Opt-Out

If you're a project maintainer and prefer not to be listed, [open an opt-out request](https://github.com/dontoisme/awesome-powered-by-claude-code/issues/new?template=opt-out.md) and you'll be **automatically removed within minutes**. No questions asked.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
