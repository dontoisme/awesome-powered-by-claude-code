# Contributing to Awesome Powered by Claude Code

Thank you for contributing! This list curates apps that **run via Claude Code** as the runtime/interface.

## What Belongs Here

### Include
- Apps where Claude Code is the primary user interface
- Apps with local data persistence (SQLite, files, external services)
- Apps with SKILL.md, CLAUDE.md, or equivalent instructions
- Apps that actually work (we test submissions)

### Exclude
- Tools FOR developing with Claude Code (use [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code))
- Skills/prompts without persistent functionality (use [awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills))
- Apps that were merely "vibe coded" but don't run through Claude Code
- Tutorials, demos, or proof-of-concepts that aren't meant for real use

## How to Submit

### Option 1: Pull Request

1. Fork this repository
2. Add your app to the appropriate category in `README.md`
3. Follow the format:
   ```markdown
   | [app-name](https://github.com/user/repo) | One-line description | [@username](https://github.com/username) |
   ```
4. Submit a PR with title: `Add [app-name]`

### Option 2: Issue

Open an issue with:
- **App name and link**
- **Category** (Finance, Productivity, Career, etc.)
- **One-line description**
- **How Claude Code serves as the runtime** (brief explanation)

## Quality Standards

Before submitting, verify:

- [ ] **README exists** with clear installation instructions
- [ ] **SKILL.md or CLAUDE.md** (or equivalent) is present
- [ ] **Actually works** — you've tested installation and basic functionality
- [ ] **Maintained** — has commits within the last 6 months (exceptions for stable apps)
- [ ] **Not a fork** — original work or significantly modified fork

## Categories

Current categories:
- **Finance & Money** — Budgeting, subscriptions, expenses
- **Productivity & Time** — Pomodoro, task management, time tracking
- **Career & Job Search** — Resume, job applications, interview prep
- **Personal Development** — Coaching, journaling, habit tracking
- **Health & Fitness** — Workout tracking, health logging
- **Knowledge Management** — Notes, PKM, research
- **Communication & Scheduling** — Email, calendar, scheduling
- **Developer Tools** — Analytics, debugging, utilities

Suggest new categories via issue if needed.

## Code of Conduct

- Be respectful in discussions
- Don't submit your own app without disclosure
- Don't submit apps with security issues
- Don't submit abandoned/broken projects

## Questions?

Open an issue with the `question` label.
