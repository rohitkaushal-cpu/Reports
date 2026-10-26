CIGI Paper No. 331 — August 2025
How Will Stablecoins Integrate
with the Financial System?
Christian Catalini

CIGI Paper No. 331 — August 2025
How Will Stablecoins Integrate
with the Financial System?
Christian Catalini

About CIGI Credits
The Centre for International Governance Innovation (CIGI) is an President, CIGI Paul Samson
independent, non-partisan think tank whose peer-reviewed research Research Director, Digital Economy S. Yash Kalash
and trusted analysis influence policy makers to innovate. Our global
Director, Program Management Dianna English
network of multidisciplinary researchers and strategic partnerships
Program Manager Jenny Thiel
provide policy solutions for the digital era with one goal: to improve
Publications Editor Christine Robertson
people’s lives everywhere. Headquartered in Waterloo, Canada,
CIGI has received support from the Government of Canada, the Publications Editor Susan Bubak
Government of Ontario and founder Jim Balsillie. Graphic Designer Abhilasha Dewan
À propos du CIGI
Le Centre pour l’innovation dans la gouvernance internationale
(CIGI) est un groupe de réflexion indépendant et non partisan dont
les recherches évaluées par des pairs et les analyses fiables incitent
les décideurs à innover. Grâce à son réseau mondial de chercheurs
pluridisciplinaires et de partenariats stratégiques, le CIGI offre
des solutions politiques adaptées à l’ère numérique dans le seul
but d’améliorer la vie des gens du monde entier. Le CIGI, dont le
siège se trouve à Waterloo, au Canada, bénéficie du soutien du
gouvernement du Canada, du gouvernement de l’Ontario et de son
fondateur, Jim Balsillie.
Copyright © 2025 by the Centre for International Governance Innovation
The opinions expressed in this publication are those of the author and do not
necessarily reflect the views of the Centre for International Governance Innovation
or its Board of Directors.
For publications enquiries, please contact publications@cigionline.org.
The text of this work is licensed under CC BY 4.0. To view a copy of this licence,
visit http://creativecommons.org/licenses/by/4.0/.
For reuse or distribution, please include this copyright notice. This work may
contain content (including but not limited to graphics, charts and photographs)
used or reproduced under licence or with permission from third parties.
Permission to reproduce this content must be obtained from third parties directly.
Centre for International Governance Innovation and CIGI are registered
trademarks.
67 Erb Street West
Waterloo, ON, Canada N2L 6C2
www.cigionline.org

Table of Contents
vi About the Author
vi Acronyms and Abbreviations
1 Executive Summary
1 Introduction
2 Different Types of Stablecoins
4 Stablecoin Design: The Key Dimensions
5 What Problems Can Stablecoins Solve?
6 Core Scenarios for the Future Global Order
8 Conclusion
10 Works Cited

About the Author Acronyms and
Abbreviations
Christian Catalini is the founder of the
Massachusetts Institute of Technology (MIT)
Cryptoeconomics Lab and a research scientist at  AI    artificial intelligence
MIT. He is also a co-founder and chief strategy
| AML    | anti-money laundering |     |
| ------ | --------------------- | --- |
officer of Lightspark. Previously, he was a co-creator
of Diem (formerly Libra), chief economist of the
| API    | applied programming interface |     |
| ------ | ----------------------------- | --- |
Diem Association and head economist of Meta
FinTech. Christian is an advisor to Coinbase,
| BRICS+    | Brazil, Russia, India, China,   |     |
| --------- | ------------------------------- | --- |
Algorand and Delphia, and independent board
  South Africa, Egypt, Ethiopia,
member at Hivemind Capital. Since 2013, Christian
  Indonesia, Iran and the
has also been a member of the US Commodity
  United Arab Emirates
Futures Trading Commission’s Technology Advisory
Committee. His academic research at MIT focuses  CBDCs    central bank digital currencies
on blockchain technology and cryptocurrencies,
| CFT    | countering the   |     |
| ------ | ---------------- | --- |
and he previously worked on the economics of
equity crowdfunding and start-up growth, as    financing of terrorism
well as the economics of scientific collaboration.
| DeFi    | decentralized finance   |     |
| ------- | ----------------------- | --- |
He holds a Ph.D. from the University of Toronto
(Rotman School of Management), and M.Sc.
| fintech    | financial technology |     |
| ---------- | -------------------- | --- |
(summa cum laude) in economics and management
of new technologies from Bocconi University,  G7    Group of Seven
Milan, Italy. In 2018, Christian was appointed as
| IOU     | I owe you |     |
| ------- | --------- | --- |
a Faculty Research Fellow in the Productivity,
Innovation and Entrepreneurship Program at
| REITs     | real-estate investment trusts |     |
| --------- | ----------------------------- | --- |
the National Bureau of Economic Research.
| RWAs     | real-world assets                 |     |
| -------- | --------------------------------- | --- |
| SWIFT    | Society for Worldwide Interbank   |     |
  Financial Telecommunication
vi CIGI Paper No. 331 — August 2025 • Christian Catalini

