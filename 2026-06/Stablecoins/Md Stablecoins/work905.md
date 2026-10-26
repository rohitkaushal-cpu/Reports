BIS Working Papers
No 905
Stablecoins: risks,
potential and regulation
by Douglas Arner, Raphael Auer and Jon Frost
Monetary and Economic Department
November 2020
JEL classification: E42, E51, E58, F31, G28, L50, O32.
Keywords: stablecoins, cryptocurrencies, crypto-assets,
blockchain, distributed ledger technology, central bank
digital currencies, fintech, central banks, regulation,
supervision, money.

BIS Working Papers are written by members of the Monetary and Economic
Department of the Bank for International Settlements, and from time to time by other
economists, and are published by the Bank. The papers are on subjects of topical
interest and are technical in character. The views expressed in them are those of their
authors and not necessarily the views of the BIS.
This publication is available on the BIS website (www.bis.org).
© Bank for International Settlements 2020. All rights reserved. Brief excerpts may be
reproduced or translated provided the source is stated.
ISSN 1020-0959 (print)
ISSN 1682-7678 (online)

Stablecoins: risks, potential and regulation
Douglas Arner, Raphael Auer and Jon Frost1
Abstract
The technologies underlying money and payment systems are evolving rapidly. Both
the emergence of distributed ledger technology (DLT) and rapid advances in
traditional centralised systems are moving the technological horizon of money and
payments. These trends are embodied in private “stablecoins”: cryptocurrencies with
values tied to fiat currencies or other assets. Stablecoins – in particular potential
“global stablecoins” such as Facebook’s Libra proposal – pose a range of challenges
from the standpoint of financial authorities around the world. At the same time,
regulatory responses to global stablecoins should take into account the potential of
other stablecoin uses, such as embedding a robust monetary instrument into digital
environments, especially in the context of decentralised systems. Looking forward, in
such cases, one possible option from a regulatory standpoint is to embed supervisory
requirements into stablecoin systems themselves, allowing for “embedded
supervision”. Yet it is an open question whether central bank digital currencies
(CBDCs) and other initiatives could in fact provide more effective solutions to fulfil
the functions that stablecoins are meant to address.
JEL Codes: E42, E51, E58, F31, G28, L50, O32.
Keywords: stablecoins, cryptocurrencies, crypto-assets, blockchain, distributed ledger
technology, central bank digital currencies, fintech, central banks, regulation,
supervision, money.
1 Douglas Arner, Kerry Holdings Professor in Law, University of Hong Kong, douglas.arner@hku.hk;
Raphael Auer, Principal Economist, Innovation and the Digital Economy, Bank for International
Settlements (BIS), raphael.auer@bis.org; Jon Frost, Senior Economist, Innovation and the Digital
Economy, BIS, and Research Affiliate, Cambridge Centre for Alternative Finance, jon.frost@bis.org.
This article has been published in the Banco de España Financial Stability Review. The article is the
sole responsibility of the authors and does not necessarily reflect the opinion of the Banco de España,
the Eurosystem or the BIS. All errors are our own. We thank Stijn Claessens, Leonardo Gambacorta,
Luis Gutiérrez de Rozas, Antony Lewis, Maria Luisa Leyva Salmeron, Tony McLaughlin, Bénédicte
Nolens, Joe Noss, Tara Rice, Lee Schneider, Hyun Song Shin, Nobu Sugimoto, Andres Wohlberg-Stok,
Dirk Zetzsche and an anonymous referee for comments. We thank Giulio Cornelli for research
assistance, and Nicola Faessler and Maria Canelli for editorial and communications support. Douglas
Arner thanks the Hong Kong Research Grants Council Research Impact Fund for financial support.
BIS Working Papers No 905 1

1. Introduction
Finance and technology have always been co-developmental, with global trends in
digitisation and datafication transforming finance over the past several decades.2 The
2010s, however, ushered in a burst of energy around digital innovation in finance,
emanating from rapidly evolving technologies, particularly information and
communications technologies (ICT). These innovations have affected not only
financial services like payments, credit, investment and insurance, but also the core
foundations of the financial system – namely money, itself (BIS, 2018; 2020). The
Covid-19 crisis has accelerated the shift to digital payments. It has fanned public
concerns about viral transmission through cash (graph 1, left-hand panel) and led to
a surge in the use of digital payments (Auer et al. (2020a); right-hand panel).
As with all periods of rapid innovation, there is the potential for excessive hype,
fads and hyperbole, as highlighted in the classic financial instability hypothesis (Fisher,
1933, Minsky, 1975 and 1982, Kindleberger, 1978) or the more contemporary Gartner
hype cycle (Gartner, 2020). For authorities and the public alike, separating the “wheat
from the chaff” in digital innovation remains a challenge. Just as Paul Volcker
questioned the value of past financial innovations in the aftermath of the 2008 Great
Financial Crisis (WSJ, 2009), future observers may look back sceptically on some
current digital innovations. For central banks and regulators, these challenges take on
particular importance in their pursuit of financial and monetary stability.
Today, authorities around the world are grappling with the rise of digital
currencies and decentralised finance based on both emerging technologies –
particularly various combinations of distributed ledger technology (DLT) and
blockchain3 – and advances in traditional centralised systems underpinning finance.
Many argue that a technological revolution is occurring in money and payment
systems (Arner et al., 2020). From the creation of Bitcoin in 2009, to the emergence
of “stablecoin” projects such as Dai, HUSD, Paxos Standard, Tether, TrueUSD and USD
Coin starting from 2014, to the announcement of Facebook’s Libra project in 2019,
technological challenges to existing monetary frameworks have put a broader set of
regulatory issues on the agenda (see Fatás and Weder Di Mauro, 2019; G7 Working
Group on Stablecoins, 2019; FSB 2020). An overarching consideration is that, when
faced with innovations, authorities must consider how best to apply regulation so that
similar economic and financial risks emerging from varying technologies and
participants are treated similarly, avoiding regulatory arbitrage. Still, the “regulatory
dialectic” of regulation, regulatory avoidance and re-regulation (Kane, 1977; 1981)
may be unavoidable.
While Bitcoin and other cryptocurrencies have not evolved into major
alternatives to sovereign monetary arrangements, stablecoins have raised new
2 Digitisation can be defined as the process of changing information from analogue to digital form.
This is sometimes confused with digitalisation – the use of digital technologies to change a business
model and provide new revenue and value-producing opportunities, or the process of moving to a
digital business. See Gartner (2020). Datafication, meanwhile, refers to the collective tools,
technologies, and processes used to transform an organisation into a data-driven enterprise.
3 The term “blockchain” is often used interchangeably with systems which are often based on a
combination of DLT and blockchain, in which blockchain is in fact a cryptographic security structure.
While it is often used with DLT, it can in fact be used in the context of permissionless, permissioned
DLT and even in centralised systems, in which blocks of transactions are encrypted together. For a
discussion of the spectrum of different types of DLT, see Wadsworth (2018).
BIS Working Papers No 905
2

challenges. They also offer opportunities for specific use cases, with private
stablecoins aiming to be adopted as a means of payment for online purchases (“e-
commerce”), peer-to-peer and micro-payments and a range of potential future
applications. As discussed further below, they also have the potential to serve as a
digital monetary instrument to embed in DLT applications, including for
programmable money or smart contracts.
Concerns about viral transmission by cash have accelerated the shift to digital
payments Graph 1
Search intensity of relevant terms has shot up…1 …leading to greater use of contactless cards2
Interest over time, index Per cent Per cent
The shaded areas in the left-hand panel indicate Jan 2009–Aug 2010 (Swine Flu (H1N1)), Sep 2012–Mar 2016 (Middle East Respiratory
Syndrome Coronavirus (MERS-CoV)), Dec 2013–Mar 2016 (West African Ebola epidemic) and Dec 2019–current (Covid-19). The black vertical
line in the right-hand panel indicates 30 January 2020, when the World Health Organisation (WHO) declared the Covid-19 outbreak a “public
health emergency of international concern”.
1 Data accessed on 21 Mar 2020. Data resulting from worldwide Google search queries for selected terms in the period 2008-current, indexed
to 100 by peak search interest. 2 Share of contactless in all card-present transactions by a global card network. In many countries, transaction
limits for contactless payments were raised in Q2 2020. 3 Countries that are members of the Committee on Payments and Market
Infrastructures (CPMI). Excludes MX and TR due to data availability.
Sources: Auer et al (2020a), BIS (2020) and GoogleTrends.
In the current policy debate, a stablecoin can be defined as a cryptocurrency that
aims to maintain a stable value relative to a specified asset, or a pool or basket of
assets (FSB, 2020).4 Following the “money flower” of Bech and Garratt (2017),
stablecoins inhabit the same realm as Bitcoin and other cryptocurrencies, in that they
are electronic, can be exchanged peer-to-peer and are not issued by central banks.
Stablecoins are token-based; their validity is verified based on the token, itself, rather
than the identity of the counterparty, as is the case for account-based payments (see
Kahn, 2016).
The idea of stablecoins is not entirely new. Indeed, one can argue that early
European public deposit banks, such as the 17th century Bank of Amsterdam, shared
an economic structure with modern stablecoin proposals (Frost et al., 2020; Carstens,
2019; Knot, 2019). Stored value cards and money market funds (MMFs) also offer
4 The FSB and other international policy committees refer to cryptocurrencies as “crypto-assets” to
emphasise that they are not currencies. In this paper, we will use the two terms synonymously.
BIS Working Papers No 905 3

