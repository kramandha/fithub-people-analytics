# FIT HUB People Analytics

Standalone, self-contained HTML reports built from FIT HUB's People Analytics & Intelligence case study data. No build step, no dependencies — each is a single HTML file with its data embedded inline.

Live via GitHub Pages: **https://kramandha.github.io/fithub-people-analytics/**

## Reports

### [Requisitions](./index.html) — hiring/requisition pipeline
Pipeline KPIs, replacement-hiring rate (an attrition proxy), SLA outcomes, sourcing-channel effectiveness, and full breakdowns by role and by club location.

1. **Pipeline** — total requisitions, closed vs. open, replacement-hiring rate, average time-to-fill, SLA success rate, and channel effectiveness ranked by SLA success.
2. **Per Role** — requisition volume, replacement rate, Beyond-SLA rate, and average time-to-fill for every role.
3. **Per Area** — the same breakdown across all club locations.

### [Attrition](./attrition.html) — exit analysis
Every exit in the Turnover dataset, broken down three ways — nothing capped to a top-N, every category shown.

1. **Position** — total exits, involuntary rate, regrettable rate, and average tenure for all 14 roles. Hover any bar in the Position/Involuntary charts to see that role's top exit reasons.
2. **Location** — the same cuts across all 25 club locations.
3. **Exit Survey** — the same cuts across all 16 exit-survey reasons, plus which reasons drive involuntary exits.

### [Engagement](./engagement.html) — survey breakdown
A one-page heatmap of the 1,636-response Employee Engagement survey, sliced five ways: **Role, Age, Gender, Location, Length of Service**. Each dimension score (Career Growth, Work Clarity, Supportive Workplace, Fair Performance, Compensation Benefit) is colored relative to its own column; eNPS is colored by health (red = at risk, green = healthy) rather than by rank.
