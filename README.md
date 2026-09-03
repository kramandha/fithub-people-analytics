# FIT HUB People Analytics — Requisitions Report

A standalone, self-contained HTML report analyzing FIT HUB's hiring/requisition pipeline: pipeline KPIs, replacement-hiring rate (an attrition proxy), SLA outcomes, sourcing-channel effectiveness, and full breakdowns by role and by club location.

Built from FIT HUB's Hiring dataset as part of a People Analytics & Intelligence case study.

## Contents

- [`index.html`](./index.html) — the report. Open it directly in a browser, or enable **GitHub Pages** (Settings → Pages → Deploy from branch `main`, folder `/`) to get a shareable link.

## Pages

1. **Pipeline** — total requisitions, closed vs. open, replacement-hiring rate, average time-to-fill, SLA success rate, and channel effectiveness ranked by SLA success.
2. **Per Role** — requisition volume, replacement rate, Beyond-SLA rate, and average time-to-fill for every role.
3. **Per Area** — the same breakdown across all club locations.

No build step, no dependencies — it's a single HTML file with the data embedded inline.