some parallels, as do various forms of mobile money, with discussions of electronic
or “e-money” dating to the 1990s. Yet DLT has allowed for the creation of new digital
forms of money and payment systems that could serve novel purposes and extend
some of the well-known economic and regulatory issues with past innovations into
the digital realm. Existing stablecoins such as Tether, USD Coin and Maker’s Dai aim
to serve as a means of settlement for automated financial products. They offer also
offer the possibility of so-called “smart” contracts, i.e. self-executing code, and
possibilities for “programmable money”.5 Stablecoin proposals like Libra claim that
they will make possible new forms of online exchange through their 24/7 availability,
borderless nature, fractionalisation6 and integration with non-financial services. In this
light, they aim to challenge existing digital means of payment for e-commerce like
traditional bank payments, credit cards and electronic wallets.
The market value of existing stablecoins (Tether, USD Coin, Dai, etc.) reached USD
14 bn in August 2020, yet authorities are braced for a world in which these volumes
are orders of magnitude higher. If this comes to pass, regulation and supervision will
need to adapt quickly, both to monitor and assess risks from stablecoins, and to
address risks to the economy, consumers and the financial system. Facebook’s
announcement of its Libra project has taken the private stablecoin onto an entirely
different plane than any previous cryptocurrency or stablecoin: it is the first proposal
backed by a group of corporations for a “global stablecoin” aimed at retail payments.7
Also with the changes introduced in Libra 2.0 (see Libra Association (2020)), this
project involves the creation of both a new stablecoin with both existing and new
payment systems. The Libra stablecoin in particular could be used across Facebook’s
rapidly growing payments offerings in multiple markets including Facebook Pay,
WhatsApp Pay and Instagram Pay, with potentially rapid access to hundreds of
millions of retail customers in a very short period. If successful, Libra could easily
attain mass adoption across multiple jurisdictions given the established networks of
Facebook and other Libra Association members, with the potential to achieve
substantial volumes relative to the existing payments providers. This could bring a
range of benefits, particularly in the context of cross-border transfers, but it also raises
substantial questions for monetary and financial authorities.
The fact that regulation should treat similar risks arising from differing
technologies similarly does not preclude public authorities themselves from
embracing innovation. Authorities are applying technology in their own functions,
whether in the context of regulation and supervision or in the provision of public
goods. These public goods include appropriate monetary instruments (constantly
evolving with technology) and supporting payment and liquidity infrastructures.
Whereas “financial regulation” is the process of setting the rules that apply to the
regulated entities, “financial supervision” is the compliance monitoring and
enforcement of these rules, which has to be dynamic and adaptable. In particular,
technology opens up new possibilities to develop better forms of financial
5 Smart contracts can be formally defined as programmable distributed applications that trigger
financial flows or changes of ownership if specific events occur (FSB, 2017). In other words, they are
algorithms that automate the execution of contracts. Programmable money is not precisely defined
in the literature, but generally refers to a similar set of applications that make automated payments
conditional on certain objective criteria. See section 2.
6 Fractionalisation refers here to the ability to pay in very small units, eg small fractions of one cent.
7 Global stablecoins are those that can build on existing large, cross-border user bases to scale rapidly
and achieve substantial (global) volume. See G7 Working Group (2019) and FSB (2020).
BIS Working Papers No 905
4

infrastructure, enhance supervisory processes and regulatory outcomes, and even for
embedded supervision (Auer, 2019b; Arner et al., 2017).
Stablecoin proposals are one area where embedded supervision may work in
practice. Information is a central function of regulation, both from the standpoint of
enhancing market functioning and efficiency, and as from the standpoint of
supervision, whether for purposes of market integrity, customer and investor
protection, or prudential supervision. Direct automated provision of data as a
licensing or registration requirement for digital payment systems and markets
provides an important opportunity to better use technology to achieve regulatory
and supervisory objectives as well as reduce costs for market participants. While many
DLT companies have not necessarily focused on this joining of technology, regulation
and supervision, it is being seen in some contexts. The automated provision of
information by certain large value digital payments platforms, such as Alipay and
WeChat Pay in China, provides one example.
At the same time, there are open questions as to whether central bank digital
currencies (CBDCs) and other initiatives could fulfil these functions even more
effectively than privately developed stablecoins. CBDCs would enjoy the backing of
the central bank and would not be subject to the same conflicts of interest around
the asset backing and stabilisation mechanism. Their value could be fixed by design
to the currency they reference (in particular in systems where the CBDC was actually
the digital representation of the currency), thus eliminating fluctuations in value. The
question is how a CBDC could be designed to offer robust interoperability with novel
decentralised financial solutions (see Auer and Böhme (2020) for a taxonomy of
technological designs).
Meanwhile, a number of improvements to existing payment systems could be an
alternative or complement to both stablecoins and CBDCs. In particular, appropriately
designed public sector and public-private initiatives, like retail fast payment systems
(FPS), supported by public digital identify (ID) infrastructures, are already greatly
improving the speed, availability and universal access of payments in many countries.
In theory, FPS could offer additional functionalities or become interoperable with DLT
applications. These could help to achieve some of the same policy goals.
This paper is organised as follows. Section 2 discusses extant stablecoins and
stablecoin proposals, and means for monitoring them, including indicators on price
volatility, volumes, use and economic potential. Section 3 discusses the specific case
of Facebook’s Libra, in particular its latest incarnation (“Libra 2.0”). Section 4 discusses
principles for regulating stablecoins, in particular regarding financial stability and
conflicts of interest around their asset backing. Section 5 discusses the promise of
embedded supervision in the context of stablecoins, CBDCs and other financial
technology frameworks. Section 6 concludes.
2. The stablecoin sector and how to monitor it
Like the proverbial phoenix, stablecoins have risen from the ashes of the 2018
cryptocurrency bubble. After its introduction in 2009, Bitcoin saw at least two distinct
periods of boom and bust – first in late 2013/early 2014, ending with the high-profile
hack of crypto-exchange Mt. Gox, and second in late 2017/early 2018, when the
market capitalisation of Bitcoin, Ether and other crypto-assets peaked at USD 830 bn
BIS Working Papers No 905 5

before crashing. After the latest high-profile speculative bubble, it became clear that
the high price volatility of existing cryptocurrencies impaired their usability as a
means of payment, store of value or unit of account.8 As such, attention moved to a
new type of digital asset which sought a stable value against one or more fiat
currencies and/or other assets. Stablecoins like Tether (introduced in January 2014),
USD Coin, Dai and others entered the limelight. However, it was the announcement
of Facebook’s Libra proposal in June 2019 which for the first time offered a stablecoin
with serious potential to emerge as a monetary alternative with scale – the first so-
called “global stablecoin” (see next section).
Stablecoins aim to preserve a stable value through at least two distinct
mechanisms. Most commonly, stablecoin issuers purport to back stablecoins with fiat
currency, assets or other cryptocurrencies; these are called asset-linked stablecoins.
By contrast, algorithm-based stablecoins seek to use algorithms to increase or
decrease the supply of stablecoins in response to changes in demand (FSB, 2020).
Initially, stablecoins evolved in order to address the failure of Bitcoin and other
cryptocurrencies to provide an effective monetary and payment instrument. This
reflected the preference of main market participants to base transactions and
payments on sovereign fiat currencies, in particular the US dollar. It also reflected
weaknesses in Bitcoin and other crypocurrencies inter alia as means of payment, store
of value or unit of account. However, as no digital form of the dollar or other
sovereign fiat currencies was available, market participants developed the stablecoin
structure as a means to address this issue, as well as to provide an instrument to
support hedging between crypto-assets and fiat currencies. The need was for a bridge
between DLT and fiat currencies, with stablecoins seeking to fill this need. This was
particularly relevant in the context of high volatility in the price of Bitcoin, making it
less useful as a payment instrument and more of an investment – speculative or
otherwise – or hedge. For instance, Tether claims to provide “individuals and
organizations with a robust and decentralized method of exchanging value while
using a familiar accounting unit” (Tether, 2016). Tether has become a common means
of putting funds into and out of crypto trading platforms. Issuers have also portrayed
stablecoins as a solution to promote financial inclusion and address issues in cross-
border payments, particularly for emerging markets: this is in fact the central
proposition initially put forward in the context of Libra (Libra Association, 2019).
Beyond these use cases, a range of new DLT / blockchain applications would
benefit from a trustworthy monetary and payment instrument to embed in digital
environments. For instance, many DLT projects aim to combine a digital environment
and a monetary or payment instrument. In the context of decentralised systems, i.e.
financial systems without formal intermediaries, a representation of value is very
useful in designing smart contracts. One large example is Ethereum – a digital
environment and infrastructure built on a dedicated digital token (Ether). In each case,
however, the volatility of the underlying crypto-asset has been a major barrier for
effective settlement. This has spurred the desire for a means to effectively link digital
transactions with fiat currencies, and the case for stablecoins.
8 The lack of scalability and high costs of achieving payment finality with permissionless DLT based on
“proof-of-work” are also barriers to adoption. Second-layer solutions such as the Lightning Network
aim to enhance efficiency, yet the only fundamental remedy may be to depart from proof-of-work
(Auer, 2019a).
BIS Working Papers No 905
6

