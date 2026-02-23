---
name: browser-use
description: Automate web browsing via the browser-use CLI (navigation, clicking, form filling, screenshots, extraction). Use when you need scripted, repeatable browser actions beyond the built-in browser tool, or when a persistent CLI session is preferred.
---

# Browser automation via browser-use CLI

Use the `browser-use` CLI for persistent, index-based browser automation. This skill assumes the CLI is installed locally.

## Quick check

Run:

```bash
browser-use doctor
```

If not installed, either:

- **One-line install (macOS/Linux):** `curl -fsSL https://browser-use.com/cli/install.sh | bash`
- **Manual:** `uv pip install browser-use` then `browser-use install`

## Core workflow

1. **Open** a URL: `browser-use open <url>`
2. **Inspect** elements: `browser-use state`
3. **Interact** using indices: `browser-use click <index>` / `browser-use input <index> "text"`
4. **Verify**: `browser-use state` or `browser-use screenshot <path>`
5. **Repeat** as needed (session persists)

## When to prefer this skill

- Need **persistent** session across many commands
- Need **index-based** DOM interactions
- Want **CLI-driven** browser automation

## Reference

See `references/cli.md` for a concise command cheat sheet.
