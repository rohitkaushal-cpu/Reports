The Stablecoin Toolkit
PART I: FINANCIAL AND MARKET DIMENSIONS
January 2026

Executive Summary ...................................................................................................................................... 1
Introduction .................................................................................................................................................. 3
1.  The Stablecoin Landscape ...................................................................................................................... 4
1.1  Definition ................................................................................................................................................... 6
1.2  Stablecoins and Other Forms of Money ...................................................................................................... 9
1.3  History ...................................................................................................................................................... 13
1.4  Market Data .............................................................................................................................................. 15
1.5  Entities in the Stablecoin Ecosystem ........................................................................................................ 19
2.  Categorizing Stablecoins ...................................................................................................................... 24
2.1  Custodial (Off-Chain Fully-Collateralized) .............................................................................................. 25
2.2  Decentralized (Non-Custodial) Approaches ............................................................................................. 26
2.3  Hybrids ..................................................................................................................................................... 29
2.4  Denomination ........................................................................................................................................... 30
2.5  Yield ......................................................................................................................................................... 31
3.  Use Cases ............................................................................................................................................... 32
3.1  Overview ................................................................................................................................................... 32
3.2  Trading Uses ............................................................................................................................................. 34
3.3  Payments .................................................................................................................................................. 35
3.4  Store of Value ........................................................................................................................................... 36
3.5  Credit and Lending ................................................................................................................................... 37
3.6  Programmable and Agentic Commerce .................................................................................................... 38
4.  Conclusion ............................................................................................................................................ 38
4.1  Stablecoin Market Evolution .................................................................................................................... 38
4.2  Implications for Policy-Makers and Regulators ........................................................................................ 40
Appendix A: Major Stablecoins Today ....................................................................................................... 43
Appendix B: Stablecoin Regulatory Definitions ......................................................................................... 44
Appendix C: Contributors ........................................................................................................................... 45

The Wharton Blockchain and Digital Asset Project (BDAP), part of the Wharton Initiative on Financial Policy and
Regulation, is a research initiative focused on the evolving blockchain phenomenon. BDAP provides balanced,
research-based perspectives, and draws on world-class Wharton/Penn faculty, alumni, and students, as well as
relationships with officials and industry experts from around the world, to bridge gaps among stakeholders.

Visit bdap.wharton.upenn.edu for more information.

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Executive Summary

Stablecoins are essential elements of the digital asset world. More broadly, stablecoins promise to bridge the gap
between the traditional financial system and the digital asset realm. With recent and proposed regulatory
regimes providing clarity for institutions, these instruments are poised to become even more significant in
financial markets. Stablecoins represent a potential direction for the future of money and payments globally,
overcoming the limitations of legacy market infrastructure and offering novel capabilities. Although interest in
stablecoins among both financial market participants and policy-makers has increased dramatically, attention
has focused on a limited portion of the market.

This report provides a comprehensive overview of the stablecoin world today, including the business
ecosystem, categories of approaches, and use cases. A second report in the series will focus on the legal
and regulatory considerations for stablecoins, highlighting approaches in major jurisdictions.

Developers have created hundreds of stablecoin projects over more than a decade. These use a variety of
mechanisms to maintain price stability. Even within categories, policies and business approaches are diverse.
Stablecoins take various approaches to backing assets, yield provision, redemption rights, availability on layer 1
blockchains, and other attributes. Regulatory regimes will limit some of these choices for licensed operators, but
they differ from country to country.

While centralized custodial issuers represent the overwhelming majority of the more than $200 billion in assets
associated with stablecoins today, other approaches should not be ignored. The history of digital assets and
blockchains shows how innovative solutions, even if outside existing legal regimes, can take hold and gain
significant market traction if they address real-world needs. Alternative approaches to stablecoins highlight
opportunities and use cases. A comprehensive understanding of the stablecoin market is also essential to
understand the legal questions that must be addressed in the coming years. While not taking a position on the
legality or long-term business viability of any stablecoin, we believe it is critical for policy-makers, regulators,
and market participants to understand the stablecoin world as it actually exists.

Lack of precision in defining stablecoins is also a barrier to effective analysis of the market. Though every legal
regime contains a definition of the stablecoins subject to its coverage, these do not describe the concept from
first principles. Stablecoins should be distinguished from related instruments, such as central bank digital
currencies (CBDCs) and tokenized bank deposits. The concept should be framed broadly enough to reflect the
full stablecoin market, even if some approaches may not achieve economic significance or regulatory approval.
To that end, we define a stablecoin as: a publicly available, non-central bank issued digital asset, aiming
for stable value through economic mechanisms.

Beyond the formal definition, other common attributes of stablecoins are that the token should be able to stay
close to its peg for an extended period of time, and should have a strong basis for confidence about its safety and
soundness. For some purposes, stablecoins will be expected to have similar protections to traditional money
market funds, but in other situations, some measure of protection may be traded off against other values.

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

While it is possible that other methods will be invented, there are today four mechanisms used to maintain a
stablecoin at its peg, along with hybrids of those four:

1.  Off-Chain Fully-Collateralized
2.  Programmatic Overcollateralized
3.  Supply-Based Algorithmic
4.  Synthetic Hedged

The first category, often described as “custodial” or “centralized,” requires centralized entities maintaining
custody over traditional financial assets. The other three categories operate largely or entirely on blockchains
and therefore do not depend traditional banks and central banks.

We highlight two other major distinguishing attributes of stablecoins, which are not necessarily tied to their
choice of stabilization method: Denomination (single-currency USD, single-currency non-USD, synthetic,
commodity, and unpegged); and Yield. We also show how major regulatory regimes define categories for
stablecoins subject to regulation or permitted. In an Appendix, available at whr.tn/stablecointable, we classify
more than 40 of the most significant stablecoins based on a variety of economic and legal characteristics.

Stablecoins are the nexus of a large and growing universe of firms from the digital asset world, traditional
finance, and other sectors. While most attention focuses on issuers, the utility of stablecoins depends on a
number of other market participants. These include Authorized Participants able to transact directly with
issuers; Distributors such as digital asset exchanges and market makers; Custodians for stablecoin backing
assets; and Networks connecting issuers.

Finally, we describe the major use cases for stablecoins, including Liquidity for Digital Asset Markets, Payments,
Store of Value, Credit and Lending, and Foreign Exchange. Stablecoin applications reflect the realities of product
market fit. Stablecoins have broad utility because they function as a new form of money, and money serves many
functions. They promise greater speed, better efficiency, reduction in costs, near-universal accessibility,
composability, and novel programmability compared to alternatives. However, different stablecoin approaches
are more or less useful in certain contexts, depending on their economic properties or legal restrictions. The
take-up of stablecoins also reflects the pre-existing environment. Where traditional forms of money or other
new digital modalities are effective, there is less demand for stablecoin-based innovations (although stablecoins

may still offer enhanced functionality or efficiency). In important areas, however, stablecoins can address
limitations of existing money and payments technologies.

Those following stablecoin developments, whether focused on market dynamics or regulation, should evaluate
stablecoins based on their attributes as well as their uses.

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Introduction

Despite significant growth in both market and regulatory activity, a significant awareness gap remains around
the mechanics and benefits of stablecoins. At the 11th Wharton Reg@Tech Roundtable on Digital Assets, held in
October 2024, participants discussed the need for a comprehensive overview of stablecoin models and regulatory
approaches.1 Lack of understanding of the stablecoin landscape poses difficulties for both market participants
and governmental actors. A clear understanding of stablecoins is essential to assess both the opportunities and
challenges of stablecoin innovation and adoption in the financial value chains.

General categories such as “fiat-backed,” “asset-backed,” or “algorithmic” stablecoins do not fully capture
differences among stabilization mechanisms, business models, legal structures, risk profiles, adoption patterns,
and regulatory implications. The relationship among stablecoins, CBDCs, tokenization, private payment tokens,
and other means of payment has also not received sufficient attention. Legal regimes covering stablecoins are
not consistent around the world. All this leads to confusion among both policy-makers and private sector actors,
posing challenges for regulatory and market development. Against this backdrop, our project brought together a
high-level global expert group, supervised by the Wharton Blockchain and Digital Asset Project, to develop a
comprehensive picture of stablecoin models. A full list of participants is provided in Appendix C.

Stablecoins are already essential elements of the digital asset world. Over 80% of digital asset trades now use
stablecoins for one leg of the transaction.2 Beyond that, however, stablecoins promise to bridge the gap between
the traditional financial system and the realm of digital assets.

Stablecoin activity has increased dramatically in recent years. As a result, major payment processors (e.g. Stripe
and PayPal) and card networks (e.g. Visa and Mastercard) have integrated stablecoin capabilities. Traditional
banks are also partnering with stablecoin companies. In April 2025, Standard Chartered Bank announced that it
was partnering with companies to issue stablecoins pegged to the Hong Kong dollar.3 Traditional payment and
financial institutions have also embraced stablecoin initiatives. In 2023, PayPal launched PayPal USD,4 while
Visa became the first payment network to settle a transaction in stablecoin through Anchorage Digital, the first
US federally chartered digital asset trust bank.5 New regulatory regimes for stablecoins in the US and other
jurisdictions promise substantial expansion in stablecoin activity connected to the existing financial system.

1 Sangita Gazi, The Evolving Landscape of Digital Asset Regulation The 11th Wharton Reg@Tech Roundtable (December 14, 2024),
https://bdap.wharton.upenn.edu/wp-content/uploads/2025/01/The-11th-Reg@Tech-Report.pdf

2 Treasury Borrowing Advisory Committee, Digital Assets and the Treasury Market (October 2024),
https://home.treasury.gov/system/files/221/TBACCharge2Q42024.pdf.

3 Standard Chartered, Animoca Brands and HKT establish joint venture to issue HKD-backed stablecoin, February 17, 2025,
https://www.sc.com/en/press-release/standard-chartered-animoca-brands-and-hkt-establish-joint-venture-to-issue-hkd-backed-stablecoin/.

4 PayPal Launches U.S. Dollar Stablecoin, August 7, 2023, https://newsroom.paypal-corp.com/2023-08-07-PayPal-Launches-U-S-Dollar-Stablecoin.
5 Visa Network Will Settle Transactions in Crypto, First Use Case USD Stablecoin, PYMNTS (March 29, 2021),
https://www.pymnts.com/cryptocurrency/2021/visa-network-settle-transactions-crypto-first-use-case-usd-stablecoin/.

3

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Notably, the European Union’s Markets in Crypto Assets (MiCA) regulations related to stablecoins became
effective in mid-2024,6 and the US GENIUS Act was adopted in mid-2025.7

Against this backdrop, our project aims to address these critical gaps by developing a framework to categorize
existing stablecoins and highlighting use cases around the world.

1. The Stablecoin Landscape

Stablecoins have captured the attention of the major players in both the digital asset world and traditional
finance. Adoption has accelerated since 2023, as markets have matured and regulatory environments have
become more accommodating. Together, these developments appear poised to drive deeper engagement by
large, established financial institutions.

In a 2025 survey by Fireblocks among executives across traditional financial institutions, fintech companies and
payment gateways, 90% of respondents stated that they were either exploring or employing stablecoins, with
nearly half already using them in payments.8 According to Visa, stablecoin transaction volume was $34.7 trillion
over the past 12 months as of June 2025.9 This represents more than double Visa’s annual transaction volume for
traditional payments.10

An April 2025 report by the Citi Institute predicts a base case of $1.6 trillion in stablecoin supply in 2030, with
$3.7 trillion as a bull case and $500 billion (still more than double the current level) if adoption and integration
challenges persist.11 Standard Chartered similarly predicts a $2 trillion stablecoin market in 2028.12

It should be noted, however, that stablecoin transaction volumes are inflated by high-frequency trading and
bots. Visa’s June 2025 estimate of “adjusted” annual stablecoin volume, when accounting for such activity, is
$7.3 trillion.13 And even of that number, roughly 99% represents effective cash holdings in digital asset trading
accounts, rather than transactions in which a stablecoin is used to pay for a good or service. 14

Another way to assess the size of the stablecoin market is to compare it to the volume of U.S. currency in
circulation, and to M1, a narrow measure of the money supply that includes cash, demand deposits, and other

6 Regulation (EU) 2023/1114 of the European Parliament and of the Council of 31 May 2023 on Markets in Crypto-Assets, and Amending
Regulations (EU) No 1093/2010 and (EU) No 1095/2010 and Directives 2013/36/EU and (EU) 2019/1937, O.J. (L 150) 40 (June 9, 2023), hereinafter
MiCA.

7 See, e.g., Guiding and Establishing National Innovation for US Stablecoins Act, Pub. L. No. 119-27, 139 Stat. 419 (2025), hereinafter GENIUS Act.
8 Fireblocks, State of Stablecoins 2025, https://www.fireblocks.com/report/state-of-stablecoins/.

9 Visa, Stablecoin Transactions, https://visaonchainanalytics.com/transactions#adjusted-transaction-methodology.
10 Visa Annual Report 2004, Year-End Financial Highlights, https://annualreport.visa.com/financials/default.aspx.

11 Citi Institute, Digital Dollars: Banks and Public Sector Drive Blockchain Adoption (April 2025),
https://www.citigroup.com/rcs/citigpa/storage/public/GPS_Report_Blockchain_Digital_Dollar.pdf.

12 Yogita Khatri, Standard Chartered Expects Stablecoin Supply to Surge to $2 Trillion by 2028, The Block (April 15, 2025),
https://www.theblock.co/post/350851/standard-chartered-stablecoin-supply-2-trillion-2028.

13 Visa, supra note 2.
14 Michael Cembalest, “OK Boomer”: On Stablecoins, S&P Profits, Tariffs vs Tax Cuts and the History of Presidential Break-Ups, Eye on the Market,
https://assets.jpmprivatebank.com/content/dam/jpm-pb-aem/global/en/documents/eotm/ok-boomer.pdf (June 12, 2025), at 3.

4

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

checkable deposits. As shown in Table 1, stablecoins remain small relative to these traditional payment
instruments.

Stablecoins	vs	M1

M1

Currency	in	Circ

Stablecoins

Figure 1 -- Relative size of the stablecoin market

Some of the most prominent stablecoins in the market today have been in operation since 2014 (USDT), 2017
(DAI), and 2018 (USDC), despite many dramatic reversals in digital asset markets, regulatory interventions, the
Covid-19 pandemic, and the 2023 U.S. banking crisis. This should provide some comfort that stablecoins can
effectively maintain their peg, even without the protections contemplated under new regulatory regimes. On the
other hand, more than twenty stablecoins collapsed during the period between 2016 and 2022.15 Even successful
survivors, such as USDT and USDC, have lost their peg at times.16

In this report, we provide a detailed picture of the stablecoin world. Unlike most overviews of the market, we do
not limit our consideration to the centralized custodial stablecoins that are the focus of most current and
proposed stablecoin regulatory regimes. An important dimension of the stablecoin market is that developers
have created projects using a variety of different mechanisms. While it is possible that many of these will die out
as regulation pushes activity toward a limited set of approaches, we are skeptical that this will be the case. The
history of the digital asset and blockchain world shows how innovative approaches, even if outside existing legal
regimes, can take hold and gain significant market traction. That is, after all, the story of the stablecoin market

15 Arthur Wilmarth, Jr., The Looming Threat of Uninsured Nonbank Stablecoins, Delaware Corporate Law Journal, May 2025.

