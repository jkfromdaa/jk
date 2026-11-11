# Can and will the customers behind the CoreWeave and Nebius backlogs pay?

Compiled 2026-11-11. Finished under a reduced search budget (16 searches in total), so several items rest on search summaries and a few on recalled figures that are flagged as such.

Evidence marks: **[P]** read in the primary document this session (SEC XBRL company facts on data.sec.gov, CoreWeave/Nebius filing text, CoreWeave Q3 2026 call transcript). **[S]** search-result summary only, page not opened. **INFERRED** my arithmetic or judgment. **[RECALLED]** from training memory, not found in a source this session — treat as unverified. Tiers: T1 company filing/call, T2 counterparty filing, T3 financial press, T4 blogs, aggregators, newsletters.

---

## 1. Method

### 1.1 The order in which the measures matter

A multi-year take-or-pay compute contract is an unsecured, non-traded claim on the customer's future operating budget. Rank the evidence like this:

1. **Commitment coverage** — the customer's total contractual compute, purchase and lease commitments against its cash plus its free cash flow (or, for a loss-making lab, against cash plus committed funding). This is the single most informative measure, because every named payer has signed far more than the CoreWeave or Nebius contract. A customer with ample cash can still be over-committed.
2. **Free cash flow after its own capital spending**, and its direction. Net income is a poor guide: it excludes capex and is distorted by investment gains (Alphabet) and convertible-note charges (Anthropic).
3. **Rating and market-implied default risk** (CDS, bond spreads). Useful as an outside check and for trend. CDS overstates real-world default probability because it prices a risk premium.
4. **Funding dependence**, for private labs only: burn, runway, date and size of the last round, whether the next round has closed.
5. **Strategic necessity** — is this compute the customer's production capacity (hard to drop) or marginal overflow (first to be cut)?
6. **The contract's own protections** — prepayment held, take-or-pay, no termination for convenience, a backstop. These set loss given default, not probability of default.
7. Cash on its own, the customer's own backlog, and revenue growth are supporting evidence only. A large backlog at the customer (Microsoft RPO $683B [P]) shows demand, not ability to pay.

### 1.2 "Cannot pay" versus "tries to pay less"

These are different risks and need different evidence.

- **Cannot pay (default).** For the AAA/AA hyperscalers this is remote on any base rate. It is a live question only for the private labs and smaller AI-natives.
- **Tries to pay less.** The contracts have no termination for convenience [P, filed MSAs], so the routes are: letting a late tranche lapse, repeated-availability termination, declining options and renewals, and negotiated amendments. All filed contracts make the customer liable only for delivered service [P].

Evidence found:

| Item | What it shows | Mark |
|---|---|---|
| FT, 2025-03-06: Microsoft withdrew from some CoreWeave agreements over delivery issues and missed deadlines | An AAA customer used delivery failure, not inability to pay, to reduce commitments | [S] T3, from prior research; not re-verified |
| Microsoft cut its calendar-2026 capex outlook to ~$170B from $175B, citing third-party capacity delays; press says it is tightening oversight of Nebius and IREN projects | The same lever is in play in 2026 at Nebius's largest contract | [S] T3/T4 |
| Nebius–Microsoft SOW: per-tranche termination with refund of the upfront payment after a grace period | The legal route exists and is public | [P] T1 |
| Poolside "Project Horizon" with CoreWeave reported collapsed 2026-04-02 | A small AI-native deal failed before delivery | [S] from prior research |
| CoreWeave Q3 2026: no cancellation or backlog write-down disclosed; one 2025 timing slip where the customer agreed to move dates | No realised loss so far | [P] T1 |
| Any 2026 renegotiation of a signed take-or-pay contract by OpenAI or Anthropic with a cloud or neocloud | **None found** in one targeted search. Absence in one search is weak evidence | — |

Conclusion (INFERRED): for about four-fifths of Nebius's RPO and roughly two-fifths of CoreWeave's backlog the realistic loss route is the supplier's own late delivery handing the customer an exit, not customer credit. Customer credit proper matters for the remaining third of CoreWeave's backlog and a sixth of Nebius's.

