# The State of Stablecoins in Latin America

**A source-graded market, regulatory and infrastructure assessment**
Research cut-off: 31 August 2026 · Prepared for Antier Solutions

---

## How to read this document

Every material claim carries a source, a date, and a confidence grade. Grades are not decorative — most of the numbers circulating about LatAm stablecoins fail at least one of these tests.

| Grade | Meaning |
|---|---|
| **[M]** Measured | On-chain, regulator, or central-bank data. Citable without hedging. |
| **[S]** Survey | Methodologically disclosed survey of a defined population. Directional; sample-dependent. |
| **[V]** Vendor claim | Self-reported by a company with commercial interest. Not audited. Never present as market fact. |
| **[P]** Practitioner | Stated on the record by an operator in the market. Valuable for mechanism and texture; not a measurement. |
| **[U]** Unverified | Widely repeated, could not be traced to a primary source. Do not use externally. |
| **[I]** Inference | My analysis, not a sourced claim. Flagged wherever it appears. |

A dedicated section at the end — **Verification Ledger** — lists the figures that did *not* survive checking, including several that circulate freely in stablecoin marketing and would embarrass anyone who repeated them in front of a CFO.

---

## 1. Executive summary

**The headline finding is not that LatAm stablecoin adoption is booming. It is that adoption and regulation have decoupled, and the region's two largest markets are moving in opposite directions.**

Six things a decision-maker needs to hold in mind:

**1. Brazil is now the region's centre of gravity, and it is simultaneously the region's tightest regulatory regime.** Brazil recorded **$318.8bn in crypto value received** over July 2022–June 2025, roughly **109.9% period-over-period growth** [M — Chainalysis, Oct 2025]. Receita Federal and BCB officials both put stablecoins at **~90% of Brazilian crypto flow** [M — Receita Federal, Nov 2025]. And yet, within nine months, Brazil published a full VASP authorisation regime (Res. 519/520/521), reclassified stablecoin transactions as FX operations, **banned** stablecoin settlement inside the regulated cross-border payments channel (Res. 561, effective 1 Oct 2026), and imposed a **24-hour cautionary hold** on outbound virtual-asset transfers above US$10,000 (Res. 584, effective 1 Jan 2027). The market is growing into a closing aperture.

**1a. It is a rail, not a vault — and now there is on-chain proof.** **Over 99% of withdrawn dollar volume moves onward within 30 days**; only about **6% of addresses behave like savers**, down from a 15% peak; the dollar half-life is **10.9 days** [M — BeInCrypto, Dune queries, July 2026]. And **72% of Ethereum stablecoin transfers are now under $1,000**, up from 43% in 2022 — small money, not wealth, is the growth story. Any product thesis built on balances sitting still is built on ~6% of the addresses. §2.10 has the counter-reading (the half-life doubled in a year).

**1b. The binding constraint is FX liquidity, not adoption or regulation.** Before Brazil's FX reform there was roughly **US$4 million of total order-book depth in USDT against BRL** on the main venue, and a **~15% all-in premium to trade even $3–4 million** — against a national market of about **$2 trillion a year** in spot B2B and consumer transfers [M — Dfns, July 2026]. Across the region, the local exchanges that function as the Global South's FX venues have depth "measured in single-digit millions," and there is no CLS-equivalent for stablecoin FX. Corridor operators carry a **~5x working-capital multiple on daily volume** to bridge the gap. Read every opportunity in this report against that ratio; §2.8 has the detail.

**2. Argentina — the canonical "inflation drives stablecoins" story — got less compelling, not more.** Argentina fell from **15th to 20th** on Chainalysis's Global Crypto Adoption Index between 2024 and 2025 [M]. Interannual inflation is **33.8%** (July 2026) and falling [M — INDEC]. The blue-official spread has collapsed to roughly **1.3%** [M — spot, 26 Aug 2026]. The cepo was lifted for individuals in April 2025, and Argentines have since bought **~US$44.4bn** in dollars through the formal banking channel [M — BCRA via Infobae, Aug 2026]. When you can buy dollars at a bank at a near-market rate, the marginal case for buying them on-chain weakens. **This is the single most important corrective to the standard LatAm stablecoin pitch.**

> **Qualified after a second pass through the Reports folder.** BIS WP 1370 (July 2026) finds dollarisation is a **ratchet** — AR(1) persistence ~0.8, no measurable decline even four years after countries exit high-inflation regimes — and that capital controls have **no statistically significant effect** on stablecoin inflows. Dfns separately reports Argentina's crypto dollar still trading several percent above official. So the defensible claim is narrower than the one above: **Argentine demand is very unlikely to collapse; its growth rate is normalising and the easy arbitrage is gone.** §4.1b states the counter-argument at full strength, including where it weakens my "corporate cepo is the opportunity" framing.

**3. The durable demand driver is dollar-banking *access*, not inflation — and the returns data proves it.** Over the decade to June 2026, **a plain local deposit beat holding dollars in both Brazil (150 vs 99) and Mexico (130 vs 58)**, indexed to 100 [M — BeInCrypto, from BCB/BCRA/INDEC/FRED]. Only in Argentina did dollars win, and there overwhelmingly: peso cash retained **0.8**. So in the region's two largest economies the *return* case for dollarising has been negative for ten years, and what buyers are actually purchasing is access, diversification and cross-border utility. §2.11 has the full table. This distinction matters commercially. Per DolarApp's own account in the Castle Island / Brevan Howard emerging-markets study you already hold: Mexican banks cannot offer USD accounts to anyone living more than 20km from the US border; **Colombia and Brazil do not permit retail dollar banking at all**; Argentina permits it but constrains it by volume and by the official FX rate. That structural exclusion does not go away when inflation falls. Inflation is cyclical; banking law is not.

**4. Local-currency stablecoins: supply is growing fast, on-chain liquidity has collapsed, and only Brazil is moving.** The BRL/COP/MXN complex carries **~US$166m of supply across ten issuers, up ~3.6x from $46m in 2025**, with ~$8.0bn of 2026 transfer volume — roughly **48x annual turnover**, confirming these are settlement legs rather than savings instruments [M — Iporanga Research dashboard, on-chain via Dune; §2.9]. But two findings cut hard against the growth story. **Aggregate DEX liquidity for every local-currency token in the region is $1.56m across 21 pools, deepest pool $188,900, with on-chain swap volume down ~99.8% since 2024.** And **essentially all growth is Brazilian** — BRLV and BRLA account for $83m of the $94m minted in 2026, while the entire Mexican peso complex is flat to negative. An earlier version of this report called the category a rounding error on a BRL-only $23m figure; that was too dismissive. What remains true, and is now much better evidenced: **issuing another token is not the opportunity — the flow is, and the liquidity to support it does not exist yet.**

**5. The margin structure is changing under the industry's feet.** After BCB's June 2026 notification that fund-routed stablecoin FX import structures were illegal, spreads on stablecoin FX operations in Brazil reportedly jumped from **~0.1% to 0.7–1%+** [M — Conjur, July 2026]. That is a 7–10x compression of the arbitrage that funded a generation of LatAm stablecoin PSPs. The profit pool is migrating from spread capture to compliance, licensing and settlement infrastructure.

**6. Consolidation has arrived.** Mastercard completed its **~$1.8bn acquisition of BVNK** on 3 Aug 2026 [M]. Stripe owns Bridge. Tether led a **$14m** round in Argentina's Belo (April 2026) and moved its HQ to El Salvador. Coinbase, notably, **retreated** from Argentine peso–USDC trading in January 2026, citing FX volatility, regulatory complexity and compliance cost. Growth and retreat are happening in the same region at the same time.

**What this means for Antier, in one line:** the sellable product in LatAm over the next 18 months is not another stablecoin wallet or another USD rail. It is the compliance, licensing, custody-governance and bank-issuance infrastructure that the region's new rules have just made mandatory — with Brazil's **30 October 2026 VASP authorisation deadline** as the single hardest, most dateable demand event in the market. Section 11 develops this.

---

## 2. Regional market data

### 2.1 Volume and ranking

Chainalysis is the only source producing consistent, comparable, on-chain-measured country data for the region.

| Country | Crypto value received, Jul 2022–Jun 2025 | LatAm rank |
|---|---|---|
| Brazil | $318.8bn | 1 |
| Argentina | $93.9bn | 2 |
| Mexico | $71.2bn | 3 |
| Venezuela | $44.6bn | 4 |
| Colombia | $44.2bn | 5 |
| Peru | $28.0bn | 6 |
| Chile | $23.8bn | 7 |
| Bolivia | $14.8bn | 8 |
| El Salvador | $3.5bn | — |

[M — Chainalysis, *2025 LATAM Crypto Adoption*, Oct 2025]

Regional total: **~$1.5 trillion** over the same three-year window. Monthly volume peaked at **$87.7bn in December 2024** and had fallen to **$47.9bn by June 2025** — a 45% drawdown from peak that the bullish commentary on this region rarely mentions.

> **⚠ Internal inconsistency, flagged.** Chainalysis writes that Brazil's $318.8bn accounts for "nearly one-third of all LATAM crypto activity." $318.8bn against a $1.5tn regional total is **21%**, not a third. Either the country figures and the regional figure use different definitions ("value received" vs. "transaction volume"), or the country figures cover a shorter window than stated. I could not resolve this from the public blog. **Recommendation: quote the absolute figures and the ranking, not the "one-third" characterisation.**

### 2.2 Global adoption index (Chainalysis, 2025, published 2 Sept 2025) [M]

Only three LatAm countries appear in the global top 20: **Brazil (5th), Venezuela (18th), Argentina (20th)**. Colombia, Mexico, Peru, Chile and Bolivia are all absent. Argentina's fall from 15th (2024) to 20th (2025) is the most analytically loaded data point in the set.

The **2026 index had not been published** as of 31 August 2026. Any "2026 Chainalysis ranking" circulating online is fabricated or misattributed.

### 2.3 Stablecoin share of activity

- **Brazil: ~90%** of crypto flows are stablecoin-related — stated by Receita Federal auditor Flavio Correa Prado (Nov 2025) and echoed by BCB president Gabriel Galipolo [M].
- **Argentina: 61.8%**, **Brazil: 59.8%**, **Colombia: 66%** of total crypto value received, against a global average of **44.7%** [M — Chainalysis, Jul 2023–Jun 2024 window]. For the Jul 2024–Jun 2025 window Chainalysis reverted to a qualitative "over half of all exchange purchases" for COP, ARS and BRL pairs — no per-country percentage was published.
- **Regional retail purchases: 40%** of purchases on Bitso's platform were USDC+USDT combined in 2025, the first year stablecoins overtook Bitcoin [V/S — Bitso, ~10m users across AR/BR/CO/MX].

**Bitso's country split** [V/S — Bitso *Crypto Landscape in Latin America 2025*]:

| Country | USD-linked share of purchases | USDC | USDT |
|---|---|---|---|
| Argentina | 71% | 14% | 57% |
| Colombia | 46% | 25% | 21% |
| Mexico | 36% | 24% | 12% |
| Brazil | 34% | 23% | 11% |

> **Do not average these against Chainalysis figures.** Three different denominators are in play: Chainalysis measures all on-chain value received (broadest, includes B2B and treasury); Bitso measures retail purchase behaviour on one exchange; Kaiko measures order-book volume on a partial venue set. Kaiko puts Bitso at ~26% of measured LatAm CEX volume [M — Kaiko, Jan–May 2025], so Bitso's platform data is a meaningful but non-representative slice.

### 2.4 Trading venue concentration [M — Kaiko, *State of LATAM Crypto Markets 2025*, Jan–May 2025]

Total measured LatAm volume Jan–May 2025: **$16.2bn**, +42% YoY. Brazil accounts for **77%** of measured regional trading activity. Venue share: **Binance $8.4bn (51.9%)**, **Bitso $4.2bn (25.9%)**, **Mercado Bitcoin ~$1.9bn (12%)**. USDT is **45%** of regional trading volume; Bitcoin 24%.

### 2.5 Chain distribution [M — Artemis, *Stablecoin Payments From The Ground Up 2025*]

- **Tron** leads in Colombia, Ecuador and Brazil.
- **Ethereum** dominates in Argentina and Peru.
- **BSC** shows traction in Chile, Brazil and Ecuador.
- **Argentina is the regional outlier on issuer mix**: USDC is nearly half of Argentine stablecoin volume, against minimal USDC share in Brazil, Chile and Colombia. Note this cuts against Bitso's platform data (which shows Argentina at 57% USDT / 14% USDC) — a genuine source conflict, likely explained by Artemis measuring total on-chain flow including institutional, versus Bitso measuring retail purchases.

### 2.6 LatAm payment flows [M — Artemis]

- **B2B stablecoin flow in LatAm grew from under $100m/month (early 2023) to ~$6.0bn/month (mid-2025)** — the single most impressive measured growth figure in this research.
- **Card payments** grew from $250m/month (early 2023) to $1.5bn/month (mid-2024).

Global context: Artemis measures **$122bn annualised** in "organic" stablecoin payments as of Aug 2025 — distinct from the **$26tn** total on-chain settlement figure that includes trading and DeFi. These two numbers are routinely conflated in press coverage. Stripe separately reported ~**$400bn** in global stablecoin payment volume in 2025, ~60% B2B [V — Stripe annual letter, Feb 2026]. Three methodologies, three answers; none is wrong, and none is interchangeable.

### 2.7 Remittances

**World Bank / KNOMAD official series** [M]:

- LatAm & Caribbean remittance flows: **$155bn (2023 actual)**, $160bn (2024 forecast), **$162bn (2025 forecast)**.
- Global average remittance cost Q3 2025: **6.36%**. LAC regional average: **5.64%**. Mexico is the cheapest G20 receiving market at **4.53%**.
- Corridor costs (Aug 2025 collection): **US→Mexico ~5.82%**, **US→Guatemala 4.19%**.

The World Bank's Migration and Development Brief contains **no reference to crypto or stablecoins**. The official statistical apparatus does not yet measure this channel at all — which is precisely why every stablecoin-penetration figure in this space comes from a vendor.

**Institutional cost claims** [S — BVNK *Stablecoin Utility Report 2026*, n=4,685 across 15 markets, incl. Brazil n=326, Argentina n=321, Colombia n=324, Mexico n=267]:

- Users who receive stablecoin payments report a **mean fee saving of 40%** vs. traditional methods; **LatAm respondents report 38%**.
- **54% of LatAm respondents currently hold or have held stablecoins** — Colombia highest at 67%, Argentina 56%, Brazil 47%, Mexico 47%.
- **71%** of LatAm respondents would use a linked debit card to spend stablecoins; **70%** are interested in merchant acceptance.
- **32% of LatAm holders convert stablecoins to fiat immediately or within days** — second-fastest of any region after South Asia (45%). *This is a use-as-rail pattern, not a store-of-value pattern*, and it contradicts the popular framing of LatAm stablecoin demand as primarily savings-driven.

---

### 2.8 Liquidity depth and corridor pricing — the missing half of the market

Source: **Dfns, *Stablecoin FX*, Edition Two (July 2026)** — interviews conducted November 2025, market and regulatory data verified 18 July 2026. This was sitting in `D:\Reports\Stablecoins` and is the single most on-point document in the folder for this report's subject. Its framing: *"Stablecoins move dollars at internet speed. Turning those dollars into pesos, reais, euros or won still runs at bank speed, bank cost, and bank hours."*

**The number that should reframe the Brazil opportunity.** Before the FX reform, Brazil offered what the report calls the cleanest demonstration of the problem: **roughly US$4 million of total order-book depth in USDT against BRL on the main venue, and a ~15% all-in premium to trade even $3–4 million — against a national market of about $2 trillion a year in spot B2B and consumer transfers** [M].

**[I]** Read that ratio and the standard LatAm pitch collapses. The largest stablecoin market in the region had order-book depth equal to roughly two parts per million of the fiat flow it claims to be disrupting, and moving a mid-seven-figure ticket cost fifteen percent. **The constraint is not adoption, regulation or rails. It is FX liquidity.** Everything in §9 and §11 should be read against this: orchestration, treasury and compliance products sell precisely because the liquidity layer is thin, and any thesis that assumes deep local-currency markets is assuming the hardest part away.

**Local exchanges are the FX venues, and they are small.** Per Visa's Sheffield, quoted in the report: "Bitso in Mexico and Yellow Card in Africa have done a really good job building liquid markets for converting between USDT and traditional MXN or Kenyan shillings." Their order books are the closest thing exotic stablecoin pairs have to price discovery — and **their depth is measured in single-digit millions**. Regulated venues arrived in 2026 (Deutsche Börse's 360T listing MiCA-compliant pairs; Circle's StableFX piloting RFQ across ten currencies) but published volumes are negligible; onchain EURC/USDC turnover is under $1m a day. **There is no CLS for stablecoin FX** — no settlement utility, no obligation on anyone to make a price in USDC against pesos.

**Corridor pricing — this resolves an open item in my Verification Ledger.** The **Borderless Q2 2026 Benchmark** (2.96 million rate observations across 260 corridors, 377 payout routes, 108 countries) found stablecoin delivery pricing at a **median 3.2 basis points *below* the same day's interbank rate**, having crossed under parity in February 2026 and drifted further below every month since April. At the median corridor, a **$10,000 payment cost 27.2bp all-in**; the best route delivered it for three dollars.

But the median hides the fork, and the fork is the LatAm story: Asia and Europe deliver below interbank; Africa still carries a **+68bp median premium**; and **parallel-market currencies — Argentina explicitly named alongside Congo and Ghana — still price access at hundreds to thousands of basis points over official rates.** Per Borderless's CEO: "in a lot of emerging markets, stablecoins actually trade at a *premium* compared to traditional fiat FX." The premium is not irrational — it prices scarce local liquidity, compliance risk, and, where capital controls bind, the value of an exit.

**[I]** So the honest answer to "are stablecoins cheaper in LatAm?" is: **at the median global corridor, yes and measurably so as of 2026; in the LatAm markets with the strongest narrative demand, often no.** That is a far more defensible position than the industry's blanket claim, and it points the commercial opportunity at liquidity provision and netting rather than at cost arbitrage.

**The working-capital tax nobody prices.** Bernardo Brites, cofounder/CEO of Trace Finance, on acquiring dollars in Brazil: *"Move the reais to your FX bank, convert, wait a day or two for the money to reach your US account, send it to your OTC desk, get USDT, sell again. If you're going to sell $2 million a day, in reality you need $10 million or more just to keep operations running."* The report's gloss: **a 5x working-capital multiple on daily volume is the quiet tax the T+2 world levies on every corridor business** — which is why corridor operators, not ideologues, are the technology's heaviest users. Compare Borderless's Lehtiniitty on the same problem: "$300 million of prefunding across all these different bank accounts all over the world from my balance sheet — what is the cost of that capital?"

**Orchestration networks, sized.** The report confirms §10.2(c)'s conclusion in one line — *"orchestration networks are where most real corridor FX executes, invisibly, inside payment flows"* — and puts numbers on them: **Conduit $10bn+ annualised** (independently corroborating the interview in §10.4d), **OpenFX ~$45bn annualised** after its March 2026 Series A, **Trace ~$9bn annualised**, with liquidity financiers **Arf and Huma** (~$7bn cumulative) funding the gaps.

Report-level context figures [M, as of July 2026]: stablecoin supply ~**$312bn**, ~99% dollar-pegged; USDT ~$184bn and USDC ~$73bn ≈ 82% combined; bot-adjusted on-chain volume **$10.2tn** TTM. Its real-economy payments figures ($390bn in 2025, $226bn B2B, "up more than 7x") are the contested ones — see the Verification Ledger.

---

### 2.9 The local-currency stablecoin complex, finally measured

Source: **Iporanga Research, *LATAM Stablecoins Report* dashboard** — `iporesearch.ventures/dashboard`. A live, purpose-built on-chain tracker for LatAm **local-currency** stablecoins, run by **Iporanga Ventures** (a Brazilian VC — note the commercial interest). All quantitative data is from **Dune Analytics with the developer profile published for transparency**, combined with expert interviews. This is the resource that fills the gap this report has flagged repeatedly: nobody was measuring the BRL/COP/MXN complex as a category.

**Headline figures (snapshot, dashboard is live):**

| Metric | Value |
|---|---|
| Total supply, 10 issuers | **~US$166.3m** |
| Holders | **126,400** |
| Weekly transfer volume (current) | **~US$474.7m** |
| Transfer volume, 2026 (yearly view) | **~US$8.0bn** |
| Implied turnover | **~48x supply per year** |

> **Correction to my own arithmetic.** In the previous version I annualised the single-week figure and reported "~2.9x of supply per week, ~150x/year." The dashboard's yearly view shows **~$8.0bn of 2026 transfer volume against ~$166m of supply — about 48x**, and even that may be year-to-date rather than full-year. Annualising one week from a live dashboard was sloppy; the velocity conclusion survives, the multiple was overstated roughly threefold. Use **~48x/year**, or quote the weekly figure as a weekly figure.

**Growth trajectory (yearly series):**

| Year | Supply | Net mint | Transfer volume |
|---|---|---|---|
| 2024 | ~$10m | ~$4m | ~$0.5bn |
| 2025 | **~$45.8m** | ~$31m | ~$5.8bn |
| 2026 | **~$166m** | **~$94m** | ~$8.0bn |

2025 supply by token: BRLV $18.4m · BRZ $13.7m · BRLA $4.5m · BBRL $2.7m · MXNB $2.1m · COPM $1.9m · BRL1 $1.2m · MXNt $1.1m · BRLm $230k · MXNe $19.3k.

**Coverage — nine tracked tokens across three currencies:**

| Currency | Tokens (issuer) |
|---|---|
| **BRL** | BRZ (Transfero) · BRLA (**Avenia**) · BRL1 (BRL1 Consortium) · BBRL (Braza Bank) · cREAL (Mentolabs) |
| **COP** | COPM (Minteo) · cCOP (Mentolabs) |
| **MXN** | MXNB · MXNe (Etherfuse) · **MXNt (Tether)** |

Chains: Polygon, Gnosis, Celo, Ethereum, Base, BNB, Avalanche, XRP Ledger, World Chain. Metrics include supply, transfer volume, holders, mint/burn, DEX swap volume, pool TVL and proof-of-reserve.

**The DEX liquidity data is the most important thing on the dashboard, and it is brutal.**

| | |
|---|---|
| Total DEX TVL, all LatAm local-currency pools | **~$1.56m across 21 pools** |
| Deepest single pool | **USDC-BRLA on Uniswap/Polygon — $188,900** |
| DEX swap volume, 2026 | **~$23,000** (BRLV $16.1k, BRLA $4.0k, BRZ $2.0k, everything else in hundreds or single dollars) |
| DEX swap volume, 2024 | **~$9.5m** |

Top pools by TVL: USDC-BRLA/Polygon $188.9k (weekly volume $789.5k, 1.6k tx) · USDC-BRLA/Polygon $154.7k · BRL1-USDT0/Polygon $124.0k (weekly volume **$16.13k, 74 tx**) · USDC.e-BRLA/Gnosis $107.9k · BRZ-USDT0/Polygon $100.3k (weekly volume $636.9k, 4.0k tx) · USDC-BRL1/Polygon $79.4k (**weekly volume $7.11, seven transactions**) · BRZ-BRLA/Polygon $39.6k · then three BRLm pairs on Celo (USD₮, EURm, KESm) at $23–32k each.

**[I] Read those two rows together.** Aggregate DEX TVL for every local-currency stablecoin in Latin America is **$1.56 million** — less than the deposit insurance on six US bank accounts — and **on-chain swap volume has collapsed by roughly 99.8% since 2024**, from ~$9.5m to ~$23k. The USDC-BRL1 pool holds $79,400 and did **seven transactions and $7.11 of volume** in a week. That is not a market; it is a set of parked liquidity positions.

This is the single strongest confirmation in the entire report of the constraint identified in §2.8. Dfns measured ~$4m of USDT/BRL order-book depth on Brazil's main *centralised* venue; this measures the *on-chain* side of the same market at **$1.56m across the whole region and every currency**. Two independent datasets, two venue types, the same verdict: **there is no meaningful local-currency FX liquidity in LatAm, and what little existed on DEXs has drained away** — presumably to CEXs and OTC desks, which this dashboard explicitly does not see. Anyone planning to route local-currency conversion on-chain should assume they are the market, not a participant in one.

**Chain distribution — and a correction to the standard narrative.** For local-currency tokens the chain mix is **Base ~48%, Celo ~30%, Polygon ~12%, XRPL ~5%**, with Ethereum, Arbitrum, Gnosis and Avalanche as slivers. That is a completely different picture from the USD stablecoin story in §2.5, where Tron and Ethereum dominate. **Tron does not appear at all.** If you are building for the BRL/COP/MXN complex, the chains that matter are Base and Celo — a point no other source in this research surfaced.

**The Brazil/Mexico split is stark, and it kills something I said last turn.** Of the ~$94m net minted in 2026, **BRLV ($53.6m) and BRLA ($29.6m) are $83m of it** — essentially all growth is Brazilian real. Meanwhile the entire Mexican peso complex is stagnant to shrinking: **MXNB +$9,200, MXNe −$13,900, and MXNt exactly $0.00 net mint for 2026** against $1.1m of supply.

