# Minimal Skill Example

[![Powered by Claude Code](https://img.shields.io/badge/Powered%20by-Claude%20Code-orange?logo=anthropic)](https://github.com/YOUR_USERNAME/awesome-powered-by-claude-code)

A minimal template showing the structure of a "Powered by Claude Code" app.

## Installation

```bash
# Clone to your Claude skills directory
git clone https://github.com/YOUR_USERNAME/minimal-skill ~/.claude/skills/minimal-skill

# Or for project-specific installation
git clone https://github.com/YOUR_USERNAME/minimal-skill .claude/skills/minimal-skill
```

## Usage

Once installed, just ask Claude:

- "Start a new session"
- "What's my current status?"
- "Show me my history for this week"

Claude reads `SKILL.md` and knows how to operate the app.

## Structure

```
minimal-skill/
├── SKILL.md          # Instructions for Claude
├── README.md         # Human documentation
├── bin/
│   └── app           # CLI binary (or script)
└── data/
    └── .gitkeep      # Data directory (SQLite lives here)
```

## The Pattern

This follows the [System Skill Pattern](https://www.shruggingface.com/blog/the-system-skill-pattern):

1. **CLI** — Self-contained binary Claude can execute
2. **SKILL.md** — Tutorial teaching Claude how to use the CLI
3. **SQLite** — Persistent state that accumulates over time

## Requirements

- Claude Code
- macOS / Linux (Windows via WSL)

## License

MIT