---

## 2. Counterparty fact sheet

### 2.1 Public companies (figures in $B)

All financial figures are [P] from SEC XBRL company facts unless marked. TTM = trailing twelve months, INFERRED by adding and subtracting reported periods. Free cash flow here = operating cash flow less purchases of property and equipment; it excludes finance-lease principal payments.

| | Microsoft | Meta | NVIDIA | Alphabet | IBM |
|---|---|---|---|---|---|
| Balance date | 2026-09-30 | 2026-09-30 | 2026-07-26 | 2026-09-30 | 2026-09-30 |
| Cash and short-term investments | 64.5 | 82.4 (11.2 cash + 71.2 securities) | cash 22.4; securities not pulled | 265.1 | cash 9.2 |
| Debt | 41.3 carrying | 84.0 carrying (28.8 a year earlier) | 33.4 (8.5 a year earlier) | 125.1 non-current (49.1 at end-2025) | 56.8 non-current |
| Operating cash flow | TTM 195.9 | TTM 133.1; 9M 2026 96.9 | H1 FY27 74.4 | 9M 2026 127.1 | 9M 2026 11.8 |
| Capex (cash) | TTM 135.9; latest quarter 39.4 | TTM 104.4; 9M 2026 83.1 | H1 FY27 4.4 | 9M 2026 132.0 | 9M 2026 0.8 |
| Free cash flow | TTM ~60.0 | TTM ~28.6; Q3 2026 alone −1.2 (32.8 − 33.9) | H1 FY27 ~70.0 | 9M 2026 −4.8 | 9M 2026 ~11.0 |
| Net income, latest quarter | 36.6 | 9.9 | 59.7 | 26.5 | 2.2 |
| Disclosed commitments | Finance-lease payments due 95.2; operating-lease payments due 33.0. Leases not yet commenced and purchase commitments are in note text, not pulled | **Contractual obligations 454.5** (81.2 a year earlier), of which 121.4 due within 12 months; unconditional purchase obligations 355.7 | Guarantee maximum exposure **108.5** (0.86 at 2025-10-26) | Unconditional purchase obligations 75.6 at 2026-03-31 (latest tagged) | 0.3 at end-2025 |
| 2026 capex guide [S] T3 | ~170 (calendar 2026, cut from 175) | 135–145 | n/a | 195–205 | n/a |
| 2027 capex [S] T3 | not found | "continue investing aggressively"; analysts >210 | n/a | "increase significantly" | n/a |
| Rating | AAA / Aaa [RECALLED] | AA− / Aa3 [RECALLED]; S&P outlook cut to negative, autumn 2026 [S] T4 | AA-category [RECALLED] | AA+ / Aa2 [RECALLED] | A− / A3 [RECALLED] |
| Five-year CDS, Oct 2026 [S] | highest since 2021; level not found | 108 bp, record | 101 bp, record | highest since 2021; level not found | not found |

Readings (INFERRED):

- **Meta** is the counterparty whose numbers moved most. Obligations rose from $81B to $455B in twelve months, debt tripled, quarterly free cash flow turned negative, and it announced an equity offering in late October 2026 [S]. Commitment coverage: $121B due within twelve months against TTM operating cash flow of $133B. Still AA-category, but it is the largest single name in both backlogs.
- **Microsoft** is the only one of the four hyperscalers still clearly free-cash-flow positive (~$60B TTM), and it is the one with a record of walking from late capacity.
- **NVIDIA**'s $108.5B of guarantees is new. Its backstops (CoreWeave $6.3B) are part of a much larger book of contingent support for its customers, so its support is correlated with the sector it would be backstopping.
- **Alphabet** has the largest liquidity but nine-month capex exceeded operating cash flow.
- Press, citing FactSet via Apollo: forward free cash flow about −$25B each for Alphabet and Meta, −$30B for Amazon; Microsoft positive [S] T3.

### 2.2 Private companies