If successful, stablecoins could be a means to simplify and enable novel forms of
exchange in the digital economy. For instance, smart contracts could allow for the
automation of certain transactions – such as only transferring the funds for a house
purchase once an inspection report has been received and confirmed. The financial
transfer is thus automated on the basis of certain objective conditions, which trigger
payment. The digital payment would be linked to fiat currency and accounts via the
stablecoin. Decentralised transactions could enhance the efficiency of wholesale
payments and settlement, trade finance and capital market transactions (FSB, 2019).9
In such transactions, embedding payment into the transaction has the potential to
both reduce risk (particularly payment and settlement risks) as well as enhance
efficiency. Smart contracts could also execute micro-payments in the so-called
“Internet of Things”, such as self-driving cars that pay one another to change lanes
when one is in a hurry and traffic is particularly heavy, or computers that pay one
another for file storage space or processing power (see Milkau, 2018). Governments
could use “programmable money” in the form of stablecoins to restrict the purposes
that government-to-person payments could be used for, such as only groceries, or
making such funds “expire” after a certain period.10 Of course, this could also be done
in the context of CBDCs, or even “synthetic” CBDC structures, i.e. arrangements in
which a private intermediary’s digital token is directly backed with central bank
reserves or liquidity facilities (see Adrian and Mancini-Griffoli, 2019; Auer et al.,
2020b). Finally, because of their 24/7 availability, borderless nature and
fractionalisation, i.e. their ability to support programmable micropayments
(McLaughlin, 2020), stablecoins could become a convenient digital means of payment
for e-commerce. Particularly when integrated into online platforms, they could
challenge current means of payment like credit cards and electronic wallets. In
wholesale transactions, they could allow for “atomic settlement”, i.e. delivery-versus-
payment, where a payment and the transfer of ownership for e.g. a security happen
at the same time.
To achieve these ambitions, stablecoins must have a stable value. For all
stablecoins currently in existence, there has been some price volatility in practice, i.e.
fluctuation relative to the reference assets (graph 2, left-hand panel). This has led
some policymakers to quip that stablecoins are neither stable nor coins (ECB, 2019;
Woolard, 2019). Nonetheless, volatility is much lower than that of Bitcoin, Ether and
other cryptocurrencies. Over 2020, the market capitalisation of extant stablecoins (e.g.
Tether, USD Coin, Dai and Paxos) has grown, from a low level (graph 2, right-hand
panel). The total market value of these coins reached USD 14 billion in August,
dominated by Tether.11 This is tiny relative to the global financial system and even
relative to the market for crypto-assets, but this may understate their usage in specific
contexts. Indeed, it is estimated that in mid-2018, up to 80% of Bitcoin trading
volumes involved Tether on one side of the transaction (Vigna and Russolillo, 2018).
9 Decentralisation of financial services refers to the elimination – or reduction in the role – of
intermediaries or centralised processes. This may include the decentralisation of risk-taking, decision-
making and record-keeping away from traditional intermediaries. See FSB (2019).
10 Experiments to date show that programmable money can also be used for more prosaic purposes.
Feltwell et al. (2019) show the sometimes fanciful ideas of consumers, such as paying money into a
penalty jar when personal resolutions not to eat junk food are broken, or adding money to a savings
account when the International Space Station passes overhead.
11 This measure does not take into account JPM Coin, launched in February 2019 to enable
instantaneous payments between institutional clients of J.P. Morgan based on blockchain (J.P.
Morgan, 2019). The current volume of JPM Coin is undisclosed.
BIS Working Papers No 905 7

Moreover, it is notable that stablecoin market capitalisation has more than doubled
since the start of the Covid-19 pandemic. In the same period, there has been a large
rise in digital payments more generally, and in related services such as e-commerce
(Auer et al., 2020c).
Stablecoin market developments Graph 2
Existing stablecoins fluctuate in price1 Market capitalisations have grown strongly
Days traded at each price USD bn
1 Histogram of daily trading prices in USD. The sample includes Tether (2 Jan 2018–14 Aug 2020), USD Coin (9 Oct 2018–14 Aug 2020), Dai
(2 Jan 2018–14 Aug 2020), Paxos (28 Sep 2018–14 Aug 2020) and TrueUSD (6 Mar 2018–14 Aug 2020).
Source: The stablecoin index, Messari.
In parallel to the growth in market capitalisation (a stock measure), the use of
stablecoins has increased, as seen in more transactions in stablecoins on the Bitcoin
blockchain (a flow measure). In fact, total transfer volume in Tether reached USD 1.6
billion in July 2020, while on-chain transfers in Dai and USD Coin peaked at USD 400-
500 million (graph 3, left-hand panel). As a live coin, Tether continues to see high
internet search interest from the general public, even as search interest in Facebook
Libra has recently ebbed (graph 3, right-hand panel).
These current trends are informative to the extent that they give clues into the
potential future growth and operation of stablecoins. From what has been presented,
at least three insights can be drawn. First, the value of stablecoins against reference
assets may still fluctuate more than existing digital instruments like e-money.12
Second, while stablecoins are by nature less susceptible to speculative bubbles of the
type that Bitcoin and other cryptocurrencies have experienced, their market
capitalisation may nonetheless rise and fall rapidly with purchases and redemptions
by investors. Worse yet, without additional private or public backstops, stablecoins
can be subject to severe price discounts or self-fulfilling runs, especially when backed
by risky or opaque assets and in times of market turmoil. Furthermore, if stablecoins
were to gain significant usage, runs on stablecoins could provoke fire sales of the
assets used to back their value. This could have negative spillovers on the rest of the
financial system (Adachi et al., 2020; G7 Working Group, 2019). Third, and more
positively, indicators for monitoring stablecoins in real time are available. Prices,
12 Details of the pegging mechanisms differ across stablecoins. For example Lyons and Viswanath-
Natraj (2020) argue that in case of Tether, it appears that most of the fluctuations are driven by
arbitrageurs’ inability to employ their balance sheets to profit from price differentials.
BIS Working Papers No 905
8

market capitalisation, on-chain transfers and search interest may all be useful
measures of specific aspects of stablecoin markets. A forward-thinking design process
may yield further indicators for the purpose of market monitoring and financial
supervision that can be made available by design.
Use of stablecoins has increased while attention has shifted Graph 3
On-chain trading volume is sizeable Planned coins are no longer seeing substantial attention2
USD millions USD millions Search interest, index
1 Weekly average. 2 Worldwide interest. Data accessed on 14 Aug 2020.
Sources: glassnodestudio; Google Trends.
3. Case study: the structure of Facebook’s Libra 2.0
While the potential attractiveness of stablecoins for specific use cases in DLT systems
is clear, no cryptocurrency or stablecoin has emerged as a real competitor or
alternative to major sovereign fiat currencies. From a regulatory standpoint, there
have been clear regulatory and supervisory issues, in particular around market
integrity (anti-money laundering / combating the financing of terrorism (AML/CFT))
and consumer and investor protection. So far, the concerns around financial or
monetary stability have been limited in most jurisdictions.
Libra 2.0: a primer
This changed with Facebook’s announcement in mid-2019 of its plan to create Libra,
a combination of a private stablecoin and a global electronic payment framework.
Facebook’s initial proposal for the first “global stablecoin” (“Libra 1.0”) met with
considerable scepticism by policymakers around the globe.13 After an intense
dialogue with regulatory authorities, on 16 April 2020, the Libra Association published
a revamped “Libra 2.0” stablecoin proposal (Libra Association, 2020).
13 See Libra Association (2019) for the proposal, and G7 Working Group on Stablecoins (2019), Financial
Stability Board (2020), and Zetzsche et al. (2020b) for the policy discussion on Libra.
BIS Working Papers No 905 9

Libra 2.0 features a three-layer architecture. The first layer is the value backing of
two distinct types of stablecoins: (i) single-currency stablecoins in US dollars (USD),
British pounds (GBP), euro (EUR) and Singapore dollars (SGD), referred to as Libra$,
Libra€, etc., and (ii) a global stablecoin (LBR) that is a basket of the single-currency
stablecoins (see Graph 4). The second layer is the Libra Blockchain, the wholesale
payment system where the Libra Blockchain makes stablecoins available to payment
service providers (PSP) and e-wallet providers, such as Facebook’s digital wallet Novi
(previously called Calibra). In the third layer, the single-currency stablecoins and LBR
are made available to other clients and wallets.
The value backing of the Libra stablecoin is two-tiered. The first tier is the Libra
Reserve, a traditional asset-based value guarantee for single-currency stablecoins.
The second tier is a DLT-based smart contract combining single-currency stablecoins
into the global stablecoin, LBR.
In the Libra Reserve, custodian banks hold assets on behalf of the Libra
Association backing the single-currency stablecoins. The asset backing would be
composed as follows. Over 80% are to be invested in short-term securities (up to 3
months remaining maturity) issued by liquid sovereigns with low credit risk (i.e. A+
rating from S&P and A1 from Moody’s, or higher). The remainder is to be held in cash,
with overnight transfers into MMFs. The MMFs must invest in short-term liquid
sovereign debt (up to 1 year remaining maturity) with low credit risk. The white paper
notes that there will be no currency risk as the currency composition of assets will
match the composition of outstanding single-currency stablecoins. The Libra reserve
has provisions to address emergencies such as rapid outflows of funds during market
turmoil. The Libra reserve can temporarily halt conversion or apply haircuts.
The second tier of Libra 2.0 is a DLT-based global stablecoin. Custodian banks
use their digital signature to cryptographically sign their guarantee into the public
Libra Blockchain. Once these value guarantees are signed into the Libra Blockchain,
LBR is a smart contract combining several single-currency stablecoins into a basket
of currencies. For every LBR that is created, the smart contract “locks in” the respective
amount of single-currency stablecoins on the Libra Blockchain. The white paper
mentions as an example a 50% weight for Libra$, 18% for Libra€, and 11% for Libra£
(the remaining 21% is not spelled out).14
All major policy decisions will require the consent of two-thirds of the Libra
Association Council’s representatives. Each of the association’s members will have
one council member, including Facebook, which will also have only one vote.
On the technological implementation of voting arrangements; the Association
will not use permissionless DLT (i.e. abstain from using proof-of-work or proof-of-
stake).15 This contrasts with the first white paper, which aimed to begin with a
permissioned system then gradually move to permissionless DLT within 5 years.
Instead, a permissioned DLT system will be used, similar to most major financial sector
blockchain / DLT initiatives. The consensus protocol will require a two-thirds majority
in line with the Association’s voting rule.
14 The white paper mentions the possibility that the basket weights are controlled “by a group of
regulators and central banks or an international organization (e.g., IMF) under the guidance of the
Libra Association’s main supervisory authority [e.g., FINMA]”.
15 See Budish (2018) and Auer (2019a) for an assessment of the economic potential of permissionless
DLT.
BIS Working Papers No 905
10

