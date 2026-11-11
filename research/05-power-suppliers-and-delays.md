# CoreWeave and Nebius — power suppliers, delay base rates, supplier map

Compiled 2026-11-11. Finished under a reduced search budget (about 14 searches after a restart), so coverage is uneven; section 6 lists what was not sourced.

Evidence marks: **[P]** primary document read this session (local copies of SEC filings, company site pages, Motley Fool transcripts). **[S]** search-result summary only, page not opened. **INFERRED** my arithmetic, matching, or stable background knowledge (utility territories, corporate parents, tickers) not confirmed this session. Tiers: T1 company; T2 counterparty; T3 press; T4 blogs, trackers.

**All tickers and parent companies in this file are INFERRED from background knowledge unless marked otherwise. Verify before trading on them.**

---

## 1. Power by site

### 1.1 CoreWeave

| Site (MW to CoreWeave) | Utility / supplier (parent, ticker) | Grid / market | On-site or behind-the-meter | Interconnect size disclosed | Site-specific power risk | Evidence |
|---|---|---|---|---|---|---|
| Helios, Dickens County TX (526: 133 live, 260 from Q2 2027, 133 in 2028) | Landlord Galaxy ($GLXY) owns a 345 kV substation; ties into Pitchfork and Cottonwood 345 kV substations owned by Wind Energy Transmission Texas (WETT; private, infrastructure-fund owned, INFERRED). Retail supplier not disclosed | ERCOT | None disclosed | Up to 900 MW transformer capacity; 800 MW gross leased; 1,630 MW approved campus-wide | Galaxy 2026-10-27: "certain additional approvals remain outstanding following governor Abbott's September directive"; expects no timing impact. Helios I and II are "previously approved baseload" in Batch Zero, "largely unaffected". Audit results expected December 2026 | [P] T2 Galaxy deck and call |
| Ellendale ND (400: 250 ready) | Not named in Applied Digital's 10-K. Montana-Dakota Utilities ($MDU MDU Resources) per earlier file; not confirmed this session | MISO (INFERRED) | Backup generation: Caterpillar ($CAT); electrical: ABB (SIX: ABBN); cooling: BASX (owned by $AAON, INFERRED) — Applied Digital's standard vendors | Not disclosed | None found. Stranded-wind area; curtailment terms not disclosed | Vendors [P] T2 APLD 10-K; utility INFERRED |
| Denton TX (~260) | Denton Municipal Electric (city-owned, no ticker) | ERCOT | None disclosed | ~390 MW gross; site "to roughly double" city demand, uses "majority of extra system capacity"; costs passed to operator | Fully billing, so the ERCOT energisation pause does not apply to existing load. Texas large-load curtailment rules in grid emergencies (Core Scientific risk factor [P]) | [S] T3 Bloomberg Jul 2025; [P] T2 risk factor |
| Dalton GA (~175: 75 live, ~100 early 2027) | Dalton Utilities (municipal; no ticker) INFERRED, not confirmed | Southeast, non-RTO (Southern balancing area) INFERRED | None disclosed | Not disclosed | Phase 2 in commissioning. Georgia governor-elect's position not confirmed this session | INFERRED |
| Muskogee OK (~70) | OG&E ($OGE OGE Energy) | SPP | Core Scientific considering a behind-the-meter building for a later (AMD) phase, not CoreWeave's | Not disclosed; more capacity "working its way through load study" | None for the live 70 MW | [P] T2 CORZ Q3 call |
| Marble NC (~65) | Not disclosed. Likely Murphy Electric Power Board, a TVA distributor (INFERRED; Duke is the alternative) | TVA or Duke Carolinas (INFERRED) | None | Not disclosed | None found | INFERRED |
| Austin TX (~20) | Austin Energy (city-owned) INFERRED | ERCOT | None | Not disclosed | Small; live | INFERRED |
| Plano / Richardson / Round Rock TX (unsized) | Plano: one tracker lists Grayson-Collin Electric Cooperative for a 13.75 MW site [S] T4; otherwise Oncor wires (Sempra $SRE majority, INFERRED). Richardson: Oncor INFERRED. Round Rock: Oncor INFERRED | ERCOT | None | n/d | Live sites | [S] T4 / INFERRED |
| Cedar Creek TX (unsized, up to 96) | Bluebonnet Electric Cooperative / LCRA transmission INFERRED | ERCOT | n/d | n/d | Not on CoreWeave's Nov 2026 list of active Texas sites; if not yet energised and ≥75 MW it falls inside the ERCOT pause (INFERRED) | INFERRED |
| Kenilworth NJ (40; campus 250) | PSE&G ($PEG Public Service Enterprise Group) | PJM | None; "100% clean energy" claim | 40 MW planned load; CoreWeave funds ~$150M substation | Residents' petition (Apr 2026) [S]; PJM capacity tightness | [P] T1 coreweave.com |
| Lancaster PA (100; option to 300) | PPL Electric Utilities ($PPL PPL Corp) — new substation and switchyard [S] | PJM | One search summary mentions planned on-site generation, unverified | n/d | Resident appeal of phase 2 [S]; proposed 3-year Pennsylvania pause bill (Sen. Muth) is a proposal only [S] | [S] T3 |
| Chester / Digital Drive, Chesterfield VA (28 live; 76–200 planned) | Dominion Energy Virginia ($D) INFERRED | PJM | n/d | n/d | Dominion zone has the longest reported waits in the US (JLL: Northern Virginia about seven years [S]); not site-specific | INFERRED |
| Elk Grove Village IL | ComEd ($EXC Exelon) INFERRED | PJM | n/d | n/d | n/d | INFERRED |
| Volo IL (14) | Bloom Energy ($BE) solid-oxide fuel cells, on-site primary power; gas from the local distributor (Nicor Gas, Southern Co $SO, INFERRED) | Behind the meter; ComEd backup INFERRED | Bloom; landlord Chirisa | 14 MW | Commissioning was due Q3 2025; actual date not found | [S] T2 Bloom release, T3 |
| Hammond IN, Digital Crossroads (180) — **new, not in the facility file** | NIPSCO ($NI NiSource) | MISO | n/d | 180 MW; "contingent upon" a NIPSCO power agreement; no grid draw until 2027 | Power agreement not final | [S] T3 DCD |
| Cheyenne WY (88) | Black Hills Energy ($BKH Black Hills Corp), large-load tariff | WECC, non-RTO | n/d | n/d | First building was due late 2026; status not found | [S] from earlier file |
| Niagara Falls NY (85; option to 300) | Not confirmed. NYPA hydro allocation is the lead; lease text says "hydroelectric and nuclear" | NYISO | None | Expansion conditional on Blockfusion "securing firm power" | New York Executive Order 62, in force 2026-07-14: one-year pause on discretionary environmental permits for data centers of 50 MW or more. A retrofit needing no new discretionary permit may be outside it; not confirmed | [P] T2 lease; [S] T3 moratorium |
| Saskatchewan (140) | SaskPower (provincial Crown utility, no ticker) | Saskatchewan, non-market | n/d | Campus 300 MW | n/d | [S] |
| Hillsboro OR (45) | Portland General Electric ($POR) INFERRED | Non-RTO | n/d | n/d | n/d | INFERRED |
| Las Vegas NV (Switch) | NV Energy (Berkshire Hathaway $BRK.B) or Switch's own supply arrangements INFERRED | Non-RTO | n/d | n/d | n/d | INFERRED |
| Douglasville GA (9) | Georgia Power ($SO) or GreyStone EMC INFERRED | Southeast | n/d | n/d | n/d | INFERRED |
| Navi Mumbai, India (240) | Landlord AdaniConneX; supply not disclosed. Adani group utilities or MSEDCL (INFERRED) | India western grid | n/d | Three 80 MW buildings | n/d | [P] T1 for MW only |
| Greater Jakarta, Indonesia (360) | PLN (state utility) INFERRED; developer not named | Java-Bali grid | n/d | n/d | n/d | INFERRED |
| Denmark, Sweden, Norway, UK, Spain | Renewable PPAs via landlords (atNorth, Conapto, EcoDataCenter, Bulk, Digital Realty, Global Switch, Merlin Edged); suppliers not named | Nord Pool / GB / Iberian markets | None | n/d | n/d | [P] T1 "renewable" only |