| | OpenAI | Anthropic | Jane Street |
|---|---|---|---|
| Revenue | ~$50B annualised at end-September 2026, told to investors; ~$68–70B had circulated a month earlier and reportedly included partners' gross revenue. Target ≥$70B by year-end [S] T3 | Run-rate ~$30B (April), >$47B (May), ~$65B (end-July) [S] T4; "Q2 2026 revenue $11.6B" [S] T4 | Net trading revenue $39.6B in 2025; Q1 2026 $16.1B revenue, $10.3B net income; >$40B year-to-date despite a ~$15B loss in July 2026 [S] T3/T4 |
| Burn / cash flow | 2026 cash burn estimates $17B to $27B; Q1 2026 burn $3.7B; internal projection of $278B cumulative burn 2026–2030 (FT via secondary) [S] T4 | H1 2026 operating cash flow +$3.9B, capex $0.48B, free cash flow ~+$3.4B; operating loss $693M [S, analyses of the S-1] | Profitable |
| Cash | >$73B after Q1 2026; ~$4.7B undrawn credit facility; no debt at 2026-03-31 [S] T4 | ~$131.7B at 2026-06-30 [S, S-1 analyses] | Members' equity ~$55B (S&P, March 2026) [S] |
| Last funding | $122B at $852B post-money, closed 2026-03-31. Talks for ≥$30B at ~$1.2–1.4T, **not closed** [S] | $65B Series H at $965B post-money, 2026-05-28; S-1 filed for an IPO [S] | n/a |
| Total commitments | $600B compute through 2030, or ~$665B purchase commitments (The Information), or ">$1 trillion" cumulative; components cited: Oracle >$300B, Azure ≥$250B through 2032, AWS ~$138B [S] T4, sources disagree | Purchase commitments $265.6B plus leases not yet commenced $321.4B at 2026-06-30; later analyses $518B to $895B; ~$70B due in the year to September 2027; hyperscaler deals payable "regardless of actual usage" [S] | CoreWeave ~$6B [P] |
| Rating | none | none | Fitch upgraded to BBB− on 2026-07-24; S&P and Moody's outlooks positive (rating letters not found; non-investment-grade at S&P/Moody's is INFERRED) [S] T4 |
| Lender pricing on contracts they back | CoreWeave DDTL 5.0 ($3.1B, "two large, non-investment grade customers", identified on the Q1 call as OpenAI and Cohere): **SOFR + 4.50%** [P] | not separately disclosed | not disclosed |

Readings (INFERRED):

- **OpenAI.** Coverage is the problem, not current liquidity. At ~$50B run-rate and $17–27B of annual burn, ~$73B of cash covers about three years of burn, but $600B+ of commitments through 2030 require either revenue to multiply or continuous new funding. The next round was unclosed when the revenue figure came out. CoreWeave's ~$20B is about 3% of OpenAI's commitments, so OpenAI will choose which suppliers to pay in full if it has to ration.
- **Anthropic** now looks stronger than OpenAI on cash ($132B) and cash flow (positive in H1 2026), but its commitments ($587B at June, up to $895B later) are of the same order as OpenAI's against a similar revenue base. Its CoreWeave contract value is undisclosed.
- **The October 2026 report.** The Financial Times reported, and Reuters and CNBC confirmed, that OpenAI told investors its revenue was running at about $50B a year at end-September, against ~$68–70B believed earlier [S] T3. On 2026-10-08 CoreWeave fell 7.8% to $81.58, NVIDIA ~3%, Oracle ~6%. CoreWeave's bond sell-off was mainly 13–15 October: the 9.625% 2032 notes yielded ~14.8–15%, and five-year CDS went from 368 to 643 bp in a week [S] T3/T4. Coverage also ties the bond move to an inflation report and rising yields.

### 2.3 Others, one line each

