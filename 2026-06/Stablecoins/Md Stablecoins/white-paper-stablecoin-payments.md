WHITE PAPER
Stablecoin Payments
The Truth Behind the Numbers
January 2026
By Inderpreet Batra, Max Zevin, Ankit Mathur, Cláudio Quitete, Carlos Bravo, and Dawson Li

Stablecoin Payments
The Truth Behind the Numbers
Executive Summary
In linking the speed and efficiency of blockchain infrastructure with traditional financial
systems, digital currency appears poised to lead the next wave of innovation in money
movement. Stablecoins are a major component of this story. But outside financial
infrastructure and cryptocurrency trading, how much impact are they really having? In a
unique collaboration, BCG and Allium Labs set out to discover the reality behind the hype1.
Our research reveals that only a small proportion of stablecoin activity today drives real
economy payments. On the other hand, an annual growth rate of 60% suggests a
significant runway for digital assets in some use cases. There is much to play for as the
industry continues to evolve.
Public blockchain data suggests there is more than $62 trillion of stablecoin transfers
annually, but our analysis reveals that real economic activity amounts to just $4.2 trillion,
or about 7% of the total. In short, the vast majority of stablecoin activity relates to trading,
derivative collateral transfers, protocol mechanics, and intermediary routing, rather than
payments for goods and services.
For our initial sizing, we use a conservative, behavior-based methodology. This reveals that
in 2025, there was approximately $350–$550 billion of observable bilateral payments for
goods and services. We exclude large categories of off-chain usage, including internal
exchange settlements and stablecoin card-based payments. As such, the numbers should
be interpreted as directionally robust lower bounds. In future, we intend to expand our
digital asset flows dataset, adding additional coverage and more in-depth analysis.
Our research also distinguishes between goods and services payments initiated by
businesses and those initiated by consumers. B2B payments account for about 40% of real
economy payments and are growing at a rate of 65% per year. C2C payments account for
about 25% and are expanding at about 75% annually. (See Exhibit 1).
While overall real economy stablecoin flows are minor when set against the $200 trillion
global payments market, the trend is positive. Use cases tend to emerge where traditional
payment rails face structural inefficiencies, including cross-border settlement timing, high
FX costs, trapped liquidity, delayed finality, or complex payout workflows.
As stablecoin real world payments grow, albeit from a low base, the blockchains preferred
for payments are changing. In 2025, TRON remained the dominant rail by volume
(accounting for about $235–375 billion of transactions), but our analysis shows incremental
growth is increasingly driven by larger, more regulated entities, favoring chains such as
BNB Smart Chain (~$35–50B), Ethereum (~$20–35B), Solana (~$20–35B), and Polygon
(~$8-10B). This reflects a shift from pure cost minimization toward a multi-rail
interoperable settlement model, where compliance, programmability, analytics, and
institutional trust are seen as equally as important as fees .
1. Allium is a blockchain data provider with coverage across more than 1,000 stablecoins and multiple
major blockchains.
2 BOSTON CONSULTING GROUP

EEXXHHIIBBIITT 11
B2B payments are most prominent on-chain
B2B payments are most prominent on-chain
USD B, Jan 2025 to Dec 2025
350–550
150– 230
90–130
90–130
20– 60
Real Economy B2B C2C C2B B2C
Payments 2025
CAGR ~55% ~65% ~75% ~55% ~50%
24–25
Source: Allium database, BCG analysis.
Solving the Stablecoin Payments Puzzle
Stablecoins sit within a broader landscape of digital assets that includes tokenized
deposits, central bank digital currencies, and other blockchain-based instruments. Within
this ecosystem, stablecoins have emerged as a practical bridge between on-chain systems
and traditional finance, in some cases driving tangible real-world benefits incremental to
existing payment methods.
As of December 2025, stablecoin market capitalization exceeded $307 billion, roughly 50%
higher than in the same period the previous year. Growth was supported by increasing
regulatory clarity across major jurisdictions (including the U.S., Canada, Europe, Singapore,
and the UAE). We expect digital assets to grow 53% per year until 2033. (See Exhibit 2).
Meanwhile, major platforms are operationalizing their stablecoin strategies. And payments
companies, fintechs, and banks are integrating stablecoins into payouts, cross-border
settlement, and treasury workflows. That said, estimates of volumes of “stablecoin
payments” vary dramatically—from tens of billions to over a trillion dollars. The reason is
that estimates often rely on different definitions and data sources. Survey-based
approaches offer depth but limited coverage. Top-down blockchain metrics capture scale
but fail to distinguish payments from trading or internal routing. This divergence reflects
not just data gaps, but a classification problem. Without a consistent taxonomy for
economic intent, fundamentally different behaviors continue to be grouped under the
same “payment” label.
STABLECOIN PAYMENTS: THE TRUTH BEHIND THE NUMBERS 3

