# Example: Minimal Skill Template

This is a minimal example showing the structure of a "Powered by Claude Code" app.

---

## What This Skill Does

[Describe what problem this solves in 1-2 sentences]

## Commands

### Start a Session
```bash
./app start --name "session name"
```

### Check Status
```bash
./app status
```

### View History
```bash
./app history --period week
```

## Data Location

All data is stored in `~/.app-name/data.db` (SQLite).

## Typical Workflows

### Daily Use
1. User asks Claude to start a session
2. Claude runs `./app start`
3. Data is logged to SQLite
4. User can query patterns later

### Weekly Review
1. User asks "How did I do this week?"
2. Claude runs `./app history --period week`
3. Claude analyzes patterns and provides insights

## Notes

- All data stays local
- No network requests required
- Database accumulates context over time
