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

## Period 3: 31 August to 27 September 2026

**Counting basis:** copy improvements are counted per document, as in Periods 1 and 2. The sidebar regroup and the removal of four duplicate stub pages are each counted once as a restructure, not per page.

| Criterion | Committed | Delivered | Met? | Line value | Released | Evidence |
|---|---|---:|:---:|---:|---:|---|
| Copy improvements | ≥ 8 | 11 | ✅ | $750 | $750 | #237, #238, #242 |
| Functionality improvements | ≥ 4 | 5 | ✅ | $750 | $750 | #240, #241, #242, #243, #244 |
| Maintenance (issues current) | backlog cleared | cleared | ✅ | $750 | $750 | #238, #239, project-quiver#272 |
| New-feature coverage | doc within ~7 days | 0 of 0 | ✅ | $750 | $750 | none shipped in the window |

**Released:** $3,000 / $3,000

**Merge timing, stated plainly:** the period's work was complete and pushed at close. PRs [#237](https://github.com/Arrow-air/website/pull/237) to [#244](https://github.com/Arrow-air/website/pull/244) and [project-quiver#272](https://github.com/Arrow-air/project-quiver/pull/272) were opened at 23:11 UTC on 27 September (00:11 on 28 September UK time), with code-owner review requested on opening and all checks green. Three PRs are stacked on others: #242 on #237, and #243 and #244 on #238. Merge and production promotion will be noted here once they land.

### Evidence: 31 Aug to 27 Sep, `Arrow-air/website`

**Copy improvements (11).** All in [#238](https://github.com/Arrow-air/website/pull/238) unless noted.

- Grants & Bounties Committee: written from AIP-002 and AIP-003, with a notice that the committee is currently inactive
- Contracts API reference: deployed addresses, and the functions of the ARROW token and the vesting escrows
- Token Contracts introduction: rewritten to describe what is on-chain
- DAO Resources: published as a grouped directory of Arrow's tools and pages
- Why a DAO?, Treasury and Grants & Bounties: updated to describe project leads handling compensation, with Treasury linking AIP-009 as a planned revenue source and Grants & Bounties covering all three funding shapes
- DAO Voting: current projects and the GBC funding history
- ARROW Token: Rubicon and Uniswap v3 pools, and AIP-009 described as a basic design still being finalized
- The docs sidebar regrouped into nested sections, one restructure ([#237](https://github.com/Arrow-air/website/pull/237))
- Four duplicate stub pages removed and redirected to the pages that cover them, one restructure ([#242](https://github.com/Arrow-air/website/pull/242))

**Functionality improvements (5).**

- Client-side redirects for removed pages and `/docs/<project>` URLs ([#242](https://github.com/Arrow-air/website/pull/242))
- A stale docs report (`npm run stale-docs`) and a monthly review issue ([#241](https://github.com/Arrow-air/website/pull/241))
- An animated governance loop on Why a DAO? ([#240](https://github.com/Arrow-air/website/pull/240))
- Live GBC membership read from AIP-003 ([#243](https://github.com/Arrow-air/website/pull/243))
- Copy buttons on contract and multisig addresses ([#244](https://github.com/Arrow-air/website/pull/244))

**Maintenance.** The vesting guide gave the ARROW token's address as the vesting factory and described contracts contributors never used; with contributor vesting finished, it was removed ([#238](https://github.com/Arrow-air/website/pull/238)). Inline code overlapped on wrapped lines ([#239](https://github.com/Arrow-air/website/pull/239)). The kitchen sink test page was published with lorem ipsum and is now kept to the dev server ([#238](https://github.com/Arrow-air/website/pull/238)). Six dead links in the Quiver README fixed ([project-quiver#272](https://github.com/Arrow-air/project-quiver/pull/272)). No docs issues were opened and left unresolved in the period.

**New-feature coverage (0 of 0).** No AIPs merged in `dao-aips` between 31 August and 27 September, and no new DAO feature or process change shipped in the window.

_(7 periods total, ending ~18 January 2027.)_
