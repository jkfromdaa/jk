# CoreWeave and Nebius — facilities, backlog and contract conditions

Step 1 summary, compiled 2026-11-11.

- CoreWeave data is as of its Q3 2026 report (period end 2026-09-30, released 2026-11-10). Its Q3 10-Q was not yet filed, so note-level detail (RPO schedule, customer concentration, leases) is from the Q2 10-Q.
- Nebius data is as of its Q2 2026 report (released 2026-08-12). **Nebius reports Q3 on 2026-11-12; refresh sections 3 and 4 after that.**
- Debt and financing are out of scope for this step, except where a contract term or a delivery delay is tied to them.

Evidence marks: **[P]** read in the primary document (SEC filing or exhibit, company release, or call transcript); **[S]** seen only in a press or search summary, not opened; **INFERRED** is our own arithmetic or matching. Full sourcing, quotes and URLs are in the four detail files listed in the README.

---

## 1. Can the facility picture be known exactly?

No. Partly, and less than half of it from the companies themselves.

- **Neither company publishes a site list with megawatts.** Both report only fleet totals.
- **The best per-MW source is the landlords.** Core Scientific, Applied Digital and Galaxy Digital each disclose, in their own SEC filings, how many MW they have leased to CoreWeave, how many are live, and when the rest is due.
- **Hardware is disclosed at fleet level only.** Which chips, network and storage sit in which building is public for a handful of sites.
- **Memory suppliers are not disclosed by either company.** CoreWeave names Solidigm (SSD supply) and VAST Data (storage); Nebius names WEKA.

How much of each fleet can be tied to named sites:

| | Company total | Tied to named sites | Not attributable |
|---|---|---|---|
| CoreWeave active power (2026-09-30) | >1,700 MW | ~960–970 MW (793 MW from landlord filings) | ~730–740 MW |
| CoreWeave contracted power (2026-09-30) | >4,600 MW | ~2,800–2,950 MW | ~1,650–1,800 MW |
| Nebius active power (2025-12-31, last actual published) | ~170 MW | 114–152 MW | 18–56 MW |
| Nebius contracted power (target for 2026-12-31) | 5,000 MW | ~4,000 MW | ~1,000 MW |

CoreWeave runs 52 data centers; about 35 have no public MW figure [P for the count].

---

## 2. CoreWeave — facilities

### 2.1 Fleet totals [P]

| Date | Data centers | Active power | Contracted power |
|---|---|---|---|
| 2023-12-31 | 10 | ~70 MW | n/d |
| 2024-12-31 | 32 | ~360 MW | 1.3 GW |
| 2025-12-31 | 43 | >850 MW | ~3.1 GW |
| 2026-03-31 | ~49 | >1 GW | >3.5 GW |
| 2026-06-30 | 51 | 1.5 GW | ~3.7 GW |
| 2026-09-30 | 52 | >1.7 GW | >4.6 GW (>1.3 GW outside the US) |
| 2026-12-31 guide | — | >1.85 GW | — |

- "Contracted power" is power CoreWeave has secured from data center providers. It is not capacity sold to customers.
- As of 2026-06-30 CoreWeave leased every operating data center. Its only ownership interest was a 35% stake in the Kenilworth, NJ joint venture, plus $1.7B committed to two unnamed development joint ventures [P].
- Leases signed but not yet started: $35.5B of future payments at 2026-06-30, starting 2026–2029, terms of 7–16 years [P].
- Not in contracted power: more than 1.5 GW of powered land, expansion options and letters of intent (as of 2026-08-11) [P].

### 2.2 Operational sites with a known MW figure

