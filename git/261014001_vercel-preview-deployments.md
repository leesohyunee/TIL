# Every branch gets its own preview site on Vercel

_2026-10-14 · learned while publishing seashelly.vercel.app_

## What I learned
When a GitHub repo is connected to Vercel:

- A push to **`main`** updates the **live site** (production).
- A push to **any other branch** creates a separate **preview site** with its own URL. You can open it from Vercel → Deployments → **Visit**.

So I can try a change on a branch like `content/daydream-attic`, check it on my laptop and phone, and only merge it into `main` when it looks right.

## Why it matters
Nobody sees a half-finished page on the real site. The preview link is also easy to share for feedback before publishing.

## In practice
```
branch (content/xxx) → push → preview URL → check → merge into main → live
```
