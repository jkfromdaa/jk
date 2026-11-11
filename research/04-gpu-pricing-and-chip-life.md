# GPU rental pricing and economic life — evidence and proposed ranges

Compiled 2026-11-11 for the CoreWeave (CRWV) / Nebius (NBIS) work.

**Evidence marks.** [P] = primary page or document text read in this session. [S] = search-result summary only, page not opened. INFERRED = my arithmetic. Source tiers: T1 company, T2 counterparty or index publisher, T3 press, T4 blog/aggregator.

**Limits of this pass.** Only www.fool.com, www.coreweave.com, nebius.com and local SEC text could be read directly. Every index reading, every hyperscaler useful life and every third-party forecast below is [S]. The search budget was cut to about 15 searches in total, so item 4 (forward views) is thin and several items in the brief are listed as not sourced in section 9.

---

## 0. What the evidence supports, in short

- **Today (Nov 2026).** H100 index prices are $3.01–3.30 per GPU-hour [S], up 50–65% from the $1.70–2.00 trough of Oct–Dec 2025 [S]. New 4–5 year contracts on current chips price at $20–25M per MW per year at both companies [P], which is about $4.3–5.4 per GB300-hour at rack-level power and $5.7–7.1 at the one facility-level density that is public (INFERRED).
- **The investor's $3.50 base case** sits below today's new-contract price for a GB300 on any density assumption I could source, and close to what CoreWeave's own renewal figures imply for its older fleet ($3.5–3.8 per GPU-hour, INFERRED).
- **No forward curve exists yet.** Both futures contracts (ICE/Ornn, CME/Silicon Data) are still pending regulatory review [S]. That is the main reason the 2028+ ranges rest on mechanism, not market prices.
- **Decay rate.** The one clean observation is the H100: spot fell about 75% from the 2023 peak to the late-2025 trough (roughly 45% a year), then recovered half of that in eleven months [S]. Contract prices moved far less: CoreWeave's average H100 price ended 2025 within 10% of where it started [P]. Spot decay overstates what a contracted fleet experiences.
- **Economic life.** A chip introduced in 2020 (A100) was contracted in mid-2026 through 2029 [P]. That supports six years or more in a shortage. Nothing observed yet tests life in a glut.

---

## 1. Live trackers (item 1)

| Tracker | Publisher / URL | What it measures | Frequency | Access | Latest reading | Evidence |
|---|---|---|---|---|---|---|
| H100 Rental Index (SDH100RT) | Silicon Data, silicondata.com/products/silicon-index/h100; also on Bloomberg | Like-for-like H100 $/GPU-hour across neoclouds and marketplaces | Daily | Headline free; history paid | **$3.01 on 2026-11-09**; $2.97 on 11-05; $2.81 on 10-07; $2.00 on 2025-12-09. The public page showed a stale $2.53 (snapshot ~118 days old) | [S] T2/T4 |
| OCPI H100 | Ornn, data.ornn.com; Bloomberg tickers | H100 SXM $/GPU-hour, daily settlement | Daily | Headline free | **$3.30 on 2026-11-09**; $3.12 on 10-20; $2.86 early Oct; an older page showed $2.59 on 10-04 (conflicts with $2.86) | [S] T2 |
| OCPI B200 | Ornn | B200 $/GPU-hour | Daily | Headline free | ~$4.08 (date not captured; article headline says +48%) | [S] T4, unverified |
| H100 Daily & Contract Pricing Index | SemiAnalysis, gpu-index.semianalysis.com | H100 composite plus 1-year contract range; B200 tier | Monthly public rows | Partly free | H100 composite $2.82; **1-year contract $2.10–2.70 (Apr 2026 row)**; 1-year contract $2.35 in Mar 2026 vs $1.70 in Oct 2025. No Oct/Nov 2026 row found | [S] T2 |
| getdeploying.com | GetDeploying | Median on-demand list price across ~45 providers | Continuous | Free | Median H100 on-demand **$4.04 on 2026-11-10** (from the brief; not re-verified) | [S] T4 |
| gpu.ai | gpu.ai/gpus/... | Cheapest listed price by chip | Continuous | Free | A100 80GB "from $1.07/hr (November 2026)" | [S] T4 |
| AI Compute Tracker | aicomputetracker.com | Posted list prices, specialist clouds | Periodic | Free | A100 80GB specialist median ~$2.30 (late Aug 2026); floor $1.35 | [S] T4 |
| CoreWeave price list | coreweave.com/pricing | Own on-demand and spot list | Live | Free | See section 2 | [P] T1 |
| Nebius price list | nebius.com/prices | Own on-demand and preemptible list | Live | Free | See section 2 | [P] T1 |
| Akash, SF Compute, Vast.ai | — | Marketplace prices | Live | Free | Not captured in this pass | not sourced |

**Futures and forward prices.**

- ICE has specified a monthly cash-settled OCPI H100 future (symbol HPR) and a B200 future. Both are "pending the CFTC comment period"; no listing date [S, ICE product page and exchange notice].
- CME and Silicon Data planned H100 and B200 rental futures for 2026-10-05; the launch was delayed twice at the CFTC's request, most recently to January [S, T4].
- One tracker reports "futures" on A100 list prices that are nearly flat to August 2027 (+0.9%). These are posted quotes, not trades [S, T4].
- A Substack claim that OCPI contracts trade on Kalshi and Robinhood could not be confirmed [S, T4].
- **Net: there is no traded forward curve for 2027 as of today.** The first listing date is the event to watch.

