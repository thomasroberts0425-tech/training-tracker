# Training Tracker — Phase 2

A self-contained, offline-capable tracker for a 5-week football **strength + speed** block
(Phase 2 / July, "Jackson"). One HTML file — no build, no dependencies. Open it in any browser
or add it to your phone's home screen.

**Live version:** https://claude.ai/code/artifact/eb704d08-ce43-47bc-9635-00a3efccb73c

## Features
- **Lift** — log against the program by Week × Day (exercises grouped into the program's supersets
  with per-week rep schemes + deload logic). Weight / reps / **RPE (1–10)** per set, with
  autoregulation hints ("last time + a load nudge") and RPE-adjusted 1RM estimates.
  Weights in **lb or kg** (toggle in the ⋯ menu).
- **Sprints** — the program's Wed/Fri/Sun sprint workouts; RPE on every drill, **times** on the
  unresisted 10 / 20 / 30 yd efforts, plus a quick single-time logger for 40 yd dash tests.
- **Progress** — per-lift weight & est-1RM trends, session-effort trend, goal snapshots, PRs.
- **Goals** — speed goals (e.g. 10 yd @ 1.60s) and strength goals for the four key lifts
  (Front Squat, Bench Press, Power Clean, SA DB Snatch). Each draws a target line on its chart.

## Data
Everything is stored in your browser (`localStorage`). Use the **⋯ menu → Data** to:
- **Export JSON** — full backup; re-import to restore or move data between devices.
- **Export Markdown** — a readable training log.

## Run it
Open `training-tracker.html` in a browser. On a phone, use **Share → Add to Home Screen** for an
app-like, offline experience.