The architecture of Libra 2.0: a global LBR and single-currency stablecoins Graph 4
Libra 2.0 is to feature both single-currency stablecoins and a global stablecoin (LBR) that is a basket of the single-currency stablecoins. The
architecture has three layers. The first layer is the value backing. In the second Libra Blockchain/wholesale layer, the various stablecoins are
made available to retail payment providers through dealers/market makers. The third layer is that these payment service providers, in turn,
make LBR and the single-currency stablecoins available to retail clients for use in payments.
The white paper has a comprehensive discussion on how to comply with
AML/CFT regulation and due diligence. The Libra Association owns a subsidiary called
Libra Networks, which is directly responsible for operating the Libra payment system,
minting and burning Libra stablecoins and administering the Reserve. Members of
the Association will become Validators of the network, i.e. they will validate the
transactions on the Libra blockchain. It also specifies four different types of payment
service participants:
• Designated Dealers (market makers buying and selling Libra stablecoins from/to
Libra Networks and which do not interface directly with users);
• Regulated Virtual Asset Service Providers (“VASPs”) that are registered or
licensed as VASPs in Financial Action Task Force (FATF) member jurisdictions;
• Certified VASPs (certified by the Libra Association but not regulated by a public
authority); and
• “Unhosted wallets” – i.e. anonymous wallets which pose potentially high financial
crime risks. (It is unclear if these wallets will meet regulatory requirements in
practice).
VASPs and “unhosted wallet” providers would have the ability to offer consumer
facing services, such as buying, selling, transferring and holding (in a wallet) Libra
stablecoins. They will interface with Designated Dealers when required (e.g. to buy
stablecoins against fiat currencies).
BIS Working Papers No 905 11

The white paper and a tweet by the Libra Association from 16 April 2020 state
that the association has applied for a payment system license with the Swiss Financial
Markets Authority (FINMA) for its subsidiary Libra Networks, confirmed by a press
release from FINMA.16 The news agency Reuters reports that the Libra Association
will register with the U.S. Treasury’s Financial Crimes Enforcement Network (FinCen).
Policy implications of Libra
The description of the key issues in Libra Association (2020) is much clearer than the
original white paper (Libra Association, 2019). The Association has made progress in
addressing some of central concerns voiced in G7 Working Group on Stablecoins
(2019) and FSB (2020). In particular, it has addressed many of the AML/CFT concerns
(aside from those generally existing around “unhosted wallets”) and clearly detailed
the backing of the reserve.
However, some key issues remain. Generally, it has been widely noted that Libra
has been scaled down, but this is not necessarily true. Paramount is that LBR is to be
created as a new unit of account with an elastic net supply, with potential for use in
payments across the globe. One may argue that LBR is factually no different from the
Libra 1.0 proposal. LBR is backed by a basket of country-specific stablecoins, which in
turn are backed by high-quality sovereign assets. Libra 1.0 would have been backed
directly by a basket of high-quality sovereign assets. The establishment of the
individual major currency stablecoins does however largely address most concerns in
those jurisdictions regarding currency substitution risks (Bank of Canada, 2020).
LBR does still threaten currency substitution, i.e. clients may use LBR as an
alternative to the sovereign currency in a given jurisdiction, particularly those outside
of major currency areas with established Libra stablecoins. This is noted in the new
white paper: “if adoption in a region without a single-currency stablecoin on the
network generates concerns about currency substitution, then the Association could
work with the relevant central bank and regulators to make a stablecoin available on
the Libra network” (Libra Association, 2020, p. 10).
That said, it is unclear how large demand for LBR will be, as many customers
could prefer a single currency Libra (e.g. Libra$). At the same time, for cross-border
transactions in particular, the availability of not only LBR but also the single currency
stablecoins may provide an attractive alternative for many markets with currencies
that are not widely accepted outside of their jurisdiction.
It is also unclear how the single-currency stablecoins differ from other forms of
financial intermediary-created money such as fractional reserve banking and money
market funds. The white paper states that “because of the 1:1 backing of each coin,
this approach would not result in new net money creation”. However, if banks
engaged in the equivalent activity of the single-currency stablecoins, that would be
seen as money creation: the Libra Association will have government bonds as assets
and sight-deposit like liabilities or functionally like a money market fund. The launch
of the single-currency stablecoins could hence have systemic implications, and lead
to a substantial part of the money supply being taken out of the control of the central
bank and the banking system. It could also remove a significant stock of safe assets
from the banking system, a concern voiced by Kahn et al. (2020).
16 See https://twitter.com/Libra_/status/1250786192502685696
BIS Working Papers No 905
12

The governance of the Association is also not fully elaborated. Voting among the
members is spelled out, and a list of criteria for applying for membership is provided.
The list touches on ownership and respectability of the company, AML/CFT
compliance, the technical ability to run a validator node and more subjective aspects
such as company location and the geographic reach of users. Periodic reviews of
membership are planned. Yet it remains to be seen in practice if these fair and
transparent rules will be adequately applied to all members, and therefore will allow
for proper governance of the arrangement.
Compared with the 2020 FSB consultation report on “global stablecoin” (GSC)
arrangements, which spells out 10 recommendations aimed at authorities and GSC
arrangements, an early analysis of Libra 2.0 proposals reveals some gaps. In particular,
the compliance framework described is geared towards AML/CFT and sanctions but
does not inform on other aspects of market integrity, market conduct and consumer
and investor protection. More generally, no details are given on a comprehensive
compliance framework for the overall GSC arrangement and its service providers,
including how to ensure ongoing compliance. No details are given regarding
compliance with international standards from the Committee on Payments and
Market Infrastructures (CPMI) and International Organization of Securities
Commissions (IOSCO). These would be relevant for activities pertaining to a Libra as
a systemically important payment system or other form of financial market
infrastructure (FMI) and also to the management of the reserve (IOSCO, 2020; FSB,
2020).
Regarding AML/CFT compliance with FATF rules, certified VASPs and unhosted
wallet providers will not benefit from the same level of compliance achieved by
Regulated VASPs, and only the latter will seek full FATF compliance. Risk mitigation
measures regarding the management of the reserve appear incomplete at this stage.
For instance, details on loss-absorbing capital buffers, restrictions from lending and
other aspects are missing, alongside further details on the composition of assets
comprising the reserve.17
While the Libra Association plans contingency measures in response to stress
scenarios that could result in a run from Libra stablecoins, contingency and business
continuity plans are not provided for the overall GSC arrangement, e.g. in case of
failure of a significant number of validators, and/or VASPs or unhosted wallets. No
comprehensive resolution framework, including continuity and recovery of identified
critical functions and activities of the Libra GSC arrangement is provided. No details
are given on any contractual obligations in place to ensure such mechanisms are
effective, or on the involvement of relevant authorities. This is a major omission.
4. Principles for regulating stablecoins
In order to address the concerns which have arisen around stablecoins and to provide
an appropriate framework for market evolution, authorities around the world are
working to develop regulatory systems and structures. At the international level,
discussions around crypto-asset and stablecoin approaches are taking place through
the G20, G7, FSB, IOSCO, BCBS, FATF and others. A range of other authorities
17 Coelho et al. (2019) discuss how technology might help to bring down the cost of AML/CFT.
BIS Working Papers No 905 13