**How to track it.** Use SDH100RT and OCPI H100 for the daily spot direction, the SemiAnalysis 1-year contract row for what term buyers pay, and the two company price pages plus each quarter's $/MW comments for contract pricing. The index-to-contract gap matters: on 2026-11-09 the indices read $3.0–3.3 while CoreWeave's on-demand list was $6.16 and its spot $2.46.

---

## 2. Price history by generation (item 2)

All figures $ per GPU-hour.

### 2.1 List prices read today [P]

| Chip | CoreWeave on-demand | CoreWeave spot (US) | Nebius on-demand | Nebius preemptible |
|---|---|---|---|---|
| A100 80GB | $2.70 | $1.21 | not listed | — |
| H100 | $6.16 | $2.46 | $4.50 | from $0.79 |
| H200 | $6.31 | $2.62 | $5.40 | from $0.79 |
| B200 (HGX) | $8.60 | $4.26 | $8.50 | from $0.99 |
| B300 (HGX) | contact sales | $4.48 | $9.50 | from $0.99 |
| GB200 NVL72 | $10.50 | n/a | contact us | — |
| GB300 NVL72 | contact sales | n/a | contact us | — |
| Vera Rubin | not listed | — | not listed | — |

Per-GPU figures are the instance price divided by GPU count (INFERRED for spot; CoreWeave prints the per-GPU on-demand price). CoreWeave's H100 at $6.16 is well above the indices, consistent with two list increases in Q3 2026 (+25% in July, +10% later) [P].

### 2.2 Dated history

| Date | Chip | Price | Type | Source | Evidence |
|---|---|---|---|---|---|
| 2023 (peak) | H100 | $7–10; commonly "~$8" | (i) spot/on-demand | Silicon Data blog; vendor blogs | [S] T2/T4 |
| Early 2023 | A100 | ~$3.00 | (i) marketplace | Vast.ai-related note | [S] T4, weak |
| Mid-2024 | H100 (used card) | up to $50,000 per card | resale | Hashrate Index | [S] T4 |
| Before Jun 2025 | H100 | ~$7.57 | (iii) AWS P5 on-demand | vendor blogs | [S] T4 |
| Jun 2025 | H100 | ~$3.90 after a 44–45% cut (another source: still ~$7 on AWS/Azure) | (iii) AWS P5 | conflicting blogs | [S] T4 |
| 2025 | H100 | $2.85–3.50 | (i)/(ii) | Thunder Compute | [S] T4 |
| Oct 2025 | H100 | $1.70 (trough) | (iv) 1-year contract | SemiAnalysis | [S] T2 |
| 2025-12-09 | H100 | $2.00 | (i) index | Silicon Data | [S] T2 |
| Full-year 2025 | H100 | Q4 average "within 10% of where it started the year" | (iv) CoreWeave blended | CoreWeave Q4 2025 call | [P] T1 |
| Full-year 2025 | A100 | average price "increased in 2025" | (iv) CoreWeave | CoreWeave Q4 2025 call | [P] T1 |
| Feb 2026 | A100 80GB | ~$0.72 | (i) Vast.ai average | blog | [S] T4 |
| Mar 2026 | H100 | $2.35 | (iv) 1-year contract | SemiAnalysis | [S] T2 |
| Apr 2026 | H100 | $2.10–2.70; composite $2.82 | (iv) / composite | SemiAnalysis | [S] T2 |
| Q1 2026 | A100, H100, H200, L40 | average price up quarter on quarter | (iv) CoreWeave | Q1 2026 call | [P] T1 |
| Jun 2026 | B200 | ~$3.70 | (ii) neocloud on-demand | blog | [S] T4 |
| Jul 2026 | B200 | $4.90–5.64 | tier range | blog | [S] T4 |
| Mid-2026 | GB300 | ~$5.88 (another source: $10.50–30) | unclear | blogs, conflicting | [S] T4 |
| Q2 2026 | older generations | ">30% higher pricing ... versus Q1" | (iv) Nebius | Q2 2026 letter | [P] T1 |
| Late Sep 2026 | B200 | $8.01 | attributed to SemiAnalysis | secondary article; conflicts with other B200 prints | [S] T4, unverified |
| Q3 2026 | A100 / H100 | "increased 30% to 50% quarter over quarter, and at prices above their original contracts" | (iv) CoreWeave | Q3 2026 call | [P] T1 |
| 2026-10-07 | H100 | $2.81 | index | Silicon Data | [S] |
| Oct 2026 | A100 80GB | $1.09–2.30 neoclouds; $3.43 AWS; $5.03 Google Cloud | (ii)/(iii) | Thunder Compute | [S] T4 |
| 2026-11-09 | H100 | $3.01 (Silicon Data); $3.30 (Ornn) | index | — | [S] T2 |
| 2026-11-11 | all | section 2.1 | (ii) list | company pages | [P] T1 |