EEXXHHIIBBIITT 22
Digital assets are growing fast, fueled by public and private investment
Digital assets are growing fast, fueled by public and private investment
Per asset class in USD trillion
18.9
Fixed Income
16.5
Derivatives
Deposits
13.4
Other Assets
+53% p.a. Treasury & liquidity
9.4 Equities
Lending & credit
Alt (PE, HF)
4.6 Mutual Funds
Real Estate
2.7
1.6 Stablecoins
1.0
0.6
2025 2026 2027 2028 2029 2030 2031 2032 2033
Source: Ripple and BCG “Approaching the Tokenization Tipping Point” report from April 2025.
How Blockchain Data Represents Stablecoin Activity
Public blockchains are transparent by design: every transfer, timestamp, and amount is
visible. However, blockchains record how value moves, not why it moves. Wallets are
pseudonymous, transaction metadata is minimal, and economically distinct actions can
look identical at a transaction level. (See Exhibit 3). By contrast, traditional payment
systems embed rich contextual metadata—merchant type, transaction purpose, reversals,
settlement status—which allows intent to be directly observed.
Due to these dynamics, raw blockchain metrics such as total transfer volume or
transaction count materially overstate meaningful economic activity. They capture
settlement mechanics rather than use cases, and cannot, on their own, distinguish
payments from trading, treasury movements, or protocol operations. The core analytical
challenge is therefore not visibility, but interpretation.
Pattern Identification as the Basis for
On-Chain Analytics
Because economic intent is not explicitly encoded on-chain, pattern identification is the
primary enabler of stablecoin analytics. As with traditional transaction monitoring,
classification relies on repeatable behavioral signals rather than declared purpose.
These include transaction size, frequency, flow symmetry, counterparty diversity, and
temporal consistency.
4 BOSTON CONSULTING GROUP

EXHIBIT 3
EDXHeIsBpITi t3e every transaction being published on an open blockchain,
Despite every transaction being published on an open blockchain,
on-chain data doesn’t explicitly encode economic intent
on-chain data doesn’t explicitly encode economic intent
On-chain stablecoin Stablecoin payments  Off-chain fiat transactions
transactions bridged to traditional rails (e.g., cards, wires, PSPs)
While all transactions history and address  In between, payment services connects  Despite not being public, off-chain
behavior is public, data is limited: stablecoin with traditional rails, lacking  transactions explicitly record:
public data and economic intent
| • Sender/receiver address  |     |     | •  Merchant category (MCC) |     |     |
| -------------------------- | --- | --- | -------------------------- | --- | --- |
• Token (e.g., USDC) & Chain (e.g, Tron,  On-chain: Stablecoins transferred to a custodial  •  Transaction type
 BSC) wallet for trading, transfer, payment… •  Merchant ID & Legal entity
