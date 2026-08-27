# NATO–Russia Clash

A local-first dashboard for recording open-source events and reviewing an explicit escalation-signal heuristic. It is not an intelligence product, a probability forecast, or policy advice.

## Run locally

No build step is needed. Open `index.html` in a browser, or serve the folder with `python3 -m http.server 8080` and visit `http://localhost:8080`.

## How it works

- Five editable signal categories produce a transparent 0–100 average.
- The result is labeled as a heuristic signal, never a likelihood or certainty.
- Events, notes, sources, and scoring choices live only in browser local storage.

## Changelog

**2026-08-28 — [Public HTTPS deployment](https://github.com/codyprocody/nato-russia-clash/commits/main) — Externally accessible.** Added a hardened Nginx configuration for the public static site, HTTPS-only access, and automatic certificate renewal compatibility.

**2026-08-28 — [Initial dashboard](https://github.com/codyprocody/nato-russia-clash/commits/main) — Project created.** Added a local-first event log, editable signal board, transparent watch-level calculation, and clear limits on what the assessment can claim.
