# Giving an AI coding agent rules and a memory

_2026-10-15 · learned while building my site with Claude Code_

## What I learned
- **`CLAUDE.md`** in the project root is a standing rulebook the agent reads every session. Mine says, for example: content tasks only touch `src/content/` and `public/images/`, and never change the design unless I explicitly ask.
- Separate AI chats can't see each other's conversations. A shared **`PROGRESS.md`** log fixes that: every session reads it first and adds a short entry after changes.
- A **git post-commit hook** (`.git/hooks/post-commit`) runs a small script after every commit. I use one to add each commit to `PROGRESS.md` automatically.

## Why it matters
My job shifted from typing code to writing clear instructions, setting boundaries and reviewing changes. Those are skills too.