| Site | Landlord and structure | Contracted to CoreWeave | Live | Evidence |
|---|---|---|---|---|
| Denton, TX | Core Scientific, 12-year licence | ~260 MW | ~260 MW billing (2026-11-05) | [P] landlord |
| Dalton, GA (phase 1) | Core Scientific | ~175 MW total | ~75 MW billing | [P] landlord |
| Muskogee, OK | Core Scientific | ~70 MW | ~70 MW billing | [P] landlord |
| Marble, NC | Core Scientific | ~65 MW | ~65 MW billing | [P] landlord |
| Austin, TX | Core Scientific, 7-year term | ~20 MW | ~20 MW billing | [P] landlord |
| Ellendale, ND (buildings 1 and 2) | Applied Digital, ~15-year leases | 400 MW across three buildings | 250 MW ready for service (2026-10-01) | [P] landlord |
| Helios phase I, Dickens County, TX | Galaxy Digital, 15-year lease | 133 MW | 133 MW (delivered Q2 2026) | [P] landlord |
| Copenhagen (Ballerup), Denmark | atNorth | 22.5 MW | "majority" online (2026-10-27) | [P] CoreWeave |
| Chester, VA | Chirisa Technology Parks | ~28 MW | operational | [S] |
| Barcelona, Spain | Merlin Edged | 15 MW | opened May 2025 | [S] |
| Hillsboro, OR | Digital Realty / Flexential | 45 MW combined | n/d | [S] aggregator |
| Volo, IL | Chirisa (Bloom fuel cells on site) | 14 MW | n/d | [S] |
| Douglasville, GA | Flexential | 9 MW | n/d | [S] aggregator |

Operating with no public MW: Crawley and London Docklands (UK), Vennesla (Norway), Stockholm and Falun (Sweden), other Spanish sites, Cambridge (Ontario), Plano, Richardson and Round Rock (TX), Las Vegas, the New Jersey and Chicago regions, and roughly 20 more that are not named anywhere.

Landlord "billing" or "ready for service" runs one to two months ahead of CoreWeave's "active", because CoreWeave still has to install and test the GPUs.

### 2.3 Under construction or contracted, not yet active

| Site | Landlord and structure | MW | Schedule | Evidence |
|---|---|---|---|---|
| Dalton, GA phase 2 | Core Scientific | ~105 | early 2027; in commissioning Nov 2026 | [P] landlord |
| Ellendale, ND third building | Applied Digital | 150 | calendar 2027, "on schedule" | [P] landlord |
| Helios phase II, TX | Galaxy Digital | 260 | data halls from Q2 2027 | [P] landlord |
| Helios phase III, TX | Galaxy Digital | 133 | rent starts 2028 | [P] landlord |
| Kenilworth, NJ (NEST 11) | Joint venture, CoreWeave 35% | 40 first building; campus up to 250 | "2026" originally; early 2027 per press | [P] MW; [S] date |
| Lancaster, PA | Blue Owl / Chirisa / Machine developer JV | 100 initial | summer 2027 per press | [P] MW; [S] date |
| Greater Jakarta, Indonesia (three facilities) | n/d | 360 | 2028 | [P] CoreWeave |
| Navi Mumbai, India | AdaniConneX, sole tenant | 240 | first phase mid-2028 | [P] CoreWeave |
| Saskatchewan, Canada | Bell Canada | 140 | first phase H1 2027 | [S] |
| Cheyenne, WY | Related Digital | 88 | first building late 2026 | [S] |
| Niagara Falls, NY | Blockfusion, 15-year lease signed 2026-09-16 | 85 | n/d | [P] lease; [S] MW |
| Chesterfield County, VA (Digital Drive) | PowerHouse / Chirisa / Blue Owl | 76 or 200 (sources conflict) | late 2027 and mid-2028 | [S] |
| Elk Grove Village, IL | Prime Data Centers, 15-year lease | n/d | n/d | [S] |
| Cedar Creek, TX (building 1) | EdgeConneX | n/d (one source: up to 96) | building due summer 2026 | [S] |

### 2.4 Pipeline, options and cancellations

- Named expansion options: India +240 MW, Lancaster +200 MW, Kenilworth ~+210 MW, Niagara Falls ~+215 MW [S]. Together ~865 MW of the >1.5 GW the company cites.
- **Cancelled:** Poolside "Project Horizon", West Texas (250 MW anchor plus 500 MW option), reported collapsed 2026-04-02 [S].
- **Terminated:** the acquisition of Core Scientific (2025-10-30). The leases continue [P].

### 2.5 Main components (fleet level unless a site is named) [P]