including those in Switzerland, Russia and the UK have either enacted related
legislation or are in the process of development. From the standpoint of major
jurisdictions, probably the most comprehensive approach so far was announced by
the EU in September 2020 (EC, 2020).
As a starting point, it is important to differentiate between stablecoins in general
– which raise many regulatory issues but so far are not systemically important – and
what the FSB has called “global stablecoins” or the EU calls “significant stablecoins” –
where the bar for compliance on a range of policy issues will be much higher. In
particular, the latter pose higher risks to financial stability, monetary policy
transmission and monetary sovereignty that would not be present for more limited-
purpose coins. They may be considered “systemically important payment systems” or
other forms of FMI. This section will consider principles for regulating both in turn.
In regulating any stablecoin, the starting point should be an appropriate
registration or licensing regime, which allows for adequate information and
monitoring, combined with prudential requirements in appropriate cases. It is
essential to build systems to collect data on such instruments. Thus, a registration
requirement is likely to be useful in the jurisdiction of establishment. Because of the
inherent cross-border potential, authorities will need to combine this with
information sharing arrangements between each other. Without data and monitoring,
potential financial stability risks may develop unobserved. In particular, there is the
potential that a limited-purpose stablecoin may quickly evolve into a global
stablecoin, thus fomenting much higher financial stability risks. This highlights the
value of proportional graduated approaches, with differential treatment based on
factors relating to the underlying structure or scale. For example, the proposed EU
approach will provide different requirements for utility tokens (non-stablecoins),
financial instruments (under the existing financial regulatory framework), e-money
stablecoins (single currency, on-demand payment at par), asset-backed stablecoins,
and significant stablecoins. The latter, which pass certain thresholds, have much
higher regulatory requirements.
In addition to financial stability risks, stablecoins clearly raise a number of other
regulatory and supervisory concerns, in particular in relation to market integrity and
consumer / investor protection.18 Much attention has been already directed by
international regulatory organisations – in particular the G20 and FATF – towards
AML/CFT issues and approaches to crypto-assets and these apply fully to stablecoins.
Likewise, international regulators – in particular IOSCO – are considering issues
relating to market manipulation, fraud, abusive practices toward consumers, etc.
(IOSCO, 2020). These traditional market regulatory concerns arise in the stablecoin
context as in the crypto-asset area more broadly. Yet stablecoin arrangements bring
with them additional investor protection concerns given the link between the digital
asset and fiat currency or other assets. In particular, stablecoin issuers may face a
strong incentive to invest in risky assets, or to lend out assets backing the stablecoin,
to achieve higher returns (see Frost et al., 2020). Indeed, in the absence of regulation,
stablecoin issuers can earn a profit by investing in higher-return or illiquid assets, or
by lending funds or assets, while paying low or no interest to stablecoin holders.
18 Auer and Claessens (2018) build a database of regulatory news pertain to cryptocurrencies and
examine how such events effect valuations and usage.
BIS Working Papers No 905
14

These incentives make asset segregation and collateral considerations key, in addition
to market surveillance and disclosure frameworks.19
These arguments have historical and current examples. Throughout history,
whenever new issuers have been successful in circulating a currency, they soon find
themselves tempted to engage in profitable activities such as borrowing and lending.
During the Mexican Revolution, for example, several different generals issued
currencies or forced banks to make loans to pay soldiers’ salaries, leading to high
inflation and a debasement of the private bank currencies in circulation (Bátiz
Vázquez, 2009). As a more recent example, the issuer of Tether had until recently
claimed that every Tether was 100% backed by fiat currency. Since 2019, it has been
accused by the New York Attorney General of lending at least $700 million to Bitfinex,
an affiliated crypto-asset trading platform (see NYAG (2019)). The shift from full
backing by safe assets to a mix of safe assets and credit is in some ways reminiscent
of the Bank of Amsterdam in the late 18th century, which lent extensively to the Dutch
East India company, the Town Treasury and Town Loan Chamber prior to its downfall.
A key difference is that in Tether’s case, the balances have actually continued to grow
after the extent of lending to affiliated entities has come to light (graph 5).20
Tether: “déjà vu all over again”? Graph 5
Bank of Amsterdam Tether
Millions of guilders USD mn
Sources: van Dillen (1934); Frost et al. (2020); CoinMarketCap.com; authors’ calculations.
Regardless of their size, the digital and borderless nature of stablecoins will raise
cross-border coordination issues. As such, as a first principle for policy, it will be
essential to develop appropriate regulatory and supervisory tools in advance. This is
particularly true from the standpoint of global stablecoins; tools should be activated
when a global stablecoin or global stablecoin arrangement is identified. The tools
could come from a variety of experiences. One example is the supervisory college
19 An additional facet is fraud. If a global stablecoin is able to enhance inclusion, it customers – who are
less accustomed to managing their financial lives (especially online) – may be more vulnerable to
phishing attacks and account takeovers in general.
20 Griffin and Shams (2020) find, based on blockchain data, that purchases with Tether are timed
following market downturns and result in sizable increases in Bitcoin prices. They argue that these
results are “consistent with Tether being printed unbacked and pushed out onto the market” (p.1918).
BIS Working Papers No 905 15

approach which is now applied to large cross-border banks. Another comes from the
experience with FMIs: these are in some cases supervised via supervisory colleges, in
others established under specific legal and regulatory systems as part of a
cooperative design approach between private and public participants (such as SWIFT,
CLS and Euroclear). In some cases, this could involve regulation as a utility or
operation by the central bank or otherwise itself (Zetzsche et al., 2021). Reflecting this
approach, to the EU has proposed not only a framework addressing the full scope of
digital assets, but also a separate framework for the licensing, regulation and
supervision of DLT FMIs.
Second, more informal means of cooperation will be needed. Memorandums of
understanding (MoUs) and multilateral memorandums of understanding (MMoUs)
could be helpful from a cross-border standpoint. The challenge in many cases will be
the necessity to bring such instruments into the formal regulatory and supervisory
perimeter of relevant authorities.
Third, beyond information sharing and enforcement, international standards may
be particularly useful from the standpoint of approaches to embedded supervision –
setting standards for the systems and approaches which could be required as part of
the registration / licensing process for stablecoins. We return to this in the following
section.
Fourth, for global stablecoins, specific regulatory treatment is necessary. Like
most forms of systemically important FMI or financial institution – both domestic and
global – systemic importance can be difficult to define precisely.21 The elements
however are some combination of size, scale and interconnectedness: economies of
scope and scale combined with network effects all potentially suggest systemic
importance in the context of the financial system. This is reflected in the EU proposals,
in the context of both “significant stablecoins” as well as DLT FMIs.
In seeking an approach to global stablecoins, a key challenge is identification of
GSCs. This is problematic because the entry of non-traditional participants in finance
– particularly large technology companies (big techs) – means that existing size, scale
etc. can all be leveraged very rapidly to achieve a dominant position in specific market
segments or financial infrastructures (BIS, 2019; Petralia et al., 2019). From a financial
stability standpoint, in addition to traditional risks of “too big to fail” and “too
connected to fail”, the private sector nature of stablecoins raises risks to monetary
policy transmission and may threaten the effectiveness of the central bank’s lender of
last resort function. For all technological systems – private or otherwise – operational
and cyber incidents are relevant, but these become even more pressing for a
stablecoin that may be very widely adopted. Because of the scale, other issues also
rise to the financial stability level, including market integrity (the risk of a global
stablecoin being widely used for criminal activities), consumer protection (the risk that
a collapse destroys many individuals’ financial resources) and risks of anti-competitive
behaviour and restrictions on innovation (due to market dominance). Such
identification could build on frameworks for global systemically important financial
institutions (G-SIFIs), or could be done in the context of a specific proposal – as in the
context of Libra, or as has been done with CLS. Proposals could be both purely private
or some sort of public-private process, as has been historically more common in the
21 For a discussion of indicators on systemic importance in the context of banking, see BCBS (2013).
BIS Working Papers No 905
16

evolution of major payments infrastructure domestically, regionally and
internationally.
The content of the regulatory approach would involve a variety of specific
instruments. These could be activity-based, entity-based or infrastructure-based
depending on the nature of the specific GSC. Activity-based approaches would vary
depending on the nature of the products and services offered. These could relate to
payments, securities, etc. Cooperation and coordination on licensing, market access,
supervision, resolution, etc. would all be required.
The key point is that the Libra experience should be used as an opportunity to
develop systems at the global level to identify GSCs, to put in place appropriate
supervisory arrangements and to monitor their activities and impact. This is exactly
the approach that is being pursued in the context of the development of a set of 10
principles from the FSB to address GSCs (FSB, 2020) as well as the new EU proposals.
The FSB principles highlight:
• the need of the supervisory authority to have appropriate powers, tools and
resources;
• that regulatory requirements should be applied on a functional and proportional
basis;
• that there is comprehensive regulation, supervision and oversight on a cross-
border basis and that these are met by a GSC arrangement before commencing
operations;
• that GSC arrangements have in place a comprehensive governance, risk
management and fit and proper framework, robust data systems, appropriate
resolution and recovery plans; and
• that GSC arrangements provide sufficient data and legal clarity for users,
particularly around redemption and insolvency.
In looking at approaches, to the extent that one is creating an automated
financial product, it may well make sense to explore automated or embedded
supervisory approaches (see next section).
Last, the repercussions of stablecoins on the disintermediation of the traditional
banking sector should also be taken into account. If consumers switch from sight
deposits and payment accounts towards stablecoins, traditional bank lending could
become costlier (see Kahn, 2016). A closely related implication is that certain central
banks could receive substantial inflows onto their balance sheets if stablecoins are to
be restricted to keep reserves at the central bank (as is often the case under e-money
regulations). This may also affect the transmission of monetary policy.
5. From regulation to supervision: the promise of
“embedded supervision"
Regulation and supervision are evolving with technology. In some cases, in addition
to the use of technology for regulatory compliance, monitoring and implementation
(regtech and suptech), regulatory and supervisory requirements are being built into
technological systems. Some jurisdictions are already implementing or planning
automated reporting (see EC, 2020). In recent work, Auer (2019b) puts forward the
BIS Working Papers No 905 17