### 1.2 Nebius

| Site (MW) | Utility / supplier (parent, ticker) | Grid / market | On-site or behind-the-meter | Interconnect / agreement | Site-specific power risk | Evidence |
|---|---|---|---|---|---|---|
| Independence MO (1,200) | Independence Power & Light (city-owned). The 800 MW "will come from a new, privately financed facility developed by Independence Power Partners LP" at the retired Blue Valley plant | SPP | 400 MW on-site generation, still "evaluating"; two backup generators per building | 800 MW IPL + 400 MW on-site. "IPL to deliver initial power in the second half of 2026 and launch a study to provide additional power by early 2029" | Bulk of the 800 MW depends on a new gas plant whose turbine supplier and schedule were not found; gas-turbine slots are the longest-lead item in the industry (section 3) | [P] T1 nebius.com/independencemo |
| Schuylkill County PA (1,200) | PPL Electric Utilities ($PPL) — "dedicated Energy Service Agreement", new infrastructure paid by Nebius | PJM | Battery storage, ~30 minutes backup | 260 MW Oct 2027; 660 MW Jan 2029; 1,000+ MW Nov 2029 | Township land-development approval pending [S]; PJM zone waits of 36–48 months typical [S]; proposed state pause bill | [P] T1 |
| Vineland NJ (300; Bloom 328 installed) | Bloom Energy ($BE) fuel cells on natural gas with a 1.5M-gallon on-site LNG tank [S]; LNG supplier not found. City utility: Vineland Municipal Electric Utility (INFERRED; role not confirmed). Landlord DataOne | Behind the meter; PJM (Atlantic City Electric zone, $EXC, INFERRED) | Bloom replaced reciprocating gas engines (May 2026) | 328 MW installed [P] | Two city stop-construction orders (Aug 6 LNG tank; Aug 10 fuel cells); plan approved 8-1 on Aug 17; NJDEP fined DataOne $1.07M over 62 unpermitted gas generators (Sept); NJDEP said in Aug it had issued no permits for power generators there. **No source found that the orders were lifted or the permits granted** | [P] T1 Bloom release; [S] T3 |
| Lappeenranta, Finland (310) | Not disclosed. Local grid Lappeenrannan Energia; transmission Fingrid (state-owned) INFERRED | Nord Pool FI | None disclosed | n/d | n/d | INFERRED |
| Birmingham AL (~300) | Alabama Power ($SO Southern Company); Nebius funds a new switching station and substation | Southeast, non-RTO | None disclosed | MW not disclosed by Nebius | Neighbours' lawsuit; construction continued [S]. Energisation was planned Q4 2026 | [P] T1 nebius.com/birminghamal |
| Béthune, France (240) | Not disclosed. Grid RTE (EDF, state-owned) INFERRED | French market | Up to 110 MW interim gas generation [S] | ~45 MW grid initially; full 240 MW link ~3 years away [S] | Grid link is the constraint | [S] T3 from earlier file |
| Mäntsälä 1 and 2, Finland (75 + 70) | Not disclosed. Local grid Nivos (municipal) INFERRED; Fingrid | Nord Pool FI | None | 70 MW substation by Caverion, autumn 2027 [S] | n/d | INFERRED / [S] |
| Israel (8 + 80) | Israel Electric Corp (state-owned) INFERRED | Israel | n/d | n/d | n/d | INFERRED |
| UK: Longcross, Harlow, Newport (65–84) | Landlord-procured (Ark, Kao, Vantage); Ark cites "on-site power generation" | GB market | Ark on-site generation | n/d | n/d | [P] T1 partial |
| Southeastern US, AIB (50) | Not named; 65 MW 15-year electric service agreement | Likely Duke Energy ($DUK) INFERRED | n/d | 65 MW | n/d | [S] T2 |
| Kansas City MO (5–40) | Evergy ($EVRG) INFERRED | SPP | n/d | n/d | n/d | INFERRED |
| Keflavik, Iceland (10) | Verne's suppliers: Landsvirkjun (state) / HS Orka (private) INFERRED | Iceland | None | 10 MW | n/d | INFERRED |
| Paris, Estonia, Spain, Minnesota, Oklahoma | Landlord-procured; not disclosed | — | — | — | — | — |