• Amount
•  Invoice/purpose codes
| • Timestamp |     | Sender | Receiver |     |     |
| ----------- | --- | ------ | -------- | --- | --- |
•  FX & settlement details
|     |     | Address | Address |     |     |
| --- | --- | ------- | ------- | --- | --- |
• Smart contract
|         |          | Externally Owned                 | Custodial Wallet |               |          |
| ------- | -------- | -------------------------------- | ---------------- | ------------- | -------- |
|         |          | Address1                         | (e.g., Revolut)  | Presents card |          |
|         |          |                                  |                  | Customer      | Merchant |
| Sender  | Receiver |                                  |                  |               |          |
| Address | Address  | Off-chain: Payment executed via  |                  |               |          |
0xc3fa… A m o u nt :  $ 18 0  0xf89d… traditional rails (e.g., card networks) A c c o u n t  a n d
| Co in :  U S D T   |     |     |     | fr a u d  c h e c k | Auth |
| ------------------ | --- | --- | --- | ------------------- | ---- |
Chain: BSC
| Timestamp: Jan-16-2025  |     | Customer | Merchant |     |     |
| ----------------------- | --- | -------- | -------- | --- | --- |
07:26:49 PM UTC Schemes
|     |     |     |     | Issuer | Acquirer |
| --- | --- | --- | --- | ------ | -------- |
Auth Auth
Schemes
|     |     | Revolut | Acquirer |     |     |
| --- | --- | ------- | -------- | --- | --- |
Source: BCG analysis.
1Externally Owned Address (EOA) : On-chain address controlled by private keys.
Key On-Chain Entities and mechanisms
• Centralized exchange (CEX): A custodial trading platform where user balances and most trading
activities are settled off-chain on internal ledgers. On-chain transactions primarily reflect deposits,
withdrawals, and internal wallet rebalancing rather than end-user economic activity. Examples: Binance,
Coinbase, Crypto.com, Kraken
• Decentralized exchange (DEX): A smart-contract-based trading venue where asset swaps and liquidity
provision occur directly on-chain. Stablecoins interacting with DEXs are typically converted into liquidity positions
or collateral, meaning inflows do not imply payment activity. Examples: Uniswap, Curve, PancakeSwap, Raydium
• Externally owned address (EOA): A blockchain account controlled by a private key and not governed by
smart-contract code. EOAs may be controlled by individuals, businesses, or custodial platforms and should
not be assumed to map one-to-one with economic actors. Examples: MetaMask, Trust Wallet, Phantom;
exchange-controlled wallets
• Custodial wallet: A digital asset wallet through which a third party, such as an exchange, fintech, or
payment platform, controls private keys on behalf of the end user. Transactions are authorized and settled
through the custodian’s internal systems rather than directly by the user.
• Automated market maker: A smart contract system that enables on-chain trading by pricing assets
algorithmically against pooled liquidity, rather than matching buyers and sellers through an order book.
• Bridge: A smart-contract system that enables assets, including stablecoins, to move between different
blockchains. Rather than representing a payment or transfer between economic parties, a bridge temporarily
locks, burns, or escrows a token on one chain and issues a corresponding representation on another chain.
STABLECOIN PAYMENTS: THE TRUTH BEHIND THE NUMBERS       5

To operationalize this approach, we partnered with Allium, a blockchain data provider with
coverage across more than 1,000 stablecoins and multiple major blockchains, to develop a
conservative, behavior-based framework for classifying stablecoin transfers by economic
use case. One limitation of our approach is that it only captures activity that settles on
public blockchains. Large categories of stablecoin usage occur predominantly off-chain and
are therefore not observable, including:
• Centralized exchange internal activity: Overwhelmingly spot and derivatives trading
settled on internal ledgers; peer-to-peer transfers exist but are marginal .
Examples: Binance spot trading; Revolut account-to-account transfers
• Crypto card payments: Transactions executed on card rails using custodial stablecoin
balances, where on-chain data captures only issuer inflows and outflows, which should
amount to about $15 billion in 2025 according to Artermis and Visa2.
Examples: Coinbase card; Binance card, Crypto.com card
Because of these factors, our estimates should be interpreted as conservative relative to
total stablecoin economic activity2.
Three-step methodology
We apply a three-step approach to isolate economically meaningful stablecoin activity.
• Step 1 — Remove non-economic activity: We exclude bot-driven transactions,
protocol mechanics (e.g., pre-minting, bridges, internal contract calls), and intermediary
routing such as automated market maker hops.
• Step 2 — Infer economic use cases: Unlike traditional payments analytics, which
map intent using identity and metadata, the analysis infers use cases from observable
wallet behavior, including sender–receiver dynamics, transaction sizes, frequency,
counterparty breadth, and timing patterns. (See Exhibit 4).
• Step 3 — Apply conservative classification: Ambiguous activity is intentionally
classified as investment or trading rather than payments. This creates a bias toward
understatement of real-economy usage.
How Much Stablecoin Volume is Actually Payments?
Of approximately $62 trillion of gross stablecoin transfer volume in 2025, only $4.2 trillion
remains after removing non-economic activity. We use this figure as the basis for all
subsequent analysis. (See Exhibit 5). We also classify transfers into five primary
categories based on observable wallet behavior and transaction patterns.
2. Assumption based on Artemis “Stablecoin Update: October 2025” estimated at ~$18B card payments less the
Visa $3.5B on-chain stablecoin volume included in our analysis already.
6 BOSTON CONSULTING GROUP