concept of “embedded supervision.” Embedded supervision is a framework that
provides for compliance to be automatically monitored by reading the ledger of a
DLT-based market (see Graph 6). The ledger of a DLT-based market contains much
information relevant for supervisory purposes. As such, it can be used to improve the
quality of data available to the supervisor, while reducing the need for firms to actively
collect, verify and report data to authorities. Through their use of DLT, stablecoins
could allow this approach in practice.
Compliance monitoring process using embedded supervision Graph 6
Embedded supervision can verify compliance with regulations by reading the distributed ledgers in both wholesale (symbolised by the green
blockchain) and retail banking markets (symbolised by the yellow blockchain). Supervisors could access all transaction-level data. Alternatively,
the use of smart contracts, Merkle trees, homomorphic encryption and other cryptographic tools might give supervisors verifiable access just
to selected parts of such micro data, or relevant consolidated positions such as to institution-to-institution or sectoral exposures. Firms would
only need to define the relevant access rights, obviating the need for them to collect, compile and report data.
Source: Auer (2019b).
Allowing for embedded supervision could be of substantial importance for the
development of so-called asset “tokenisation” – the process by which claims on or
ownership in real and financial assets are digitally represented by tokens, allowing for
new forms of trading and improved settlements (Bech et al., 2020). In particular, one
key early use case of embedded supervision may be in the monitoring of the full asset
backing of a blockchain-based stablecoin. Currently, USDC and Paxos publish
monthly public auditor reports of the smart contract and of the reserve on their
websites; to reduce fraud risk this process could be fully automated and even real-
time.22 To exemplify both the merits and limits of embedded supervision applied to
stablecoins, consider the revised Libra proposal.23 Libra 2.0 highlights that when it
comes to applying embedded supervision, one needs to carefully distinguish the use
of DLT from other traditional elements that involve technology, but still rely on the
22 There are many concerns with Libra that go beyond the discussion of the value backing discussed,
see the above discussion in Section 4.
23 Other examples include MakerDao’s DAI, as well as other “on-chain” stablecoins in the terminology
of Bullmann et al. (2019).
BIS Working Papers No 905
18

value underpinning provided by supervised institutions and the legal system. Auer
(2019b) discusses principles that should govern a framework designed to make use
of a market’s distributed ledger for financial supervision.
A first of these principles goes back to how the value underpinning of the single-
currency stablecoins is guaranteed in Libra 2.0: it is the banks’ digital signatures in the
ledger that underpin the value of these coins. Obviously, there is nothing other than
the judicial system that obliges banks to honour these guarantees. The first principle
of embedded supervision is that the process of tokenisation must be supported by
the legal system. The connection between the claim on or ownership in the underlying
asset and the record of the digital token must ultimately be established by the legal
system and relevant contractual arrangements. This is true for stablecoins, but also
for assets such as real estate or shares in a bricks-and-mortar business. Importantly,
this means that just as in a traditional financial system, a decentralised financial
system needs to be backed up by an effective legal and judicial system and
supporting enforcing institutions for contractual arrangements (see Zetzsche et al.,
2020a).
A second principle relates to exchange in DLT-based markets: transactions and
transfer of ownership must be irrevocable and final – otherwise balance sheet items
are not definitive (see CPMI-IOSCO, 2012; CPMI, 2017). Even with “permissioned” DLT,
there may be no central entity capable of vouching for finality with a legally binding
signature. The risks of one party failing to settle transactions remain (Bech et al., 2020).
As such, another criterion for transaction finality must be established, with payment
finality being a particular concern.
A third principle is to consider how the market will react to being automatically
supervised. Embedded supervision focuses on the concept of economic finality
proposed in Auer (2019a), i.e. economic finality is the notion that a transaction is final
once it is no longer profitable to reverse it.24 When it comes to applying this
consideration to the case of Libra 2.0, the white paper does not spell out how
transaction finality will be achieved. It does spell out a standard process to achieve
consensus on transactions via a 2/3 supermajority among the association members.
What is however missing is a set of rules that would spell out what were to happen if
indeed 2/3 of the members of the association were to coordinate to fraudulently
undo transactions via so-called history reversion attack. Further information is thus
needed to establish economic finality, and to ensure that attempts to deceive the
supervisor will be unprofitable.25 It is of course important to remember that
technological finality or even contractual finality is not the same as legal payment
finality (see Zetzsche et al., 2018), which will generally require settlement across the
books of the central bank or via an appropriately authorised payment system.
The last principle concerns the broader societal goals when designing embedded
supervision. Despite substantial technological advances of recent decades, financial
24 Auer (2019a) examines economic finality for the proof-of-work-based consensus schemes used in
Bitcoin.
25 Auer (2019b) extends the theoretical considerations regarding transaction finality to the impact of
the supervisors’ actions on the regulated market. Regulated firms incur a cost in complying with
regulation that they would not incur voluntarily. By the same token, in the DLT world, this creates
incentives for a regulated firm to cheat the supervisor by altering the transaction history in the
blockchain. He thus also models the supervisor’s impact on the market.
BIS Working Papers No 905 19

services have for a long time remained expensive (Philippon, 2015 and Bazot, 2018).
This might partly reflect high barriers to entry in financial services, some of which are
created by the administrative burden of complying with financial regulation. As a side
effect of their focus on detailed regulation and supervision to tackle the risks of large
and complex financial intermediaries, supervisors may have inadvertently further
favoured concentration – by creating compliance costs that weigh disproportionately
on smaller intermediaries (see Graph 7).26 While these are certainly not the only
barriers to entry in financial markets, measures to reduce such costs may enhance
competition and contestability.
Smaller financial institutions are disproportionately affected by compliance costs
In per cent Graph 7
Note: estimate for US deposit-taking institutions. Sources: Auer (2019b) and Dahl et al (2016).
One goal of embedded supervision should hence be to achieve high-quality
compliance at lower cost, thus levelling the playing field for large and small
institutions.27 In the context of Libra 2.0, one operational aspect is for supervisors to
take an active role in the design of the market, in particular regarding standardisation
of the database structure – for example, to ensure interoperability of the Libra
blockchain with other blockchains. A second goal might be to develop a freely
available open-source suite of monitoring tools with the aim of clarifying how specific
regulatory frameworks are applied in practice. A third goal is to ensure the legal
finality of payments, as is the case for today’s payment systems.
Efficient guidance of market standards to ensure contestability may also require
an adequate definition of what it means to truly “decentralise” decision-making, risk-
taking and system governance (see Buterin (2017) and FSB (2019) for a discussion
26 In particular, following the Great Financial Crisis, politicians, legislators and supervisors have focused
on increasing the resilience of the financial system and, in particular, of the large banks that account
for the bulk of total positions and thus aggregate risk, an effort that is still ongoing (see e.g. Carstens,
2018).
27 See Broeders and Prenio (2018) for a general assessment of suptech in bringing down the cost of
compliance.
BIS Working Papers No 905
20

and Walch (2019) for a critical review).28 Regulators and supervisors can steer some
design elements of new decentralised markets, as they will set the market standards
under which regulatory compliance can be automated (see also Zetzsche et al.,
2020a).
A further operational goal is to reduce the marginal cost of doing business by
facilitating access to trustworthy official information. One measure that could be
easily implemented would be for public authorities to directly offer digitally signed
and time-stamped information that could be fed into relevant market ledgers – or to
set standards so that private intermediaries could do so. In many cases, financial
contracts may reference data originating from the official sector, such as the central
bank’s policy rate or data releases from the national statistical office. Moreover, in
many jurisdictions, firm and land registries are operated by the government. Low-cost
tokenisation of the underlying firms and real estate would be facilitated if these
registries were to make their information accessible in a digitally signed, time-
stamped and publicly available form.
A last operational aspect concerns the handling of disputes. Regulatory
frameworks or standards could guide arbitration processes if any information
referenced in smart contracts turns out to be fraudulent. This could happen where
the smart contract has a security flaw (as is frequently the case; see Luu et al (2016)
and Fröwis and Böhme, 2017) or in other unforeseen events, such as if a smart
contract depends on an interest rate benchmark that ceases to exist. Ultimately,
though, the world is sometimes too complex to be put into code. Moreover, cases
concerning individuals may generate personal information that needs to be handled
with confidentiality, and such that users have recourse if data are used improperly.
Thus, the more intractable cases may always need to be handled via an old-fashioned
legal process (see Zetzsche et al., 2020a). In this light, the added value of decentralised
automation should be seen as simplifying the standard execution of a contract.
One possible function of stablecoins – a desired function from the standpoint of
users – is to provide a digital means of payment which can be embedded in both DLT
and traditional centralised environments in order to reduce payment and settlement
risks and transaction costs, in particular enhancing user trust in systems and
payments. One could think of this as “embedding” payments within transactions and
their settlement. From this standpoint, stablecoins offer a potentially desirable
innovation but also one which could create a range of new risks and concerns.
However, this discussion highlights that a better solution could in fact be using
technology to embed fiat currencies in the same way, for instance in the context of
central bank digital currencies (CBDCs). Central banks around the world are
researching and developing CBDCs (Boar et al., 2020; Auer et al., 2020b). Both
wholesale and retail CBDCs provide a combination of private sector expertise and
central bank value backing and infrastructure. By design, CBDCs would have a fixed
value against other representations of the central bank’s currency. Indeed, in most
designs, a CBDC would be a direct claim on the central bank in question (Auer et al.,
28 Even with the most decentralised systems, many aspects of centralisation remain, for example when
it comes to the evolution of the code (core developers etc.). Further to this, as shown by the
concentration of the mining power of all of the world’s major cryptocurrencies in the hands of only
a few companies or mining pools, even systems that are intended to be decentralised have a
tendency to centralise, owing to unforeseen returns to scale. Regulators and supervisors could
counter this, for example, by setting standards that guide or encourage entry into the verification
market or by mandating open data requirements.
BIS Working Papers No 905 21

2020b). While private sector intermediaries still may offer client-facing services, the
inherent conflicts of interest, by which intermediaries seek to achieve higher returns
with the funds entrusted to them, would be eliminated. Even “synthetic” CBDC
arrangements in which a stablecoin is not a claim on the central bank, but in which
the issuer has direct access to central bank liquidity, similar to many RTGS systems,
could offer some of these benefits.
Some of the benefits also could be achieved through less far-reaching reforms
to existing payment systems. For instance, retail fast payment systems (FPS) may allow
for the 24/7 availability and speed that consumers and businesses are demanding. It
may also be possible to programme payments in such a way as to support atomic
settlement (immediate “delivery-vs-payment”), to allow for very small values (micro-
payments) or to be interoperable with DLT systems. Together with advances in digital
ID, such systems could also work to enhance financial inclusion and universal access
(Arner et al., 2018). Indeed, the recent experience with the India Stack (D’Silva et al.,
2019) shows that great strides can be achieved through public payment and other
infrastructures that do not rely on DLT, stablecoins or CBDCs. Unlike CBDCs, FPS build
on existing accounts at intermediaries. Such accounts are not backed by the
sovereign, but they also do not lead to concerns around “digital runs” or
disintermediation. It is possible for such advances to be complementary to efforts to
issue a CBDC as a robust public digital means of payment.
From the standpoint of payment finality, this typically is defined to occur when a
transfer takes place in the books of the central bank. Finality can also take place if the
relevant legal framework provides for it to take place in the context of a regulated
payment system. As such, while a stablecoin or FPS may not offer finality in the same
way as a CBDC (as CBDC payments would settle across the books of the central bank,
both in token-based or account-based systems), the legal and regulatory framework
for the licensing and supervision of payments systems must provide for requirements
for systems to provide for such finality. This would provide a clear opportunity for
mandating embedded supervision into such systems.29
Overall, it is not clear that stablecoins are necessarily needed to provide some of
the benefits that they purport to serve. While a digital representation of value could
hold great potential in many applications, CBDCs may offer these benefits without
the inherent fluctuation in value or conflicts of interest entailed by stablecoins.
Improvements to existing payment infrastructures, or new infrastructures that do not
rely on DLT, may also be able to fulfil many of the use cases for stablecoins. FPS may
serve some of the same goals, or serve as a useful complement. Thus, in the same
way that stablecoins from previous centuries (Frost et al., 2020) were an evolutionary
step on the road to central banking, today’s stablecoins could too eventually give way
to other reforms. This may include robust sovereign-backed alternatives and new
means to connect central bank money across borders (Auer et al. (2020d)).
29 International spillovers have to be take into account in the context of CBDC design. Ferrari et al (2020)
show that CBDC issuance amplifies international spillovers of macroeconomic shocks. However, the
magnitude of these effects depends on CBDC design features; for example they can be mitigated by
limits on transactions by non-residents.
BIS Working Papers No 905
22