### 2.3 One line per generation

- **A100 (2020):** about $3 in early 2023 [S, weak]; $0.7–1.4 on marketplaces and $2.30–2.70 at neoclouds in 2026; CoreWeave's contracted A100 price rose through 2025 and 2026 [P].
- **H100 (2023):** $7–10 peak in 2023; $1.70–2.00 trough in Oct–Dec 2025; $3.0–3.3 index and $4.50–6.16 neocloud list in Nov 2026.
- **H200 (2024):** only today's list is sourced: $5.40–6.31 on-demand, $2.62 spot.
- **B200/GB200 (2025):** $3.70 (Jun 2026) to $4.9–5.6 (Jul 2026) on third-party trackers [S]; $8.50–8.60 on-demand list and $4.26 spot today; GB200 $10.50 list [P].
- **GB300 (late 2025):** no public list price at either company. Contract pricing is the $/MW figures in section 3.
- **Vera Rubin (first production 2026-09-30):** no price found. CoreWeave says its margin step-up on new deals is coming "in the Vera Rubin SKU" [P].

### 2.4 Why the three phases

- **2023 peak.** H100 scarcity. Sources agree on the level, not on a single cause; I did not source the supply chain detail [S].
- **2024–2025 decline.** Supply caught up with demand on spot markets (Introl: "64% decline"; others "more than 60%") [S, T4]. Hyperscaler list prices followed late (AWS cut P5 by ~44% in June 2025) [S].
- **2026 rebound.** Company statements attribute it to inference demand and sold-out capacity: "We are sold out in our H100s. We are sold out in our A100s" (CoreWeave, Q1 2026) [P]; Nebius "sold out" every quarter from Q3 2025 to Q2 2026 [P]. Component cost increases were passed through (CoreWeave capex guidance raised for "increases in component pricing") [P]. Press adds HBM and CoWoS shortages lasting to at least mid-2027 [S, T4].

---

## 3. Contract pricing per MW and the conversion (item 3)

### 3.1 Per-MW datapoints

| Date | Company | Figure | Contract type | Evidence |
|---|---|---|---|---|
| FY2025 | CoreWeave | $5.1B revenue on >850 MW active at year-end (~360 MW at start). On the average of the two, about **$8M per active MW** | realized, blended | [P] inputs; INFERRED ratio, rough |
| Q2 2026 | CoreWeave | $6.9–8.2M annualized revenue per active MW | realized | [S] T4 arithmetic |
| Q2 2026 | Nebius | $11.1M annualized revenue per active MW | realized | [S] Bernstein via T4 |
| 2026–2027 | Neoclouds | ~$12M per MW (HSBC; CoreWeave 2027 average), vs $17–18M for hyperscalers | analyst estimate | [S] T3 |
| Q2 2026 (signed) | Nebius | **$20–25M ACV per MW**, 1–3 year terms, four deals averaging >$1B; prepayments covering 50–60% of capex; payback under 2 years | new contracts | [P] T1 |
| Early Q3 2026 | Nebius | **$40–50M per MW** for 3–6 month GB300 clusters; first one signed Aug 2026. Auction cleared 15% above any prior price and 20% above its Blackwell pipeline | short-term | [P] T1 |
| Q3 2026 | CoreWeave | **$20–25M per MW** on new 4–5 year contracts ("moving to"); **>$40M per MW** short-term | new contracts | [P] T1 |
| Q3 2026 | CoreWeave | Hardware capex payback 1–2 years on long contracts, 6–18 months on short | new contracts | [P] T1 |

No per-MW or per-GPU contract price for 2023–2025 was found in a primary document for either company. The order forms that carry price are unfiled (see the step-1 summary). The realized-revenue rows are the only window on older pricing: **contracts signed in 2024–2025 appear to have priced at roughly $8–12M per MW, about half of today's new-contract level** (INFERRED, low precision, because active MW ramps within each period).

### 3.2 Power per GPU

| System | Rack power | kW per GPU | GPUs per MW of IT load | Evidence |
|---|---|---|---|---|
| H100 chip | 700 W TDP | — | — | [S] T4 |
| H100, 8-GPU HGX server | ~10.2 kW per server (my recollection of the DGX H100 spec; **not sourced in this session**) | ~1.3 server; ~1.4 with network (assumed) | ~715 | assumption |
| GB200 NVL72 | ~120 kW | 1.67 | 600 | [S] T4 (Spheron and others) |
| GB300 NVL72 | 135 kW TDP, peak ~155; another source 132–142 kW. CoreWeave describes "~130 kW racks" | 1.83–1.97 | 507–545 (use 533) | [S] T4; CoreWeave figure from step-1 file |
| GB300, facility level | Ellendale building 1: ~100 MW critical IT [P, Applied Digital 10-K] holding "more than 40,000" GB300 (step-1 file, landlord) | ≤2.5 | **~400** | INFERRED |
| Vera Rubin NVL72 | 190–230 kW "reported, not NVIDIA-confirmed"; NVIDIA told CNBC about twice Blackwell | 2.6–3.2 | 313–379 | [S] T3/T4 |

