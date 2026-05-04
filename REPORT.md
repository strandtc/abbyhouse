# Due-Diligence Report: 2980 Budd Road, Stockbridge, MI 49285

**Prepared 2026-05-03** for the buyer's family. The buyer (your daughter) has an accepted offer; inspection contingency expires within ~7 days.

Each fact is tagged **[Confirmed]** (primary public-records source verified by hand), **[Likely]** (strong indirect evidence, but verify), or **[Assumption]** (analyst inference — please verify before relying on it).

Saved artifacts (PDFs, deed-index summary) are in `/Users/strandtc/dev/abbyhouse/property-records/` — see `INDEX.md` for the file list.

---

## Update — 2026-05-04 chrome browser portal sweep

I drove all the JS-heavy portals via chrome browser automation. Material new findings:
- **Clear Sky Trust filed a landlord-tenant eviction in Ingham 55th District (case 2024-241430LT-LT, BLAYS, 4/5/2024, CLOSED).** Confirms Trust acts as landlord, not just flipper.
- **MITTEN REI LLC filed a landlord-tenant eviction in Ingham 55th District (case 2025-25-04906-LT, JOHNSTON, 10/24/2025, CLOSED) — *AFTER* the LLC was supposedly dissolved 3/1/2024.** Either the dissolution data is wrong, the LLC was reinstated, or someone filed in the name of a dissolved entity. **Title company must reconcile current LLC status.**
- **No Ingham 30th Circuit civil cases** found for Clear Sky Trust, Mitten REI, or Hawkins Robert.
- **The "Eric David Snyder" identity match is now WEAKER**: LARA's current public licensee search shows only one Eric David Snyder, and his licenses are *medical* (Doctor + Drug Control + Controlled Substance — all active). No Eric Snyder shows any builder/contractor license. The 2019-suspended roofer license-holder may be a third Eric David Snyder, OR may simply be off the public list; either way the link to the Trust trustee is unconfirmed.
- **EGLE MPART PFAS:** **0 sites or Areas of Interest within 10 miles** of the parcel (queried API directly).
- **EGLE Water Well Viewer:** **0 UST / LUST / Part 201 / landfill / hazardous-waste sites within ~1 mile** of the parcel.
- **Ingham Equalization GIS:** parcel + owner confirmed (CLEAR SKY TRUST, 2980 BUDD RD, 33-16-16-04-400-023).

These results are folded into the relevant sections below; this block summarizes the deltas vs. the original report.

## Headline — five things to do today

