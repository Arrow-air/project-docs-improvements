# Project: Docs Maintainer & Improver — Proposal (frozen)

> **This is the frozen spec for this project, tagged `v1-proposal`.** It is the version the Snapshot vote binds. Any change after ratification requires a fresh Snapshot. Live status and links live in [README.md](./README.md); the period-by-period record lives in [accountability/](./accountability/).

Part of the Media / Docs / Compass bundle proposed under [AIP-006](https://github.com/Arrow-air/dao-aips/blob/main/AIPs/AIP-006.md), led by Sleety (@sl33ty). Narrative context: [DAO forum discussion](https://dao.arrowair.com/t/media-docs-compass-project-proposal-discussion/169). Recorded on a pass via an amendment to [AIP-007](https://github.com/Arrow-air/dao-aips/blob/main/AIPs/AIP-007.md).

## Binding terms (frozen)

- **Project lead:** Sleety (@sl33ty)
- **Cap:** $3,000 USDC per 4-week pay period, gated, no rollover (AIP-004 Level 5 × 40 hrs/period).
- **Funding-eligibility start:** 6 July 2026. Work begins at the leader's risk ahead of the vote; if the vote fails, no compensation is owed for the interim.
- **Term:** 28 weeks = 7 four-week pay periods, funding expiring ~18 January 2027.
- **Pay period:** 4 weeks (AIP-004's 48-week year = twelve 4-week periods). The AIP-007 "Monthly Spending Cap" here means one 4-week period. Compensation disburses at period end, only against this project's accountability table.
- **Midpoint checkpoint (week 14, ~12 October 2026):** a 7-day forum sentiment poll (continue / wind down). If it closes net-negative (more "wind down" than "continue", meeting a fixed 2M $ARROW quorum), a binding Snapshot halt-vote opens within 7 days, opened by any GBC member or the leader, halting on a simple majority. On a halt, funding stops at the week-14 mark with the in-progress period pro-rated.
- **Governance:** one shared project multisig across the bundle (leader + GBC seat per AIP-002); per-project spend tracked in this repo's accountability table.

## Purpose

To treat Arrow's documentation as a living product: keeping the global docs experience clear, beautiful, and low-friction as the DAO grows, so any contributor anywhere can find what they need and get started.

## Scope

This is the ongoing stewardship layer for the docs platform that Project Onboarding built, not a rebuild. Onboarding stood up the website, the Docusaurus docs site, and the first guides as a one-time effort, and it has since expired. But docs are an infinite game, and right now keeping them current is nobody's job, so they drift.

This role owns **global** docs infrastructure: structure, styling, UX, new features, and the guides that should appear whenever something ships or changes. Individual project docs stay with their teams; this is the layer underneath them. It is the most direct expression of AIP-008's minimal-friction goal for global contributors, and it deliberately does not overlap the completed Onboarding build.

## Project lead

Me (Sleety). I designed and built a significant portion of the current docs platform, so the context is already there. I have ambitions for what our docs could be, and I will stay pragmatic about shipping incremental improvements alongside the bigger experiments.

## Payment gate

A monthly floor of shipped, live-and-merged work, split across the role's two jobs, improve and maintain. The cap is split **evenly four ways at $750 per line:**

- **Copy improvements ($750):** ≥ 8 per period (rewrites, new guides, clarity passes, restructures). Pro-rates at ~$93.75 per item short.
- **Functionality improvements ($750):** ≥ 4 per period (an integrated `.mdx` doc-app, an embed, an automation, a new interactive feature). Pro-rates at ~$187.50 per item short.
- **Maintenance kept current ($750):** open docs issues (broken links, outdated pages, doc bug reports) triaged and resolved within the period. Pro-rates by issues resolved against issues open.
- **New-feature coverage ($750):** whenever something ships in the DAO (a feature, a passed AIP, a process change), a corresponding doc or guide exists within ~7 days. Pro-rates by features covered against features shipped.

Every item is a real artifact an agent can verify is live in the repo or site.

**Worked example** (one 4-week period):

| Criterion | Committed | Delivered | Met? | Line value | Released | Evidence |
|---|---|---:|:---:|---:|---:|---|
| Copy improvements | ≥ 8 | 9 | ✅ | $750 | $750 | _links_ |
| Functionality improvements | ≥ 4 | 3 | ⚠️ 75% | $750 | $562.50 | _links_ |
| Maintenance (issues current) | backlog cleared | 7 of 7 closed | ✅ | $750 | $750 | _issue links_ |
| New-feature coverage | doc within ~7 days | 2 of 2 features | ✅ | $750 | $750 | _doc links_ |

Three lines clear the threshold; functionality lands at 3 of 4, docking ~$187.50, so the period releases **$2,812.50 of $3,000**. Paid for what shipped, every line checkable in the [website](https://github.com/Arrow-air/website) repo.

## Cost

~10 hrs/wk = 40 hrs per 4-week period at **Level 5 ($75)**, so the cap is **$3,000**. Level 5 reflects the highest-quality deliverables and specialist knowledge of our docs, code, design, and infrastructure.