### 1.3 What the power picture says

- Only two of the roughly 45 sites run mainly on on-site generation: Vineland (Bloom, 328 MW) and Volo (Bloom, 14 MW). A third is planned at Independence (400 MW, undecided technology). Béthune uses interim gas [S].
- Four of the five largest future blocks depend on something not yet built or approved: Independence (a new 800 MW private gas plant), Schuylkill (new PPL infrastructure, local approval pending), Vineland (permits), Helios II and III (outstanding Texas approvals, though classified as approved baseload).
- Municipal utilities serve a large share: Denton, Dalton (INFERRED), Independence, possibly Vineland. They have no ticker and little public disclosure.

---

## 2. Delay sample from the two facility files

Slip is measured against the first published date. "0" means within about two weeks.

| # | Site | Original | Actual / revised | Slip (months) | Stated cause | Evidence |
|---|---|---|---|---|---|---|
| 1 | Denton TX (Core Scientific 250 MW billing fleet-wide) | end-2025 | 120 MW at Q4 2025; 225 at Q1 2026; 395 at Q2 2026 | ~4–5 (INFERRED from billing curve) | Weather stopped concrete pours ~60 days (WSJ [S]); disputed | [P] / [S] |
| 2 | Ellendale building 1 (100 MW) | Q4 2025 | Oct–Nov 2025 | 0 | — | [P] |
| 3 | Ellendale building 2, first 75 MW | mid-2026 | 2026-07-01 | 0 | — | [P] / [S] |
| 4 | Ellendale building 2, second 75 MW | mid-2026 | 2026-10-01 | 3 | Phased handover; no cause given | [P] / [S] |
| 5 | Helios phase I (133 MW) | H1 2026 | Q2 2026 | 0 | — | [P] |
| 6 | Muskogee (70 MW) | mid-2026 | billing by Q3 2026 | 0–2 (use 1) | n/d | [S] / [P] |
| 7 | Vineland first capacity | late summer 2025 | November 2025 | 2–3 (use 2.5) | n/d | [P] |
| 8 | Mäntsälä expansion | end-2025 | early 2026 (by March) | 1–3 (use 2) | n/d | [P] |
| 9 | Kansas City phase 1 | Q1 2025 | April 2025 | ~1 | n/d | [P] |
| 10 | Kansas City phase 2 | end Q2 2025 | early July 2025 | 0 | — | [P] |
| 11 | Keflavik | end Q1 2025 | March 2025 | 0 | — | [P] |
| 12 | Longcross UK | Q4 2025 | 2025-11-06 | 0 | — | [P] |
| 13 | Béthune first capacity | late summer 2026 | mid-October 2026 | ~1.5 | n/d | [S] T4 |
| Open A | Kenilworth NEST 11 | "2026" | early 2027 | ≥2 | n/d | [P] / [S] |
| Open B | Cedar Creek building 1 | summer 2026 | not active in Nov 2026 | ≥4 | n/d (ERCOT pause possible, INFERRED) | [S] |
| Open C | Vineland remainder | 2026 | "operational by 2027" on Nebius's page | ≥1, unresolved | Power redesign, stop orders, permits | [P] / [S] |
| Forecast only | Ellendale 3, Helios II and III, Dalton 2, Lancaster, Schuylkill, Independence, Birmingham | — | all still described as on schedule | not scored | — | [P] |
| Cancelled | Poolside West Texas (250 MW + 500 option); Nebius Andalusia | — | — | cancelled | Deal collapse | [S] |