EXHIBIT 4
EXHIBIT 4
Stablecoin on chain transaction volumes are dominated by bots and
Stablecoin on chain transaction volumes are dominated by bots and
internal transactions
internal transactions
USD T, Jan 2025 to Dec 2025
62
50
7.5
4.2
Total Stablecoin Volume1 Bots, Likely Bots & Intermediary transactions BCG’s Adjusted
Internal Transactions2 Transaction Volume3
Source: Allium database, BCG analysis .
1Removes anomaly transactions (e.g. >1e18, Paxos 300T mint).
2Excludes mapped synthetic, bridged, or pre-minted tokens; known bots activities and wallets with 1000+ txns or $10M+ volume in any 30-days due to
potential bot activity.
3Only considers the largest transfer in a transaction, removing self-transfers and intermediary transfers within the transaction (e.g., Uniswap transaction have
multiple smart contract and intermediaries transfer to execute a transaction).
EEXXHHIIBBIITT 55
IInnvveessttmmeenntt aanndd ttrraaddee ddoommininaattee o onn-c-chhaainin a addjujusstetedd v ovolulummeses
USD B, Jan 2025 to Dec 2025
Off-chain CEX spot trading is estimated
at ~$25T in the period (CoinDesk)
4,200 EOA to EOA (P2P) transfer
700
400
100
1,500
950 350–550
BCG’s Adjusted Intra CEX CEX <> EOA DEX Flow Investment/Trade Unclear Real Economy
Transaction Volume settlement2 Me2Me Me2Me classification Payments3
Flows between known Flows between Flows between EOAs1 Flows supporting Flows with unclear Flows between two
address from same EOAs1 and CEXs for and DEXs for trading, trading, or address or different parties as
CEX for wallet trading, exchange, exchanges, lending... investment transaction service or goods
management ramp or store behavior payments
Sources: Allium database, CoinDesk Exchange Review November 2025; BCG analysis.
1Externally Owned Address (EOA) : On-chain address controlled by private keys.
2Most of CEX trade and transactions are settled off-chain through CEX internal ledger and it’s not captured in this exercise.
3Stablecoin payments settled in card rails such as crypto card are not registered on-chain and it’s not captured in this exercises (e.g., Revolut).
STABLECOIN PAYMENTS: THE TRUTH BEHIND THE NUMBERS 7