currencies, especially when exchanges had limited
Executive Summary integration with traditional payment systems.
Stablecoins have evolved far beyond trading tools,
becoming pivotal in DeFi ecosystems. They now
Stablecoins are transforming from niche
anchor diverse financial instruments, including
crypto instruments to critical programmable
lending platforms, yield-generating protocols
infrastructure, with profound implications for
and derivatives. Additionally, stablecoins are
global finance and business strategy. By enabling
increasingly used for traditional financial services
instantaneous, low-cost settlement, they bridge
such as cross-border payments and international
disparate domestic payment systems, dismantle
settlements, addressing inefficiencies in legacy
inefficiencies in entrenched card networks and
systems. In markets characterized by currency
legacy rails, and unlock decentralized finance
volatility or instability, they offer a practical way
(DeFi) applications. This analysis delineates the
to access US dollars or other harder currencies.
core stablecoin archetypes — fully reserved
Interest in stablecoins accelerated significantly
variants, deposit tokens, tokenized money-market
following Stripe’s 2024 acquisition of Bridge, a
funds and algorithmic constructs — assessing
stablecoin-focused start-up, highlighting the
their trade-offs in reserve robustness, consumer
growing interest in stablecoins as tools for
protection, regulatory compliance and long-
global payment orchestration (Catalini 2024).
term business viability. The paper then charts
This acquisition has led financial institutions
five geopolitical pathways, ranging from a lightly
— as well as financial technology (fintech),
upgraded Bretton Woods order to fragmented
retail and digital platforms1 — to consider using
multipolar or more chaotic monetary regimes,
stablecoins to connect disconnected national
unpacking how these trajectories could propel
payment systems, which historically relied on
or impede stablecoin adoption. Notably, well-
legacy rails such as the Society for Worldwide
regulated, fully reserved stablecoins, bolstered
Interbank Financial Telecommunication (SWIFT)
by a robust public-private partnership, position
or closed-loop services from providers such as
themselves as agile, bottom-up alternatives to
Wise or Western Union to interoperate. These
central bank digital currencies (CBDCs), which
legacy systems often involve complex messaging
often struggle with protracted technical and
protocols, intermediaries and reconciliation
deployment challenges. Bitcoin’s ascendance in a
processes, leading to delays and higher costs.
changing world order also merits attention, serving
By enabling instant settlement, stablecoins
as an impartial inter-bloc conduit in a multipolar
reduce transaction costs, streamline operations
context, a safeguard against authoritarian controls
and contribute to global financial inclusion.
in cases of extreme institutional turbulence and
In 2019, Facebook’s Libra announcement
potentially a neutral reserve asset during existential
sparked intense regulatory scrutiny, highlighting
disruptions. Ultimately, the rapid feedback
stablecoins’ vast potential and inherent risks.
loops and user-driven iteration of private-sector
Regulators still navigate a delicate balance,
initiatives and permissionless networks position
recognizing stablecoins’ capacity to drive
them to capture critical network effects well before
competition, innovation and consumer choice in
slower, top-down CBDC programs can take hold
payments, yet wary of challenges to monetary
and interoperate smoothly across countries.
sovereignty and traditional banking frameworks.
Nonetheless, major economies, including the
United States, are warming to stablecoins, in
some cases seeing them as a stronger alternative
to CBDCs, which face steeper implementation
Introduction
and technical hurdles compared to the public-
private partnerships behind stablecoin issuance.
Overall, stablecoins have clearly evolved from niche
Stablecoins are digital assets engineered to
digital assets to essential infrastructure, powering
hold a consistent value, typically pegged to
a more seamless and efficient global financial
a fiat currency, such as the US dollar or euro,
system. Their ultimate role, however, will track
or a basket of assets. They were developed
to counter the volatility of cryptocurrencies
such as bitcoin and Ether, initially providing
1 See Heeb, Andriotis and Dawsey (2025) and Schwartz and Weiss
traders with a bridge between crypto and fiat (2025).
How Will Stablecoins Integrate with the Financial System? 1