**Statistics, 13 completed cases (INFERRED):**

- On time: 6 of 13 (46%).
- 1–3 months late: 6 of 13 (46%).
- 3–6 months late: 1 of 13 (8%), Denton.
- More than 6 months: none.
- Median slip 1 month; mean about 1.2 months; worst about 4.5 months.
- Adding the three open cases at their lower bounds: on time 6 of 16 (38%), median still about 1 month, worst still unknown.

**Limits of this sample:**

- It is small and survivor-biased. It contains only sites that were announced late in development and then finished. Sites that died earlier (Poolside, Andalusia) never got a date pair.
- Weighted by MW the picture is worse. The two largest completed blocks (Denton, Ellendale 2) both slipped; the on-time cases are mostly 5–20 MW colocations.
- All 13 were delivered before the August 2026 Texas pause and the November elections.
- Landlord "ready" dates precede CoreWeave revenue by one to two months [P].

---

## 3. Industry evidence, 2025–2026

**Share of capacity delayed**

- Sightline Climate (now Currence), Feb 2026: 30–50% of capacity slated for 2026 expected to slip. Tracker: ~16 GW across ~140 projects due in 2026, only ~5 GW under construction. Causes: electrical equipment and securing power. Nine explicit US cancellations in the 2026 tracker versus none in 2024. Smaller and newer developers slip most. Sources disagree on whether the scope is US or global. [S] T3 (Axios, TechSpot)
- A syndicated October 2026 piece repeats "nearly half of all planned projects delayed or canceled". [S] T3

**Interconnection waits** (all [S], mostly consultants and blogs; treat as approximate)

- PJM: about 40 months average; 36–48 months in data-center growth zones; some estimates seven to eight years application to operation.
- Northern Virginia (Dominion): about seven years (JLL 2026 outlook).
- ERCOT large loads over 75 MW: three to four years, before the pause.
- Georgia Power: no published queue; 18–36 months near substations with headroom, three to five years where new generation is needed.
- SPP: large-load process approved January 2026, agreements in 90 days for qualifying projects.
- Wood Mackenzie: power availability adds 24–72 months to data-center timelines.
- PPL: nothing found.