First, we divide approximate volumes by venue:
• Centralized Exchanges - CEX ($1,100 billion): Transfers involving over 130 mapped
centralized exchanges fall into two distinct patterns:
ǟ Intra CEX settlements ($700 billion): These flows are mostly economically neutral
and reflect exchange internal liquidity management, including movements between
online/hot wallets used for daily operations and offline/cold wallets used for asset
custody and risk management.
ǟ CEX <> EOA ($400 billion): These transfers represent users depositing and
withdrawing from the centralized trading infrastructure. We note a structural
imbalance; the data shows about $400 billion in deposits but just $5 billion in
withdrawals. The reason is that stablecoins habitually enter exchanges once and are
then reused internally for trading and derivatives, with most gains and losses settling
on internal ledgers and only a small share of returns exiting.
• Decentralized exchanges - DEX ($100 billion): Activity involving users sending
stablecoins from self-custodied wallets to on-chain trading protocols.
ǟ Stablecoins entering DEXs are typically not returned as stablecoins. Instead, they are
locked into liquidity pools or used as trading collateral, with users receiving liquidity
positions or non-stable assets in return. As a result, stablecoin inflows ($90 billion)
materially exceed outflows ($10 billion).
• Investment/trading ($1.5 trillion): This category captures short-term, reversible
flows or transaction patterns inconsistent with payment behavior, such as for wallet
management or store as value. Typical signals include rapid inflow-outflow cycles,
irregular transaction sizing, and high temporal clustering.
ǟ Importantly, this category reflects only on-chain activity. Most stablecoin trading,
particularly spot trading and derivatives, occurs off-chain on centralized platforms, and
is therefore not observable. For context, CoinDesk Exchange Review reports $25 trillion
in spot trading and $75 trillion in derivatives trading on centralized exchanges between
December 2024 and November 2025.
• Real economy payments ($350–550 billion): This category represents payments for
goods and services between economically distinct parties. The flows are directional,
non-reversible, and recurring, consistent with commercial and personal payment
activity. While volumes are small relative to global payments, they expanded about 60%
between 2024 and 2025.
• Unclear classification ($950 billion): Here we allocate activity that cannot be
confidently attributed to any category, often due to insufficient history, anomalous
behavior, or atypical transaction patterns. These flows are deliberately excluded from
payments estimates, so that our results remain analytically conservative.
Our categorization highlights a critical distinction: most stablecoin activity supports
financial market infrastructure rather than payments. But while real-economy payments
represent a minority share, they are growing rapidly and concentrated in use cases where
traditional payment rails are structurally inefficient.
8 BOSTON CONSULTING GROUP

Segmentation of Real-Economy Stablecoin Payments
Beyond identifying real-economy payments in aggregate, we segment payment flows into
B2B, C2C, C2B, and B2C categories. Using behavioral patterns as a starting point, we cross
reference against external data sources and validate through discussions with industry
participants. While inherently probabilistic, we believe our analysis provides a robust
directional view of how stablecoins are used for payments today. We will refine our analysis
as coverage expands and additional off-chain data becomes available.
The payments distribution reflects where stablecoins solve the most acute economic
frictions, which today are in high-value, cross-border, and treasury-driven settlement,
rather than everyday retail scenarios. Differences across segments are driven by
transaction economics (ticket size, urgency), structural inefficiencies in traditional payment
rails, and behavioral patterns observable on-chain.
B2B payments (about 40% of the total)
B2B payments represent the largest share of real economy stablecoin volumes. That’s
because B2B transfer needs align most directly with stablecoins’ core advantages:
24x7/365, speed, finality, and USD settlement without correspondent banking. These
benefits are particularly valuable for activities including liquidity pooling, treasury
positioning, and intercompany funding, especially when traditional banking rails are closed,
such as at weekends and during holidays. In addition, cross-border supplier settlement and
platform-to-merchant payouts are favored, especially in contexts where traditional
correspondent banking introduces delays, FX costs, and trapped liquidity.
We identified on-chain B2B flows through ticket sizes, directional and non-reversible
transfers, low counterparty diversity, and recurring payment patterns consistent with
invoice settlement.
C2C stablecoin payments (about 25% of the total)
C2C payments are primarily driven by cross-border remittances and peer-to-peer transfers,
particularly in regions with limited access to USD banking, volatile local currencies, or
expensive remittance corridors. In these contexts, stablecoins provide a faster, cheaper,
and more reliable alternative to traditional money transfers and informal cash networks.
Methodologically, C2C flows are characterized by high transaction counts, smaller average
ticket sizes, and broad counterparty diversity, resulting in a meaningful share of payment
activity but a lower share of aggregate value relative to B2B.
C2B stablecoin payments (about 25% of the total)
C2B payments consist of consumers paying businesses for digital and cross-border
services, often where traditional card acceptance may be limited, costly, or operationally
complex. These flows are most common in sectors such as gaming, gambling, online
subscriptions, and digital services with globally distributed customer bases.
On-chain, C2B payments are characterized by moderate ticket sizes, one-directional flows
to business wallets, and recurring transaction behavior, distinguishing them from trading
or treasury activity.
STABLECOIN PAYMENTS: THE TRUTH BEHIND THE NUMBERS 9

