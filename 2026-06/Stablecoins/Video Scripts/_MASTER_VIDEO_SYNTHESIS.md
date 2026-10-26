# MASTER VIDEO SCRIPTS SYNTHESIS
## 31 Stablecoin Video Scripts — Deep Read Complete
### Sources: StabelSummit Day1 & Day2, Economics of Payment (Fed), State of Fintech, 2026 Predictions, CAC26, ITP Payments, Stablecoin Settlement, Distribution, Cash Legs, Euros Onchain, Genius Effect, Agentic Payments, Sanctions, Consensus 2026, Crypto Rails, NYU Stern Parts 1&2, Regulation AI, Dollar Milkshake, User Trust, ACCESS 2026, Operational Stablecoin, Configurable Privacy, Corporate Adoption, Onchain FX, Flipping USDC, Frankencoin, Nightfall, Neobanks, WEF Stablecoins
---

---
## BATCH 1
---
# Video Script Synthesis: Stable Summit Day 1 (Cannes, 2026)

**Source file:** `Stabelsummit Day1 Video Script.txt`  
**Total runtime:** ~7 hours 47 minutes  
**Total lines:** 3,215  
**Conference:** Stable Summit 2026 (First Edition) — held at Cannes Film Festival venue

---

## 1. OVERVIEW — Format, Length, Style, Audience

**Format:** Auto-generated transcript of a full-day live conference. Timestamps follow two formats: compact (`H:MM:SS`) and verbose (`X hours, Y minutes, Z seconds`). No moderator narration; raw speaker text only, captured with ASR (Automatic Speech Recognition) — occasional transcription errors present (e.g., "Stabelsummit", "Dwayne" for "Twine").

**Length:** Approximately 7 hours 47 minutes of recorded content, beginning around 9 AM and running to late afternoon/evening (7:47 PM timestamp appears at end). Six main content blocks plus a pitch competition.

**Style:** Academic-practitioner hybrid. Sessions alternate between:
- Keynote/solo talks (didactic, code-heavy conceptual explanations)
- Fireside panels (conversational, debate-style, candid)
- Technical deep-dives (AMM math, oracle design, protocol mechanics)
- Pitch competition Q&A (investor grilling, startup founders defending mechanics)

**Audience:** Highly technical DeFi builders, protocol founders, DeFi-native investors, institutional DeFi teams. Assumes fluency in AMMs, CDP mechanisms, stablecoin design, MiCA/GENIUS Act. Not a beginner intro — speakers routinely reference Liquity v2, Morpho, Aave, Curve, Pendle mechanics without explanation.

**Language register:** Informal, fast, unscripted. Heavy use of "right?", "basically", "essentially", "kind of like". Occasional profanity ("holy [ __ ]"). Technical jargon delivered casually.

---

## 2. SPEAKERS & SEGMENTS — All Named, Roles, Key Arguments

### SEGMENT 1: Opening/Keynote — Stablecoin Market Overview
**Speaker: Michael (implied host/organizer)**
- Sets tone: "stablecoins are the killer app of crypto"
- Frames conference as practitioner-focused: "We want to talk about the real problems"

---

### SEGMENT 2: AMM Design for Stablecoins — Technical Keynote
**Speaker: Michael Egorov (Curve Finance founder)**
Key arguments:
- Five AMM types: constant product, constant sum, StableSwap, CryptoSwap, FX Swap
- StableSwap works because it concentrates liquidity near the peg — "the more you zoom in to the peg, the more it resembles constant sum"
- CryptoSwap: "invariant has two components — geometric mean and a sum... automatically shifts the price to what the market thinks it should be"
- FX AMM design: key challenge is **rebalancing** ("refueling") — if EUR/USD AMM gets drained of EUR, must reinject EUR liquidity
- Curve FX Swap uses oracles + rebalancing mechanics to solve this
- "Onchain FX is $9 billion annually, offchain FX is $9 trillion" — 1000x gap = the opportunity
- On Yield Basis: "Concentrated liquidity AMM for stablecoins with the ability to borrow against LP positions" — designed for crvUSD/USDC pairs, allows leveraged LP positions

**Key quote:** "If you want to make a very large trade in a very short time in a very stable asset... the constant sum is the best."

---

### SEGMENT 3: Panel — Tokenized Money Market Funds vs. Deposit Tokens vs. Stablecoins
**Speakers:**
- **Mona El Isa** (moderator/Avantgarde Finance)
- **Josh (Ondo Finance)** — "Tokenized money market funds are the killer application for blockchain today"
- **Ananya (Agora)** — Stablecoins as infrastructure layer; yield distribution models
- **Heiko (Deutsche Bank / project Guardian)** — Bank perspective, deposit tokens, MiCA compliance challenges
- **Patrick (Libre Capital)** — Institutional fund tokenization; "we are a feeder fund on chain"

Key arguments:
- Josh (Ondo): Three layers — stablecoins (M1-like), deposit tokens (M1), tokenized MMFs (M2-adjacent). "The distinction matters for systemic risk and monetary policy transmission."
- Heiko: "Under MiCA, e-money tokens must hold 30% minimum in deposits, 60% in liquid assets. Yield is prohibited." Deutsche Bank building deposit tokens as liability on their own balance sheet.
- Patrick: Libre deployed $200M+ in tokenized funds; "the future is not one stablecoin to rule them all — it's programmable money with choice"
- Ananya: "Stablecoins settle in seconds, globally, 24/7 — that's not incremental improvement, that's a different product"

**Key framing:** "Singleness of money" — M0/M1/M2 distinctions matter onchain for systemic reasons. The panelists disagree on whether yield-bearing tokens undermine monetary transmission mechanisms.

---

### SEGMENT 4: Technical Talk — Private Credit + Blockchain (CAP Protocol)
**Speaker: [Name not clearly stated — CAP protocol co-founder]**
Key arguments:
- Existing private credit on DeFi fails to scale because: (1) originator model concentrates risk, (2) due diligence is duplicated across pools
- CAP introduces **underwriter model**: specialized underwriters take first-loss positions, creating risk segmentation
- Three parties: originators (find deals), underwriters (assess risk, take first loss), LPs (senior tranches)
- Underwriters compete on performance — "reputation becomes the moat"
- "We have done $X billion in cumulative originations" [exact figure not captured in transcript — given rapidly]
- Scalability fix: underwriters can serve multiple pools across multiple originators simultaneously
- Integration with USDC, USDT, crvUSD

---

### SEGMENT 5: Technical Talk — Risk Oracles for RWAs
**Speaker: [LlamaRisk / Chainlink CRE presenter]**
Key arguments:
- Llamaguard Nav: risk oracle that bounds NAV of tokenized funds for use as DeFi collateral
- Problem: tokenized RWA funds report NAV asynchronously (T+1, T+2) — stale oracle = exploit risk
- Solution: oracle caps NAV at last confirmed value, applies conservative haircut
- Chainlink CRE (Cross-chain Real-world asset Engine): same bounding logic but standardized
- "Pricing anomalies" in RWA tokens are the #1 barrier to DeFi composability
- Real example: tokenized fund NAV diverged from market price during stress — liquidations would have been mispriced

---

### SEGMENT 6: Panel — MiCA, GENIUS Act, Regulation
**Speakers: Multi-person panel (names partially captured)**
- **Regulatory expert (EU-side):** "MiCA is a net positive — at least we have clarity"
- **US legal perspective:** GENIUS Act (2025): cash + treasury reserves only, no rehypothecation, monthly attestation
- **Clarity Act debate:** "The key unresolved question is: is yield from staking 'passive' (like interest) or 'active' (like a security)?"
- **MiCA yield prohibition:** "You cannot pay yield on e-money tokens in Europe. Full stop. This kills algorithmic or yield-bearing stablecoin models under MiCA."
- Panelist: "Fragmented jurisdictions mean a token compliant in Switzerland is not compliant in EU which is not compliant in US"
- Discussion of FATF travel rule application to stablecoins and CASPs

---

### SEGMENT 7: Technical Talk — Singleness of Money / M-Level Framework
**Speaker: [Academic presenter — monetary economics background]**
Key arguments:
- Singleness of money: the public accepts different monetary instruments at par (1:1) because of government guarantee + mutualized acceptance networks
- Historical context: pre-Fed US had hundreds of bank monies trading at a discount
- "On blockchain we are recreating 1800s US banking — every stablecoin is its own note-issuer"
- M0 = central bank reserves; M1 = commercial bank deposits; M2 = money market funds
- Tokenized MMFs = M2 analog — should NOT be treated as money but as near-money
- "The question for DeFi is: who is the guarantor of last resort for stablecoin parity?"
- Mutualized acceptance network = Visa/Mastercard analog = what stablecoins currently lack

---

### SEGMENT 8: Talk — Money Market Fund History
**Speaker: [Finance historian / practitioner]**
Key arguments:
- Reserve Primary Fund "breaking the buck" in 2008 — the seminal MMF crisis
- Regulation Q (1933) prohibited interest on demand deposits → created MMFs in 1971 as workaround
- Bruce Bent invented the MMF: "He was fired by his bank for being too innovative"
- Sweep accounts: banks automatically sweep idle balances into MMFs overnight
- Current AUM: $6 trillion in MMFs in the US
- "Tokenized MMFs are doing exactly what MMFs did in 1971 — finding the yield that regulators prohibited elsewhere"
- "The GENIUS Act is 2025's version of Regulation Q — it will create the next MMF"

---

### SEGMENT 9: Talk — FX Markets Onchain (Mento / FPMM)
**Speaker: [Mento Labs presenter]**
Key arguments:
- Mento uses Fixed Price Market Makers (FPMM) — oracle-based rather than AMM-based
- "We don't use an AMM. We use the oracle price directly. This means no impermanent loss for LPs."
- Non-USD stablecoins: "99% of stablecoin market is USD. But the world transacts in 180+ currencies."
- cEUR, cREAL, cKES (Kenyan Shilling) — Mento's non-USD portfolio
- Use case for Global South: "A Kenyan merchant doesn't want USD exposure — they want KES-denominated stable value"
- Challenge: "Liquidity fragmentation. You need a cKES/cEUR pool, a cKES/USDC pool, and they don't talk to each other."
- FPMM + circuit breakers: if oracle and market price diverge > threshold, FPMM pauses to prevent exploitation

---

### SEGMENT 10: Talk — Onchain Privacy / Confidential Stablecoins
**Speakers: Two presenters (privacy infrastructure + Aleo/ZK perspective)**

**Presenter 1 (ZK/privacy)**
- "Blockchains are transparent by default. That's a bug for institutional adoption, not a feature."
- Two solutions: ZK proofs (prove compliance without revealing identity) and onchain encryption (FHE — Fully Homomorphic Encryption)
- Privacy pools: "You can prove you're not on a sanctions list without revealing who you are"
- "ZK compliance is the only model that satisfies both FATF travel rule and user privacy simultaneously"

**Presenter 2 (Generic/GUSD confidential)**
- Generic: FHE-encrypted stablecoin — "all balances and transfers are encrypted onchain"
- GUSD: yield-bearing confidential stablecoin
- "Banks already operate in confidential mode — they don't broadcast your account balance. Why should onchain be different?"
- Challenge: "FHE is computationally expensive. Current latency is 2-10 seconds per transaction. Acceptable for settlements, not for high-frequency."

---

### SEGMENT 11: Panel — Basis Trade Stablecoins / Delta-Neutral Strategies
**Speakers: Multi-person panel**
- Discussion of Ethena (USDe) as template: long spot ETH/BTC + short perp = delta-neutral yield
- "Ethena abandoned delta-neutral. Their original USDT-margined perps created USDT counterparty risk."
- Basis trade yield source: funding rates — "historically positive 87% of the time for BTC"
- Risk: funding rate goes negative → yield turns negative → incentive to exit → potential run
- Panel debate: "Is this a stablecoin or a structured product?"
- Counterparty risk on CEX: OKX, Bybit, Binance — "you are not protected 100%, same as any trader"
- Auto-Deleverage (ADL) as exchange-level risk management feature

---

### SEGMENT 12: Panel — VC Capital Deployment in Stablecoins
**Speakers:**
- **Peter (Namu Capital)**
- **Selene (BPI France)**  
- **Daniel (Gnosis VC)**

Key arguments:
- Peter: "We look for stablecoin projects that solve a real FX problem, not just another USD-on-chain"
- Selene: "Europe is underrepresented in stablecoin innovation. MiCA creates compliance burden but also regulatory clarity — both matter."
- Daniel: "Contrarian thesis: wallets for low-end smartphones in emerging markets. 3 billion people, feature phones, no MetaMask."
- Daniel: "Stable coins will kill the eurodollar market" — strongest contrarian statement of the day
- On yield regulation: "GENIUS Act says no yield from stablecoins held for payment. But what counts as 'payment'? This is the $6 trillion question."
- On Clarity Act: "Still being debated. If yield = passive income = not a security, DeFi wins. If yield = activity = security, everything is a security."

---

### SEGMENT 13: Zero TVL Pitch Competition
**Judges:** Peter (Namu Capital), Tessa (Flashbots), Amen (Gnosis VC), Petro (Chain Security)

**Pitcher 1: Aegis (min, CEO)**
- Institutional-grade yield-bearing stablecoin
- ~$40M TVL at time of pitch
- Delta-neutral: long BTC spot + short BTC perp (BTC-margined, not USDT-margined)
- "We don't have the USDT risk embedded in us like Ethena"
- GLP hedge strategy as secondary approach
- Hedging on OKX, Bybit, Binance
- ADL protection built into exchanges as standard feature
- Funding rates: "87% of time historically positive for BTC"

**Pitcher 2: Ethan (Ibizu Finance / EBUSD)**
- CDP protocol: fixed rate, open-term loans against blue-chip tokenized collateral
- EBUSD = fully backed by over-collateralized debt; permissionless 1:1 redemption → always redeemable for $1 of collateral
- Market-set fixed rates: "No one is setting the rate — it is set by the market via peg strength"
- Rate mechanism: if EBUSD depegs → redemptions → borrowers with lowest rate auto-deleveraged → average rate rises
- JIT (Just-In-Time) liquidation as primary path; stability pools as backup
- Revenue split: 25% to stability pools, 75% to DEX incentives (EBUSD/USDC curve pools)
- Current TVL: ~300k collateral
- Collateral: BTC, ETH, Bitcoin ETH derivatives, Ethena, CAP, Syrup, USDA, gold
- Strategic investor announced: funding DEX incentives $10k-$35k/month from April 1st
- Built on Liquity v2 mechanism with JIT modification (audited by Dub)
- OEV: signed LOI with Chainlink for OEV capture on WBTC
- LTV: static, set conservatively; advised by Antheus (DeFi boutique risk shop)

**Pitcher 3: Lawrence (Polaris)**
- Three-layer innovation: collateral layer (PE token), stablecoin layer (PUSD), governance layer (POLAR token)
- Bonding curve: ETH enters → mints PE asset; concave curve designed to outcompete liquid staking by ~5-7%/year
- Swap fees on bonding curve → burned → creates floor price for PE → viable collateral
- PUSD: CDP-style with direct minting/redemption; interest rates set autonomously via minting/redemption volume
- Can support negative interest rates: "If yield from bonding curve > borrowing rate, effective rate goes negative"
- Expansion: P Swiss Franc, P Gold — "Polaris as a stable coin operating system"
- POLAR governance token: only minted by burning PE via Dutch auction
- Governance votes on whitelist of yield recipients
- Status: available on gated testnet
- Quote: "Polaris is not just a simple stablecoin but rather a broader reserve-centered architecture for DeFi"
- Judge pushback: "That's what they said about Terra and algo stable coins"
- Defense: "The floor price is continuously ratcheting up — even if Polaris fully unwinds, users get exit value"

**Pitcher 4: Talant (Twine)**
- Programmable credit on top of existing lending markets (Aave, Morpho)
- Key insight: "$12 billion sitting at 0% LTV taking no leverage. On the far right, $66 billion leveraged up."
- Marketplace for idle credit: lender's credit capacity transferred to borrower → borrower borrows more on Aave
- Accounting trick: one position, two perspectives — Twine sees 80% LTV, Aave sees composite 50% LTV
- Two liquidation layers: Twine liquidation (creditors protected) → Aave liquidation (borrowers hit first)
- Loss absorption order: borrower first, then creditor, Aave segregated
- Simulation: 94% of liquidated positions would have survived with 10% buffer over 30 days
- Capital efficiency: $1 credit enables $32 in borrowing capacity; 1% yield on $32 → 32% yield to creditor
- Just launched PT senior USD looping vault: ~30% yield, TVL 4x in 10 days
- Bootstrapping strategy: build on one chain, one lending market, then aggregate
- Moat: "Aave won't aggregate other lending markets. We will."
- **Winner of Zero TVL Competition**

**Pitcher 5 (last): Karan (Monetary)**
- End-to-end tokenization infrastructure for financial institutions in emerging markets
- Focus: Turkish Eurobond tokenization
- 36 Turkish government Eurobonds in European/US markets, 5-7 year maturity, 5-11% yield
- Target yield: ~7% (300-500 bps premium over US treasury bills)
- Structure: Cayman foundation (no beneficial owners) → NexumBond SPC → Incorbank (broker, segregated account under Clearstream) → Eurobonds
- Custody: Clearstream as ultimate custodian (bankruptcy remote from Incorbank)
- Smart contracts: custom, audited by Haken; discussing Halborn for second audit
- Chains: Ethereum, Stellar; considering other RWA chains; Canoe chain for Visa deposit token project
- Regulatory: Phase 1 — Cisfina-exempt, qualified investors only, min ticket $100k; Phase 2 — EEA passport via Liechtenstein prospectus
- DeFi composability: Phase 2 only; phase 1 whitelist-only; Centrifuge wrapping mentioned as path
- Working with: TeraBank (holding company/investment bank), Cointra (gold tokenization), Visa (Turkey/Eastern Europe deposit token corridor), Fimple (core banking partner), Osprey (KYC/AML embedded)
- Quote: "This is no crypto strategy. This is real life government bond yield that is 2x the treasury bill."

---

## 3. ALL KEY STATISTICS & DATA POINTS

| Statistic | Figure | Context |
|---|---|---|
| Stablecoin market cap (USD share) | ~99% | USD dominance, non-USD < 1% |
| Onchain FX volume (annual) | $9 billion | vs. $9 trillion offchain — "1000x gap" |
| Offchain FX volume (annual) | $9 trillion | Kurve FX AMM target market |
| US Money Market Fund AUM | $6 trillion | Historical context, MMF keynote |
| MMF inception year | 1971 | Bruce Bent invented MMF as Reg Q workaround |
| Reserve Primary Fund break date | September 2008 | "Breaking the buck" — seminal MMF crisis |
| Regulation Q enacted | 1933 | Prohibited interest on demand deposits |
| Non-USD government bonds onchain | $1.33 billion | Mainly EU bonds with less yield than US T-bills |
| MiCA deposit requirement | 30% minimum in bank deposits | E-money token reserve rules |
| MiCA liquid asset requirement | 60% in liquid assets | E-money token reserve rules |
| MiCA yield prohibition | Full prohibition | No yield on e-money tokens |
| GENIUS Act reserve requirement | Cash + Treasuries only | No rehypothecation, monthly attestation |
| BTC funding rate positive % | 87% historically | Aegis pitch — delta-neutral thesis |
| Aegis TVL | ~$40M | At time of pitch |
| Ibizu/EBUSD TVL | ~$300k collateral | At time of pitch |
| Ibizu strategic investor funding | $10k-$35k/month | DEX incentives starting April 1st |
| Ibizu revenue split | 25% stability pools / 75% DEX | Protocol revenue allocation |
| Ibizu JIT vs stability pool efficiency | 3x more margin per unit of debt | vs. Liquity v2 approach |
| Polaris competitive yield | ~5-7%/year over ETH | Vs. liquid staking |
| Polaris floor price protection | ~75% example | Maximum loss for bonding curve participants |
| Twine idle Aave capital | $12 billion at 0% LTV | Massive untapped credit capacity |
| Twine leveraged capital | $66 billion | Highly-leveraged tail of Aave users |
| Twine capital efficiency | $1 credit → $32 borrowing capacity | Bootstrap efficiency |
| Twine yield amplification | 1% yield on $32 = 32% to creditor | Via credit delegation leverage |
| Twine TVL growth | 4x in 10 days post vault launch | PT senior USD looping vault |
| Twine liquidation simulation | 94% positions survive | With 10% buffer over 30 days |
| Twine ETH liquidation scenario | 0.6% annualized losses at 94% LTV | If all liquidations hit fallback |
| Twine loop amplification | +30 loops for 95% → 98% LTV boost | 3% LTV improvement |
| Turkish Eurobonds available | 36 bonds | In European and US markets |
| Turkish Eurobond maturity | 5-7 years | Average maturity |
| Turkish Eurobond yield range | 5-11% | Depending on bond |
| Monetary target fund yield | ~7% | Turkish Eurobond tokenization |
| Monetary yield premium over T-bills | 300-500 bps | Over US treasury bills |
| Monetary minimum ticket size | $100k | Phase 1, qualified investors |
| Monetary gold tokenization scale | 10 kilobars | ICO starting Q2 |
| Libre Capital tokenized fund AUM | $200M+ | Deployed in tokenized funds |
| Twine looping vault APY | ~30% (60% with boost) | PT senior USD vault |
| Conference edition | First edition | Stable Summit 2026, Cannes |
| Conference duration | ~7h 47m | Full day |

---

## 4. CORE NARRATIVE ARCS — Main Storylines and Arguments

### Arc 1: The FX Gap — Crypto's Next Frontier
Kurve's Egorov opens the conference by reframing the stablecoin question from "USD pegged coins" to "all-currency AMMs." The $9B onchain vs. $9T offchain FX gap is positioned as the defining opportunity. The arc culminates in Mento's FPMM approach (oracle-driven FX market) and Monetary's Turkish Eurobond tokenization — both attacking non-USD, non-US use cases.

### Arc 2: Regulation as Constraint AND Moat
MiCA's yield prohibition and GENIUS Act's reserve requirements are discussed throughout as both kill switches (for some models) and moats (for compliant players). The panel consensus: "Regulatory clarity, even if restrictive, is better than ambiguity." Sub-arc: the Clarity Act debate over passive vs. active yield — unresolved, hanging over all yield-bearing stablecoin models.

### Arc 3: What Is a Stablecoin, Actually?
The money framework panel establishes M0/M1/M2 distinctions. Tokenized MMFs ≠ stablecoins ≠ deposit tokens. This isn't semantic — it matters for regulatory treatment, systemic risk, and monetary policy. The arc runs through the whole day: Ibizu (CDP = M2-adjacent?), Polaris (bonding curve collateral = M1.5?), Twine (credit markets = M3?).

### Arc 4: The Privacy Paradox
Blockchain's transparency is a feature for auditability but a bug for institutional adoption. ZK proofs + FHE encryption offer paths to confidential compliance. "You can prove you're not sanctioned without revealing who you are." GUSD demonstrates that confidential + yield-bearing is technically achievable — now the question is regulatory acceptance.

### Arc 5: DeFi Infrastructure Maturation
Multiple talks show DeFi moving from primitive speculation to institutional infrastructure: CAP protocol (underwriter model), LlamaRisk oracles (NAV bounding), Ibizu (fixed-rate CDP with JIT liquidation), Twine (credit delegation layers). The arc implies: "DeFi v1 was for degens. DeFi v2 is for institutions."

### Arc 6: Singleness of Money — The Unsolved Problem
The academic keynote on monetary economics frames the deepest challenge: stablecoins lack the "mutualized acceptance network" that makes bank money fungible at par. Visa/Mastercard created this network for card payments. Who creates it for stablecoins? No answer offered — left as open question.

---

## 5. POSITIONING PILLARS — Unique Angles, Claims, Framings

**Pillar 1: "We are solving the 1000x gap"**
Curve FX AMM / Mento's positioning: the $9T FX market is 1000x bigger than what's onchain. Everyone else is fighting over the USD-stablecoin 1%. The real prize is being the AMM/infrastructure layer for global FX.

**Pillar 2: "Non-USD is underserved and over-rewarded"**
Monetary and Mento both use this: cKES for Kenya, Turkish Eurobonds for EM yield, non-EU government bonds. "99% USD stablecoins but the world transacts in 180 currencies." Non-USD = higher yield + clearer product-market fit outside US regulatory reach.

**Pillar 3: "MiCA is the floor, not the ceiling"**
European speakers reframe MiCA from "regulatory burden" to "minimum viable compliance that creates a moat." Deutsche Bank's Heiko frames this explicitly: "If you can operate under MiCA, you can operate anywhere."

**Pillar 4: "Institutional grade" as differentiator**
Aegis, Monetary, and Libre all use "institutional grade" as a positioning anchor. Subtext: delta-neutral strategies without USDT counterparty risk (Aegis), Clearstream custody (Monetary), regulated feeder fund structure (Libre).

**Pillar 5: "We're not Terra"**
Every decentralized stablecoin presenter faces implicit Terra comparison. Polaris addresses it directly with floor price mechanics. Ibizu does it with over-collateralization. Twine sidesteps by not being a stablecoin at all. This pillar = "We have real collateral, not algorithmic growth assumptions."

**Pillar 6: "The MMF playbook, onchain"**
Multiple speakers invoke the 1971 MMF creation as the historical analog for tokenized yield-bearing instruments. "Bruce Bent invented the MMF because Reg Q prohibited bank interest. GENIUS Act is the new Reg Q — tokenized treasuries are the new MMF." This reframes innovation as historically inevitable, not speculative.

**Pillar 7: "Idle capital should earn"**
Twine's entire pitch. $12B sitting at 0% LTV on Aave. "You're already exposed to smart contract risk — you should get paid for it." The yield-on-idle-credit framing is clean and non-speculative.

---

## 6. HOOKS & OPENINGS — How Each Segment Opens, Attention-Grabbing Lines

**Egorov/Curve:** Opens with taxonomy — "Let me show you five AMM types." Clean authority frame. No hype, immediate technical depth.

**MMF history talk:** Opens with the Reserve Primary Fund crisis — narrative hook using a known disaster. "It broke the buck in 2008. Everyone thought MMFs were safe."

**Singleness of money:** Opens with pre-Fed US banking anecdote — "Before the Federal Reserve, your bank note from the Second Bank of the United States might trade at 15% discount in Cincinnati." Historical contrast as entry point.

**Privacy/ZK talk:** Opens with the paradox: "Blockchain is supposed to be trustless. But to operate in TradFi, you need to prove you're compliant. How do you prove compliance without revealing identity?" — Classic problem-solution frame.

**Aegis pitch:** Direct product statement — "Institutional-grade yield-bearing stablecoin. ~$40M TVL. Delta-neutral. No leverage." No story, just numbers.

**Ibizu/EBUSD pitch:** "I'm Ethan from Ibizu. Ibizu is a stablecoin credit market that enables fixed rate open-term loans against blue-chip tokenized collateral." One sentence, four differentiators (fixed, open-term, blue-chip, credit market).

**Polaris pitch:** Opens with problem statement — "When you analyze the existing decentralized DeFi stablecoin landscape, you realize that the existing solutions fail to scale. Polaris is designed to address exactly that problem." Classic problem → solution framing.

**Twine pitch:** Opens with visualization — "This is the leverage profile of the protocol. You can see $12 billion sitting at 0% LTV taking no leverage at all. And on the far right, the emote, they are leveraging up $66 billion." Data-first, visual, creates immediate cognitive tension.

**Monetary pitch:** Opens with differentiation from TradFi baseline — "Most DeFi liquidity providers onchain are stuck with US treasury bills at max 4-5%. In real life, most liquidity is starting to pivot towards emerging markets which has the juiciest deals obviously."

---

## 7. RECURRING PHRASES & LANGUAGE — Exact Phrases, Metaphors, Analogies

### Structural metaphors:
- **"Singleness of money"** — academic term used throughout for fungibility at par
- **"Breaking the buck"** — Reserve Primary Fund 2008; used as shorthand for catastrophic peg failure
- **"Delta neutral"** — used for basis trade strategies (Aegis, Ethena comparison)
- **"Just in time" (JIT)** — Ibizu's liquidation mechanism; borrowed from manufacturing
- **"Floor price"** — Polaris bonding curve protection mechanism; used repeatedly
- **"Idle capital"** / **"Idle credit"** — Twine's core framing for untapped Aave borrowing capacity
- **"First loss"** — CAP underwriter model; standard private credit language brought onchain
- **"Mutualized acceptance network"** — academic term for what gives bank money par value
- **"Refueling"** / **"Rebalancing"** — Egorov's AMM vocabulary for restoring FX pool liquidity
- **"Permissionless"** — used ~15+ times across all pitches; DeFi shibboleth

### Filler/verbal tics:
- "Basically" — most common filler (~50+ occurrences)
- "Right?" — tag question seeking confirmation (~30+ occurrences)
- "Kind of like" — hedging technical claims
- "Essentially" — formal near-synonym for "basically"
- "At the end of the day" — closing argument marker
- "Obviously" — used ironically when things are not obvious

### Technical shorthand:
- **CDP** — Collateralized Debt Position (used without explanation)
- **LTV** — Loan-to-Value (ubiquitous)
- **AMM** — Automated Market Maker
- **DEX** — Decentralized Exchange
- **JIT** — Just-In-Time (liquidation)
- **OEV** — Oracle Extractable Value (Chainlink feature)
- **ADL** — Auto-Deleverage (CEX exchange feature)
- **NAV** — Net Asset Value (tokenized fund pricing)
- **FPMM** — Fixed Price Market Maker (Mento's mechanism)
- **FHE** — Fully Homomorphic Encryption (Generic/GUSD privacy)
- **MEV** — Maximal Extractable Value (appears in Polaris arbitrage discussion)
- **MiCA** — Markets in Crypto Assets (EU regulation)
- **GENIUS Act** — US stablecoin reserve law (2025)
- **Clarity Act** — US ongoing legislative debate on yield classification

### Analogies used:
- "The MMF of 1971 is what tokenized treasuries are today" — historical analog
- "Twine is like how AMMs were aggregated by routers, and we'll do the same for lending markets"
- "The bonding curve is like a load balancer for liquidity"
- "Stablecoins will kill the eurodollar market" — Daniel (Gnosis VC) — provocateur framing
- "Aave is like a single big pool. Morpho segregated it. Twine is the aggregation layer on top."

---

## 8. COMPANIES/PROTOCOLS MENTIONED — Every Named Entity and Framing

### Core protocol mentions:
| Entity | Framing/Context |
|---|---|
| **Curve Finance** | AMM innovation leader; Egorov presenting StableSwap, FX AMM, Yield Basis |
| **Yield Basis** | Egorov's new project — concentrated liquidity AMM for stablecoins with LP borrowing |
| **Mento** | Non-USD stablecoin issuer (cEUR, cREAL, cKES); FPMM oracle-based |
| **Ethena (USDe)** | Used as comparison/cautionary tale; "abandoned delta neutral", "USDT margin risk" |
| **Liquity v2** | Comparison point for Ibizu — same base mechanism, different liquidation path |
| **Morpho** | Comparison for lending market segmentation; Twine described as "layer above Morpho" |
| **Aave** | Primary lending market Twine is built on; "$12B idle" stat |
| **Pendle** | Mentioned as integration target for Ibizu and Twine; PT tokens as collateral |
| **Centrifuge** | Mentioned for RWA wrapping to create DeFi-composable tokens (Monetary) |
| **CAP Protocol** | Private credit underwriter model presentation |
| **Ondo Finance** | Josh presenting; tokenized MMFs as "killer app" |
| **Agora** | Ananya presenting stablecoin infrastructure layer |
| **Libre Capital** | Patrick presenting $200M+ tokenized funds as feeder fund |
| **Avantgarde Finance** | Mona presenting; moderator of MMF/deposit token panel |
| **Generic/GUSD** | FHE-encrypted confidential stablecoin |
| **Aegis** | Pitch competitor — institutional delta-neutral yield stablecoin |
| **Ibizu Finance** | Pitch competitor — CDP, fixed-rate open-term loans, EBUSD |
| **Polaris** | Pitch competitor — bonding curve collateral, PUSD, POLAR governance (2nd place) |
| **Twine** | Pitch competitor — programmable credit on Aave/Morpho (**Winner**) |
| **Monetary** | Pitch competitor — Turkish Eurobond tokenization, EM infrastructure |
| **LlamaRisk** | Risk oracle provider (Llamaguard Nav) |
| **Chainlink** | CRE oracle product; OEV feature mentioned by Ibizu |

### TradFi entities:
| Entity | Framing/Context |
|---|---|
| **Deutsche Bank** | Heiko presenting deposit token under MiCA; project Guardian participant |
| **BPI France** | Selene on VC panel; European institutional investor |
| **TeraBank** | Monetary's parent investment bank (Turkey); already runs Eurobond funds |
| **Incorbank** | Broker for Monetary's Eurobond tokenization |
| **Clearstream** | Custodian for Monetary's Turkish Eurobonds — ultimate bankruptcy-remote holder |
| **Visa** | Deposit token corridor project in Turkey/Eastern Europe with Monetary |
| **Fimple** | Core banking partner for Monetary's Visa project |
| **Osprey** | KYC/AML embedded solution used by Monetary |
| **Haken** | Smart contract auditor for Monetary's gold tokenization |
| **Halborn** | Additional auditor Monetary considering |

### VC/Investor entities:
| Entity | Framing/Context |
|---|---|
| **Namu Capital** | Peter — competition judge, VC panel participant |
| **Flashbots** | Tessa — competition judge |
| **Gnosis VC** | Amen (judge) and Daniel (panel) |
| **Chain Security** | Petro — competition judge, security firm |
| **Antheus** | DeFi boutique risk advisory shop used by Ibizu for LTV settings |

### DEX/Infrastructure:
| Entity | Framing/Context |
|---|---|
| **OKX** | Hedging venue for Aegis |
| **Bybit** | Hedging venue for Aegis |
| **Binance** | Hedging venue for Aegis |
| **Dub** | Audited Ibizu's JIT modification |
| **Stellar** | Blockchain used by Monetary for gold tokenization |
| **Aleo** | ZK/privacy chain — mentioned in privacy talk |

---

## 9. USE CASES HIGHLIGHTED — Which Applications Get Airtime and How Framed

### 1. Cross-Border FX (HIGH airtime)
**Framing:** "The $9T offchain FX market is untouched by crypto. Onchain is $9B — 1000x gap." Positioned as the biggest addressable market. Curve FX AMM, Mento's non-USD stablecoins, and Monetary's Turkish Eurobonds all attack this.

### 2. Yield for Non-US Institutions (HIGH airtime)
**Framing:** "DeFi LPs are stuck at 4-5% US T-bills. Real-world EM bonds yield 7-11%." Monetary's core pitch. Also in VC panel: "juiciest deals are in emerging markets."

### 3. Institutional Fixed-Income Onchain (MEDIUM airtime)
**Framing:** Libre Capital's $200M+ and Monetary's Eurobonds both use this. "Tokenized MMFs and bonds as M2-equivalent near-money instruments for institutional treasuries."

### 4. Capital Efficiency in DeFi Lending (MEDIUM airtime)
**Framing:** Twine: "$12B sitting at 0% LTV. Idle capital should earn." Credit delegation as productivity layer on top of existing lending infrastructure.

### 5. Confidential Compliance for Institutions (MEDIUM airtime)
**Framing:** "Banks don't broadcast your balance. Why should blockchains?" ZK proofs for FATF compliance without identity disclosure. FHE for fully encrypted transactions.

### 6. Delta-Neutral Yield (MEDIUM airtime)
**Framing:** Aegis, Ethena comparison. "Institutional-grade stablecoin that earns BTC funding rates without directional exposure." Positioned as superior to Ethena because no USDT counterparty risk.

### 7. DeFi-Native CDP Borrowing at Fixed Rates (MEDIUM airtime)
**Framing:** Ibizu — "One of the only places in DeFi you can lock in a fixed rate and repay any time." Synergy with Pendle fixed-yield instruments. Positioned as infrastructure for structured DeFi products.

### 8. Non-USD Stablecoins for Global South (MEDIUM airtime)
**Framing:** Mento's cKES — "A Kenyan merchant doesn't want USD exposure." Use case grounded in real economic need, not financial engineering.

### 9. Private Credit Onchain (LOWER airtime but technically deep)
**Framing:** CAP protocol — underwriter model fixes scaling bottleneck of originator-only DeFi lending. "Reputation becomes the moat" for underwriters.

### 10. MMF-equivalent Onchain Instruments (LOWER airtime but historically framed)
**Framing:** "Tokenized treasuries are the 1971 MMF moment." Ondo Finance's Josh makes this case explicitly. Regulatory analog to GENIUS Act as new Reg Q.

### 11. Decentralized Stablecoin OS (LOW airtime — early stage)
**Framing:** Polaris — "Not just a stablecoin, a stable coin operating system." P Swiss Franc, P Gold as future expressions. Bonding curve as reserve layer for any peg.

---

## 10. TONE & STYLE — Educational, Hype, Analytical, Debate, Interview

### Overall tone: Practitioner-analytical with occasional controlled hype
The conference skews heavily toward technical depth over marketing. Founders are expected to defend their mechanisms under grilling — judges interrupt, challenge assumptions, draw Terra comparisons. This is not a "pitch to retail" event; it's a "convince domain experts" event.

### Style by segment type:

**Keynotes (Egorov, monetary economics talks):** Educational/tutorial. Dense, no hype. Egorov uses whiteboard-style explanation: "Let me show you five AMM types." Academic presenter uses historical case studies. Both assume fluency in the underlying technology.

**Panels:** Debate + candid opinion. VC panelists speak freely: "Stablecoins will kill the eurodollar market" is said directly, not as a think-piece thesis but as a casual conviction. MiCA panel has European pessimism vs. US optimism tension.

**Pitch competition:** High-stakes interview meets technical audit. Founders pitch under 8-minute limit, then face 4 judges who ask: "How is this different from Terra?", "What happens with no demand?", "Can Aave just copy you?" Tone shifts from polished pitch to improvised defense. Best founders (Ethan/Ibizu, Talant/Twine) are fluent in their own mechanisms under pressure.

**Investor panel:** Candid, slightly provocateur. Daniel from Gnosis VC is the most quotable — "wallets for low-end smartphones" and "stablecoins will kill the eurodollar market" as contrarian theses. Selene from BPI France is measured and institutional. Peter from Namu Capital is concise and thesis-driven.

### Language register evolution:
- Morning keynotes: formal-technical
- Afternoon panels: casual-analytical ("basically", "right?", "kind of")
- Evening pitch competition: exhausted-candid ("I mean holy [ __ ] that's one big AVA pool" — Twine presenter)

### What's absent (notable):
- Almost no price speculation ("is BTC going to $200k")
- No "stablecoins will replace banks" retail-hype language
- No celebrity founder name-dropping
- Very little "we're changing the world" rhetoric — founders ground claims in mechanism design

### Creator's voice/style for content strategy:
The content creator (whoever recorded/produced this) chose to capture the raw, unedited practitioner conversation. No interjections, no editorial commentary, no B-roll descriptions. This is maximally raw — ideal for "what the experts actually think" content. The creator's implicit positioning: "We go where the real conversations happen, not the sanitized keynotes." The venue (Cannes Film Festival) is a deliberate contrast with the technical depth of content — glamour setting, zero-hype substance.

---

## APPENDIX: Pitch Competition Results

| Place | Team | Product |
|---|---|---|
| **1st (Winner)** | Twine (Talant) | Programmable credit on Aave/Morpho |
| **2nd** | Polaris (Lawrence) | Bonding curve CDP + governance token |
| 3rd-5th (unranked) | Aegis, Ibizu, Monetary | Delta-neutral, fixed-rate CDP, EM bonds |

Announcement: "The winner of this Zero TVL competition for Stable Summit 2026 first edition Cannes is... Twine. Sorry, I said Polaris first — I'm pregnant and my brain stopped working at 4 PM."

---

*Synthesis written by Claude (Sonnet 4.6 1M). Source: 3,215-line auto-generated transcript, Stable Summit Day 1, Cannes 2026. All direct quotes are from transcript; approximate figures noted where exact figure unclear in transcript.*

---
## BATCH 2
---
# Synthesis: Stabelsummit Day2 Video Script

**Source file:** `Stabelsummit Day2 Video Script.txt`
**Total lines:** 3,157
**Approximate runtime:** ~7 hours 11 minutes (timestamps run from ~15:19 to 7:11:37)
**Coverage:** All sections read in full.

---

## 1. OVERVIEW

This is a **verbatim auto-transcription** of Day 2 of "Stable Summit 2026" — a live, in-person conference focused on stablecoins, DeFi, RWA tokenization, and payments infrastructure. The event was held in Cannes (context clues: "in can," references to coming to New York next). The format is a full-day, multi-session summit with:

- **Keynote solo presentations** (20–30 min each, with brief Q&A)
- **Fireside chats** (one-on-one interviews, ~20 min)
- **Multi-panelist discussions** (4–6 speakers, moderated, ~45–60 min)
- **Lightning talks** (~10 min each)
- **Closing announcements** (next event: NY, Stable Summit + Vault Summit + Agentic Finance Summit)

The transcript is a raw auto-caption dump with timestamps in `HH:MM:SS` format prepended to every line. Speech is conversational, sometimes fragmented, with filler words, crosstalk, laughter, and technical terminology. The audience appears to be builders, founders, DeFi-native professionals, and some institutional representatives — not retail investors or journalists.

**Tone overall:** Practitioner-grade, candid, intellectually honest, sometimes blunt. Speakers openly criticize protocols (including Ethena, Stream Finance, Resolve, USDC's actions, PayPal USD). Not a marketing event — this is an insider peer-to-peer forum.

---

## 2. SPEAKERS & SEGMENTS

### SEGMENT 1 — Opening Keynote
**Speaker: Sebastian Deivo**
- Role/Affiliation: Not explicitly stated, but clearly a DeFi protocol architect / balance-sheet expert
- Topic: "DeFi in 2026: Stablecoin Vaults and Real World Assets"
- Style: Conceptual / theoretical framework talk. Self-describes as loving balance sheets.
- Key framing: The three-layer map of DeFi (User World → Stablecoins → DeFi World → Vaults → TradFi World → RWA)
- Evolution narrative: MakerDAO/Sky's journey from 2022 to the star system (Spark, Grove, Obsex as asset allocators)

---

### SEGMENT 2 — Solo Presentation
**Speaker: Dennis** (from ERC 3643 Association)
- Role: Association representative (volunteer team of ~8)
- Topic: "Rebuilding Capital Markets Infrastructure On Chain"
- Key claim: ERC 3643 has $35B+ in assets on-chain; predicts $250B by next year
- Positioned as the leading RWA tokenization standard globally
- Key partners mentioned: Apex Group, Stellar Foundation, Midas, BNP Paribas, Enterprise Ethereum Alliance, SEC Crypto Task Force
- Style: Energetic, audience-engaging, show-of-hands format, slightly evangelical about standards

---

### SEGMENT 3 — Panel: "Building Secondary Markets for Onchain Real World Assets"
**Moderator: Bianca Buzza** — Head of DevRel at Chronicle (first oracle on Ethereum, 2017; now powers $15B+ of onchain assets via Proof of Asset oracle)

**Panelists:**
- **Alio** (Emilio) — Senior VP of Engineering, Aave Labs; oversaw Aave V3, V4; leads Horizon (RWA initiative)
- **Charles Johnson** — Leads Digital Asset / DeFi / Tokenization / Blockchain at S&P Global
- **Graeme** — DeFi Product Lead at Centrifuge; protocol tokenizing ~$1.3–1.4B in RWAs; oldest RWA tokenization protocol (since early 2017)
- **Amos** — CBO at DJFT; RWA exchange regulated in Singapore and Hong Kong; tokenization partner of UBS, Invesco, BNY

---

### SEGMENT 4 — Solo Presentation
**Speaker: Chris** — Founder and CEO of Credit Cooperative ("Credit Coop")
- Topic: "Follow the Money: Payment Flows as Collateral"
- Key product: Spigot mechanism — smart contract that routes payment company receivables as loan collateral
- Key stat: $1.4B processed, no defaults; ~$250M/month current run rate; 45–46x coverage ratio

---

### SEGMENT 5 — Fireside Chat
**Speaker: Tomer** — Stellar Development Foundation
**Interviewer: Emiliano (Boundless)**
- Topic: "Building Configurable Privacy for Real World Payments"
- Stellar's X-ray protocol upgrade: added BN254 curve, ZK primitives
- Product: Stellar Private Payments (open-source, collaboration with Nethermind)
- Key distinctions: Confidentiality vs. Privacy; selective disclosure; association sets; administrative controls

---

### SEGMENT 6 — Panel: "Stablecoin Distribution: Interoperability from Issuance to Ubiquity"
**Moderator: Redwan** — Enterprise Ethereum Alliance

**Panelists:**
- **Imo** — Deutsche Bank (building stablecoin infrastructure for banks)
- **Ian** — Generic Money (onchain / DeFi native builder)
- **Tony** — Founder of Ubix (UBX); focused on stablecoin acceptance infrastructure
- **Ernesto** — Kibalis / Kalis; new consortium of 12 European banks; incorporated in Amsterdam; EMoney Institute; targeting post-summer 2026 go-live

---

### SEGMENT 7 — Fireside Chat: "Stable Coins as Infrastructure Powering New Markets"
**Interviewer: DeFi Dave**
**Speaker: Stani Kulechov** — Founder/CEO of Aave
- Topics: DeFi credit, yield-bearing stablecoins, Aave V4 architecture, RYOSHI integration (21M user e-commerce platform), surplus liquidity problem, incentives

---

### SEGMENT 8 — Keynote
**Speaker: Dr. Lucius Meiser** — Frankencoin Association
- Topic: "Macro Mechanics of Decentralized Credit and Money Creation"
- Academic/theoretical tone; discusses types of money, credit multipliers, capital requirements, oracle-free liquidations
- Product: Frankencoin (ZCHF) — collateral includes BTC (40%), Boss Info H Swiss IT shares (15%), gold tokens, Stanor ETFs

---

### SEGMENT 9 — Solo Presentation
**Speaker: Guillaume (Guom) Nervo** — Co-founder of Merkel
- Topic: "Institutional Stablecoins Need a Revenue Distribution Layer"
- Merkel stats: $1.5B+ tokens distributed, ~5M addresses rewarded
- Products mentioned: Ethena's use of Merkel; PayPal USD; GHO (Aave)
- Key regulatory framing: Genius Act vs. Clarity Act difference in yield distribution rules

---

### SEGMENT 10 — Panel: "Evaluating Systemic Risks in Interconnected Stablecoin Systems"
**Moderator: Syakin** — Oak Research

**Panelists:**
- **Engineer** — Solutions Architect at Yearn, former security auditor
- **Siril** — Contributor to Aladin DAO / FX Protocol (FXUSD stable coin, backed by rStETH and rBTC, no oracle, one-time fee, no liquidations)
- **Vojtech** — CEO/Co-founder of Accountable (ZK-proof financial verification for off-chain assets)
- **Michael** — CEO of Liquity (BOLD stable coin; described as "the Ethereum dollar," most decentralized stablecoin)

---

### SEGMENT 11 — Lightning Talk: "A Year of Yield Tokens in 10 Minutes"
**Speaker: Ptor** — Founder, Stable Watch
- Risk research firm using FRTB model and Monte Carlo "StableScene" model
- Announced at event: became a Sky Agent
- Delivers retrospective on YBS market growth, hall of fame, hall of shame

---

### SEGMENT 12 — Lightning Talk: "RWA Looping Is Broken"
**Speaker: Romeo** — Co-founder, 3F (Three Finance)
- Topic: "RWA Looping Is Broken — How to Fix It and Bring the Next $2T of Stablecoins On Chain"
- 3F model: single-settlement-cycle leveraged RWA carry trade using bridge facilitators + Morpho

---

### SEGMENT 13 — Final Panel: "Building the Best Stablecoin Liquidity in Fragmented Markets"
**Moderator: Ian GBI** — DeFi at Ethereum Foundation; co-founder of Yearn Protocol

**Panelists:**
- **Phil Fogle** — Building Cork Protocol (risk token primitives; allows tokenizing/trading any risk in any asset)
- **Ben Haslam** — CTO/Co-founder, Superset Finance (multi-chain unified liquidity architecture)
- **Lorenzo** — Co-founder, USDT0 (largest onchain mover of USDT across 25 chains; $8B+ volume in 15 months)
- **Jackie Chang** — Asia Strategy, Bridge (stablecoin issuance, on/off-ramp, stablecoin-backed cards)

---

### SEGMENT 14 — Mid-day Panel: Yield, Incentives, Delta-Neutral Products
**Moderator: Redstone (unnamed)**
Additional discussants including Credit Coop's Chris and Ptor (Stable Watch)
- Topics: delta-neutral yields, Athena, Sky, Maple Finance, incentive program analysis

---

### CLOSING ANNOUNCEMENTS
- **Next event:** Stable Summit New York — Stable Summit (day 1), Vault Summit (day 2), Agentic Finance Summit (day 3)
- Hosted at Microsoft office in Soho
- Partners/confirmed: Enterprise Ethereum Alliance, OpenAI, Cloudflare, Google, Microsoft, Coinbase

---

## 3. ALL KEY STATISTICS & DATA POINTS

### Market Size / Scale
- **$307B stablecoin market** (referenced implicitly across speakers)
- **$2T stablecoins** projected by 2028 (Standard Chartered prediction, cited by Romeo/3F)
- **$300 trillion** global real-world asset market (Romeo/3F)
- **$27B** RWA currently on-chain (Romeo)
- Stablecoins grew **150% annually** from 2020–2026; crypto market cap grew only **30% annually** (Romeo)
- **$15T** Visa total payment volume; **$25T** Visa + Mastercard combined (fiat)
- Visa settling **$3–4B annualized** in stablecoin flows; could reach **$30–40B in 2026** (Credit Coop)
- **$1.9T** stablecoin payments processed by Stripe (2024 annual report, per Chris)
- **$4B** stablecoin payments by Slash (Visa issuer) last year
- **$700M** euro stablecoins on chain; **$150M** other-currency stablecoins on chain

### Protocol-Specific Numbers
- **ERC 3643:** $35B+ in assets on-chain; 140+ institutional members; 12 working groups; 23 jurisdictions
- **ERC 3643 projection:** $250B in assets on-chain by next year
- **Apex Group** (ERC 3643 member): pledged $100B on T-Rex network (Polygon AggLayer) by 2027
- **Centrifuge:** ~$1.3–1.4B in RWAs tokenized
- **Chronicle:** Powers $15B+ onchain assets via Proof of Asset oracle
- **Credit Coop:** $1.4B processed; no defaults; ~$250M/month; 45–46x coverage ratio (legal maturity); 15–16x trailing 30-day; average loan duration 3 days
- **Settlement speeds:** Solana 200ms, Base 400ms, Ethereum 12 seconds
- **Morpho:** $750M in RWA deposits; $330M in borrows against RWA assets (>40% utilization — "parabolic")
- **USDT0:** $8B+ volume moved between chains in 15 months across 25 supported chains; 3rd largest USDT holder globally at $4.2B
- **Sky/USDS:** Largest yield-bearing stablecoin in 2026 (surpassed Ethena)
- **Ethena (USDe):** Yield dropped from 16%+ (bull) to ~3.5% (current); ~87% backed by T-bills and DeFi stablecoins
- **Kalis:** 12 founding banks; ~200M customer base across consortium banks
- **BOLD (Liquity V2):** 6–8% yield last 6–9 months; no counterparty risk; backed by wrapped stETH and wrapped BTC only
- **Merkel:** $1.5B+ in tokens distributed; ~5M addresses rewarded; 6-layer DeFi composability common
- **3F:** RWA looping previously required 30 loops over 30 days for 5x leverage; 3F reduces to 1 day
- **3F yields:** 4–7% for stablecoin lenders (most senior); 20%+ for leveraged positions; 5–10% for bridge facilitators
- **Frankencoin:** BTC 40% of collateral; Boss Info H Swiss IT (15%); gold tokens; Stanor ETFs
- **PayPal USD (PYUSD):** ~$25M spent over 2 years on incentives; never crossed $1B organically; now ~$4–5B with sustained incentives
- **Stripe:** ~$1.9T in stablecoin payments (2024 annual report)
- **YBS market:** grew 200%+ last year (Stable Watch data)

### Yield / Rate Data
- **DeFi lending rates:** Down to 1.8% on Morpho (March 2026) — below risk-free rate of 3.75%
- **RWA borrow rates:** 4.5–5.5% (Acredex/Falcon X on Morpho) vs crypto collateral rates much lower; 50–80% premium
- **CLO yield:** ~4.7%
- **Credit Coop yield:** 11–12% after fees
- **Ethena USDe yield:** ~3.5% current; peaked at 16%+ in bull market
- **Ethena distribution:** 3% baseline + 2% targeted campaign yield via Merkel
- **Business leverage effect:** 5% organic growth + 50% LTV at 3% interest = 30x growth in 50 years vs 10x unlevered
- **Security pricing:** worth 50 without leverage; worth 77 with 2x leverage at 3% cost

### Regulatory / Legal
- **GENIUS Act** passed July 2025: bans stablecoin issuers from distributing yield to holders
- **Clarity Act** (in negotiation): extends prohibition to platforms; carves out yield for risk-taking (LP, lending)
- **Broker-dealer haircut change** (3 weeks before event): 100% to 2% haircut on stablecoin balance sheets
- **OCC** issued request for comment on Genius Act implementation ~1 month before event
- **25 out of 50 US states** adopted Article 12 of UCC (digital asset control perfection)
- **ERC 3643** won innovation exemption from SEC Chairman Atkins; 6 Latin American countries adopted the standard next day
- **Circle stock** dropped ~20% in week before conference (Clarity Act yield restriction fears)
- **6** Latin American countries adopted ERC 3643 after Atkins exemption
- **23** jurisdictions ERC 3643 currently operates across

### Crisis Data
- **November 2025 depeg event:** $2.5B outflow; three major YBSCs depegged in one week (largest event since Terra/Luna USD)
- **Stream Finance / XUSD:** $93M in user deposits lost; collateral shifted off-chain to "loans to friends"
- **Elixir DUSD:** Circular minting concentration risk with Stream Finance
- **PYUSD:** 3+ years old; one of the biggest stablecoin ecosystems; still couldn't sustain $1B without incentives

---

## 4. CORE NARRATIVE ARCS

### Arc 1: "The Liability Side Is the Product, Not the Asset"
Sebastian Deivo opens Day 2 with this reframing: everyone obsesses over treasury allocations and vault strategies (the asset side) but stablecoins are fundamentally a liability product. Your job is to get people to hold, use, and trust your liability. Distribution, utility, brand, and integration are the real competition. This thread runs through every panel — Tony (Ubix) calls it "acceptance infrastructure," Ian calls it "demand not liquidity," and Jackie (Bridge) returns to "who is the buyer and what do they actually need."

### Arc 2: "Secondary Markets for RWA Don't Exist Yet — And Here Is Why"
The RWA secondary market panel (Bianca/Aave/S&P/Centrifuge/DJFT) diagnoses a structural gap: most RWAs are issued, held, and redeemed — it is a primary market with an exit button, not a true secondary market. AMMs are capital-inefficient for low-turnover, yield-bearing assets. KYC/KYB gates prevent permissionless liquidation. NAVs are calculated once daily, which breaks atomic DeFi. Oracle risk is unresolved (trust the issuer or have no price). The 3F lightning talk continues this thread: looping (the primary economic incentive for RWA tokenization) requires 30 iterations over 30 days due to T+1 settlement — so no one is doing it at scale.

### Arc 3: "Yield-Bearing Stablecoins Are Vaults Mislabeled — The November Reckoning Proved It"
Multiple segments converge on this: Michael/Liquity, Siril/FX Protocol, Oak Research, Ptor/Stable Watch, and the systemic risk panel all argue that "yield-bearing stablecoins" are actually investment funds or vaults, and calling them stablecoins harms users. When Stream Finance, Elixir DUSD, SMSUSD, Resolv USR, and VUSD all had incidents in 2025, users were not mentally prepared. The November 2025 event ($2.5B outflow, three depegs) is the case study used throughout. The proposed solution: call vaults "vaults," enforce risk disclosure at protocol level, build independent rating agencies.

### Arc 4: "DeFi Decentralization vs. Institutional Compliance — The Swiss Model as Best Answer"
Dennis (ERC 3643) sets the framing: permissioned digital securities need KYC but that destroys DeFi composability. Clawback mechanisms in DeFi are "untenable" (you'd have to freeze the LP, then the vault, then the user). Tomer/Stellar introduces configurable ZK privacy as the technical answer — hide amounts, keep identities, or use selective disclosure for specific parties. The Swiss DLT Act (know your shareholder, not KYC; freely transferable unless shareholder requests registration) is praised as the most elegant legal solution. Kalis (European bank consortium) plans to launch on Ethereum mainnet to gain DeFi interoperability from day one.

### Arc 5: "The EMVco Moment for Crypto" — Acceptance Infrastructure as the Missing Layer
Tony (Ubix) delivers the conference's most quotable argument: the card industry's EMVco kernel (the contactless payment standard embedded in every POS terminal) is the analogy for what stablecoins need. Right now stablecoin issuers are strapping cards onto the front of stablecoins, which means all transactions still run on legacy rails. The needed innovation is a blockchain-native, open-source kernel in every POS device — built as a consortium standard so no single party monopolizes it. Kalis, Ubix, Deutsche Bank, and Generic Money all agree during Q&A to pursue this as a shared project.

### Arc 6: "Regulatory Clarity Has Finally Arrived and It Is Reshaping Every Business Model"
Guillaume (Merkel) opens with the Circle stock drop to anchor the stakes. The Genius Act (July 2025) bans yield distribution for simply holding a stablecoin. The Clarity Act (in progress) extends this to platforms but carves out yield for "embedded risk" activities (LPing, lending). This forces stablecoin issuers to build precision yield distribution systems (Merkel's product) or face commoditization. Chris (Credit Coop) notes the broker-dealer haircut change from 100% to 2% that happened three weeks prior. Dennis references SEC's January digital securities rubric. Regulatory updates are embedded in every panel segment.

### Arc 7: "DeFi TVL Has Double-Topped — The Next Unlock Is Credit, Not Collateral"
Stani (Aave) argues DeFi now has a liquidity surplus but insufficient credit demand. The next wave: lending against non-fungible ERC-721 obligations, data (payment receivables, streaming income), and "abundance assets" (solar panels, batteries, GPUs). Aave V4's hub-and-spoke model (hub as central bank, spokes as commercial banks with credit lines from the hub) is designed to capture this. Romeo/3F argues the same from a different angle: $2T of stablecoins need yield opportunities and $300T of global RWA is the obvious destination — but the looping mechanism to get there is fundamentally broken.

### Arc 8: "Trustless vs. Fully Regulated — The Middle Is Dying"
Michael (Liquity) and Siril (FX Protocol) make the sharpest philosophical argument: the industry is bifurcating into (1) fully decentralized, trustless stablecoins (BOLD, FXUSD, Frankencoin) and (2) fully regulated, compliant stablecoins (USDC, USDT, Kalis). Products pretending to be both — "yield-bearing stablecoins" with opaque off-chain collateral and admin keys — are being squeezed out, evidenced by the November 2025 crisis. Dr. Lucius (Frankencoin) adds the macro argument: decentralized credit creation democratizes access to financing for sectors banks won't serve due to regulatory capital requirements.

---

## 5. POSITIONING PILLARS

### Pillar 1: "The Liability Side Is the Product" (Sebastian Deivo)
> "Anyone can emit a stable coin — I can, you can, anyone here. No one will care most of the time. It's really because your product if you're issuing a stable coin is the liability."
Reframes the entire stablecoin competition: stop competing on treasury yield and start competing on integration, utility, brand, and distribution.

### Pillar 2: "Stablecoins Are a Bridge, Not a Destination" (Sebastian Deivo)
Stablecoins = bridge between User World and DeFi World. RWAs = bridge between DeFi World and TradFi World. Vaults = the asset orchestration layer within DeFi. These are structurally different products requiring different strategies.

### Pillar 3: "Standards Are a Compass, Not a Fence" (Dennis / ERC 3643)
> "Standards are a way to gain adoption without inherently creating winners or losers."
> "ERC 3643 is a lighthouse."
Standards allow every participant to meet regulatory requirements in their own way — creating an ecosystem rather than a monopoly.

### Pillar 4: "Secondary Markets Require Machine-Readable Risk Signals" (Charles Johnson / S&P Global)
Without standardized, on-chain risk data traveling with the token, there is "no pressure in the pipe." AI agents cannot trade what they cannot price. Machine-readable risk signals — not static credit ratings, but real-time oracle feeds — are the missing piece for secondary RWA markets.

### Pillar 5: "The Payment Flow IS the Collateral" (Chris / Credit Coop)
> "Use the network, own the network."
Not theoretical — programmatic routing of stablecoin payment flows via spigot smart contracts creates super-senior collateral by control under UCC Article 12. Coverage ratios of 45x are achievable. Three-day average loan duration makes this the shortest-duration private credit product on-chain.

### Pillar 6: "Acceptance Is the Unlock for Issuance" (Tony / Ubix)
> "There's a point in spacetime that we can all work towards — when every bank and fintech on the planet offers wallets to their customers."
> "Acceptance is the exam question."
Issuance without acceptance infrastructure is zero sum. The industry must co-build an open, permissionless acceptance layer or risk all stablecoin innovation getting captured by legacy card rails.

### Pillar 7: "Tokenization Will Be to Wall Street What the Internet Was to Mail"
Used by multiple panelists; attributed to institutional reports. Signals the inevitability framing — not "if" but "when and by whom."

### Pillar 8: "Configurable Privacy, Not Maximum Anonymity" (Tomer / Stellar)
Privacy is a spectrum. For institutions: selective disclosure, global audit keys. For payments: hide amounts, keep identities visible (confidential tokens). Full anonymity only needed at the edges. The goal is compliance-compatible privacy that institutions can actually adopt.

### Pillar 9: "Boring RWAs Will Never Have Liquid Secondary Markets via AMMs" (Graeme / Centrifuge)
> "Boring RWAs are really always going to struggle building secondary market liquidity on chain because the current way that AMMs work is just not capital efficient for these kind of assets."
An LP giving up 4.7% CLO yield to sit in a 50/50 AMM pool earning 1–2% fee revenue is irrational. The answer is RFQ/prop market-maker models (not pools) for anything yield-bearing.

### Pillar 10: "Stay Paranoid. Collateral Composition Changes." (Ptor / Stable Watch)
> "Stream Finance started with T-bills. By the time they failed, 70% of their collateral was off-chain loans to friends."
One-time assessment of a protocol's safety is worthless. The only protection is continuous monitoring of collateral composition — which no user does and which Stable Watch now provides as a service.

---

## 6. HOOKS & OPENINGS

- **Sebastian Deivo (opening keynote):** "Who doesn't like a balance sheet at 10:00 a.m. on a Saturday?" — sets low expectations with humor, then delivers a rigorous framework.

- **Dennis / ERC 3643:** "ERC 3643 — what the hell is that? What is that even?" — opens by voicing the audience's own skepticism. Follows with show-of-hands: "Who here has deployed an ERC 3643 token?" Only a few hands. "Who here has ever used one?" More hands. Then reveals: "We have over 35 billion in assets on chain and no one uses the name."

- **Chris / Credit Coop:** Opens with the Visa/Mastercard 2–5 day settlement float problem — any payment company doing $1M/day has at least $2M sitting idle in a float buffer. Immediate pain for anyone who has built in payments. Pivot: "What if that float was your collateral?"

- **Romeo / 3F:** "Why would you lend at below risk-free on DeFi? I mean this makes no sense." — starts with an observable paradox (1.8% DeFi yield vs 3.75% risk-free rate). Then: "Stablecoins have grown 150% annually and crypto market cap has grown 30% annually. We need to find somewhere to put $2 trillion."

- **Ptor / Stable Watch:** "Last year was incredible and especially because of the Genius Act which pushed all issuers of payment stablecoins in a direction where they can't give us yield — we've seen a big influx of money into this new category of yield products." Immediately pivots to: "More than 200% growth in yield tokens. And also a lot of failures."

- **Guillaume / Merkel:** Opens with the Circle stock drop (~20% in the prior week) — gives the regulatory risk a concrete, financial-market hook before going into Genius Act vs Clarity Act mechanics.

- **Dr. Lucius / Frankencoin:** Opens with taxonomy of money types (central bank cash, CBDC, bank deposits, tokenized deposits, centralized stablecoins, DeFi stablecoins) — academic scaffolding used to frame the philosophical argument about who gets to create money and under what rules.

- **Tony / Ubix:** "We're in a bizarre place in the development of tokenized money where everyone is focused on issuance. Acceptance is the unlock." — reframes the entire industry's current focal point.

- **Stani / Aave:** Asked "what's been missing?" — "DeFi now has a surplus of liquidity. The problem is not liquidity, it's credit demand." Immediately inverts the scarcity narrative that has defined DeFi since 2020.

- **Bianca / Chronicle (panel moderator):** Asks each panelist to define what a "functioning secondary market" looks like from their vantage point before any discussion begins — surfaces the fact that all four define it differently, which itself becomes the first finding of the panel.

---

## 7. RECURRING PHRASES & LANGUAGE

### Exact Phrases (repeated or distinctive)
- **"The liability side"** / "your product is the liability" — Sebastian Deivo; echoed across multiple panels
- **"Boring RWAs"** — Graeme (Centrifuge); deliberate irony; boring = safe = structurally hard to trade on chain
- **"The payment flow IS the collateral"** — Chris (Credit Coop); essentially their product tagline
- **"Acceptance is the unlock"** / "Acceptance is the exam question" — Tony (Ubix); used at least twice verbatim
- **"A point in spacetime"** — Tony (Ubix); rhetorical device for describing a shared industry goal
- **"Stay paranoid"** — Ptor (Stable Watch); closing advice from the systemic risk session
- **"Tokenization will be to Wall Street what the internet was to mail"** — multiple speakers; attributed to institutional reports
- **"Do your own research" / "DYOR"** — invoked critically multiple times as inadequate user advice when protocols don't disclose risk
- **"Yield baggage"** — Michael (Liquity); "some stablecoins have a lot of baggage — exposed to different chains, protocols, collaterals, admin rights"
- **"Call it what it is"** — multiple speakers insisting yield-bearing stablecoins should be called vaults or funds
- **"Trust me bro"** — invoked to mock undisclosed off-chain collateral; the "Alameda spreadsheet" reference is the canonical example
- **"You can call the issuer on the phone"** — said somewhat ironically about why some people trust centralized stablecoins over decentralized ones
- **"Onchain finance"** vs. "DeFi"** — explicit debate about terminology; Lorenzo (USDT0): "DeFi is no longer really decentralized so onchain finance is more accurate for institutional conversations"; pushback from audience and other panelists
- **"Freely transferable"** — key regulatory/product term used by Centrifuge and DJFT to describe the goal for RWA tokens
- **"Permissioned vs. permissionless"** — contrast running throughout the entire day; applied to tokens, pools, liquidations, markets
- **"Super senior position by control"** — Credit Coop's legal innovation label (UCC Article 12 digital asset control)
- **"We can walk and chew gum"** — Tony (Ubix) on pursuing both proprietary product and open consortium work simultaneously
- **"The spigot"** — Credit Coop's core smart contract mechanism; their named product artifact
- **"Hub and spoke"** — Aave V4 architecture metaphor; hub = central bank, spokes = commercial banks with credit lines
- **"Abundance assets"** — Stani Kulechov's term for solar panels, batteries, GPUs as future RWA collateral
- **"One rate for all tends to zero profit"** — Guillaume (Merkel) on the economics problem of undifferentiated yield distribution
- **"Pipe without pressure"** — Charles Johnson (S&P) on secondary markets lacking standardized risk signals
- **"Fintech in the front, Aave in the back"** — Stani's framing for Aave's integration model (invisible infrastructure)
- **"Circle jerking each other"** — a panelist's blunt criticism of crypto conference echo chamber dynamics
- **"Building a car without brakes and blaming the driver"** — Oak Research moderator on inadequate risk disclosure by protocols

### Metaphors & Analogies
- **Balance sheet as the lens** — Sebastian Deivo's entire analytical framework
- **Vaults as "asset orchestration layer"** — Sebastian Deivo; separates the allocation function from the liability (stablecoin) function
- **"Diversification is the only free lunch in finance"** — Deivo; classic Markowitz quote applied to the Sky vault diversification argument
- **Chicken and egg problem** — cited for AMM liquidity bootstrapping, RWA secondary markets, stablecoin acceptance; multiple panelists
- **EMVco kernel** — Tony (Ubix); the contactless payment standard inside POS terminals; stablecoins need an equivalent
- **"POS device is just a swipe machine"** — Tony (Ubix); you can't accept card payments without the reader; can't accept stablecoins without a wallet
- **Sports bag vs. 10 black boxes** — Michael (Liquity) on BOLD vs complex YBSCs: "BOLD is three collateral types in one protocol — it's a sports bag. Complex yield stable coins are 10 black-box baggages stacked on top of each other."
- **"Car without brakes"** — Oak Research on protocols blaming users for not understanding risk
- **Vending machine** — Credit Coop's vault: "put USDC in, get CCUSDC back, put CCUSDC back in, get USDC out"
- **Central bank / commercial bank model** — Stani's description of Aave V4's hub-and-spoke: the hub is the central bank setting credit policy; each spoke is a commercial bank deploying that credit

---

## 8. COMPANIES / PROTOCOLS MENTIONED AND HOW THEY'RE FRAMED

### Stablecoins / Issuers
- **USDT (Tether):** 80% T-bills on balance sheet; $4.2B held by USDT0's smart contract (3rd largest holder); praised by Lorenzo (USDT0) as "best stablecoin in the world"; moat described as pure distribution without yield dependency
- **USDC (Circle):** Co-opted by Coinbase/Stripe for distribution; Circle froze accounts (referenced as "what happened with USDC this week"); Circle stock fell ~20% on Clarity Act fears; described as "tokenization of a money market fund"
- **USDT0:** 25 chains; $8B+ volume; native USDT scaled to zero on Neutron; LayerZero-based; "being the best stablecoin in the world and making it 1% better" — Lorenzo's stated thesis
- **USDS/sUSDS (Sky/Maker):** Largest yield-bearing stablecoin in 2026; star system of sub-agents (Spark, Grove, Obsex); Stable Watch becoming Sky Agent; "diversified portfolio" backing (crypto + RWA)
- **USDe (Ethena):** Delta-neutral carry trade; peaked 16%+ yield; now ~3.5%; ~87% T-bills and DeFi stablecoins; praised for demand-first GTM; criticized for shifting strategy without transparency; held up as case study in incentive-driven growth but also "lost its edge"
- **GHO (Aave):** CDP/over-collateralized; Merkel partner for targeted reward distribution
- **BOLD (Liquity V2):** "The Ethereum dollar"; no counterparty risk; no oracle; permissionlessly mint/redeem without KYC; 6–8% yield last 6–9 months; praised as most decentralized option available
- **FXUSD (FX Protocol):** No liquidations; one-time borrow fee; backed by rStETH and rBTC only; no oracle; challenge-based price discovery; described as "delivering better yields than Ethena from scratch"
- **Frankencoin (ZCHF):** Oracle-free via auction liquidation mechanism; can accept Swiss IT company shares as collateral; BTC, gold, Stanor ETFs also accepted; philosophical framing as democratization of money creation
- **PayPal USD (PYUSD):** $25M spent; never crossed $1B organically; described as "disastrous" given PayPal's distribution advantage (350M+ users)
- **CCUSDC (Credit Coop):** Launching in ~3 months; Maple/syrup USDC comparable; Pendle integration planned Q4 2026; Morpho/Aave composability Q4
- **Kalis / Kibalis EUR:** 12 European bank consortium; Amsterdam EMoney Institute; Ethereum mainnet launch post-summer 2026; ~200M customer base; working with Monerium
- **EuroC (Societe Generale):** Mentioned as European stablecoin player
- **Monerium:** Mentioned as Kalis partner candidate for euro stablecoin ecosystem

### DeFi Protocols
- **Aave:** V3/V4; Horizon (institutional RWA lending); integrated with RYOSHI (21M user e-commerce); hub-and-spoke V4 model; named as top 3 respected competitor by Lorenzo (USDT0)
- **Morpho:** $750M RWA deposits; $330M borrows; described as "parabolic" growth; praised by Lorenzo; 3F building on Morpho; permissionless vault structures praised
- **Centrifuge:** Oldest RWA tokenization (since 2017); $1.3–1.4B TVL; building "freely transferable" RWA tokens; CLO product yielding 4.7%; Chronicle oracle integration
- **Sky/MakerDAO:** $10B+ stablecoin; Spark/Grove/Obsex subagent model; the canonical case study for delegated asset allocation from stablecoin issuers
- **Pendle:** Q4 2026 integration target for Credit Coop; PT sniping alpha discussed
- **Cork Protocol:** Risk token primitives; tokenizes both sides of any liquidity risk trade; agentic underwriting direction; compared to Geico's online auto insurance slider model
- **Superset Finance:** Multi-chain virtualization layer; one deposit simultaneously powers trades on multiple chains; described as unprecedented architecture
- **Cap Money:** On-chain credit default swap equivalent for private credit; praised by Credit Coop as a good competitor
- **Steakhouse:** Risk curator on Morpho; praised for quality underwriting; mentioned as surviving Resolv exposure; named as respected competitor by Jackie (Bridge)
- **3F (Three Finance):** Going live in private beta at time of conference; bridge facilitator auction model; single-settlement-cycle RWA leverage; built on Morpho
- **Frankencoin:** Oracle-free; auction liquidations; Swiss company shares as novel collateral class
- **Yearn:** Engineer (Solutions Architect) on systemic risk panel; Ian GBI (co-founder of Yearn) moderates final panel

### Infrastructure
- **Chronicle:** First Ethereum oracle (2017); $15B+ powered; Proof of Asset oracle for tokenized assets; Centrifuge pushes CLO balance sheet on-chain via Chronicle
- **LayerZero:** Used by USDT0 and Bridge; praised for cross-chain interoperability; "always replies on a Sunday" (Lorenzo); named as top 3 respected infrastructure by multiple panelists
- **CCTP (Circle Cross-Chain Transfer Protocol):** "Burn and mint" model praised as elegant; USDT0 moved 6x what CCTP moved in its first year; named as top 3 infrastructure by panelists
- **Stellar:** X-ray protocol upgrade (BN254 curve, ZK primitives); Stellar Private Payments (Nethermind collaboration); ERC 3643 Sorbon implementation coming
- **Ethereum Foundation:** Ian GBI now at EF; running use-case lab in San Francisco; actively working on privacy and intent ERCs
- **Plasma:** Low-cost transaction layer; used in RYOSHI/Aave integration; referenced in USDT0 context
- **GSR:** Market maker providing instant mint/burn on Centrifuge tokens; described as how Centrifuge solves the AMM liquidity problem
- **Maple Finance (syrup USDC):** Comparable for Credit Coop's vault model; praised for reducing emissions while retaining holders
- **Ando Finance:** Tokenized money market with RFQ-style retail product; Franklin Templeton ETF partnership; "always gives best execution price"; described as solving RWA secondary liquidity via prop market making
- **Securitize:** Tokenized securities platform; mentioned alongside Ando and Coinbase/Kraken stocks
- **Coinbase:** Tokenized stocks; Morpho integration (bringing new institutional liquidity to Morpho); paid by Circle for USDC distribution; named as Agentic Finance Summit partner
- **BlackRock (BUIDL):** USDC redemption fund on-chain; instant redemption feature praised; USDTB's high-quality backing component (Ethena)
- **Apollo:** Buying Morpho tokens; seen by panelists as institutional validation of RWA lending as a sector
- **Franklin Templeton:** Ando partnership; BVI jurisdiction; tokenized ETF

### Institutional / Regulatory
- **S&P Global:** Digital asset/DeFi/tokenization team; provides risk ratings for some stablecoins but only static, not real-time; Charles Johnson argues for "machine-readable risk signals" as the needed evolution
- **Deutsche Bank:** Building stablecoin payment infrastructure for banks; Imo focused on atomic DVP settlement, B2B invoice data, confirmation of pay services
- **BNP Paribas:** Adopting ERC 3643 for tokenized securities pilots
- **Enterprise Ethereum Alliance (EEA):** Co-hosting Agentic Finance Summit in NY; partner of ERC 3643; represented by Redwan (moderator)
- **Credora:** Praised for rating vaults with actual due diligence rather than self-assessment
- **Accountable:** ZK-proof financial verification; direct integrations with exchanges/custodians/banks for verified financial data; "we show reality, we don't make opinions"
- **Gauntlet:** Risk curator mentioned in context of Resolv/USR depeg — question about how established curators can fail
- **Oak Research:** Moderates systemic risk panel; Syakin's firm; described as providing analysis that users ignore

### Failed / Problem Protocols (cautionary examples)
- **Terra/Luna (USTC):** The benchmark stablecoin collapse; referenced multiple times as the gold standard of failure; "biggest wipeout since Luna USD" used as comparative phrase
- **Stream Finance / XUSD:** Lost $93M; started with T-bills; composition shifted to off-chain "loans to friends"; cascaded into Morpho/lending markets; described as "free money" when borrowers stopped repaying; multiple panelists discuss in detail
- **Elixir DUSD:** Circular minting concentration risk with Stream Finance; described as "robbing users"; listed in Stable Watch's hall of shame
- **Resolve Finance / USR:** Recent depeg (week before conference); panelists note it had "never depegged before" so users trusted it; Steakhouse had exposure and survived
- **Usual protocol:** Changed redemption price overnight from $1 to ~$0.86; described as "an abuse of trust"; one panelist calls it "the most offensive" failure because it was intentional
- **SMSUSD:** Lost money trading treasury options; "a lack of skilled people or bad luck"; listed in hall of shame
- **VUSD:** Sega protocol counterparty risk; listed in hall of shame
- **Alameda (FTX):** Invoked as origin of "trust me bro" spreadsheet collateral problem; why Accountable was built

---

## 9. USE CASES HIGHLIGHTED — AIRTIME AND FRAMING

### 1. RWA Tokenization + Secondary Markets (most airtime — full panel + multiple keynotes)
Described as the essential next wave that is fundamentally immature. Key diagnosis: we have tokenized the simplest (T-bills) and some of the most complex (private credit) assets, but the secondary trading infrastructure doesn't exist. AMMs don't work for low-turnover yield assets. KYC restricts who can liquidate. No standardized risk signals on-chain. Oracle pricing requires trust in NAV from the issuer. Near-term solutions: freely transferable tokens (Centrifuge), RFQ/market-maker models (Ando, DJFT/GSR), risk signal oracles (Chronicle), and 3F's leveraged loop mechanism to finally create yield demand for the asset class.

### 2. Payments / Stablecoin Settlement Infrastructure (heavy airtime — 2 dedicated segments)
Credit Coop: payment receivables as on-chain super-senior collateral; programmatic repayment; no defaults in 3 years; $250M/month. Interoperability panel: moving value across bank systems and chains without 5 hops and a 3-day settlement window. Tony/Ubix: stablecoin-native POS payments without card intermediation. Tomer/Stellar: privacy for payroll and B2B payments where amounts must be confidential. Kalis: European bank consortium creating stablecoin for interbank settlement as cash equivalent. Framing: payments is the killer use case but requires solving acceptance, KYC interoperability, atomic DVP, invoice data in memo fields, and cross-chain liquidity simultaneously.

### 3. Yield-Bearing Products / "Savings Accounts" (heavy airtime — full panel, lightning talk, fireside)
The market bifurcated: T-bill-backed stablecoins (safe, commodity, yield not distributable under Genius Act); DeFi-native yield products (risky, must disclose collateral). Ptor (Stable Watch): "200%+ growth in yield-bearing products last year." Guillaume (Merkel): Clarity Act will require embedded risk before yield is payable; precision distribution is the answer. Critical view: most yield-bearing stablecoins are vaults sold as stablecoins; November 2025 was the reckoning. Maple Finance praised as doing incentive programs correctly (cutting emissions slowly while retaining sticky users).

### 4. Institutional DeFi / Permissioned Lending (medium-high airtime)
DJFT regulated in Singapore and Hong Kong; UBS, Invesco, BNY as tokenization partners. ERC 3643: $35B+ digital securities; permission token standard for share registries. Aave Horizon: institutional users mostly hold-and-leverage for yield optimization rather than actively trading. Key friction: KYC gates prevent DeFi composability; whitelisted liquidators required; Morpho flash loans cannot be used for permissioned RWA tokens. Swiss DLT Act praised as the best legal framework — "know your shareholder" not "know your customer."

### 5. FX / Cross-Currency Stablecoins (medium airtime — dedicated panel segment)
Euro stablecoins: Kalis, EuroC, Monerium; all struggling with liquidity vs USD-denominated competitors. USDT0: building non-USD products (HT0 on Conflux, TedGold Zero) but slower than USD expansion. Critical gap: on-chain FX requires swap infrastructure, credit lines, netting standards, and cross-chain interoperability none of which exists adequately. Tony's blunt summary: "we need swaps, you also need swaps — this is unsolved."

### 6. Private Credit / Receivables Financing (medium airtime)
Credit Coop: payment receivables as super-senior on-chain collateral via spigot; three-day duration; 45x coverage ratio. Sebastian Deivo: private credit was 2025's hot sector; CLOs have never defaulted; direct lending has a more complex risk profile. S&P: credit risk assessment for on-chain private credit must include smart contract risk, oracle risk, and custody/blockchain risk on top of traditional credit analysis. KKR raised more private credit than private equity in 2024 — cited as evidence of institutional direction.

### 7. Agentic Finance / AI Underwriting (emerging theme — mentioned in 5+ segments)
Machine-readable risk signals on tokens enabling AI agent trading of RWAs. Cork Protocol's model compared to "Geico auto insurance online" — slider-based, instant, continuously repriced risk underwriting without human intervention. Aave V4 hub designed so any builder team can plug a spoke in. Stani: "liquidity moves programmatically to risk-adjusted opportunities" — already partially agentic. NY event announced as Agentic Finance Summit with OpenAI, Cloudflare, Google, Microsoft, Coinbase as confirmed speakers. Described as the next wave: stablecoins as infrastructure for AI agent economy.

### 8. Decentralized / Trustless Stablecoins (medium airtime, philosophical)
BOLD, FXUSD, Frankencoin presented as the trustless alternative track. Michael (Liquity): "The Ethereum dollar — no freeze risk, no oracle manipulation, mint/redeem without KYC." Siril (FX Protocol): backed purely by rStETH and rBTC; challenge-based price discovery; no oracle at all. Dr. Lucius: macro argument — decentralized credit creation democratizes financing for sectors banks won't serve due to regulatory capital requirements. Counter from Vojtech (Accountable): "the off-chain opportunity is orders of magnitude larger than the on-chain opportunity" — trustless has a ceiling.

### 9. ZK / Privacy (light airtime — one dedicated segment)
Stellar Private Payments: open-source, configurable privacy framework. Confidential tokens (hide amounts, keep identities visible) for payroll use case. Privacy pools (hide both parties) for more sensitive transactions. "ZK is the first candidate but not the only one." Composable ZK proofs (composing proofs across multiple DeFi operations) "probably achievable by end of 2026." Boundless: integrating Term Labs and Comply Advantage into on-chain ZK proofs for compliance verification without exposing underlying data.

---

## 10. TONE & STYLE

### Overall Register
**Practitioner peer forum, not a marketing conference.** The dominant tone is candid, technically dense, self-critical, and occasionally blunt to the point of profanity (multiple f-words in the raw transcript — organic conversation, not staged). Speakers name specific protocols that have failed and describe in precise terms why they failed. Audience members ask technically sophisticated questions (Swiss DLT Act, clawback in DeFi, xStocks on DEXes).

### Sub-tones by Speaker / Segment

**Sebastian Deivo (opening keynote):** Intellectual and framework-driven. Builds mental models (the three-world map, the asset orchestration model). Gentle humor to warm the room, then high-density slide-by-slide analysis. Self-aware about being a "balance sheet person" in a room of builders.

**Dennis / ERC 3643:** Evangelical and participatory. Show-of-hands techniques to create audience investment. Slightly defensive about standards being "unsexy" but argues for their inevitability. Uses celebrity name-drops (Apex Group, BNP Paribas, S&P Global) to establish credibility.

**RWA secondary market panel (Bianca moderating):** Professional and honest about structural limitations. S&P's Charles Johnson adds institutional gravitas; Graeme (Centrifuge) is candid about the AMM capital efficiency problem; Alio (Aave) is more promotional about Horizon's potential. Most balanced panel of the day.

**Chris / Credit Coop:** Data-driven and product-pitch focused. Specific numbers (coverage ratios, settlement speeds, loan duration), legal frameworks (UCC Article 12), and a clear roadmap (CCUSDC in 3 months, Morpho/Pendle by Q4). Least philosophical speaker of the day — purely operational.

**Tomer / Stellar:** Careful and technically precise. Explicitly distinguishes "confidentiality" from "privacy" — takes care not to oversell ZK. Measured about what's possible by when.

**Interoperability panel (Tony, Imo, Ian, Ernesto):** Most animated debate of the day. Tony is the most quotable speaker overall — confident, macro-framing, slightly contrarian. Kalis's Ernesto is measured and diplomatic. Ian is constructively cynical. Imo (Deutsche Bank) is analytical and focused on specific B2B payment failure modes.

**Stani / Aave fireside:** Visionary and occasionally hedged ("we'll see"). DeFi Dave is a deferential interviewer. Stani thinks in multi-decade timeframes ("abundance assets" as future collateral) while grounding it in current products (RYOSHI integration).

**Dr. Lucius / Frankencoin:** Academic, macro-economic, philosophical. Least promotional speaker. Interested in the theory of money creation, capital requirements as a distortionary force, and DeFi as a democratizing force for credit access. Audience questions are the most conceptual of the day.

**Guillaume / Merkel:** Dense regulatory update delivered drily. The Circle stock hook gives impact. Content is highly technical (Genius Act clause-by-clause vs Clarity Act carve-out mechanics) but delivered in a builder context.

**Systemic risk panel (Oak Research moderating):** Most critical of the industry. Syakin (Oak Research) explicitly condemns the culture of blaming users for not reading the fine print. Michael (Liquity) and Siril (FX Protocol) are the most ideologically committed to the trustless thesis. Vojtech (Accountable) is the pragmatist arguing for verified off-chain data as a complement to on-chain systems.

**Ptor / Stable Watch:** Data-journalism style. "Hall of fame of f***ups" framing is memorable and slightly darkly humorous. Objective but grim about what happened in 2025. Presents risk models (FRTB, Monte Carlo) as the professional's answer.

**Romeo / 3F:** Startup-pitch energy. Clear problem-solution structure. Enthusiastic that the product is going live this week. Uses simple math to illustrate the looping problem (30 loops, 30 days, 5x leverage) and the solution (1 settlement cycle).

**Final panel (fragmented markets, Ian GBI moderating):** Late-day, slightly looser energy. Lorenzo (USDT0) is the most confident and promotional. Phil Fogle (Cork) is the most technically specific about risk tokenization primitives. Ben Haslam (Superset) is measured about multi-chain virtualization. Jackie Chang (Bridge) is pragmatic about the on/off-ramp and compliance realities.

### Audience Signals
Show-of-hands questions reveal: most attendees have not deployed or used ERC 3643 tokens; most are unfamiliar with the SEC's digital securities market structure rubric; nearly all have heard of Ethena. References to Curve 3-pool, flash loans, and Terra/Luna get immediate knowing responses with no explanation needed. Q&A questions from the floor are sophisticated (Swiss DLT Act question, clawback in DeFi composability, xStocks liquidity on DEXes). The crowd skews builder-native, not institutional.

---

*End of synthesis. This document covers 100% of the 3,157-line transcript — all 7+ hours of Stable Summit 2026 Day 2 content.*

---
## BATCH 3
---
# Video Script Synthesis — _VS_PARTIAL_3.md

**Files covered:**
1. `Economics of Payment Video Script.txt` (~143KB, 2815 lines)
2. `State of Fintech Video Script.txt` (~81KB, 1444 lines)

---

# FILE 1: Economics of Payment Video Script

## 1. OVERVIEW

**Format:** Academic conference panel — "Economics of Payments" conference hosted by the Federal Reserve Board. Video transcript of a recorded session.
**Length:** ~2.5–3 hours of content; 2815 lines of transcript.
**Structure:**
- Session intro by unnamed moderator (Elena referenced as organizer)
- Paper 1 presentation: Matti Alandoni (Federal Reserve Bank of Boston) — "Stablecoins and Money Market Funds"
- Discussion of Paper 1: Federico Greenberg (IMF)
- Paper 2 presentation: Sharon Ross (Federal Reserve Board) — "Leverage and Stablecoin Pegs"
- Discussion of Paper 2: Scott Shu (West Virginia University)
- Brief Q&A on both papers
- Welcome/keynote intro by Dave Mills (Federal Reserve Board, Payments Division)
- Keynote address: Sir John Cunliffe (Deputy Governor for Financial Stability, Bank of England / Chair, CPMI at BIS)
- Q&A with Sir John Cunliffe

**Style:** Dense academic/policy discourse. Formal presentation language; no hype. Quantitative, regression-driven, model-based. The keynote is more discursive and policy-oriented, with some deliberate wit and "parting shot" candor (Sir John's last day as a central banker).
**Audience:** Academic economists, central bank officials, payment system researchers, financial regulators. Highly specialist.

---

## 2. SPEAKERS & SEGMENTS

### Matti Alandoni — Federal Reserve Bank of Boston
**Role:** Paper presenter (Paper 1)
**Paper title:** Implied: "Stablecoins and Money Market Funds" (runs/flights to safety)
**Key arguments:**
- Stablecoins resemble money market funds (MMFs) in their run dynamics
- Documents "flights to safety" within the stablecoin ecosystem analogous to flights from Prime to Government MMFs
- Identifies a psychological peg threshold at $0.99 — outflows jump 10x when price crosses below that level
- Stablecoins on larger blockchains (Ethereum, Tron, Binance) show flight-to-safety within the chain; on smaller blockchains, money simply leaves the chain entirely
- Stress episodes studied: Terra Luna collapse (2022) and SVB collapse (2023)

### Federico Greenberg — IMF
**Role:** Discussant of Paper 1
**Key arguments:**
- Affirms the MMF analogy but cautions it's one dimension of a complex "elephant"
- Uses "blind man and the elephant" parable: each analogy (MMF, exchange rate peg, etc.) captures one leg
- Draws parallel to exchange rate regime stress: Bitcoin price shocks to the crypto ecosystem resemble terms-of-trade shocks to a small open economy
- Calls for more robustness in regression analysis; notes very few cross-sectional observations (only 2–3 coins represent ~90% of market cap)
- Highlights key difference: stablecoins are NOT remunerated (unlike MMFs), making them more exposed to the monetary policy cycle
- Notes stablecoins are primarily settlement assets within crypto, not standalone money

### Sharon Ross — Federal Reserve Board
**Role:** Paper presenter (Paper 2)
**Paper title:** "Leverage and Stablecoin Pegs" — joint with Gary Gorton, Beth Klee, Chase Ross, Alex Velikov
**Key arguments:**
- Stablecoins maintain their peg NOT through issuer interest payments, but through secondary market lending rates
- Demand for stablecoins comes primarily from leveraged crypto speculation; speculators borrow stablecoins to take levered positions in Bitcoin
- Two peg-stabilization channels identified: (1) liquid asset portfolio share channel — issuer shifts from commercial paper to treasuries; (2) redemption channel — reduced circulating supply when speculative demand falls
- Critical linkage point: stablecoins are the transmission belt between traditional financial markets and crypto markets, in BOTH directions
- At one point, Tether was the third-largest holder of US commercial paper
- Instruments speculative demand using MLB (Major League Baseball) viewership via FTX umpire patch sponsorship — a creative IV strategy

### Scott Shu — West Virginia University
**Role:** Discussant of Paper 2
**Key arguments:**
- Self-deprecating macro guy; admits he nearly invested $1,000 in Bitcoin in 2010 (would have earned $34.6 billion)
- Summarizes Paper 2 as: "investors with too much money lending to issuers who don't have to disclose anything so they can make more money lending to crypto trader speculators who might be linked to the issuers"
- Questions whether stablecoins are truly money — argues they're more "get-rich-quick schemes"
- Notes that US pre-WWII average inflation was 0%; post-WWII it's been positive — questions whether asset-backed crypto is the right direction given history
- Raises regulatory screaming question: why do governments allow this?
- Key comparison: stablecoin liquidity share allocations (30–60%) mirror voluntary bank reserve ratios before the Great Depression

### Dave Mills — Federal Reserve Board (Payments Division)
**Role:** Conference host intro for keynote
**Notes:** Leads CPMI work on new technologies and cross-border payments

### Sir John Cunliffe — Bank of England / BIS CPMI Chair
**Role:** Keynote speaker (last day as central banker — Halloween, midnight, "turning into a pumpkin")
**Key arguments:**
Three main areas covered:
1. **G20 Cross-Border Payments Roadmap** (CPMI/FSB hat)
2. **Digital Pound / CBDC exploration** (Bank of England hat)
3. **Regulation of systemic stablecoin Payment Systems in the UK** (Bank of England hat)

Core thesis: Central banks can't know which technology will win, so must maintain optionality, ensure beneficial innovation can happen, and ensure risks are managed to equivalent standards as existing money/payment systems. "Same risk, same regulation."

---

## 3. ALL KEY STATS & DATA

### Stablecoin Market Size
- Stablecoin market cap rose quickly to ~**$200 billion** (from chart description)
- Tether: **$84 billion** AUM (largest, offshore, audited by no recognized firm)
- USDC: **$25 billion** AUM (US-based, audited by Deloitte)
- Top 12 stablecoins = **>99% of total market cap** — "winner take all game"
- Terra Luna: peaked at **$19 billion** market cap (19 billion tokens at $1 each), collapsed to near zero; still ~10 billion tokens technically in circulation

### MMF Comparison
- US Money Market Funds: ~**$5 trillion** in assets
- Prime MMFs: invest in commercial paper, CDs, Treasury/agency debt, repo
- Government MMFs: only Treasury/agency debt and backed repo

### Run Dynamics
- Peg threshold effect: 
  - Price between $1.00 and $0.99: outflows of **0.34% per day**
  - Price crosses below $0.99 (touching $0.9991 rounded to 99¢): outflows jump to **3.43% per day** — ~10x larger
  - Price below $0.98: outflows moderate back down
- Two focal stress episodes: Terra Luna (2022) and SVB collapse (2023)

### Paper 2 Empirical Data
- Margin lending rate for stable coins: average ~**7–8%** annually (Sharon Ross data)
- Perpetual Futures funding rate: average **~20%**, standard deviation **~30%**
- One SD increase in speculative demand → stable coin lending rate increases ~**50%**
- Terra Luna: lost **27% of its face value in a single day** at peak of collapse
- ~**30% of time** there are net redemptions for largest stablecoins
- DCA (crypto-backed stablecoins): $1.70 of Ethereum deposited to get $1 of DAI
- Tether: **~50%** of self-reported holdings in Treasuries (the rest opaque)
- Tether at one point: **third-largest holder of US commercial paper**

### G20 Cross-Border Payments Roadmap
- G20 targets for 2027: cost, speed, reliability for wholesale, retail, remittance payments
- Current progress: "somewhere between half and two-thirds of the way there" to 2027 targets
- Payment systems in **more than 100 jurisdictions** actively using ISO 20022 messaging standard
- 19 "building blocks" identified by CPMI for the roadmap
- First annual monitoring report delivered to G20/Central Bank governors in Marrakesh

### UK Cash Use
- 10 years ago: **>60%** of UK transactions were physical cash
- Last year: **~14%** of UK transactions were physical cash
- UK debit card transaction fees for large firms: **25–30 basis points**
- Small UK merchants: **up to 150 basis points** for card transactions
- US rates: "a multiple of that"

### Digital Pound CBDC
- Bank of England consultation paper: received **50,000 responses** (vs. normal 4–5,000 from financial firms)
- Three main concerns from public: privacy, programmability, access to physical cash
- Project Rosalind: demonstrated a digital pound platform using BIS Innovation Hub with private sector
- UK Parliament passed legislation giving Bank of England power to regulate systemic stablecoin payment systems

### Stablecoin Regulatory Standards
- CPMI/IOSCO issued stablecoin guidance in **2022**
- Financial Stability Board issued high-level recommendations on global stablecoins in **2023**
- Bank of England Financial Policy Committee (2022): backing assets must be "extremely high quality liquid assets" — Central Bank Reserves OR very liquid government securities
- No collective deposit insurance for stablecoins (no industry to share cost)
- Libra announcement: **June 2019** — the "Black Ships" moment for central banks
- Libra fell by the wayside "last year" (from speaker's perspective, ~2022)

---

## 4. CORE NARRATIVE ARCS

### Arc 1: Stablecoins as Unregulated MMFs (Paper 1)
Stablecoins and MMFs are structurally analogous: both hold financial assets as backing, both promise redemption at par, both are runnable. The paper pushes this metaphor quantitatively — demonstrating flights to safety within the ecosystem analogous to Prime→Government MMF flows during stress, a 10x run amplification at the 0.99 psychological threshold, and chain-level dynamics (flee within chain on large chains; flee the chain entirely on small chains).

### Arc 2: Speculation Sustains the Peg (Paper 2)
The puzzle: stablecoins have run risk but pay no yield, yet they maintain their peg. Answer: holders are compensated not by issuers on the primary market, but by lending to leveraged crypto speculators on secondary markets (7–8% margin lending rates). When speculative demand falls, issuers either shift reserves to more liquid assets (commercial paper → Treasuries) or allow more redemptions (reducing supply → raising lending rates). This creates a tight feedback loop between crypto speculation and traditional money markets.

### Arc 3: Stablecoins as the Crypto↔TradFi Bridge
Both papers converge on this: stablecoins are the transmission mechanism between crypto markets and traditional financial markets, in both directions. A shock to commercial paper markets raises stablecoin run risk; a shock to crypto markets causes stablecoin issuers to sell traditional assets. Tether as the third-largest commercial paper holder is the vivid example.

### Arc 4: The Libra Wake-Up Call and Its Legacy (Keynote)
Sir John frames the entire post-2019 regulatory landscape as a response to the Facebook Libra announcement — the "Black Ships moment." Before Libra: central banks watched warily. After Libra: galvanized into three parallel tracks — G20 cross-border payments roadmap, CBDC exploration, stablecoin regulatory frameworks. The arc is: threat provoked urgency, urgency created frameworks, frameworks are still incomplete, time to deliver is now.

### Arc 5: Are Stablecoins Money? (Cross-cutting debate)
Multiple speakers interrogate this. Sharon Ross: stablecoins "aim to be money but are bad money." Scott Shu: "Not a store of value we think about for money — more get-rich-quick schemes." Sir John: reframes the question — what matters is whether beneficial innovation can happen safely. The paper argues stablecoins have a "negative convenience yield" (another Sharon Ross paper). Greenberg: stablecoins are primarily settlement assets within crypto, not general money.

### Arc 6: The Elephant Problem (Federico Greenberg)
Greenberg introduces the "blind man and the elephant" meta-narrative: each analogy (MMF, exchange rate peg, small open economy) captures one dimension of what stablecoins are. No one has seen the whole elephant yet. This is a meta-comment on the entire field of stablecoin research.

---

## 5. POSITIONING PILLARS

### From Papers 1 & 2:
- **"Stablecoins are like unregulated money market funds"** — the dominant academic framing
- **"Same risk, same regulation"** — the regulatory principle (Sir John's keynote)
- **"Stablecoins link crypto to the real economy"** — the systemic risk framing
- **"Speculation sustains the peg"** — the counterintuitive mechanism Paper 2 reveals
- **"Flights to safety within crypto"** — stablecoins have an internal hierarchy of safety

### From Keynote:
- **"Black Ships moment"** — the Libra announcement as irreversible wake-up call
- **"Optionality"** — the Bank of England's answer to uncertainty about which tech wins
- **"Singleness of money"** — the public policy goal of ensuring all forms of money are interchangeable at par
- **"Small frictions, big behavioral shifts"** — the theory of why payment technology changes matter (contactless tap → huge cash decline)
- **"The payment becomes invisible"** — tokenization's promise: payment integrated seamlessly into larger processes
- **"Public sector anchor"** — CBDC as backstop for competition/innovation even if not widely used
- **"Innovation that improves money can happen, but not without managing risk"** — the balancing act

---

## 6. HOOKS & OPENINGS

- **"At midnight on Tuesday I stopped being a central banker after 10 years. I turn into a pumpkin. It's Halloween."** — Sir John Cunliffe opening his keynote
- **"This is the chance to say all the things I've wanted to say for the last 10 years and haven't been able to."**
- **"What is the Bank of England for? That's a difficult question. So rather than give them the long list... I give a much simpler answer: central banks' responsibility is that that most foundational element of not just the economy but society — the thing that we call money — works."**
- The Terra Luna coffee cup metaphor: "On my desk over there I have two empty coffee cups. To understand the fragility of this mechanism: if I take one and throw it away, you will still value the remaining coffee cup at zero."
- Scott Shu: "I calculated this morning for the first time — I've been avoiding this for 14 years — $34.6 billion is what I would have earned if I had invested $1,000 in Bitcoin."
- Scott Shu summarizing Paper 2: "investors with too much money and perhaps too many Super Bowl rings lending to issuers who don't have to disclose anything at all so those investors can then make even more money lending to crypto trader speculators who might actually be linked to the issuers unbeknownst to everyone involved."
- Sharon Ross on the FTX/MLB instrument: "we use Major League Baseball viewership" — then shows a photo of umpires wearing the FTX logo patch
- Sir John on Henry Ford: "if he'd asked people what innovation they wanted, they'd have said they wanted faster horses"
- Sir John on Deuteronomy: "the idea that somewhere in Deuteronomy it's written that this is the model of the banking system and we can't disturb it is something I don't subscribe to"

---

## 7. RECURRING PHRASES & LANGUAGE

**Exact phrases:**
- "Runnable" / "run risk" — used repeatedly by all speakers
- "Flight to safety" — the core concept of Paper 1
- "Breaking the buck" — MMF term applied to stablecoin peg threshold
- "Singleness of money" — Sir John's key concept for CBDC motivation
- "Same risk, same regulation" — regulatory principle, repeated
- "Black Ships moment" (referring to 1853 Japan / Libra)
- "Settlement asset" — how Greenberg and others classify stablecoins' primary function
- "Permissionless blockchain" — raised in regulatory context
- "Bankruptcy remote legal entity" — Sir John's regulatory requirement
- "Platform model" — Sir John's CBDC design philosophy
- "General purpose [settlement asset / platform]" — Sir John's CBDC framing
- "Convenience yield" — economic concept applied to stablecoins
- "Information insensitive" — Holmstrom reference by Sharon Ross: stablecoins aim to be like this but aren't
- "Maturity transformation" / "liquidity transformation" — distinguishing bank business models from stablecoin payment business models
- "Winner take all" — describing stablecoin market structure
- "Tokenization" — Sir John: "means many different things to many different people... a very slippery word"
- "The elephant" / "one leg of the elephant" — Greenberg's meta-metaphor
- "Parting shot" — self-reference by Sir John
- "Road map" — G20 cross-border payments roadmap
- "ISO 2022" (ISO 20022) — messaging standard
- "Hash time lock" — technical feature referenced in Project Rosalind
- "Small frictions → big behavioral shifts" — Sir John's theory of payment change

**Metaphors and analogies:**
- Stablecoins ≈ money market funds (the central metaphor of Paper 1)
- Stablecoins ≈ exchange rate pegs (Greenberg's alternative)
- Crypto ecosystem ≈ small open economy subject to terms-of-trade shocks (Greenberg)
- Terra's algorithmic mechanism ≈ throwing away empty coffee cups (Alandoni)
- Libra ≈ Black Ships of Commodore Perry arriving in Tokyo Harbor 1853
- CBDC decision ≈ "Henry Ford / faster horses"
- Digital pound as public anchor ≈ ensuring app stores don't monopolize payment rails
- London Underground contactless → illustrated the "small friction, big shift" principle

---

## 8. COMPANIES/PROTOCOLS MENTIONED

**Stablecoins:**
- **Tether (USDT)** — offshore, largest ($84B), opaque reserve, not audited by recognized firm, self-reports ~50% Treasuries; formerly third-largest US commercial paper holder
- **USD Coin (USDC)** — US-based, Deloitte-audited, $25B AUM; suffered from SVB exposure (largest SVB account); seen as "safe" US-based stablecoin
- **DAI** — crypto-collateralized (Ethereum), over-collateralized (1.7 ETH per $1 DAI), complex smart contract system
- **Terra / TerraUSD (UST) / Luna** — algorithmic stablecoin, collapsed 2022 from $19B to near zero; the central stress episode
- **PayPal Stablecoin (PYUSD)** — mentioned as new entrant (with Paxos); potential "killer app" to bring stablecoins outside crypto

**Crypto networks:**
- **Ethereum** — largest stablecoin blockchain
- **Tron** — second major blockchain for stablecoins
- **Binance Smart Chain** — third major blockchain referenced
- **Bitcoin** — used as aggregate crypto sentiment measure (Bitcoin price drops = stress instrument in Paper 1)

**Institutions/Organizations:**
- **Federal Reserve Bank of Boston, New York, Federal Reserve Board** — paper authors' affiliations and conference host
- **IMF** — Federico Greenberg's affiliation
- **West Virginia University** — Scott Shu's affiliation
- **Bank of England** — Sir John's institution; issued digital pound consultation, passed stablecoin legislation
- **BIS (Bank for International Settlements)** — CPMI housed here; Innovation Hub ran Project Rosalind
- **FSB (Financial Stability Board)** — co-led G20 roadmap, issued stablecoin recommendations 2023
- **CPMI (Committee on Payments and Market Infrastructures)** — Sir John's chair role at BIS
- **G20** — adopted 2027 cross-border payment targets; adopted roadmap 2020
- **G7** — issued first statement that Libra/global stablecoins can't operate until regulatory issues addressed
- **Facebook / Meta** — announced Libra June 2019; the "Black Ships moment"
- **FTX** — referenced via MLB/FTX umpire patch IV strategy (Paper 2); collapsed November 5, 2022
- **Major League Baseball (MLB)** — instrumental variable source (FTX umpire patches)
- **California Teachers Pension Fund** — Scott Shu's analogy to repo market opacity (pre-stablecoins)
- **Bank of New York Mellon** — same analogy
- **European Central Bank / ECB** — referenced in context of future CBDC interoperability concerns
- **Central Bank of Brazil** — developing CBDC despite having PIX instant payments
- **Reserve Bank of India** — also developing CBDC

**Projects:**
- **Libra (Facebook)** — the galvanizing event; later renamed Diem; fell by the wayside ~2022
- **Project Rosalind** — BIS Innovation Hub + Bank of England digital pound experiment; demonstrated programmable payment use cases (train ticket + automatic refund example)
- **G20 Cross-Border Payments Roadmap** — 19 building blocks, adopted 2020, targets for 2027

**Academic references:**
- Goldstein and Pauzner — bank run model used by Sharon Ross
- Gromov and Vayanos / Bruno, Merber, Petrov — leveraged collateralized trading model
- Holmstrom — "information insensitive" concept (no-questions-asked money)
- S. Kim — paper showing stablecoin issuance leads to increase in commercial paper issuance next day
- Jillian Tett (Financial Times) — provided the "Black Ships" analogy for Libra

---

## 9. USE CASES HIGHLIGHTED

- **Stablecoins as settlement asset for crypto trading** — primary use case (Greenberg, Ross)
- **Stablecoins as collateral for leveraged crypto positions** — the peg-sustaining mechanism (Paper 2)
- **Stablecoins in cross-border payments** — Greenberg mentions USDT used for this more than others
- **Stable coins as potential payment system money** — the question the entire conference is probing
- **Digital pound use cases (Project Rosalind):** Train ticket + automatic refund if train doesn't depart on time; illustrated concept of payment integrated seamlessly into larger commercial processes
- **Programmable payments** — general use case enabled by tokenization/CBDC platform: automation of payment conditional on events
- **Cross-border retail payments improvement** — G20 roadmap target; interlinked faster payment systems in Asia cited as positive example
- **Tokenized bank deposits (JPMorgan JPMD concept)** — mentioned briefly in context of future bank stablecoin regulatory classification

---

## 10. TONE & STYLE

**Paper presentations (Alandoni, Ross):** Formal academic conference style. Data-led, hypothesis-testing, regression-reporting. Self-deprecating disclaimers ("this does not represent the views of the Federal Reserve…"). No hype; cautious hedging throughout. Quantitative claims are precisely stated.

**Discussants (Greenberg, Shu):** More discursive. Greenberg: analytical and constructive, adds meta-framing. Shu: deliberately self-deprecating, macro-skeptical, uses baseball and consumer payment analogies to ground abstract crypto concepts. Both raise "big picture" questions that papers don't answer.

**Keynote (Sir John Cunliffe):** Authoritative but candid — explicitly frames as "parting shots" after 10 years. Witty (pumpkin/Halloween, Deuteronomy, Arsenal question). Historical in sweep (1853 Black Ships, history of cash decline). Policy-minded rather than academic. Uses "I think" frequently. More willing to express opinion than typical central bank speech. Avoids making predictions about outcomes.

**Overall register:** The most academic/policy of all video scripts in this collection. Zero consumer marketing. Zero hype. The emotional register is sober, occasionally witty, always restrained.

---

# FILE 2: State of Fintech Video Script

## 1. OVERVIEW

**Format:** Podcast/video interview — "State of Fintech 2026" episode. Two hosts in conversation.
**Length:** ~1 hour 13 minutes of content; 1444 lines of transcript.
**Hosts:**
- **Simon Taylor** — author of the 110-page "State of Fintech 2026" deck; described as working at tempo.xyz; newsletter fintechbrainfood.com; self-described as "head of crypto R&D at a bank 11 years ago"
- **Rex** (unnamed in transcript beyond first name reference) — US-based investor, hosts the show

**Style:** Conversational, energetic, forward-looking. Pundit/analyst style — data-driven but accessible. Clear structure following slide deck chapters. Predictions-focused at end. Much more consumer-facing than File 1.
**Audience:** Fintech practitioners, investors, startup founders, financial services professionals interested in trends. General intelligent business audience, not academic.

---

## 2. SPEAKERS & SEGMENTS

### Simon Taylor — Fintech analyst, tempo.xyz / Fintech Brainfood
**Role:** Primary expert guest; author of State of Fintech 2026 deck (110 pages)
**Background:** Former head of crypto R&D at a bank (11 years ago); deep fintech knowledge
**Key segments and arguments:**
- Fintech hyperscalers are getting bigger and competing with banks at global scale
- AI has driven 1-in-6 Black Friday purchases; half of consumers use AI to research purchases
- Stablecoin growth has "completely decoupled from crypto prices" — the signal of durable product-market fit
- Stablecoin growth is in B2B payments, corporate treasury, payroll/payouts — NOT peer-to-peer
- Prediction markets are being bootstrapped by sports (analogous to memecoins bootstrapping crypto)
- Open finance: bank fee-charging for API access creates strange clarity
- Bank charters are coming back after a decade of near-zero approvals
- Agentic commerce is the next internet shift — protocol wars are at "early internet" stage
- His most important prediction: DTCC stock tokenization will be switched on in 2026
- His most concerning prediction: consumer delinquencies at 2008 levels; consumer distress incoming

### Rex (host)
**Role:** Interviewer; US-based early stage investor
**Contributions:** Adds US market perspective, shares his own AI shopping experience (bought a TV using ChatGPT), investor framing on each trend

---

## 3. ALL KEY STATS & DATA

### Fintech Hyperscalers
- **Klarna:** 85 million customers last year → **114 million** now
- **Nubank:** 110 million → **127 million** now
- **Revolut:** 50 million → **64 million** (in European markets — "not a place known for its dynamism")
- **Robinhood:** Almost doubled assets under custody (AUC)
- **Stripe:** Added **40%** of total processing volume in a 12-month period

### Public Markets
- Public fintech incumbents (Fiserv, FIS, legacy payment companies): underperformed major market indices
- Robinhood, Nubank, Shopify: strong performers
- "Bifurcation of the market"

### Robinhood Specifics
- **13 million+** monthly active users
- Gold subscription: grew from ~1 million → **~4 million**
- JP Morgan: **70 million** consumer households (benchmark)
- Robinhood launched **11 new businesses** generating more than **$100 million** in combined annualized revenue
- Aims for **50% of revenue from international** in 10 years

### AI / Agentic Commerce
- **1 in 6** Black Friday purchases was AI-assisted (Salesforce data; corroborated by Write Sonic, Atest)
- **Half of all consumers** use AI tools to research purchases
- AI adoption: reaching **20–25% of western population** using generative AI weekly
- Enterprise AI usage: **79%** of companies use generative AI in at least one function
- ChatGPT: **800 million users** but "still not touching most of the planet"
- AI conversion vs traditional search: some sources suggest **2–6x higher conversion** from ChatGPT clicks (Simon is less confident in this figure)
- AI has grown faster than the cell phone

### Stablecoins
- Total stablecoin supply: passing **$350 billion**
- Visa earnings call: **$3.5 billion annualized total processing volume** in stablecoin-linked cards
- Visa's total 2024 TPV: **$15.7 trillion** (stablecoin cards = tiny fraction)
- Estimate: stablecoin card TPV has **3x'd in a quarter**
- "If it 3xes for a few more quarters, you're going to be really in sort of the 50, 70, 100 billion TPV in the not too distant future"
- "Could become the fastest growing segment of Visa, faster than Visa Direct"
- **99%** of stablecoins are USD-denominated
- Fastest growing stablecoin: euro-denominated
- Also emerging: Brazilian real, Mexican peso, Singapore dollar, Hong Kong dollar stablecoins
- Coinbase: facilitated **more than $1 billion** in borrowing through the Morpho protocol in 2026
- Morpho vault yields: **6–12%** for investors

### Open Finance
- 1033 rules "walked back" under new administration
- JP Morgan and others now charging for API access to customer permissioned data
- FICO partnered with Plaid for new cash flow-based scoring
- Plaid is now a Consumer Reporting Agency (CRA)

### Bank Charters
- Historical norm: **~132 new bank charters** per year (mid-1980s to ~2010)
- Since 2010: **average 6 per year** ("unreasonably hard")
- Charter types now being applied for:
  - Full FDIC-insured charter: Nubank, Arbor, Mercury
  - National Trust Bank: Circle, Ripple, Paxos, BitGo, Bridge
  - MALP (Georgia Charter): Stripe, Checkout.com (direct Visa/Mastercard principal member access)
- Mercury applied just before the holidays

### Prediction Markets
- Previous November peak: US election
- Football season drove "massive amount of volume"
- Polymarket raise: **~$2 billion** from New York Stock Exchange parent ICE
- Kalshi: raised **$1 billion** at **$11 billion valuation**; Citadel invested
- Kalshi: **79% of volume** from sports (October timeframe)
- Accuracy: **95.6%** accuracy from 30 days out on future events
- Kalshi: crossed **$100 billion in annualized volume** (latest data point)

### Neobanks
- Affirm card: **2.8 million users**
- Klarna card (globally): **3.2 million users**
- Cash App: **$22 billion in originations** (lending scale)
- Stablecoin neo-banks emerging: Cast, Altitude, Fuse

### Consumer Stress (Predictions section)
- Mortgage delinquencies: currently at **2008 levels**
- Consumer confidence: low

### DTCC (Prediction)
- DTCC holds all US stock certificates
- **$500 trillion gross notional value** (includes derivatives)
- Securities portion: **~$37 trillion** (S&P 500 etc.)
- Prediction: DTCC switches on stock tokenization in 2026

### Agentic Payments Take Rates
- Card payment: **~2.5%**
- BNPL: variable, cash flow risk
- Google (top of funnel traffic): **~15%** median take rate
- BNPL-style high-converting: could be **~5%** with 20% tax
- ChatGPT starting take rate estimate: **~2%**, then gradually increasing (Netflix model)

---

## 4. CORE NARRATIVE ARCS

### Arc 1: The Fintech Hyperscalers Are Taking Over
The first and most sustained narrative: the largest fintechs keep getting larger. This isn't just growth — it's category-defining scale. Nubank at 127 million customers, Klarna at 114 million, Revolut doubling in markets where banks didn't think they could. The arc: "it used to be you couldn't even see these companies on the y-axis compared to incumbents. Now you can."

### Arc 2: AI Is Eating Commerce
1-in-6 Black Friday purchases AI-assisted. Half of consumers research purchases with AI. The arc moves from consumer AI research → agentic shopping execution → protocol wars for who controls the checkout layer. The question is who captures the value: OpenAI? Card networks? Stripe? The "early internet / no clear standard yet" framing.

### Arc 3: Stablecoins Have Found Product-Market Fit — But Not Where You Think
The decoupling from crypto prices is the thesis-level data point. Then the reveal: it's not peer-to-peer. The actual growth is in B2B payments, corporate treasury, payroll in emerging markets, remittances. The arc ends with the prediction: "the letter after the coin will start to fade away" — stablecoins becoming invisible infrastructure.

### Arc 4: Everything Goes Onchain
Runs through multiple sections: stablecoins → tokenized deposits → DTCC stock tokenization prediction → DeFi lending in consumer apps (Coinbase/Morpho) → bank charters for crypto-native companies. The arc: "I was head of crypto R&D at a bank 11 years ago. It was always inevitable. The question was when. Now I think we're over a tipping point."

### Arc 5: Banks Are Fine — But The Clock Is Ticking
Counter-intuitive beat: banks are actually doing great. Rates high, consumer resilient, IPOs back, Wells Fargo and Citi out of regulatory purgatory. But Simon's warning: the hyperscalers are coming, and banks are celebrating while they should be investing. JP Morgan is the positive exception.

### Arc 6: Consumer Distress Beneath the Surface
The dark prediction thread: delinquencies at 2008 levels, consumer confidence low, cost-of-living crisis driving anti-AI and anti-tech sentiment. Every incumbent in the West is getting unelected. The tech/finance class is "cinking the champagne" while consumers hurt.

### Arc 7: The DTCC Tokenization Prediction
The most important long-term prediction: every US stock becomes a token. This eliminates collateral problems (Robin Hood/GameStop controversy explained as a DTCC collateral call), enables real-time clearing, and creates "compounding effects" of composable financial infrastructure. "We'll look back on it as the computerization era or mobile era."

---

## 5. POSITIONING PILLARS

- **"Fintech hyperscalers"** — the framing for category leaders (Nubank, Revolut, Klarna, Robin Hood, Stripe)
- **"Decoupled from crypto prices"** — the key signal that stablecoins have genuine product-market fit
- **"The letter after the coin will fade away"** — stablecoins becoming invisible infrastructure
- **"Early internet moment"** — framing for agentic payments protocol wars (no HTTP yet)
- **"Everything goes onchain"** — the meta-trend connecting stablecoins, tokenized deposits, DTCC
- **"Liquidity trapped"** — what stablecoins solve for businesses in markets where JP Morgan doesn't operate or doesn't serve
- **"Product market fit for payments / for onchain markets"** — applied to stablecoins
- **"Private credit for the mass market"** — framing for Morpho/DeFi lending yields (6–12%)
- **"Coming of age moment"** — bank charters for fintech
- **"Bifurcation of the market"** — legacy payment incumbents underperforming vs. new winners

---

## 6. HOOKS & OPENINGS

- Episode title: **"State of Fintech 2026: What Matters Now"**
- Opening tease: "the growth in that stable coin volume has completely decoupled from crypto prices. And we even cover the rise of prediction markets... But the most important thing was..."
- **"What did Klarna have — 85 million customers when we did this report last year. Now they've reported 114 million."** — the hyperscalers slide hook
- **"One in six Black Friday purchases was AI assisted. What does that mean?"**
- **"The stable coin volume has completely decoupled from crypto prices. That is the beginning of a durable trend."**
- **"I was head of crypto R&D at a bank 11 years ago. It was always inevitable. The question was when."**
- **"Stocks become the next stablecoin."** — prediction hook
- **"In the next 12 months you will see DeFi lending and stable coins in just about every NEO bank."**
- **"From 2010 we've averaged six per year [bank charters]. So it became unreasonably hard to get a charter."**
- **"79% of Kalshi's volume in October was from sports."** — prediction markets hook
- **"Mortgage delinquencies are currently where they were in 2008."** — the dark turn hook

---

## 7. RECURRING PHRASES & LANGUAGE

**Exact phrases:**
- "Fintech hyperscalers" — used repeatedly as the core category term
- "Completely decoupled from crypto prices" — the stablecoin PMF signal phrase
- "Product market fit" — applied to stablecoins for payments and onchain markets
- "Going onchain" / "brings things onchain" — recurring
- "The letter after the coin will start to fade away" — key prediction phrase
- "Early internet" / "early internet moment" — applied to agentic payment protocols
- "Winner is going to... / who wins this?" — recurring investor framing
- "Invisible" — applied to stablecoins becoming infrastructure
- "Bifurcation" — public market split between old and new fintech
- "Bootstrapping" — sports bootstrapping prediction markets, just as memecoins bootstrapped crypto
- "Liquidity gets trapped" — where stablecoins win (markets JP Morgan doesn't serve)
- "24/7" — modifier applied to stablecoins, onchain settlement
- "Composable" / "remixable" — applied to onchain financial features
- "Everything app" — Coinbase's stated strategy
- "Compounding effect" — onchain composability's long-run impact
- "Private credit for the mass market" — framing DeFi lending yields
- "Black swan" / "whipsaw" — macroeconomic risk language
- "Correspondent banking system" — what stablecoins route around
- "Coming of age moment" — bank charters for fintech
- "Clunky" — honest assessment of Coinbase app UX
- "I don't think we will [get ahead of consumer distress]. But I think that's going to really show next year."

**Metaphors and analogies:**
- Prediction markets ≈ crypto's memecoin phase (ugly bootstrap but leads somewhere real)
- AI adoption speed > cell phone adoption speed
- CBDC/stablecoin trust ≈ app store dynamics (platform lock-in risk)
- DeFi lending ≈ "private credit but for the mass market"
- DTCC tokenization ≈ computerization era / mobile era (defining turning point in hindsight)
- Self-driving car safety ≈ tokenized stocks becoming the "safer, smarter choice"
- Token as next stablecoin: "Stocks become the next stablecoin"
- Netflix pricing model ≈ how ChatGPT will gradually increase take rates
- Robin Hood/GameStop = DTCC collateral call, not villainy (myth-busting)

---

## 8. COMPANIES/PROTOCOLS MENTIONED

**Fintech Hyperscalers:**
- **Klarna** — 114 million customers; card (3.2M globally); becoming neobank-like; BNPL-to-neobank evolution
- **Nubank** — 127 million customers; applying for full bank charter; doing stablecoins; "dominant" in Brazil
- **Revolut** — 64 million customers; European; described as "masterclass in product velocity"; doing stablecoins
- **Robinhood** — ~13M MAUs; 4M Gold subscribers; assets under custody nearly doubled; private banking launch; 11 new businesses generating $100M+ annualized revenue; aims for 50% international revenue in 10 years; "quietly crushing it in the UK"
- **Stripe** — 40% TPV growth in 12 months; applying for MALP/Georgia Charter; built agentic checkout protocol (works even for non-Stripe merchants like Etsy); partnered with OpenAI

**Payment Networks & Infrastructure:**
- **Visa** — $3.5B annualized stablecoin-linked card TPV; $15.7T total 2024 TPV; Visa Direct reference
- **Mastercard** — referenced in Georgia Charter (principal membership)
- **Cloudflare** — sees 20% of internet traffic; partnered with Coinbase on X402/H402
- **Coinbase** — "everything app" strategy; launched prediction markets, tokenized stock trading, Base wallet, stablecoin card (4% cash back), regular equities; facilitated $1B+ through Morpho
- **Morpho protocol** — DeFi lending platform; Coinbase integration; 6–12% yields; collateralized Bitcoin lending
- **DTCC** — holds all US stock certificates; $500T gross notional; $37T securities; actively discussing tokenization
- **Plaid** — now a CRA (Consumer Reporting Agency); selling signals/insights; FICO partnership; paying JP Morgan API fees

**Neobanks:**
- **Cash App (Block)** — $22B lending originations; launched Cash App Scroll (credit scoring); lending; investing; crypto; AI assistance; "knows what it wants to be"
- **Chime** — similar positioning to Cash App; lending at scale
- **Affirm** — 2.8M card users; credit card + debit hybrid; still figuring out the bundle
- **Mercury** — applied for full bank charter just before holidays
- **Arbor** — applying for full bank charter

**Crypto/DeFi:**
- **Circle** — applying for National Trust Bank charter
- **Ripple** — applying for National Trust Bank charter
- **Paxos** — applying for National Trust Bank charter (also mentioned as PayPal PYUSD partner)
- **BitGo** — applying for National Trust Bank charter
- **Bridge** — applying for National Trust Bank charter
- **Solana** — referenced as example of composable blockchain features
- **USDC / USDT** — mentioned (the letter "fading away" prediction)

**Stablecoin/Remittance:**
- **Western Union** — announced own stablecoin
- **MoneyGram** — stablecoin wallets; enduser wallet enabling yield, loans, broader product expansion
- **DLO, Nuvei, Flywheel (Flywire)** — moving dollars for treasury management into hard-to-reach markets
- **Felix Pago** — referenced as example of stablecoin becoming invisible in transfers
- **Sling Money** — cited as example of stablecoins becoming seamless

**AI / Commerce:**
- **OpenAI / ChatGPT** — 800M users; AI shopping; rumors of ads + transaction fees; partnered with Stripe, Shopify, Etsy
- **Salesforce** — source of 1-in-6 Black Friday AI purchase data
- **Write Sonic / Atest** — corroborating AI shopping data sources
- **Shopify** — partnered with OpenAI for agentic checkout; strong public market performance
- **Etsy** — example merchant in Stripe/OpenAI agentic checkout demo (Etsy is NOT a Stripe merchant — the protocol worked anyway); also: Simon's Sonic the Hedgehog purchase example
- **Google** — ATP protocol for agent mandates; location data API example; advertising revenue from foundation models
- **PayPal** — working on ATP; Venmo; still "finding their way"
- **Amazon** — referenced as discovery/commerce platform
- **Meta** — advertising revenue growing from foundation model use

**Prediction Markets:**
- **Polymarket** — raised ~$2B from ICE (NYSE parent); Citadel invested
- **Kalshi** — raised $1B at $11B valuation; 79% sports volume; 100B annualized volume; Citadel invested; sued CFTC over election contracts
- **FanDuel / DraftKings** — seeing Kalshi/Polymarket as competitors
- **CNN** — starting to feature prediction market data for news/politics/culture/economics

**Banks & Traditional Finance:**
- **JP Morgan** — 70M consumer households; JPMD (tokenized deposit); "does surprising things" like AI proxy voting tool; "outperformed every other banking stock"; only serves select customers
- **Wells Fargo, Citi** — out of "regulatory purgatory"; "ending their transformation; can grow again"
- **FICO / Experian** — seeing cash flow data as key to growth
- **Checkout.com** — applying for Georgia Charter

**Regulatory:**
- **CFTC** — tried to ban sports prediction markets; lost in court (Kalshi vs. CFTC); new administration more accommodative

---

## 9. USE CASES HIGHLIGHTED

**Stablecoins:**
- **B2B payments** — paying suppliers in hard-to-reach markets; no correspondent banking relationship needed
- **Corporate treasury management** — moving dollars 24/7 at low cost
- **Payroll in far-flung markets** — getting paid in stable currency in emerging markets
- **Remittances** — MoneyGram/Western Union stablecoin wallets; recipient gets stablecoin instantly via mobile app; issuer can then cross-sell yield, loans
- **Stablecoin-backed cards** — Visa stablecoin-linked card TPV growing; user holds stablecoin, card converts at point of sale
- **Yield products** — tokenized T-bills as savings account; stablecoin as cash account; instant switching
- **Collateralized DeFi lending** — Coinbase/Morpho: Bitcoin as collateral → borrow against → 6-12% yield for vault investors
- **Invisible infrastructure** — "the letter after the coin fades away"

**Agentic Commerce:**
- Automated purchasing agent with budget mandate and merchant permission validation via card networks
- Access to Wall Street Journal / API keys / digital goods without credit card (Cloudflare/Coinbase X402/H402)
- Stripe/OpenAI: checkout appearing inside LLM with full merchant fraud data preserved
- "I want to buy that thing below $100" — Google ATP mandate for future conditional purchase

**Open Finance:**
- Cash flow data for lending underwriting (better predictor than credit history)
- Bank-fintech data sharing for fraud and credit
- Plaid as CRA: selling insights beyond plumbing

**Prediction Markets:**
- Sports betting (dominant current use)
- Elections/politics
- Economic data, weather hedging, insurance-like products
- Potential: stadium owner hedging against losses if home team loses

**Bank Charters:**
- Full charter: FDIC insurance, Fed discount window access, traditional banking
- National Trust Bank: Fed Wire access for payment businesses (no yield, no FDIC)
- MALP/Georgia Charter: direct Visa/Mastercard principal membership without sponsor bank

---

## 10. TONE & STYLE

**Format:** Conversational podcast. Informal, energetic, forward-looking. Heavy use of "yeah," "I think," "absolutely," "right," hedging language. Occasional laughter and banter.
**Balance:** Data-driven (Simon presents actual figures from his 110-page deck) but interpreted conversationally and with investor framing (Rex).
**Honesty:** Simon is willing to express uncertainty ("I'm less confident on that one"), admit he doesn't know ("I have a harder time understanding what PayPal is doing with Venmo. No. [laughter]"), and flag risks (consumer delinquencies, anti-AI sentiment).
**Optimism bias:** Broadly optimistic about fintech, onchain, AI — but balanced by genuine concern about consumer distress.
**UK vs. US lens:** Simon is UK-based; Rex is US-based. This creates useful comparative perspective, especially on Revolut's UK success and US companies' failure to understand European markets.
**Register:** Accessible expert — assumes knowledge of industry terms but explains them conversationally. Far more consumer/market-facing than File 1.

---

# CROSS-CUTTING THEMES BETWEEN THE TWO FILES

## Theme 1: The Stablecoin Product-Market Fit Question
**File 1** (academic): Stablecoins have PMF as settlement assets for crypto speculation and leverage. They are NOT useful as money (negative convenience yield; run risk not compensated). The question of payments use is an appendix discussion.
**File 2** (practitioner): Stablecoins have PMF for B2B payments, corporate treasury, remittances. The decoupling from crypto prices IS the proof. Volume in stablecoin-linked Visa cards is growing 3x per quarter.
**Synthesis:** The academic and practitioner communities are looking at different use cases and drawing opposite conclusions. File 1 is studying the crypto speculation use case (2021–2023 data). File 2 is tracking the payments use case (2025–2026 growth). Both are right about their observed domain. The key question — have stablecoins crossed over from crypto speculation to real economy payments — is the central unresolved tension.

## Theme 2: Stablecoins as MMFs / Tokenized Deposits / New Money Forms
**File 1**: Deep academic analysis of how stablecoins resemble unregulated MMFs. Sir John's keynote draws clear regulatory boundary: stablecoin payment system regime ≠ banking regime ≠ investment regime.
**File 2**: Simon on the JP Morgan tokenized deposit (JPMD) vs. stablecoins: tokenized deposits can't be sent to non-JP Morgan customers; stablecoins can — "it's a bit like cash." "Tokenized deposits will be very different in how they impact who can use what deposits for what loans."
**Synthesis:** Both files circle the same conceptual territory — what is the difference between stablecoins, tokenized deposits, MMFs, and CBDC as forms of digital money? File 1 provides the academic/regulatory framing. File 2 provides the practitioner business-model framing.

## Theme 3: The Run Risk Problem
**File 1**: Papers 1 and 2 both quantify stablecoin run risk in detail. The 0.99 threshold, flights to safety, the role of speculative demand in sustaining pegs.
**File 2**: Simon notes Circle and Tether are on path to National Trust Bank charters — which would mean they "can clear like dollars" and the USDC→fiat swap becomes seamless. He's describing the regulatory solution to the run risk problem.
**Synthesis:** File 1 documents the problem; File 2 describes the emerging regulatory/business solution.

## Theme 4: The Regulatory Shift
**File 1**: Sir John's keynote describes the post-Libra regulatory framework from the central bank perspective. "Same risk, same regulation." UK Parliament passed stablecoin legislation. CPMI/FSB standards issued.
**File 2**: Simon describes the US regulatory shift as enabling bank charters for crypto-native companies, CFTC becoming more accommodative, GENIUS Act (mentioned in the master synthesis context), stablecoin legislation coming. "We're over a tipping point."
**Synthesis:** Both files see a regulatory inflection point in 2023–2026. The difference is geographic and institutional: File 1 is UK/BIS-centered and cautious; File 2 is US-market-focused and optimistic about the new environment.

## Theme 5: The Transmission Belt Between TradFi and Crypto
**File 1**: Sharon Ross's core finding — stablecoins are the link between traditional financial markets and crypto markets in BOTH directions. Tether as third-largest US commercial paper holder.
**File 2**: Simon: "If you can have a stable coin that's in local fiat and a stable coin that's in US dollars, you can swap in and out of those as fast as 24/7 and at low cost." JP Morgan tokenized deposit + stablecoin allowing on/off-ramp elegantly. Coinbase/Morpho as DeFi lending through a consumer app.
**Synthesis:** Both files see stablecoins as the bridge layer. File 1 worries about financial stability implications of this bridge. File 2 sees it as the feature — the business opportunity.

## Theme 6: Tokenization as the Meta-Trend
**File 1**: Sir John uses "tokenization" as umbrella term (cryptography, DLT, atomic settlement, blockchain, fractionalization, programmability). His caution: "means many different things to many different people — a very slippery word." He sees potential in programmable payments (Project Rosalind train ticket example) but is careful not to predict outcomes.
**File 2**: Simon makes it concrete: DTCC stock tokenization is his #1 most important prediction. "Stocks become the next stablecoin." Every stock available in every software wallet. DeFi lending in every neobank within 12 months. "I was head of crypto R&D at a bank 11 years ago. It was always inevitable."
**Synthesis:** Sir John is the cautious central bank voice ("one cannot say with certainty"); Simon is the bullish practitioner voice with a specific timeline. Both see tokenization as the defining technological shift. The gap is in certainty and urgency.

## Theme 7: The Dollar Dominance Question
**File 1**: Not explicitly addressed in the academic papers, though offshore vs. US-based stablecoin distinction runs throughout. Sir John references the G20 cross-border payments goal and the risk of new rails bypassing existing system.
**File 2**: "99% of stablecoins are USD-denominated. But the fastest growing stablecoin is a euro stablecoin." Brazilian real, Mexican peso, Singapore dollar stablecoins emerging. "Don't expect the US dollar to disappear anytime soon. It goes from 99% to maybe 90%."
**Synthesis:** File 2 explicitly addresses what File 1 leaves implicit: US dollar dominance in the stablecoin world is an extension of US financial dominance, and it's beginning — slowly — to pluralize.

## Theme 8: Competition, Innovation, and the Platform Risk
**File 1**: Sir John's second CBDC motivation: "digital marketplaces have a tendency to concentration" — the risk that big tech entering money/payments creates app-store-style lock-in. CBDC as public alternative to anchor competition. "If you provide that public sector alternative, it may not be used very much, but actually you anchor the whole system and you anchor competition."
**File 2**: Simon: protocol wars for agentic payments — card networks, Stripe, OpenAI, Cloudflare/Coinbase X402, Google ATP. "There are more standards than there are transactions at the moment." The "early internet" framing: will there be a graphical browser moment?
**Synthesis:** Both identify the same competition risk (lock-in by dominant platform). File 1's solution is CBDC as public alternative. File 2 sees the market resolving it via competing protocols coalescing over time, "just like HTTP and CSS and Java."

## Theme 9: Instant, 24/7, Programmable Money as the End State
Both files converge on this vision, from opposite directions:
- Sir John (File 1): "The payment becomes invisible and integrated into a much broader operation" — his description of what tokenization/programmability offers.
- Simon (File 2): "The letter after the coin will start to fade away" — stablecoins becoming invisible infrastructure. Instant 24/7 payments as the product.
- The G20 2027 targets (File 1) and the Visa stablecoin card TPV growth (File 2) are both pointing at the same destination: money that moves instantly, across borders, 24/7, with programmable logic.

## Theme 10: Are Stablecoins Money? (The Persistent Unanswered Question)
- **File 1 academic answer:** Largely no. Negative convenience yield. Not information-insensitive. Not a true store of value. "Bad money." Run risk not compensated on primary market.
- **File 1 policy answer (Sir John):** Doesn't matter what we call them — what matters is whether risks are managed equivalent to what we expect of Commercial Bank money.
- **File 2 practitioner answer:** Increasingly yes, for specific use cases. And the distinction will blur as the "letter fades away."
- The question itself — what is money? — runs through both files as the deep unresolved substrate beneath all the data and all the policy debates.

---

*Synthesis complete. Both files fully read.*

---
## BATCH 4
---
# Video Script Synthesis — _VS_PARTIAL_4
## Files Covered
1. `2026 Prediction Video Script.txt` — "Tokenized" Podcast 2026 Predictions Special (~79KB, ~64 min)
2. `CAC26 Video Script.txt` — Crypto Asset Conference 2026 (CAC26) Panel: "Next Phase of Capital Markets with Crypto" (~43KB, ~43 min)
3. `2026 ITP Payments Video Script.txt` — ITP Payments Conference Panel: Genius Act / Stable Coins / Tokenized Deposits (~44KB, ~41 min)

---

# FILE 1: 2026 Prediction Video Script
**("Tokenized" Podcast — 2026 Predictions Special)**

## 1. OVERVIEW
- **Format:** Long-form conversational podcast, video-enabled, timestamped transcript
- **Length:** ~64 minutes (1:03:57); organized into 10 named chapters
- **Style:** Casual co-host banter + structured guest predictions with grading of prior-year predictions, debate, cross-talk, and "over/under" betting on each prediction
- **Audience:** Crypto-native and institutional stablecoin/RWA audience; "payments nerds," fintech professionals, investors, founders in the stablecoin-tokenization space
- **Sponsors:** Centrifuge, Visa, Stripe

---

## 2. SPEAKERS & SEGMENTS

### Simon Taylor — Host
- Author of "Fintech Brain Food"; Head of Market Development at Tempo; based in UK
- Moderates, grades prior predictions, offers his own predictions, provides critical commentary
- Key positions: Bullish on stablecoin-linked cards; skeptical of AI/crypto crossover hype; interested in tokenized loyalty; believes JP Morgan's "JPMM" will overtake Bidd in tokenized money market fund space
- Find at: fintechbrainfood.com / @sytail

### Kai Sheffield — Co-Host / Visa
- Works at Visa (specifically in crypto/stablecoin settlement); runs Kai Sheffield on LinkedIn and visa.com/crypto
- "The man in the hour, the man with the power"
- Key positions: Introduced stablecoin-linked card prediction in prior year (A+ grade); deep insider view of Visa's stablecoin settlement program; bullish on on-chain lending growth; curious/cautious on X42 agentic payments
- Personal style: Hard grader on vague predictions — "I'm going to be a hard grader. I'm going to give us a C because none of these were really quantifiable."

### Rob Haddock — Guest; GP at Dragonfly Capital
- "Making his third appearance" on the show
- Investor in Rain (stablecoin-linked card issuer processor, direct Visa member)
- Key positions: Boldly predicts Visa stablecoin settlement hits $100B+ annualized by end of 2026; predicts major corporate collapses loyalty program into stablecoin-powered cashback; predicts DTCC goes live with all US stock entitlements on-chain; predicts Robinhood goes "token native"; skeptical of AI/crypto timeline; skeptical that JPMM overtakes Bidd
- Style: Confident, VC-bull, loves a "bonus prediction," "the train has left the station"
- Find at: @hadock_mal on Twitter/LinkedIn

### Tyler Mayius — Guest; CEO & Co-founder, Smart Media Technologies
- "Debutant" — first appearance on the show
- Company works on tokenized loyalty / stablecoin-linked merchant programs
- Key positions: Defends and expands loyalty tokenization thesis; ~$300B worth of point liability issued annually; $1T unused point liability on corporate balance sheets; predicts $1B in tokenized collateral pegged to loyalty points by end of 2026 (5–10% of all tokenized RWAs); supports cashback/yield-via-reserve thesis
- Find at: LinkedIn

### Chapter Structure:
1. Introduction / sponsor reads (Centrifuge, Visa VTAP, Stripe)
2. Grading prior-year predictions (Yuval Rooz/Digital Asset, Simon, Kai)
3. Debate: AI/crypto crossover skepticism (Rob's skepticism)
4. Prediction 1 (Rob): Visa stablecoin settlement exceeds $100B annualized
5. Prediction 2 (Simon): Tier-2 bank closed-loop stablecoin settlement rails >$100B
6. Prediction 3 (Rob/Kai/Tyler): Loyalty program tokenization; cashback vs. loyalty debate
7. Prediction 4 (Simon): Clarity Act passes; JPMM tokenized money market fund surpasses Bidd
8. Prediction 5 (Rob): "Pay with stablecoin" widget on major e-commerce sites; $2B annualized merchant stablecoin payments
9. Prediction 6 (Kai): On-chain lending using tokenized RWAs as collateral grows 5x
10. Bonus predictions + X42 agentic payments; outro

---

## 3. ALL KEY STATS & DATA

### Visa Stablecoin Settlement
- Current: **$3.5 billion annualized** volume in stablecoin card settlement
- Prior baseline (May): **$250 million** annualized — used to show trajectory
- Rob's prediction: **>$100 billion annualized** by end of 2026
- Simon's "under": 10x from current = **$30–50B** is more likely
- "Will be the fastest growing part of Visa's business"

### Prior-Year Prediction Grades
- Yuval Rooz (Digital Asset): RWAs reach 25% of stablecoin market cap → Grade: **C+** (doubled from 3.5% to 7%, not 25%); US regulatory clarity → **A**; Crypto derivatives volumes double → **A+**
- CME derivatives volume: **~$1 trillion in Q3 2025 alone**
- Simon: Stablecoins mainstream via B2B → **B**; AI/blockchain bull cycle → **D minus** ("there was no bull cycle")
- Kai: Stablecoin-linked cards → **A+**; Bank-issued stablecoins / non-dollar stable → **B minus**; AI/crypto consensus → **B+/C** (X42 happened but faded)

### RWAs and On-Chain Lending
- Current on-chain stablecoin-denominated loans originated: **~$250 billion**
- Growth in 2025: **~175%**
- Collateral breakdown: **~75% crypto assets** (Bitcoin/ETH); only **1.8% (~$1.5B) tokenized RWAs**
- Kai's prediction: Grow 5x → **$10 billion** in tokenized RWAs / non-dollar stablecoins used as collateral for on-chain lending

### Loyalty / Tokenized Loyalty
- Unused point liability on corporate balance sheets: **~$1 trillion**
- Annual point liability issued: **$300 billion/year**
- Would make loyalty points **3rd largest currency in the world** after USD and EUR
- United Airlines recently paid off a **$5 billion revolving credit line** securitized against **$8 billion in point liability**
- Tyler/Kai prediction: **$1 billion in tokenized collateral** pegged to loyalty points by end of 2026
- That ~= **5–10% of all tokenized RWAs** at that time
- Consumer preference for cashback: **63%** of credit card users prefer cash back over any other loyalty reward (Citi or JP Morgan report)
- Cash back redemption rate: only **~58%** of cash back is actually claimed

### Tokenized Money Market Funds (Bidd vs. JPMM)
- Bidd (BlackRock): Peak ~**$3 billion** supply; dropped to **~$1.8 billion** at time of recording
- Bidd holders: Only **100 addresses** (many may be large entities)
- Minimum buy-in for Bidd: **$5 million**
- JP Morgan Kinexys: Processed **>$1 trillion in settlement** in prior 12 months
- Simon: JPMM (JP Morgan's new tokenized money market fund ticker: "MONEY") will surpass Bidd
- Rob: Disagrees — BlackRock will match distribution; "credibly neutral player"

### Merchant Stablecoin Payments
- Shopify USDC volume since launch (June): Only **~$600K total** (Rob guessed $100K, Simon guessed $1M)
- Shopify offers **1% back** in incentive — yet still minimal adoption
- Rob's prediction: **$2 billion annualized** merchant stablecoin payments by end of 2026
- Current e-commerce digital payment share: **~66% in some digital payment format**
- Account-to-account: "fastest growing part of payments in e-commerce today"

### Tier-2 Bank Settlement
- US banks: **~5,000 total**, but "probably only 500 of them need to exist"
- Kavelís (European bank consortium): Stated intent to go live **back half of 2026**; includes ~half-dozen announced banks
- JP Morgan Kinexys: Processing **>$1 trillion internally** — but Simon explicitly says this doesn't count (intra-bank)
- AMP Financial live with HSBC, Citi, JP Morgan: 24/7 instant settlement
- Quote: "if you had to guess today how much value has moved on chain between two banks directly in a stable coin / tokenized deposit... it's hard to think of a case where it's over a billion"

### X42 Agentic Payments
- Total X42 volume to date: **~$36 million**
- Estimated **≥90%** tied to memecoin minting — "not really agentic"
- Non-memecoin activity: **~$2 million** at most (optimistic)
- Second use case after memecoins: **crypto data services**
- Kai's prediction: **5x growth** → ~**$10 million in real (non-memecoin) volume** through X42 by end of 2026
- Current AI/crypto standards: **12 standards** for agentic payment protocols (Rob says "probably will be 24 by the time the podcast gets released")

---

## 4. CORE NARRATIVE ARCS

### Arc 1: Visa Stablecoin Settlement Is Going Parabolic
Rob's opening prediction is the episode's anchor. The jump from $250M to $3.5B in months is presented as proof of exponential trajectory. Kai cannot confirm specifics but validates directionally — noting the shift from crypto-native non-bank members to US banks using public blockchains for settlement. Simon takes the under (10x is not nothing) but acknowledges the bull case. Investment in Rain (Dragonfly-backed, direct Visa member issuer processor) is cited as firsthand color.

### Arc 2: Grading Ourselves — Accountability Without Excuses
The show opens with a structured retrospective: Yuval Rooz's predictions (Digital Asset), Simon's, and Kai's are all read out and graded. Kai criticizes the lack of quantifiable metrics: "We have to be better this year in putting a number out that we can then go back and measure a year from now." This sets up the entire episode's structure — every prediction must have a measurable number.

### Arc 3: The AI/Crypto Crossover Is More Meme Than Momentum
Rob's extended skepticism of AI/crypto crossover forms a thematic backbone. He argues: too many standards (12 now, probably 24 soon), real scaling requires standard convergence (like TCP/IP for the internet), agentic payments will use stablecoins eventually but "much further out than a lot of people believe." Simon partially agrees: the goat bot / X bot hype "grew as fast as it went away because there wasn't enduring fundamental value." Simon cites Visa's Intelligent Commerce Protocol (ICP) and Agentic Commerce Protocol (ACP) with Walmart, Etsy, and Instacart live and doing volumes as where actual traction is.

### Arc 4: Loyalty Points Are the Stealth Stablecoin Opportunity
Tyler's thesis reframes loyalty points as a sleeping stablecoin asset class. The framing: $1T in unused liability, $300B issued annually, loyalty points already rank as 3rd-largest currency globally if treated as currency. The tokenization angle: earn yield on reserves, create interoperable on-chain points, collapse marketing expense into revenue stream, enable tap-to-pay with points that swap into stablecoins. Kai extends this to "branded stablecoins" that enable merchant closed-loop payment networks. Rob anchors it to cash-back funded by yield on stablecoin reserves + new interchange share for non-bank issuers like Klarna.

### Arc 5: Tier-2 Banks Face an Existential Moment — Stablecoins Are the Response
Simon's prediction about tier-2 bank closed-loop settlement rails situates stablecoins as survival infrastructure for smaller banks: "This is core to how they survive today." Rob adds: "5,000 banks in the US, probably only 500 of them need to exist." Kavelís (European consortium) is the focal example. Cross-border settlement between two banks today: likely well under $1 billion on-chain. The prediction targets >$100B by end of 2026 — most panelists take the under but see the directional trend.

### Arc 6: Tokenized MMFs — JP Morgan vs. BlackRock
Simon argues JPMM (ticker: "MONEY") will surpass Bidd because JP Morgan can push it through Kinexys to existing corporate treasury clients who already use tokenized deposits. The 24/7 instant swap between tokenized deposits and MMFs solves a real treasury waterfall problem. Rob pushes back: BlackRock will match distribution; the "credibly neutral" argument gives them an edge. Both agree Bidd has been too crypto-native (even the name is a meme) and institutional positioning will shift.

### Arc 7: Merchant Stablecoin Payments — The Dog That Hasn't Barked Yet
Shopify's $600K in USDC volume since June launch despite 1% cashback incentives is the damning data point. Kai makes the structural argument: stablecoin linked cards are winning over direct merchant acceptance because consumers aren't holding stablecoins yet. The infrastructure precondition is wallet distribution + consumer incentives (Klarna as the model). Rob's $2B prediction is described as "not huge" — Simon himself notes he was going to object before hearing the number.

---

## 5. POSITIONING PILLARS

- **Stablecoins as "better cash":** "Stable coins are like better cash. They're instant. They're 24/7. They're global cash that I can stick in a teleporter and they can show up at the other side of the world."
- **The "train has left the station":** Used multiple times; signals irreversibility
- **Accountability via measurable predictions:** The show explicitly distinguishes itself from "directional" predictions that can't be graded
- **"Existential moment" for mid-tier banks:** Stablecoin settlement is not optional — it's survival
- **Loyalty as the stealth stablecoin use case:** $1T liability as "yield-bearing" tokenized asset — no one else is talking about this
- **Stablecoin linked cards > direct merchant acceptance:** Data supports card rails growing faster than on-chain merchant payments
- **JP Morgan as "the Borg":** "They will assimilate you... never bet against JP Morgan"

---

## 6. HOOKS & OPENINGS

The episode opens cold with the most dramatic stat — Visa stablecoin settlement going from $250M to $3.5B to (predicted) $100B+ — before any introductions. This is the show's best hook and it's used intentionally at the very top.

Other hooks/attention-grabbing lines:
- "There's nearly a trillion dollars of unused point liability trapped on corporate balance sheets. When you look at the reserves that would make loyalty points the third largest currency in the world behind the dollar and the euro."
- "JP Morgan moved a trillion dollars through Kinexys and that was before stable coins became a thing."
- "Shopify — one of the most innovative fastest-growing e-commerce marketplaces — accepted USDC since June. Total volume: $600K." (Delivered as a question — "Does anyone have any guesses?" — making it a game-show reveal)
- "There are 5,000 banks in the US. Probably only 500 of them need to exist."
- "I'm going to say that DTCC will go live with all US stock entitlements on chain... and my boldest bet is that Robinhood announces a plan to go token native."
- "Bidd. It's a crypto meme. Even the name is a crypto meme."

---

## 7. RECURRING PHRASES & LANGUAGE

- **"The train has left the station"** — Rob and Simon use independently; means stablecoins / tokenization is now irreversible
- **"All Christmases come at once"** / "all Christmases come early" — used twice for very bullish outcomes
- **"Never bet against JP Morgan"**
- **"Canary in the coal mine"** — Klarna USD (CLAUSD) as signal of broader fintech-to-stablecoin migration
- **"The Borg"** — JP Morgan; "they will assimilate you"
- **"Token native"** — used for Robinhood prediction; means building infrastructure natively on tokenized rails
- **"Story of my life, man"** — Rob's response to being called "a little early"
- **"Genie back in the bottle"** — used for regulatory inevitability
- **"Cryptonative"** (often unhyphenated) — describes early Bidd holders, X42 use cases, non-bank Visa settlement members
- **"Tortured analogies"** — Rob self-deprecates about mixing metaphors
- **"Screaming into the void"** — Simon describes his newsletter
- **"Payments nerds"** — Simon's term for his audience
- **"Get nerdy and get weird in 2026"** — outro catchphrase
- **"Points to pay"** / "tap to pay with my points" — Tyler's consumer framing
- **"Smart money"** / **"programmable money"** — used for stablecoin-powered B2B programmability
- **"Yield bearing"** — key phrase for tokenized loyalty / stablecoin reserve assets
- **"Off balance sheet"** — describing tokenized loyalty and stablecoin structures vs. traditional reserves
- **"Directional"** — the problem with last year's predictions; Kai wants "quantifiable" not just directional
- **"Existential moment"** — Rob on tier-2 banks and stablecoin adoption

---

## 8. COMPANIES / PROTOCOLS MENTIONED

| Entity | Role / Framing |
|---|---|
| **Visa** | Sponsor; stablecoin settlement via VTAP; Intelligent Commerce Protocol (ICP); "leader in digital payments" |
| **Stripe** | Sponsor; acquired Bridge; CLAUSD (stablecoin via Bridge); Klarna as user; "borderless finance" |
| **Centrifuge** | Sponsor; "market leader in tokenized real world assets"; >$1B TVL in RV lending; minted first RWA-backed stablecoin with Maker in 2017 |
| **Rain** | Stablecoin-linked card issuer processor; direct Visa member; Dragonfly investment; "possibly fastest growing issuer processor in history" |
| **Dragonfly Capital** | Rob Haddock's firm; investor in Rain |
| **Smart Media Technologies** | Tyler's company; tokenized loyalty / stablecoin merchant programs |
| **JP Morgan / Kinexys** | >$1T in settlement; JPMM (tokenized MMF); "MONEY" ticker; DBS partnership; "the Borg" |
| **BlackRock / Bidd** | $3B peak → $1.8B; only 100 holders; $5M minimum; "crypto product" framing |
| **Kavelís** | European bank consortium; closed-loop stablecoin settlement; ~6 announced banks; targeting back-half 2026 live |
| **Klarna (CLAUSD)** | Rob's "canary in the coal mine" for fintech stablecoin wallets; consumer wallet + merchant wallet; yield-based loyalty |
| **Shopify** | USDC acceptance on Base (via Coinbase); only $600K total since launch despite 1% incentive |
| **Coinbase / Base** | Partners for Shopify USDC; also mentioned in context of Bidd distribution |
| **X42** | Agentic payment protocol; $36M total volume; 90%+ memecoins; Kai's prediction of 5x growth |
| **Cloudflare** | Cited as potential X42 server / participant — "the wild card" |
| **Disney / OpenAI** | Disney-Sora content licensing deal cited as analog for IP monetization via agentic payments |
| **Robinhood** | Rob's bold prediction: will go "token native" following DTCC move; complication: deep ties with Citadel |
| **Citadel** | "Secretly runs the world"; publicly anti-clarity; potentially blocks Robinhood tokenization |
| **DTCC** | Predicted to go live with all US stock entitlements on-chain in 2026 |
| **Fifth Third Bank** | Tim Spence cited as example of regional bank leader saying stablecoin adoption is "core to how they survive" |
| **Fiserv** | Mentioned as exploring US equivalent of Kavelís-style settlement |
| **Cross River / Lead Bank** | Named as crypto-friendly banks that could pioneer closed-loop settlement |
| **Interactive Brokers (IBKR)** | Announced stablecoin deposits powered by Zero Hash |
| **PayPal** | Announced "pay with crypto" widget July |
| **Zero Hash** | Powered IBKR stablecoin deposit feature |
| **AMP Financial** | Live with HSBC, Citi, JP Morgan for 24/7 instant settlement |
| **DBS** | Partnered with JP Morgan Kinexys for potential open-loop expansion |
| **United Airlines** | Paid off $5B revolving credit line securitized against $8B in point liability |
| **Canton Network** | Yuval Rooz's (Digital Asset) project; "doing well" |
| **rwa.xyz** | Cited as data source for Bidd holder stats; "great data source" |
| **Arbitrum** | Robinhood did a deal with Arbitrum (referenced) |
| **Cursor** | Used as example of agentic payment UX — vibe coding, buying developer tools without leaving IDE |
| **ACP (Agentic Commerce Protocol)** | Simon's preferred agentic standard; Walmart, Etsy, Instacart live on it |
| **Etsy / Walmart / Instacart** | All live on ACP with actual volumes |
| **Tempo** | Simon's employer; Head of Market Development |
| **CME** | ~$1T derivatives volume in Q3 2025 |
| **Starbucks** | Used as analogy for merchant stablecoin / point pre-purchase model |

---

## 9. USE CASES HIGHLIGHTED

1. **Stablecoin-linked card settlement** — Visa network; fastest growing; replacing USD settlement in card programs
2. **Tier-2 bank inter-bank settlement** — Kavelís-style closed-loop consortia; alternative to correspondent banking
3. **Tokenized loyalty programs** — $1T off-balance-sheet liability → yield-bearing, interoperable, merchant-revenue-generating
4. **Cashback via stablecoin yield on reserves** — Klarna model; yield + interchange share → consumer wallet incentive
5. **Tokenized money market funds** — JPMM vs. Bidd; corporate treasury waterfall; 24/7 instant swaps
6. **On-chain lending with tokenized RWAs as collateral** — FX synthetic via collateral (borrow USDC against South African rand, avoid FX swap)
7. **"Pay with stablecoin" at e-commerce merchants** — Still nascent; Shopify $600K as cautionary data
8. **Stablecoin-backed brokerage deposits** — IBKR + Zero Hash
9. **Agentic payments (X42)** — Developer tools purchased inside IDE (Cursor); early-stage meme vs. real use case
10. **Gift cards → stablecoins** — Gift cards replaced with stablecoins to eliminate fraud and breakage
11. **Private equity tokenization + DTCC clearing** — More near-term than public equities; "no central clearing for PE"
12. **B2B stablecoin onchain FX alternative** — Borrow USDC against local currency tokenized treasury; repay after receipt of USD

---

## 10. TONE & STYLE

- **Interview-meets-debate** with structured betting ("I'll take the under")
- **Insider-fluent** — assumes deep stablecoin/TradFi payments knowledge; no definitions given
- Occasional self-deprecating humor; strong rapport between hosts
- **Prediction accountability culture** — explicit grading, public commitments with numbers
- Warm and casual but substantively rigorous; "nerdy and weird" as brand identity
- Cross-cutting dynamic: Rob (VC, somewhat bearish on AI/crypto), Kai (Visa insider, bullish on cards), Simon (UK journalist/exec, eclectic), Tyler (startup founder, data-driven bull on loyalty)

---

---

# FILE 2: CAC26 Video Script
**(Crypto Asset Conference 2026 — Frankfurt School Panel: "Next Phase of Capital Markets with Crypto")**

## 1. OVERVIEW
- **Format:** Live conference panel, Q&A format, audience participation, one moderator + 4 panelists
- **Length:** ~43 minutes (panel + audience Q&A)
- **Style:** Academic-meets-practitioner debate; European institutional perspective; moderator is personally invested ("sentimental day" — graduated from Frankfurt School in 2023); moderate hype level with genuine skepticism about European competitiveness; audience Q&A in final third
- **Audience:** European institutional finance professionals, regulators, crypto asset conference attendees; Frankfurt School alumni and faculty; mix of TradFi and DeFi practitioners
- **Venue:** Frankfurt School of Finance & Management lecture room

---

## 2. SPEAKERS & SEGMENTS

### Moderator — Head of Business Development, EOTA
- EOTA (founded by Philip Zander 3 years ago) focuses on tokenization of CO2 credits and carbon credits
- Frankfurt School 2023 Masters in Management graduate
- Frames questions provocatively: "colonization of DeFi methods by TradFi?" and "Europe is dead?" challenge

### Michael — CEO & Founder, 360X
- Former head of R&D unit and venture capital arm, Commerzbank
- 360X is part of Doza Group; focuses on tokenized securities
- Recently partnered with Kraken and ONO
- Key argument: US dominance is structural; DTCC/US FMI will capture tokenization infrastructure globally; only reason to tokenize is 24/7 trading; AI-driven agentic trading is the next frontier; SAP/HANA S4 stablecoin hub is Germany's best use case
- Style: Blunt, provocateur; "Europe is dead. That's my conclusion."

### Dolph Dixon — Co-founder & CEO, Hive
- Hive: digital asset trading to banks and brokers in B2B and B2C setups; moving into tokenized securities
- Key argument: Competition between TradFi and DeFi is dual-layered (intermediate and ultimate); in 10 years technology itself won't be the differentiator — services and investment opportunities will be
- Style: Measured, structural thinker; good at reframing questions

### Ben Duvet — Global Head of Partnerships, GK8 by Galaxy
- Galaxy Digital's crypto custody solution; former head of digital assets at BNY and the ECB
- Key argument: US capital has decisive liquidity advantage; Europe risks becoming a "dumb repository" feeding into DTCC infrastructure; threat is real but not total since European capital markets already mostly run by US institutions; Kraken tokenizing $25B in X stocks vs. EU's $4B in bond issuance says it all
- Style: Diplomatic institutional perspective; frames threats and opportunities

### Thomas — CCO, Tresor
- Tresor provides digital asset operating infrastructure for banks and brokers
- Former Commerzbank, consulting, joined crypto/digital assets 2018–2019
- Key argument: Three-wave evolution (crypto → digital payments → tokenization); settlement still has the "fiat payment piece missing"; synchronous vs. asynchronous settlement problem; stable coins one of several solutions alongside CBDC and CBMT; fiat rails are still the "annoying part" (money disappears for 8 hours)
- Style: Practical infrastructure view; not sure privately issued stablecoins are the solution

### Segment Structure:
1. Intro round (abbreviated)
2. Q1 (Moderator): DeFi vs. TradFi — convergence or colonization?
3. Q2 (Moderator): Which global region is best positioned? Europe vs. US vs. Asia
4. Discussion: 24/7 trading as the only current reason for tokenization
5. Discussion: AI-driven agentic trading as the next major shift
6. Q3 (Audience): Stock exchange buys crypto exchange, or vice versa?
7. Discussion: AI tools driving down cost of regulated compliance software
8. Q4 (Audience): Germany/Dutchland AGI 2.0?
9. Q5 (Audience): Are stablecoins the kickass tokenization driver for institutions?
10. Q6 (Audience, final): EU bond tokenization: only $4B since 2021 — what are the hurdles?
11. Moderator closes, thanks panelists

---

## 3. ALL KEY STATS & DATA

- **EU on-chain bond issuance since 2021:** Only **€4 billion** — cited by ECB executive board member in a recent talk titled "Building the Rates for Europe's Tokenized Financial Markets"
- **Kraken X Stocks tokenization:** **$25 billion** — Michael uses this to contrast with EU's €4B ("Kraken did 25 billion in tokenization on X stocks")
- **US DTCC tokenization (Canon):** Mentioned as tokenizing "by the end of this year on Canon" but as "just an interim stage"
- **ADRs by index:** 100% of DAX companies have ADR programs; 96% of MDAX; 97% of Euro Stoxx 600
- **European capital markets:** Already run predominantly by US institutions ("all key players are non-European, all liquidity formation is non-European")
- **AI cost reduction:** "The cost of software is basically zero" with new AI tools — driving down compliance, data, and operational costs for new entrants
- **Traditional bank expense breakdown (3 items):** 1) Regulatory/paperwork; 2) Data and connectivity costs; 3) People
- **Tokenization timeline:** "It still takes 25 years at least until things go really tokenized" (Michael)
- **Hybrid market:** Will exist "for 20–25 years at least" alongside fully tokenized markets
- **$4B** EU bond issuance vs. $25B Kraken X Stocks — the headline comparison of this panel

---

## 4. CORE NARRATIVE ARCS

### Arc 1: The DeFi vs. TradFi Question Is the Wrong Frame — It's Really About Standards Convergence
Dolph's opening reframe: in 10 years, the technology will become invisible plumbing. Competition will shift from "DeFi vs. TradFi technology" to "quality of service, investment opportunities, and client experience on the same rails." The intermediate phase involves real competition for retail clients (risk appetite determines TradFi vs. DeFi choice). Long-run = convergence.

### Arc 2: Europe Is at Structural Risk of Becoming a "Dumb Repository" for US FMI
Michael's blunt thesis: DTCC wins globally because it controls the deepest liquidity pool plus US regulatory momentum. EU's DAX/MDAX/EuroStoxx 600 issuers all already have ADR programs → they'll connect to whoever has the most product. Europe built fragmented systems ("a great idea by lawyers was a great idea by regulators but no one cares"). Ben nuances: European capital markets are already mostly run by US institutions (BNY, Citi, Goldman), so the marginal loss is smaller. But if DTCC adds EUR to their platform — competitive advantage gone.

### Arc 3: The Only Real Reason for Tokenization Right Now Is 24/7 Trading
Michael's key thesis: Traditional clearing technology will catch up on everything else. The only structural reason to tokenize today is the ability to trade and react on weekends, evenings, during event-driven market disruptions (Michael cites "attacks" that happen outside business hours). "That's the only reason you're doing it." The hybrid market will persist 20–25 years, which is "good for incumbents."

### Arc 4: AI-Driven Agentic Trading is the Next Seismic Shift
Michael, former head of electronic trading, draws an explicit parallel: "We had needed to have standard languages between computers to have orders — that's when FIX was created. We need the same thing now for having agentic trading among each other." The bilateral/multilateral framing becomes obsolete. His firm is actively investing in AI-driven agentic trading. This is the big unstated opportunity from this panel.

### Arc 5: Europe Has Hope — But Needs to Move Much Faster
Thomas and Dolph both resist full pessimism. Points in Europe's favor: MiCA regulation is pan-European (first time), DORA driving supply chain risk reassessment, European "self-confidence" building after US dependency exposed. Michael: Amsterdam is where real 2026 innovation is happening. SAP/HANA S4 stablecoin integration is Germany's best near-term stablecoin use case. But the pace problem is real: US companies in the fall planning cycle can commit capital amounts "we in Europe would never take."

### Arc 6: Stablecoins Are Essential but Not Sufficient — CBDC/CBMT Are European Alternatives
Thomas: three digital payment waves (crypto → digital payments → tokenization) — stablecoins are part of wave 2. For US companies, stablecoins are the only option (no CBDC). For Europeans, CBDC and CBMT are alternatives. Ben: private stablecoins require assessing risk, ensuring partner uptake simultaneously; the real gap is lack of wholesale digital euro. Michael: SAP HANA S4 stablecoin hub is Germany's practical killer app for stablecoin payments — enterprises can wire immediately, handle minor FX, without needing a bank.

---

## 5. POSITIONING PILLARS

- **"The only reason we're doing tokenization right now is 24/7 trading"** — Michael's anchor claim; reduces hype to one real value driver
- **Europe as dumb repository risk** — stark warning; used to generate urgency for institutional European audience
- **"The FMI will be based in the US"** — structural claim about infrastructure power
- **Amsterdam as Europe's 2026 innovation hub** — positive note; "everything related to crypto in Europe is happening in Amsterdam"
- **AI tools → cost of software is basically zero** — democratization of compliance tech; levels playing field for new entrants
- **Exchanges are exchanges** — products expand, not identities; no meaningful distinction between stock and crypto exchange
- **SAP HANA S4 stablecoin hub** — Germany's specific, practical stablecoin use case
- **"Never give up without a fight"** — Thomas's European resilience framing

---

## 6. HOOKS & OPENINGS

- Moderator opens with sentimental personal connection (lecture room = former classroom), then pivots: "Do we see a colonization of DeFi methods by TradFi?" — provocative framing
- Michael's blunt opener: **"Europe is dead. That's my conclusion."** — strongest hook of the panel
- Audience Q: "Will a stock exchange buy a crypto exchange, or will a crypto exchange acquire a stock exchange?" — generates the clearest answer: "There is no difference between a stock exchange and a crypto exchange."
- **"Kraken did 25 billion in tokenization on X stocks. [EU]: 4 billion euros of bond issuance since 2021."** — the starkest data contrast of the panel

---

## 7. RECURRING PHRASES & LANGUAGE

- **"Chicken and egg / chicken of an egg and an egg neck problem"** — Thomas on coordination challenge between tokenization adopters
- **"Dumb repository"** — Ben's threat scenario for European FMI
- **"The FMI will be based in the US"** — Michael's refrain
- **"Winner takes all"** — moderator's framing for TradFi/DeFi competition
- **"Get your act together"** — repeated call for European coordination
- **"Legacy systems that work quite well"** — Thomas on why TradFi incumbents are slow to change
- **"Plumbing"** — technology becoming invisible infrastructure; "10 years not be discussing the technology anymore because it's the plumbing"
- **"On and off ramps"** — European challenge without integrated payment scheme
- **"Event-driven markets"** — weekends when "attacks" happen and you need to trade your portfolio; 24/7 value driver
- **"You invest based on identity or where you make money"** — Michael dismissing European resilience as emotional argument
- **"The cost of software is basically zero"** — AI-driven disruption of regulated tech costs
- **"Superior liquidity"** / **"deepest liquidity pool"** — Ben's framing of US structural advantage
- **"SAP stablecoin hub"** — Michael's practical German use case
- **"Not an OG"** — self-deprecating credential check in crypto context
- **"Real opportunities in event-driven markets"** — Michael on 24/7 trading as the key tokenization value driver
- **"Asynchronous"** — Thomas describing fiat payment leg in digital asset settlement
- **"Two different streams"** — asset stream (on-chain) vs. payment/cash stream (still off-chain)

---

## 8. COMPANIES / PROTOCOLS MENTIONED

| Entity | Role / Framing |
|---|---|
| **360X** | Michael's company; Doza Group subsidiary; tokenized securities; partnered with Kraken and ONO |
| **Hive** | Dolph's company; digital asset trading B2B/B2C for banks/brokers; moving into tokenized securities |
| **GK8 by Galaxy** | Ben's company; Galaxy Digital crypto custody solution |
| **Tresor** | Thomas's company; digital asset operating infrastructure for banks and brokers |
| **EOTA** | Moderator's company (Philip Zander founded); CO2/carbon credit tokenization |
| **Commerzbank** | Michael and Ben's former employer; 2017 first regulated bond tokenization |
| **Frankfurt School of Finance** | Venue; moderator's alma mater |
| **Deutsche Boerse / 3DX** | Trading crypto today; "what's the difference"; mentioned as sponsor |
| **Kraken** | 360X partnership; $25B in X Stocks tokenization — contrasted with EU's $4B |
| **ONO** | 360X partner |
| **DTCC** | US FMI threat to European tokenized capital markets; moving all US stock entitlements on-chain |
| **Euroclear / Clearstream** | EU clearing infrastructure; fragmented; competitors to any tokenized alternative |
| **CSD (Central Securities Depositories)** | Expensive to connect; "connects only once to whoever has the most product" |
| **ECB** | Executive board talk "Building the Rates for Europe's Tokenized Financial Markets"; cited the €4B stat; wholesale digital euro proponent |
| **Bundesbank** | Technical infrastructure for German payments (alongside H1/Emila for securities) |
| **MAS (Monetary Authority of Singapore)** | Mentioned in context of Kinexys / Kexus cross-border settlement |
| **SAP / HANA S4** | Michael's killer app: SAP stablecoin hub enabling enterprise payments without banks |
| **ZCash / Zchen** (unclear) | Stablecoin issuers on same platform as payments; opportunity for change |
| **BNY** | Ben's former employer; mentioned as example of US institution running European capital markets |
| **Kavelís** | Mentioned briefly in context of European bank settlement innovation (more detailed in File 1) |
| **Prediction markets** | Mentioned as current onramp alongside tokenized securities by Dolph |

---

## 9. USE CASES HIGHLIGHTED

1. **24/7 trading of tokenized assets** — the only currently justified use case per Michael
2. **AI-driven agentic trading** — replacing FIX protocol; bilateral/multilateral becomes obsolete; Michael's firm actively investing
3. **ADR tokenization** — all major European index companies already have ADR programs; tokenization of those is inevitable via DTCC
4. **SAP HANA S4 stablecoin hub** — German enterprise stablecoin payments without traditional banking rails
5. **Bond tokenization** — EU €4B vs. global ambition; blocked by liquidity fragmentation
6. **Tokenized private equity** — cleaner use case than public equities near-term (no central clearing today)
7. **360X platform** — settling securities against stablecoin already live
8. **Wholesale CBDC / digital euro** — Ben's preferred solution for bank-to-bank settlement; "retail CBDC makes no sense"
9. **Carbon/CO2 credit tokenization** — EOTA's specific domain (moderator's company)
10. **Prediction markets** — mentioned as current onramp by Dolph

---

## 10. TONE & STYLE

- **Academic-institutional with practitioner edge** — Frankfurt School setting; panelists have long European TradFi credentials
- **More skeptical and measured** than File 1; less hype, more structural analysis
- **Provocation-driven moderation** — "Europe is dead?" framing successfully draws sharp answers
- **Genuinely uncertain** about outcomes; panelists hedge, caveat, and disagree productively
- **European identity undertone** — mild defensive nationalism about EU competitiveness; pragmatic acknowledgment of US dominance
- **Technical depth** assumed — FIX protocol, CSD connectivity, ICSD market, CBMT, MiCA all used without definition
- Lighter on data / numbers than File 1 but stronger on structural framework

---

---

# FILE 3: 2026 ITP Payments Video Script
**(ITP Payments Conference — Panel: Genius Act, Stablecoins & Tokenized Deposits — 6 Months On)**

## 1. OVERVIEW
- **Format:** Conference panel, moderated; live audience polls via Slido for two questions; conversational
- **Length:** ~41 minutes
- **Style:** Educational but practitioner-focused; structured around three sections (Genius Act boundaries → launching solutions → financial reality → 12–24 month outlook); audience polls ground the discussion in real-time institutional readiness data; final section on "parting words of advice" for laggards
- **Audience:** US-focused financial institution professionals — banks, credit unions, fintechs; primarily those evaluating or beginning to deploy digital asset strategies
- **Format note:** File begins mid-sentence — the opening portion of the panel is missing from the transcript

---

## 2. SPEAKERS & SEGMENTS

### Elizabeth — Visa (Senior Digital Assets / Product)
- References "what we're doing at Mia" — possibly a Visa division or subsidiary
- Key positions: Both stablecoins and tokenized deposits will coexist; banks have trust + distribution advantages; fintech/crypto-native firms have technology + speed advantages; best path is cooperation; stablecoin sandwich concept; monitoring tokenized deposit behavior for bank run risk
- Style: Careful, measured, customer-centric; "ground yourself in the customer"

### Larry Pros — Managing Director, Strategic Resource Management (SRM)
- Full-service consulting firm; Larry's focus: emerging and disruptive financial technology (stablecoins, tokenized deposits, digital ID, quantum computing, AI)
- Key positions: Stablecoins are more like full-reserve banking — arguably safer than fractional-reserve deposits in stress; $6.6 trillion deposit flight risk (Treasury Department estimate); yield finds a way despite Genius Act restrictions; biggest threat to bank deposits is tokenized MMFs; stablecoins will disintermediate payments, lending, and deposits simultaneously; $10 trillion in stablecoin payment activity already; "you better have an answer" for your board in 2 years
- Style: Direct, advisory; consultant voice; willing to say uncomfortable things to bank audiences

### Segment Structure:
1. Welcome and framing (Elizabeth introduces three sections + Slido poll)
2. Poll 1: Where does your organization stand today on digital assets?
3. Discussion: End customers — who are they? (B2C/B2B/gig economy/remittances)
4. Poll 2: Which forms of digital money are you evaluating? (stablecoins / tokenized deposits / both / neither)
5. Genius Act: stable coin vs. tokenized deposit distinction; risk profiles; bank advantages
6. FDIC insurance and full-reserve banking safety argument
7. Tokenized deposit risks (programmable bank run)
8. Stablecoin sandwich concept
9. Disintermediation threat analysis (payments, deposits, lending)
10. Yield / Genius Act loophole discussion
11. Banks vs. fintechs: speed to market and regulatory advantage
12. Technology evolution: account-based → wallet-based; unified ledger
13. Financial reality: net interest margin impact; LCR adjustment
14. FX and cross-border implications
15. Scaling proof of concepts
16. Parting advice (Larry): "You better have an answer for your board in 2 years"

---

## 3. ALL KEY STATS & DATA

### Market Size & Flows
- **$10 trillion** in stablecoin payment activity "associated with true payment activity" — mostly B2B, mostly cross-border (Larry)
- **$300 billion** DeFi lending market ("about a $300 billion business" — Larry)
- **$6.6 trillion** potential US deposit flight to stablecoins — Treasury Department study from April [prior year]
- **2–3 basis points** stablecoin transaction cost vs. "a whole lot more" for traditional card transactions
- **Stablecoin reserves:** Must be backed 1:1 by HQLA per Genius Act — specifically: US Treasuries ≤93 days, repos, reverse repos, bank deposits

### Workforce / Gig Economy
- **5%** of US businesses have overseas exposure (employees or vendor payments)
- **18%** of US workers are foreign-based workers in the US sending remittances home
- **30%** of consumer businesses workers are in the gig economy — "living paycheck to paycheck"

### E-Commerce Payments
- **66%** of e-commerce volume today is in "some sort of digital payment format"
- Account-to-account payments: "fastest growing part of payments in e-commerce today"

### Stablecoin Reserves / Genius Act Specifics
- Eligible HQLA backing: US Treasuries ≤93 days maturity, repos, reverse repos, bank deposits
- Genius Act explicitly prohibits stable coin issuers from paying yield directly to holders
- Genius Act does NOT prohibit passing yield to third-party intermediaries (the "loophole" — Coinbase-style revenue share)
- Upcoming Clarity Act may close this loophole (bank lobby position)
- Genius Act: stable coin issuers must comply with BSA, AML, KYC — same as banks
- 180-day rule-making period following Genius Act passage; FDIC was earliest to provide guidance

### Audience Poll Results
- Poll 2 results: "Just under half" chose "both" (stablecoins + tokenized deposits) — described as the largest single answer category

### Historical Analogs
- SVB failure: Large depositors fled to systemically important institutions; next crisis, they might flee to fully-reserved stablecoins
- Money market funds introduction: Banks historically lost that argument; "they were giving away toasters" to compete
- Trump's 10% interest cap discussed as hypothetical: "I don't think anyone in this room believes that's going to happen" but would push people toward DeFi/stablecoin lending

---

## 4. CORE NARRATIVE ARCS

### Arc 1: Ground Everything in the Customer — Stop Starting with the Technology
Elizabeth's primary theme: "What's the problem that we're solving? Who is our customer?" Repeated multiple times. Three customer segments identified: B2C/gig economy (instant payments), P2P remittances (difficult corridors), B2B (programmability, smart contracts, conditional payments, data with payments). The technology enables all of these but starting from the technology is the wrong approach.

### Arc 2: Stablecoins vs. Tokenized Deposits — Different Tools, Different Jobs
The Genius Act's definitional distinction (stable coin = not a bank deposit) forces a structural choice. Elizabeth's framing: tokenized deposits feel like traditional deposits (FDIC analog, familiar accounting) = easier first step for banks. Stablecoins are different: non-bank issuers compete, 1:1 HQLA backing required, no FDIC insurance, bearer instrument. But both will coexist. Predicted future: stable coins = high-velocity money movement; tokenized deposits/MMFs = store of value. The "stablecoin sandwich" makes this concrete.

### Arc 3: Stablecoin Sandwich — The Practical Architecture
"You may go from either a traditional deposit or a tokenized deposit. You transfer it into a stable coin to do the money movement around the world cuz it's a lot more interoperable. At the receiving end it's again moved back either into regular deposit fiat or tokenized deposit." This is the cleanest use-case architecture presented in any of the three files. Makes explicit why interoperability is the critical property.

### Arc 4: Full-Reserve Banking May Be Safer Than Fractional-Reserve in a Stress Event
Larry's counter-intuitive argument: FDIC insurance absence is not a vulnerability — it's a feature. Stablecoins are fully reserved, bankruptcy remote, fully segregated. SVB scenario: large depositors fled to SIBs. Next crisis: they may flee to stablecoins. Implication for banks: you cannot rest on FDIC as competitive differentiation.

### Arc 5: Yield Will Find a Way — Banks Will Lose This Argument
Genius Act prohibits direct yield to holders. But: third-party intermediary loophole (Coinbase-style revenue share) not addressed. DeFi liquidity pools earn yield on stablecoins. Merchants may offer rewards for stablecoin payments. "Yield finds a way. I think that's a bad argument tried to be chasing down." Elizabeth agrees: biggest threat is actually tokenized MMFs offering yield — banks should sell those rather than argue against yield.

### Arc 6: The Real Disintermediation Threat Is Three-Dimensional
Larry's comprehensive threat map: (1) Payments — stablecoin as alternative payment rail; (2) Deposits — $6.6T in potential deposit flight (Treasury estimate); (3) Lending — DeFi $300B lending market + programmable stablecoin entering liquidity contracts. The Trump 10% interest cap (if it happened) would accelerate #3. "You need to be very aware of these tools and get involved in them early, right? So that you're not disintermediated."

### Arc 7: Banks Have Advantages — But Not the Ones They Think
Elizabeth's banker's honest assessment: distribution, client relationships, compliance infrastructure, trust, on/off ramps — these are real advantages. But: fintechs are hiring banking compliance staff, Genius Act levels the regulatory playing field, fintechs have technology speed. Larry: "Regulatory moves are not going to protect us anymore." Solution: cooperate with fintechs as partners/clients, not just competitors. Move from account-based to wallet-based infrastructure now.

### Arc 8: The Clock Is Running — The Board Will Ask in 2 Years
Larry's closing warning: "You don't have to have a stable coin offering. You don't have to have a solution. You have to have had thought about it. You have to have an informed decision around it. Because if your board, your investors ask you why or why you didn't do something with stable coins in two years from now, you better have an answer."

---

## 5. POSITIONING PILLARS

- **"Ground yourself in the customer"** — Elizabeth's master key; repeated as antidote to tech hype
- **"Stable coin sandwich"** — named architecture for how stablecoins fit into larger payment flows
- **Full-reserve banking as a feature, not a bug** — reframes FDIC absence as safety advantage in stress scenarios
- **"Yield finds a way"** — resistance to bank lobby's Genius Act yield-restriction argument
- **"Transformative technology — everyone benefits"** — Larry's closing framing; banks, merchants, consumers, governments all win
- **"Both will exist"** — stablecoins and tokenized deposits are not either/or
- **Account-based → wallet-based shift** — infrastructure evolution banks must prepare for now
- **"You better have an answer for your board"** — urgency without panic; informed decision required even if no product launched
- **"Don't unsolve solved problems"** — Elizabeth's product design principle
- **"Smart money"** — programmable, conditional, event-based payment capability of stablecoins/tokenized deposits

---

## 6. HOOKS & OPENINGS

The strongest attention-grabbing moments:
- **"$6.6 trillion dollars of deposit flight could be at risk of moving to stable coin"** — Treasury Department figure; devastating for bank audience
- **"30% of consumer businesses workers here in the US are associated with the gig economy. These people are living paycheck to paycheck."** — humanizing the use case
- **"This is one of those technologies that everyone benefits from it. Banks can benefit. Merchants can benefit. The end customer can benefit. Governments can benefit."** — rare "everyone wins" framing
- **"You better have an answer [for your board] — because it may be dependent on whether or not you're still in business."** — existential stakes
- The SVB analogy: "What we saw during SVB was we saw a lot of large depositors... flee... Well, we have another one of those. They might actually flee to stable coins which are fully reserved, bankruptcy remote, fully segregated — arguably a safer place to have it than deposits."
- **"They were giving away toasters"** — historical analog to yield competition

---

## 7. RECURRING PHRASES & LANGUAGE

- **"Stable coin sandwich"** — the defining architecture metaphor of this file; stablecoin used only for movement, deposit for store of value
- **"Full reserve banking"** vs. **"fractional reserve banking"** — the foundational distinction; used to reframe FDIC debate
- **"Ground yourself in the customer"** — Elizabeth's repeated directive
- **"Smart money"** — programmable payment capability
- **"Don't unsolve solved problems"** — Elizabeth's product design principle
- **"Programmable bank run"** — risk of 24/7 instant tokenized deposits; new liquidity monitoring challenge
- **"Bankruptcy remote / fully segregated"** — stablecoin safety properties in stress
- **"Wallet-based vs. account-based"** — the infrastructure evolution framing; "big push and talk in the industry"
- **"On and off ramps"** — critical for banks as bridge between TradFi and DeFi
- **"Yield finds a way"** — Larry's refrain
- **"Liquidity coverage ratio (LCR)"** — bank metric Elizabeth says Treasury teams are adjusting
- **"High quality liquid assets (HQLA)"** — Genius Act reserve requirement term
- **"It's very early days"** / **"early days"** — used multiple times; hedge on behavioral predictions
- **"Level playing field"** — repeated; Genius Act creates one between banks and fintechs for compliance
- **"Interoperable"** / **"interoperability"** — key property of stablecoins for cross-border movement
- **"Push to card"** — Visa-specific FX solution at point of sale
- **"Stablecoin as a cash derivative"** — Larry's definitional anchor
- **"Informed decision"** — Larry's minimum bar for non-adopters

---

## 8. COMPANIES / PROTOCOLS MENTIONED

| Entity | Role / Framing |
|---|---|
| **Visa** | Elizabeth's employer; embedding stablecoins across infrastructure; "push to card" FX at POS; Visa debit in front of stablecoin |
| **Strategic Resource Management (SRM)** | Larry's consulting firm; advises banks, credit unions, fintechs on emerging fintech |
| **BlackRock / Bidd** | Largest tokenized MMF; "biggest threat to bank deposits is tokenized money market funds" |
| **JP Morgan (JPMM)** | Referenced via tokenized MMF context; "big money market fund providers" |
| **SVB (Silicon Valley Bank)** | Historical analog for deposit flight; stablecoins as next potential flight-to-safety destination |
| **Coinbase** | Revenue-share model for Genius Act yield loophole; "I pay Coinbase some sort of my revenue" |
| **FDIC** | FDIC insurance cannot cover stablecoins (by law); earliest to provide Genius Act guidance |
| **Federal Reserve / Fed Wire** | "Outside of Fed wire hours" — programmable bank run risk framing |
| **BIS (Bank for International Settlements)** | "Regulated liability network" / unified ledger concept |
| **Treasury Department** | April study: $6.6 trillion deposit flight risk estimate |
| **DTCC** | Briefly referenced in context of shared ledger |
| **OCC** | Now licensing non-bank issuers as federal qualified stable coin issuers |
| **DeFi (general)** | $300B lending market; liquidity pools for yield; "DeFi contract" |
| **Genius Act** | Central regulatory framework throughout; 180-day rule-making; prohibits yield to holders; requires BSA/AML/KYC; HQLA reserve requirement |
| **Clarity Act** | Under congressional debate; may close yield loophole |
| **Congress / bank lobby** | Bank lobby wants Clarity Act to close yield loophole |
| **Trump** | 10% interest cap discussed as hypothetical (dismissed as unlikely but instructive) |

---

## 9. USE CASES HIGHLIGHTED

1. **B2C / gig economy instant payments** — 30% of US workforce in gig; wants immediate pay
2. **P2P remittances** — 18% of US workers are foreign-based; "difficult corridors"
3. **B2B cross-border payments** — 5% of businesses with overseas exposure; want instant USD payments to vendors
4. **Conditional / event-based B2B payments (smart contracts)** — why checks still exist in B2B (data + payment together); stablecoin smart contracts solve this
5. **Stablecoin sandwich** — movement layer between deposit stores of value
6. **DeFi lending** — $300B market; earn yield on stablecoins in liquidity pools; disintermediation of bank lending
7. **Tokenized MMFs as store of value** — corporate treasurer waterfall: stablecoin for movement → tokenized MMF for storage
8. **FX via push-to-card** — Visa debit card in front of stablecoin; merchant gets local currency; handle FX at POS
9. **Remittance off-ramp** — stablecoin transferred → push to card → local bank account in local currency
10. **Flight to safety in stress events** — stablecoins as full-reserve alternative to SIB deposits in crisis
11. **Programmatic cashback / merchant rewards** — merchants offer rewards for stablecoin payments (emerging)

---

## 10. TONE & STYLE

- **Educational and practitioner-advisory** — designed for bank/credit union professionals not yet deeply engaged
- **Moderate urgency without panic** — Larry's "you better have an answer" is the strongest pressure but balanced by Elizabeth's measured "early days"
- **Poll-grounded** — unique use of live audience data to self-reflect as an industry
- **Customer-centric vs. technology-centric framing** — explicitly positioned against hype
- **Regulatory-dense** — most references to specific legislation of all three files (Genius Act, Clarity Act, FDIC, OCC, BSA, AML, LCR, HQLA)
- **Cooperative competition framing** — "competition makes all of us better"; fintechs as partners and clients
- **US-centric** — almost exclusively US market; FX treated as edge case

---

---

# CROSS-CUTTING THEMES ACROSS ALL THREE FILES

## Theme 1: Infrastructure Is the Real Prize — Not Product

All three files ultimately argue that the battle for stablecoin/tokenization dominance is won at the infrastructure layer:
- File 1: Visa settlement network, Kinexys, DTCC stock entitlements
- File 2: "The FMI will be based in the US" — DTCC vs. EU CSDs
- File 3: Account-based → wallet-based; unified ledger; side-core blockchain attached to traditional core

**Shared language:** "plumbing," "rails," "settlement," "clearing," "on/off ramps"

---

## Theme 2: 24/7 / Instant Settlement as the Killer Differentiator

All three files cite speed and round-the-clock availability as the fundamental value proposition:
- File 1: Stablecoin linked cards > direct payments; tier-2 bank settlement; instant MMF swaps for corporate treasurers
- File 2: Michael — "The only reason we're doing tokenization is 24/7 trading"
- File 3: Gig workers "living paycheck to paycheck"; B2C instant pay; programmable bank run risk as downside of the same feature

---

## Theme 3: Stablecoins Not Crypto — But the Perception Gap Is Still a Problem

All three files push against the "crypto = stablecoin" framing:
- File 1: Bidd described as "a crypto product" even though it's BlackRock's; "even the name is a meme"
- File 2: Thomas — "stable coins might be CBDC, CBMT and different forms of solutions... they will coexist"
- File 3: Larry — "stable coins come from the crypto world; I wouldn't look at them as crypto; I'd look at them as a new payment rail"

---

## Theme 4: Regulation as Enabler, Not Obstacle — But With Snapback Risk

All three files treat regulatory clarity as a net positive but with nuance:
- File 1: Rob — "coin flip" on Clarity Act; real concern is post-2028 snapback risk; regulatory clarity already happening through rulemaking regardless of legislation
- File 2: MiCA cited positively but European execution speed insufficient; DORA driving supply chain risk reassessment
- File 3: Genius Act's 180-day rulemaking; FDIC first to provide guidance; OCC licensing non-bank issuers; yield prohibition will be circumvented anyway

---

## Theme 5: Banks Have Trust and Distribution, Fintechs Have Technology and Speed — Cooperation Is the Answer

All three files converge on a "cooperate or die" thesis for traditional banks:
- File 1: Rain as the model — crypto-native issuer processor as direct Visa member, fastest growing; banks partnering not competing
- File 2: "Cost of software is basically zero" with AI tools; new entrants can rebuild compliance infrastructure from scratch
- File 3: "Let's cooperate... these firms are competitors but they're also partners and they're also potential clients"

---

## Theme 6: The Loyalty / Yield / Cashback War Is Coming

Directly addressed in File 1, obliquely connected in Files 2 and 3:
- File 1: Tyler's $1T loyalty liability thesis; 63% of consumers want cashback; yield on reserves funds cashback
- File 2: SAP stablecoin hub enables enterprise payment yield and FX efficiency
- File 3: Yield finds a way despite Genius Act; tokenized MMFs paying yield = biggest bank deposit threat; merchants will offer stablecoin rewards; "they were giving away toasters"

---

## Theme 7: JP Morgan Is the Gorilla in Every Room

Referenced across all three files, never as a sponsor but always as the gravitational center:
- File 1: Kinexys ($1T processed); JPMM tokenized MMF predicted to surpass Bidd; "the Borg — never bet against JP Morgan"
- File 2: US capital markets already dominated by US institutions including JP Morgan; DTCC/US infrastructure will assimilate tokenization
- File 3: Tokenized MMFs (BlackRock + JP Morgan) as biggest deposit threat; bank lobby trying to close yield loophole

---

## Theme 8: Europe Is Both Warning and Opportunity

File 2 makes this most explicit, but Files 1 and 3 also frame it:
- File 1: Simon's UK/European perspective; Kavelís as European bank consortium; Euro C's market cap tripled but still small; UK stablecoin bill passing
- File 2: "Europe is dead" — structural FMI risk; Amsterdam as innovation center; MiCA as first pan-EU crypto regulation
- File 3: US-centric but FX section raises cross-border stablecoin complexity for non-USD markets

---

## Theme 9: B2B Is the Real Battleground — Despite All the B2C Hype

All three files land on B2B as the near-term stablecoin/tokenization opportunity:
- File 1: Simon's original B2B prediction got a "B" grade; tier-2 bank settlement; on-chain lending for FX alternatives
- File 2: SAP enterprise use case; 24/7 institutional trading; AI agentic trading (B2B by nature)
- File 3: "Most of that B2B, most of that cross-border but $10 trillion in growing"; B2B programmability (smart contracts, conditional payments, data with payments); "why do checks still exist in B2B?"

---

## Theme 10: The "Stablecoin Linked Card" Beats "Pay With Stablecoin" — For Now

Only explicit in File 1, but implied across all three:
- File 1: Kai's Visa data — card volumes growing faster than direct merchant acceptance; Shopify's $600K total as cautionary data
- File 3: "Push to card" as FX solution; Visa debit in front of stablecoin at POS
- File 2: Implicit in the settlement focus; on-chain settlement but card infrastructure still on top

---

## KEY QUOTES ACROSS ALL THREE FILES FOR ADVERTISING / CONTENT USE

**On trajectory:**
> "Visa stablecoin settlement is about $3.5 billion annualized volume... That's up from $250 million in May... I expect by the end of next year Visa stablecoin settlement will be over $100 billion annualized... and will be the fastest growing part of Visa's business." — Rob Haddock, File 1

**On loyalty:**
> "It's estimated that there's nearly a trillion dollars of unused point liability trapped on corporate balance sheets. When you look at the reserves that would make loyalty points as a currency the third largest currency in the world behind the dollar and the euro." — Tyler Mayius, File 1

**On inevitability:**
> "The train has left the station and there is just no way to put the genie back in the bottle." — Rob Haddock, File 1

**On stablecoins as money:**
> "Stable coins are like better cash. They're instant. They're 24/7. They're global cash that I can stick in a teleporter and they can show up at the other side of the world." — Simon Taylor, File 1

**On Europe:**
> "Europe is dead. That's my conclusion. Everything has to go through America. DTCC takes it all." — Michael (360X), File 2

**On 24/7:**
> "The only reason we're doing tokenization is because of 24/7 trading." — Michael (360X), File 2

**On the FMI:**
> "The FMI will be based in the US." — Michael (360X), File 2

**On the stablecoin sandwich:**
> "You may go from either a traditional deposit or a tokenized deposit. You transfer it into a stable coin to do the money movement around the world cuz it's a lot more interoperable. At the receiving end it's again moved back either into regular deposit fiat or tokenized deposit. That's what we call a stable coin sandwich." — Elizabeth (Visa), File 3

**On full-reserve safety:**
> "Well, we have another one of those [SVB-type events]. They might actually flee to stable coins which are fully reserved, bankruptcy remote, fully segregated — arguably a safer place to have it than deposits." — Larry Pros (SRM), File 3

**On board accountability:**
> "You don't have to have a stable coin offering. You don't have to have a solution. You have to have had thought about it... Because if your board, your investors ask you why or why you didn't do something with stable coins in two years from now, you better have an answer. Because it may be dependent on whether or not you're still in business." — Larry Pros (SRM), File 3

**On yield:**
> "At the end of the day, I think yield finds a way. I think that's a bad argument tried to be chasing down. I'm not sure the banking industry is really going to win the yield question." — Larry Pros (SRM), File 3

**On the scale of B2B:**
> "About $10 trillion of it associated with true payment activity. Most of that B2B, most of that cross-border, but $10 trillion in growing is nothing to sneeze at." — Larry Pros (SRM), File 3

---
## BATCH 5
---
# Video Script Synthesis — Partial Set 5
## Files: Settlement in Card Networks | Distribution Interoperability | Cash Legs | Euros Onchain

---

# FILE 1: STABLECOIN SETTLEMENT IN CARD NETWORKS VIDEO SCRIPT

## 1. OVERVIEW
**Format:** Conference panel discussion — live audience event
**Estimated Length:** ~43 minutes (timestamp 0:03–42:30)
**Style:** Practitioner roundtable with spontaneous, conversational dialogue; moderator-driven with audience Q&A at end; includes humor, self-deprecation, and real-time banter between colleagues
**Audience:** Industry insiders — payments professionals, crypto entrepreneurs, fintech builders; not a retail/consumer audience. Everyone in the room is assumed to know what a stable coin is.

---

## 2. SPEAKERS & SEGMENTS

**Dante Reminik** — Moderator. Frames the panel as covering "probably one of the use cases that has the highest levels of PMF out of any use case in stable coins." Sets tone as excited/informal.

**Malcolm Cart** — Western Union. Describes WU as "really small company about 175 years old" (self-deprecating). Three main WU use cases: (1) own stablecoin USDPT for liquidity management with agents, (2) digital asset network for on/off ramping via 500,000 global agents, (3) imminent launch of a "stable card" with Visa. Most focused on treasury economics, capital efficiency, and last-mile cash-out challenges. Takes a "3-to-5 year journey" view of timeline.

**Ahmed Zifsaf** — Head of Crypto Partnerships, Global Payments (formerly WorldPay). Positions Global Payments as "the largest globally merchant acquirer payment service provider" doing "$4 trillion in global payments volume." Self-described "protector of the untrustworthy." Agnostic approach — will not launch own stablecoin or wallet. Sees stablecoins as "just an addition to already the fragmentation that we already deal with." Notes that the trickle-down effects from settlement efficiency improvements are "almost immediate" from the acquirer vantage point.

**Brian** — Payments and Partnerships, Polygon; former Visa Crypto team. Was there when stablecoin settlement "went from $50 million in run rate when I was there to now over five billion." Key argument: enterprises need "one contract" not "three vendors." Full-stack or die ("full stack or die" — Polygon's CPO John Eaggan). Polygon acquired Sequence and CoinMe for "$a quarter of a billion dollars" to get on/off ramping + 35 money transmission licenses. Most entrepreneurial voice on panel.

**Pete** — Visa Crypto. Describes Visa as having "five billion Visa credentials throughout the world" and "$15 trillion in payment volume settlement" historically via "fed wire and swift." Visa now supports "five stable coins today across nine chains." Has "130 some odd programs around the globe" for crypto-linked cards. Key settlement innovation: 7-day settlement allows issuers to reduce collateral requirements. Most institutional/cautious voice.

**Segment Structure:**
- Introductions (0:03–6:03)
- How companies use stablecoins internally (6:03–15:00)
- First/last mile and on-ramp friction (15:00–22:52)
- Gaps and missing infrastructure (22:52–32:00)
- Chargebacks, fraud, finality (32:00–37:53)
- Timeline predictions speed round (37:53–42:30)

---

## 3. ALL KEY STATS & DATA

- Western Union: ~175 years old; 500,000 global agents; moves "$130 billion plus a year" in capital; launching stable card "later this month" (at time of recording)
- Global Payments: "$4 trillion in global payments volume"; supports "dozens of different currencies across 170 countries"; doing card acceptance for crypto since 2014
- Visa: "five billion Visa credentials"; "$15 trillion in payment volume settlement"; operates in "200 plus countries"; "15,000 banks" connected; supports "five stable coins today across nine chains"; "130 some odd programs" for crypto-linked cards worldwide; 175 million merchants accept Visa
- Polygon stablecoin settlement volume: went from "$50 million in run rate" to "over five billion" (Brian's tenure) — possibly now "over seven and a half"
- Polygon acquisitions: Sequence + CoinMe for "a quarter of a billion dollars"; now has "35 money transmission licenses"
- Bridge acquired by Stripe: cited as inflection moment for enterprise push
- Sling (Venmo with stable coins): expanded to "150 markets within two years"
- Collateral savings: "three to eight basis points" freed up when moving to 7-day settlement; money previously held can go to "six to 7%" ROI initiatives
- Airwallex (Jack Zang, CEO): spent "15 years building local on and off ramping in 100 plus markets"
- Timeline prediction: Ahmed — "early 2030s" for ubiquitous stablecoin acceptance; Malcolm — "3 to 5 year journey" for Western Union
- SoFi USD: cited as FDIC-insured tokenized deposit that can also be sent globally

---

## 4. CORE NARRATIVE ARCS

**Arc 1: The Back-End is Where the Money Is**
Stablecoins are not primarily a consumer-facing innovation in payments. The real innovation is back-end settlement efficiency. "When we're talking about settlement which is the topic today... historically that is done over banking rails." Visa, GlobalPayments, and Western Union all use stablecoins to improve their own treasury operations before any consumer ever touches them. "That is not a front-end consumer concern."

**Arc 2: Collateral Unlock — The Perverse Capital Trap**
"If you are more successful, you actually have to provide us more collateral. That's a perverse thing. So we're fixing that." 7-day settlement via stablecoin rails allows issuers to reduce collateral requirements with Visa, freeing 3–8 basis points. This cascades down to consumers over time, similar to how ACH rails enabled Chime to offer free accounts.

**Arc 3: First Mile / Last Mile Is Brutally Hard**
Everyone agrees on this. MCC 6051 (merchant category code for crypto purchases) causes "really, really low acceptance rates" for on-ramping with credit cards. This creates two separate ecosystems — onchain and off-chain. The goal: make that "line between onchain and offchain blurred, invisible, gone."

**Arc 4: Full Stack or Die**
Enterprises don't want three vendors. "When I was at Visa, I saw it very much plainly. A lot of these enterprises, you know, don't want three vendors in order to get into this space. They need one contract." This drives Polygon's $250M acquisition strategy. Aggregation and vertical integration are key competitive dynamics.

**Arc 5: Chargebacks Are Solvable, Not Blocking**
The "people who hate stable coins" argument about chargebacks is addressed head-on. Western Union already works with assets (cash) where finality is instant and irreversible. Stablecoins actually add tools: "you have the ability to track it through chain. You can freeze it, you can pause it, you can recheck it." Stable coin-linked cards get the best of both worlds — stablecoin efficiency on the back end + Visa's chargeback infrastructure on top.

**Arc 6: Grandma Still Wants Cash**
Despite all efficiency gains, "grandma wants cash. She's going to need it. She doesn't know what a stable coin is." The cash-out / off-ramp problem — especially in developing markets — is the final unresolved mile. Bolivia agents must swap stablecoins, but "the second they start flipping and swapping into all the other stable coins, you lose the trail."

---

## 5. POSITIONING PILLARS

- **"The game is scale"** — Malcolm's framing: infrastructure is built, execution is the challenge
- **"Full stack or die"** — Polygon/Brian's thesis about enterprise needs
- **"Money at the speed of the internet"** — Brian's consumer pitch ("when my mom asked what I do")
- **Stablecoins as plumbing, not product** — Shared framing across all speakers; Pete: "we've looked at stable coins as a plumbing layer to make that more efficient"
- **Inevitable, not optional** — "It's an inevitable... Who wouldn't want global accessibility?"
- **Consumer doesn't care, and that's fine** — "Most of the customers in Western Union... they don't give two monkeys"
- **B2B and enterprise drive it first, consumers follow**

---

## 6. HOOKS & OPENINGS

- "In my opinion, this is probably one of the use cases that has the highest levels of PMF out of any use case in stable coins" — Dante Reminik, opening
- "When I was there [stablecoin settlement volume went] from $50 million in run rate... to now over five billion" — Brian
- "You actually already accept Bitcoin. You already accept stable coins" — Pete's twist on the merchant question
- "If you are more successful, you actually have to provide us more collateral. That's a perverse thing. So we're fixing that." — Pete on collateral
- "When my mom asked what I do, that's what I always say. I make money move at the speed of the internet." — Brian
- "Grandma wants cash. She's going to need it." — Malcolm

---

## 7. RECURRING PHRASES & LANGUAGE

- "First mile and last mile is always the hardest" — repeated refrain
- "Trickle down [effect]" — used by Brian and Malcolm to describe how settlement savings reach consumers
- "Plumbing" / "plumbing layer" — Pete's preferred metaphor for back-end stablecoin use
- "Full stack or die" — Polygon CPO's phrase, repeated by Brian
- "High on our own supply" — Ahmed's warning about industry echo chambers
- "The real payments world is so much bigger than what stable coins represent" — Ahmed grounding the discussion
- "T+0" / "T+1" / "T+2" — settlement timing shorthand used throughout
- "Seven days a week, 247, 365" — recurring phrase for 24/7 settlement capability
- "Three to five year journey" — Malcolm's timeline framing
- "Crypto bros or girls" — Malcolm's dismissive framing of retail holders (used twice)
- "Stable coin neo banks" — Ahmed's phrase for new entrants using cheap rails
- "Earn yield" — Western Union moving from "negative capital to a plus capital cost"
- "North Korean" — cited twice as example of fraud actors (cash AND crypto)

**Analogies:**
- ACH/Chime analogy: "Companies like Chime came in and said, 'We're going to offer free accounts'... same thing with stable coins now"
- Zelle/Venmo: "You don't use a credit card to get Zelle money. You don't use a credit card to get Venmo money"
- "Zero dollar balance account" — Pete's description of Visa's net settlement position

---

## 8. COMPANIES / PROTOCOLS MENTIONED

- **Western Union** — 175 years old; USDPT stablecoin; 500k agents; stable card launch
- **Visa** — 5B credentials; $15T volume; stablecoin settlement pioneer; crypto card programs
- **Global Payments / WorldPay** — $4T volume; agnostic infrastructure; crypto acceptance since 2014
- **Polygon** — full-stack infra; acquired Sequence + CoinMe; 35 MTLs
- **Stripe / Bridge** — Bridge acquisition cited as enterprise signal
- **Airwallex** — CEO Jack Zang cited as skeptic who "did it the hard way"
- **Sling** — "Venmo with stable coins on the back end" expanding to 150 markets in 2 years
- **SoFi / SoFi USD** — FDIC-insured tokenized deposit, cited as model for future
- **USDC** — mentioned as widely-held but still carries risk concerns for enterprises
- **Walgreens** — cited for ATM on-ramp capability
- **Chime** — used as ACH analogy

---

## 9. USE CASES HIGHLIGHTED

1. **Treasury / liquidity management between issuer and agents** — Western Union USDPT; "gone from negative capital to plus capital cost"
2. **7-day settlement between issuers and Visa** — "we already have plenty of issuers that settle obligations to us every day of the week"
3. **Stable coin-linked debit/credit cards** — spending down crypto/stablecoin balances at 175M Visa merchants
4. **Remittances to developing markets** — sending to agents in Bolivia, Argentina, Turkey; "wealth preservation" for consumers in high-inflation markets
5. **On-ramping via physical stores / ATMs** — WU agents as cash-in entry points; Walgreens ATMs
6. **Global expansion for fintechs** — Sling entering 150 markets in 2 years using stablecoin rails
7. **Machine-to-machine payments** — Ahmed flags this as future frontier for novel settlement mechanisms
8. **Stable card with stablecoin balance as "true balance"** — card without going through agent network; instant availability

---

## 10. TONE & STYLE

Highly conversational, collegial, peer-to-peer. Lots of inside jokes ("Brian is also my former manager"), visible camaraderie, competitive gentle ribbing ("Pete, you're getting beat up here"). Moderator Dante is enthusiastic and pushy, pushing for concrete answers. Speakers are direct, opinionated, and use plain language over jargon. Humor is constant but never undermines substance. Strong practitioner credibility — everyone has done deals, built products, faced regulatory barriers firsthand. Not a hype panel; honest about challenges (MCC 6051, last mile, regulation). Speed round at end forces quotable predictions.

---
---

# FILE 2: STABLECOIN DISTRIBUTION INTEROPERABILITY VIDEO SCRIPT

## 1. OVERVIEW
**Format:** Conference panel discussion — large stage setting ("very big stage")
**Estimated Length:** ~46 minutes (timestamp 0:03–46:22)
**Style:** More philosophical and technical than File 1; European flavor; moderator (unnamed "Peter" / "you" voice — likely French/US-based, mentions living in US) facilitates structured turn-taking; ends with audience Q&A
**Audience:** Mix of blockchain builders, institutional finance, and infrastructure players. More technically sophisticated than File 1; assumes knowledge of DeFi, KYC/AML, EVM, atomic swaps, privacy tooling.

---

## 2. SPEAKERS & SEGMENTS

**Moderator** — French, living in US. Asks for "a specific use case, an example, not something theoretical" upfront. Explicitly frames the evolution: "We don't talk about tech as much as we used to... We're more on that phase where we actually need coordination."

**Imo (Emma)** — German institutional banking perspective. Focused on interoperability as an infrastructure gap: "every hop separate KYC, separate AML... reconciliation... all of that stuff is very bespoke for every counterparty." Key point: "the asset movement itself... it's been largely solved by now. It's all the stuff around it that is still like non-existent."

**Kalis / Jan** — CEO, Kalis (Kibalis). Consortium of 12 European banks; registered as e-money institute in Amsterdam; launched September 2024 (Jan joined 3 weeks prior to recording). Key thesis: "stable coins are money" — the interoperability question is a "discussion about the uniqueness of money." Argues the equation will flip: rather than asking how to integrate wallets with credit cards, people will ask "can my employer pay me in stable coins." Ethereum mainnet from day one. Wants to collaborate with ECB on wholesale CBDC access as reserve backing.

**Tony McLolin** — CEO, Ubix; deep institutional payments background (worked in banks "for a long period of time"). Most opinionated/provocative voice. Key thesis: **acceptance infrastructure must be mutualized**. "The acceptance infrastructure needs to be mutualized. This is the unlock." Hates cards on the front end of stablecoins: "It's an abomination." Proposes open-source EMV co-equivalent kernel for point-of-sale to accept stablecoin natively. His company: "My company is the new Visa for tokenized money." (Also appears in File 4.)

**Ivan** — Described as someone who "lives on chain." DeFi native perspective. Argues: "Issuance is a very sexy business but you actually have to pay for growth." The regulatory moat around issuance is "already outdated." Focused on user acquisition economics. Notes ETH wins long-term because "no single party can own it." Raised confidentiality/privacy as the superseding priority: "confidential privacy is like kind of supersedes all of that."

**Audience Q1 (Kio Ernesto):** Asks about atomic swaps for institutionals — why no one offers it, how to solve it.
**Audience Q2 (unnamed):** Asks about public goods funding declining and what institutions can do to support open source.

**Segment Structure:**
- Defining interoperability with real use cases (0:03–4:07)
- Kalis model and European bank consortium (4:07–13:33)
- Acceptance vs. issuance as the key unlock (9:18–15:00)
- Reserve interoperability and wholesale CBDC (15:00–17:18)
- The shift from tech to coordination (17:18–18:35)
- Workshop: what would panelists work on together? EMV kernel / open source (18:35–27:09)
- Missing pieces: atomic DVP, B2B remittance info, confirmation of payee, privacy (27:09–35:50)
- Builders vs. institutions disconnect (35:50–41:00)
- Audience Q&A (40:41–46:22)

---

## 3. ALL KEY STATS & DATA

- Kalis: 12 founding banks; open consortium expecting "quite a few more banks" after summer launch; Jan joined 3 weeks before panel recording; 2-year setup process; Amsterdam-based EMI
- "200 million US customers" across the 12 banks in Kalis consortium
- Vero (new app): mentioned as movement toward account-based payments not yet supporting stablecoins
- Lightning Network: El Salvador example — "I can pay my coffee via lightning"
- ERC 80004: Marco de Rosi from Consensus building "agentic ID and reputation standard"
- No direct financial figures cited (this panel is more structural/conceptual)
- EMV Co (payment kernel standard): formed in late 1990s as consortium; near-failed before achieving success
- Free Software Foundation: moderator notes it was founded around "1980 something... or 85"

---

## 4. CORE NARRATIVE ARCS

**Arc 1: Issuance Is Solved; Acceptance Is the Bottleneck**
"The exam question for ubiquity and interoperability is really about acceptance... We're in a bizarre place in the development of tokenized money where everyone is focused on issuance. Now acceptance is the unlock that enables issuance and enables a pluralistic market structure." Tony delivers this as the panel's central thesis. Analogized to POS machines in card payments: "If you don't have a POS device, you cannot accept a card payment. If you don't have a wallet, you cannot accept a stablecoin payment."

**Arc 2: The Tech is Solved; Coordination is the Problem**
Multiple speakers converge on this: "In every kind of transaction... any sort of problem which could potentially be solved by tech, it's solved already. It's really mostly like a legal question... how we standardize transactions and our business flow." The moderator explicitly frames this as the evolution from 2 years ago when the conversation was all blockchain/chain selection.

**Arc 3: Mutualized Acceptance Network as the Missing Architecture**
Tony's most forceful contribution: "The acceptance infrastructure needs to be mutualized... every bank and fintech on the planet offers wallets... connected to multiple chains. Any token can be transacted across that infrastructure." This must be multi-chain, not ETH-only. Open source is the right model. The EMV Co analogy: "They were about to fail and it's because they create that consortium... and we now have credit card everywhere in the world."

**Arc 4: Cards on Front End of Stablecoins Are an Abomination**
Tony's controversial position: crypto cards co-opt the general purpose token into legacy rails. "Let's say we are out for a nice meal... we come to the paying of the bill... the restaurant hasn't been paid. What's happened is that the card has obtained an authorization and then the restaurant pays 2 and a half% sales tax... and then the payment two days later." If stablecoins can be accepted natively at POS, "the restaurant has been paid and hopefully doesn't have to pay 2 and a half%."

**Arc 5: The Blockchain Native POS Kernel**
Tony's proposed common project: "A token, a blockchain native kernel in the point of sale devices that can accept a wallet-to-wallet peer-to-peer transfer... a new kernel in every point of sale on the planet that accepts stable coin native payments without going through cards." Kalis agrees and sees this as part of their mandate given 200M bank customers as leverage.

**Arc 6: Reserve Interoperability Is Also Missing**
Imo raises an overlooked dimension: "Whenever we offramp between tokens there's actually reserves also flowing which we still need to make also interoperable... different reserve banks... for selected tokens you need to have like this high liquidity that you have direct access for a swap also on the liability side." Kalis response: wholesale CBDC access (ECB's AIA program) could solve this by providing deep institutional liquidity against central bank.

**Arc 7: B2B Missing Pieces — Remittance Info, Confirmation of Payee**
Tony identifies two critical gaps from traditional payments that stablecoins haven't solved: (1) Extended remittance information — "You send me 20 invoices, I'm paying for 10... I send you the stable coin payment. How do you know which 10 invoices I'm paying for? Best case you get some sort of memo field." (2) Confirmation of payee — "Can I check before I make the payment that the wallet is owned by [the right party]?"

---

## 5. POSITIONING PILLARS

- **"The acceptance infrastructure needs to be mutualized"** — Tony's core thesis
- **"Every bank and fintech on the planet offers a wallet"** — the target state for the ecosystem
- **"It will resolve on ETH because no single party can own it"** — Ivan's ETH thesis
- **"We're amazing at building tech and pretty poor at building product"** — Ivan on the ecosystem's PMF gap
- **"It takes a finite amount of time that begins when we start the initiative"** — Tony on open-source POS kernel
- **"We can't think that Kalis is going to dominate this"** — Jan on pluralistic market structure
- **"The conversation between builders and institutions is where the value is going to come out of"** — Jan's conclusion

---

## 6. HOOKS & OPENINGS

- "How's everyone? That's a very big stage." [snorts] — moderator opening
- "The asset movement itself... it's been largely solved by now. It's all the stuff around it that is still like non-existent." — Imo, establishing the thesis
- "There's a bizarre place in the development of tokenized money where everyone is focused on issuance. Now acceptance is the unlock." — Tony
- "The acceptance infrastructure needs to be mutualized. This is the unlock." — Tony, crescendo moment
- "It's an abomination." — Tony on cards as front-end for stablecoins
- "We're at the edge of a great big ocean and we're fighting over one shrimp. It's ridiculous." — Tony on Canton vs ZK Sync Twitter war
- "We're amazing at building tech and pretty poor at building product." — Ivan

---

## 7. RECURRING PHRASES & LANGUAGE

- "Exam question" — Tony's framing for what the industry must answer ("ubiquity and interoperability")
- "Every bank and fintech on the planet" — repeated multiple times as the target state
- "Mutualized" — Tony's key word for acceptance infrastructure
- "Equation will flip" — Jan's phrase for when onchain becomes primary (not on-ramp/off-ramp)
- "Space-time" — Tony's philosophical framing ("a point in space-time that we can all work towards")
- "The fun stuff" — sarcastic shorthand for KYC/AML/reconciliation complexity
- "Zero sum game" — Jan dismissing closed-loop consortium thinking
- "Walking and chewing gum" — Tony on doing issuance AND mutualized acceptance simultaneously
- "Talking your own book" — moderator/Ivan acknowledging self-interest in arguments
- "Positive network effects" — Tony on why common projects benefit everyone
- "Public goods" — audience member's term for open-source shared infrastructure
- "Category error" — Tony's strong word for mistaken issuance-only mindset
- "General purpose token being co-opted by legacy payment rails" — Tony on card-wrapped stablecoins

**Analogies & References:**
- EMV Co (late 1990s): the model for open-source payment kernel consortium
- Lightning Network / El Salvador coffee payment: used as counter-example for single-leg settlement
- Atomic swaps in DeFi: cited as already working; needs institutional implementation
- Bitcoin: "Bitcoin was not developed from scratch. They basically put together lots of different solutions that were already there."
- Canton vs ZK Sync Twitter feud: cited as example of tribal rivalry while 20,000 banks remain off-chain

---

## 8. COMPANIES / PROTOCOLS MENTIONED

- **Kalis (Kibalis)** — 12-bank European e-money institute; Amsterdam; Ethereum mainnet; open consortium
- **Ubix (Tony McLolin)** — "New Visa for tokenized money"; clearing system for tokenized money
- **ING, Uni Credit, BBBA (BBVA), BNP Paribas** — named as Kalis founding banks
- **Monerium** — European euro stablecoin issuer; Kalis considering interoperability
- **Ethereum Foundation** — Kalis co-developing ERC standards; mentioned as collaboration target
- **Consensus / Marco de Rosi** — building ERC 80004 for agentic ID/reputation
- **Curve, Uniswap** — cited as needing peg stability requiring multiple issuers
- **ECB** — wholesale CBDC (AIA program); "give access to European issuers to AIA"
- **Canton, ZK Sync** — Twitter feud cited as example of counter-productive rivalry
- **Open Zeppelin** — Kalis' smart contract foundation; "nothing you know tricky or weird"
- **Vero** — new account payments app moving away from cards; not yet supporting stablecoins
- **Deutsche Bank, Raiffeisen Bank, Danska Bank** — cited as Kalis consortium members / analogy banks

---

## 9. USE CASES HIGHLIGHTED

1. **Cross-border payment from Germany to Japan** — the foundational use case for interoperability discussion
2. **Agentic payments / AI-agent transactions** — Jan's "equation flip" scenario
3. **Accessing tokenized money market funds** — "Can my employer pay me in stable coins so I can use this at Bipa to access a tokenized money market fund"
4. **B2B invoice payments** — Tony's red wine example: 20 invoices, 10 paid; needs extended remittance info
5. **Point-of-sale native stablecoin payment** — restaurant scenario; goal is instant payment without card rails
6. **Coffee via Lightning** — El Salvador POS example for single-leg settlement
7. **Atomic DVP (delivery vs. payment)** — institutional settlement without settlement risk
8. **Smart bonds / smart derivatives** — mentioned as ERC activity from Kalis bank consortium members

---

## 10. TONE & STYLE

Intellectual and architectural. More European in sensibility — regulatory frameworks, consortium-building, philosophical first principles. Tony McLolin is the dominant intellectual voice, making sweeping historical analogies (store cards to credit cards, 19th century checks to 21st century tokens). Jan is pragmatic and institutional. Ivan is DeFi native and direct. Imo is technically precise. Moderator is facilitative but opinionated, explicitly noting the shift from "tech talk" to "coordination talk" as a sign of ecosystem maturity. Panel feels more like a working group than a promotional panel — participants are actively workshopping ideas together, inviting each other's critiques. Less humor than File 1 but genuine intellectual energy. The "abomination" comment and the "fighting over one shrimp" line are the most quotable moments.

---
---

# FILE 3: STABLECOIN CASH LEGS VIDEO SCRIPT

## 1. OVERVIEW
**Format:** Conference panel discussion — "Stable Summit" branding at end
**Estimated Length:** ~41 minutes (timestamps 0:03–41:00)
**Style:** Moderator-facilitated discussion with strong structured turns; more institutional/Wall Street flavor than other panels; blends TradFi credentialing (DTCC, Fidelity) with crypto-native perspectives (Spark/DeFi, Superstate)
**Audience:** Asset managers, institutional investors, DeFi protocols, infrastructure builders. Knowledge of tokenization, T-bills, DeFi lending, RWAs assumed.

---

## 2. SPEAKERS & SEGMENTS

**Moderator** — Unnamed; investment-focused lens; phrases questions around "bottlenecks," "best format," "cash leg" as infrastructure problem.

**Monet Supply** — Spark Protocol. "DeFi native" background. Spark pulled "billions of dollars of stable coins" and held "over a billion dollars of tokenized money market funds." Previously: "permissionless lending of DAI against permissionless collateral assets like ETH." Changed view: "I've warmed up to tokenized assets... every asset needs to be permissionless... if it's backed off-chain, it's not real." Now bullish on robustness of stablecoins and new RWA classes.

**Simon** — Superstate. $1.3 billion AUM reached with T-bill fund (USB) and crypto carry fund (youCC); 300 institutional clients; integrated across "Salana and Ethereum and Bloom and now Base." Now pivoting to Fund OS — technology platform for asset managers. Passed $1B fund to Invesco, basis trading fund to Bitwise; Coinbase Asset Management using platform. Former trading desk (12 years). Most practically entrepreneurial voice.

**Otto / Ottonino** — DTCC (Digital Treasury Clearing Corporation). "Embedded risk management director for digital assets." DTCC settles "quadrillions" (not just trillions). Most institutional/risk-management voice. Published white paper with Clearstream and Euroclear on precision in programmable asset design. Key message: "Programmability of assets... standardize... risk is shifted to an earlier stage, not eliminated."

**Jasmine Gia** — Head of Tokenization Ecosystem, Fidelity Digital Asset Management. Asset manager perspective. Focused on "adding crypto to accessible fund structures" and taking investment funds onchain. Uses cooking analogy: "I'm an asset manager. I want to cook a meal on chain. However, I don't have enough ingredients also today to make a decent meal." Changed view: "I used to be very aversive about open source but I've learned that is the only way to really test whether your programmability functions or not."

**Segment Structure:**
- Context setting: $30B RWAs onchain; $5.5T forecast by 2030; 1.9T stablecoins by 2030 (0:03–1:27)
- Quick intros — problem each is solving (1:27–3:20)
- Superstate's evolution: from fund manager to Fund OS platform (3:20–6:05)
- The cash leg question: stable coin vs. tokenized deposit vs. tokenized MMF (6:05–18:00)
- Atomic settlement, finality, and netting (18:00–28:05)
- DeFi hack risk, key management, security (28:05–37:00)
- DTCC's vision — 24/7, interoperability, asset efficiency (37:00–38:30)
- What has changed in your opinion over last 2 years (38:30–41:00)

---

## 3. ALL KEY STATS & DATA

- **Current state:** ~$30 billion real-world assets onchain at time of recording
- **Citibank forecast:** $5.5 trillion RWAs by 2030
- **Stablecoin forecast:** 1.9 trillion stablecoins in 2030
- **Superstate AUM:** $1.3 billion; 300 institutional clients
- **Superstate fund composition:** USB T-bill fund is "95% invested in US government debt"; NAV "ticks up by the second"
- **Spark holdings:** "pulled billions of dollars of stable coins"; held "over a billion dollars of tokenized money market funds"
- **USDC near-insolvency:** 2023 Silicon Valley Bank episode — "USDC was at like a pretty high risk of insolvency"
- **DTCC settlement volume:** "quadrillions" (not trillions; emphatic correction)
- **DTCC white paper:** published with Clearstream and Euroclear
- **DeFi hacks:** "hundreds of millions lost" in recent months; but losses "less and less resulting from code bugs... more just key management or custody issues"
- **Regulation:** GENIUS Act cited for stablecoin clarity; Clarity Act for market structure; "currently moving through legislation"
- **Superstate T-bill fund:** earn interest "every second you're in that fund"; can enter Saturday, exit Sunday and earn day and a half interest while markets closed
- **Tokenized treasury adoption:** "emerging market retail users" adopting because "they need US denominated assets; they want higher interest rate"
- **US users:** "less motivated because they have easier access to treasury assets"

---

## 4. CORE NARRATIVE ARCS

**Arc 1: $30B → $5.5T — The Gap Is Institutional Infrastructure**
The numbers point one direction. The constraint is not demand or technology but distribution infrastructure: "right now the rules and regulations are still pretty much tailored for a more centralized model." Tokenized treasury funds require issuers to onboard each user individually — no broker-dealer distribution layer exists onchain yet. "These frictions are not web three problems. However, these are the necessary web two adapters that we have to live with."

**Arc 2: The Three-Way Race — Stable Coin vs. Tokenized Deposit vs. Tokenized MMF**
Each has a different risk/return/liquidity profile. Jasmine's framing: "That question itself is misleading... A tokenized money market fund is a security. It's not money." It's a cash management investment, not a payment instrument. Stablecoins and tokenized deposits are form factors for money movement (liquidity, not yield). The three are complementary: tokenized MMFs can use stablecoins for in/out; stablecoins can use MMFs for reserves.

**Arc 3: Natively Issued vs. Wrapper — The Last Marathon Mile**
Simon's framework: "A wrapper and a native issue is great because it's 24/7 trading, DeFi integrated... But a wrapper still is at the behest of traditional market structure which comes down to timing. It comes down to fedwire timing." Native issuance allows you to enter/exit at 2am on a Saturday. Superstate's USB T-bill fund earns interest "every second you're in that fund."

**Arc 4: Atomic Settlement — Risk Shifted, Not Eliminated**
Otto's nuance: "The risk is shifted to an earlier stage... Right now the programmability of assets allows you to keep it standardized. Instead of having random events of risk or random events of where the security didn't settle because of human error, you have programmability that will standardize all that." Requires attention to smart contract design, audits. Published with Clearstream and Euroclear.

**Arc 5: Finality — Where Is the Book of Records?**
Jasmine: "The main limitation is finality... until regulation allows the blockchain to be the actual book of records, there's going to be all these limitations... we have to confide in where is it that the value that I'm accounting... is being reflected." Otto: "The asset doesn't depend on the rails anymore. The rails are in the asset... interoperability, liquidity become an attribute of the asset, not of the blockchain."

**Arc 6: DeFi Hacks Are Getting Better, But Key Management Remains Risk**
Monet: "Less and less of these losses are resulting from code bugs and like the actual smart contracts being faulty. It's more just key management or custody issues." Superstate's mitigant: permissioned "allowed list" — only KYC'd wallets can hold USB; transactions to non-whitelisted addresses "just get decayed." Residual risk: whitelisted user gets hacked, posts tokenized fund as collateral in DeFi lending, exfiltrates permissionless assets. Who bears the loss?

**Arc 7: The Brokerage Account Analogy**
Jasmine: "When you think about all of us holding a brokerage account, the cash in your brokerage account is actually in a money market fund automatically... it's like effortless. We want that to be in the wallet structure as well." The gap: no broker-dealer distribution layer onchain yet; issuers must onboard each user individually.

---

## 5. POSITIONING PILLARS

- **"Natively issued is better than wrapper"** — Simon's core thesis; wrapper is still gated by fedwire timing
- **"The rails are in the asset"** — Otto's paradigm shift: interoperability as asset attribute, not rail attribute
- **"Money at rest vs. money in motion"** — Jasmine's framing for stable coins vs. tokenized MMFs
- **"Competition is misleading"** — Jasmine: the three cash leg forms are synergistic, not competing
- **"Test test test"** — Jasmine's mantra, learned from open source; "In real estate it's location location location, I call it here test test"
- **"These are web two adapters we have to live with"** — Jasmine on current regulatory friction
- **"Permissionless with a permission layer on top"** — Simon's model for institutional DeFi

---

## 6. HOOKS & OPENINGS

- "There's roughly about 30 billion real world assets on chain. Citi recently reported that they're forecasting 5.5 trillion by 2030." — moderator, opening data blast
- "Our T-bill fund is 95% invested in US government debt. It has a NAV that ticks up by the second... you can go into it on a Saturday morning, come out on a Sunday afternoon and earn a day and a half's interest in US government debt when the markets have been closed." — Simon
- "Fortunately we have reached the quadrillions in the settlement in the clearing." — Otto's correction to "trillions" framing
- "I want to cook a meal on chain. However, I don't have enough ingredients also today to make a decent meal." — Jasmine's analogy
- "I came into the space originally just like really gung-ho, like every asset needs to be permissionless. Um you know if it's backed off-chain, it's not real." — Monet's confession of changed views
- "USDC was at like a pretty high risk of insolvency" — Silicon Valley Bank moment

---

## 7. RECURRING PHRASES & LANGUAGE

- "Cash leg" — the specific term used throughout for the settlement/payment side of tokenized asset transactions
- "Natively issued" vs. "wrapper model" — key product distinction, repeated multiple times
- "Money in motion" vs. "money at rest" — Jasmine's taxonomy
- "The rails are in the asset" — Otto's paradigm-shifting phrase
- "Atomic settlement" — repeated across all speakers as the ideal state
- "24/7, 365" — recurring benefit description
- "Intraday repo" — Simon's use case for T-bill fund velocity
- "T-bill fund" / "USB" — Superstate's product, used as practical example throughout
- "Allowed list" / "permissioned" — Simon's technical framing for Superstate's access control
- "Bug-free code" — Monet's emerging confidence; "growing confidence that we are going to be able to create bug-free code"
- "Human error" vs. "code error" — recurring frame for shifting risk types
- "DeFi wild west no rules situation" — Monet's phrase for old state
- "Web two adapters" — Jasmine on necessary friction
- "Finality" — single most repeated technical term; where settlement is recorded and considered binding

**Analogies:**
- Brokerage account cash → automatic money market fund: the target wallet UX
- Cooking a meal: tokenized asset composition; "not enough ingredients"
- UBS vs. Goldman Sachs trading desk: Simon's netting analogy; "pull the tapes, look at a Bloomberg and reverse the transaction"
- Marathon: "you've done like a good number of miles in the marathon" — native issuance as the final stretch
- Barbell strategy: Jasmine's flip from illiquid (real estate, collectibles) → liquid (stablecoins, treasuries) → back to private markets

---

## 8. COMPANIES / PROTOCOLS MENTIONED

- **Superstate** — Fund OS; USB T-bill fund; youCC crypto carry fund; 1.3B AUM; 300 institutional clients
- **Invesco** — using Superstate rails for T-bill fund
- **Bitwise** — using Superstate rails for basis trading fund
- **Coinbase Asset Management** — announced on Superstate platform
- **Spark Protocol** — DeFi-native lending; Monet Supply; formerly MakerDAO adjacent
- **DTCC** — quadrillions in settlement; embedded risk management director for digital assets
- **Fidelity Digital Asset Management** — Jasmine; tokenization ecosystem; ETP structures
- **Clearstream, Euroclear** — white paper co-authors with DTCC
- **Silicon Valley Bank** — 2023 near-collapse; USDC near-insolvency cited
- **USDC / Circle** — cited for SVB risk episode
- **GENIUS Act** — regulatory clarity for stablecoins
- **Clarity Act** — market structure regulation moving through legislation
- **Salana (Solana), Ethereum, Bloom, Base** — Superstate integration chains
- **CME** — used in Superstate's basis trading fund reference

---

## 9. USE CASES HIGHLIGHTED

1. **Intraday repo** — T-bill fund with second-by-second NAV; "huge implications for intraday repo for interest payments for velocity of money"
2. **24/7 fund access** — enter Saturday, exit Sunday, earn weekend interest on US government debt
3. **Tokenized equity natively issued** — "we can take any equity, any fund, any ETF and put them on chain within a couple of weeks"
4. **DeFi collateral** — tokenized MMFs as collateral in lending protocols; Monet describes billions held
5. **B2B settlement** — stablecoins as "more efficient, always-on equivalent of Fed Wire"
6. **Starbucks payment** — Simon's vision: pay and earn interest until payment lands; recipient earns interest from receipt
7. **Institutional cross-border trading** — counterparty relationships with people you don't know via real-time gross settlement
8. **Private market tokenization** — Jasmine's late flip: "maybe it is very interesting for private market as long as it's done right... price discovery mechanism that blockchain market can do is very valuable"
9. **Smart contract vault** — native portfolio management onchain; "asset managers to create native portfolio onchain"

---

## 10. TONE & STYLE

Institutional but accessible. Less humor than File 1; more structured intellectual exchange. Strong tension between TradFi credentialing (DTCC, Fidelity) and crypto-native perspective (Spark, Superstate) that generates productive friction. Otto brings risk-management gravitas. Monet is intellectually honest about evolving views. Simon is entrepreneurial and specific. Jasmine is strategic and vision-oriented. Moderator is technically sophisticated — uses terms like "atomic settlement," "cash leg," "finality" without definition. Notable moment of authenticity: Monet's admission of changed views on permissionless assets. Jasmine's changed view on open source. Both frame change as maturation, not reversal. This panel feels like a serious investment conference session.

---
---

# FILE 4: EUROS ONCHAIN VIDEO SCRIPT

## 1. OVERVIEW
**Format:** Conference panel discussion — at a Frankfurt-based event (likely Token 2049 Europe or similar); moderator on stage, one panelist remote (Patrick Hansen calling in due to "an emergency")
**Estimated Length:** ~41 minutes (timestamp 0:04–41:43)
**Panel Title:** "Euros on Chain — Roles, Use Cases and Guard Rails"
**Style:** Policy/geopolitical flavored; moderator Daniela Bubak (Head of BD and Ecosystem, Blockchain Bundesverband — German blockchain association) drives structured questions; more formal European conference style; includes audience applause at opening
**Audience:** European blockchain and fintech ecosystem; policymakers, bank representatives, DLT infrastructure builders; possibly some US observers. Most geopolitically charged panel of the four files.

---

## 2. SPEAKERS & SEGMENTS

**Daniela Bubak** — Moderator. Head of BD & Ecosystem, Blockchain Bundesverband (German blockchain association). Structured, formal; asks targeted policy questions. Frames the euro gap explicitly: "36% of onchain transactions are European but only 0.2% are in euros."

**Patrick Hansen** — Director EU Strategy and Policy, Circle. Remote participant (called in). Most policy-expert voice. Circle is "the largest regulated stablecoin issuer in the world." Issues USDC, Euro C (largest euro stablecoin), and USYC (largest tokenized money market fund). Notes EuroC has "grown 10x since our Mika announcement one and a half years ago." Pushes bottom-up adoption thesis vs. top-down regulatory mandates. Warns against "guard rails around foreign currency stable coins." Pro-integration with global liquidity rather than Euro-fortress approach.

**Tony McLolin** — CEO, Ubix. Same speaker as File 2; clearest articulation of "new Visa for tokenized money" thesis. Also appears in File 2. Here he extends the negotiable instrument / check analogy. "Stable coins can be processed exactly like checks. You should be able to take a stable coin to your bank and deposit it into your bank account directly like a check." Makes the "16,000 card issuers and zero fragmentation" argument. Most quotable on euro fragmentation being a false fear.

**Alexander Bunga** — Senior Adviser, VIA Science. US-based perspective. VIA Science originally built military-grade data security for US Navy/US Air Force; recently integrated stablecoin payments with Circle as first partner. Working on Stellar. Most geopolitically provocative voice: US is using stablecoins as geostrategic tool; Europe is lagging strategically; China has already built blockchain-based payment rails (references Forbes article on China's system with "trillions of transactions of yuan every day"). Mentions autonomous vehicle payments as use case. Backed by Borch and BMW.

**Yan** — CEO, Kalis. Same company as File 2 (Jan/Yan = same person). Here gives clearest articulation of Kalis' 12-bank consortium (ING, Uni Credit, BBVA, BNP Paribas named). Pushes back gently on Alexander's bearish Europe view: "I'm definitely less bearish on Europe than you are." Notes euro makes up "20 to 25% of global cross-border payments, global reserves, bond issuance globally but in the stable coin space is 0.2%." The gap is the strategic opportunity.

**Segment Structure:**
- Do we need euros on chain? (0:04–9:19)
- Euro stable coins as settlement asset for tokenized financial markets (9:19–12:08)
- Fragmentation: false fear and the credit card analogy (12:08–16:10)
- Stable coins as negotiable instruments; checks analogy (16:10–24:37)
- Infrastructure: what still needs to happen (24:00–29:15)
- Adoption: NGOs, AI agents, geopolitical use cases (29:15–33:00)
- Digital sovereignty — US strategy vs. European approach (33:00–40:20)
- Patrick: bottom-up adoption, EuroC growth (40:20–41:43)

---

## 3. ALL KEY STATS & DATA

- **European stablecoin transaction share:** 36% of onchain stablecoin transactions are by Europeans
- **Euro stablecoin share:** only **0.2%** of onchain transactions are in euros (vs. 36% user share)
- **Euro's fiat role:** 20–25% of global cross-border payments; similar share of global reserves; similar of bond issuance globally
- **EuroC growth:** "grown 10x since our MICA announcement one and a half years ago"
- **MICA:** 20+ euro stablecoin issuers licensed under MICA framework
- **China:** "Trillions of transactions of yuan every day" on blockchain payment system; WeChat Pay backbone cross-border payments on blockchain (Forbes article cited)
- **Kalis consortium:** 12 founding banks; includes ING, Uni Credit, BBVA, BNP Paribas; open consortium
- **VIA Science:** First partner is Circle; working on Stellar; backed by Borch and BMW
- **Haiti pilot:** VIA Science paying mothers in need and staff via stablecoins; mentioned as real adoption in emerging markets
- **Ubix claim:** "16,000 card issuers" today with "zero fragmentation" — historical analogy for stable coin market
- **EU ID Wallet:** mentioned as integration target for in-car payment use case
- **Alexander's US military claim:** "300 plus [military] bases" globally; US government exploring stablecoin payments for these
- **Circle stable coins:** USDC (largest regulated dollar stablecoin); EuroC (largest regulated euro stablecoin); USYC (largest tokenized MMF)

---

## 4. CORE NARRATIVE ARCS

**Arc 1: Europe Has a 36% → 0.2% Problem**
The central empirical fact of the panel. Europeans are 36% of onchain stablecoin transactions but only 0.2% are in euros. "There's obviously a need." This creates the fundamental thesis: the euro must come onchain or Europeans transact in dollars by default. Tony: "Our sovereign currencies have to occupy the spaces that people want to do business... If the regulated instruments are not provided on these venues, then don't be surprised if someone transacts in Tether."

**Arc 2: A Blockchain Is a Venue for Commerce — We Must Show Up**
Tony's elegant first-principles argument: "A blockchain is a venue for commerce in the same way that a high street or a physical marketplace is a venue for commerce. And if people who transact on those venues don't have access to regulated money, then they will still transact, but they will transact in unregulated money." The regulatory abdication created a vacuum filled by Tether.

**Arc 3: Fragmentation Is a False Fear — The Credit Card Analogy**
Tony challenges conventional wisdom: "16,000 card issuers... and there is zero fragmentation. You can go with your Deutsche Bank credit card to New York and shop in Macy's and Macy's doesn't give a damn about Deutsche Bank's balance sheet." The analogy: late 1960s observers predicted dollar-credit-card power law; they were wrong. We're making the same error about stablecoins. "There will be many issuers of tokenized money... and zero fragmentation."

**Arc 4: Stablecoins Should Work Like Checks**
Tony's most novel historical frame: "You should be able to take a stable coin to your bank and deposit it into your bank account directly like a check. When that happens, the stable coin market structure gets much better." The check has many issuers, many redemption agents, 19th century infrastructure equivalent of 21st century stablecoin. The enabling mechanism: every bank and fintech offers a wallet that can accept any stablecoin and convert it to euros. Yan's confirmation: this is exactly what Kalis is building.

**Arc 5: US Has a Geostrategic Stablecoin Plan; Europe Doesn't**
Alexander's provocative thesis: "The current administration has realized that there's geostrategic power to stable coins... stable coins are basically an extension of US dollars." US is exploring: (1) military bases (300+) transitioning from cash to stablecoins — instant global adoption; (2) US Treasury humanitarian aid via stablecoins; (3) debt refinancing via Circle's Treasury purchases. Europe is "still discussing the regulatory framework." China has already built at scale. "The Americans are saying 'how can we make use cases' and here the discussion is often 'what's the regulatory correct framework.'"

**Arc 6: Tony's Three-Part European Strategy**
Tony's actionable framework: (1) Have 5,000 European banks and fintechs offer wallets to catch foreign stablecoins and convert them into euros, moving value from American to European balance sheets; (2) Create universal wallet acceptance network in Europe; (3) Build global acceptance for euro stable coins using existing Deutsche Bank correspondent banking relationships in 100+ countries. "If we want to win the stable coin game, three components."

**Arc 7: Bottom-Up, Not Top-Down Adoption**
Patrick's counter to European top-down instincts: "The most important ingredient to stable coin growth and adoption... is usage and liquidity... something that requires really bottom-up nitty-gritty work with the players that actually use and transact with stable coins today... Even if you look at the largest financial institutions, they want to build rails for the stable coins that are actually being used." EuroC strategy: go where users are, build liquidity in DeFi platforms and CEX exchanges, let institutional adoption follow. "EuroC has grown 10x."

---

## 5. POSITIONING PILLARS

- **"Sovereign currencies must occupy venues for commerce"** — Tony's obligation argument
- **"16,000 issuers, zero fragmentation"** — the credit card historical proof point
- **"My company is the new Visa for tokenized money"** — Tony on Ubix
- **"Stable coins should work like checks"** — Tony's historical analogy
- **"0.2% is the scandal"** — implicit framing of euro's absence from onchain activity
- **"Top-down doesn't work; build from the bottom up"** — Patrick's strategic advice for EuroC
- **"America has a very clear plan"** — Alexander's challenge to European complacency
- **"We hope America moves and then Europe will move too"** — Alexander quoting European conference sentiment (dismissively)
- **"That's not a go-to-market approach"** — Alexander on European wait-and-see strategy

---

## 6. HOOKS & OPENINGS

- "Onchain currencies always raise a lot of fundamental questions about utility, about governance, and about their general structure." — announcer introduction
- "Do we need euros on chain actually?" — Daniela's first question; elegant in its simplicity
- "If the regulated instruments are not provided on these venues, then don't be surprised if someone transacts in Tether." — Tony
- "36% of onchain transactions are European but only 0.2% are in euros." — the central statistic
- "16,000 card issuers and there is zero fragmentation." — Tony's counterintuitive historical proof
- "You should be able to take a stable coin to your bank and deposit it into your bank account directly like a check." — Tony
- "America has a very clear plan and I think once they start transacting there'll be surprises on European side how fast it will happen." — Alexander

---

## 7. RECURRING PHRASES & LANGUAGE

- "Venues for commerce" — Tony's repeated frame for blockchains (high street, marketplace, Ethereum)
- "Regulatory vacuum" / "vacuum" — Patrick and Tony on consequences of regulated finance not showing up
- "Singleness of money" — Tony's economists' term; the issuer shouldn't matter for acceptance
- "Cash equivalent" — the target regulatory/practical status for stablecoins; mentioned multiple times
- "MICA" — EU stablecoin regulatory framework; referenced by Patrick and Daniela
- "E-money token" — MICA regulatory classification; Patrick's preferred term for Circle's products
- "Guard rails" — Patrick warns against building guard rails around foreign currency stablecoins
- "Geostrategic" — Alexander's repeated framing for the US-Europe stablecoin competition
- "Bottom up" vs. "top down" — Patrick's adoption frame, repeated
- "Acceptance" — the most repeated single word in this panel (like File 2)
- "Correspondent banking" — Tony's solution for global euro stablecoin distribution
- "Digital sovereignty" — Daniela's formal question framing; Patrick and Tony challenge the isolationist version of it
- "20 issuers" / "20 euro stable coins" — Patrick on MICA licensed issuers
- "EuroC grew 10x" — Patrick's proof point for bottom-up strategy working
- "Vietnamese dong" — Tony's vivid example for global acceptance use case (Vietnam exporter receiving Kalis tokens)

**Analogies:**
- 1960s credit card market → today's stablecoin market (Tony)
- Department store cards → credit cards → stable coins (Tony: special purpose → general purpose)
- Checks (19th century) as model for stable coins (21st century): both are promises to pay, both have many issuers and redemption agents
- "Frankenstein monster money" — Tony's phrase for what stablecoins should NOT be
- "Writing on a piece of paper / block of marble / relational database / blockchain" — Tony on the continuity of a promise to pay across technology generations
- "I owe you €10" — Tony's philosophical reduction of what USDC actually is
- Vietnamese exporter analogy: hard currency preference, FX revenue for accepting bank

---

## 8. COMPANIES / PROTOCOLS MENTIONED

- **Circle** — USDC; EuroC (largest euro stablecoin); USYC (largest tokenized MMF); Patrick Hansen; Circle Payments Network (CPN) cited by Tony as "American Express" model
- **Kalis (Kibalis)** — CEO Yan; 12-bank consortium; ING, Uni Credit, BBVA, BNP Paribas named; Dutch EMI; euro stablecoin
- **Ubix** — Tony McLolin; "clearing system for tokenized money"; "new Visa for tokenized money"
- **VIA Science** — Alexander Bunga; military-grade data security; US Navy/Air Force heritage; Borch and BMW backed; Circle partnership; Stellar integration
- **Monerium** — mentioned as another European euro stablecoin issuer
- **ECB** — retail digital euro; wholesale CBDC; mentioned separately by Patrick
- **Ethereum** — main DeFi platform; default interoperability target
- **Stellar** — VIA Science integration
- **Deutsche Bank** — correspondent banking relationships cited for global euro distribution; Manuel Klein mentioned
- **WeChat Pay** — cited by Alexander as example of China's blockchain payment rails
- **Tether (USDT)** — the "unregulated" money that fills vacuums left by regulated finance
- **EU ID Wallet** — European digital identity initiative; cited as integration target for autonomous vehicle payments
- **BMW, Borch** — VIA Science backers; autonomous vehicle payment use case

---

## 9. USE CASES HIGHLIGHTED

1. **Cross-border business payments** — corporate treasurer paying suppliers in US (dollars) and UK (pounds) and eventually onchain equivalents
2. **Tokenized securities settlement** — DT pilot regime in Europe already settling tokenized securities vs. euro stablecoins; Circle supporting some teams
3. **Tokenized money market fund purchase settled in EuroC** — already available today ("you can buy a tokenized money market fund and settle with EuroC")
4. **Humanitarian aid and NGO payments** — VIA Science Haiti pilot: paying mothers and staff via stablecoin
5. **US military base payments** — Alexander's speculative but high-leverage adoption scenario: 300+ global bases moving from cash to stablecoin
6. **Autonomous vehicle / in-car payments** — Alexander: VIA Science / BMW use case; programmable subscriptions for parking, charging
7. **AI agent payments** — Patrick: "AI agents might essentially flock towards stable coins because they are 24/7 programmable money"
8. **Correspondent banking integration** — Tony: Vietnamese bank accepting Kalis token, converting to dong, earning FX
9. **European treasury management** — catching dollar stablecoins in European bank wallets and converting to euros

---

## 10. TONE & STYLE

The most explicitly policy-oriented and geopolitically charged panel of the four. Three registers present simultaneously: (1) Patrick's regulatory expert precision (MICA, CSDR, e-money tokens, DLT pilot regime); (2) Tony's sweeping historical analogies delivered with showman's confidence; (3) Alexander's provocateur/American-observer role — the most disruptive voice on stage, challenging European complacency openly. Daniela is a structured moderator but follows Tony's frameworks as they emerge. Yan is calm, factual, and pragmatic. Panel has a sense of urgency — Europe is falling behind — that the other three panels don't have. Patrick's remote participation (emergency) creates slight asymmetry but he is articulate and punchy in short bursts. The "0.2%" statistic hangs over the entire panel as an indictment.

---
---

# CROSS-CUTTING THEMES ACROSS ALL FOUR FILES

## Theme 1: Acceptance Is the True Constraint — Issuance Is Solved
All four panels converge on this. File 1: getting stablecoins accepted at point-of-sale and through card networks. File 2: "everyone is focused on issuance — acceptance is the unlock." File 3: tokenized assets lack distribution infrastructure (no broker-dealer layer onchain). File 4: "our sovereign currencies have to occupy the venues for commerce." The tech of creating stablecoins is mature. The commercial and regulatory architecture for accepting them broadly is not.

## Theme 2: Back-End Efficiency Before Front-End Consumer Experience
Every panel features the "invisible plumbing" frame. Visa settles in stablecoins; Walmart merchants don't know. Western Union uses USDPT to fund agents; senders don't know. DTCC moves toward atomic settlement; traders don't know. File 1's most memorable formulation: "That is not a front-end consumer concern." File 4: "Stable coins are basically extension of US dollars" — the mechanism is invisible, the result is what matters.

## Theme 3: Last-Mile / Off-Ramp / Cash-Out Remains Hardest
File 1: "Grandma wants cash." File 2: "Reserves also flowing... we still need to make also interoperable." File 3: "Finality... until regulation allows the blockchain to be the actual book of records." File 4: Patrick on needing "bottom-up" usage and liquidity before institutional adoption. Across all files, the final conversion to local currency / physical cash / legally recognized settlement remains the unsolved problem.

## Theme 4: Stablecoins Are Money, Not Crypto
All four panels explicitly distance stablecoins from "crypto" in the speculative sense. File 1: Pete on the MCC code — "cryptocurrency is an investment. Stable coins is a payment mechanism." File 2: Jan — "Stable coins are money... that conversation is already settled." File 4: Tony — "Stable coins shouldn't be Frankenstein monster money. They should be normal money." And: "Cash equivalents where the issuer doesn't matter." File 3: Otto — "Goes back to the basics of economics... use of money, value of money."

## Theme 5: Tony McLolin Appears Across Two Panels (Files 2 and 4) With a Consistent Master Thesis
Tony is the most consistent intellectual voice across the dataset. His position is identical and reinforced in both appearances:
- Acceptance must be mutualized; every bank/fintech must offer wallets
- There will be thousands of stablecoin issuers and zero fragmentation (credit card analogy)
- Cards on front end of stablecoins are "an abomination" (File 2) / stablecoins should work like checks (File 4)
- Ubix is "the new Visa for tokenized money"
- Proprietary networks (like Circle Payments Network = American Express) vs. open networks (like Visa/Mastercard = Ubix model)
- Open-source EMV-equivalent POS kernel is the common project the industry needs

## Theme 6: The Regulatory Gap Is Closing But Creating Asymmetric Race Conditions
File 1: MCC 6051 being fixed; Pete says "dramatically improved" in recent months. File 2: "It's really mostly like a legal question." File 3: GENIUS Act, Clarity Act moving through US; "regulation allows blockchain to be the actual book of records" as key unlock. File 4: MICA exists but has 0.2% market penetration; US has "a very clear plan"; Europe is "still discussing the regulatory framework." America moves, Europe waits.

## Theme 7: The 7-Day / 24/7 / 365 Settlement Advantage
Every panel cites round-the-clock settlement as a primary value proposition. File 1: Visa collateral reduction from 7-day settlement; "three to eight basis points." File 2: Kalis building 24/7 infrastructure. File 3: "go into it on a Saturday morning, come out on a Sunday afternoon and earn a day and a half's interest." File 4: "AI agents might flock towards stablecoins because they are 24/7 programmable money." This is the most universally agreed-upon benefit.

## Theme 8: Enterprises and Institutions Drive Adoption — Not Consumers
File 1: Brian explicitly says "it's the enterprises that are really going to push this industry forward." Malcolm: "consumer acceptance is not the game here — the underlying infrastructure will start moving the coin." File 2: Imo — institutions need to "abstract for our clients this kind of complexity." File 3: modeled around institutional distribution (Invesco, Bitwise, Coinbase AM). File 4: Patrick — institutions "want to build rails for the stable coins that are actually being used." The consumer follows the enterprise.

## Theme 9: Confidentiality, Privacy, and Compliance Triangle
File 2 raises this most explicitly — Ivan: "confidential privacy supersedes all of that." File 2: discussion of FHE (too expensive), ZK proofs (expensive and not scalable), private networks like Canton (trust issue with key holder). File 3: Monet on permissioned "allowed list" model as privacy and security mechanism. File 4: Tony on "singleness of money" — issuer doesn't matter. No panel fully solves the tension between blockchain transparency and institutional confidentiality.

## Theme 10: The European vs. American vs. Chinese Tripartite Frame
This emerges explicitly in File 4 but underlies all panels. File 4: Alexander — "America has a very clear plan... China has built it... Europe is still discussing." File 2: Kalis as European institutional response to US dollar stablecoin dominance. File 1: All speakers are US-oriented enterprises. File 3: US regulatory framework (GENIUS, Clarity) cited as enabling; Citi's forecast is US-dollar-centric. The subtext: dollar stablecoins dominate because US government has geopolitical interest in their expansion; euro stablecoins at 0.2% represent a strategic failure.

---

## KEY QUOTES FOR ADVERTISING / CONTENT USE

### Most Quotable Lines (Ranked by Impact):

1. **"If the regulated instruments are not provided on these venues, then don't be surprised if someone transacts in Tether. That's not the fault of the person doing the transaction."** — Tony (File 4)

2. **"The acceptance infrastructure needs to be mutualized. This is the unlock."** — Tony (File 2)

3. **"We're at the edge of a great big ocean and we're fighting over one shrimp. It's ridiculous."** — Tony (File 2, on Canton vs. ZK Sync)

4. **"16,000 card issuers and there is zero fragmentation."** — Tony (File 4)

5. **"Cryptocurrency is an investment. Stable coins is a payment mechanism."** — Brian (File 1)

6. **"When my mom asked what I do, that's what I always say. I make money move at the speed of the internet."** — Brian (File 1)

7. **"If you are more successful, you actually have to provide us more collateral. That's a perverse thing. So we're fixing that."** — Pete/Visa (File 1)

8. **"We're amazing at building tech and pretty poor at building product."** — Ivan (File 2)

9. **"The rails are in the asset. Interoperability, liquidity become an attribute of the asset, not of the blockchain."** — Otto/DTCC (File 3)

10. **"Our T-bill fund has a NAV that ticks up by the second. You can go into it on a Saturday morning, come out on a Sunday afternoon and earn a day and a half's interest when the markets have been closed."** — Simon/Superstate (File 3)

11. **"Grandma wants cash. She's going to need it. She doesn't know what a stable coin is."** — Malcolm/Western Union (File 1)

12. **"America has a very clear plan and I think once they start transacting there'll be surprises on the European side."** — Alexander (File 4)

13. **"Stable coins are simply an extension of US dollars... stable coins are basically an extension of US dollars and it has another benefit for the US — you can refinance your debt."** — Alexander (File 4)

14. **"The exam question for ubiquity and interoperability is really about acceptance."** — Tony (File 2)

15. **"Stable coins shouldn't be Frankenstein monster money. They should be normal money."** — Tony (File 4)


---
## BATCH 6
---
# Video Script Synthesis — Partial 6
## Five Scripts: GENIUS Effect | Agentic Payments | Sanctions/Stablecoin | Consensus 2026 | Crypto Rails

---

# FILE 1: "The Genius Effect — Stablecoins Video Script"

## 1. OVERVIEW
- **Format:** Live conference panel — moderated Q&A with 5 panelists
- **Length:** ~40 min transcript (full session with lightning round close)
- **Style:** Policy-heavy, institutional, Washington-insider tone; moderator-driven; professional and formal; occasional humor
- **Audience:** Institutional finance, policy, regulatory, and crypto-native professionals; Milken Institute conference attendees
- **Venue:** Milken Institute (implied by "thanks to the Milken Institute for hosting us")

## 2. SPEAKERS & SEGMENTS

**Moderator (unnamed in transcript)**

**Lauren Beliv** — Global Co-Head of Policy, Ripple
- Key arguments: Stablecoins are a foreign policy tool; RLUSD as institutional-grade product; 55 million Americans (1 in 5) hold crypto; next 10x in stablecoins driven by institutions not retail; movie ends with seamless TradFi integration

**Robin Cook** — Federal Team Lead and Legislative Counsel, Coinbase
- Key arguments: GENIUS Act = first major financial services legislation in 30+ years not crisis-driven; ban on yield is about line-drawing not prohibition; banks need to get comfortable with new model; consumer protection is the real debate

**Michael Greenwald** — Global Head of Financial Innovation and Executive Relations, AWS
- Key arguments: Resilient US cloud infrastructure is the bedrock; AI + digital assets = new financial paradigm; dollar-based digital assets reinforce US economic competitiveness

**Jean Lewig** — CEO, Carry Networks (tokenized deposit solution)
- Key arguments: Digitalization is evolutionary not revolutionary (Mesopotamia rocks to metals to gold to paper to digital); tokenized deposits bring money INTO banks supporting lending; Lincoln analogy (1863 OCC creation); digital currency predicted since 1996 under Secretary Rubin

**Caroline** — Chief Legal Officer and Chief Administrative Officer, MoonPay; former Acting Chairman of CFTC
- Key arguments: "Looks like a duck test" for OCC rebuttable presumption; dual banking system analogy; MoonPay + PayPal white-label stable coin developer platform; agentic payments as "fancier recurring bill pay"; McKenzie estimate $1 trillion in agentic payments by 2030

**Key Segments:**
1. GENIUS Act overview and yield/rewards debate
2. Bank deposit flight risk — zero-sum framing debunked
3. Non-bank charters and Fed master account access
4. Tech infrastructure and cloud's role (AWS)
5. AI + digital assets convergence; agentic payments
6. Tokenized deposits vs stablecoins interplay
7. International dollarization (pros/cons)
8. Lightning round (two statements: yield amendment by 2027; AI agents initiating 50%+ of stablecoin transactions within 5 years)

## 3. ALL KEY STATS & DATA
- **$314 billion** — current stablecoin market cap (at time of taping)
- **"First 0 to $314 billion driven by retail"** — next 10x by institutional
- **55 million Americans** — hold and use crypto; 1 in 5 Americans
- **Equally divided by political party and regionally across the US**
- **13 new bank powers** in Title IV of Senate Banking Committee January draft (first new bank powers since 1999 Graham-Leach-Bliley Act)
- **JP Morgan** — processed trillions of dollars in tokenized repo and payments
- **~9% fees** at traditional remittance providers + 3-day wait + FX charges
- **$1 trillion** — McKenzie estimate for agentic payments by 2030
- **15-25%** of e-commerce to be agentic in nature (consultant estimates)
- **1996** — Secretary Robert Rubin tasked OCC team to study digital currency
- **"25 years" vs. Rubin's predicted "5 years"** for digital currency to mature
- **Most US paper currency sits OUTSIDE the United States**
- **1863** — Lincoln created first American national currency and the OCC simultaneously
- **"Third largest regulator in the country"** — New York DFS (after Fed and OCC)
- **Genius Act** signed into law "last year" (relative to panel date)

## 4. CORE NARRATIVE ARCS

**Arc 1 — The GENIUS Act as Inflection Point**
First major financial legislation in 30+ years not crisis-driven. Solved the credential/safety-and-soundness question but left the commercial viability question (yield/rewards) open. Now the debate moves from "should stablecoins exist" to "how do they grow."

**Arc 2 — Yield Debate as False Binary**
Banks claim allowing yield = deposit flight. Panelists argue: (a) it's not zero-sum, (b) third parties can still pay incentives, (c) the "looks like a duck" test is workable, (d) banks actually benefit from stablecoin rails, (e) Genius itself structurally ensures banks win any yield competition via fractional reserve advantages.

**Arc 3 — Evolutionary, Not Revolutionary**
Jean Lewig's persistent theme: rocks to metals to paper to digital. Tokenized deposits = digital checking account. Not a rupture but a modernization. "It is not revolutionary, it's evolutionary."

**Arc 4 — Institutional Entry as the Next 10x**
Lauren: retail drove the first $314B. Institutional engagement drives the next 10x. Banks building trust through tough regulatory scrutiny (NY DFS, OCC charter) enables banking partnerships.

**Arc 5 — AI + Digital Assets Convergence**
MoonPay Agents + Claude integration. Agentic commerce as "fancier recurring bill pay." $1 trillion agentic payments projection. AI leadership defined by powering digital asset infrastructure.

**Arc 6 — Dollar as Foreign Policy Tool**
Stablecoins as mechanism for global dollar demand. Remittance alternative (9% cost to near-zero). People in unstable economies can hold assets in USD via 13-word seed phrase. Dollar demand brings down US interest rates at home.

## 5. POSITIONING PILLARS
- **Regulation = Enabler, Not Barrier** — Genius Act removed "consequential blockers"
- **Institutional Is the Real Market** — Retail drove Phase 1; institutions drive Phase 2
- **Not Zero-Sum vs. Banks** — Banks and stablecoins are complementary, not competing
- **Dollar Dominance via Digital Rails** — Stablecoins = foreign policy tool for dollar supremacy
- **Safety Through Regulation** — AML, proof of reserves, bankruptcy protections make stablecoins bankable counterparties
- **Evolutionary Framing** — Always connect new to familiar (credit card miles, recurring bill pay, checking accounts)

## 6. HOOKS & OPENINGS
- "How does the movie end?" (Lauren's repeated framing device)
- "By 2027, the US will amend the Genius Act to allow all stablecoin issuers to pass interest directly to users to compete with the digital yuan." (Lightning round provocation)
- "The times they are a-changing" vs. "Frozen" (Dylan/Disney as agreement/disagreement indicators)
- "In Mesopotamia, they had rocks... why should we have paper in a digital world?"
- "At the top of my wallet is a credit card from United Airlines." (Robin's opening hook on consumer incentives)

## 7. RECURRING PHRASES & LANGUAGE
- **"How does the movie end?"** — Lauren's central rhetorical device
- **"Evolutionary, not revolutionary"** — Jean Lewig
- **"Looks like a duck test"** / **"walks like a duck, sounds like a duck"** — Caroline on OCC rebuttable presumption
- **"Consequential blockers"** — Lauren on pre-GENIUS barriers (knowledge, access, regulatory certainty)
- **"Level playing field"** — used by multiple speakers on charter competition
- **"Blooming, buzzing confusion"** — Jean on healthy market evolution
- **"Needle mover"** — Lauren on institutional engagement
- **"Handcuffing the growth of this product"** — Robin on anti-yield restrictions
- **"Better, faster, cheaper payments"** — Robin's aspirational frame
- **"One-to-one dollar backed," "proof of reserves"** — GENIUS compliance vocabulary
- **"Regulation-heavy first"** — Ripple's self-description
- **"24/7, instant settlements"** — RLUSD product descriptor
- **"Cash equivalent"** — positioning stablecoins for institutional treasury use
- **"I Robot controlled by a simple man"** — Jean's creative compound answer to lightning round on AI agents

## 8. COMPANIES/PROTOCOLS MENTIONED
- **Ripple** — 13-year-old company, B2B digital asset infrastructure, RLUSD stablecoin, XRP utility token, OCC charter approved
- **Coinbase** — Trust charter at OCC and NY DFS, ~decade as bitlicense holder at DFS
- **MoonPay** — "Global value network," PayPal partnership (white-label stablecoin developer platform), MoonPay Agents (non-custodial wallet + Claude integration), spend limits for agentic AI
- **AWS (Amazon Web Services)** — Cloud infrastructure as "bedrock," AI + digital assets convergence
- **Carry Networks** — Tokenized deposit solution (Jean Lewig's company)
- **JP Morgan** — Trillions in tokenized repo and payments; long-standing blockchain use
- **New York DFS** — "Third largest regulator," RLUSD approval, Coinbase bitlicense
- **OCC (Office of the Comptroller of the Currency)** — National trust bank charters, stablecoin rule proposal, "pro-innovation under Comptroller Gold"
- **CFTC** — Caroline's former agency (acting chairman)
- **PayPal** — MoonPay partnership for white-label stablecoin platform
- **United Airlines** — Used as consumer incentive/loyalty program analogy
- **Federal Reserve** — Referenced for master account access debate
- **FDIC** — Referenced for deposit insurance in tokenized deposit context
- **Graham-Leach-Bliley Act** (1999) — Last time new bank powers were created before GENIUS

## 9. USE CASES HIGHLIGHTED
- **Cross-border payments** — Ripple's core use case; remittances at near-zero vs. 9% traditional cost
- **Treasury management** — Stablecoins as cash equivalents for institutional liquidity
- **Tokenized deposits** — Bank-issued digital payment tokens (like digital checking account)
- **Retail payment processing** — Consumer-facing stablecoin spending
- **Collateral** — Stablecoins as cash-equivalent collateral for institutional balance sheets
- **Agentic commerce** — AI agents spending from non-custodial wallets with preset limits
- **Remittances** — Sending money home cheaply vs. Western Union-style 9% + 3-day delays
- **Savings for unstable-currency populations** — USD-denominated savings via 13-word seed phrase
- **International dollarization** — Extending dollar reach without physical currency
- **Developer platforms** — White-label stablecoin issuance for branded apps (MoonPay + PayPal)

## 10. TONE & STYLE
- **Primarily:** Policy panel — serious, insider, credentialed
- **Moderator style:** Well-prepared, push-pull with panelists, probes contrarian views
- **Panelist style:** Largely consensus-building with occasional sharp edges (Nick/Caroline more pointed)
- **Notable device:** Lightning round with pop culture (Dylan, Disney, Lynyrd Skynyrd, Isley Brothers) to force simple opinions
- **Humor:** Sporadic but present ("Satoshi rumors," "I Robot controlled by a simple man")
- **Vocabulary register:** Washington/regulatory (rebuttable presumption, AML/CFT, bitlicense, proof of reserves) mixed with consumer-accessible analogies (United miles card, recurring bill pay)

---

# FILE 2: "Agentic Payments Video Script"

## 1. OVERVIEW
- **Format:** Live conference panel — moderator plus 4 panelists
- **Length:** ~35 min transcript
- **Style:** Technical-builder, startup-founder energy; more informal than File 1; forward-looking and bullish; practical demonstrations and real examples
- **Audience:** Crypto-native builders, fintech founders, institutional technologists, developers entering agentic AI space
- **Venue:** Unspecified conference (references "agentic summit yesterday")

## 2. SPEAKERS & SEGMENTS

**Moderator (unnamed)**

**Anil Nminti** — Senior Solutions Architect, AWS
- Focus: Infrastructure for agentic AI; X402 as foundational payment service; agent security vectors; agent loop architecture
- Key role: Technical explainer for how agents work and how AWS supports them

**Vincent Chak** — Founder and CEO, First Digital
- Known for: Issuing FDUSD stablecoin from Hong Kong; new project "Finance District" (platform for Agentic Economies)
- Key arguments: E-commerce is primary agentic payments beneficiary; emerging markets + unbanked as key audience; McKinley $1.5-$3T e-commerce projection; "this is the year of the agentic agent"

**Phil** — Co-founder and CEO, Soho Pay
- Building: Onchain credit card for AI agents (left American Express to build it)
- Key arguments: X402 as standard; pay-per-use model replacing subscriptions; B2B agentic commerce; SpaceX S1 example; 70-75% of retail still in-store

**Marcus** — Founder and President, Mentor (onchain FX platform); Head of Stablecoins, Celo Foundation
- Focus: FX market opportunity ($7.5 trillion/day); multicurrency stablecoin need; Celo ecosystem examples; Africa chatbot use cases
- Key arguments: Agents need fast/cheap/safe chains not specific stablecoins; FX hedging automation; currency-diverse stablecoin ecosystem needed

**Key Segments:**
1. Agent definition and agentic payment definition
2. Stablecoin preference for agents (or lack thereof)
3. Security challenges: scams, prompt hijacking, supply chain attacks
4. AWS infrastructure: X402 as native service, Agent Core, micro-VMs
5. Business model disruption: subscriptions to pay-per-use
6. X402 protocol deep-dive and MPP comparison
7. Industry/geography adoption examples
8. Market size projections
9. Learning resources and closing

## 3. ALL KEY STATS & DATA
- **$7.5 trillion** — FX traded every day (Bank for International Settlements estimate); "largest market in the world"
- **$1.5 to $3 trillion** — McKinley (McKinsey) projection for e-commerce orchestrated by agents by 2030
- **53%** — US businesses already using AI agents (Vincent's claim at time of panel)
- **$50 million** — value of X402 transactions (at time of panel)
- **170-175 million** — X402 transactions completed (at time of panel)
- **~200 milliseconds** — X402 transaction settlement time
- **98%** of X402 transactions on Base (due to latency benefits)
- **$1 and a few cents** — cost of having an agent read SpaceX S1 and produce investment committee memo
- **$1 trillion** — McKenzie estimate for agentic payments by 2030 (corroborating File 1)
- **15-25%** of e-commerce to be agentic (consistent with File 1 citation)
- **70-75%** — share of retail that is still in-person/in-store (Phil's caveat on agentic commerce ceiling)
- **$100/month** — earnings baseline for emerging market unbanked user example
- **$5** — savings amount example for low-income emerging market user
- **8 hours** — maximum uptime for individual micro-VM in AWS Agent Core
- **1,100** — malicious skills in OpenClaw Hub (supply chain poisoning example)
- **Sub-second, sub-cent** — descriptors for agentic micropayments at scale
- **$100/month or $200/month** — Anthropic subscription cost example (pay-per-use disruption argument)

## 4. CORE NARRATIVE ARCS

**Arc 1 — What Is an Agent?**
"Just code... a program that probably runs some loop where it's looking to do some job." Inputs: prompts + tools (APIs, MCP servers, databases, human-in-the-loop) + knowledge bases + LLM intelligence. Runs until goal achieved. Agent payments = transactions discovered, initiated, and authorized by agents.

**Arc 2 — Stablecoin as Native Agent Currency**
Agents buy digital items first (cloud space, server capacity). They don't care about which stablecoin — they care about fast, cheap, low-gas, low-settlement-time rails. FX exposure matters more than brand. Agents need multicurrency options because users are global.

**Arc 3 — X402 as the Infrastructure Revolution**
HTTP 402 ("Payment Required") left open since the internet's founding. Coinbase activated it. Now: seller exposes 402-capable endpoint, client signs authorization header, facilitator settles on-chain, server releases response. Micropayments become native to internet commerce. Every e-commerce transaction could be an X402 endpoint.

**Arc 4 — Security Is Day Zero**
Multiple attack vectors: prompt hijacking (man-in-the-middle), skill/supply-chain poisoning (OpenClaw Hub's 1,100 malicious skills, Cursor hack, TanStack), long-running agent sessions (hours/days/weeks = large attack surface). AWS solution: deterministic policy engine that checks every execution against authorization rules. "Non-deterministic LLM loop" must be paired with "deterministic policy layer."

**Arc 5 — Business Model Disruption: Subscriptions to Pay-Per-Use**
"Marc Andreessen is big on this point" — internet moving from SaaS subscriptions to pay-per-use. Why pay $100-$200/month for Anthropic if you don't use that much or use more than the subscription covers? Pay-per-use "enables a lot of economic activity on the internet that just doesn't work today."

**Arc 6 — Emerging Markets as Primary Beneficiary**
Unbanked person earning $100/month putting aside $5 to build financial footprint. Agent can hedge currency inflation automatically. Africa chatbot examples (buy airtime/data, choose cheapest provider). Philippines to Malaysia payment example (avoids double FX conversion). "For emerging markets this might be their only solution."

## 5. POSITIONING PILLARS
- **Agents as Economic Actors** — Not a gimmick; legal, financial, and commercial actors in their own right
- **Speed + Cost as Selection Criteria** — Agents choose rails by settlement time and gas fees, not brand loyalty
- **X402 as Internet's Missing Payment Layer** — Foundational protocol unlocking machine-to-machine commerce
- **Security as Foundation** — "We see security as day zero at AWS"
- **Emerging Markets + Unbanked = Primary Opportunity** — Not just a US story; global financial inclusion angle
- **B2B as the Big Real Use Case** — Construction company agent negotiating with cement supplier's agent; FX management for mobile carriers

## 6. HOOKS & OPENINGS
- "TLDR, it's going to be big. It's going to be real big."
- "This is the year of the agentic agent." (Vincent)
- "Your agents don't sleep." (Vincent on 24/7 nature)
- SpaceX S1 example: agent reads entire prospectus and produces investment committee memo for $1 and a few cents
- "Why can't every e-commerce transaction be an X402 endpoint?"
- "All these agentic autonomous loops break when they see a payment wall."

## 7. RECURRING PHRASES & LANGUAGE
- **"The year of the agentic agent"** — Vincent
- **"Your agents don't sleep"** — Vincent
- **"Autonomous loops break when they see a payment wall"** — Anil
- **"Day zero security"** / **"Security as day zero"** — AWS philosophy
- **"Non-deterministic loop" vs. "deterministic policy engine"** — Anil's architecture framing
- **"Sub-second," "sub-cent"** — micropayment descriptors
- **"The addressable market is, in the end, infinite"** — Marcus on FX opportunity
- **"This is Jetsons happening now"** — Caroline (File 1 cross-reference, describing MoonPay Agents)
- **"Allowance"** — Vincent's framing for agent spending limits (parental control analogy)
- **"Fat finger rates"** — Marcus referencing years of blockchain trading experience

## 8. COMPANIES/PROTOCOLS MENTIONED
- **First Digital / FDUSD** — Hong Kong-based stablecoin issuer; Finance District (new Agentic Economy platform)
- **Soho Pay** — Onchain credit card for AI agents; founded by ex-American Express exec
- **Mentor** — Onchain FX platform (stablecoin to stablecoin currency swaps at FX rate)
- **Celo Foundation** — Marcus appointed Head of Stablecoins; onchain FX and stablecoins focus; Africa use cases
- **AWS (Amazon Web Services)** — Agent Core (foundational agent OS); X402 SDK; micro-VM architecture; payments as native foundational service
- **Coinbase** — Origin of X402 protocol
- **Anthropic / Claude** — Referenced multiple times: MoonPay Agents built on Claude; Vincent's company using Claude; Phil's pay-per-use example
- **OpenClaw Hub** — ~1,100 malicious skills discovered (security threat example)
- **Cursor** — Developer tool hijacked (supply chain attack example)
- **TanStack** — Open source project hit by similar supply chain attack
- **Open Router** — Phil connected agent to Telegram via Open Router (free alternative to Claude)
- **Hermes** — Mentioned as agent framework to "start messing around"
- **Base (Coinbase L2)** — 98% of X402 transactions; latency benefits
- **Solana / Ethereum** — Referenced as chain options
- **SpaceX** — S1 document used as famous agent micropayment use case example
- **McKinsey/McKinley** — $1.5-$3T and $1T projections for agentic e-commerce and payments

## 9. USE CASES HIGHLIGHTED
- **SpaceX S1 investment memo** — Agent reads prospectus, produces committee memo, ~$1 total cost via micropayments
- **E-commerce** — Primary industry for agentic payments adoption
- **Digital goods** — Cloud space, server capacity (agents' current primary purchases)
- **Africa airtime/data** — Chatbot in messenger app buys airtime/data, chooses cheapest provider and rail
- **B2B cross-border** — Home builder's agent negotiates with cement supplier's agent; FX risk hedged; cheapest rail chosen
- **Emerging market inflation hedge** — Agent holds in USD, settles in local currency; automatic hedging
- **Mobile carrier FX management** — Carriers re-balance FX exposure in real time rather than end-of-day
- **Healthcare appointments** — Agents making bookings
- **Travel/hospitality** — Flight reservations negotiated by agents
- **Advertising** — Agents publishing and consuming ads via API (not billboards)
- **Robotics payment** — Robots with payment tags; task allocation by performance; real-world agent loop
- **Yield generation** — Automated stablecoin vaults for savings
- **Onchain credit** — Soho Pay's product: agent pings credit layer instead of holding balance
- **Pay-per-use API services** — Internet micro-commerce replacing subscriptions

## 10. TONE & STYLE
- **Builder/founder energy** — Practical, fast-paced, excited
- **Technical depth** — Anil provides genuine architectural explanations (micro-VMs, policy engines, X402 flow)
- **Informal and collegial** — "TLDR it's going to be real big"; "start messing around"
- **Global perspective** — Marcus and Vincent consistently bring emerging market, FX, and Asian/African context
- **Honest about risks** — Security section is genuinely candid about attack surfaces
- **Cross-references** — Multiple panelists validate each other's projections ($1T figure appears in both Files 1 and 2)

---

# FILE 3: "Sanctions Stablecoin Video Script"

## 1. OVERVIEW
- **Format:** Live conference panel — moderated discussion, 5 panelists (plus a service dog named Bla1)
- **Length:** ~35 min transcript
- **Style:** Legal/compliance deep-dive; nuanced, academic-ish; frank about industry failures; surprisingly balanced and self-critical
- **Audience:** Compliance professionals, DeFi lawyers, protocol builders, institutional onboarding teams, regulators listening in
- **Notable:** Panel includes a service dog (Bla1) whose vaccination records are on the blockchain — used as proof-of-concept for verifiable credentials

## 2. SPEAKERS & SEGMENTS

**Dominic Sagera** — Moderator/Panelist; consultant who drafted Wyoming SPDI manual; built blockchain analytics and stablecoin controls at NYDFS; set up California's DeFi evaluation system; working on Bla1's vaccination records as verifiable credentials proof-of-concept

**Anna SE** — US Head of Compliance, Laser Digital (crypto arm of Nomura); former Deputy CCO and CCO at Gemini Trust Company; former Assistant District Attorney, Brooklyn DA's office

**Matias** — Bermuda (privacy protocol built on ZK; Noah infrastructure; SDK for wallets and assets; focus on institutional onboarding); "spaghetti approach" vs. mixer approach

**Linda Jen** — Chief Legal and Policy Officer, A Labs (core service provider for Aave Protocol, "largest decentralized lending protocol"); visiting scholar, Georgetown Law; ran DeFi United coalition post-Kelp DAO incident

**Eric** — Privacy and DeFi lawyer; working on "Private Proof of Innocence" (PPY) — verification and trust layer for DeFi; aggregator for proving fund origin is not suspect

**Key Segments:**
1. Who's responsible for stopping exploits? (opening debate)
2. Kelp DAO incident and Aave's response (Linda's firsthand account)
3. Compliance as multi-layered stack
4. Programmable compliance controls (PPY deep-dive)
5. ZK-based enforcement vs. observability-based enforcement
6. Travel rule failures ($6B spent, less than 1% illicit activity stopped)
7. The "fallacy of contamination" (Eric's controversial framing)
8. "Poop in the swimming pool" analogy (Dominic)
9. Tornado Cash lessons and privacy protocol design differences
10. Modular escalating protocol architecture for compliance
11. Bermuda's ZK approach — "spaghetti" vs. mixer
12. Closing: convergence of compliance and privacy

## 3. ALL KEY STATS & DATA
- **$6 billion** — amount spent on illicit finance compliance in the US last year (Linda's figure)
- **Less than 1%** — illicit activities stopped by US bank compliance despite $6B spend
- **TD Bank** — fined **$3.9 billion** for non-compliance/letting through bad funds
- **$500 billion** — illicit funds referenced as having flowed through TD Bank
- **60 minutes** — PPY (Private Proof of Innocence / Rail Gun) block period before token trace clears
- **10% slippage threshold** — PPY trigger for full 60-minute compliance block on DeFi swaps
- **5 of 10 oracles** — Lido's polling threshold for secure rebase (10 oracles vs. competitors' 1 oracle)
- **40 wrench attacks** — France, through mid-April (year unspecified), originated from on-chain balance visibility
- **"Kelp DAO incident"** — referenced as public knowledge; Linda joined A Labs "a few weeks before" it
- **Ethereum Foundation's CROPS framework** — referenced as new standard; Matias endorses it

## 4. CORE NARRATIVE ARCS

**Arc 1 — Where Does Responsibility Fall?**
Not a simple answer. Depends on: (a) type of act (blocked property vs. stolen property vs. speculative); (b) what information the party has access to; (c) whether they have control over fund movement. "Everybody has some responsibility, but to what degree varies." DeFi answer: block them from using your protocol, send them elsewhere.

**Arc 2 — Compliance Is a Stack, Not a Monolith**
Linda's framework: tech stack = base layer + L2s + DeFi protocols + interfaces. Then: blockchain analytics firms + custodians + centralized exchanges. "It's about applying the right type of control at the right layers." The Kelp DAO incident: exploit happened outside Aave Protocol but bad debt landed inside it.

**Arc 3 — ZK as the Future of Compliance**
Bermuda's argument: current compliance relies on observability (watching everything) which is expensive, privacy-invasive, and often retroactive (leading to freezes). ZK can enforce rules AT the point of transaction — "any arbitrary rule at the very point when those assets move." Global liquidity layer + multi-policy enforcement simultaneously. No siloes, no retroactive freezes.

**Arc 4 — The Travel Rule as "Paper Blockchain"**
Eric: "I refer to the travel rule as a paper blockchain." Traditional banks must send sender info to recipient bank on every wire transfer. "Clearly doesn't work" — $6B spent, less than 1% illicit activity stopped. Now being forced onto crypto. ZK proofs at transaction level could be "cryptographic tools that are actually better for compliance."

**Arc 5 — The Fallacy of Contamination**
Eric's argument: If every counterparty to TD Bank (which let through $500B in illicit funds) were frozen, "there would be a liquidity crisis on the planet that nobody could ever buy milk." Banks don't contaminate their counterparties. Yet in crypto, the "contamination theory" says brushing against a bad actor address taints a whole protocol. "The people who are pushing that are people who are selling analytics."

**Arc 6 — Modular Escalating Compliance**
Eric's vision: "Series of independent modular escalating protocols." One business does one thing (basic screening), charges a tiny fee. Someone denied access goes to another layer. Another layer does deeper verification. Can get "cleared" and come back for privacy. Different providers at each layer = no single bias point. "My only responsibility is to do this one little thing."

**Arc 7 — Tornado Cash Lessons**
Bermuda learned from Tornado Cash: don't be a pure mixer. Instead: "spaghetti approach" — funds remain identifiable. Deposits have a status. That status can be retroactively identified if it misses a compliance check. Bad funds can be withdrawn but remain traceable to law enforcement. "Compliance verification first, privacy as byproduct."

## 5. POSITIONING PILLARS
- **Privacy and Compliance Are Not Mutually Exclusive** — "Selective disclosure" not "hiding illicit activity"
- **ZK as Proactive Compliance Tool** — Not reactive (freeze, claw back) but preventive (verify at point of transaction)
- **Protocol Layer vs. Application Layer** — Critical design distinction; wrong layer causes both economic inefficiency and compliance failure
- **Modular Decentralized Compliance** — Better than monolithic: avoids bias, maintains neutrality, creates market for specialized services
- **Contamination Theory Is a Fallacy** — Banks don't apply this logic to themselves; shouldn't be applied selectively to crypto
- **"Truth Layer" framing** (File 5 overlap) — Blockchain as truth not just ledger

## 6. HOOKS & OPENINGS
- Opening with Bla1 the dog (vaccination records on blockchain) — disarming, memorable
- "This panel is not about the good of blockchain. It's about the dark side." (Dominic's framing)
- "North Korea hacking, moving funds" — immediate escalation to high-stakes
- TD Bank fined $3.9 billion — immediately contextualizes crypto criticism within TradFi failures
- "If you were to apply what they did to Tornado Cash to TD Bank, all everyone at TD Bank should have been frozen." — provocative equivalence
- "The poop in the swimming pool analogy" — Dominic's memorable OFAC characterization

## 7. RECURRING PHRASES & LANGUAGE
- **"Fallacy of contamination"** — Eric's term for tainted-funds-spread-to-whole-protocol logic
- **"Paper blockchain"** — Eric's description of the travel rule
- **"Poop in the swimming pool analogy"** — Dominic's characterization of OFAC's contamination view
- **"Compliance verification first, privacy as byproduct"** — Bermuda's design philosophy
- **"Spaghetti approach"** vs. **"mixer"** — Bermuda's architectural metaphor
- **"Selective disclosure"** — Linda's reframing of privacy as proactive compliance
- **"Modular escalating protocols"** — Eric's vision for layered compliance architecture
- **"Zero day bad actor address"** — Eric describing PPY's detection output
- **"Protocol layer vs. application layer"** — Matias's persistent refrain
- **"Observability"** — Matias's term for the flawed current approach
- **"Retroactive actions such as freezes"** — Matias's characterization of current failure mode
- **"DeFi United coalition"** — Linda's post-Kelp DAO industry response
- **"Private Proof of Innocence"** (PPY) — Eric's verification layer
- **"Wrongly tagged" / "innocent people can be tagged"** — Eric on false positives from analytics
- **"Bad attribution given by machines"** — Eric on analytics vendor mistakes

## 8. COMPANIES/PROTOCOLS MENTIONED
- **Laser Digital** — Crypto arm of Nomura; Anna's employer
- **Nomura** — Parent of Laser Digital
- **Gemini / Gemini Trust Company** — Anna's previous employer (Deputy CCO and CCO)
- **A Labs / Aave Protocol** — "Largest decentralized lending protocol"; Linda's current role; Kelp DAO incident's bad debt recipient
- **Bermuda** (privacy protocol) — ZK-based; Noah core infrastructure; SDK for wallets and assets; "spaghetti approach"
- **Rail Gun / PPY** — Client for Private Proof of Innocence; 60-minute block + token trace; revert-to-origin option
- **Tornado Cash** — Sanctioned mixer; canonical case study; Bermuda explicitly differentiates from it
- **Lido** — 10 oracles (risk mitigation control example vs. single-oracle competitors)
- **TD Bank** — Fined $3.9B; $500B illicit funds; used as TradFi hypocrisy example
- **OpenClaw Hub** — 1,100 poisonous/malicious skills (security threat; File 2 cross-reference)
- **Wyoming SPDI** — Dominic drafted the manual
- **NYDFS** — Dominic built blockchain analytics and stablecoin controls there
- **Ethereum Foundation** — CROPS framework; Matias endorses it
- **Georgetown Law** — Linda is visiting scholar; hosted privacy tech roundtable
- **FATF** — Travel rule guidance applied to bank wires; inadequate for crypto
- **Chain Analysis** — Referenced obliquely as analytics provider that makes mistakes

## 9. USE CASES HIGHLIGHTED
- **Privacy for institutional onboarding** — Bermuda's SDK for wallets; ZK-based compliance verification
- **DeFi protocol risk mitigation** — Multi-oracle polling (Lido); slippage-triggered compliance blocks (PPY)
- **Anti-wrench-attack privacy** — 40 France attacks enabled by on-chain balance transparency
- **Verifiable credentials** — Bla1's vaccination records on blockchain as proof-of-concept for decentralized identity
- **Onchain compliance at smart contract level** — Linda's Georgetown research
- **Modular compliance services** — Independent third-party layers: basic screen to deeper verification to cleared for privacy
- **Post-exploit response** — Kelp DAO incident: DeFi United coalition formation; improved asset listing standards
- **Regulatory reporting innovation** — ZK proofs replacing travel rule observability at transaction level

## 10. TONE & STYLE
- **Legal and compliance register** — Precise, nuanced, cautious
- **Self-critical and honest** — Panelists acknowledge industry failures; don't over-hype
- **Academic undercurrent** — Linda's Georgetown connection; Eric's conceptual frameworks
- **Dry humor** — Dog's vaccination records; "poop in the swimming pool" analogy
- **Deliberately provocative** — "Fallacy of contamination," "paper blockchain," OFAC/TD Bank equivalence
- **Contrast with industry hype** — Explicitly frames this as "the dark side" while still building toward optimistic future
- **Notable absence of stats-heavy claims** — More qualitative and framework-focused than other scripts

---

# FILE 4: "Consensus 2026 Stablecoin Video Script"

## 1. OVERVIEW
- **Format:** Live conference panel — Consensus 2026; moderator plus 4 panelists
- **Length:** ~34 min transcript
- **Style:** Builder/institutional hybrid; forward-looking; convergence of regulation and infrastructure; more polished and strategic
- **Audience:** Institutional finance, stablecoin issuers, custodians, on/off-ramp operators, crypto-native builders at Consensus
- **Venue:** Consensus 2026 (explicitly stated via context)

## 2. SPEAKERS & SEGMENTS

**Moderator (unnamed)**

**Sergio Melo** — Global Head of Stablecoin Solutions, Anchorage Digital
- Role: Qualified custodian holding assets underpinning institutional stablecoin activity; national trust bank (OCC-chartered for 5 years)
- Key arguments: "Stablecoin is a distribution game"; bank consortiums are the future; JP Morgan partnership for cashless reserves; all of America's banks should become crypto banks; rail gauge analogy for global harmonization

**Michael Scholov** — CEO and Co-founder, Fireblocks
- Role: Infrastructure moving trillions in digital assets across thousands of institutional clients globally
- Key data: Q4 2025 = first time bank/payment company pipeline exceeded crypto-native pipeline in Fireblocks' 7-8-year history; European bank consortium (12 partners, growing to 32) using Fireblocks for euro stablecoin
- Key arguments: Regulation is what takes stablecoin to next level; convergence of regulation + infrastructure

**Nick Vanek** — CEO and Co-founder, Agora
- Role: Next-generation institutional-grade stablecoin issuance
- Key arguments: Banking opposition to stablecoin yield is "100% anti-competitive behavior"; stablecoins = overregulated money market funds; $7T money market fund market; eurodollar market ($15-20T) as precedent for global dollar demand; stablecoins as "value in motion" not "value at rest"

**Edward Woodford** — Founder and CEO, ZeroHash
- Role: On/off-ramps where stablecoins touch the real world; interoperability between stablecoins and tokenized money market funds (BlackRock, Franklin Templeton); partners with Couch, Interactive Brokers, Gusto
- Key arguments: 30+ chains = massive UX fragmentation; interoperability key; accounting treatment (gross vs. net) is real hidden friction; stablecoins are "powerful alternative payment method" not "value at rest"

**Key Segments:**
1. Why stablecoins at tipping point now (distribution thesis)
2. Fireblocks European bank consortium (ING origin, 12 to 32 banks, euro stablecoin)
3. Anchorage custody and bank-to-bank solutions
4. Q4 2025: banks exceed crypto-native in Fireblocks pipeline (historic first)
5. Emerging market demand permanence debate
6. On/off-ramp friction and democratization question
7. Global regulatory developments (Japan, Korea, Australia, LATAM/Brazil)
8. Accounting treatment as hidden friction (gross vs. net revenue)
9. Bank yield opposition: anti-competitive or systemic risk concern?
10. Visa/Mastercard integration question (yes/no closing)

## 3. ALL KEY STATS & DATA
- **2.5 billion wallets** — globally that can now be seamlessly enabled for stablecoins (PayPal, Revolut, NuBank, GCash accounts)
- **Q4 2025** — First time in Fireblocks' 7-8 year history that bank/payment pipeline exceeded crypto-native
- **12 partners** — current European bank consortium (Fireblocks-supported euro stablecoin)
- **32 partners** — rumored near-term expansion of same consortium
- **ING** — origin bank of European consortium idea ("a few years ago")
- **99.9%** — share of global stablecoin flow/volume denominated in dollars
- **$15-$20 trillion** — eurodollar market (dollar deposits outside United States); precedent for global dollar demand
- **$7 trillion** — money market fund assets; stablecoins framed as "overregulated money market funds"
- **$300 billion** — stablecoin market size reference (Rob in File 5 uses same figure)
- **5-10 basis points** — typical payment processing margin on stablecoin flows
- **$100 billion** — example stablecoin flow at payment business; revenue distortion under gross accounting
- **$5-$10 billion/quarter** — revenue size of large payment companies whose margins get destroyed by gross accounting treatment
- **200 basis points** — example bank spread (park at Fed overnight, give consumer 200bps, make spread)
- **5% or 6%** — what banks "should be giving you" to compensate for risk (Nick's consumer advocacy)
- **12-18 months** — Sergio's window for homogeneous, harmonized global stablecoin landscape
- **24 months** — Nick's window for trillions to replatform onchain
- **5 years** — Anchorage OCC national trust bank charter duration
- **Silicon Valley Bank** — cited as artifact of fractional reserve fragility in instantaneous settlement world
- **$2.5 billion AUM** — BUIDL (BlackRock tokenized money market fund) accumulated

## 4. CORE NARRATIVE ARCS

**Arc 1 — Distribution Is the Tipping Point, Not Technology**
Stablecoins are available to 2.5 billion wallets today. Like the iPhone: "you've distributed all the iPhones, now the application layer has been built." Volumes pick up when distribution is in place.

**Arc 2 — Banks Are the Next Wave**
Q4 2025: banks/payment companies first exceed crypto-native in Fireblocks pipeline. "The Fireblocks pipeline reflects what we'll see in 6-12 months." Dollar replatforming onto chain "can only happen if banks are comfortable holding billions of clips."

**Arc 3 — Bank Opposition to Yield Is Anti-Competitive**
Nick: "It's 100% anti-competitive behavior." Stablecoins = overregulated money market funds. Banks love the arbitrage: give consumer 200bps, park at Fed overnight, make spread. Under GENIUS, stablecoin issuers can NEVER compete with fractional reserve banks on yield — so the debate is moot.

**Arc 4 — Emerging Markets = Already Happened, Not Future**
Argentina: people using cash, stablecoins are "much better vehicle." Euro dollar market ($15-20T) = already institutions using dollars outside US. International payroll, corporate treasury, B2B payments — already moving to stablecoins.

**Arc 5 — Fragmentation + Interoperability**
30+ chains for USDC/USDT alone. Tokenized money market funds. Tokenized deposits. Stablecoins. All must interoperate. ZeroHash solves this: "at the end of the day it should be as simple between me moving money to Michael." User should never have to think about which chain or which type of money.

**Arc 6 — Global Harmonization = Rail Gauge Moment**
Sergio: "This is a moment where the world is deciding whether cars drive on the right or left side of the road." Rail gauge analogy: different distances between rails make cross-border train travel require transferring goods. "Global regulators are actively looking at US rulemaking... to shape their local framework so the gauges match."

## 5. POSITIONING PILLARS
- **"Stablecoin Is a Distribution Game"** — Sergio's foundational thesis
- **Bank Consortiums as Scale Mechanism** — ING model, 12 to 32 European banks; JP Morgan partnership
- **Infrastructure Builders at the Critical Stack Layer** — custody + infrastructure + issuance + on/off-ramp = the four essential components
- **"Replatforming Money"** — preferred framing for what stablecoins do to the dollar
- **"Value in Motion, Not Value at Rest"** — Edward's key positioning for stablecoins vs. yield debate
- **Visa/Mastercard as Augmenters, Not Disruptees** — All four panelists answer "yes" to Visa/MC integration question

## 6. HOOKS & OPENINGS
- "We are at one of those rare inflection points where technology, regulation and geopolitics are colliding simultaneously and the outcome is going to reshape how money moves around the world. And none of this is theoretical anymore. This is infrastructure."
- "Q4 2025 was the first time in the history [of Fireblocks] that the pipeline of banks and payment companies exceeded the number of companies that are fintech and crypto-native."
- "We need all the banks in America to be crypto banks. We want crypto to be money, a better way of money."
- "There won't be deposits. That's the truth."
- Rail gauge / voltage / left-right driving analogies — unusually vivid physical world metaphors

## 7. RECURRING PHRASES & LANGUAGE
- **"Replatform money / replatforming the dollar"** — multiple speakers
- **"Stablecoin is a distribution game"** — Sergio
- **"Value in motion vs. value at rest"** — Edward
- **"Rail gauge" / "voltage on outlets" / "left or right side of the road"** — Sergio's harmonization analogies
- **"Cashless reserves"** — Anchorage's product; JP Morgan partnership enables this
- **"The Fireblocks pipeline reflects what we'll see in 6-12 months"** — Michael
- **"Crypto banks" / "we want crypto to be money"** — Sergio
- **"Dollar account" / "global dollar account"** — Nick's emerging market product framing
- **"Abstracted away"** — Edward on UX friction (chain choice, money type should be invisible)
- **"The green dollar or the blue dollar"** — Nick on Argentina informal currency market
- **"Anti-competitive behavior"** — Nick's characterization of bank yield opposition
- **"No pun intended"** — Sergio joking about tokens "going into the ether"

## 8. COMPANIES/PROTOCOLS MENTIONED
- **Anchorage Digital** — Qualified custodian; OCC national trust bank (5 years); JP Morgan partnership (cashless reserves)
- **Fireblocks** — Moves trillions; 7-8 years old; European consortium; Q4 2025 historic pipeline shift
- **Agora** — Institutional stablecoin issuance (Nick's company)
- **ZeroHash** — On/off-ramps; BlackRock, Franklin Templeton, Couch, Interactive Brokers, Gusto partnerships
- **JP Morgan** — Cashless reserve partnership with Anchorage (announced day before panel)
- **ING** — Origin of European bank consortium idea
- **BlackRock / BUIDL** — $2.5B AUM tokenized money market fund; ZeroHash provides rails to/from
- **Franklin Templeton** — Tokenized money market fund; ZeroHash rails
- **PayPal / Revolut / NuBank / GCash** — 2.5B wallet distribution channels
- **Visa / Mastercard** — Final question: will they integrate stablecoins? All four: yes
- **Silicon Valley Bank** — Artifact of fractional reserve fragility; bank run in instantaneous world
- **Early Warning Services / Zelle** — "Made stablecoin solution announcements last year"
- **Interactive Brokers / Gusto** — ZeroHash enterprise partners
- **OCC** — National trust bank charter; 5-year Anchorage relationship
- **FASB** — Accounting treatment issue (gross vs. net) "less sexy pieces around FASB"
- **Tether (USDT) / USDC** — Named as largest US stablecoins; 30+ chain fragmentation problem
- **MiCA (EU regulation)** — Advantage for European banks issuing stablecoins
- **ECB** — "In a quiet period pending updates"
- **Korea / Japan / Australia / Brazil** — Regulatory developments outside US/EU

## 9. USE CASES HIGHLIGHTED
- **International payroll** — Companies paying workers globally via stablecoin
- **Corporate treasury** — B2B payments moving from Swift to stablecoins (instant settle, cheaper, earn on dollars)
- **Emerging market savings** — Argentina replacing informal cash/blue-dollar markets
- **Eurodollar market digitization** — $15-20T already exists; now moving onchain
- **Tokenized money market funds** — Institutional yield-bearing instrument with ZeroHash interoperability rails
- **Bank-to-bank custody** — Anchorage providing institutional-comfort custody for stablecoin backing assets
- **European bank consortium euro stablecoin** — Proper euro-denominated stablecoin for MiCA compliance
- **Cashless reserves** — Anchorage + JP Morgan enabling stablecoin backing via bank balance sheets
- **Fortune 10/500 treasury** — Multi-jurisdictional operations moving to stable coins
- **"Global dollar account"** — Small startup to Fortune 10 use case
- **Visa/MC settlement augmentation** — Not replacement; stablecoins added to existing card networks as payment rail

## 10. TONE & STYLE
- **Strategic and builder** — Not academic; "we're building it right now"
- **Collaborative tension** — Nick is most provocative (anti-competitive banking); others more diplomatic
- **Data-led** — Q4 2025 Fireblocks data; eurodollar numbers; 2.5B wallets figure
- **Physical world analogies** — Rail gauges, voltage, driving sides; unusually grounded for crypto content
- **Optimistic but grounded** — "None of this is theoretical anymore. This is infrastructure."
- **Close convergence with policy** — All panelists reference GENIUS Act, rulemaking, FASB as active concerns

---

# FILE 5: "Crypto Rails Video Script"

## 1. OVERVIEW
- **Format:** Live conference panel — moderated; 4 panelists (3 bank representatives + 1 blockchain foundation)
- **Length:** ~34 min transcript
- **Style:** Traditional banking + blockchain intersection; most skeptical/cautious panel of the five; significant tension between stablecoin optimism and banking realism; explicitly includes non-US/UK/Bermuda perspectives
- **Audience:** Banks, wealth managers, asset managers, institutional tokenization stakeholders, regulators, Bermuda financial community
- **Venue:** Bermuda (implied; "on the island," Bermuda Commercial Bank, BMA in room, Bermuda dollar reference)
- **Notable:** Most geographically diverse framing; most skeptical US voice (Rob from Customers Bank)

## 2. SPEAKERS & SEGMENTS

**Moderator (unnamed)**

**Rob** — Customers Bank (US bank); banking crypto space since 2017
- Key arguments: US already has fast payments (real-time payments); domestic stablecoin utility limited; cross-border is the real use case; tokenization more exciting than stablecoins domestically; compliance as essential trust builder; "cautiously optimistic"

**Hugo** — Bermuda Commercial Bank; cross-border specialist
- Key arguments: Stablecoins are "killer app for crossborder payments"; daily cross-border volume; on/off-ramps into digital assets; insurance, reinsurance, trade finance disruption; Bermuda as model regulatory jurisdiction
- Regulated by BMA; one of four banks on the island

**Wasim** — Monument Bank (London; "fastest growing bank in the UK"); phase one: £250M tokenized saving program
- Building: Mass affluent (£100K-£5M wealth) market; tokenized savings + investments + Lombard lending; partnership with Midnight Foundation
- Key arguments: "Forgotten and vacated middle" of wealth market; best technology is invisible (Uber analogy); AI + agentic orchestration in 5 years; "wealth partners in their pocket"

**Farmy** — Midnight Foundation (permissionless but private blockchain network)
- Key arguments: Stable coins existed before digital — they were liquidity funds / money market funds; blockchain as "truth layer" (not just ledger); privacy as prerequisite for institutional adoption; "web 2.5" as destination; smart contracts substitute for agency trust; "collateralization is the real value" of tokenization
- Background: 20+ years in hedge fund world; used to put "tens of billions of dollars" into liquidity funds

**Key Segments:**
1. CBDC landscape overview (Bahamian dollar, Bermuda, China)
2. Stablecoin utility — US domestic vs. cross-border debate
3. Cross-border as "killer app" (Hugo)
4. Tokenized assets: real estate, RWA, money market funds
5. Monument Bank + Midnight partnership deep-dive
6. "Forgotten and vacated middle" wealth market
7. Midnight's web 2.5 vision (permissionless + private)
8. Collateralization as the real tokenization value
9. Regulatory comparison: US vs. UK vs. Bermuda
10. Basel rules and US non-adoption (provocative aside)
11. FOMO and compliance risks
12. Five-year outlook: digital cash in 2031

## 3. ALL KEY STATS & DATA
- **$300 billion** — stablecoin market size (Rob's opening frame; consistent with Files 1 and 4)
- **£250 million** — Monument Bank's Phase 1 tokenized saving program
- **$2.5 billion AUM** — BUIDL reference (File 4 cross-reference)
- **"Tens of billions of dollars"** — Farmy's former allocation to liquidity funds / money market funds (analog to stablecoins)
- **2020** — Bahamian dollar CBDC launch date
- **"9:00 to 5:00 PM Fed window"** — restriction that digital stablecoins bypass; 24/7 availability advantage
- **Half an hour** — Monument Bank's corporate client onboarding time (via AI and cloud)
- **20 minutes** — Bermuda Commercial Bank's individual client onboarding time
- **Half an hour** — Bermuda Commercial Bank's corporate onboarding (data upload)
- **£100,000 to £5 million** — Monument Bank's mass affluent wealth target range
- **£5,000-£10,000** — minimum investment threshold targeted (vs. £100K minimum for traditional private banking)
- **5-10%** — share of ultra high net worth portfolio in private equity type products (target allocation for mass affluent)
- **70%** — gains lost to fees in existing private equity/hedge fund access products
- **5 years (to 2031)** — panel's forward-looking horizon
- **2018** — Rob's first tokenization conference (real estate, RWA tokenization discussed even then)
- **2017** — Rob's start banking the crypto space
- **"100 years"** — dollar's successful geopolitical projection; "will be probably for the next hundred" (File 4 cross-reference, Sergio)
- **"Mid-19th century telegraph"** — Western Union's heritage (cross-border payment legacy)
- **Basel rules** — US as "the one place that didn't adopt them" (provocative line; Hugo)

## 4. CORE NARRATIVE ARCS

**Arc 1 — US Domestic vs. Cross-Border Utility Divide**
Rob (US bank): US already has fast real-time payments; domestic stablecoin benefit is mainly cost-related and rate-dependent; in falling rate environment stablecoins will need to charge fees like Visa/Mastercard. Hugo (Bermuda): cross-border is the use case; "killer app." Farmy: removes fragmentation, enables borderless payments without censorship.

**Arc 2 — Stable Coins Existed Before Blockchain**
Farmy's reframe: "Stable coins existed before digital stable coins. They're called liquidity funds." $1 NAV, stable, same-day subscribe/redeem. Now digitized to run 24/7 outside Fed window. Not a new concept — an upgrade.

**Arc 3 — Privacy as Institutional Prerequisite**
Farmy's central argument: public blockchains expose your account balance to "every pair of eyes in this room." If you transact on a public network, "everything you do is transparent and visible forever." Triggers doxing, alpha copying, front-running. Solution: not private permissioned networks (that's just a bank). Solution: Midnight — permissionless but private. "Web 2.5."

**Arc 4 — Collateralization as the Real Value of Tokenization**
Farmy: "Tokenization is about democratization, fractionalization — the real value is collateralization." Getting leverage on a hedge fund unit is hard. Getting leverage on the underlying portfolio is easy. Proof of asset + proof of collateral + proof of reserve + proof of investment guidelines adherence = access to better leverage, better finance.

**Arc 5 — Trust + Truth**
Rob: "A network is a group of people who trust one another." Trust is the foundation. Farmy: "Trust is great but that's like saying no regulated hedge fund has ever blown up and taken down a bank. It happens." Blockchain provides "truth layer" to back up trust. Smart contracts substitute for agency trust (Morgan Stanley onboards you, Goldman trusts Morgan Stanley's work — smart contract can do the same).

**Arc 6 — Monument + Midnight as Proof of Concept**
First bank putting client assets cash deposits on a permissionless but private network, approved by Bank of England and PRA. Phase 1: £250M tokenized savings. Phase 2: tokenized assets in private domain for mass affluent clients. Phase 3: Lombard lending against tokenized assets. Blockchain banking as a service / crypto as a service for other banks.

**Arc 7 — The 2031 Vision**
Rob: "Digital asset, stable coin, tokenization all disappear from our language and it just becomes part of the financial fabric." Hugo: "The dollar will look the same, but all the plumbing, accessibility, speed — that will all change." Wasim: "Best technology is invisible" (Uber analogy). Farmy: "Good infrastructure is invisible. Midnight is open to all networks."

## 5. POSITIONING PILLARS
- **"Killer App for Cross-Border Payments"** — Hugo's core thesis
- **"Web 2.5"** — Midnight's positioning: not fully public (web3) and not siloed (web2)
- **"Truth Layer"** — Blockchain framing; backs up but doesn't replace trust
- **"Collateralization Is the Real Value"** — Farmy's differentiating thesis vs. fractionalization/democratization narratives
- **"Forgotten and Vacated Middle"** — Monument's mass affluent market opportunity (£100K-£5M)
- **"Blockchain Banking as a Service"** — Monument + Midnight model for export to other banks
- **Stablecoins = Upgraded Liquidity Funds** — Farmy's reframing; demystifies the asset class

## 6. HOOKS & OPENINGS
- "First of all, like everyone up here, my opinions are my own, not my bank's." (Rob — grounding moment)
- "The Bermuda dollar was fully backed by US dollars held in custody for longer than a number of the innovations that you said there." (Hugo — historical corrective)
- "If I ask you where you bank, you might say JP Morgan Chase or Wells Fargo, but you won't tell me your bank account. You won't tell me how much you own in the bank account. As soon as you transact on any public network, any public blockchain, everything you do is transparent and visible forever." (Farmy — privacy argument)
- "The best technology is invisible. So you think about Uber when you go from A to B." (Wasim — 2031 vision)
- "There are complexities... holding stable coins on your balance sheet as a bank as a regulated entity is tricky." (Hugo — honest friction admission)
- "It was amazing that the Basel rules were foisted on the world, but the one place that didn't adopt them was the United States." (Hugo — provocative US critique)

## 7. RECURRING PHRASES & LANGUAGE
- **"Killer app for cross-border payments"** — Hugo
- **"Web 2.5"** — Farmy's Midnight positioning
- **"Truth layer"** — Farmy's blockchain framing
- **"Permissionless but private"** — Midnight's definition
- **"Collateralization" / "proof of asset," "proof of collateral," "proof of reserve"** — Farmy's tokenization value chain
- **"Forgotten and vacated middle"** — Wasim's market opportunity framing
- **"Fees on fees"** — Wasim on existing private equity access cost structure
- **"Wealth partner in their pocket"** — Wasim's 5-year AI vision
- **"Blockchain banking as a service" / "crypto as a service"** — Farmy on Monument-Midnight model
- **"Best technology is invisible"** — Wasim (Uber analogy)
- **"Plumbing"** — Hugo and others; infrastructure that changes while UI looks the same
- **"Cautiously optimistic"** — Rob's persistent qualifier
- **"On the island"** — Bermuda-specific shorthand throughout
- **"Digital cash"** — panel's framing for the future of money
- **"Atomic settlement"** — Farmy's term for stablecoin settlement finality
- **"Lombard lending"** — Monument Bank's aspirational product for mass affluent
- **"Private banking product for the masses"** — Wasim's thesis
- **"Legacy banking"** — Wasim positioning Monument against incumbent infrastructure

## 8. COMPANIES/PROTOCOLS MENTIONED
- **Customers Bank** — US bank; banking crypto since 2017; Rob's employer
- **Bermuda Commercial Bank** — Cross-border specialist; on/off-ramps into digital assets; BMA regulated
- **Monument Bank** — "Fastest growing bank in the UK"; £250M tokenized savings (Phase 1); Midnight partnership; AI/cloud onboarding (20-30 minutes)
- **Midnight Foundation** — Permissionless but private network; stewarded by Farmy; Monument partnership; ZK-based privacy; "web 2.5"
- **JP Morgan Coin / JPM Coin** — Early tokenized deposit reference ("came out some time ago")
- **Bank of England / PRA** — Approved Monument-Midnight deposit arrangement
- **BMA (Bermuda Monetary Authority)** — Bermuda regulator; "members in the room"; highly collaborative
- **BlackRock / BUIDL** — $2.5B AUM tokenized money market fund (cross-reference File 4)
- **Franklin Templeton** — Tokenized money market fund (File 4 cross-reference)
- **Western Union** — "Traces history to mid-19th century telegraph"; trialing stablecoin involvement
- **Circle** — OCC announcement "addressing proof of settlement issues"
- **Charles Hoskinson** — Referenced giving speech at consensus on developer audiences in Argentina/sub-Saharan Africa paid in stablecoins
- **Morgan Stanley / Goldman Sachs** — Smart contract analogy: agency trust vs. smart contract substitute
- **Federal Reserve / Fed wire** — Traditional system access via banks/agencies; smart contract alternative
- **OCC** — National bank regulator; Circle's OCC announcement; Anchorage (File 4) charter
- **GENIUS Act** — Referenced throughout
- **MiCA** — European regulation (File 4 cross-reference)
- **China CBDC** — "Probably the biggest CBDC project around"
- **Bahamian Dollar** — First CBDC example (2020)
- **Cardano** — Hoskinson's connection (implied)

## 9. USE CASES HIGHLIGHTED
- **Cross-border payments** — Hugo's "killer app"; insurance, reinsurance, trade finance, supplier payments
- **CBDC** — Bahamas model; Bermuda private issuance; China scale; "pretty unpopular amongst some of us here"
- **Tokenized deposits** — JPM Coin; digital checking account equivalent
- **Tokenized money market funds / liquidity funds** — Farmy's pre-existing stablecoin analog; BlackRock BUIDL
- **Tokenized savings for mass affluent** — Monument Bank £250M Phase 1; access for £100K-£5M wealth segment
- **Lombard lending on tokenized assets** — Monument Phase 3; private banking product democratized
- **Private equity / hedge fund access for mass affluent** — "Forgotten middle" currently excluded by high minimums
- **Collateral / leverage on portfolio proof** — Farmy's institutional hedge fund use case
- **On/off-ramp** — Bermuda Commercial Bank providing stable coin channel for cross-border payments
- **"Web 2.5" private institutional network** — Monument putting client deposits on permissionless but private chain
- **Western Union cross-border remittance** — Stablecoin disruption of telegraph-era money transfer

## 10. TONE & STYLE
- **Most skeptical/balanced of the five** — Rob provides genuine US domestic counterpoint; "failing to quite see" domestic utility
- **Heavily physical-world analogized** — "plumbing," "invisible technology," Uber, Lombard lending, private equity
- **Geographically diverse** — US + UK + Bermuda + blockchain foundation = genuinely multi-jurisdictional panel
- **Banker-speak** — liquidity funds, NAV, Lombard, private equity, haircuts, Basel rules
- **Quietly provocative** — Basel/US non-adoption; "poop in the swimming pool" echoes from File 3
- **Practical and grounded** — Phase 1/2/3 sequencing; specific client profiles; real bank regulatory approvals cited
- **Forward-looking but honest** — "These are not simple things to unwind"; "people shouldn't underestimate the financial system that has learned from its scars"

---

# CROSS-CUTTING THEMES — ALL FIVE SCRIPTS

## Theme 1: Regulatory Clarity as Inflection Trigger
Every panel cites the GENIUS Act (Files 1, 2, 4, 5) or equivalent (MiCA in File 4) as the catalyst enabling institutional engagement. The phrase "regulatory certainty" appears in direct or paraphrased form across all five. Without regulation, stablecoins remain niche. With it, the "next 10x" becomes possible. Caroline (File 1): "consequential blockers — lack of knowledge, lack of access, lack of regulatory certainty — are coming down."

## Theme 2: Cross-Border as the Killer App
Every panel — including the most skeptical (File 5, Rob) — agrees that cross-border is where stablecoins deliver undeniable value. "Killer app for crossborder payments" (File 5). "Crossber payments are going to serve an incredible purpose" (File 5). Ripple's entire business is cross-border (File 1). Emerging market remittances at 9% vs. near-zero (File 1).

## Theme 3: Evolutionary, Not Revolutionary
Jean Lewig's phrase (File 1) — "evolutionary not revolutionary" — is the implicit master narrative of all five scripts. File 5 (Farmy): stablecoins existed before blockchain as liquidity funds. File 2 (Caroline echo): agentic payments are like "fancier recurring bill pay." File 4 (Edward): "It's money after all." File 3: compliance is multi-layered not brand new. The framing consistently domesticates stablecoins within familiar financial history.

## Theme 4: The Stack / Layered Architecture
All five panels use stack metaphors. File 3 (Linda): "base layer, L2s, DeFi protocols, interfaces, blockchain analytics, custodians, exchanges." File 2 (Anil): "non-deterministic LLM loop + deterministic policy engine." File 4 (Edward): custody + infrastructure + issuance + on/off-ramp. File 5 (Farmy): "web 2.5." File 3 (Eric): "independent modular escalating protocols." The consistent motif: no single point of control or failure; different layers have different responsibilities.

## Theme 5: Institutional Demand as the Next Phase
Files 1, 2, 4, 5 all mark Q4 2025/2026 as the institutional inflection point. File 4: Fireblocks pipeline — banks exceed crypto-native for first time. File 1: "First $314B driven by retail; next 10x by institutional." File 5: Monument Bank, Bermuda Commercial Bank. File 2: AWS's enterprise customers all investing in agentic AI architecture. The "retail to institutional" transition is the consistent macro frame.

## Theme 6: AI + Stablecoins as Convergent Infrastructure
Files 1 and 2 are most explicit. File 1 (Michael/AWS): "AI + digital assets creates new financial paradigm." MoonPay Agents with Claude integration. McKenzie's $1T agentic payments by 2030. File 2: entire panel on X402, pay-per-use, B2B agent negotiation. File 5 (Wasim): "agentic orchestration; wealth partners in their pocket" in 5 years. File 3: AI as new attack surface for exploits. The AI-stablecoin convergence appears in all five.

## Theme 7: Dollar Hegemony as Geopolitical Frame
File 1 (Lauren): "Stablecoins are a foreign policy tool." File 4 (Sergio): "Dollar power-projecting as its finest tool of geopolitics for 100 years... will be for the next hundred." File 4 (Michael): "Dollar-based digital assets reinforce US economic competitiveness." File 5: Western Union disruption, crossborder dollar access. File 2 (Marcus): 99.9% of stablecoin volume is dollar-denominated (implicit). Stablecoins = dollarization engine.

## Theme 8: Privacy vs. Compliance Are Not Mutually Exclusive
File 3's dominant theme bleeds into Files 4 and 5. File 3 (Anna): "compliance and privacy do not have to be mutually exclusive." File 3 (Matias): ZK enforces rules at point of transaction without mass observability. File 5 (Farmy): public blockchain transparency makes institutional adoption impossible; Midnight provides permissionless but private network. Privacy as "selective disclosure" and proactive compliance — not evasion.

## Theme 9: Banks as Partners, Not Enemies
Every panel explicitly or implicitly rejects the zero-sum framing. File 1 (Lauren): "It is really not zero-sum." File 4 (Nick): "Stablecoin issuers are very complementary to the banks." File 4 (Sergio): JP Morgan partnership. File 5 (Hugo): "Trust and partnerships" as foundation. File 2 (Vincent): policy makers always answer with payments + banks together. The consistent argument: stablecoins improve bank infrastructure and expand banking relationships.

## Theme 10: Invisible Infrastructure as the End State
The 2031 vision across all panels converges on the same point. File 5 (Rob): "Digital asset, stable coin, tokenization all disappear from our language." File 5 (Wasim): "Best technology is invisible — like Uber." File 4 (Edward): "This point around users making decisions about chains... needs to be abstracted away." File 1 (Lauren): "Integrated very seamlessly." File 3 (Linda): technology becomes "a very normal part of the compliance tech stack." The destination in all five: infrastructure you don't think about.

---

## NOTABLE DIRECT QUOTES (CROSS-SCRIPT)

**On the GENIUS Act:**
> "The first major piece of financial services legislation in more than three decades that was not directly responsive to a crisis." — Robin Cook (File 1)

**On stablecoin as evolutionary:**
> "In Mesopotamia, they had rocks. They put little marks on rocks and that was money... why should we have paper in a digital world?" — Jean Lewig (File 1)

**On dollar geopolitics:**
> "Stable coins, I think, ultimately are a foreign policy tool." — Lauren Beliv (File 1)

**On agentic payments:**
> "All these agentic autonomous loops break when they see a payment wall." — Anil (File 2)

**On the FX market:**
> "The addressable market is, in the end, infinite." — Marcus (File 2)

**On compliance fallacy:**
> "If everybody who ever transacted as a counterparty to a bank that let through $500 billion worth of illicit funds [were frozen], it would mean there would be a liquidity crisis on a scale on the planet that nobody could ever buy milk." — Eric (File 3)

**On the tipping point:**
> "We are at one of those rare inflection points where technology, regulation and geopolitics are colliding simultaneously and the outcome is going to reshape how money moves around the world. None of this is theoretical anymore. This is infrastructure." — Moderator (File 4)

**On banks in the pipeline:**
> "Q4 2025 was the first time in the history [of Fireblocks] that the pipeline of banks and payment companies exceeded the number of companies that are fintech and crypto-native." — Michael Scholov (File 4)

**On bank opposition to yield:**
> "It's 100% anti-competitive behavior." — Nick Vanek (File 4)

**On privacy and institutional adoption:**
> "If I ask you where you bank, you might say JP Morgan Chase or Wells Fargo, but you won't tell me your bank account. You won't tell me how much you own in the bank account. As soon as you transact on any public network, any public blockchain, everything you do is transparent and visible forever." — Farmy (File 5)

**On the 2031 vision:**
> "I'm very optimistic that digital asset, stable coin, tokenization all disappear from our language and it just becomes part of the financial fabric." — Rob (File 5)

---

*Synthesis complete. Five video scripts covered: The GENIUS Effect, Agentic Payments, Sanctions/Stablecoin, Consensus 2026, Crypto Rails. Total runtime approximately 178 minutes of conference panel content.*

---
## BATCH 7
---
# Video Script Synthesis — Batch 7
### Files: NYU Stern Part 2 | Regulation AI Stablecoins | Dollar Milkshake | User Trust | ACCESS 2026

---

## FILE 1: 2026 NYU Stern Fintech Conference Part 2

### 1. OVERVIEW
- **Format:** Academic conference presentation — single speaker formal lecture with Q&A outro from moderator
- **Length:** ~28 minutes (transcript ~34KB)
- **Style:** Dense, empirical, quantitative academic; working-paper presentation with slides; methodological walkthrough with policy implications at the end
- **Audience:** Institutional finance professionals, academics, policymakers, fintech practitioners at NYU Stern conference

---

### 2. SPEAKERS & SEGMENTS

**Kathleen DeRose** — Moderator, NYU Stern organizing team. Introduces speaker, frames context, closes with praise.

**Dr. Iñaki Aldasoro** — Principal Economist, Bank for International Settlements (BIS). Joined BIS 2016. Previously consultant for European Systemic Risk Board, European Central Bank, International Monetary Fund. Author/co-author of papers on AI adoption and stablecoin policy implications. Presenting joint work with **Rashad Ahmed** (Anderson Institute).

**Paper:** "Stablecoins and their links with safe assets" — first working paper version April (prior year), updated post-GENIUS Act passage.

**Segment flow:**
- Intro/motivation: stablecoins as Treasury market players
- Methodology overview: local projections, controls, IV approach
- Data sources and sample description (Jan 2021–March 2025)
- Crypto shock series construction
- Case studies: Terra Luna, FTX, US election, Trump meme coin
- Formal results: impulse response functions
- Robustness checks: tenor specificity, liquidity regimes
- Implications: monetary policy, financial stability, reserve transparency
- Moderator close

---

### 3. ALL KEY STATS & DATA

- **Stablecoin Treasury holdings:** On par with largest government money market funds and major foreign jurisdictions as of end of last year (stock basis)
- **Dollar-backed stablecoin T-bill purchases in 2025:** ~$40 billion over the course of the year — "similar to the largest U.S. government money market funds and larger than most foreign purchases"
- **Focus tenor:** Three-month T-bill market — stablecoins' role is "even larger" than in longer maturities
- **Naive (biased) estimate:** 25 basis points decline in T-bill yields per $3.5 billion stablecoin inflow (two standard deviations in sample) — "in the ballpark of a Fed rate cut, which is obviously unrealistically high"
- **Controls-only estimate:** 2 to 4 basis points per $3.5B inflow
- **Baseline IV estimate (preferred):** 2.5 to 3.5 basis points per $3.5B inflow — "more or less comparable to what the literature has found for small-scale QE"
- **Sample period:** Daily data, January 2021 to March 2025
- **Stablecoins studied:** Largest six U.S. dollar-pegged stablecoins (aggregated); USDT and USDC are the dominant contributors
- **Crypto market cap at time of writing:** ~$3 trillion — "dwarfed by traditional financial markets"
- **U.S. Treasury market size:** ~$35 trillion
- **Forward projection at ~$2 trillion stablecoin market cap (TBAC forecast, ~2028):** 9 to 12 basis points yield compression on three-month T-bills (back-of-envelope, requires volatility scaling assumptions)
- **Liquidity regime effect:** Effects "large when liquidity is low, small and statistically not significant when liquidity tends to be high"
- **Case studies:** Terra Luna collapse (May 2022), FTX collapse (November 2022), U.S. election (November 2024), Trump meme coin issuance (early 2025)
- **Average stablecoin market cap jump around case study events:** ~$10 billion
- **10-year yield spillover:** Some estimated impact after 15–20 days (flagged as possible indirect spillover, requires further research)
- **Debt ceiling episodes:** Four major episodes in sample identified via Google Trends data — high concern periods show strongest stablecoin effects on yields

---

### 4. CORE NARRATIVE ARCS

**Arc 1 — From curiosity to systemic relevance:** The paper was written when stablecoins were not yet institutionally prominent; GENIUS Act passage and U.S. official statements validated the research direction after publication. High-ranking officials (Treasury Secretary Bessent, Fed Governor Myron) made "very explicit statements" aligned with the paper's themes.

**Arc 2 — Empirical grounding for a policy debate:** The paper positions itself as "a first attempt to add some empirical grounding" to discussions that had previously been largely theoretical. The methodological contribution is fighting endogeneity with an IV approach.

**Arc 3 — Stablecoins as shadow Treasury investors:** The core thesis is that stablecoins are already a meaningful force in short-term Treasury markets — "stablecoins are already today an important play in Treasury markets, both from a stock and a flow perspective." Their preferred habitat is the three-month T-bill.

**Arc 4 — Scale up, implications scale up:** The back-of-envelope exercise shows that at $2T market cap, the yield compression effect reaches 9–12 basis points — enough to "meaningfully influence the transmission of Fed monetary policy to market-based yields." This mirrors the "Greenspan conundrum" of the 2000s when outsized foreign demand suppressed long-term yields against Fed intentions.

**Arc 5 — Asymmetry and financial stability risk:** The paper argues current estimates are a lower bound because they are estimated in a growing market where stablecoin issuers can time purchases. In fire-sale conditions (runs), liquidation must happen immediately — no discretionary timing. Stablecoins "remain a runnable instrument" subject to potential fire sales.

---

### 5. POSITIONING PILLARS

- **Empirical over theoretical:** Explicitly frames the paper as empirical grounding for conversations that previously lacked data
- **Methodological rigor as credibility:** Devotes substantial time to explaining why naive estimates are wrong and how IV approach corrects for endogeneity
- **Comparability to known phenomena:** Anchors results to small-scale QE, the Greenspan conundrum, and Fed rate cuts — all familiar to the audience
- **State-dependence insight:** The liquidity-regime split is presented as a key update to the baseline results — effects are not constant, they are worst when markets are most fragile
- **Humble on future projections:** Explicitly caveats that institutional money flowing into stablecoins will likely already hold Treasuries, making future net new demand smaller

---

### 6. HOOKS & OPENINGS

- Opening by moderator: "Dr. Aldasoro... the author or co-author of multiple papers on the adoption of both artificial intelligence and the policy implications of stablecoins... going to share his insights from his seminal paper on stablecoin growth and the implications for our financial system."
- Opening data hook: Stablecoins stand "on par with the largest government money market funds" in short-term Treasury holdings
- Shock statistic: "$40 billion over the course of the past year, similar to the largest U.S. government money market funds and larger than most foreign purchases"
- GENIUS Act as validation: "The issue really took off a bit later as the Genius Act moved through its legislative process and was finally approved in July."
- Policy implication teaser: "A growing stablecoin market may eventually suppress short-term yields to an extent that meaningfully influences the transmission of Fed monetary policy."

---

### 7. RECURRING PHRASES & LANGUAGE

- "Preferred habitat" — used to describe stablecoins' concentration in three-month T-bills (pre-GENIUS Act: by revealed preference; post-GENIUS Act: by regulatory requirement)
- "Back of the envelope" — self-deprecating framing for the forward projection exercise
- "Kitchen sink" — "we're basically throwing the entire kitchen sink in terms of trying to kill the effect"
- "State-dependent effects" — the liquidity-regime-conditional finding
- "Naive linear projections" / "naive version" — 25bp estimate dismissed as biased
- "Local projections" / "impulse response function" — methodology terminology used throughout
- "Crypto shock series" — the instrument, described as "the unforecastable component of the Bloomberg Galaxy Crypto Index" after purging financial market developments
- "Blurring the lines between crypto markets and traditional finance" — closing framing
- "Fire sales" / "runnable instrument" — financial stability risk language
- "Greenspan conundrum" — historical analogy for monetary policy transmission failure
- "Grain of salt" — explicit caution about forward projections
- "Two standard deviations" — $3.5B stablecoin inflow as the unit of analysis throughout

---

### 8. COMPANIES/PROTOCOLS MENTIONED

- **Tether (USDT):** Largest contributor to stablecoin flows; mentioned as rotating in/out during Terra Luna and SVB events
- **Circle (USDC):** Second-largest; mentioned specifically for lower Treasury bill exposure versus Tether; rotations described during SVB and Terra Luna
- **Terra Luna:** Case study outflow event, May 2022
- **FTX:** Case study outflow event, November 2022
- **Anderson Institute:** Rashad Ahmed's affiliation (co-author)
- **Bank for International Settlements (BIS):** Speaker's institution; paper published on BIS website
- **ECB (European Central Bank):** BIS/ECB colleagues co-developed crypto shock series in related paper
- **Bloomberg Galaxy Crypto Index:** Used to construct crypto shock instrument
- **Goldman Sachs:** Financial Condition Index (FCI) used as control variable
- **Treasury Borrowing Advisory Committee (TBAC):** Source of ~$2T 2028 market cap forecast
- **Fed (Federal Reserve):** Monetary policy interaction discussed; overnight reverse repo facility used for liquidity regime classification; FOMC meeting windows used for monetary policy shock construction

---

### 9. USE CASES HIGHLIGHTED

- Stablecoins as **de facto Treasury investors** — the primary use case studied
- Stablecoins as **settlement assets within crypto** — described as having "established themselves as a sort of a settlement asset within crypto space" and correlating with crypto activity
- **Reserve asset composition** — policy implication around reserve transparency and audit visibility
- **Monetary policy transmission channel** — yield compression as unintended consequence of stablecoin growth
- **Financial stability risk** — run potential and fire-sale dynamics in Treasury markets

---

### 10. TONE & STYLE

Strictly **academic/empirical**. Methodologically dense, self-correcting, careful about causality. Frequent hedging ("we suggest the possibility," "I am somewhat skeptical," "one should take with a grain of salt"). Uses analogies to make methodology accessible (Greenspan conundrum, Fed rate cut as benchmark). Policy recommendations are cautious and framed as implications rather than prescriptions. The overall affect is rigorous, credible, and dry — the opposite of promotional.

---
---

## FILE 2: Regulation AI Stablecoins Video Script

### 1. OVERVIEW
- **Format:** Multi-speaker panel discussion at a fintech/digital assets conference (described as "the digital dollar revolution" panel)
- **Length:** ~27 minutes (transcript ~35KB)
- **Style:** Conversational, entrepreneurial, occasionally political; a mix of startup founder energy, political commentary, and venture/investment perspective; audience engagement format
- **Audience:** Crypto/fintech investors, founders, entrepreneurs; likely a mixed audience at a conference with strong crypto-native presence; moderator Owen Laauo is from Clear Street (fintech research)

---

### 2. SPEAKERS & SEGMENTS

**Owen Laauo** — Moderator; research analyst at Clear Street covering fintech. Frames questions, manages panel flow.

**Reeve Collins** — Co-founder and chairman of Stable (STBL/Stablecoin 2.0 project); also co-founder of Tether. The veteran voice of the panel; offers origin story and future vision.

**Joe Amio** — Senior portfolio manager, Galaxy Fintech Fund. Investment analysis perspective; explains bear market dynamics.

**San Jeffrey** — Chief Business Development Officer, DIFC (Dubai International Financial Centre). International regulatory/hub perspective; pitches Dubai.

**Francis Suarez** — 43rd Mayor of Miami. Political/city-level crypto advocacy perspective; Bitcoin salary, Miami as crypto hub.

**Chapter breakdown by timestamp:**
- Ch.1: Introduction and panel framing
- Ch.2: Reeve Collins on co-founding Tether 12 years ago
- Ch.3: "We formatted the dollar so it could work on a blockchain"
- Ch.4: Stablecoins proven — institutions ready
- Ch.5: Biden vs. Trump on crypto
- Ch.6: "A tale of two cities" — regulation by enforcement
- Ch.7: David Sachs and the GENIUS Act
- Ch.8: Nobody wants a letter from the SEC or the FBI
- Ch.9: When you overregulate, you're saying people aren't smart enough
- Ch.10: Bear market drivers since October 10th
- Ch.11: Four-year cycle and self-fulfilling prophecy
- Ch.12: Global monetary policy: Great to Good environment
- Ch.13: AI angst rippling through markets
- Ch.14: Dubai's pitch to founders and investors
- Ch.15–17: DIFC details, tax incentives
- Ch.18: Multipolar world — Miami, Dubai, Singapore
- Ch.19: Miami stats
- Ch.20–31: Bear market impact, stablecoin/RWA adoption, Stablecoin 2.0, predictions

---

### 3. ALL KEY STATS & DATA

- **USDT + USDC combined market share:** ~84% of total global stablecoin market
- **Tether founding:** 12 years ago from time of recording
- **DIFC stats:** 52,000 people; 8,000 companies; 1,000 regulated firms; 500+ asset managers; one-third of asset managers are alternatives; 100+ hedge funds
- **DIFC tax rate:** 0% corporate tax for companies under $750 million annual revenue (global minimum tax exemption); 0% income tax for non-US nationals
- **Dubai ultra-high-net-worth attraction:** ~9,500 ultra-high-net-worth individuals and families per year
- **Miami real estate growth (reference period):** 100% growth in real property value over 8 years
- **AUM-based companies moved to Miami:** "$13 trillion in AUM based companies that moved to Miami"
- **Miami venture capital pipeline:** Increased 500%+ during Suarez's term
- **Miami crypto investment increase (one year):** 2,200%; "number one in the nation for crypto investments"
- **Mayor Suarez's Bitcoin salary:** "First elected official in America paid in Bitcoin" — paid for a year and a half at cost average $30,000; "still 100% up on my Bitcoin salary"
- **Stablecoin 2.0 minimum investment reduction:** AI agents will reduce minimum investment "all the way down to a dollar"
- **Prediction for onchain asset explosion:** "10x, 100x, a thousandx asset explosion of the onchain economy"
- **GENIUS Act passage:** Referenced as passed in July (prior year from recording)
- **US Series A funding lost to regulatory friction:** "40% of Series A funding gets spent in sorting out what is still a fragmented kind of regulatory landscape" in the US
- **Bear market trigger:** October 10th identified as "a big liquidation event, a historic unwind of positioning"

---

### 4. CORE NARRATIVE ARCS

**Arc 1 — Origin to legitimacy:** Reeve Collins frames Tether's founding 12 years ago as democratization of the dollar. The problems that motivated Tether "still exist today" in traditional finance — slow, expensive, layered rails. But now the world is at an inflection: "regulation is finally there," "blockchain has been proven," institutions are ready.

**Arc 2 — Regulatory whiplash (Biden vs. Trump):** Francis Suarez delivers a political contrast narrative. Biden era = "regulation by enforcement," hostile, unclear rules drove innovation offshore and contributed to crises. Trump era = David Sachs, GENIUS Act, "clear set of rules," innovation-friendly. The GENIUS Act is framed as "generational."

**Arc 3 — The bear market as a feature, not a bug:** Joe Amio argues the current downturn is unique because "price and infrastructure are decoupling." Institutional stablecoin adoption, tokenization pilots, and RWA activity are accelerating even as prices fall — "extremely bullish." The four-year cycle, AI angst, and shifting monetary policy backdrop explain the price weakness without undermining the long-term thesis.

**Arc 4 — Multipolar capital geography:** The world is fracturing into three financial hubs — the Americas (Miami), Middle East (Dubai/DIFC), Asia (Singapore/Hong Kong). Crypto is the connective tissue. Each panelist pitches their node.

**Arc 5 — Stablecoin 2.0 as the next evolution:** Reeve Collins introduces his new project (Stable/STBL) as solving two problems with current stablecoins: collateral opacity (solved via tokenized RWA as on-chain collateral) and yield capture (yield split into a separate token, returned to users rather than kept by issuer). This is framed as "the promise of blockchain."

**Arc 6 — AI + blockchain convergence:** Stablecoins and RWAs are described as the necessary financial rails for AI agents. "An agent's not going to wait for Monday morning for a bank to open up." AI agents need 24/7, frictionless, cross-border financial infrastructure.

---

### 5. POSITIONING PILLARS

- **"We formatted the dollar so it could work on a blockchain"** — Tether origin story as the simplest possible frame for stablecoins
- **Democratization narrative:** Stablecoins = access to dollars for the unbanked, for the world outside the US
- **Infrastructure vs. speculation:** Bear market is when real builders build; "just because there are fewer Ferraris doesn't mean you stop building roads"
- **Stablecoin 2.0 as the corrective:** Current issuers keep yield; Stablecoin 2.0 returns yield to users; tokenized collateral replaces audit opacity
- **AI as the demand driver:** AI agents will require stablecoins and RWAs to operate; this is the new demand layer
- **Regulatory clarity as unlock:** GENIUS Act is the gate that opened — "trillions of dollars on the sidelines" will flow in

---

### 6. HOOKS & OPENINGS

- Chapter title hook: "We formatted the dollar so it could work on a blockchain" (Reeve Collins, most quotable line)
- Political drama hook: "It's been like a tale of two cities" (Suarez on Biden vs. Trump)
- Fear hook: "Nobody wants to get a letter from the SEC or the FBI. I promise you that."
- Bear market contrarian hook: "This is the first downturn we've seen in digital asset markets where price and infrastructure are decoupling."
- Dubai pitch hook: "If you're under $750 million in annual revenue... you will be subject to a 0% corporate tax rate. That's a pretty good tax rate."
- AI agent hook: "An agent's not going to wait for Monday morning for a bank to open up, you know, and they're not going to send seven wires through correspondent banks to get money from Miami to Dubai."
- Prediction hook: "10, 100x, a thousandx asset explosion of the onchain economy"

---

### 7. RECURRING PHRASES & LANGUAGE

- "Formatted the dollar so it could work on a blockchain" — Tether's founding thesis compressed to one line
- "Democratization of the dollar" — stablecoin as financial inclusion tool
- "The traditional financial system still operates the same way it always did. Very slow, inexpensive [sic], lots of layers and regulations"
- "Regulation by enforcement" — Biden-era crypto policy characterization
- "A tale of two cities" — Biden vs. Trump contrast
- "Price and infrastructure are decoupling" — Joe Amio's key bear market framing
- "Just because there are fewer Ferraris on the road, you're not going to stop building roads" — DIFC analog for building infrastructure during downturns
- "An agent's not going to wait for Monday morning for a bank to open up" — AI agent use case framing
- "All the catchphrases that we've been saying in this industry for a decade, but now it's actually prime time"
- "Trillions of dollars on the sidelines" — institutional money waiting for regulatory clarity
- "Stablecoin 2.0" — Reeve Collins's brand name for next-generation yield-bearing stablecoins with RWA collateral
- "The promise of blockchain" / "the promise of web 3" — that those who put money in should reap rewards
- "Four-year cycle" — Bitcoin cycle mystique
- "Creating wealth is not viewed as a negative thing" — Dubai/Miami culture pitch
- "Multipolar world" — geopolitical framework for three-hub crypto geography
- "Agentic economy" — the AI agent economy requiring crypto rails

---

### 8. COMPANIES/PROTOCOLS MENTIONED

- **Tether (USDT):** Reeve Collins is co-founder; dominates market with 84% market share alongside USDC
- **Circle (USDC):** Named as the other 84% partner; traditional issuer model critiqued by Stablecoin 2.0
- **Stable / STBL (Universal Stablecoin / USST):** Reeve Collins's new project — Stablecoin 2.0; yield-bearing, RWA-collateralized
- **Galaxy (Galaxy Fintech Fund):** Joe Amio's employer
- **DIFC (Dubai International Financial Centre):** San Jeffrey's institution; 52K people, 8K companies, 0% tax
- **Visa and Mastercard:** Named as integrating stablecoin technology (bullish signal)
- **New York Stock Exchange, NASDAQ, DTCC:** Named as piloting 24/7 tokenized equity trading — "a huge market structure change"
- **BlackRock:** Referenced obliquely ("maybe the next BlackRock-sized RWA fund originates from Dubai")
- **SEC:** Mentioned as source of regulatory threat ("letter from the SEC")
- **FBI:** Mentioned alongside SEC as enforcement risk
- **David Sachs:** Named as Trump's crypto/AI czar/"crypto task force" leader — "one of the most innovative, creative, and brilliant people in the US and in the world"
- **GENIUS Act:** Regulatory framework; passed July (prior year)
- **MetaPlanet:** Referenced briefly in context of Bitcoin treasury companies

---

### 9. USE CASES HIGHLIGHTED

- **Dollar access for unbanked populations globally** — Tether's original mission
- **Cross-border money movement** — "move money globally instantly and for free"
- **AI agent payments** — stablecoins as the 24/7 settlement rails for the agentic economy
- **Portfolio optimization by AI agents** — AI making "a million investments... across the board" via tokenized RWAs down to $1 minimum
- **Yield-bearing savings** — Stablecoin 2.0 separating yield token from principal token; users earn yield on their dollar holdings
- **RWA tokenization** — "all traditional assets are going to be formatted in those formats"
- **24/7 tokenized equity trading** — NYSE/NASDAQ/DTCC pilot
- **Real estate tokenization in Dubai** — mentioned as concrete RWA conversation happening

---

### 10. TONE & STYLE

**Entrepreneurial-optimistic with political flavor.** The panel has the energy of a crypto conference circa 2021 but seasoned by regulatory experience. Reeve Collins is measured and visionary. Joe Amio brings institutional discipline. Francis Suarez is the political showman — quotable, blunt, personal. San Jeffrey is the smooth international pitch. The overall tone is bullish, forward-looking, but acknowledges the bear market directly rather than dismissing it. The panel celebrates the GENIUS Act as a watershed moment and paints AI+stablecoin convergence as the next frontier.

---
---

## FILE 3: The Dollar Milkshake Meets Stablecoins

### 1. OVERVIEW
- **Format:** Podcast/conference panel — three-speaker conversation; two guests plus an implied host/moderator (host unnamed)
- **Length:** ~24 minutes (transcript ~31KB)
- **Style:** Macro-finance intellectual debate; conversational but substantive; explores geopolitical, monetary, and crypto dimensions; no slides or data — pure discussion
- **Audience:** Macro-focused crypto investors, Bitcoin holders, macro traders; people familiar with the Dollar Milkshake Theory

---

### 2. SPEAKERS & SEGMENTS

**Host (unnamed)** — Asks questions, bridges between speakers; references Dylan as "the face of MetaPlanet."

**Brent Johnson** — Described as "the legendary Bitcoin bear" (though actually a gold/dollar bull who is not anti-Bitcoin but skeptical of Bitcoin as reserve currency replacement). Creator of the Dollar Milkshake Theory. Gold bug, libertarian. Works in macro finance.

**Dylan LeClair** — Associated with MetaPlanet (Bitcoin treasury company based in Japan). Younger macro analyst; self-described "cipher punk anarchist Bitcoiner" turned institutional interface.

**Segments:**
- What is the Dollar Milkshake Theory (Brent explains)
- Dollar structural strength: is it happening? (Dylan)
- Dollar index levels and timing (Brent)
- Geopolitical fracturing: economics to power (Brent)
- Bitcoin as geopolitical asset — Russia FX freeze, IRGC stablecoin seizures, censorship risk
- Are stablecoins dampening Bitcoin price? (Brent thesis; Dylan debates)
- Why US stablecoin regulation may protect Bitcoin (Brent)
- Stablecoins as turbocharger for dollar hegemony (Brent)
- Where Bitcoin fits in the milkshake endgame (Dylan)
- Bitcoin treasury companies, volatility, MetaPlanet Japan companies
- The "gradually then suddenly" dollar endgame scenario
- Closing: "Buy Bitcoin, maybe buy some gold"

---

### 3. ALL KEY STATS & DATA

- **Dollar index at start of Milkshake Theory:** ~90
- **Dollar index at time of recording:** ~98
- **Dollar index 2022 high:** 134
- **Dollar endgame threshold mentioned:** If dollar breaks above 115, "could see a gap to 125–130 pretty quickly"
- **Bitcoin treasury company math:** If Bitcoin goes up "10, 11, 12, 13, 14% a year, Sailor's going to be a giant. MSTR is going to be a giant. MetaPlanet's going to be a giant."
- **MetaPlanet Japan competitors:** 10 other Japanese companies followed MetaPlanet into Bitcoin; "nine out of 10 have come out and apologized to shareholders"
- **Bitcoin price prediction:** "I could see if Bitcoin goes to a million dollars, it will not surprise me"
- **IRGC stablecoin seizure:** "A couple weeks ago" from recording
- **Gulf countries:** Sold gold for dollars, asked for swap line from Bessant
- **Bitcoin volatility:** Referenced as having dropped a lot over the last decade; expected to continue declining

---

### 4. CORE NARRATIVE ARCS

**Arc 1 — The Dollar Milkshake Theory:** The world printed money; the US has "the biggest straw" and sucks up all liquidity. The dollar rises vs. all other fiat currencies not because it's good but because all others are worse. Fiat currencies always return to zero, but the dollar is "last to fail."

**Arc 2 — Stablecoins as the ultimate milkshake turbocharger:** This is Brent's central insight in the conversation. Pre-stablecoins, someone in Argentina wanting dollars needed black market access. Post-stablecoins, dollar access is frictionless. The US is "rewiring and replumbing the entire global monetary system" without forcing it — local citizens willingly adopt because the dollar stablecoin "is better than their local currency." This "drains sovereignty from local governments" and spreads US influence "like wildfire." It is "almost more difficult for a foreign country to protect against this than to protect against military action... because citizens want dollars, they don't want bombs."

**Arc 3 — The censorship paradox:** Both Russia FX freeze and IRGC stablecoin seizures demonstrate that stablecoins are not bearer assets — they can be frozen. Brent says the Russian FX freeze "will ultimately be seen as a mistake" because it accelerated geopolitical competition. But the world is finding it very hard to actually dedollarize without "massive pain."

**Arc 4 — Do stablecoins dampen Bitcoin?** Brent's thesis: entities previously using Bitcoin to circumvent sanctions are now using Tether instead. This substitution effect has "dampened Bitcoin's price." Dylan partially agrees but also notes stablecoin liquidity is "a net benefactor to the overall crypto complex." Unresolved: is this latent Bitcoin demand or a genuine substitute?

**Arc 5 — Stablecoin regulation protects Bitcoin:** Brent argues that if the US wants stablecoins to be viable, it has to be "very careful about attacking other digital systems" — and Bitcoin benefits from this regulatory umbrella.

**Arc 6 — Bitcoin's role in the milkshake endgame:** Dylan frames Bitcoin as the asset that captures the debasement of USD against "a basket of everything you would ever want to own." The dollar milkshake theory and Bitcoin are not contradictory — dollar wins vs. other fiat currencies; Bitcoin wins vs. the dollar over long time frames. Brent: "I could see Bitcoin go to a million dollars" because they'll have to print money, and the rest of the world will print even more.

---

### 5. POSITIONING PILLARS

- **"The US has the biggest straw"** — the central milkshake metaphor
- **Stablecoins = voluntary dollarization** — the world adopts dollar stablecoins because they're superior to local currencies, not because the US forces them to
- **Dollar hegemony extended, not ended, by crypto** — counter-narrative to crypto-as-dollar-killer thesis
- **The "last to fail" framework** — not defending dollar, just observing relative trajectory
- **Bitcoin as the escape hatch** — for those fighting for liberty, Bitcoin will be their money; but central banks adopting Bitcoin as reserve asset is unlikely
- **Volatility as the real Bitcoin enterprise adoption barrier** — not price direction, but unpredictability
- **Gradually then suddenly** — dollar endgame described as a threshold event, not gradual

---

### 6. HOOKS & OPENINGS

- Title frame: "The legendary Bitcoin bear Brent Johnson" — sets up intellectual tension
- Theory hook: "The United States had the biggest straw and would suck up all that liquidity"
- Argentina frame: "If you were in Argentina... the way you would have to do that is go to get black market dollars from a dollar dealer. Stablecoins change that picture entirely."
- Censorship drama: "The IRGC was using stablecoins and those were frozen" — real-world geopolitical stakes
- Iran payment routes: "The payment options they suggested were Bitcoin, stablecoins, and I think gold."
- Sovereignty drain: "What you're doing is you're draining the sovereignty from the local government."
- Military vs. monetary: "It's almost more difficult for a foreign country to protect against this than to protect against military action. Because the citizens want the dollars, they don't want bombs."
- Bitcoin endgame: "I could see if Bitcoin goes to a million dollars, it will not surprise me."
- Close: "Buy Bitcoin, maybe buy some gold."

---

### 7. RECURRING PHRASES & LANGUAGE

- "Dollar Milkshake Theory" — the central conceptual frame
- "The biggest straw" — US ability to attract global liquidity
- "Fiat currency always returns to its intrinsic value, which is zero" — Brent's foundational view
- "Last to fail" — the dollar's position
- "Dedollarize" / "dedollarization" — the counterforce the theory says will fail
- "Dollarize the world rather than dedollarize the world" — stablecoin paradox
- "Massive pain" — cost of actual dedollarization
- "Bearer asset" — distinguishing gold and Bitcoin from freezable stablecoins
- "Censorship risk" / "seizure risk" — the stablecoin vulnerability Dylan raises
- "Draining the sovereignty" — from local governments to the US dollar system
- "New set of rails" / "rewire and replumb the entire global monetary system"
- "Willingly adopted" — key to the theory; not forced dollarization
- "Spread like wildfire" — pace of dollar hegemony extension via stablecoins
- "Lubricant" — stablecoins as lubricant for Bitcoin's interface with traditional finance (Dylan)
- "Neo bank financial system emerging" — Dylan's framing for the post-2022 crypto infrastructure
- "Bucket shops" — Dylan analogy for 2022 failures (reminiscent of 1900s-era Great Depression stock broking houses)
- "Gradually then suddenly" — borrowed Hemingway framing for dollar endgame acceleration
- "The final endgame" / "full expression of the milkshake theory" — when it "gets away from the Fed"
- "Hyper-financializes" — Wall Street's effect on new asset classes
- "Transmuted" vs. suppressed — volatility cannot be suppressed, only transformed
- "Numerator BTC, denominator USD" — Dylan's framing for Bitcoin price structure

---

### 8. COMPANIES/PROTOCOLS MENTIONED

- **Tether:** Named as the stablecoin used by IRGC; described as "very fast, very efficient, cheap"; still partially outside US regulatory purview but US "getting hands deeper into it"
- **MetaPlanet:** Dylan LeClair's company; Japan's Bitcoin treasury company; 10 companies followed, 9/10 apologized to shareholders
- **Strategy (MicroStrategy / Saylor's company):** Named in Bitcoin treasury company discussion — "If Bitcoin goes up 10%+ a year, Sailor's going to be a giant. MSTR is going to be a giant."
- **IRGC (Iranian Revolutionary Guard Corps):** Had stablecoins frozen by US — real-world censorship example
- **Russia:** FX reserves frozen — geopolitical precedent
- **Iran:** Considering Bitcoin/stablecoins/gold for shipping lane tolls
- **Gulf countries:** Sold gold for dollars, sought swap lines from Bessant
- **Bessant (Treasury Secretary):** Referenced for Gulf swap line negotiations

---

### 9. USE CASES HIGHLIGHTED

- **Dollar access for populations under capital controls** (Argentina example) — stablecoins replace black market dollar access
- **Sanctions circumvention** — Bitcoin and stablecoins as routes around US sanctions (Russia, Iran, IRGC)
- **International shipping toll payment** — Iran's proposed use of Bitcoin/stablecoins/gold
- **Corporate Bitcoin treasury reserve** — Strategy/MetaPlanet model discussed; Brent skeptical of broad corporate adoption due to volatility
- **Bitcoin as monetary exit** — for "those fighting for liberty"

---

### 10. TONE & STYLE

**Macro-intellectual debate.** High signal density, conversational, no slides. Brent Johnson is the elder statesman — measured, paradox-embracing, not a Bitcoin maximalist but not hostile. Dylan LeClair is the younger Bitcoin-native voice who has evolved toward institutional thinking. The tone is intellectually honest about tensions (stablecoins may suppress Bitcoin price; censorship risk is real; dollar milkshake and Bitcoin can coexist). No hype, no promotional language. Closer to a CFA/macro podcast than a crypto YouTube channel. The most geopolitically sophisticated of all five files.

---
---

## FILE 4: User Trust in Stablecoins Video Script

### 1. OVERVIEW
- **Format:** Conference panel discussion — "Stable Summit" event; 5 panelists plus moderator Bianca Buzz; audience Q&A at the end
- **Length:** ~35 minutes (transcript ~32KB)
- **Style:** Practitioner-focused; UX/security/infrastructure lens; technical but accessible; collaborative rather than debate-style
- **Audience:** Crypto/Web3 builders, security engineers, DeFi protocol teams, stablecoin infrastructure developers; Buenos Aires event

---

### 2. SPEAKERS & SEGMENTS

**Bianca Buzz** — Moderator; Head of Deell at Chronicle (Oracle for tokenized assets). Chronicle founded 2017, spun out of Maker in 2023, powers ~$19 billion in assets across DeFi and tokenized assets.

**Julian (Jill)** — Chief Operating Officer, Symbiotic. Builds "an economic coordination layer to secure things that require trust on chain" — staking and economic security building blocks.

**Ron Barat** — Solutions Engineer, Blockade (standing in for Ido who had a personal emergency). Blockade provides Web3 security: wallet support for end users, protocol monitoring, smart contract security, fraud prevention, co-signers.

**Bryce Ferguson** — Co-founder and CEO, Turnkey. Low-level wallet infrastructure. Clients include Bridge, Poly Market, Moonshot, Axiom, Alchemy. Powers key management flows — business stablecoin flows and end-user wallets with web2-style authentication.

**Yugo** — Works at Immunefi. Known from bug bounty world; now "end-to-end onchain security platform" — monitoring, operational security, formal verification, firewall.

**Segments:**
- Round of intros and what each is building
- Card-level UX overview for stablecoins
- What stablecoins must do better than Visa/Mastercard
- Guard rails: watch towers, circuit breakers, spending limits
- Centralized vs. decentralized stablecoins
- Building resilient decentralized stablecoins — best practices
- Trust-building: on-chain vs. off-chain vs. hybrid
- Forward-looking innovations for mainstream credibility
- Audience Q&A on nefarious activities and adoption

---

### 3. ALL KEY STATS & DATA

- **Global stablecoin market cap at time of recording:** ~$297 billion ("last time I checked a few days ago the market was at 297 billion")
- **Chronicle assets powered:** ~$19 billion in assets across DeFi and tokenized assets
- **Chronicle founding:** 2017; spun out of Maker in 2023
- **Rain card lending yield:** 8 or 9% via Morpho (mentioned as current stablecoin neo-bank product)
- **Turnkey clients:** Bridge, Poly Market, Moonshot, Axiom, Alchemy
- **Aave ("a") user insurance announced:** $1 million user funds insurance for balances — described as "really interesting announcement" from two days prior
- **Hypothetical bad mint amount mentioned:** "$300 trillion mint by mistake" — used as humorous example of why monitoring matters
- **Morpho yield:** 8–9% on stablecoin lending

---

### 4. CORE NARRATIVE ARCS

**Arc 1 — UX has largely been solved, security/trust has not:** Multiple panelists agree that the UX for stablecoin payments has improved dramatically. "We're there actually." Cards like Rain work. Yield products on Morpho. "A lot of the UX has been solved over the last couple years." But the core remaining barrier is security and trust: "People feel afraid and stablecoins seem stable but... people call this the unstable summit."

**Arc 2 — Security builds trust, trust brings users:** Ron Barat's core argument: "Once things are secure, trust will increase and then the users will come. If you build it, they will come." The chain is security then trust then adoption. Critical functions (minting, burning, pausing, freezing) must be monitored with automated responses.

**Arc 3 — Stablecoins can destroy Visa/Mastercard in B2B, harder in B2C:** The panel distinguishes retail payments (where Visa/Mastercard work well and are hard to displace) from business payments (where stablecoins can genuinely disrupt — factoring, invoicing automation, eliminating correspondent banking layers). "If you want stablecoin payments to make sense... you should really have the ambition to destroy Visa and Mastercard."

**Arc 4 — Yield as the mass migration trigger:** Julian and Bryce converge on this: mainstream migration to stablecoins in developed markets won't come from "my payment system sucks" — it will come from "I didn't know I could be earning yield on my dollars." The Coinbase yield product, the Aave insurance product — these are the unlock mechanisms. "Putting money to work for the user instead of for the bank."

**Arc 5 — Centralized vs. decentralized trust models:** Yugo distinguishes the two camps. Circle/Tether have regulatory legitimacy path (years-long battle) but opacity in policies. No major exploits yet (Lindy effect). Decentralized players (Pinto, Beanstalk offspring) adopt open security practices. The coming fight: which model wins? Current trend under Trump administration moves away from decentralized governance structures.

**Arc 6 — The hybrid trust path:** Bryce's synthesis: centralized trust will be "the first big wave" to onboard consumers (because that's what they've always known), decentralized will be "the second big wave." Insurance products are the bridge — they combine decentralized assets with centralized guarantees consumers trust.

---

### 5. POSITIONING PILLARS

- **"Security is not just smart contract security — it's also economic security"** — Symbiotic's framing
- **Abstraction as mass adoption:** "The more you can abstract away all of the underlying technology, just the more this will be successful." Users don't need to know what's underneath.
- **Guard rails as a spectrum:** Consumer-facing: hide controls. Business-facing: expose deep controls with smart defaults.
- **Yield as the real disruption:** Not "better payments" — "earning yield on dollars you didn't know you could earn yield on"
- **Money streaming vs. chunky transactions:** Bryce's forward-looking framing — agent-to-agent commerce with streaming money requires fundamentally different security guard rails
- **Don't call them stablecoins:** "99% that don't care about or know crypto... they're just going to use the payments option that works best for them"
- **Not decentralized vs. centralized — hybrid:** The realistic path is centralized first, decentralized second

---

### 6. HOOKS & OPENINGS

- Market size hook: "Last time I checked a few days ago the market was at 297 billion"
- Fear framing: "The next speaker jokingly calls this the unstable summit in Buenos Aires... that's what people feel"
- Credit card trust reframe: "A credit card's major value is fraud prevention — if someone wrecks you, you trust the credit card company will make you whole"
- Bad mint hypothetical: "$300 trillion mint by mistake" — monitoring saves the day
- Visa/Mastercard disruption: "The ambition to destroy Visa and Mastercard and create better networks for payments in the world"
- Yield unlock: "Oh I've been getting screwed by banks for so long I didn't even know that I could be earning yield on my dollars"
- Streaming money: "What does money look like when it is truly streaming in real time? You have agent-to-agent commerce happening in a real way."

---

### 7. RECURRING PHRASES & LANGUAGE

- "Security builds trust, trust brings users" / "If you build it, they will come" — Ron Barat's mantra
- "The unstable summit" — the dark joke about stablecoin fear among mainstream users
- "Lindy effect" — Circle/Tether's trust advantage from operating longest without major exploit
- "Economic security" — Symbiotic's preferred term for staking-backed security; broader than smart contract security
- "Account abstraction" — key technical term for hiding wallet complexity from users
- "Guard rails" — watch towers, circuit breakers, spending limits
- "Mint, burn, pause, freeze" — the four critical monitored functions for any stablecoin issuer
- "Watchtower" — monitoring system; compared and contrasted with oracles
- "On-ramps are still tough" — persistent UX pain point
- "Island of their own" — stablecoins' interoperability gap with traditional finance
- "Connective tissue" — missing piece between stablecoin UX and traditional fiat
- "Rent seeking" — critique of Visa/Mastercard as legacy infrastructure
- "Dinosaurs" — Visa/Mastercard framing (Bianca)
- "Old fat cats" — fee-extracting traditional payment networks
- "Chunk transactions vs. streaming" — Bryce's distinction for future guard rail design
- "Nefarious activities" — audience Q&A term for illicit use; panel unpacks with nuance
- "Anti-financial crime infrastructure" — AML/compliance apparatus on top of Visa/Mastercard
- "Web two style authentication" — Turnkey's approach for abstracting wallet UX
- "Bug bounty world" — Immunefi's reputation frame
- "Virtual card" / "Google Pay or Apple Pay" — near-term practical card integration target

---

### 8. COMPANIES/PROTOCOLS MENTIONED

- **Chronicle:** Moderator Bianca's company; Oracle for tokenized assets; $19B assets; spun out of Maker 2023
- **Symbiotic:** Julian/Jill's company; economic coordination layer; secures CCIP oracles
- **Blockade:** Ron Barat's company; web3 security — wallet, protocol, smart contract, fraud prevention
- **Turnkey:** Bryce Ferguson's company; wallet infrastructure for Bridge, Poly Market, Moonshot, Axiom, Alchemy
- **Immunefi:** Yugo's company; bug bounty to end-to-end onchain security platform
- **Morpho:** Yield protocol; 8–9% lending yield for Rain card users
- **Rain:** Stablecoin neo-bank with card product; cited as good UX example
- **Circle (USDC):** Single-owner minting model; regulatory legitimacy path; opacity in security policies; Lindy effect
- **Tether (USDT):** Named alongside Circle as market leader with Lindy effect
- **Pinto:** Decentralized stablecoin; offspring of Beanstalk; cited as new project with good security approach
- **Beanstalk:** Predecessor to Pinto; oblique Terra reference
- **Terra/Luna:** Named as cautionary tale ("not doing what Terra did"); also referenced as "Luna incidents" that scare users
- **Aave ("a"):** $1 million user fund insurance announcement; yield product attracting users
- **Coinbase:** Yield product attracting users; "trusted brand" framing
- **Uniswap:** Referenced as "unification of a bunch of entities"; Stani went on governance forum to criticize their approach to decentralized governance vs. the "a model"
- **Visa / Mastercard:** Target for disruption; "dinosaurs" / "old fat cats" / "rent seeking"
- **CCIP (Chainlink Cross-Chain Interoperability Protocol):** Symbiotic secures CCIP oracles through staking

---

### 9. USE CASES HIGHLIGHTED

- **Stablecoin savings accounts / yield-bearing** — the primary mass adoption unlock; earning yield instead of banks; $1M insured accounts
- **Stablecoin debit/credit cards** (Rain example) — near-term retail payments
- **B2B payments** — factoring, invoicing automation, eliminating correspondent banking friction
- **Agent-to-agent payments** — streaming money for AI agents operating 24/7
- **Protocol security monitoring** — watch towers for minting/burning/pausing/freezing
- **Slashing / economic security enforcement** — oracle watchtowers with stake-based consequences
- **Multi-currency stablecoins** — Euro, Canadian dollar denominated; described as "not competitive yet to build" but necessary for complete disruption

---

### 10. TONE & STYLE

**Practitioner-collaborative.** This is the most technically grounded and operationally focused of the five files. The panelists are all builders — they discuss specific protocols, specific security mechanisms, specific UX patterns. The tone is honest about remaining challenges without being pessimistic. There is humor (the "unstable summit" joke, the "$300 trillion mint by mistake" hypothetical, the Lindy effect on Circle's luck). The panel is intellectually honest about what stablecoins can't yet do well (replace Visa/Mastercard for retail, handle chargebacks, provide credit). The most nuanced treatment of centralized vs. decentralized stablecoin trust models across all five files.

---
---

## FILE 5: ACCESS 2026 Stablecoins Video Script

### 1. OVERVIEW
- **Format:** Institutional panel at the New York Stock Exchange; "ACCESS" conference sponsored by Halbourne; 5 speakers plus moderator Sarah Hammer from Charles Schwab
- **Length:** ~28 minutes (transcript ~32KB)
- **Style:** Institutional finance/regulatory; formal, careful, precise; legal and compliance-aware; infrastructure and settlement focus
- **Audience:** Institutional finance professionals — bank executives, digital asset leads, fintech infrastructure companies, tokenization practitioners; NYSE setting signals seriousness

---

### 2. SPEAKERS & SEGMENTS

**Sarah Hammer** — Moderator; Charles Schwab.

**Jen Lacier** — Head of Digital Assets, Standard Chartered, Europe/UK/Americas. UK-headquartered bank, 120+ years in US, operating in 50+ markets; focus on emerging markets in Africa/Asia/Middle East. No US retail activity. Client demand: multinational corporates, cross-border money movement.

**Tom Sullivan** — Leads product solutions for DTCC digital assets. Previously served on digital asset markets subcommittee for global markets advisory committee to the CFTC. DTCC acquired "Currency" (tokenization company) two years ago.

**Steve** — Kido — "digital asset blockchain infrastructure company" used broadly across financial services for cash tokens in financial transactions. Has worked with 20+ central banks on CBDC projects.

**Henry** — Founder and CEO, DGFT (based in Singapore). MAS-licensed decentralized exchange — "first in the world to get licensed as a decentralized exchange for security tokens including equities." Now also called "RWAs."

**Segments:**
- Near-term bank use cases: retail payments vs. cross-border vs. treasury vs. capital market settlement
- DTCC: moving from pilots to production; legal/operational constraints
- DTCC blockchain announcement and closed vs. open systems
- Engineering differences: stablecoins vs. CBDCs vs. tokenized deposits
- CBDC use case evolution (20+ central banks)
- Tokenized deposits: the most exciting category for banks
- Regulatory gaps for scaling tokenized deposits globally
- Standards across jurisdictions as key need
- Scale underestimation as the biggest institutional mistake
- Regulatory/operational requirements for digital money at scale
- Close

---

### 3. ALL KEY STATS & DATA

- **Standard Chartered global footprint:** 120+ years in US; operating in 50+ markets
- **DTCC assets in custody:** $100 trillion — "potentially all of the assets that we hold in custody" eligible for tokenization under SEC no-action relief
- **DTCC acquisition:** Acquired "Currency" (tokenization company) approximately 2 years ago
- **DTCC blockchain announcement:** Canon blockchain named as first; expecting multiple chains; open to both permissioned and public chains
- **Kido CBDC work:** 20+ central banks globally
- **DGFT asset classes on platform:** UBS (money market fund), Wellington (money market fund), Invesco (high-yield fund, daily liquidity), DBS (structured notes with BTC performance mapping)
- **DBS:** Largest Southeast Asia bank; first structured note on chain; underlying maps to BTC performance
- **GENIUS Act passage:** "Over the summer" — now past; unlocking "real opportunity to move from pilot to production"
- **CFTC advisory committee recommendation:** "The rapper doesn't matter and you can use tokenized assets for collateral purposes" — endorsed by Commissioner Fam at end of last year
- **JD Vance quote (TokeniZon 2025 summit, May):** "Stablecoin is DeFi" — stablecoin owners can choose to store/use money on chain with "minimum or almost zero dependency on intermediary"
- **Time in traditional finance for DGFT CEO Henry:** "More than 20 years"
- **China CBDC:** Referenced as operational — Standard Chartered operates in China; e-CNY is a real CBDC Standard Chartered deals with

---

### 4. CORE NARRATIVE ARCS

**Arc 1 — From pilots to production:** DTCC's Tom Sullivan frames this as the central industry moment: "We think those days are ending soon" — the days of controlled two-party pilots and press releases. The GENIUS Act passing, SEC no-action relief, and CFTC advisory endorsements are creating the regulatory floor for scale. But the "Clarity Act" for securities has not yet passed, and gaps remain.

**Arc 2 — Money on chain as the foundation:** Henry (DGFT) provides the clearest conceptual framing for why stablecoins, CBDCs, and tokenized deposits all matter: they are all "money on chain." Once money is on-chain and assets are on-chain, you can do token-to-token transactions — eliminating the fiat conversion round-trip. This fundamentally changes both "how to pay" and "how to invest/earn."

**Arc 3 — The bank's three choices with stablecoins:** Steve (Kido) names the three strategic plays for any bank: (1) bank one of the stablecoin players (web2 revenue quickly), (2) launch your own stablecoin (JPMorgan JPM Coin model), (3) use existing stablecoins and find ways to incorporate for end customers. Which door you go through "greatly influences the different engineering and work you can do."

**Arc 4 — Tokenized deposits as the most exciting category:** Steve argues "if you're a bank and you're not thinking about tokenized deposits, you're probably a bit behind where the midpoint of the market is." Every bank is asking: how do we respond to potential capital flight from stablecoins? Tokenized deposits are the defensive play and the innovation opportunity simultaneously.

**Arc 5 — CBDCs honing in on specific use cases:** The CBDC evolution arc: years ago, central banks invited use cases. Then focus on settlement leg (RTGS efficiency). Now: very specific use cases like collateral management — "a better sign towards this pilot to production evolution." Kido worked with 20+ central banks through this evolution.

**Arc 6 — Standards, not harmony:** Tom Sullivan's closing take: "Having standards across jurisdictions — it doesn't have to be regulatory harmony — standards across jurisdictions is the way to go." Jen Lacier flags the unresolved questions: credential treatment, jurisdictional supervisory overlap (who owns a cross-border transaction in flight?), and whether tokenized deposits are legally equivalent to bank deposits "with all the protections that they have today."

**Arc 7 — Scale is underestimated:** Steve's key warning: "The scale aspect of it is really underestimated... you make a bunch of compromises on the tech to get there and then day two you realize there's no way to get to the actual volumes or scale that I need to get to."

---

### 5. POSITIONING PILLARS

- **"The rapper doesn't matter"** — CFTC advisory framing: the type of tokenized asset (stablecoin, CBDC, tokenized deposit) matters less than the legal and use-case clarity
- **"Money on chain" as unifying concept** — Henry's framing collapses the stablecoin/CBDC/tokenized deposit distinction into one idea
- **"Wise people think alike"** — Henry's observation that every major global jurisdiction is working on digital money; not coincidental
- **Closed to open systems** — DTCC's 50-year closed system is opening via blockchain; first the Canon chain, then multiple chains including public
- **Siloed to networked** — Jen Lacier's framing: current activity is siloed in individual assets/jurisdictions; the goal is to knit together a globally interoperable institutional digital money system
- **Amazon-started-with-books analogy** — Henry explains tokenization starts with simple/vanilla assets (money market funds, T-bills), then moves up the risk/complexity chain

---

### 6. HOOKS & OPENINGS

- NYSE setting hook — "here at the New York Stock Exchange" (Sarah Hammer opening)
- $100 trillion hook: "DTCC holds $100 trillion worth of assets and potentially all of those can be tokenized"
- Convergence hook (JD Vance): "Stablecoin is DeFi" — coming from the Vice President of the United States at a blockchain summit
- Standard Chartered cross-border pain point: "Moving money around the world particularly in Africa, Asia and the Middle East" — concrete emerging markets use case
- DBS structured note: "Mapping to BTC performance" — convergence of web2/web3 through Singapore's largest bank
- Scale warning: "Day two you realize there's no way to get to the actual volumes or scale that I need to get to"
- Global convergence close: "No major jurisdiction missing [from] working on this one from the regulatory perspective... all the people think this is the future and they're moving fast"

---

### 7. RECURRING PHRASES & LANGUAGE

- "Pilot to production" — the central transition the panel discusses; Tom Sullivan uses it repeatedly
- "The rapper doesn't matter" — CFTC advisory committee's phrase for tokenized asset interoperability
- "Money on chain" — Henry's unifying concept for stablecoins, CBDCs, and tokenized deposits
- "Siloed" — Jen Lacier's description of current activity in individual asset types and jurisdictions
- "Knit together" — Jen's aspiration for interoperable cross-border digital money
- "Walled garden" — protection mechanism for early production deployments
- "Regulatory harmony" — term used and then questioned ("I don't know how I feel about the label of harmony")
- "Standards across jurisdictions" — Tom Sullivan's preferred alternative to "harmony"
- "Day two problems" — Steve (Kido) on scale challenges discovered post-launch
- "Cash tokens" — Kido's generic term for stablecoins, CBDCs, tokenized deposits
- "Bearer token or not" — key legal distinction for tokenized deposit instruments
- "Possession or control" — SEC requirement for DTCC's blockchain custody arrangement
- "Closed system to open system" — DTCC's 50-year transition
- "Wise people think alike" — Henry's close on global regulatory convergence
- "Modernizing the institutional movement of money" — Standard Chartered's framing vs. replacing retail payment rails
- "Crossborder efficiency and speed" — largest client demand category for Standard Chartered
- "Amazon started with books" — Henry's tokenization progression analogy

---

### 8. COMPANIES/PROTOCOLS MENTIONED

- **Standard Chartered:** Head of Digital Assets Jen Lacier; UK HQ, 50+ markets, 120+ years US presence; no US retail; multinational corporate client base; operates in China with e-CNY
- **DTCC (Depository Trust & Clearing Corporation):** Tom Sullivan; member-based DAO analogy; acquired Currency; $100T assets; SEC no-action relief; Canon blockchain first chain; transitioning from closed to open system
- **Kido:** Steve's company; digital asset blockchain infrastructure; 20+ central banks; used across financial services for cash token transactions
- **DGFT:** Henry's company; Singapore MAS-licensed DEX; first licensed decentralized exchange for security tokens/equities/RWAs
- **UBS:** Money market fund on DGFT; "UBS Global Initiative"
- **Wellington:** Money market fund on DGFT
- **Invesco:** High-yield fund on DGFT; daily liquidity
- **DBS (Development Bank of Singapore):** Largest Southeast Asia bank; structured notes on DGFT; BTC-performance underlying
- **Halbourne:** Event sponsor
- **Charles Schwab:** Sarah Hammer's employer
- **SEC:** No-action relief granted to DTCC; Clarity Act not yet passed
- **CFTC:** Tom Sullivan served on digital asset markets subcommittee; advisory committee endorsed "rapper doesn't matter" recommendation; Commissioner Fam endorsement
- **MAS (Monetary Authority of Singapore):** Henry's regulator; described as "regulated central bank and SEC and all the others under one name"
- **Canon blockchain:** First blockchain named in DTCC's tokenization announcement
- **LSCG:** Referenced by Jen Lacier for recent tokenized deposit announcement
- **JPMorgan / HSBC:** Named as examples of centralized architecture ("JP Morgan cannot talk to HSBC in Hong Kong in London")
- **SWIFT:** Named as current cross-bank payment requirement
- **China / e-CNY:** The one operational CBDC that Standard Chartered actually deals with daily
- **JD Vance (then Vice President):** Quoted from TokeniZon 2025 summit — "Stablecoin is DeFi"
- **GENIUS Act:** Referenced as passed "over the summer"; unlocking pilot-to-production transition

---

### 9. USE CASES HIGHLIGHTED

- **Cross-border treasury and FX risk management** — Standard Chartered's primary near-term use case; Africa/Asia/Middle East corridors
- **Institutional collateral management** — CFTC advisory endorsement; DTCC tokenization; CBDCs for collateral pledging/depledging
- **24/7 tokenized equity trading** — DTCC/NYSE/NASDAQ (mentioned in other panels; DTCC confirms tokenizing $100T in custody)
- **Interbank settlement (alternative to RTGS)** — CBDC use case studied
- **Tokenized money market funds** — UBS, Wellington on DGFT; simplest vanilla starting point
- **Tokenized high-yield funds** — Invesco on DGFT; daily liquidity
- **Tokenized structured notes** — DBS on DGFT; BTC performance underlying; convergence of web2/web3
- **Token-to-token investment** — Henry's vision: once money is on chain and assets are on chain, direct token swaps eliminate fiat round-trip
- **CBDC collateral management** — specific narrow use case where CBDCs are now focused
- **Bank tokenized deposits** — response to stablecoin competition; defensive and offensive play

---

### 10. TONE & STYLE

**Institutional-formal and regulatory-precise.** The most conservative and compliance-aware of all five files. Sarah Hammer explicitly notes Tom Sullivan's joke about "playing a lawyer on TV" — this is an audience that cares about legal permissibility, regulatory frameworks, and supervisory oversight. The tone is optimistic but measured; every opportunity is paired with a regulatory caveat or open question. Henry provides the most visionary framing from Asia (DeFi/MAS/DGFT), which contrasts with the careful bank-speak from Standard Chartered and DTCC. The GENIUS Act is treated as a green light but not a solution to all remaining questions. The panel ends with explicit calls for standards, scale planning, and global regulatory convergence — not hype.

---
---

## CROSS-CUTTING THEMES ACROSS ALL FIVE FILES

### Theme 1: The GENIUS Act as Watershed Moment
All five files reference the GENIUS Act as the pivotal regulatory event that transformed the stablecoin landscape from uncertainty to clarity. The BIS paper notes it moved the paper from academic exercise to policy-relevant empirical grounding. The Regulation/AI panel (File 2) features Francis Suarez calling it "generational." The Dollar Milkshake panel doesn't name it directly but frames US regulatory blessing as key. The User Trust panel references Trump-era regulatory shifts. The ACCESS panel (File 5) explicitly frames the GENIUS Act as the unlock for "pilot to production." The GENIUS Act is the single most referenced regulatory event across the entire corpus.

### Theme 2: Stablecoins as T-Bill / Treasury Infrastructure
File 1 (BIS paper) documents this empirically — $40B in T-bill purchases, 2.5–3.5bp yield compression per $3.5B inflow, effects concentrated in the 3-month tenor. File 2 (Regulation/AI) identifies Tether and Circle as institutions that buy treasuries and keep the yield — which Stablecoin 2.0 seeks to disrupt. File 5 (ACCESS) addresses this from the institutional infrastructure side — DTCC tokenizing $100T in custody, CFTC endorsing tokenized assets for collateral. The stablecoin-Treasury nexus is both the largest current use case and the largest systemic risk.

### Theme 3: Price vs. Infrastructure Decoupling
File 2 introduces this explicitly: "This is the first downturn where price and infrastructure are decoupling." File 4 (User Trust) echoes this — the bear market is when real security infrastructure gets built. File 3 (Dollar Milkshake) doesn't use this language but implicitly agrees — the dollar milkshake theory doesn't depend on crypto prices. File 5 (ACCESS) is entirely indifferent to crypto prices — it's about institutional infrastructure. The consensus: the price downturn is irrelevant to the infrastructure buildout.

### Theme 4: AI Agents as the Demand Frontier
File 2 is most explicit: "An agent's not going to wait for Monday morning for a bank to open up... they're not going to send seven wires through correspondent banks." File 4 echoes: "What does money look like when it is truly streaming in real time? You have agent-to-agent commerce happening." Reeve Collins (File 2): AI agents will make "a million investments for you" via tokenized RWAs down to $1 minimum. This theme is absent from File 1 (academic) and File 3 (macro), and present but secondary in File 5. AI agents represent the emerging demand driver that all builder-facing panels agree will be the next wave.

### Theme 5: Dollar Hegemony Extension, Not Replacement
File 3 (Dollar Milkshake) makes this most explicitly — stablecoins are "the biggest turbocharger" on dollar dominance; they "dollarize the world rather than dedollarize it." File 2 implicitly agrees — Reeve Collins's original Tether thesis was dollar democratization globally. File 1 documents the treasury market implications. File 5 shows institutional infrastructure aligning with this (CFTC, SEC, DTCC all operating in dollar-denominated tokenized assets). No file makes a credible case for stablecoins threatening the dollar; they universally reinforce it.

### Theme 6: Trust as the Adoption Bottleneck
File 4 (User Trust) is entirely organized around this. Yugo: "Security builds trust, trust brings users." Bryce: "If you build it, they will come." The centralized vs. decentralized debate is really a debate about which model achieves sufficient trust fastest. File 2 echoes: institutions are ready because trust has been built through years of operation. File 5 (ACCESS) frames regulatory clarity as the institutional trust mechanism. File 3 notes that stablecoins can be frozen (trust vs. censorship resistance tradeoff). Trust — variously achieved through security, regulation, or Lindy effect — is the single most commonly cited adoption barrier across all five files.

### Theme 7: The Three-Hub World
File 2 explicitly maps it: Miami (Americas hub), Dubai/DIFC (Middle East hub), Singapore/Hong Kong (Asia hub). File 5 has Henry from Singapore representing the Asia node. File 3 discusses geopolitical fracturing from "economics to power" as the macro frame. The multipolar world is both a geopolitical observation and a competitive pitch — each panelist is simultaneously analyzing the world and marketing their node within it.

### Theme 8: Centralized vs. Decentralized Tension (Unresolved)
File 4 is most direct: Circle/Tether's Lindy effect vs. decentralized protocols' open security practices. The Trump-era regulatory environment favors centralized models. Stani (Aave) pushes back on Uniswap's governance consolidation. File 2 positions Stablecoin 2.0 as a hybrid — using RWA collateral on-chain (decentralized transparency) with centralized issuer architecture. File 5 (ACCESS) skirts the question — focuses on institutional tokenized deposits which are inherently centralized. None of the files resolves this tension; they all acknowledge it and position their solution accordingly.

### Theme 9: Scale Is Harder Than Pilots
File 5's Steve (Kido) is most direct: "Day two problems" — institutions underestimate scale requirements and make tech compromises to launch that prevent actual volume. File 1 (BIS) implicitly addresses this — the paper explicitly caveats that estimates at current scale may not extrapolate linearly. File 4 (User Trust) addresses scale from a trust/security perspective — more users means more attack surface. File 2 dismisses the current bear market as irrelevant to eventual scale. The leap from pilot to production at institutional scale is the central unresolved operational challenge in the institutional panels.

### Theme 10: Yield as the Mass Consumer Unlock
File 4 is clearest: yield on dollar balances — currently captured by banks — becomes available to consumers via stablecoins. The Coinbase product, the Aave ($1M insured) product, Morpho's 8–9% — these are the adoption triggers. File 2 frames Stablecoin 2.0 as addressing the yield problem at the protocol level — programmatically returning yield to token holders. File 5 implicitly backs this via tokenized money market fund access on DGFT. Yield democratization is the consumer-facing complement to the institutional infrastructure buildout.

---

*Synthesis covers all five files. Total estimated original transcript content: ~164KB. All major speakers, statistics, frameworks, language patterns, and entity references documented.*

---
## BATCH 8
---
# Video Script Synthesis — Batch 8 (9 Scripts)
**Files covered:** NYU Stern Fintech Conference, Operational Stablecoin (MoneyGram), Configurable Privacy (Stellar/Boundless), Corporate Adoption (Noble), Onchain FX (Celo), Flipping USDC (Polaris/Frankencoin), Nightfall Stablecoin, Neobanks Stablecoin

---

## FILE 1: 2026 NYU Stern Fintech Conference

### 1. OVERVIEW
- **Format:** Academic conference keynote — single speaker (Ronit Ghose, Citi) introduced by host (Kathleen DeRose)
- **Length:** ~30 minutes (estimated from transcript density)
- **Style:** Structured policy/analyst briefing — slide-driven, formal, authoritative; balances data with macro narrative
- **Audience:** NYU Stern students (undergrad, MBA, master's, executives), academics, finance practitioners, ~1,000 attendees

### 2. SPEAKERS & SEGMENTS
**Kathleen DeRose** — Director, FinTech Initiative, Fubon Center for Technology, Business & Innovation; Finance Professor, NYU Stern. Frames the conference theme ("Betting on the Future"), establishes stablecoins as one of three "hottest topics in FinTech today." Introduces Ghose as having produced "one of the most well-documented forecasts for stable coin adoption."

**Ronit Ghose** — Runs the Future of Finance team at Citi Global Insights ("Citi's thought leadership unit"); based in Dubai; author of *Future Money* (2024); 30+ years analyzing financial markets. Primary speaker covering:
- What stablecoins are and why now
- The legal/definitional framework
- Citi's $1.9T base / $4T bull case forecast for 2030
- Three demand drivers
- Bank tokens vs. stablecoins
- Implications for banks, deposits, Treasuries, credit
- Geopolitical implications and CBDC reaction

### 3. ALL KEY STATS & DATA
- Stablecoin market cap: **"sub $300 billion or around $300 billion"** at time of talk
- Stablecoin turnover: **~$11 trillion** (on Citi's preferred definition)
- Citi 2030 base case forecast: **$1.9 trillion** in issuance
- Citi 2030 bull case: **$4 trillion**
- Earlier "Digital Dollars" report (April prior year): bull case **$3.7T**, base case **$1.6T**
- Conference attendees: **"nearly a thousand people"**
- Prediction markets: **nearly $25 billion a month** of notional volume, "more than double six months ago"
- China's US Treasury holdings: peaked at **$1.2–1.3 trillion** (late 2012–2013); now down to **~$650 billion**
- Foreign ownership of US Treasuries: peaked at **~50% post-GFC**; now down to **~30%**
- Dollar share of central bank FX reserves: now **below 60%** (20–25 year low); including non-fiat reserves (gold): **~45%**
- USD share of global FX trading (BIS data): **~90%**
- Gold holdings in Russia: "as high as they've been in modern history in the last 25 years"
- Countries with real-time payments: **"85, 90 countries"**
- Stablecoin growth timeline: "2025 was a year of project announcements... 2026 is going to be the year of execution and implementation"
- Non-crypto industry stablecoin pickup: forecast **2026 to 2028**
- AI agents: "billions of AI agents doing economic activity on behalf of us 24-7" (Jeremy Allaire/Circle CEO view)
- Tokenized deposit interoperability: noted as "one major shortcoming"

### 4. CORE NARRATIVE ARCS
**Arc 1 — The Infrastructure Moment:** Stablecoins are not speculative crypto; they are a change to "digital and financial infrastructure." Regulation (GENIUS Act, MiCA, Singapore, UAE) has transformed stablecoins from promise to regulated liability.

**Arc 2 — The Money Taxonomy:** Ghose carefully distinguishes central bank money → commercial bank money → stablecoins → bank tokens. Pre-GENIUS Act stablecoins lacked legal liability status; post-regulation they are "redeemable at par... a liability of an institution." Cryptocurrencies, by contrast, are "no one's liability."

**Arc 3 — The Three Demand Legs:** (1) existing crypto markets, (2) dollarization demand from non-G10 inflation-prone jurisdictions, (3) domestic onshore industry adoption as a payment option (BNPL analogy — not the only option at checkout, but a new lane).

**Arc 4 — Bank Tokens as Bridge:** Many corporates prefer bank tokens (tokenized deposits) over stablecoins because they maintain existing banking relationships and regulatory familiarity. Major shortcoming: not interoperable. "Watch this space."

**Arc 5 — The Geopolitical Dollar Play:** US Treasuries are losing public sector buyers (China down from $1.2T to $650B; central bank dollar reserves at 20–25 year low). Stablecoins are a replacement private-sector demand source. "Public buyers of dollars going down, private buyers never been more keen."

**Arc 6 — The CBDC Reaction:** US stablecoin push is accelerating CBDC development in China, India, and potentially Europe — not because of consumer payment needs (largely solved) but for geopolitical reasons.

**Arc 7 — Non-Zero-Sum Future:** "Stablecoins, bank tokens, and CBDCs will all grow in the coming five years." Not a battle; complementary.

### 5. POSITIONING PILLARS
- Citi as the authoritative institutional forecaster (forecasts used by US Treasury in GENIUS Act communications)
- Stablecoins as infrastructure upgrade, not crypto speculation
- Bank tokens as the "regulated financial industry's version" of stablecoins
- Dollar geopolitical framing: stablecoins extend dollar dominance where central bank demand is retreating
- "It depends" nuance on deposit cannibalization — deliberately anti-sensationalist

### 6. HOOKS & OPENINGS
- Conference title framing: **"Betting on the Future. That future is ours to shape."**
- Opening stat from host: **"Prediction markets have reached nearly $25 billion a month of notional volume, more than double six months ago"** — establishes pace of change
- Ghose's framing: **"This is a change to digital and financial infrastructure"** — immediate repositioning away from crypto hype
- The AI agent frame: **"billions of AI agents doing economic activity on behalf of us 24-7... the natural instrument... is going to be a stable coin"**

### 7. RECURRING PHRASES & LANGUAGE
- **"Stable coins are a bridge"** — used twice, including as geopolitical bridge
- **"It depends"** / **"it's not a simple A equals B"** — deliberate analytical caution
- **"Bank tokens"** — Ghose's coined term for tokenized deposits / deposit tokens
- **"A liability of the central bank / issuing bank"** — definitional anchor
- **"Watch this space"** — on tokenized deposit interoperability
- **"2025 was a year of project announcements... 2026 is going to be the year of execution"**
- **"Public sector cannot get enough... private sector cannot get enough of dollars"** — schizophrenia framing
- **"Sub $300 billion... a market that's... still relatively small"**
- **"By clear contrast, cryptocurrencies are no one's liability"**
- **"Not a digital zero-sum game"**
- **"TLDR / one-liner"** — signals slide-deck presenter style

### 8. COMPANIES/PROTOCOLS MENTIONED
- **Citi / Citi Institute / Citi Global Insights** — Ghose's employer; issuer of forecasts; Citi report "Stablecoins 2030"
- **Circle** — Jeremy Allaire (CEO) cited on AI agents; Circle mentioned as Layer 1 announcer
- **Stripe, Google** — among companies announcing Layer 1 blockchains
- **TradeWeb, Cal-She, Robinhood, Citibank, Superstate** — listed as conference speakers/participants
- **Bank of International Settlements (BIS)** — cited for FX reserve data
- **US Treasury Department** — used Citi forecasts in GENIUS Act communications
- **Federal Reserve** — cited for deposit flow analysis framework
- **J.P. Morgan, HSBC** — used as examples of commercial bank deposit relationships
- **KLARNA, AFFIRM** — BNPL checkout comparisons (Europe: "Tabis and Tabaras")
- **Starbucks** (implicit in loyalty program discussion)
- Named countries/regulators: EU (MiCA), Singapore, UAE, China, India, Russia, Germany, France

### 9. USE CASES HIGHLIGHTED
- Cross-border payments (speed, 24/7, settlement in minutes vs. hours/days)
- Dollar proxy for inflation-prone non-G10 jurisdictions
- Stablecoin at checkout as loyalty/e-commerce option ("bundled into a loyalty program")
- AI agent transactions (24/7 economic activity)
- International treasury management by corporations
- Replacement demand for US Treasuries (demand-side fiscal benefit)
- Tokenized deposits for large corporate multi-currency cross-border flows

### 10. TONE & STYLE
Authoritative institutional analyst. Deliberately measured — repeatedly hedges ("it depends," "conditional," "it might seem like a cop-out"). Slide-driven with chapter structure. Occasional self-aware asides ("in my career of almost 30-plus years"). Geopolitically sophisticated — frames stablecoins inside the dollar reserve currency debate. Academic in intellectual rigor, practitioner in market experience. Not promotional. No crypto enthusiasm; treats stablecoins as financial infrastructure.

---

## FILE 2: Operational Stablecoin Video Transcript (MoneyGram)

### 1. OVERVIEW
- **Format:** Conference interview / fireside chat — two speakers on stage at "Stable Summit"
- **Length:** ~18 minutes
- **Style:** Conversational, startup-founder energy mixed with established-company pivot story; anecdote-heavy, personal and authentic
- **Audience:** Stablecoin conference attendees — crypto-native and fintech professionals

### 2. SPEAKERS & SEGMENTS
**Dante Reminik** — Leads stablecoin initiatives at "Holiday Payments" (deposit/payout solutions); interviewer/host. Recently married (noted in opening).

**Josh** (surname not given) — Head of digital/stablecoin at MoneyGram; previously co-founded Pangia (digital-first remittance company, founded 2012, ran 10 years, sold the company). Joined MoneyGram ~1.5 years prior after Madison Dearborn private equity acquired MoneyGram. Manages all "digitally funded remittances."

Key segments:
- Josh's background and why he joined MoneyGram
- Why stablecoins vs. earlier Bitcoin experiments failed
- MoneyGram's MGUSD stablecoin launch announcement
- Treasury use of stables ($2B/year in backend flows)
- Consumer wallet (El Salvador, Ghana, Colombia)
- The "global Venmo" vision
- 500,000 agent network as global ATM
- Kraken partnership
- Buy-in across the organization

### 3. ALL KEY STATS & DATA
- MoneyGram stablecoin treasury flows: **"over $2 billion this year"** through stables for treasury purposes
- MoneyGram agent network: **500,000 agents globally** — larger combined than Subway + McDonald's + 7-Eleven + Walmart
- Consumer wallet live in: **3 countries** (El Salvador, Ghana, Colombia) at time of recording
- Expansion target: **"over a hundred [countries] by the end of the year"**
- MoneyGram company age: **85 years** (noted; Josh describes it as "startup-paced" inside)
- Stablecoin team size at MoneyGram: **"about 25 maybe 30 folks"**
- Pangia founding: **2012** (Bitcoin was $100 at launch of their CTO's suggestion)
- Kraken partnership: **~6 weeks prior** to recording
- MoneyGram founded: **~85 years prior** (per Josh: "85-year-old company")

### 4. CORE NARRATIVE ARCS
**Arc 1 — The Netflix/Blockbuster Reframe:** Josh's initial resistance to joining MoneyGram ("seems like joining Blockbuster"). Pivot: MoneyGram has irreplaceable regulatory relationships, licenses, and agent network that took "billions and decades to build." The opportunity: add a great consumer app.

**Arc 2 — Crypto Journey:** Founded Pangia in 2012 during Bitcoin's rise. Asked constantly "what's your Bitcoin strategy?" Tried fiat-to-Bitcoin-to-fiat. "None of it really moved the needle." Stablecoins different: non-volatile, scalable across 200 countries without country-by-country setup.

**Arc 3 — Treasury to Consumer:** MoneyGram has used stables for backend treasury for years ($2B/year). MGUSD is a consumer play — not forcing partners but building receiver-side wallet products with yield benefit.

**Arc 4 — The Receiver as Customer:** Traditional remittance only monetizes the sender. Stablecoin balance on receiver side makes receiver a customer too ("potentially doubling your customer base immediately"). Receiver side is "in general less financially served" — bigger layered opportunity.

**Arc 5 — Global ATM via Agent Network:** Agent network (500K locations) becomes on/off-ramp for digital wallet. Agents weren't losing volume to digital — now they're gaining transactions through the balance/ATM model. Conflict resolved.

**Arc 6 — Infrastructure Not Crypto:** "Our customers don't care that it's MGUSD or USDC or whatever it is... they care that it's dollar denominated." Stablecoins should be invisible infrastructure. "My grandma uses Visa. She has no idea what an acquiring bank or an issuing bank is. Same thing is going to happen with the stablecoin stack."

### 5. POSITIONING PILLARS
- MoneyGram as "built-for-the-moment" reinvention of a legacy company — not a startup pretending to be big, not a big company afraid of change
- Stablecoins as the first time crypto has "real practical value" for remittance
- Consumer experience over technology: hide the rails, show the dollars
- Receiver-side monetization as the untapped frontier
- "Leapfrogging" — not catching up, building as if from scratch today

### 6. HOOKS & OPENINGS
- The Netflix/Blockbuster analogy: **"Why would I ever join MoneyGram? It seems like Netflix people join Blockbuster."**
- The CTO regret: **"Our CTO said 'You should just put all that [first million raised] in Bitcoin' — it was $100 each."**
- The size context: **"If you take Subway, McDonald's, 7-Eleven, and Walmart and you combine them, they have fewer than 500,000 locations globally."**

### 7. RECURRING PHRASES & LANGUAGE
- **"Leapfrogging"** — internal MoneyGram term for not just reaching parity but building as if from today
- **"Global Venmo"** — aspirational product vision for MoneyGram post-stablecoin
- **"Table stakes"** — used for treasury use of stables (the basics are already done)
- **"Speed of rolling out websites"** — for scaling country coverage on stablecoin rails vs. fiat rails
- **"Send-receive to in-or-out and in-or-out"** — describing the business model shift
- **"Hidden from consumers... disclosed and explicitly accepted"** — threading the needle on crypto disclosure
- **"The hardest part is done"** — on completion of infrastructure build (licenses, on/off ramps already in place)
- **"Fun summer of announcements"** — teaser for upcoming news
- **"Small teams go faster"** — MoneyGram organizational philosophy despite company-wide buy-in

### 8. COMPANIES/PROTOCOLS MENTIONED
- **MoneyGram** — 85-year-old remittance company, now stablecoin issuer (MGUSD)
- **Holiday Payments** — Dante's employer; deposit/payout solutions
- **Pangia** — Josh's prior company (founded 2012, remittance, sold after ~10 years)
- **Madison Dearborn** — Private equity firm that acquired MoneyGram
- **Kraken** — Exchange partnership: Kraken users can use MoneyGram on/off-ramps globally
- **Walmart** — Agent comparison for scale; also mentioned as exploring "Walmart dollars"
- **MetaMask** — mentioned as example of non-custodial crypto wallet
- **USDC / Circle** — Josh misspoke "USDC" when he meant "MGUSD" — revealing moment about commodity nature of stablecoins
- Countries: El Salvador, Ghana, Colombia, Venezuela, France

### 9. USE CASES HIGHLIGHTED
- **Backend treasury/float:** Moving $2B+/year using stablecoins to reduce negative float and speed up settlement
- **Dollar-denominated savings for receiving countries:** USD access in El Salvador, Ghana, Colombia (and 100+ by year-end)
- **Cash pickup alternative:** Venezuela example — partial cash, partial MGUSD digital hold
- **Receiver-side financial inclusion:** Building layered financial services for the less-served receiver demographic
- **Global ATM network:** Using 500K agent network as on/off-ramp for digital wallet
- **B2B and business disbursements:** Mentioned as future directions
- **Exchange on/off-ramp:** Kraken users accessing MoneyGram rails

### 10. TONE & STYLE
Conversational, startup-founder authentic. Josh is self-deprecating and funny (Bitcoin regret story, Netflix/Blockbuster). Dante is a warm interviewer who has clearly pre-briefed well. Zero jargon — deliberately consumer-accessible even in a crypto conference context. Energy is optimistic but grounded in practical operational realities. The tone feels like a founder telling a genuine pivot story rather than a polished PR narrative.

---

## FILE 3: Configurable Privacy Video Script (Stellar/Boundless)

### 1. OVERVIEW
- **Format:** Conference panel — two speakers in dialogue; audience Q&A at end
- **Length:** ~21 minutes
- **Style:** Technical conversation between practitioners; moderately dense on cryptographic concepts but kept accessible; collaborative rather than competitive
- **Audience:** Technical builders, DeFi/blockchain developers, institutional payment operators at a crypto conference

### 2. SPEAKERS & SEGMENTS
**Tomer** (surname not given) — Appears to be from SDF (Stellar Development Foundation); references "I work for SDF." Leads the technical explanation of Stellar's privacy approach (Protocol X-ray upgrade, cryptographic primitives, configurable privacy menu).

**Dmer (or similar name — likely "Damur")** — From Boundless; introduces himself as building "the Boundless Digital Stack" — a modular framework for institutional deployment. Building a "shielded vault."

Audience member (unnamed) asks the closing question about privacy for permissionless individuals.

Segments:
- Opening: Stellar Protocol X-ray upgrade (January)
- Configurable privacy defined — two dimensions: guarantees + administrative controls
- Confidential tokens (hide amounts, keep identities visible) — payroll use case
- Privacy pools (hide sender/receiver) — mixing, association sets
- Administrative control menu: selective disclosure, view keys, global audit keys, clawback
- Boundless's approach: ZK proofs bringing offchain compliance logic onchain; modular stack
- ZK as primary but not only privacy technology
- Confidential DeFi: private swaps, private lending, composability challenge
- Timeline: composable proofs by end of 2026
- Open source as trust foundation
- Permissionless individual use case (audience Q&A)

### 3. ALL KEY STATS & DATA
- Stellar Protocol upgrade: **"X-ray"** — BN254 curve, hash functions enabling ZK primitives; launched "early January"
- Composable ZK proofs timeline: **"by the end of 2026 we're going to see something like that"**
- Cost of launching own chain: **"six to seven figures to actually run the chain"** — barrier Boundless aims to eliminate
- Compliance integration partners mentioned: **Theorem Labs**, **Comply Advantage** (traditional compliance tooling)
- Projects collaborating on privacy: **Nethermind**, **Open Zeppelin**, **Confidential Token Association**
- Stellar Private Payments: open-source package released in collaboration with Nethermind

### 4. CORE NARRATIVE ARCS
**Arc 1 — Modular Privacy Philosophy:** Stellar's L1 must remain "open, neutral, and transparent." Privacy lives in layers above, not baked into the base protocol. This respects institutional need for auditability while enabling configurable options.

**Arc 2 — The Spectrum of Privacy:** Privacy is not binary. Confidentiality (hide amounts, keep identities) vs. full anonymity (hide everything) are different products for different use cases. Payroll needs the former; fully private DeFi needs the latter.

**Arc 3 — The Compliance Catch-Up Problem:** "The world of compliance is not really caught up to the world of private blockchains." Therefore, build a menu of administrative options rather than committing to one compliance model. Selective disclosure, audit keys, association sets, clawback — offer all options.

**Arc 4 — ZK as On-Chain Compliance Bridge:** Boundless's innovation — whatever compliance logic you run offchain (AML tools like Theorem Labs, Comply Advantage), you can bring it onchain via ZK proofs. Compliance verified without revealing the underlying data.

**Arc 5 — Open Source as Non-Negotiable:** For ZK specifically, open source is critical because "ZK can be so opaque sometimes that without having this clear visibility it will be very challenging to get confidence in this technology."

**Arc 6 — Institutions Need Other Institutions:** The audience question about permissionless individuals gets a sharp answer: "for 10 years in crypto we've been dealing with the ideological version of privacy... It's hardly ever used because it's not very useful." For individuals to use private payments, they need the on/off-ramps that only institutions provide.

### 5. POSITIONING PILLARS
- Stellar as the open, neutral, auditable L1 that privacy builds on top of (not into)
- Boundless's modular framework as the anti-thesis of "launch your own chain" — reduces institutional entry cost to near zero
- ZK as compliance bridge — not privacy vs. compliance but privacy enabled via compliance proofs
- The "menu" model: institutions choose their privacy/compliance configuration rather than accept a one-size-fits-all solution
- Open source as the only credible path to institutional trust in privacy tech

### 6. HOOKS & OPENINGS
- Opening frame: **"Stellar has been very forefront in that kind of innovation and you know like early January you basically made a protocol upgrade to the network that enabled basically the primitives"** — establishes Stellar as ahead of the field
- Closing hook (audience Q&A): **"If we want adoption for everyone, not just for the institutions... if an individual wants to be able to receive a payment from the company that they work with... you actually need the institutions in play."**

### 7. RECURRING PHRASES & LANGUAGE
- **"Configurable privacy"** — the central concept; repeated throughout
- **"Menu of administrative options"** / **"menu of configurable privacy options"** — architecture metaphor
- **"Modular"** — used by both speakers to describe their approach
- **"Open, neutral, and transparent"** — Stellar L1 properties (repeated)
- **"Spectrum of privacy"** — from confidentiality to full anonymity
- **"Confidential tokens"** — hide amounts, keep identities
- **"Privacy pools"** — hide identities, mixing component
- **"Selective disclosure"** / **"view keys"** — ad hoc proof of source of funds
- **"Global audit keys"** — law enforcement access mechanism
- **"Association sets"** / **"non-association sets"** — gating mechanism for privacy pools
- **"Bring it onchain"** — ZK compliance bridge concept
- **"Six to seven figures to actually run the chain"** — cost barrier for competitors
- **"Composable proofs"** — the research frontier for confidential DeFi
- **"Ideological version of privacy"** — dismissal of peer-to-peer crypto privacy that sees no adoption

### 8. COMPANIES/PROTOCOLS MENTIONED
- **Stellar / SDF (Stellar Development Foundation)** — L1 host; Protocol X-ray upgrade
- **Boundless** — Building modular institutional payment stack on Stellar; shielded vault; "Boundless Digital Stack"
- **Nethermind** — Collaborator on Stellar Private Payments open-source package
- **Open Zeppelin** — Collaborator; Confidential Token Association
- **Theorem Labs** — ZK-based compliance tooling integration
- **Comply Advantage** — Traditional AML/compliance tooling (Boundless integrating)
- **Confidential Token Association** — Standards body for confidential tokens on Stellar

### 9. USE CASES HIGHLIGHTED
- **Payroll:** Know employer/employee identities, hide salary amounts and transaction history — confidential tokens ideal
- **Institutional capital deployment on public chain:** Privacy to protect trading strategies and counterparty information
- **Regulatory compliance onchain:** Bringing existing AML/KYC logic onchain via ZK proofs
- **Private lending/swaps (confidential DeFi):** Single use case possible now; composability across use cases by end of 2026
- **Law enforcement access:** Non-selective disclosure via audit keys for specific records
- **Self-sovereign privacy:** Selective disclosure to prove source of funds without revealing to the world

### 10. TONE & STYLE
Technical but not exclusionary. Both speakers are practitioners thinking out loud together — collaborative not competitive. Tomer is more structured/professor-like; Dmer is more visionary/builder. The Q&A answer is the most pointed moment — a pragmatic slap at ideological crypto privacy advocates. No hype; the focus is on building real institutional products. Pace is measured, with natural hesitation suggesting unscripted authenticity.

---

## FILE 4: Corporate Adoption of Stablecoins Video Script (Noble)

### 1. OVERVIEW
- **Format:** Conference presentation / solo stage talk — single speaker with slide deck
- **Length:** ~13 minutes (with timestamp references)
- **Style:** Startup pitch meets industry thesis presentation; evangelistic but data-grounded; includes live app demo (20-second video referenced)
- **Audience:** Stablecoin Summit attendees — sophisticated audience explicitly acknowledged ("This is a very sophisticated audience. Everybody at this point knows what a stable coin is")

### 2. SPEAKERS & SEGMENTS
**Unnamed speaker** (Noble founder) — "I started Noble over three years ago." Runs Noble, described as "the first purpose-built stable coin issuance protocol." Chapters in transcript:
1. Introduction / payments infrastructure problem
2. Stablecoins for mainstream payments
3. Noble's platform overview
4. Market drivers for adoption
5. Merchant stablecoins and retail strategy
6. Loyalty programs and rewards flywheel
7. Wallet experience and customer incentives

### 3. ALL KEY STATS & DATA
- Stablecoin market cap at time of talk: **"plus of 300 billion"** (Noble started when it was half that — ~$150B)
- Noble chain volume: **"over 20 billion"** grown; **"hundreds of millions of assets minted on chain"**
- Citi 2030 projection cited: **"over three trillion"** (projections for stablecoin market)
- Payment infrastructure age: **"legacy systems from the 70s, 80s"**
- Interchange fees: **"3 to 4%... hundreds of billions of dollars paid in card fees"**
- Block times: **"half a second block times"** mentioned as competitive threshold with card networks
- Noble chain transition: EVM ref client + Commonware consensus mechanism (also used by Stripe's Tempo chain)
- Stablecoins supported: multiple named in deck (not listed by name in transcript)
- Noble Dollar: own stablecoin with programmable rewards
- GENIUS Act: passed, making stablecoin "a legal payment instrument" enabling yield distribution to third parties
- Starbucks rewards analogy: customer puts $5 in app — "that's not money, that's a loan to Starbucks"

### 4. CORE NARRATIVE ARCS
**Arc 1 — The Internet/Payments Infrastructure Gap:** "When the modern internet went mainstream in the '90s, we upgraded our telecommunications... And yet the payments infrastructure did not follow suit." Systems are "largely legacy systems from the 70s, 80s."

**Arc 2 — The Trojan Horse Strategy:** "We believe that to scale stablecoin payments, there is an opportunity to use loyalty traditional rewards programs as a Trojan to get customers using stable coins without even knowing it." Consumers don't need to know it's a stablecoin — they just see rewards.

**Arc 3 — Retailers Surrendered Their Relationship:** In the '90s, retailers outsourced payments and loyalty to card networks and banks, gaining programs but losing control. 3-4% interchange fees are "hundreds of billions" in costs. Post-GENIUS, Amazon and Walmart exploring own stablecoins because now they can be "legal payment instruments."

**Arc 4 — The Loyalty Liability Problem:** Points are liabilities on the retailer's balance sheet (not assets until spent). Gift cards expire (breakage economics). Co-branded credit cards are being abandoned by Gen Z. Stablecoin balances flip the model: live accounts earning yield, programmatic rewards, sticky customer relationships.

**Arc 5 — The Rewards Flywheel:** Customer deposits stablecoin → backed by T-bills → generates yield → yield distributed as rewards (per GENIUS Act allowing third-party yield distribution) → promotionality spend funneled back → incremental spend → repeat. "Keeping that flywheel going."

**Arc 6 — Merchant Dollars:** The vision: every major retailer issues their own stablecoin (Amazon dollars, Walmart dollars post-GENIUS). Noble provides the issuance infrastructure. "Put the power back with the retailers."

### 5. POSITIONING PILLARS
- Noble as the infrastructure layer for merchant stablecoins — "first purpose-built stablecoin issuance protocol"
- Trojan horse positioning: stablecoins entering retail through loyalty programs, invisible to consumers
- Retailers as the distribution mechanism for mass stablecoin adoption (not crypto wallets, not banks)
- DeFi gamification mechanics (incentive loops, yield) translated to real-world retail
- GENIUS Act as the unlock that made merchant stablecoins legally viable

### 6. HOOKS & OPENINGS
- **"When the modern internet went mainstream in the '90s, we upgraded our telecommunications systems to make it possible to send an email to somebody across the world at the speed of light. And yet the payments infrastructure did not follow suit."** — Opening statement
- **"We believe that to scale stablecoin payments, there is an opportunity to use loyalty traditional rewards programs as a Trojan to get customers using stable coins without even knowing it."**
- The Starbucks analogy: **"If I put $5 into my Starbucks rewards app, that's not money. That's a loan to Starbucks."**
- The retailer paradox: **"The retailer — they build the brand, they own the distribution, but very oddly they surrender the payments and loyalty piece to card networks and banks."**

### 7. RECURRING PHRASES & LANGUAGE
- **"Trojan"** / **"Trojan your way into"** — central strategic metaphor
- **"Merchant dollars"** / **"Amazon dollars"** / **"Walmart dollars"** — the product category
- **"Flywheel effect"** / **"keeping that flywheel going"** — rewards loop description
- **"Money redefined"** — philosophical positioning of programmable stablecoins
- **"Programmable"** / **"programmability"** / **"baked into them"** — repeatedly applied to stablecoins and rewards
- **"Juicy rewards"** — consumer-facing incentive language
- **"Native internet dollars"** — description of what stablecoins represent
- **"Step function improvement"** — on stablecoins vs. paper money
- **"Without even knowing it"** — stealth adoption strategy
- **"Put the power back with the retailers"**
- **"Gamification incentives... apply that to the real world"** — DeFi mechanics translation
- **"Breakage economics"** — gift card revenue from never-spent balances

### 8. COMPANIES/PROTOCOLS MENTIONED
- **Noble** — Stablecoin issuance protocol; Noble Dollar (own stablecoin)
- **Stripe / Stripe's Tempo chain** — Mentioned as using same Commonware consensus; example of purpose-built payment chain
- **Circle / ARC** — Circle experimenting with its own Layer 1 called ARC
- **Hallborne** (Halborn) — Security partner/auditor ("customers since the very beginning")
- **Amazon** — Exploring "Amazon dollars" post-GENIUS
- **Walmart** — Exploring "Walmart dollars" post-GENIUS; cited from Wall Street Journal report
- **Starbucks** — Loyalty rewards analogy (Starbucks app = loan to Starbucks)
- **Citibank** — Citi 2030 report cited ("thank you so much for the report")
- **Klarna, Affirm** — BNPL as precedent for "option at checkout"
- Regulatory: GENIUS Act (US), "market structure bill"

### 9. USE CASES HIGHLIGHTED
- **Merchant-branded stablecoins (Merchant Dollars):** Retailer issues own stablecoin; customers hold and spend with yield-powered rewards
- **Loyalty program disruption:** Replace points liability with live yield-bearing stablecoin balance
- **E-commerce payments:** Stablecoin as checkout option (BNPL analogy)
- **Customer retention/flywheel:** Programmatic rewards funnel deposits into repeat spend
- **Retail-brand consumer wallet:** App-embedded stablecoin balance replacing traditional gift card / loyalty card
- **Cross-border commerce simplification**
- **High-spend merchant categories** (noble's thesis: Starbucks model doesn't scale; stablecoin model does for big-ticket merchants)

### 10. TONE & STYLE
Evangelical startup pitch. Fast-paced, enthusiastic, chapter-structured with timestamps. Explicitly acknowledges sophisticated audience but still explains concepts. Gratitude-heavy (thanks Citi for the report, thanks Hallborne). Mixes retail consumer language with DeFi mechanics fluently. The "Trojan horse" language is deliberately provocative — positioning mass adoption as something that happens through disguise. Confident, persuasive, commercially focused.

---

## FILE 5: Onchain FX Video Script (Celo)

### 1. OVERVIEW
- **Format:** Conference presentation — solo speaker, slide-driven, ~14 minutes
- **Style:** Analytical/data-driven thesis presentation; references prior speakers (Johannes, Max from Curve); collegiate conference tone
- **Audience:** Stablecoin/DeFi conference attendees; crypto-native and some institutional; global (Africa/LatAm focus prominent)

### 2. SPEAKERS & SEGMENTS
**Unnamed speaker** — "I just rejoined Celo as head of stablecoins" — the role was newly created, signaling stablecoin/FX priority for Celo. Previously at another company. 

Key segments:
- Need for multicurrency stablecoins (agreeing with prior speaker "Johannes")
- FX market size and the case for onchain FX
- Celo's design philosophy: mobile-first, gas fees in any stablecoin, ultra-low fees
- Celo as #1 chain for Tether by weekly active users
- MiniPay wallet (Opera) — product market fit example
- Tether's choice of Celo as second chain after Ethereum
- Mento: onchain FX DEX using oracle-based price discovery
- Infrastructure needs: updown.xyz (leveraged FX perpetuals)
- Dollar volatility / need for non-dollar stablecoins (Swiss Franc, Kenyan shilling, British pound, etc.)

### 3. ALL KEY STATS & DATA
- Global FX market: **$7.5 trillion per day** (BIS estimate) — "the biggest market in the world"
- FX market settlement: **T+2 days** (offline); longer if bank holiday intervenes; not 24/7
- Celo: **#1 chain for Tether by weekly active users** (at time of talk)
- MiniPay (Opera wallet): **close to half a billion transactions**; **more than 15 million active wallets**; **growing in 60 countries**
- Opera browser global users: **~300 million**
- Dollar depreciation: **"over two years the dollar to the euro lost around 16-17%"**; to Swiss Franc "even more"
- Celo gas fees: payable in the stablecoin you're using (USDC for USDC sends, USDT for USDT sends, euro for euro sends)
- Mento: **15 different currencies** accessible onchain
- Non-dollar stablecoin supply: ~$5B gold-pegged + ~$500M euro-pegged vs. **$310 billion total** (referenced from Flipping USDC/Frankencoin context — same event)
- Stablecoin fragmentation: GENIUS-compliant vs. MiCA-compliant stablecoins; yield/non-yield variants

### 4. CORE NARRATIVE ARCS
**Arc 1 — The Dollar Monoculture Problem:** 99%+ of stablecoins are dollar-pegged. But FX risk is real and matters especially in emerging markets and for businesses with local-currency revenue who need local-currency loans.

**Arc 2 — FX Is the Killer App:** The FX market is $7.5T/day. It's the largest market in the world. It settles T+2, isn't 24/7, runs on fragmented rails. Onchain FX is a natural application for blockchain's properties (24/7, instant settlement, programmability).

**Arc 3 — The Entrepreneur in Kenya Argument:** If you're building a business in Kenya with Kenyan shilling revenue, taking a dollar loan exposes you to FX risk. You need a Kenyan shilling stablecoin. The argument extends to Swiss Franks, British pounds, Colombian pesos, Philippine pesos — all live on Celo.

**Arc 4 — Product Market Fit Over TVL:** Repeats the Max (Curve) line: "You can always buy TVL but what you cannot buy is product market fit." MiniPay is cited as the example of genuine product-market fit in web3 — 15M+ wallets, 500M transactions, growing in 60 countries.

**Arc 5 — Infrastructure That Works for Non-Crypto-Natives:** MiniPay abstracts complexity. "You can find new users via their phone number. You can send stablecoin to their phone number. You can swap easily between different currencies." Drag-and-drop pocket swap. Mobile-first for regions where phone = financial access.

**Arc 6 — Tether Validation:** Tether chose Celo as its second chain after Ethereum mainnet (with Anchorage Digital Bank) — a meaningful institutional validation of Celo's user traction.

### 5. POSITIONING PILLARS
- Celo as the multicurrency stablecoin chain — designed from genesis for payments in different currencies
- Mobile-first, ultra-low fees, gas payable in stablecoins — removing every friction point for non-crypto users
- Product market fit as the real metric — not TVL, not chain metrics
- FX market as the macro prize: $7.5T/day, needs new infrastructure
- Local currency stablecoins as financial inclusion tool — not just dollar dollarization
- Mento as the oracle-based onchain FX DEX (different from AMM price discovery)

### 6. HOOKS & OPENINGS
- **"There are more currencies in the world than just the dollar and there can be many interesting use cases for non-dollar stablecoins."**
- Immediately quotes Max from Curve: **"You can always buy TVL but what you cannot buy is product market fit."** — borrowed authority, frames entire talk
- FX market size drop: **"It's the biggest market in the world. There's more than 7.5 trillion dollars in trading every day estimated by the BIS."**

### 7. RECURRING PHRASES & LANGUAGE
- **"You can always buy TVL but you cannot buy product market fit"** — repeated 3x; becomes the talk's refrain
- **"Product market fit"** — central evaluative concept
- **"Multicurrency ecosystem"** / **"multicurrency stablecoins"**
- **"FX risk"** — repeated concern (local business, institutional, individual levels)
- **"Ultra low gas fees"** / **"pay gas fees in [the stablecoin you're using]"**
- **"Mobile"** / **"mobile phone"** — repeated emphasis on mobile-first design
- **"Kenyan shilling stable coin"** / **"Swiss Frank stable coin"** / **"British pound stable coin"** — the concrete currency list
- **"Drag and drop one pocket on the other and then you've swapped"** — MiniPay UX description
- **"The biggest market in the world"** — FX framing

### 8. COMPANIES/PROTOCOLS MENTIONED
- **Celo** — L1 blockchain; focus on stablecoins, FX, mobile, multicurrency
- **MiniPay** — Wallet built by Opera; 15M+ wallets, 500M+ transactions, 60 countries
- **Opera** — Browser company (~300M users globally) that built MiniPay
- **Tether** — Chose Celo as second chain after Ethereum for USDT deployment
- **Anchorage Digital Bank** — Partnered with Tether on Celo USDT launch
- **Mento** — Onchain FX DEX on Celo; 15 currencies; oracle-based price discovery (not AMM)
- **Curve / Max** — Quoted on TVL vs. product-market-fit distinction
- **Johannes** — Prior speaker at same conference (advocated multicurrency stablecoins)
- **updown.xyz** — FX perpetuals DEX for leveraged onchain FX trading
- **Chainlink, Redstone, Pyth** — Oracle providers used by Mento for FX rate feeds
- **BIS** — Source for $7.5T daily FX volume
- GENIUS Act / MiCA — Regulatory compliance frameworks mentioned
- Countries: Kenya, Africa, Latin America, Switzerland, UK, Colombia, Philippines, Singapore

### 9. USE CASES HIGHLIGHTED
- **Cross-border remittances** in local currencies (not just dollar)
- **FX trading onchain:** Mento for spot, updown.xyz for leveraged perpetuals
- **Local-currency business lending:** Entrepreneur in Kenya taking KES loan (not USD)
- **Dollar access in high-inflation emerging markets** (existing use case)
- **Consumer FX swaps:** MiniPay drag-and-drop pocket swapping
- **Mobile-first financial access:** Phone number = wallet address
- **Institutional non-dollar stablecoin use:** Swiss business wanting CHF stablecoin

### 10. TONE & STYLE
Data-anchored, globally minded, inclusive. The speaker references other talks multiple times — conference-collegial. Africa and Latin America feature prominently (not as afterthought but as primary markets). The MiniPay section is almost reverential — genuine excitement about real-world traction. Less promotional than Noble/MoneyGram; more analytical. The FX market framing gives the talk macro weight beyond typical stablecoin discussions.

---

## FILE 6: Flipping USDC (Polaris / Frankencoin — combined from same event)

### 1. OVERVIEW
- **Format:** Two separate conference talks from the same event/day — presented sequentially in the transcript. Speaker 1: Polaris (decentralized stablecoin infrastructure). Speaker 2: Frankencoin (Swiss Franc decentralized stablecoin). They reference each other contextually.
- **Length:** Polaris ~15 minutes; Frankencoin ~11 minutes
- **Style:** Polaris: technical DeFi protocol presentation, fast-paced, complex. Frankencoin: keynote/thesis talk, more philosophical, audience engagement
- **Audience:** Crypto/DeFi conference attendees — likely same "Stable Summit" context; technically sophisticated

### 2. SPEAKERS & SEGMENTS

**SPEAKER 1 — Polaris (unnamed):**
Identifies as "involved in Polaris, building a decentralized stablecoin infrastructure." References Vitalik's three-problem framework as their design brief. References "Lawrence right there" (colleague at conference).

Segments:
- Vitalik's three problems for decentralized stablecoins
- USDC counterparty risk (SVB event)
- MakerDAO/Sky trajectory (DAI → USDS degradation)
- USDE as "risk blank check stablecoin"
- Polaris three-token system: PE (collateral), PUSD (stablecoin), POLAR (stewardship token)
- Bonding curve mechanism and forever-rising floor
- CDP system details
- Beyond-dollar ambition: PCHF, PEURO, PGOLD, "P Big Mac"
- Stewardship vs. governance
- Autonomous market-driven interest rates

**SPEAKER 2 — Frankencoin (unnamed):**
Opening: "Today I'm going to talk about the other 3%." Is Swiss; references speaking at the Bank of England panel in Paris "yesterday." Carries physical book: *History of the Swiss Franc over the last 250 years*.

Segments:
- Dollar dominance analysis (99% of stablecoin market)
- Transactions vs. store of value as two distinct use cases
- T+2 settlement and trapped money supply
- Dollar as poor store of value (Swiss Franc appreciation)
- Tether as one of largest holders of US government debt
- Policy maker concerns (Bank of England, French bank, "head economist of [institution]")
- Frankencoin: decentralized Swiss Franc stablecoin
- Audience Q&A on depeg risk / CDP

### 3. ALL KEY STATS & DATA
**Polaris:**
- USDC SVB depeg: **"trading at 90 cents for a whole weekend"** (3-4 years prior)
- Stablecoin market: **99%+ dollar-pegged** (Vitalik's framing)
- Gold-pegged stablecoins: **~$5 billion** circulating
- Euro-pegged stablecoins: **~$500 million**
- Total stablecoin market: **$310 billion**
- ETH staking yield: **"2.67% six 7% that it is right now"** (noted as approximate)
- Polaris three tokens: PE (collateral via bonding curve), PUSD (USD stablecoin), POLAR (stewardship)
- Polaris ambitions: PUSD, PGOLD, PCHF, PEURO, "P Big Mac"

**Frankencoin:**
- Frankencoin TVL: **~$80 million USD** ("about $80 million US in TVL... in Swiss Frank so in dollar it's a bit more")
- Swiss Franc vs. USD since 1975: **~300% appreciation** ("it's about I think uh 300% appreciation in value")
- Non-dollar stablecoins: **"about or more than actually more than 99%... of the stablecoin market is in dollars"**
- Tether's US Treasury holdings: between Israel and South Korea on the sovereign debt holders list; "I think there's not a single private player that is even closely holding that much US treasury bonds"
- Settlement improvement: Ethereum ~10 seconds; other L1s sub-1 second; vs. T+2 traditional
- Money "stuck in transit": speaker estimates "in the teens or in the twenties [trillion] even... is just constantly stuck somewhere being sent from A to B"

### 4. CORE NARRATIVE ARCS
**Polaris Arcs:**

**Arc 1 — The Three Problems (Vitalik's Framework):** Dollar dominance, oracle problem, staking yield competition. Polaris addresses all three. The oracle problem: using a medianizer approach (from Liquity and Ethics Protocol). The staking yield problem: the bonding curve PE mechanism provides competitive yield without the counterparty of liquid staking tokens.

**Arc 2 — Centralized Stablecoin Risk Catalog:** USDC depegged to $0.90 during SVB crisis. MakerDAO's trajectory from pure ETH-backed DAI → USDC-dependent DAI → real-world-asset-heavy USDS = "each update introduces more counterparty risk." USDE started as basis trade stablecoin but silently became a "real world asset wrapper" — a "risk blank check stablecoin."

**Arc 3 — The Bonding Curve Innovation:** PE (Polaris Ether) is the core collateral token. Users swap ETH against a bonding curve to get PE. The floor price "forever rises" via two mechanisms: (1) swap fees accumulate upward, (2) POLAR tokens can only be created by burning PE — connecting governance to system health. The bonding curve acts as permanent liquidity provider; no withdrawal queue risk like staked ETH.

**Arc 4 — Stewardship Not Governance:** Core system is immutable. POLAR holders (stewards) can only tune parameters within hardcoded ranges. Unlike MakerDAO, stewards can't fundamentally change the system. "The key core system functions like the interest rate decision are fully automated."

**Arc 5 — Beyond the Dollar:** Polaris makes its CDP model available to any team. PCHF, PEURO, PGOLD, "P Big Mac." The system can handle any asset with an oracle — including negative interest rate assets (PCHF, PGOLD).

**Frankencoin Arcs:**

**Arc 1 — Transaction vs. Store of Value:** Most stablecoin discourse focuses on transactions. With instant settlement (10 seconds on Ethereum, sub-second on others), the dollar isn't actually needed — you just need a liquid shared asset for the moment of the swap. But for long-term holding (months, years, decades), denomination matters. The dollar is a poor store of value.

**Arc 2 — The Dollar-as-Treasury Problem:** Every dollar stablecoin effectively means you hold US Treasury risk without getting paid for it. "You hold the risk of the US Treasury, but you don't get paid for it." Tether is one of the largest sovereign bond holders in the world — between Israel and South Korea.

**Arc 3 — Policy Maker Backlash:** Speaking at Bank of England panel, French bank panel. Policymakers say: "either we do something about this now and we become players in that market... or the dollar is just going to eat the world and there's nothing we can do about it."

**Arc 4 — The Swiss Franc Alternative:** CHF has appreciated ~300% vs. USD since 1975. For long-term store of value, for non-dollar financial sovereignty, the Swiss Franc is the argument. Frankencoin is the decentralized digital Swiss Franc. $80M TVL, fully decentralized, high yield, super liquid.

**Arc 5 — Currency Environments Change:** "Do not expect the status quo how it is now to be the status quo in 10 years because things change and currency environments can change very very quickly."

### 5. POSITIONING PILLARS
**Polaris:**
- Trustless by design — immutable core, no governance attack vector
- The bonding curve as the key differentiation vs. liquid staking
- Universal CDP infrastructure — not just one stablecoin but a platform for any currency/commodity
- Autonomous interest rates as the holy grail that others have failed to achieve

**Frankencoin:**
- The "other 3%" — deliberate underdog/contrarian positioning
- Store of value vs. transaction framing — unique angle in stablecoin discourse
- Swiss Franc as empirically superior store of value (300% appreciation)
- Full decentralization + financial sovereignty = no bank can lock your account

### 6. HOOKS & OPENINGS
- Frankencoin: **"Today I'm going to talk about the other 3%."** — immediate contrarian stance
- Polaris: **"USDC was actually trading at 90 cents or something for a whole weekend... people love to think, you know, USDC, USDT, they are super sturdy. They will never fail. Well, USDC himself just failed a few years ago."**
- Frankencoin: **"The dollar is not a very good store of value. I just, you know, put that here into the room. I know I'm in the US."**
- Frankencoin: **"You hold the risk of the US Treasury, but you don't get paid for it."**
- Frankencoin: **"Do not expect the status quo how it is now to be the status quo in 10 years."** — closing statement

### 7. RECURRING PHRASES & LANGUAGE
**Polaris:**
- **"Risk blank check stable coin"** — USDE characterization
- **"Counterparty risk"** — repeated critical theme
- **"Stewardship"** / **"stewards"** — governance model name
- **"Forever rising floor"** — PE mechanism description
- **"Bonding curve"** — core innovation
- **"Immutable"** / **"massively constrained"** — system design properties
- **"Trust minimization"** — design goal
- **"Fully autonomous market-driven interest rate"** — the holy grail
- **"P Big Mac"** — joke-but-not-joke synthetic asset tracker

**Frankencoin:**
- **"The other 3%"** — opening frame
- **"Store of value"** — repeated alternative use case framing
- **"You hold the risk of the US Treasury, but you don't get paid for it"**
- **"Dollar is not a very good store of value"**
- **"The dollar is just going to eat the world"** — policymaker framing
- **"CDP"** — Collateralized Debt Position (referenced in Q&A)
- **"Financial sovereignty"** — implied value proposition
- **"Decentralized Swiss Franc"** / **"digital version of the Swiss Frank"**

### 8. COMPANIES/PROTOCOLS MENTIONED
**Polaris:**
- **Polaris** — Decentralized stablecoin infrastructure; PE / PUSD / POLAR token system
- **MakerDAO / Sky** — DAI → USDS trajectory; negative example of governance-driven degradation
- **USDC / Circle** — SVB depeg example; centralization risk
- **USDE / Ethena** — "Risk blank check stablecoin"; basis trade → RWA wrapper without disclosure
- **Liquity** — Oracle switching logic (v1); redemption mechanism inspiration
- **Vitalik Buterin** — Framework provider (three problems)

**Frankencoin:**
- **Frankencoin** — Decentralized Swiss Franc stablecoin; ~$80M TVL
- **Tether** — Largest private holder of US Treasuries; dollar stablecoin negative example for store of value
- **Circle / USDC** — Referenced alongside Tether as "the decentralized ones in fact what you're holding is some form of US treasury"
- **Bank of England** — Panel co-participant (Paris)
- **French bank** — Panel co-participant (Paris)
- Countries: Switzerland, France, UK, US, Israel, South Korea, Russia

### 9. USE CASES HIGHLIGHTED
**Polaris:**
- Trustless CDP: mint PUSD against ETH without centralized counterparties
- Multi-currency synthetic assets: PCHF, PEURO, PGOLD, P Big Mac
- DeFi collateral: PE as an alternative ETH-productive asset vs. liquid staking
- Autonomous yield management: interest rates set by market signals, not governance

**Frankencoin:**
- **Long-term store of value** in Swiss Franc (vs. dollar inflation)
- Non-custodial, censorship-resistant savings in appreciating currency
- Cross-border Swiss Franc access for non-Swiss residents
- CDP-based Swiss Franc minting (CDP collateral basket with gold and CHF-nominated assets)

### 10. TONE & STYLE
**Polaris:** Technical, fast-paced, intellectually rigorous. Speaker acknowledges going long and speeds up. Dense with protocol mechanics. Not promotional in a sales sense — more like a technical whitepaper presented aloud. The "risk blank check" phrase and the Vitalik name-drop give it intellectual gravitas.

**Frankencoin:** Keynote-philosophical. Speaker uses humor ("I know I'm in the US"), props (physical book), and cross-event references (Bank of England panel in Paris the day before). More conversational than technical. The strongest talk in this file for pure narrative clarity — the store of value vs. transaction distinction is the single most original framing in all 9 scripts.

---

## FILE 7: Nightfall Stablecoin Video Script

### 1. OVERVIEW
- **Format:** Conference talk — solo speaker; slide deck implied
- **Length:** ~10 minutes
- **Style:** Provocative contrarian thesis; self-aware humor; analogies from tech history; venture/startup perspective
- **Audience:** Crypto/stablecoin conference; the speaker is pitching to potential investors while sharing market thesis

### 2. SPEAKERS & SEGMENTS
**Unnamed speaker** — Founder of Nightfall Networks; previously spent 11 years as "global head of blockchain at Ernst & Young," building it into "a billion dollar business for EY." Now fundraising for startup and having a hard time.

Segments:
- Steve Jobs / Dropbox / iCloud opening
- Three market forces commoditizing payments
- "Your TAM is toast" thesis
- Ethereum transaction pricing: down 98%+ from peak
- Voice telephony as historical template (product → feature)
- "Streaming theory of money" — shift from batch to real-time/continuous payments
- Digital music analogy (album → download → stream)
- Dropbox resolution (feature, not product — but $2.5B revenue, $1B+ FCF)

### 3. ALL KEY STATS & DATA
- iCloud launch: **2011**; Steve Jobs met Dropbox founders: **2009**
- Stablecoin market: **"300 billion in in stable coins"** referenced
- Bell System breakup: **1983**; voice telephony was **98% of all telecom traffic** then
- Voice telephony market in 2025: **$225 billion/year** (before commoditization)
- Landline cost inflation-adjusted: **"$40-$70 a month"**
- VoIP replacement: **~$8/month**
- Current cost: **$0** (bundled with cell/WhatsApp)
- Ethereum transaction pricing: **down more than 98% from the peak**
- Ethereum Foundation roadmap: **"a trillion transactions"** capacity (= ~100 transactions per person per day globally)
- Blockchain volume increase: **3x**
- AI demand increase: **"literally 330-fold"**
- Cross-border wire transfer historical price: **"$10, $15, $20, $50"**
- Cross-border wire future price: **"a penny or less"**
- Payment volume increase needed to offset pricing: far more than 3x (not achievable)
- Payment shift from monthly to daily/hourly: volume increase **"200 or 300-fold"** projected
- Dropbox revenue: **$2.5 billion/year**
- Dropbox cash flow: **"over a billion dollars a year"**
- IPO technical execution cost on-chain: **"under a dollar"** (SpaceX IPO context)

### 4. CORE NARRATIVE ARCS
**Arc 1 — The Steve Jobs "You're Just a Feature" Problem:** Dropbox story. Payments infrastructure is being Dropbox'd — becoming a feature bundled into something else, not a standalone product.

**Arc 2 — Three Forces Commoditizing Payments:** (1) New blockchain rails, (2) regulatory clarity, (3) excess blockchain capacity. Together they are "absolutely collapsing transaction pricing."

**Arc 3 — Your TAM Is Toast:** Cross-border payments going from $10-50/transaction to "a penny or less." 3x volume increase cannot offset 98-99% price reduction. "That's not a TAM, that's what you price a feature."

**Arc 4 — Voice Telephony Template:** 1983: voice = 98% of telecom, $225B/year industry. New rails (VoIP) → cheaper product → feature → free. Voice now "just something that goes into your conferencing system" like storage into iCloud. **Payments will follow the same arc.**

**Arc 5 — The Streaming Theory of Money:** Music → albums → digital downloads → streaming (Spotify). Payments → batch (once/month) → cheap batch → real-time → streaming (per-second/per-hour machine payments). Daily payroll example: overtime incentive dramatically higher if paid tonight vs. two weeks from now. Utility billing example: why extend 30 days of credit when you could bill daily for actual consumption?

**Arc 6 — The Feature Resolution:** Payments become embedded in enterprise cash flow software, consumer apps, billing systems. "Software products will have banks, not banks will have software products." Banking bundled with airport lounges (joke). Dropbox comps: not a $200B company but $2.5B revenue / $1B+ FCF as a feature. "Not the end of the world."

### 5. POSITIONING PILLARS
- Contrarian: "your TAM is toast" is deliberately provocative in a stablecoin conference context
- Historical analogies as proof: voice telephony, Dropbox, digital music all demonstrate the pattern
- "Streaming theory of money" as the original intellectual contribution
- The optimistic flip: being a feature isn't death — it's just a different (potentially very good) business

### 6. HOOKS & OPENINGS
- **"How many of you use iCloud? [pause] So, back in [2011] iCloud launched... Steve Jobs went to see the founders of Dropbox... 'You guys are basically not a product, you're just a feature.'"** — immediate contextualizing analogy
- **"Your TAM is toast. It's really my TAM is toast."** — self-deprecating pivot to honesty
- **"We are looking at a future where [cross-border payments] are a penny or less. That's not a TAM. That's what you price a feature."**
- **"The future of banking is that we're going to pay for airport lounges and we're going to get banking for free."** — the joke-that-isn't

### 7. RECURRING PHRASES & LANGUAGE
- **"You're not a product, you're just a feature"** — Jobs/Dropbox quote; central metaphor
- **"Your TAM is toast"** — the provocative headline thesis
- **"The streaming theory of money"** — original conceptual frame
- **"Your mess for less"** — IBM term for first-phase digital: same process, cheaper
- **"Commodity"** / **"commoditization"** / **"commoditizing"** — key economic process
- **"A penny or less"** — future price of cross-border payments
- **"98% reduction"** — Ethereum transaction pricing drop; voice telephony reference
- **"Feature, not a product"** — repeated as both warning and possible resolution
- **"Jevons's paradox"** — make things cheaper, market gets bigger (AI example cited)
- **"200 or 300-fold"** volume increase when payments go from monthly to daily/continuous
- **"Streaming"** — applies to money, not just music

### 8. COMPANIES/PROTOCOLS MENTIONED
- **Nightfall Networks** — Speaker's startup; payments infrastructure
- **Dropbox** — Primary analogy; Steve Jobs "feature not product" story; $2.5B revenue resolution
- **Apple / iCloud** — Storage-as-feature template
- **Ethereum / Ethereum Foundation** — 98%+ transaction pricing drop; trillion-transaction roadmap
- **Spotify** — Streaming music analogy
- **AT&T / Bell South** — Voice telephony; landline cost; commoditization
- **WhatsApp** — Voice calls for free; embedded feature
- **IBM** — "Your mess for less" terminology
- **SpaceX** — IPO example; on-chain execution cost under a dollar
- **Ernst & Young (EY)** — Speaker's prior employer (11 years, global head of blockchain, built to $1B business)
- **PayPal, Robinhood** — Mentioned implicitly in fintech context (file 9 has these explicitly)

### 9. USE CASES HIGHLIGHTED
- **Daily payroll:** Pay hourly workers tonight rather than in two weeks; overtime incentive amplified
- **Daily utility billing:** Bill for actual electricity consumption at midnight rather than monthly
- **Machine payments / micropayments at near-zero cost:** Per-second streaming of value
- **Enterprise cash flow management as payments platform:** Payments bundled into software, not separate
- **IPO execution:** On-chain technical cost "under a dollar"
- **Consumer finance apps that ARE banks** (not apps that connect to banks)

### 10. TONE & STYLE
Self-deprecating, intellectually playful, funny. The speaker is genuinely working through a hard realization (their startup TAM is shrinking) and using the conference to think out loud about it. Analogy-driven; historical pattern-matching. The airport lounges joke lands because it's absurd but directionally true. Very accessible — no crypto jargon. Would play well to a non-crypto business audience. The most original intellectual framing of any talk in this set (streaming theory of money; voice telephony template).

---

## FILE 8: Neobanks Stablecoin Video Script

### 1. OVERVIEW
- **Format:** Conference presentation — solo speaker; slide deck; QR codes for follow-up
- **Length:** ~9 minutes
- **Style:** Macro-economic data thesis; problem-solution structure; startup pitch embedded
- **Audience:** Stablecoin/crypto conference; builder and investor audience; some financial sophistication assumed

### 2. SPEAKERS & SEGMENTS
**"Pod"** — Founder of "Stable Channel" (stable yield research); also references "Osero" as the product ("Osero Earn"). Building a neobank product.

Segments:
- US macro: credit card APR vs. savings APY spread
- Bank structural constraints (CRE debt, unrealized losses, Basel 3)
- 1982 historical precedent (MMFs, MMDA response)
- Federal Reserve trillion-dollar migration forecast
- Jamie Dimon shareholder letter reference
- Fintech alternatives: Robin Hood Gold, Revolut
- New neobanks coming to market (100+ companies)
- Two yield models (vaults, lending) and their problems
- SUSDS (Sky) as the better solution
- Osero Earn: 10 lines of code integration
- AnomaY live use case (fully private yield)

### 3. ALL KEY STATS & DATA
- US credit card APR: **21%** (national average; "highest in very long time")
- US savings account APY: **0.61%** ("lowest also in quite a long time")
- Spread between credit card APR and savings APY: **"more than 20 percentage points of a spread — widest spread on record"**
- US consumer sentiment: **lowest in 75 years of tracking**
- US household debt: **"almost 190 billion [likely $190 billion in additional context]"**
- Midterm inflation expectation: **4-5%**
- Bank net interest margins: **3.4%** — "more than five times than what they're paying us on the savings account"
- Commercial real estate debt maturing 2025 (at time of talk): **"almost 900 billion"**
- CRE debt sitting on bank balance sheets: **"almost 400 billion"**
- CRE loan entry rates: **1.5-2%** (entered when rates were low)
- Bank unrealized losses from CRE: **~$300 billion**
- 1982 comparison: MMF inflows from savings accounts: **~$220 billion**; banks' MMDA response recaptured: **~$300 billion in just three months**
- Federal Reserve forecast: **"trillion dollar migration from the banks to these stablecoins"**
- Impact on bank lending capacity: **"more than 1.3 billion [likely $1.3 trillion] capacity for lending"** reduction
- PayPal PYUSD deposits: **"more than four billion"**; timeline: "over very short [period]"
- Robin Hood Gold cash sweep APY: **3.35%** (vs. national average; "more than five times")
- New neobank companies: **"more than 100 of those companies coming to the market"** in recent months
- SUSDS (Sky) balance sheet: **"more than 11 billion"**
- SUSDS APY: **3.6-6%** APY (competitive with Robin Hood / Revolut)
- SUSDS: more than half balance sheet in USDC (instant liquidity)
- Non-yield stablecoins: **"250 billion of stable coins are no yields"** currently
- Federal Reserve trillion-dollar migration forecast (repeated): into stablecoin market as macro opportunity
- Osero Earn integration: **"10 lines of code"**

### 4. CORE NARRATIVE ARCS
**Arc 1 — The Math Problem:** If inflation is 4-5% and savings accounts pay 0.61%, depositors are guaranteed to lose purchasing power. "This is guaranteed loss and not really a savings account."

**Arc 2 — Why Banks Can't Fix It:** Banks are earning 3.4% margins but can't share more yield because their balance sheets are distressed. $900B CRE debt maturing; $400B on bank books; entered at 1.5-2% rates when real estate prices were higher; now ~$300B unrealized losses. Basel 3 equity capital requirements force them to save rather than compete.

**Arc 3 — The 1982 Precedent:** In 1982, MMFs pulled $220B from bank savings accounts. Banks responded with MMDA (money market deposit accounts) and recaptured $300B in 3 months because their balance sheets were healthy enough to compete. Today's situation: banks can't compete. The threat (stablecoins/crypto) is much bigger.

**Arc 4 — The Fed's Trillion-Dollar Migration Warning:** The Federal Reserve itself is forecasting a "trillion dollar migration from banks to stablecoins." This will reduce bank lending capacity by ~$1.3 trillion. This is now "a really big macro event" not "niche crypto story."

**Arc 5 — Neobanks as the Capture Vehicle:** 100+ neobank companies are entering the market. But existing yield models (vaults with risk curators; lending against two-asset leverage) have problems — curators take no responsibility; yield concentration risk. There is a better solution.

**Arc 6 — SUSDS as the Infrastructure:** Sky's SUSDS: largest yield-bearing onchain product; $11B+ balance sheet; transparent; Basel 3 risk framework (junior → mezzanine → senior tranches); 3.6-6% APY; more than half of balance sheet in USDC (instant liquidity). Clear waterfall of losses. Easy to understand for fintechs and neobanks.

**Arc 7 — Osero Earn as the Integration Layer:** 10 lines of code. Built on SUSDS. First live use case: AnomaY (private yield). 250B in non-yielding stablecoins represents the opportunity if/when migrations go to trillions.

### 5. POSITIONING PILLARS
- Macro timing: widest ever spread between lending and savings rates = maximum consumer pain = maximum opportunity
- Banks structurally unable to compete (CRE losses, Basel 3) — not a temporary gap
- Historical precedent (1982 MMF moment) shows the pattern; today's version is bigger and banks can't respond
- SUSDS as the "safe" yield-bearing stablecoin — Basel 3 risk framework, transparent, diversified
- Osero Earn as the lowest-friction integration (10 lines of code)
- Privacy as a differentiator: AnomaY use case for fully private yield

### 6. HOOKS & OPENINGS
- **"The credit card APR national average in the US is at 21%... the savings APY is at 0.61%... that is more than 20 percentage points of a spread — widest spread on record."** — Data hook, immediate shock
- **"If the inflation is that high and the savings accounts are paying us almost nothing then this is guaranteed loss and not really a savings account."** — consumer reframe
- **"Jamie Dimon said something very important in his latest letter to shareholders in April — the whole new set of competitors is emerging."**

### 7. RECURRING PHRASES & LANGUAGE
- **"Widest spread on record"** — credit card APR vs. savings APY
- **"Guaranteed loss"** — savings account in inflation environment
- **"Unrealized losses"** — bank CRE exposure
- **"Trillion dollar migration"** — Fed Reserve forecast
- **"Big macro event"** / **"really big macro events"** — elevating crypto story to mainstream
- **"Niche crypto story"** (what it no longer is)
- **"10 lines of code"** — Osero Earn integration pitch
- **"Waterfall of losses"** — SUSDS risk tranching description
- **"Fully private"** — AnomaY use case
- **"Depositors been left on ice"** — vault/lending risk description for failed neobank models
- **"Banks are frozen"** — structural inability to compete on yield

### 8. COMPANIES/PROTOCOLS MENTIONED
- **Stable Channel** — Speaker's research entity
- **Osero / Osero Earn** — Product built on SUSDS; 10 lines of code integration
- **AnomaY (Anoma Pay)** — First live use case; private yield
- **Sky / SUSDS** — Yield-bearing stablecoin; $11B+ balance sheet; Sky is the rebrand of MakerDAO
- **USDC** — Majority of SUSDS liquidity backing
- **PayPal / PYUSD** — $4B deposits in short period; rail-shifting example
- **Robin Hood Gold** — 3.35% APY cash sweep; fintech competition signal
- **Revolut** — European fintech yield comparison
- **Jamie Dimon / JPMorgan** — April shareholder letter quote on stablecoin competition
- **Plasma One, Anoma Pay, Ether** — Named as among 100+ new neobank entrants
- **Federal Reserve** — Trillion-dollar migration forecast source
- **Basel 3** — Regulatory framework driving bank balance sheet constraints
- **Federal Reserve (again)** — SVB/CRE exposure framing

### 9. USE CASES HIGHLIGHTED
- **High-yield savings alternative:** Neobanks offering 3.6-6% APY via onchain yield vs. bank 0.61%
- **Consumer stablecoin wallets with yield** embedded (neobank as bank replacement)
- **Private yield:** AnomaY integration for privacy-preserving yield access
- **Developer integration:** 10-line Osero Earn API for wallets and neobanks
- **Enterprise liquidity management:** SUSDS as treasury instrument
- **Payment rail migration:** Settlement shifting to onchain (PayPal PYUSD example)

### 10. TONE & STYLE
Data-driven, macro-analytical, slightly urgent. The speaker builds a tight argument from consumer pain → bank constraints → historical precedent → regulatory warning → market opportunity → product solution. Less evangelistic than Noble/MoneyGram; more like a fintech analyst pitch. The "banks are frozen" narrative is politically sharp — positions stablecoins as filling a gap that regulators themselves created. Short and punchy; the data carries the talk.

---

## CROSS-CUTTING THEMES ACROSS ALL 9 SCRIPTS

### THEME 1: INFRASTRUCTURE OVER SPECULATION
Every single talk explicitly or implicitly repositions stablecoins away from "crypto" and toward infrastructure. Ghose (NYU): "This is a change to digital and financial infrastructure." Josh (MoneyGram): "You should not care what stablecoin you're using or if it's a stablecoin on what chain." Noble: "Without even knowing it." Nightfall: payments as a feature embedded in software. The consensus is unanimous — stablecoins succeed when users don't know they're using stablecoins.

### THEME 2: THE INVISIBLE STABLECOIN PRINCIPLE
Directly related to Theme 1. Josh's grandma doesn't know what an acquiring bank is. Noble's loyalty app shows rewards, not rails. MiniPay abstracts blockchain complexity. Osero Earn integrates in 10 lines. The talks converge on a shared principle: **successful stablecoin products make the stablecoin invisible to the end user.**

### THEME 3: REGULATION AS UNLOCK (GENIUS ACT WATERSHED)
The GENIUS Act is referenced directly or indirectly in 6 of 9 scripts. NYU Stern: "2025 was a breakthrough moment because of regulation." Noble: GENIUS enabled merchant stablecoins as legal payment instruments and third-party yield distribution. MoneyGram: regulatory comfort level with stables is a prerequisite. Neobanks: "trillion dollar migration" now credibly possible because of regulatory clarity. Frankencoin: policy makers choosing between "level the playing field" or "the dollar eats the world." Regulation is consistently framed as an accelerant, not a constraint.

### THEME 4: THE DOLLAR DOMINANCE TENSION
A striking intellectual thread runs through the non-US-centric talks. Ghose describes the geopolitical decline of official dollar reserves. Frankencoin explicitly says "the dollar is not a very good store of value." Celo/Onchain FX argues for multicurrency stablecoin infrastructure. Flipping USDC notes 99%+ dollar dominance as a problem Vitalik himself identified. Neobanks talks about the extractive nature of the dollar-stablecoin-as-Treasury relationship. The US-based talks (NYU, Noble, MoneyGram) are bullish on dollar stablecoins. The non-US talks are more skeptical of dollar monoculture. This tension is not resolved — it is the central unresolved debate across the scripts.

### THEME 5: YIELD AS THE KILLER FEATURE
Yield is the underlying economic engine in at least 6 of 9 talks. Noble's flywheel: yield → rewards → spend. Neobanks: SUSDS 3.6-6% APY vs. 0.61% bank savings. MoneyGram: "the yield on stables, we enjoy the full stack of that and can pass that to our customers." Frankencoin: "very high yield on it." Nightfall: streaming micropayments and daily payroll imply yield-bearing money. Ghose mentions concerns about yield-bearing stablecoins cannibalizing bank deposits. The "yield question" — who gets it, how it's distributed, whether it's legal — is the economic core of every business model in this set.

### THEME 6: THE NETWORK/AGENT PROBLEM
Several talks note that stablecoin infrastructure needs both supply (issuers, chains) and demand (users, merchants). MoneyGram has the agent network but needed consumer tech. Noble uses retailers as distribution. Celo uses MiniPay (Opera's 300M users). Nightfall argues payments become embedded in existing software products. The common insight: stablecoins alone don't create distribution — they need to attach to an existing network with users. "You can always buy TVL but you cannot buy product market fit" (Celo, quoting Curve's Max) is the cross-talk refrain.

### THEME 7: DECENTRALIZATION VS. COMPLIANCE — THE UNRESOLVED TENSION
The Configurable Privacy, Polaris, and Frankencoin talks all grapple explicitly with the contradiction between blockchain's trustless/censorship-resistant properties and the compliance requirements of regulated finance. Tomer (Stellar): "the world of compliance is not really caught up to the world of private blockchains." Polaris: building immutable, trust-minimized systems specifically because governance degrades (MakerDAO/USDS trajectory). Frankencoin: full decentralization means "no bank can lock your account." But MoneyGram, Noble, and Neobanks all work within regulated frameworks. The two camps — trustless DeFi and compliant fintech — are in the same stablecoin ecosystem but pulling in different directions.

### THEME 8: THE COMMODITIZATION CRISIS (NIGHTFALL'S UNIQUE CONTRIBUTION)
Only Nightfall addresses this directly, but it haunts every business model in the set. If transaction pricing goes to "a penny or less," every company building on transaction revenue faces an existential question. MoneyGram is solving for this with the receiver-customer model. Noble solves for it with yield + loyalty lock-in. Celo bets on volume (15M+ wallets, 500M transactions). Neobanks bets on the yield spread. The Nightfall thesis — payments become a feature, not a product — is the darkest and most intellectually honest reading of where the market is heading, and none of the other speakers directly refute it.

### THEME 9: HISTORICAL ANALOGIES AS LEGITIMIZATION
Multiple speakers reach for historical templates to explain the stablecoin moment:
- **Ghose:** BNPL as checkout option template for stablecoins
- **Nightfall:** Voice telephony commoditization; Dropbox/iCloud; digital music → streaming
- **Noble:** BNPL at checkout; Starbucks rewards vs. stablecoin wallet
- **Frankencoin:** 250-year history of the Swiss Franc; "currency environments can change very quickly"
- **Neobanks:** 1982 MMF / MMDA bank response

The pattern: when speakers want to make the stablecoin transition feel inevitable rather than speculative, they reach for a precedent where a new digital infrastructure replaced an old one. Nightfall is the most sophisticated user of historical analogy; Frankencoin is the most original (a physical book as prop).

### THEME 10: EMERGING MARKETS AS BOTH TEST BED AND PRIMARY MARKET
MoneyGram starts in El Salvador, Ghana, Colombia. Celo's MiniPay is growing in Africa and Latin America. Ghose identifies non-G10 high-inflation jurisdictions as the second demand leg. Frankencoin implicitly serves international investors fleeing dollar debasement. The Onchain FX talk is almost entirely about local-currency access in Kenya, Colombia, Philippines. The neobanks problem is described as US-centric but the solutions (mobile wallets, stablecoin yields) are more urgently needed in emerging markets. This is the most consistent cross-talk agreement: **the real adoption laboratory for stablecoins is not Wall Street but Lagos, Bogotá, and Nairobi.**

---

*Synthesis compiled from full transcript reads of all 9 video scripts. Quotes are verbatim from transcripts. All statistics reflect claims made by speakers, not independently verified.*