**[I]** I flagged MXNt last turn as strategically notable — Tether issuing a local LatAm currency. On this data it is **dormant**: issued, then nothing. That tempers the point considerably. The interesting Mexican question is no longer "Tether is entering" but "why has *every* peso token flatlined while the real tokens 3.6x'd" — and the likeliest answer is §5.3's regulatory vacuum: Mexico has no legal category for a peso stablecoin, and the Murat Initiative would hand issuance to banks and IFPEs exclusively. Nobody is going to scale a token into that.

**One data artifact to avoid tripping on.** **BRLm has ~67,000 holding addresses — by far the largest holder base of any token here — against $230,000 of supply.** That is roughly $3.40 per address. It is a distribution artifact (airdrop or micro-balance seeding on Celo), not adoption, and it inflates the 126,400 headline holder count. BRLA's ~12,300 holders in 2024 growing to ~55,000 by 2026 is the more meaningful retail-adoption series.

**Methodology caveats that matter for how you cite it:**
- **Centralised exchanges are out of scope** — only on-chain and DEX activity is captured, so this is a floor on real activity, not a total.
- **Closed-loop stablecoins inside proprietary ecosystems are excluded**, as are smaller issuers with insufficient activity.
- BRZ uses non-standard supply management (treasury wallet rather than burning), so its supply is computed as total minus treasury; only BRZ v2 contracts are analysed following migration.
- **No stated update frequency** — check the as-of date before quoting.

**[I] Three things follow, and the third is the commercial one.**

First, **a correction to my own framing.** I called this category a rounding error based on a BRL-only $23m figure from June 2025. Broader, current coverage puts it at **$166m across three currencies** — roughly seven times larger, though not a like-for-like comparison. Still small in absolute terms; no longer dismissible.

Second, **the velocity number is the strongest confirmation of the rail-not-vault thesis in this entire report.** Supply turning over ~2.9x per week generalises what §5.4 observed for MXNB alone ($1.23m float, $94m of monthly transfers) to the whole local-currency complex, and it sits alongside BeInCrypto's finding (§2.10) that >99% of withdrawn dollars move on within 30 days. Two independent on-chain datasets, two currencies of denomination, the same behavioural conclusion: **this is settlement infrastructure, and the supply figure is close to meaningless as a measure of its importance.** Anyone sizing this market on market cap is measuring the wrong quantity by two orders of magnitude.

