# CoreWeave and Nebius research

Working notes on how CoreWeave (CRWV) and Nebius (NBIS) turn contracted backlog into delivered capacity and revenue: which data centers exist, which are being built, what the customer contracts say, and what could delay or reduce them.

The work is being done in steps. Each step is checked against primary documents before the next one starts.

## Status

| Step | Topic | Status |
|---|---|---|
| 1 | Facilities per site and per MW; backlog size, schedule and contracts; conditions that end or shrink a contract | Done as of 2026-11-11. Nebius needs a refresh after its Q3 report on 2026-11-12 |
| 2 | Debt, and how delays interact with it | Not started |

## Where to start

Read [`research/00-summary.md`](research/00-summary.md). It holds the conclusions for both companies, the per-site tables, the roadmap by year and the list of open items.

## Detail files

| File | Contents |
|---|---|
| [`research/coreweave/01-facilities.md`](research/coreweave/01-facilities.md) | Every CoreWeave site found, in three buckets (operational, under construction, pipeline), with landlord, MW, schedule, delays, hardware, and a reconciliation against the company's totals |
| [`research/coreweave/02-backlog-and-contracts.md`](research/coreweave/02-backlog-and-contracts.md) | Backlog definition and history, conversion schedule, contract ledger, which contracts are filed, verbatim termination terms, slippage to date |
| [`research/nebius/01-facilities.md`](research/nebius/01-facilities.md) | The same site inventory for Nebius |
| [`research/nebius/02-backlog-and-contracts.md`](research/nebius/02-backlog-and-contracts.md) | The same backlog and contract analysis for Nebius |
| [`research/sources/contracts/`](research/sources/contracts/) | Plain-text copies of the nine customer agreements the two companies have filed with the SEC (redacted by the filers). Each file starts with its source URL |

## How evidence is marked

Every fact in the detail files carries one of these:

- **[P]** — read in the primary document: an SEC filing or exhibit, a company press release or web page, or an earnings-call transcript.
- **[S]** — seen only in a press article or search summary; the underlying page was not opened. Treat as a lead until checked.
- **INFERRED** — our own arithmetic or matching, not a statement by any source.

Sources are also tiered: T1 the company itself, T2 a counterparty (landlord, customer, vendor), T3 trade or financial press, T4 blogs, trackers and social media.

## Limits to keep in mind

- Neither company publishes a list of sites with megawatts. Named sites account for roughly 60% of CoreWeave's contracted power and 80% of Nebius's year-end target.
- CoreWeave's order forms, which hold delivery dates and late-delivery remedies, are not public. Nebius's contracts are filed but with dates, prices and grace periods redacted.
- CoreWeave's investor-relations site and Data Center Dynamics could not be read directly, so the CoreWeave Q3 2026 slide deck and all Data Center Dynamics reporting are marked [S].
- Earnings-call quotes come from Motley Fool transcriptions, which can contain transcription errors.

This is research, not investment advice.
