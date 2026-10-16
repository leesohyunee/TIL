# Cloud sessions can't see my laptop

_2026-10-14 · learned while building seashelly with Claude Code_

## What I learned
Claude Code can run in two places:

- **Local session:** runs on my own computer. It can read my folders and open the site I'm running at `localhost:4321`.
- **Cloud session:** runs on a computer in the cloud. It works from a copy of the GitHub repo, so it **can't see files that only live on my laptop**, and it **can't open my `localhost`** (that address means "this computer", and the cloud isn't my computer).

## Why it matters
If the work needs my local files or my running preview, I start a local session. If it only needs what's on GitHub, a cloud session can keep working even when my laptop is closed.