The gap between 533 (rack only) and 400 (whole hall) is networking, storage, CPU nodes and headroom. Which one a company means by "per MW" is not stated. CoreWeave reports active power as "critical IT load" [P], which points to the facility-level figure.

### 3.3 Conversion (INFERRED)

Formula: $/GPU-hour = ($ per MW-year) ÷ (GPUs per MW) ÷ 8,760. Assumes every hour is billed (take-or-pay).

| $ per MW-year | GB200 (600/MW) | GB300 rack (533/MW) | GB300 facility (400/MW) | Vera Rubin (313–379/MW) |
|---|---|---|---|---|
| $10M | $1.90 | $2.14 | $2.85 | $3.01–3.65 |
| $12M | $2.28 | $2.57 | $3.42 | $3.61–4.38 |
| $20M | $3.81 | $4.28 | $5.71 | $6.02–7.29 |
| $25M | $4.76 | $5.35 | $7.13 | $7.53–9.12 |
| $40M | $7.61 | $8.57 | $11.42 | $12.0–14.6 |
| $50M | $9.51 | $10.71 | $14.27 | $15.1–18.2 |

Checks against other evidence:

- CoreWeave's GB200 on-demand list of $10.50 [P] equals $55M per MW at 600 GPUs/MW. On-demand list sits above even the short-term contract figure, as expected.
- CoreWeave's renewal statement: 130,000 GPUs in 2027 at "approaching $4 billion" and ~300,000 by 2028 at "nearly $10 billion" of annualized revenue [P]. That is **$3.51 and $3.81 per GPU-hour** (INFERRED), for a fleet that is mostly Hopper-era. The CFO described the figure as "the ARR to be generated against that infrastructure"; if it is instead uplift over current revenue, the implied price is higher.
- H100 at $3.00–3.30 and ~715 GPUs/MW is $19–21M per MW. Old chips at today's index earn about the same per MW as new long contracts, which is why power, not chips, is the scarce input right now.

---

## 4. Forward views (item 4) — limited to what was attributable

| Source, date | Statement | Direction for price | Evidence |
|---|---|---|---|
| CoreWeave, 2026-11-10 | Pricing "continued to move higher in Q4". "If data center construction across the sector were to slow, installed compute becomes scarcer ... GPU pricing may stay higher for longer." Management says the plan is not built on that scenario | Up near term; management's own hedge on duration | [P] T1 |
| Nebius, 2026-08-12 | "We could sell today our entire 2027 capacity on these terms"; deliberately not pre-selling, "reflecting our confidence with respect to future pricing" | Up into early 2027 | [P] T1 |
| Alphabet, Amazon, Meta, Microsoft, late Oct 2026 | Alphabet: 2027 capex to "increase significantly" (2026: $195–205B). Amazon: "meaningfully more in 2027" (2026: ~$220B). Meta: 2026 at $135–145B, no 2027 number. Microsoft cut FY guide to $170B from $175B, citing third-party delays pushing capacity to H1 2027 | Demand for capacity still rising; supply slipping right | [S] T3 (CNBC, 2026-10-29) |
| Sell-side consensus | 2027 capex ~$285B Google, ~$257B Amazon, ~$208B Microsoft, ~$186B Meta | Same | [S] T4 table |
| BofA (date not captured) | Models "the GPU supply-demand imbalance persisting through at least 2029" | Up / flat through 2029 | [S] T4 relay |
| HSBC (Sep–Oct 2026) | Reduce on CoreWeave; expects ~$12M revenue per MW in 2027 | Realized pricing well below new-deal pricing | [S] T3 |
| Bloomberg-sourced (2026) | NVIDIA told customers to expect >15% price increases on Grace Blackwell and Vera Rubin servers shipping early 2027 | Cost push; supports rental prices | [S] T4 relay |
| NVIDIA / CoreWeave | Vera Rubin: ~10x tokens per MW vs GB200 on one workload (CoreWeave measurement); NVIDIA claims up to 30x vs GB300 on an agentic workload; ~2x rack power | Bearish for old chips where power is the constraint; see section 7 | [S] T1/T2 pages not opened |
| Tracker blogs (2026) | H100 "toward roughly $1/hr by mid-2027"; "$2–3 through 2026 then $1–1.50 ... 2027–28"; "another 20–30%" | Down for old generations | [S] T4, no method |
| NVIDIA roadmap | Rubin Ultra (NVL576) "late 2027" from one secondary article; Feynman timing not found | A successor roughly every 12 months | [S] T4 |

Not found in this pass: SemiAnalysis, Epoch AI, McKinsey, Bain or IEA forecasts; cost-per-token trend data; a quantified 2027–2028 supply schedule; moratoria beyond what the step-1 summary already records.

**Decay rate once a successor ships.**