B2C stablecoin payments (about 10% of the total)
B2C payments account for the smallest share of real economy stablecoin volume. They
include business-to-individual payouts such as contractor payments, creator earnings,
refunds, and rebates. While conceptually well-suited to stablecoin programmability and
global reach, adoption remains constrained by effective domestic fiat payout rails,
regulatory considerations, tax treatment, and the strength of domestic fiat payment rails in
developed markets.
On-chain, B2C flows are identified through recurring outbound payments from business
wallets to a wide range of individual wallets, typically with moderate ticket sizes. Adoption
is most visible among Web3-native companies and global platforms paying distributed
workforces or creators.
Chain Dynamics: Where Stablecoin Payments Settle
Our analysis of real-economy payment flows by blockchain shows that TRON is the
dominant settlement rail in absolute terms, with 60–80% of flows driven by ultra-low
transaction fees and deep USDT liquidity. These characteristics make TRON highly
effective for high-frequency, price-sensitive transfers such as remittances and peer-to-peer
payments. However, TRON’s share of real economy stablecoin payment volumes declined
from about 74% in January 2025 to about 60% by year-end, even as absolute volumes
continued to grow.
This shift reflects incremental growth patterns. New volume is increasingly driven by larger,
more regulated institutions and platform-integrated use cases, rather than informal retail flows.
Institutional and enterprise payment models, such as platform payouts, B2B settlement,
and app-embedded payments prioritize trust, compliance, operational integration, and
analytics, alongside costs. These priorities favor blockchains with mature infrastructure,
strong ecosystem support, and clearer regulatory signaling, in addition to smart-contract
capabilities. As a result, Ethereum, Solana, BNB Smart Chain, and Polygon are capturing a
growing share of flows. Still, this represents diversification at the margins rather than
displacement of the incumbent rail. It also reflects rising interoperability needs across
payment and settlement workflows.
What the Data is Telling Us
Stablecoins today function primarily as financial market and settlement infrastructure,
rather than as a mass-market rail. In addition, while on-chain data captures only a partial
view of activity, it clearly shows that payment usage is real, growing, and concentrated in
specific high-friction contexts—notably cross-border B2B settlement, remittances, and
platform-driven payouts. The evolution of stablecoins as payment instruments is credible
and accelerating but we have yet to see a step function change in growth. Further growth
beyond niche applications will depend on deeper integration with existing financial
systems, continued regulatory clarity, and improved visibility into off-chain flows.
Looking ahead, we intend to expand our digital asset flows dataset with additional coverage,
complexity, and analytical fidelity. Please contact BCG or Allium if you are interested in learning more
or accessing detailed insights.
10 BOSTON CONSULTING GROUP

Appendix:
Glossary of Key Terms
Adjusted stablecoin volume: The subset of gross stablecoin transfer volume that
remains after removing non-economic activity such as bots, protocol mechanics, and
intermediary routing. Represents organic, economically interpretable on-chain activity.
Ambiguous /Unattributable flows: Residual stablecoin activity that cannot be
confidently classified due to atypical wallet behavior, one-off transactions, or insufficient
historical context. Deliberately excluded from payment estimates to avoid overstatement.
Balance-sheet positioning: Stablecoin transfers whose primary purpose is to hold,
reposition, or prepare liquidity rather than to settle a real-world obligation. Includes
treasury rebalancing, exchange positioning, and store-of-value usage.
Centralized exchange (CEX): A custodial trading platform where user balances and most
trading activities are settled off-chain on internal ledgers. On-chain activity primarily
reflects deposits, withdrawals, and wallet rebalancing.
Custodial wallet: A wallet in which a third party controls the private keys on behalf of
users. On-chain, custodial wallets often appear as EOAs despite not being user-controlled.
Decentralized exchange (DEX): A smart-contract-based trading venue where trades and
liquidity provision occur on-chain. Stablecoins entering DEXs are typically transformed into
liquidity positions or collateral.
Economic intent: The underlying purpose of a transaction, such as payment for goods or
services, trading collateral, or treasury positioning. Economic intent is not explicitly
recorded on-chain and must be inferred.
EOA (Externally owned address): An on-chain account controlled directly by a private
key with no associated smart contract code. EOAs may be controlled by individuals,
businesses, or centralized exchanges.
Gross stablecoin transfer volume: The total value of all stablecoin transfers observed
on-chain, including protocol mechanics, intermediary routing, trading collateral
movements, and payments.
Hybrid stablecoin payment (On-/Off-chain): A payment flow where stablecoins are
transferred on-chain to a custodial wallet, and the payment is executed off-chain using
traditional rails such as card networks or PSPs.
Intermediary routing: Temporary hops through multiple wallets or contracts within a
single transaction path, such as AMM routing or bridge mechanics, which do not represent
independent economic activity.
Me-2-me transfers: Transfers between wallets controlled by the same economic entity,
including internal treasury movements or hot-to-cold wallet transfers. These are
economically neutral.
STABLECOIN PAYMENTS: THE TRUTH BEHIND THE NUMBERS 11