**Equipment lead times** (all [S])

- JLL average for data-center equipment: ~42 weeks; transformers and switchgear ~43 weeks, 83% above 2019.
- Medium-voltage switchgear 15 kV: 52–80 weeks; 38 kV: 78–104 weeks (contractor data, June 2026).
- Large power transformers: 128 weeks average (mid-2025); some high-voltage units 160 weeks (Reuters); DOE cites three to four years.
- Backup generators: ~51 weeks.
- Gas turbines: aeroderivative ~40 months; heavy-duty frames next open slots 2031–2032; smaller Solar Turbines units late 2028–2029.
- Labour constraints and chillers: not sourced this session.

**Politics: what is in force versus proposed**

| Jurisdiction | Status on 2026-11-11 | Evidence |
|---|---|---|
| Texas — ERCOT | **In force.** Since 2026-08-03 the Batch Zero study and final classification are paused, and approvals to energise new data-center and crypto loads of 75 MW or more are paused pending verification. Follows Governor Abbott's directive for "a comprehensive verification and audit". Verification report due to the PUC by 2026-12-10; failures are disqualified. Batch Zero allocations expected April 2027 (Galaxy [P]) | [S] ERCOT/PUC documents via search, Baker Botts; [P] Galaxy |
| Texas — TCEQ | **In force.** September 2026 instruction to stop issuing new data-center permits while information is gathered. This is the "September directive" Galaxy cites | [S] T3 |
| Texas — governor-elect Hinojosa | **Pledge only.** "Immediate moratorium" on new data centers until the Legislature passes protections; reported to apply to new projects, not those operating or under construction. Form undefined; Legislature is Republican-held | [S] T3 |
| New York | **In force.** Executive Order 62, effective 2026-07-14: one-year pause on discretionary environmental permits for data centers of 50 MW or more, ending when the state files its generic environmental impact statement. Complete applications proceed; local zoning unaffected. A separate bill with a 20 MW threshold: sources conflict on whether it was signed | [S] T3, law-firm notes |
| Maine | Legislature passed a statewide moratorium; governor vetoed. Three local six-month moratoriums passed on Nov 3 | [S] |
| Ohio | Governor-elect supports a "conditional moratorium" (proposal). A constitutional ban above 25 MW missed the 2026 ballot | [S] |
| Pennsylvania | Three-year pause bill proposed only | [S] |
| Georgia, Michigan, New Mexico | Governors-elect positions not confirmed this session | — |
| Local ballots, Nov 3 | Limits favoured in 40 of 41 measures across 10 states (Ballotpedia) | [S] T3 |

No statewide construction moratorium by statute is in force anywhere found. Two executive-branch pauses are: Texas (energisation and permits) and New York (permits).

**Peers and customers in 2026**

- Microsoft, 2026-10-29: quarterly capital spending $45.2B against "over $50 billion" guided; year cut to $170B from $175B; CFO attributed it to late third-party capacity, moved into January–June 2027. Providers not named; press notes Microsoft uses CoreWeave, IREN and Nebius. [S] T3 CNBC
- Crusoe / Abilene: buildings due March 2026 were still not online in June 2026 (≥3 months); OpenAI cancelled the 1.2 → 2.0 GW expansion in March. One blog says all six buildings were online by September; unverified. [S] T4
- Oracle: guidance said to absorb delays of up to two quarters at any large site. [S] T4
- Galaxy: "we saw actual projects around us getting delayed"; Helios II energisation mid-2028 at the earliest. [P]
- Applied Digital: "more local moratoriums, tighter zoning requirements, longer permitting time lines". [P]
- Core Scientific: reached 485 of 590 MW; the fleet target slipped about one to two quarters during 2025–2026. [P]
- IREN 10-K: "may be delays in the energization" of Texas projects. Bitdeer: Rockdale TX energisation moved from Q3 2027 to Q4 2027 between two filings. SB Energy S-1: Texas energisation subject to the audit. [S] T2
- Cipher, TeraWulf: nothing found.

---

## 4. Proposed delay distribution (judgement, not a model)

Probabilities are my estimates. The anchor is the 13-case sample (46% on time, 46% one to three months, 8% three to six), then shifted for three things the sample misses: larger sites slip more; the Sightline 30–50% delayed share covers all developers; and the 2026 political changes postdate the sample.

**(i) Energised or under construction with permits and power in hand**
Examples: Dalton 2, Ellendale 3, Helios II, Kenilworth, Mäntsälä 2, UK colocations.