| Layer | What is disclosed |
|---|---|
| Chips | NVIDIA only. Generations in service: Ampere, Hopper (H100, H200), Blackwell (B200, GB200, GB300), and Vera Rubin (first production workload 2026-09-30) |
| Servers | Dell is the only named supplier. Three unnamed suppliers were 23%, 20% and 17% of 2025 purchases |
| Cluster network | NVIDIA Quantum-2 and Quantum-X800 InfiniBand; Spectrum-X Ethernet; BlueField-3 DPUs (BlueField-4 with Vera Rubin) |
| Storage | Own object storage; dedicated VAST Data clusters; multi-year Solidigm SSD supply agreement (Aug 2026) |
| Memory | Not disclosed |
| Cooling | Closed-loop direct-to-chip liquid cooling on recent builds; ~130 kW racks |
| Power | Grid at most sites. Helios: Galaxy-owned 345 kV substation, up to 900 MW of transformer capacity. Kenilworth: ~$150M substation funded by CoreWeave. Volo, IL: on-site Bloom fuel cells [S] |

Per-site hardware that is public: Ellendale building 1 can hold more than 40,000 GB300 GPUs [P landlord]; Denton had more than 16,000 GPUs by January 2026 [S]; the UK sites launched with H200 [P]; Denmark runs Blackwell on Quantum-X800 [P].

### 2.6 Per-MW economics that are public

| Item | Figure | Evidence |
|---|---|---|
| What CoreWeave charges on new 4–5 year contracts | $20–25M per MW per year | [P] Q3 2026 call |
| What it charges on short-term (3–6 month) capacity | about $40M per MW per year | [P] Q3 2026 call |
| Rent at Helios phase I | $315M a year for 133 MW, about $2.4M per MW | [P] Galaxy |
| Rent at Helios phase II | $675M a year for 260 MW, about $2.6M per MW | [P] Galaxy |
| Rent at Ellendale | ~$11.0B over ~15 years for 400 MW, about $1.8M per MW per year (INFERRED) | [P] Applied Digital |
| Landlord build cost at Helios | $1.8B for 133 MW; $4.0B estimated for 260 MW | [P] Galaxy |
| CoreWeave's contribution to build-out at Core Scientific | up to $1.5M per MW, credited against fees | [P] Core Scientific |

Rent is roughly a tenth of what CoreWeave charges per MW on new contracts. The larger costs are the GPUs and the interest on the debt that buys them.

### 2.7 Delays found

| Site | Original | Actual | Evidence |
|---|---|---|---|
| Denton, TX | Core Scientific aimed for 250 MW billing fleet-wide by end-2025 | 120 MW billing at Q4 2025; full 260 MW by Q3 2026 | [P] landlord; cause (weather, ~60 days) is [S] |
| Ellendale building 2 | mid-2026 | half on 2026-07-01, half on 2026-10-01 | [P] / [S] for dates |
| Kenilworth | initial phase "delivered in 2026" | early 2027 | [P] original; [S] revised |
| Helios, as described in CoreWeave's filings | "in 2026" (Sep 2025) | "2026 and 2028" (Jun 2026); Galaxy says on schedule | [P]; the match of this lease to Helios is INFERRED |

The Denton delay is the one that reached the income statement: it caused the Q3 2025 guidance cut. Management said in February 2026 that the affected capacity had been delivered, and a loan covenant schedule was amended on 2025-12-31 to match the new delivery timing [P].

---

## 3. CoreWeave — backlog and contracts

### 3.1 What "backlog" is [P]

Backlog is remaining performance obligations (RPO, the accounting measure in the 10-Q) plus "other amounts we estimate will be recognized as revenue in future periods under committed customer contracts, in each case, subject to the satisfaction of delivery and availability of service requirements". It appears only in press releases and presentations. The 10-Q discloses RPO, and RPO is already reduced by management's estimate of service credits, "amounts that may not be recognized as revenue due to delivery delays", and capacity it has the right to resell. The size of that reduction is not disclosed.

### 3.2 History [P unless marked]

| Quarter-end | Backlog | RPO | Main driver |
|---|---|---|---|
| 2024-12-31 | $15.1B | $15.1B | — |
| 2025-03-31 | $25.9B | $14.7B | OpenAI $11.2B, not yet in RPO |
| 2025-06-30 | $30.1B | $30.1B | OpenAI +$4B; new hyperscaler |
| 2025-09-30 | $55.6B | $50.0B | Meta up to $14.2B; OpenAI up to $6.5B |
| 2025-12-31 | $66.8B | $60.7B | broad-based |
| 2026-03-31 | $99.4B | $98.8B | Meta ~$21B; Jane Street ~$6B; Anthropic |
| 2026-06-30 | $104.2B | $103.7B | — |
| 2026-09-30 | ~$132.5B | $132.3B [S] | >$25B of commitments signed early in Q3; customers not named |

