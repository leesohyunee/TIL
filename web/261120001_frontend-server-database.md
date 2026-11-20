# Frontend, server and database are separate pieces, and different services run each one

_2026-11-20 · learned while using Vercel, Cloudflare and Supabase on my projects_

## What I learned
I used to think of a website as one thing. Using these services a little at a time showed me it has separate parts:
- **Frontend**: the pages people see in the browser. **Vercel** hosts mine and puts it online.
- **Server (backend)**: code that runs out of sight, on a computer somewhere else, and does work the browser shouldn't do itself. **Cloudflare** is one service that can run this kind of code.
- **Database**: where data is kept, so it's still there next time. **Supabase** gives me a database.

## Why it matters
When something breaks or I want a new feature, I can now ask "which part is this?" instead of seeing one big mystery. I still rely on AI for most of the code, so knowing the parts is my first step to learning them properly.
