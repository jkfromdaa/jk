# CoreWeave (NASDAQ: CRWV) — per-facility data-center inventory

Compiled 2026-11-11. Latest company data point: Q3 2026 results (period end 2026-09-30, reported 2026-11-10).

## 0. How to read this file

**Evidence flags used on every figure**

- **[P]** = I opened the document itself in this session and read the passage (SEC filing text, company web page, or call transcript text).
- **[S]** = the figure comes from a web-search result summary only. I did not open the underlying page. Treat as unverified until checked.
- **INFERRED** = my own arithmetic or matching, not a statement by any source.
- **n/d** = not disclosed in anything I saw.

**Source tiers**

- T1 = CoreWeave SEC filing, press release, website, or earnings call.
- T2 = counterparty filing, press release or earnings call (landlord, developer, vendor).
- T3 = trade or financial press, local news.
- T4 = aggregator sites, analyst blogs, social media.

**Access notes**

- Primary documents were read directly from SEC EDGAR (CoreWeave filings, and the landlords' own filings: Core Scientific 10-Q, two decks and a press release; Applied Digital 10-K and two press releases; Galaxy Q3 exhibit 99.2; Blockfusion Form 425), from www.coreweave.com and from Motley Fool call transcripts.
- investors.coreweave.com and datacenterdynamics.com were never opened; everything from DCD, Bloomberg, LancasterOnline, The Information, WSJ etc. is [S].
- The Q3 2026 10-Q was not in the EDGAR index snapshot (latest entry: 8-K filed 2026-11-10). The Q3 2026 slide deck was not opened; its content here is [S].
- Call transcripts are Motley Fool transcriptions, which carry their own accuracy disclaimer.
- About 55 web searches were run.

**Important definitional caveat.** CoreWeave's "active power" is critical IT load that is operational and revenue-generating. Landlords report "billing MW" (Core Scientific), "ready for service" (Applied Digital) or "delivered critical IT load" (Galaxy). These are not the same measure and can lead CoreWeave's own "active" figure by one to two months of fit-out.

---

## (a) Fleet-wide facts

### a1. Data-center count, active power, contracted power

| Date | Data centers | Active power | Contracted power | Source |
|---|---|---|---|---|
| 2023-12-31 | 10 | ~70 MW | n/d | FY2025 10-K [P] T1 |
| 2024-12-31 | 32 | ~360 MW | 1.3 GW | 10-K [P]; 1.3 GW from Q4 2025 call [P] T1 |
| 2025-03-31 | n/d | not sourced this session | ~1.6 GW INFERRED (Q2 release says contracted rose "approximately 600 MW to 2.2 GW") | Q2 2025 release [P] T1 |
| 2025-06-30 | 33 (28 in US) per July 2025 blog | ~470 MW | 2.2 GW | Q2 2025 release [P]; Pennsylvania blog [P] T1 |
| 2025-09-30 | n/d | ~590 MW (+~120 MW in quarter) | ~2.9 GW | Q3 2025 release [P] T1 |
| 2025-12-31 | 43 | >850 MW (+~260 MW in quarter) | ~3.1 GW | Q4 2025 release, 10-K, Q4 call [P] T1 |
| 2026-03-31 | 49 ("close to 50") | >1 GW | >3.5 GW (+>400 MW, "entirely via long-term leases") | Q1 2026 release, Q1 call, Indonesia release [P] T1 |
| 2026-06-30 | 51 (8 added in 2026) | 1.5 GW (+~500 MW; >300 MW in June alone) | ~3.7 GW; 4.2 GW as of 2026-08-11 | Q2 2026 release, Q2 call, backbone blog [P] T1 |
| 2026-09-30 | 52 (9 added in 2026 per deck [S]) | >1.7 GW (+>200 MW) | >4.6 GW (+>900 MW vs 3.7 GW); >1.3 GW outside US | Q3 2026 release, Q3 call, coreweave.com/ai-data-centers [P] T1 |
| 2026-12-31 target | n/d | >1.85 GW (first guided >1.7 GW in Feb 2026; raised Aug 2026) | n/d | Q4 2025, Q2 2026, Q3 2026 calls [P] T1 |
| 2030 target | n/d | >8 GW | n/d | Q1 and Q2 2026 calls [P] T1 |

Other count facts:

- Year to date through Q3 2026, CoreWeave "brought online more than 850 megawatts" (Q3 call [P]).
- Europe: nine data centers across five geographies (UK, Spain, Sweden, Norway, Denmark) as of 2026-10-27 (Denmark release [P]). DCD's tally is Sweden x2, Norway, Denmark, Spain x3, UK x2 [S].
- INFERRED: 52 total minus 9 in Europe leaves 43 active sites in the US and Canada.
- FY2025 10-K: data centers "across the United States, Europe, and Canada, operating in six countries total" [P].
- An earlier company release (Jan 2025) says "By the end of 2024, CoreWeave opened 28 data centers globally" [P], against 32 at 2024-12-31 in the 10-K. See conflicts.

### a2. Lease versus own

| Fact | Source |
|---|---|
| "We currently lease all of our existing data centers and offices." Stated in both the FY2025 10-K and the Q2 2026 10-Q (as of 2026-06-30). | [P] T1 |
| Only ownership interest disclosed: a JV developing a multi-phase campus in Kenilworth NJ. CoreWeave held 15% at formation (June 2025), 20% at 2026-03-31, 35% at 2026-06-30. | Q1 and Q2 2026 10-Qs [P] T1 |
| During H1 2026 CoreWeave "committed to invest up to $1.7 billion ... to acquire equity interests in two separate joint ventures that each hold a data center development project" ($1.2B at Q1, +~$0.5B in Q2). The projects are not named. | Q2 2026 10-Q [P] T1 |
| Q1 2026 contracted additions were "entirely via long-term leases". "We expect our first self-build site to come online later this year" (said May and again Aug 2026). The site is not named by the company. | Q1 and Q2 2026 calls [P] T1 |
| Not in contracted power: "more than 1.5 gigawatts of further potential power from powered land we have accumulated. Options we have to expand at existing sites, and LOIs we have executed." (as of 2026-08-11) | Q2 2026 call [P] T1 |
| Concentration: "no single data center provider that delivers more than 17% of our active infrastructure" (May 2026). In Nov 2025: none above ~20% of contracted power [S]. | Q1 2026 call [P]; DCD [S] |

### a3. Lease commitments (fleet level)

| Date | Undiscounted operating-lease payments (commenced leases) | Leases not yet commenced | MW-denominated disclosures | Source |
|---|---|---|---|---|
| 2025-03-31 | $5.2B | n/d | n/d | XBRL companyfacts [P] |
| 2025-09-30 | $7.7B | $39.1B (start 2025-2029; 2-16 yr terms) | Single site 393 MW, "delivered in phases in 2026", rent $13.5-14.4B over 16 yrs; other cost-based leases 232 MW (2025-2027) | Q3 2025 10-Q [P] |
| 2025-12-31 | $13.6B | $38.5B (start 2026-2029; 5-17 yr terms) | Single site 393 MW, phases "in 2026 and 2027"; other 378 MW (2026-2028) | FY2025 10-K [P] |
| 2026-03-31 | $17.0B | $40.7B | Single site 525 MW, phases "in 2026 and 2028", rent $18.7-19.6B; other 363 MW | Q1 2026 10-Q [P] |
| 2026-06-30 | $29.1B | $35.5B (start 2026-2029; 7-16 yr terms) | Single site: 393 MW "remained undelivered", phases "in 2026 and 2028", rent capped at $14.7B; other 355 MW undelivered (2026-2028) | Q2 2026 10-Q [P] |

Also at 2026-06-30 [P]: lessee-owned equipment obligations at leased premises of $0.5-1.2B through 2028; an equipment lease (mechanical, electrical, plumbing infrastructure for a data center) with committed payments of ~$1.8B; lease prepayments of $108M to developer VIEs.

### a4. Timing from contracted to active

| Fact | Source |
|---|---|
| "Upon receipt of a powered shell ... the fit-out process, which, on average, takes us about 1 to 2 months ... By month 3, however, we are typically generating revenue." | Q1 2026 call [P] T1 |
| 3.1 GW at YE2025: "virtually all of which we expect to come online by 2027" (Feb 2026). 3.5 GW at Q1 2026: "substantial majority ... by the end of 2027" (May 2026). | Q4 2025 and Q1 2026 calls [P] T1 |
| Lead times on new international sites: Indonesia "approximately 18 months" (Aug 2026), India first phase mid-2028 (signed by Oct 2026). | Q2 call, India release [P] T1 |
| "We also do not see material risks to our 2027 deliveries based on ongoing construction at fully permitted sites." | Q3 2026 call [P] T1 |

### a5. Hardware, network, storage — fleet-level statements only

Per-site hardware is rarely disclosed. Everything in this table is a fleet-level statement unless a site is named.

| Layer | What CoreWeave has stated | Source |
|---|---|---|
| GPUs | "all of the GPUs used in our infrastructure today are NVIDIA GPUs". Generations referenced: Ampere, Hopper (H100, H200), Blackwell (HGX B200, GB200 NVL72, GB300 NVL72), RTX PRO 6000, Vera Rubin NVL72 (first production workload for Cognition, 2026-09-30). | 10-K, Vera Rubin release, Q3 release [P] T1 |
| CPUs | AMD and Intel; NVIDIA Grace in GB200/GB300; NVIDIA Vera announced. | 10-K, Q3 release [P] T1 |
| Server OEM | Dell is the only named OEM: GB300 "housed within Dell's integrated rack scale system"; "among the first cloud providers to deploy Dell PowerRack systems featuring NVIDIA GB200 and GB300 NVL72". Other OEMs and ODMs are not named. Three unnamed suppliers were 23%, 20% and 17% of 2025 purchases. | GB300 blog, Vera Rubin release, 10-K [P] T1 |
| Cluster network | NVIDIA Quantum-2 InfiniBand; Quantum-X800 (800 Gb/s per GPU with ConnectX-8); Spectrum-X Ethernet with RoCE. With Vera Rubin: liquid-cooled Spectrum-X SN6600-LD (102.4 Tb/s, Spectrum-6 ASIC), ConnectX-9. | 10-K, GB300 blog, liquid-cooled switching blog [P] T1 |
| DPUs | BlueField-3 (18 per GB300 NVL72 rack); BlueField-4 with Vera Rubin. | GB300 and Rubin blogs [P] T1 |
| Backbone | Own backbone across North America and Europe; "multiple 400 gigabit-per-second connections at each point of presence", MACsec; new PoPs in UAE, India, Indonesia, Singapore, Australia, Korea, Japan from Q4 2026, full loop mid-2027. Direct Connect at 10/100/400 Gbps. Switch, optics and fibre vendors are not named. | Denmark release, 10-K [P] T1 |
| Storage | Own AI Object Storage (LOTA); "Dedicated VAST clusters"; VAST Data named as partner; multi-year Solidigm SSD supply agreement (2026-08-05). Memory suppliers n/d. | Website, Q3 release, Solidigm release [P] T1 |
| Cooling | Closed-loop direct-to-chip liquid cooling "in many cases"; ~130 kW racks; GB200 NVL72 at 85% liquid / 15% air; Vera Rubin at 45°C liquid. | Website and blogs [P] T1 |
| Data-centre partners named for first GB300 deployment | Dell, Switch, Vertiv (July 2025). | GB300 release [P] T1 |

---

## (b) Facility tables

Column notes: "MW contracted" is critical IT MW unless marked gross. "MW live" uses the landlord's own measure where the landlord is the source.

### b1. OPERATIONAL / energized (status as of 2026-09-30 to 2026-11-10)

| # | Site | Owner / landlord; structure | MW contracted to CRWV | MW live and date | Original vs actual timing | End customer | Power; cooling; compute | Evidence |
|---|---|---|---|---|---|---|---|---|
| 1 | Denton, TX | Core Scientific; colocation licence, 12 yr + two 5-yr options | ~260 | ~260 billing (2026-11-05) | Landlord targeted 250 MW billing fleet-wide by YE2025; only 120 MW billing at 4Q25. Denton delayed ~60 days by weather per WSJ [S]. Full by Q3 2026. | OpenAI per The Information [S] | ERCOT; cooling n/d by site; >16,000 GPUs deployed by Jan 2026 [S] | T2 [P] for MW; T3 [S] for delay and customer |
| 2 | Dalton, GA (phase 1) | Core Scientific; same contract family | ~175 total | ~75 billing (2026-11-05); ">70 MW" on call | Phase 2 in bucket 2 | n/d | n/d | T2 [P] |
| 3 | Muskogee, OK | Core Scientific | ~70 | ~70 billing | Was "on track for midyear" 2026 [S]; billing by Q3 2026 | n/d | OG&E; landlord paid $13M toward utility substation | T2 [P] |
| 4 | Marble, NC | Core Scientific | ~65 | ~65 billing | Fully handed over [S] | n/d | n/d | T2 [P] |
| 5 | Austin, TX | Core Scientific; 7-yr term with extensions | ~20 (first reported as 16 MW [S]) | ~20 billing | Fully handed over [S] | n/d | n/d | T2 [P] |
| 6 | Polaris Forge 1, Ellendale, ND (buildings 1 and 2) | Applied Digital; three ~15-yr leases; landlord builds, tenant fit-out billed to tenant | 400 across three buildings | 250 RFS as of 2026-10-01 (100 in late 2025; +75 on 2026-07-01; +75 on 2026-10-01) | Bldg 1: planned Q4 2025, met. Bldg 2: planned "middle of 2026"; half delivered 1 Jul, half 1 Oct 2026 | n/d | MDU; liquid-cooled; bldg 1 "capable of supporting more than 40,000 liquid cooled NVIDIA GB300s" | T2 [P] |
| 7 | Helios I phase I, Dickens County, TX | Galaxy Digital; 15-yr lease with CoreWeave, Inc. (parent) | 133 (~200 gross) | 133 delivered through Q2 2026; completion announced July 2026 [S] | Planned H1 2026 [S]; delivered "on schedule" | "large multitrillion dollar investment grade hyperscaler" (unnamed) | ERCOT; Galaxy-owned 345 kV substation; direct liquid cooling | T2 [P] |
| 8 | DEN01, Copenhagen (Ballerup), Denmark | atNorth; lease | 22.5 | "majority" online (2026-10-27) | n/d | n/d | Renewable PPAs, heat reuse; Blackwell + Quantum-X800 | T1 [P] |
| 9 | Crawley, UK | Digital Realty | n/d | Live since Oct 2024 | n/d | n/d | Renewable; H200 + Quantum-2 InfiniBand | T1 [P] |
| 10 | London Docklands, UK | Global Switch | n/d | Live since Dec 2024 | n/d | n/d | Renewable; H200 + Quantum-2 | T1 [P] |
| 11 | Barcelona (Zona Franca), Spain | MERLIN Edged (Merlin Properties / Edged JV) | 15 [S] | Inaugurated May 2025 [S] | n/d | n/d | 10,224 H200 [S]; Blackwell phase planned 2026 [S] | T3 [S] |
| 12 | Other Spain (DCD counts three Spanish sites) | Merlin / Edged, Álava reported at 18 MW [S]; third site n/d | n/d | n/d | n/d | n/d | Solar and wind PPA; a site with adjacent 100 MW solar farm mentioned mid-2025 [S] | T3 [S] |
| 13 | Stockholm 4 South, Sweden | Conapto; colocation | n/d (site IT capacity 32 MW [S]) | "initial capacity already online" (2026-06-24) | n/d | n/d | 100% renewable, heat recovery; Blackwell and Vera Rubin + Quantum-X800 | T1 [P] |
| 14 | Falun, Sweden | EcoDataCenter | n/d | Planned early 2025 [S]; actual n/d | n/d | n/d | Blackwell [S] | T3 [S] |
| 15 | N01, Vennesla (near Kristiansand), Norway | Bulk Infrastructure | n/d | Planned summer 2025 [S]; actual n/d | n/d | n/d | GB200 NVL72 + Quantum-2 [S] | T2/T3 [S] |
| 16 | Cambridge, Ontario, Canada | n/d | n/d | Set up by Dec 2024 [S] | n/d | Cohere [S] | n/d | T3 [S] |
| 17 | CTP-01, Chester (Chesterfield County), VA | Chirisa Technology Parks; 12-yr licence + two 5-yr options [S] | ~28 (27-28 [S]); aggregator shows 82 [S] | Operational [S] | n/d | n/d | n/d | T3/T4 [S] |
| 18 | Plano, TX (1000 Coit Rd) | Lincoln Rackhouse [S]; a Flexential 13 MW deployment is also listed for Plano [S] | n/d (aggregator: 30 [S]) | Announced to be fully operational by 2023-12-31 [S]; named as active in Nov 2026 letter [S] | n/d | n/d | $1.6B announced 2023 [S] | T3/T4 [S] |
| 19 | Richardson, TX | n/d | n/d | Named as active in Nov 2026 letter [S] | n/d | n/d | n/d | T3 [S] |
| 20 | Round Rock, TX | n/d | n/d | Named as active in Nov 2026 letter [S] | n/d | n/d | n/d | T3 [S] |
| 21 | Hillsboro, OR | Digital Realty 36 MW [S]; Flexential "Portland – Hillsboro 4" 9 MW [S] | 45 combined [S] | n/d | n/d | n/d | n/d | T4 [S] |
| 22 | Douglasville, GA | Flexential | 9 [S] | n/d | n/d | n/d | n/d | T4 [S] |
| 23 | Las Vegas, NV | Switch | n/d | Listed as US West region [S]; first GB300 NVL72 deployment was at a Switch facility (city not stated) [P] | n/d | n/d | Dell GB300 racks, Vertiv | T1 [P] / T4 [S] |
| 24 | Weehawken, NJ; Chicago, IL | n/d | n/d | Listed as US East and US Central regions [S] | n/d | n/d | n/d | T4 [S] |
| 25 | Volo, IL | Chirisa Technology Parks | 14 [S] | Bloom fuel cells due Q3 2025 [S]; actual n/d | n/d | n/d | Bloom Energy solid-oxide fuel cells (behind the meter) [S] | T3 [S] |
| 26 | Unidentified "DCSP" site | A data-centre service provider; service agreement June 2023 plus 14-yr finance lease from April 2025 | up to 78 MW of electrical power | n/d | n/d | n/d | CoreWeave lent the provider up to $305M at 13% | T1 [P]; site not named |

Leads checked and not confirmed as CoreWeave sites in this session: Secaucus NJ, Orangeburg NY, TierPoint. Aggregators also list Edison NJ, Boston and Phoenix with no corroboration [S].

### b2. UNDER CONSTRUCTION or contracted but not yet active

| # | Site | Owner / developer; structure | MW contracted to CRWV | Schedule: original → current | End customer | Power; cooling; compute | Capex / property | Evidence |
|---|---|---|---|---|---|---|---|---|
| 1 | Dalton, GA phase 2 | Core Scientific | ~100-105 remaining of 175 | "Early 2027"; in commissioning Nov 2026 | n/d | n/d | Landlord paid $0.7M road works | T2 [P] |
| 2 | Polaris Forge 1 third building, Ellendale, ND | Applied Digital; third lease (Aug 2025), ~15 yr | 150 | "mid 2027" (Aug 2025) → "calendar year 2027", "progressing on schedule" (Oct 2026). 10-K delivery window for the 400 MW: "2H25–1H27" | n/d | Liquid-cooled | Funded by $1.59B 7% notes due 2031 | T2 [P] |
| 3 | Polaris Forge 1 second building, last 75 MW | Applied Digital | 75 (included in b1 row 6 as RFS) | RFS 2026-10-01; in tenant fit-out, so probably not in CoreWeave's 2026-09-30 active figure (INFERRED) | n/d | — | — | T2 [P] |
| 4 | Helios I phase II, Dickens County, TX | Galaxy Digital; 15-yr lease | 260 (~400 gross) | Galaxy 2025: delivered "throughout 2027" [S] → Galaxy Oct 2026: data-hall deliveries from Q2 2027, on schedule. CoreWeave filings moved from "2026" to "2026 and 2027" to "2026 and 2028" (see notes) | Not yet allocated | 345 kV substation; direct liquid cooling | Est. construction cost $4.0B; $3.5B notes | T2 [P] |
| 5 | Helios I phase III | Galaxy Digital; 15-yr lease | 133 (~200 gross) | Initial rent commencement 2028; debt financing planned H1 2027 | Not yet allocated | As above | Equity funded so far | T2 [P] |
| 6 | NEST 11, Kenilworth, NJ | JV: CoreWeave 35% (2026-06-30) with a third-party developer; forward-starting 15-yr lease with rent set as a percentage of construction cost | "planned 40 MW load" for NEST 11; campus "up to 250MW" | "initial phase expected to be delivered in 2026" (Aug 2025) → "operational in early 2027" [S] | n/d | PSE&G; CoreWeave funds ~$150M substation; closed-loop cooling; "100% clean energy" | $1.8B; $322M purchase of building [S]; $555M loan [S]; 392,600 sq ft [S] | T1 [P]; T3 [S] |
| 7 | Lancaster, PA (216 Greenfield Rd) | Developer JV of Blue Owl, Chirisa Technology Parks, Machine Investment Group [S]; CoreWeave commits "up to $6 billion to equip" | 100 initial | Announced July 2025; phase 1 "expected to be ready by summer 2027" [S] | n/d | New PPL substation and switchyard [S] | 78 acres [S]; $4B developer capital [S] | T1 [P] for MW; T3 [S] for status |
| 8 | Digital Drive, Chesterfield County, VA | PowerHouse Data Centers / Chirisa with Blue Owl equity [S]; 15-yr lease, $2.94B [S] | 76 MW IT [S] vs 200 MW two-building [S] | Buildings due late 2027 and mid-2028 [S] | n/d | n/d | ~$1.1B junk bond, Sept 2026 [S] | T3 [S] |
| 9 | Chester, VA JV programme | Blue Owl / Chirisa / PowerHouse JV (up to $5B) [S] | 120 [S] | "delivered ... in 2025 and 2026" [S]; actual n/d. May already be partly operational | n/d | n/d | $750M financing May 2025 [S] | T2/T3 [S] |
| 10 | Cheyenne, WY | Related Digital; "long-term lease" | 88 | Ground broken 2025-10-07; first building "expected to be completed late 2026" [S] | n/d | Black Hills Energy large-load tariff [S] | $1.2B phase 1; 184,000 sq ft on 36 acres [S] | T2 [S] |
| 11 | Elk Grove Village, IL | Prime Data Centers (Elk Grove Village Property LLC); build-to-suit, 15-yr lease + two 7-yr renewals, ~$2.2B [S] | n/d | n/d | n/d | Tenant pays power, utilities, taxes [S] | $900M 7.5% notes, 2026-06-02 [S] | T3 [S] |
| 12 | Cedar Creek (Bastrop County), TX, Building 1 | EdgeConneX | n/d (one source: "up to 96 megawatts" for the building [S]) | Building expected finished summer 2026 [S]; not in the Nov 2026 list of active Texas sites [S] | n/d | n/d | $440M; 578,000 sq ft; 10-yr 75% tax abatement [S] | T3 [S] |
| 13 | Niagara Falls, NY | Blockfusion (North East Data, LLC); 15-yr anchor lease + two 5-yr options, signed 2026-09-16 | 85 take-or-pay per June LOI [S]; definitive release gives no MW [P] | n/d | n/d | Hydroelectric and nuclear; liquid-cooled retrofit | ~$2.8B over 15 yr [S] | T2 [P] for lease; [S] for MW |
| 14 | Bell AI Fabric, RM of Sherwood (near Regina), Saskatchewan | Bell Canada (BCE); tenants fund compute | 140 [S] (Cerebras 160) | Announced 2026-03-16; first phase H1 2027, revenue to Bell from H2 2027 [S] | n/d | SaskPower [S] | Bell capex C$1.7B [S] | T2/T3 [S] |
| 15 | Greater Jakarta, Indonesia (three facilities) | Developer n/d | 360 "contracted IT power" | Announced 2026-08-04; "expected to come online in 2028"; "approximately 18 months" | n/d | n/d | n/d | T1 [P] |
| 16 | Taloja campus, Navi Mumbai, India | AdaniConneX (Adani / EdgeConneX JV); sole tenant, three 80 MW buildings | 240 | Announced 2026-10-06; first phase "mid-2028" | n/d | Direct liquid cooling, non-evaporative chilled water; Vera Rubin planned | n/d | T1 [P] |
| 17 | DataVita, Scotland | DataVita (DV1 supports up to 40 MW [S]) | n/d | Announced 2025-09-16; live date n/d | "sovereign AI" deployment also planned | Renewable; closed-loop cooling; Grace Blackwell Ultra (GB300) | Part of £1.5B UK phase | T1 [P] |
| 18 | Second Stockholm campus | Conapto | n/d | n/d | n/d | Renewable | n/d | T1 [P] |

### b3. ANNOUNCED / PIPELINE / options (company says these are outside contracted power) and cancellations

| # | Item | MW | Status | Evidence |
|---|---|---|---|---|
| 1 | Company aggregate: powered land, expansion options at existing sites, executed LOIs | >1,500 | As of 2026-08-11; not itemised | Q2 2026 call [P] T1 |
| 2 | Navi Mumbai expansion option | up to +240 | "opportunity to double capacity" (DCD summary says total 580 [S], which conflicts) | India release [P] T1 |
| 3 | Niagara Falls expansion agreement | up to ~215 more (300 total per LOI [S]) | Conditional on Blockfusion securing firm power and CoreWeave approval | Blockfusion 425 [P]; DCD [S] |
| 4 | Lancaster, PA expansion | +200 (to 300) | "room to grow up to 300 MW"; a second Greenfield Road phase faces a resident appeal [S] | Blog [P] T1; [S] |
| 5 | Kenilworth, NJ rest of campus | up to ~210 beyond NEST 11 (250 total) | Ground lease on a separate parcel (Nov 2025) with purchase option; 27 acres acquired next to NEST 11 [S] | 10-Q [P]; [S] |
| 6 | Two unnamed JV development projects | n/d | $1.7B funding commitment, to be satisfied during 2026 | Q2 2026 10-Q [P] T1 |
| 7 | Cheyenne campus beyond the 88 MW | campus 302 or 420 [S] | No CoreWeave option disclosed | [S] |
| 8 | Bell Saskatchewan expansion | up to 900 | Non-binding MOU 2026-09-14; tenant not stated | [S] T4 |
| 9 | Cedar Creek buildings 2-4 | n/d | No CoreWeave commitment seen | [S] |
| 10 | NVIDIA collaboration | ">5 gigawatts of AI factories by 2030" | Framework (Jan 2026); NVIDIA to help procure land, power, shell | Release [P] T1 |
| 11 | CANCELLED: Poolside "Project Horizon", West Texas | 250 anchor + 500 option | Deal reported collapsed 2026-04-02 (FT via DCD) [S] | T3 [S] |
| 12 | TERMINATED: acquisition of Core Scientific | — | Core Scientific holders voted it down; merger agreement terminated 2025-10-30 [S]. Since then: leases continue, some assigned to a CoreWeave SPV [P] | [S]; Core Scientific 10-Q [P] |
| 13 | Not CoreWeave: Polaris Forge 2 (Harwood ND) | 200 | Leased to an investment-grade hyperscaler, no CoreWeave link found | APLD call [P] |
| 14 | Not CoreWeave: Helios II | 830 gross approved | Unleased; Galaxy walked away from a summer 2026 deal with an unnamed party | Galaxy call [P] |

No lease between CoreWeave and TeraWulf, Cipher, Hut 8, IREN, Bitdeer, Riot, CleanSpark, Bitfarms, Crusoe, Vantage, Aligned, CyrusOne, Compass or Stream turned up in the searches run. That is absence of evidence in a limited search, not proof.

---

## (c) Per-site notes with supporting quotes

Quotes are verbatim from documents I opened unless marked [S], in which case the text is a search-result summary.

### Core Scientific sites (Denton, Dalton, Muskogee, Marble, Austin)

- Core Scientific 10-Q for 2026-09-30 [P]: "Billable customer power capacity of 485 MW as of September 30, 2026, against 590 MW of leased customer power capacity to CoreWeave, with the remaining 105 MW in various stages of construction and commissioning."
  https://www.sec.gov/Archives/edgar/data/1839341/000183934126000030/core-20260930.htm
- Same filing [P]: "Operating lease payments expected to be received exclude $1.8 billion in total future noncancellable operating lease payments expected to be received for CoreWeave operating leases that have not yet commenced as of September 30, 2026, which have initial lease terms of 12 years from commencement."
- Same filing [P]: "CoreWeave entered into assignment and assumption agreements transferring certain license agreements to CW SPV, a special purpose vehicle that is an indirect subsidiary of CoreWeave. CoreWeave remains a primary obligor under those agreements."
- Same filing [P]: "Our agreement with CoreWeave is funded almost entirely by the customer". Nine-month capex of $1.5B, "of which $180.9 million was funded by CoreWeave".
- Q3 FY26 deck, 2026-11-05 [P]: "COREWEAVE 590 MW LEASED POWER Denton, TX 260 MW Dalton, GA 175 MW Muskogee, OK 70 MW Marble, NC 65 MW Austin, TX 20 MW".
  Status slide: Denton ~260 billing; Dalton ~175 leased, ~75 billing, "Est. completion early 2027"; Muskogee ~70; Marble ~65; Austin ~20; "Total ~590 MW ... ~485 MW* *Total billing as of November 5, 2026."
  Billing progression: "120 225 395 485 4Q25 1Q26 2Q26 3Q26".
  Contract: "~590MW infrastructure ~800MW gross"; "12-year contract with two 5-year options"; "Austin, Texas contract term is 7 years with elective extensions"; "Up to $1.5 Million per MW (or approximately $750 Million) of data center build out costs are funded by CoreWeave and credited against hosting payments at no more than 50% of monthly fees until fully repaid."
  https://www.sec.gov/Archives/edgar/data/1839341/000183934126000028/q3fy26earningsdeckvfinal.htm
- Q3 2026 call, 2026-11-05 [P]: "Dalton Phase 2 is the only facility still under construction, and we remain on track to deliver the remaining approximately 100 MW by early next year." Also: "We are now billing for 485 MW of the 590 MW contracted across five campuses, up from 120 MW at the beginning of the year." Also: "At certain campuses, payments are made through special purpose vehicles supported by end customer commitments, with CoreWeave remaining the ultimate guarantor."
  https://www.fool.com/earnings/call-transcripts/2026/11/05/core-scientific-corz-q3-2026-earnings-call-transcript/
- Q4 FY25 deck, 2026-03-02 [P]: "Energized ~350 MW and delivered 185+ MW of active billable capacity".
  https://www.sec.gov/Archives/edgar/data/1839341/000162828026013214/q4fy25earningsdeckvfinal.htm
- Feb 26, 2025 release [P]: "The 70 MW of expansion at the Denton site brings the full critical IT load to just over 260 MW." For that 70 MW, "Core Scientific is responsible for funding $104 million of capex ($1.5M per MW) for the powered core and shell".
  https://www.sec.gov/Archives/edgar/data/1839341/000162828025008312/ex991-coreweavepressrelease.htm
- Delay evidence [S]: Core Scientific's Oct 30, 2025 presentation said "On track to energize 250 MW by the end of 2025 and a total of 590 MW by early 2027". A March 2026 call summary says 213 MW was energized by YE2025, short of the goal by one data hall. WSJ (Dec 2025) reported rain and wind stopped concrete pours for about 60 days at Denton and that completion of the 260 MW cluster slipped "several months". The Information (Jan 2026) reported more than 16,000 GPUs deployed at the delayed site and identified it as being developed for OpenAI. A commentator disputed the weather explanation on social media (T4).
- CoreWeave's own account [P]: "We quickly cleared the delays discussed in our third quarter earnings call, and in total, we have now delivered more than 50,000 Grace Blackwells to the impacted customer" (Q4 2025 call). The company never named the site or the landlord.
- CoreWeave 8-K filed 2026-01-02 [P]: the DDTL 3.0 amendment "aligns the facility for the timing of deliveries described by the Parent on its earnings call reporting financial results for the quarter ended September 30, 2025", and postpones covenant test dates.
  https://www.sec.gov/Archives/edgar/data/1769628/000176962826000003/crwv-20251231.htm

### Applied Digital — Polaris Forge 1, Ellendale, ND

- FY2026 10-K (year ended 2026-05-31) [P]: "Our first HPC data center at the campus, with approximately 100 MW of critical IT load, became operational in October 2025. A second data center, expected to provide an additional 150 MW, is partially operational, and a third data center, also expected to provide approximately 150 MW, is under construction with an anticipated ready-for-service date in calendar year 2027."
  Lease table row: "Polaris Forge 1 CoreWeave 400 MW 15 years ~$11.0B 2H25–1H27".
  https://www.sec.gov/Archives/edgar/data/1144879/000114487926000048/apld-20260531.htm
- Same 10-K [P], on restructuring: "On March 30, 2026 ... the ELN-02 Lease was amended and the ELN-03 Lease was assigned, in each case, to a wholly owned subsidiary of CoreWeave, CoreWeave Compute Acquisition Co. VIII, LLC". CoreWeave gave springing guaranties and "is obligated to provide a letter of credit in the amount of $50 million".
- Same 10-K [P], fit-out: the HPC business recognised "approximately $270.6 million related to tenant fit-out services" in the year the first building opened. INFERRED: the tenant pays the landlord for fit-out.
- Naming: the 10-K calls the 100 MW building "Building 2" (ELN-02), the first 150 MW building "Building 3" (ELN-03) and the third lease the "Building 4 Lease". Press releases call them the first, second and third buildings.
- Original dates, June 2025 release [P]: "Applied Digital expects the first 100 MW data center for CoreWeave to be ready for service in the fourth quarter of calendar 2025. The second building, which is expected to house a 150 MW data center, is currently under construction and is expected to be ready for service in the middle of 2026."
  https://www.sec.gov/Archives/edgar/data/1144879/000164117225013199/ex99-2.htm
- Aug 2025 release [P]: "The new lease agreement is anticipated to be at full capacity and ready for service in mid 2027."
  https://www.sec.gov/Archives/edgar/data/1144879/000149315225012458/ex99-1.htm
- Fiscal Q1 2027 call, 2026-10-07 [P]: "As of today, we have achieved full Ready for Service or RFS across our first 2 buildings at our Polaris Forge 1 campus with our third building progressing on schedule. The operational buildings encompass 10 data halls and are supported by 250 megawatts of critical IT load." Also: "By the end of calendar year 2025, the first building was fully operational, capable of supporting more than 40,000 liquid cooled NVIDIA GB300s." Also: "the full 400 megawatts of the CoreWeave campus at Polaris Forge 1 ... are now fully funded."
  https://www.fool.com/earnings/call-transcripts/2026/10/08/applied-digital-apld-q1-2027-earnings-call-transcript/
- Dates of the second building's two 75 MW phases (2026-07-01 and 2026-10-01) are [S] (GlobeNewswire headline and results summaries).

### Galaxy Digital — Helios, Dickens County, TX

- Q3 2026 investor presentation (exhibit 99.2) [P]: "CoreWeave has leased 526 MW of critical IT capacity ... Galaxy successfully delivered 133 MW of critical IT to CoreWeave on schedule under the Phase I lease agreement, transitioning the site from construction to operational facility throughout Q2 2026."
  Phase table: "Phase I Delivered Critical IT Load 133 MW Q2 2026 Delivery Date $315M Annual Base Revenue Construction Cost $1.8B Phase II Contracted Critical IT Load 260 MW Q2 2027 Initial Rent Commencement $675M Annual Base Revenue Est. Construction Cost $4.0B Phase III Contracted Critical IT Load 133 MW 2028 Initial Rent Commencement".
  Gross power: "approximately 200 MW of gross power capacity for Phase I, approximately 400 MW ... for Phase II, and approximately 200 MW ... for Phase III."
  Term: "Each data hall is leased through the end of the 15-year base term, which commences upon turnover of the final data hall".
  Site: "over 2,200 contiguous acres in Dickens County"; "privately owned 345 kV grid connected substation ... supporting up to 900 MW of transformer capacity"; chillers feeding "direct-liquid-cooling systems"; data-centre building "spanning over 125,000 sq ft".
  https://www.sec.gov/Archives/edgar/data/1859392/000185939226000108/exhibit992-glxyq32026ove.htm
- Q3 2026 call, 2026-10-27 [P]: "Both buildings and the supporting substation are progressing on schedule and within budget ... with data hall deliveries scheduled to begin in the second quarter of 27." Also: "While certain additional approvals remain outstanding following governor Abbott's September directive, we do not currently expect an impact to our construction progress or our anticipated energization timelines."
- Same call [P], on tenant and customer: "the 3 leases that exist today for Helios I are with CoreWeave's parent company." "the loads running today ... in Helios I are coming from a customer contract that is currently allocated to a, large multitrillion dollar investment grade hyperscaler." "We do not have insight yet into ultimately who is going to be in phase 2, let alone Phase III."
  https://www.fool.com/earnings/call-transcripts/2026/10/27/galaxy-digital-glxy-q3-2026-earnings-call-transcript/
- Original schedule [S]: Galaxy's April 2025 release put phases I and II at about 393 MW combined, with phase I ready in H1 2026 and phase II delivered "throughout 2027".

**Matching CoreWeave's "single site" lease to Helios — INFERRED, not confirmed by either company.**

- CoreWeave Q3 2025 10-Q [P]: "The agreement provides access to 393 MW of electrical power, which is expected to be delivered in phases in 2026 ... total contractual rent payments range from $13.5 billion to $14.4 billion over the 16 year term".
- FY2025 10-K [P]: same 393 MW, "delivered in phases in 2026 and 2027".
- Q1 2026 10-Q [P]: "access to 525 MW ... delivered in phases in 2026 and 2028 ... $18.7 billion to $19.6 billion over the sixteen year term".
- Q2 2026 10-Q [P]: "393 MW of electrical power remained undelivered at the site and was expected to be delivered in phases in 2026 and 2028 ... contractual maximum of $14.7 billion".
- The numbers line up with Helios: 133 + 260 = 393 (phases I and II, leased in 2025); 133 + 260 + 133 = 526 (all three phases, vs 525 in the 10-Q); and after phase I's 133 MW was delivered in Q2 2026, 393 MW (260 + 133) remained. Rent is cost-based in both descriptions.
- This also means phase III was added to CoreWeave's contracted power in Q1 2026 (INFERRED).
- Residual mismatch: CoreWeave's June 2026 wording has part of the remaining 393 MW arriving in 2026, while Galaxy has phase II starting Q2 2027.

**The other disclosure (355 MW undelivered at 2026-06-30, cost-based rent, 2026-2028) could not be matched to named sites.** The 10-Q says several leases, with developer and operator lessors that are VIEs. Candidates consistent with that description are the Kenilworth JV lease (rent "based on a percentage of construction costs incurred" [P]) and the Blue Owl / Chirisa / PowerHouse build-to-suits in Virginia and Pennsylvania [S]. No source ties the 355 MW to any of them.

### Kenilworth, NJ (NEST 11)

- coreweave.com project page [P]: "CoreWeave is investing $1.8B to redevelop a former pharmaceutical research facility at 2000 Galloping Hill Road into NEST 11". "NEST 11 has a planned 40 MW load, supported by the new electrical infrastructure funded by CoreWeave." "CoreWeave is funding approximately $150 million in new electrical infrastructure, including a new substation." "The cooling system is a closed loop."
  https://www.coreweave.com/ai-data-center-development/kenilworth-new-jersey
- Q2 2025 release [P]: "Developing, as part of a joint venture, a new data center campus in Kenilworth, NJ, with capacity of up to 250MW. This marks CoreWeave's first greenfield purpose-built AI data center project, with the initial phase expected to be delivered in 2026".
  https://www.sec.gov/Archives/edgar/data/1769628/000176962825000039/coreweave2q25earningspress.htm
- Q2 2026 10-Q [P]: "As of June 30, 2026, the Company's ownership interest was 35%." The lease with the JV "will have an initial lease term of 15 years with base rent payments that are based on a percentage of construction costs incurred." Q1 2026 10-Q [P]: guarantee of up to $95M, lease prepayment of $32M, estimated maximum construction funding exposure of up to $200M.
- [S]: construction began mid-September 2025 with operation expected "early 2027" (Real Estate NJ); building bought for $322M in Aug 2025 (DCD, NJBIZ); $555M loan and "250-megawatt development" (Commercial Property Executive); $250M state tax credit; a residents' petition against the project in April 2026 (News 12).
- DCD says the unnamed "first self-build" is thought to be Kenilworth [S]. That conflicts with the early-2027 date.

### Lancaster, PA

- Q3 2025 release [P]: "Announced intent to commit up to $6 billion to equip a state-of-the-art data center in Lancaster, Pennsylvania, with an initial 100 MW of capacity and expansion potential to 300 MW".
- Blog, July 2025 [P]: "With room to grow up to 300 MW ..." and "over 600 local construction jobs and at least 75 operational jobs".
  https://www.coreweave.com/blog/building-pennsylvania-into-the-mid-atlantic-ai-hub
- [S]: LancasterOnline (Feb 2026) reported that lenders passed on a $4B financing for the Lancaster data centers; CoreWeave replied that the facility "is fully funded, under construction, and moving forward as planned". First phase "expected to be ready by summer 2027". A residents' group appealed approval of a second phase in Aug 2026.

### International sites announced by CoreWeave (all [P], T1)

- Indonesia, 2026-08-04: "three new facilities totaling 360 megawatts of contracted IT power, expected to come online in 2028. CoreWeave will own and operate the compute environment across all three sites".
  https://www.coreweave.com/news/coreweave-expands-cloud-ai-platform-to-indonesia-marking-first-move-into-asia-pacific-region
- India, 2026-10-06: "CoreWeave plans to expand its AI Cloud platform with 240 megawatts (MW) of data center capacity in Navi Mumbai. ... three 80 MW buildings at AdaniConneX's Taloja campus. ... The first phase of the project is expected to be available in mid-2028 ... CoreWeave will be the sole tenant across the three buildings, with the opportunity to double capacity by expanding by up to 240 MW".
  https://www.coreweave.com/news/coreweave-enters-india-expanding-ai-cloud-platform-with-adaniconnex
- Denmark, 2026-10-27: "CoreWeave has brought the majority of its planned 22.5 megawatts (MW) of IT capacity online at atNorth's DEN01 data center in Copenhagen ... Accelerated by NVIDIA Blackwell systems connected with NVIDIA Quantum-X800 InfiniBand, the facility expands CoreWeave's European infrastructure footprint to nine data centers across five geographies".
  https://www.coreweave.com/news/coreweave-expands-global-ai-cloud-platform-with-new-capacity-in-denmark-and-first-ai-network-backbone
- Sweden, 2026-06-24: co-location agreement with Conapto covering "two campuses in Stockholm, with initial capacity already online at Stockholm 4 South"; "The Conapto agreement brings CoreWeave's sites in Europe to eight."
  https://www.coreweave.com/news/coreweave-partners-with-conapto-to-expand-ai-cloud-capacity-in-sweden-powered-by-renewable-energy
- UK, 2025-01-13: "The first data center utilizing NVIDIA H200 GPUs went live in October 2024 in Crawley with CoreWeave partner Digital Realty, whilst the second operational data center went live in December 2024 in London Docklands, with partner Global Switch."
  https://www.coreweave.com/news/coreweave-announces-two-initial-data-centers-in-the-uk-are-now-operational
- UK, 2025-09-16: "CoreWeave is partnering with NVIDIA and DataVita in Scotland. Together they will deploy the most advanced NVIDIA Grace Blackwell Ultra GPUs". Total UK investment £2.5B.
  https://www.coreweave.com/news/coreweave-announces-significant-commitment-to-power-uk-ai-innovation-and-growth
- Europe 2024 plan: "$2.2 billion to open up data centers in Norway, Sweden, and Spain by the end of 2025".
  https://www.coreweave.com/blog/coreweaves-european-expansion-lets-power-tomorrows-ai-innovations
- Q3 2026 release: "Broadened our international footprint to more than 1.3 GW of contracted power including India, Indonesia, and Spain". The Spanish addition is not sized anywhere I looked.

### Texas

- Q3 2026 call [P]: "within Texas specifically, the overwhelming majority of our power is either online or fully permitted and under construction."
- [S]: CoreWeave's 2026-11-07 letter to the governor-elect lists active Texas facilities in Austin, Denton, Dickens County, Plano, Richardson and Round Rock, and says CoreWeave funds substations and transmission upgrades for new sites.
- Named Texas MW: Austin ~20, Denton ~260, Dickens County 526 (133 live) = ~806 MW contracted, ~413 MW live. Plano, Richardson, Round Rock and Cedar Creek are unsized.
- [S]: Governor Abbott ordered a halt to new data-centre interconnection and permitting pending an audit (reported as 2026-08-03; Galaxy calls it a September directive). ERCOT's "Batch Zero" process classifies projects; Helios I and II are described by Galaxy as previously approved baseload [P].

### Other US sites (all [S])

- Elk Grove Village, IL: build-to-suit by a Prime Data Centers subsidiary, "fully leased to CoreWeave for 15 years", about $2.2B of revenue, two 7-year renewals; $900M five-year notes at 7.5% priced 2026-06-02 (Bloomberg, Crain's).
- Digital Drive, Chesterfield VA: ~$1.1B junk bond in Sept 2026 for a Blue Owl-sponsored data centre leased to CoreWeave; "about 76 megawatts of IT capacity"; 15-year, $2.94B contract; operations 2027-2028. Richmond BizSense (Jan 2026) describes a 200 MW two-building project at 1600 Digital Drive.
- Cheyenne, WY: Related Digital release (2025-10-07): CoreWeave "will be the anchor tenant through a long-term lease for 88 MWs of critical IT capacity"; campus up to 302 MW (a later page says 420 MW).
- Niagara Falls, NY: the Blockfusion Form 425 [P] confirms a "definitive anchor lease" with a "15-year initial term" and a companion expansion agreement, converting a 2026-06-30 LOI. The 85 MW / 300 MW figures come from DCD's report of the LOI [S].
  https://www.sec.gov/Archives/edgar/data/2097508/000118518526004075/bldc425091626.htm
- Cedar Creek, TX: county records name CoreWeave as tenant of Building 1 at EdgeConneX's campus (DCD, 2026-07-27).
- Saskatchewan: Bell's 300 MW campus announced 2026-03-16, "100% pre-sold to Cerebras and CoreWeave"; the 140 / 160 MW split is from press reports, not confirmed in Bell's own material per the search summary.

---

## (d) Reconciliation against company totals

### d1. Active power: company >1,700 MW at 2026-09-30

| Component | MW | Evidence |
|---|---|---|
| Core Scientific billing (five sites) | 485 | T2 [P] |
| Applied Digital RFS at 2026-09-30 (100 + 75) | 175 | T2 [P] / [S] for dates |
| Galaxy Helios phase I | 133 | T2 [P] |
| **Subtotal, landlord-disclosed** | **793** | |
| Denmark DEN01 ("majority" of 22.5) | ~12-22 | T1 [P] |
| Press and aggregator figures: Chester 28, Barcelona 15, Hillsboro 36 + 9, Douglasville 9, Plano 13 + 30, Volo 14 | ~154 | T3/T4 [S] |
| **Total attributed to named sites** | **~960-970** | |
| **Unexplained gap** | **~730-740 MW (~43%)** | INFERRED |

- Using only primary-verified figures (about 805-815 MW), the gap is about 885-895 MW, roughly 52% of active power.
- As of 2026-10-01 Applied Digital's RFS figure is 250 MW, which adds 75 MW to the named total.
- The gap sits in roughly 35 sites with no public MW: the UK pair, Norway, two in Sweden, the rest of Spain, Cambridge ON, Richardson, Round Rock, Las Vegas, New Jersey, Chicago and others.
- Cross-check that does not close: CoreWeave said in May 2026 that no provider delivered more than 17% of active infrastructure, yet Core Scientific was billing 225 MW at 2026-03-31 against "more than 1 GW" active (about 22% if active was exactly 1 GW). Either active power was well above 1 GW, or landlord "billing" runs ahead of CoreWeave "active".

### d2. Contracted but not active: company ~2,900 MW (>4.6 GW less >1.7 GW)

| Component | MW | Evidence |
|---|---|---|
| Core Scientific Dalton phase 2 | 105 | T2 [P] |
| Applied Digital: 75 (RFS 1 Oct) + 150 (third building) | 225 | T2 [P] |
| Galaxy Helios phases II and III | 393 | T2 [P] |
| India (Navi Mumbai) | 240 | T1 [P] |
| Indonesia | 360 | T1 [P] |
| Lancaster initial phase | 100 | T1 [P] |
| Kenilworth NEST 11 | 40 | T1 [P] |
| **Subtotal, primary-verified** | **1,463** | |
| Saskatchewan 140, Cheyenne 88, Niagara Falls 85, Digital Drive 76 (or 200) | 389 (or 513) | [S] |
| **Total attributed** | **~1,850-1,980** | |
| **Unexplained gap** | **~0.9-1.05 GW** | INFERRED |

- Unsized and so excluded: Elk Grove Village, Cedar Creek Building 1, the Chester 120 MW JV programme, DataVita Scotland, second Stockholm campus, Spanish additions.
- Whether Kenilworth and Lancaster are counted in CoreWeave's "contracted power" at 40 / 100 MW, at 250 / 300 MW, or at all is not disclosed.

### d3. Total contracted: company >4,600 MW

- Named sites across both buckets: about 2.8-2.95 GW.
- **Unexplained gap: about 1.65-1.8 GW, or 36-39% of contracted power.**
- On primary-verified figures only (about 2.27 GW), the gap is about 2.3 GW, roughly half.

### d4. International: company >1,300 MW

- Named: India 240 + Indonesia 360 + Saskatchewan 140 + Denmark 22.5 + Barcelona 15 + Álava 18 = ~796 MW.
- Gap: at least ~500 MW, spread over the UK, Norway, Sweden, the rest of Spain and Canada.

### d5. Quarterly additions to contracted power

| Quarter | Company figure | Named additions found | Unidentified |
|---|---|---|---|
| Q1 2026 | +>400 MW | Saskatchewan 140 [S]; Helios phase III 133 (INFERRED from 10-Q) | ~130+ MW |
| Q2 2026 | ~+200 MW (3.5 → 3.7 GW) | Conapto (unsized); possibly Elk Grove (timing unknown) | ~200 MW |
| Q3 2026 | +>900 MW (3.7 → 4.6 GW) | Indonesia 360; India 240 (announced 6 Oct but cited in the Q3 release); Niagara Falls 85 [S]; Cedar Creek and Spain unsized | ~215+ MW |

Whether the cancelled Poolside commitment (250 MW) was ever in contracted power, and when it came out, is not disclosed.

### d6. Pipeline: company >1,500 MW of land, options and LOIs (2026-08-11)

- Named options: India +240, Niagara Falls +215 [S], Lancaster +200, Kenilworth +210 = ~865 MW.
- Unidentified: at least ~650 MW, including the two JV development projects behind the $1.7B commitment.

---

## (e) Conflicts, and things I could not source

### Conflicts (both versions listed)

1. **Kenilworth size.** "capacity of up to 250MW" (CoreWeave Q2 2025 release, Aug 2025) vs "planned 40 MW load" for NEST 11 (coreweave.com, sitemap dated Nov 2026). Likely campus versus first building, but the company does not say so. Capex: $1.2B (2025 press [S]) vs $1.8B (company page).
2. **Kenilworth timing.** "initial phase expected to be delivered in 2026" (Aug 2025) vs "operational in early 2027" (Real Estate NJ [S]) vs CoreWeave's "first self-build site ... later this year" (Aug 2026), which DCD believes is Kenilworth [S].
3. **Helios delivery dates.** CoreWeave filings: "in 2026" (Sep 2025) → "2026 and 2027" (Dec 2025) → "2026 and 2028" (Mar and Jun 2026). Galaxy: phase II "throughout 2027" (Apr 2025 [S]) and deliveries from Q2 2027 (Oct 2026), described as on schedule. This rests on my inference that the single-site lease is Helios.
4. **Digital Drive, Virginia.** 200 MW two-building project (Richmond BizSense, Jan 2026 [S]) vs about 76 MW IT for the bond-financed facility (Bloomberg-derived, Sept 2026 [S]).
5. **Chester, VA.** 27-28 MW for CTP-01 vs 82 MW (aggregator) vs 120 MW JV programme. Probably different scopes.
6. **India option.** Company release: up to +240 MW (480 total). DCD summary: potential total 580 MW [S].
7. **Austin, TX.** 16 MW in the original 2024 report [S] vs ~20 MW in Core Scientific's decks [P].
8. **Core Scientific site count.** "six sites" (Feb 2025 release) vs five sites (2026 filings). Both are primary.
9. **Polaris Forge 1 first building.** The same 10-K says it became operational in "October 2025" in one place and "November 2025" in another.
10. **Data-centre count at YE2024.** 28 "opened" (Jan 2025 release) vs 32 operated (10-K).
11. **Denton delay cause.** Weather (WSJ [S]) vs a commentator's challenge using weather records (T4).
12. **Lancaster financing.** "Lenders passed" (LancasterOnline, Feb 2026 [S]) vs CoreWeave's "fully funded".
13. **Texas order date.** 3 August 2026 (press [S]) vs "September directive" (Galaxy call [P]). There may have been two orders.
14. **Cheyenne campus size.** 302 MW (Related release) vs 420 MW (later Related page) [S].
15. **Core Scientific share of active power.** See d1.

### Not sourced in this session

- Q1 2025 active power (the ~420 MW lead was not confirmed).
- The Q3 2026 10-Q (not yet filed in the index I saw) and the Q3 2026 slide deck (not opened).
- The share of active or contracted power that is self-built. The only statement is that all existing data centres are leased.
- The identity of the first self-build site, of the two JV projects behind the $1.7B commitment, of the 355 MW of cost-based leases, and of the 78 MW "DCSP" site.
- MW for: Crawley, London Docklands, DataVita Scotland, Bulk N01, Falun, both Conapto campuses, the Spanish sites beyond Barcelona, Cambridge ON, Richardson, Round Rock, Plano, Las Vegas, the New Jersey and Chicago regions, Elk Grove Village, Cedar Creek Building 1.
- Actual go-live dates for Norway, Falun and the Volo fuel cells.
- The Indonesian developer and exact locations.
- End customers by site, other than OpenAI at Denton [S], an unnamed hyperscaler at Helios I [P] and Cohere at Cambridge [S]. Meta, Anthropic, Microsoft, Google, Jane Street and NVIDIA capacity is not mapped to sites anywhere I looked.
- Per-site GPU counts, server OEMs, switch and optics vendors, dark-fibre providers, storage and memory suppliers. Only fleet-level statements exist.
- Utility interconnect sizes other than Helios (345 kV, up to 900 MW transformer capacity) and Kenilworth (~$150M substation).
- Any CoreWeave lease with TeraWulf, Cipher, Hut 8, IREN, Bitdeer, Crusoe, Vantage, Aligned, CyrusOne, Compass, Stream, TierPoint; any site in Germany, Italy or the Middle East beyond planned network points of presence.

---

## (f) Sources

### Opened and read in this session [P]

CoreWeave (T1)

- Q3 2026 earnings release (8-K exhibit, 2026-11-10): https://www.sec.gov/Archives/edgar/data/1769628/000176962826000461/coreweave3q26earningspress.htm
- Q2 2026 10-Q: https://www.sec.gov/Archives/edgar/data/1769628/000176962826000366/crwv-20260630.htm
- Q1 2026 10-Q: https://www.sec.gov/Archives/edgar/data/1769628/000176962826000222/crwv-20260331.htm
- FY2025 10-K: https://www.sec.gov/Archives/edgar/data/1769628/000176962826000104/crwv-20251231.htm
- Q3 2025 10-Q: https://www.sec.gov/Archives/edgar/data/1769628/000176962825000062/crwv-20250930.htm
- Earnings releases: Q2 2025 https://www.sec.gov/Archives/edgar/data/1769628/000176962825000039/coreweave2q25earningspress.htm ; Q3 2025 https://www.sec.gov/Archives/edgar/data/1769628/000176962825000059/coreweave3q25earningspress.htm ; Q4 2025 https://www.sec.gov/Archives/edgar/data/1769628/000176962826000094/coreweave4q25earningspress.htm ; Q1 2026 https://www.sec.gov/Archives/edgar/data/1769628/000176962826000220/coreweave1q26earningspress.htm ; Q2 2026 https://www.sec.gov/Archives/edgar/data/1769628/000176962826000362/coreweave2q26earningspress.htm
- 8-K filed 2026-01-02 (DDTL 3.0 amendment): https://www.sec.gov/Archives/edgar/data/1769628/000176962826000003/crwv-20251231.htm
- Other 2025-09 to 2026-09 8-Ks (financings; no site detail)
- XBRL company facts: https://data.sec.gov/api/xbrl/companyfacts/CIK0001769628.json ; filing index: https://data.sec.gov/submissions/CIK0001769628.json
- Call transcripts (Motley Fool): Q3 2026 https://www.fool.com/earnings/call-transcripts/2026/11/10/coreweave-crwv-q3-2026-earnings-call-transcript/ ; Q2 2026 https://www.fool.com/earnings/call-transcripts/2026/08/18/coreweave-crwv-q2-2026-earnings-call-transcript/ ; Q1 2026 https://www.fool.com/earnings/call-transcripts/2026/05/08/coreweave-crwv-q1-2026-earnings-transcript/ ; Q4 2025 https://www.fool.com/earnings/call-transcripts/2026/02/27/coreweave-crwv-q4-2025-earnings-call-transcript/
- coreweave.com: /ai-data-centers ; /ai-data-center-development/kenilworth-new-jersey ; /blog/building-pennsylvania-into-the-mid-atlantic-ai-hub ; /blog/coreweaves-european-expansion-lets-power-tomorrows-ai-innovations ; /blog/coreweave-builds-the-first-global-backbone-network-purpose-built-for-ai ; /blog/our-capacity-plans-for-coreweave-data-centers ; /blog/coreweave-data-center-operations-built-for-ai ; /blog/the-data-center-questions-everyone-is-asking-answered ; /blog/coreweave-leads-the-way-with-first-nvidia-gb300-nvl72-deployment ; /blog/what-it-takes-to-bring-up-a-multi-rack-nvidia-vera-rubin-nvl72-cluster ; /blog/liquid-cooled-switching-doubles-ai-network-bandwidth-per-rack
- coreweave.com/news: India (AdaniConneX), Indonesia, Denmark and backbone, Conapto Sweden, two UK releases, NVIDIA collaboration (2026-01-26), first GB300 deployment (2025-07-03), Vera Rubin with Cognition (2026-09-30), Solidigm (2026-08-05), Meta $21B (2026-04-09), Anthropic (2026-04-10). Full URLs are in section (c) for the site-specific ones; the rest follow the pattern https://www.coreweave.com/news/<slug>.

Counterparties (T2)

- Core Scientific 10-Q, 2026-09-30: https://www.sec.gov/Archives/edgar/data/1839341/000183934126000030/core-20260930.htm
- Core Scientific Q3 FY26 deck: https://www.sec.gov/Archives/edgar/data/1839341/000183934126000028/q3fy26earningsdeckvfinal.htm
- Core Scientific Q4 FY25 deck: https://www.sec.gov/Archives/edgar/data/1839341/000162828026013214/q4fy25earningsdeckvfinal.htm
- Core Scientific release, 2025-02-26: https://www.sec.gov/Archives/edgar/data/1839341/000162828025008312/ex991-coreweavepressrelease.htm
- Core Scientific Q3 2026 call: https://www.fool.com/earnings/call-transcripts/2026/11/05/core-scientific-corz-q3-2026-earnings-call-transcript/
- Applied Digital FY2026 10-K: https://www.sec.gov/Archives/edgar/data/1144879/000114487926000048/apld-20260531.htm
- Applied Digital releases: https://www.sec.gov/Archives/edgar/data/1144879/000164117225013199/ex99-2.htm ; https://www.sec.gov/Archives/edgar/data/1144879/000149315225012458/ex99-1.htm
- Applied Digital fiscal Q1 2027 call: https://www.fool.com/earnings/call-transcripts/2026/10/08/applied-digital-apld-q1-2027-earnings-call-transcript/
- Galaxy Q3 2026 presentation: https://www.sec.gov/Archives/edgar/data/1859392/000185939226000108/exhibit992-glxyq32026ove.htm
- Galaxy Q3 2026 call: https://www.fool.com/earnings/call-transcripts/2026/10/27/galaxy-digital-glxy-q3-2026-earnings-call-transcript/
- Blockfusion / Blue Acquisition Form 425, 2026-09-16: https://www.sec.gov/Archives/edgar/data/2097508/000118518526004075/bldc425091626.htm

### Seen only as search results [S] (not opened)

- CoreWeave Q3 2026 deck: https://s205.q4cdn.com/133937190/files/content_files/CoreWeave-3Q26-Earnings-Presentation-Final.pdf
- DCD: Q3 2025 results https://www.datacenterdynamics.com/en/news/coreweave-q3-earnings-show-revenue-backlog-doubled-to-556bn/ ; Denton GPUs https://www.datacenterdynamics.com/en/news/coreweave-deploys-16000-gpus-at-delayed-data-center-in-denton-texas/ ; Poolside https://www.datacenterdynamics.com/en/news/poolside-seeks-partners-for-data-center-in-texas-after-coreweave-deal-falls-apart/ ; Cedar Creek https://www.datacenterdynamics.com/en/news/coreweave-to-lease-capacity-from-edgeconnex-at-data-center-campus-in-cedar-creek-texas/ ; Blockfusion https://www.datacenterdynamics.com/en/news/blockfusion-signs-coreweave-as-a-customer-in-niagara-falls-new-york/ ; Bell Saskatchewan https://www.datacenterdynamics.com/en/news/canadas-bell-announces-300mw-data-center-campus-in-saskatchewan-names-coreweave-cerebras-as-customers/ ; Cheyenne https://www.datacenterdynamics.com/en/news/related-digital-breaks-ground-on-12bn-data-center-in-cheyenne-wyoming-will-host-coreweave-servers/ ; Blue Owl JV https://www.datacenterdynamics.com/en/news/blue-owl-chirisa-and-powerhouse-announce-5bn-data-center-jv-for-coreweave/ ; Kenilworth purchase https://www.datacenterdynamics.com/en/news/coreweave-acquires-nest-data-center-for-322m-at-life-sciences-campus-in-new-jersey/ ; Merlin Edged Barcelona https://www.datacenterdynamics.com/en/news/merlin-edged-launches-barcelona-data-center-coreweave-to-take-15mw/ ; India https://www.datacenterdynamics.com/en/news/coreweave-teams-up-with-adaniconnex-for-ai-cloud-region-in-india/ ; Denmark https://www.datacenterdynamics.com/en/news/coreweave-leasing-225mw-from-atnorth-data-center-in-denmark/ ; DataVita https://www.datacenterdynamics.com/en/news/coreweave-plans-15bn-uk-ai-data-center-investment-will-deploy-nvidia-gpus-at-scotlands-datavita-data-center/ ; EcoDataCenter https://www.datacenterdynamics.com/en/news/coreweave-to-deploy-nvidia-blackwell-gpu-clusters-at-ecodatacenter-in-sweden/ ; Chirisa loan https://www.datacenterdynamics.com/en/news/chirisa-secures-200-million-loan-to-fit-out-virginia-data-center-for-coreweave/
- Bloomberg: Elk Grove bond https://www.bloomberg.com/news/articles/2026-06-02/coreweave-tied-data-center-raises-900-million-in-junk-bond-sale ; Blue Owl bond https://www.bloomberg.com/news/articles/2026-09-21/coreweave-tied-data-center-project-kicks-off-junk-bond-offering ; Texas letter https://www.bloomberg.com/news/articles/2026-11-07/coreweave-asks-texas-governor-elect-for-data-center-cooperation ; Saskatchewan https://www.bloomberg.com/news/articles/2026-03-16/coreweave-bce-to-back-large-data-center-in-western-canada
- Crain's Chicago: https://www.chicagobusiness.com/news/ccb-coreweave-bond-sale-elk-grove-20260602/
- The Information (Denton milestone): https://www.theinformation.com/briefings/coreweave-hits-first-data-center-milestone-texas-internal-message-shows
- WSJ via Yahoo (Denton weather): https://finance.yahoo.com/news/summer-weather-delayed-coreweave-denton-161453750.html
- LancasterOnline: https://lancasteronline.com/business/local_business/lenders-passed-on-financing-for-lancaster-city-data-centers-report/article_cf4631fa-288f-43ef-adf8-d21b63da5d9b.html
- Real Estate NJ (Kenilworth): https://re-nj.com/coreweave-begins-1-8-billion-data-center-project-in-kenilworth-landing-first-award-under-new-eda-tax-credit-program/
- Commercial Property Executive (Kenilworth loan): https://www.commercialsearch.com/news/exclusive-coreweave-lands-555m-for-1-8b-new-jersey-project/
- Richmond BizSense (Digital Drive): https://richmondbizsense.com/2026/01/05/two-new-data-centers-to-rise-on-formerly-stalled-cartograf-site-in-chesterfield/
- Related Digital release: https://www.related.com/press-releases/2025-10-07/related-digital-breaks-ground-302-mw-data-center-campus-cheyenne-wyoming
- BCE: https://www.bce.ca/news-and-media/newsroom?article=bell-ai-fabric-expands-national-network-with-300-mw-data-centre-in-saskatchewan
- Applied Digital release (second building): https://www.globenewswire.com/news-release/2026/07/01/3320913/0/en/Applied-Digital-Delivers-Second-Building-at-Polaris-Forge-1.html ; fiscal Q1 2027 results https://www.globenewswire.com/news-release/2026/10/07/3376854/0/en/applied-digital-reports-fiscal-first-quarter-2027-results.html
- Galaxy: phase I completion https://www.prnewswire.com/news-releases/galaxy-completes-phase-i-of-its-helios-data-center-campus-delivering-133-megawatts-of-critical-it-load-to-coreweave-302818664.html ; April 2025 commitment https://www.galaxy.com/newsroom/galaxy-announces-commitment-with-coreweave
- Core Scientific Oct 30, 2025 investor update: https://d1io3yog0oux5.cloudfront.net/_adcf01b98407e90f46511945a1635315/corescientific/db/1061/11262/presentation/Core+Scientific+Investor+Update+Presentation+FINAL.pdf ; merger termination https://www.businesswire.com/news/home/20251030641010/en/Core-Scientific-Announces-Termination-of-Merger-Agreement-with-CoreWeave
- Bulk Infrastructure: https://bulkinfrastructure.com/newsroom/coreweave-partners-with-bulk-infrastructure
- Microgrid Knowledge (Bloom, Volo): https://www.microgridknowledge.com/data-center-microgrids/article/55126611/bloom-energy-bringing-fuel-cell-power-to-coreweave-data-center-project-in-illinoi
- El Economista (Merlin, Álava): https://www.eleconomista.es/vivienda-inmobiliario/noticias/13362523/05/25/el-gigante-de-la-ia-aterriza-en-espana-coreweave-elige-los-data-center-de-merlin-en-barcelona-y-alava.html
- Texas letter coverage: https://thenextweb.com/news/coreweave-texas-hinojosa-data-centre-letter ; https://cryptobriefing.com/coreweave-self-fund-texas-data-center-costs/
- Aggregators (T4): https://dgtlinfra.com/coreweave-data-center-locations/ ; https://baxtel.com/data-centers/coreweave ; https://globaldatacenters.net/project/coreweave-chester-va-chester-virginia/ ; https://epoch.ai/data/ai-data-centers/directory/coreweave-lancaster-greenfield-site ; https://fourweekmba.com/ai-two-texas-sites-hold-786-mw-of-coreweaves-4-2-gw-contracted/