- **Cohere:** ARR ~$240M; valuation $7B (Sept 2025), with reports of a round at ~$20B or €22.9B, conflicting [S] T4. Has $1B+ contracts at both CoreWeave and Nebius against that revenue.
- **Mistral:** raised €3B, valued ~€21B (Sept 2026); revenue not found [S] T4.
- **Reflection AI:** $25B pre-money (April 2026); no disclosed revenue [S] T4. A >$1B Nebius contract is funded entirely from equity raised.
- **IBM:** investment grade, nine-month operating cash flow $11.8B [P]; contract value undisclosed.
- **Oracle** (not a customer; sector marker): five-year CDS 288 bp, a record [S].
- Also tied to Anthropic, for context: NScale S-1 shows Anthropic agreements of up to ~$44.6B; TeraWulf 20-year, ~401 MW [S].

---

## 3. Base rates

### 3.1 Corporate default rates by rating

The S&P table could not be read this session (three searches returned the study but not the table). What was sourced, and what is recalled:

| Rating | 1-year | 3-year | 5-year | Status |
|---|---|---|---|---|
| AAA | 0.00% | ~0.13% | **0.34%** | 5-year figure [S], S&P investor fact book; others [RECALLED] |
| AA | ~0.02% | ~0.11% | ~0.30% | [RECALLED] |
| A | ~0.05% | ~0.20% | ~0.45% | [RECALLED] |
| BBB | ~0.15% | ~0.75% | ~1.5% | [RECALLED]; 10-year 2.86% is [S] |
| BB | ~0.6% (long-term one-year average 0.86% in the 2020 US study [S]) | ~3.3% | ~6% | [RECALLED]; 10-year 10.44% is [S] |
| B | ~3% | ~10.5% | ~16% | [RECALLED] |
| CCC/C | ~26% (26.5% and 28.3% long-term one-year averages [S]) | ~39% | ~45% | [RECALLED] |

Source to verify against: S&P Global Ratings, "2024 Annual Global Corporate Default And Rating Transition Study", 2025-03-27, global average cumulative default rates 1981–2024 (Table 24). **The recalled cells must be checked before this table is quoted.**

Recovery: long-run average recovery on senior unsecured bonds of about 35–45% of face, per Moody's and S&P recovery studies [RECALLED, not sourced]. A rejected service contract in bankruptcy ranks as a general unsecured claim, usually reduced by a duty to mitigate.

Market-implied, for comparison (INFERRED, five-year probability = 1 − exp(−spread × 5 / 0.6), 40% recovery): Meta at 108 bp ≈ 8.6%; Oracle at 288 bp ≈ 21%; CoreWeave itself at 643 bp ≈ 41%. These are risk-neutral and run several times above historical frequencies for the same ratings.

### 3.2 Outcomes when a capacity customer fails or walks

**Not sourced.** No search budget remained for data-center lease defaults, post-2001 telecom capacity contracts, or 2022–2023 cloud-commitment renegotiations. General knowledge only [RECALLED]: after 2001, long-term telecom capacity purchase contracts were widely rejected in bankruptcy or renegotiated at market prices that had fallen by most of their value, so collected value was a small fraction of contracted value; in 2022–2023 cloud customers mostly extended terms rather than cut totals. The useful lesson for the model is the direction of the correlation: customers fail when capacity prices are low, so re-letting is worth least exactly when it is needed.

---

## 4. Backlog by credit bucket

### 4.1 CoreWeave — $132.5B at 2026-09-30 [P]

Hard anchors:

- Non-investment-grade AI labs and AI-natives: under 30% of backlog (May 2026) [P].
- Financial services: ~10% of backlog (Nov 2026) → ~$13.3B INFERRED [P for the percentage].
- Investment-grade share: >60% (Q3 2025 call) [S]; about two-thirds (Deutsche Bank, Oct 2026) [S] → ~$87B investment grade, ~$45B not. No company figure was given on the Q3 2026 call.
- More than 75% of remaining committed 2027 capex not yet financed is tied to investment-grade and enterprise customers [P].

Named contracts, remaining value INFERRED:

| Customer | Headline | Less recognised to date | Remaining (estimate) |
|---|---|---|---|
| Meta | up to $14.2B + ~$21B [P] | unknown; assumed ~$2B | ~$33B |
| OpenAI | up to $22.4B [P], plus an undisclosed Q3 2026 expansion | ~$2.5–3B if "Customer B" (23% of H1 2026 revenue of ~$4.7B) is OpenAI — a guess | ~$20B |
| NVIDIA | $6.3B [P]; inclusion in backlog not disclosed | — | $0–6.3B |
| Jane Street | ~$6B [P] | small | ~$6B |
| Microsoft | >$10B through 2030 [S] | ~$6.5B since 2023 (INFERRED from revenue shares) | ~$5–15B, very uncertain |
| Anthropic, Google, IBM, Cohere, Mistral | undisclosed | — | unknown |
| Unnamed, early Q3 2026 | >$25B [P] | — | >$25B, identity unknown |

Bucket estimate (all INFERRED; built to match the two-thirds / one-third split and the 10% financial-services figure):

| Bucket | $B | Share | How built |
|---|---|---|---|
| AAA/AA hyperscalers and NVIDIA | ~55 (range 45–65) | ~42% | Meta 33 + Microsoft ~8 + NVIDIA 6.3 + Google and unidentified hyperscaler orders ~8 |
| Other investment grade and enterprise | ~32 (range 22–42) | ~24% | Investment-grade total 87 − 55. Includes Jane Street 6 (investment grade at Fitch only), IBM, and most of the unnamed >$25B |
| Large private labs (OpenAI, Anthropic) | ~28 (range 22–35) | ~21% | OpenAI ~20 + Anthropic and OpenAI expansion ~8 (pure assumption) |
| Smaller AI-natives | ~10 (range 5–15) | ~8% | Residual of non-investment-grade 45.5 after labs and finance |
| Non-investment-grade or unrated financial firms | ~7.5 | ~6% | 13.3 financial services − Jane Street 6 |
| Total | 132.5 | | |

**Honest remainder:** only about $60–65B (under half) can be tied to a named customer, and only Meta, OpenAI, NVIDIA and Jane Street have a disclosed value. Roughly $65–70B, including the entire >$25B signed in Q3 2026, is assigned to buckets by inference from two percentage statements, one of which is a broker estimate.

### 4.2 Nebius — RPO $37.5B at 2026-06-30 [P]

| Bucket | $B | Share | How built |
|---|---|---|---|
| AAA/AA hyperscalers | ~31.5 | ~84% | Microsoft 17.39 + Meta 2.88 + Meta 12.0 = 32.27 [P], less ~0.7 recognised since Nov 2025 (INFERRED) |
| Smaller AI-natives (Reflection, Cohere, unnamed US lab) | ~3.0–3.5 | ~9% | Three of four deals "averaging over $1B" [P] |
| Quant trading firm | ~1.0 | ~3% | Fourth deal [P for existence] |
| Unknown | ~1.5–2.0 | ~4–5% | Residual |
| Total | 37.5 | | |

Outside RPO: Meta's $15B backstop (a floor under capacity Nebius means to sell to others). No OpenAI or Anthropic contract found. Nebius reports Q3 on 2026-11-12; refresh then.

---

## 5. Expected loss over five years — a model on stated assumptions

This is arithmetic on assumptions, not a measurement. Loss = contracted revenue not collected, before any offset.

### 5.1 Assumptions

Five-year probability of default by bucket:

| Bucket | Low | Central | High | Basis |
|---|---|---|---|---|
| AAA/AA hyperscalers | 0.1% | 0.3% | 2% | Historical AA ~0.3%; high case leans toward CDS (Meta 108 bp ≈ 8.6% risk-neutral) |
| Other investment grade | 0.5% | 1.5% | 4% | Historical A to BBB |
| Large private labs | 5% | 15% | 35% | Rating-equivalent BB to B to weak-B. Evidence: lenders charge SOFR + 4.50% on OpenAI/Cohere-backed loans and + 5.50% on DDTL 5.5, against + 2.25% on an A3-rated investment-grade-backed loan [P] — a 225–325 bp premium, typical of single-B loans. Commitments are 10x or more of revenue |
| Smaller AI-natives | 15% | 30% | 50% | B to CCC; contracts exceed annual revenue several times over |
| Financial firms below investment grade | 2% | 5% | 12% | BBB− to BB |