Quarterly net increases ranged from $4.2B to $32.6B. Bookings are lumpy.

### 3.3 When it converts

| As of | Base | Within 24 months | Months 25–48 | Later | Evidence |
|---|---|---|---|---|---|
| 2025-03-31 | RPO $14.7B | 58% | 40% | 2% | [P] |
| 2025-12-31 | RPO $60.7B | 43% | 38% | 19% (to month 84) | [P] |
| 2026-06-30 | RPO $103.7B | 41% | 39% | 20% (to month 78) | [P] |
| 2026-09-30 | Backlog $132.5B | 36% (~$48B) | 38% (~$50B) | 26% (~$34B) | [S] |

- More than 50% of the Q3 backlog is attached to contracts where delivery starts by the end of 2026 [P].
- Revenue starts when GPUs are deployed, tested and handed over, then runs straight-line over the contract. Fit-out takes one to two months after the landlord hands over a powered shell [P].
- Guidance: 2026 revenue $13.0–13.3B; run-rate revenue of $20–21B leaving 2026; more than $30B leaving 2027, of which more than 75% was already contracted as of May 2026 [P].
- Delivering only the committed backlog would keep 2027 capital spending "in line with" 2026's $37–39B [P].
- No 12-month bucket and no weighted-average remaining term are disclosed.

### 3.4 Contract ledger

| Customer | Value | Runs to | Evidence |
|---|---|---|---|
| OpenAI (three orders) | up to ~$22.4B ($11.9B + $4B + $6.5B) | Oct 2030 to May 2031 | [P] |
| Meta (Sept 2025 order) | up to ~$14.2B | Dec 2031 | [P] |
| Meta (March 2026 order) | ~$21B, including exercise of an earlier option | Dec 2032 | [P] |
| NVIDIA | $6.3B initial value; NVIDIA must buy residual unsold capacity | Apr 2032 | [P] |
| Jane Street | ~$6B | n/d | [P] |
| Microsoft | not disclosed (press: >$10B through 2030) | n/d | [S] for value |
| Anthropic, Google, Cohere, Mistral, IBM, Poolside | not disclosed | n/d | [P] that they exist |
| Unnamed, signed early Q3 2026 | >$25B | n/d | [P] |

Concentration [P]: the top customer was 67% of 2025 revenue (Microsoft) and 36% of Q2 2026 revenue; the top three were 36%, 26% and 10% in Q2 2026. Non-investment-grade AI companies were under 30% of backlog in May 2026. Financial-services customers were about 10% of backlog in November 2026.

Which site serves which contract is public in only three cases: Denton for OpenAI [S], Helios phase I for an unnamed investment-grade hyperscaler [P landlord], Cambridge (Ontario) for Cohere [S].

### 3.5 Can the contracts be pulled?

Partly. Five master agreements are filed with the SEC in redacted form, and plain-text copies are in `sources/contracts/`: Microsoft (2023), OpenAI (March 2025 and May 2025), Meta (2023), NVIDIA (2023).

Not filed anywhere:

- **Every order form.** These hold the price, capacity, chip type, delivery dates, any long-stop date, late-delivery remedies, prepayments, options and site.
- **Every service-level exhibit** and credit schedule.
- **Any agreement** with Jane Street, Anthropic, Google, Cohere, or the customers behind the >$25B signed in Q3 2026.
- No customer contract has been filed as a material agreement in 2026.

### 3.6 Conditions that end or shrink a contract [P, from the filed text]

- **No termination for convenience** in any filed agreement. Committed contracts are take-or-pay: 98% of revenue.
- **Customers pay only for delivered service.** Microsoft: "in no event will Customer pay any fees ... for any Services that Customer does not receive". Undelivered capacity produces no revenue and no claim on the customer.
- **Uncured material breach.** Microsoft: 45 days. OpenAI, Meta, NVIDIA: cure period redacted (NVIDIA 30 days per the 8-K).
- **Insolvency of either party.** For OpenAI, CoreWeave's insolvency also lets OpenAI require the order and the data center agreement to be assigned to a substitute operator of its choosing.
- **Repeated availability failures.** OpenAI may "terminate all or a portion of the committed amount" (10-Q description; the clause itself is redacted or in the unfiled exhibit).
- **Prolonged force majeure.** OpenAI: 30 consecutive days, with "government actions or restrictions" inside the definition. Microsoft: payment for affected service is cancelled after two business days, and the definition includes "regional shortage of adequate power". Meta: period redacted.
- **Change of control.** Microsoft "reserves the right to terminate in the event of CoreWeave acquisition". Microsoft and Meta may terminate if CoreWeave is acquired by their direct competitor.
- **Prepaid fees are refundable** if the customer terminates for cause.
- **Delivery deadlines and late-delivery remedies are in the unfiled order forms.** This is the largest gap in what can be verified.