16 In particular, there have been many accusations regarding the legitimacy of USDT. The US Commodity Futures Trading Commission found that
USDT was not fully backed during test periods between 2016 and 2018. CFTC Orders Tether and Bitfinex to Pay Fines Totaling $42.5 Million,
Release No. 8450-21, October 15, 2021, https://www.cftc.gov/PressRoom/PressReleases/8450-21. In this report, we do not take a position on
USDT’s backing or other questions about it, either now or in the past. Our aim is to describe the stablecoin landscape as it exists, not to make
judgments about factual matters to be considered by regulators. USDT is the most widely-used stablecoin by market participants despite the prior
enforcement actions and concerns.

5

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

itself, with the dominant player, Tether, not waiting for regulatory approval to grow a massive global business.
Moreover, ignoring alternative approaches to stablecoins hides opportunities and use cases beyond those
contemplated by regulators. While not taking a position on the legality or long-term business viability of any
stablecoin, we believe it is critical for policy-makers, regulators, and market participants to understand the
stablecoin world as it actually exists.

1.1  Definition

The term “stablecoin” is now widely used, both in the digital asset world and, increasingly, in traditional finance.
However, there is no convergence on the definition of the term.

Relevant laws and regulations often define concepts such as “covered stablecoins” or “payment stablecoins”
subject to their provisions, rather than attempting to encompass all stablecoins.17 The Financial Stability Board
describes stablecoin as, “A cryptoasset that aims to maintain a stable value relative to a specified asset, or a pool
or basket of assets.”18 Others use similar phrasing.19 While not inaccurate, these definitions are vague, and fail to
highlight the major attributes that distinguish stablecoins from other instruments. They are, in effect, simply a
restatement of the term “stablecoin” – a coin (digital asset) that seeks to remain stable in value. Other scholars
focus not on price stability, but on the promise of collateralization with “safe assets,” effectively defining non-
custodial stablecoins out of the category.20 A third definitional approach is to recognize stablecoins as aiming to
fulfill the classic economic attributes of money. For example, the U.S. Securities and Exchange Commission
(SEC) Department of Corporate Finance in April 2025 described “Covered Stablecoins” as “designed and
marketed for use as a means of making payments, transmitting money, or storing value.”21

On the other hand, some lawmakers avoid the term “stablecoin” entirely for this category of assets.22 As
described below, the stability of stablecoins is not guaranteed, and all stabilization mechanisms create risks and
tradeoffs. Using the label “stablecoin” is seen by some as assuming the very property they seek, potentially
creating unrealistic market expectations.23 The European Union’s MiCA regulation, for example, consciously uses
“E-Money Token” and “Asset Referenced Token” rather than stablecoin. Some market participants also
deliberately avoid using this terminology. For example, Ethena markets USDe as a “synthetic dollar”.

17 See, e.g., GENIUS Act, supra note 6, at 2(22) (defining “payment stablecoins”).

18 Bank for International Settlements, Recommendations for the Regulation, Supervision and Oversight of Global Stablecoin Arrangements –
Executive Summary, FSI Connect, https://www.bis.org/fsi/fsisummaries/global_stablecoins.pdf.

19 See e.g., SEC Department of Corporate Finance, Statement on Stablecoins, April 4, 2025, https://www.sec.gov/newsroom/speeches-
statements/statement-stablecoins-040425 (“A stablecoin is a type of crypto asset designed to maintain a stable value relative to a reference
asset....”); Parma Bains and Ranjit Singh, Stablecoins Are Far From the Revolutionary Ideals of Crypto’s Creators and Are Not Without Risk, Finance &
Development Magazine, September 2022, https://www.imf.org/en/Publications/fandd/issues/2022/09/Basics-Crypto-conservative-coins-Bains-
Singh (“A stablecoin is a crypto asset that aims to maintain a stable value relative to a specified asset, or a pool of assets.”).

20 Gary B. Gorton & Jeffrey Y. Zhang, Taming Wildcat Stablecoins, 90 U. Chi. L. Rev. 909, 915 (2023).

21 SEC Department of Corporate Finance, supra note 19.
22 The EU’s Markets in Crypto Assets (MiCA) regulation speaks instead of “E-Money Tokens” and “Asset Referenced Tokens.” EU lawmakers wanted
to establish a regulatory framework based on legal precision and more0tailored oversight.

23 Financial Stability Board, Crypto-assets and Global “Stablecoins”, https://www.fsb.org/work-of-the-fsb/financial-innovation-and-structural-
change/crypto-assets-and-global-stablecoins/; Financial Action Task Force, FATF Report to G20 on So-called Stablecoins (July 7, 2020),
https://www.fatf-gafi.org/en/publications/Virtualassets/Report-g20-so-called-stablecoins-june-2020.html.

6

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

All of these definitional approaches have limitations. They address the status of stablecoins within a relevant
context. However, they are either too specific or too vague to identify broadly what makes a digital asset a
stablecoin. Developers have created hundreds of stablecoin projects over the past decade. The universe of
stablecoins is significantly broader and more diverse than one might think by reading stablecoin legislation or
the legal and finance literature. Stablecoins are a sufficiently significant and durable phenomenon to deserve a
clear definition from first principles.

In this report, we use the term to cover assets that market participants regularly describe as stablecoins, and that
have the relevant attributes described below. Some may be more stable than others.

We define a stablecoin as follows:

A stablecoin is a publicly available, non-central bank issued digital asset, aiming to

serve as a stable unit of account through economic mechanisms.

Below, we unpack each element of this definition.

1.1.1  Publicly Available

Stablecoins are not the only stable-value tokens represented on distributed ledgers. Banks such as JPMorgan
have created private payment coins, typically using private permissioned ledgers such as the Ethereum-based
Quorum, to move funds for their customers or for internal purposes. A stablecoin must operate on at least one
public permissionless blockchain. Any holder of the native assets of that chain could, in theory, purchase it.
However, acquisition and transfer of stablecoins may be limited by identity verification, financial crime or
sanctions compliance checks, and asset freezes, especially with centralized stablecoin models. For example, in
April 2023, the French bank Société Générale launched the EUR Coinvertible (EURCV) stablecoin on the public
Ethereum mainnet, subject to address whitelisting and smart contract permissioning for regulatory compliance.24

1.1.2  Non-Central Bank Issued

While stablecoins are publicly available, like fiat currencies, and usually bear denominations of those currencies,
they are expressly not direct liabilities of a central bank. This is a dividing line, although not the only one,
between stablecoins and CBDCs.

In effect, stablecoins occupy the same space in the hierarchy of money as commercial bank money, functionally
serving as an equivalent to central bank money for users so long as they maintain stability, but not directly
subject to the central bank’s monetary policy decisions or the responsibility of the central bank to backstop.
While governments might take action to protect stablecoin holders, such as creating an insurance scheme
analogous to FDIC deposit insurance in the U.S., none has yet done so. Notably though, when Silicon Valley Bank
(SVB) failed in 2023, it put at risk several billion dollars of collateral for Circle’s USDC stablecoin, causing USDC

24 Societe Generale–Forge Launches “Coinvertible”: The First Institutional Stablecoin Deployed on a Public Blockchain (April 20, 2023),
https://www.sgforge.com/societe-generale-forge-launches-coinvertible-the-first-institutional-stablecoin-deployed-on-a-public-blockchain/.

7

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

to depeg on secondary trading venues.25 U.S. banking regulators stepped in to facilitate an orderly process that
made SVB depositors whole, including Circle, alleviating the price pressure on USDC.  If stablecoin assets
continue to grow, and some are held by commercial banks, the responsibility of bank supervisors to stablecoin
holders will once again be a question.

Generally speaking, stablecoins are issued by private firms. In Section 1.5.1, we identify the major types of
entities issuing stablecoins. It is, however, possible for a stablecoin to be issued by a governmental entity that is
not a central bank.  The Wyoming Stablecoin Commission, pursuant to legislation adopted by the state
legislature, launched the Frontier Stable Token (FRNT) in August 2025.26

1.1.3  Digital Assets

Stablecoins are representations of value on a blockchain. We use the term “digital asset” here, noting that in
other contexts, terms such as “cryptoasset,” “cryptocurrency,” “virtual asset,” and “token” are used for the same
purpose.27 Generally speaking, stablecoins are not the native digital assets used to secure validation or access
blockspace on a Layer 1 blockchain, such as Bitcoin or Ether. Because those native assets incentivize actions and
have volatile supply and demand, they are likely to be incompatible with the goal of stability. In fact, a major
rationale for the creation of stablecoins was to overcome the volatility that limited the utility of native digital
assets for functions such as payments.

A stablecoin may be instantiated as a token on multiple blockchains. For example, USDC is available on over
twenty blockchains. This effectively means that there are separate tokens on each chain, labeled “USDC” and
backed by the same collateral base of custodial high-quality liquid assets off-chain. Payments can thus be made
across chains, but this requires a bridging mechanism to prevent token loss or double-spending.

1.1.4  Aiming to Serve as a Stable Unit of Account

Stablecoins seek stability for a reason. Their goal is to be well-accepted measuring sticks for transactions and
value storage: what economists call a unit of account.28 Though Bitcoin proponents are quick to declare that
“one bitcoin is worth one bitcoin,” because its value resists debasement by monetary policy decisions, measuring
the price of other things in terms of bitcoin, whether physical goods or digital assets, is problematic because of
its volatility. In 2010, a pizza was worth 10,000 bitcoin; no longer.29 Yet one can comfortably quote the price of a
pizza in dollars, as well as USDC or other stablecoins.

Serving as a unit of account may also make stablecoins useful for the other classical attributes of money: serving
as an effective medium of exchange and store of value. Similarly, implicit in the stability objective of stablecoins
is the idea that they are adapted to certain uses. A stablecoin will not be ideal for an investor seeking massive

25 Ashley Capoot, Stablecoin USDC Breaks Dollar Peg After Firm Reveals It Has $3.3 Billion in SVB Exposure, CNBC.com (March 11, 2023),
https://www.cnbc.com/2023/03/11/stablecoin-usdc-breaks-dollar-peg-after-firm-reveals-it-has-3point3-billion-in-svb-exposure.html.
26 Wyoming Stable Token Commission, https://stabletoken.wyo.gov/.

27 “Digital Asset” is defined in the US Code as “any digital representation of value which is recorded on a cryptographically secured distributed
ledger.” 26 USC §6045(g)(3)(D)).

28 Gregory Mankiw, Principles of Economics § 29-1a (Cengage, 8th ed. 2018).
29 Shaurya Malwa, Bitcoin Pizza Day is Now a $1.1B Celebration, Coindesk (May 22, 2025), https://www.coindesk.com/markets/2025/05/22/bitcoin-
pizza-day-is-now-a-11b-celebration.

8

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

capital appreciation from growth in a protocol's adoption. Conversely, it will likely be appropriate for functions
such as payments or treasury management. In contrast to the SEC's April 2025 staff statement, however, we
believe that specific uses should be considered applications of stablecoins rather than definitional attributes.30

The stability of a stablecoin is aspirational. Any successful stablecoin will need to be effective in maintaining its
stability peg and meeting redemptions. But even a failed effort, such as Terra Luna UST or Iron, which both
catastrophically spiraled away from their peg, deserves to be labelled definitionally as a stablecoin.

However, stability is relative. It must be established in relation to a reference asset, or a pool of assets, which are
themselves perceived as stable. The vast majority of existing stablecoins aim for parity with the US dollar, which
is widely considered a stable asset. Yet, the price of USD does fluctuate somewhat relative to other currencies in
the foreign exchange market, and its purchasing power decreases over time due to inflation. This is true,
typically even more so, with other currencies, and significantly more so with real-world assets such as precious
metals. A commodity-collateralized token denominated in gold may achieve some of the functions of a
stablecoin, since it aims for par with a physical asset that is widely used as a stability hedge. However, it is
unlikely to serve as an effective unit of account or a payment tool. Overall, there is no degree of stability
objective that is “enough” to make a token a stablecoin; rather, the dividing line is that the token is designed and
marketed with stability as a goal.

1.1.5  Through Economic Mechanisms

The final element of our definition may seem unnecessary. And indeed, stablecoin definitions typically stop with
the objective of stability. However, this begs the question of how that stability is to be achieved. As described in
Section 2, the answers to that question are, to a significant extent, the dividing lines among different types of
stablecoins. We therefore do not specify any particular means of promoting stability, most notably not rejecting
mechanisms such as seigniorage-based algorithmic stablecoins and hedging-based synthetic stablecoins that
many national regulatory regimes exclude or even prohibit.

It is crucial, however, to note what all these mechanisms have in common. They rely on economic incentives to
maintain the peg to the reference asset. Because the stablecoin is publicly available, if the stablecoin price
deviates from its peg, it will create arbitrage opportunities. How that arbitrage operates, and how effectively, will
vary. The point is that the stablecoin aims to maintain a value of $1 or one ounce of gold, not merely by labeling
it as such or by a sovereign declaring its value by fiat.

1.2  Stablecoins and Other Forms of Money

Money is a fundamental social technology that, as noted previously, functions as a medium of exchange, unit of
account, and a store of value. Institutional economists talk of the “singleness” of money—ensuring a unified
standard within economies to facilitate pricing, accounting, and policy control.31 In practice, however,
“moneyness” exists on a spectrum with various instruments fulfilling monetary functions to different degrees.

30 SEC Department of Corporate Finance, supra note 19.
31 Rhys Bidder et al, Single Minded? Stablecoins and the Singleness of Money, Kings Business School Qatar Centre for Global Banking & Finane
https://www.kcl.ac.uk/business/assets/pdf/single-minded-final.pdf (2025).

9

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Throughout history, money has evolved from pre-monetary systems (gift economies, credit arrangements) to
commodity money (cattle, shells), standardized coinage (Lydia, 7th century BCE), paper currency (Tang/Song
China), and electronic forms. Each transition reflected changing societal needs while maintaining money's core
functions. The gold standard (19th century) and Bretton Woods system (1944-1971) represented attempts to
balance stability with flexibility before giving way to today's unbacked fiat currencies with floating exchange
rates. Money's relationship with state sovereignty has been fundamental, with currency issuance representing a
defining power of the modern state. Yet monetary sovereignty exists on a continuum, as demonstrated by the
Eurozone's supranational experiment, dollarized economies, and China's managed internationalization. As a
social contract, money operates through collective agreement—users accept its value because they trust others
will accept it in turn.

The digital transformation of money began with electronic payment systems (1970s-2000s) and accelerated with
mobile money innovations like M-Pesa in Kenya and Alipay/Wechat Pay in China, which demonstrated how
digital payments could leapfrog traditional banking infrastructure. Bitcoin's 2008 introduction represented a
radical departure—a decentralized, programmable monetary system operating outside established institutions.
Bitcoin and subsequent digital assets have had tremendous impacts. Yet with a few exceptions, they have not
been significantly adopted for the purpose specified in the title of the Bitcoin Whitepaper: peer to peer electronic
cash.32 The volatility of bitcoin and most other digital assets limits their utility for money-like functions such as
payments. Stablecoins seek to overcome this limitation.