Loss given default on the remaining contract value: 20% / 50% / 80%.

"Pays less without defaulting" haircut on contract value (renegotiation, lapsed tranches, declined volumes): none / 1% for investment-grade buckets, 5% for labs and AI-natives, 2% for financial firms / 3%, 10%, 5%.

Other assumptions: bucket sizes from section 4; no correlation modelled inside the expected value; NVIDIA's backstop counted inside the hyperscaler bucket; Nebius "unknown" treated as smaller AI-natives; exposure held flat at today's balance (overstates, since backlog amortises).

### 5.2 Result

| | Low | Central | High |
|---|---|---|---|
| **CoreWeave** — default loss | $0.7B | $4.1B | $14.5B |
| CoreWeave — pays-less loss | $0 | $2.6B | $5.2B |
| **CoreWeave total** | **$0.7B (0.5%)** | **$6.7B (5.0%)** | **$19.7B (14.8%)** |
| **Nebius** — default loss | $0.2B | $0.8B | $2.6B |
| Nebius — pays-less loss | $0 | $0.5B | $1.2B |
| **Nebius total** | **$0.2B (0.4%)** | **$1.3B (3.5%)** | **$3.8B (10.2%)** |

In CoreWeave's central case the two lab-and-AI-native buckets (29% of backlog) produce $5.1B of the $6.7B.

### 5.3 Mitigants and aggravators

Mitigants:

- **Prepayments held:** CoreWeave deferred revenue $10.0B [P] (7.5% of backlog), prepayments on 70% of 2026 deals [P]; Nebius $6.0B [P] (16% of RPO), mostly Microsoft's. Caveat: prepaid fees are refundable if the customer terminates for cause [P], so they protect against customer default, not against the supplier's own late delivery.
- **Re-letting:** new 4–5 year contracts price at $20–25M per MW a year and short-term capacity at ~$40M [P], above older contracts. While that holds, loss given default is near the low case.
- **NVIDIA** must buy CoreWeave's residual unsold capacity up to $6.3B through April 2032 [P]; Meta's $15B backstop at Nebius [P].
- **Step-in and lien** rights run the other way: they protect OpenAI against CoreWeave [P], not CoreWeave against OpenAI.

Aggravators:

- **Correlation.** A lab fails only when AI revenue or funding disappoints, which is also when compute prices fall and NVIDIA's own guarantees ($108.5B [P]) are being called. In that state loss given default moves to the high case and re-letting stops working. The expected value understates the tail: the distribution is bimodal (near the low case, or near the high case), not centred on the central figure.
- **Concentration.** Meta alone is ~25% of CoreWeave's backlog and ~38% of Nebius's RPO (INFERRED). One counterparty's decision moves the whole number.
- **Leverage.** CoreWeave's loans are sized to contracted cash flow; a loss of 5–15% of backlog falls on a thin equity layer and can trigger cash traps [S].
- **Supplier-caused exits** (section 1.2) are outside this credit model entirely and are the larger risk for Nebius.

### 5.4 The assumption that moves the answer most

**The default probability assigned to OpenAI and Anthropic, together with the correlated loss-given-default.** Holding everything else at central, moving the lab probability from 5% to 35% moves the lab bucket's loss from $2.0B to $5.8B; moving loss given default from 20% to 80% moves CoreWeave's default loss from $1.6B to $6.6B. The hyperscaler rating assumptions barely matter. For Nebius the credit answer is driven by the small AI-native deals, and is small either way.

---

## 6. What to watch

