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