Whether a state construction moratorium would count as force majeure under these contracts is a legal question the public text does not settle.

### 3.7 Reductions so far

None disclosed. No customer cancellation, capacity reduction or backlog write-down appears in any document read. The record is one timing slip (late 2025, Denton), where management said the customer agreed to move dates and the revenue was deferred, not lost. A March 2025 press report that Microsoft withdrew from some agreements over missed deadlines is [S] and predates the IPO.

---

## 4. Nebius — facilities

### 4.1 Fleet totals [P]

| Report | Contracted | Connected | Active | Year-end 2026 target at that date |
|---|---|---|---|---|
| Q4 2025 (Feb 2026) | >2 GW | n/d | ~170 MW at 2025-12-31 | >3 GW contracted; 800 MW–1 GW connected |
| Q1 2026 (May 2026) | >3.5 GW, more than 75% owned | n/d | n/d | >4 GW contracted |
| Q2 2026 (Aug 2026) | n/d | n/d | n/d | 5 GW contracted; 800 MW–1 GW connected, becoming active "throughout the first half of 2027" |

Nebius has published no actual connected-power figure since 25 MW at end-2024 and no actual active-power figure since ~170 MW at end-2025. Everything since is a target. It plans to deploy more than 1 GW a year from 2027.

### 4.2 Operational sites

| Site | Model | MW | Notes | Evidence |
|---|---|---|---|---|
| Mäntsälä, Finland | Owned | 75 | Expansion finished early 2026, a few months late. Free-air cooling, heat reuse | [P] |
| Vineland, NJ phase 1 | Built for Nebius, owned and operated by DataOne | site up to 300; delivered MW n/d | Serves Microsoft only. First capacity Nov 2025 against "summer 2025" | [P] |
| Kansas City, MO | Colocation (Patmos) | 5, expandable to 40 | Online April 2025 | [P] |
| Keflavik, Iceland | Colocation (Verne) | 10 | Online March 2025 | [P] |
| Longcross, UK | Colocation (Ark) | 16 or 19 | Launched Nov 2025; Blackwell Ultra on Quantum-X800 | [P] launch; [S] MW |
| Modi'in, Israel | Colocation | 8 | Launched Oct 2025; 4,000 B200 | [P] launch; [S] MW |
| Paris, France | Colocation (Equinix) | n/d | Since Nov 2024; H200 | [P] |

### 4.3 Under construction or contracted

| Site | Model | MW | Schedule | Evidence |
|---|---|---|---|---|
| Vineland, NJ remainder | DataOne | to 300 | Management (Aug 2026): part of 2026 connected power. Nebius site page: "expected to be operational by 2027" | [P] both |
| Independence, MO | Owned, ~400 acres | up to 1,200 (800 from the city utility, 400 on-site generation) | Ground broken May 2026; first building 2027; four buildings over five to seven years | [P] |
| Birmingham, AL | Owned | ~300 per press; Nebius gives none | Energization Q4 2026; operational 2027; build-out through 2028 | [P] dates; [S] MW |
| Lappeenranta, Finland | "Owned" per Nebius; developer Polarnode says it owns the campus | up to 310 | First capacity 2027 | [P]; ownership conflict [S] |
| Béthune, France | Colocation-type (Azur builds) | 240 at full build | First capacity autumn 2026 per press | [P] MW; [S] dates |
| Mäntsälä 2, Finland | Owned | up to 70 | From 2027 | [S] |
| Israel (two sites) | Colocation (Mega Or) | 80 | From Q3 2026 to Q1 2027 | [S] |
| UK (three more sites) | Colocation | 65 when fully ramped | Through 2027 | [P] |
| Southeastern US | Lease (AIB Data Centers) | 50 | Two halls by Q4 2027 | [S] |
| Spain, Estonia | Colocation | 18 and 22 | n/d | [S] |
| Minnesota, Oklahoma, second French site | Colocation | n/d | n/d | [P] that they exist |