| Datapoint | Where | How often |
|---|---|---|
| Customer concentration note, receivables by customer, deferred revenue, RPO schedule | CoreWeave 10-Q (Q3 due mid-November 2026) and 10-K | Quarterly |
| Investment-grade share of backlog; prepayment share; renewal pricing; price per MW | CoreWeave and Nebius earnings calls and letters | Quarterly |
| Customer mix of each new delayed-draw loan and its spread over SOFR | CoreWeave 8-K and press release per facility | Per deal |
| RPO, deferred revenue, tranche status, any "updated delivery date" with Microsoft | Nebius 6-K (next: 2026-11-12) | Quarterly |
| Meta contractual obligations, free cash flow, debt; Microsoft leases not yet commenced; Alphabet purchase obligations; NVIDIA guarantees | Their 10-Qs; data.sec.gov XBRL | Quarterly |
| Hyperscaler capex guidance and comments on third-party capacity | Earnings calls (late Jan, Apr, Jul, Oct) | Quarterly |
| OpenAI: revenue run-rate, burn, whether the ≥$30B round closes and at what valuation | FT, The Information, Bloomberg, Reuters | Irregular |
| Anthropic: purchase commitments, leases not yet commenced, cash flow | S-1 amendments, then 10-Q once listed | Quarterly after IPO |
| Five-year CDS on Meta, Oracle, NVIDIA, CoreWeave; CoreWeave 2031/2032 bond yields | Press citing Solve, ICE, S&P | Daily, reported irregularly |
| Rating actions (Meta outlook; Jane Street; Oracle) | S&P, Moody's, Fitch releases | Irregular |
| Spot and short-term GPU rental prices | Company calls; third-party indices | Quarterly / continuous |

---

## 7. Could not be sourced

1. The S&P cumulative default table and recovery rates (section 3.1) — recalled figures only, apart from AAA five-year 0.34% and two ten-year figures.
2. Historical collection rates on failed or renegotiated capacity contracts (section 3.2).
3. Current ratings with dates for Microsoft, Meta, NVIDIA, Alphabet, IBM — recalled; only "all comfortably above A" and Meta's negative S&P outlook came from search.
4. CDS levels for Microsoft and Alphabet; where OpenAI-linked debt trades; spreads on Stargate/Oracle-related loans.
5. Microsoft and Alphabet purchase commitments and leases not yet commenced at 2026-09-30 (in note text, not XBRL); NVIDIA marketable securities; Alphabet trailing-twelve-month figures.
6. Guided 2027 capex in dollars for any hyperscaler.
7. Contract values for Microsoft, Anthropic, Google, IBM, Cohere and Mistral at CoreWeave; identity of the >$25B signed in Q3 2026; whether NVIDIA's $6.3B is in backlog; who Customers A, B and C are.
8. Jane Street's S&P and Moody's rating letters.
9. Q3 2026 hyperscaler call transcripts on fool.com were not read; capex guidance is from press.
10. Anthropic S-1 figures are from secondary analyses. To verify: https://www.sec.gov/Archives/edgar/data/2130357/000162828026067168/anthropicpbc-sx1.htm . NScale S-1 (Anthropic contract): https://www.sec.gov/Archives/edgar/data/0002110365/000119312526395475/ck0002110365-20260918.htm

---

## 8. Sources

Primary, read this session:

- SEC XBRL company facts (T2): https://data.sec.gov/api/xbrl/companyfacts/CIK0000789019.json (Microsoft), CIK0001326801.json (Meta), CIK0001045810.json (NVIDIA), CIK0001652044.json (Alphabet), CIK0000051143.json (IBM)
- CoreWeave Q2 2026 10-Q, debt and concentration notes (T1): https://www.sec.gov/Archives/edgar/data/1769628/000176962826000366/crwv-20260630.htm
- CoreWeave 8-Ks and releases for DDTL 4.0 (SOFR + 2.25%, A3 / A (low)), DDTL 5.0 (SOFR + 4.50%, two non-investment-grade customers), DDTL 5.5 (SOFR + 5.50%) (T1): .../000176962826000129/, .../000176962826000236/, .../000176962826000357/
- CoreWeave Q3 2026 call transcript (T1): https://www.fool.com/earnings/call-transcripts/2026/11/10/coreweave-crwv-q3-2026-earnings-call-transcript/
- Prior research files in /home/user/jk/research/ (contract terms, backlog and RPO figures, with their own source lists)

