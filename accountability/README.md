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