the fate of the Bretton Woods system: if the dollar- to support minting and burning.2 Issuers must
centric order endures, dollar-pegged stablecoins also maintain a capital buffer of additional assets
could become the neutral settlement layer of to mitigate credit, market and operational risks.
global commerce. If a multipolar reserve regime
or CBDC-dominated architecture emerges instead, This approach positions issuers as narrow banks —
stablecoins may be relegated to specific, high-value institutions that take deposits but park them
use cases rather than occupying the monetary core. only in ultra-safe, short-duration assets such as
This paper is structured as follows: the section titled central bank reserves or treasury bills, avoiding
“Different Types of Stablecoins” briefly examines the classic “borrow short, lend long” maturity
the various asset types competing in the stablecoin transformation that characterizes conventional
arena, noting their distinct business and regulatory banking. The issuer therefore carries minimal
trade-offs, yet highlighting their suitability for interest-rate or credit risk, even if the broader
diverse use cases, likely driving specialization stablecoin ecosystem later reintroduces those
over the next decade. “Stablecoin Design: The Key risks through derivative tokens, rehypothecation
Dimensions” outlines key design dimensions for or on-chain lending protocols. When fully backed
robust stablecoin frameworks. The next section, in this way, stablecoins function as digital bearer
“What Problems Can Stablecoins Solve?”, explores instruments: whoever controls the private keys
challenges that well-designed stablecoins could controls the money, although issuance, redemption
address. “Core Scenarios for a Future Global Order” and reserve management all remain subject to the
analyzes stablecoins’ interplay with different constraints of the relevant regulatory regime.
geopolitical scenarios, followed by a conclusion
Fully reserved stablecoins, due to their capital-
intensive one-to-one backing, are costly to
issue and maintain. Consequently, issuers must
promote high-velocity, high-value use cases, such
Different Types of as payments, to drive ecosystem adoption. This
approach poses a further challenge: issuers have
Stablecoins traditionally relied on interest from reserves to fund
operations, but this model falters in low-interest-
rate environments or amid intense stablecoin
This section briefly outlines the product types
competition (Catalini and Wu 2024). As regulatory
likely to compete in the stablecoin space in the
clarity is reached across jurisdictions, there will
coming years, beginning with the most successful
be significant entry by new issuers — including
category to date: fiat-backed stablecoins, with
traditional financial institutions, fintechs and even
their safest implementation resembling a narrow-
retailers and platforms. Through entry, stablecoin
bank structure. Next, deposit tokens issued
issuers will be pushed to share more of the yield
by banks are explored, followed by tokenized
on the underlying assets with key distribution
money market funds (which are securities)
partners and eventually even consumers, which
and finally, the most experimental categories
dries up the revenues from the reserve.
(algorithmic stablecoins and hybrid models).
One might argue that if issuers of stablecoins
Fully Reserved Stablecoins
cannot capture value through the reserve — in
other words, the stock of coins — they should
Fiat-backed stablecoins such as USDT and USDC
naturally turn to transaction fees, or the flow of
must address a key challenge: ensuring on-demand
coins, as an alternative revenue stream. However,
redeemability for cash, akin to commercial
the reality is far more nuanced and challenging.
bank deposits. As stablecoin issuers are not yet
Enforcing fees at the blockchain level is not always
regulated as banks, this requires one-to-one
feasible due to the open and decentralized nature
backing with high-quality liquid assets. For US
of these systems. Issuers face the constant risk
dollar stablecoins, the optimal reserve, as proposed
of disintermediation, as users and developers
for US dollar-based Libra (now Diem), consists of
can bypass fees through off-chain solutions. This
US treasuries with 90-day or shorter maturities,
minimal cash, and repos for immediate liquidity
2 See www.diem.com/en-us/economics-and-the-reserve/
#the-libra-reserve-and-protections.
2 CIGI Paper No. 331 — August 2025 • Christian Catalini

dynamic fundamentally complicates the ability such as deposit insurance, providing users with
of issuers to monetize the flows they facilitate. familiar security in a blockchain context.
Fully reserved stablecoins are unlikely to By combining blockchain’s efficiency with
be sustainable as stand-alone ventures. The traditional banking’s stability, deposit tokens
operational costs of maintaining reserves, ensuring enable banks to offer low-cost, instant transfers.
regulatory compliance and managing infrastructure Banks, with their scale, distribution and
are significant, while opportunities for direct established trust, are well positioned to deliver
value capture remain limited. Consequently, the these services to consumers and businesses.
issuance of fully reserved stablecoins is likely However, achieving interoperability among deposit
to be led by fintechs and financial institutions tokens is non-trivial, requiring technical and
with complementary business models. These regulatory advancements to match the seamless
entities can strategically position stablecoins functionality of bearer instruments such as fully
as a cornerstone of a more open platform reserved stablecoins. Additionally, compliance
strategy, leveraging them to expand the reach poses challenges, as banks must develop
of their existing products and services. robust tools to monitor tokenized transactions,
ensuring safe interactions with other entities.
For instance, a fintech with a robust payments
business could integrate a stablecoin to lower It remains uncertain whether deposit tokens can
transaction costs, enhance cross-border efficiency effectively compete with fully reserved stablecoins
or enable seamless interoperability with DeFi for use cases requiring interoperability across
ecosystems. By doing so, it not only expands its financial institutions. They may also provide little
user base but also creates new touchpoints for additional value and functionality beyond existing
monetization through adjacent services — such as deposits. As a result, banks may find it simpler
lending, staking or premium features — without to maintain traditional deposits for customers
relying solely on transaction fees. Similarly, while supporting fully reserved assets to facilitate
traditional financial institutions could leverage stronger cross-institutional compatibility.
stablecoins to modernize their infrastructure,
offering clients a bridge between legacy Tokenized Money Market Funds
systems and blockchain-based applications.
Although tokenized money market funds and
This strategic interplay between stablecoins and US Treasuries (such as BlackRock’s BUIDL) or
broader platform dynamics underscores a critical similar instruments are not stablecoins in the
insight: the value of a stablecoin lies not in the coin conventional sense, they compete with them,
itself but in the ecosystem it enables. Issuers that particularly in institutional use cases where
focus narrowly on monetizing the coin through the distinction between cash-like instruments
fees or reserves risk being outmanoeuvred in and securities is less significant for usability.
a landscape defined by openness, competition
The core advantage of these tokenized, yield-
and a fierce battle for distribution — both on
generating assets is their ability to deliver greater
the consumer and on the institutional side.
value to users through embedded returns, such
as interest or yield, making their economics
Deposit Tokens
more compelling than fully reserved stablecoins.
Unlike fully reserved stablecoins, which are These instruments are best suited for scenarios
backed one-to-one by high-quality liquid assets, where store of value and yield generation
deposit tokens such as JPMorgan’s JPMD token3 are priorities, appealing to sophisticated
mirror commercial bank deposits, relying on institutional players. For example, tokenized
a fractional reserve model. Issuers engage in Treasuries can offer stable, yield-bearing
maturity transformation — lending deposited funds alternatives to stablecoins in DeFi or institutional
for longer-term obligations while maintaining custody solutions. However, as securities,
liquidity — and generate returns through they face stricter regulatory requirements that
interest-rate spreads. This approach allows introduce operational friction compared to
deposit tokens to inherit consumer protections, the simplicity of fully reserved stablecoins.
3 See Irrera and Kharif (2025).
How Will Stablecoins Integrate with the Financial System? 3