| Case | Observation | Annualized | Evidence |
|---|---|---|---|
| H100 spot, 2023 peak to Oct–Dec 2025 trough | ~$8 to $1.70–2.00, about −75% over ~2.3 years. Blackwell volume arrived during 2025 | about −45% a year | [S]; INFERRED rate |
| H100 spot, Dec 2025 to Nov 2026 | $2.00 to $3.01–3.30 | +50% to +65% | [S] |
| H100 CoreWeave contracted average, 2025 | within 10% over the year | 0 to −10% | [P] |
| H100 CoreWeave, Q3 2026 | +30–50% in a quarter, above original contract prices | positive | [P] |
| A100 relative to H100, Nov 2026 | CoreWeave list $2.70 vs $6.16 (44%); spot $1.21 vs $2.46 (49%) | n/a | [P]; INFERRED ratio |
| A100 absolute, early 2023 to 2026 | ~$3.00 to $2.30–2.70 at neoclouds; $0.7–1.4 on marketplaces | −3% to −35% a year | [S], weak start point |

Two things follow. First, spot and contract decay are different numbers, and the companies live on contract prices. Second, the 2023–2025 fall started from a scarcity peak; using −45% a year as a steady-state rate would double count the unwind of that peak. A defensible steady-state range for an ageing chip is **−10% to −25% a year in a balanced market, −40% to −50% in the year a glut arrives, and flat to positive while capacity is sold out.**

---

## 5. Proposed price ranges (item 5)

Convention: $/GPU-hour for a GB300 uses 533 GPUs per MW (rack level). Multiply by 1.33 for the 400/MW facility-level view.

### 5.1 New long-term contracts on the then-current chip, $M per MW-year

| Horizon | Low | Central | High | Confidence |
|---|---|---|---|---|
| Today | — | 20–25 | 40–50 short-term | observed [P] |
| Year-end 2027 | 15 | 20–24 | 28 | Medium-high |
| Year-end 2028 | 11 | 15–21 | 27 | Medium-low |
| 2029–2031 | 9 | 12–18 | 24 | Low |

Evidence behind each bound:

- **2027 central 20–24.** Both companies sign at $20–25M now [P]; Nebius calls the Q2 deals "the baseline for pricing early next year" [P]; CoreWeave has >75% of its 2027 exit run-rate contracted [P]; chip-supply tightness is reported to last to at least mid-2027 [S].
- **2027 high 28.** CoreWeave's two list increases compound to +37.5% in one quarter [P], and NVIDIA is reported to be raising server prices >15% for early 2027 [S]. One more pass-through of that size on $24M gives ~$28M.
- **2027 low 15.** Midpoint between today's $20M floor and the ~$8–12M realized on earlier contracts (section 3.1). It needs a demand shock or a financing-driven fire sale within twelve months; neither is in evidence, but credit conditions for neoclouds worsened in October 2026 (step-1 summary).
- **2028 low 11.** Full reversion to the 2025–early 2026 realized level (Bernstein $11.1M, HSBC ~$12M) [S].
- **2028 high 27.** Shortage persists (BofA "through at least 2029") [S] with a modest cost pass-through.
- **2029–2031 central 12–18.** Mechanism, not observation. CoreWeave says hardware pays back in 1–2 years at $20–25M per MW [P], so hardware costs roughly $25–45M per MW (INFERRED). A payback that short invites entry. If competition pushes payback out to 2.5–3 years at similar hardware cost, price falls to $10–18M.
- **2029–2031 low 9.** A glut year on top of that: 3-year-plus payback at the lower hardware cost.
- **2029–2031 high 24.** Today's level persists because power stays the binding constraint.

### 5.2 A GB300 bought in 2026, as it ages, $ per GPU-hour

This is the price to re-rent the chip in the market at that date. Capacity already under a 4–5 year contract keeps earning its signed price ($4.3–5.4 at 2026 terms) whatever this table says.

| Horizon | Chip age | Low | Central | High | Confidence |
|---|---|---|---|---|---|
| Today | 0–1 | — | 4.3–5.4 long contract; ~4.5 spot (HGX B300) | 8.6–10.7 short-term | observed [P] |
| Year-end 2027 | 1–2 | 3.0 | 4.0–4.6 | 5.5 | Medium-high |
| Year-end 2028 | 2–3 | 2.0 | 3.0–3.8 | 4.6 | Medium-low |
| 2029–2031 | 3–5 | 0.9 | 1.6–2.6 | 3.6 | Low |

Evidence behind each bound:

- **2027 central.** Flat to −10% on today's contract price. Rubin ships in volume during 2027, but both companies describe 2027 capacity as sellable now at current terms [P].
- **2027 low 3.0.** One glut-year step (−35 to −45%) from $4.3–5.4. Cross-check: it equals today's H100 index, i.e. a GB300 would have to rent for no more than a 2023 chip does now.
- **2027 high 5.5.** Top of today's long-contract range with no decay; CoreWeave's Hopper pricing rose after Blackwell shipped [P], so a no-decay year has a precedent.
- **2028 central.** Two years at −10% to −20% from $4.3–5.4.
- **2028 low 2.0.** The H100 precedent: the Dec 2025 index print for a chip 2.5 years after launch [S].
- **2028 high 4.6.** The A100/H100 precedent of rising older-generation prices in a sold-out market [P], held roughly flat.
- **2029–2031 central.** Continued −15% to −25% a year from the 2028 central. Cross-check: the A100 at six years rents for 44–49% of the H100 on CoreWeave's own list [P]; half of a 2029 current-chip price of $3–5 lands in the same range.
- **2029–2031 low 0.9.** Cash-cost floor (INFERRED): data center rent of $1.8–2.6M per MW-year (step-1 summary, landlord filings) is $0.39–0.56 per GPU-hour at 533/MW, plus power at an assumed $0.06–0.08/kWh and PUE 1.25 (~$0.15–0.19), plus operations. Below roughly $0.8–1.0 the chip is better switched off and the power given to a newer rack. Rubin's reported 10x tokens per MW [S] is what makes this floor reachable when power is scarce.
- **2029–2031 high 3.6.** The implied price in CoreWeave's own renewal guidance ($3.5–3.8) for 3–5 year old chips [P, INFERRED], assumed to hold for the next generation at the same age.

