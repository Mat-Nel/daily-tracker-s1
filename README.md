# daily-tracker-s1

A single-file habit tracker + science-based weekly scheduler. Open `index.html` (or add it to your phone's home screen) — no build, no server, data lives in localStorage.

**Today tab** — morning launch / evening shutdown checklists, streak-tracked habits, today's plan with Now/Next markers (checkboxes only on blocks you drive), and a "Late start?" button that rebuilds today from your real wake time without moving bedtime.

**Week tab** — full-week block calendar (blocks sized by real duration, now-line, effort colors) plus a day-detail list view; tap any block to skip it for a week or adjust its event.

**Plan tab** — draft your commitments, then press **Generate & apply** — nothing changes silently. Manage multiple schedules (e.g. summer vs. fall), start from scratch with a guided setup, or load the example template:

- **Fixed anchors** (work, class, meetings — time can't move, travel becomes real blocks)
- **Weekly deliverables** (due at a fixed point; bulk sessions land early in peak windows — wrapping into the previous week's tail for early-week deadlines — with a polish pass the morning it's due; can count toward a quota, e.g. a presentation counting as research hours)
- **Weekly quotas** ("20 focused hours" — split into ~90–150 min sessions, spread across days)
- **Routines** (specific days, flexible time — gym, meal prep)
- **Daily practices**

**Sync tab** — import a work/class calendar (.ics) and the scheduler builds around it; export the generated plan back out as an .ics Google Calendar can read.

The scheduler places everything using circadian alertness curves (peak ~2–6.5 h after waking, post-lunch dip, second wind), attention-residue buffers, ultradian session lengths, effort-scaled planning-fallacy padding, spaced deadline work, sleep-protected evenings, and a fixed 7-day wake anchor.