Algorithmic Stablecoins future designs could reduce capital intensity while
enhancing stability. For instance, a stablecoin
Algorithmic stablecoins grapple with an inherently
backed by tokenized Treasuries could dynamically
complex challenge: they rely on on-chain
adjust its supply using on-chain oracles,
mechanisms to peg their value to an off-chain asset,
maintaining its peg with lower overcollateralization
such as the US dollar, whose price is determined by
ratios. However, even these improved models
external market dynamics. Without tokenized real-
will likely remain susceptible to extreme market
world assets (RWAs) — such as tokenized Treasuries
shocks or adversarial attacks. Regulatory scrutiny
or bonds — to serve as high-quality collateral,
further complicates adoption, as tokenized RWAs
these stablecoins face a dilemma4 between two bad
must comply with securities laws, introducing
options: become capital intensive and inefficient by
friction absent in fiat-backed stablecoins.
demanding heavy overcollateralization — roughly
$150–$2005 in assets locked up for every $100 of Ultimately, the evolution of algorithmic stablecoins
stablecoins — to absorb price shocks and defend hinges on a stronger bridging of the on-chain and
the peg in stressed market conditions; or operate off-chain worlds through safe, tokenized assets.
with lighter backing and accept a depeg risk that While they hold promise for DeFi, their success
can quickly snowball into a full collapse. The will depend on balancing capital efficiency,
Terra (LUNA) crash in May 2022 starkly illustrated stability and regulatory compliance. Until then,
this vulnerability.6 While overcollateralized they remain a high-risk proposition, best suited for
designs (such as DAI) are safer, they also tie up users prioritizing decentralization over stability.
significant capital, reducing their scalability and
appeal, whereas undercollateralized models risk Additional Designs
death spirals when market confidence erodes.
The four categories above dominate today’s digital
This fragility renders algorithmic stablecoins assets market, yet the design space is far from
highly risky for holders today, limiting their settled. As tokenization widens the investable
viability to niche-use cases where users are universe, issuers will test hybrid collateral
willing to accept a higher risk for enhanced structures that mix short-dated Treasuries with
decentralization. Ironically, many existing tokenized gold, REIT shares, investment-grade
algorithmic stablecoins rely on fiat-backed credit, commodity baskets or dynamically
stablecoins within their reserves, underscoring rebalanced portfolios. These blends may target
the critical need for a robust link between the specific needs — say, an inflation-hedged savings
tracked asset and its on-chain representation. coin that combines Treasuries and tokenized gold.
This dependency highlights a fundamental
tension: the pursuit of decentralization Whatever mix emerges and gains traction,
currently compromises the stability that users the fundamental test remains the same: how
expect from a stablecoin to begin with. faithfully the reserve tracks the unit of account
and whether the issuer holds enough high-
The emergence of tokenized RWAs — such as quality liquid assets — and capital buffers sized
real-estate investment trusts (REITs), money to that mix’s volatility and correlations — to
market funds or Treasuries — offers a path toward meet redemptions under stress. A design that
more resilient algorithmic stablecoin designs. By excels on yield but stumbles on liquidity or
leveraging high-quality, yield-bearing collateral, solvency merely repackages old risks in new
technology. Future stablecoins will therefore rise
or fall on transparent reserve reporting, prudent
4 See Catalini and de Gortari (2021). risk management, and credible governance
and legal guarantees, even as innovators push
5 All dollar figures in US dollars unless otherwise noted.
the frontier of what can serve as collateral.
6 The system used LUNA tokens as an equity-like backstop for the TerraUSD
(UST) stablecoin, allowing users to always exchange one UST for $1
worth of LUNA tokens. This mechanism worked when LUNA’s market cap
exceeded UST’s supply, but when massive UST redemptions began, the
protocol minted exponentially more LUNA to honour the $1 peg, diluting
LUNA holders and crashing its price. As LUNA’s value plummeted,
it could no longer credibly back UST, creating a death spiral — UST
holders rushed to redeem, further flooding the market with newly minted
LUNA, until both tokens became essentially worthless and the $60 billion
ecosystem collapsed within days.
4 CIGI Paper No. 331 — August 2025 • Christian Catalini