### 4.4 Pipeline

- **Schuylkill County, PA:** owned, 1.2 GW. 260 MW by October 2027, 660 MW by January 2029, 1,000+ MW by November 2029 [P]. Local land-development approval still pending [S].
- **New Jersey expansion option:** "hundreds of megawatts" [P].
- **Rotterdam and NEOM (Saudi Arabia):** letter-of-intent stage [S].

### 4.5 Main components (fleet level) [P]

| Layer | What is disclosed |
|---|---|
| Chips | NVIDIA: H100, H200, B200, B300, GB200, GB300; first Vera Rubin systems received, deployment late 2026 or early 2027 |
| Servers and racks | Designed in-house; contract manufacturers not named |
| Cluster network | NVIDIA InfiniBand (Quantum-2 and Quantum-X800 generations). No Spectrum-X deployment found |
| Storage | In-house object, file and block storage plus third parties; WEKA named |
| Memory | Not disclosed |
| Cooling | Free-air at Mäntsälä; closed-loop liquid for newer chips |
| Power | Vineland runs on on-site Bloom fuel cells (328 MW installed capacity planned), having switched from gas engines in May 2026. Independence: city utility plus on-site generation. Pennsylvania: PPL Electric |

### 4.6 Delays found

- **Vineland** is the one that matters. First capacity slipped from summer 2025 to November 2025. The power design was changed in May 2026. Press reports describe two city stop-work orders (2026-08-06 and 08-10), approval of the revised plan on 2026-08-17, and a state environmental fine in late September [S for all four]. Vineland is roughly a third of the 2026 connected-power target and the only site serving the Microsoft contract.
- **Mäntsälä expansion:** end-2025 became early 2026 [P].
- **Revenue timing:** capacity connected in late 2026 becomes revenue-generating through the first half of 2027 [P].

---

## 5. Nebius — backlog and contracts

### 5.1 What is disclosed [P]

Nebius has no defined "backlog". It reports RPO (since FY2025) and annualized run-rate revenue (last month times twelve).

| Quarter-end | Revenue | Run-rate revenue | RPO | Customer prepayments held |
|---|---|---|---|---|
| 2025-12-31 | $227.7M | $1.25B | $21.3B | $1.6B |
| 2026-03-31 | $399M | $1.9B | $33.6B | $4.8B |
| 2026-06-30 | $582.3M | $3.0B | $37.5B | $6.0B |

- RPO at 2026-06-30: 36% (~$13.5B) within 24 months, 40% (~$15.0B) in months 25–48, 24% (~$9.0B) later.
- RPO excludes contracts of one year or less, so on-demand use and 3–6 month deals never appear in it.
- Management cites "more than $40 billion of customer commitments". That is above total RPO and is not reconciled to it; the gap is most plausibly the Meta backstop below (INFERRED).
- 2026 guidance: revenue $3.0–3.4B; run-rate revenue $7–9B at year-end; capital spending $20–25B.

### 5.2 Contract ledger [P]

| Customer | Value | Term | Delivery | Site |
|---|---|---|---|---|
| Microsoft | $17.4B, up to ~$19.4B; ~$7.0B of it as upfront payments, tranche by tranche | billed through Oct 2031 | nine tranches in 2025–2026 plus two added Jan 2026; all tranches due by 2026-08-12 delivered | Vineland, NJ only |
| Meta (Nov 2025) | ~$2.9B | five years | two tranches, both delivered by Feb 2026 | n/d |
| Meta (Mar 2026) | $12B firm, plus up to $15B backstop | five years per order | tranches through H1 2027 | "multiple locations", n/d |
| Reflection, Cohere, two unnamed | average above $1B each | one to three years | capacity arriving late 2026 | n/d |

- The $15B Meta backstop is a floor, not extra revenue. Meta must buy capacity in certain clusters only where Nebius has not sold it to others.
- At end-2025 Microsoft and the first Meta contract were about 95% of RPO (INFERRED).
- The top three customers were 59% of Q2 2026 revenue; none is named.

### 5.3 Can the contracts be pulled?

