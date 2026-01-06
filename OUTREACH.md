# Creator Outreach & Growth Strategy

## The Growth Loop

```
Add app → Notify creator → Creator adds badge → Creator shares → Followers discover list
                ↓                   ↓                  ↓                    ↓
           Engagement         Backlink/SEO      Amplification         New submissions
```

---

## Notification Templates

### Twitter/X DM (Preferred - Highest Response Rate)

```
Hey @{username}! 👋

I added {app-name} to "Awesome Powered by Claude Code" - a curated list of apps that run via Claude Code as the runtime.

{link-to-list}

Your project is a great example of the pattern. If you want, you can add the badge to your README:

[![Powered by Claude Code](https://img.shields.io/badge/Powered%20by-Claude%20Code-orange?logo=anthropic)](https://github.com/dontoisme/awesome-powered-by-claude-code)

Let me know if you'd prefer to be removed or have any corrections!
```

### GitHub Issue on Their Repo

**Title:** Added to "Awesome Powered by Claude Code" list

```markdown
Hi @{username}! 👋

I'm curating a list of apps designed to run via Claude Code as the runtime/interface (not just built with Claude, but actually *powered by* it).

Your project [{app-name}]({their-repo-link}) is a great example, so I added it:
👉 https://github.com/dontoisme/awesome-powered-by-claude-code

**Optional:** If you'd like, you can add this badge to your README:

```markdown
[![Powered by Claude Code](https://img.shields.io/badge/Powered%20by-Claude%20Code-orange?logo=anthropic)](https://github.com/dontoisme/awesome-powered-by-claude-code)
```

Let me know if you'd prefer to be removed or have any corrections to the description!

---
*This is a one-time notification. I won't open follow-up issues.*
```

### Email (If Available in Profile)

```
Subject: Added {app-name} to "Awesome Powered by Claude Code"

Hi {name},

I'm building a curated list of apps that run via Claude Code as the runtime -
not just "vibe coded" but actually designed to be operated through Claude.

Your project {app-name} is a great example of the pattern, so I added it:
https://github.com/dontoisme/awesome-powered-by-claude-code

If you'd like, you can add the "Powered by Claude Code" badge to your README.
Badge code is here: {link-to-badges}

Let me know if you'd prefer to be removed or want any corrections!

Best,
{your-name}
```

---

## Opt-Out Process

### If Someone Asks to Be Removed

1. Remove immediately (within 24 hours)
2. Reply confirming removal
3. Add to `REMOVED.md` (private note, not public) to avoid re-adding

### Proactive Opt-Out Statement

Add to README footer:

```markdown
## Opt-Out

If you're a project maintainer and prefer not to be listed,
[open an issue](link-to-issues) or email {email} and we'll remove you promptly.
```

---

## Outreach Tracking

### Spreadsheet/Notion Template

| App | Creator | Platform | Contacted | Date | Response | Badge Added? |
|-----|---------|----------|-----------|------|----------|--------------|
| just-fucking-cancel | @rohunvora | Twitter | ✅ | 2026-01-07 | Liked | ❓ |
| pomodoro | @jakedahn | GitHub Issue | ✅ | 2026-01-07 | - | ❓ |

### Batch Outreach Schedule

**Week 1 (Pre-Launch):**
- Contact 5 highest-profile creators
- Get at least 2-3 badge adoptions before public launch
- These become "founding" featured projects

**Launch Day:**
- Contact remaining creators
- Post to HN
- Tweet with @mentions of responsive creators

**Ongoing:**
- Contact new additions within 48 hours of adding
- Weekly roundup tweet tagging recent additions

---

## Growth Tactics

### 1. Badge Viral Loop

The badge is the key mechanic:
- Creator adds badge → Their repo visitors see it → Click through → Discover list
- Each badge is a backlink and discovery path

**Increase badge adoption:**
- Make it dead simple (one-line copy/paste)
- Offer multiple styles (flat, for-the-badge, etc.)
- Show examples of other repos using it

### 2. "Featured" Rotation

- Feature 1 app per week on Twitter
- Tag the creator
- Include screenshot/demo if available
- They'll likely RT to their followers

### 3. Cross-Pollination

- Comment on HN threads about personal software, vibe coding, Claude Code
- Link to relevant apps from the list (not just the list itself)
- "This reminds me of {app} which does similar: {link}"

### 4. Creator Spotlights

- Short interview/Q&A with interesting creators
- "How I built X with Claude Code"
- Publish as GitHub discussions or separate blog
- Creators share their own spotlight

### 5. Anthropic Engagement

- Tag @AnthropicAI when sharing interesting finds
- They may RT/engage, bringing massive visibility
- Be genuine, not spammy

---

## Metrics to Track

| Metric | Tool | Goal (Month 1) |
|--------|------|----------------|
| GitHub Stars | GitHub | 500+ |
| Badge Adoptions | Manual count | 10+ repos |
| Referral Traffic | GitHub Insights | - |
| Twitter Mentions | Twitter Search | 20+ |
| New Submissions | GitHub Issues | 10+ |
| HN Points | HN | 100+ |

---

## Anti-Patterns to Avoid

1. **Don't spam** - One notification per creator, ever
2. **Don't be pushy about badges** - Offer, don't demand
3. **Don't mass-DM** - Personalize each outreach
4. **Don't add without checking** - Verify repos actually work
5. **Don't ignore removal requests** - Handle within 24 hours