| | On time | 1–3 mo | 3–6 mo | 6–12 mo | >12 mo or cancelled |
|---|---|---|---|---|---|
| Due 2027 | 40% | 35% | 15% | 8% | 2% |
| Due 2028 | 30% | 30% | 20% | 13% | 7% |

Basis: the sample, almost unadjusted for 2027. Denton and Abilene show that a three-to-six-month slip happens at large sites even with power in hand. 2028 is wider because construction has mostly not started (Helios III).

**(ii) Permitted, awaiting grid connection or a power plant**
Examples: Schuylkill, Independence, Birmingham, Lancaster, Hammond, Cedar Creek, Béthune full capacity, Vineland remainder (permits for the power plant itself).

| | On time | 1–3 mo | 3–6 mo | 6–12 mo | >12 mo or cancelled |
|---|---|---|---|---|---|
| Due 2027 | 20% | 25% | 25% | 20% | 10% |
| Due 2028 | 15% | 20% | 25% | 25% | 15% |

Basis: Sightline's 30–50% delayed share is closest to this group; transformer and switchgear lead times of one to three years mean a late order cannot be recovered; Texas energisation is paused with allocations not before April 2027; Vineland shows a behind-the-meter redesign costing months. No completed case in our sample belongs cleanly to this group, so this row rests on industry evidence only.

**(iii) Announced without permits**
Examples: expansion options (Niagara +215, Lancaster +200, Kenilworth +210), Rotterdam, NEOM, the unnamed >1.5 GW CoreWeave pipeline, Galaxy-type "studied load".

| | On time | 1–3 mo | 3–6 mo | 6–12 mo | >12 mo or cancelled |
|---|---|---|---|---|---|
| Due 2027 | 5% | 10% | 15% | 25% | 45% |
| Due 2028 | 10% | 10% | 15% | 25% | 40% |

Basis: Sightline found only ~5 of 16 GW due in 2026 under construction; cancellations rose from zero to nine; our own files hold two cancellations (Poolside, Andalusia); 40 of 41 local ballots went against developers; interconnection waits of three to seven years. The sample for this group is two cancellations and no completions.

**How thin this is.** Thirteen completed cases, none above 260 MW, none after August 2026. Group (i) is supported by data; (ii) and (iii) are informed guesses. A single observation would move them materially: Nebius's Q3 report on 2026-11-12 (Vineland) and ERCOT's report on 2026-12-10.

---

## 5. Supplier map for GB300 and Vera Rubin deployments

"Named" means CoreWeave or Nebius has named the company in a document read. "Reference" means generic to NVIDIA's design or the industry and INFERRED.