interoperability between providers. Portable,
Stablecoin Design: The zero-knowledge credentials, address-based risk
scoring and on-chain analytics will enable issuers
Key Dimensions to satisfy regulators’ information demands while
preserving end-user privacy. When implemented
correctly, stablecoin payments can meet and
Reserve Integrity
exceed current standards: illicit flows are
flagged and frozen in real time, while legitimate
At the heart of any credible stablecoin architecture
commerce gains a frictionless settlement medium
lies the integrity of its reserves. A stablecoin
that transcends domestic payment silos.
that promises stability must deliver robust
assurances that the reference value remains fully
Taken together, rigorous reserve integrity,
redeemable on demand. That objective is only as
bankruptcy-remote consumer safeguards and novel
strong as the quality, liquidity and transparency
compliance controls create a self-reinforcing triad.
of the assets that back it. For example, for a US
Each dimension bolsters the others, anchoring
dollar stablecoin, reliance on short-duration US
trust in both the monetary and legal foundations
Treasuries and overnight repos satisfy those
of a stablecoin. That trust, more than any technical
criteria better than exotic credit or commercial
feature, is what ultimately determines whether
paper. Robust, rules-based disclosure — through
a stablecoin can mature from a cryptocurrency-
daily balance-sheet snapshots and independent
trading instrument into a mainstream, systemically
attestations — shifts disclosure from marketing
relevant piece of financial infrastructure.
to verifiable economic guarantees. Beyond
strict one-to-one backing, credible issuers
should hold a separate capital buffer sized for
credit, market and operational shocks — such
as a software bug or hack of the mint and burn
What Problems Can
facility. This loss-absorbing cushion preserves full
redemption even when unforeseen failures hit.
Stablecoins Solve?
Consumer Protection
Sound reserves are necessary but not sufficient. Connector between Domestic
The legal wrapper around them determines Real-Time Payment Systems
whether holders possess an enforceable claim
or own merely a promissory digital “I owe you” National instant-payment rails — such as FedNow
(IOU). A best-in-class stablecoin embeds clear in the United States, the Unified Payments Interface
bankruptcy-remote structures — typically a trust in India and Pix in Brazil — have driven domestic
or segregated custodial account — so that, if the settlement to near-real time. The moment funds
issuer fails, the reserve cannot be swept into cross a border, however, they stall in a maze of
general creditor proceedings. Transparent terms correspondent banks, cut-off windows and opaque
of service must stipulate instant redemption foreign exchange markups. A well-designed
rights and list dispute-resolution venues that stablecoin offers a neutral 24/7 settlement asset
do not rely on the issuer’s goodwill. Together, that bridges those disconnected systems. Payment
these safeguards confer real “moneyness,” providers can either prefund stablecoin balances
turning the stablecoin into a genuine bearer or acquire them on demand, then redeem them
instrument rather than a mere digital IOU. into the recipient’s local fast-payment rail in
seconds. In effect, the stablecoin supplies a shared,
Compliance always-on ledger that collapses the latency and
cost normally imposed by cross-border frictions.
Finally, no stablecoin can scale globally without
threading the needle between financial-crime Lower-Cost Rails and the
safeguards and the open access that gives public
Unbundling of Card Networks
networks their innovation and competition
edge. The balancing act is less about reinventing Credit-card networks such as Visa and Mastercard
know-your-customer controls than about handle three jobs — checking who you are
re-architecting them for programmability and (authentication), taming fraud and settling
How Will Stablecoins Integrate with the Financial System? 5

payments later — but they do so with legacy In DeFi, liquidity pools redeploy idle balances as
architecture that makes every card swipe or tap market-making capital, generating yields that
costly. Each transaction involves interchange offset user fees or reward network participants.
and other fees paid by the merchant’s bank to Rather than letting money sit dormant in accounts,
the card holder’s bank to fund risk coverage, these systems automatically put unused funds
float and card holder rewards, and that toll rolls to work — lending them out, facilitating trades
straight down to the merchant. Stablecoins can between different currencies or providing
give merchants “good funds” without the same liquidity for various financial activities, all while
costs: transfers finish in seconds and are final, earning returns that can be passed back to
and any needed refunds can be built into smart- users or used to subsidize transaction costs.
contract escrow or managed by outside services.
This turns today’s many-layered card process into Traditional firms can ride the same rails: a logistics
a simple two-party trade of digital cash. Merchants platform, for instance, can trigger payment
keep more of each sale, and payment processors automatically when an on-chain oracle — a service
have to compete on real value instead of hidden that brings real-world data onto the blockchain —
markups. It is no wonder the incumbents have confirms delivery, eliminating disputes and freeing
moved from brushing the idea off to embracing it working capital. No more waiting for invoices,
themselves — Visa’s response7 to the US GENIUS manual verification or payment-processing delays.
The money moves instantly when the conditions
Act shows how hard it is to dismiss a cheaper,
for a specific workflow are verifiably met.
bearer-style digital dollar once it exists.
The design space keeps expanding; stablecoins
Programmability and
supply the monetary substrate for experiments we
DeFi-Enabled Use Cases
have yet to imagine, much the way the Hypertext
Transfer Protocol became the scaffolding for a web
Stablecoins are best understood not as a cheaper
that soon dwarfed its creators’ early use cases.
wire transfer but as a programmable monetary
Just as the early internet pioneers could not have
primitive. Think of them less like digital cash
envisioned social media, streaming services or
and more like smart money that can follow
cloud computing, we are likely only scratching the
instructions automatically. Because settlement
surface of what becomes possible when money
is deterministic — meaning transactions always
itself becomes programmable infrastructure.
execute the same way under the same conditions
— and smart contracts8 are composable (they can
be combined like building blocks), entire back-office
workflows collapse into a few lines of code.
Complex business processes that traditionally Core Scenarios for the
require multiple intermediaries, manual approvals
and days of processing can now be automated Future Global Order
into simple, reliable code. Escrow services that
hold funds until conditions are met, supplier
financing that releases payments based on delivery Stablecoins live — or die — by the shape of
milestones, revenue-sharing agreements that the global monetary order around them. Their
automatically distribute profits and even streaming destiny could be a modest upgrade, a peripheral
payroll that pays employees by the minute — all of workaround or the backbone of a new system,
these can be invoked as modular functions by any depending on how geopolitics and regulation
application that speaks the protocol. It is like having unfold. The five scenarios9 that follow map
a universal financial application programming those possibilities, stressing how design choices
interface (API) that any business can plug into. must adapt as the world tilts from reform to
fragmentation, or even outright upheaval.
7 See Forestell (2025). Reform of the Existing
8 Smart contracts are deterministic programs stored on a blockchain. Global System
When a user transaction (or another contract) calls them, every node
re-executes the same code and updates the ledger’s state identically,
letting the network enforce agreed-upon terms without traditional
intermediaries or manual reconciliation. 9 These five scenarios are drawn from Samson et al. (2024).
6 CIGI Paper No. 331 — August 2025 • Christian Catalini