1. **🚨 Verify the 2026 tax-foreclosure was redeemed for *this specific parcel*.** [Confirmed risk; resolution Likely] The parcel was on Ingham County's 2025 Tax Insert (legal show-cause publication) with **$7,800.17 delinquent**. Both **CLEAR SKY TRUST** and **ROBERT L HAWKINS TRUST** were noticed. Show-cause hearing was 2/12/2026, judicial-foreclosure hearing 2/19/2026, absolute foreclosure date 3/31/2026. A "Redemption of Notice of Forfeiture" recorded 1/16/2026 (document #2026-001338) shows Clear Sky Trust paying exactly $7,800.17 to the Treasurer — strong dollar-match evidence the redemption covers this parcel, but the recorded image is "Multiple Legals: See Record". **The title company must pull doc 2026-001338 (~$10) and confirm parcel 33-16-16-04-400-023 is in its legal description.** If not, title vested in the County 3/31/2026 and Clear Sky Trust cannot legally convey.
2. **🚨 The seller has serious credibility flags that warrant deeper title and inspection scrutiny.** [Likely] The trust's likely principal — **Eric David Snyder** (Snyder's Roofing LLC / All American Remodeling) — had Michigan **building/contracting licenses suspended** by LARA in May 2019 for failing to comply with consent orders relating to homeowner complaints (no permits, didn't follow manufacturer instructions on a metal-roof install, $1,000 fine + $1,044 restitution unpaid). The affiliated wholesale entity **MITTEN REI LLC** that touched this property was dissolved 3/1/2024. The trust shows a **chronic pattern of tax delinquencies** on its inventory. The renovation work on this property — including the new metal roof — must be inspected with the assumption that a licensed builder may not have done it correctly. (Identity match between Eric David Snyder of Snyder's Roofing and Eric Snyder TR of Clear Sky Trust is strong but not 100%-confirmed; see Section 2.4 below.)
3. **🚨 Confirm the $67,500 seller-financed mortgage to the Hawkins Trust has been discharged.** [Confirmed exists; status unverified] On 8/29/2022 Clear Sky Trust gave the Hawkins Trust a $67,500 mortgage as part of seller-financing (doc #2022-032386). I did not find a recorded discharge. Title company must confirm a discharge exists or arrange payoff at closing.
4. **Order radon, full water-quality (especially arsenic), and septic inspections.** Ingham County is **EPA Radon Zone 2** AND among Michigan's worst counties for natural arsenic in well water. Well is 281 ft deep into bedrock, drilled 1980. See Section 7 for the full test list.
5. **Phone Stockbridge Township building department** at **(517) 851-9362** to ask whether permits were issued for the furnace, roof, electrical, and plumbing work performed since August 2022. There is no online portal. If the work was unpermitted, that's an insurance, lender, and resale-value problem.

---

## Section 1 — Property identification

| Field | Value | Source |
|---|---|---|
| Address | 2980 Budd Road, Stockbridge, MI 49285 | listing |
| County | Ingham | [Confirmed] BS&A, Ingham GIS |
| Township | Stockbridge Township | [Confirmed] BS&A |
| Parcel ID | **33-16-16-04-400-023** | [Confirmed] BS&A, Brick Built listing |
| Latitude / Longitude | 42.499168, −84.200343 | [Confirmed] FEMA MSC pin |
| Section / T-R | Section 4 of Stockbridge Township | [Confirmed] Wellogic + parcel format |
| Lot size | 1.68 acres (400×183) | [Confirmed] listing |
| Year built | 1860 | [Confirmed] listing, Spokeo |
| Square feet | 1,700 (Spokeo says 1,786) | [Confirmed] listing |
| Beds / baths | 4 / 2 | [Confirmed] listing |
| Foundation | Stone, with crawl space + Michigan basement (partial) | [Confirmed] listing |
| Roof | Metal (recently replaced) | [Confirmed] listing |
| Heating | Forced air, **new furnace January 2026** | [Confirmed] listing |
| Water | Private well | [Confirmed] listing + Wellogic |
| Sewer | Septic tank | [Confirmed] listing |
| School district | Stockbridge Community Schools (Emma Smith Elementary) | [Confirmed] listing |
| 2025 property taxes | $5,607 | [Confirmed] listing (BS&A details paywalled) |

Listing sources: [Brick Built (MLS 26006743)](https://brickbuiltrealestate.com/listing-detail/1177882013/2980-Budd-Road-Stockbridge-MI) ; [Zillow](https://www.zillow.com/homedetails/2980-Budd-Rd-Stockbridge-MI-49285/74031386_zpid/).

---

## Section 2 — Ownership chain & seller-entity background research

### 2.1 Current owner — CLEAR SKY TRUST [Confirmed]

- BS&A Stockbridge Township shows current owner of record: **CLEAR SKY TRUST**.
- The trustees are **Eric Snyder ("SNYDER ERIC TR")** and **Linda Snyder ("SNYDER LINDA TR" / "SNYDER LINDA COTRUSTEE")**.
- **Benjamin Ford** ("FORD BENJAMIN INDV") appears as a named third party on multiple Clear Sky Trust certifications recorded with the Ingham County Register of Deeds.
- Clear Sky Trust appears **35 times** in the Ingham deed-index search alone (since 2022). It buys via quitclaim from estates and other distressed sellers (often through affiliated wholesale entity **MITTEN REI LLC**) and conveys out via warranty deed at retail prices — a high-volume **fix-and-flip operation**. Sale prices to retail buyers in this index range from $20,000 to $104,300; the 2980 Budd Road sale price is the highest yet ($284,900 listed).
- Trusts in Michigan are not registered with LARA — there is no public corporate filing for "Clear Sky Trust" itself (only its real-estate recordings).

Sources: [BS&A Stockbridge Township](https://bsaonline.com/?uid=650) ; [Ingham Fidlar Direct Search](https://rep2laredo.fidlar.com/MIIngham/DirectSearch/) (free index — full table in `deed_index_findings.md`).

### 2.2 MITTEN REI LLC — affiliated wholesale entity [Confirmed]

- **Michigan ID 802351231**
- **Formed 8/8/2019** (right around the time Eric David Snyder's contractor licenses were being suspended; see 2.4 below)
- **Dissolved 3/1/2024** — MITTEN REI is no longer an active entity
- **Registered agent: Jeshua T. Lauka**, attorney at **David, Wierenga & Lauka, P.C., 99 Monroe Ave NW, Suite 1210, Grand Rapids MI 49503**, phone 616-454-3883
- **Business/mailing address: not on file** (an "address-of-convenience" using the attorney's office)
- **Members/managers not publicly disclosed** (Michigan LLCs aren't required to disclose them on the corporate filing)

Lauka is a Business / Real Estate / Estate-Planning attorney at David, Wierenga & Lauka P.C. He is almost certainly the lawyer who structured both MITTEN REI LLC and CLEAR SKY TRUST for the Snyders. The same firm address being used as the registered-agent address for both entities is consistent with this.

Sources: [michigan-company.com profile of MITTEN REI LLC](https://michigan-company.com/co/mitten-rei-llc) ; [Jeshua Lauka bio at DWL Law](https://www.dwlawpc.com/Bio/JeshuaLauka.html) ; [Jeshua Lauka — Super Lawyers profile](https://profiles.superlawyers.com/michigan/grand-rapids/lawyer/jeshua-t-lauka/72c31d65-472b-4fbd-8d13-e7bf78aa300f.html).

### 2.3 CLEAR SKY ADVISERS LLC — likely UNRELATED to your seller [Likely]

A separate LLC named **CLEAR SKY ADVISERS LLC** exists in Michigan (MI ID 802522023, formed 9/17/2020, address 4482 Buteo Drive Traverse City MI 49684), but **after deeper research this entity appears to be a different business — an SEC-registered investment-adviser firm (CRD 311751) with partners Omar Khawaja and William Carapucci, not the Snyder operation.** The Buteo Drive address is a residential 3BR/4BA condo built 2003 in Garfield Township, Grand Traverse County. Disregard this entity for purposes of the Clear Sky Trust due diligence. (Sources: [Clear Sky Advisers SEC](https://adviserinfo.sec.gov/firm/summary/311751) ; [Buteo Dr addresses](https://www.spokeo.com/Buteo+Dr+Traverse+City+MI+addresses) ; [michigan-company.com](https://michigan-company.com/co/clear-sky-advisers-llc).)

### 2.3a SNYDER'S REAL-ESTATE LLC — possibly successor entity [Likely]

A separate Michigan LLC, **SNYDER'S REAL-ESTATE LLC** (MI ID 803202778), was formed **4/19/2024** — just 7 weeks after MITTEN REI LLC was dissolved (3/1/2024). Status is **already inactive**. This may be a short-lived successor entity to Mitten REI. Members/organizer not publicly disclosed. Source: [michigan-company.com](https://michigan-company.com/co/snyder-s-real-estate-llc).

### 2.4 Eric David Snyder — possible builder-license history [Likely; not 100% confirmed]

This is the critical question for the buyer. **The likely principal of Clear Sky Trust appears to be Eric David Snyder, a former licensed Michigan residential builder and roofer who lost his licenses in 2018-2019.**

Confirmed facts about Eric David Snyder of Grand Rapids/Greenville:

- **5/24/2018:** licenses for All American Remodeling Inc. and Eric David Snyder were **suspended** by Michigan LARA's Bureau of Construction Codes for **failure to comply with a consent order**.
- The consent order arose from **two separate homeowner complaints** alleging:
  - Failed to include license information on the contract (Occupational Code violation)
  - Failed to obtain a building permit before starting work (Michigan Residential Code violation)
  - On a metal-roof install: "did not follow the manufacturer instructions on installing the roof covering and the flashing" — directly relevant since this property has a "new metal roof" claimed by the listing.
- Consent order required **$1,000 fine + $1,044.60 restitution to the City of Grand Rapids** within 60 days. **Snyder did not pay** — that's why licenses were suspended.
- **5/21/2019:** LARA additionally suspended **Snyder's Roofing LLC** in Grand Rapids (Eric David Snyder, qualifying officer) and **Eric David Snyder dba Snyder Roofing** in Greenville for the same non-compliance.
- A separate but related individual, **John Frederick Snyder** (owner of Snyder's Roofing), pleaded guilty to **federal tax evasion** in June 2018 for the 2011 tax year and admitted underreporting income by **over $6 million** for 2009–2014. Sentenced to prison October 2018.

Whether the Eric David Snyder of the LARA action is the same Eric Snyder TR of Clear Sky Trust:

- **Strong circumstantial evidence (all five point to "yes"):**
  - Both operate in Michigan residential construction / remodel / fix-and-flip.
  - MITTEN REI LLC's registered agent is in Grand Rapids — Snyder's home base.
  - The Clear Sky Trust pattern (acquire distressed property → renovate → resell) is exactly what someone with builder/roofer experience would do, and exactly the niche Snyder's prior businesses occupied.
  - Time fit: licenses suspended May 2019; MITTEN REI LLC formed August 2019 — three months later.
  - **Public-records aggregator (ClustrMaps) shows "Eric D Snyder" co-residing with "Linda Agnes Snyder"** at addresses including **10700 Morgan Mills Rd NE, Greenville MI** (matching the Greenville location of Snyder Roofing) and **4245 W Jolly Rd, Lansing MI**. The Trust's two named trustees are Eric Snyder TR and Linda Snyder TR — the names match. (Source: [ClustrMaps Eric Snyder MI](https://clustrmaps.com/persons/Eric-Snyder/Michigan).)
- **Open verification items (cannot 100%-confirm without):**
  - Pulling the Tapestry image of any Clear Sky Trust deed to see Eric Snyder's signing address.
  - LARA "Verify a License" public search at https://aca-prod.accela.com/MILARA/Default.aspx to confirm Eric David Snyder's current contractor-license status.
  - Court records search (MiCOURT statewide + Ingham CourtRecordSearch) — these are JS-rendered and not web-indexed, so the lack of search-engine hits does NOT mean a clean record. Title company should run names through these portals manually.

Recommend the buyer **assume identity match** for purposes of due diligence (i.e., scrutinize the renovation work as if done by an unlicensed contractor with prior code-violation history) until confirmed otherwise.

Sources: [LARA news release](https://www.michigan.gov/lara/news-releases/2019/05/21/lara-suspends-building-and-contracting-licenses-connected-to-eric-david-snyder) ; [Fox 17](https://www.fox17online.com/2019/05/21/state-suspends-license-of-grand-rapids-roofer) ; [WOOD-TV](https://www.woodtv.com/news/grand-rapids/state-suspends-w-mi-contractors-license/) ; [JLC Online](https://www.jlconline.com/business/michigan-suspends-roofing-contractors-license_c) ; [DOJ press release: John Frederick Snyder guilty plea](https://www.justice.gov/usao-wdmi/pr/2018_0621_Snyder) ; [DOJ press release: John Frederick Snyder sentenced](https://www.justice.gov/usao-wdmi/pr/2018_1019_Snyder) ; [BBB Snyder's Roofing Greenville](https://www.bbb.org/us/mi/greenville/profile/roofing-contractors/snyders-roofing-0372-17001510) ; [BBB All American Remodeling Inc.](https://www.bbb.org/us/mi/walker/profile/remodeling/all-american-remodeling-inc-0372-38142235).

### 2.5 How Clear Sky acquired the property — *not* a tax auction [Confirmed]

Despite chronic tax delinquencies, the original acquisition was **not** through an Ingham County tax-foreclosure auction. (I downloaded all available 2022, 2023, and 2024 auction-result PDFs and grep'd for the parcel and "Hawkins" — no matches.) It was a **probate-flip** orchestrated through MITTEN REI LLC:

| Doc # | Date | Type | From → To | $ |
|---|---|---|---|---|
| 2022-024562 | 6/22/2022 | **Death Certificate** | HAWKINS ROBERT LEE (notes: "DIVORCED") | — |
| 2022-026514 | 7/11/2022 | Letters of Authority for Personal Rep | HAWKINS ROBERT LEE EST | — |
| 2022-028216 | 7/25/2022 | Personal Rep Deed | Hawkins Estate → MITTEN REI LLC (Snyder Eric P3) | — |
| 2022-032382 | 8/29/2022 | Quit Claim | MITTEN REI LLC → Hawkins Estate (curative) | — |
| 2022-032383 | 8/29/2022 | Quit Claim | Hawkins Estate → HAWKINS ROBERT L TRUST | — |
| 2022-032384 | 8/29/2022 | Trust certification | Hawkins Robert L Trust (R L Hawkins II + Charles successor co-trustee, Donahue J III) | — |
| **2022-032385** | **8/29/2022** | **Warranty Deed** | **HAWKINS ROBERT L TRUST → CLEAR SKY TRUST** | **$75,000** |
| 2022-032386 | 8/29/2022 | Mortgage | CLEAR SKY TRUST → HAWKINS ROBERT L TRUST (seller-financed) | $67,500 |
| 2022-034266 | 9/15/2022 | Redemption of Forfeiture | Ingham Treasurer (paid by Hawkins Robert L) | $1,535.87 |

Robert Lee Hawkins died ~mid-2022; his son Robert L Hawkins II opened probate and acted as Personal Representative. The estate sold to MITTEN REI LLC on 7/25/2022. On 8/29/2022 the chain was reshuffled (Mitten REI quitclaimed back to estate → estate to the Hawkins Trust → warranty deed to Clear Sky Trust at $75,000) — likely a curative chain to clean up some defect Lauka found on the original Mitten REI deed. **The Hawkins Trust held back $67,500 in seller-financing**, which is unusual; it suggests the estate or Donahue (the Hawkins family attorney) wanted some assurance the property would be properly resold.

**Hawkins family attorney: John J. Donahue III** [Confirmed] — Michigan State Bar #41700, admitted 1988, **estate-planning / elder-law solo** at 23411 Jefferson Ave, St. Clair Shores MI 48080, phone (586) 779-5539. He's named as a third party on the trust certification (doc 2022-032384). His SE Michigan elder-law practice is consistent with handling the Hawkins family's estate plan. *This means the Hawkins side had professional representation in the transaction* — a positive signal for chain-of-title cleanliness on that side. Sources: [Avvo profile](https://www.avvo.com/attorneys/48080-mi-john-donahue-737471.html) ; [Justia profile](https://lawyers.justia.com/lawyer/john-j-donahue-iii-715441) ; [LinkedIn](https://www.linkedin.com/in/jodonahue/).

**Profit-margin signal:** $75,000 acquired 8/2022 → $284,900 listed (down from $319,900). Even with $80–120k in renovations claimed by the listing, this is a **high-margin flip**; combined with the seller's principal's licensing history, the buyer should treat the renovation work with skepticism until inspected.

### 2.6 Clear Sky Trust's tax-delinquency pattern [Confirmed]

Clear Sky Trust has appeared in 35+ recordings in Ingham County alone since 2022. The Fidlar deed index shows:

- Multiple "NOTICE OF FORFEITURE" events recorded against the trust in 2024 and 2025 (covering different parcels)
- Multiple "REDEMPTION OF NOTICE OF FORFEITURE" events in 2023, 2024, 2025, and 2026 (paying off delinquencies)
- This is a chronic operational pattern — not a one-off.

For this parcel specifically, the parcel-level $7,800.17 delinquency was redeemed (likely) on 12/29/2025. **Title company must verify**.

### 2.7 Court-records findings (manual portal search)

I drove the Michigan court portals directly via chrome browser automation. Findings:

**Clear Sky Trust (Ingham 55th District Court — Mason):**
- **Case 2024-241430LT-LT — CLEAR SKY TRUST V BLAYS — filed 4/5/2024 — CLOSED — Landlord-Tenant (eviction).** Clear Sky Trust = plaintiff. [Confirmed]

**MITTEN REI LLC (Ingham 55th District Court — Mason):**
- **Case 2025-25-04906-LT — MITTEN REI, LLC V JOHNSTON — filed 10/24/2025 — CLOSED — Landlord-Tenant (eviction).** Mitten REI = plaintiff. [Confirmed]
- **Important:** This eviction was filed 10/24/2025, **AFTER MITTEN REI LLC was supposedly dissolved on 3/1/2024** (per the michigan-company.com record). Possible explanations: (a) the LLC was reinstated, (b) the dissolution data is inaccurate, or (c) someone filed an eviction action in the name of a dissolved entity. The title company should resolve this with current LARA filings before closing.

**Ingham 30th Circuit Court** (where civil suits >$25K go) returned **0 hits** for Clear Sky, Mitten REI, or Hawkins Robert. The Ingham Probate Court online search also returned 0 hits for "Hawkins Robert" — yet the Register of Deeds shows Letters of Authority recorded 7/11/2022 (case must exist; the search may have a name-format quirk, or the case may be in a different county). 30th Circuit civil cases would have surfaced here if they existed.

**Eric Snyder name search in Ingham 55th District** returned 7 hits — but all are for *different* people based on middle names + DOBs:
- **Eric Paul Snyder (b.1963)**: 2× Edward W Sparrow Hospital debt-collection (2020, 2021); state infraction 2025
- **Eric James-Edward Snyder (b.1990)**: 3× municipal-ordinance violations (2011-2013) — too young to be the trustee
- **Eric Snyder (no middle name)**: 1× evicted by DTN Properties (2012)
- **None show "Eric David Snyder"** (the name on the 2019 LARA suspension)

**Eric Snyder in Kent 62A District (Wyoming, MI):** 0 hits.

**Linda Snyder in Ingham 55th District:** 0 hits.

**Significant MiCOURT limitation:** Several major civil courts are **NOT** in MiCOURT's index — including Kent County 17th Circuit Court (Grand Rapids — where Snyder Roofing operated), Kent 61st District Court (Grand Rapids), and most major-city district courts. To rule out civil suits against these entities, the title company / your daughter's attorney must check **manually with the Kent County Clerk** at https://accesskent.com/ and Montcalm County (where Greenville is).

### 2.8 LARA "Verify a License" finding

I searched LARA's public licensee portal (https://aca-prod.accela.com/MILARA/) for "Eric Snyder". 14 individuals named Eric Snyder are licensed in Michigan. Notably:

- **Eric David Snyder** in LARA's *current* public search holds **only medical licenses** — Medical Doctor (#4301079409), Drug Control (#5307006594), Controlled Substance (#5315009027), all **active until 3/21/2027**.
- **No active builder, residential builder, or maintenance/alteration contractor licenses** appear under any "Eric Snyder" name.
- The 2019-suspended Eric David Snyder roofing licenses (Snyder's Roofing LLC, All American Remodeling, Inc.) **do not appear in the active licensee search**.

This raises an important question: **the "Eric David Snyder" of the 2019 LARA enforcement action may NOT be the same Eric Snyder who is trustee of Clear Sky Trust.** "Eric David Snyder" is a common Michigan name (the publicly-licensed medical doctor with the same name is unrelated to construction). The previous research agent's ClustrMaps-based identity link is now less reliable than I initially indicated. The deed image (paywalled $1 on Tapestry) would show the trustee's signing address — that's the way to confirm identity.

**Updated guidance:** Treat the 2019 LARA suspension as a *possibility* for who is behind Clear Sky Trust, not a confirmed fact. Either way, the same skepticism toward the renovation work still applies (high-margin flip + opaque trust ownership + no permit history online).

### 2.9 What I could NOT find on the seller

- **No BBB profile** for Mitten REI, Clear Sky Trust, or Clear Sky Advisers MI
- **No news hits** in MLive, Lansing State Journal, Detroit Free Press, Record-Eagle
- **No BiggerPockets, Reddit, real-estate investor forum** posts about the seller
- **No CourtListener federal cases**
- **No Michigan AG, EGLE, MSHDA, DIFS public enforcement actions**
- **No probate case** for Robert Lee Hawkins surfacing in Ingham Probate online search (despite the deed-recorded Letters of Authority)

Caveats: many Michigan civil-court portals (Kent 17th Circuit, 61st District, Detroit-area courts, PACER) are not web-indexed. For full coverage, the title company or your daughter's attorney must manually check those portals.

### 2.8 Trust transparency — separate yellow flag

LLCs and trusts in Michigan are not required to publicly disclose members/managers/beneficiaries. For Mitten REI LLC, the registered agent (Lauka) is the only public-facing person. For Clear Sky Trust, only the named trustees on each deed (Eric and Linda Snyder, occasionally with Benjamin Ford as a third party) are visible. This is **legal but opaque** — for a 35-property fix-and-flip operator, it means buyers cannot easily verify scale, capitalization, insurance coverage, prior dispute history, or beneficial ownership. Treat all renovation work as warranty-less and as if performed by an unknown contractor — because effectively it was.

---

## Section 3 — Robert Lee Hawkins (prior owner) [Confirmed]

| Fact | Source |
|---|---|
| Full legal name: HAWKINS ROBERT LEE | Death certificate doc 2022-024562 |
| Died: shortly before 6/22/2022 | Death cert recording date |
| Marital status at death: Divorced | Death cert notes |
| Successor: son Robert L Hawkins II (PR + co-trustee) | Letters of Authority + trust certification |
| Other family on trust: Charles Hawkins (successor co-trustee) | Doc 2022-032384 |
| No public obituary located | Stockbridge Community News, Caskey-Mitchell, Legacy MI, Echovita all empty |
| Earlier history: 2017 MI Treasury tax lien $8,198.41 (released 4/2022); 2002 redemption of forfeiture; multiple Farmers State Bank of Munith and Dart National Bank mortgages 1985–2001 | Fidlar Direct Search |
| Public-records databases (voterrecords.com, simplecontacts.com) showing him at "age 85/86" in 2024 | [Likely stale data] not updated for death |

Other Hawkins family at this address per public records databases: **Bernice Elaine Hawkins**, **Charles Joseph Hawkins**.

Sources: [Fidlar Direct Search (Ingham)](https://rep2laredo.fidlar.com/MIIngham/DirectSearch/) ; [voterrecords.com — Budd Road](https://voterrecords.com/street/budd+rd-stockbridge-mi/) ; [simplecontacts.com — Budd Road](https://www.simplecontacts.com/state/MI/Stockbridge/Budd-Road).

---

## Section 4 — Permits & physical condition

### 4.1 Renovations claimed by listing
"new furnace JAN 2026, flooring, drywall, lighting, paint, roof, kitchen, bathrooms, porches, new insulation, hardy wired smoke detectors."

### 4.2 Permit lookup [Action item — call required]

- **Stockbridge Township Building Department** — 125 S. Clinton Street, Stockbridge MI 49285. Mon–Fri 9:00 AM – 12:00 PM. Phone **(517) 851-9362** or alternate **(517) 851-7530**. Clerk email twpclerk@wowway.biz. **No online portal.**
- **Ingham County Community Development** also handles some permits, accessible through bsaonline.com (paywalled).
- **Action: phone Stockbridge Twp during business hours and ask for permit history on parcel 33-16-16-04-400-023 from 8/29/2022 to today.** Specifically ask:
  1. Furnace replacement permit (claimed Jan 2026)
  2. Roof replacement permit
  3. Electrical permit(s)
  4. Plumbing permit(s)
  5. Any insulation, drywall, or structural work permits
  6. Final inspection sign-offs for all of the above

If any of these are missing, that's a **major flag**. Unpermitted work can:
- Void homeowners insurance for related claims
- Be required to be removed/redone by a future buyer's lender
- Create a code-violation liability that survives the sale

Sources: [Stockbridge Township](https://www.stockbridgetownship.com/) ; [Stockbridge Township Building Department page](https://www.stockbridgetownship.com/building-department/).

### 4.3 Structural concerns — 1860 farmhouse, stone foundation, Michigan basement

The combination of a 165-year-old structure, fieldstone foundation, and Michigan basement is the highest-risk profile in residential inspection. None of the listed renovations address structure. Specific concerns:

- **Fieldstone / rubble foundation:** mortar deterioration, water infiltration, rolled stones. Structural cracks may be cosmetically pointed without underlying repair.
- **Michigan basement** (partial, often dirt or thin-slab floor): chronic moisture, mold, rodent entry, no thermal envelope, **major radon entry path**.
- **Crawl space portion:** moisture, vapor barrier integrity, joist condition above.
- **Balloon framing** (typical 1860): no fire-stops between floors; insulation rarely retrofitted properly; joists may be undersized or notched/drilled poorly for utility runs.
- **Original sills** (where wood meets stone): water/insect damage and rot common at this age.
- **Settled or sagging floors / out-of-plumb walls** common; cosmetic "leveling" with floor compound or carpet often hides structural issues.

---

## Section 5 — Environmental & health hazards

### 5.1 FEMA Flood Zone — *not* in a special flood hazard area [Confirmed]
- FIRM panel **26065C0425D**, effective **8/16/2011** (Stockbridge Township)
- Parcel pin (42.499168, −84.200343) sits in default **Zone X (minimal flood hazard)** — outside the 1% (100-year) and 0.2% (500-year) flood zones
- Zone A (riverine, no BFE determined) flood zone runs along a wetland ~1,200–1,500 ft west of the parcel
- 6 LOMR amendments + 1 revalidation since 2011; all for *other* addresses in the township
- Saved artifacts: `FEMA_FIRM_panel_26065C0425D.png` (45 MB FIRM panel image), `FEMA_FIRM_panel_26065C0425D.pgw` (georef world file), `FEMA_FIRM_panel_26065C0425D.zip` (original FEMA download), `FEMA_FIRM_README.pdf` (FEMA's generic read-me). Note: FEMA's "Download FIRM Panel" delivers a ZIP containing a PNG, not a PDF — open the .png to view the official map.

Source: [FEMA MSC](https://msc.fema.gov/portal/search?AddressQuery=2980+Budd+Road+Stockbridge+MI+49285).

### 5.2 Well — deep bedrock, drilled 1980 [Confirmed]
- **Wellogic Well ID 33000001176**: drilled **2/21/1980**, depth **281 ft**, static water level **30 ft**. Submitted by Local Health Department. Section 4 of Stockbridge Twp.
- 281 ft is consistent with a deep bedrock aquifer (likely Saginaw or Marshall sandstone)
- 46 years old — **at the high end of typical well age**. Casing typically lasts 30-60 yrs; pump and pressure tank typically 10-15 yrs (so the original 1980 pump has almost certainly been replaced — ask seller for receipts/dates)
- Neighboring wells on Budd Road range 51-285 ft (Wellogic search results saved); some neighbors have shallow ~50-72 ft wells, suggesting both aquifers are locally available
- **Action items below in Section 7.**

Source: [Michigan EGLE Wellogic — public search no login required](https://www.egle.state.mi.us/wellogic/).

### 5.3 Septic — no online record [Action item]
- Ingham County Health Department holds septic permits but they're not online. Call **(517) 887-4308**.
- For an 1860 home, the septic field could be original-era or any age since the 1970s. Sized for 4 bedrooms (matches).
- **Strongly recommend a separate septic-tank inspection** (open the tank, visually inspect, dye-test through the field) — *not* part of a standard home inspection.

### 5.4 Arsenic in well water — high regional risk [Confirmed]
- Ingham County is **among the worst counties in Michigan** for naturally-occurring arsenic in groundwater. Some Michigan counties require arsenic testing as a condition of sale.
- **EPA action level: 10 ppb.** Long-term exposure linked to bladder, lung, and kidney cancer.
- Reverse-osmosis under-sink filters ($300-600 install) handle drinking/cooking water economically if arsenic is detected.

Sources: [Michigan Public — arsenic in well water](https://www.michiganpublic.org/environment-science/2014-07-02/theres-arsenic-in-michigans-well-water-but-not-a-lot-of-people-are-talking-about-it) ; [MDHHS arsenic county data](https://www.michigan.gov/egle/-/media/Project/Websites/egle/Documents/Programs/DWEHD/Contamination-Investigation/arsenic-water-quality-maps-michigan-county.pdf).

### 5.5 Radon — Zone 2 (moderate–elevated) [Confirmed]
- EPA Radon Map: **Ingham County is Zone 2** (predicted average indoor radon 2-4 pCi/L; some homes >4 pCi/L).
- EPA action level: **4 pCi/L**. Mitigation typically $800-1,500.
- Stone foundation + Michigan basement = elevated radon-entry profile regardless of zone.
- Test method: short-term test kit ($15-30) or professional ($150). Test in lowest occupied level under closed-house conditions for 48-96 hours.

Sources: [EPA Radon Map of Michigan](https://www.epa.gov/sites/default/files/2014-08/documents/michigan.pdf) ; [Ingham County radon data](https://www.homefacts.com/radon/Michigan/Ingham-County.html).

### 5.6 Lead-based paint — assumed present [Confirmed risk]
- Federal law requires the seller to provide a **Lead-Based Paint Disclosure** for any home built before 1978. **Demand it now if not yet provided.**
- 1860 home means original interior trim, doors, windows, and exterior siding all had multiple lead-paint coats applied throughout the 19th and 20th centuries. Even if "renovated", lead is in the substrate of pre-2022 paint, in window glazing putty, in original plaster, etc.
- **For a young family, especially with children under 6:** request a lead-paint risk assessment by a state-certified Michigan Lead Risk Assessor. Search at [Complichek Environmental](https://complichek.com/) or similar.
- Test the well water for lead too (old plumbing).

### 5.7 Asbestos / vermiculite [Confirmed risk]
- Common asbestos-containing materials in 1860+ Michigan houses with later updates:
  - **Vermiculite attic insulation** (often Zonolite brand from Libby, MT mine — known asbestos-contaminated). The listing says "new insulation" — **verify whether new insulation was installed *over* old vermiculite or *after removing* it.** Removal of vermiculite is regulated abatement.
  - Pipe wrap on basement plumbing
  - Vinyl floor tile and mastic (especially 9×9" tiles pre-1980)
  - Plaster (some Michigan plasters contain asbestos fibers)
  - Old roofing felt / siding shingles
  - Boiler/furnace wraps and ducting
- Action: ask seller to disclose any abatement that was done; budget for asbestos testing of any disturbed materials ($300-500 for several samples).

Sources: [Michigan asbestos testing](https://innovativehomeinspection.com/michigan-asbestostesting) ; [LEO MIOSHA Asbestos FAQs](https://www.michigan.gov/leo/bureaus-agencies/miosha/divisions/construction-safety-and-health-division/asbestos-program/asbestos-faqs).

### 5.8 PFAS — confirmed clean within 10 miles [Confirmed]
- EGLE MPART feature service queried directly via API: both layer 0 (Areas of Interest) and layer 1 (PFAS Sites) returned **zero features within 10 statute miles** of parcel coordinates (42.499168, −84.200343).
- This is excellent news — no known PFAS contamination, no Area of Interest, no Site within 10 miles.
- Even so, recommend including PFAS in the well-water test panel as a standard precaution (~$300-500 incremental). Michigan's MCL for PFOA/PFOS has been binding since August 2020.

Source: [EGLE MPART PFAS Feature Service](https://services1.arcgis.com/FNjlrOFR0aGJ71Tg/arcgis/rest/services/Michigan_PFAS_Sites_and_Areas_of_Interest_PUBLIC_view/FeatureServer) ; [EGLE MPART PFAS GIS map](https://www.michigan.gov/egle/maps-data/mpart-pfas-gis).

### 5.9 Underground Storage Tanks (UST) and contamination — confirmed clean within ~1 mile [Confirmed]
- I drove the EGLE Water Well Viewer (https://experience.arcgis.com/experience/4af1cf3544b34411b1da781d756956e2) directly to the parcel coordinates and enabled all five environmental overlays (Part 211 USTs, Part 213 LUSTs, Part 201 contamination, Part 115 landfills, hazardous-waste TSD facilities).
- **No environmental site markers visible within ~1-mile radius of the parcel.**
- Despite the rural area being clean of registered sites, an **on-property** historic UST (e.g., a buried heating-oil tank from the 1930s-1970s) typically wouldn't appear in EGLE's database (those records are for *registered* tanks; old residential heating-oil tanks are often unregistered). The on-site inspection should still include a metal-detector sweep near the original heating-equipment location and along foundation walls.
- A leaking UST is a **major financial liability** — remediation can run $20,000+.

### 5.10 Wetlands [Likely]
- The Zone A flood area to the west indicates a wetland system / drainage. Check the **National Wetlands Inventory map** at https://fwsprimary.wim.usgs.gov/wetlands/apps/wetlands-mapper/ for parcel coordinates 42.499168, −84.200343.
- If part of the parcel is regulated wetland, EGLE Part 303 may regulate building/disturbance. For a flat farmhouse with most acreage open, this is unlikely to be a problem but worth a check.

### 5.11 Mold [Likely concern]
- Michigan basement + stone foundation + 165-year-old structure = high mold risk, regardless of recent renovation.
- Look for: musty smell, water staining on walls/joists, prior parging that hides cracks, visible mold colonies in basement crawl space.
- If detected, sample with a state-certified mold inspector ($300-500).

### 5.12 Sex offender / crime check [Recommended]
- Michigan State Police Sex Offender Registry: https://mspsor.com/Search.aspx — search by zip 49285 to confirm no registered offenders nearby.
- Crime data via Crimegrade.org or local Stockbridge Twp policing data.

---

## Section 6 — Market & financial analysis

### 6.1 Price & comparable sales
- **Stockbridge median sale price (last 12 months): $308,000, +15% YoY.** Median 41 days on market.
- **Listed at $284,900** (reduced from $319,900 — see Zillow for date).
- **Acquisition cost** to Clear Sky Trust: **$75,000** (8/29/2022).
- Implied flip margin: ~$210K minus $80-120K renovation costs = **$90-130K profit**. Typical for a fix-and-flip in this market.
- For a 1860 farmhouse with stone foundation/Michigan basement on 1.68 acres, a 10-20% discount to median is reasonable to reflect the carrying-cost overhead and unrenovated structural systems. A target of **$240,000-260,000** is consistent with comps; the accepted price your daughter has should be in that range or below to leave margin for the items the inspection is going to surface.

Source: Homes.com Stockbridge market data.

### 6.2 Michigan Proposal A tax uncap [Confirmed effect]
- In Michigan, when a property sells, the **taxable value resets** from the prior owner's capped TV to the new SEV for the year of sale.
- 2025 listed taxes: $5,607. **Post-sale 2027 taxes will likely jump significantly.** With a $284,900 sale price, the SEV will reset to ~$142,450 (approximately 50% of true cash value).
- Stockbridge Township millage rates (estimated): ~32-40 mills non-homestead, ~17-25 mills with Principal Residence Exemption claimed.
- **Estimated post-uncap annual tax:** $2,400-3,600 if claimed as principal residence (likely scenario for your daughter), or $4,500-5,700 if not.
- **Verify with Stockbridge Township Assessor** (517) 851-9362 before closing — ask for the projected 2027 SEV/TV/tax bill if she takes possession at $284,900 with Principal Residence Exemption.

### 6.3 Resale-risk factors going forward
- **+** Below-median list price for a renovated home; rural appeal is steady; school district decent.
- **+** Below-flood-zone, in a good location between Lansing and Ann Arbor.
- **−** 1860 farmhouse sells to a narrower buyer pool; resale is subject to the next inspector finding the same things you do.
- **−** Property tax uncap will surprise the next buyer too; resale comps reflect uncapped taxes.
- **−** Clear Sky Trust's pattern of chronic tax delinquencies on its inventory creates a small reputational risk for the chain of title (a buyer's title insurance underwriter may see the seller name and ask more questions).

---

## Section 7 — Inspector / inspection-vendor punch list

This is a **comprehensive** list. Pull what your daughter's home inspector would normally do, and add the items below as either separate-vendor work or as specific instructions to the inspector.

### 7.1 Standard home inspection (general)
A licensed Michigan home inspector typically covers: structure, exterior, roof, attic, plumbing, electrical, HVAC, interior, insulation, ventilation. Specifically request a **detailed written report with photos** and a **post-inspection walkthrough** with the inspector. Cost: $400-700.

### 7.2 Required separate inspections (in addition to standard)

| # | Inspection | Why specifically here | Estimated cost |
|---|---|---|---|
| 1 | **Radon test (short-term, 48-96 hr, closed-house)** | Ingham Co Zone 2; stone foundation Michigan basement is a classic entry path | $15-30 kit, $150 pro |
| 2 | **Full well-water panel:** arsenic (priority), lead, copper, nitrates, total coliform / E. coli, iron, manganese, hydrogen sulfide, hardness, pH, sodium, chloride. Add **PFAS** and **VOCs** | Ingham Co among MI's worst for arsenic; deep bedrock well; old farm + agricultural area for nitrates | $250-500 base; +$300-500 for PFAS |
| 3 | **Well system inspection:** pump age + condition, pressure tank age, casing visible above grade and not corroded, well cap is sanitary, pitless adapter not corroded, **water flow rate (gpm) under load** | 1980 well; pump definitely replaced once already; ask for receipts | $150-300 |
| 4 | **Septic tank + field inspection** (open the tank, dye test): tank age, sludge level, baffles intact, field condition, distribution box | Original septic likely 30-50 years old; renovations may have increased load | $300-500 |
| 5 | **Lead-based paint assessment** (state-certified Michigan Lead Risk Assessor) | 1860 home with multiple paint generations; if children live there | $400-700 |
| 6 | **Asbestos sampling** of any potentially-disturbed materials (attic insulation, basement pipe wrap, vinyl floor tile, plaster, boiler wrap if any) | Vermiculite + 1860+era updates likely | $300-500 for several samples |
| 7 | **Mold inspection** of Michigan basement + crawl space; sample if visible | Stone foundation + chronic-moisture basement | $300-500 |
| 8 | **Wood-destroying organism (WDO/termite) inspection** | Fieldstone foundation in soil contact; 165-year-old structure | $50-150 (often free with home inspection) |
| 9 | **Sewer scope** (if applicable; only if any portion connects to a public/shared line) | Likely septic-only, but verify | $150-300 |
| 10 | **Buried fuel-oil tank check** — metal detector around basement perimeter and outside walls; ask seller | Common on 1860 farm properties; leaks are $$$$ | included w/ inspector |
| 11 | **Boundary survey** (if last survey is old or unavailable) | 1.68-acre rural parcel; mineral-rights and easement clarity | $500-1,500 |
| 12 | **Sex offender registry / crime data check** | Standard resale-risk check | free — see Section 5.12 |

### 7.3 Specific things the home inspector should open up / probe

#### Foundation & basement
- Probe mortar between fieldstones with a pick — check for crumbling, missing mortar
- Look for water staining, mineral efflorescence, prior parging that may hide cracks
- **Sill plate** (where wood meets stone): probe with awl for rot, termite damage
- **Posts/columns** supporting first floor — confirm proper bearing and footings
- Vapor barrier in any dirt-floor crawl space
- Look up at floor joists from below for sagging, sister-joists, beam additions
- Check exterior grade and downspout discharge — does water drain *away* from foundation?

#### Framing
- Evidence of **balloon framing without fire blocks** (peek into wall voids if possible during electrical/plumbing inspection)
- Bouncy / sloping floors
- Joist notching/drilling for utility runs (1990s+ rough-ins are a frequent code issue)
- Roof framing in attic — visible water stains, sister rafters, sagging ridge

#### Plumbing
- Identify supply pipe material throughout: **galvanized steel** (old), **copper with lead solder pre-1986**, **PEX or modern copper** (updated)
- Check for active leaks under all fixtures and at the well-line entry
- Water pressure at multiple fixtures simultaneously
- Drain wastes — cast iron vs PVC vs ABS
- Hot water heater age, type (electric/propane/oil), pan/drain
- Confirm shutoffs work at every fixture

#### Electrical
- Open the panel — confirm proper bonding/grounding, no double-tapped breakers, no aluminum branch wiring, no Federal Pacific or Zinsco panels (insurance flags)
- **Trace at least 2-3 random outlets back** to confirm no abandoned active knob-and-tube
- AFCI/GFCI in required locations (kitchens, baths, basement, exterior, garage, laundry)
- Smoke / CO detectors hardwired (claimed by listing — verify)
- Service amperage adequate (100A min, 200A preferred)

#### HVAC
- New furnace: confirm it was permitted (call township per Section 4.2). Get manufacturer + serial #, AHRI certificate, warranty paperwork.
- Have inspector look at supply/return ducts — old farmhouse ducts are often undersized or leaky
- Combustion air supply, venting, condensate handling
- AC system if present — age, refrigerant type, condition
- Backup heat plan (in case furnace goes down in MI winter)

#### Roof — ESPECIALLY GIVEN SECTION 2.4
- The listing says "new metal roof". Given the seller's possible licensing history of metal-roof complaints, **scrutinize this carefully:**
  - Type (standing seam vs exposed-fastener)
  - Underlayment (synthetic vs felt; ice-and-water shield at eaves and valleys)
  - Flashing at chimney, plumbing penetrations, valleys, sidewalls
  - Snow guards (Michigan winter requirement)
  - Manufacturer's installation instructions followed (the prior LARA case specifically alleged Snyder did NOT follow manufacturer instructions)
  - Manufacturer warranty paperwork and registration
  - Permit number and final inspection sign-off

#### Windows
- "Insulated" windows claimed — confirm which were actually replaced vs. left original
- Sash condition on any remaining originals (lead-paint glazing concern)

#### Exterior
- Vinyl siding installation (claimed) — j-channels, flashings, weep holes
- Original siding underneath (asbestos shingles, cedar, etc.)
- Foundation grade and drainage
- Outbuildings — including detached garage; wiring is often unpermitted

#### Other
- **Chimney(s):** original masonry probably present. Have flue scoped if any wood-burning intention
- **Gutters and downspouts** — especially with new metal roof, drainage paths matter
- **Driveway encroachments**, shared easements, and right-of-way clarity

---

## Section 8 — Title company punch list (exceptions to clear)

These are the specific recorded documents the title company should pull, verify, and clear before closing. Ask the title commitment to address each by exception number.

| # | Document | Why |
|---|---|---|
| 1 | **Doc 2026-001338** — Redemption of Notice of Forfeiture, 1/16/2026, $7,800.17 | **Confirm parcel 33-16-16-04-400-023 is in the legal description.** If not, the property is County-owned. |
| 2 | **Doc 2022-032386** — $67,500 Mortgage Clear Sky Trust → Hawkins Robert L Trust | **Must be discharged at or before closing.** Order payoff letter from Hawkins Trust. |
| 3 | **Doc 2022-032385** — Warranty Deed Hawkins Trust → Clear Sky Trust | Verify legal description, all required trustees signed, proper acknowledgments. |
| 4 | **Doc 2022-032384** — Trust certification | Confirms who can sign for the Hawkins Trust as of 8/29/2022 (Robert L II + Charles successor + Donahue J III). |
| 5 | **Doc 2022-026514** — Letters of Authority | Confirms PR's authority for the 7/25/2022 Personal Rep Deed. |
| 6 | **Docs 2022-028216 / 2022-032382 / 2022-032383** — same-day round-trip through MITTEN REI LLC | Make sure title company understands and approves the curative chain. Confirm Mitten REI did not retain any senior interest unreleased (Mitten REI is now dissolved as of 3/1/2024 — title company should also confirm dissolution did not strand any unrecorded interest). |
| 7 | **Older Hawkins-era liens / mortgages** (1985-2017): Farmers State Bank of Munith, Dart National Bank, MI Treasury 2017 lien (released 4/2022 by doc 2022-015219) | Confirm all are discharged of record. |
| 8 | **Easements / oil-and-gas leases** | The 1980 BF-406384 oil-and-gas lease and other O&G leases recorded against this section suggest mineral rights may be severed. Title commitment should state mineral-rights status and any active surface-use easements. |
| 9 | **Boundary survey** | Recommended on a 1.68-acre rural parcel. Some lenders require. |
| 10 | **Property tax certification** | Confirm 2024 + 2025 taxes paid in full and 2026 not yet delinquent. |

Sources: free index at [Fidlar Direct Search (Ingham)](https://rep2laredo.fidlar.com/MIIngham/DirectSearch/) ; document images on [Tapestry](https://tapestry.fidlar.com/Tapestry2/Search.aspx) at $8.75/search + $1.00/page.

---

## Section 9 — Questions to ask the seller (in writing, before contingency expiry)

### Required disclosures (legally mandated)
1. Provide the **Federal Lead-Based Paint Disclosure** (required for pre-1978 sales).
2. Provide the **Michigan Seller's Disclosure Statement** in full, with all known defects.

### Permits (call out by name; demand permit numbers and inspection sign-offs)
3. Was the **furnace replacement permitted** by Stockbridge Township? Permit number and inspection sign-off.
4. Was the **roof replacement permitted**? Permit number, contractor name, and inspection sign-off. Provide the roofing manufacturer name and warranty registration.
5. Were the **electrical updates permitted**? Permit number(s), contractor name(s), final inspection.
6. Were the **plumbing updates permitted**? Permit number(s), contractor name(s), final inspection.
7. Was any **structural repair** to foundation, sills, or framing done? Permit, contractor, photos.

### Systems and services
8. Provide the most recent **septic tank pumping receipt** and date of last drain-field service.
9. Provide any **water-quality test results** (arsenic, bacteria, nitrates, lead) from the past 5 years.
10. Has the **well pump** been replaced since the well was drilled in 1980? When? Provide service records.
11. When was the **pressure tank** last replaced?
12. Was any old **underground storage tank** (heating oil, propane, gasoline) ever used or removed on the property? Closure documentation if so.

### Hazards / hidden conditions
13. **Knob-and-tube wiring** — was any found and removed during the renovation? Where? Provide receipts.
14. Is there any **vermiculite** insulation present, or **was it removed** during the renovation? Provide abatement documentation if removed.
15. Any **asbestos-containing materials** identified during renovation? Floor tile, pipe wrap, plaster, boiler wrap, siding shingles.
16. Any **lead pipes or lead solder** in plumbing supply lines?
17. Any **mold remediation** done in the basement / crawl space?

### Title and tax
18. Confirm payoff statement for **mortgage 2022-032386** ($67,500 to Hawkins Trust) and that it will be released at closing.
19. Confirm the **2025 tax foreclosure** affecting this parcel was redeemed — provide a copy of the redemption certificate that names parcel 33-16-16-04-400-023 specifically (not a "multiple legals" group document).
20. Are there any **easements, mineral-rights leases, oil-and-gas leases, or surface-use agreements** on this parcel?

### Other
21. Why was the listing price reduced from $319,900 to $284,900?
22. Has the property been **listed previously** (prior MLS 25053093) and if so, why did it not sell?

---

## Section 10 — Paywalled records & external follow-ups

| # | Record / Source | Where | Cost | Priority |
|---|---|---|---|---|
| 1 | Image of doc **2026-001338** (1/16/2026 redemption) | [Tapestry](https://tapestry.fidlar.com/Tapestry2/Search.aspx) | $8.75 + $1/pg | **Required** |
| 2 | Image of doc **2022-032386** (mortgage to Hawkins Trust) and any subsequent **discharge** | Tapestry | ~$15 | **Required** |
| 3 | Image of doc **2022-032385** (warranty deed in to Clear Sky Trust) | Tapestry | ~$10 | Recommended |
| 4 | Stockbridge Township BS&A full property record | [bsaonline.com](https://bsaonline.com/?uid=650) | $6.95 | Optional (title co. will see this) |
| 5 | Hawkins probate file (Ingham County Probate Court, case PR2022-XXXX) | [Ingham CourtRecordSearch](https://courts.ingham.org/CourtRecordSearch/) — index free; full file in-person | Variable | Optional |
| 6 | Septic permit / inspection records | Ingham Co Health Dept | FOIA call | **Required** — call (517) 887-4308 |
| 7 | Stockbridge Township permit history | call (517) 851-9362 | free | **Required** |
| 8 | LARA "Verify a License" — current status of Eric David Snyder's contractor license | https://aca-prod.accela.com/MILARA/Default.aspx | free | **Recommended** — confirms identity question in 2.4 |
| 9 | Updated water-quality test (full panel + arsenic + PFAS) | Local lab (Ingham Health Dept can refer) | $250-500 | **Required** |
| 10 | Boundary survey | Local surveyor | $500-1,500 | Optional (some lenders require) |
| 11 | Asbestos sample test | Complichek, Tri-Tech, similar | $300-500 | **Recommended** |
| 12 | Lead-based paint risk assessment | State-certified MI Lead Risk Assessor | $400-700 | **Recommended** if children |
| 13 | EGLE Water Well Viewer (UST overlay) by parcel coords | https://www.michigan.gov/egle/maps-data/waterwellviewer | free | **Recommended** |
| 14 | EGLE MPART PFAS GIS map | https://www.michigan.gov/egle/maps-data/mpart-pfas-gis | free | Recommended |
| 15 | National Wetlands Inventory for parcel | https://fwsprimary.wim.usgs.gov/wetlands/apps/wetlands-mapper/ | free | Optional |
| 16 | MI sex offender registry | https://mspsor.com/Search.aspx | free | Standard |

---

## Section 11 — All sources consulted, with URLs

### Primary public records
- [Ingham County Fidlar Direct Search](https://rep2laredo.fidlar.com/MIIngham/DirectSearch/) — free deed index 1956-present
- [Fidlar Tapestry](https://tapestry.fidlar.com/Tapestry2/Search.aspx) — paid deed images
- [BS&A Online — Stockbridge Township](https://bsaonline.com/?uid=650), [Ingham County](https://bsaonline.com/?uid=383)
- [Ingham Co Treasurer Auctions](https://tr.ingham.org/departments_and_officials/treasurer/auctions.php)
- [Ingham Co Treasurer Forfeiture & Foreclosure](https://tr.ingham.org/departments_and_officials/treasurer/forfeiture___foreclosure.php)
- [2025 Tax Insert PDF](https://docs.ingham.org/Department/Treasurer/2025%20Tax%20Insert_Publication_Final.pdf) (saved)
- [Ingham Equalization Tax Mapping Viewer](https://ingham-equalization.rsgis.msu.edu/)
- [Ingham County Court Record Search](https://courts.ingham.org/CourtRecordSearch/)
- [FEMA MSC — flood map](https://msc.fema.gov/portal/search) — saved FIRM panel PDF
- [EGLE Wellogic](https://www.egle.state.mi.us/wellogic/) — Well 33000001176
- [EGLE Water Well Viewer (UST)](https://www.michigan.gov/egle/maps-data/waterwellviewer)
- [EGLE MPART PFAS GIS](https://www.michigan.gov/egle/maps-data/mpart-pfas-gis)
- [EPA Radon Map of Michigan](https://www.epa.gov/sites/default/files/2014-08/documents/michigan.pdf)
- [USGS / Michigan Public — arsenic in well water](https://www.michiganpublic.org/environment-science/2014-07-02/theres-arsenic-in-michigans-well-water-but-not-a-lot-of-people-are-talking-about-it)
- [MDHHS arsenic county data PDF](https://www.michigan.gov/egle/-/media/Project/Websites/egle/Documents/Programs/DWEHD/Contamination-Investigation/arsenic-water-quality-maps-michigan-county.pdf)

### Seller-entity background
- [LARA news release: Eric David Snyder license suspension, 5/21/2019](https://www.michigan.gov/lara/news-releases/2019/05/21/lara-suspends-building-and-contracting-licenses-connected-to-eric-david-snyder)
- [Fox 17 — Grand Rapids roofer license suspended](https://www.fox17online.com/2019/05/21/state-suspends-license-of-grand-rapids-roofer)
- [WOOD-TV — W. Michigan contractor suspension](https://www.woodtv.com/news/grand-rapids/state-suspends-w-mi-contractors-license/)
- [JLC Online — Michigan suspends roofing contractor's license](https://www.jlconline.com/business/michigan-suspends-roofing-contractors-license_c)
- [DOJ press release — John Frederick Snyder tax evasion guilty plea, 6/21/2018](https://www.justice.gov/usao-wdmi/pr/2018_0621_Snyder)
- [DOJ press release — John Frederick Snyder sentenced to prison, 10/19/2018](https://www.justice.gov/usao-wdmi/pr/2018_1019_Snyder)
- [BBB — Snyder's Roofing Greenville profile](https://www.bbb.org/us/mi/greenville/profile/roofing-contractors/snyders-roofing-0372-17001510)
- [BBB — All American Remodeling Inc. profile](https://www.bbb.org/us/mi/walker/profile/remodeling/all-american-remodeling-inc-0372-38142235)
- [michigan-company.com — MITTEN REI LLC](https://michigan-company.com/co/mitten-rei-llc)
- [OpenCorporates — MITTEN REI LLC](https://opencorporates.com/companies/us_mi/802351231)
- [michigan-company.com — Snyder's Real-Estate LLC](https://michigan-company.com/co/snyder-s-real-estate-llc)
- [michigan-company.com — Clear Sky Advisers LLC (likely unrelated)](https://michigan-company.com/co/clear-sky-advisers-llc)
- [SEC IAPD — Clear Sky Advisers, LLC CRD 311751 (the unrelated investment-adviser firm)](https://adviserinfo.sec.gov/firm/summary/311751)
- [ClustrMaps — Eric Snyder MI (cluster including Linda Agnes Snyder, Greenville + Lansing)](https://clustrmaps.com/persons/Eric-Snyder/Michigan)
- [Jeshua Lauka attorney bio — David, Wierenga & Lauka P.C.](https://www.dwlawpc.com/Bio/JeshuaLauka.html)
- [Jeshua Lauka — Super Lawyers profile](https://profiles.superlawyers.com/michigan/grand-rapids/lawyer/jeshua-t-lauka/72c31d65-472b-4fbd-8d13-e7bf78aa300f.html)
- [John J. Donahue III — Avvo profile (Hawkins family attorney)](https://www.avvo.com/attorneys/48080-mi-john-donahue-737471.html)
- [John J. Donahue III — Justia profile](https://lawyers.justia.com/lawyer/john-j-donahue-iii-715441)
- [LARA "Verify a License" public search](https://aca-prod.accela.com/MILARA/Default.aspx) — to confirm current status of Eric David Snyder's contractor license
- [MiCOURT statewide case search](https://micourt.courts.michigan.gov/case-search/) — for litigation against the seller (manual / CAPTCHA)
- [Ingham CourtRecordSearch](https://courts.ingham.org/CourtRecordSearch/) — Ingham circuit + district + probate cases (manual / CAPTCHA)

### Ingham Co. permit / building
- [Stockbridge Township homepage](https://www.stockbridgetownship.com/)
- [Stockbridge Township Building Department](https://www.stockbridgetownship.com/building-department/)

### Listings
- [Brick Built Real Estate listing (MLS 26006743)](https://brickbuiltrealestate.com/listing-detail/1177882013/2980-Budd-Road-Stockbridge-MI)
- [Zillow listing](https://www.zillow.com/homedetails/2980-Budd-Rd-Stockbridge-MI-49285/74031386_zpid/)
- [voterrecords.com — Budd Road residents](https://voterrecords.com/street/budd+rd-stockbridge-mi/)
- [simplecontacts.com — Budd Road residents](https://www.simplecontacts.com/state/MI/Stockbridge/Budd-Road)

### Obit search (returned no Robert Hawkins from Stockbridge in 2020-2022)
- [Stockbridge Community News — obituaries section](https://stockbridgecommunitynews.com/category/obituary/)
- [Caskey-Mitchell Funeral Home / Legacy.com](https://www.legacy.com/funeral-homes/michigan/stockbridge/caskey-mitchell-funeral-home-inc/fh-21034)
- [Echovita Stockbridge](https://www.echovita.com/us/obituaries/mi/stockbridge)

### Phone numbers (call list)
- **Stockbridge Township Building Dept**: (517) 851-9362 or (517) 851-7530 — permit history
- **Ingham County Health Department**: (517) 887-4308 — septic + well permits
- **Ingham County Treasurer**: (517) 676-7233 (Alan Fox) — verify tax-foreclosure redemption
- **Ingham County Register of Deeds**: (517) 676-7294 — deed search subscription, document orders
- **Stockbridge Township Assessor / Treasurer**: (517) 851-9472 (treasurer) — projected post-uncap taxes

### Saved artifacts in `/Users/strandtc/dev/abbyhouse/property-records/`
- `FEMA_FIRM_panel_26065C0425D.png` (45 MB image, 14400×10350 RGB) — official FEMA FIRM panel — **open this directly to view the map**
- `FEMA_FIRM_panel_26065C0425D.pgw` — world file (georeferencing data) for use in GIS software
- `FEMA_FIRM_panel_26065C0425D.zip` — original ZIP from FEMA Map Service Center (contains the .png + .pgw + a generic read-me)
- `FEMA_FIRM_README.pdf` — FEMA's generic "How to read a FIRM" document (1 page; not parcel-specific)
- `ingham_2025_tax_insert_publication.pdf` — Ingham County 2025 show-cause publication; lists this parcel as delinquent
- `ingham_auction_*.pdf` (5 files) — Aug 2022, Oct 2022, Aug 2023, Oct 2023, Oct 2024 county tax-foreclosure auctions (parcel **not** present)
- `deed_index_findings.md` — tabulated deed-by-deed history of Hawkins ownership and Clear Sky Trust transactions
- `REPORT.md` — this report
- `INDEX.md` — file index