Looking forward, monetary evolution presents a tension between traditional singleness and emerging pluralism.
While sovereign digital currency dominance would maintain monetary singularity, we may instead see
public/private hybrid systems or specialized currencies for different purposes. The development of non-USD
stablecoins suggests a future in which multiple regulated digital currencies coexist within frameworks balancing
innovation with coordination benefits. The programmability of digital money—whether through blockchain
smart contracts or CBDC conditional payments—introduces unprecedented possibilities for embedding
governance logic directly into monetary instruments, raising questions about surveillance and control.  How
tensions between centralization and decentralization, privacy and transparency, and national versus global
optimization resolve will determine how monetary principles adapt to a digital, multipolar world.

In this context, are stablecoins truly a novel form of money, or merely a new technological representation of
existing financial instruments, such as electronic money (e-money)? An academic analysis suggests that
stablecoins exhibit some characteristics of private currencies under Frederick Hayek's currency competition
model (stability, transparency, and a robust technological framework), but unlike private currencies, they remain
inflationary because they mimic the price of fiat currencies.33 Some argue that it is most appropriate to treat
stablecoins as only money-like, because “e-money represented on a DLT platform is still e-money.”34 The Bank

32 Satoshi Nakamoto, Bitcoin: A Peer-to-Peer Electronic Cash System (October 31, 2008), https://bitcoin.org/bitcoin. pdf.

33 Firat Cengiz, Stablecoins and Their Regulation: A Hayekian Approach, Journal of International Economic Law, 2025, jgaf014,
34 European Commission, ECB Disagree About US Stablecoin Risks – Report, Ledger Insights (April 22, 2025),
https://www.ledgerinsights.com/european-commission-ecb-disagree-about-us-stablecoin-risks-report/.

10

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

for International Settlements argued in June 2025 that stablecoins “exhibit some attributes of money…[but]
perform poorly when assessed against the three tests for serving as the mainstay of the monetary system.”35

There are also legal consequences to how the lines between forms of money are drawn. Categories are subject to
the jurisdiction of different regulators (for example, the SEC, Treasury and Federal Reserve at the federal level in
the U.S., along with state regulation of payment services as money transmitters), and may be subject to distinct
and sometimes inconsistent legal regimes (for example, the E-Money Directive and the MiCA Regulation in the
EU). Whether a stablecoin is legally recognized as "money," a "security," a "commodity," or "e-money" dictates
the nature of the holder's rights (e.g., a claim against an issuer, a property right in the underlying asset, or a
contractual right), the enforceability of commercial agreements, and the treatment in insolvency. The ambiguity
creates legal uncertainty that can deter widespread adoption, complicate cross-border transactions, and
challenge central banks' ability to maintain monetary policy effectiveness and financial stability.

We recognize that the economic status of stablecoins as money is contentious, and not all stablecoins will
necessarily land in the same bucket. For purposes of this report, we treat stablecoins as a distinct form of money.
We identify ten other types of stable-value assets, both traditional and novel, that stablecoins compete against.

Cash refers to physical, bearer monetary instruments issued by or under the authority of a state,
denominated in the sovereign unit of account, primarily in the form of coins and bills. It remains an
important element of the financial system. Cash offers significant financial privacy, works when internet
connectivity is unavailable, and can be taken across borders. On the other hand, reliance on physical
representations of money greatly limits liquidity and raises concerns about counterfeiting and financial
crime.

Bank Deposits are digital representations of cash held by commercial banks, and are redeemable by
customers on demand. Banks generally use a fractional reserve system, in which they hold only a fraction
of the value of deposits on hand, because under normal circumstances, most customers will not demand
redemption simultaneously. This allows banks to lend out deposits, effectively creating significantly
more productive capital in the economy than the underlying cash base, transforming on-demand assets
into longer-maturity ones and allowing for payment of yield to depositors. The danger is that in times of
crisis, banks will not have sufficient capital to satisfy depositors, and indeed, catastrophic bank runs are

a recurrent feature of financial history. For this reason, banks today are heavily regulated, backed by
central banks engaging in active supervision and monetary policy interventions, and supported by
government-run deposit insurance schemes.

Tokenized deposits take bank deposits and represent them with tokens tradeable on a blockchain. This
allows them, in theory, to take advantage of the vast size and reliability of bank deposits as well as the
flexibility, immutability, and instant settlement of blockchain transactions. Those initial bank
experiments with tokenized deposits use private permissioned ledgers. In June 2025, JP Morgan issued a
pilot transaction with a tokenized deposit coin, JPMD, between one its customer wallets and Coinbase on
the public Base blockchain.

35 Bank for International Settlements Annual Economic Report, June 24, 2025, at 79, https://www.bis.org/publ/arpdf/ar2025e3.pdf.

11

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Non-Bank Balances are held by entities that offer regulated financial services but are not banks. A
major category is held through fintech payment platforms such as PayPal, Block, Alipay, and WeChat
Pay. These services are often used to facilitate payments between merchants and consumers, or between
persons or entities. Credit card balances constitute another category of non-bank balances. Although
users may perceive these balances as functionally similar to bank accounts, they generally do not offer
interest and are subject to distinct regulatory regimes. In the U.S., in particular, only licensed banks are
legally permitted to accept “deposits,” rendering non-bank balances legally and institutionally distinct
from bank deposits.

High-Quality Liquid Assets (“HQLA”) other than cash are easily and reliably redeemable at par and
thus can function as an equivalent to cash under most conditions. Major categories include U.S. Treasury
Bills and sovereign debt of other nations with a track record of financial stability, overnight repurchase
agreements (repos) for securities, and short-term corporate paper, although the risk levels of these assets
differ. Though used to back money market funds and directly available to institutions, HQLAs are
generally not held directly by retail users. However, HQLAs may also be tokenized and made available
directly to end users through a blockchain.

Money Market Funds (MMFs) are held in investment funds that hold HQLAs, enabling them to reliably
maintain a stability peg. Though they serve as an alternative yield-bearing option to bank deposits for
retail users, they are subject to different regulatory regimes when used as investments or securities.
MMFs are typically used more for holding liquid, low-risk assets than for payments.

Tokenized MMFs structure and represents the net asset value of the MMF as a stablecoin. Examples
include BlackRock’s BUIDL, Franklin Templeton’s BENJI, USDM, USDY, and YLDS. As investment
vehicles (securities), tokenized MMFs generally incorporate the yield associated with the underlying
assets into the token. With fiat-backed stablecoins, by contrast, the collateral yield may be kept by the
issuer or allocated to distributors, rather than given to holders.

Store of Value Assets include precious metals and associated funds, and, from the perspective of some
holders, Bitcoin.36 While these assets may be volatile, their value arises differently than fiat currencies.
Thus, at times of crisis or inflation, investors may decide to move assets to them as a more reliable store

of value.

Tokenized Commodities take store of value assets and represent them on chain, most notably precious
metals such as gold. Although this makes the assets more liquid, the denomination of tokenized
commodities in the underlying asset (for example one ounce of gold) distinguishes them from
stablecoins which are based on a stable unit of account. Examples include Tether Gold (XAUt) and Paxos
Gold (PAXG).

CBDCs are digital representations of sovereign money, denominated in the domestic unit of account and
issued by central banks. Unlike conventional central bank reserves that can be accessed only by

36 Because Bitcoin has an algorithmically fixed maximum supply and a rigidly decentralized design, believers argue that it will retain its value and
become economically more significant over time as fiat currencies are debased due to inflation or falling trust in traditional institutions.

12

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

commercial banks and a few select financial institutions, CBDCs may be used for wholesale or retail
purposes, or a combination of both, depending on their structure. Wholesale CBDCs can be accessed only
by financial institutions and are primarily used to improve interbank and cross-border payments. Retail
CBDCs aim to enable the general public to access central bank money digitally, although typically only
through intermediate channels. A few countries, including China, have already launched retail CBDCs,
while several others are testing them.37 CBDCs distinguish themselves from stablecoins because they are
issued by central banks as sovereign liabilities. They are also bound by public money law, and typically
operate on permissioned infrastructures rather than permissionless blockchains.

Stablecoins are thus one of several instruments that can circumvent the limitations of traditional payment and
banking rails.38 To date, the stablecoin market has been the most active and significant in terms of assets
committed. However, it is likely quite early in the development of next-generation money, especially given the
regulatory activity underway in many jurisdictions today. A full discussion of the relative benefits and
limitations of stablecoins compared to alternatives is beyond the scope of this report.

1.3  History

The earliest known conceptualization of stablecoins was in the “Second Bitcoin Whitepaper” published in 2012
by J.R. Willett.39 His idea of a new cryptocurrency was that it should be “backed by trusted entities, pegged to
external values like the U.S. dollar, and traded using the Bitcoin blockchain as the transport layer.” He later
created the Mastercoin protocol (subsequently renamed Omni) to enable virtual coins of this and other types.
The first functional implementation of a stablecoin, however, is considered to be BitUSD, launched in 2014 on
the BitShares blockchain co-founded by Dan Larimer and Charles Hoskinson. While innovative, BitUSD struggled
with complexity, volatility in its collateral base, and weak demand, ultimately failing to maintain its peg over
time.40

That same year, a second model appeared with the launch of Realcoin, later rebranded as Tether (USDT) by a
group associated with the Bitfinex digital asset exchange. Tether introduced the fiat-collateralized paradigm,
claiming that each USDT token was backed 1:1 by U.S. dollars held in reserve. Deployed initially via the Omni
Layer on Bitcoin, Tether quickly dominated the market.41 The launch of Ethereum in 2015, and other smart
contract blockchains within a few years thereafter, provided the crucial building blocks for minting virtual tokens
and associating them with collateral assets to maintain a stablecoin peg.

By 2017, amid growing interest in decentralized applications and the limitations of custodial fiat-backed models,
new experiments emerged. MakerDAO's DAI, launched in December 2017 on Ethereum, introduced the first
widely adopted programmatic overcollateralized stablecoin. Unlike fiat-backed coins, DAI functioned entirely

37 Atlantic Council, Central Bank Digital Currency Tracker, https://www.atlanticcouncil.org/cbdctracker/
38 Heath P. Tarbert, The Dollar's Digital Future, Wharton Future of Finance, https://finance-pillar.wharton.upenn.edu/wp-
content/uploads/2025/03/The_Dollars_Digital_Future.pdf.

39 J.R. Willett, The Second Bitcoin Whitepaper (2012), https://github.com/OmniLayer/omniwallet/wiki/History.

40 Jordan Cole, Exploring Early Stablecoin Projects: The Foundations of Stability in Crypto, BlockApps Blog (December 26, 2024),
https://blockapps.net/blog/exploring-early-stablecoin-projects-the-foundations-of-stability-in-crypto/.
41 Kraken, What is Tether (USDT)?, Kraken Learn Center (February 1, 2023), https://www.kraken.com/learn/what-is-tether-usdt.

13

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

on-chain and without custodians, becoming an important element of the emerging Decentralized Finance (DeFi)
ecosystem.42

Concerns around the opacity of Tether’s reserves led to demand for a more transparent and compliant fiat-
backed alternative. In 2018, Circle and Coinbase launched USD Coin (USDC) through the CENTRE Consortium.
USDC offered regular attestations by accounting firms and held reserves in cash and U.S. Treasuries. This
emphasis on compliance made USDC attractive to institutional users and DeFi platforms.43  In August 2023,
Circle assumed full control over the issuance and governance of USDC), following the dissolution of the CENTRE
Consortium.

One of the most consequential developments in the history of stablecoins—though ultimately unrealized—was
Facebook’s (now Meta) announcement of Libra in June 2019. Libra was envisioned as a global digital currency
backed by a basket of fiat currencies and government securities, governed by the Libra Association, a consortium
of private entities led by Facebook. The project aimed to provide low-cost, borderless financial infrastructure for
billions of users, leveraging Facebook’s vast social network. Libra’s design prompted immediate and intense
scrutiny from global regulators and central banks, who raised concerns about monetary sovereignty, financial
stability, and data privacy. In response to regulatory pressure, the project was significantly revised in 2020 and
rebranded as Diem, shifting to a model of single-currency stablecoins, such as a USD-backed Diem Dollar.
Despite these changes, Diem failed to gain regulatory approval in the United States. In early 2022, the Diem
Association formally announced the sale of its assets to Silvergate Capital, effectively terminating the
initiative.44 Although it never launched, Libra/Diem catalyzed a wave of policy debates and central bank interest
in digital currencies, and played a key role in shaping the regulatory discourse around global stablecoins.

Between 2020 and 2021, stablecoins became essential financial infrastructure in crypto markets. Their combined
market capitalization grew from approximately $5 billion to over $150 billion, driven largely by their utility in
lending, borrowing, and liquidity provisioning within DeFi.45

The emergence of algorithmic stablecoins sought to improve capital efficiency and decentralization by
minimizing or eliminating collateral reserves. The most notable of these was TerraUSD (UST), introduced by
Terraform Labs. Fueled by high promised yields (≈20%) on the Anchor Protocol, UST grew rapidly in market
share.46 However, in May 2022, the system experienced a catastrophic collapse, erasing over $40 billion in value
and precipitating broader contagion across digital asset markets. This event became a watershed moment for
stablecoin policy, prompting global regulatory scrutiny and eroding the perceived viability of algorithmic
models.

42 MakerDAO, The Maker Protocol: MakerDAO’s Multi-Collateral DAI (MCD) System, https://makerdao.com/whitepaper/White%20Paper%20-
The%20Maker%20Protocol_%20MakerDAO%E2%80%99s%20Multi-Collateral%20Dai%20(MCD)%20System-FINAL-%20021720.pdf.

43 Circle, The Role of USDC in DeFi Crypto Interest Markets, Circle Blog (July 16, 2021), https://www.circle.com/blog/usdc-stablecoin-crypto-defi-
lending-interest-markets ("USDC dominates the DeFi space....").

44 David Attlee, Vale Diem: How Facebook’s ambitious stablecoin project came to an end, CoinTelegraph (February 2, 2022),
https://cointelegraph.com/news/vale-diem-how-facebook-s-ambitious-stablecoin-project-came-to-an-end.
45 Federal Reserve Bank of New York, Stablecoins and Crypto Shocks: An Update, Liberty Street Economics, April 2025,
https://libertystreeteconomics.newyorkfed.org/2025/04/stablecoins-and-crypto-shocks-an-update/.
46 Jordan Cole, What Caused the Depeg of TerraUSD? An In-Depth Analysis of Its Collapse, BlockApps Blog (December 26, 2024),
https://blockapps.net/blog/what-caused-the-depeg-of-terrausd-an-in-depth-analysis-of-its-collapse/.

14

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

In the aftermath, market participants gravitated back toward fully reserved fiat-backed stablecoins like USDC
and USDT. Nonetheless, innovation continued in pursuit of a stablecoin architecture that was both scalable and
decentralized, without the fragility of algorithmic models.

Synthetic stablecoins based on delta-neutral hedging, such as Ethena’s USDe, emerged in 2024. USDe combines
staked crypto collateral with offsetting short perpetual futures positions, thereby creating a “market-neutral”
reserve whose net value is designed to remain close to $1. The system also generates yield through staking
rewards and derivatives funding rates. While promising a blend of decentralization, capital efficiency, and
income generation, this approach introduces dependence on derivatives liquidity and funding rate dynamics.
Ethena labels USDe as a “synthetic dollar” rather than a stablecoin, in recognition of its different risk profile
compared to custodial offerings; within our framework, we consider it a form of stablecoin.

1.4  Market Data

