# Accountability — Docs Maintainer & Improver

Updated each 4-week period. Before any payment releases, this table is the thing checked. **No table, no payment.**

Cap **$3,000 USDC / 4-week period**, split **evenly four ways at $750/line**. See [../PROPOSAL.md](../PROPOSAL.md) for the pro-ration rules.

## Period 1 — 6 July to 2 August 2026

| Criterion | Committed | Delivered | Met? | Line value | Released | Evidence |
|---|---|---:|:---:|---:|---:|---|
| Copy improvements | ≥ 8 | 13 | ✅ | $750 | $750 | #189, #197, #208 |
| Functionality improvements | ≥ 4 | 8 | ✅ | $750 | $750 | #183, #187, #190, #191, #195, #196, #197, #210 |
| Maintenance (issues current) | backlog cleared | cleared | ✅ | $750 | $750 | #193, #208 |
| New-feature coverage | doc within ~7 days | 2 of 2 | ✅ | $750 | $750 | #197, #208 |

**Released:** $3,000 / $3,000

### Evidence — 11 PRs merged into `Arrow-air/website`, 6 Jul – 2 Aug

**Copy improvements (13 documents).** #208 carried the bulk: `what-are-bounties.md` (corrected a false payment promise, rebuilt the discipline list from the taxonomy), `creating-bounties.md` (fixed the required-field count, documented the green-but-empty failure mode), `previous-bounties.md` and `previous-grants.md` (removed invented payment records), `how-to-claim.mdx` (full prose pass), `video-guide.md` (removed a placeholder video that would have served unrelated content), plus prose passes on `about.md`, `index.mdx` and the `grants/*` set. #189 cleared the bounty board dummy data and announced fresh bounties; #197 corrected the bounty flow docs.

**Functionality improvements (8).** #183 white flash on homepage load, refresh and navigation to docs · #187 mega menu and mobile Quicklinks drawer · #190 Caribou nav icon with filled-panel active state · #191 disciplines taxonomy across bounty pipeline, board filters and contributor map · #195 bounty form cut to five required fields with publishing gated behind a label · #196 bounty sync via PR rather than pushing to a protected branch · #197 board stacked into cards on mobile · #210 placeholder contributors removed from the map.

**Maintenance.** #193 unbroke all three sanity checks on staging; #208 carried the remaining docs corrections.

**New-feature coverage.** The bounty form and board shipped in #195 and #197 and the docs were corrected in the same window; #208 followed with the disciplines and bounty-flow documentation.

### Open question — counting basis

Copy improvements are counted **per document** here, giving 13 against a floor of 8. Counted per PR the figure is 3, which would miss. PROPOSAL.md does not define which applies, and the difference is worth $187.50 on this line alone. Per-document is the reading used since the line was written, and it matches how the work actually lands, but this should be defined explicitly in the Period 2 table rather than settled again after the fact.

_(Copy this block for each subsequent period. 7 periods total, ending ~18 January 2027.)_

## Period 2 — 3 August to 30 August 2026

**Counting basis:** copy improvements are counted per document, the reading used since Period 1 (see that period's open question). Stated here up front rather than settled after the fact.

| Criterion | Committed | Delivered | Met? | Line value | Released | Evidence |
|---|---|---:|:---:|---:|---:|---|
| Copy improvements | ≥ 8 | 9 | ✅ | $750 | $750 | #228 |
| Functionality improvements | ≥ 4 | 6 | ✅ | $750 | $750 | #213, #228 |
| Maintenance (issues current) | backlog cleared | cleared | ✅ | $750 | $750 | #228 |
| New-feature coverage | doc within ~7 days | 3 of 3 | ✅ | $750 | $750 | #228 |

**Released:** $3,000 / $3,000

**Merge timing, stated plainly:** the period's work was complete, pushed, and green on [#228](https://github.com/Arrow-air/website/pull/228) and [#213](https://github.com/Arrow-air/website/pull/213) at period close, with the code-owner review requested the same evening. Both merged to staging 31 Aug; staging was promoted to production via [#230](https://github.com/Arrow-air/website/pull/230) on 1 Sep, and every URL below is live and verified.

### Evidence — 3 Aug – 30 Aug, `Arrow-air/website`

**Copy improvements (9 documents), all in #228.** Working Async, the GitHub Guide, Grants & Bounties, and Snapshot (DAO Votes) written as full pages — the first two also carry new contributor-expectations copy (link-sharing with context, how bounties are awarded, temperature-checking a PR before building, retroactive contributions). The Glossary rebuilt from a JS-data stub into a prose glossary. The Active Project List written as a new governance page. Calls & Events rewritten around the current Discord event roster with the Events-tab visual. Getting Started restructured with a Growing Arrow path and engineers routed to the open meetings. The changelog caught up from April through August with a stated two-weekly Tuesday cadence.

- Working Async — https://arrowair.com/docs/community/working-async
- GitHub Guide — https://arrowair.com/docs/guides/github-guide
- Grants & Bounties — https://arrowair.com/docs/contributing/grants-bounties
- Snapshot (DAO Votes) — https://arrowair.com/docs/reference/snapshot
- Glossary — https://arrowair.com/docs/reference/glossary
- Active Project List — https://arrowair.com/docs/governance/active-project-list
- Calls & Events — https://arrowair.com/docs/community/community-calls
- Getting Started — https://arrowair.com/docs/overview/getting-started
- Changelog — https://arrowair.com/docs/changelog

**Functionality improvements (6).** #213: exploded view, component labels and materials for the Quiver 3D viewer. #228: changelog draft generator (`npm run changelog-draft`); live AIP index reading Arrow-air/dao-aips at view time (corrected AIP-005's type on first render); changelog image galleries with lightbox and jump-to-line links; live Snapshot proposals on the Snapshot reference page; the binding AIP-007 projects table read live on the Active Project List. One-click copy for the token page's key addresses shipped alongside, uncounted.

**Maintenance.** The markdown link checker was failing on staging (bot-blocking domains on the token page); repaired in #228 together with route patterns for /quiver and /spearhead. No docs issues were opened and left unresolved in the period.

**New-feature coverage (3 of 3).** The $ARROW token page and CoinGecko verification went to production 4 Aug with its docs in the same window. The Caribou Phase 2 Snapshot vote is reflected on the Active Project List status line and the Snapshot page lists it live. The AIP-007 amendment adding the three operations projects merged 30 Aug and appeared the same day via the live AIP index and projects table — coverage lag of zero, which is what the live-data approach was for.

_(7 periods total, ending ~18 January 2027.)_