Third, **it closes an open item and adds issuers I did not have.** **BRLA is issued by Avenia** — that resolves the naming question flagged in §9.1. New to this report: **BRLV** (now the largest local-currency token by supply, and absent from the site's own published methodology list), **BRLm**, **BRL1** (a consortium issuer), **cREAL** and **cCOP** (Mentolabs), **MXNe** (Etherfuse), **MXNt** (Tether), and on the DEX side the Argentine peso tokens **wARS** (Ripio), **nARS** and **nuARS** — all with trivial volume.

**One figure on the site to handle carefully:** its projection that BRL stablecoins could facilitate **>$132bn annually with $6.6bn of savings if they captured 10% of trade finance and remittances** is a **modelled TAM, not a measurement** — a 10%-share assumption applied to an existing market. Useful for framing, not citable as evidence of anything.

**Recommendation: treat this dashboard as the standing monitor for the local-currency category**, and re-check it before any Brazil, Colombia or Mexico local-token claim. It is the only continuously maintained source of its kind found in this research.

### 2.9b The policy case for local-currency stablecoins — and what the measured data does to it

Source: **Sebastián Serrano, "How local stablecoins could help Latin America's economies," World Economic Forum Stories, 23 February 2026.** Serrano is **Founder and CEO of Ripio**.

**Read the byline before the argument.** Ripio issues **wARS**, the Argentine peso stablecoin (§9.1). This is an **advocacy piece by a local-currency stablecoin issuer arguing that Latin America needs local-currency stablecoins**, published under WEF's institutional brand — which lends it a credibility it has not earned as research. Grade it **[V], not [M]**, regardless of where it appears. WEF Stories is an op-ed platform, not WEF research; the distinction matters and is easy to lose when a claim gets re-quoted as "per the World Economic Forum."

**His four arguments, tested against the measurements in this report:**

**1. Monetary sovereignty — strong, and independently supported.** Serrano argues that heavy reliance on dollar stablecoins erodes "the tools policy-makers use to manage liquidity, influence credit conditions and respond to domestic challenges." **This holds.** BIS WP 1370 (§4.1b) finds dollarisation is a ratchet — AR(1) persistence ~0.8, no measurable decline even four years after countries exit high-inflation regimes — and, critically, that **capital controls have no statistically significant effect on stablecoin inflows**. A central bank watching dollarisation entrench through a channel its existing tools cannot reach has a genuine reason to want a local alternative. **[I] But note what kind of argument this is: a case for policymakers, not a demand case.** It explains why a central bank might want local stablecoins to exist. It says nothing about whether anyone would use one.

**2. Cash-handling efficiency — the weakest claim, and the data contradicts it.** Serrano argues local stablecoins would cut the cost of moving, storing and securing physical cash. **Latin America has the highest instant-payment penetration of any region on Earth — 52%, against a 40% global average** (§3.5, BCG). Pix processed **79.8bn transactions** in 2025 covering **93% of Brazilian adults**, free and instant. Bre-B did **617m transactions in six months**. And the sharpest rebuttal comes from someone with Serrano's exact commercial incentive — the founder and CEO of **Lumx**, a Brazilian stablecoin infrastructure company: *"In Brazil we don't need a local BRL stablecoin to do payments"*, because Pix is instant, 24/7 and almost free (§10.4a). **A local stablecoin adds nothing to domestic payments that the central-bank rail does not already do better and at zero cost.**

**3. Integration with tokenised local instruments — his strongest commercial point, and he understates it.** Serrano frames this as domestic investors moving between bank balances, stablecoins and local products. **The measured opportunity runs the other way.** Per Lumx (§10.2a): Brazil's non-resident account takes individuals three to four months and requires businesses to hold a regulated entity in a recognised jurisdiction; a BRL stablecoin wallet collapses that barrier, and Brazilian sovereign yield sits near **15% nominal**. The real use case is **offshore access to local assets**, not domestic circulation — a distinction that changes who the customer is and which licences the product needs.

**4. Government disbursement — the sourcing does not support the claim.** This is the article's only hard statistic, and it is misapplied. Serrano links the IDB finding that government spending waste costs the region **4.4% of GDP** to argue that programmable stablecoins would speed and audit subsidy, pension and relief payments. The underlying study is *Better Spending for Better Lives* (Izquierdo and Pessino, IDB Development in the Americas, **~2018** — cited in a 2026 article with no date qualifier), and its **$220bn / 4.4% figure decomposes into procurement inefficiencies, excessive civil-service payroll, and targeting errors in transfers**. It makes **no mention of payment systems or disbursement mechanisms as a source of waste at all.** A study about *who receives money and how much governments overpay* is being used to argue that *payment rails* are the problem. Chile and Peru show the lowest waste (1.8% and 2.5% of GDP) — a spread that tracks institutional quality, not payment technology.

**Sourcing quality of the piece — worth knowing before anyone cites it.** Eight hyperlinks. Four are tier-1 (World Bank inflation series, CGAP/Findex, an IMF blog, the IDB study). But **two of the eight — both supporting the "tech talent is growing" and "modernize" claims — point to Alcor, a recruitment and Employer-of-Record staffing firm**, whose page is marketing content with embedded calls-to-action and proprietary salary data of undisclosed methodology. A third points to a **gated Chainalysis demo landing page with lead-tracking parameters**, not to the report itself. So a quarter of the article's evidence base is a staffing agency's lead-generation page.

**One usable data point, with a caveat.** The CGAP link gives LAC account ownership rising from **39% (2011) to over 75% (2025)**. This report carries BeInCrypto's **39% → 70% (2024)** from the same Findex series (§2.11 context). Both are plausible at different vintages; the range is 70–75% and neither should be quoted as definitive without checking the Findex edition.

---

**[I] The synthesis that matters, and it is not a simple debunk.**

Serrano is making a **normative** argument — Latin America *should* have local stablecoins. This report answers a **positive** one — do they work today? Those are different questions, and the honest answer is that his policy case is stronger than his market case.

But the gap between them is enormous, and it is quantified. The entire regional local-currency complex is **~$166m of supply with $1.56m of total DEX liquidity**, deepest pool **$188,900**, and on-chain swap volume **down ~99.8% since 2024** (§2.9). **Ripio's own wARS recorded $378.94 of DEX swap volume in 2026**, against a wARS-USDC pool holding $69,700.

That does not make Serrano wrong — it may make him early, and the sovereignty argument stands on its own merits regardless of current volumes. But it means **the article is a statement of intent, not evidence of a market**, and it should never be cited as the latter.

**Why the local-currency thesis keeps failing in practice — a mechanism, not just a scoreboard:**

1. **Domestic payments are already solved by free central-bank rails.** Pix, SPEI, Bre-B. There is no cost or speed gap for a token to fill, and Pix is going cross-border to Argentina and Uruguay (§3.5), closing the next gap too.
2. **Measured demand is for dollars, not local currency.** Over 99% of withdrawn dollars move on within 30 days; ~6% of addresses behave like savers (§2.10). The whole regional local-currency complex is smaller than one mid-size DeFi pool.
3. **There is no liquidity, and liquidity is the binding constraint region-wide** (§2.8, §2.9). A token nobody can convert at size is not money.
4. **So the surviving use cases are precisely the ones a central-bank rail cannot serve:** non-resident account access, netting around transaction taxes (Colombia's 4x1000, §6.1), and tokenised local-asset distribution to offshore buyers. **Every one of them is cross-border. None is domestic.**

**And one piece of context worth stating plainly.** The loudest case for local-currency stablecoins is being made from Argentina — the single market in this report where local currency has performed worst. Peso cash retained **0.8 of 100** over the decade to June 2026 (§2.11), while dollars retained 74. That is not a gotcha: it is plausibly *why* Serrano thinks monetary sovereignty is urgent. But it does mean the advocacy and the demand data point in opposite directions in his home market, and anyone repeating the argument should know that.

**For Antier:** this article is useful as a *policy* narrative to sell into central banks and public-sector buyers, where the sovereignty argument is real and the audience is normative. It is actively dangerous as a *market-sizing* input. Section 11 already reflects this — issue-a-token is not on the opportunity list; the licensed cross-border and bank-issuance work is.

### 2.9c Macro context from Davos 2026 — one quote to use, one to reckon with

Source: **Pablo Uchoa, "Latin America at Davos 2026: From building trust, to Venezuela and trade insights," WEF Stories, 29 January 2026.** A conference report, not research — most of it (clean hydrogen, planetary boundaries, the jobs and AI sessions) is outside this report's scope. Four items are not.

**The quote worth having.** **James Scriven, CEO of IDB Invest**, on the region's binding constraint: *"Across the region, one of the biggest constraints we see is volatility — including uncertainty and a lack of trust in laws, institutions and **currencies**."* That is the head of the private-sector arm of the region's development bank naming distrust of currencies as a primary growth constraint. **It is the strongest institutional articulation of this report's core demand thesis** (§1.3) from a source with no commercial interest in stablecoins — considerably better provenance than any issuer quote in §10.

**The quote to reckon with, because it cuts the other way.** **Julio Velarde, Governor of the Central Reserve Bank of Peru**, said macroeconomic instability is **"no longer a regional concern,"** crediting independent central banks and credible monetary frameworks that have proved resilient to political pressure. A sitting central bank governor asserting the region's macro problem is solved is a direct challenge to inflation-driven stablecoin demand.

**[I] Both are true, and together they sharpen §4.1b.** Velarde is describing the **flow** — current macro conditions, which have genuinely improved (Argentine inflation to 33.6%, the escape premium from 150%+ to 2%, Milei's reported 13,500 structural reforms and >4% 2025 growth per the IMF's January 2026 WEO). Scriven is describing the **stock** — accumulated institutional distrust, which BIS WP 1370 measures as a ratchet that does not unwind when macro conditions normalise. **The macro crisis is receding while the distrust it created persists.** That is precisely the reconciliation §4.1b arrives at, now with a central bank governor and a development-bank CEO on opposite sides of it. Sell to the stock, not the flow.

**Regional integration — relevant to the intra-LatAm corridor gap.** Brazil's **Esther Dweck** (Minister of Management and Innovation): *"One point that is critical for growth is deeper integration in Latin America,"* describing EU–Mercosur as breaking US–China polarisation. **Juan Carlos Mora, CEO of Bancolombia**, argued against aligning with either superpower and said the private sector is ready to invest in infrastructure **once governments establish regional integration frameworks**. §6 identifies intra-LatAm as the "untapped corridor family" — no shared currency, no shared rail, two adjacent economies often settling through New York. **Political momentum for integration is the precondition for that corridor becoming addressable**, and it is notable that the executive making the infrastructure argument runs the bank behind Wenia's COPW and USDW (§6.3) — the region's only verified bank-issuance template.

**Also noted:** Mexico's "Plan Mexico" targets investment at **28% of GDP by 2030** and a move from the world's 12th to 10th largest economy; a WEF–McKinsey white paper estimates AI could add **1.9–2.3% annually** to LatAm productivity with value capture still limited. Context, not evidence.

### 2.10 The retention data — on-chain proof that this is a rail, not a vault

Source: **BeInCrypto Research, *The Exodus Economy: How Latin American Money Finds a New Financial Home*** (data pulled 16 July 2026; Dune queries 7995037/43/60/132 and 7996277 published as re-runnable). This is the best-methodology document in the folder: primary central-bank series (BCB CBE, BCRA, Banxico SIE, BanRep), US Treasury TIC, UN DESA, plus its own on-chain queries, with an explicit editorial-independence statement — "contributors and data providers are sources, not sponsors… all partner data is requested indexed, never absolute."

Its proprietary on-chain measurement answers a question every survey in this report only gestures at: **what actually happens to a dollar once someone withdraws it?**

| Metric | Finding |
|---|---|
| **Pass-through** | **>99% of withdrawn dollar volume moves onward within 30 days.** Every cohort measured runs at 96% or above. |
| **Dollar half-life** | Time for 50% of withdrawn dollars to leave the corridor: **4.7 days (Mar 2025) → 10.9 days (Mar 2026)**, a 2.3x lengthening. Series: 5.8 → 5.0 → 4.7 → 6.2 → 10.9. |
| **Retention ratio** | Addresses behaving like long-term savers (≥90% untouched after 90 days): peaked at **15%**, now near **6%**. |
| **March 2026 Bitso Tron cohort** | 89% pass-through, 5% in-between, **6% savers**. |
| **Transfer size** | **72% of Ethereum stablecoin transfers are now under $1,000**, up from 43% in 2022; Tron 66%. |

**[I] This is the hard version of a claim I had only from survey data.** BVNK's survey said 32% of LatAm holders convert within days (§2.7); this measures it on-chain and finds the reality is far more extreme — **over 99% of the money moves on within a month, and only ~6% of addresses behave like savers.** BeInCrypto's phrasing is the right one: *"a payments highway, not a piggy bank."* Every product thesis built on stablecoin balances sitting still — yield products, deposit-like economics, float capture — is being built on roughly 6% of the addresses.

**But read the half-life honestly, because it cuts the other way.** It **doubled** in twelve months, 4.7 to 10.9 days. Dollars are being held meaningfully longer than they were, and Nomad's Head of Investments describes the same shift qualitatively: *"Early on, simply holding dollars was enough… we now see a strong shift toward fixed income in USD, equities, and ETFs, as investors move from capital preservation toward actively seeking returns."* The behaviour is still overwhelmingly transactional, and it is becoming less so at the margin. Both facts are true; quoting only one is how this data gets misused.

### 2.11 The purchasing-power test — the finding that most complicates the dollar narrative

BeInCrypto ran the same $10,000-equivalent through four instruments in four markets, June 2016 to June 2026, indexed to 100 at the start (BCB, BCRA, Bluelytics, INDEC, FRED, Yahoo Finance):

| Instrument | Brazil | Argentina | Mexico | US (control) |
|---|---|---|---|---|
| Local cash | 61 | **0.8** | 62 | 72 |
| Local deposit | **150** | 44 | **130** | 91 |
| US dollars (cash / USDC) | 99 | 74 | 58 | 72 |
| USD + T-bill yield | 125 | 94 | 73 | 91 |

**[I] Read the Brazil and Mexico rows carefully, because they invert the standard pitch.** Over the last decade, **a plain local deposit beat holding dollars in both Brazil (150 vs 99) and Mexico (130 vs 58)** — decisively, and even against dollars earning T-bill yield. A Brazilian who dollarised in 2016 gave up roughly a third of the return available from a CDI deposit. Only in **Argentina** did dollars win, and there they won overwhelmingly: peso cash retained **0.8** of 100 — more than 99% of purchasing power erased — against 74 for dollars.

This is the sharpest available evidence for the argument running through §1.3 and §4.1b: **the LatAm dollar story is not one story.** In Argentina, Venezuela and Bolivia, dollarisation is financial survival and the return case is overwhelming. In Brazil and Mexico, the return case for holding dollars has been *negative* for a decade — so what people are buying there is **access, diversification and cross-border utility**, not yield. Any pitch that tells a Brazilian CFO that dollars protect their purchasing power is contradicted by ten years of data, and they will know it. The honest Brazilian pitch is settlement, working capital and reach.

---

### 2.12 The rail-quality gradient — Mexico and Argentina, finally measured (added 1 Sept 2026)

This closes the gap flagged in §12 "Open gaps". Until now the public-rail argument rested on Brazil and Colombia only. The two remaining big markets now have numbers, and they do **not** all point the same way.

#### 2.12.1 The comparable-year table

Using each central bank's own published figure, on the last year where all four are audited rather than press-reported:

| Country | Instant-payment rail | Transactions, latest official year | Population | Per inhabitant / yr | Source grade |
|---|---|---|---|---|---|
| **Brazil** | Pix | **63.5bn (2024)**; 79.8bn (2025) | ~213m | **298 (2024) / 375 (2025)** | [M] BCB |
| **Mexico** | SPEI | **5.34bn (2024)** | ~130m | **41** | [M] Banxico, *Informe Anual sobre las Infraestructuras de los Mercados Financieros 2024* |
| **Argentina** | Transferencias inmediatas (push) | **675.9m in Dec 2025 alone** → ~8.1bn annualised | ~46m | **~176** | [M] BCRA *Informe de Pagos Minoristas* |
| **Colombia** | Bre-B (launched Oct 2025) | 617m in first six months | ~53m | ~23 and climbing steeply | [M] BanRep via Stablecoin Insider |

**⚠ CORRECTION (1 Sept 2026) — do not quote a per-capita multiple.** An earlier version of this section called "Brazil does ~7x more instant payments per person than Mexico" the most defensible number in the report. **It is not like-for-like.** Banxico's own page states: *"SPEI® payments are always made between accounts at different banks."* **SPEI is interbank only.** A Mexican moving money between two accounts at the same institution never touches SPEI, and with BBVA México holding roughly a fifth of Mexican deposits that is a large invisible volume. Pix carries intra-institution transfers as well. The correct formulation is: **Pix carried 63.5bn transactions in 2024 against SPEI's 5.34bn, each from its own central bank; SPEI counts only interbank transfers, so the true gap is narrower than the ratio suggests and still very large.** State the limitation whenever the comparison is used.

*Further caveat [I]:* these are not methodologically harmonised. BIS CPMI Red Book covers Brazil and Mexico but **not** Argentina or Colombia, so a fully like-for-like four-country table does not exist. Argentina's push-transfer count also includes large volumes of wallet-funding movement that Pix would classify differently. Treat the gradient as directionally sound and the per-capita column as indicative only.

#### 2.12.0b Bre-B, re-sourced to Banco de la República (supersedes the sponsored-report figures)

The earlier Bre-B numbers (617m transactions / 218 institutions / 33m users in six months) came from Stablecoin Insider citing BanRep. Direct sourcing gives better and fresher figures:

- **1.07 billion operations in the first eight months** (to ~June 2026) [M — BanRep, via El Nuevo Siglo, 10 Jul 2026]
- **108 million registered keys (llaves)** as of 24 June 2026; **~35 million users**
- **Daily transactions tripled from 1.5m to 5m inside seven months**; peak 5.8m movements in March 2026 [M — BanRep news release, 5 May 2026]
- Average cumulative ticket COP 152,509
- BanRep publishes live indicators at `banrep.gov.co/es/bre-b/indicadores`, though the figures render through Power BI and are not in the static HTML

**Use these, not the sponsored-report set.**

#### 2.12.0c Pix merchant pricing — the counterargument this report had been missing

Pix is free **for the payer**. **Merchants pay roughly 0.33%**, against 1.13% on debit and 2.34% on credit. The "nothing prices below zero" argument therefore holds on the consumer side and **fails on the acceptance side**: a stablecoin acceptance rail at 10–20bp would undercut Pix's merchant fee.

Why nobody has taken it, and this is the answer to give when a client raises it: undercutting 33bp requires converting into and out of BRL at scale, daily, for less than 33bp. Against **~$4m of order-book depth and a ~15% premium to move $3–4m** (§2.8), the conversion costs more than the fee it is trying to beat. **The merchant-acceptance case is blocked by liquidity, not by pricing** — which makes it the strongest argument in the file for the liquidity/working-capital opportunity (§11, rank 5).

#### 2.12.2 Mexico's retail layers did fail — and Banxico's own words say so

This was carried as an unverified pre-cutoff recollection in the previous version. It is now verified, and it is worse than I assumed.

**CoDi** (QR layer, launched 30 Sept 2019), at its six-year mark:

- **21.8m validated accounts**, but **fewer than 2.5m** have ever made a payment, and only **1,085,933** have ever received one [M — Banxico data via DPL News, 16 Oct 2025]
- **17,792,880 transactions in six years**, total value **16,720m pesos**; average ticket ~940 pesos [M — Banxico, as of 8 Sept 2025]
- Banxico's own 2024 report: **9,903 average daily operations** in Dec 2024, with an average daily value of **10.6m pesos** — a national retail payment system moving roughly half a million dollars a day
- Concentration: **BBVA México accounts for 59% of account validations** [M]; **78.3% of CoDi payments go to beneficiaries representing 0.3% of beneficiary accounts** [M — Banxico 2024], i.e. a handful of large billers
- Banxico's own language across editions: performance "below expected levels", "evolución moderada"
- The IDB's assessment: *"the implementation of CoDi in Mexico produced no considerable change"* [S]

Scale that against Pix: **CoDi did 17.8 million transactions in six years. Pix did 79.8 billion in 2025.** Pix clears CoDi's entire six-year output roughly every **two hours**.

**DiMo** (phone-number layer, 2023): **5.28m registered users** (Dec 2023) → **12.2m** (Dec 2024) [M — Banxico]. Registration, not usage; Banxico does not separately quantify DiMo operations or value, which is itself informative.

**August 2026 confirmation:** ABM president Emilio Romano publicly conceded *"CoDi no es para todos y ni para todos los pagos"*, against an original target of 18m users in year one. Banks are now retrofitting automatic enrolment and simplified navigation [P — Cronista, 27 Aug 2026].

**Why it failed, per the DPL analysis** [S]: participation was **voluntary** for banks; no incentive for either side of the transaction; required a pre-existing bank account; buried inside banking apps.

> **⚠ CORRECTION (1 Sept 2026) — the "CoDi was voluntary" claim is WRONG, and this report repeated it.** DPL's framing does not survive checking against the primary sources, and any content built on it needs fixing.
> - **Brazil [M]:** Resolution BCB 1 of 12 Aug 2020, **Art. 3** — *"Participation in Pix is mandatory for the financial institutions and payment institutions authorized to operate by the Banco Central do Brasil that have more than half a million active customer accounts."* §1 defines active accounts as demand deposit, savings and prepaid payment accounts not closed. 90 days to apply.
> - **Mexico [M]:** Banxico **Circular 14/2017** as amended (published in the DOF 23 Mar 2022) obliges credit institutions and IFPEs holding **at least 3,000** demand-deposit or electronic-payment accounts to let all such account holders generate CoDi payment requests. Institutions below 3,000 accounts may join voluntarily. Banxico's own CoDi page lists **34 "participantes obligados"**, including BBVA México, Banorte, Santander, Banamex and HSBC.
> - **Therefore Mexico's mandate was proportionally BROADER than Brazil's** (a 3,000-account threshold against 500,000), and CoDi still failed. **Compulsion cannot be the explanatory variable.**
>
> **The replacement explanation, and it is an inference, not a measurement [I]:** Pix had a **paid incumbent to displace** (TED and DOC carried fees; Pix took them to zero). Mexico already had SPEI, cheap or free at most banks and familiar since 2004, so CoDi was an additional feature layered on a solved problem. This is corroborated by Álvaro Vértiz (DGA Group), who attributes CoDi and DiMo's weak adoption to "SPEI's success and existing market familiarity" (§2.12.2), and by the fact that 94% of SPEI traffic is retail-sized. Secondary factors that remain valid from the DPL list: CoDi required a pre-existing bank account, needed both parties present with 4G, and sat buried in banking apps.
>
> **Usable rule for any market:** a public rail closes the domestic payment case where it **replaces something people currently pay for**. Where the incumbent is already free, mandating a second free option changes little. Ask about displacement, not about mandates.

**⚠ Discrepancy logged:** Fintech Expert (1 Oct 2025) reports CoDi cumulative value as "slightly over 720 million pesos". DPL reports 16,720m pesos. The stated average ticket (875–940 pesos) is consistent with the DPL figure and inconsistent with the smaller one, so the 720m figure is most likely a transcription of "16,720 millones". **Use 16,720m pesos, cite Banxico, and do not use either number without the caveat.**

**⚠ SPEI 2025 figure is contested — do not use the headline number:** press reports of **"7.3bn transfers / 600tn pesos / 16.8x GDP" in 2025 trace to STP and to a Bitso report [V], not to Banxico.** Other outlets citing Banxico say "over 6bn". Banxico's own audited 2024 figure is 5.34bn / 578tn pesos / ~17.2x GDP. **Use the 2024 Banxico figure.** The 36.8% YoY growth claim rests on the contested 2025 number.

#### 2.12.3 Argentina is the genuinely contested case

Argentina has a competent public instant rail and it is heavily used — but the rail is a substrate, not a destination. From BCRA's *Informe de Pagos Minoristas*:

| Metric | Dec 2025 | Feb 2026 |
|---|---|---|
| Immediate transfers, push (peso) | 675.9m / ARS 81.2tn, **+24.2% YoY** | 731.5m / ARS 82.2tn |
| Immediate transfers, foreign currency | 2.4m ops / **USD 3,420.7m**, −2.4% YoY | 2.2m ops / USD 3,222m |
| Payments with transfer (PCT) | 93.3m, **+48.1% YoY** / ARS 2.1tn | 100.8m / ARS 2.3tn |
| — of which QR-initiated | 92.1m (+53% YoY) | 99.6m (**98.8% of PCT**) |
| Debit cards | 162.8m, **−28.4% YoY** | 160.4m |
| Credit cards | 181.6m, −1.8% YoY | 153.2m |

Three findings that matter:

1. **[M] 76.2% of immediate transfers originate from a CVU — a digital wallet, not a bank account.** Argentina's instant payments run on a public interoperable rail but through **private wallet front-ends**. This is structurally different from Brazil, where Pix is the bank's own product. It is the one large LatAm market where a private layer owns the customer relationship on top of the public rail.
2. **[M] QR payments are growing ~50% YoY while debit cards fell 28% YoY.** The rail is actively cannibalising cards, fast. Whatever window existed for a domestic payment token is closing here too, just with different owners.
3. **[M] Argentines moved USD 3.4bn through the formal foreign-currency transfer rail in a single month, and that flow is flat-to-declining (−2.4% YoY).** This is the most direct available read on §4.1b: with the peso stabilised, the *formal* dollar-transfer channel is not growing. Anyone arguing dollar demand in Argentina is still accelerating needs to explain this number.

#### 2.12.4 What this does to the thesis — including the part that cuts against it

The tempting formulation is *"the public rail absorbs the domestic use case where it is well designed and adopted, and leaves it contested where it is not."* Mexico fits the second half. **But the Mexico case actively breaks the naive version of that story**, and this must be stated in any external writing:

> Mexico has the region's weakest retail instant-payment layer **and** the region's deadest local-currency stablecoins. MXNB net supply change 2026: **+$9,200**. MXNe: negative. MXNt: **$0.00 net mint in 2026** (§2.9).

If rail weakness created the opening for a domestic payment token, Mexico would be the local-stablecoin capital of Latin America. It is the opposite. **The binding constraint is not rail quality — it is that nobody wants a token denominated in the currency they are already trying to get out of, and where they are not trying to get out of it (Brazil, Mexico) the local rail is free anyway.** Rail quality determines *how fast* the domestic case closes, not *whether* it closes.

Note also that CoDi's failure did not produce a stablecoin; it produced **SPEI itself absorbing retail** (94% of SPEI transactions are under 1,500 UDIs, i.e. retail-sized) plus persistent cash. The counterfactual to a bad public rail in LatAm has been a bigger public rail and cash, not crypto.

**Corollary that survives, and is the stronger claim:** the jobs stablecoins hold in LatAm are **not** payment-rail jobs at all. They are dollar access, out-of-scheme corridors, and tax netting (§2.8, §5.1, §6.1). Those are unaffected by whether SPEI or Pix is better, which is precisely why they are the durable ones.

### 2.13 Source sweep, 1 Sept 2026 — what the additional feeds added, and what they did not

Seven further sources were checked at the user's direction. Recording the negatives matters as much as the positives, so this ground is not re-covered later.

**Added something**

- **Castle Island Ventures / Visa / Brevan Howard, *Stablecoins: The Emerging Market Story*** [S — YouGov, n=500 Brazilian crypto-using adults 18+, fielded 29 May–13 Jun 2024]. Brazil respondents' stated goals: **trading 44%, earning yield 42%, saving in dollars 40%, better conversion rates 33%, converting local currency to dollars 31%**. Activities: converting local currency to stablecoin **67%**, business use **33%**, paying for goods and services **35%**, cross-border to relatives **29%**, salary **18%**. Brazilians reported the **lowest stablecoin portfolio share** of the five countries surveyed (49% held 1–10%). **Use this as the survey-versus-measured contradiction:** 40% *say* they save in dollars, while the on-chain retention data (§2.10) shows **over 99% of withdrawn dollar volume moving onward within thirty days and ~6% of addresses still holding at ninety**. Stated intent is savings; measured behaviour is pass-through. Caveat hard on the date (mid-2024) and on the crypto-user-only sample. Only five countries: Brazil, India, Indonesia, Nigeria, Turkey. **No 2026 wave exists.**
- **Meta's USDC creator payouts — verified and CORRECTED.** The Fireblocks blog (31 Aug 2026) listed the Philippines, Argentina, Peru and Colombia. Primary reporting of the launch (Fortune, 29 Apr 2026; Polygon Labs) puts the initial rollout at **Colombia and the Philippines only**, on **Solana and Polygon**, with **Stripe** handling crypto tax reporting, and a stated intent to reach 160+ countries by end-2026. **Do not use the four-country list.** The two-country version is the better fact anyway: **Meta pays Colombian creators in USDC six months into Bre-B's life**, because Bre-B lands pesos inside Colombia and does nothing for a US platform paying across 160 countries. That is the out-of-scheme corridor job demonstrated against the region's newest and best-performing rail.
- **DefiLlama** [M, 1 Sept 2026]: **USDT $183.47bn, USDC $73.98bn** circulating. Confirms the $183bn Tether figure used throughout.

- **Pix cross-border — CORRECTED, and it is weaker than this report implied.** Earlier text said BCB "prioritising Uruguay and Argentina", which downstream writing turned into "Pix is going cross-border". What is actually live is **Banco do Brasil**, a commercial bank, letting **Brazilian travellers** pay **Argentine merchants** by QR through its own subsidiary **Banco Patagonia**, with BB doing the conversion (reported 6 Mar 2026). **One bank's closed loop for tourists, not the scheme crossing a border.** This flips the argument: the difficulty of taking Pix cross-border is evidence *for* the corridor job surviving, not against it. Note also the internal-consistency trap: Lumx's lesson (§10.2) is never to build to a central bank's roadmap, so citing a BCB roadmap item as evidence undercuts the same section that quotes them.

**Added nothing, and here is why**

- **DefiLlama's stablecoin dataset carries only `peggedUSD` assets. Not one BRL, MXN, COP, ARS or CLP token appears in it.** This is independently corroborating: the region's local-currency complex is too small for the largest public stablecoin dataset to track. The Iporanga/Dune dashboard (§2.9) remains the only usable source, which is a real limitation to state out loud rather than a gap to keep hunting.
- **Visa Onchain Analytics** publishes eight global metrics across 10 L1s and 9 L2s with **no country or regional segmentation whatsoever**. Useless for LatAm attribution. Do not cite it for regional claims.
- **Castle Island's weekly roundups** (through 28 Aug 2026): no LatAm, emerging-market or payment-rail content.
- **Murmurations (Nic Carter)**: three posts since May 2026, most recent 3 Jun 2026. The stablecoin post (28 May 2026) argues the private-money case against the free-banking critique. No LatAm or dollarisation content.
- **Tether transparency page**: figures are served dynamically and the static page returns none. The MXNt product tab exists; supply must be read from the dashboard or from RWA.xyz.
- **Stablecoin Insider's 1 Sept 2026 LatAm payments piece**: see the box at the head of §12. It recycles four already-debunked aggregates. Genuinely new items were **Circle Payments Network annualised volume ~$8.3bn (Mar 2026)** [V], **card-linked stablecoin spending +673% YoY** [V, unattributed], and **Argentina monthly active crypto user penetration 12% (2025)** [V]. Treat all three as vendor claims.

---

## 3. Brazil — deep dive

### 3.1 Why Brazil matters

Brazil is simultaneously the region's largest market, its most institutionally driven, and now its most heavily regulated. Roughly **95% of Brazil's foreign trade is dollar-denominated** [Circle, Sept 2024], while **retail dollar banking is not permitted domestically**. That gap — massive dollar exposure, no retail dollar account — is the structural engine.

### 3.2 Regulation: the framework, precisely

**In force:**

| Instrument | Published | Effective | What it does |
|---|---|---|---|
| Lei 14.478/2022 | 2022 | Jun 2023 | Virtual asset framework; designates BCB as regulator |
| Res. BCB 519 | 10 Nov 2025 | 2 Feb 2026 | VASP ("SPSAV") authorisation process; fit-and-proper, IT/governance tests |
| Res. BCB 520 | 10 Nov 2025 | 2 Feb 2026 | SPSAV constitution and operation; **defines stablecoins**; three licence modalities; client-asset segregation; daily balance and monthly reserve-attestation reporting |
| Res. BCB 521 | 10 Nov 2025 | 2 Feb 2026 (FX reporting provisions 4 May 2026) | **Brings virtual-asset operations into the FX regime**; classifies stablecoin↔fiat exchange, international payment via virtual assets, and card settlement via virtual assets as FX operations |
| Joint Res. CMN/BCB 14/2025 + Res. BCB 517/2025 | 2025 | — | Minimum capital formula for PSAVs |

**Licence modalities (Res. 520):** *Intermediárias* (intermediation, portfolio administration, staking, FX), *Custodiantes* (key custody, position-keeping), *Corretoras* (combined). Banks and securities brokers may also provide these services.

**Capital requirement — it is a formula, not a number.** "Parcela Custo": R$2m per notified operational category, +R$5m if tech-intensive (component capped at R$10m). "Parcela Atividades": base R$1m/3m/5m/7m by category, plus R$5m (restricted) or R$8m (free) investment component, multiplied by a capture factor of 60%/80%/120%/200%. A worked example for an intermediation+custody PSAV with free investment lands near **R$13m**, +R$5m if tech-intensive. The **R$10.8m–R$37.2m** range that circulates is a simplification from Chainalysis's blog summary, not the rule.

**Self-custody — the 2024 proposal was not the 2025 rule.** Public Consultation 110/2024 proposed restricting stablecoin transfers to self-custodial wallets, and that framing persists in press archives. The final rules did **not** adopt an outright ban. They require VASPs to identify the beneficial owner of a self-custodied wallet before sending or receiving, and document provenance. Self-custody transfers enter the FX perimeter only where a cross-border or foreign-currency dimension exists.

**The authorisation cliff:**

- **2 Feb 2026** — 270-day clock starts.
- **30 Oct 2026** — deadline for existing VASPs, **including foreign platforms serving Brazilian residents**, to file. After this date, BCB-authorised institutions may not transact with unauthorised counterparties.
- Firms that filed on time may continue operating pending review; firms that missed it must cease within **30 days**.

This is, in commercial terms, the most actionable date in the entire LatAm stablecoin landscape. Every exchange, PSP, wallet and remittance provider touching Brazilian residents must be filed within eight weeks of this report's date.

**Then it tightened further:**

- **Res. BCB 561** (published ~1–2 May 2026, effective **1 Oct 2026**): **bans** the use of stablecoins or crypto to settle cross-border payments processed through the regulated eFX channel. An eFX provider can no longer take BRL, convert to USDT/USDC, and settle abroad on-chain. Permitted settlement is now traditional FX or non-resident BRL accounts in Brazil. Unauthorised eFX firms must apply by **31 May 2027**. Named as directly affected: **Nomad** and **Braza Bank**. This does *not* restrict individuals from buying or holding stablecoins through authorised VASPs.
- **23 June 2026**: BCB notified banks and funds that structures using investment funds as liquidity providers to route stablecoin-based FX imports are illegal. Reported market effect: stablecoin FX spreads rose **from ~0.1% to 0.7–1%+** [M — Conjur, 1 Jul 2026].
- **Res. BCB 584** (published 7 Aug 2026, effective **1 Jan 2027**): cautionary hold of **up to 24 hours** on virtual-asset transfers exceeding **US$10,000** (per transaction or cumulative daily per customer) destined for foreign entities or self-custody wallets. Early release permitted with documented risk-based justification. **ABToken and ABCripto publicly objected.**

**[I] Reading the sequence.** Brazil is not banning stablecoins. It is systematically closing the channel where stablecoins substituted for the regulated FX market — first by definition (521), then by prohibition inside eFX (561), then by enforcement against workaround structures (June 2026), then by friction on outbound flow (584). The permitted use case is narrowing to on-exchange, authorised, reported, and slow. That is a compliance-services market being created by decree.

### 3.3 Tax — one important correction

**The "17.5% flat crypto tax introduced in 2025" is not law.** MP 1303/2025 proposed a unified 17.5% rate on capital-gains-type income including crypto and staking. It **lapsed without a floor vote**, losing validity around **8 October 2025**. The prior regime continues: progressive 15–22.5% rates with the **R$35,000/month individual sale exemption** intact, monthly/annual filing, no staking withholding. Anyone quoting the 17.5% figure as current Brazilian law is wrong.

**IOF — now reported as in scope at 3.5%, which changes Brazilian corridor economics.** By classifying stablecoin operations as FX, Res. 521 created the legal pathway for IOF-Câmbio. The Stablecoin Insider report states that the reclassification **brings a 3.5% IOF-Câmbio charge into scope for covered cross-border stablecoin payments from February 2026** — "a concrete case of a 'cheap' rail acquiring a fiscal cost once formalised" — and advises modelling the regulated cost rather than the on-chain cost [source: Avalon Blockchain Consulting, cited in that report]. **Single secondary source; confirm against Receita Federal before relying on the rate.** But directionally it resolves the open question, and it is consistent with the observed spread move from ~0.1% to 0.7–1%+ after BCB's June 2026 enforcement (§3.2).

**[I] If the 3.5% figure holds, it is the most important number in the Brazilian section.** A 3.5% fiscal charge on the FX leg dwarfs every on-chain efficiency the rail provides — Tron's median fee is ~$0.09 — and it means the Brazilian cross-border stablecoin case can no longer be sold on cost. It has to be sold on settlement speed, working capital and 24/7 availability, which is exactly what the operators in §10 say they actually sell on.

**DeCripto** — Receita Federal's OECD CARF-aligned reporting regime, replacing **IN 1888/2019** (dated May 2019 — much secondary coverage says "IN 1888/2020" and is wrong; PwC's Brazil entry, authored by three named PwC Brazil partners, and LegisWeb both date it 03/05/2019). Aggregate annual reporting from **1 Jan 2026**; monthly reporting and individual obligations from **1 Jul 2026**; first individual filing **August 2026**. Threshold for foreign-exchange/DeFi reporting rises to **R$35,000/month**. Domestic providers must report all operations individually regardless of size. Transactions over **US$50,000** flagged. Penalties: R$100/month late (individuals), 1.5% of transaction value for errors, 50% reduction if self-corrected.

### 3.4 Drex is over — and that matters

BCB **deactivated the Drex pilot infrastructure in November 2025** (announced ~5 Nov, deactivated ~10 Nov), five years after starting. Stated reason: the DLT solutions tested could not meet **banking-secrecy and inter-institution transactional privacy requirements**. Drex coordinator Fábio Araújo was quoted saying tested solutions "lack maturity levels required by national financial system services." BCB plans to resume tokenisation work in 2026 on an **architecture-agnostic** basis, prioritising interoperability of tokenised assets with settlement in central bank money, and including tokenised assets as loan collateral.

> **Sourcing caveat, important.** bcb.gov.br is JavaScript-rendered and did not return article text on fetch. The Drex-termination narrative rests on four independent Brazilian outlets reporting consistently (Gazeta do Povo, Central do Varejo, COFECI republication, Cointelegraph BR syndication) — but **not** on BCB's own release text. Corroboration is strong; primary confirmation is missing. Verify before using in a client-facing document.

**A precursor the secondary reporting missed.** Per Lumx's founder (§10.4a), the public signal came earlier and from the top: at **Blockchain Rio in early August 2025**, the **BCB president gave a keynote saying they might not use blockchain for the CBDC at all.** He describes the reaction as disbelief — banks had spent four years and, in some cases, built ~80-person digital-asset teams around the Drex pilot — and attributes the reversal partly to the change of BCB president between 2024 and 2025. [P — I could not independently confirm the keynote; the sequencing (August 2025 signal → November 2025 deactivation) is coherent and consistent with everything else in §3.4.]

**[I]** The timing is the story: in the same month BCB abandoned its CBDC on privacy grounds, it finalised the private stablecoin framework. Brazil effectively conceded the tokenised-money rail to private issuers while reserving the right to regulate them into the FX perimeter. Brazilian crypto press reads this as ceding ground to USDT/USDC. That reading is interpretation, not an official BCB position.

### 3.5 Pix — the thing stablecoins do not compete with

2025 full year: **~80 billion transactions**, **R$35tn+** in value, +25.7% in count and +33.8% in value YoY [M — BCB *Pix Management Report*, 2nd ed., 10 Aug 2026]. Person-to-business share rose from 39% to 43%. Single-day record: **313m transactions**. Pix Automático launched June 2025 and has grown slowly — receiving users went from ~1,000 (end-2025) to ~14,000 (Aug 2026). Pix Parcelado remains experimental without dedicated regulation.

**The regional picture, and a competitive development I had missed.** BCG's *Global Payments Report 2025* (Sept 2025) puts **Latin America's instant-payment penetration at 52% — the highest of any region in the world** (Middle East 32%, North America 39%, global average 40%), measured as instant payments' share of total digital retail payments across 63 countries using central-bank data. **Pix alone serves over 160 million users.** Real-time A2A reached ~25% of global retail payments in 2024, with 70+ countries running real-time systems.

And the part that matters most here: **Pix is moving toward cross-border integration, with Brazil's central bank prioritising corridors to Uruguay and Argentina** [M — BCG, citing public announcements].

**[I]** Stablecoins do not have a domestic Brazilian payments story. Pix is instant, ubiquitous and effectively free. The entire Brazilian stablecoin thesis is cross-border, FX, and dollar exposure — which is exactly the surface BCB has spent nine months regulating. **A cross-border Pix narrows it further, and it targets Argentina first** — the highest-value stablecoin corridor in the region. Combine that with Colombia building its own Pix-model rail (§6.1) and the pattern is clear: **LatAm's central banks are building the public instant-payment layer themselves, and they are extending it into precisely the corridors private stablecoin rails were counting on.** What survives is what a central-bank rail cannot do — hold dollars, cross into non-participating jurisdictions, and net around transaction taxes. Build for those, not for speed.

### 3.6 Market data

- Receita Federal (Nov 2025): **$6–8bn/month** in stablecoin flow, projected ~$9bn/month by 2030 [M].
- **May 2026: $2.63bn** in stablecoin purchases, **+158% YoY**; **June 2026: $2.54bn** vs $1.48bn a year earlier; **Q1 2026: $6.7bn** sent abroad in stablecoins, double Q1 2025; cumulative declared since 2019 **~$219bn** = **71.7%** of all declared Brazilian crypto volume; **USDT = 88.7%** of declared stablecoin flow. **[U — sourced to an individual analyst's Substack (Eduardo Moore) citing declared/on-chain data; directionally consistent with Receita Federal's own figures but not independently confirmed. Do not cite externally without corroboration.]**
- **~120 providers** estimated serving the Brazilian market informally as of mid-2026 [U — same source]. **[I]** If even directionally right, this is the size of the addressable base facing the 30 Oct authorisation deadline.

### 3.7 Players

| Player | Position | Grade |
|---|---|---|
| **Nubank** | 100m+ Brazilians have USDC access via Circle partnership; 25% of new Nubank Cripto users buy USDC first; USDC volume +30% H1 2025; USDC = 30% of platform crypto portfolios; killed its own Nucoin token Sept 2024 | [V — Circle case study; note *access* ≠ *usage*] |
| **BTG Pactual** | **Discontinuing BTG Dol.** Announced 9 Jan 2025; purchase cutoff 24 Jun 2026; full discontinuation 1 Jul 2026; balances auto-converted 1:1 to **USDC**, no fee. The first bank-issued dollar stablecoin in the world (2023) is being retired in favour of USDC. | [U on dates — sourced to a crypto aggregator, not BTG IR. **The strategic signal is more reliable than the dates.**] |
| **Braza Bank** | Issued **BBRL** on Polygon (Feb 2026); processed ~$1bn in stablecoin payments on XRP Ledger (Aug 2025); partnered with **Conduit** on stablecoin FX swaps (Jun 2025). **Directly impacted by Res. 561.** | [M on partnerships; V on volume] |
| **Itaú Unibanco** | Completed Drex pilot; **11 Aug 2026** new pilot with OpenAssets and ANBIMA to tokenise fixed income and funds. **Still pilot-stage — nothing shipped.** Board member Ricardo Villela Marino personally backs Trace Finance. | [M — CoinDesk] |
| **Binance Brazil** | Acquired **Sim;paul** broker-dealer; BCB approved 30 Dec 2024, giving direct Pix access. Whether this exempts it from SPSAV authorisation is **unresolved**. | [M on approval; unverified on SPSAV status] |
| **Transfero (BRZ)** | Largest BRL-pegged stablecoin; **no tier-1 current volume or market-cap data obtainable** | [gap] |
| **BRLA / Avenia** | $3m pre-seed; joined Borderless.xyz network. **Naming resolved: BRLA is issued by Avenia**, per the Iporanga Research issuer table (§2.9). | [M on issuer; V on funding] |
| **Mercado Pago** | Shut down **Mercado Coin** in Brazil in 2026, citing Pix competition. Meli Dólar launched in **Chile**, not Brazil. | [M — eMarketer, Apr 2026] |

**[I] Two banks, two directions.** BTG is retiring its own dollar stablecoin for USDC while Bancolombia (Section 6) is doing the reverse — replacing USDC with its own USDW. Both are rational: BTG concluded liquidity and acceptance favour the incumbent; Bancolombia concluded reserve control and margin favour self-issuance. Which is right depends entirely on whether you monetise the float or the flow. **This is the central strategic question for any bank Antier advises on stablecoin issuance.**

---

## 4. Argentina — deep dive

### 4.1 The macro reset

This is the section most likely to change how you pitch the region.

| Metric | Value | Date |
|---|---|---|
| Interannual inflation | **33.8%** | Jul 2026 [M — INDEC] |
| Monthly inflation | 2.1% (Jul), 1.9% (Jun), 2.1% (May) | 2026 [M — INDEC] |
| Cumulative Jan–Jul 2026 | 19.3% | [M — INDEC] |
| Blue–official spread | **~1.30%** | 26 Aug 2026 [M — spot] |
| Dollars bought by individuals since cepo lift | **~US$44.4bn cumulative** | Apr 2025–Aug 2026 [M — BCRA via Infobae] |
| BCRA reserve purchases 2026 YTD | US$14.05bn (vs IMF floor of US$10bn) | Aug 2026 [M — IMF] |

Context for scale: inflation was ~211% (2023) and ~118% (2024). It is now roughly a sixth of the 2023 level.

**FX regime.** April 2025: Argentina moved from a 1%/month crawling peg to a **floating band** alongside a 48-month **US$21bn IMF EFF**. From 2 Jan 2026 the band adjusts with **realised inflation on a ~2-month lag** rather than a fixed 1%. IMF's May 2026 review describes a "managed float with a widening band framework," notes the peso has **appreciated ~13% in real terms** since end-2025, and confirms BCRA is buying ~US$80m/day.

**The cepo is asymmetric — and this is the commercial opening.** Lifted for individuals in April 2025. **Still in force for corporates** as of May 2026, per BCRA's own confirmation: FX access tied to customs registration for imports; 90-day intercompany payment waits; 90-day parking between official market and MEP/CCL; restrictions on pre-Dec-2023 intercompany debt; ban on corporate FX purchases for hoarding; dividend remittances only from fiscal years closed since 2025; mandatory export-proceeds liquidation under Decree 609/2019.

**[I] The corporate cepo, not retail inflation, is now the Argentine stablecoin thesis.** Retail demand has a legal alternative; corporate treasury does not. Any Argentina product built for retail dollarisation is fighting a receding tide. Any Argentina product built for corporate cross-border settlement, import financing and treasury is fighting a wall that BCRA has explicitly said it is in no hurry to remove.

The IMF programme explicitly still authorises Argentina to maintain exchange restrictions and one multiple currency practice under Article VIII — **full capital-account liberalisation is not an IMF requirement.** The programme's structural benchmarks *do* include enhanced supervision of VASPs.

### 4.1b The strongest counter-argument to my own Argentina call

I argued in §1.2 and above that Argentina's driver is receding. Two tier-1 sources sitting in `D:\Reports` push back, and the pushback deserves to be stated at full strength rather than buried.

**BIS Working Paper No. 1370, *Dollarisation and monetary control: what lessons for the rise of stablecoins?* (Hofmann, Mehrotra & Paulick, July 2026)** — foreign-currency deposit and dollar-stablecoin inflow data across 130+ economies, with a dedicated higher-frequency Latin America and Caribbean panel. Four findings that bear directly on this report:

1. **Dollarisation is a ratchet.** Deposit dollarisation is "highly persistent even after the macroeconomic conditions that may have triggered it have passed." Event study around exits from high-inflation regimes: dollarisation drifts up to ~50% approaching the exit and **stays there through t+4, with no detectable downward trend** — and the result holds even when the high-inflation threshold is lowered to 5%. AR(1) persistence coefficient ~**0.8**, similar in advanced and emerging economies, and not declining since 2000. The authors find the same persistence in stablecoin dollarisation.
2. **Capital controls don't bind on stablecoins.** Cross-border capital-flow restrictions and account restrictions generally reduce *deposit* dollarisation — but **neither those nor rules specifically restricting stablecoin use between residents and non-residents have a statistically significant effect on gross stablecoin inflows**, because stablecoins partly circulate outside the regulatory perimeter.
3. **Banking crises specifically drive stablecoin flows** — over and above what drives deposit dollarisation — "consistent with the notion that the non-bank nature of stablecoins becomes more attractive if there has been instability in the banking sector."
4. **The two markets are segmented.** Only limited evidence of substitution between dollar deposits and stablecoins, suggesting demand for stablecoins in EMDEs "largely does not stem from existing US dollar deposits, and vice versa" — different user populations.

Separately, **Dfns (§2.8) reports that Argentina's crypto dollar still trades several percent above the official rate even after the 2024–25 normalisation**, and names Argentina among the parallel-market currencies still pricing access at hundreds to thousands of basis points over official.

**The escape premium, measured.** BeInCrypto tracks Argentina's blue-vs-official premium from **above 150% in 2023 to 2% in July 2026** (Bluelytics, BCRA), with inflation at 33.6% by June 2026 and monthly at 1.9%. Their gloss is the most compact statement of the BIS finding: **"Dollar habits linger. Flows don't."** Note also that the two sources disagree at the margin — Dfns says the Argentine crypto dollar still trades "several percent" over official; BeInCrypto measures the blue premium at 2%. Different instruments (crypto dollar vs blue), so both can hold, but do not quote a single "Argentine premium" number without saying which one.

**And the ten-year purchasing-power test (§2.11) is the strongest quantitative support for the Argentine case specifically:** peso cash retained **0.8 of 100** over the decade to June 2026 — more than 99% of purchasing power erased — against 74 for dollars and 44 for a local *plazo fijo*. Every domestic option lost value; the deposit only reduced the damage. That is why Argentina is the one market in the region where "hold dollars" is not a diversification argument but a survival one, and why its demand is structurally different from Brazil's or Mexico's.

**[I] How I'd reconcile this.** My evidence for a receding driver is real and measured: the Chainalysis rank fall from 15th to 20th, the ~1.3% blue–official spread, US$44.4bn of formal-channel dollar buying. But those measure the *flow* driver — the marginal incentive to dollarise this month. BIS measures the *stock* — and says the stock does not unwind. **The defensible position is therefore narrower than the one I stated: Argentina's stablecoin demand is very unlikely to collapse, but its growth rate is normalising, and the easy arbitrage is gone.** The Nigerian comparator in the Dfns report is the cleanest precedent — the naira parallel gap collapsed from above 60% to about 2% after the float, "taking the easy stablecoin arbitrage with it," without the underlying dollar demand disappearing.

Finding (2) also weakens a claim I made: I framed the surviving corporate cepo as *the* Argentine opportunity. If capital controls have little measurable effect on stablecoin flows, then the cepo is not what gates stablecoin adoption — it shapes *who* uses it and *why*, but it is not the causal lever I implied. The corporate treasury opportunity stands on transaction economics and dollar access, not on the cepo persisting.

### 4.2 Regulation

**Ley 27.739** (14 Mar 2024) created the PSAV category and made VASPs AML-obligated subjects. **CNV RG 994/2024** (25 Mar 2024) created the registry, with an exemption below UVA 35,000/month.

**CNV RG 1058/2025** (14 Mar 2025) is the operative rule:

- Minimum capital: **US$150,000** (Cat. 1/2/4 — exchange/custody), **US$75,000** (Cat. 3 — transfers), **US$35,000** (Cat. 5 — ICO services). 50% reduction if prior-12-month volume below US$2.5m.
- Local entities must be S.A. or S.R.L. (SAS entities must convert). Foreign PSAVs must establish local presence.
- Registration deadlines: individuals 1 Jul 2025, domestic entities 1 Aug 2025, foreign entities 1 Sept 2025. First monthly reports Nov 2025; annual supervision fee ~US$10,000.

**Registry size: 50 companies + 7 individuals** — but that snapshot is from **July 2024** and is over two years stale. Current count not verified. **[gap]**

**Banks are still barred from direct crypto** under a **May 2022** BCRA prohibition — triggered when Galicia, Brubank and Ualá briefly launched BTC trading and were shut within three days. **And the ban is wider than "banks": PwC's *Global Crypto Regulation Report 2025* records that during 2023 the prohibition was extended to all payment service providers operating in the country.** That materially changes who is affected — it is why Argentine fintechs operate as CNV-registered PSAVs rather than as PSPs offering crypto, and it means a BCRA reversal would unlock distribution across the fintech sector, not just the banks. BCRA was reported to be evaluating lifting this **from ~April 2026**. **As of 31 August 2026 I could not confirm that this has been finalised.** Given today's date is four months past the target, this is a live, high-value gap: it is the difference between a market where banks can distribute stablecoin products and one where they cannot.

**The workaround is already running, and the BIND leg is now primary-sourced.** Argentine banking groups are building peso-pegged stablecoins through separately licensed virtual-asset subsidiaries: **BIND Group** via **BEN** (~US$2bn AUM), and **Petersen Group** developing **DIPE** with technology support from **Lirium** — whitepaper complete, **not yet launched**, targeting corporate treasury and programmable payments rather than consumer.

**Circle's own Q2 2026 earnings release confirms the BIND partnership** [M — Circle press release, Q2 2026]: *"Grupo Bind announced a collaboration with Circle to bring USDC access to institutions in Argentina."* Circle's stated framing is **"a major step for USDC/ARS liquidity."** That upgrades what was previously an aggregator-sourced claim to issuer-confirmed, and it is worth noting *how* Circle frames it — not as distribution or product, but as **liquidity**. The largest regulated dollar issuer in the world describes its Argentine bank partnership in exactly the terms §2.8 and §2.9 identify as the binding regional constraint.

The **Petersen/DIPE** leg remains **[U]** — still aggregator-sourced, not corroborated. Structurally both mirror the Bancolombia/Wenia pattern (§6.3), which is verified.

**LIBRA fallout.** Milei promoted the $LIBRA memecoin in Feb 2025; it collapsed with estimated investor losses of **US$100–251m**, triggering federal investigations. CNV published RG 1058/2025 the following month. The causal link is press interpretation, not an admitted fact.

### 4.3 Market

- **Chainalysis rank: 20th globally (2025), down from 15th (2024).** Volume $93.9bn, now 2nd in LatAm behind Brazil [M].
- **Stablecoin share: 61.8%** of value received (Jul 2023–Jun 2024) — highest in the region at the time; Chainalysis published only "over half" for the following window [M].
- **Lemon Cash**: **1.1m MAU in Argentina**, **US$160m assets under custody**, **US$20m Series B** (F Prime, ParaFi) Oct 2025; Sept 2025 app-share **Lemon 29% vs Binance 27%**. Regionally 4m+ validated users, 1.3m MAU [M/V — Forbes Argentina].
- **Buenbit**: ~1m Argentine users; **acquired by Nexo** (announced 11 Dec 2025), which chose Buenos Aires as its LatAm hub [M].
- **Coinbase**: launched Argentina Jan 2025 with CNV approval; **discontinued the peso–USDC pair effective 31 Jan 2026**, citing FX volatility, regulatory complexity and compliance/banking cost. Framed as "a deliberate pause, not a full exit"; Base L2 presence and Ripio partnership retained [M].
- **Ripio** launched **wARS**, an Argentine peso stablecoin, on Ethereum, Base and World Chain — **1 Nov 2025** [M — CoinDesk].
- **Belo**: Tether led a **$14m** round, April 2026; 3M+ users; three years of profitable operations; expansion targets Mexico, Chile, Colombia, Peru, Bolivia, Paraguay and deeper Brazil [M — CoinDesk].

### 4.4 The freelancer data point that breaks the narrative

**Deel platform data, May 2025–April 2026: 93% of Argentine contractors withdraw in traditional dollars; only 6% in stablecoins** [M — Deel, via Forbes Argentina].

A competing claim — "75% of crypto-paid workers in Argentina prefer stablecoins" — is sourced to a vendor blog and describes a *different, narrower population* (people already paid in crypto). The two are not comparable, and the second is often quoted as if it described the first.

**[I]** If you sell an Argentina freelancer-payments product on the premise that stablecoins are the default, the platform data says you are wrong by an order of magnitude. The realistic pitch is the 6% growing, not the 93% already converted.

---

## 5. Mexico — deep dive

### 5.1 The remittance corridor, honestly

**Banxico official series** [M]:

| Year | US→Mexico remittances |
|---|---|
| 2023 | **US$63.31bn** (record) |
| 2024 | **US$64.75bn** (+1.6%) |
| 2025 | **US$61.79bn** (−4.6%) — largest annual decline in 16 years |
| H1 2026 | **US$30.76bn** (+3.1%); June 2026 US$5.47bn (+4.2%) |

**Mexico's decline is idiosyncratic, and I under-stated that.** In the same year Mexico fell 4.6%, **remittances to the rest of Latin America and the Caribbean grew by more than 16% on average** — Honduras **+25.3%**, Guatemala **+18.7%**, El Salvador **+17.8%**, Colombia **+10.6%** [M — BBVA Research citing Banxico]. LatAm and the Caribbean received roughly **$163bn in 2024**, Mexico alone $64.7bn. So the regional remittance story is one of growth with a single large market diverging on US enforcement — not a regional slowdown. Presenting Mexico's fall as the headline without that contrast, as the earlier version of this report did, gets the region backwards.

The 2025 decline is structural, not cyclical. Drivers, all measured: ~500,000 remitters/year aging past the 30-year sending threshold against only 36,313 new Mexican migrants; border apprehensions of Mexicans down from 630,202 (2024) to ~170,000 (2025), **−73%**; ~160,000 deportations in 2025, over 90% of them established remitters; enforcement-driven labour-market withdrawal; peso appreciation. Average ticket rose from US$490 to US$520 (+6.1%) — insufficient to offset fewer senders. In H1 2026, transaction *volume* fell 1.8% YoY even as dollar value rose 3.1%; growth is coming from bigger tickets, not more senders.

**The US remittance excise tax** (One Big Beautiful Bill Act): **1%, effective 1 January 2026** [M — IRS]. Critically, it applies **only** to transfers funded with **cash, money orders, cashier's cheques or similar physical instruments**. Bank-account, debit-card and credit-card-funded transfers are **exempt**.

**The last-mile number that settles the architecture argument.** Of Mexico's *electronically received* remittances, **49.6% is still collected as cash at physical payout locations**; 50.4% arrives as bank deposits [M — Banxico via Mexico News Daily]. Nearly half of the value that arrives digitally is picked up in person, at a counter, from a licensed physical network that no blockchain reaches.

**[I]** That single statistic is the strongest available evidence for the thesis running through §2.8, §9.4 and §10.2(c): stablecoins take the **middle leg** — the interbank settlement between institutions — while origination and last-mile disbursement stay on regulated local rails. Movantis' CEO puts it more bluntly than any analyst has: *"Stablecoins solved the value movement. They didn't solve landing it in local currency, compliantly, across every market in the region. In Latam, the last mile is still the hardest mile, and it doesn't run on-chain."* Any product plan that assumes the on-chain leg is the business is planning around the half of the corridor that was already cheap.

**[I] This is the most misunderstood fact in the LatAm stablecoin pitch deck.** The tax does not push volume to stablecoins — it exempts almost every electronic rail, stablecoin ones included, along with the digital incumbents. It hits cash-in agents serving the unbanked. So the structural advantage it confers goes to *anyone digital*, which is a much weaker competitive claim than "stablecoins win." And it was not in force during 2025, so it explains none of the 2025 decline.

### 5.2 The Bitso "10% of the corridor" claim — do not use it

The claim that "Bitso processes ~10% of US–Mexico remittances" is everywhere, attributed to CEO Daniel Vogel. Cross-checking its supporting figures ($1bn processed in H1, Q1 corridor total $12.5bn, May record $5.17bn) against Banxico's actual series shows **those numbers match 2022, not 2025–26** — and CoinDesk reported the identical "$1bn in H1" figure in **June 2022**.

**Assessment: this is a four-year-old vendor claim being recirculated as current market data.** [U — high confidence it is stale.]

**But the underlying question now has a defensible answer, and it is not 10%.** BeInCrypto put both rails on one chart in the same units, from Banxico SIE plus its own Dune queries (data to May 2026):

| | |
|---|---|
| Family remittances into Mexico | **$5.6bn/month** (net inflows) |
| Bitso's stablecoin corridor | **$2.6bn/month** average across 2026; **$2.8bn** in the latest month |
| The lane, Jun 2025–May 2026 | **$63.2bn**, 157M transfers, 13.1M/month; outbound $1.2bn |
| Average remittance, May 2026 | **$404** (up from $278 in Jan 2015) |
| Argentina's average crypto transfer, retail rails | **$544** — same order of magnitude, same class of sender |
| Bitso Tron USDT monthly corridor | **~$28m (Aug 2023) → ~$480m (May 2026)** — 17x |
| Bitso annualised 2026 corridor, EVM + Tron | **$31.5bn** |
| Mexican remittances already electronic | **99%** |

**[I] Handle the comparison carefully, because the two numbers are not the same measurement.** The remittance figure is *net family inflows*; the stablecoin figure is *gross corridor volume in both directions*, and it includes B2B and treasury flow that is not remittance at all. So "the stablecoin rail is half the size of the remittance lane" is **not** a market-share statement, and anyone who reduces it to one is repeating the same error as the 10% claim in a new form.

What it does establish, defensibly: **one exchange's corridor now runs at roughly half the monthly value of the entire net family-remittance lane between the same two countries**, at ticket sizes ($544 average on Lemon; $404 average remittance) that are indistinguishable in class. BeInCrypto's own framing of the scale — its "Exodus Multiple" — is that this single corridor moves about **32x the wealth that Mexico's departing millionaires carry**. The corridor is not a niche; the *measurement* is what has been sloppy.

Set against that, the last-mile constraint below (49.6% cash collection) is what keeps this a middle-leg business rather than an end-to-end one.

What *is* datable: Bitso Business announced (18 Dec 2025) it was on track for **$82bn annualised total payment volume** region-wide, with **$15.6bn annualised** in Mexican real-time payments [V]. That is TPV across all products — not remittance share.

### 5.3 Regulation

**Ley Fintech (2018)** created IFPE (e-money) and IFC (crowdfunding) licences. **NVIO**, a Bitso affiliate, was the first authorised IFPE. CNBV's first-ever public disclosure (Oct 2024, data to Dec 2023): **50 IFPEs authorised, 37 operating**; leaders by captación share **STP 35.42%**, **Mercado Pago 30.10%**, **OXXO/SPIN 12.16%**. No updated official count found for 2025–26.

**Banxico's prohibition stands.** Circular 4/2019 restricts credit institutions and fintechs from operating with virtual assets absent prior Banxico authorisation, and only in internal/controlled schemes. The June 2021 joint Banxico/SHCP/CNBV statement explicitly barred banks from operating with cryptocurrencies. **No confirmed change as of Aug 2026.** Stablecoins are therefore **not a formally permitted payment instrument in Mexico**; MXNB and comparable products operate through IFPE and cross-border licensing rather than any dedicated stablecoin authorisation, which does not exist.

**The Murat Initiative — proposed, not law.** Introduced to the Senate **6 May 2026** by Senator Alejandro Murat. Creates a new category, **AVE** (*Activos Virtuales Estables Referenciados en Moneda Nacional* — peso-referenced stable virtual assets). Key features:

- Amends **ten** financial-system laws.
- **Banxico** becomes the primary authoriser, not CNBV.
- Issuance restricted to **licensed banks and IFPEs only** — independent issuers and startups excluded from direct issuance.
- **1:1 reserve backing** in pesos, Mexican government securities or Banxico deposits; reserves patrimonially segregated, non-pledgeable, non-rehypothecable.
- Foreign issuers must show equivalent home-jurisdiction regulation plus a Mexican legal representative; **no grace period**.
- **Criminal penalties: 5–15 years imprisonment** for unauthorised issuance.
- Framed in Mexican press as mirroring the US GENIUS Act for T-MEC alignment.

**Status as of 31 Aug 2026: no confirmed committee vote or passage.**

**[I]** If this passes as drafted, Mexico becomes a bank-and-IFPE-only issuance market with criminal liability for outsiders. That is simultaneously the worst possible outcome for a standalone stablecoin startup and one of the better outcomes for a vendor selling issuance and reserve-management infrastructure **to** banks and IFPEs. Antier is on the right side of that line.

**Digital peso: stalled.** Banxico's public target was "early 2024" (per Deputy Governor Jonathan Heath). It was missed. A transparency-request disclosure showed progress stuck at an initial phase with a budget of **10.22m pesos (~US$535,000)** — a figure incompatible with active CBDC development. Banxico has said the digital peso would be legal tender and would **not** use DLT. No current target date exists. **Note:** the widely repeated claim that "Banxico announced a CBDC for 2025" could not be substantiated; the documented target was 2024.

**The FinCEN action.** On **25 June 2025**, FinCEN issued orders under the FEND Off Fentanyl Act declaring **CIBanco, Intercam Banco and Vector Casa de Bolsa** institutions of primary money-laundering concern — prohibiting covered US institutions from sending or receiving funds, **explicitly including convertible virtual currency**, to or from them. Effective date extended to **20 Oct 2025**. Consequences: CIBanco's banking licence revoked and liquidated via IPAB; trust business to Multiva, auto-loan book to BanCoppel; Intercam's majority operations to **Kapital**; Vector's assets to Finamex. Mexico's Supreme Court upheld UIF account-freezing authority (April 2026); SAT/UIF powers expanded (March 2026).

**[I, flagged]** The obvious inference — that this tightened banking access for Mexican crypto and fintech firms — is **not established by any source found**. It is plausible and I believe it, but it is inference. Do not assert it as fact.

**Tax:** no primary SAT or SHCP source located. Every available source is SEO-tier. Treat Mexican crypto tax treatment as **unverified** in this document.

### 5.4 MXNB — correct the record

**MXNB is not Arbitrum-exclusive.** Issued by **Juno** (a Bitso company), inception **5 May 2025**, deployed across **Ethereum (17.1m tokens), Polygon (2.46m), Arbitrum (1.55m), Optimism (1.12m)** [M — RWA.xyz snapshot].

- Circulating supply **~22.2m MXNB**, market cap **~US$1.23m**.
- 30-day transfer volume **US$94.1m**, up 1,182% in 30 days.

**[I]** Read those two numbers together: a **$1.2m float turning over $94m a month**. MXNB is not a store of value — it is a settlement leg with extremely high velocity. That is the correct mental model for every local-currency stablecoin in this region, and it means "market cap" is close to a meaningless metric for them.

**MMXN** could not be verified as a distinct product. Do not list it.

### 5.5 Players

**Bitso / Bitso Business / Juno / Nvio** — the dominant regional franchise. >9m retail users LatAm-wide (Jan 2025) [V]. Last confirmed valuation is **$2.2bn from May 2021**; no 2025–26 round or revaluation found. **Félix Pago** — WhatsApp-native, USDC-funded, **$6bn+ cumulative remittances** [V]; partnered with **dLocal** (13 Nov 2025) for direct-to-bank payouts live in US→Mexico, US→Guatemala, US→Honduras, announced for El Salvador, sub-two-minute delivery. **Klar** — $190m Series C at $800m valuation (July 2025), targeting a 2026 IPO; no stablecoin product confirmed. **Circle** and **Tether** — no Mexico-specific strategy found beyond Circle's Sept 2024 SPEI integration. **Bridge (Stripe)** — launched USD↔MXN↔stablecoin API on/off-ramps **28 April 2025**, no volume minimums; early users include a superwallet provisioning MXN virtual accounts for Amazon sellers.

**Mercado Coin was a Brazil product and it is dead** (shut 2026, citing Pix). Do not attribute it to Mexico.

---

## 6. Colombia — deep dive

### 6.1 Regulation: tax rules exist, market-structure rules do not

**"La Arenera" sandbox** ran 2021 to **13 June 2024**: seven bank–exchange pairings (Bancolombia↔Gemini; Davivienda and Powwi↔Binance; Banco de Bogotá↔Bitso and Buda; Coltefinanciera↔Obsidiam; Coink↔Banexcoin; Movii↔Panda and Bitpoint). SFC's own conclusion: no incidents that put continuity at risk. **It closed without producing a framework.** Exchanges remain outside prudential supervision.

**The proposed digital assets law is stuck at the Ministry of Finance**, ready for submission with **no filing date set**. Its design is notable: it would split oversight three ways — **SFC** for specialised entities, **Banco de la República for stablecoins specifically** (on monetary-sovereignty grounds), and **DIAN** for tax and registration. Principle cited: *"misma actividad, mismo riesgo, misma regulación."*

**What *is* in force is tax and reporting:**

- **DIAN Unified Concept, 17 Oct 2023**: crypto is an intangible asset, not legal currency. Fiscal residents declare holdings at 31 Dec cost. Unrealised gains untaxed; taxed on realisation. Occasional-gains rules for fixed assets held over two years. Mining and staking income taxable at commercial value. Airdrops treated as occasional gain; swaps as barter. Electronic invoicing required for crypto-asset sales.
- **DIAN Resolution 000240**, issued **24 Dec 2025**, first observation year **2026**, first major report due **May 2027**. Implements OECD **CARF**. Reporting entities are "RCASPs." Transactions above **US$50,000** trigger automatic DIAN alerts. XML submission via RUT. Penalty up to **1% of transaction value**.

**The 4x1000 netting play — a live Colombian use case almost nobody writes about.** Colombia levies a **0.4% financial transactions tax (GMF, the "cuatro por mil") per local payment**. Per Trace Finance's CEO in the Dfns report: a business can **onramp once into a peso stablecoin, settle with suppliers and customers ten or twenty times onchain, and pay the tax only on the net amount it finally withdraws** — the same logic by which clearinghouses exist. Dfns' verdict: "stablecoins as a private netting layer for overtaxed domestic rails is a use case almost nobody writes about and operators already exploit."

**[I] This is the most interesting thing in the Colombia section, and it is durable.** It survives a Pix-clone launch (see below), because it is a *tax* arbitrage, not a speed or cost arbitrage — an instant payment rail does not net anything, it just settles faster and still triggers GMF per transaction. It is also the first argument I have seen for a COP-denominated stablecoin that does not depend on cross-border flow. Two caveats before anyone builds it: the tax treatment of on-chain settlement legs is exactly the sort of thing DIAN Res. 000240's CARF reporting is designed to make visible from 2026, and a structure whose economics depend on not triggering a levy is a structure a tax authority can close. Get Colombian tax counsel before, not after.

**Bre-B is live, and it is scaling fast — gap closed.** Colombia's central-bank instant payment system is named **Bre-B**. It **launched in October 2025** and, within six months, had processed **617 million+ transactions** and connected **218 financial institutions and 33 million users** [M — Stablecoin Insider, citing PaymentBrief and FiscalNote]. Lumx's founder described it as "close to launching" because that interview is 2025-vintage (§10.0); it has since shipped.

**[I] What this does to the Colombian thesis.** Brazil's precedent now applies directly: a free, instant, 24/7 domestic rail removes the *domestic* payments rationale for a COP stablecoin while leaving the cross-border, dollar-access and tax-netting rationales intact. Colombia's two COP stablecoins — Wenia's COPW and Minteo's COPM — are therefore in the same position as the BRL token complex: no domestic payments case, a real cross-border case. It also changes the integration target: the rail worth integrating with is Bre-B, not PSE/Transfiya, and Pix's precedent says access will require regulated-entity status or a banking-as-a-service partner. And note the corridor operators already treat it as table stakes — VelaFi lists "the per-country nuances of SPEI, PIX, CVU, and Bre-B" as the local knowledge that separates operators who can serve a corridor from those who cannot.

**Banco de la República's position** (Financial Stability Report, 2nd semester 2025, published 5 Dec 2025): notes global stablecoin market cap ~**$298.9bn** (Sept 2025) with USDT+USDC ~**90%**; flags that stablecoins are not central-bank money and lack legal-tender status. Colombia has **no formal FX-control regime** — BanRep's concern is prudential and monetary-sovereignty, not capital-control enforcement. **[I on the absence of FX controls; inferred from the absence of such language plus the bill's framing.]**

### 6.2 Market and remittances

- **$44.2bn** crypto value received, **5th in LatAm**; **stablecoins over 50% of exchange purchases** (Jul 2024–Jun 2025) [M — Chainalysis]. Colombia does **not** appear in the global top 20.
- **67% of Colombian survey respondents currently hold or have held stablecoins — the highest of any LatAm market surveyed, above Argentina's 56%** [S — BVNK, n=324]. This is a genuinely surprising result and worth interrogating: Colombia has neither Argentina's inflation nor Venezuela's collapse, but does have no retail dollar banking and a large migrant corridor.
- **Remittances 2025: US$13.098bn, +10.6%**, ~3% of GDP [M — BanRep]. **Jan–May 2026: US$5.638bn**, +5.9%, ~$38m/day; May 2026 monthly record **$1.189bn**, 24th consecutive month above $1bn.
- Corridor shares Q1 2026: **US 48.2%, Spain 17.7%, Chile third** [M — BanRep].
- Receiving departments (Jan–Sep 2025): Valle del Cauca $2.525bn, Cundinamarca $1.590bn, Antioquia $1.545bn.
- **Outbound Colombia→Venezuela remittances reached US$48m by Sept 2025**, rising with formalisation under the Temporary Protection Statute for Venezuelan migrants.
- **US→Colombia average remittance cost: could not verify** (World Bank corridor page returned 404). **[gap]**
- **Stablecoin penetration of Colombian remittances is not separately quantified anywhere.** [gap]

### 6.3 Players — and the region's most important bank case study

**Wenia (Grupo Cibest / Bancolombia)** is the most consequential single deployment in LatAm, and the structure matters as much as the product:

- Wenia is registered in **Bermuda** and licensed by the **Bermuda Monetary Authority**. Its own site states it is **not regulated in Colombia** and is independent of Bancolombia. That is deliberate regulatory ring-fencing by Colombia's largest bank.
- **COPW** — 1:1 COP-pegged, announced **May 2024**, year-one target 60,000 users (a target, not an achievement). Chainlink proof-of-reserves added subsequently. **Chain not disclosed in any source found.**
- **USDW** — 1:1 USD-pegged, launched **24 April 2026**, explicitly **replacing USDC** in Wenia's ecosystem with automatic conversion of existing USDC balances. Reserves custodied at **Bancoagrícola (El Salvador)**, a Grupo Cibest subsidiary. Convertible to COPW. Integrated into **Nequi** and **Mi Bancolombia**. Up to **6% annual reward** on savings, fee-free transfers to US bank accounts. Reported as ~**20% of Wenia ecosystem transactions** now in digital dollars.

**[I] This is the template.** A major LatAm bank, blocked or discouraged domestically, issues both a local-currency and a dollar stablecoin through an offshore-licensed subsidiary, custodies reserves at a group entity in a friendly jurisdiction, distributes through its existing 20m-user retail apps, and displaces a third-party issuer (USDC) to capture the float. Every element of that is replicable by other regional banks — and every element requires infrastructure someone has to build.

**Others:** **Bitso Colombia** — 550,000 retail active users and 2,000+ corporate clients as of 25 Nov 2025 [V]. **Littio** — USD accounts backed by USDC, Circle partnership, uses OpenTrade for yield [V]. **Minteo (COPM)** — a *competing* COP stablecoin, reportedly **>US$200m/month** in transaction volume, primarily on **Polygon** [V — company-reported via La República]. Note this is far larger than any disclosed COPW figure. **Binance Colombia** — prepaid card with Movii. **Buda.com**, **Movii**, **Minka** — present but no verifiable stablecoin-specific metrics; Minka's stablecoin activity could not be substantiated at all.

---

## 7. Rest of the region

### Venezuela
Global adoption rank **18th**; **$44.6bn** in volume, 4th in LatAm [M]. USDT functions as de facto dollarisation and remittance medium. **PDVSA began requiring new clients to pay in USDT for spot oil deals in Q1 2024**; ~**$119m in crypto sold to the private sector in July 2024** alone; Atlantic Council's assessment is that crypto is "a small share of total oil trade by value" but plays "an outsized strategic role" as a sanctions channel. **The circulating claim that Venezuela collects 80% of oil revenue in USDT is unverified and contradicted by that assessment — do not use it.** TRM Labs reports **38% of Venezuelan IP traffic to digital-asset platforms goes to a single global P2P provider** (Dec 2025). Venezuelan remittance totals could not be reconciled: three secondary sources give $4bn, $6bn and a "65% of families receive nothing" framing, none primary. **[gap]**

**Regime change — and why it probably does not open the market.** Per WEF Stories (Pablo Uchoa, 29 Jan 2026, reporting the Davos 2026 session *"Venezuela: What Next?"*), **a US operation removed Nicolás Maduro on 3 January 2026.**

> ⚠️ **Single-source, uncorroborated in this session.** This is one WEF conference report; my search budget was exhausted and I have no independent recollection of the event. The named panellists are real and appropriately credentialed, which makes the account internally credible, but **verify this against primary reporting before putting it in anything client-facing.**

What the Davos panel actually said matters more than the event itself, because it cuts hard against the obvious inference:

- **Ricardo Hausmann** (Harvard Growth Lab; former Venezuelan Minister of Planning) characterised conditions as **"coercion — marked by ongoing political imprisonment and sweeping limits on basic freedoms"** rather than stability, and said **interim authorities lack the legitimacy to establish credible investment frameworks.** His stated agenda: *"free the political prisoners, allow people to return, and set an electoral timetable."*
- **Jeffry Frieden** (Columbia) on the prerequisites for foreign investment: **"political stability, political stability, and political stability"** — explicitly questioning whether authoritarian stability suffices absent democratic transition.
- **Ilan Goldfajn** (President, IDB) said the bank requires board approval and sustainable recovery conditions before it can act.
- Hausmann flagged Venezuela's **8-million diaspora** as needing restored rights of return — consistent with the 8.3m UN DESA figure in §2.

**[I] This inverts the forecast in §10.2(g).** Tether's LatAm lead predicted that once sanctions lifted, Venezuela's use case would migrate from Argentina-style inflation hedging toward Brazil-style cross-border payments. **That migration requires exactly the institutional conditions Hausmann says are absent** — legitimate authority, enforceable investment frameworks, functioning rule of law. Regime change does not conjure a banking system for stablecoins to plug into.

The more defensible near-term read is the opposite: **Venezuela's informal, P2P, USDT-denominated dollarisation persists — and may intensify — precisely because formal financial infrastructure remains unavailable during a contested transition.** Anyone planning regulated Venezuelan corridor infrastructure on the strength of the January event is pricing an institutional recovery that the region's own development bank says it cannot yet underwrite.

**One genuine unknown worth tracking:** if 8 million people regain the right to return, Venezuela's corridor could **reverse direction** — from a remittance-receiving market to a return-migration and repatriation market. My report has Colombia→Venezuela outbound remittances at $48m by September 2025 and rising (§6.2). A large-scale return would change both the direction and the composition of that flow. Too uncertain to model; concrete enough to watch.

### Bolivia — the cleanest natural experiment in the region
BCB **Resolution 082/2024, 25 June 2024**, nullified the 2020 crypto ban. Stated driver: acute USD shortage from collapsing gas export revenue. Result [M — BCB via Bloomberg Línea]:

- **H1 2025: US$294m** in virtual-asset transactions via electronic channels
- **H1 2024 baseline: ~US$46.5m**
- **Growth: >630% YoY**
- Cumulative since enablement: **~US$430m**
- Interannual inflation 23.96% (June 2025)

Rain separately reports Bolivian stablecoin **card spend grew 6x in 2025** [V].

**Bolivia is now the region's most interesting regulatory case, not just its fastest-growing market.** Per the Stablecoin Insider report: state-controlled **Banco Unión began supporting USDT purchases through its Yasta wallet in April 2026** for international payments and remittances; **Banco FIE launched USDT buy/sell in its mobile app**; and the **Economy Ministry is formally evaluating a framework that would recognise USDT as a payment instrument circulating alongside the boliviano and the dollar**, with AML safeguards. Mandioca's transaction-level data records **parallel-market premiums of 80–95% over the official rate**, peaking near **20 BOB/USD in May 2025 (~+200%)** before stabilising when the incoming government signalled a float — against an official rate pegged at 6.86–6.96 from 2011.

**[I]** If that framework passes, Bolivia becomes the first country in the region to formally integrate a *private dollar stablecoin* into its payment system — not a CBDC, not a local-currency token. That is a materially different regulatory template from Brazil's (bring stablecoins inside the FX perimeter) or Mexico's proposed one (restrict issuance to banks and IFPEs), and worth watching precisely because it is the opposite of what the large markets are doing.

**The YPFB fuel-import-settlement-in-crypto claim could not be corroborated by any source found**, despite targeted searching, and it does not appear in the Stablecoin Insider report either. It is widely repeated. Treat as unverified.

**Also beware the $14.8bn Bolivia figure** now circulating from an issuer employee on a public panel — it is Chainalysis's cumulative three-year on-chain total for Bolivia being restated as one year of post-legalisation dollar inflow. See the Verification Ledger. Practitioner colour on the Bolivian market is in §10.2(f).

### Chile
**Ley Fintec (Ley 21.521)**, enacted Dec 2022, CMF as regulator, operationalised via **NCG 502**. **42 entities registered under Ley Fintec between 2024 and 2025** [U — search-snippet only, primary CMF confirmation needed]. **$23.8bn** volume, 7th in LatAm. **No CLP-pegged stablecoin identified** — a genuine gap in the market or in the search; worth a targeted check. **Meli Dólar (MUSD)** was piloted in Chile first, with **$65m circulation as of Sept 2025** [V — Rain report].

### Peru
**No comprehensive crypto law.** SBS oversight is AML/CFT-only via the UIF. April 2025: SBS reportedly authorised a sandbox for **Banco de Crédito del Perú** to offer Bitcoin to a 5,000-customer pilot [unverified against an SBS release]. A congressional framework bill exists but **SBS itself reportedly does not support it**. **$28.0bn** volume, 6th in LatAm. **Lemon reached 1m Peruvian users** (April 2026) and accounted for one in two crypto app downloads in Peru in 2025 [V]. **SOL Digital**, a PEN-pegged stablecoin by Anclap on Stellar, launched Sept 2021 — no 2026 status confirmed.

### El Salvador
**Bitcoin Law reformed 30 January 2025** (55 votes): mandatory merchant acceptance eliminated, tax payment in BTC repealed, Chivo Wallet withdrawn, **Bitcoin no longer legal tender** though still a recognised asset. Driven by the **US$1.4bn IMF Extended Fund Facility**. Separately, the **Digital Assets Issuance Law (LEAD)**, enacted Jan 2023 and reformed Aug 2024, consolidated **CNAD** as sole regulator, redefined stablecoins, required FATF-standard AML, and recommended a **US$1,000** transaction limit per GAFILAT guidance. **Tether announced a DASP licence and HQ relocation to El Salvador on 13 January 2025.** Volume: $3.5bn.

**[I]** El Salvador has quietly executed the pivot everyone missed: it abandoned the Bitcoin experiment and rebuilt as a **licensing jurisdiction** for stablecoin issuers. Bancolombia custodies USDW reserves at its Salvadoran subsidiary. Tether is headquartered there. That is a functioning offshore stablecoin hub for LatAm, and it is far more strategically relevant than the Bitcoin Law ever was.

### Guatemala & Honduras
Guatemala: **US$2.468bn in July 2026 alone**, Banguat's highest monthly figure on record. Honduras: **US$12.21bn full-year 2025, +25.3% YoY**. Both are among the world's most remittance-dependent economies. **No confirmed stablecoin remittance pilot in either country** — the Félix/dLocal partnership covers US→Guatemala and US→Honduras payouts, which is the closest live deployment.

### Panama
2022 crypto bill **partially vetoed** by President Cortizo (16 June 2022) on AML grounds. A 2025 second attempt exists but is not enacted. **As of Nov 2025, no comprehensive virtual-asset law is in force.** The driver now is FATF Recommendations 15 & 16 compliance ahead of a **2027 review** — Panama exited the FATF grey list in 2023 and the EU high-risk list in July 2025 and risks relisting. Panama functions as a dollar banking hub, not an issuance jurisdiction.

### Ecuador, Uruguay, Costa Rica, Paraguay
**Ecuador**: BCE states explicitly that crypto assets are neither legal tender nor an authorised means of payment. Fully dollarised, which removes the FX-depreciation driver entirely. **Uruguay**: BCU moving toward requiring dollar-denominated guarantees and user reporting from crypto platforms; no completed framework. **Costa Rica**: "vigilant tolerance," no binding rules. **Paraguay**: not researched — gap.

---

## 8. Regulatory clarity scoreboard

| Country | Comprehensive framework in force? | Key instrument | Status |
|---|---|---|---|
| **Brazil** | **Yes — the most complete in the region** | Res. BCB 519/520/521 (+561, 584) | In force, phased; **VASP filing deadline 30 Oct 2026** |
| **Argentina** | Partial — VASP registry only | CNV RG 1058/2025 | In force; bank participation still barred (lift pending, unconfirmed) |
| **Chile** | Yes | Ley 21.521 + NCG 502 | In force since ~2024 |
| **El Salvador** | Yes | LEAD (2023, reformed 2024) + CNAD licensing | In force; issuer-friendly |
| **Colombia** | No — tax/reporting only | DIAN Res. 000240 | Tax in force; market-structure bill stuck pre-Congress |
| **Mexico** | No — stablecoins have no legal category | Ley Fintech (IFPE); Circular 4/2019 | Grey zone; Murat Initiative **proposed** May 2026 |
| **Bolivia** | Partial — ban lifted, rules pending | BCB Res. 082/2024 | Enabled, unregulated |
| **Peru** | No — AML only | — | Bill proposed, SBS reportedly opposed |
| **Uruguay** | No | — | In development |
| **Panama** | No | — | Vetoed 2022; FATF pressure to 2027 |
| **Venezuela** | No | — | De facto tolerated vacuum |
| **Ecuador** | No — restrictive stance | — | BCE disclaims crypto as payment |
| **Costa Rica** | No | — | Vigilant tolerance |

### Structural demand drivers, honestly categorised

| Driver | Countries | Durability |
|---|---|---|
| **No retail dollar banking permitted** | Brazil, Colombia | **High** — statutory, not cyclical |
| **Restricted dollar banking** | Mexico (>20km from border), Argentina (volume + official rate) | **High** |
| **Corporate FX controls** | Argentina (cepo remains for corporates) | **Medium-high** — BCRA says lifting is "not a priority" |
| **Acute FX/dollar scarcity** | Bolivia, Venezuela | Medium — resolves if macro resolves |
| **High inflation** | Venezuela; Argentina (**falling fast**) | **Low and falling** — least durable driver |
| **Cross-border transaction taxes** | Brazil (IOF) | High, though 521 may extend IOF *to* stablecoins |
| **Remittance cost/friction** | Mexico, Central America, Colombia | High |
| **Full dollarisation** | Ecuador, El Salvador, Panama | No FX driver; remittance/cost driver only |

---

## 9. Rails, players and capital

### 9.1 Issuers

**Circle** integrated USDC directly with **Pix (Brazil)** and **SPEI (Mexico)** in **Sept 2024** — the only global issuer with confirmed direct national-rail integration in both large markets. Circle Payments Network added **Movantis** (April 2026, $60bn+ annual volume, 80,000+ payout locations, 10+ LatAm off-ramp countries), plus Alfred and Tazapay, and **Grupo BIND for institutional USDC in Argentina** (confirmed in Circle's Q2 2026 results — §4.2).

**CPN scale, updated from Circle's Q2 2026 release** [M]:

| Metric | Value |
|---|---|
| CPN annualised transaction volume (trailing 30 days) | **$14.7bn, +76% QoQ** |
| Enrolled financial institutions | **175, +29% QoQ** |
| USDC in circulation | **$73.3bn, +19% YoY** |
| USDC on-chain transaction volume, Q2'26 | **$14.8tn, +151% YoY** (raw, not bot-adjusted) |

This supersedes the **$8.3bn annualised as of March 2026** figure carried in earlier versions of this section — CPN has roughly **doubled in one quarter**. Given that Movantis (50+ money transmitters, 90,000+ payout locations, $63bn annual volume) settles its interbank leg through CPN, a meaningful share of that growth is plausibly LatAm corridor flow, though Circle does not break out geography.

> **Do not compare the $14.8tn to the volume figures elsewhere in this report.** It is raw on-chain USDC transfer volume. Visa's bot-adjusted measure puts total stablecoin volume at $1.79tn for June 2026, and Artemis's "organic payments" measure at ~$122bn annualised. Three methodologies, three orders of magnitude. §2.6 covers the distinction.

**Two further items from the same release worth holding.** Circle received final approval for **Circle National Trust** (federal charter) and **Circle New York Trust**, and **Arc launches on public mainnet 16 September 2026** with 100+ ecosystem builders and validators including BlackRock, DTCC, Galaxy, Global Payments, ICE, Mastercard, MoneyGram, SBI, Standard Chartered, Sumitomo and Visa. Neither is LatAm-specific, but a chartered issuer running its own settlement chain changes the counterparty question for any bank-issuance engagement in §11.5.

**[I] One claim in that release to treat carefully.** Circle reports that **99.3% of x402 agent-payment volume settles in USDC**. True, and close to meaningless: x402 network-wide volume runs at roughly **$41,800/day and is down ~93% year-to-date**, with Artemis estimating about half of it is wash or self-dealing. Near-total share of a market this small is a positioning statement, not evidence of an agentic-payments business.

**Tether** dominates volume, relocated HQ to **El Salvador** under a DASP licence (Jan 2025), and is now an **investor**, not just an issuer — leading Belo's $14m round (April 2026) to expand across Mexico, Chile, Colombia, Peru, Bolivia, Paraguay and Brazil.

**Bridge (Stripe)** launched Mexico USD↔MXN↔stablecoin on/off-ramps April 2025, Brazil planned; partnered with **Visa** (March 2026) for stablecoin-backed card issuing in 100+ countries.

**Local-currency stablecoins:**

| Token | Issuer | Chain(s) | Launch | Measured traction |
|---|---|---|---|---|
| MXNB | Juno (Bitso) | Ethereum, Polygon, Arbitrum, Optimism | May 2025 | $1.23m cap; $94m/mo transfers [M] |
| COPW | Wenia (Grupo Cibest) | not disclosed | May 2024 | 60k-user target only [V] |
| USDW | Wenia (Grupo Cibest) | not disclosed | 24 Apr 2026 | ~20% of Wenia transactions [V] |
| COPM | Minteo | Polygon | — | >$200m/month claimed [V] |
| wARS | Ripio | Ethereum, Base, World Chain | 1 Nov 2025 | none disclosed |
| Meli Dólar (MUSD) | Mercado Pago | not disclosed | Chile pilot | $65m circulation, Sept 2025 [V] |
| BRZ | Transfero | multi-chain | pre-2024 | none obtainable |
| BBRL | Braza Bank | Polygon | Feb 2026 | none disclosed |
| BTG Dol | BTG Pactual | Polygon | 2023 | **being retired → USDC, Jul 2026** |
| SOL Digital | Anclap | Stellar | Sept 2021 | none current |

Aggregate BRL-pegged supply was ~**US$23m** in June 2025, with transfer counts up 10x YoY and average ticket up **330%** to R$12,600 [M — Dune]. **Superseded for the category as a whole:** the Iporanga Research tracker puts BRL + COP + MXN combined at **~$166m across ten issuers, up 3.6x from $46m in 2025**, with ~$8.0bn of 2026 transfer volume (§2.9). It adds issuers missing from the table above — **BRLV** (now the largest by supply), **BRLm**, **BRL1**, **cREAL**, **cCOP**, **MXNe** and **MXNt** — and shows that **aggregate DEX liquidity for the whole complex is $1.56m across 21 pools**, with the deepest at $188,900.

### 9.2 Rails, PSPs and orchestration

**Live and material:**

- **Bitso Business** — $82bn annualised TPV (Dec 2025); 45% of institutional volume is B2B/corporate treasury [V].
- **Félix Pago** — WhatsApp-native, USDC-funded; $6bn+ cumulative; **dLocal** partnership live US→MX/GT/HN, announced for SV; sub-2-minute delivery [M/V].
- **dLocal** — confirmed stablecoin user, not just observer: launched a stablecoin product across 44 emerging markets plus a B2B partnership with Stable Sea.
- **Trace Finance** — **$32m Series A led by CoinFund, 18 June 2026**; investors include Coinbase Ventures, Haun, Jump Crypto, Valor, Paxos, Chainlink Labs, plus angels Sean Neville (Circle co-founder), Anatoly Yakovenko (Solana), Ricardo Villela Marino (Itaú board). $10bn+ processed; describes itself as infrastructure for "the top four global payment providers in LatAm, including dLocal." Brazil-primary.
- **Yellow Card** — **$40m strategic round, 7 Aug 2026** (Sony Innovation Fund, SC Ventures, Polychain, Blockchain Capital); pivoted from African retail exchange to pure B2B infra serving Visa, Mastercard, PayPal, Coinbase; funds explicitly earmarked for **LatAm local rail and currency expansion**.
- **Conduit** — $36m Series A (May 2025); powers Braza Bank's stablecoin FX swaps.
- **Zerohash** — Visa Direct stablecoin payouts and prefunding (Aug 2026); Marqeta partnership (July 2026); states regulatory footprint including Latin America.
- **Takenos** — LatAm remittance app on Solana, $560m+ processed, ~20% MoM growth in 2025, $10m seed co-led by Variant and Lattice [V].

**Card rails:** Visa's stablecoin settlement hit a **$7bn run-rate** across nine blockchains; 85+ company crypto partner programme (March 2026). Mastercard extended settlement to stablecoins (June 2026) and **completed the ~$1.8bn BVNK acquisition on 3 Aug 2026**. **Rain** ($24.5m, Norwest) reports card spend growing **100% YoY**, with Bolivia spend up 6x in 2025 and Colombian cardholders up 64x since the start of 2025 [V — Rain's own report].

**Rail integration reality check:** Circle has confirmed direct integration with **Pix and SPEI**. For **PSE/Transfiya (Colombia)** and **CBU/CVU + Transferencias 3.0 (Argentina)**, **no tier-1 source confirms direct stablecoin-provider integration**. That is a real, specific infrastructure gap.

### 9.2b What a "dollar account" actually is — a product audit worth stealing

BeInCrypto read the terms, fee schedules and help pages of **twelve LatAm dollar-account products** (July 2026) and scored eleven fields including jurisdiction, deposit insurance, FX spread and stablecoin use. The question: *where does the dollar legally live?*

- **2 of 12 hold customer balances in real, insured US bank deposits** — **Nomad** (US bank CFSB, FDIC $250k + SIPC) and **Avenue** (US bank Coastal, FDIC + SIPC).
- **5 of 12 have a USD balance that IS a stablecoin, by their own terms** — **DolarApp/ARQ** (on-chain, Circle — "the balance is USDC"), **Littio** (Cayman SPC, USDC lent for yield), **Belo** (on-chain USDT/USDC ledger), **Lemon** (on-chain + Bridge, USDt balance), **Mercado Pago MX** (on-chain).
- **Your dollar may legally sit in six different places:** the US, Cayman, Singapore, Argentina, Panama, or on a blockchain.
- Others: **C6 Global** (C6 Cayman branch, no insurance stated), **Inter Global** (US custodial accounts, transmitter ledger, not FDIC), **Wise** (safeguarded e-money), **Revolut BR** (Singapore trust entity), **Global66** (Panama entity, undisclosed ledger, insurance described as contradictory).

Their taxonomy is the useful part: **"Home" = you can invest and accumulate. "Door" = you can hold and spend.** Only four products score as unqualified Homes.

**[I] Two implications, and the second is the commercial one.** First, a consumer-protection and regulatory exposure sitting in plain sight: five products marketed as dollar accounts are stablecoin balances with no insurance, and the report's dry note is that "most users never read that page." When a LatAm regulator eventually reads it — and Brazil's Res. 520 client-asset-segregation rules show the direction of travel — the disclosure and structuring work lands on the providers. Second, for Antier: **this is a product-architecture map of who has built a Home and who has only built a Door**, and the gap between the two is exactly the custody, segregation, insurance-plumbing and investment-rail work that §11.3 and §11.5 describe. Nubank's Director of Crypto frames the same need from the buyer's side: the region wants infrastructure that lets people "build, invest, and keep wealth locally while staying connected globally."

**Supporting scale data from the same report:** Visa has **140+ stablecoin card programmes live globally, "a great part of them in Latin America"**; Visa's LatAm Director of Digital Currencies also notes that **retail is "a little more than 1% of the transactions"** — the volume is institutional and B2B — and that while banks now let clients *buy* stablecoins, "solutions of transaction with stablecoin, there is still a lack on that yet." **Puerto Rico** is named as one of the region's biggest stablecoin hubs, and **Lemon** as the largest crypto wallet in LatAm, settling with Visa in stablecoin.

### 9.3 Capital and consolidation, 2024–2026

| Company | Round | Amount | Date | Lead |
|---|---|---|---|---|
| Conduit | Series A | $36m | 28 May 2025 | — |
| Klar (Mexico) | Series C | $190m @ $800m | Jul 2025 | — |
| Lemon (Argentina) | Series B | $20m | Oct 2025 | F Prime, ParaFi |
| Belo (Argentina) | — | $14m | 28 Apr 2026 | **Tether** |
| Rain | Growth | $24.5m | ~May 2026 | Norwest |
| Trace Finance (Brazil) | Series A | $32m | 18 Jun 2026 | CoinFund |
| Yellow Card | Strategic | $40m | 7 Aug 2026 | Sony IF, SC Ventures et al. |

**M&A:** Mastercard→BVNK (~$1.8bn, completed 3 Aug 2026). Stripe→Bridge. Nexo→Buenbit (Dec 2025). Binance→Sim;paul (Brazil, approved Dec 2024).

**And the retreat:** Coinbase paused Argentine peso–USDC trading effective 31 Jan 2026, citing FX volatility, unclear regulation and high compliance and banking-infrastructure cost. **[I]** One of the best-capitalised firms in the industry concluded that the unit economics of a LatAm local-currency pair did not work under the current regulatory load. That is a datapoint about the market, not about Coinbase.

### 9.4 The pilot-to-production gap — the most useful single statistic in this report

[M/S — Fireblocks, *Financial Grid: Latin America*, 2026]

- **$1.2bn** in LatAm local-currency stablecoin volume on Fireblocks (trailing 12 months), **+440% over two years**.
- **Over 50% of regional financial institutions are in active pilots. Only 14% are in production.**
- Top blocker: **internal governance — 47% regionally, the highest of any region globally.** Mexico 71% and Brazil 68% cite security and resilience.
- **75% of LatAm respondents call institutional custody and wallet governance "critical" — 13 points above the global average.**

Earlier Fireblocks LatAm survey (June 2025): 71% cite cross-border payments as the primary use case (vs 49% globally); 86% have partnerships in place; only 29% cite regulatory uncertainty as a barrier (vs 41% globally); only 7% cite lack of expertise — the lowest of any region.

**[I]** Read those together and the diagnosis is unambiguous. LatAm institutions are not blocked by strategy, appetite, partnerships or regulatory fear. They are blocked by **governance, custody and operational-control infrastructure** — 36 percentage points of institutions stuck between pilot and production. That gap is the product.

---

## 10. Practitioner ground truth — operator panels and interviews

Everything in this section is graded **[P]** unless otherwise marked. It is worth reading because it describes *mechanism* — how the money actually moves and where it breaks — which no analytics vendor publishes. Several headline numbers do not survive checking; those are in the Verification Ledger.

### 10.0 Dating caveat — read this first

**None of these transcripts carries a reliable date, and internal evidence says they are not all recent.** This matters because Brazil's regulatory position changed three times in nine months, so a statement's date determines whether it is current or superseded.

- **The three Stablecoin Conference LatAm interviews (Mexico City) date to 2025, not 2026.** Four independent markers: the Conduit interviewee says he is "eager to catch up with you next year in 2026"; he dates SWIFT as "built 52 years ago, 1973" (1973 + 52 = 2025); Lumx's founder expects Brazilian VASP regulation "by the end of October… start running in January," which matches Res. 519/520/521 published 10 Nov 2025 and effective 2 Feb 2026 — i.e. he is speaking *before* publication; and he notes "the president of the central bank changed between last year and this year," which places the conversation in 2025 (Galípolo succeeded Campos Neto in January 2025). **Treat everything in §10.4 as a late-2025 snapshot.**
- **The Utila builder panel is later — roughly Q1–Q2 2026, not August 2026.** Markers: Lumx's founder says "we *finally* got a regulated market in Brazil" (so post-February 2026); Tether's lead describes Bolivia as having "one year and a half of legalisation" (June 2024 + 18 months ≈ December 2025); several panelists date Bolivian trends "since January."

**I dated the Utila panel to August 2026 in the previous version of this report. That was wrong** — it was the upload date, not the recording date, and I should not have inferred one from the other. Corrected here.

### 10.1–10.3 The Utila LatAm builder panel

Source: Utila *Stablecoin Builder Series*, episode 7, "Stablecoins in LatAm" (transcript; recorded ~Q1–Q2 2026, see §10.0). Panel: **Kaio**, founder, Lumx (Rio; cross-border payments since 2022); **Andrés Kim**, LatAm expansion lead, **Tether**; **Chava**, Chief Product Officer, **Movantis** (the merged Trans Network / InSwitch / Spectrum / Arisa); **Cristóbal**, partnerships, **Global66** (Chile); **Leandro Meneses**, founder/CEO, **Mandioca** (LatAm export collections). Host: Utila (claims 200+ institutions, ~$20bn monthly volume — [V]).

### 10.1 What the panel independently corroborates

- **"LatAm is not a single market"** was said unprompted by four of five panelists. Tether's own LatAm lead gives the country split: **hedging in Venezuela and Argentina, arbitrage in Colombia, cross-border payments in Brazil.** Note that one — *arbitrage* as Colombia's leading use case, from the largest issuer's regional lead, is not how Colombia is usually pitched, and arbitrage is a materially lower-quality demand base than remittances or trade settlement. It also sits oddly next to Colombia's 67% survey-measured ownership (§6.2). Worth probing before building a Colombia thesis.
- **Drex's afterlife.** Kaio: "the project failed but the idea stayed." The incumbents and banks that were in the Drex pilot "are now doing the same things that they did before but using stablecoins" — and he locates that activity in **capital markets**, not payments, arguing Brazil's capital-market rails need reshaping more than its payment rails do. This is market-side corroboration of the inference in §3.4, from someone with no stake in the CBDC narrative.
- **The Brazilian FX-tax arbitrage was real and is closing.** Kaio confirms stablecoins in Brazil "have been leveraging this regulatory arbitrage," saving companies "tons of millions of dollars" against traditional rails — and volunteers, unprompted, that "this specific situation is more time-sensitive. I don't know how long this will last." That is an operator confirming the §3.3 IOF pathway and the §3.2 spread compression from the inside.
- **The bottleneck is the fiat boundary, not the chain.** Chava: even real-time domestic payment networks "have cut-off times, they don't operate 24/7." Bridging on- and off-ramp is where the engineering goes.

### 10.2 New material worth acting on

**(a) BRL stablecoins as synthetic non-resident accounts — the most commercially interesting thing said on the call.**
Kaio's account of what is actually driving BRL-stablecoin growth is *not* payments. Brazil's non-resident BRL account (*conta de não residente*) is heavily bureaucratic and effectively out of reach unless you are a regulated offshore financial institution. A BRL stablecoin wallet functions as a synthetic BRL account for a non-resident — "you can just spin up a wallet and give them a BRL stable coin and now they have a BRL account." Layer on Brazilian sovereign yield at roughly **15% nominal**, and the same rail becomes a distribution channel for offshore access to Brazilian fixed income.

**[I]** That is a tokenisation and RWA-distribution product wearing a stablecoin costume, and it is squarely in Antier's lane — closer to §11.4 (bank issuance) than to anything in payments. **The caveat is severe:** Res. 521 pulls stablecoin↔fiat conversion into the FX perimeter precisely to catch structures that substitute for regulated FX and account access. Build this as a licensed product with a Brazilian regulated counterparty, or do not build it.

**(b) "Over 10 BRL-pegged tokens" in Brazil** (host, [P]). Corroborated in structure by the Iporanga tracker, which lists **five BRL issuers alone** among the nine tokens it considers to have sufficient activity to track — and explicitly excludes smaller issuers, so the host's "over 10" is plausible for the full field. Against a whole-region local-currency supply of ~$166m (§2.9), that is a shakeout in progress — consistent with BTG retiring BTG Dol. The near-term opportunity in local-currency Brazil is consolidation and infrastructure, not another token.

**(c) The stablecoin sandwich is ~80% of volume and it has *more* intermediaries, not fewer.**
Kaio's walkthrough of a BRL→USD transfer, which is the clearest public description of the actual flow I found anywhere in this research:

1. Fiat collection — a Pix transfer into a Brazilian bank account.
2. Conversion to stablecoin via a **local** liquidity provider — which, post-Res. 519/520, must itself be regulated in Brazil or partnered with a regulated local entity.
3. Transfer of the stablecoin from **local custody to offshore custody**, to the partner handling the last mile.
4. Conversion to destination local currency.
5. Local fiat payout to the beneficiary account.

The named roles are **OFI** and **BFI** — originating and beneficiary financial institutions, the parties holding local fiat licences in each jurisdiction — plus liquidity providers, who may or may not be the same entity. His verdict: "we always say that [stablecoins remove] intermediaries but you can actually have a lot of intermediaries too." Easier and faster, and "not always but most of the time cheaper." Roughly **80% of Lumx's volume is still sandwich**; native stablecoin settlement at either end is "in the process of ramping up."

**[I] This is the most important correction in the whole panel.** The value proposition being sold across this industry — disintermediation — is not what operators actually get. What they get is speed and, usually, cost. What they *lose* is certainty about where the money is, because the failure modes are worse: if the liquidity provider or the last-mile partner fails mid-flow, the client's money has already moved and the transaction must be unwound. Kaio names granular transaction monitoring and a very fine-grained transaction engine — knowing exactly where the money is and exactly what to do when each step fails — as what Lumx invested most in. **Orchestration and observability is a buildable product. "Removing intermediaries" is a slide.**

**(d) The build-vs-buy line, from three operators who have already made the call.**

| Operator | Own it | Buy it |
|---|---|---|
| **Mandioca** (Leandro) | Treasury and wallets ("without control of the treasury… you're never going to have control"); compliance and KYB/KYC — **custody your own documentation even when using a third-party provider**; technology | Liquidity — but treat proximity to the liquidity source as a *margin* decision, not a control one: the closer you are, the tighter the spread |
| **Movantis** (Chava) | Orchestration end-to-end; both end clients | Wallet infrastructure, liquidity, KYT — "those jobs are much better done by experts than developing them in-house, which could take a very long time to market" |
| **Global66** (Cristóbal) | Whatever you are actually good at | The rest — but note the trap: **one partner for everything costs you control and visibility; too many partners fragments the service and destroys the speed and visibility you were buying.** Land and expand. |

Also from Global66, and useful for anyone pitching a fintech: they did not choose stablecoins. Their users were already transacting in them and demanded a fiat bridge. When they shipped receive-into-wallet and then payout-to-external-address, "the volume came along pretty quick… the flow was like there from day one." Demand-pull, not vendor-push.

**(e) Product design principle worth stealing wholesale.**
Cristóbal's rule: **abstract everything that creates confusion or anxiety; surface everything that builds confidence.** Abstracted — gas management (Global66 absorbs it), chain mechanics, the existence of the blockchain leg at all. Surfaced — real-time status, exactly where the money is at any moment, the FX rate applied at the moment of conversion, the final amount that will land. B2B needs more: configurable timestamps and an API so they can build their own reporting.

Chava's institutional sequence is the same idea applied to sales: lead with speed, cost and security and **do not mention stablecoins**; prove the unit economics; then disclose the rail; then offer the white-labelled wallet and card. "Oh, by the way, it just so happened to be a stablecoin wallet product." He frames the end state as democratising the USD account — a product that in LatAm "was typically reserved only for highly affluent customers." That framing is consistent with the dollar-banking-access thesis in §1.3, and it is a better pitch than inflation.

**(f) Bolivia ground truth.** Both Leandro and Tether's LatAm lead named Bolivia as the market they are watching most closely. Reported on the call: importers now quote spread **against USDT**, not against USD; the **Binance P2P rate functions as the de facto reference rate** rather than the central bank's; banks are beginning to take USDT and to move into prepaid cards; the domestic QR payment scheme is being connected to stablecoin wallets; and USDT is displayed as a currency at **Viru Viru airport in Santa Cruz**. Directionally consistent with the measured **630% YoY** growth in §7 — but note that the same speaker's headline Bolivia number is wrong (Verification Ledger).

**(g) Venezuela after sanctions.** Tether's LatAm lead, who is Venezuelan, expects that if sanctions lift, Venezuela's dominant use case migrates from Argentina-style inflation hedging toward **Brazil-style cross-border payments**, because the economy is heavily import/export dependent and firms have already learned the rails out of necessity. A forecast from an interested party, not data — but a coherent one, and it implies the Venezuelan opportunity is trade settlement infrastructure rather than retail dollarisation.

### 10.4 Stablecoin Conference LatAm, Mexico City — three operator interviews (2025 snapshot)

This is the conference whose agenda would not load in §10.5. The interviews establish what the page could not: **Mexico City, powered by Bitso Business, at least two days of programming.** All three are 2025-vintage (§10.0).

#### (a) Lumx — the tokenisation-to-stablecoins pivot, and why Brazil does *not* need a BRL payment stablecoin

Same founder as the Utila panel, but this interview is earlier and more candid.

**Lumx started in 2022 as a tokenisation platform and wallet-infrastructure provider** — "literally no joke anything": carbon credits, real estate, receivables, fan tokens, NFTs. They pivoted to stablecoins for three stated reasons: tokenisation traction was not materialising; the value would take **~five years** to arrive; and stablecoins were a near-term solution customers already wanted. His warning is the useful part: they had built product **explicitly aligned to the central bank's Drex agenda**, and concluded "it's not that good to build your own company following an agenda that can change."

**[I]** For a firm that sells tokenisation platforms, that is the single most important sentence in all four transcripts. An operator who built to a central bank's tokenisation roadmap, in the most advanced tokenisation market in the region, abandoned it on a five-year-payback judgement — and was then vindicated when the agenda changed. The lesson is not "don't do tokenisation." It is: **do not let a public-sector roadmap be the demand thesis.** Every LatAm tokenisation pitch should be underwritten by a paying private use case that survives the roadmap being cancelled.

**"In Brazil we don't need a local BRL stablecoin to do payments."** Stated flatly, by the founder of a Brazilian stablecoin infrastructure company. The reasoning: Pix is instant, 24/7 and almost free; BRL↔USDC/USDT liquidity is deep; and Lumx has bank liquidity for BRL against stables. This is a stronger version of the §3.5 conclusion, from someone with every commercial incentive to say the opposite.

**Where BRL stablecoins *do* make sense — expanding §10.2(a) with the mechanics.** Getting a Brazilian non-resident account (NRA) took acquaintances of his **three to four months** as individuals; for businesses it is faster but **requires a regulated entity in a recognised jurisdiction** — he gives the concrete example that holding a **US MSB licence** is what makes a Brazilian NRA obtainable, because the regulator can see someone is supervising you. A BRL stablecoin wallet collapses that. And the second leg is capital markets: an offshore investor funds a wallet in stables, and the stablecoin partner handles conversion and application into specific Brazilian assets. His words: "capital markets will be very, very transformed based on this new structure of BRL stablecoins."

**The embedded-finance deal worth studying.** A signed but unlaunched client (name withheld; launch was slated for "mid to end of September"): a **SaaS for import/export management through which roughly 25% of Brazil's trading volume passes — "one trillion reais."** It has **no payments functionality at all** today — it is supply-chain management plus AI market data, and banks already use it as a data platform to underwrite credit to those importers and exporters. Lumx is embedding a stablecoin wallet plus **USD and EUR virtual accounts**, so a Brazilian exporter can receive USD locally without holding a USD bank account.

**[I]** This is the highest-leverage go-to-market pattern in the transcripts and it is not a payments-company pattern. The distribution is a vertical SaaS that already owns the workflow and the counterparty graph; the stablecoin rail is embedded underneath. Note also what Lumx says about who they actually sell to: mostly **FX brokers** intermediating for multinationals, not the multinationals themselves, because the corporates lack the in-house engineering to integrate an API-first product — which is why Lumx added a dashboard. **For Antier: the buyer for corridor infrastructure in Brazil is the broker or the vertical SaaS, not the corporate.**

**Pix, precisely.** Its formal name is **SPI** (*Sistema de Pagamentos Instantâneos*); Pix is the consumer-facing brand. Built by the central bank, with open-source code, but production access requires being a regulated entity — a bank or a **PI** (*instituição de pagamento*) — or plugging in through a banking-as-a-service provider. He estimates 60–70% of Brazilian transactions now run through it and says it has surpassed India's UPI as the largest instant payment system in the world. (He hedges his own dates; §3.5 has the audited BCB figures — use those.)

#### (b) **Colombia is building a Pix clone — and this partly closes one of my "white space" claims**

Lumx's founder, citing **Bruno Batista**, a former Brazilian central bank employee involved in both Pix development and the Drex pilot, now a partner at a LatAm fintech VC: **Colombia is close to launching its own instant payment system, "heavily inspired by" Pix — "to not say a copy of" — after the Colombian government approached the Brazilian central bank to learn how it was built.**

**[I] and a correction to my own analysis.** In §9.2 and §11.6 I flagged "no confirmed stablecoin integration with Colombia's PSE/Transfiya" as white space. If Banco de la República is standing up a central-bank-operated instant payment system on the Pix model, then the integration target is about to change entirely — and the Brazilian precedent says a free, instant, 24/7 domestic rail **removes** the domestic payments case for a COP stablecoin while leaving the cross-border case intact. That would put Colombia's two COP stablecoins (Wenia's COPW, Minteo's COPM) in the same position BRL tokens are in: no domestic payments rationale, a real cross-border and account-access rationale.

**Unverified and important.** I could not confirm the system's name, launch date or status — the search budget was exhausted and the Banco de la República fetch was blocked. Colombia's instant payment scheme is, to my knowledge, branded **Bre-B**, but I am not treating that as established here. **This is the highest-value open item in the report; it should be checked before any Colombia strategy is built.**

#### (c) Mesh — the PYUSD distribution model, and a competitive dynamic not otherwise in this report

Naveen, SVP Strategy/Operations/Execution. Mesh describes itself as "the **connectivity layer** to enable stablecoin payments" — connecting sources of funds (wallets, exchanges) to destinations (PSPs, merchants) and orchestrating the payment, so neither the user nor the merchant handles the conversion. Positioning, in their own framing: **"Plaid for crypto connectivity, with a Visa-like network of destinations,"** taking a deliberately neutral "Switzerland" stance across issuers, chains and wallets.

- Formerly **Front Finance** (TradFi account-aggregation APIs), pivoted to crypto wallets and exchanges on the same integration thesis. **300+ integrations.**
- **Exclusive global crypto partner to PayPal for PYUSD** [V — company statement, not independently verified]. Cited scale: **~300,000 PayPal merchants** (he self-corrects from "300 million").
- Product: **"smart funding."** The user picks pay-with-crypto; Mesh handles chain, asset and route. Critically, **the swap executes on the connected exchange** — so the exchange earns the trading revenue even as funds leave, which is what makes exchanges willing partners rather than obstacles.
- Merchant side: hold PYUSD, off-ramp to local currency, or split (his example: 80% local / 20% PYUSD). **PayPal is incentivising the stablecoin path with lower fees.**
- Beyond commerce: a direct integration with **stake.com** for iGaming pay-ins — a category where banking access is chronically hard and crypto pay-in share is already high.
- Partners: **Bridge** for orchestration and geographic coverage; **Paxos** as PYUSD issuer.
- Funding: **$83m Series B, ~$135m total.** Monetisation: basis points on orchestrated volume, charged mainly on the merchant/PSP side, plus fee arrangements with exchanges.

**[I] Why this belongs in a LatAm report.** It is a working template for **using a payments network to grow a stablecoin's float** — every pay-with-crypto transaction routes value into PYUSD, and merchant optionality is tilted toward holding it with a fee incentive. He is explicit that LatAm is where merchants are most likely to *keep* the stablecoin rather than convert, "because local currency has a lot of fluctuations." That is a distribution playbook any bank or PSP issuing a local stablecoin can copy — and it is a competitive threat to §11.5, because if PYUSD-style rails reach LatAm merchants first, a bank's own coin has to displace an incumbent rather than fill a vacuum. Also note the honest constraint from the same interview: pay-with-crypto checkout is "still clunky," and asking a payer which chain and which asset produces "extreme drop-off." **Abstraction is the product** — the same conclusion as §10.2(e), reached independently.

#### (d) Conduit — scale, banking stack, and the "benefits without holding" requirement

Omid, VP Partnerships (ex-Robinhood, ex-Google LatAm; ~2 months in role at time of recording).

- Cross-border **B2B** stablecoin payments. **Over $50m raised** — Dragonfly, Coinbase Ventures, Circle Ventures, plus fintech investors. (§9.3 records the $36m Series A of May 2025; "over $50m" is the cumulative figure.)
- **Headed toward a $10bn annualised run rate; grown 16x in the past year** [V].
- **~24 banking partners globally**, with direct integrations into local banking rails as the stated differentiator; **130+ markets** reachable via partners where direct integration does not yet exist.
- Two products, two segments: a **web portal** for companies transacting for themselves, and an **API** for clients whose own customers need the rails.
- Licence strategy is explicitly economic: acquiring its own licences (Hong Kong and Mexico named) because operating through licensed partners "comes inherently with a cost" that gets passed to clients.

**The single most sellable insight in the interview:** traditional institutions "are very uncertain about the idea of holding stablecoins themselves… they want to benefit from the technology" but do not want stablecoins on their balance sheet, in their accounts, or to sit in the line of the funds flow. They are buying **exposure to the rail without custody of the asset**.

**[I]** That is a precise product specification, and it maps directly onto the Fireblocks 50%-piloting / 14%-in-production gap in §9.4. The institutions stuck between pilot and production are not asking for a better wallet. They are asking to never need one. Any Antier offer to a LatAm bank or PSP should lead with the non-custodial, off-balance-sheet construction, not with wallet features.

He also independently reproduces Lumx's sandwich point in better language: **"you can do the stablecoin piece, but the bread on the outside, you still depend on the banking rails of the markets you're operating in."** And on trade patterns: 20 years ago most LatAm countries' largest trading partner was the US; today it is largely China — so the growth corridors are the *thinner*, less liquid ones, where SWIFT takes five-plus days rather than two. That is a better argument for LatAm–Asia corridor infrastructure than anything in the vendor literature, and it aligns with Mandioca's Bolivia/Colombia→China observations in §10.2.

Three of his figures do not hold up; see the Verification Ledger.

### 10.5 A note on the other two sources supplied

**stablecoinconferencelatam.com/agenda** — the agenda loads dynamically through Whova and returns nothing to a fetch. All the page yields is that the next edition is **June 2026**, with five tracks (Payments, Regulation, Business Adoption, Security, Trends) under the tagline "The new TradFi runs on stablecoins." The interviews in §10.4 fill in what the page could not — the conference runs in **Mexico City**, is **powered by Bitso Business**, and runs at least two days — but they are from the **2025** edition. If the 2026 speaker list matters, someone needs to open it in a browser.

**stablecoininsider.org, "The LATAM Stablecoin Economy 2026" — I judged this too harshly, and I was working from a web summary rather than the document.** The full 70-page report (Stablecoin Insider, Q3/August 2026, author Chiara Munaretto) later turned up in `D:\Reports\Stablecoins`. Having read it, the correct assessment is more useful than "don't source from it":

- **It is a sponsored report.** The five operators profiled as case studies — **Mandioca, Pomelo, Rise, VelaFi, Movantis** — are also the five sponsors on the cover and in every page footer. Its own disclaimer says figures labelled "company data" are those operators' internal records, "shared for citation in this report." That is the single most important thing to know about it: the case-study numbers are unaudited self-reporting by commercially interested parties.
- **Several headline figures route through secondary aggregators rather than the primary sources named** — GO Markets for the $730bn/$324bn pair, AMBCrypto for the McKinsey/Artemis B2B numbers, The Defiant, Transak. When it says "Source: Chainalysis," check whether that means Chainalysis or an intermediary citing Chainalysis.
- **But it cites and links sources throughout, its regulatory table is accurate and current, and it closed two of the hardest open items in this report** — Bre-B's launch and scale (§6.1) and the 3.5% IOF charge (§3.3). Its central-bank-sourced and World Bank-sourced material is usable.

**Working rule:** treat every "company data" figure as a vendor claim, verify anything routed through an aggregator, and use the regulatory and official-statistics material freely. My earlier blanket dismissal was wrong.

---

## 11. Where Antier can actually sell

Ordered by evidence strength, not by attractiveness.

### Tier 1 — dated, mandatory, imminent

**1. Brazilian VASP authorisation and compliance build-out.** Deadline **30 October 2026**, eight weeks out. Every exchange, PSP, wallet and foreign platform serving Brazilian residents must file, then operate under Res. 520's regime: client-asset segregation, three-director governance, daily balance and custody reporting, monthly reserve attestation, staking disclosure, security and business-continuity requirements. Res. 521 layers FX reporting on top from May 2026. Res. 584 requires a **24-hour hold engine with documented risk-based early-release logic** from 1 Jan 2027 — that is a build, not a policy. If the "~120 informal providers" figure is even directionally right, the addressable base is large and the deadline is not negotiable.

*Why this is Antier's:* it is engineering work with a statutory deadline, not a strategy sale.

**2. CARF/DeCripto and DIAN Res. 000240 reporting infrastructure.** Brazil's DeCripto (monthly reporting from July 2026, >US$50,000 flagging) and Colombia's Res. 000240 (first observation year 2026, first report May 2027, 1%-of-value penalties) are the same OECD standard landing in two jurisdictions eighteen months apart. Build once, sell twice. Argentina's CNV monthly/annual reporting and Mexico's eventual AVE regime extend the same product.

**3. Institutional custody and wallet governance.** The Fireblocks data is the strongest evidence in this document: 50% piloting vs 14% in production, governance cited as the top blocker by 47% regionally, and 75% calling custody/governance critical. This is a stated, quantified, regional gap — not an inferred one.

### Tier 2 — strong evidence, longer sales cycle

**4. Bank-issued stablecoin and tokenised-deposit platforms.** The proof point exists and is verified: **Bancolombia/Wenia** issues both COPW and USDW through an offshore-licensed subsidiary, custodies reserves at a group entity in El Salvador, distributes through Nequi and Mi Bancolombia, and displaced USDC to capture the float. **Itaú** is running a tokenisation pilot with OpenAssets and ANBIMA but has **shipped nothing**. Argentine bank groups are building the same structure to route around BCRA's bank ban — **BIND/BEN now confirmed by Circle itself** (§4.2), Petersen/DIPE still unverified. Mexico's Murat Initiative, if passed, **restricts issuance to banks and IFPEs** — which converts every Mexican bank into a mandatory buyer of issuance infrastructure and locks out startup competitors.

*The strategic question to lead with:* BTG retired its own dollar coin for USDC; Bancolombia replaced USDC with its own. Whether a bank should issue or distribute depends on whether it monetises float or flow. Antier can build either, but the client needs to answer that first.

**5. Corporate treasury and cross-border settlement for Argentina.** The corporate cepo remains, BCRA has said lifting it is not a priority, and the IMF does not require it. Meanwhile 45% of Bitso's institutional volume is already B2B/corporate treasury. This is the durable Argentine opportunity — not retail dollarisation, which now has a legal alternative.

**6. Local-rail integration where none exists.** Circle has Pix and SPEI. Nobody has confirmed direct integration with **PSE/Transfiya (Colombia)** or **Transferencias 3.0 (Argentina)**. Colombia has the region's highest survey-measured stablecoin ownership (67%) and no confirmed stablecoin-to-local-rail bridge.

> **Caveat added after the operator interviews.** If Colombia is in fact launching a central-bank Pix-model instant payment system (§6.1, §10.4b), the integration target changes before this opportunity can be built — and access will likely require regulated-entity status or a banking-as-a-service partner, exactly as Pix does. Confirm the Colombian scheme's name, status and access model before committing engineering here. The same Brazilian precedent also means the *domestic* payments case for a COP stablecoin is likely to close, while the cross-border case survives.

### Tier 3 — real but crowded or unproven

**6b. Working-capital and liquidity infrastructure — the best-evidenced opportunity in this report.** The measured constraint in LatAm stablecoin FX is not adoption, it is depth: **~$4m of USDT/BRL order-book depth against a $2tn national flow, a 15% premium to trade $3–4m, and single-digit-million depth on the local exchanges that serve as the region's FX venues** (§2.8) — and, on the on-chain side, **$1.56m of total DEX liquidity across every local-currency token in the region, with swap volume down ~99.8% since 2024** (§2.9). Two independent datasets, centralised and decentralised, both saying the same thing. Corridor operators carry a **~5x working-capital multiple on daily volume** to bridge it. Products that attack this — prefunding reduction, netting engines, liquidity routing across venues, and the reconciliation to make either safe — sell against a quantified pain with named sufferers. Note this is also where the incumbents are heading (Arf, Huma as liquidity financiers), so it is a partnership market as much as a build market.

**6c. Domestic netting under transaction taxes — Colombia first.** The GMF/4x1000 netting structure in §6.1 is a real, operator-exploited use case with no good incumbent product, and it is the rare COP-stablecoin argument that does not depend on cross-border flow. Requires Colombian tax counsel up front and CARF-compatible reporting from day one.

**7. Remittance corridor infrastructure.** Large and growing — but Félix/dLocal, Bitso Business, MoneyGram, Western Union and Zepz are all already there, and the honest state of the evidence is that **nobody can substantiate current stablecoin penetration of any LatAm corridor**. Enter on infrastructure (compliance, off-ramp liquidity, reconciliation), not on a consumer remittance app.

**8. Merchant acceptance and card programmes.** BVNK's survey puts LatAm merchant-acceptance interest at 70% and card interest at 71%; Rain reports 100% YoY card-spend growth. But these are survey and vendor numbers, and Mastercard just bought BVNK for $1.8bn — the consolidation is happening above Antier's layer.

### What not to build

- **A retail dollar-savings wallet for Argentina.** The cepo is lifted for individuals, the brecha is ~1.3%, and 93% of Argentine contractors on Deel already take traditional dollars. You would be entering as the driver recedes.
- **A local-currency stablecoin as a standalone product.** The whole regional complex is ~$166m of supply across ten issuers — but turning over ~2.9x weekly (§2.9). Demand for these as *assets* barely exists; they work as settlement legs inside a larger flow, which means **the product is the flow, not the token.** Ten-plus issuers already splitting a market this size is a shakeout, not an opening.
- **Anything premised on the US remittance tax pushing volume to crypto.** The tax exempts electronic funding entirely.

---

## 12. Verification ledger — figures that did not survive

These circulate widely. Each fails a check. Do not use them, and flag them when a client or vendor does.

> **Live confirmation the ledger is doing its job (1 Sept 2026).** Stablecoin Insider published *Stablecoin Payments in Latin America 2026* on **1 September 2026**. It repeats, as current fact and without caveat, at least four entries already in this table: **"$324bn stablecoin volume 2025, +89%"** and **"+60% regional on-chain growth"** (GO Markets lineage, not in Chainalysis's own report); **"Brazil is ~one third of regional volume"** (the arithmetic gives 21%); **"733% B2B growth to $226bn"** (BCG measures ~65% organic); and **"Bolivia $14.8bn over 12 months"** (that figure is Chainalysis's *cumulative three-year* number; Bolivia's central bank reports **$294m for H1 2025**, roughly 34x smaller). It also carries a new unverified claim, **Brazil +109.9% YoY**, which no primary source in this file supports. Anything downstream of this publisher needs the same treatment: **use its regulatory and official-statistics material, verify every aggregate.**

| Claim | Problem |
|---|---|
| **"Bitso processes ~10% of US–Mexico remittances"** | Supporting figures ($1bn H1, $12.5bn Q1 corridor, $5.17bn May record) match **2022**, and CoinDesk reported the identical "$1bn in H1" in June 2022. A four-year-old vendor claim recirculated as current. **Now doubly wrong:** BeInCrypto's measurement (§5.2) puts Bitso's corridor at **$2.6–2.8bn/month against $5.6bn/month of net family remittances** — so the stale figure is not just old, it materially *understates* the corridor. But the two are different measurements (gross both-directions vs net inflows), so the fix is to stop quoting a percentage at all, not to substitute a bigger one. |
| **"Brazil introduced a 17.5% flat crypto tax in 2025"** | MP 1303/2025 **lapsed without a vote**, ~8 Oct 2025. The prior progressive regime with the R$35,000/month exemption still applies. |
| **"Brazil is nearly one-third of LatAm crypto activity"** | Chainalysis's own figures: $318.8bn against a $1.5tn regional total is **21%**. The characterisation and the arithmetic disagree. Use the absolute numbers. |
| **"Venezuela collects 80% of oil revenue in USDT"** | Headline-only, contradicted by Atlantic Council's assessment ("small share of total oil trade by value," $119m in July 2024). |
| **"Bolivia settles fuel imports via YPFB in crypto"** | Could not be corroborated by any source, despite targeted search. |
| **"MXNB is an Arbitrum stablecoin"** | Multi-chain; **Ethereum holds the largest share** of supply, not Arbitrum. |
| **"Meli Dólar launched in Brazil"** | All sourcing points to **Chile**, with Argentina pending. No Brazil launch confirmed. |
| **"Mercado Coin is a Mexican product"** | It was Brazil-only and was **shut down in 2026**, citing Pix competition. |
| **"Banxico announced a digital peso for 2025"** | The documented public target was **early 2024**, later missed. Budget of ~US$535,000 indicates a paused project. No 2025 re-announcement found. |
| **"The US remittance tax pushes volume to stablecoins"** | The 1% tax applies only to **cash-funded** transfers. Electronic funding — including every digital incumbent — is exempt. |
| **"Total LatAm remittances were $174bn in 2025"** | World Bank's official forecast is **$162bn**. The $174bn figure could not be traced to a named primary document. |
| ~~**"Stablecoins cost <2% vs 6% traditional"**~~ — **partially resolved, see right** | The traditional side always checked out (World Bank: 5.64–6.36%). The stablecoin side now **does** have a primary measurement, from a source that was in the Reports folder all along: the **Borderless Q2 2026 Benchmark** (2.96m rate observations, 260 corridors, 108 countries) puts stablecoin delivery at a **median 3.2bp below same-day interbank**, with a median corridor cost of **27.2bp** on a $10,000 payment. But the blanket claim still fails for LatAm specifically: **parallel-market currencies including Argentina still price at hundreds to thousands of bp over official**, and Borderless's own CEO says stablecoins "actually trade at a premium" in many emerging markets. Use the measured median and name the exception; do not use "<2% vs 6%." |
| **"$226bn of B2B stablecoin volume, up ~7x YoY"** — appears in the Dfns *Stablecoin FX* report as well as stablecoininsider | The figure has a traceable lineage after all, so it is not fabricated — but the lineage does not settle it. "Up more than 7x" is the same ~733% growth rate our own market-state file flags as **almost certainly a wallet-labelling artifact**, against **BCG measuring ~65% organic growth for the same segment**. Two credible houses, an order of magnitude apart, on the same quantity. Cite the dispute, not either number. |
| **"Bitso processes up to 10% of remittance volumes on the Mexico–US corridor"** — *also sitting inside `Laws/Law Files/Crypto_Regulation_Master_Reports.md`* | Same stale 2022-vintage claim debunked above. Flagging it separately because it is **already embedded in your own regulation knowledge base**, which means it will get pulled into future drafts unless that file is annotated. |
| **"Government waste costs LatAm 4.4% of GDP — so programmable stablecoins would fix disbursement"** — WEF Stories op-ed by Ripio's CEO, Feb 2026 | The 4.4% / $220bn figure is real (IDB, *Better Spending for Better Lives*, Izquierdo & Pessino) but is **~2018 vintage, cited with no date**, and decomposes into **procurement inefficiency, civil-service payroll and transfer targeting errors**. The study makes **no reference to payment systems or disbursement mechanisms as a source of waste.** The statistic does not support the argument it is attached to. §2.9b. |
| **Anything sourced to "the World Economic Forum" on LatAm local stablecoins** | The piece in question is **WEF *Stories*** — an op-ed platform — authored by the **CEO of Ripio, which issues the wARS peso stablecoin**. It is vendor advocacy carrying an institutional masthead. Grade **[V]**. Two of its eight links point to a **recruitment/EOR staffing firm's marketing page**; a third is a **gated Chainalysis lead-capture form**, not the report. |
| **"Argentina's 178% inflation"** — in `Stablecoins/Md Stablecoins/Neo Banks.md` | A 2024-vintage figure in a report dated ~22 Oct 2025, used to justify the LatAm neobank thesis. **Argentine interannual inflation was 33.8% in July 2026** and falling. The whole document is fund thesis material (MOIC), not measured research — its "50–90% of activity in stablecoins" range and "$160bn in annual remittances" are directionally fine, but date-check every number in it before use. |
| **"Crypto-assets and stablecoins are not operationally regulated in Brazil"** — PwC *Global Crypto Regulation Report 2025*, in the same folder | True when written; **superseded by Res. BCB 519/520/521** (published 10 Nov 2025). A reminder that the regulation master file's Brazil and Argentina entries are 2025 snapshots, not current law. |
| **"92% cost reduction via stablecoins"** | Untraceable. Marketing extrapolation. |
| **A 2026 Chainalysis adoption ranking** | **The 2026 index had not been published** as of 31 Aug 2026. Any such ranking is fabricated or misattributed. |
| **"Bolivia's digital-asset inflows went from $500m in 2023 to $14.8bn after legalisation"** — stated by Tether's LatAm expansion lead on the Utila panel | **$14.8bn is Chainalysis's cumulative July 2022–June 2025 on-chain total for Bolivia** — three years, all crypto activity — restated as a single year of post-legalisation dollar inflow. Bolivia's own central bank reports **$294m in H1 2025** and roughly **$430m cumulative** since the ban was lifted. The stated figure is about **34x** the central bank's. An issuer employee said it on a public panel; expect to hear it repeated. |
| ~~**"LatAm crossed ~$730bn in crypto transaction volume in 2025, +60% YoY"**~~ — **lineage found, still not primary** | I said this appeared nowhere. It does: the Stablecoin Insider report states "regional on-chain volume rose 60% year-on-year; of the **$730 billion** received during the year, **$324 billion** moved through stablecoin transactions, an 89% year-on-year surge," sourced to **GO Markets, citing Chainalysis**. So the panel host was repeating a circulating figure, not inventing one — but both numbers trace to a secondary aggregator, and **neither appears in Chainalysis's own published LatAm report**, which gives $1.5tn cumulative (Jul 2022–Jun 2025), an $87.7bn Dec 2024 peak and $47.9bn by June 2025. Two different measurement bases; cite the Chainalysis figures, and if you use $730bn/$324bn, attribute them to GO Markets. |
| **"Movantis enables ~60% of remittances flowing from the US into LatAm"** — Movantis CPO, same panel | Does not reconcile with the company's own disclosed volume. Movantis reports **$60–63bn total annual processing** across payins, payouts, wallets, issuing and core banking. US→Mexico alone was **$61.8bn in 2025**; add Guatemala, Honduras, El Salvador and Colombia and the US→LatAm corridor is comfortably above **$100bn**. 60% of that would exceed Movantis' entire disclosed volume across all products and all corridors. Whatever the 60% measures, it is not share of corridor value. |
| **"Brazil is ~50% of Latin America's economic output and ~50% of its population"** — Conduit VP Partnerships, Stablecoin Conference interview | Both are roughly **one third**, not one half. Brazil is ~212m of a LatAm population near 665m (~32%) and its GDP is a comparable share of the regional total. The ~50% intuition probably comes from Brazil's share of *measured crypto volume* among the ranked LatAm countries, which is close to half — a different denominator entirely. His adjacent claim in the same breath, **"2.5x more crypto investors than equity investors in Brazil, by headcount,"** is plausible but unsourced and unverified here. |
| **"$4 trillion sits idle in prefunded accounts"** — same interview | A third mutually incompatible figure for the same pool. Our own market-state file already records **"$27 trillion locked in nostro/vostro" as untraceable**, against Spark's **$400bn–$1T** and Bain declining to quantify. Three sources, two orders of magnitude. Do not cite any of them without a primary derivation. |
| **"$150 trillion of cross-border B2B payments a year"** — same interview | Widely circulated, no primary source given, and estimates in this category vary enormously by whether they count gross interbank flow or actual commercial payments. Unverified. |
| **This report previously dated the Utila builder panel to August 2026** | Wrong — that was the upload date, not the recording date. Internal evidence puts the panel at roughly Q1–Q2 2026 and the three Stablecoin Conference interviews at **2025** (see §10.0). A self-inflicted error, corrected; the lesson generalises to every undated transcript in this pile. |
| **"+733% YoY B2B growth to $226bn"** — Stablecoin Insider report, sourced to McKinsey & Artemis via AMBCrypto | Still contested, and this is now the third document carrying it. Our own market-state file flags 733% as **almost certainly a wallet-labelling artifact**, against **BCG measuring ~65% organic growth** for the same segment. The report's own framing is internally consistent ($390bn real-economy payments of which $226bn B2B, $90bn payroll/remittances, $8bn capital markets, $4.5bn cards) but the $390bn total is itself contested by an order of magnitude (BCG $350–550bn; Artemis's own bottom-up ~$118bn). Cite the dispute, not either number. |
| **"Bolivia recorded $14.8bn in crypto transaction volume over the twelve months measured in Chainalysis' 2025 regional analysis"** — Stablecoin Insider report | **This is the origin of the Tether executive's claim** in §12 above. The report makes the same error: $14.8bn is Chainalysis's **cumulative July 2022–June 2025** figure, not twelve months. Bolivia's central bank reports **$294m in H1 2025** and ~$430m cumulative since the ban lifted. The error is now circulating in at least two places; expect it in decks. |
| **"75% of Argentine freelancers prefer stablecoins"** | Describes only people **already paid in crypto**. Deel's platform data across all Argentine contractors: **93% take traditional dollars, 6% stablecoins**. |

### Open gaps worth closing before this goes to a client

1. **Has BCRA lifted the 2022 bank-crypto ban?** Targeted for ~April 2026; unconfirmed four months later. Materially changes the Argentine distribution picture.
2. ✅ **CLOSED (needs primary confirmation).** IOF on stablecoin FX: reported as **3.5% IOF-Câmbio in scope for covered cross-border stablecoin payments from February 2026** (§3.3). Single secondary source — verify the rate against Receita Federal before quoting it, but stop treating it as an open question.
3. **Current CNV PSAV registry count** (last verified figure is from July 2024).
4. **Binance Brazil's SPSAV filing status** ahead of 30 Oct.
5. **BCB's own primary text** on the Drex termination (four independent outlets corroborate; the release itself was not retrievable).
6. **Which chains COPW and USDW run on** — undisclosed in every source.
7. **US→Colombia remittance cost** (World Bank corridor page 404'd).
8. **Any CLP-pegged stablecoin in Chile** — none found, and notably **the Iporanga tracker covers only BRL, COP and MXN**, which is corroborating (if indirect) evidence that no CLP token has enough activity to track. Likely a genuine market gap rather than a research gap.
9. **Mexican crypto tax treatment** — no primary SAT/SHCP source located; everything available is SEO-tier.
10. **Murat Initiative committee status** in the Mexican Senate.
11. ✅ **CLOSED.** Colombia's instant payment system is **Bre-B**, live since **October 2025**, with **617M+ transactions, 218 institutions and 33M users** in its first six months (§6.1). What remains open is narrower: Bre-B's *access model* for non-bank providers — whether it mirrors Pix's regulated-entity-or-BaaS requirement.
12. **Venezuela's political transition** — corroborate the 3 January 2026 removal of Maduro against primary reporting, then reassess: sanctions status, whether an electoral timetable exists, and whether any legitimate authority can yet sign an investment framework. Currently single-sourced to one WEF conference report (§7). This is the largest single unknown in the report's country coverage.
13. **Mesh's "exclusive global crypto partner to PayPal for PYUSD" claim** — company statement, not independently verified, and material to §11.5 if a PYUSD merchant rail reaches LatAm ahead of bank-issued local coins.
14. ✅ **CLOSED (1 Sept 2026).** Mexico and Argentina instant-payment rail data — see the new **§2.12**. Banxico's own annual report gives SPEI 5.34bn operations in 2024 (vs Pix 63.5bn, same year); CoDi is verified as a failure in Banxico's own numbers (17.8m transactions in six years); BCRA gives Argentina's monthly transfer, QR and foreign-currency-transfer volumes. What remains genuinely open is narrower: **SPEI's official 2025 total** (press figures of 6bn–7.3bn are vendor-sourced and conflict — see the warning in §2.12.2), and **DiMo's transaction count**, which Banxico does not publish separately.
15. **BIS CPMI Red Book coverage** — Brazil and Mexico are CPMI jurisdictions; Argentina and Colombia are not. A methodologically harmonised four-country instant-payments table therefore does not exist from any source. Any cross-country per-capita comparison in this report or downstream is assembled from national statistics and must carry that caveat.

---

## 13. Sources

**Central-bank payment statistics (added 1 Sept 2026, §2.12)**
- [Banco de México — *Informe Anual sobre las Infraestructuras de los Mercados Financieros 2024* (PDF)](https://www.banxico.org.mx/publicaciones-y-prensa/informe-anual-sobre-las-infraestructuras-de-los-me/%7BE0085475-B1D7-DED0-60AF-05ED88153BDC%7D.pdf) — SPEI, CoDi, DiMo primary figures
- [Banco de México — *Informe Anual sobre las Infraestructuras de los Mercados Financieros 2023* (PDF)](https://www.banxico.org.mx/publicaciones-y-prensa/informe-anual-sobre-las-infraestructuras-de-los-me/%7BC0033C9D-4821-F3F2-1F71-79BB7EDAE1AA%7D.pdf)
- [BCRA — *Informe de Pagos Minoristas*, enero 2026 (PDF)](https://www.bcra.gob.ar/archivos/Pdfs/PublicacionesEstadisticas/informes/informe-pagos-minoristas-2026-01.pdf)
- [BCRA — *Informe de Pagos Minoristas*, marzo 2026](https://www.bcra.gob.ar/publicaciones/informe-de-pagos-minoristas-marzo-de-2026/)
- [CoDi — official statistics portal (data served from Banxico SIE)](https://www.codi.org.mx/secundarias/estadisticas.html)
- [BIS — CPMI payment statistics / Red Book](https://www.bis.org/statistics/payment_stats.htm)
- [DPL News — *¿Por qué fracasó CoDi?* (16 Oct 2025)](https://dplnews.com/por-que-fracaso-codi-pagos-qr-mexico/)
- [DPL News — SPEI at 22 (13 Aug 2026)](https://dplnews.com/spei-cumple-22-anos-desafio-siguiente-fase/)
- [El Cronista — ABM on CoDi/DiMo underperformance (27 Aug 2026)](https://www.cronista.com/mexico/finanzas-economia/no-es-para-todos-la-banca-simplifica-codi-y-dimo-ante-una-adopcion-menor-a-la-esperada-de-los-pagos-digitales/)
- [Fintech Expert — *CoDi: seis años sin despegar*](https://www.fintechexpert.mx/p/codi-seis-anos-sin-despegar)
- [Expansión — SPEI vs card payments (11 Aug 2026)](https://expansion.mx/economia/2026/08/11/transferencias-spei-superan-pago-tarjetas-mexico) — **[V] figures sourced to STP/Bitso, not Banxico**
- [Veritas — SPEI, CoDi, DiMo y la evolución de los pagos digitales](https://www.veritas.org.mx/Economia-y-finanzas/Fintech/SPEI-CoDi-DiMo-y-la-evolucion-de-los-pagos-digitales-en-Mexico)

**On-chain and market analytics**
- [Chainalysis — 2025 LATAM Crypto Adoption](https://www.chainalysis.com/blog/latin-america-crypto-adoption-2025/)
- [Chainalysis — 2024 LATAM Crypto Adoption: The Rise of Stablecoins](https://www.chainalysis.com/blog/2024-latin-america-crypto-adoption/)
- [Chainalysis — 2025 Global Crypto Adoption Index](https://www.chainalysis.com/blog/2025-global-crypto-adoption-index/)
- [Chainalysis — Brazil's crypto asset regulatory framework 2025](https://www.chainalysis.com/blog/brazil-crypto-asset-regulatory-framework-2025/)
- [Artemis — Stablecoin Payments From The Ground Up 2025 (PDF)](https://reports.artemisanalytics.com/stablecoins/artemis-stablecoin-payments-from-the-ground-up-2025.pdf)
- [Kaiko Research — The State of LATAM Crypto Markets 2025 (PDF)](https://marketing.kaiko.com/hubfs/The%20State%20of%20LATAM%20Crypto%20Markets,%202025.pdf)
- [Dune — The Money Layer: LATAM Crypto 2025 Report](https://dune.com/blog/latam-crypto-2025-report)
- [DefiLlama — Stablecoins](https://defillama.com/stablecoins)
- [RWA.xyz — MXNB](https://app.rwa.xyz/assets/MXNB)
- [Rain — State of stablecoins in Latin America](https://www.rain.xyz/resources/state-of-stablecoins-in-latin-america)

**Institutional research**
- [BIS Papers No. 170 — The impact of stablecoins on the international monetary system (PDF)](https://www.bis.org/publ/bppdf/bispap170.pdf)
- [IMF — Argentina 2026 Article IV / 2nd EFF Review (PDF)](https://www.imf.org/-/media/files/publications/cr/2026/english/1argea2026001.pdf)
- [IMF — Press Release 26/165, 21 May 2026](https://www.imf.org/en/news/articles/2026/05/21/pr26165-argentina-imf-completes-2nd-rev-of-extended-arr-under-eff-concludes-2026-aiv-consultation)
- [IMF — Decrypting Crypto: How to Estimate International Stablecoin Flows (Jul 2025)](https://www.imf.org/en/publications/wp/issues/2025/07/11/decrypting-crypto-how-to-estimate-international-stablecoin-flows-568260)
- [IMF — Stablecoins and the Future of Payments (Mar 2026)](https://www.imf.org/en/publications/wp/issues/2026/03/20/stablecoins-and-the-future-of-payments-evidence-from-financial-markets-574831)
- [World Bank — Remittance Prices Worldwide, Issue 54 (PDF)](https://remittanceprices.worldbank.org/sites/default/files/2026-04/RPW_main_report_and_annex_Q325.pdf)
- [World Bank — Migration and Development Brief 40 (PDF)](https://documents1.worldbank.org/curated/en/099714008132436612/pdf/IDU-a9cf73b5-fcad-425a-a0dd-cc8f2f3331ce.pdf)
- [IDB — What's the Impact of Stablecoins on Remittances and Regulatory Risks?](https://www.iadb.org/en/blog/research-development/whats-impact-stablecoins-remittances-and-regulatory-risks)
- [Atlantic Council — Venezuela, PDVSA and crypto sanctions evasion](https://www.atlanticcouncil.org/)
- [Milken Institute — Global Digital Asset Adoption: Latin America](https://milkeninstitute.org/content-hub/insights/global-digital-asset-adoption-latin-america)

**Regulators and primary legal sources**
- [Banco Central do Brasil — VASP framework presentation, 10 Nov 2025 (PDF)](https://www.bcb.gov.br/conteudo/home-ptbr/TextosApresentacoes/AVs_mercado_cambio_%20e_capitais_coletiva1_10.11.25.pdf)
- [Boletín Oficial — CNV RG 994/2024](https://www.boletinoficial.gob.ar/detalleAviso/primera/305110/20240325)
- [Boletín Oficial — CNV RG 1058/2025](https://www.boletinoficial.gob.ar/detalleAviso/primera/322539/20250314)
- [DIAN — Concepto Unificado Criptoactivos, 17 Oct 2023 (PDF)](https://www.dian.gov.co/normatividad/Documents/100202208-1621-Concepto-Unificado-Criptoactivos-17102023.pdf)
- [Banco de la República — Reporte de Estabilidad Financiera, Recuadro 3, 2S2025](https://www.banrep.gov.co/es/publicaciones-investigaciones/reporte-estabilidad-financiera/recuadro-3-segundo-semestre-2025)
- [Banco Central del Ecuador — crypto is not legal tender](https://www.bce.fin.ec/los-criptoactivos-no-son-una-moneda-de-curso-legal-ni-un-medio-de-pago-autorizado-en-ecuador/)
- [IRS — Remittance transfer tax proposed regulations](https://www.irs.gov/newsroom)
- [Receita Federal — DeCripto transition](https://www.gov.br/receitafederal/pt-br/assuntos/noticias/2026/marco/receita-federal-constroi-a-transicao-para-a-decripto-em-interacao-com-a-sociedade)

**Legal analysis**
- [Demarest — BCB regulates virtual asset services (PDF)](https://www.demarest.com.br/wp-content/uploads/2025/11/Demarest_BC_regulamenta_a_prestacao_de_servicos_de_ativos_virtuais.pdf)
- [Mattos Filho — Brazil virtual assets regulation](https://www.mattosfilho.com.br/unico/normas-regulamentacao-ativos-virtuais/)
- [Mattos Filho — DeCripto and the OECD framework](https://www.mattosfilho.com.br/unico/decripto-receita-federal-ocde/)
- [Conjur — O cerco do Banco Central às stablecoins, 1 Jul 2026](https://www.conjur.com.br/2026-jul-01/o-cerco-do-banco-central-as-stablecoins/)
- [Conjur — BC cria retenção cautelar, 17 Aug 2026](https://conjur.com.br/2026-ago-17/bc-cria-retencao-cautelar-para-transferencias-de-ativos-virtuais/)
- [Beccar Varela — CNV RG 1058/2025](https://beccarvarela.com/novedades/resolucion-general-cnv-n1058-regulacion-de-proveedores-de-servicios-de-activos-virtuales-psav/)
- [Holland & Knight — DIAN crypto reporting](https://www.hklaw.com/en/insights/publications/2026/01/la-dian-busca-regular-el-reporte-de-informacion-sobre-criptoactivos)
- [Global Financial Integrity — El Salvador Digital Assets Issuance Law reform](https://gfintegrity.org/changes-to-the-digital-assets-issuance-law-in-el-salvador/)
- [Morrison Foerster / Gibson Dunn / Mayer Brown — FinCEN FEND Off Fentanyl orders](https://www.mofo.com/)

**News of record**
- [CoinDesk — Brazil's central bank bans stablecoin and crypto settlement in cross-border payments, 2 May 2026](https://www.coindesk.com/policy/2026/05/02/brazil-s-central-bank-bans-stablecoin-and-crypto-settlement-in-cross-border-payments)
- [The Block — Brazil central bank prohibits crypto use in regulated cross-border payments, 1 May 2026](https://www.theblock.co/news/macro/2026-05-01-brazil-central-bank-prohibits-crypto-use-in-regulated-cross-border-payments-under-new-fx-rules-399713)
- [CoinDesk — Stablecoins drive 90% of Brazil's crypto volume, 30 Nov 2025](https://www.coindesk.com/policy/2025/11/30/stablecoins-drive-90-of-brazil-s-crypto-volume-tax-authority-data-shows)
- [CoinDesk — Itaú steps deeper into tokenization, 11 Aug 2026](https://www.coindesk.com/business/2026/08/11/brazil-s-largest-lender-itau-is-stepping-deeper-into-the-tokenization)
- [CoinDesk — Tether leads Belo's $14m raise, 28 Apr 2026](https://www.coindesk.com/business/2026/04/28/tether-leads-belo-s-usd14-million-raise-to-expand-stablecoin-payments-across-latin-america)
- [CoinDesk — Ripio launches Argentine peso stablecoin wARS, 1 Nov 2025](https://www.coindesk.com/markets/2025/11/01/latin-american-crypto-exchange-ripio-launches-argentine-peso-stablecoin-wars)
- [CoinDesk — Conduit and Braza debut stablecoin FX swaps, 12 Jun 2025](https://www.coindesk.com/business/2025/06/12/conduit-braza-group-debut-stablecoin-forex-swaps-for-cross-border-payments-in-brazil)
- [CoinDesk — Stablecoin card spend growing 100% YoY (Rain), 8 May 2026](https://www.coindesk.com/business/2026/05/08/stablecoin-card-spend-is-growing-100-year-over-year-rain-exec-says)
- [The Block — Mastercard completes BVNK acquisition, 3 Aug 2026](https://www.theblock.co/news/business/2026-08-03-mastercard-completes-bvnk-acquisition-410521)
- [The Block — Visa stablecoin settlement hits $7bn run-rate](https://www.theblock.co/post/399405/visa-stablecoin-settlement-hits-7-billion-run-rate-pilot-expands-nine-blockchains)
- [Fortune — Visa, Stripe and Bridge stablecoin-backed cards in 100+ countries, 3 Mar 2026](https://fortune.com/2026/03/03/visa-stripe-bridge-stablecoin-backed-cards-100-countries/)
- [Ledger Insights — Bancolombia launches stablecoin offering](https://www.ledgerinsights.com/bancolombia-colombias-largest-bank-launches-stablecoin-crypto-offering/)
- [Ledger Insights — Brazil partial ban on stablecoins for cross-border payments](https://www.ledgerinsights.com/brazil-imposes-partial-ban-on-stablecoins-crypto-for-cross-border-payments-and-fx/)
- [Forbes Argentina — Lemon raises $20m, overtakes Binance on users, 8 Oct 2025](https://www.forbesargentina.com/money/lemon-levanta-us-20-millones-supera-binance-usuarios-cripto-activos-argentina-n79514)
- [Forbes Argentina — Nexo acquires Buenbit, 11 Dec 2025](https://www.forbesargentina.com/negocios/bomba-cripto-gigante-us-11000-millones-activos-compra-buenbit-elige-buenos-aires-como-su-hub-america-latina-n83179)
- [Forbes Argentina — Deel data on freelancer stablecoin use](https://www.forbesargentina.com/innovacion/stablecoins-opcion-preferida-freelancers-cobrar-exterior-n91914)
- [Infobae — Argentines bought ~US$45bn since the cepo was lifted, 29 Aug 2026](https://www.infobae.com/economia/2026/08/29/desde-que-se-levanto-el-cepo-a-las-personas-los-argentinos-compraron-casi-usd-45000-millones/)
- [Infobae — BCRA confirms corporate cepo remains, 19 May 2026](https://www.infobae.com/economia/2026/05/19/el-bcra-confirmo-que-mantendra-el-cepo-cambiario-a-las-empresas-cuales-son-las-restricciones-que-siguen-vigentes/)
- [Infobae — Colombia remittances Jan–May 2026, 7 Jul 2026](https://www.infobae.com/colombia/2026/07/07/las-remesas-hacia-colombia-promedian-38-millones-de-dolares-diarios-sumaron-5638-millones-de-dolares-entre-enero-y-mayo-de-2026/)
- [Inter-American Dialogue — Mexican remittance decline analysis, May 2026](https://www.thedialogue.org/)
- [Bloomberg Línea — Bolivia's crypto boom, driven by dollar scarcity](https://www.bloomberglinea.com/latinoamerica/bolivia/por-que-hay-un-boom-de-criptomonedas-en-bolivia-no-es-por-entusiasmo-tecnologico/)
- [BeInCrypto — El Salvador reforms Bitcoin Law amid IMF agreement](https://beincrypto.com/el-salvador-reforms-bitcoin-law-amid-imf-agreement/)
- [Tether — Licensed in El Salvador, 13 Jan 2025](https://tether.io/news/tether-licensed-in-el-salvador-strengthening-focus-on-emerging-markets-and-innovation/)
- [dLocal — Instant stablecoin-funded WhatsApp remittances with Félix, 13 Nov 2025](https://www.dlocal.com/press-releases/dlocal-and-felix-launch-instant-stablecoin-funded-whatsapp-remittances-across-latin-america/)
- [FinTech Futures — Yellow Card secures $40m for LatAm and APAC, 7 Aug 2026](https://www.fintechfutures.com/venture-capital-funding/yellow-card-secures-40m-to-fuel-b2b-stablecoin-infrastructure-in-latam-and-apac)
- [Ventureburn — Coinbase ends Argentina peso–USDC trading](https://ventureburn.com/coinbase-exits-argentina-peso-to-usdc-trading-ends-2026/)
- [CNN Brasil — Pix transaction volume grew 25.7% in 2025 (BCB)](https://www.cnnbrasil.com.br/economia/macroeconomia/volume-de-transacoes-via-pix-aumentou-257-em-2025-mostra-bc/)

**Vendor research (graded as such throughout)**
- [Fireblocks — Financial Grid: Latin America](https://www.fireblocks.com/blog/financial-grid-latin-america)
- [Fireblocks — Execution in Motion: How Latin America Is Leading Stablecoin Adoption, 4 Jun 2025](https://www.fireblocks.com/blog/execution-in-motion-how-latin-america-is-leading-stablecoin-adoption)
- [Bitso — Crypto Landscape in Latin America 2025](https://bitso.com/blog/crypto-landscape-in-latin-america-2025)
- [Circle — USDC available in Brazil and Mexico through national payment systems, Sept 2024](https://www.circle.com/blog/usdc-now-available-in-brazil-and-mexico-through-national-payment-systems-with-local-currency)
- [Circle — Nubank case study](https://www.circle.com/case-studies/nubank)
- [Bridge — MXN FX on/off-ramps, Apr 2025](https://www.bridge.xyz/blog/mxn-fx)
- [Castle Island Ventures / Brevan Howard Digital — Stablecoins: The Emerging Market Story](https://castleisland.vc/writing/stablecoins-the-emerging-market-story/)

**Live data resources**
- **[Iporanga Research — LATAM Stablecoins Report dashboard](https://iporesearch.ventures/dashboard)** (Iporanga Ventures, Brazil). The standing on-chain monitor for LatAm **local-currency** stablecoins: BRL/COP/MXN, nine tokens, ten issuers, nine chains; supply, transfer volume, holders, mint/burn, DEX volume, pool TVL, proof of reserve. Quantitative data from Dune with the developer profile published. **Caveats:** CEXs out of scope, closed-loop tokens excluded, no stated update frequency, and the operator is a VC with commercial interest. Methodology at `/methodology`, commentary at `/insights`, prior papers at `/library`. **Re-check before any local-token claim.**

**Conference reporting**
- [Pablo Uchoa, "Latin America at Davos 2026: From building trust, to Venezuela and trade insights," WEF Stories, 29 Jan 2026](https://www.weforum.org/stories/geographies-in-depth/latin-america-davos-2026-trade-venezuela-trust/). Reports the Davos sessions *Venezuela: What Next?*, *Rebuilding Trust in Latin America* and *Breaking Latin America's Growth Ceiling*. Source of the Scriven and Velarde quotes (§2.9c) and the Venezuela transition material (§7). **Sole source in this session for the 3 Jan 2026 removal of Maduro — uncorroborated, verify before client use.** Session pages are JS-rendered and returned no content to a fetch; the companion piece *"Davos 2026: How middle powers are reading the global moment"* (Chhabria, 22 Jan 2026) contains no currency or dollarisation content.

**Policy advocacy (graded [V] — read §2.9b before citing)**
- [Sebastián Serrano (Founder & CEO, **Ripio**), "How local stablecoins could help Latin America's economies," WEF Stories, 23 Feb 2026](https://www.weforum.org/stories/financial-and-monetary-systems/local-stablecoins-latin-america-economies/). Op-ed by an issuer of the wARS peso stablecoin. Its sublinks: [World Bank LAC inflation series](https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG?locations=ZJ) · [CGAP on Findex financial health in LAC](https://www.cgap.org/blog/financial-health-driving-growth-in-latin-america-and-caribbean) (account ownership 39% in 2011 → 75%+ in 2025) · [IMF, "How Stablecoins Can Improve Payments and Global Finance," Adrian/Miccoli/Sugimoto, 4 Dec 2025](https://www.imf.org/en/blogs/articles/2025/12/04/how-stablecoins-can-improve-payments-and-global-finance) · [IDB, "Government spending waste costs LAC 4.4% of GDP"](https://www.iadb.org/en/news/government-spending-waste-costs-latin-america-and-caribbean-44-gdp-idb-study) (*Better Spending for Better Lives*, ~2018 — $220bn/yr; procurement, payroll and targeting; **no payment-system finding**) · [Americas Quarterly on public finances](https://www.americasquarterly.org/article/three-ways-to-fix-latin-americas-public-finances/) · Chainalysis 2025 Geos Report (**gated lead-capture page, not the report**) · Alcor "Tech hubs in Latin America" (**recruitment/EOR vendor marketing, cited twice**).

**Issuer filings and releases**
- [Circle — Q2 2026 results](https://www.circle.com/pressroom/circle-reports-second-quarter-2026-results). Revenue and reserve income $701m (+7% YoY); reserve income $668m; distribution/transaction/other costs $412m; net income from continuing operations $48m (+$530m YoY); adjusted EBITDA $143m; adjusted opex $146m (+23%); reserve return rate −66bp YoY; USDC circulation $73.3bn (+19%), average circulation +25%. **CPN $14.7bn annualised (+76% QoQ), 175 institutions (+29% QoQ).** Confirms the **Grupo BIND / Argentina** collaboration (§4.2) and Arc mainnet for 16 Sept 2026.

**Independent research (highest-methodology source in this report)**
- **BeInCrypto Research, *The Exodus Economy: How Latin American Money Finds a New Financial Home*** (24pp), `D:\Reports\Stablecoins\LATAMREPORT The Exodus Economy.pdf`. Data pulled 16 July 2026. Stack: Dune (queries 7995037/43/60/132, 7996277 — published as re-runnable), DefiLlama, BCB + CBE census, BCRA V4, Banxico SIE, BanRep, Bluelytics, BIS, US Treasury TIC, UN DESA, Miami Realtors, AIMA/SEF, Forbes, UNODC, World Bank WGI, PwC, Henley, Knight Frank, UBS, Capgemini. Featured contributors (Visa, Nomad, Nubank, Banco Inter) are stated as **sources, not sponsors**, with partner data requested indexed rather than absolute. Source of the retention/half-life data (§2.10), the purchasing-power test (§2.11), the Mexico two-rail comparison (§5.2), the Argentine escape premium (§4.1b), the Brazilian offshore census, and the twelve-product dollar-account audit (§9.2b).

**Practitioner testimony** (all transcripts undated on their face — see §10.0)
- Utila — *Stablecoin Builder Series*, ep. 7: "Stablecoins in LatAm" (recorded ~Q1–Q2 2026). Panel: Lumx, Tether, Movantis, Global66, Mandioca.
- Stablecoin Conference LatAm, Mexico City (powered by Bitso Business), **2025 edition** — interviews with Naveen (SVP Strategy/Ops, Mesh), Kaio (founder/CEO, Lumx), Omid (VP Partnerships, Conduit).
- [Stablecoin Conference LatAm 2026 — agenda](https://stablecoinconferencelatam.com/agenda/) (loads via Whova; not retrievable by fetch)

**Sponsored industry research (graded accordingly)**
- **Stablecoin Insider, *The LATAM Stablecoin Economy 2026*** (Q3 / August 2026, 70pp, author Chiara Munaretto), `D:\Reports\Stablecoins\LatAm-Stablecoin-Report--2026-.pdf`. **Sponsored by the five operators it profiles** — Mandioca, Pomelo, Rise, VelaFi, Movantis — whose "company data" figures are unaudited self-reporting. Several headline numbers route through aggregators (GO Markets, AMBCrypto, The Defiant, Transak). Nonetheless the source of the Bre-B launch data (§6.1), the 3.5% IOF charge (§3.3), the Mexican remittance divergence (§5.1), the 49.6% cash last-mile figure (§5.1), the Bolivian bank-adoption detail (§7) and the Tron fee comparison. See §10.5 for the full assessment and the working rule.

**Internal files consulted (D:\Reports)**
- `Stablecoins/stablecoin-fx.pdf` — **Dfns, *Stablecoin FX*, Edition Two (July 2026).** Interviews Nov 2025, data verified 18 Jul 2026. Liquidity depth, corridor pricing, the Borderless Q2 2026 Benchmark, orchestration-network sizing, the Colombian GMF netting play. The most on-point document in the folder for this report.
- `Stablecoins/Dollarisation July 2026.pdf` — **BIS Working Paper No. 1370**, Hofmann, Mehrotra & Paulick, *Dollarisation and monetary control: what lessons for the rise of stablecoins?* (30 June 2026). 130+ economies; dedicated LatAm/Caribbean panel. The persistence and capital-controls findings in §4.1b.
- `Md Stablecoins/stablecoins_emerging_market_story.md` — Castle Island / Brevan Howard survey; DolarApp and Félix Pago first-party accounts of dollar-banking restrictions by country
- `Md Stablecoins/BVNK_Stablecoin_Utility_Report_2026.md` — n=4,685 across 15 markets including Brazil, Argentina, Colombia, Mexico
- `Md Stablecoins/Neo Banks.md` — LatAm neobank and stablecoin-native market framing
- `Md Stablecoins/stablecoin_services_market_research_2026.md` — corridor and vertical mapping
- `Laws/Law Files/Crypto_Regulation_Master_Reports.md` — ~50,000-line aggregate of BCG, BIS, Citi, ESRB, FSB, IMF, KPMG, PwC, Standard Chartered and GENIUS Act material (newest content ~June 2026). **Mined.** Its PwC *Global Crypto Regulation Report 2025* section supplied the IN 1888/2019 dating (§3.3) and the 2023 extension of Argentina's BCRA ban to all PSPs (§4.2). Only LatAm country entries are Argentina and Brazil. **Contains the stale Bitso 10% claim** (§12).
- `Stablecoins/2025-global-payments-report-sep-2025.pdf` — **BCG, *Global Payments Report 2025* ("The Future Is (Anything But) Stable"), Sept 2025.** LatAm instant-payment penetration 52% — highest of any region; Pix 160m+ users; Pix cross-border corridors prioritised to Uruguay and Argentina (§3.5).
- `Stablecoins/Md Stablecoins/Neo Banks.md` — MOIC LatAm neobank thesis (~22 Oct 2025). Fund thesis material; date-check every figure (§12).
- `Tokenization Blog/Citi-Securities-Services-Evolution-2025.pdf` — LatAm capital-markets infrastructure; T+1 migration sequencing (Argentina and Mexico moved May 2024; Brazil, Chile, Peru and Colombia to follow, with BCB from late 2025). Relevant to the capital-markets angle in §10.4a.

---

## 14. Appendix — coverage of `D:\Reports`

Stated plainly because it affects how much weight this report can carry: **the folder holds 370 files** (148 PDF, 146 TXT, 74 MD) across Stablecoins, Tokenization Blog, Laws, AI, Blockchain + AI, Quantum, Mckinsey Charts and PSPs. In the first pass I keyword-grepped the tree and read excerpts from four files. **That was not adequate**, and two of the documents I skipped — the Dfns FX report and BIS WP 1370 — turned out to be the two most on-thesis sources available, one of which materially qualifies my Argentina argument.

Second pass: every `.md` and `.txt` scored for LatAm term density, and all 148 PDFs text-extracted and scored the same way. Files above the relevance threshold, and whether they are now reflected in this report:

| File | LatAm density | Used |
|---|---|---|
| `Stablecoins/Neo Banks.pdf` / `.md` | very high | Partially — framing only; the LATAM chapter deserves a dedicated read |
| `Stablecoins/stablecoin-fx.pdf` (Dfns) | high | **Yes — §2.8, §6.1, §11.6b** |
| `Stablecoins/Dollarisation July 2026.pdf` (BIS WP 1370) | high | **Yes — §4.1b** |
| `Stablecoins/stablecoins_the_emerging_market_story_091224.pdf` | high | Yes |
| `Stablecoins/BVNK_Stablecoin_Utility_Report_2026.pdf` | high | Yes |
| `Laws/Law Files/Crypto_Regulation_Master_Reports.md` | high (but 123 of the hits are false positives) | **Yes — mined.** Closed two items (§3.3, §4.2); no Mexico/Colombia content exists in it |
| `Tokenization Blog/Citi-Securities-Services-Evolution-2025.pdf` | high | Partially — T+1 sequencing noted |
| `Stablecoins/2025-global-payments-report-sep-2025.pdf` (BCG) | medium | **Yes — §3.5.** LatAm 52% instant-payment penetration (highest globally); Pix 160m users; **Pix cross-border to Uruguay and Argentina** |
| `Stablecoins/Md Stablecoins/Neo Banks.md` (MOIC thesis, ~Oct 2025) | very high | Read — fund thesis, not research. Contains a **stale "Argentina 178% inflation"** figure (§12) |
| `Stablecoins/LatAm-Stablecoin-Report--2026-.pdf` (Stablecoin Insider, Aug 2026) | very high | **Yes — §3.3, §6.1, §5.1, §7.** Sponsored; grade per §10.5 |
| `Stablecoins/LATAMREPORT The Exodus Economy.pdf` (BeInCrypto Research, Jul 2026) | very high | **Yes — §2.10, §2.11, §4.1b, §5.2, §9.2b.** Best methodology of any source in the folder |
| `Stablecoins/Video Scripts/` (44 files, incl. the three transcripts supplied this session) | medium | Three used; the rest **not systematically reviewed** |
| `Stablecoins/Md Stablecoins/` — `Avalanche Stablecoins`, `TopOfMind`, `Stablecoins-five-killer-tests`, `1748547380930` | medium | **Not used** |
| `Laws/Video Scripts Law/Spanish MICA.txt`, `OTC.txt` | medium | **Not used** |
| `Stablecoins/1788012840324.pdf` (Accenture Banking 2026) | low-medium | **Not used** — light on LatAm |

**Third pass — the regulation master file, mined.** Result, stated plainly: **it closes two open items and cannot close the rest.**

- ✅ **IN 1888 is 2019, not 2020** — PwC's Brazil entry (three named PwC Brazil partners) plus LegisWeb both date it May 2019.
- ✅ **Argentina's 2022 BCRA crypto prohibition was extended to all payment service providers during 2023**, not just financial entities — materially wider than "banks are barred," and it changes what a BCRA reversal would unlock.
- ❌ Everything else. The file is a ~50,000-line aggregate of BCG, BIS, Citi, ESRB, FSB, IMF, KPMG, PwC, Standard Chartered and GENIUS Act material whose newest content is ~June 2026. Its only LatAm country entries are **Argentina and Brazil** (via PwC) — there is **no Mexico, Colombia, Chile or Peru entry**, and the file contains **zero** occurrences of IOF, Banxico, CNBV, Superintendencia Financiera or Bre-B. Its Brazil entry still states "crypto-assets and stablecoins are not operationally regulated in Brazil," which Res. 519/520/521 superseded five months after it was written.
- ⚠️ Two apparent LatAm signals in that file are false: **"DIAN" (179 hits) is entirely `custodian`/`custodians`/`Canadian`/`Indian`**, and **"SFC" (27 hits) is Hong Kong's Securities and Futures Commission**, not Colombia's Superintendencia Financiera. Worth knowing before anyone greps it again.

**Best find of the third pass, from a different file:** BCG's *Global Payments Report 2025* gives **LatAm the highest instant-payment penetration of any region at 52%**, Pix at **160m+ users**, and — the part that changes the analysis — **Pix moving cross-border with BCB prioritising corridors to Uruguay and Argentina** (§3.5).

**Known remaining gaps in folder coverage:** ~40 unreviewed stablecoin video scripts; the Spanish MiCA and OTC law scripts in `Laws/Video Scripts Law/`; four unread `Md Stablecoins` files (Avalanche Stablecoins, TopOfMind, Stablecoins-five-killer-tests, 1748547380930); and `Laws/Law Files/1788101922846.pdf`, a "Regulatory Radar" deck added 31 Aug 2026 that is almost entirely images — only ~2,300 characters of extractable text, so it needs to be viewed rather than parsed.

**The honest bottom line on the folder:** it materially improved this report — the two best sources in it (Dfns and BIS WP 1370) were better than anything the web research surfaced, and BCG's cross-border-Pix finding changes the competitive picture. But it **cannot close the Mexico, Colombia or current-Argentina regulatory gaps**, because nothing in it covers those jurisdictions at that depth or that recency. Those still need primary-source web research (§12).