| Layer | Named by CoreWeave | Named by Nebius | Reference design / industry (INFERRED) |
|---|---|---|---|
| GPUs | $NVDA NVIDIA — sole GPU supplier [P] | $NVDA NVIDIA [P] | Foundry and packaging: $TSM TSMC |
| CPUs | NVIDIA Grace and Vera (Arm-based); $AMD AMD and $INTC Intel [P] | NVIDIA Vera; "ARM and CPU deployments" [P] | $ARM Arm Holdings (architecture) |
| High-bandwidth memory | None | None | SK hynix (KRX: 000660), Samsung Electronics (KRX: 005930), $MU Micron. HBM is bought by NVIDIA and arrives inside the GPU module; the cloud does not buy it separately |
| Server DRAM and SSDs (cloud buys) | Solidigm — SSD maker owned by SK hynix; multi-year supply agreement Aug 2026 [P]. DRAM supplier not named | None | DRAM: SK hynix, Samsung, $MU Micron. SSD: Samsung, Kioxia (TSE: 285A), $SNDK Sandisk, $MU Micron |
| Servers and racks | $DELL Dell — only named OEM; delivered first Vera Rubin NVL72 rack June 2026 [P]/[S]. Three unnamed suppliers were 23%, 20%, 17% of 2025 purchases [P] | In-house design; manufacturers not named [P] | $SMCI Supermicro, Quanta/QCT (TWSE: 2382), Wiwynn (TWSE: 6669), Foxconn/Hon Hai (TWSE: 2317), Wistron (TWSE: 3231), Inventec (TWSE: 2356), $HPE HPE. None confirmed for either company |
| Cluster network | NVIDIA Quantum-2 and Quantum-X800 InfiniBand, Spectrum-X Ethernet, ConnectX-8/9, BlueField-3/4 [P] | NVIDIA InfiniBand; BlueField [P] | Alternatives not named by either: $ANET Arista, $AVGO Broadcom, $CSCO Cisco, $MRVL Marvell |
| Optics and cables | None | None | $COHR Coherent, $LITE Lumentum, InnoLight (SZSE: 300308), Eoptolink (SZSE: 300502), $FN Fabrinet, $CRDO Credo, $APH Amphenol, $GLW Corning |
| Storage | VAST Data (private): all-flash data platform for AI, "dedicated VAST clusters" [P]. Own object storage | WEKA (private): parallel file system software on flash [P]. Own storage | DDN (private; Blackstone minority): parallel file storage for supercomputing. $PSTG Pure Storage: all-flash arrays. Neither named by either company in documents read |
| Cooling and power equipment | $VRT Vertiv (named with Dell and Switch for first GB300) [P] | None | Via landlord Applied Digital: ABB, BASX ($AAON), $CAT Caterpillar [P]. Others: Schneider Electric (Euronext Paris: SU), $ETN Eaton, $GEV GE Vernova, Siemens Energy (XETRA: ENR), Hitachi (TSE: 6501), $CMI Cummins, $TT Trane, $CARR Carrier, $JCI Johnson Controls, $MOD Modine, $NVT nVent, $POWL Powell |
| Fuel cells / on-site generation | $BE Bloom Energy at Volo IL [S] | $BE Bloom Energy, 328 MW [P]; Independence Power Partners LP (private) gas plant [P] | Turbines: $GEV, Siemens Energy, Mitsubishi Heavy (TSE: 7011), $CAT Solar Turbines |
| Landlords and developers | $CORZ Core Scientific, $APLD Applied Digital, $GLXY Galaxy, $DLR Digital Realty, Switch (private; DigitalBridge/IFM), Flexential (private), Chirisa (private), $OWL Blue Owl, Related Digital (private), Prime (private), EdgeConneX (private; EQT), Blockfusion (going public via Blue Acquisition), Bell (BCE, $BCE), AdaniConneX (Adani Enterprises NSE: ADANIENT / EdgeConneX), atNorth, Conapto, EcoDataCenter, Bulk, Global Switch, Merlin Properties (BME: MRL), DataVita (all private unless shown) | DataOne (private), Patmos (private), Verne (private; Ardian), Ark (private), $EQIX Equinix, Mega Or (TASE: MGOR), Kao Data, Vantage (private), Polarnode (private), Azur Datacenter (private), AIB Data Centers (SEC registrant; ticker not confirmed), builders ARCO and Hoar (private) | — |
| Fibre / backbone | Own backbone; vendors not named [P] | Not named | $LUMN Lumen, Zayo (private), $CIEN Ciena, $NOK Nokia |

Check result: no document read or search summary shows CoreWeave or Nebius naming Arista, Supermicro, Quanta/QCT, Wiwynn, Foxconn, Coherent, Lumentum, Schneider, Eaton or GE Vernova. One analyst note says CoreWeave's Q1 2026 call "did not disclose specific OEM or ODM suppliers" [S]. SemiAnalysis reports Dell gaining share at CoreWeave from Supermicro [S] T4.

---

## 6. Not sourced

- Utilities for Ellendale, Dalton, Marble, Austin, Cheyenne, Saskatchewan, Niagara Falls, Chesterfield, Elk Grove, Las Vegas, Hillsboro and all non-US sites: INFERRED or carried from the earlier file, not confirmed.
- Whether Vineland's stop orders were lifted and NJDEP permits issued; Vineland Municipal Electric's role; the LNG supplier.
- Independence Power Partners: owner, turbine supplier, capacity, in-service date.
- Interconnect MW for most sites; curtailment or interruptible terms for any site.
- Whether the ERCOT pause touches any specific CoreWeave site other than by inference (Cedar Creek, Helios approvals).
- Georgia, Michigan and New Mexico governors-elect positions; status of the New York 20 MW bill.
- Primary Sightline/Currence report; JLL, CBRE, Uptime, Synergy, Cushman, S&P, satellite trackers and Epoch AI were not reached.
- Labour and chiller lead times; Cipher and TeraWulf slippage.
- Server manufacturers for either company; DRAM suppliers; optics vendors.
- All tickers and ownership notes.