Off-chain transaction: A transaction processed within a centralized system or payment
network that is not publicly visible on a blockchain. Off-chain systems explicitly record
payment intent but obscure settlement mechanics.
On-chain settlement: The final and irreversible transfer of value recorded directly on a
blockchain, providing transparent and atomic settlement.
On-chain Transaction: A transfer or contract interaction recorded directly on a public
blockchain, exposing settlement mechanics but not explicit economic intent.
Payment Rail: The infrastructure used to move value between parties, including
blockchain networks, card networks, and correspondent banking systems.
Probabilistic Classification: A methodology that infers transaction use cases from
observable behavioral patterns rather than explicit labels, preserving uncertainty through
ambiguity buckets.
Real-Economy Payments: Stablecoin transactions representing payment for goods or
services between economically distinct parties, inferred from wallet behavior patterns
rather than identity attribution.
Self-custodial Wallet: A wallet in which the user controls the private keys and therefore
has direct control over associated EOAs.
Stablecoin: A digital token issued on a blockchain designed to maintain a stable value
relative to a reference asset, most commonly the U.S. dollar.
12 BOSTON CONSULTING GROUP

About the Authors
Inderpreet Batra is a Managing Director and Senior Partner in BCG’s New York office
and global head of BCG’s Payments and Fintech practice. You may contact him by email
at Batra.Inderpreet@bcg.com.
Max Zevin is a Managing Director and Partner in BCG’s New York office. You may
contact him by email at Zevin.Max@bcg.com.
Ankit Mathur is a Senior Director in BCG’s Toronto office and the global lead for BCG’s
Payments and Fintech knowledge and research teams. You may contact him by email
at Mathur.Ankit@bcg.com.
Cláudio Quitete is a Project Leader in BCG’s Toronto office. You may contact him by
email at Quitete.Claudio@bcg.com.
Carlos Bravo is a Director in BCG’s Madrid office. You may contact him by email
at Bravo.Carlos@bcg.com.
Dawson Li is a Senior Analyst in BCG’s Toronto office. You may contact him by email
at Li.Dawson@bcg.com.
For Further Contact
If you would like to discuss this report, please contact the authors.

Boston Consulting Group partners with leaders in business
and society to tackle their most important challenges and
capture their greatest opportunities. BCG was the pioneer
in business strategy when it was founded in 1963. Today,
we work closely with clients to embrace a transformational
approach aimed at benefiting all stakeholders—empowering
organizations to grow, build sustainable competitive
advantage, and drive positive societal impact.
Our diverse, global teams bring deep industry and functional
expertise and a range of perspectives that question the
status quo and spark change. BCG delivers solutions
through leading-edge management consulting, technology
and design, and corporate and digital ventures. We work
in a uniquely collaborative model across the firm and
throughout all levels of the client organization, fueled by
the goal of helping our clients thrive and enabling them to
make the world a better place.
For information or permission to reprint, please contact
BCG at permissions@bcg.com. To find the latest BCG
content and register to receive e-alerts on this topic or
others, please visit bcg.com. Follow Boston Consulting
Group on LinkedIn, Facebook, and X (formerly Twitter).
© Boston Consulting Group 2026. All rights reserved. 1/26