The least disruptive trajectory preserves the survive in two niches: corridors the e-CNY has
Bretton Woods framework and layers on targeted yet to reach, and communities that prioritize
upgrades. Led by the Group of Seven (G7), neutrality over state stewardship. Even there,
legislators in the largest economies codify reserve, liquidity thins as regulators in many countries
capital and disclosure requirements for fully steer banks, payment processors and crypto
backed payment stablecoins. Once that legal clarity exchanges toward the sanctioned rail.
arrives, inertia favours the incumbents: banks
The result is a landscape where CBDCs set the
tokenize deposits or issue their own stablecoins,
standard for speed, cost and policy levers, while
card networks wrap merchant balances, and
stablecoins serve as a parallel — but secondary —
major fintechs and neobanks mint branded digital
substrate for users seeking censorship resistance or
dollars and euros. The network still mirrors the old
dollar exposure outside the new sphere of influence.
correspondent-banking web — dense, dollar-centric
and knit together by redundant bilateral links —
Emergence of a Bloc-Based
yet settlement now clears in seconds instead
of days and programmability progressively Global System
automates workflows and financial services.
A genuinely multipolar equilibrium would
Interoperability mandates and real-time partition the world into rival monetary-technology
redemption rails stitch this mosaic of bank and spheres. In the China-centric zone, a sovereign
fintech tokens into a single, more fluid liquidity CBDC — and, over time, a mesh of interoperable
pool. Merchant fees compress, yet most of the CBDCs — runs end-to-end payments, from retail
surplus flows to the institutions that already point-of-sale to wholesale interbank clearing. The
dominate distribution. For consumers and US-EU bloc takes a hybrid approach: a CBDC in
businesses, the change feels like a quiet software Europe for basic payments, and privately issued,
upgrade: tap, pay, settle. The clear winners are fully backed stablecoins for retail transactions, DeFi
scale players with modern stacks — tech-forward experimentation and programmable commerce
banks, agile neobanks and crypto exchanges across all regions. Non-aligned economies leverage
that pivot from trading venues to mainstream neutrality as a strategic asset; for them, bitcoin’s
wallet and financial services providers. politically agnostic settlement and deep global
liquidity become a natural bridge across blocs.
Replacement of the
Inside the Western sphere, stablecoins thrive.
Existing Global System
Open standards spark greater fintech and payment
competition, composable smart contracts drive
A more disruptive path envisions an enlarged
financial innovation at the application layer,
BRICS+ bloc (consisting of Brazil, Russia, India,
and bank-grade rules on reserves and capital
China and South Africa plus new members Egypt,
buffers keep systemic risk contained. On the
Ethiopia, Indonesia, Iran and the United Arab
other side of the geopolitical fault line, state
Emirates) erecting its own monetary and settlement
digital money dominates day-to-day trade, yet
architecture. China’s digital renminbi evolves from
bitcoin serves as an escape valve for capital and
a domestic project into a full-stack alternative to
commerce that must cross political seams. The net
SWIFT and the card networks, bundling messaging,
result is a tiered monetary stack: CBDCs anchor
foreign exchange conversion and instant clearing
domestic policy objectives; stablecoins power
into a single API. Heavily subsidized rollouts across
open innovation, large-scale digital platforms
Africa, Asia and large swaths of Latin America
and AI agents; and bitcoin provides the neutral
turn the e-CNY ecosystem into the default channel
connective tissue binding the blocs together.
for trade that bypasses the United States.
Top-down CBDC rails crowd out stablecoins by A Case of Disorder
design. Compliance is baked into the core protocol,
In the darkest trajectory, multiple shocks
foreign exchange spreads are cross-subsidized
converge — geopolitical conflict, resource
and onboarding comes packaged with soft-power
nationalism and cascading sovereign-debt
incentives — development loans, infrastructure
crises — tearing holes in the fabric of multilateral
grants and preferential market access. Against
cooperation. Faced with acute capital-flight risk,
that backdrop, permissionless networks
governments prioritize domestic control over
and stablecoins retreat to the margins. They
How Will Stablecoins Integrate with the Financial System? 7