6. Conclusion
Finance and technology continue to evolve together. Today, technology is not only
transforming finance, but money as well, with the advent of a range of challengers to
traditional sovereign currencies, from Bitcoin to Libra. Of these, the evolution of new
technology-based “stablecoins” offers important potential to embed a digital
monetary instrument in distributed systems and transaction frameworks. Yet as with
all technologies for payments and all structures involving asset backing, there is a
need for adequate regulation. Moreover, while most stablecoins offer limited financial
and monetary stability risk, the advent of global stablecoins raises much larger issues
and concerns. Going forward, it is essential for authorities have the tools, skills and
technology to identify the evolution or creation of stablecoins, in particular global
stablecoins, and to build appropriate regulatory and supervisory frameworks.
Technology also offers the potential not only to enhance supervision but in fact
to provide new tools for implementing regulation. Stablecoins and other forms of
decentralised finance not only provide regulatory and supervisory challenges but also
opportunities for embedding supervisory and monitoring frameworks directly into
systems during the process of their creation and authorisation. This has the potential
to enhance achievement of regulatory and supervisory objectives through the
technology which initially was targeted with making the role of regulation
unnecessary. Still, there are open questions as to whether central bank infrastructures,
like CBDCs or retail fast payment systems, with a role for private sector services built
on top, could provide many of these same opportunities more effectively.
BIS Working Papers No 905 23

References
ADACHI, M., M. COMINETTA, C. KAUFMANN and A. VAN DER KRAAIJ (2020). “A
regulatory and financial stability perspective on global stablecoins”, Macroprudential
Bulletin, Issue 10, ECB, Frankfurt am Main, March.
ADRIAN, T. and T. MANCINI-GRIFFOLI (2019). “The rise of digital money”, IMF Note
no. 19/001, July.
ARNER, D., J. BARBERIS and R. BUCKLEY (2017). “FinTech, RegTech and the
Reconceptualization of Financial Regulation”, 37 Northwestern Journal of International
Law and Business 371.
ARNER, D., R. BUCKLEY and D. ZETZSCHE (2018). “FinTech for Financial Inclusion: A
Framework for Digital Financial Transformation”, Special Report, Alliance for Financial
Inclusion / Group of 24
ARNER, D., R. BUCKLEY, D. ZETZSCHE and A. DIDENKO (2020). “After Libra, the Digital
Yuan and COVID-19: Central Bank Digital Currencies and the New World of Money
and Payment Systems”, European Banking Institute Working Paper, 65/2020, July.
AUER, R. (2019a). “Beyond the doomsday economics of ‘proof-of-work’ in
cryptocurrencies”, BIS Working Papers, no. 765, January.
--- (2019b). “Embedded supervision: how to build regulation into blockchain finance”,
BIS working paper no. 811.
AUER, R. and R. BÖHME (2020). “The technology of retail central bank digital
currency”, BIS Quarterly Review, March, pp. 85–100.
AUER, R. and S. CLAESSENS (2018). “Regulating cryptocurrencies: assessing market
reactions”, BIS Quarterly Review, September.
AUER, R., G. CORNELLI and J. FROST (2020a). “Covid-19, cash and the future of
payments”, BIS Bulletin, no. 3, April.
AUER, R., G. CORNELLI and J. FROST (2020b). “Rise of the central bank digital
currencies: drivers, approaches and technologies”, BIS Working Papers, no. 880,
August.
AUER, R., J. FROST, T. LAMMER, T. RICE and A. WADSWORTH (2020c). “Inclusive
payments for the post-pandemic world”, SUERF Policy Note, August.
AUER, R, P HAEHNE and H HOLDEN (2020d): “Multi-CBDC arrangements and the
future of cross-border payments”, BIS papers, forthcoming.
BANK FOR INTERNATIONAL SETTLEMENTS (2018). “Cryptocurrencies: looking
beyond the hype”, Annual Economic Report, ch. 5, June.
--- (2019). “Big tech in finance: opportunities and risks”, Annual Economic Report, ch.
3, June.
--- (2020). “Central banks and payments in the digital era”, Annual Economic Report,
ch. 3, June.
BANK OF CANADA (2020). “Contingency planning for a central bank digital currency”,
February.
BIS Working Papers No 905
24

BASEL COMMITTEE ON BANKING SUPERVISION (2013). “Global systemically
important banks: updated assessment methodology and the higher loss absorbency
requirement”, 3 July.
BÁTIZ VÁZQUEZ, J. (2009). “Paper money in the Mexican revolution”, in F Rubli (ed.),
Money in the Mexican War of Independence and Revolution, Mexico City: Bank of
Mexico.
BAZOT, G. (2018). “Financial intermediation cost, rents, and productivity: An
international comparison”, Working Papers 0141, European Historical Economics
Society (EHES).
BECH, M. and R. GARRATT (2017). “Central bank cryptocurrencies”, BIS Quarterly
Review, September, pp. 55–70.
BECH, M., J. HANCOCK, T. RICE and A. WADSWORTH (2020). “On the future of
securities settlement”, BIS Quarterly Review, March, pp. 67–83.
BOAR, C., H. HOLDEN and A. WADSWORTH (2020). “Impending arrival – a sequel to
the survey on central bank digital currency”, BIS Papers, no. 107, January.
BROEDERS, D. and J. PRENIO (2018). “Innovative technology in financial supervision
(suptech) - the experience of early users”, FSI Insight, no. 9, July.
BUDISH, E. (2018). “The Economic Limits of Bitcoin and the Blockchain”, University of
Chicago Booth School of Business working paper.
BULLMANN, D., J. KLEMM and A. PINNA (2019). “In search for stability in crypto-
assets: are stablecoins the solution?”, Occasional Paper Series, no. 230, ECB, August.
BUTERIN, V. (2017). “The meaning of decentralization”, Medium.com, 6 February.
CARSTENS, A. (2018). “Sustaining the momentum”, speech, 24 June.
--- (2019). “The future of money and the payment system: what role for central
banks?”, speech, 5 December.
COELHO, R., M. DE SIMONI and J. PRENIO (2019): “Suptech applications for anti-
money laundering”, FSI Insights, no. 18.
COMMITTEE ON PAYMENTS AND MARKET INFRASTRUCTURES and INTERNATIONAL
ORGANIZATION OF SECURITIES COMMISSIONS (2012). “Principles for Financial
Market Infrastructures”, April.
COMMITTEE ON PAYMENTS AND MARKET INFRASTRUCTURES (2017). “Distributed
ledger technology in payment, clearing and settlement - an analytical framework”,
February.
DAHL, D., A. MEYER and M. NEELY (2016). “Scale matters: community banks and
compliance costs”, Federal Reserve Bank of St Louis, The Regional Economist, July.
DILLEN, J. VAN (1934). “The Bank of Amsterdam”, in J G van Dillen (ed.) History of the
Principal Public Banks, The Hague: Martinus Nijhoff: pp. 79–124.
D’SILVA, D., Z. FILKOVÁ, F. PACKER and S. TIWARI (2019). “The design of digital
financial infrastructure: lessons from India”, BIS Papers, no. 106.
EUROPEAN CENTRAL BANK (2020). “Stablecoins – no coins, but are they stable?”,
INFOCUS, no. 3.
BIS Working Papers No 905 25

