# Cron is how you tell a computer "do this on a schedule"

_2026-11-20 · learned while asking Claude what "cron" means_

## What I learned
**Cron** schedules a task to run automatically at set times, like an alarm for code. A schedule is written as five fields: minute, hour, day of month, month, day of week. `*` means "every".

```
0 9 * * 1    → every Monday at 9:00
30 7 * * *   → every day at 7:30
```

Examples: check every morning that my site is up, or remind me every Friday to write a TIL.

## Why it matters
Some jobs shouldn't depend on me remembering them. Claude Code can also run tasks on a schedule, so this is a word I'll keep seeing.