Widespread adoption of stablecoins began with the digital asset market recovery and initial DeFi growth in 2020.
The value of the stablecoin market grew sharply through 2021. The 2022 digital asset market crash led to a
plateau in stablecoin values and included the implosion of Terra Luna’s UST stablecoin, which was one of the top
ten most valuable digital assets at the time. Binance-Paxos’ BUSD, another significant stablecoin, was also shut
down through a gradual redemption process in 2023, following a Wells Notice from the SEC.

Figure 2: Stablecoin Assets Over Time (Billions of $)

Overall, stablecoin market capitalization fell roughly 25% during the 2022-23 “crypto winter,” and grew sharply
again once the 2024-25 recovery began. The collapse of the FTX exchange and of SVB, which held significant
USDC reserves, created significant turmoil in digital asset markets but did not trigger a dramatic flight of assets

15

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

from stablecoins. While other depeg moments have occurred, they have tended to be fleeting for the largest
stablecoins.47

Transaction volume using stablecoins shows a similar general pattern of rapid growth in 2021 and 2024-25. And
while, as noted earlier, payments represent only around 1% of that volume, they have been increasing steadily in
recent years. A transaction could be anything, including arbitrage on the price of the stablecoin itself, or activity
otherwise unrelated to the utility of the token. While a useful indicator, transaction volume may therefore at
times be an unreliable indicator of real adoption.

Figure 3: Stablecoin Transaction Value. [Source: Stripe, Visa Onchain Analytics]

The stablecoin market today is growing in two ways: the market capitalization (essentially, HQLA base backing
the tokens) is increasing, and the number and variety of tokens is expanding. There are now over one hundred
stablecoins in circulation, with new ones being issued frequently.

47 Christina Polizu, Anoop Garg, and Miguel de la Mata, Stablecoins: A Deep Dive into Valuation and Depegging, S&P Global, September
2023,https://www.spglobal.com/content/dam/spglobal/corporate/en/images/general/special-
editorial/stablecoinsadeepdiveintovaluationanddepegging.pdf

16

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Figure 4: Number of Stablecoins Launched by Year

The total value of stablecoin assets in circulation exceeds $200 billion at the time of this writing. USDT currently
represents around 60% of market capitalization (and a higher percentage of transaction volume), with USDC
around 25%. Yet there is a long tail of the stablecoin market. There are roughly thirty stablecoins at this time
with a circulating supply in excess of $100 million. (Aggregators report slightly varying numbers for stablecoin
market value and rankings.) The majority of stablecoin activity is on the Ethereum and Tron blockchains,
although that number is falling as activity picks up on Solana and layer 2 networks such as Base and Arbitrum.48

48 Liam Miller, The Rise of Stablecoins: 2025 Market Update and Key Statistics, NFT Evening (June 9, 2025), https://nftevening.com/the-rise-of-
stablecoins/.

17

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Figure 5: Share of Monthly Stablecoin Volume by Chain

The dramatic, temporary spikes in BNB Chain activity in 2021 and in Solana activity in 2024 are good examples
of factors that can influence transaction volume. “Farm multipliers” for the PancakeSwap decentralized
exchange and arbitrage bot activity due to low transaction fees appear to be the reason for the jump in BUSD
activity relative to users and assets in 2021; activity related to miner/maximal extractable value (MEV) seems to
account for the 2024 Solana spike.

As with the digital asset market more broadly, the stablecoin sector has evolved continuously, yet the largest
tokens by value have remained remarkably stable. Tether has consistently been the largest stablecoin by assets
since its inception, with USDC in second place. Aside from the relatively brief rise and subsequent decline of UST
and BUSD, the third-largest stablecoin has been DAI (either alone or in combination with its successor, USDS)
for several years. More recently, Ethena’s USDe has taken the fourth spot. Other broad metrics are consistent
with these rankings.

Figure 6: Leading Stablecoins by Market Share

18

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

As regulatory developments increasingly encourage participation by traditional financial institutions, the
composition of the stablecoin market may change substantially in the coming years. Nonetheless, it is important
to recognize the breadth and heterogeneity of the stablecoin market. Figure 6 shows the evolution of the market
for stablecoins that, while not close to the market capitalization of the leaders, have nonetheless achieved some
degree of traction.

Figure 7: Stablecoins with Peak Market Capitalization Between $0.5 and $3 Billion

Stablecoins may serve distinct needs and target particular geographies. Regulators will differ on what conditions
they impose for stablecoin approval. As markets and legal regimes develop around the world, understanding the
differences among stablecoins will be important for both business and regulatory analysis.

There are at least six key factors that explain usage patterns and adoption of certain stablecoins over others:
information sensitivity (the impact of news about the health of the stablecoin reserves or deviations from the
peg); technological and cost efficiency; network effects (where more users increase the value of the network
polynomially); economic conditions of a country; financial incentives for the user base (such as yields), and
regulatory favorability. These factors may have different impacts depending on the user base and use case. A
follow-up paper will develop a formal model for stablecoin adoption.

1.5  Entities in the Stablecoin Ecosystem

Stablecoins are the nexus of a large and growing universe of firms from the digital asset world, traditional
finance, and other sectors. While most of the discussion focuses on the firms issuing stablecoins, the utility of
stablecoins depends on a number of other market participants. Especially as stablecoins become more deeply

19

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

integrated into both rapidly-growing Web3 and digital asset markets, as well as established payments activities,
roles emerge for facilitators to improve efficiency, functionality, and ease-of use.

1.5.1

Issuers

The issuer is the one responsible for bringing the stablecoin into existence, overseeing the stabilization
mechanism, issuing or redeeming tokens, and managing governance and risk.

Blockchain-Native Firms

The two dominant stablecoins are issued by firms that grew up in and focused on the blockchain world: Tether
(associated with the exchange Bitfinex) and Circle. Most of the other prominent stablecoins are similarly issued
by crypto-native firms, including stablecoin specialists such as Paxos. Some of this reflects regulation, as banks
and other regulated financial institutions are highly constrained in most of the world in their ability to issue
stablecoins. However, crypto-native firms have the technical expertise, market understanding, and credibility
necessary to build a stablecoin business.

Fintechs

Non-bank fintech firms are also well-positioned to issue stablecoins, leveraging their technical know-how and
ability to integrate different payment rails. As of mid-2025, the only one of the 20 most valuable stablecoins
issued by such a firm is PYUSD from PayPal. However, that may change with the acceptance of regulated
payment stablecoins in the U.S. under the GENIUS Act. Also, PayPal and other fintechs, such as Stripe and Block,
are actively engaged in building platforms for stablecoin usage in payments.49

Banks

Until very recently, with the possible exception of an offering from Société Générale,50 there are virtually no
stablecoins issued by the firms that dominate payments and money issuance: regulated banks. While banks
themselves have not historically issued stablecoins, the enactment of the GENIUS Act in the U.S. has established
a framework under which nationally chartered banks supervised by the Office of the Comptroller of the Currency
(OCC) may do so. Anchorage Digital Bank, the first federally chartered crypto bank, has partnered with Ethena
Labs to bring USDtb—previously issued offshore—under U.S. regulatory oversight. In addition, Tether has
announced USAT, a forthcoming U.S.-regulated stablecoin that will likewise be issued through Anchorage Digital
Bank. Both initiatives mark early efforts to align stablecoin issuance with the prudential standards introduced by
the GENIUS Act.  However, this is likely to change as regulators create lanes for banks to participate in the
stablecoin market.

A consortium of major US banks, including JPMorgan Chase, Bank of America, Citigroup, and Wells Fargo, is
reportedly discussing a joint stablecoin launch.51 Fiserv, a major software provider for banks and credit unions,

49 Stripe is launching its own blockchain, in partnership with Paradigm, to support stablecoin transactions. See Emily Mason and Muyao Shen,
Stripe and Paradigm Open Tempo Blockchain to Public, Add Kalshi, UBS as Partners, Bloomberg (December 9, 2025),
https://www.bloomberg.com/news/articles/2025-12-09/stripe-and-paradigm-open-tempo-blockchain-to-public-add-kalshi-ubs-as-partners.

50 See supra note 24.
51 Gina Heeb and Justin Baer, Big Banks Explore Venturing Into Crypto World Together With Joint Stablecoin, Wall St. Journal, May 22, 2025,
https://www.wsj.com/finance/banking/crypto-stablecoin-big-banks-a841059e.

20

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

has launched a stablecoin, FIUSD, with a platform for integrating it into its bank customers.52 State-chartered
banks in the U.S. are also likely to pursue stablecoins, such as Custodia in Wyoming, which operates under a
Special Purpose Depository Institution license designed specifically for digital assets.

Technology Firms and Retailers

Major digital platforms such as Amazon and Apple already engage in significant digital payments activities for
their internal activities, as do major retailers such as Walmart. Meta unsuccessfully attempted to launch a global
multi-currency stablecoin, Libra/Diem, in 2019, and other major technology firms such as Google, X, and
Microsoft have the wherewithal to do so. In China, Alibaba and Tencent already operate massive mobile
payments businesses, albeit through traditional banking rails. To date, these firms have not, however, made
significant moves into stablecoins, with the exception of Meta’s effort that faltered amid governmental
resistance.

With growing recent interest in stablecoins, major retailers including Walmart, Amazon, Expedia, and airlines
have begun to consider the possibility of issuing stablecoins.53 The U.S. GENIUS Act prohibits “permitted
payment stablecoin issuers” from engaging in non-stablecoin activities and prohibits anyone else from issuing
stablecoins.54

DeFi protocols

In the case of a programmatic over-collateralized stablecoin such as DAI/USDS, the stablecoin is minted by smart
contracts. The issuer is effectively the decentralized application embodying the stabilization and governance
mechanisms, which may be structured as one or more decentralized autonomous organizations (DAOs). While
for legal purposes there may be questions about whether an identified group of developers or others is
responsible for aspects of the DAO’s operation, on a practical basis, it is the DAO itself issuing stablecoins, just
as the Bitcoin network is the original issuer of bitcoin.

A key element in this arrangement is governance. Governance token holders may vote on protocol changes and
attributes such as the over-collateralization ratio. In the case of MakerDAO, there have been contentious debates
about various governance aspects, such as the decision to incorporate USDC, a centralized stablecoin, in the
collateral base, in addition to fully on-chain digital assets. That contributed to the launch of RAI—a floating
stablecoin—as an alternative over-collateralized stablecoin that remained limited to Ether for collateral.

Government Affiliates

As noted earlier, the state of Wyoming recently launched the FRNT stable token on seven major blockchains.55 As
a state-sponsored stablecoin, FRNT is different from a CBDC because it is not a central bank liability. Wyoming
has a long record of financial regulatory innovation, with some experiments more successful than others. It

52 Fiserv Launches New FIUSD Stablecoin for Financial Institutions, June 23, 2025, https://investors.fiserv.com/newsroom/detail/2848/fiserv-
launches-new-fiusd-stablecoin-for-financial-institutions.

53 Gina Herb, AnnaMaria Andriotis & Josh Dawsey, Walmart and Amazon Are Exploring Issuing Their Own Stablecoins, Wall St. Journal, June 13,
2025, https://www.wsj.com/finance/banking/walmart-amazon-stablecoin-07de2fdd.

54 GENIUS Act, Sections 3(a), 4(a)(7). Subsidiaries of federally-insured depository institutions may also issue stablecoins.
55 Wyoming Stable Token Commission, supra note 26; Emily Mason, Wyoming Becomes the First to Launch a State-Issued Stablecoin, Bloomberg
(August 19, 2025), https://www.bloomberg.com/news/articles/2025-08-19/wyoming-becomes-the-first-to-launch-a-state-issued-stablecoin.

21

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

remains to be seen whether state-issued stablecoins will find traction in the market, especially if federal
legislation dramatically expands the number of private stablecoin issuers. The U.S. has a dual banking system, in
which states such as Wyoming retain the power to charter banks alongside the federal government. The recently-
adopted GENIUS Act preserves state authority to authorize stablecoin issuers, subject to approval by federal
oversight.

1.5.2  Authorized participants

Stablecoin issuers do not necessarily allow anyone to deal with them directly to request issuance or redemption.
For custodial issuers in particular, there are generally a limited number of authorized participants who have
these rights. (Typically these are firms such as major exchanges, market makers, and proprietary traders.) All
other holders of the stablecoin interact with those third parties or transact on an exchange. Among other things,
this structure may be important for regulatory purposes. Tether was banned from operating in New York State
under a regulatory settlement, but USDT remained widely used on U.S.-based exchanges on the basis that Tether
itself did not directly transact in the US.56

Because they have the right to mint or redeem stablecoins directly at the pegged price, these authorized
participants function as arbitrageurs or market makers. Stablecoin issuers differ in how they structure these
arrangements. According to finance scholars Yiming Ma, Yao Zeng, and Anthony Lee Zhang, USDT had only six
arbitrageurs in 2024 while USDC had 521.57 In both cases, however, there was significant concentration, with the
top five arbitrageurs representing 95% of activity for USDT and 85% for USDC. Although major stablecoins do
not publicly identify their authorized participants, they typically include digital asset exchanges, proprietary
trading firms, prime brokers, and custodians.

On-chain stablecoin mechanisms, such as Programmatic Overcollateralized and Algorithmic Uncollateralized
stablecoins, generally allow any digital asset holder to mint or redeem directly through a smart contract,
although they may limit who can interact directly for functions such as providing collateral or altering
governance elements.

1.5.3  Distributors

Distributors offer stablecoins to end-users. They may or may not also be authorized participants. The most
prominent distributors are centralized digital asset exchanges, which provide custodial wallets to their
customers to hold tokens. Other firms that provide payments and trading services for digital assets, such as
Robinhood, Block, and PayPal, may also function as stablecoin distributors. An important function that these
distributors may perform for custodial stablecoins is to offer yield to their end users, even when the stablecoin
issuer does not do so directly. For example, Circle splits the revenue it earns from holding collateral assets such

56 Attorney General James Ends Virtual Currency Trading Platform Bitfinex’s Illegal Activities in New York, February 23, 2021, New York State
Attorney General, https://ag.ny.gov/press-release/2021/attorney-general-james-ends-virtual-currency-trading-platform-bitfinexs-illegal. This
prohibition may not apply to Tether’s forthcoming US-focused USAT stablecoin.
57 Yiming Ma, Yao Zeng, and Anthony Lee Zhang, Stablecoin Runs and the Centralization of Arbitrage, NBER Working Paper 33882 (May 2025),
https://www.nber.org/system/files/working_papers/w33882/w33882.pdf.

22

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

as Treasury bills with distributors such as Coinbase, which use it to incentivize users to hold USDC in their
wallets.

1.5.4  Custodians or Treasury Managers

For stablecoins backed with off-chain assets, managing the collateral is often the responsibility of specialized
service providers. For example, Tether has a relationship with Cantor Fitzgerald, and Circle has a partnership
with BlackRock. In Circle’s case, the deal includes BlackRock promoting USDC and not launching its own
stablecoin. In other cases, the stablecoin issuer may be paying only for standard custody services – reliably
storing and providing secure access to the assets – or engaging in purchases and sales of various forms of high-
quality liquid assets.

For stablecoins backed by on-chain assets, there is an analogous need for treasury management for the DAO
holding the assets.

1.5.5  Networks

A number of networks are developing to connect stablecoin issuers. For example, Ubyx has launched a stablecoin
clearing network to simplify transitions between stablecoins and bank accounts across different jurisdictions.