### 5.3 Where the evidence runs out

- **2027:** supported by signed contracts and stated sold-out positions. The main unknown is how much 2027 capacity is still unpriced.
- **2028:** no contract, index or futures price reaches it. It rests on the decay-rate table and on one sell-side line (BofA).
- **2029–2031:** entirely mechanism: cash-cost floor at the bottom, payback-competition logic in the middle, persistence of today's shortage at the top. No source found forecasts rental prices that far out with a method.
- Against the illustrative model: at ±$0.50 moving the return 8–9 points, the 2028 range ($2.0–4.6) alone spans the whole space between a large loss and a large gain. Contract cover in years 1–5, not the spot path, is what narrows it.

---

## 6. Accounting useful lives (item 6)

| Company | Life used for servers / GPUs | Last change | Evidence |
|---|---|---|---|
| CoreWeave | "Technology equipment 6 years" | "Effective January 1, 2023, the Company changed its estimate of the useful life for its computing equipment utilized in data centers from five to six years"; 2023 effect $20M | [P] FY2025 10-K |
| Nebius | 5 years, servers and network equipment | Extended "from four to five years", applied prospectively from 2026-01-01; cut H1 2026 depreciation by $86.1M ($43.0M in Q2) | [P] Q2 2026 interim statements and letter |
| Microsoft | Servers and network equipment "two to six years" | 4 to 6 years in FY2023 (not re-sourced here) | [S] |
| Alphabet | 6 years, servers and network | Extended from 4 in 2023 (per aggregator) | [S] |
| Amazon | 5 years for a subset of servers and networking; 6 for the rest | Cut 6 to 5 for that subset from January 2025, citing the pace of AI/ML; ~$700M operating income effect and $920M accelerated depreciation | [S] |
| Meta | 5.5 years for most servers and network | Raised effective 2025-01-01; reduced depreciation by $2.92B | [S] |
| Oracle | 6 years per one aggregator; "1–6 years" per another | n/d | [S], conflicting |
| IREN | HPC hardware 5 years (mining hardware 4) | n/d | [S] |
| Applied Digital | Networking, electrical equipment, software 3–5 years. It is a landlord; GPUs are the tenant's | n/d | [S] FY2026 10-K |
| Lambda, Crusoe | not found | — | not sourced |

**The 2025–2026 debate.**

- Michael Burry (November 2025) argued the hyperscalers overstate server lives, put real life at two to three years, and estimated ~$176B of understated depreciation over 2026–2028. That figure is his projection [S, CNBC 2025-11-14 and relays]. Advocacy, from a declared short.
- JPMorgan Asset Management sensitivity: a three-year life would cut 2025 EPS by ~6–7% at Amazon, Meta and Microsoft, ~6% at Alphabet, ~17% at Oracle [S].
- Amazon is the only large operator that shortened a life in this period; Meta and Nebius lengthened [S]/[P].
- Hyperscaler policies cover servers as a class. None discloses a GPU-specific life [S].
- CoreWeave's own risk factor: "any inability to redeploy components of our existing infrastructure to extend past their contracted life could significantly affect our business" [P].

---

## 7. Evidence on real economic life (item 7)

**Facts (company statements read in primary transcripts)**

- CoreWeave, Q2 2026: "we recently signed an A100 contract that extends into 2029 at an attractive price. As a reminder, this SKU was introduced in 2020." Also: "a GPU whose architecture was from 2020 in a contract that was fully priced out to 2029" [P]. Price not given. The age of the specific units is not given; the architecture will be nine years old in 2029.
- CoreWeave, Q3 2026: "We are signing multiyear commitments extending beyond the GPUs' depreciable lives" [P].
- CoreWeave, Q3 2026: more than 130,000 GPUs come off contract in 2027 and ~170,000 in 2028; $3B+ of prepayments in the next three months relate to recontracting existing infrastructure "at meaningful premiums to their original price" [P].
- CoreWeave, Q4 2025: Hoppers recontracting at "about 10% of the original ASPs" in the transcript, which the same call's summary line renders as H100 pricing "within 10%" of start-of-year levels. Read as within 10% of original; the transcript wording is garbled [P].
- CoreWeave, Q2 2026: "largely sold out of prior generations"; renewals so far are "a very limited part of our fleet" [P]. The sample of actual renewals is small.
- CoreWeave still lists A100 at $2.70 on-demand and $1.21 spot [P]; Nebius no longer lists A100 [P].
- Nebius gives "usage patterns and current utilization commitments" as the reason for its five-year life [P].

**Facts with weaker sourcing**