global connectivity. Two policy instruments stand in stark contrast to the open financial
rise to the top of the autocrat’s toolkit: CBDCs networks envisioned at their inception.
and stablecoin national champions.
Transformed Global Order
Many states accelerate CBDC programs that
embed real-time monitoring, granular wallet A systemic shock — a sudden climate tipping point
limits and programmable spending permissions. or the emergence of general-purpose artificial
Domestic stability becomes synonymous intelligence (AI) — could force a wholesale
with transactional visibility, and privacy is rewrite of our economic plumbing. In that reset,
reframed as a national-security liability. Capital programmability and instant finality shift from
controls are enforced not only at the border optional features to essential public infrastructure.
but also at the wallet level, with automatic Governments would have to disburse universal
throttles on foreign remittances and instant basic income or climate-relief transfers to
blacklisting of politically sensitive addresses. billions of wallets in real time, complete with
conditional logic and full audit trails. Coupled
Where a full CBDC rollout proves technically or with interoperable digital-identity standards,
politically unwieldy, governments bless a handful fully backed stablecoins — or retail CBDCs
of “domestic champions” — bank-affiliated or modelled on their design — become the obvious
state-influenced stablecoin issuers — tasked with settlement rail as AI agents enter the workforce.
the same objectives. These tokens carry hardwired
compliance modules and mandatory whitelisting, In this setting, stablecoins graduate from
effectively merging private branding with public “crypto-adjacent” curiosities to civic utilities. Smart
surveillance. The arrangement preserves the optics contracts automate eligibility, claw-backs and even
of market choice while funnelling transactional streaming tax collection, while AI agents negotiate
data straight to regulatory dashboards. payments on behalf of individuals and firms.
Should the shock also undermine confidence in
Under either model, cross-border interoperability sovereigns, a black-swan outcome remains on the
is sacrificed. Correspondent-bank corridors wither, table: bitcoin’s issuer-less neutrality could elevate
sanctions regimes fragment and liquidity pools it to reserve-asset status, relegating both CBDCs
become increasingly balkanized. Retail access and institutional stablecoins to secondary roles.
to permissionless stablecoins is choked off at
the fiat on- and off-ramps; liquidity splinters,
spreads widen and counter-party risk climbs.
The original promise of a borderless, low-friction
stablecoin economy goes largely unrealized. Conclusion
Precisely because bitcoin lacks a central issuer and
is censorship resistant, it emerges as the hedge Stablecoins have moved from niche crypto
asset for those with the technical know-how to plumbing to credible candidates for the
self-custody. Its role is narrower — store-of-value internet’s native money. Scaling them now
and flight-to-quality rather than everyday demands improvements across reserve
payment rail — but in a world of tightening integrity, robust consumer protections
controls, that neutrality comes with a premium. and effective compliance frameworks.
This leads to a bifurcated digital-money Reserves backed by high-quality, short-term
landscape: CBDCs or state-aligned stablecoins Treasuries, transparent disclosures and capital
dominate retail flows inside national borders, buffers ensure redeemability. Bankruptcy-
while a thinner, harder-to-police bitcoin market remote structures (such as trusts) give holders an
operates in the shadows as insurance against enforceable claim, converting a digital IOU into
domestic policy overreach. Stablecoins that bearer cash. Programmable anti-money laundering
once promised frictionless global commerce (AML) and countering-the-financing-of-terrorism
are relegated to niche corridors or co-opted (CFT) controls, leveraging on-chain analytics
outright — their programmable potential
redirected toward objectives (surveillance,
capital containment, political compliance) that
8 CIGI Paper No. 331 — August 2025 • Christian Catalini