The Global Dollar Network (GDN) is an enterprise alliance designed to accelerate and reward global stablecoin
adoption. It is powered by Global Dollar (USDG), a U.S. dollar-backed stablecoin issued by Paxos Digital
Singapore Pte. that is substantively compliant with the Monetary Authority of Singapore’s upcoming stablecoin
framework. Network participants are incentivized to distribute USDG by receiving a share of reserve yield. GDN
partners include Anchorage Digital, Bullish, Galaxy Digital, Kraken, Nuvei, Paxos, Robinhood and Worldpay.

1.5.6  Others

These are many other kinds of activities in the stablecoin ecosystem. For example, Stripe acquired both Bridge –
a stablecoin infrastructure firm – and Privy, a digital asset wallet provider, as part of its effort to build a
comprehensive stablecoin stack.58 Layer 1 and Layer 2 blockchain networks optimized for stablecoins  are also
being launched, such as Tempo, Arc, Plasma, 1Money, and Codex. New stablecoin infrastructure platforms have
launched making it easy to deploy white-labeled stablecoins, such as M0, Agora, and Paxos Labs. Interoperability
systems are making it easier to move stablecoins across blockchains, such as Circle’s Cross-Chain Transfer
Protocol, LayerZero’s Omnichain Fungible Token standard, and Axelar’s Interchain Token Standard.59

58 Paula Tudoran, Stripe to Acquire Startup Privy After $1.1B Bridge Deal to Power Over 75M Crypto Wallets For OpenSea, Coinbase Ventures, And
Web3 Giants, Yahoo! Finance (June 17, 2025), https://finance.yahoo.com/news/stripe-acquire-startup-privy-1-151600147.html.
59 Ubyx Stablecoin Clearing Network Raises $10m, Ledger Insights (June 17, 2025), https://www.ledgerinsights.com/ubyx-stablecoin-clearing-
network-raises-10m/.

23

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

2. Categorizing Stablecoins

There are several ways to categorize stablecoins. The primary one is by the stabilization mechanism. However,
there are other dimensions, such as whether the token offers yield to holders and its denomination, that may be
important for specific purposes. As Circle President and former CFTC Commissioner Heath Tarbert observes,
“two stablecoins purporting to equal $1 may be radically different in the way that they operate and retain
value.”60

Key dimensions for evaluating stablecoin designs include:

Issuance conducted under prudential supervision

●  What (if anything) the stablecoin value is pegged to
●  Governance: Centralized versus decentralized
●
●  Reserve asset composition and liquidity buffers
●  Yield structure
●  Redemption and authorized participant structure
●  Availability: Representation on one or multiple blockchains
●  Transparency: Audits and attestations of reserves versus open-source visibility of blockchains

and smart contracts.

●  Regulation: Regulatory oversight and classification depending on jurisdiction
●  Legal structures: Property rights in stablecoin assets and protections for holders
●  Economic Risks: Credit, liquidity, duration, demand, and operational

While it is possible that other methods will be invented, there are today four types of mechanisms used to
maintain a stablecoin at its peg, along with hybrids of those four:

•  Off-Chain Fully-Collateralized

•  Programmatic Overcollateralized

•  Supply-Based Algorithmic

•  Synthetic Hedged

In the first category are centralized stablecoins issued by a registered legal entity, with legal personality and,
typically, with limited liability. Although they rely on the blockchain as the ledger for transactions involving
their stablecoins, the smart contracts do not govern issuance or redemption. Decentralized stablecoins in the
other three categories operate via immutable self-executing code deployed on a public blockchain (also known as
“smart contracts”), thereby minimizing reliance on centralized intermediaries and custodians.

Like the “moneyness” of financial instruments, centralization operates on spectrum. Both centralized and
decentralized approaches, furthermore, have advantages. Decentralization is not good in itself; it is an
instrumental value to achieve ultimate objectives such as accessibility, censorship resistance, and efficiency.

60 Tarbert, supra note 38, at 10.

24

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Therefore, while we note the division of stablecoin approaches into centralized and decentralized categories, we
do not use it—or the related custodial/non-custodial division—as the primary classification.

2.1  Custodial (Off-Chain Fully-Collateralized)

Custodial stablecoins, more precisely described as off-chain fully-collateralized, include USDT, USDC and
PYUSD, as well as most of the other stablecoins on the list.  This is the model that most stablecoin legislation
includes as “covered stablecoins” or other legally authorized forms. It is conceptually the simplest way for a
volatile digital asset to remain at par: Maintain full collateral to allow bilateral exchange of the stablecoin with
that asset or assets. If anyone who wants the stable asset can easily and cheaply get it, there is no reason the
stablecoin would remain priced substantially lower or higher. As is often the case in finance, of course, the
specifics are more complex, and there are, as noted, various ways this mechanism can be constructed.

To initiate issuance, someone who wants a newly minted stablecoin of this type sends some other asset in
exchange to an authorized party. This authorized party may be a custodian, e.g., a bank, a wallet provider, some
other real-world party, or a smart contract, depending on the type of stablecoin.61 Upon confirmation that the
assets have been received, the issuer creates (also known as minting) and allocates an equivalent amount of
stablecoins to the users’ account or wallet.

We emphasize that this mechanism involves assets stored off-chain, and by implication, subject to some form of
centralized custody. That raises a variety of legal, regulatory, business, and risk considerations, which we
consider in later sections. Furthermore, this model only makes sense if the collateral base is seen as effectively
matching the value of stablecoins outstanding. Unlike traditional assets in the banking system, digital assets are
inherently liquid 24/7, unless constrained by smart contract lockups. Unlike the banking system, which uses a
fractional reserve model to enable short-term deposits to support long-term loans, stablecoins do not have
governmental guarantees as lenders of last resort. Some stablecoins do, however, employ partial
collateralization with off-chain assets as part of a hybrid strategy.

For custodial stablecoins, transparency depends on the issuer’s policies and willingness for disclosure and, which
can range from internally prepared attestations to independent audit reports. Collateral reserves, usually called
the “backing assets”, are generally comprised of fiat currency and/or high-quality liquid assets denominated in
the currency which value the stablecoin is designed to represent. These are held either directly by the issuer or
by a third-party financial custodian and can be invested in yield-bearing instruments – such as treasury bonds
and repos – with the risk profile determined by each issuer. Direct redemption at a one-to-one peg is guaranteed
only by some centralized issuers and is often restricted to a select range of users and/or to those who have
completed Know Your Customer / Anti-Money Laundering (KYC/AML) checks.

Tokenized deposits and MMFs are quite similar to custodial stablecoins in that they use a digital asset on a
blockchain to represent high quality liquid assets which are centrally custodied. Tokenized deposits, however,
operate through fractional reserve banking, which creates different liquidity and redemption dynamics through
the process of maturity transformation. As regulated as investment products, tokenized MMFs do not lend

61 Garth Baughman, et al, The Stable in Stablecoins, FEDS Notes, December 16, 2022, https://www.federalreserve.gov/econres/notes/feds-
notes/the-stable-in-stablecoins-20221216.html.

25

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

themselves to the same use cases as stablecoins. A stablecoin could, however, use traditional MMFs as a backing
asset. Tokenized commodities have a similar structure to custodial stablecoins. As noted earlier, however, we do
not believe they should be considered stablecoins because they are denominated in the prices of the (still
volatile) commodity rather than a stable unit of account.

The most prominent existing stablecoins, such as USDT, USDC, and PYUSD, are backed by fiat currencies (most
commonly US dollars) in the form of high-quality liquid assets. These are typically cash deposits, short-duration
sovereign bonds, and in some cases overnight repos and commercial paper.

Virtually all fiat-collateralized stablecoins today are associated with a single currency. With the GENIUS Act in
the U.S., new stablecoins will be issued under this the fiat-collateralized model under national bank supervision.
As discussed below, fiat-collateralized stablecoins could also be backed by a basket of currencies, in which case
they would likely be denominated in some synthetic value, as was the case with the Libra proposal from
Facebook (now Meta) in 2019. Major regulatory regimes for stablecoins today generally mandate backing in the
home currency only.

While the issuers of these stablecoins typically offer redemption for fiat currency at (close to) a 1:1 ratio in
normal circumstances, the collateral portfolios themselves are exposed to a range of financial risks. Short-
duration bonds carry duration risk as their market value fluctuates with interest rate changes, while bank
deposits and commercial paper introduce counterparty and credit risks. Additionally, the liquidity of these
underlying assets can vary significantly in times of market stress, potentially affecting the redemption process.
The economic model for these stablecoins relies on the issuer’s ability to generate returns from these underlying
assets by capturing interest spreads while managing the associated financial risks, or pairing the stablecoin with
other monetizable financial products. Regular reserve audits and transparency reports are often employed to
reinforce user confidence, though the extent of these disclosures varies

2.2  Decentralized (Non-Custodial) Approaches

The blockchain provides real-time visibility into both collateral reserves and token circulation, while custody
and enforcement are handled programmatically by the protocol itself via smart contracts. Governance over
collateral types, investment strategies, and risk parameters is typically exercised by the protocol’s token holders
– which is issued separately from the stablecoin itself – through on-chain voting or public governance forums.
When the collateral comprises volatile digital assets, reserve values may fluctuate significantly – especially
during periods of market stress. Collateral is managed entirely on-chain, commonly by deploying assets into
decentralized finance protocols, such as liquidity protocols (e.g., Aave) or others that provide yield with limited
risk (e.g., Ethena), within predefined risk constraints.

Issuance and redemption follow algorithmic rules encoded in smart contracts, which automatically adjust token
supply accordingly, either minting or burning, to maintain the peg.

Redemption entails exchanging stablecoins for crypto collateral rather than fiat currency. A leading example is
USDS/DAI, which is generated by locking crypto collateral into the Sky ecosystem.

Although decentralized stablecoins are often lumped together as “algorithmic,” this is a misnomer. As with
custodial stablecoins, there are several sub-categories of non-custodial stablecoins. We identify three major

26

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

approaches to maintaining stability without full off-chain collateralization: Programmatic Over-
Collateralization, Supply-Based Algorithmic, and Synthetic Hedging.

2.2.1  Programmatic Overcollateralized

Programmatic overcollateralized stablecoins seek to maintain stability through on-chain assets. They address
the volatility of digital assets through overcollateralization. To illustrate overcollateralization, a user might lock
$150 worth of Ether (ETH) into a smart contract, known as a Vault, to mint $100 of a stablecoin. This excess
collateral provides a buffer to absorb price fluctuations in the underlying asset. Smart contracts continuously
monitor the value of the locked collateral. If the value of the collateral falls below a predetermined threshold
(e.g., 125% of the value of the minted stablecoins), the system automatically triggers a liquidation event. During
liquidation, the underlying collateral is sold off to repay the debt and any associated penalties. This keeps the
total value of the collateral backing the stablecoin always over the value of the stablecoins in circulation, thereby
preserving the peg. Furthermore, arbitrageurs play a crucial role. If the stablecoin's market price deviates from
its peg, traders are incentivized to buy or sell the asset to profit from the price difference, which in turn helps to
restore the peg.

Examples include DAI/USDS, which pioneered the approach beginning in 2017.62 DAI has endured tremendous
price volatility in its original backing asset, ETH, although it did experience difficulty when digital asset markets
fell precipitously in 2020 during the Covid-19 pandemic.63 DAI/USDS is now backed by a mix of collateral
including USDC and tokenized real world assets such as US Treasury Bills. A different philosophy is embodied by
RAI, which remains solely backed by ETH and is not pegged to a fiat currency. It uses a combination of
programmatic overcollateralization and algorithmic supply arbitrage to significantly dampen, but not eliminate,
price volatility. MIM (Magic Internet Money) utilizes interest-bearing tokens as collateral and allows users to
earn yield on their locked assets while simultaneously using them to mint stablecoins.

Because programmatic overcollateralized stablecoin are fully on-chain, they do not require centralized entities
to custody and control the collateral. They can also be governed in a decentralized fashion using token voting
and a DAO structure for decisions such as changing the collateral ratio. Whether the benefits of decentralization
outweigh the difficulties is a common question in the blockchain context; those drawn to fully on-chain
mechanisms will find programmatic overcollateralized stablecoins appealing.

The overcollateralization approach limits uses of these stablecoins. For payment applications, immobilizing
assets with a significantly greater value than the stablecoins produced is capital inefficient. On the other hand,
they provide a convenient mechanism of increasing leverage and engaging in DeFi activities such as lending,
yield farming, and looping.

62 DAI is the legacy stablecoin issued by MakerDAO since 2017. USDS was created with MakerDAO’s rebranding as Sky Protocol in 2024. Both use
the same basic stabilization mechanism, but USDS is offered on multiple blockchains and has different governance and reward structures.
63 Shalini Nagarajan, Maker Firm Settles for $1.16M With Users Liquidated in Covid Crash, Blockworks (June 23, 2023),
https://blockworks.co/news/maker-settle-black-thursday.

27

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

2.2.2  Supply-Based Algorithmic

Unlike their overcollateralized or fiat-backed counterparts, algorithmic stablecoins do not rely on reserves of

other assets. Instead, their stability mechanisms are encoded in software protocols that algorithmically adjust
the stablecoin's circulating supply in response to market dynamics. The objective is to create a decentralized
currency with an elastic supply, capable of expanding or contracting to maintain a target price. This model's
primary distinction lies in its attempt to achieve price stability through endogenous, rule-based processes.

In the ideal case, algorithmic stablecoins are totally uncollateralized. In reality, virtually all major algorithmic
stablecoins incorporate some element of collateral banking to restore the peg at times of stress. The line
between “true” algorithmic and hybrid stablecoins is thus difficult to draw. We use the category for those
stablecoins who predominant mechanism is supply-based, rather than collateral-based.

The most prevalent architecture for uncollateralized stablecoins is the “seigniorage” model, most prominently
associated with the Terra Luna ecosystem and the UST stablecoin. This design typically employs two separate
tokens: the stablecoin, which maintains the price peg, and a secondary, volatile token often referred to as a
"share" or "governance" token. The protocol's algorithm seeks to regulate the stablecoin's price by creating
arbitrage opportunities. When the stablecoin's market price exceeds its target, the system incentivizes holders of
the share token to mint new stablecoins, thereby increasing the supply and applying downward pressure on the
price. Conversely, if the stablecoin's price falls below its peg, the protocol provides mechanisms for users to
exchange the stablecoin for a predetermined value of newly issued share tokens, thereby reducing the
stablecoin's circulating supply and helping torestore the peg.

A critical aspect of the model is its dependence on market participants' expectations regarding the future value
of the secondary, volatile token. The system's stability is contingent on the belief that the share token will retain
sufficient value to absorb contractions in the stablecoin's supply. This creates the potential for a reflexive
feedback loop, often termed a "death spiral." Such a scenario can be triggered by a significant decline in the
stablecoin's price, which can erode confidence in the peg. As users attempt to redeem their stablecoins, the
protocol is compelled to mint an increasing quantity of the share token, leading to its hyperinflation. This, in
turn, can further undermine confidence in the system's ability to maintain the peg, potentially leading to a rapid
and self-reinforcing collapse of both tokens.