- Used H100: $15,000–28,000 per card and $150,000–195,000 per 8-GPU server in 2026, versus up to $50,000 per card in mid-2024 [S, resellers]. Against a new price of $25,000–40,000 [S], that is roughly 50–85% retained at two to three years.
- Meta's Llama 3 run: 148 GPU failures among 16,384 H100s in 54 days, extrapolated by others to ~9% a year [S]. A 54-day window annualized, not a lifetime measurement.
- Vera Rubin delivers ~10x tokens per MW versus GB200 on one measured workload [S, CoreWeave blog not opened], at about twice the rack power.

**Advocacy or unverified**

- "Datacenter GPUs last one to three years": one unnamed Alphabet architect, reported second-hand in 2024; the report itself says it needs confirmation [S].
- Burry's two-to-three-year life (section 6).
- CoreWeave's CEO on life ("I have been pretty steadfast around what I believe is going to be the useful life") is also an interested party [P]. His claims above are counted as fact only where they describe signed contracts.

**What the evidence does and does not show**

- It shows chips of 2020 and 2023 vintage fully rented, at rising prices, in late 2026. That is one market state: shortage.
- It does not show what happens to a five-year-old chip when power is scarce and a successor produces several times the output per MW. In that state the old chip's value is capped by the opportunity cost of its power, and retirement can come before physical failure. No retirement of a working fleet for this reason was found.
- The 2025 trough is the nearest test: H100 spot fell 75% from peak, but CoreWeave's contracted price held within 10% [P]. Price fell; utilization of contracted fleets did not.

---

## 8. Proposed ranges for economic life (item 8)

**Earning life (years of rental income after deployment)**

| Case | Years | Evidence or mechanism |
|---|---|---|
| Low | 4 | Shortest accounting life in use before 2026 (Nebius, four years) [P]; Amazon's cut to five for AI-heavy servers [S]; power displacement by Rubin-class systems once a site is power-limited. Burry's 2–3 years is below any operator's observed practice and is not used as the bound |
| Central | 6 | CoreWeave's accounting life [P]; hyperscaler cluster of 5–6 [S]; H100s at 3.5 years rent above original contract prices [P] |
| High | 8 | A100 contracted to 2029, nine years after introduction [P]. Applies only if shortage conditions recur late in life |

Confidence: years 1–5 are largely settled by contract for capacity sold on 4–5 year terms. The uncertainty is years 5–8, and half a year there is worth less than half a year lost at the front through deployment delay, which the step-1 work shows is the more frequent event.

**Residual rental value, as a share of the year-1 price**

| Age | Low | Central | High | Anchor |
|---|---|---|---|---|
| Year 2 | 70% | 90% | 105% | H100 contracted price within 10% through 2025 [P]; high = 2026 increases [P] |
| Year 3 | 45% | 75% | 105% | Low = H100 index trough relative to early contract-level prices [S]; high = H100 above original contract in Q3 2026 [P] |
| Year 4 | 35% | 60% | 95% | H100 at 3.5 years, index $3.0–3.3 vs 2023–2024 list |
| Year 5 | 25% | 50% | 80% | Interpolated |
| Year 6 | 20% | 40% | 70% | A100 at six years: 44–49% of H100 on CoreWeave's list [P]; ~$2.30–2.70 vs ~$3.00 in 2023 [S] |
| Years 7–8 | 0–15% | 25% | 50% | Low = cash-cost floor reached, chip retired; high = A100 2029 contract [P] |

The central column implies roughly −12% a year. The low column implies roughly −25% a year and retirement after year 6. Both sit inside the decay table in section 4.

---

## 9. What could not be sourced

1. A traded forward curve. Neither futures contract is listed.
2. Any primary read of an index page. All index readings are from search summaries, and Ornn's October figures conflict ($2.59 on 10-04 vs $2.86 "early October").
3. Per-MW or per-GPU contract prices for 2023–2025 from a primary document.
4. A list or contract price for GB300 NVL72 or Vera Rubin.
5. Lambda and Crusoe prices and useful lives; Akash, SF Compute and Vast.ai readings.
6. A clean A100 price series 2020–2026. The A100 decay figures rest on one weak 2023 starting point.
7. Hyperscaler useful lives from the 10-Ks themselves. To confirm, read the property-and-equipment policy notes in the latest 10-K of Microsoft, Alphabet, Amazon, Meta, Oracle and IREN on www.sec.gov (not fetched, per instructions).
8. Forecasts from SemiAnalysis, Epoch AI, McKinsey, Bain, IEA; cost-per-token trends; a dated 2027–2028 supply schedule; Rubin Ultra and Feynman timing from NVIDIA.
9. The H100 server power figure (~10.2 kW) is from memory and not sourced here.
10. Whether CoreWeave's "$4B / $10B incremental" renewal revenue is total revenue on those GPUs or uplift.
11. Nebius Q3 2026 results are due 2026-11-12 and will update the $/MW figures.

---

## 10. Sources

**Read directly [P]**