EUROPEAN COMMISSION (2020). “Proposal for a regulation of the European
Parliament and of the Council on Markets in Crypto-assets, and amending Directive
(EU) 2019/1937”, September.
FATÁS, A. and B. WEDER DI MAURO (2019). “The benefits of a global digital currency”,
VoxEU.org, 30 August.
FELTWELL, T., C. ELSDEN, S. LAWSON and J. VINES (2019): “Recipes for Programmable
Money”, Proceedings of the 2019 CHI Conference on Human Factors in Computing
Systems.
FERRARI, M, A MEHL, and L STRACCA (2020), “Central bank digital currency in an open
economy”, CEPR Discussion Paper 15335.
FINANCIAL STABILITY BOARD (2017). “Financial stability implications from fintech:
supervisory and regulatory issues that merit authorities’ attention”, June.
--- (2019). “Decentralised financial technologies: Report on financial stability,
regulatory and governance implications“, June.
--- (2020). “Addressing the regulatory, supervisory and oversight challenges raised by
“global stablecoin” arrangements”, 14 April.
FISHER, I. (1933), “The Debt Deflation Theory of Great Depressions”, Econometrica,
Vol. 1, pp. 337–57.
FROST, J., H.S. SHIN and P. WIERTS (2020). “An early stablecoin? The Bank of
Amsterdam and the governance of money”, BIS Working Papers, no. 902.
FRÖWIS, M. and R. BÖHME (2017): “In code we trust? Measuring the control flow
immutability of all smart contracts deployed on Ethereum”, in J. García-Alfaro, G.
Navarro-Arribas, H. Hartenstein and J. Herrera-Joancomartı ́ (eds), Data privacy
management, cryptocurrencies and blockchain technology, Springer, pp. 357–72.
GARTNER (2020). “Gartner Glossary”, available online at:
https://www.gartner.com/en/glossary, accessed 15 August.
GRIFFIN, J. and A. SHAMS (2020). “Is Bitcoin Really Untethered?”, The Journal of
Finance, vol. 75, no. 4, pp. 1913–64.
G7 WORKING GROUP ON STABLECOINS (2019). “Investigating the impact of global
stablecoins”, October.
INTERNATIONAL ORGANIZATION OF SECURITIES COMMISSIONS (2020). “Global
Stablecoin Initiatives”, March.
J.P. MORGAN (2019). “J.P. Morgan Creates Digital Coin for Payments”, February.
KAHN, C. (2016). “How are payment accounts special? Payments Innovation
Symposium, Federal Reserve Bank of Chicago.
KAHN, C., C. LONG and M. SINGH (2020). “Privacy Provision, Payment Latency, and
Role of Collateral”, IMF Working Paper WP/20/148.
KANE, E. (1977). “Good Intentions and Unintended Evil: The Case Against Selective
Credit Allocation”, Journal of Money, Credit and Banking, no. 9, pp. 55–69.
--- (1981). “Accelerating Inflation, Technological Innovation and the Decreasing
Effectiveness of Banking Regulation”, Journal of Finance, no. 36, pp. 355–67.
KINDLEBERGER, C.P. (1978), Manias, Panics and Crashes: A History of Financial Crises,
New York, Basic Books.
BIS Working Papers No 905
26

KNOT, K. (2019). “Risks and benefits of modern financial technology; Lessons from a
17th century stablecoin”, speech, 2 December.
LIBRA ASSOCIATION (2019). “An Introduction to Libra”, 18 June.
--- (2020). “White Paper: v2.0”, the Libra Association Members, 16 April.
LYONS, R. and G. VISWANATH-NATRAJ (2020). “What Keeps Stablecoins Stable?”
National Bureau of Economic Research Working Paper, no. w27136.
LUU, L., D. CHU, H. OLICKEL, P. SAXENA and A. HOBOR, (2016). “Making smart
contracts smarter”, in Proceedings of the 2016 ACM SIGSAC Conference on Computer
and Communications Security, pp. 254–69.
MCLAUGHLIN, T. (2020). “Two Paths to Tomorrow’s Money”, Citi Digital Policy,
Strategy and Advisory paper.
MINSKY, H. (1975). John Maynard Keynes, New York, Columbia University Press.
--- (1982). "The Financial-Instability Hypothesis: Capitalist Processes and the Behavior
of the Economy", Hyman P. Minsky Archive Paper, no. 282.
MILKAU, U. (2018). “The advent of machine payments: The right way to pay?” Journal
of Payments Strategy & Systems, vol. 12, no. 4.
NEW YORK ATTORNEY GENERAL (2019). “Attorney General James Announces Court
Order Against “Crypto” Currency Company Under Investigation For Fraud”, Press
release, 24 April.
PETRALIA, K., T. PHILIPPON, T. RICE and N. VÉRON (2019). “Banking Disrupted?
Financial Intermediation in an Era of Transformational Technology”, Geneva Report,
no. 22, September.
PHILIPPON, T. (2015). “Has the US Finance Industry Become Less Efficient? On the
Theory and Measurement of Financial Intermediation”, American Economic Review,
vol. 105, no. 4, pp. 1408–38.
TETHER (2016). “Tether: Fiat currencies on the Bitcoin blockchain”, tether.to.
VIGNA, P. and S. RUSSOLILLO (2018). “The Mystery Behind Tether, the Crypto World’s
Digital Dollar”, The Wall Street Journal, 12 August.
WADSWORTH, A. (2018). “Decrypting the role of distributed ledger technology in
payments processes”, Reserve Bank of New Zealand Bulletin, vol. 81, no. 5, May.
WALCH, A. (2019). “Deconstructing ‘decentralization’: exploring the core claim of
crypto systems”, in C. Brummer (ed), Cryptoassets: legal and monetary perspectives,
Oxford University Press.
WALL STREET JOURNAL (2009). “Paul Volcker: Think More Boldly”, 13 December.
WOOLARD, C. (2019). “Regulating financial innovation – going behind the scenes”,
speech, 2 July.
ZETZSCHE, D., R. BUCKLEY and D. ARNER (2018). “The Distributed Liability of
Distributed Ledgers: Legal Risks of Blockchain”, 2018:4 University of Illinois Law
Review, no. 101.
ZETZSCHE, D., D. ARNER and R. BUCKLEY (2020a). “Decentralised Finance”, Journal of
Financial Regulation.
BIS Working Papers No 905 27

ZETZSCHE, D., R. BUCKLEY and D. ARNER (2020b). “Regulating Libra: The
Transformative Potential of Facebook’s Cryptocurrency and Possible Regulatory
Responses”, Oxford Journal of Legal Studies.
ZETZSCHE, D., W. BIRDTHISTLE, D. ARNER and R. BUCKLEY (2021). “Digital Finance
Platforms: Toward a New Regulatory Paradigm”, University of Pennsylvania Journal of
Business Law, forthcoming.
BIS Working Papers No 905
28

Previous volumes in this series
| 904            | Housing booms, reallocation and   | Sebastian Doerr  |
| -------------- | --------------------------------- | ---------------- |
| November 2020  | productivity                      |                  |
903  Bargaining power and the Phillips curve:   Marco J Lombardi, Marianna Riggi
| November 2020  | a micro-macro analysis  | and Eliana Viviano  |
| -------------- | ----------------------- | ------------------- |
902  An early stablecoin? The Bank of Amsterdam  Jon Frost, Hyun Song Shin and
| November 2020  | and the governance of money  | Peter Wierts  |
| -------------- | ---------------------------- | ------------- |
901  Inside the regulatory sandbox: effects on  Giulio Cornelli, Sebastian Doerr,
November 2020  fintech funding  Leonardo Gambacorta and Ouarda
Merrouche
900  What can commercial property performance  Emanuel Kohlscheen and Előd
| November 2020  | reveal about bank valuations?  | Takáts  |
| -------------- | ------------------------------ | ------- |
899  The macro-financial effects of international  Iñaki Aldasoro, Paula Beltrán,
November 2020  bank lending on emerging markets  Federico Grinberg and Tommaso
Mancini-Griffoli
| 898  | What comes next?  | Daniel M Rees  |
| ---- | ----------------- | -------------- |
November 2020
897  Non-US global banks and dollar   Torsten Ehlers, Mathias Hoffmann
October 2020  (co-)dependence: how housing markets  and Alexander Raabe
became internationally synchronized
896  Have the driving forces of inflation changed  Güneş Kamber, Madhusudan
October 2020  in advanced and emerging market  Mohanty and James Morley
economies?
| 895           | Pass-through from short-horizon to long- | James Yetman  |
| ------------- | ---------------------------------------- | ------------- |
| October 2020  | horizon inflation expectations, and the  |               |
anchoring of inflation expectations
894  Effects of eligibility for central bank purchases T Mäkinen, F Li, A Mercatanti and
| October 2020  | on corporate bond spreads  | A Silvestrini  |
| ------------- | -------------------------- | -------------- |
893  Assessing the fiscal implications of banking  Claudio Borio, Juan Contreras and
| October 2020  | crises  | Fabrizio Zampolli  |
| ------------- | ------- | ------------------ |
892  Banking across borders: Are Chinese banks  Eugenio Cerutti, Catherine Koch
| October 2020  | different?  | and Swapan-Kumar Pradhan  |
| ------------- | ----------- | ------------------------- |
All volumes are available on our website www.bis.org.