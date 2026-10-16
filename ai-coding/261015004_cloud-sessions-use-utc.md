# Cloud sessions write times in UTC

_2026-10-15 · learned while keeping my PROGRESS.md log_

## What I learned
My progress log had entries that looked like they happened **tomorrow at 1–2 AM**. They were written by Claude Code **cloud sessions**, which run on servers set to **UTC** (Coordinated Universal Time), not my time zone.

Berkeley is UTC−7 right now, so "10/16 01:40" in UTC was really **10/15 18:40** for me.

The fix: I added a rule to `CLAUDE.md` that every log time uses my local time (America/Los_Angeles), never UTC.

## Why it matters
When a log mixes time zones, the order of events looks wrong and it's hard to trust. Saying "use my time zone" once, in the rules file, fixes it for every future session.