More fully than CoreWeave's. Filed with the annual report, and saved in `sources/contracts/`: the Microsoft statement of work and its addendum, and both Meta agreements. Redacted: delivery dates, tranche sizes and values, prices, the grace period, the damages rate. Not filed: any Meta order, the service-level exhibits, the four large AI-cloud contracts, the Vineland lease, the Bloom agreement.

### 5.4 Conditions that end or shrink a contract [P]

Microsoft:

- **Take-or-pay, no termination for convenience.** Microsoft pays for each accepted tranche for its full term "irrespective of the actual usage".
- **Late delivery is handled tranche by tranche.** A tranche not accepted on time earns Microsoft daily liquidated damages. After a grace period (length redacted), if Nebius cannot supply equivalent capacity, Microsoft may terminate that tranche or agree a new date. Missing the new date is a deemed termination. A terminated tranche's upfront payment is refunded and Microsoft "will have no obligation to pay for that GPU Service".
- **Tranches are sequential.** A tranche cannot be delivered until earlier ones are merged into the production cluster, so one slip can hold up the next.
- **Substitute capacity** counts only if Microsoft, in its sole reasonable discretion, accepts it. The contract is tied to one data center location.
- **Uncured material breach** (60 days) or **insolvency**.
- **Change of control** of Nebius to Amazon or Google.
- **Availability failures:** service credits, and termination of individual tranches for repeated failure.
- The January 2026 addendum set a special uptime level and credit for the first tranche; the figures are redacted and the reason is not given.

Meta:

- Take-or-pay. A material breach on one tranche allows termination of that tranche only.
- The first contract's delivery-delay termination right is spent, since both tranches are delivered.
- For the March 2026 contract only "discounted monthly fees for late delivery" and customary termination are disclosed; the delivery-delay wording is not public.
- Meta may terminate immediately for an incurable trade-controls breach.

### 5.5 Reductions so far

None disclosed. No tranche termination, capacity reduction or missed contractual date appears in any filing. Open as of today: whether the Microsoft tranches due in the second half of 2026 are on time. Press reports that Microsoft cut its 2026 capital spending outlook in late October citing third-party capacity delays, without naming a supplier [S].

---

## 6. Roadmap by year

MW are from named sites only, so they understate both companies' plans.

**CoreWeave**

| Period | Active power | Named capacity due | Revenue markers |
|---|---|---|---|
| End-2025 | >850 MW | — | 2025 revenue $5.1B |
| 2026-09-30 | >1.7 GW | — | Q3 revenue $3.66B |
| End-2026 | >1.85 GW (guide) | Ellendale's last 75 MW in fit-out | 2026 revenue $13.0–13.3B; run-rate $20–21B |
| 2027 | management: "substantial majority" of the 3.5 GW contracted at Q1 2026 | Dalton ~105, Ellendale 150, Helios II 260, Kenilworth 40, Lancaster 100, Saskatchewan 140, Cheyenne 88 — about 880 MW named | run-rate above $30B leaving 2027 |
| 2028 | — | Helios III 133, Indonesia 360, India 240 — about 730 MW named | — |
| To 2032 | target of more than 8 GW by 2030 | — | last disclosed contract end: Dec 2032 |

About $48B of backlog is scheduled for the 24 months to September 2028, about $50B for the following 24 months, and about $34B after that [S for the split].

**Nebius**

| Period | Power | Named capacity due | Revenue markers |
|---|---|---|---|
| End-2025 | ~170 MW active | — | 2025 revenue $530M |
| End-2026 | 800 MW–1 GW connected (target) | Vineland to 300, Béthune part, Israel 80, smaller colocations | 2026 revenue $3.0–3.4B; run-rate $7–9B |
| 2027 | more than 1 GW a year deployed | Independence first building (~200), Birmingham, Lappeenranta first phase, Mäntsälä 2 (70), Pennsylvania 260 by October | Meta $12B starts early 2027 |
| 2028–2030 | "almost all" of 5 GW online within 3 to 3.5 years of Aug 2026 | Independence to 1,200; Pennsylvania 660 by Jan 2029 and 1,000+ by Nov 2029 | Microsoft billed through Oct 2031 |

About $13.5B of RPO is scheduled by mid-2028, about $15.0B for the following 24 months, and about $9.0B after that.

---

## 7. Should backlog be assumed to grow, be replaced, or shrink?

All three happen at once. The parts behave differently.