sec.gov documents worth pulling next: IREN 10-K (https://www.sec.gov/Archives/edgar/data/0001878848/000187884826000052/iren-20260630.htm); SB Energy S-1 (https://www.sec.gov/Archives/edgar/data/0002133037/000162828026059639/sbenergy-sx1.htm); Bitdeer 6-Ks (https://www.sec.gov/Archives/edgar/data/0001899123/000121390026086938/ea030131301ex99-1.htm).

---

## 7. Sources

**Read [P]**: Galaxy Q3 2026 presentation and call; Core Scientific Q3 2026 10-Q and call; Applied Digital FY2026 10-K and fiscal Q1 2027 call; CoreWeave Q2 2026 call and coreweave.com pages (Kenilworth, GB300, Solidigm, Vera Rubin); nebius.com/independencemo, /birminghamal, /schuylkillcountypa, /vinelandnj; Nebius Bloom release. URLs are in the two facility files.

**Search summaries only [S]:**
- Denton: https://www.bloomberg.com/news/articles/2025-07-14/coreweave-expands-dallas-area-data-center-power-grid-strains-grow
- ERCOT: https://www.ercot.com/files/docs/2026/08/20/Batch-Zero-Verification-and-Audit-PUCT-Presentation.pdf ; https://www.ercot.com/files/docs/2026/09/11/14-Batch-Zero-Update.pdf ; https://interchange.puc.texas.gov/Documents/59142_52_1675838.PDF ; https://www.bakerbotts.com/thought-leadership/publications/2026/august/texas-large-load-interconnection-update---ercot-batch-zero-pause-and-verification-process
- Texas governor-elect: https://kfoxtv.com/news/local/gina-hinojosa-won-the-governors-race-what-happens-to-texas-data-centers-now-11-04-2026 ; https://www.newsweek.com/texas-hits-brakes-on-data-centers-and-elon-musks-plans-12675796 ; https://qz.com/coreweave-texas-governor-elect-hinojosa-data-centers-110926 ; https://energynewsbeat.co/energy-policy/hinojosa-can-pause-data-centers-she-cant-rewrite-texas-power-alone/
- New York: https://www.datacenterknowledge.com/data-center-construction/new-york-data-center-moratorium-state-pauses-projects-over-50-mw ; https://www.clm.com/new-yorks-data-center-moratorium-a-practical-roadmap-through-the-one-year-pause/ ; https://spectrum.ieee.org/new-york-data-center-ban
- Ballots: https://news.ballotpedia.org/2026/11/06/voters-favored-limiting-data-center-development-in-40-of-41-local-ballot-measures-on-nov-3/
- Sightline: https://www.axios.com/2026/02/24/ai-data-center-boom-projects-numbers ; https://www.techspot.com/news/111947-nearly-half-us-data-centers-planned-2026-facing.html ; https://abc17news.com/stacker-technology/2026/10/19/tech-companies-need-more-data-centers-so-why-are-nearly-half-of-all-planned-projects-delayed-or-canceled/
- Equipment: https://terrapincg.com/news/switchgear-transformer-generator-lead-times-2026 ; https://datacenterscope.com/power/transformer-cost-lead-times/ ; https://savrn.com/research/data-center-supply-chain-crisis
- Interconnection: https://www.carbon-direct.com/press/carbon-direct-releases-new-analysis-of-power-grid-interconnection-queues-pjm-ercot ; https://gpuleaseindex.com/readiness/georgia-power-interconnection-timeline ; https://megawatthorizon.com/posts/miso-and-pjm-interconnection-queue-delays-for-data-centers
- Microsoft: https://www.cnbc.com/2026/10/29/microsoft-google-ai-capex-estimates.html
- Stargate: https://www.distilled.earth/p/openais-stargate-data-centers-are ; https://measuredai.substack.com/p/stargate-site-by-site-status
- Vineland: https://hntrbrk.com/breaking-news/vineland (publisher is short Bloom) ; https://cryptobriefing.com/nebius-vineland-data-center-second-stop-construction-order/ ; https://computeruser.com/microsoft-backed-data-center-under-fire-over-62-unpermitted-gas-generators
- Nebius Pennsylvania / Alabama: https://www.datacenterdynamics.com/en/news/nebius-details-plans-for-12gw-data-center-campus-in-pennsylvania/ ; https://www.tnonline.com/20260724/data-center-company-eyes-schuylkill-site/
- CoreWeave Volo, Hammond, Plano: https://www.bloomenergy.com/news/bloom-energy-and-coreweave-partner-to-revolutionize-ai-data-center-power-solutions/ ; https://www.datacenterdynamics.com/en/news/coreweave-to-develop-180mw-data-center-at-digital-crossroads-campus-in-hammond-indiana/ ; https://www.datacenter.fyi/public-record/coreweave-0d7f2259
- Suppliers: https://datacentremagazine.com/news/inside-dell-and-coreweave-world-first-vera-rubin-deployment ; https://newsletter.semianalysis.com/p/how-dell-is-beating-supermicro