The historical performance of purely algorithmic, uncollateralized stablecoins has highlighted the significant
challenges inherent in this model. The 2022 collapse of UST, which at its peak held assets of over $40 billion,
serves as a prominent case study of the potential failure modes of such systems. This event resulted in
substantial financial losses and had a broad impact on the digital asset market. Consequently, there has been a
notable shift in the design of stablecoins away from purely algorithmic, uncollateralized models. These
approaches also tend to be excluded, or explicitly prohibited, under regulatory regimes such as GENIUS and
MiCA.

However, some algorithmic stablecoins remain in the market, as well as others that incorporate algorithmic
supply incentives alongside partial collateral backing. Another purely algorithmic approach is represented by
Ampleforth, which employs a single token and a "rebase" mechanism. This protocol automatically and
proportionally adjusts the supply of AMPL in every user's wallet on a daily basis. If the price of AMPL is above its
target (which is pegged to the 2019 U.S. dollar's purchasing power), the protocol increases the supply of AMPL in

28

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

all wallets, which is termed a "positive rebase." Conversely, if the price is below the target, the protocol decreases
the supply across all wallets in a "negative rebase."

The key difference is that this supply change is direct and universal; it does not rely on external arbitrageurs to
buy or sell a separate share token. Instead, the AMPL model is path-dependent, aiming for its token to be a
stable unit of account where each holder maintains their proportional share of the network's total market
capitalization, even as the nominal number of tokens they hold changes. This creates a unique dynamic where
the token is non-dilutive, contrasting with seigniorage models where the value of the secondary token can be
significantly diluted during periods of contraction.

2.2.3  Synthetic Hedged

The newest approach to stablecoins is synthetic hedging, also sometimes described as the delta-neutral,
derivatives-backed strategy, or structured finance approach. Originally envisioned in an essay by BitMEX co-
founder Arthur Hayes, it is most prominently represented by Ethena's USDe.64 This model creates a synthetic U.S.
dollar that is fully collateralized by digital assets but simultaneously hedged to neutralize price volatility. The
core mechanism involves a "cash and a carry" trade structure. Ethena takes a crypto asset, primarily staked Ether
(stETH) which provides a native yield, and matches it with a corresponding short perpetual futures position of
the same asset on a derivatives exchange. This delta-neutral strategy ensures that for every dollar of long spot
exposure to the underlying crypto asset, there is an equal and opposite short position. As a result, the value of
the collateral remains stable in U.S. dollar terms, irrespective of the price movements of the underlying asset,
while simultaneously generating yield from both the staked Ether and the funding payments received from the
short futures position.

The hedging model is not purely algorithmic, because it relies on full collateralization. However, unlike the off-
chain collateralized approach, it does not involve centralized entities maintaining collateral and interacting with
the regulated banking system. Instead, it builds on derivatives exchanges for digital assets, which maintain
liquid markets for the perpetual swaps they employ.

USDe quickly amassed a multi-billion dollar market capitalization since its launch. Ethena has also launched a
tokenized MMF, USDtb, collateralized with Blackrock’s BUIDL tokenized treasuries, and announced plans to use
it as a reserve asset during periods of negative funding rates in the derivatives markets underlying USDe.

2.3  Hybrids

Some stablecoins use hybrid mechanisms that combine algorithmic adjustments and collateral backstops to
provide stability. Examples include RAI, FRAX, and USDD. These models aim to strike a balance between capital
efficiency and resilience, offering flexible stability mechanisms that can adjust to changing market conditions.
They often utilize on-chain governance and automated market operations to stabilize their value, providing a
more adaptable, robust yet complex framework compared to purely algorithmic designs. However, adding
collateral to algorithmic stability maintenance also dilutes the decentralized nature of such projects, and is far

64 Arthur Hayes, Dust on Crust, Medium (March 8, 2023), https://ehandbook.com/dust-on-crust-300d4b5cf3ec; Arthur Hayes, Dust on Crust Part
Deux, Medium (March 7, 2024), https://cryptohayes.medium.com/dust-on-crust-part-deux-85a4670239d6.

29

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

from a guaranteed solution if they are not fully collateralized. The most famous failed stablecoin, Terra Luna,
had a Luna Foundation Guard, which deployed billions of dollars of digital assets to restore the peg of UST, only
to fail to prevent its unwinding.65

2.4  Denomination

A stablecoin is typically pegged to some established stable asset, usually a fiat currency. This is the case for two
reasons. First, the whole reason for establishing stablecoins as a distinct class of digital assets is that other
digital assets are volatile. Second, denominating stablecoins in fiat currency facilitates their use for payments.
Serving as a unit of account is one of the three classic economic elements of money. There are, however, several
ways stablecoins are, or could be, denominated.

Single-Currency USD is by far the most common denomination for stablecoins today, both in terms of the
number of stablecoins and the value of assets. Virtually all of the largest stablecoins today peg their value to one
US Dollar. The dollar is the global reserve currency, broadly accepted as a stable asset worldwide. It is worth
noting, however, that the dollar is the native currency of less than 5% of the world’s population and represents a
minority of the world economy. Moreover, the digital asset industry is quite global. Many of the largest firms,
such as Binance, are not U.S.-based, nor is the largest stablecoin firm, Tether. And until recently, the U.S. did not
have a legal regime designed for stablecoins, or a favorable regulatory environment for on-shore digital asset
activity. Nonetheless, the stablecoin market has to date converged on the dollar as its denomination.

Single-Currency Non-USD stablecoins are not technically different from USD-denominated ones, but reference
a different currency. The most valuable, Circle’s EURC, which was the first stablecoin to receive an E-Money
Token license under the MiCA regime, is not at this writing in the top 20 largest stablecoins. If stablecoins
continue to grow in importance, however, non-dollar stablecoins will be a part of the market, given that so many
existing transactions are not dollar-denominated, and other nations do not wish to cede their monetary
sovereignty. There are many non-USD stablecoins in existence today, including several created by Mentom
GYEN issued by GMO Trust, and the Turkish project BitLira (TRYB).

Synthetic stablecoins reference an artificial value, typically representing multiple fiat currencies in a basket.
The idea of creating a basket as the foundation for a virtual global currency is far from new. For more than fifty
years, the International Monetary Fund has issued Special Drawing Rights (SDRs) denominated in a basket of
major currencies. Mark Carney, former head of the Bank of Canada and Bank of England and currently Prime
Minister of Canada, gave a speech in 2019 advocating for a “synthetic hegemonic currency” as a global CBDC,
although this idea has not seen further discussion.66 And as previously discussed, Meta’s Libra/Diem proposal
envisioned a global stablecoin based on a fiat currency basket.  Synthetic stablecoins could also reference values
other than fiat currencies. For example, purchasing power parity (PPP) indices use prices of common goods to
calculate a value, approximating how much money it takes to purchase an equivalent amount over time.

65 A significant reason for both UST’s rapid rise and rapid downfall is that, despite its backers’ emphasis on decentralization, it was heavily
influenced by a small number of actors. For example, adoption of UST was driven by Anchor Protocol, a lending platform that offered extremely
high yields for locking up UST.
66 Mark Sobel, Carney’s Proposals for Multipolarity, OMFIF (October 8, 2019), https://www.omfif.org/2019/10/carneys-proposals-for-multipolarity/.

30

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Commodity stablecoins are denominated in a unit of a physical commodity, most commonly one ounce of gold.
As noted earlier, while not as stable as fiat currencies, precious metals and other commodities may serve an
analogous purpose for some uses of stablecoins.

Unpegged stablecoins do not reference any external asset. Their price is simply the amount it takes to purchase
them in dollars or another currency. However, they are designed to trade in a narrow range, without the wild
volatility characteristic of digital assets. RAI is the most prominent example of this model.

2.5  Yield

Stablecoins were born in a world of zero interest rates. In that environment, there was little need to think about
yield—holding a dollar, whether tokenized or not, was effectively the same as holding cash. But when rates
surged in 2022 and beyond, the reserves backing stablecoins began to generate substantial Net Interest Margin
(NIM).

That shift unlocked billions in revenue and forced the industry to confront a new design challenge: how should
that yield be distributed? Different models emerged. Early players like Tether, benefiting from first-mover
advantage and entrenched network effects, retained their dominance while passing none of the yield to users.

Yield is inherent to stablecoins. Every tokenized dollar—whether parked in Treasury bills, at the Federal Reserve,
or in repo—generates income. The real question is not whether there is yield, but who captures it. There are
multiple ways to distribute yield; stablecoins may use a combination in different proportions.

Despite this, the stablecoin legislation adopted in the U.S. and the EU expressly prohibits payment of yield. MiCA
bans any sort of interest relating to the length of time a person holds both Asset Referenced Tokens and an E-
Money Tokens.67 This applies even to indirect compensation from third parties. The U.S. GENIUS Act prohibits
payment stablecoin issuers from paying any form of interest or yield to holders, but is silent on indirect
payments.68 This means that yield-bearing instruments such as tokenized money market funds are excluded from
treatment as stablecoins under these regimes, and yield-paying stablecoins may not be offered in those
jurisdictions.

Yield to the Issuer

This is the original—and still most dominant—model: the stablecoin issuer retains all yield generated by backing
assets such as U.S. Treasuries. Holders receive a stablecoin that maintains its peg but pays no interest. Tether,
the most prominent example that keeps the entire yield on its token, reportedly made over $13 billion in profit in
2024, mostly from interest on reserves. Tether offers deep liquidity and broad adoption, especially among traders
and exchanges who prioritize utility over passive income. This model is hard for followers to replicate, as new
entrants need to build a liquidity/acceptance network and differentiate to entice users to overuse the most liquid
asset.

67 MiCA, supra note 6, at Articles 40, 50.
68 GENIUS Act, supra note 7, Section 4(a)(11).

31

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Yield to the Distributor

In this structure, the issuer captures the yield from backing assets but shares most of the yield with distribution
partners—typically exchanges and fintech apps. Users do not usually earn yield directly, but distributors will
often pass yield to holders on platform. For example, Coinbase has direct USDC rewards, Kraken has USDG
rewards, and Paypal has pyUSD rewards. It is worth noticing that transparency of the details of the commercial
agreements to the end user is limited. While Circle earned $1.7 billion in interest income on their reserve assets
in 2024, it paid $1 billion out as distribution fees to third party platforms.

Yield to the Holder

This model distributes yield directly to stablecoin holders. In early 2025, stablecoins constituting 4.5% of total
assets fell in this category.69 Tokenized MMF stablecoins are backed by U.S. Treasuries and use on-chain
mechanisms to pass rewards to holders, regardless of where they custody their tokens, while maintaining the
prudential protections of regulated stablecoins. The synthetic hedged stablecoin USDe provides yield to holders
through a combination staking collateral assets and earning arbitrage and basis spreads in its derivatives
operations. For these types of products, U.S. regulatory classification risk is high.

Yield to the Collateral Provider

For programmatic over-collateralized stablecoins, locking up collateral assets in smart contracts earns yield,
similar to participation in other DeFi activities such as liquidity provision for algorithmic market maker (AMM)
exchanges and lending.

3. Use Cases

3.1  Overview

Stablecoins now underpin a wide array of applications, both for data in motion and data at rest. For transactional
uses, such as serving as the trading pair for digital assets on exchanges, payments, and remittances, low costs
and high throughput are valuable. For static uses, such as parking cash-like assets that maintain their value for a
period of time or locking digital assets in DeFi protocols, the ability to earn yield is more critical. The most
effective approach to stablecoin design depends on the application.

Most stablecoin transactions are by retail users, but larger-value institutional transactions (typically exceeding
$1 million) make up the majority of total value transferred. Reflecting this mix, the average transaction size is
$97,900 on USDC and $41,700 on USDT, according to Amberdata,70 suggesting that USDT skews more toward
retail. Some stablecoins have significantly higher average values, including DAI at $812,000 (reflecting its use

69 Miller, supra note 48.
70 Mike Marshall, Amberdata 2025:  Q1 Stablecoin Market Intelligence Report, https://20854245.fs1.hubspotusercontent-
na1.net/hubfs/20854245/Amberdata2025_Q1Stablecoin.pdf.

32

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

primarily in DeFi activities such as yield farming by sophisticated market participants), and FDUSD at $2 million
(suggesting its use for treasury management or high-value trades).

We discuss below five major use cases for stablecoins:

1.  Trading
2.  Payments
3.  Store of value
4.  Credit and lending
5.  Agentic commerce

It also bears noting that stablecoins are used in financial crime, most prominently to launder digital asset
proceeds from illicit activities such as ransomware, terrorist financing, drug sales, evasion of capital controls,
hacks, and scams. The Financial Action Task Force (FATF) reported in June 2025 that “a majority of all on-chain
illicit activity is now transacted in stablecoins.”71 Similarly, Chainalysis found in its 2025 Crypto Crime Report
that illicit on-chain activity shifted from roughly 20% bitcoin in 2020 to over 60% stablecoins from 2022.72
However, such data should be understood within the context that, according to the same Chainalysis report, only
0.14% of on-chain volume involved illicit activity in 2024. Given that stablecoins are roughly 60% of overall on-
chain volume, less than 1% of stablecoin transactions involve illicit activity.73

Custodial stablecoins generally require KYC checks from authorized participants who transact directly with the
issuers. However, ordinary users generally acquire tokens from exchanges or wallet providers rather than from
the issuers themselves. This means that even though regulated providers in major jurisdictions require identity
verification to acquire custodial stablecoins such as USDC and USDT, it is still possible to do so without such
checks.74

Similarly, secondary transfers of stablecoins are purely on-chain transactions. However, to comply with AML
requirements, checks may be performed when transactions pass through regulated providers, and custodial
stablecoin issuers can impose transfer blacklists or freeze transactions at the request of law enforcement. The
dominant stablecoin in the market today, USDT, has been accused of significant use in money laundering,
although today it also works with law enforcement to block some illicit transactions.75

In the case of decentralized stablecoins, the ability to block transactions and the requirements for KYC may be
limited. However, with increasing regulatory scrutiny, even such issuers are moving toward compliance with
AML regimes. In the case of the synthetic stablecoin USDe, Ethena uses a similar approach to custodial issuers,

71 Financial Action Task Force, Targeted Update on Implementation of the FATF Standards on Virtual Assets and Virtual Asset Service Providers
(June 2025), https://www.fatf-gafi.org/content/dam/fatf-gafi/recommendations/2025-Targeted-Upate-VA-VASPs.pdf.coredownload.pdf, at 20.

72 Chainalysis, The 2025 Crypto  Crime Report (February 2025), https://www.chainalysis.com/wp-content/uploads/2025/03/the-2025-crypto-crime-
report-release.pdf, at 6.

73 GENIUS Act Passes Senate, Paving the Way for Landmark US Crypto Legislation, TRM Blog (June 17, 2025,
https://www.trmlabs.com/resources/blog/genius-act-passes-senate-paving-the-way-for-landmark-us-crypto-legislation.
74 BlackRock, Larry Fink’s 2025 Annual Chairman’s Letter to Investors, https://www.blackrock.com/corporate/investor-relations/larry-fink-annual-
chairmans-letter.
75 Oliver Bullough, How Tether Became Money-Launderers’ Dream Currency, The Economist (July 4, 2025),
https://www.economist.com/1843/2025/07/04/how-tether-became-money-launderers-dream-currency

33

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

requiring KYC for direct purchases and redemptions, screening for illicit transactions and communicating with
regulators. DAI monitors transactions and screens wallets for suspicious activity, and its successor, USDS, has
the capability to freeze transactions in response to law enforcement requests.

Whether any of these use cases (beyond trading, which is well-established) become substantial will depend on
market forces, technical developments, and regulation. Stablecoins have limitations, such as blockchain
transaction fees, incompatibility between stablecoins that can cause fragmentation or re-intermediation, the
common need to off-ramp to fiat currencies, and a variety of risks.76 And competing non-stablecoin technologies
are also evolving. For example, the cost of remittances on popular corridors is substantially cheaper than a
decade ago.

3.2  Trading Uses

The primary use case for stablecoins today is as a corresponding asset for digital asset trades, eliminating the
need for fiat currency, and as a liquidity bridge between exchanges. As noted earlier, three-fourths or more of
digital asset trading volume involves stablecoins rather than other volatile digital assets or fiat currencies. For
DeFi, stablecoins are even more essential, because all activity must occur on-chain.77

A study by Nodiens in November 2024 found that Tether has the highest liquidity across both centralized and
decentralized exchanges.78 USDT has the best connectivity with centralized exchanges, with over 39,000 trading
pairs available compared to 2,340 for USDC. Reflecting its importance in the DeFi ecosystem, USDC has over
2,500 trading pairs on DEXs compared to 2,020 for Tether.  Other stablecoins are far behind, with DAI, for
example, having 170 CEX pairs and 260 DEX pairs.79

Stablecoins may also have uses in trading other asset classes beyond digital assets, most notably foreign
exchange (FX or FOREX). Such markets are among the largest and most liquid in the world, processing trillions
of dollars in daily transactions.80 Despite this scale, traditional FX markets suffer from inefficiencies such as high
transaction costs, slow settlement times, fragmented liquidity, and restricted access for smaller participants.
These challenges present a significant opportunity for decentralized solutions like on-chain FX to disrupt the
status quo. On-chain FX enables spot trading, swaps, and derivatives like forwards, futures, and options, creating
new efficiencies and potentially reducing the cost of cross-border transactions. Stablecoin-based FX can offer
faster settlement times, lower transaction costs, and broader market access, particularly in regions where access
to traditional FX markets is limited.

76 Ashley Lannquist, Stablecoins Are Trending, but What Frictions and Risks Are Getting Overlooked?, Atlantic Council (July 8, 2025),
https://www.atlanticcouncil.org/blogs/econographics/stablecoins-are-trending-but-what-frictions-and-risks-are-getting-overlooked/.

77 World Economic Forum and the Wharton Blockchain and Digital Asset Project, Decentralized Finance (DeFi) Policy-Maker Toolkit (June 2021),
https://wifpr.wharton.upenn.edu/wp-content/uploads/2021/06/DeFi-Policy-Maker-Toolkit-Final.pdf.

78 Nodiens, Comparative Analysis of Liquidity Among Stablecoins (November 2024), https://cdn.prod.website-
files.com/66def659b3585808da2bbd8c/67535caa25e07bdeddfeb596_Nodiens_Nov24_Stablecoins.pdf.
79 Nodiens, supra note 29, at 8.

80 According to the Bank for International Settlements (BIS), the average daily turnover in global FX markets reached $7.5 trillion in April 2022,
reflecting a significant increase from previous years Bank for International Settlements (2022). "Triennial Central Bank Survey of Foreign Exchange
and Over-the-Counter (OTC) Derivatives Markets." Retrieved from [BIS](https://www.bis.org/statistics/rpfx22_fx.htm)

34

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

3.3  Payments

Many traditional fiat payment flows are antiquated compared to technological developments in other industries:
They take at least one business day to process, restrict access to those with bank accounts or cards, and require
several intermediaries, nearly all of whom take a cut of the payment total. Stablecoin payments promise
borderless, permissionless access to a global population of customers and merchants at a fraction of the time and
cost associated with fiat transactions. Insulation from the volatility of digital assets makes stablecoins the logical
way to bring the vast world of global payments on-chain.

Though payments volumes on stablecoins today are dwarfed by trading volumes, activity is substantial and
growing. Artemis Analytics estimated that payments using stablecoins reached a $72 billion annualized run rate
in February 2025, while Architect Partners in June 2025 estimated $100-$300 billion annually in stablecoin
payments.81 Payments will be a major impetus for banks and other established financial institutions, beyond
trading firms, to adopt stablecoins. Among traditional banks, Fireblocks found that a majority (58%) of those
using stablecoins did so for cross-border payments, while 36% used them for other forms of payments (retail
transactions, B2B invoicing), and 12% for treasury/liquidity optimization.82

3.3.1  Retail and B2B Payments

The traditional payments funds flow includes three key steps: pay-ins, in which a customer provides payment for
a good or service; payments storage, in which a merchant holds funds received from the customer’s bank once
the transaction settles; and pay-outs, in which merchants move settled funds from storage to their own bank
account.

When merchants accept stablecoin payments, they are expanding their customer base beyond those who hold
cash, those with a bank account, or those with card network access (e.g., Visa, Mastercard). Due to the
permissionless nature of crypto wallets, anyone globally can obtain one. Fintech firms such as Stripe offer
services, including KYC/AML, to simplify these processes behind the scenes.

When accepting fiat payments from customers, merchants must wait anywhere from one business day (in
domestic cases) to nine business days (in cross-border cases) for those funds to settle in storage. This settlement
timing, known as T+ settlement, is due to the various steps and intermediaries needed to move fiat funds
between customers’ and merchants’ banks. Stablecoin payments collapse settlement timing from days to
seconds — once a customer initiates a transaction to move stablecoins from their wallet to the merchant’s
wallet, the stablecoins can settle in the merchant’s wallet within minutes, giving the merchant immediate access
to funds.

81 Artemis Analytics, Castle Island Ventures, and Dragonfly, Stablecoin Payments from the Ground Up (May 2025),
https://reports.artemisanalytics.com/stablecoins/artemis-stablecoin-payments-from-the-ground-up-2025.pdf; Architect Partners, Crypto Payments
& Infrastructure: The Strategic Opportunity (June 11, 2025), https://architectpartners.com/wp-content/uploads/2025/06/Crypto-Payments-
Infrastructure-Part-II-The-Momentum-is-Building.pdf
82 Fireblocks, State of Stablecoins 2025, https://www.fireblocks.com/report/state-of-stablecoins/.

35

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Stablecoins may also be used in B2B payment settings. As of late 2024, JPMorgan moved over $2 billion per day
using its Kinexys Digital Payments platform, formerly called JPM Coin.83 This compares to $10 trillion per day for
JPMorgan’s overall payments business.

3.3.2  Cross-Border Payments and Remittances

Cross-border payments, such as remittances, are a particularly strong use case for stablecoins.84 Cross-border
payments include the above steps of the payment process plus an additional step of currency conversion. The
currency conversion can be orchestrated by converting a customer’s fiat currency into a stablecoin, then
swapping that stablecoin for another stablecoin denominated in the destination currency, and finally burning
that stablecoin for a fiat payout in the destination currency.85 The end-to-end cross-border process may take
minutes rather than days and, depending on the currencies involved, may cost a fraction of what a traditional
foreign exchange transaction would.

Illustrating the potential of stablecoins for cross-border payments, Airtm, which processed $1.2 billion in
transactions in 2024, expects stablecoins to represent the majority of its volume in 2025.86 Fireblocks, in its
stablecoin survey, found that adoption of stablecoins for cross-border payments was highest in Latin America,
with 71% using them, followed by Europe at 58%, Asia 53%, and North America 39%.87

3.4  Store of Value

The third major use case of stablecoins is as a reliable store of value, avoiding the volatility of most digital assets
and offering worldwide availability, unlike U.S. Dollars or other safe fiat currencies.

3.4.1  Alternatives to Deposits and MMFs

For investors in digital assets, stablecoins serve the same function as cash or cash-like instruments in traditional
portfolios: a liquid, safe asset for risk management and to maintain availability for other purposes or
investments. As noted in Section 1.2, they compete with traditional assets such as cash, deposits, and MMFs.
Stablecoin yields offered by distributors and issuers (where applicable) are typically higher than those offered on
traditional cash-like accounts. Today, however, distributor rates for USDC are close to those of high-yield and
institutional savings accounts. As stablecoins become regulated in the U.S., a major question is how the market
will shake out between traditional MMFs, tokenized MMFs, and custodial stablecoins.

83 Kinsexys by J.P. Morgan, Fuel Programmable, Near Real-Time, Multicurrency Payments 24/7, https://www.jpmorgan.com/kinexys/digital-
payments.
84 Raphael Auer, Ulf Lewrick and Jan Paulick, DeFiying Gravity? An Empirical Analysis of Cross-Border Bitcoin, Ether and Stablecoin Flows, BIS
Working Papers No 1265, May 2025, https://www.bis.org/publ/work1265.pdf.

85 Several possible funds flows exist for stablecoin-based cross-border transactions, but this is a common one.

86 Stellar, How Airtm and Bridge Are Scaling Stablecoin Payouts With Stellar, https://stellar.org/case-studies/airtm-x-bridge-cross-border-
payments.
87 Fireblocks, supra note 82.

36

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

3.4.2  Global Access to Stable Currencies

In many parts of the world, stablecoins represent a soft form of dollarization.88 In high-inflation economies like
Argentina (where annual inflation exceeded 211% in 2023) and Turkey (approaching 75% in early 2024), USD-
pegged stablecoins provide essential inflation hedges. In such countries, stablecoins are being more widely
adopted for payments, salaries, and other functions as a means of preserving purchasing power.89 The challenge
is that such uses are likely to be frowned upon by local authorities and financial institutions, for the same reason
they restrict direct access to dollars and other more stable foreign currencies.

Locally denominated stablecoin projects such as BiLira (TRYB)—the local lira-pegged stablecoin—can serve as
on/off ramps by facilitating the transition between local currency and dollar-backed stablecoins like USDT and
USDC. Trading pairs such as TRYB/USDT enable Turkish citizens to access dollar stability in a regulatory-
compliant manner, creating a two-step process that bridges local and global financial systems.

3.4.3  Treasury Management

For enterprises and institutions, stablecoins offer a different but equally appealing value proposition. These
entities are often global in their operations, yet there is no global currency. They must hold assets in local fiat
currencies wherever they operate and use the slow, expensive correspondent banking system to move funds
between those locations. The capital inefficiency of this process is a significant challenge for global firms.
Because stablecoins operate on global blockchains, they are not subject to such limitations. If treasury funds in
one jurisdiction can be converted to stablecoins, they can be moved elsewhere on-chain at minimal cost, and
then off-ramped as needed. Some leading-edge firms are starting to exploit this opportunity.90 For example,
SpaceX uses stablecoins to repatriate revenues from Starlink sales in countries such as Argentina and Nigeria.91
Tax and accounting rules will be an important factor in the speed with which this use case develops.

3.5  Credit and Lending

Stablecoins play a role in the credit and lending ecosystem, particularly in underserved markets. Approximately
2.5 billion people globally remain excluded from formal financial services.92 Local currency stablecoins are
especially critical in this context, as they enable local currency credit, reducing the currency mismatch risk that
can otherwise expose borrowers to significant FX and inflation risks.

Microcredit, a subcategory of this use case, holds promise. Small businesses, SMEs, and local merchants often
generate revenue, pay taxes, and cover operating expenses in local currencies. Providing credit in a foreign

88 See generally Chainalysis, The 2024 Geography of Crypto Report, October 2024, https://www.chainalysis.com/wp-content/uploads/2024/10/the-
2024-geography-of-crypto-report-release.pdf.

89 Elizabeth Cohn, Peso Preservation: Argentina’s Embrace of Stablecoins for Economic Stability, Michigan Journal of Economics (January 8, 2025),
https://sites.lsa.umich.edu/mje/2025/01/08/peso-preservation-argentinas-embrace-of-stablecoins-for-economic-stability/.

90 From conversations with a member of our working group who has significant experience in treasury management, some enterprising corporate
treasurers have quietly been exploiting the global nature of digital assets for many years, even employing volatile digital assets such as bitcoin.
91 Chris Smith, ‘SpaceX Uses Stablecoins to Collect Payments From Starlink Customers’, Says Chamath Palihapitiya, TheStreet Roundtable (Dec. 21,
2024), https://www.thestreet.com/crypto/innovation/spacex-uses-stablecoins-to-collect-payments-from-starlink-customers-says-chamath-
palihapitiya.
92 Financial Inclusion, World Bank Group, https://www.worldbank.org/en/topic/financialinclusion/overview.

37

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

currency, such as USD, exposes these businesses to significant exchange rate risk, potentially undermining their
financial stability. Stablecoins like cKES or cPHP, which mirror local fiat currencies, can mitigate these risks by
aligning the currency of revenues and liabilities.

3.6  Programmable and Agentic Commerce

Beyond efficiency gains, stablecoins advance the capabilities of programmable money. Many stablecoins now
incorporate features enabling automated compliance, conditional payments, and programmability. Stablecoins
may become not merely digital replicas of existing currencies, but fundamentally new monetary instruments
with composability. They would evolve from simple payment tools into programmable settlement layers
enabling complex financial operations, automated treasury management, and novel financial services.

Coinbase’s x402 protocol, launched in May 2025, exemplifies the next stage of innovation by embedding
stablecoin payments directly into HTTP interactions. This resurrects the dormant "402 Payment Required" status
code, enabling autonomous AI agents to transact without human intervention. The next stage of AI’s evolution
is the move toward increasingly autonomous AI agents that can transact and interact directly with external
systems on behalf of users. Major payment providers such as Visa, Mastercard, and Stripe are launching
frameworks for tokenized access to credit cards by AI agents. Stablecoins represent a payment mechanism that is
already natively digital and controlled by algorithms via smart contracts.  As agentic commerce develops,
approaches built around blockchains and stablecoins will compete against those operating on traditional
payment rails.

4. Conclusion

This report has provided a comprehensive overview of the stablecoin market, recognizing the diversity of
approaches in use. The goal has been to broaden understanding of the space and offer a balanced perspective.
We offer a perspective on the evolution of stablecoins and on how policymakers and regulators should think
about them going forward.

4.1  Stablecoin Market Evolution

The future of stablecoins will be driven by four primary factors: evolution of stablecoins themselves; connections
with traditional finance; the larger economic environment; and legal/regulatory developments.

In some ways, the stablecoin market has been, for lack of a better term, stable. Just as Bitcoin and Ether have
been the first and second most valuable digital assets overall since they launched, USDT and USDC have
occupied that position in stablecoins for many years. After skyrocketing from 2020-2022, the value of stablecoin
assets was flat through early 2025 and has grown only about 25% since then. And the custodial model of USDT
and USDC has long dominated the market.

However, as we discuss in Section 2, there are a variety of different stablecoin models, with new issuers
frequently offering distinctive approaches. The market has learned that there is room for other models from the
brief popularity and catastrophic fall of UST, the ongoing operation of DAI (including the introduction of USDS),
and the recent growth of USDe. More competition will come with regulatory legitimacy. This will create market

38

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

pressure for issuers to make stablecoins more appealing, such as by offering higher yields or better integration
with other financial services. While major regulatory regimes currently prohibit issuers from paying interest
directly (though indirect yields through distributors remain available), the status of stablecoins such as USDe
that incorporate yield directly will be important to watch.

Moves to bring the stablecoin world into closer alignment with traditional finance will also have a significant
impact. Stripe’s $1 billion acquisition of Bridge and its plans to launch the layer-1 blockchain Tempo are a
watershed moment. A leading provider of plumbing for financial services seeks to connect to the stablecoin
environment. Other major fintech and payments firms are moving in the same direction. These integrations hide
underlying complexity from users, making stablecoin rails seem no different from other, more familiar ones. As
with stablecoin designs, however, there are a range of ways to connect the blockchain and traditional financial
worlds, privileging one or the other.

Macroeconomic and geopolitical factors will also matter. The business of stablecoins changed dramatically for
centralized operators when interest rates finally moved up. Future changes in interest rates, inflation, economic
growth, and financial crises will significantly impact stablecoin markets. The borderless nature of stablecoins is
an advantage for those who favor the free flow of capital and a danger for nations enforcing currency controls.
Similarly, the fact that the stablecoin market is today almost entirely denominated in US Dollars is a benefit for
the U.S. and a concern elsewhere, which is leading the EU to push for a digital euro and major firms in China to
urge approval of a yuan-denominated Hong Kong stablecoin.93 Or perhaps the advantages of a truly global form
of money will be so significant that a stablecoin-based virtual-dollar ecosystem becomes a practical reality for
cross-border firms.

Finally, the shift from an environment in which stablecoins are used in the world’s largest economies without
clear regulation there, to one in which stablecoin-focused regulatory regimes seem inevitable worldwide, is
bound to impact the industry in significant ways. Differences in regulatory approaches will create arbitrage
opportunities, but efforts toward harmonization will run into differences in viewpoints and concerns about the
benefits of a diversity of approaches. If there is another major stablecoin failure along the lines of UST, or worse,
significant ripple effects into traditional financial markets will lead to further stringent regulations.

It is also important to keep the size of the industry in perspective. The most recent data from researchers at the

Federal Reserve Bank of St. Louis found that only 4.3% of US households held any digital assets, let alone
stablecoins.94 As large as the stablecoin market is, the equivalent markets around fiat currencies dwarf it. The
proper comparison for nearly $35 trillion in stablecoin volume over the past year is not the payment volumes of
networks such as Visa and Mastercard, but the settlement volume of exchange clearinghouses such as the
Depository Trust and Clearing Corporation, which measures its annual volume in quadrillions of dollars. This
means stablecoins have a long way to go.

93 China's Tech Giants Lobby for Offshore Yuan Stablecoin, Sources Say, Reuters (July 3, 2025), https://www.reuters.com/world/china/chinas-tech-
giants-lobby-offshore-yuan-stablecoin-sources-say-2025-07-03/.
94 Juan M. Sanchez and Masataka Mori, Cryptocurrency Ownership among U.S. Households, Federal Reserve Bank of St. Louis (March 11, 2025),
https://www.stlouisfed.org/on-the-economy/2025/mar/cryptocurrency-ownership-us-households.

39

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Until recently, few of the largest global financial jurisdictions had a legal regime that recognized stablecoins. The
EU’s MiCA regulations for stablecoins became effective in mid-2024, and U.S. legislation was passed in July 2025,
alongside activity in Hong Kong, Singapore, Japan, and the UK, among others. The opportunity to offer
stablecoins in compliance with regulation is likely to draw significant engagement from banks and other large
traditional financial services providers, who are also aware of the competitive challenge that stablecoins pose.

One scenario is that traditional financial institutions will quickly come to dominate the market, given their size,
relationships, and established customer trust. Another is that legacy firms will lose out to competitors who are
nimbler and better aligned with new technology platforms. There is a range of views among our expert working
group on this and other topics. Our purpose in this report is not to speculate on broad market developments.
However, this is clearly a time to watch closely for indications of how activity will shift.

A related question is what will happen to those stablecoin issuers that do not meet the requirements of new
regulatory regimes. All the major laws and rules being adopted focus on centralized models, and in some cases
expressly prohibit more decentralized models.

One possibility is that non-compliant stablecoins will go on as they have up to now. Though largely outside
banking and payment regulation, issuers would still be subject to the significantly broader requirements of
financial crime prevention obligations. In the U.S., any entity in the business of accepting and transmitting
money (or anything that can serve as money) is required to obtain state money transmission licenses and register
at the federal level. Globally, the FATF’s standards impose obligations on crypto-asset service providers to
protect against money laundering and other financial crimes. On the other hand, growing regulatory acceptance
of stablecoins may lead to stricter enforcement against those that do not meet the new requirements.
Governments could forbid regulated entities from transacting with non-compliant issuers. Already, major
European-licensed digital asset exchanges have delisted USDT because it is not licensed under MiCA.95 Similarly,
the GENIUS Act prohibits digital asset service providers from selling unlicensed stablecoins or stablecoins from
foreign issuers starting in mid-2028.96

Another question is whether stablecoin regulation will produce greater consistency for licensed stablecoin
issuers. At first, this might seem to be the case: Stablecoin issuers will need to comply with consistent legal
requirements to earn licenses. However, inconsistencies among stablecoin legal regimes worldwide make the

story a bit more complicated. Not all stablecoins will be licensed everywhere, and so issuers may navigate
variability in their practices. The GENIUS Act includes provisions for state licensure of stablecoin issuers, subject
to federal approval. Wyoming has already created a stablecoin-friendly regime of Special Purpose Depository
Institutions, and other states are likely to compete if not preempted by federal legislation.

4.2  Implications for Policy-Makers and Regulators

A follow-up report will examine in greater detail how nations are addressing the important policy questions
raised by stablecoins, including protecting holders, maintaining financial stability, limiting financial crime, and

95 Ryan S. Gladwin, Binance to Delist Tether and Other Stablecoins for EEA Users, Due to MiCA Regulation, Decypt (March 3, 2025),
https://decrypt.co/308449/binance-to-delist-tether-and-other-stablecoins-for-eea-users-due-to-mica-regulations.
96 GENIUS Act, Section 3(b).

40

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

their impacts on the banking system. Here, we offer general guidance based on the market overview materials in
this report.

Stablecoins are Real

Stablecoins already represent a major form of financial activity. The largest stablecoin issuers control over $200
billion in assets, primarily in the form of U.S. Treasury bills. Stablecoins are now essential components of the
multi-trillion-dollar global digital asset trading world. Other uses of stablecoins, while considerably smaller, are
not insignificant and are poised for major growth as new stablecoin regulatory regimes provide clarity and
authorization for established financial market participants to engage. Stablecoins offer compelling narratives for
reducing costs and improving functionality of a variety of financial services. However, stablecoins also have
limitations. They should compete on a level playing field with other mechanisms that offer similar functionality.
Policy-makers should neither limit stablecoins simply because they use blockchains, nor promote stablecoins
simply because they represent a new, innovative approach.

The Diversity of Stablecoins

Though it is tempting to divide “risky” digital assets from “safe” stablecoins and regulate the latter accordingly,
this view misunderstands the nature of financial markets. Tolerance for and demand for risk vary depending on
the customer and the context. Modern finance is built on the recognition that the risk in a properly diversified
portfolio may be significantly lower than that of its constituent assets. Conversely, “safe” locations such as
regulated banks and MMFs are not perfectly safe, as demonstrated by various financial crises and bank failures.
Traditional finance offers an array of risk/reward tradeoffs with regulation that imposes disclosure or business
practice requirements, limits access to riskier offerings, and mandates government backstopping mechanisms
such as bailouts and deposit insurance.

The range of different stablecoin stability mechanisms, legal arrangements, and business practices similarly offer
a variety of options. They provide a spectrum of risk and also various benefits and limitations for certain uses. All
stablecoins should meet some minimum threshold of stability and risk mitigation to distinguish from volatile
digital assets. However, what that minimum looks like and what restrictions limit stablecoin offerings will be
important questions for regulators and policy-makers to consider. A “one size fits all” approach is unlikely to
meet market needs and would limit legitimate opportunities for innovations that improve efficiency and offer

better returns.

Yield Should Not be Ignored

As noted in Section 2.5, stablecoin issuers earn yield on their collateral regardless of their business model. The
major stablecoin regimes prohibit stablecoins from paying interest. Yet that does not prohibit issuers from
funneling it through distributors as an incentive mechanism. A user holding USDC in their Coinbase wallet is
earning yield, just as long as they keep the funds with Coinbase (or another distributor offering such incentives).
Offering any yield has both operational and business consequences, and yields are likely to become a more
significant competitive feature as the stablecoin market grows. This could be good for retail customers, who earn
more on their liquid assets, but challenging for incumbents such as banks. From a regulatory perspective,
providing tokens with yield directly to holders may look more like a security, which may have been a reason

41

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

supporting the German BaFin’s recent ban on Ethena.97 Policy-makers need not authorize direct provision of
stablecoin yield to holders, but they must consider the implications of their decisions and how market
participants will move around them based on financial incentives.

Money Evolves

Though the foundational plumbing is often outdated and messy, the financial sector relentlessly evolves through
technology. Most of the developed world today uses mobile payment systems that provide a completely new
interface for spending money, just as non-bank payment applications swept through the market previously. It
has been more than fifteen years since Bitcoin launched, promising a decentralized financial revolution, a fact
often noted by blockchain skeptics. Only a very small number of people today regularly use bitcoin to make
payments, but that does not mean the thesis was completely wrong, as evidenced by the market capitalization of
digital assets. Stablecoins may be the missing piece that supercharges whole categories of digital asset use cases.
They could become the primary form of money that most people in the world interact with directly over the
course of the next decade or so. Such disruptive change is far from guaranteed, but policy-makers should be alert
to the possibility. If stablecoins take hold more broadly, it will be because of the real benefits they offer for large-
scale mass-market and financial services use cases.

97 BaFin, Ethena GmbH: BaFin prohibits new business with USDe token, June 25, 2025,
https://www.bafin.de/SharedDocs/Veroeffentlichungen/EN/Verbrauchermitteilung/weitere/2025/meldung_2025_03_21_Ethena_GmbH_en.htmlhttp
s://www.bafin.de/SharedDocs/Veroeffentlichungen/EN/Verbrauchermitteilung/weitere/2025/meldung_2025_03_21_Ethena_GmbH_en.html

42

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Appendix A: Major Stablecoins Today

We have compiled a detailed chart highlighting the main attributes of nearly 40 stablecoins. It provides the
following datapoints:

•  Category
•  Token
•
Issuer
•  Pegged value
•  Stabilization mechanism
•  Yield offering to distributors
•  Yield offering to native token holders
•  Composition of reserve assets
•  Redemption on demand
•  Redemption structure
•  Redemption settlement timeframe
•  Attestations or Audits
•  Regulatory authorizations
•  FDIC pass-through insurance or equivalent (non-US jurisdictions)
•  Available Blockchains
•  Bankruptcy protection
•  Exculpatory provision
•  Capacity in which assets are held
•

Issuer discretion in the use of reserve assets

To allow for updating and corrections, and due to the limited space available on pages
of this report, the chart is available online at:
https://whr.tn/stablecointable

43

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Appendix B: Stablecoin Regulatory Definitions

Regulation

EU MiCA

Classification

Key features

Asset-referenced
tokens (ART)

E-Money Tokens
(EMT)

EU MiCA (also the
proposed UK
stablecoin regulatory
framework)

Significant ARTs and
EMTs

US GENIUS Act

Payment Stablecoins

US Securities and
Exchange Commission
guidance

Covered Stablecoins

Hong Kong Stablecoin
Ordinance

Specified Stablecoins

Monetary Authority of
Singapore proposal

Single-currency-
stablecoins (SCS)

Japan Payment
Services Act

Non-SCS or digital
payment token

Digital money-type
stablecoins

Crypto-asset type
stablecoins

ARTs are pegged to the value of multiple fiat currencies,
commodities, cryptocurrency, or a combination. Their
value is derived from the performance of a portfolio of
underlying assets.

EMTs are pegged to a single fiat currency and are
intended to function similarly to electronic money. The
issuer acts as an e-money institution.

Stablecoins are likely to meet certain criteria, including a
large customer base, high market capitalization, or a large
number of transactions. As such, they could be used by a
large number of holders, and raise specific challenges in
terms of financial stability, monetary policy transmission,
and monetary sovereignty.

A digital asset used or designed as a means of payment or
settlement, the issuer of which is obligated to redeem for
a fixed amount of monetary value, and which is
represented as having stable value. Excludes national
currencies, deposits, and securities.

A type of crypto asset designed to maintain a stable value
relative to a reference asset, such as USD or another fiat
currency, or a commodity like gold, or a pool or basket of
assets. Stablecoins generally are designed to track the
value of the reference asset on a one-for-one basis.

Pegged to a fiat currency or a basket of currencies
representing a unit of account or store of economic value
approved by the Hong Kong Monetary Authority.

SCSs are pegged to Singapore dollars or G10 currencies
issued in Singapore. Non-SCSs, including algorithmic
stablecoins, are considered digital payment tokens. MAS
views SCS differently from e-money for the purpose of
regulation.

Issued at a price linked to a legal fiat currency’s value,
promised to be redeemed at par, and regulated as
electronic payment instruments.

Non digital money-type stablecoins are crypto assets
under the Payment Services Act or securities under the
Financial Instrument and Exchange Act.

44

 Wharton BDAP

Stablecoin Toolkit: Financial and Market Dimensions

Appendix C: Contributors

Lead Author

•  Kevin Werbach (Wharton)

Steering Committee

•  Austin Campbell (Zero Knowledge Consulting)
•  Sangita Gazi (Wharton BDAP)
•  Daniel Hellwig (Kepler Cannon)
•  Dimitris Psarrakis (Wharton BDAP)
•  Nikhil Raghuevera (Predicate)
•  Daniel Resas (_Placehodler)

Expert Working Group

Jacek Czarnecki (Stablewatch)

•  Dan Awrey (Cornell)
•  Martin Carrica (Anchorage Digital)
•  Christian Catalini (MIT and Lightspark)
•
•  Amy Davine Kim (PayPal)
•  Miguel Dinis Lucas (Dinis Lucas & Almeida Santos)
•  Lindsey Einhaus (Stripe)
•  Markus Franke (Mento)
•  Yulia Guseva (Florida State University College of Law)
•  Goran Karlic (WHU)
•  Andrei Kirilenko (Cambridge Judge)
•  Caitlin Long (Custodia)
•  Tim Massad (Harvard/Georgetown)
•  Urszula McCormick (King & Wood)
•  Monica Ramirez de Arellano (Anchorage Digital)
•
•  Sumved Sharma (Kepler Cannon)
•  Ramy Soliman (GMO Trust/Stablecoin Standard)
•
Jesse Spiro (Tether)
•  Corey Then (Circle)
•  Andrea Tosato (Southern Methodist University)
•  Helen Tu (Binance)
•  Harald Uhlig (University of Chicago)
•  Yesha Yadav (Vanderbilt Law School)

Jack McDonald (Ripple)

Special thanks to StableWatch for stablecoin market charts.

45

This report is a product of the Wharton Blockchain and Digital Asset Project
(BDAP), part of the Wharton Initiative on Financial Policy and Regulation.

BDAP is a research initiative focused on the evolving blockchain phenomenon,
led by Professor Kevin Werbach. BDAP provides balanced, research-based
perspectives, and draws on world-class Wharton/Penn faculty, alumni, and
students, as well as relationships with officials and industry experts from
around the world, to bridge gaps among stakeholders.

Visit bdap.wharton.upenn.edu for more information.