Search summaries only, not opened:

- OpenAI revenue report and market reaction: https://www.cnbc.com/2026/10/08/open-ai-revenue-nvidia-oracle-coreweave.html ; https://qz.com/openai-annualized-revenue-50-billion-correction-ai-stocks-100826 ; https://www.tikr.com/blog/coreweave-stock-fell-nearly-8-in-a-day-on-an-openai-revenue-report-heres-why-its-borrowing-model-raises-the-stakes ; https://247wallst.com/investing/2026/10/09/openais-revenue-is-reportedly-20-billion-lower-than-thought-nvidia-just-lost-170-billion/ ; https://startupfortune.com/coreweave-bond-yields-near-15-percent-as-stock-sinks-on-ai-debt-fears/ ; https://9to5ai.tech/ai-stocks-credit-selloff-coreweave-bonds-october-2026
- OpenAI funding, burn, commitments: https://tech-insider.org/openai-122-billion-funding-round-852-billion-valuation-2026/ ; https://finance.yahoo.com/technology/ai/articles/openai-projects-70-billion-annualized-113114847.html ; https://finance.biggo.com/news/d52272f6-21ab-497b-8663-2e87dd7b6a03 ; https://presenc.ai/research/openai-compute-commitments-tracker-2026 ; https://valueaddvc.com/pulse/openai-278b-cash-burn-1-2-trillion-valuation-2026 ; https://sacra.com/c/openai/
- Anthropic: https://www.9fin.com/insights/anthropic-s-1-revenue-gains-looming-infrastructure-bill ; https://finance.yahoo.com/technology/ai/articles/anthropic-1-numbers-thriving-business-070000837.html ; https://www.geekwire.com/2026/whos-getting-anthropics-compute-spending-ipo-filing-shows-where-the-tech-giants-really-stand/ ; https://www.cloudcomputing-news.net/news/anthropic-ai-infrastructure-518-billion/ ; https://tech-insider.org/anthropic-65-billion-series-h-965-billion-valuation-2026/ ; https://explodingtopics.com/blog/anthropic-revenue ; https://davefriedman.substack.com/p/north-american-compute-infra-report
- CDS and ratings: https://www.semafor.com/article/10/15/2026/the-cost-of-insuring-against-ai-company-defaults-spikes ; https://www.cnbc.com/2026/10/27/ai-debt-hyperscaler-earnings.html ; https://www.cnbc.com/2026/09/16/hyperscaler-debt-signals-warning-sign-apollo-cautions.html ; https://aiweekly.co/alerts/hyperscaler-debt-insurance-hits-highest-cost-since-2021
- Capex guidance: https://www.cnbc.com/2026/10/21/meta-earnings-q3-2026-live-updates.html ; https://www.cnbc.com/2026/10/29/amazon-amzn-q3-earnings-report-2026.html ; https://valueaddvc.com/ai-spending
- Jane Street: https://www.gurufocus.com/news/8816562/jane-street-group-reports-record-396-billion-in-trading-revenue ; https://www.disruptionbanking.com/2026/08/06/why-has-fitch-broken-ranks-on-jane-street-despite-its-india-and-terraform-risks/ ; https://ppc.land/jane-street-loses-15bn-as-leveraged-ai-bets-collapse-in-july/
- Cohere, Mistral, Reflection: https://valueaddvc.com/blog/cohere-valuation-revenue-2026-enterprise-ai-240m-arr ; https://www.trendingtopics.eu/cohere-series-e-schwarz-group-aleph-alpha/ ; https://techfundingnews.com/mistral-ai-3b-euro-20b-valuation-data-centres/ ; https://valueaddvc.com/blog/reflection-ai-valuation-2026-25b-46x-in-a-year-and-the-6-3b-spacex-deal-explained
- Default study: https://www.spglobal.com/ratings/en/research/articles/250327-default-transition-and-recovery-2024-annual-global-corporate-default-and-rating-transition-study-13452126 ; https://investorfactbook.spglobal.com/sp-global-ratings/ratings-track-record-standing-the-test-of-time/