and zero-knowledge proofs,10 balance regulatory with incumbent financial institutions and leading
demands with privacy and the open access that new entrants capturing most of the value. If a
fuels innovation and experimentation. Together, BRICS+ alternative emerges, stablecoins might be
these pillars enable low-cost, instant settlement marginalized by state-sponsored CBDCs, retreating
and programmable finance while fostering to corridors under stronger US influence.14 A
trust across payments, DeFi and global trade. multipolar world could see stablecoins thrive in
Western spheres while coexisting with CBDCs
Growth also hinges on two strategic questions: Can
elsewhere, with bitcoin serving as neutral
permissionless networks and stablecoins modernize
connective tissue between blocs due to its credibly
cross-border settlement faster than CBDCs, and
neutral and censorship-resistant design. Under
will a common programmable-payments standard
conditions of global disorder, stablecoins and
emerge before the world calcifies further into
CBDCs risk co-option by states as surveillance tools,
rival Western and Eastern stacks? How these
while bitcoin’s decentralized architecture and self-
resolve will decide whether stablecoins remain
custody options position it as the premier hedge
small relative to global money movement or
against capital controls and sovereign overreach.
become systemic financial infrastructure.
As domestic instant-payment rails proliferate
Recent policy and market signals underscore
and on-chain settlement costs approach zero, the
that the race is under way. In the United States,
most plausible outcome is not a winner-takes-all
the GENIUS Act is advancing through Congress.
monetary regime but a layered, interoperable
Europe’s Markets in Crypto-Assets framework
one. Fully reserved, dollar-denominated
has entered into force, and major incumbents —
stablecoins are poised to become the defacto
including Stripe (global stablecoin accounts),11
connective tissue for G7-centric commerce and
Coinbase (commerce protocol with Shopify),12 digital platform economies; CBDCs or domestic
Visa, Mastercard and PayPal — have begun stablecoins will handle domestic policy objectives
to embed stablecoins in merchant acquiring, where political will and technical capacity align;
settlement and retail payments. Concurrently, and permissionless assets such as bitcoin will
China’s e-CNY and cross-border rails expansion persist as “escape valves” in times of stress and
and the Bank for International Settlements’ geopolitically neutral infrastructure. The decisive
mBridge project13 demonstrate that CBDCs can variable is speed: whichever camp — public or
slowly move beyond sandbox experimentation. private — delivers a programmable, safe and
compliant standard first will set the baseline that
Benefits are already evident: in inflationary or
everyone else must match. Either way, the direction
underbanked regions, remote workers store their
is clear: money is converging on an always-on,
earnings in US dollar stablecoins, collapsing
programmable foundation, and the institutions
remittance costs and delivering M-Pesa-style
and businesses that embrace this shift early on
financial inclusion — albeit amid renewed
will write the next chapter of global finance.
pushback against dollarization and concerns
about big tech companies further expanding
their role through digital wallets and payments.
Unsurprisingly, the role stablecoins will play
across the global economy will largely depend on
which geopolitical scenario unfolds. In a reformed
Bretton Woods system, stablecoins serve primarily
as efficiency upgrades to existing payment rails,
10 Zero-knowledge proofs are cryptographic protocols that let one party
prove a statement — for instance, that a wallet satisfies AML/CFT rules —
without revealing any of the underlying transaction data, preserving
privacy while maintaining verifiable compliance.
11 See Egan (2025).
12 See Coinbase (2025). 14 Several CBDC initiatives explicitly build privacy safeguards into their
design. The European Central Bank’s digital-euro prototypes, for
13 See www.bis.org/about/bisih/topics/cbdc/mcbdc_bridge.htm. example, include an offline mode meant to offer “cash-like” anonymity.
How Will Stablecoins Integrate with the Financial System? 9

Works Cited
Catalini, Christian. 2024. “Why Everyone Is Wrong
About Stablecoins.” Forbes, November 1.
www.forbes.com/sites/christiancatalini/2024/11/01/
why-everyone-is-wrong-about-stablecoins/.
Catalini, Christian and Alonso de Gortari. 2021. “On the
Economic Design of Stablecoins.” SSRN Working
Paper. https://ssrn.com/abstract=3899499.
Catalini, Christian and Jane Wu. 2024. “The Race to Dominate
Stablecoins.” Harvard Business Review, August 6.
https://hbr.org/2024/08/the-race-to-dominate-stablecoins.
Coinbase. 2025. “Coinbase and Shopify Bring USDC
Payments on Base to Millions of Merchants Worldwide.”
Coinbase (blog), June 12. www.coinbase.com/
blog/coinbase-and-shopify-bring-usdc-payments-
on-base-to-millions-of-merchants-worldwide.
Egan, John. 2025. “Introducing Stablecoin Financial Accounts
in 101 countries.” Stripe (blog), May 20.
https://stripe.com/blog/introducing-
stablecoin-financial-accounts.
Forestell, Jack. 2025. “The potential genius of GENIUS.” Visa, June
23. https://corporate.visa.com/en/sites/visa-perspectives/
company-news/stablecoin-regulation-genius-act.html.
Heeb, Gina, AnnaMaria Andriotis and Josh Dawsey. 2025.
“Walmart and Amazon Are Exploring Issuing Their Own
Stablecoins.” The Wall Street Journal, June 13. www.wsj.com/
finance/banking/walmart-amazon-stablecoin-07de2fdd.
Irrera, Anna and Olga Kharif. 2025. “JPMorgan to Pilot Deposit
Token on Coinbase-Linked Blockchain.” Bloomberg, June 17.
https://news.bloomberglaw.com/tax-insights-
and-commentary/jpmorgan-to-pilot-deposit-
token-on-coinbase-linked-blockchain.
Samson, Paul, S. Yash Kalash, Nikolina Zivkovic, Tracey Forrest and
Bessma Momani. 2024. Scenarios of Evolving Global Order.
Special Report. Waterloo, ON: CIGI.
www.cigionline.org/publications/scenarios-
of-evolving-global-order/.
Schwartz, Leo and Ben Weiss. 2025. “Exclusive: Meta in
talks to deploy stablecoins three years after giving
up on landmark crypto project.” Fortune, May 8.
https://fortune.com/crypto/2025/05/08/meta-
stablecoins-exploration-usdc-circle-diem-libra/.
10 CIGI Paper No. 331 — August 2025 • Christian Catalini

67 Erb Street West
Waterloo, ON, Canada N2L 6C2
www.cigionline.org