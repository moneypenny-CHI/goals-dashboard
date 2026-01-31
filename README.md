# 🎯 Ben's Goals Dashboard

A clean, modern goals tracking dashboard built for Vercel deployment.

## Features

- **JSON-driven** - Easy to update via `goals.json`
- **Responsive** - Mobile-friendly design
- **Dark theme** - Easy on the eyes
- **Progress tracking** - Visual progress bars for each goal
- **Model routing** - Shows AI model assignments

## Deployment

### Vercel (Recommended)

1. Connect this repo to Vercel
2. Deploy (zero config needed - it's static HTML)
3. Done! ✨

### Manual

Just serve the files with any static file server:

```bash
npx serve .
```

## Updating Goals

Edit `goals.json` and commit. The dashboard reads from this file on load.

### Goal Structure

```json
{
  "id": "unique-id",
  "title": "Goal Title",
  "status": "active|progress|planning",
  "priority": "high|medium|low",
  "objective": "What you're trying to achieve",
  "tasks": [
    { "text": "Task description", "done": false }
  ],
  "nextAction": "The immediate next step",
  "lastActivity": "2026-01-31",
  "blockers": "Any blockers or null"
}
```

## Tech Stack

- Vanilla HTML/CSS/JS (no build step)
- GitHub-inspired dark theme
- Zero dependencies

---

Managed by [Moneypenny](https://github.com/moneypenny-CHI) 🤖
