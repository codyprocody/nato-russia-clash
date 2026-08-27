# NATO–Russia Clash

A local-first dashboard for recording open-source events and reviewing an explicit escalation-signal heuristic. It is not an intelligence product, a probability forecast, or policy advice.

## Run locally

No build step is needed. Open `index.html` in a browser, or serve the folder with `python3 -m http.server 8080` and visit `http://localhost:8080`.

## How it works

- Each scheduled review records one editable 0–100 percentage assessment.
- The assessment is accompanied by reasoning and optional public-source links.
- The dashboard retains the 06:00, 12:00, and 18:00 Europe/Tallinn review history in browser local storage.

## Changelog

**2026-08-28 — [Initial 30-day assessment](https://github.com/codyprocody/nato-russia-clash/commits/main) — Added a starting percentage.** The live dashboard now opens with a clearly labeled 1% analytical assessment for a conventional Russian attack on any NATO country within the next 30 days, with source links and rationale.

**2026-08-28 — [Minimal dashboard](https://github.com/codyprocody/nato-russia-clash/commits/main) — Simplified the interface.** Replaced the editorial landing-page layout with a direct question, percentage, reasoning, review times, and history.

**2026-08-28 — [Scheduled assessment log](https://github.com/codyprocody/nato-russia-clash/commits/main) — Percentage-first dashboard.** Reworked the dashboard around one recorded percentage, a concise justification, a complete assessment history, and three daily review checkpoints at 06:00, 12:00, and 18:00 EEST.

**2026-08-28 — [Public HTTPS deployment](https://github.com/codyprocody/nato-russia-clash/commits/main) — Externally accessible.** Added a hardened Nginx configuration for the public static site, HTTPS-only access, and automatic certificate renewal compatibility.

**2026-08-28 — [Initial dashboard](https://github.com/codyprocody/nato-russia-clash/commits/main) — Project created.** Added a local-first event log, editable signal board, transparent watch-level calculation, and clear limits on what the assessment can claim.