1. **It shrinks every quarter by the revenue recognized.** For CoreWeave that is about $3.7B in Q3 2026, rising to roughly $5B a quarter at the end of 2026 and $7.5B a quarter at the end of 2027 on management's run-rate targets (INFERRED). New signings below that pace mean a falling backlog.
2. **It grows only with new signed commitments, and those are lumpy.** CoreWeave has grown backlog every quarter since its IPO, by $4.2B to $32.6B a quarter. Nebius has signed no new hyperscaler contract since March 2026.
3. **Both companies are deliberately signing shorter contracts** to capture higher prices: CoreWeave's short-term capacity and managed inference, Nebius's one-to-three-year and 3–6 month deals. Shorter contracts add less backlog per dollar of yearly revenue, so backlog can flatten while revenue grows. For Nebius the shortest deals never enter RPO.
4. **Older contracts roll off and must be replaced.** At CoreWeave more than 130,000 GPUs come off contract in 2027 and about 170,000 in 2028. Management values re-renting them at nearly $10B of yearly revenue at today's prices, but that is not contracted and sits outside backlog.
5. **Real reductions have a short list of triggers,** and none has been disclosed as triggered: late delivery beyond a grace period, repeated availability failures, prolonged force majeure, insolvency, change of control. Because customers pay only for delivered capacity, a delay first shows up as revenue arriving later.
6. **The two companies carry this risk differently.** Nebius's largest contract is tied to one site (Vineland) with tranche-by-tranche termination rights that are public. CoreWeave's is spread over many sites and landlords, but its delivery terms are not public.

---

## 8. Things outside the contracts that bear on delivery

Press-based unless marked; verify before relying on them.

- **Texas.** On 2026-08-03 the governor ordered an audit of data centers awaiting grid connection, and the grid operator paused approvals to energize large loads. The governor-elect campaigned on a statewide moratorium. CoreWeave's CEO wrote to her on 2026-11-07 naming its Texas sites: Austin, Denton, Dickens County, Plano, Richardson, Round Rock. Named Texas capacity is about 806 MW contracted and 413 MW live (INFERRED), with 393 MW at Helios still to come in 2027–2028. Galaxy said on 2026-10-27 that "certain additional approvals remain outstanding" but that it expects no effect on timing [P]. CoreWeave says the "overwhelming majority" of its Texas power is online or fully permitted and under construction, without giving a figure [P].
- **Other states.** After the November 2026 elections, governors-elect in Georgia, Ohio, Michigan and New Mexico had campaigned on pausing or restricting data centers, and 40 of 41 local ballot measures favored limits. New York announced a moratorium on new data centers of 50 MW or more in July 2026 [P, CoreWeave 10-Q]. Sites in affected states include Dalton, GA (CoreWeave, ~105 MW still to deliver) and Niagara Falls, NY (CoreWeave, lease signed September 2026).
- **New Jersey.** The Vineland permitting events in section 4.6.
- **Credit markets.** Neocloud shares and bonds fell sharply in October 2026. CoreWeave said on 2026-11-10 it will not issue unsecured debt at current yields [P]. Nebius took a $3.5B, 364-day bridge loan in October 2026 [P].

---

## 9. Open items

1. **Nebius Q3 2026 report (2026-11-12):** updated RPO, any actual connected-power figure, status of the remaining Microsoft tranches, 2027 guidance.
2. **CoreWeave Q3 2026 10-Q:** RPO schedule, customer concentration, lease and undelivered-MW notes. The Q3 investor presentation was not readable from here, so the $132.3B RPO and the 36/38/26 split rest on press summaries.
3. **Who signed CoreWeave's >$25B in early Q3 2026,** and on what terms.
4. **CoreWeave's unnamed ~1.7 GW:** about 35 operating sites and roughly 1 GW of contracted capacity with no public MW. Local permits, utility filings and landlord bond documents are the next sources.
5. **Texas exposure in MW** for Plano, Richardson, Round Rock and Cedar Creek.
6. **Press items to verify at source:** Vineland stop-work orders and fine; Microsoft's October capital-spending comment; the Poolside cancellation; the Microsoft withdrawal report of March 2025.
7. **Debt:** deferred to the next step. Links already noted: CoreWeave's loan covenant amendment after the Denton delay; Nebius's $775M facility secured on one investment-grade contract's cash flows.