- CoreWeave Q3 2026 call transcript (Motley Fool)
- CoreWeave Q2 2026, Q1 2026, Q4 2025 call transcripts (Motley Fool)
- CoreWeave FY2025 Form 10-K
- Nebius Q2 2026 call transcript (Motley Fool)
- Nebius Q2 2026 shareholder letter and interim financial statements (Form 6-K exhibits)
- Nebius Q1 2026 interim statements: scratchpad/dl/sec_nbis/txt/000110465926064092__nbis-20260331xex99d2.txt
- Applied Digital FY2026 10-K (Ellendale building sizes)
- https://www.coreweave.com/pricing (fetched 2026-11-11; saved in scratchpad/r2a_dl/)
- https://nebius.com/prices (fetched 2026-11-11; saved in scratchpad/r2a_dl/)
- /home/user/jk/research/00-summary.md (step-1 figures for rents, Ellendale GPU count, rack power)

**Search summaries only [S]**

- https://www.silicondata.com/products/silicon-index/h100
- https://www.silicondata.com/blog/h100-rental-price-over-time
- https://www.silicondata.com/blog/h100-price-spike
- https://explainx.ai/blog/nvidia-h100-gpu-rental-price-45-percent-since-december-silicon-data-chamath-claimed-vs-verified-2026
- https://fourweekmba.com/ai-cme-delays-nvidia-gpu-rental-futures-again-to-january/
- https://data.ornn.com/ ; https://data.ornn.com/markets/bloomberg ; https://data.ornn.com/preview
- https://www.ice.com/products/83050006/Ornn-Compute-Price-Index-OCPI-H100-Future
- https://www.ice.com/publicdocs/futures_us/exchange_notices/ICE_Futures_US_Exchange_Notice_ORNN_Compute_4Q2026_20260929.pdf
- https://ir.theice.com/press/news-details/2026/ICE-and-Ornn-to-Launch-GPU-Compute-Futures-Contracts/default.aspx
- https://rillor.com/insights/gpu-rental-price-indexes-compared/report
- https://gpu-index.semianalysis.com/
- https://uvik.net/blog/gpu-price-index/
- https://gpusmith.com/articles/en/h100-rental-price-history-trends
- https://shattered.io/nvidia-b200-cloud-price-79-percent-surge-2026/
- https://tech-insider.org/nvidia-blackwell-gpu-rental-price-surge-ornn-index-2026/
- https://computestacker.com/insights/gpu-capacity-crunch-rental-prices/
- https://akash.network/the-bid/blackwell-vera-rubin-gpu-prices-2027/
- https://introl.com/blog/gpu-cloud-price-collapse-h100-market-december-2025
- https://www.itiger.com/news/1185188896 (SemiAnalysis H100 +40%)
- https://cryptobriefing.com/nvidia-h100-gpu-rental-costs-surge/
- https://www.thundercompute.com/blog/ai-gpu-rental-market-trends
- https://gpu.ai/gpus/a100-80gb
- https://aicomputetracker.com/gpu-cloud/a100-80gb/
- https://fourweekmba.com/ai-bernstein-puts-nebius-at-11-1m-revenue-per-mw-riot-1-3m/
- https://dealroom.co/news/164243-hsbc-sticks-with-reduce-on-coreweave-neoclouds-earn-12m-per-mw-versus-17/
- https://fourweekmba.com/ai-new-ai-cloud-deals-quote-20m-40m-per-mw-before-earnings/
- https://www.spheron.network/blog/nvidia-mgx-1-2-explained-what-250kw-open-racks-mean-for-gb300/
- https://datacenterdynamics.com/en/analysis/nvidia-gtc-jensen-huang-data-center-rack-density
- https://www.cnbc.com/2026/02/25/first-look-at-nvidias-ai-system-vera-rubin-and-how-it-beats-blackwell.html
- https://www.coreweave.com/blog/nvidia-vera-rubin-nvl72-on-coreweave-10x-more-tokens-per-megawatt-than-blackwell
- https://developer.nvidia.com/blog/nvidia-vera-rubin-and-blackwell-set-a-new-standard-for-agentic-ai-performance-per-watt/
- https://www.cnbc.com/2026/10/29/microsoft-google-ai-capex-estimates.html
- https://www.cnbc.com/2025/11/14/ai-gpu-depreciation-coreweave-nvidia-michael-burry.html
- https://www.datagravity.dev/p/how-long-does-a-gpu-last
- https://gpuinsights.net/server-useful-life-gpu-depreciation-2026/
- https://www.amcompute.com/gpu-depreciation-schedules
- https://www.sec.gov/Archives/edgar/data/0001144879/000114487926000048/apld-20260531.htm
- https://hashrateindex.com/blog/used-gpu-market-pricing-deprecation-secondary-ai/
- https://www.amcompute.com/gpu-server-values/h100
- https://serverbuyback.com/resources/gpu-resale-value-index/
- https://www.mercatus-ai.com/blog/h100-resale-value
- https://www.trendforce.com/news/2024/10/31/news-datacenter-gpus-may-have-an-astonishingly-short-lifespan-of-only-1-to-3-years/
- https://www.tomshardware.com/pc-components/gpus/datacenter-gpu-service-life-can-be-surprisingly-short-only-one-to-three-years-is-expected-according-to-unnamed-google-architect
- https://fullhoffman.com/2026/03/21/gpu-failure-rates/
