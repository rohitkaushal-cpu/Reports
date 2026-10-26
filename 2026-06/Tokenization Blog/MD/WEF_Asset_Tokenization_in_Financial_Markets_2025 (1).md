# WEF_Asset_Tokenization_in_Financial_Markets_2025 (1)

**Source:** WEF_Asset_Tokenization_in_Financial_Markets_2025 (1).pdf | **Pages:** 63

---

<!-- Page 1 -->

Contents
1
M A Y  2 0 2 5
I N S I G H T  R E P O R T
In collaboration with Accenture
Asset Tokenization 
in Financial Markets: The Next 
Generation of Value Exchange

<!-- Page 2 -->

Contents
2
Contents
Foreword 
3
Executive summary 
4
Introduction 
5
1. Foundational key concepts 
6
    1.1 Tokenization 
7
    1.2 Programmable ledgers  
8
    1.3 Tokenization models 
8
    1.4 Token attributes 
11
    1.5 Settlement assets 
12
2. Value proposition 
13
3. Tokenized assets 
18
    3.1 Use case patterns 
19
    3.2 Asset issuance 
22
    3.3 Securities ﬁnancing 
33
    3.4 Asset management 
34
4. Barriers to adoption 
37
    4.1 Traditional ﬁnancial infrastructure 
38
    4.2 Global standards 
38
    4.3 Cross-chain interoperability 
39
    4.4 Secondary markets 
39
    4.5 Privacy and compliance 
40
5. Impacts of tokenization 
41
    5.1 Evolving market structures 
42
    5.2 Changes to incumbents 
42
    5.3 New market roles 
46
    5.4 New products 
46
6. Design choices 
47
    6.1 Infrastructure 
48
    6.2 Settlement assets 
50
    6.3 Operating hours 
50
7. Considerations 
51
    7.1 Cybersecurity 
52
    7.2 Financial stability 
53
    7.3 Regulatory developments 
53
Conclusion 
55
Contributors 
56
Endnotes 
58
Contents
Disclaimer
This document is published by the World 
Economic Forum as a contribution to a 
project, insight area or interaction. The 
ﬁndings, interpretations and conclusions 
expressed herein are a result of a collaborative 
process facilitated and endorsed by the World 
Economic Forum but whose results do not 
necessarily represent the views of the World 
Economic Forum, nor the entirety of its 
Members, Partners or other stakeholders. 
© 2025 World Economic Forum. All rights 
reserved. No part of this publication may be 
reproduced or transmitted in any form or by 
any means, including photocopying and 
recording, or by any information storage and 
retrieval system.  
Look out for this icon 
for pages that can be 
interacted with
T H I S  R E P O R T  I S  I N T E R A C T I V E
To ensure interactive 
capability, please download 
and open this PDF with 
Adobe Acrobat.

<!-- Page 3 -->

Contents
3
Foreword
Foreword
Duane Block
Managing Director, 
Accenture
Drew Propson
Head, Technology 
and Innovation 
in Financial Services, 
World Economic Forum
Financial markets are evolving to meet 
growing demands for speed, efﬁciency and 
connectivity. Among the forces driving this 
transformation is the rise of distributed 
ledger technology (DLT) and tokenization – 
innovations that have the ability to offer faster 
transactions, improved efﬁciency and greater 
transparency across asset classes. With 
strong momentum towards regulatory 
clarity and increasing technological maturity, 
the tokenization of ﬁnancial assets is well 
positioned to support the next generation
of value exchange in banking and 
capital markets.
Global stakeholders are now commonly 
distinguishing between attention-grabbing 
cryptocurrencies and the underlying 
technology, fuelling a renewed era of public–
private cooperation focused on scaling 
tokenization in a safe and compliant manner. 
Yet progress in ﬁnancial infrastructure is 
inherently gradual. History reﬂects this in the 
multi-decade transition from paper-based 
certiﬁcates to electronic book entries following 
the 1960s Paperwork Crisis. While the 
changes will not be immediate, ﬁnancial 
markets may be approaching another major 
phase in the development of their architecture, 
powered this time by tokenization.
Today’s global ﬁnancial system relies on 
fragmented, message-based integrations to 
reconcile ownership and transfers across 
independent networks. In contrast, 
tokenization – enabled by programmable 
ledgers and smart contracts – offers the 
potential for uniﬁed systems of record, ﬂexible 
custody models and on-chain governance. 
These capabilities unlock new possibilities 
for real-time settlement, fractional ownership, 
asset composability and more resilient 
market design. 
In this context, the World Economic Forum 
has collaborated with Accenture to examine 
the role of asset tokenization in ﬁnancial 
markets. The report that follows is the result 
of this joint effort. Over the past year, we 
analysed asset classes ranging from equities 
to alternative investments to develop a 
taxonomy of tokenization models and the 
differentiation they provide. While tokenization 
is expected to scale, realizing its full impact will 
require sustained public–private coordination 
and a phased, risk-aware approach. We hope 
that the insights shared in this report serve 
as a valuable foundation for informed decision-
making and encourage continued 
collaboration across the ﬁnancial ecosystem. 
Finally, we extend our sincere gratitude to the 
many experts who contributed to this analysis. 
Their insights and perspectives, offered 
through interviews, workshops and written 
reviews, have been instrumental in shaping the 
ﬁndings of this report.

<!-- Page 4 -->

Contents
4
Shared system 
of record
Uniﬁed records that 
drive information 
symmetry and provide 
an unambiguous view 
of asset ownership
Executive summary
Flexible custodial 
arrangements
Increased user-
centricity through 
varied custody models, 
granting end users 
greater control over 
their assets
Asset fractionalization
Expanded market 
accessibility through 
micro-units of 
ownership, signiﬁcantly 
reducing administrative 
burdens and 
barriers to entry
Composability
Enhanced multi-asset 
mobility, enabling 
efﬁcient reuse of 
collateral across 
trading and settlement 
activities
Programmability
Operational efﬁciency 
via smart contracts that 
automate complex 
ﬁnancial transactions, 
embedding logic 
directly into processes
The report examines existing use cases to clearly articulate tokenization’s unique value proposition and outlines five distinct 
differentiators powered by programmable ledgers (DLT/blockchain):
This report assesses current asset tokenization 
use cases in issuance, securities ﬁnancing and 
asset management, highlighting conditions 
and regional factors that determine successful 
implementation. Both incumbent and new 
market structures, along with digitally native 
service providers, are actively reshaping their 
services to meet the growing expectations 
for speed, efﬁciency and user-centricity in 
a rapidly evolving landscape.
While the potential of tokenization is clear, 
barriers to adoption remain, including legacy 
infrastructure integration, inconsistent global 
standards, limited cross-chain interoperability, 
inadequate secondary market liquidity, and 
privacy and compliance concerns. Addressing 
these challenges through careful coordination 
and pragmatic strategies is critical for 
tokenization to achieve scale and lasting 
impact in ﬁnancial markets.
As tokenization develops, there are design 
choices that need to be considered such as 
the choice between permissioned and 
permissionless ledgers, the most suitable 
settlement asset and the operating hours of 
future marketplaces. Likewise, there are 
considerations for deploying tokenized 
products, including cybersecurity, ﬁnancial 
stability and regulatory developments. 
Despite its beneﬁts, tokenization adoption 
remains non-linear, constrained by 
infrastructure readiness, commercial viability, 
regulatory fragmentation and insufﬁcient, yet 
emerging, market coordination. Transitioning 
ﬁnancial markets from ﬁxed-trade windows 
and regional frameworks to continuous, 
global operations requires a practical, 
phased approach.
Tokenization has the potential to unlock the 
next generation of value exchange in ﬁnancial 
markets. While barriers remain, momentum 
continues to build, and ﬁnancial institutions, 
policy-makers and technology providers 
need to coordinate regulation, interoperability 
and consumer protections to safely usher 
in this evolution. 
Executive 
summary
This report employed a global 
multistakeholder approach 
to exploring the potential 
impacts of asset tokenization 
on financial markets.
Tokenization presents a transformative 
digital asset ownership model, fundamentally 
reshaping global ﬁnancial markets. When 
effectively implemented, tokenization can 
signiﬁcantly enhance transparency, 
accessibility, operational and cost efﬁciency 
and market ﬂexibility, allowing participants 
to transact at any time and anywhere. The 
core advantage of tokenization lies in 
democratizing ﬁnancial market access, 
enabled by trusted infrastructure.

<!-- Page 5 -->

Contents
5
that analysed more than 75 
industry reports to establish initial 
assumptions
DESK RESEARCH
Research methods:
with more than 60 experts 
representing public- and private-
sector stakeholders
INTERVIEWS
of 10 leaders from leading ﬁnancial 
institutions and technology 
companies to advise on strategic 
direction 
STEERING COMMITTEE
Community:
of more than 200 expert 
members representing more than 
100 institutions
COMMUNITY
conducted worldwide, in London, 
Singapore and San Francisco 
COMMUNITY WORKSHOPS
Introduction
This report examines the 
evolution of asset tokenization 
in financial markets by 
analysing its distinguishing 
features and value proposition.
Scope: In the context of recent advancements 
in tokenization in ﬁnancial markets, the 
report evaluates tokenized asset classes 
and key use cases, examines the barriers 
to adoption, identiﬁes expected market 
impacts and outlines strategies for realizing 
scalable implementation.
The report builds on previous World Economic 
Forum reports, including Digital Assets, 
Distributed Ledger Technology and the Future 
of Capital Markets (2021), Evolution of Non-
Fungible Tokens (2023) and Modernizing 
Financial Markets with Wholesale Central Bank 
Digital Currency (2024).
These reports have covered the tokenization 
of payment assets and non-ﬁnancial assets. 
This report focuses on ﬁnancial assets. 
Select the tabs
to cycle between texts
Introduction
This report will
This report will not
q
—  Focus on regulated financial market 
activities and instruments
—  Define tokenization’s key differentiating 
features and value proposition
—  Identify emerging use cases and promising
applications of tokenization
—  Map the expected impacts on the financial 
markets value chain
—  Share strategies for overcoming identified 
barriers to adoption
—  Outline design choices and considerations 
for adopting tokenization

<!-- Page 6 -->

Contents
6
1
Foundational key concepts
Tokenization facilitates the exchange of information and value. Its 
defining aspects are proof of value, ownership and transaction.
Foundational key concepts

<!-- Page 7 -->

Contents
7
Pre-1980s
1980s–2010s
Post-2010s
FRAGMENTED AND
MANUAL-INTENSIVE
CENTRALIZED AND
 INTERMEDIARY-INTENSIVE
DISTRIBUTED AND 
USER-CENTRIC
PAPER CERTIFICATES
—  Securities were manually issued, 
transferred and settled through 
physical paper certiﬁcates, creating 
signiﬁcant operational bottlenecks, 
slow T+5+ settlements and fragmented 
record-keeping across registrars and 
custodians. 
—  The lack of effective, centralized 
coordination made reconciliation error-
prone and delayed capital movement.
DEMATERIALIZATION
—  Electronic book-entry systems digitized 
securities and centralized them within 
clearing houses and custodians, 
solving many operational inefﬁciencies 
from the paper era. 
—  However, they introduced new 
dependencies on intermediaries, and 
settlement cycles – although faster – 
still hovered at T+2.
—  Geographic barriers and limited 
interoperability constrained inclusivity, 
and real-time transparency was 
available only to selected institutions.
—  Tokenization introduces a shared 
system of record and programmable, 
real-time asset transfer, reducing 
settlement risk and optimizing 
intermediary chains.
—  With on-chain auditability and greater 
ownership control, tokenized assets 
address the coordination inefﬁciencies 
and the latency and exclusivity of prior 
iterations of ﬁnancial systems.
—  This shift enables multi-asset 
operations underpinned by ﬁnancial 
infrastructure that is more 
composable and accessible.
TOKENIZATION
Foundational key concepts
F I G U R E  1
The evolution of financial assets
1.1 Tokenization
Tokenization is the process of using a 
programmable ledger to digitally represent the 
ownership of an asset – ﬁnancial or otherwise 
– in a transferable format. By creating provably 
unique digital tokens that can be issued, 
stored and traded on these ledgers, 
tokenization enables the exchange of 
information and value. 
A “token”, in this context, represents 
something of value (e.g. a claim on or digitized 
version of a real or ﬁnancial asset) that can be 
legally and operationally exchanged on a 
programmable ledger.1

<!-- Page 8 -->

Contents
8
1.3 Tokenization 
models
According to the World Economic Forum, 
tokenization is differentiated from conventional 
systems in the following ways:3
This report adopts these three viewpoints to 
identify two tokenization models – backed and 
native – and analyses their impacts across 
issuance, value, ownership, transaction or 
settlement, custody and redemption.4 
Fundamentally, tokenization acts as a 
capability to enhance settlement operations, 
underpinned by the asset life cycle functions. 
PROOF OF VALUE
Provides evidence or veriﬁcation 
that an asset has a certain value 
or uniqueness
PROOF OF OWNERSHIP
Establishes unambiguous 
ownership and assigns agency 
of the asset to the rightful owner
PROOF OF TRANSACTION
Produces a veriﬁable record to 
provide transaction history and 
evidence of settlement
Foundational key concepts
1.2 Programmable 
ledgers
Programmable ledgers or DLT and blockchain 
systems support smart contract-based 
processes. Programmable ledgers may be 
public or private and permissioned or 
permissionless, each with varying trade-offs 
and advantages. These systems allow 
ﬁnancial assets to be tokenized by codifying 
essential data and properties of the asset on 
the ledger or on-chain.2
—  “On-chain” refers to an asset or activity 
being operated on a programmable ledger; 
this term is borrowed from the popularized 
“blockchain” term, which is a speciﬁc type 
of programmable ledger. 
—  “Off-chain” refers to ﬁnancial processes or 
asset life-cycle functions taking place on 
non-tokenized, or conventional, systems.

<!-- Page 9 -->

Contents
9
Select the tabs
to cycle between texts
Foundational key concepts
F I G U R E  2
Tokenization models
Off-chain
On-chain
MODEL
Purpose
Component(s)
Issuance
Asset is issued off-chain
Asset is issued off-chain
Token is issued on-chain
Driven by issuer credibility
Driven by issuer credibility
Evidenced by on-chain records
Recorded on-chain
Evidenced by off-chain records
Recorded off-chain
Qualiﬁed custodian
Qualiﬁed custodian
Flexible custodial arrangements
No token
Token may be redeemable for the reference asset or its par value
Physical gold (commodity)
Public equities
Token is issued on-chain
Driven by issuer credibility
Evidenced by on-chain records
Recorded on-chain
Flexible custodial arrangements
No reference asset
Sovereign digital bonds
Proof of value
Proof of 
ownership
Proof of 
transaction
Custody
Redemption
Example
To allow investors to trade, 
hold and settle off-chain
Conventional asset
Reference asset
Token
Token
To allow investors to trade, hold and settle on-chain, 
with the ability to redeem the underlying reference asset
To allow investors to trade, 
hold and settle on-chain
CONVENTIONAL
BACKED TOKEN
NATIVE TOKEN
Native token
Backed token
Native tokens represent assets issued on-
chain without reference to off-chain 
counterparts, except for compliance functions 
or identity management, embedding issuance,
trading, custody, settlement and ownership 
within the token. From a lending and collateral 
standpoint, this model resembles a “perfect 
asset” as theoretically no off-chain processes 
are needed and ownership claims are 
systematically verifiable. If implemented well, 
native tokens minimize operational burdens 
and eliminate liquidity risks; however, 
technology and governance risks increase as 
the asset can then have bearer-like 
characteristics. While this model is currently 
still in development in regulated markets, 
trends indicate that it serves as the target-
state tokenization model for non-physical or 
electronic assets.

<!-- Page 10 -->

Contents
10
Foundational key concepts
Legal, operational and market 
dynamics
These two tokenization models provide 
the foundation for issuance and settlement 
driven by programmable ledgers, yet these 
models are inﬂuenced by legal and 
operational dynamics.
From a legal perspective, the proof of 
ownership, or a claim, over an asset may 
technically be evidenced by the programmable 
ledger. However, two challenges persist: 
Operationally, proof of value and redemption, 
if applicable, carry some ambiguity. Reliance 
on a reference asset necessitates off-chain 
third-party audits and coordination of dual- 
or tri-liquidity pool management to ensure 
sufﬁcient backing and proof of value to cover 
the outstanding tokens and other buffers, 
such as liquidity coverage ratios. Redemption 
depends on issuer and custodian operations. 
Another operational aspect is bankruptcy-
remoteness, which aims to protect customer 
assets if the issuer or custodian becomes 
insolvent. Proper segregation of accounts and 
legal structures ensures underlying reference 
assets are separated from the issuer’s balance 
sheet, safeguarding investors and reducing 
counterparty risks.
The state of ownership must be legally 
enforceable, such as through a 
rulebook. Currently, property and 
ownership rights assigned to assets 
outside programmable ledgers remain 
legally uncertain.
Clear rules must be established 
regarding the reconciliation and 
synchronization of counterparties’ 
books and records against the 
programmable ledger to mitigate 
discrepancies. 
1
2

<!-- Page 11 -->

Contents
11
P
E
R
M
IS
SI
O
N
C
O
N
T
R
O
LS
P
R
O
V
E
N
A
N
C
E
A
S
S
E
T
D
E
FI
NI
TI
O
N
E
M
B
E
D
D
E
D
RI
G
H
T
S
T O K E N
O
W
N
E
R
S
HI
P
S
T
A
T
U
S
C
O
M
P
LI
A
N
C
E
R
U
L
E
S
Clearly identiﬁes the underlying asset, 
specifying its category (e.g. bond, 
equity), issuer details, unique 
identiﬁers, available quantity and 
characteristics essential for valuation, 
accounting and trading.
ASSET DEFINITION
Details legal and economic 
entitlements granted to the token 
holder, such as dividend payouts, 
voting participation, redemption 
capabilities or interest payments.
EMBEDDED RIGHTS
Provides a transparent, tamper-proof 
and auditable record of the token’s 
origin, transaction history and previous 
ownership – all of which can be 
designated to authorized viewers or 
publicly viewable.
PROVENANCE (HISTORY)
Accurately represents current holders 
or custodians of the token, including 
explicit claims or encumbrances over 
the underlying asset.
OWNERSHIP STATUS
Encodes compliance requirements, 
regulatory conditions and jurisdiction-
speciﬁc rules directly into the token, 
enforcing rules governing 
transferability, trading eligibility and 
legal adherence.
COMPLIANCE RULES
Implements permissions within smart 
contracts that specify and control 
user actions, allowing designated 
users or restricting actions 
(e.g. transfers, freezing) based 
on predeﬁned rules.
PERMISSION CONTROLS
F I G U R E  3
Token attributes
Foundational key concepts
1.4 Token attributes
Six attributes – asset deﬁnition, embedded 
rights, provenance (history), ownership status, 
compliance rules and permission controls – 
make ﬁnancial asset tokens more transparent, 
secure and efﬁcient. By embedding key asset 
information into tokens, ﬁnancial markets 
could operate with reduced complexity, 
stronger investor protections and greater trust.

<!-- Page 12 -->

Contents
12
Source: World Economic Forum
1.5 Settlement assets
In a ﬁnancial transaction, the delivery of an 
asset (D) typically requires a reciprocated 
payment leg, whether in cash (the “P” in DvP) 
or asset (the second “D” in DvD) form. This leg 
is also referred to as a settlement asset, which 
is mutually recognized by transacting parties 
as a ﬁnal means to discharge obligations. 
Choosing the right settlement asset involves 
balancing liquidity and counterparty risks with 
the speed needed to achieve settlement for 
the trading scenario.
Settlement assets include ﬁat-backed 
stablecoins, reserve-backed digital 
currencies, deposit tokens and wholesale 
central bank digital currencies (wCBDC).5
Crypto-assets, such as Ether, are used as 
settlement assets in decentralized exchanges 
(DEXs) or Layer-2 networks.
Note: Reserve-backed money combines elements of 
both public and private money – while classiﬁed here 
as private due to operation by private entities, it is 
backed by public funds, namely central bank reserves.
—  General public
—  FIs
—  General public
—  General public
—  Ether
—  Fiat-backed 
stablecoin
—  Deposit token
—  Reserves-backed 
digital currency*
—  RTGS systems
—  Wholesale
—  CBDC
—  Bank customers 
(commercial and 
retail)
—  Financial institutions
—  Financial market 
infrastructures (FMIs)
—  Bank customers 
(commercial and 
retail)
PUBLIC MONEY
PRIVATE MONEY
Central bank money
Reserve-backed money
Commercial bank money
Non-bank money
Crypto-assets
Description
A central bank liability 
can be used for 
settlement purposes 
in both physical and 
digital formats.
A liability of a licensed 
non-bank FI or 
commercial bank backed 
by reserves in an 
omnibus account held 
at a central bank.
A commercial bank 
liability in the form of 
deposits held at the 
bank, which can be used 
for payment purposes.
A liability of a non-bank 
FI that holds a licence to 
issue e-money and can 
be used to settle 
commercial transactions.
A native digital asset that 
is usually the utility token 
of a programmable 
ledger and is used to pay 
for transaction fees.
Issuer/operator
Central banks
Commercial banks or 
non-bank FIs
Commercial banks
Non-bank FIs
Minted via blocks
Risk
Virtually credit risk-free
Bankruptcy-remote
Carries credit and 
liquidity risk
Carries credit and 
liquidity risk
Carries settlement risk
Users
Examples
F I G U R E  4
The digital money continuum
Foundational key concepts

<!-- Page 13 -->

Contents
13
2
Value proposition
Tokenization offers five differentiating features that 
are driving its value proposition in financial markets.
Value proposition

<!-- Page 14 -->

Contents
14
Note:  The table continues with additional features on the next page.
FEATURE
Enhances 
information 
symmetry
Enables user-
centricity
Shared system 
of record
Flexible 
custodial 
arrangements
— Off-chain synchronization – 
a new system of record can 
complicate harmonization with 
existing institutional books and 
records, possibly resulting in 
further reconciliations or errors.
— Reversals and clawbacks – 
some networks do not natively 
offer reversibility.
— Data privacy and conﬁdentiality
– the ability to comply with 
certain measures, such as the EU 
GDPR’s “right to be forgotten”.
— Information symmetry – 
ensures visibility and auditability, 
driving the reduction of 
information asymmetry and a 
reduction in reconciliations.
— Immutability and auditability –
creates an immutable, tamper-
resistant ledger that securely 
records and veriﬁes asset 
ownership, history and rights.C
— Establishes unambiguous 
cryptographic proof of the state 
of the transaction.A
— Allows for the automation of key 
functions, such as corporate 
actions and asset servicing.B
— Financial institutions use 
electronic messaging to 
coordinate transactions 
and update their own set of 
books and records based on 
structured data.A
— Multiple self-contained 
databases lead to inefﬁciencies 
and manual reconciliations that 
can lead to errors and delays.
— Virtually all ﬁnancial assets 
require intermediaries for 
safekeeping.
— Certain markets exhibit 
centralization risk with few 
parties dominating market share.
— Enables self-custody through 
private keys at the most 
fundamental level.
— Offers security options 
with multisignature and 
decentralized approaches.
— Direct user control – allows 
individuals to have direct control 
over their digital assets and data, 
driving privacy, portability and 
user autonomy.D
— Cyberattacks – the risk of third-
party providers being attacked 
with malicious code and 
bypassing security.
— Lost keys – the risk of users/
institutions misplacing or leaking 
private keys.
CONVENTIONAL
TOKENIZATION
BENEFITS
RISKS
There are ﬁve differentiated technical features of tokenization.
T A B L E  1
Differentiated features of tokenization 
Value proposition

<!-- Page 15 -->

Contents
15
Value proposition
FEATURE
Programmability
Facilitates 
operational 
efﬁciency
Asset 
fractionalization
Expands 
accessibility
Composability
Promotes 
multi-asset 
mobility
CONVENTIONAL
TOKENIZATION
BENEFITS
RISKS
— Process automation – 
transforms point-solution 
automation to broader strategic 
orchestrationF by embedding 
predeﬁned conditions into assets, 
automating transfers, compliance 
and event-based logic. 
— Reduced operational costs – 
efﬁciencies in administrative 
processes reduces costs 
associated with these 
transactions.
— Encodes transaction logic and 
rules directly into smart contracts 
(self-enforcing code) and the 
network’s operations.
— Performs business logic 
based on predeﬁned conditions, 
resulting in transfer of value 
and information across 
trading scenarios.
— Disparate systems require 
external messaging/APIs for 
coordination, limiting ability to 
integrate rules and conditions 
into assets or arrangements.
— Processes payments 
independently and relies on 
external messaging and APIs.E
— Administrative burdens often 
limit asset fractionalization 
because of additional effort 
required for functions such 
as asset servicing.
— Legacy systems do not always 
allow for ownership at the 
decimal level.
— Legacy infrastructure 
requires manual workarounds 
for composability to ensure 
sufﬁcient linkage.
— Siloed platforms limit asset 
reusability.
— Rehypothecation and 
collateral reuse are slow 
and operationally complex.
— Enables multi-asset operations 
for assets to be integrated, 
reused and transferred across 
platforms (e.g. DvD, DvP).
— Allows the combination of 
system components or discrete 
pieces of programmable code to 
meet any use case across 
transaction types, such as liquid 
staking and wrapped assets.
— Collateral mobility – accelerates 
collateral reuse, extending asset 
usability across multiple trades.
— Multi-asset coordination –
unlocks multi-asset 
and multiparty settlement 
opportunities on a 
common platform.
— Asset fungibility – enables 
greater fungibility across 
assets and markets, facilitating 
new economic linkages 
and businesses.I
— “Limitless composability” – 
repackaging assets can lead to 
an inﬁnite number of yield 
aggregation and ﬁnancial vehicle 
strategies, leading to possible 
stability risks.
— Interoperability risks – bridging, 
mint/burn, etc. not fully 
developed yet.
— Enables any asset to be 
divided into smaller units and 
made available under various 
custodial models.
— Supports the ownership of 
micro-units of value.
— Reduction of administrative 
burden – eases the 
administrative burden of making 
assets available in divisible, 
smaller parts, lowering minimum 
investment thresholds.
— Lower barriers to entry – lowers 
barrier to entry for retail 
investors, particularly in illiquid 
and secondary markets. 
— Fragmented ownership – the 
challenge with coordinating 
decisions or ensuring fair 
governance practices.
— Issuer restrictions – certain 
issuers may not offer smaller 
denominations of assets based 
on regulation.
— “Paradox of programmability” – 
trade-off of harnessing smart 
contract efﬁciency and 
constraining the ﬂexibility 
needed to react to or prevent 
on-chain issues.G
— Off-chain functions – 
requirements may require new 
off-chain processes, thus 
eroding the operational beneﬁts.H
Table sources: 
A. Citigroup. (2024). Ready Layer 1: A general-purpose 
state machine for the ﬁnancial sector. Citigroup Global 
Insights
B. European Central Bank. (2021). Use of DLT in post-
trade processes
C. Zellweger-Gutknecht, C. (2019): “Developing the 
right regulatory regime for cryptocurrencies and other 
value data”, in S. Green and D. Fox (eds), 
Cryptocurrencies in public and private law, Oxford: 
Oxford University Press, pp. 57–91 
D. Coinbase Institute. (2025). Why the future of ﬁnance 
calls for a permissionless architecture
E. MIT Media Lab & J.P. Morgan. (2024). Application of 
programmability to commercial banking and payments
F. Bank for International Settlements. (2024). 
Tokenisation in the context of money and other assets: 
Concepts and implications for central banks.
Committee on Payments and Market Infrastructures 
G. World Economic Forum. (2024). 'Code as law':
The tokenization of ﬁnancial assets and the paradox of 
programmability
H. FEDS Notes. (2024). Tokenized assets on public 
blockchains: How transparent is the blockchain?
I. State Street. (2024). Asset tokenization now and in 
the future

<!-- Page 16 -->

Contents
16
Shared system of record
The introduction of a shared system of record, 
underpinned by programmable ledgers and 
their consensus mechanisms, can drive 
efﬁciencies corresponding to the reduction 
of information asymmetry, an aspect crucial 
to investor awareness. Tokenization 
can facilitate placing relevant data from 
ﬁnancial transactions on-chain. In addition, this 
allows for additional data to be tracked and 
enables greater transparency of all information 
linked to any transaction, including the 
provenance of the asset.
However, a shared system of record, or a so-
called golden record, may yield unexpected 
challenges for ﬁnancial institutions that already 
manage and synchronize with several systems 
of books and records, internal and external 
with counterparties. While there are examples 
of parallel, programmable ledgers and 
conventional systems operating, there needs 
to be clarity on the legally enforceable system 
of record to determine the correct claim status 
of an asset on-chain. This ambiguity has of led 
to “shadow records” being put in to record 
and manage asset ownership.
Flexible custodial arrangements
Tokenization enables ﬂexible custodial 
arrangements, ranging from full custody to 
collaborative/shared custody to hosted/
embedded custody, all building upon the user-
centric self/non-custodial model. This enables 
user-centricity by providing direct control over 
assets, identity and data through private keys, 
in many cases removing the reliance on 
intermediaries such as custodians.6 However, 
if private keys are lost or compromised, then 
the security of these models is undermined, 
which is why industry efforts such as the 
DeRec Alliance are driving adoption of private 
key recoverability. Should keys or users be 
compromised through phishing or other 
cyberattacks, on-chain ﬁnancial products 
could have freezing functions built into 
their governing smart contracts to mitigate 
and deter loss.
Programmability
Programmability is the enabling of smart 
contract-driven code to govern how tokens 
are transferred and stored – allows going 
beyond discrete automation by extending 
the scope of automation with event-based 
triggers, conditions and actions on an 
immutable ledger with embedded data 
and instructions in the token.7 Programmable 
ledgers deliver concurrent, real-time 
communication to multiple parties, 
reducing time pressures and aiding 
deadline compliance. 
Putting more of the asset life cycle on-chain 
facilitates operational efﬁciencies that can be 
derived using programmable functions to 
automate actions. Smart contract execution 
can streamline asset servicing, enable liquidity-
saving mechanisms, enhance price discovery 
and improve settlement.8 Programmability 
prevents unilateral changes due to 
immutability, bolstering trust through 
standardized operations and ensuring 
transaction data is integrated within the token 
rather than relying on external integrations.
However, programmatic structuring could have 
unintended consequences, including the 
paradox of programmability – the idea that a 
smart contract is constrained in its ability to 
adapt to market events, such as contagion 
effects, thus introducing systemic risk.9
Asset fractionalization
Conventional ﬁnancial markets offer asset 
fractionalization, yet this feature is novel under 
the paradigm of the ﬂexible custodial 
arrangements. Tokenization also reduces 
the administrative burden of offering smaller 
denominations of assets, a key limitation in 
lowering investment thresholds. This expands 
accessibility because ﬁnancial institutions can 
offer smaller denominations to investors while 
minimizing the operational burden of 
processing a higher volume of activities, such 
as disclosures, asset servicing and compliance 
checks. Fractional ownership, however, 
can result in challenges when enforcing 
ownership of off-chain assets, such as real 
estate or commodities. 
Composability
Tokenization introduces composability, or the 
ability to package and repackage system 
components and portability, which is the ability 
to transfer digital assets between different 
platforms. These features promote multichain 
and multi-asset operations, which allow for 
improved collateral mobility and a potential 
increase in liquidity due to the fungibility of 
assets. While composability contributes to 
ﬁnancial innovation, it presents a unique risk in 
limitless composability where developers could 
create and recreate a limitless number of 
derivatives of on-chain products, resulting in 
potential misuse or non-compliant holding.
Value proposition

<!-- Page 17 -->

Contents
17
ARRANGEMENT
Description
Private keys
Signing patterns
Multisig or MPC
Multisig or MPC
Multisig or MPC
Yes
Yes
Yes
Segregated
Segregated or individual
Reduced risk of key loss
No single entity controls keys
Fast, efﬁcient asset transfers
Recovery of keys possible
Segregated or omnibus
Enterprise-level security
Reduced operational risk
Centralization risk: single 
entity controls assets
Operational complexity: 
coordinating multiple custodians/signers
Platform risk: possible 
platform failures
Financial institutions that are transacting 
or storing a large value of assets
Institutions demanding a degree 
of distributed security
Retail investors prioritizing ease of access 
while remaining protected
Moderate
Moderate
Low
Single signer
Third-party custodian retains 
full control
Designated users have 
shared control
End user has primary control, while the 
wallet service provider acts as a backup
End user retains full control
No
Individual
Increased user control
Ideal for privacy
No recovery: no ability to 
recover lost keys
DeFi users and privacy-focused investors 
valuing full control
High
Recoverability
Account structure
Advantages
Trade-off
Applicability
Risk
A third-party custodian holds and manages 
private keys on behalf of users or institutions, 
making this ideal for institutional clients requiring 
regulatory compliance, security and operational 
efﬁciency.
Requires multiple parties to approve 
transactions by distributing control using 
multiparty computation (MPC), balancing 
security and decentralization while reducing 
reliance on a single entity.
Integrates custody solutions into applications 
via APIs or SDKs, offering businesses ﬂexible 
digital asset management while leveraging 
MPC for enhanced security and granting end 
users some control.
Users retain full control over their private keys 
and digital assets without intermediaries, 
requiring secure key management while 
ensuring full sovereignty and responsibility.
FULL CUSTODY
COLLABORATIVE/SHARED 
CUSTODY
HOSTED/EMBEDDED 
CUSTODY
SELF/NON-CUSTODIAL
T A B L E  2
Flexible custodial arrangements
Value proposition

<!-- Page 18 -->

Contents
18
Tokenized assets
Tokenization can be applied across the asset life cycle, from asset issuance to 
usage in secondary markets, including securities financing and asset management.  
3
Tokenized assets

<!-- Page 19 -->

Contents
19
*Noted as a set of products that bring on-chain assets into off-chain ﬁnancial markets, such as crypto-asset exchange-traded products.
Use case pattern #3: Asset management
On-chain funds
Off-chain funds*
Public equities
Fixed income/debt
Alternative assets
Sovereign bonds
Corporate bonds
Municipal bonds
Private debt
Private equity
Commodities
Real estate
Precious metals
Carbon credits
Use case pattern #1: Asset issuance
Collateral and repurchase agreement markets
Use case pattern #2: Securities ﬁnancing
F I G U R E  5
Tokenization use case patterns
Tokenized assets
3.1 Use case patterns
The sections below examine the impact of 
tokenization on relevant asset classes.
1. Asset issuance
The creation of ﬁnancial instruments across 
asset classes including public equities, 
ﬁxed income (sovereign, corporate, 
municipal) and alternatives (private equity, 
private debt, commodities). These assets 
are issued in support of capital formation 
and market access.  
2. Securities financing  
Short-term transactions such as repos and 
securities lending, where bonds, cash and 
equities serve as collateral. These markets 
enable liquidity management, collateral 
optimization and leverage strategies.
3. Asset management  
The assembly of on-chain and off-chain 
funds, spanning traditional and digital-
native vehicles such as tokenized money 
market funds and treasury funds to provide 
diversiﬁed exposure for investors.

<!-- Page 20 -->

Contents
20
Assets already governed under well-established 
frameworks (such as ETFs and bonds) are 
easier to tokenize in a compliant way – these 
will vary by region.
REGULATORY READINESS
Assets that carry high administrative burdens, 
such as corporate actions or complex 
ownership structures, beneﬁt from 
programmability and a shared system of record.
OPERATIONALLY INTENSIVE
Assets that can be repurposed or reused 
across multiple trading steps, such as collateral 
or liquid staking, beneﬁt from the composable 
features of tokenization.
ASSET REUSABILITY
Assets in high demand by institutions and that 
have familiar structures, such as MMFs and 
treasuries, beneﬁt from the increased velocity 
offered by tokenization.
INSTITUTIONAL DEMAND
Assets locked in physical form, such as gold, 
beneﬁt from secure immobilization and 
tokenization to drive tradability and liquidity.
PHYSICAL FORM FACTOR
Assets traded through unstructured channels 
and over-the-counter (informal) markets beneﬁt 
from tokenization’s programmability and 
composability to enable new trading venues.
UNSTRUCTURED OTC MARKETS
Assets trading or sold in large-value 
increments, such as real estate or public 
placement sovereign bonds, can beneﬁt 
from fractionalization.
LIMITED DIVISIBILITY
Assets with low infrastructure maturity, including 
custody and exchanges, beneﬁt from the “leap-
frog” potential of tokenization.
INFRASTRUCTURE MATURITY
F I G U R E  6
Tokenization-ready traits
There are eight key traits that help determine whether an asset is suitable for tokenization and which asset classes should be prioritized.
Tokenized assets
 WHAT MAKES 
AN ASSET 
TOKEN-READY?

<!-- Page 21 -->

Contents
21
Tokenized assets
Regional considerations
Regional differences will shape which asset 
classes are tokenized ﬁrst. Equities and 
bonds already operate rather efﬁciently in 
advanced economies (AEs) but could beneﬁt 
from tokenization through improved access, 
liquidity and lower costs. In emerging market 
economies (EMEs), where markets are less 
liquid, tokenization can democratize access 
across equities, ﬁxed income and alternatives. 
In EMEs that have nascent existing ﬁnancial 
infrastructure to invest in these products, this 
could allow for “leap-frogging”. In most 
markets, real estate, private credit and PE 
are difﬁcult to access and invest in and 
tokenization can create increased efﬁciencies. 
Meanwhile, commodities such as precious 
metals and carbon credits show region-
speciﬁc adoption based on market 
maturity and regulation. 
Current vs. target adoption
Each asset class is following its own adoption 
path, ranging from tokenizing existing assets 
to issuing them natively on-chain. While any 
electronic asset can, in principle, be natively 
issued, ﬁxed income instruments – such as 
bonds – have advanced faster due to their 
simple structures and ability to be issued as a 
digitally native token. In contrast, real estate 
and physical commodities are limited by their 
off-chain nature and cannot be natively issued 
in the same way. Similarly, off-chain funds 
often take on-chain assets and wrap them 
into traditional structures such as exchange-
traded funds (ETFs).

<!-- Page 22 -->

Contents
22
Tokenized assets
3.2 Asset issuance
Equities
Public equities are shares of publicly traded 
companies listed on stock exchanges and 
offered to a broad investor base. The global 
public equity market was valued at nearly 
$115 trillion in 2023.10 The market 
capitalization of tokenized public stocks 
was estimated at nearly $16 million 
by March 2025.11
Current public equities markets in AEs are 
already highly efﬁcient and beneﬁt from 
decades of technology modernization and 
proven intermediary chains delivering ﬁnancial 
services. Due to existing efﬁciencies in AEs, 
tokenizing public equities may not be 
prioritized over other asset classes.12
However, opportunities exist, particularly in 
EMEs, to improve efﬁciencies and provide 
access to equity markets.13
Source: RWA.xyz (2025)
F I G U R E  7
Tokenized stocks
Backed-issued stocks bCSPX, bCOIN and bNVDA represent almost 90% of tokenized stocks in value.
bCSPX
bCOIN
bNVDA
sMSTR
TSLA.d
Others
$18M
$16M
$14M
$12M
$10M
$8M
$6M
$4M
$2M
$0M
Jan 23
Mar 23
May 23
Jul 23
Sep 23
Nov 23
Jan 24
Mar 24
May 24
Jul 24
Sep 24
Nov 24
Jan 25
Mar 25
Sep 24

<!-- Page 23 -->

Contents
23
Tokenized assets
These are examples of tokenization beneﬁts in 
public equity markets:
1. Enhances information symmetry
Embedding IPO listing criteria directly into 
tokens can enhance distribution efﬁciency 
and transparency.14 This could be beneﬁcial 
as public ﬁrms demonstrate faster growth 
after receiving equity because of superior 
information efﬁciency by aggregating 
known information into the stock price and 
through robust governance mechanisms, 
improving the investor experience.15
2. Facilitates operational efficiency 
Corporate actions represent capital 
markets’ largest unstructured data 
challenge, with more than 3.7 million event 
announcements annually in the US alone 
and costing each participant $3–5 million 
annually.16 
3. Expands accessibility 
Traditional foreign public equity investments 
involve costly processes such as 
immobilizing stocks into depository 
receipts and incurring administration, 
custody and FX fees.17 Tokenization could 
mitigate these costs by embedding 
compliance directly into assets and 
improving secondary market liquidity.18
Tokenization is just one enabler for realizing 
compliance of on- and off-chain data; 
additional processes are usually also 
necessary (e.g. identity checks and legal 
checks). Despite these advantages, tokenizing 
already-efﬁcient public equity markets, 
particularly in AEs, faces challenges. Public 
equities today beneﬁt from robust governance 
and efﬁcient price discovery.19 To achieve 
adoption, tokenization must deliver substantial 
value and clarify where these assets would be 
traded in new venues such as DEXs or other 
digital trading venues.
C A S E  S T U D Y  1
Equities
Click to open
case study details

<!-- Page 24 -->

Contents
24
Tokenized assets
Source: Aldasoro, I., Cornelli, G. Frost, J., Koo Wilkens, P., & Shreeti, V. (2025). Tokenisation of government 
bonds, mimeo
Based on the subset of tokenized bonds with an available International Securities Identiﬁcation Number (ISIN).
Sovereign bonds
Government or sovereign bonds are debt 
securities issued by national governments, 
often considered low-risk investments and 
used as benchmarks for interest rates. They 
are critical for funding government operations 
and old debt or interest. They also play 
an integral role in institutional portfolios, 
providing predictable returns and aiding in 
retirement planning.24 
Government authorities are gradually 
endorsing tokenized public debt, evidenced by 
His Majesty’s Treasury’s plans for a digital gilts 
pilot in the UK Finance’s comprehensive 
roadmap,25 the US Commodity Futures 
Trading Commission acceptance of tokenized 
treasuries as non-cash collateral26 and the US 
Treasury’s acknowledgment of potential 
operational beneﬁts.27 In Hong Kong, the 
government has committed to the issuance of 
tokenized bonds as standard practice. The 
Hong Kong Monetary Authority (HKMA) is 
preparing to issue the third tranche of 
tokenized bonds, while actively exploring 
tokenizing existing bonds.28 Collectively, there 
is a progressive shift towards adopting 
tokenization for sovereign securities.  
Cumulative amount issued (left-hand side):
Commercial
Sovereign, supranational and agency
Cumulative issuances (right-hand side):
$ billion
No of bonds
2019
0
1
2
3
4
0
5
10
15
20
2020
2021
2022
2023
2024
F I G U R E  8
A growing number of issuers are experimenting with 
tokenized bonds
Commercial vs. sovereign, supranational and agency tokenized bonds
Fixed income
Fixed-income securities are debt instruments 
issued by a government, corporation or other 
entity to ﬁnance their operations. They provide 
investors with a return in the form of ﬁxed 
periodic payments and the eventual return of 
the principal at maturity.20 The global ﬁxed-
income, or bond, market was valued at 
approximately $140.7 trillion in 2023.21 Fixed-
income tokenization has seen notable 
advances in sovereign, corporate and 
municipal bonds. 
According to an Ofﬁcial Monetary and 
Financial Institutions Forum (OMFIF) survey of 
26 ﬁnancial institutions, 65% believed that 
bonds were the most likely to be tokenized.22 
For example, the European Investment Bank 
(EIB) has issued several bonds on-chain, 
proving the feasibility of tokenization. Since 
2021, with its inaugural digital bond issued on 
Ethereum, the EIB has issued ﬁve bonds, most 
recently using HSBC’s Orion platform for 
issuance and the Banque de France’s DL3S 
platform for settlement.23

<!-- Page 25 -->

Contents
25
% of total issuance volume DLT-based bonds by location 
(since 2021)
EU
US
APAC
Rest of world
Switzerland
0.3%
21%
31%
38%
10%
Source: Association for Financial Markets in Europe. (2024). Use of DLT and tokenisation in ﬁnancial markets
F I G U R E  9
Global issuance of DLT-based bonds in billions of euros 
and by location
Global issuance of DLT-based bonds (in EUR Bn)
2021
0.3
2022
0.9
2023
0.8
2024 (Aug)
1.3
Tokenized assets
Corporate bonds
Corporate bonds are issued by companies 
to raise capital, offering varied yields and 
risk levels depending on the issuer’s 
creditworthiness. Tokenized corporate bonds 
represent a form of debt in capital markets, 
enabling fractional ownership, streamlined 
settlements and broader investor access. 
For example, the Societe Generale FORGE 
in France has demonstrated how tokenized 
corporate bonds can comply with regulatory 
requirements while beneﬁtting from on-chain 
settlement efﬁciencies.29 Nomura’s partnership 
with BOOSTRY in Japan illustrates a growing 
regulatory acceptance of tokenized corporate 
bonds, reﬂecting a global innovation trend in 
ﬁnancial assets.30
Municipal bonds
Municipal bonds are issued by local or 
regional governments to fund public projects, 
often providing tax advantages to investors. 
The Six Digital Exchange (SDX) announced 
in May 2024 that it had achieved more than 
1 billion Swiss francs ($1.2 billion) in assets 
on its digital asset platform. Part of the 
success of these digital bond issuances 
on its platform is due to the availability of 
atomic settlement (e.g. DvP), using tokenized 
central bank money as part of the Swiss 
National Bank’s wCBDC limited phase pilot.31 
Examples of tokenization beneﬁts in ﬁxed-
income markets include:
1. Enhances information symmetry
Bonds can be tokenized to create and 
track metadata across the following 
parameters: issuance amount, maturity, 
coupon, features and corporate actions, 
approved operators and transfer 
conditions.32
2. Facilitates operational efficiency 
Tokenized bonds lowered underwriting 
fees by an average of 0.22% of the bond’s 
par value, reducing 5.3% bid-ask spreads 
on average and with the efﬁciencies 
compounding when including retail.33
DLT can automate up to 2,000 tasks in 
the bond issuance process,34 which can 
take up to 12 weeks, save 800–1,000 
person hours during issuance and reduce 
book-closing periods by more than 50%.35
3. Expands accessibility 
Conventional bonds have high minimum 
buy-in thresholds, limiting investor access. 
Tokenization can lower this barrier by 
fractionalizing the assets and easing the 
operational burden. Low investment 
thresholds with conventional bonds have 
operational burdens, including paperwork 
and resource costs. Lowering thresholds 
in public markets could increase the 
likelihood of regulatory limitations.
C A S E  S T U D Y  2
Fixed income
Click to open
case study details

<!-- Page 26 -->

Contents
26
Alternative assets
Private equity
Private equity (PE) is ownership stakes in 
companies not listed on public exchanges, 
typically held by institutional investors and 
requiring longer investment horizons in 
exchange for potentially higher returns. The 
size of the global PE market reached 
approximately $5.3 trillion in 2023 and shows 
signs of continued growth.36 Some projections 
are for the total PE/venture capital market to 
grow to $7 trillion by 2030, with roughly 10% 
being tokenized by that same time.37
PE markets are considered less efﬁcient than 
public markets due to limited information ﬂow 
and transparency. Investment in private 
markets relies heavily on intermediaries (fund 
managers) to source and evaluate deals, 
resulting in performance disparities.38
Tokenization has emerged as a potential 
solution to these inefﬁciencies by digitizing 
ownership in funds or companies. Industry 
research shows that 73% of European fund 
managers anticipate that PE will be the ﬁrst 
asset class to experience signiﬁcant 
tokenization, driven by a need to improve 
liquidity, transparency and accessibility.39
The following beneﬁts could be achieved:
1. Enhances information symmetry
Tokenization can drive increased data 
sharing and adding disclosures to PE can 
drive more transparency in the currently 
opaque private markets.40 
2. Facilitates operational efficiency
Tokenization, if applied, should reduce 
frictions associated with operational and 
technological aspects instead of altering 
the deal-structuring and relationship-based 
nature of these markets.
3. Expands accessibility 
For example, in 2021, ADDX tokenized 
units from Partners Group’s €5.5 billion 
($6.2 billion) PE fund, allowing fractional 
investments as low as $10,000 (previously 
$100,000-plus), greatly expanding 
investor accessibility via lower minimum 
investment thresholds and complying with 
regulatory standards.41
Several ﬁrms have already taken steps to 
tokenize PE investments. Recently, Aurum 
Equity Partners launched the world’s ﬁrst 
combined PE and debt tokenized fund valued 
at $1 billion on the XRP Ledger, an open-
source and decentralized Layer-1, to drive 
worldwide data centre investment, enabling 
enhanced investor access and liquidity 
through secondary markets.42
However, private markets derive much of their 
value from the individual nature of deals, which 
require research and structuring to deliver 
investor value. Tokenization may not always be 
necessary to achieve beneﬁts. For example, 
EquityZen and Forge Global are two 
marketplaces offering retail investors a 
minimum investment threshold of $5,000 and 
they do not use DLT.43
Tokenized assets
C A S E  S T U D Y  3
Private equity
Click to open
case study details

<!-- Page 27 -->

Contents
27
Private debt
The terms “private debt” and “private credit” 
are used interchangeably and refer to non-
bank lending or bonds outside traditional 
markets used to fund private businesses.44
The global private credit market has surpassed 
$3 trillion in assets under management 
(AUM).45 This asset class consists of higher-
risk loans with higher-interest rates than 
conventional debt. Unlike public debt, private 
debt is issued by non-bank entities or 
individuals to raise funds or form capital.
Private debt can attract investors, offering 
higher returns and risk. Private-sector leaders 
believe private debt will be the ﬁrst asset class 
to be tokenized and routinely traded.46 About 
70% of private-debt investors are institutional 
investors or entities investing on behalf of an 
individual, typically a private credit fund.47
Most private loans on-chain are direct loans to 
institutional crypto investors. These loans 
mostly appeal to high-net-worth individuals 
and accredited investors as yields range from 
9% to 20%. However, they carry risks in that 
the collateral posted is limited in diversity.48
Because crypto-assets such as Ethereum 
back most loans, signiﬁcant market 
corrections of these assets could affect the 
lending positions of the holders.
Examples of the beneﬁts of tokenization for 
private debt include:
1. Enhances information symmetry
Transaction ﬂow would be in real time, 
providing data on underlying assets 
at all times.49
2. Facilitates operational efficiency
Smart contracts reduce and mitigate back-
ofﬁce costs and lower transaction costs 
and management fees.
3. Expands accessibility
Easing the process of buying into private 
credit funds and of trading shares can 
increase the range of investors. For 
example, in 2022, KKR collaborated with 
Securitize to tokenize a segment of its $4 
billion healthcare fund on Avalanche, 
reducing investment minimums and 
onboarding accredited investors, 
increasing reach.50
On-chain activity for private debt/credit is 
increasing but is largely limited to crypto-
assets and select corporate bond issuances. 
Protocols such as Maple, Goldﬁnch and 
Centrifuge have driven more than $13 billion in 
on-chain loans in public networks, including 
Ethereum and Solana.51
Tokenized assets
F I G U R E  1 0
Tokenized private credit by issuer
Figure represents almost 80% of the value of outstanding tokenized private loans
Source: RWA.xyz (2025)
Figure
Tradable
Maple
PACT
MB | Mercado Bitcoin
Others
$14M
$12M
$10M
$8M
$6M
$4M
$2M
$0M
Jan 23
Mar 23
May 23
Jul 23
Sep 23
Nov 23
Jan 24
Mar 24
May 24
Jul 24
Sep 24
Nov 24
Jan 25
Mar 25

<!-- Page 28 -->

Contents
28
Real estate
Real estate as an asset class refers to 
investments in real property and is 
characterized by its physical nature and 
potential for both income and capital 
appreciation.52 The global real-estate market 
was valued at approximately $379.7 trillion at 
the end of 2022, encompassing residential, 
commercial and agricultural properties.53
Tokenizing real estate involves converting 
property ownership into digital tokens on a 
programmable ledger, facilitating fractional 
ownership and potentially enhancing liquidity 
in this traditionally illiquid market. The total 
value of real estate brought on-chain is 
estimated to be between $4 billion and $20 
billion, underscoring a large remaining 
addressable market. 
Real estate could beneﬁt from tokenization 
for these reasons:
1. Enhances information symmetry
Today’s real estate markets are isolated 
and do not have connected systems of 
record. Tokenization could help with 
streamlining these records for stronger 
information symmetry. For example, a 
district administration in India digitized 
700,000 land records dating back to 1950 
on the Avalanche blockchain, addressing 
challenges associated with requests for 
information regarding records and 
their veriﬁability.
2. Expands accessibility
This process can streamline transactions 
by reducing intermediaries and 
administrative overhead, making real-
estate investment more accessible.54
However, regulatory uncertainties between 
jurisdictions and technological integration 
issues exist. Outstanding design choices 
remain related to the impact of tokenizing real 
estate on the local economy and deed 
transferability.55 Existing investment vehicles 
such as real estate investment trusts (REITs), 
ETFs and direct funds offer similar beneﬁts, 
potentially limiting the appeal of tokenization. 
Despite these hurdles, successful cases 
demonstrate the potential of this approach to 
democratize real-estate investment.
Tokenized assets
C A S E  S T U D Y  4
Real estate
Click to open
case study details

<!-- Page 29 -->

Contents
29
Commodities
A commodity is a physical good attributable to 
a natural resource that is tradable in physical 
(spot) markets and in future and forward 
markets.56 The nominal value in the 
commodities market is projected to reach 
$142.85 trillion in 2025.57
Precious metals
Precious metals are valued for their scarcity 
and used as hedges against inﬂation and 
economic uncertainty. The tokenization of 
precious metals, particularly gold, has become 
a signiﬁcant use case in ﬁnancial markets. The 
total capitalization of the physical gold market, 
excluding the jewellery market, is estimated at 
$5 trillion in 2024.58 While traditional methods 
of investing in gold, such as physical gold, 
coins and ETFs, have existed for years, 
tokenization offers a unique opportunity to 
broaden access to gold. 
Several organizations have introduced gold-
backed digital tokens, including Paxos, Tether, 
WisdomTree and HSBC. 
The following opportunities are presented with 
gold-backed tokens:
1. Expands accessibility
Gold-backed tokens make it possible for 
investors to purchase fractional amounts, 
lowering the entry barrier and enabling a 
wider range of participants – such as retail 
investors – to gain gold exposure.
2. Enhances user-centricity
Through mobile applications and more 
ﬂexible custodial arrangements, the ease 
of holding gold or the exposure to gold 
improves as compared to investing 
in gold today.
3. Promotes multi-asset mobility
Tokenization of gold could allow free usage 
as collateral without traditional limitations 
such as storage.59
As highlighted in the section on backed 
tokens, gold-backed tokens are not without 
their hurdles and risks.
A leading challenge is integrating physical and 
digital worlds, especially securing and storing 
metal or stone.60 Today’s model relies heavily 
on custodians’ safekeeping and auditors 
verifying reserves, potentially creating 
concentration risk. Due to operational 
challenges, not all gold-backed token 
providers offer physical redemption. Fractional 
ownership is possible, but physical redemption 
depends on the issuer. 
Gold-backed tokens’ continuous, 24/7 nature 
can cause price dislocations when integrated 
with conventional markets, which operate only 
Monday through Friday. 
Tokenized assets
Source: RWA.xyz (2025)
F I G U R E  1 1
Tokenized commodities by product
Paxos’ PAXG and Tether’s XAUT, both tokenized gold products, account for 99% of the tokenized 
commodity market
PAXG
XAUT
Tokenized Gold (Others)
Tokenized Silver (TXAG)
Tokenized Platinum (TXPT)
$1,400M
$1,200M
$1,000M
$800M
$600M
$400M
$200M
$0M
Mar 21
Jun 21
Sep 21
Dec 21
Mar 22
Jun 22
Dec 22
Sep 22
Mar 23
Jun 23
Sep 23
Mar 24
Jun 24
Sep 24
Mar 25
Dec 24
Dec 23

<!-- Page 30 -->

Contents
30
T A B L E  3
Comparison of gold investment vehicles
Tokenized assets
MODEL
Physical bars 
and coins
Vaulted physical 
gold
Gold contracts 
(futures)
Gold ETFs
Gold-backed 
tokens
Tangible ownership of gold bars or coins 
purchased from dealers, mints or 
secondary markets.
Investor owns allocated or unallocated gold 
stored in vaults. They receive a claim/
certiﬁcate rather than holding metal.
Standardized contracts to buy/sell gold on 
a set future date, traded on regulated 
commodity exchanges.
ETFs that track the gold price and usually 
hold physical gold or futures contracts.
Digital tokens on a programmable ledger 
that represent a claim on physical gold 
stored by a custodian.
— High storage and security costs
— Limited liquidity
— High spreads
— No direct ownership
— High minimum investments
— Custody, redemption fees
— No direct exposure
— Settlement cycle-dependent
— Reliance on custodians
— Liquidation depends on exchanges
— Inaccessible for those in regions with 
underdeveloped ﬁnancial infrastructures
— Supply-chain challenges for 
physical redemption
— Potential for price dislocation during 
weekend trading
— Platform and custodian risk
— Supply-chain challenges for 
physical redemption
— Direct exposure to tangible asset
— Minimal to no counterparty risk
— Professional storage and security
— High liquidity and trading availability
— No storage or security costs
— Highly liquid and ease of trading
— Low transaction costs
— Transparent pricing
— Enables creative investment strategies, 
such as leveraging gold exposure 
through derivatives or use of collateral
— Fractionalized and easily accessible
— Continuous trading availability
— Traceability and veriﬁability
— Instant and atomic settlement
DESCRIPTION
ADVANTAGES
TRADE-OFFS
C A S E  S T U D Y  5
Precious metals
Click to open
case study details

<!-- Page 31 -->

Contents
31
DEMAND
SUPPLY
Source: Accenture (2024)
F I G U R E  1 2
The carbon offset life cycle 
Carbon credits 
Carbons credits (CCs) are tradable permits 
that represent the right to emit a speciﬁc 
amount of carbon dioxide (CO2), supporting 
global efforts to reduce emissions. The global 
CC market is valued at around $1.4 billion.61
A carbon credit is a ﬁnancial asset that 
represents ownership of 1 metric ton of CO2
equivalent and can be traded or sold to meet 
a mandatory emissions cap or a voluntary 
emissions reduction target.62 CCs are integral 
to both compliance and voluntary carbon 
markets, enabling entities to offset their 
greenhouse gas (GHG) emissions.63
As a standardized measure for emissions, 
these credits are used by corporations to 
counterbalance their GHG emissions 
stemming from operations.64 CCs can be 
tokenized – whether natively issued on a 
programmable ledger or immobilized off-chain 
and issued on-chain. 
As of 2023, more than 3,400 companies 
have committed to net-zero emissions, with 
the VCM valued at approximately $723 
million.65 However, only 188 companies 
actively invest in carbon dioxide removal 
(CDR), highlighting a gap between 
commitments and tangible actions. The 
market size for VCMs is around $2 billion, 
with conservative estimates putting it at 
$50 billion by 2050.66
Tokenized assets
Offset transaction
Exchanges, brokers, FSI
Offset retirement
Corporate/F&I + registry
Project creation/
development
Offset project developers
Offset demand
Corporates/
sovereigns
GHG inventory
Third-party consulting or 
engineering firm
Offset identification
Corporates, consultants
Project registration/ 
verification
Offset standard 
and verifier
Offset serialization 
and issuance
Offset standard 
registry

<!-- Page 32 -->

Contents
32
A leading example is AirCarbon Exchange 
(ACX), a global platform changing the 
VCM by providing a transparent, efﬁcient 
trading system for environmental assets.67 
Another example is the recently successful 
proof-of-concept pilot of using tokenized 
deposits to settle carbon credits, led by 
Standard Chartered, Mox Bank, Mastercard 
and Libeara.68
The CC market could beneﬁt from tokenization 
for the following reasons:
1. Enhances information symmetry
Tokenizing CCs can enhance transparency, 
traceability and liquidity in carbon markets. 
This process streamlines issuance, trading 
and retirement, reducing administrative 
costs and minimizing risks such as double-
counting and greenwashing. 
2. Facilitates operational efficiency
Smart contracts automate transactions, 
ensuring compliance with regulatory 
standards and boosting market efﬁciency.
3. Expands accessibility
Tokenization democratizes access, 
allowing individuals and smaller 
organizations to participate in carbon 
offset initiatives, broadening market 
reach and impact. 
CCs have faced scrutiny due to concerns 
about overstated emission reductions and the 
actual impact of offset projects. To address 
this, the Integrity Council for the VCM (ICVCM) 
introduced the Core Carbon Principles to 
enhance buyer conﬁdence by ensuring 
rigorous baseline fuel determination and usage 
monitoring. To advance the development of 
carbon credits using DLT, the InterWork 
Alliance’s Voluntary Ecological Markets set 
forth principles for further collaboration.69
CCs can vary in quality, prompting standards 
bodies to implement stringent issuance and 
trading standards to prevent low-quality CCs 
from entering markets. While tokenization 
alone cannot fully address these challenges 
due to operational and human factors, 
integrating smart contracts with robust 
governance can standardize and enhance 
the quality of tokenized CCs. 
Tokenized assets

<!-- Page 33 -->

Contents
33
3.3 Securities 
financing
Securities ﬁnancing transactions allow 
investors and ﬁrms to use assets, such as the 
shares or bonds they own, to secure funding 
for their activities.70
Collateral 
This report identiﬁes collateral and repurchase 
agreements (repos) as a key application of 
tokenization. The global collateral market is 
estimated to be worth more than $25 trillion.71  
Collateral refers to what is posted and received 
– typically a liquid and secure asset – pledged 
to support a ﬁnancial transaction, providing 
default protection. Collateral is fundamental to 
managing counterparty risk and ensuring the 
smooth functioning of ﬁnancial markets by 
mitigating credit risk. The ideal collateral 
should be free from credit and liquidity risks, 
maintain a stable value and not correlate with 
the provider’s credit risk.72 
Programmable ledger-powered collateral 
management could unlock more than $100 
billion annually in capital that can be 
redeployed for higher efﬁciency.73 This 
objective of improving collateral mobility is at 
the heart of emerging tokenized collateral 
management platforms, such as JP Morgan’s 
Total Collateral Network (TCN), HQLAx and the 
Canton Global Collateral Network (GCN), 
which all aim to address the historical 
challenge of orchestrating complex cross-
custodian movements of collateral, or the 
transfer of ownership countries between 
custodians through real-time, compliant and 
interoperable asset mobility between traditional 
and digital markets.74 This fragmented 
custodian landscape tends to be costly and 
dependent on non-overlapping operating 
hours. Collateral mobility is measured by a 
participant’s ability to identify the right 
collateral to be moved to the right party 
at the right time.75
Acceptable collateral frameworks
Current regulatory frameworks and jurisdiction-
speciﬁc rules limit which investors can hold, 
pledge or accept collateral, which hinders 
efforts to trade collateral across borders. 
Policy-makers and the private sector should 
clarify the set of eligible tokenized collateral, 
including potentially expanding the scope of 
acceptable collateral. 
Repurchase agreements
Intraday repo is observed as the primary area 
of adoption of tokenization. A repo is a short-
term loan where one party sells securities to 
another in exchange for cash, with an 
agreement to buy them back later at a higher 
price. Repos are a common way for ﬁnancial 
institutions to obtain short-term funding.76 The 
global repo market is very large, with an 
estimated size of more than $15 trillion in 
outstanding value and a daily turnover of 
around $3–4 trillion.77
Due to their high turnover, repo markets face 
several inefﬁciencies and risks. Manual and 
fragmented workﬂows rely on outdated and 
disconnected systems, leading to delays, 
errors and costs. Additionally, settlement 
inefﬁciencies are born from the many 
intermediaries coordinating complex 
transactions – rapid buy and sell orders – that 
have led to longer settlement cycles, liquidity 
constraints and counterparty risks.
Tokenization offers three beneﬁts for collateral:
1. Enhances information symmetry
Money market funds (MMFs) are not 
directly used as collateral because of 
data reconciliation challenges between 
counterparties driven by their complex 
ownership structures. Tokenization’s 
shared system of record could bring 
visibility into the custodial relationship 
with underlying fund owners, reducing 
the burden of managing relationships 
between transfer agents, custodians 
and counterparties.
2. Facilitates operational efficiency
Enables real-time position tracking and 
instant transfers of ownership.78
Programmability can automate asset 
servicing and maintain a shared record to 
ease operational burdens associated with 
maturities, dividends and coupon 
payments.
3. Promotes multi-asset mobility
Allows participants to extend asset 
usability through digitally represented 
collateral across subsequent transactions 
by using the platform’s programmable and 
composable smart contracts. For example, 
a pilot on the Canton Network with 
Euroclear and the World Gold Council 
found that gold-backed tokens allow freer 
usage as collateral.79 SDX and SIX 
Securities Services are bringing to market 
the new Digital Collateral Service (DCS), 
speciﬁcally designed to enable the usage 
of selected crypto-assets as collateral 
alongside traditional collateral.80
Tokenized assets
C A S E  S T U D Y  6
Repurchase agreements
Click to open
case study details

<!-- Page 34 -->

Contents
34
3.4 Asset 
management
Funds 
Two primary fund structures are relevant to 
tokenization: on-chain funds, which tokenize 
conventional assets, and off-chain funds, 
such as ETFs, that invest in programmable 
ledger-native assets.
On-chain funds
On-chain funds represent traditional assets as 
digital tokens on a programmable ledger, 
facilitating broader investor access on new 
digital channels and direct trading without 
central clearing parties. This approach is 
intended to reduce operational costs and 
broaden investor access. On-chain funds 
today are backed by off-chain reference assets 
or tokenized versions of traditional securities. 
Estimates indicate that tokenized treasuries 
have grown from $104 million to $5 billion in 
market capitalization since 2023.82 Examples 
such as Franklin Templeton’s Benji and Ondo 
Finance’s USDY have succeeded in bringing 
off-chain treasuries and other high-quality 
liquid assets (HQLA) on-chain.
Tokenized assets
Source: RWA.xyz (2025)
F I G U R E  1 3
Tokenized US Treasuries by product 
BlackRock USD Digital Liquidity Fund (BUIDL)
Ondo US Dollar Yield (USDY)
WisdomTree Gov. Money Market Fund (WTGXX)
Hashnote Short Duration Yield Coin (USYC)
Ondo Short Term US Gov Bond (OUSG)
OpenEden (TBILL)
Franklin Templeton Gov Money Fund (BENJI)
Superstate Asset Trust (USTB)
Others
$2.0B
$1.8B
$1.6B
$1.4B
$1.2B
$1.0B
$0.8B
$0.6B
$0.4B
$0.2B
$0M
Jan 24
Feb 24
Mar 24
Apr 24
May 24
Jun 24
Jul 24
Aug 24
Sep 24
Oct 24
Dec 24
Jan 25
Mar 25
Feb 25
Nov 24

<!-- Page 35 -->

Contents
35
However, a future trajectory points towards the 
development of funds composed of natively 
issued digital assets. Such a shift could 
improve transparency in the complex 
ownership structures of instruments such as 
MMFs. Greater clarity around ownership 
claims may enhance the suitability of MMFs 
for use as collateral, potentially supporting 
broader adoption.
There is, however, limited evidence so far 
to suggest these funds signiﬁcantly reduce 
costs, such as fund administrator fees, 
when compared to conventional models. 
Often, these funds also provide investor 
returns that are more in line with their 
conventional counterparts.
Notable examples include:
—  In 2021, Franklin Templeton launched the 
Franklin OnChain US Government Money 
Fund (FOBXX), the ﬁrst US-registered 
mutual fund to use a public programmable 
ledger for transaction processing and share 
ownership recording.83 Initially on the 
Stellar network, the fund expanded to 
other programmable ledgers, including 
Avalanche and Polygon, demonstrating 
adaptability. BENJI is the user-facing portal 
for retail investors to buy and hold shares 
of FOBXX using digital wallets, and BENJI 
tokens represent ownership in FOBXX and 
are recorded on-chain.
—  In June 2024, Fidelity International 
tokenized shares of an MMF on Kinexys 
Digital Assets, piloting a tokenized MMF 
on the Tokenized Collateral Network (TCN). 
The fund’s transfer agent (JP Morgan) and 
the TCN coordinated the tokenization, 
which improved efﬁciency in delivering 
margin requirements and reducing 
transaction costs and operational frictions 
by serving as collateral in clearing and 
margining transactions.84
—  In January 2025, Fasanara Capital 
introduced its ﬁrst tokenized MMF, the 
Fasanara MMF Token (FAST), on the 
Polygon blockchain in collaboration 
with Tokeny and others. This fund 
offers investors enhanced efﬁciency 
and transparency in money 
market investments.85
Owns
Tokenized 
Fund A shares
Tokenized 
Fund B shares
Represent ownership
Underlying 1 (e.g. Stock A)
Underlying 2 (e.g. Stock B)
Money (e.g. HKD, USD)
...
Fund legal entity
Source: Boston Consulting Group
Tokenized assets
Underlying 1 (e.g. Stock A)
Underlying 2 (e.g. Stock B)
Money (e.g. HKD, USD)
...
Investors
Owns
Implications
Allow instant fund 
ownership 
changes, enabling 
secondary transfer of 
funds through use of 
blockchain …
… while avoiding 
impact on the 
operations for 
underlying assets, 
given that existing 
process and 
infrastructure can be 
leveraged
Fund A shares
Fund 
Tokenized fund: Recording fund share 
ownership in blockchain
Fund B shares
Represent ownership
Fund legal entity
Transfer 
agents
Asset 
managers
F I G U R E  1 4
Traditional funds vs. tokenized funds
C A S E  S T U D Y  7
On-chain fund
Click to open
case study details

<!-- Page 36 -->

Contents
36
Off-chain funds
Conversely, off-chain funds such as ETFs 
provide exposure to digital assets without 
directly holding them on a programmable 
ledger. The crypto-asset ETFs are not 
tokenized ﬁnancial products, though they are 
covered in this report to capture an expansive 
view of the integration of tokenized and 
traditional markets. 
By November 2024, the spot crypto-asset 
ETFs worldwide reached approximately $136 
billion in AUM, with the United States 
accounting for nearly 95% of this total.86
These funds invest in cryptocurrencies such 
as Bitcoin (BTC), Ethereum (ETH), offering 
traditional investors a familiar TradFi vehicle 
to access the crypto market. For instance, 
Franklin Templeton ﬁled for an ETF to track 
the spot price of Solana, indicating a growing 
interest in diversifying crypto-asset offerings.87
Tokenized assets

<!-- Page 37 -->

Contents
37
Barriers to adoption
Barriers to adoption
Tokenization’s success relies on overcoming several 
barriers that exist in financial markets today. 
4

<!-- Page 38 -->

Contents
38
4.1 Traditional 
financial infrastructure
One path for driving network effects and 
liquidity is the integration of tokenized markets 
with conventional systems. A challenge faced 
by ﬁnancial services institutions is the 
reconciliation between the books and records 
of tokenized systems and their internal books, 
resulting in possible discrepancies or disputes 
on the ofﬁcial claim of the asset. Addressing 
challenges such as these requires a staged 
approach to using existing investments 
in supranational networks to secure 
transactions between traditional and tokenized 
systems. This can avoid costly new 
infrastructure, spur conﬁdence, reduce risk 
and accelerate adoption. 
Financial institutions can incrementally adopt 
tokenized assets by connecting public 
programmable ledgers to their existing 
infrastructure, beginning with non-cash assets 
and scaling as new forms of on-chain value 
emerge. For example, Chainlink, Swift and 
UBS Asset Management enabled tokenized 
fund transactions via Swift, reducing 
inefﬁciencies in the $63 trillion global mutual 
fund market.88
4.2 Global standards
Global tokenization adoption requires robust, 
harmonized standards. A lack of widespread 
industry collaboration and fragmented 
innovation is cited as a major factor in 
stymying the progress of the adoption of 
tokenization.89 Estimates show 74% of DLT 
projects in 2023 had fewer than six 
participants, underscoring a need for wider 
participation.90  Furthermore, while the legal 
and technical enablement of tokenization is 
foundational, only the engagement of market 
participants will advance adoption.91
Five critical areas that would need to align 
for widespread usage are: roles and 
responsibilities, token standards, the cash 
leg and settlement, cross-chain interoperability 
and reference data.92 Standardization will 
require time and deep dedication and will 
possibly be performed in a staged manner to 
allow incumbents and digital natives to adapt. 
For example, the Hong Kong Monetary 
Authority convened a Programmability Working 
Group in 2024 to develop a common standard 
for programmability at scale. The system can 
realize transformative beneﬁts by uniting 
around standards and inspiring global 
efﬁciency while boosting adoption and trusted 
market participation.
Barriers to adoption
The fungible
token standard
ERC-20
Swiss-compliant
standard
CMTAT
The non-fungible
token standard
ERC-721
Security token
standard
ERC-1400
Issuing and trading
SEC-compliant
securities
ERC-1450
Multi-token
standard
ERC-1155
The compliance-
aware token 
standard
ERC-3643
Swiss compliant
asset token
ERC-2980
F I G U R E  1 5
Common token standards (EVM)
Source: Nethermind & PwC Germany. (2025). Tokenization Standards: The Missing Link for Institutional Adoption.

<!-- Page 39 -->

Contents
39
Token standards are an important aspect of 
this global harmonization. ERC-20 today 
remains the dominant token standard, yet it 
lacks built-in compliance features.93 It is for this 
reason that compliance-led tokens, such as 
ERC-1400 and ERC-3643 (T-REX Protocol), 
are gaining traction:
—  ERC-1400 allows for enhanced document 
management and investor protection, 
lending itself more to securities.
—  ERC-3643 embeds identity, know your 
customer/anti-money laundering (KYC/
AML) and transfer conditions, unlocking 
new approaches to on-chain compliance.
Token standards should continue to evolve 
towards established regulatory frameworks, 
such as Markets in Crypto-Assets Regulation 
(MiCAR) in the Eurozone.  
4.3 Cross-chain 
interoperability
Interoperability across private and public 
ledgers ensures seamless asset movement. 
Financial services entities had adopted at least 
72 distributed or programmable ledgers as of 
May 2025 and driven 10 market forces that 
are accelerating the deployment of individual 
networks.94 These networks are not all 
inherently interoperable and the importance 
of cross-chain interoperability is underscored 
to realize inter-network activity.
Emerging techniques reduce concerns 
regarding cross-chain interoperability, notably 
“honey-pot attacks”, which result from non-
canonical bridging. To mitigate this, Chainlink’s 
collaboration with ANZ Bank, which 
successfully linked a private ledger to a public 
programmable ledger using the Cross-Chain 
Interoperability Protocol (CCIP), showed the 
potential for cross-chain liquidity. LayerZero 
has created its Omnichain Fungible Token 
(OFT) standard, which transfers fungible 
tokens across programmable ledgers without 
asset wrapping or middle chains.95
4.4 Secondary 
markets
In primary markets, assets are initially issued 
and purchased. Secondary markets involve 
trading after initial issuance. Today, there is a 
lack of sufﬁcient secondary-market liquidity 
and depth for tokenized assets.96
Secondary markets are critical to liquidity, yet 
tokenized assets struggle to establish market 
depth.97 Many tokenized assets could not yet 
attract sufﬁcient secondary trading volume, 
leading to illiquidity and difﬁculty in accurate 
pricing. In ﬁxed income, more than $15 billion 
in tokenized assets – bonds, structured 
products, commercial papers and funds – 
have been issued, as of 2024. However, 
nearly half of these initiatives report turnover 
below $1 million, highlighting a signiﬁcant 
gap between expectations and actual 
activity.98 Therefore, an implicit illiquidity 
premium can be applied to tokenized assets 
in today’s markets. However, there is a lack of 
secondary-market data to fully demonstrate 
the beneﬁts and drawbacks of the usage of 
tokenized assets.99
Prominent barriers include insufﬁcient 
incentives for market makers to provide 
liquidity in predominantly over-the-counter 
(OTC) markets; high minimum investment 
thresholds in private placements, with 
fractionalization offering only partial relief 
due to administrative costs; regulatory hurdles 
hindering cross-border trading and 
collateralization; investor access often 
restricted to institutions; and listing fees 
discouraging dual-listing strategies, which 
traditionally boost liquidity – though UBS 
notably dual-listed a digital bond on both 
SDX and the SIX Swiss Exchange in 2022.100 
Enabling this is SIX’s bidirectional bridge 
between traditional and digital central security 
depositories (CSDs) that enables assets 
to be issued, custodied or transferred on 
either venue. 
Fragmentation risks emerge when providing 
liquidity, such as settlement assets, for 
secondary-market trading. For example, 
Target 2 is used in the Eurozone to provide 
security settlement services for all CSDs 
in the jurisdiction. Furthermore, introducing 
another on-chain cash system for a distinct 
secondary market could fragment the unity 
of cash for settlement. 
Market makers require incentives to provide 
liquidity and inspire capital formation. Dual-
listing can beneﬁt issuers who seek to issue in 
their native jurisdiction, whether because of 
compliance requirements or allegiance to a 
target jurisdiction, to drive turnover with a 
dedicated pool of investors. Lastly, despite 
programmable ledgers’ inherent 
decentralization goals, liquidity remains 
fragmented across platforms.  
Barriers to adoption

<!-- Page 40 -->

Contents
40
4.5 Privacy and 
compliance
Fragmented identity veriﬁcation limits the 
growth of tokenized ﬁnancial products. 
Standardized KYC is estimated to improve 
onboarding efﬁciency by up to 90% in fund 
management.101 On-chain identities offer 
potential but raise privacy concerns.
Privacy is the capacity for individuals or 
organizations to dictate how and when 
their data is shared and is based on the 
principle of individuals controlling the degree 
to which they selectively express themselves 
digitally, including identiﬁers such as age, 
accredited investor status and nationality.102
On-chain identities can range from fully 
identiﬁable to pseudonymous and anonymous. 
However, fully anonymous identities conﬂict 
with Financial Action Task Force (FATF) 
guidelines, which require due diligence for 
every ﬁnancial customer and prohibit 
untraceable accounts.103
Privacy-enhancing technologies (PETs) such 
as zero-knowledge proofs and fully 
homomorphic encryption protect sensitive 
data while enabling compliance. For example, 
PETs, including pseudonymization and zero-
knowledge proofs, are being explored by the 
BIS under Project Aurum 2.0 to advance 
retail CBDCs.104 
Although anonymity provides better privacy 
safeguards in theory, it poses risks to KYC and 
AML compliance as it could allow bad actors 
to obfuscate on-chain illicit activities, which 
amounted to nearly $25 billion in 2021.105
Customer and transaction identiﬁcation is 
essential for complying with KYC, AML, 
sanctions and the Travel Rule, making 
anonymous transactions unsuitable for 
regulated markets.106 To address this, token 
standards such as ERC-3643 and ERC-5564 
are emerging. ERC-3643 enables compliant 
transfers based on on-chain identity, while 
ERC-5564 supports privacy through stealth 
addresses and dynamic address generation.107
Tokeny’s DINO protocol uses ERC-3643 to 
facilitate compliant DvD transfers across 
platforms, executing only when both parties 
are KYC-veriﬁed.108 
On-chain identity enforcement often follows 
allow- or deny-list models. Allow-lists enhance 
security but limit inclusivity, while deny-lists are 
more open but require constant monitoring to 
mitigate risks from malicious actors.
Achieving privacy on-chain is not without its 
hurdles and trade-offs. While unlikely, storing 
personal data on-chain raises concerns about 
regulations such as the General Data 
Protection Regulation (GDPR)’s “right to be 
forgotten”.109 Because public networks have 
mixer and tumbler decentralized applications 
that can hide the trail of who sent and received 
crypto (by blending or shufﬂing transactions), 
users can mostly stay anonymous – even 
though wallet addresses are partly visible. 
Another hurdle is quantum-safe PETs, as not 
all PETs are protected against quantum 
attacks, which can break encryptions and leak 
sensitive data. Additionally, compliance with 
the FATF’s Travel Rule is heightened when 
handling tokenized asset transactions, and the 
number of jurisdictions requiring compliance in 
the form of tracking originator and beneﬁciary 
data in an on-chain setting is growing.110
Barriers to adoption
T A B L E  4
Advantages and trade-offs of allow- and deny-list models
MODEL
Allow listing
Deny listing
— Tighter security and control
— Simpliﬁed compliance checks
— Clear accountability and audit trails
— Reduced privacy and anonymity 
(must disclose information)
— High maintenance overhead
— Excludes unlisted (possibly 
legitimate) users
— Reactive approach (must 
constantly update list)
— Bad actors can create new 
identities
— Potential for false positives or 
censorship
— More open and inclusive
— Less friction for onboarding
— Default user privacy preserved
ADVANTAGES
TRADE-OFFS

<!-- Page 41 -->

Contents
41
Impacts of tokenization
Tokenization is catalysing changes across market structures 
and the financial market value chain.
5
Impacts of tokenization

<!-- Page 42 -->

Contents
42
5.1 Evolving market 
structures 
Tokenization will change intermediary roles, not 
eliminate or displace them.111 Reducing 
intermediaries is often hailed as a value driver 
for tokenization; however, reducing or 
eliminating intermediaries is not always 
beneﬁcial, as incumbents provide valuable 
services to maintain safety and soundness. 
For example, Phase 2 of the e-HKD pilot 
demonstrated that intermediaries could act as 
dynamic facilitators of liquidity and trust by 
managing separate liquidity pools for instant 
retail CBDC-to-ﬁat conversion to bridge 
tokenized and traditional systems and ensure 
adoption where tokenized assets are not yet 
widely accepted.112
Market structures – including the buy/sell side 
(e.g. wealth managers, asset managers), 
issuers (e.g. a public government issuing 
securities or a corporation issuing bonds), 
exchanges, CCPs, CSDs, custodians and 
transfer agencies (TAs) – are evolving to adapt 
to tokenization. 
Full disintermediation in regulated ﬁnancial 
markets has been demonstrated 
experimentally. For example, DekaBank 
issued and sold a digital bearer bond without 
intermediaries.113 This should be viewed 
cautiously as intermediaries thwart harmful 
market practices and, instead, markets should 
evaluate the roles of incumbents alongside 
new entrants.
Regulators are advancing the collective 
understanding of enhanced market structures 
through industry initiatives, including the 
United Kingdom’s Digital Securities Sandbox 
and the European Union (EU) Pilot Regime. 
Project Guardian led by the Monetary 
Authority of Singapore also serves as another 
platform for the collaborative design of a 
tokenized value chain.
While the asset life cycle will remain 
unchanged, tokenization reshapes interactions 
among incumbents and digital-native service 
providers to meet new demands for speed, 
efﬁciency and compliance. Incumbent 
responsibilities will likely evolve in parallel with 
the introduction of digital-native market 
structures and service providers, creating a 
platform for product innovation.
5.2 Changes to 
incumbents 
Incumbent responsibilities will expand to offer 
new value propositions.114 For example, 21X 
launched a regulated exchange and settlement 
system on Polygon after being licensed under 
the EU Pilot Regime’s exemptions from CSD 
Regulations and Markets in Financial 
Instruments Directive requirements, allowing 
the integration of a conventional exchange and 
CSD into one smart contract for trading.115
What will remain a constant is the preference 
for trusted intermediaries, particularly where 
centralized services, such as custody and 
regulatory compliance, are critical. 
Buy/sell-side (asset managers, 
wealth managers, brokers/dealers)
The sell-side traditionally handles trade 
execution and client relationships with the buy-
side, while the buy-side manages portfolio 
strategies and client relationships with end 
investors. Tokenization expands their role to 
include reusable digital identity veriﬁcation, 
advising on token portfolios, underwriting 
assistance, automated ordering on digital 
exchanges, on-chain settlements with on-
chain cash, self-custody wallets (e.g. 
Robinhood’s Non-Custodial Wallet) and 
automated rebalancing/yield strategies using 
tokenized platforms. 
Issuers
Issuers are traditionally tasked with capital 
raising and corporate actions, issuers are now 
making use of tokenization for on-chain capital 
formation, automated corporate actions (e.g. 
voting) and programmable asset terms, thus 
enhancing efﬁciency and transparency. Issuers 
often incur underwriting, legal, exchange listing 
and registration fees – all aimed to be 
reduced by tokenization.
Exchanges
Tokenization modernizes exchanges by 
enabling programmable trading restrictions via 
digital identities (e.g. insider trading controls), 
supporting tokenized listings (e.g. Deutsche 
Börse’s digital exchange) and merging 
traditional and decentralized models (e.g. 
AMMs), thereby enhancing compliance and 
market accessibility.
Central counterparties
CCPs mitigate counterparty risk through 
collateral management and trade 
intermediation. In tokenized markets, they 
may evolve into governance-focused entities, 
managing tokenized collateral and cross-chain 
risk via smart contracts.116
Impacts of tokenization

<!-- Page 43 -->

Contents
43
Liquidity centralization – particularly for 
tokenized cash and various stablecoins – 
may become a core function. However, the 
scope of the CCP’s role should be assessed 
contextually. For example, Australia’s Council 
of Financial Regulators concluded that a CCP 
delivers net beneﬁt only when participation 
reaches critical mass to offset its cost 
structure (e.g. margins, fees).117 
Central securities depositories
CSDs manage post-trade functions such 
as record-keeping and corporate actions. 
Complexity and manual processes persist – 
78% of leading ﬁnancial institutions still 
process actions manually.118 CSDs could 
issue assets using veriﬁed digital IDs, manage 
settlement with on-chain cash, validate ledgers 
and automate asset servicing.119 CSDs will 
also provide regulatory compliance, while 
supporting asset tokenization, wallet 
management and interoperability between 
tokenized and traditional systems.120 In the 
Regulated Settlement Network trials, CSDs 
were also identiﬁed as potential immobilization 
providers for multi-asset DvP settlements.121
Custodians
Custodians can evolve into digital asset 
safekeepers, emphasizing multi-tiered 
custody, staking and institutional wallet 
solutions, in addition to acting as a trusted 
intermediary for on- and off-chain integration. 
For example, BNY has expanded its Digital 
Asset Platform to include on-chain data 
services, beginning with broadcasting fund 
accounting data for BlackRock’s tokenized 
fund onto the Ethereum network. This example 
reﬂects how major institutions are adapting 
to the commercialization of tokenized products 
and leveraging data transparency, automation 
and accessibility across the asset life cycle 
while also optimizing the user experience 
for the on-chain native investor.122 
Further, the expected increase in collateral 
velocity will designate custodians as key 
participants in cross-custodial asset 
movements, thus increasing their speed 
of operation while remaining KYC/AML-
compliant. Digital-native custodians are 
acquiring trust charters to facilitate payments, 
access liquidity and bridge traditional and 
crypto-assets.123 In the case of physical 
assets, analogue providers such as gold 
vault services will become integral to 
processes like redemption.
Transfer agencies
TAs manage shareholder registries, cap tables 
and security transfers, often through manual, 
fragmented processes.124 Most TAs use ledger 
software to manage investor data, but these 
systems rely on manual entry, adjustments 
and data sharing with fund administrators, 
alternative trading systems, custodians 
and brokers.125 Tokenization could improve 
their roles by using reusable digital IDs for 
efﬁcient KYC/AML, automating cap table 
services, using programmable ledger 
bookkeeping, conducting direct on-chain 
transfers and programmatically orchestrating 
corporate actions, demonstrated by 
WisdomTree’s tokenized funds and Securrency 
Transfers’ integration.126
TAs can also beneﬁt from more efﬁcient 
KYC checks and repurposable digital IDs, 
as ﬁnancial institutions spend an average 
$2,598 per client onboarded, and TAs often 
verify thousands of investors across dozens 
of countries.127 For example, as momentum 
around tokenized funds builds, the TAs’ role 
could evolve towards a digital transfer agent 
(DTA) model. In this approach, smart 
contracts can be used to maintain share 
registries and automate fund life-cycle 
activities – such as subscriptions and 
redemptions – unlocking greater operational 
efﬁciency, transparency and interoperability 
across blockchain networks.
Impacts of tokenization

<!-- Page 44 -->

Contents
44
F I G U R E  1 6
Market catalysts driving new custodial capabilities
Impacts of tokenization
Market catalysts
New capabilities
Next-gen 
custodianship
Institutional 
productization
Trusted custody 
of native digital 
assets
Custodians will be viewed as the 
trusted safekeepers of digital 
assets, unlocking new products 
and services
Increased 
collateral mobility 
and velocity
More assets can be brought on-
chain and used (and reused) as 
collateral, domestically and cross-
border
Pronounced 
public network 
adoption
Notable uptick in adoption of public 
blockchains by ﬁnancial services 
entities
Unlocked private 
market liquidity
New sources of market activity for 
private assets in primary and 
secondary markets
Quantum attacks 
to break 
encryptions
Risks of network interception, 
identity impersonation and “harvest 
now, decrypt later”
Multitiered 
custody and on-
chain functions
— Cold and hot storage
— Institutional “vaults”
— Retail and segregated wallets
— On-chain corporate actions
— Staking rewards management
— Tokenized collateral management
— Institutional wallet/vault services
— Reusable credentials
— Privacy-enhancing tech
— Off-chain ID data storage
— GDPR compliance
On-chain 
identities 
and KYC/AML 
— Cross-chain integration
— On-chain activity tracking
Network 
integration and 
on-chain 
analytics
— Cryptographic agility
— Quantum-resistant signature 
algorithms
— Novel encryption methods
Quantum-safe 
systems
C A S E  S T U D Y  8
Integration
Click to open
case study details

<!-- Page 45 -->

Contents
45
No major changes anticipated
T A B L E  5
Potential changes to incumbent responsibilities through tokenization
Impacts of tokenization
ENTITY
Buy/sell side
Issuer
(public/private 
sector)
Exchanges
CCPs
CSDs
Custodians
Transfer 
agencies
— Automated, direct ordering via 
new digital asset exchanges
— Peer-to-peer trading on 
secondary markets (e.g. DEXs)
— Hybrid: Traditional orderbooks 
and on-chain transactions (e.g. 
automated market makers)
— Tokenized Assets Advisory
— Underwriting and syndication 
(e.g. UBS Native Digital Bond 
on SDX)
— On-chain ID veriﬁcation via 
repurposable digital identities 
(e.g. JPM Project Epic)
— Smart contract design (e.g. 
asset terms)
— Re-purposable digital identities 
to enforce trading restrictions 
(e.g. insider trading)
— On-chain ID veriﬁcation (e.g. 
SDX's adoption of Digital Token 
Identiﬁer)
— On-chain ID veriﬁcation via 
repurposable digital identities
— Programmable shareholder 
registry updates
— Tokenized and digitally native 
issuance replacing book-entry 
issuance
— Tokenized asset listings (e.g. 
Deutsche Börse Digital 
Exchange)
— Smart contract deployment
— On-chain capital raises
— On-chain cash tokens for 
settlement (e.g. deposit tokens)
— Self-custody brokerage wallets 
(e.g. Robinhood wallet)
— Automated rebalancing and 
yield strategies
— On-chain corporate actions 
(e.g. voting)
— Multilateral governance (e.g. 
Eurex DLT Trials)
— Tokenized margin collateral 
management
— Default management and 
liquidation using on-chain cash
— On-chain cash for settlement
— Node operations and network 
validation
— Automated ownership records
— Updates via distributed ledger
— Cross-chain interoperability
— Digital asset safekeeping
— Digital asset staking
— Private key management
— Institutional wallets/vaults
— Automated dividend 
distributions
— Staking rewards distribution
— Tokenized lending/borrowing 
(e.g. BTC-backed loans)
— Automated cap table services
— Automated, programmatic 
corporate actions (e.g. 
Chainlink, Euroclear, Swift)
— Automated bookkeeping via 
distributed ledger
— Direct on-chain asset transfers
ONBOARDING
ISSUANCE
TRADING
CLEARING/SETTLEMENT
CUSTODY
ASSET SERVICING

<!-- Page 46 -->

Contents
46
5.3 New market roles 
New intermediaries will also support the asset 
life cycle, potentially with more participants 
than conventional setups.128 This research 
found that there may be two new classes 
of entities to support the capabilities needed 
to deliver tokenization at scale: new market 
structures and digital-native service providers. 
Combined, these two groups plus incumbents 
would then drive product development forward 
using tokenization’s features. 
New market structures
New market structures are expected to play 
critical roles across the asset life-cycle steps. 
Token Issuers could provide asset issuance 
services on-chain, including developing and 
deploying token contracts. Once the tokenized 
asset is available, a digital asset exchange 
could offer compatible trading services, driving 
liquidity and market depth. Digital securities 
depositories (DSDs) could be introduced as 
a native service provider on DLT networks 
to perform one or more of the actions typically 
provided by CSDs, including settlement and 
management of securities.129
At least three new digital-native market 
structures are conceivable:
—  Token asset issuers and developers
will create and structure tokenized assets, 
ensuring regulatory compliance and 
embedding programmability to unlock 
new market efﬁciencies. These entities 
will also develop, upgrade and maintain 
the underlying tokenization platform or DLT 
and build digital workﬂows for pre-issuance 
activities, automating various workﬂows 
between parties until deal-closing.130
—  Digital asset custodians will specialize 
in secure cryptographic key storage and 
management, enabling institutional-grade 
custody and access control for tokenized 
assets. In many cases, incumbents will use 
digital asset custodians should they decide 
not to build their own capabilities. 
—  Digital asset exchanges will facilitate 
the trading and liquidity of tokenized 
assets, bridging traditional ﬁnance with 
programmable ledger-based assets.
Digital-native service providers
Digital-native service providers will provide 
solutions for the secure issuance, trading and 
custody of digital assets. The adoption of 
these services by ﬁnancial institutions will 
require licensing and will vary by region. Often, 
incumbents or new market structures will 
employ these services in their delivery of 
tokenized products.
At least ﬁve new digital-native service 
providers are conceivable:
—  On-chain identity providers could 
streamline identity veriﬁcation, but trust in 
third-party issuers remains uncertain, so 
institutions may prefer proprietary KYC 
processes and certiﬁcate authorities are 
more likely than custodians to become 
trusted issuers while liability in transferring 
veriﬁed identities remains unresolved.
—  Interoperability providers could provide 
interoperability services between 
programmable ledgers and conventional 
systems (e.g. ACH, Swift) for settlement. 
—  Node operators could provide resources 
to verify transactions, produce blocks, 
facilitate consensus and update the ledger 
or chain.
—  Key management providers could offer 
specialized custodial services to safekeep 
tokenized assets and help ﬁnancial ﬁrms 
meet compliance measures, including 
BitGo and Metaco (acquired by Ripple).
—  Smart contract auditors could provide 
auditing and monitoring of smart contracts 
to ensure the veriﬁability and safety of the 
deployed contract. 
5.4 New products 
Evolving market structures and the rise of 
digital-native service providers could enable 
the creation of innovative ﬁnancial products 
by facilitating creativity, largely fuelled by 
composability and programmability. These 
advances can unlock new liquidity models, 
risk-free uncollateralized lending and more 
efﬁcient capital markets, reshaping traditional 
ﬁnance with programmable, automated and 
highly composable ﬁnancial primitives. For 
example, as the Bank of Canada explored, 
ﬂash loans native to blockchain ecosystems 
illustrate how uncollateralized lending with zero 
default risk transforms liquidity access for 
sophisticated market participants.131
Additionally, new mechanisms, such as using 
crypto-assets for collateral and smart funding 
– where assets are aggregated and liquidated 
based on payment needs, such as converting 
ETH to ﬁat-backed stablecoins in real time to 
facilitate payments – can further accelerate 
product development.132 
Impacts of tokenization

<!-- Page 47 -->

Contents
47
Design choices
Choices must be made on tokenization’s 
infrastructure, settlement assets and operating hours.
6
Design choices

<!-- Page 48 -->

Contents
48
6.1 Infrastructure 
When different ﬁnancial institutions adopt 
tokenization, they need to decide upon the 
underlying infrastructure. Three models of 
programmable ledgers are presented, two 
permissioned and one permissionless, with 
varying beneﬁts.
Permissioned ledgers
Financial markets have historically used 
private- and public-permissioned 
programmable ledgers because of the native 
functions of control and oversight, which can 
mitigate AML, KYC, legal and fraud risks and 
enable dispute resolution. This environment 
allows for efﬁcient data sharing and secure 
record-keeping, bolstering trust, as only 
approved entities can read or write 
transactions. At the same time, in a 
permissioned setup, broader participation is 
possible but still governed by strict rules of 
entry. For example, JP Morgan’s Kinexys 
platform has processed more than $1.5 trillion 
in notional value since its inception in 2021 by 
offering DLT-based payments, intraday repo 
and collateral services.133 Another example is 
Citi’s Integrated Digital Assets Platform 
(CIDAP), which offers an array of use cases 
across tokenized deposits, trade processing, 
bond exchange and private fund 
tokenization.134
Design choices
T A B L E  6
Key programmable ledger models 
CATEGORY
Description
Transaction 
permissions
Data 
viewability
Governance 
model
Open access: No entry barriers and any user 
with internet access can submit transactions
Restricted access: Participants vetted and 
approved by trusted authorities can submit 
transactions
Controlled transparency: Targeted privacy 
measures feasible (e.g. selective disclosure)
Moderately centralized: Governance through 
permissioned entities who validate the network
Closed and selective entry: Typically, 
enterprises and known counterparties can 
submit transactions
Strict confidentiality: Default conﬁdentiality 
with complete control over data exposure
Highly centralized: Even narrower onboarding 
of permissioned entities to validate the network
Fully transparent by default: Privacy 
achievable through additional tools 
(e.g. ZK proofs)
Highly decentralized: Consensus among 
independent nodes (e.g. proof-of-stake)
Scalability and 
performance
High throughput: Optimized for regulatory 
compliance and institutional transactions
High throughput: Purpose-built for enterprise-
level volume and with predictable performance
Varies significantly: Dependent on consensus 
algorithms (e.g. proof-of-work is not natively 
scalable, while proof-of-stake is scalable)
Compliance 
and regulatory 
alignment
Strong compliance: Designed for regulated 
activities and integration with legacy 
infrastructure
Highest compliance: Explicitly designed for 
internal regulatory adherence, auditability and 
granular control
Minimal by default: Compliance possible but 
requires additional processes or layers
Liquidity and 
market access
Moderate liquidity: Dependent on size and 
inﬂuence of the managing consortium, targeted 
towards institutional-grade asset pools
Variable liquidity: Access tightly controlled but 
can be engineered for high internal liquidity 
within members, suitable for discrete trading
High liquidity: Driven by network effects, 
global participation and interoperability; suitable 
for broadly traded assets and digital currencies
Infrastructure 
requirements
Moderate barrier to entry: Stable, 
predictable operational costs aligned with 
enterprise standards
High barrier to entry: Lowest marginal 
transaction costs; ideal for large, structured 
transactions
Low barrier to entry: Moderate–high 
operational and transaction costs based on 
network fees
PUBLIC-PERMISSIONLESS
PUBLIC-PERMISSIONED
PRIVATE-PERMISSIONED
— Open, decentralized networks where 
anyone can join, transact and validate 
transactions without prior approval
— Ideal for broad participation and innovation 
but with variable performance and limited 
default privacy
— Networks open to selected, vetted 
participants, typically regulated entities
— Blend decentralization with controlled 
governance, providing viewability, high 
performance and regulatory alignment
— Fully controlled and centralized networks 
with restricted access to pre-approved 
participants
— Optimized for high performance, 
conﬁdentiality, regulatory compliance and 
internal institutional use cases

<!-- Page 49 -->

Contents
49
The main challenges associated with 
permissioned ledgers are scalability and 
adoption, although they are likely to succeed 
when ﬁnancial institutions with strong network 
effects operate the platform. However, the 
permissioned or private construct can hinder 
adoption for smaller players. 
Permissionless ledgers
Financial institutions have historically 
approached permissionless networks with 
caution due to regulatory and operational 
concerns. Nevertheless, a clear trend towards 
exploration and adoption is emerging. 
Permissionless networks – open systems 
where anyone can join, access data and 
validate transactions – are increasingly being 
tested and integrated into institutional 
strategies.135 At their core, permissioned and 
permissionless systems differ in governance 
and access. 
There are ﬁve distinct drivers for the 
exploration of permissionless networks:
1. Economic efficiency 
Deploying and operating Layer-1s is 
increasingly cost-effective. Avalanche’s 
9000 upgrade, for instance, cut Layer-1 
deployment costs by 99%.136
2. Developer ecosystems 
Open-source networks such as Ethereum 
and Solana host more than 24,000 active 
developers, accelerating innovation and 
tool development.137
3. Network effects 
Public ledgers promote broader 
participation and distribution, reducing 
single points of failure and aligning with 
user-centric ﬁnancial models.138
4. Transparency and real-time settlement
Open ledgers allow for continuous asset 
veriﬁcation, streamlining operations and 
reducing intermediary reliance.
5. Enhanced transaction performance
Innovations such as Ethereum’s Proto-
Danksharding (EIP-4844) and Solana’s 
speed enhancements have improved 
transaction throughput and costs.139
As of May 2025, ﬁnancial services entities 
are actively using at least 30 permissionless 
programmable ledgers.140 Their adoption is 
expected to grow as various market forces 
drive further use of programmable ledgers. 
Public networks such as Ethereum now 
average 1–1.5 million daily transactions.141
Deutsche Bank is planning a permissioned 
ZK-proof Layer-2 on Ethereum to meet 
compliance requirements, demonstrating 
that compliance on permissionless networks 
does not require platform-wide gatekeeping 
functionalities and this can be enabled at the 
application or asset level.142
Notable institutional deployments include:
—  Franklin Templeton expanded its tokenized 
US Government Money Fund (FOBXX) to 
Avalanche, marking the ﬁrst US-registered 
mutual fund using a public ledger for 
recordkeeping and transactions.143
—  BlackRock launched its BUIDL fund across 
Ethereum and six other public networks: 
Aptos, Arbitrum, Avalanche, Optimism, 
Polygon and Solana.144
These on-chain products operate without 
central clearing parties, signalling a structural 
shift in market infrastructure.
Environmental concerns have diminished. 
The shift from energy-intensive proof-of-work 
(PoW) to efﬁcient proof-of-stake (PoS) 
consensus mechanisms – now the dominant 
model for public-permissionless – has made 
programmable ledgers far more sustainable 
and scalable than in prior cycles.145 The 
longstanding concern of network scalability 
has been put to rest.146
However, there can be challenges associated 
with permissionless ledgers. From a ﬁnancial 
stability perspective, the transparency of 
permissionless programmable ledgers can 
amplify liquidity risks for banks by enabling 
visible transaction ﬂows that may trigger 
withdrawals during stress events. Network 
congestion, low throughput and variable 
fees further delay settlements and can 
undermine liquidity.147
Permissionless networks also face the 
privacy–transparency conundrum – balancing 
open data access with conﬁdentiality.148
Lacking built-in identity veriﬁcation, they 
require external solutions to meet KYC/AML 
requirements, often involving off-chain data 
storage and compliance processes.
Lastly, while programmable ledgers 
enable distributed governance, ﬁnancial 
institutions must ensure that these systems 
align with their mandate to establish clear 
lines of responsibility and business 
continuity, such as reversals and 
maintenance upgrades.149
Design choices

<!-- Page 50 -->

Contents
50
6.2 Settlement assets 
Without reliable on-chain settlement assets, 
using tokenized assets at scale will be 
challenging.150 According to a 2024 survey, 
79% of respondents indicated regulatory 
clarity as the critical dependency for on-chain 
cash.151 The lack of riskless settlement assets 
is a roadblock when considering the BIS 
Committee on Payment and Settlement 
Systems (CPSS)–International Organization of 
Securities Commissions (IOSCO) Principles for 
Financial Market Infrastructures, which state 
that an FMI should conduct its money 
settlements in central bank money where 
practical and available.152 The existence of 
assets and on-chain cash is instrumental to 
achieving operational efﬁciency concerning 
ancillary functions, including coupon 
payments, dividends and interest.153
Institutions and customers risk delays, higher 
costs and compliance uncertainties without 
on-chain cash.
While wCBDCs have undergone lengthy 
development cycles that have slowed 
adoption, a recent OMFIF survey 
demonstrated that 59% of market participants 
prefer wCBDC as the settlement asset for DLT-
based debt issuances.154 Responding to 
market calls from ﬁnancial institutions for 
central bank money for DLT-based settlement, 
the ECB shared its goal of enabling a short-
term solution for this “in months, not years”, 
indicating an acknowledgement of the 
importance of delivering settlement in central 
bank money natively for on-chain 
transactions.155
In addition to central bank money, several 
forms of on-chain cash could be used, 
including ﬁat-backed stablecoins, reserves-
backed digital currency (RBDC) or deposit 
tokens. For example, to enhance its platform, 
Broadridge successfully integrated with 
Fnality’s Payment System (FnPS) – an RBDC 
platform – paving the way for real-time DvP of 
intraday repos with digitally represented funds 
held at central banks.156 By making cash 
accessible and trustworthy, ﬁnancial markets 
can accelerate the responsible adoption of 
tokenized assets.
6.3 Operating hours 
An “always-on” infrastructure is a design 
choice dependent on market demand, risk 
tolerance and technology. Not all markets 
should or could operate on a true 24/7 basis. 
For example, the New York Stock Exchange 
(NYSE) received approval by its regulator to 
expand its operating hours from 16 to 22 
hours, citing a need for a two-hour break for 
system maintenance, central clearing and 
asset servicing functions (coupon payments, 
etc.).157 Expansion of operating hours is a 
technical matter, but also a people, business 
and policy choice that will be dependent on 
time zones, trade matching, liquidity 
management and other functions that enable 
safe trading. Tokenization does offer 
functionality to operate 24/7, as demonstrated 
by the always-on feature of DeFi; however, 
regulated markets operate in a more rigid 
operational construct and will vary on a case-
by-case basis.
Design choices
say regulatory clarity is the key 
dependency for on-chain cash to scale
79%
prefer wCBDC
for DLT-based debt-issuances
59%

<!-- Page 51 -->

Contents
51
Considerations
Considerations
Important considerations include combatting emerging cyberthreats, 
ensuring financial stability and monitoring regulatory developments.
7

<!-- Page 52 -->

Contents
52
7.1 Cybersecurity 
Cybersecurity is paramount in safeguarding 
digital assets, as many crypto-related 
breaches still arise from conventional threats 
rather than lost or compromised private keys. 
Recent high-proﬁle incidents demonstrate that 
phishing, malware and insider attacks remain 
the most prevalent risks. 
For example, in 2025 the Dubai-based crypto-
exchange Bybit was hacked, leading to a loss 
of nearly $1.5 billion in ETH – it is regarded as 
the largest crypto-asset theft to date.158 This 
attack showed that even industry-accepted 
security measures such as multi-signature 
wallets and cold storage are susceptible when 
linked to operational processes and third-party 
services. While speciﬁc to crypto-assets, this 
highlights that regulated digital assets using 
the same technology must thwart 
cybersecurity risks by harmonizing 
cybersecurity measures in congruence with 
traditional ﬁnancial markets.
Although institutional private key security has 
improved through advanced methods such as 
multi-party computation (MPC) and hardware 
security modules (HSM), robust threat 
modelling and protection strategies remain 
vital. Effective private key management 
practices, including secure storage and strict 
access controls, can mitigate fallout even 
when other defences fail. Addressing 
traditional vulnerabilities and novel 
cryptographic threats is essential to protect 
users and institutions.
Quantum computers represents a key threat to 
ﬁnancial systems, and the risk increases with 
tokenized assets as quantum computing can 
render widely used encryption methods 
insecure. Many programmable ledgers are 
prioritizing quantum-resistance on their 
roadmaps; however, a trade-off is introduced 
with the efﬁciency of encryptions versus their 
quantum resistance. There are three types of 
quantum attacks: network interception, 
identity impersonation and “harvest now, 
decrypt later”.159 Design choices can thwart 
this risk, such as cross-chain protocol security, 
secure token transfer mechanisms and 
cryptographic agility.160
Considerations

<!-- Page 53 -->

Contents
53
7.2 Financial stability 
Due to its limited scale, tokenization 
currently poses a minimal risk to ﬁnancial 
stability. However, as adoption grows, the 
Financial Stability Board (FSB) warns of 
vulnerabilities, including liquidity and maturity 
mismatches, leveraged rehypothecation, price 
and quality obscurity from smart contract 
composability, systemic concentration risks 
and operational fragilities stemming from multi-
party collaboration.161
Considerations
7.3 Regulatory 
developments 
A major barrier to large-scale tokenization 
remains the lack of regulatory clarity in digital 
asset markets. However, recent political and 
regulatory shifts suggest growing momentum 
towards a more deﬁned framework. 
Institutional digital asset projects have often 
stalled due to uncertainty regarding the 
permissibility of on-chain products.162
One of the ﬁrst regulatory frameworks that 
clariﬁed the role of tokens and tokenization 
was in Luxembourg. Blockchain Law I (2019) 
recognized DLT as a valid system for securities 
registration and enforceable book transfers. 
Blockchain Law II (2021) permitted DLT-based 
securities issuance accounts. Blockchain 
Law III (2023) conﬁrmed that DLT-held 
securities qualify as ﬁnancial assets under 
collateral regulations, aligning with the EU’s 
DLT Pilot Regime.
Liechtenstein enacted the Token and Trusted 
Technology Service Provider Act (TVTG) in 
2020. This legislation provides a 
comprehensive and technology-neutral 
approach to regulating the token economy, 
addressing civil and supervisory aspects. By 
deﬁning tokens as containers of rights, the 
TVTG enhances regulatory clarity.163
CONTROLLING THE LIMITLESS NATURE OF COMPOSABILITY
Use composability in a manner congruent with safety and soundness and embed 
controls to prevent the limitless creation of wrapped assets per the asset’s risk 
proﬁle and the risk tolerance of relevant parties, such as with the application in 
increasing the velocity of collateral through reuse across multiple trading steps. 
GOVERNING MULTISTAKEHOLDER PROCESSES
Coordinate rules and governance frameworks across all participating parties while 
relying on a neutral third party to mediate disputes or challenges. 
EMBEDDING SMART CONTRACT AUDIT PROCEDURES
Apply rigorous testing procedures associated with smart contract development 
using open-source frameworks and testing tools to minimize risks associated 
with asset composability. 
The FSB highlights several strategies to encourage safe adoption:
EXPLORING NATIVELY ISSUED TOKENS
Explore using natively issued tokenized assets compared to reference asset 
models to minimize challenges associated with liquidity and maturity mismatch, 
driven by managing dual liquidity pools (token and underlying asset). Firms should 
embrace cash on-chain to mitigate maturity mismatch and ensure standard 
settlement windows. 
MITIGATING CONCENTRATION AND CONTAGION RISKS
Promote competition by making markets accessible to smaller players and carefully 
distributing market powers, balance sheets and liquidity.

<!-- Page 54 -->

Contents
54
The newly elected US administration has 
signalled a pro-digital assets stance, which 
indicates progress towards integrating digital 
assets into traditional ﬁnance.164 Hong Kong is 
advancing bond market tokenization, with the 
SFC and HKMA forming a task force to 
develop a roadmap for bond and FX market 
infrastructure, including tokenized issuance 
and trading – marking a key step towards 
institutional adoption of digital assets.165 Lastly, 
in the UK, the Financial Conduct Authority has 
recently pledged to support fund tokenization 
as part of its 2025–2030 goals.166
Source: World Economic Forum
F I G U R E  1 7
Policy and digital asset regulatory developments (2019–2024)
2019
2020
2021
2022
2023
2024
Blockchain Law I: 
Recognized DLT-based 
securities transfers 
(Luxembourg)
Token and Trusted 
Technology Service 
Provider Act (TVTG) 
(Liechtenstein)
Cayman Islands' Virtual 
Asset (Service 
Providers) Act 
(Cayman Islands)
Swiss law amended to 
accommodate DLT 
(Switzerland)
FINMA guidance on 
blockchain and 
ﬁnancial services 
(Switzerland)
Cayman Islands 
Monetary Authority 
guidance 
(Cayman Islands)
Blockchain Law II: 
Enabled DLT-based 
issuance accounts 
(Luxembourg)
UAE VARA established 
in Dubai
(United Arab Emirates)
British Virgin Islands’ 
Virtual Assets Service 
Providers Act
(British Virgin Islands)
UK’s Financial Services 
and Markets Act 2023 
(United Kingdom)
Dubai’s VARA issues 
comprehensive VASP 
framework
(United Arab Emirates)
EU Markets in Crypto-
Assets (MiCA) 
regulation
(European Union)
EU DLT Pilot Regime
(European Union)
Blockchain Law III: DLT 
securities as ﬁnancial 
instruments
(Luxembourg)
MAS updates Payment 
Services Act for digital 
assets
(Singapore)
Considerations

<!-- Page 55 -->

Contents
55
Conclusion
Tokenization can benefit 
financial markets by 
establishing transparency, 
allowing greater ownership 
control, promoting operational 
efficiency, granting greater 
accessibility to investors and 
enabling multi-asset operations.
The differentiators of this technology 
application can help to realize cost and time 
savings for ﬁnancial markets and broaden 
access to investors in capital markets. 
However, achieving these beneﬁts will not 
come without deep public–private 
collaboration on consistent regulations and 
standards, adaptation of market structures 
and value chains, enhanced collateral 
frameworks and safe and sound usage 
of open networks.
Market structures need to evolve to harness 
tokenization’s advantages. Today’s ﬁnancial 
infrastructure is based on centralized 
intermediaries and predeﬁned settlement 
cycles, whereas tokenized markets introduce 
programmability, atomic settlement and the 
potential for “always-on” markets. However, 
despite technological advances, certain 
ﬁnancial operations – including risk 
management, clearing and corporate actions – 
require controlled execution windows to 
maintain stability and mitigate volatility. 
Technological innovation alone does not 
eliminate the operational and regulatory 
realities that underpin market integrity. There 
needs to be a balance between incumbent 
institutions and new industry players from a 
regulatory and market power perspective. 
Ensuring fair market access, open 
interoperability and balanced regulatory 
inﬂuence is critical to preventing any undue 
concentration of power while inspiring 
sustainable growth.
Lack of global standards and regulatory 
fragmentation for tokenization remain a leading 
challenge and policy-makers should update 
ﬁnancial regulations based on the principle 
of technology neutrality to accommodate 
tokenized assets while ensuring enforceability, 
investor protection and risk management. 
The lack of legal clarity around on-chain 
ownership rights and settlement ﬁnality can 
stiﬂe the value proposition of tokenization as 
observed in potential discrepancies associated 
with a shared system of record and uniﬁed 
consensus on the state of an asset.
By implementing new technologies in the 
market infrastructure, it is necessary to ensure 
interoperability, particularly in deﬁning common 
transaction protocols, asset classiﬁcation 
frameworks and reference data models. 
However, complex ﬁnancial processes – 
such as corporate actions – may require 
a phased approach to standardization 
to adapt to jurisdictional differences and 
evolving industry practices.
For tokenized markets to function effectively, 
liquidity providers and market makers should 
be encouraged to participate. Without 
sufﬁcient secondary market depth, tokenized 
assets risk remaining illiquid, limiting their utility 
despite technical advances. Policy-makers 
and ﬁnancial institutions should explore 
mechanisms to encourage market-making 
activities, such as tailored liquidity 
programmes, capital treatment incentives and 
expanding regulatory sandboxes that spur 
institutional participation.
Several stakeholders should make strides to 
facilitate the use of tokenization including 
policy-makers, technology providers and 
ﬁnancial institutions.
By addressing regulatory uncertainty, adapting 
market structures and encouraging 
competitive, liquid markets, tokenization can 
enable an improved global ﬁnancial 
infrastructure. Achieving this vision requires a 
balanced, pragmatic approach that spurs 
innovation while upholding market integrity, 
competition and operational resilience.
Conclusion

<!-- Page 56 -->

Contents
56
Contributors
Lead Authors
Cameron Nili
Executive Fellow, World Economic Forum; 
Digital Assets Strategy Director, Accenture
Sandra Waliczek
Lead, Blockchain and Digital Assets, World 
Economic Forum
Project Leadership
Duane Block
Managing Director, Accenture
John Lee
Managing Director, Accenture
Drew Propson
Head, Technology and Innovation in Financial 
Services, World Economic Forum
Acknowledgements
Steering Committee
Marta Belcher
Chairperson; President, Filecoin Foundation
Duane Block
Managing Director, Accenture  
Dante Disparte
Chief Strategy Ofﬁcer; Head, Global Policy, Circle 
Internet Financial
Denelle Dixon
Chief Executive Ofﬁcer and Executive Director, 
Stellar Development Foundation
Sandy Kaul
Head of Digital Asset & Investor Advisory Services, 
Franklin Templeton Investments
German Soto Sanchez
Chief Strategy Ofﬁcer, Broadridge Financial 
Solutions
Anthony Scaramucci
Founder, SkyBridge Capital
Faryar Shirzad
Chief Policy Ofﬁcer, Coinbase
“Topp” Jirayut Srupsrisopa
Group Chief Executive Ofﬁcer, Bitkub Capital 
Group Holdings
Tom Zschach
Chief Innovation Ofﬁcer, Swift
Working Group 
Mustafa Mert Așkaroğlu
Advisor, Bank for International Settlements 
Innovation Hub, Hong Kong
Mark Attard
Director, Digital Assets & Client Engagement – 
TTS, Citi
Daniela Barbosa
Executive Director, LF Decentralized Trust
Nuntapun Bhensook
Assistant Director, Digital Currency Policy and 
Development Unit, Bank of Thailand
Amy Caruso
Head of Collateral Initiatives, ISDA
Bugra Celik
Director, Digital Assets and Currencies, HSBC
Boon-Hiong Chan
Industry Applied Innovation Lead, Head Securities 
Market & Technology Advocacy, Deutsche Bank
Hugo Coelho
Head of Digital Policy, Centre for Alternative 
Finance, University of Cambridge
Daniel Coheur
Co-Founder and Chief Commercial Ofﬁcer, Tokeny
Ezechiel Copic
Director of Digital Asset Policy, Visa
Matthew Danzig
Managing Director, Technology Investment 
Banking, Lazard Group
Richard Fenner
Director, Government Relations, Euroclear
Conan French
Director, Digital Finance, Institute of International 
Finance
Jon Frost
Head of Innovation and the Digital Economy, 
Bank for International Settlements (BIS)
Tom Duff Gordon
Vice-President International Policy, Coinbase
Aaron Gwak
Founder and Chief Executive Ofﬁcer, Libeara
Darko Hajdukovic
Head of Digital Markets Infrastructure, LSEG
Joann Healy
Director, Capital Markets Marketing, Chainlink 
Labs
Matthew Higgins
Assistant Director – Solution Adoption, ISDA
John Ho
Head of Legal, Financial Markets, Standard 
Chartered Bank
Markus Infanger
Senior Vice-President, Ripple
Candace Kelly
Chief Legal Ofﬁcer, Stellar Development 
Foundation
Nick Kerigan
Head of Innovation, Swift
Contributors

<!-- Page 57 -->

Contents
57
Kathryn Krumpholz
Managing Director, Accenture
Morgan Krupetsky
Head of Institutions & Capital Markets, Ava Labs
Marion Laboure
Managing Director – Macro Strategist, Deutsche 
Bank
Ashley Lannquist
Digital Finance Expert, Digital Advisory Unit, 
International Monetary Fund (IMF)
Xavier Lavayssière
Digital Finance Expert, International Monetary Fund 
Michael Law
Senior Fintech Director, Hong Kong Monetary 
Authority
Kelvin Lee
Co-Founder and Chief Executive Ofﬁcer, Alta 
Alternative Investments
Stephanie Lheureux
Head of Digital Asset Excellence Centre, Euroclear
Gordon Liao
Chief Economist; Head, Research, Circle Internet 
Financial
Katie Mitchell
International Policy, Coinbase
Katey Neate
Managing Director, Global Head of Investor 
Solutions, BNY
Prakash Neelakantan
Vice-President – Blockchain Strategy, Broadridge 
Financial Solutions
Kamila Nigmatulina
Research Fellow, University of Oxford
Bénédicte Nolens
Head, BIS Innovation Hub Hong Kong Center, 
Bank of International Settlements
Karen L. Ottoni
Senior Director, Ecosystem, LF Decentralized Trust
Christine Parlour
Professor and Chair, Finance and Accounting, 
Haas School of Business, University of California, 
Berkeley
Jack Pouderoyen
Strategy and Innovation, Swift
Stratos Pourzitakis
Head of Digital Policy Asia Paciﬁc, HSBC Group 
Public Affairs
Archie Giridhar Ravishankar
Co-Founder and Chief Executive Ofﬁcer, Cogni
Jessica Renier
Managing Director, Digital Finance, Institute of 
International Finance
Nilmini Rubin
Chief Policy Ofﬁcer, Hedera Hashgraph
Rajeev Sambyal
Head of Digital Cash, BNY
Nischint Sanghavi
Head of Digital Currencies – AP, VISA
Nicole Semenov
Senior Analyst, Accenture
Dinesh Shah
Director, Fintech Research, Bank of Canada
David Shone
Senior Director, Data & Digital Solutions, ISDA
Aditya Kumar Sinha
Head – Fintech & Digital Innovation, Financial 
Services Sector, Qatar Financial Centre Authority
Lukasz Szpruch
Director, The Alan Turing Institute
Pallavi Thakur
Director, CBDC and Interoperability, Swift
Wee Kee Toh
Global Head of Business Architecture for Onyx 
Coin Systems, JP Morgan
Michael Treagus
Senior Analyst, Accenture
Christiaan Van der Weerd
Senior Governmental Affairs Advisor, UBS
Matthew Van Niekerk
Founder and Chief Executive Ofﬁcer, SettleMint NV
Adhish Vyas
Senior Director, Product Management, Blockchain, 
Crypto and Digital Currencies, PayPal
Alice Wang
Managing Director, Strategic Growth Ofﬁce and 
International Consumer Wealth, JP Morgan
Heng Wang
Professor of Law and Associate Dean (Faculty 
Matters & Research), Yong Pung How School of 
Law, Singapore Management University
Joy Wann
Vice-President, Regulatory Affairs Advocacy at 
Mastercard, Mastercard International
Clinton Wilhight
Consultant, Accenture
Srikant Yennamandra
Managing Director, Accenture
Bryan Zheng Zhang
Executive Director and Co-Founder, Cambridge 
Centre for Alternative Finance, Cambridge Judge 
Business School, University of Cambridge
Zhijun William Zhang
Adviser, Bank for International Settlements (BIS)
Matt Zimmermann
General Counsel, Filecoin Foundation
Xiaonan Zou
Executive Director, Center of Expertise; Lead, 
Digital Currency; Head, Digital Asset Treasury, UBS
Contributors
Production
Bianca Gay-Fulconis
Designer, 1-Pact Edition
Tanya Korniichuk
Designer, 1-Pact Edition
Alison Moore
Editor, Astra Content

<!-- Page 58 -->

Contents
58
Endnotes
1. 
World Economic Forum. (2024). Modernizing ﬁnancial markets with wholesale central bank digital currency (wCBDC). 
https://www.weforum.org/publications/modernizing-ﬁnancial-markets-with-wcbdc/; Mandeng, O. J. (2022, March 
23). The (R)evolution of money III CBDC is here, careful design needed now. Accenture. https://www.accenture.com/
us-en/insights/blockchain/evolution-money; Bindseil, U., Pantelopoulos, G., & Coste, C.-E. (2024, November 2). 
Digital money and ﬁnance: A critical review of terminology. SSRN. https://ssrn.com/abstract=5007868 
2. 
Lavayssière, X. (2024, April 17). The design of programmable ledgers. SSRN. https://ssrn.com/abstract=4797032 
3. 
World Economic Forum. (2024). Modernizing ﬁnancial markets with wholesale central bank digital currency (wCBDC). 
https://www.weforum.org/publications/modernizing-ﬁnancial-markets-with-wcbdc/
4. 
Lavayssière, X. (2023, November 23). Tokenization of ﬁnancial assets. SSRN. https://ssrn.com/abstract=4649162
5. 
World Economic Forum. (2024). Modernizing ﬁnancial markets with wholesale central bank digital currency (wCBDC). 
https://www.weforum.org/publications/modernizing-ﬁnancial-markets-with-wcbdc/
6. 
Coinbase Institute. (2024). Why the future of ﬁnance calls for a permissionless architecture. https://assets.ctfassets.
net/o10es7wu5gm1/3DPt8YOiYtdVfqUoeuAJdS/33b4c368f7bc6b4ff7173df36c3d00da/Davos_Whitepaper_A4.pdf
7. 
Bank for International Settlements. (2024, October 21). Tokenisation in the context of money and other assets: 
Concepts and implications for central banks. https://www.bis.org/cpmi/publ/d225.htm; European Commission: 
Directorate-General for Financial Stability, Financial Services and Capital Markets Union, & Schär, F. (2024). 
Enhancing ﬁnancial services with permissionless blockchains, Publications Ofﬁce of the European Union, https://data.
europa.eu/doi/10.2874/8306042; Disparte, D., & Liao, G. (2024, October 28). “Code as law”: The tokenization of 
ﬁnancial assets and the paradox of programmability. World Economic Forum. https://www.weforum.org/agenda/
2024/10/tokenization-ﬁnancial-assets-crypto-programmable-paradox/; Lavayssière, X., & Zhang, N. (2024). 
Programmability in payment and settlement. IMF Working Papers, 2024 (177). https://doi.org/
10.5089/9798400286452.001
8. 
European Central Bank. (2021). The use of DLT in post-trade processes. https://www.ecb.europa.eu/pub/pdf/other/
ecb.20210412_useofdltposttradeprocesses~958e3af1c8.en.pdf
9. 
Disparte, D., & Liao, G. (2024, October 28). “Code as law”: The tokenization of ﬁnancial assets and the paradox of 
programmability. World Economic Forum. https://www.weforum.org/stories/2024/10/tokenization-ﬁnancial-assets-
crypto-programmable-paradox/
10. 
Securities Industry and Financial Markets Association. (2024). Capital markets fact book. https://www.sifma.org/
resources/research/statistics/fact-book/
11. 
Blockworks Research. (2025, March 24). The value of tokenized publicly traded stocks is currently below $16M. 
https://x.com/blockworksres/status/1902449278116868188
12. 
World Federation of Exchanges. (2024, June 11). Demystifying tokenisation: Dispelling myths, explaining the muted 
traction, and setting out the starting point for regulation. https://www.world-exchanges.org/news/articles/
demystifying-tokenisation-dispelling-myths-explaining-muted-traction-and-setting-out-starting-point-regulation
13. 
Tokenized Asset Coalition. (2024, September 26). State of tokenization 2024. https://www.rwa.xyz/blog/tokenized-
asset-coalition-state-of-tokenization-2024
14. 
Garcia, O., & Lillis, S. (2025). Elevating the exchange: Your guide to bringing digital infrastructure to the next level.
Accenture. https://www.accenture.com/content/dam/accenture/ﬁnal/accenture-com/document-3/Accenture-Future-
Of-Exchanges-Report.pdf
15. 
Sanati, A., & Spyridopoulos, I. (2024, December 11). Comparing capital allocation efﬁciency in public and private 
equity markets. SSRN. http://dx.doi.org/10.2139/ssrn.4403578
16. 
Depository Trust & Clearing Corporation. (2023). Automating the sourcing of corporate actions announcements from 
agents and issuers: A DTCC position paper to the industry. https://www.dtcc.com/-/media/Files/Downloads/
WhitePapers/Agent-Interaction-WP-2023-Final.pdf; The ValueExchange. (n.d.). Reimagining corporate actions: What 
is the right operating model for today's world? Retrieved April 14, 2025, from https://thevx.io/campaign/reimagining-
corporate-actions/
17. 
Whittaker, M. (2023, October 2). American depositary receipts: Pros and cons. US News & World Report. https://
money.usnews.com/investing/articles/american-depositary-receipts-pros-and-cons
18. 
Godbole, O. (2024, December 12). Assetera enables non-US investors to trade tokenized Nvidia, Coinbase, and S&P 
500. CoinDesk. https://www.coindesk.com/markets/2024/12/12/assetera-enables-non-u-s-investors-to-trade-
tokenized-nvidia-coinbase-and-s-and-p-500
19. 
State Street Global Advisors. (2024). Digital digest December 2024: Tokenization and the future. https://www.
statestreet.com/us/en/asset-manager/insights/digital-digest-december-2024-tokenization-and-future
20. 
RBC Wealth Management. (n.d.). What are ﬁxed income securities? Retrieved April 14, 2025, from https://www.
rbcwealthmanagement.com/en-ca/insights/what-are-ﬁxed-income-securities
21. 
Securities Industry and Financial Markets Association. (2024). Capital markets fact book. https://www.sifma.org/
resources/research/statistics/fact-book/
22. 
Ofﬁcial Monetary and Financial Institutions Forum (OMFIF). (2024). Digital assets 2024. https://www.omﬁf.org/
da2024/
23. 
Ledger Insights. (2024, November 26). EIB issues second €100m digital bond in a week using wCBDC. https://www.
ledgerinsights.com/eib-issues-second-e100m-digital-bond-in-a-week-using-wcbdc/
24. 
Vanguard. (n.d.). Revalidating the case for international bonds. Retrieved April 14, 2025, from https://institutional.
vanguard.com/insights-and-research/perspective/revalidating-the-case-for-international-bonds.html
25. 
UK Finance. (2024, November). Digital gilt roadmap 2024. https://www.ukﬁnance.org.uk/system/ﬁles/2024-11/
UK%20Finance%20Digital%20Gilt%20roadmap%202024.pdf
Endnotes

<!-- Page 59 -->

Contents
59
26. 
Commodity Futures Trading Commission. (2024, November 21). CFTC’s Global Markets Advisory Committee 
advances recommendation on tokenized non-cash collateral [Press release]. https://www.cftc.gov/PressRoom/
PressReleases/9009-24
27. 
US Department of the Treasury. (2024, October 29). Minutes of the meeting of the Treasury Borrowing Advisory 
Committee October 29, 2024 [Press release]. https://home.treasury.gov/news/press-releases/jy2699
28. 
Government of the Hong Kong Special Administrative Region. (2025, February 26). The 2025–26 budget: Speech by 
the Financial Secretary, the Hon Paul MP Chan. https://www.budget.gov.hk/2025/eng/pdf/e_budget_speech_2025-
26.pdf
29. 
Société Générale. (2023, December 4). Société Generale issues a ﬁrst digital green bond on a public blockchain
[Press release]. https://www.societegenerale.com/en/news/press-release/ﬁrst-inaugural-digital-green-bond-public-
blockchain
30. 
Nomura Holdings. (2025, March 14). Nomura to announce fourth quarter and full year operating results on April 25. 
https://www.nomuraholdings.com/news/nr/nsc/20250314/20250314.html
31. 
SIX Group. (2024, May 21). SIX Digital Exchange hits milestone with over 1 billion Swiss francs in digital assets on 
their platform. https://www.six-group.com/en/newsroom/media-releases/2024/20240521-six-sdx-digital-bonds-
milestone.html
32. 
International Capital Market Association. (2022, September 22). FAQs on DLT & blockchain in bond markets. https://
www.icmagroup.org/assets/ICMA-DLT-and-blockchain-in-bond-markets-FAQ-220922.pdf
33. 
Hong Kong Monetary Authority. (2023, November 28). An assessment on the beneﬁts of bond tokenisation [Research 
Memorandum 04/2023]. https://www.hkma.gov.hk/media/eng/publication-and-research/research/research-
memorandums/2023/RM04-2023.pdf
34. 
In the case of the Olam/Temasek bond issuance (DLT in the Real World podcast series from the ValueExchange and 
ISSA).
35. 
In the case of HKMA’s Evergreen bond issuance (DLT in the Real World podcast series from the ValueExchange and 
ISSA).
36. 
S&P Global. (2024). Private equity. https://www.spglobal.com/en/research-insights/market-insights/private-markets/
private-equity
37. 
Citigroup. (2023). Securities services evolution 2023. https://www.citigroup.com/global/insights/securities-services-
evolution-2023
38. 
Sanati, A., & Spyridopoulos, I. (2024, December 11). Comparing capital allocation efﬁciency in public and private 
equity markets. SSRN. http://dx.doi.org/10.2139/ssrn.4403578
39. 
Opalesque. (2022, March 30). Fund managers believe alternative asset classes are ﬁrst in line for tokenization. https:/
/www.opalesque.com/industry-updates/6722/fund-managers-believe-alternative-asset-classes-are-ﬁrst.html
40. 
Lee, A. H. (2021, October 12). Going dark: The growth of private markets and the impact on investors and the 
economy. https://www.sec.gov/newsroom/speeches-statements/lee-sec-speaks-2021-10-12
41. 
ADDX. (2021, September 28). ADDX tokenises global private equity fund to broaden investor access [Press release]. 
https://www.addx.co/ﬁles/News_Release_ADDX_Tokenises_Global_Private_Equity_Fund_To_Broaden_Investor_
Access_9dd94ed325.pdf
42. 
Zoniqx. (2024, October 23). Aurum Equity Partners launches $1B tokenized equity and debt fund using Zoniqx and 
XRP Ledger technology. https://www.zoniqx.com/resources/aurum-equity-partners-launches-1b-tokenized-equity-
and-debt-fund-using-zoniqx-and-xrp-ledger-technology
43. 
Farrell, M. (2025, March 26). Want to invest in a private company? All it takes is $5,000. The Wall Street Journal. 
https://www.wsj.com/ﬁnance/investing/investing-private-companies-equityzen-forge-global-d2713c5c?
mod=djem10point
44. 
Cai, F., & Haque, S. (2024, February 23). Private credit: Characteristics and risks. Board of Governors of the Federal 
Reserve System. https://www.federalreserve.gov/econres/notes/feds-notes/private-credit-characteristics-and-risks-
20240223.html
45. 
Alternative Investment Management Association. (2024, November 21). Private credit market surpasses US$3trn and 
maintains resilience despite growing stress [Press release]. https://www.aima.org/article/press-release-private-credit-
market-surpasses-us-3trn-and-maintains-resilience-despite-growing-stress.html
46. 
Global Digital Finance. (2024, April). Private debt “will be ﬁrst asset class to be tokenized and routinely traded”.
https://www.gdf.io/resources/private-debt-will-be-ﬁrst-asset-class-to-be-tokenized-and-routinely-traded/
47. 
S&P Global. (2024). Private credit. https://www.spglobal.com/en/research-insights/market-insights/private-markets/
private-credit
48. 
Pokorny, Z. (2025, April 14). The state of crypto lending. Galaxy. https://www.galaxy.com/insights/research/the-state-
of-crypto-lending/
49. 
S&P Global. (2024). Tokenized private credit. https://www.spglobal.com/en/research-insights/special-reports/
tokenized-private-credit
50. 
Gottfried, M. (2022, September 13). KKR makes piece of PE fund available on public blockchain. The Wall Street 
Journal. https://www.wsj.com/articles/kkr-makes-piece-of-pe-fund-available-on-public-blockchain-11663014955
51. 
Dune Analytics. (n.d.). Query dashboard: Tokenized asset performance. Retrieved April 14, 2025, from https://dune.
com/nifty0x/rwa#onchain-loans-for-rwa
52. 
Yieldstreet. (2024, February 11). Understanding real estate asset classes and property types. https://www.yieldstreet.
com/resources/article/understanding-real-estate-asset-classes-and-property-types/#:
~:text=Residential%20property%20is%20real,the%20real%20estate%20asset%20class.
53. 
Tostevin, P., & Rushton, C. (2023, September). Total value of global real estate: Property remains the world’s biggest 
store of wealth. Savills. https://www.savills.com/impacts/market-trends/the-total-value-of-global-real-estate-property-
remains-the-worlds-biggest-store-of-wealth.html
54. 
Boston Consulting Group. (2022). Relevance of on-chain asset tokenization in “crypto winter”. https://web-assets.
bcg.com/1e/a2/5b5f2b7e42dfad2cb3113a291222/on-chain-asset-tokenization.pdf 
Endnotes

<!-- Page 60 -->

Contents
60
55. 
Cornell SC Johnson College of Business. (2024). Tokenization of real-world assets report. https://business.cornell.
edu/wp-content/uploads/sites/2/2025/02/Cornell_Convenes_Roundtable_Report_Tokenization_of_Real-World_
Assets_FINAL_2.3.25_VD_.pdf
56. 
CFA Institute. (2025). Introduction to commodities and commodity derivatives. https://www.cfainstitute.org/insights/
professional-learning/refresher-readings/2025/introduction-commodities-commodity-derivatives
57. 
Statista. (2025). Commodities – worldwide. https://www.statista.com/outlook/fmo/commodities/worldwide
58. 
World Gold Council. (2023). Gold market primer: Market size and structure. https://www.gold.org/goldhub/research/
market-primer/gold-market-primer-market-size-and-structure
59. 
Canton Network. (n.d.). Unlocking collateral mobility through tokenization: Gilts, eurobonds and gold. Retrieved April 
14, 2025, from https://www.canton.network/unlocking-new-collateral-pools-and-24x7-mobility
60. 
LBMA. (2023). Tokenisation of precious metals: Challenges and blind spots. https://www.lbma.org.uk/alchemist/
alchemist-111/tokenisation-of-precious-metals-challenges-and-blind-spots
61. 
Morgan Stanley Capital International. (2025). Frozen carbon credit market may thaw as 2030 gets closer. https://
www.msci.com/www/blog-posts/frozen-carbon-credit-market-may/05232727859
62. 
Deloitte. (2022). Accounting and reporting considerations for environmental credits. https://www2.deloitte.com/
content/dam/Deloitte/us/Documents/audit/us-accounting-and-reporting-considerations-for-environmental-credits-
2024.pdf
63. 
World Economic Forum. (2024, September 6). Why the voluntary carbon market is key to scaling carbon dioxide 
removal and delivering net-zero. https://www.weforum.org/stories/2024/09/voluntary-carbon-market-carbon-dioxide-
removal-net-zero/
64. 
PwC. (2024, May 1). Carbon credit tokenization. https://www.pwc.com/m1/en/publications/carbon-credit-
tokenization.html
65. 
CDR.fyi. (2024, February 7). 2023 year in review. https://www.cdr.fyi/blog/2023-year-in-review
66. 
Blaufelder, C., Levy, C., Mannion, P., & Pinner, D. (n.d.). A blueprint for scaling voluntary carbon markets to meet the 
climate challenge. McKinsey & Company. Retrieved April 14, 2025, from https://www.mckinsey.com/capabilities/
sustainability/our-insights/a-blueprint-for-scaling-voluntary-carbon-markets-to-meet-the-climate-challenge
67. 
ACX. (n.d.). ACX: Carbon exchange. Retrieved April 14, 2025, from https://acx.net/
68. 
Mastercard. (2024). Mastercard, Standard Chartered, Mox and Libeara successfully complete a proof-of-concept 
pilot on tokenized deposits and tokenized carbon credits through regulatory sandbox. https://www.mastercard.com/
news/aq/en/newsroom/press-releases/en/2024/mastercard-standard-chartered-mox-and-libeara-successfully-
complete-a-proof-of-concept-pilot-on-tokenized-deposits-and-tokenized-carbon-credits-through-regulatory-sandbox
69. 
Gray, M. (n.d.). Standardizing sustainability: How the IWA will make this happen. InterWork Alliance. Retrieved April 
14, 2025, from https://interwork.org/standardizing-sustainability-how-the-iwa-will-make-this-happen/
70. 
European Commission. (n.d.). Securities ﬁnancing transactions (SFTs). Retrieved April 14, 2025, from https://ﬁnance.
ec.europa.eu/capital-markets-union-and-ﬁnancial-markets/ﬁnancial-markets/post-trade-services/securities-ﬁnancing-
transactions-sfts_en
71. 
Securities Finance Times. (n.d.). Collateral supply, demand and mobility. Retrieved April 14, 2025, from https://www.
securitiesﬁnancetimes.com/specialistfeatures/specialistfeature.php?specialist_id=802#:
~:text=Collateral%20supply%2C%20demand%20and%20mobility%20are%20all%20factors%20inﬂuencing%20the,
US$25%20trillion%20in%20size
72. 
Wells, D. (2024, March 12). The future of repo transactions: How tokenization is reshaping the industry. Kaleido. 
https://www.kaleido.io/blockchain-blog/repo-tokenization
73. 
GFMA. (2023). Impact of distributed ledger technology in global capital markets. https://www.gfma.org/wp-content/
uploads/2023/05/impact-of-dlt-on-global-capital-markets-full-report.pdf
74. 
Euroclear. (2025, February 25). Euroclear & Digital Asset to mobilise collateral assets. https://www.euroclear.com/
newsinsights/en/Press/2025/mr-09-digital-asset-and-euroclear.html
75. 
Allen & Overy Shearman. (n.d.). The Fuse podcast: Distributed ledger technology and collateral mobility. Retrieved 
April 14, 2025, from https://www.aoshearman.com/en/insights/the-fuse-podcast-distributed-ledger-technology-and-
collateral-mobility
76. 
Federal Reserve Bank of New York. (n.d.). Repo and reverse repo agreements. Retrieved April 14, 2025, from https://
www.newyorkfed.org/markets/domestic-market-operations/monetary-policy-implementation/repo-reverse-repo-
agreements
77. 
International Capital Market Association. (n.d.). 4. How big is the repo market? Retrieved April 14, 2025, from https://
www.icmagroup.org/market-practice-and-regulatory-policy/repo-and-collateral-markets/icma-ercc-operations/
frequently-asked-questions-on-repo/4-how-big-is-the-repo-market/
78. 
Gardia, O. (2025, February 12). Elevating the exchange. Accenture. https://www.accenture.com/cr-en/insights/
capital-markets/elevating-exchange
79. 
Canton Network. (n.d.). Unlocking collateral mobility through tokenization: Gilts, Eurobonds and gold. Retrieved April 
14, 2025, from https://www.canton.network/unlocking-new-collateral-pools-and-24x7-mobility
80. 
SDX. (n.d.). SDX launches new service to transform crypto collateral management. Retrieved April 14, 2025, from 
https://www.sdx.com/news/crypto-collateral-management/
81. 
Broadridge Financial Solutions. (n.d.). Distributed ledger repo solutions. Retrieved April 14, 2025, from https://www.
broadridge.com/ﬁnancial-services/capital-markets/transform-trade-life-cycle/distributed-ledger-repo
82. 
RWA.xyz. (n.d.). Tokenized treasuries. Retrieved April 14, 2025, from https://app.rwa.xyz/treasuries
83. 
Avalanche. (n.d.). Franklin Templeton launches tokenized money market fund BENJI on the Avalanche network. 
Retrieved April 14, 2025, from https://www.avax.network/blog/franklin-templeton-launches-tokenized-money-market-
fund-benji-avalanch
Endnotes

<!-- Page 61 -->

Contents
61
84. 
Allison, I. (2024, June 10). Fidelity International tokenizes money market fund on JPMorgan’s blockchain. CoinDesk. 
https://www.coindesk.com/business/2024/06/10/ﬁdelity-international-tokenizes-money-market-fund-on-jpmorgans-
blockchain/
85. 
Apex Group. (2025, January 21). Fasanara launches tokenized money market fund on Polygon. https://www.
apexgroup.com/insights/fasanara-launches-tokenized-money-market-fund-on-polygon/
86. 
Johnson, S. (2024, March 3). Crypto ETFs set to trump precious metals peers, says State Street. Financial Times.
https://www.ft.com/content/2c1f4a84-1f3b-4d97-85e8-6adc957c4161
87. 
Reuters. (2025, February 21). Franklin Templeton ﬁles for Solana ETF as crypto interest expands beyond bitcoin. 
https://www.reuters.com/technology/franklin-templeton-ﬁles-solana-etf-crypto-interest-expands-beyond-bitcoin-
2025-02-21/
88. 
Swift. (2024, November 5). Swift, UBS Asset Management, and Chainlink successfully complete innovative pilot to 
bridge tokenized assets with existing payment systems. https://www.swift.com/news-events/press-releases/swift-
ubs-asset-management-and-chainlink-successfully-complete-innovative-pilot-bridge-tokenized-assets-existing-
payment-systems
89. 
La Salla, F. (2024, January 16). Why standards and controls are essential to the future of ﬁnancial assets. World 
Economic Forum. https://www.weforum.org/stories/2024/01/digital-ﬁnancial-markets-developing-standards-controls-
davos24/
90. 
International Securities Services Association. (2023, July). DLT in the real world survey 2023 – key ﬁndings. https://
issanet.org/content/uploads/2023/07/DLT-in-the-Real-World-2023_Survey-Key-Findings.pdf
91. 
Plepi, A., & Schwender, P. (2024, November 11). A method for uncovering tokenisation archetypes and their effects: 
Thus spoke Switzerland. SSRN. https://ssrn.com/abstract=5017084
92. 
Swift. (n.d.). Unlocking the potential of digital asset securities. Retrieved April 14, 2025, from https://www.swift.com/
campaign/unlocking-potential-digital-asset-securities
93. 
Nethermind & PwC. (2025, February). Tokenization standards: The missing link for institutional adoption. https://cdn.
pod.website-ﬁles.com/63bcd69729ab7f3eac1d210/c6748c00035fe2c75f6de6b_Tokenization_Standards_The_
Missing_Link_for_Institutional_Adoption_Nethermind_PwC.pdf
94. 
Accenture, Chainlink, & RWA.xyz. (2025, forthcoming). Liquidity without borders: Why cross-chain interoperability 
matters.
95. 
LayerZero. (n.d.). LayerZero V2 OFT quickstart. Retrieved April 14, 2025, from https://docs.layerzero.network/v2/
developers/evm/oft/quickstart
96. 
Organisation for Economic Co-operation and Development. (2025, January 9). Tokenisation of assets and distributed 
ledger technologies in ﬁnancial markets: Potential impediments to market development and policy implications. 
OECD Business and Finance Policy Papers, No. 75. OECD Publishing, Paris. https://doi.org/10.1787/40e7f217-en
97. 
Wang, C. (2023). Trading securities as digital tokens: Is a secondary market practicable for tokenized exempt 
securities? University of New Hampshire Law Review, 22, 39. https://scholars.unh.edu/unh_lr/vol22/iss1/3
98. 
The ValueExchange. (n.d.). DLT and digital assets. Retrieved April 14, 2025, from https://thevx.io/campaign/dlt-and-
digital-assets/
99. 
Fintech at Cornell. (2025). Cornell convenes 2024 roundtable forum: Tokenization of real-world assets. https://
business.cornell.edu/wp-content/uploads/sites/2/2025/02/Cornell_Convenes_Roundtable_Report_Tokenization_of_
Real-World_Assets_FINAL_2.3.25_VD_.pdf
100. SIX Group. (2022, November 3). UBS launches world's ﬁrst native digital bond with intended dual listing and trading 
on SIX Digital Exchange and SIX Swiss Exchange [Press release]. https://www.six-group.com/en/newsroom/media-
releases/2022/20221103-sdx-ubs-bond.html 
101. JP Morgan. (2024, November 6). Project EPIC: Fueling tokenized ﬁnance with on-chain enterprise privacy, identity 
and composability. https://www.jpmorgan.com/kineyx/content-hub/project-epic-enterprise-privacy-identity-
composability
102. Westin, A. (1967). Privacy and freedom. Washington and Lee Law Review, 25(1). https://scholarlycommons.law.wlu.
edu/wlulr/vol25/iss1/20/; MIT Digital Currency Initiative. (2024). Enhancing the privacy of a digital pound. https://dci.
mit.edu/enhancing-the-privacy-of-a-digital-pound
103. Financial Action Task Force. (2025, February). The FATF Recommendations. https://www.fatf-gaﬁ.org/content/dam/
fatf-gaﬁ/recommendations/FATF%20Standard%20-%2040%20Recommendations%20crc.pdf
104. BIS. (n.d.). Project Aurum 2.0: Improving privacy for retail CBDC payment. Retrieved April 22, 2025, from https://
www.bis.org/about/bish/topics/cbdc/aurum_2_0.htm
105. Digital Dollar Project. (2023). Secure adoption of a digital dollar: Operational and compliance risks for the US banking 
sector. https://digitaldollarproject.org/wp-content/uploads/2023/06/Risk-Working-Paper_Secure-Adoption-of-a-
Digital-Dollar.pdf; Chainalysis. (2022). The 2022 crypto crime report. https://go.chainalysis.com/rs/503-FAP-074/
images/Crypto-Crime-Report-2022.pdf
106. Citigroup. (2004, December 2). Ready layer 1: A general-purpose state machine for the ﬁnancial sector. https://www.
citigroup.com/global/insights/ready-layer-1-a-general-purpose-state-machine-for-the-ﬁnancial-sector
107. Dev, A., & Buterin, V. (2022). ERC-5564: Stealth addresses. Ethereum Improvement Proposals. https://eips.
ethereum.org/EIPS/eip-5564
108. Tokeny. (n.d.). DINO: Distribute digital securities globally and compliantly. Retrieved April 14, 2025, from https://
tokeny.com/dino/
109. ERC3643 Association. (n.d.). ERC3643 – the token standard for RWA tokenization. Retrieved April 14, 2025, from 
https://www.erc3643.org/
110. Global Blockchain Business Council. (2024). The Dawn of Travel Rule with Notabene. YouTube. https://www.youtube.
com/watch?v=PzCQan0XLuI
111. Carstens, A., & Nilekani, N. (2024). Finternet: The ﬁnancial system for the future. Bank for International Settlements. 
BIS Working Papers No. 1178. https://www.bis.org/publ/work1178.htm
Endnotes

<!-- Page 62 -->

Contents
62
112. Hong Kong Monetary Authority. (2024, September 23). HKMA commences Phase 2 of -HKD Pilot Programme and 
expands Project e-HKD to explore new forms of digital money [Press release]. https://www.hkma.gov.hk/eng/news-
and-media/press-releases/2024/09/20240923-3/
113. Ledger Insights. (2024). DekaBank issues digital bond without intermediaries, as part of ECB DLT settlement trials. 
https://www.ledgerinsights.com/dekabank-issues-digital-bond-without-intermediaries-as-part-of-ecb-dlt-settlement-
trials/
114. Coinbase Institute. (2024). Why the future of ﬁnance calls for a permissionless architecture. https://assets.ctfassets.
net/o10es7wu5gm1/3DPt8YOiYtdVfqUoeuAJdS/33b4c368f7bc6b4ff7173df36c3d00da/Davos_Whitepaper_A4.pdf
115. Ledger Insights. (2024). 21X lands ﬁrst license for exchange, settlement under DLT Pilot Regime. https://www.
ledgerinsights.com/21x-lands-ﬁrst-license-for-exchange-settlement-under-dlt-pilot-regime/
116. Eurex. (2024, October 23). Eurex Clearing successfully participates in ECB trials for wholesale digital money pilot. 
https://www.eurex.com/ex-en/ﬁnd/news/Eurex-Clearing-successfully-participates-in-ECB-trials-for-wholesale-digital-
money-pilot--4151738
117. Council of Financial Regulators. (2025, March). Reassessing the case for central clearing of bonds and repos in 
Australia: Response to consultation. https://www.cfr.gov.au/publications/consultations/2025/reassessing-the-case-
for-central-clearing-of-bonds-and-repos-in-australia/
118. SIX Group. (2021, September 8). New SIX survey: Urgent need for better quality data to automate corporate actions
[Press release]. https://www.six-group.com/en/newsroom/media-releases/2021/20210908-corporate-actions-survey.
html 
119. OMFIF. (2024, September 27). Success of tokenisation will depend on the private sector. https://www.omﬁf.org/
2024/09/success-of-tokenisation-will-depend-on-the-private-sector/
120. DTCC. (n.d.). CSDs drive the shift to blockchain & tokenized assets. Retrieved April 14, 2025, from https://www.dtcc.
com/digital-assets/digital-standard/csds-in-focus
121. Securities Industry and Financial Markets Association. (2024, December 5). RSN business applicability report. https://
www.sifma.org/wp-content/uploads/2024/12/RSN-Business-Applicability-Report-FINAL.pdf
122. BNY. (2025, April 3). BNY expands digital asset platform with launch of innovative on-chain offering. https://www.bny.
com/corporate/global/en/about-us/newsroom/press-release/bny-expands-digital-asset-platform-with-launch-of-
innovative-on-chain-offering.html
123. Ripple. (2023, May 17). Ripple takes on the crypto custody market with Metaco. https://ripple.com/insights/ripple-
takes-on-the-crypto-custody-market-with-metaco/
124. The Specialist. (2021, February 20). Transfer agency and its role in digital, tokenized and fractionalized securities.
https://thespecialist.substack.com/p/transfer-agency-and-its-role-in-digital 
125. Minervi, N., & Hendrick, K. (2023, October 12). Vertalo’s digital transfer agent. ChainEnabled. https://
thechainenabled.substack.com/p/vertalos-digital-transfer-agent
126. WisdomTree. (n.d.). Digital funds: A new era of tokenized investing. Retrieved April 14, 2025, from https://www.
wisdomtreeprime.com/insights/digital-funds-a-new-era-of-tokenized-investing
127. Fenergo. (2024). Global KYC & onboarding trends in 2024. https://www.fenergo.com/kyc-trends
128. World Federation of Exchanges. (2024, June 12). Demystifying tokenisation: Embracing the future. https://www.
world-exchanges.org/our-work/articles/demystifying-tokenisation-embracing-future
129. Katz, E. (2024, April 15). The UK digital securities sandbox takes shape. Ashurst. https://www.ashurst.com/en/
insights/the-uk-digital-securities-sandbox-takes-shape/
130. European Central Bank. (2022, March 17). Tokenisation of cash and securities. https://www.ecb.europa.eu/paym/
groups/pdf/omg/2022/220317/item-2_Tokenisation-cash-securities.pdf
131. Bank of Canada. (2025, March 21). Risk free uncollateralized lending in decentred markets. https://www.
bankofcanada.ca/wp-content/uploads/2025/03/sdp2025-6.pdf
132. Azizi, B. (2025, March 24). Mesh raises $82M to bring stablecoins everywhere [Audio podcast]. https://tokenized.
simplecast.com/episodes/mesh-raise-82m-to-bring-stablecoins-everywhere-ft-ceo-bam-azizi-x56Zv7cr
133. Kinexys by J.P. Morgan. (n.d.). Next-generation ﬁnancial infrastructure. Retrieved April 14, 2025, from https://www.
jpmorgan.com/kinexys/index
134. Citigroup. (2024, July 17). Introducing Citi Integrated Digital Assets Platform (CIDAP): Driving innovation and building 
solutions with blockchain. https://www.citigroup.com/global/news/perspective/2024/introducing-citi-integrated-
digital-assets-platform
135. Coinbase Institute. (2024). Why the future of ﬁnance calls for a permissionless architecture. https://assets.ctfassets.
net/01oes7wu5gm1/3DPt8Y0iYtdVfqUoeuAJdS/33b4c368f7bc6b4ff7173df36c3d00da/Davos_Whitepaper_A4.pdf
136. Avalanche. (n.d.). Avalanche9000 Testnet launches with up to $40M in retroactive rewards. Retrieved April 22, 2025, 
from https://www.avax.network/blog/avalanche9000-testnet-launches-with-up-to-40m-in-retroactive-rewards
137. Electric Capital. (2024). Developer report: Analysis of open-source crypto developers. https://www.developerreport.
com/
138. Coinbase Institute. (2024). Why the future of ﬁnance calls for a permissionless architecture. https://assets.ctfassets.
net/01oes7wu5gm1/3DPt8Y0iYtdVfqUoeuAJdS/33b4c368f7bc6b4ff7173df36c3d00da/Davos_Whitepaper_A4.pdf
139. The Block. (2024). 2025 digital assets outlook report. https://www.theblock.co/post/332761/2025-digital-assets-
outlook-report
140. Accenture, Chainlink, & RWA.xyz. (2025, forthcoming). Liquidity without borders: Why cross-chain interoperability 
matters.
141. YCharts. (n.d.). Ethereum transactions per day. Retrieved April 14, 2025, from https://ycharts.com/indicators/
ethereum_transactions_per_day; Visa. (2022). Visa fact sheet. https://usa.visa.com/dam/VCOM/global/about-visa/
documents/visanet-factsheet.pdf
Endnotes

<!-- Page 63 -->

Contents
63
142. Weeks, R. (2024, December 18). Deutsche Bank tries to tackle compliance hurdles for public blockchains. 
Bloomberg. https://www.bloomberg.com/news/articles/2024-12-18/deutsche-bank-tries-to-tackle-compliance-
hurdles-for-public-blockchains; Schär, F. (2024). Enhancing ﬁnancial services with permissionless blockchains. 
European Commission: Directorate-General for Financial Stability, Financial Services and Capital Markets Union. 
https://data.europa.eu/doi/10.2874/8306042
143. Franklin Templeton. (n.d.). Franklin OnChain U.S. Government Money Fund. https://www.franklintempleton.com/
investments/options/money-market-funds/products/29386/SINGLCLASS/franklin-on-chain-u-s-government-money-
fund/FOBXX
144. Sandor, K. (2024, November 13). BlackRock expands tokenized fund BUIDL beyond Ethereum to 5 new blockchains. 
CoinDesk. https://www.coindesk.com/business/2024/11/13/blackrock-expands-tokenized-fund-buidl-beyond-
ethereum-to-ﬁve-new-blockchains
145. Irresberger, F., John, K., Mueller, P., & Saleh, F. (2023, September 30). The public blockchain ecosystem: An empirical 
analysis. NYU Stern School of Business. https://ssrn.com/abstract=3592849
146. Coinbase Institute. (2024). Why the future of ﬁnance calls for a permissionless architecture. https://assets.ctfassets.
net/o10es7wu5gm1/3DPt8YOiYtdVfqUoeuAJdS/33b4c368f7bc6b4ff7173df36c3d00da/Davos_Whitepaper_A4.pdf
147. Basel Committee on Banking Supervision. (2024). Novel risks, mitigants and uncertainties with permissionless 
distributed ledger technologies. Bank for International Settlements. https://www.bis.org/bcbs/publ/wp344.pdf
148. Barsan, I. M. (2019, July 1). Public blockchains: The privacy-transparency conundrum. Revue Trimestrielle de Droit 
Financier (RTDF), 2. https://ssrn.com/abstract=3442055
149. Federal Reserve Bank of Philadelphia. (2024, October 22). Next-gen ﬁnance through real-world asset tokenization
[Video]. YouTube. https://youtu.be/HB0kYQRxBEM?si=0AynKQu-xbq9Q68T&t=780
150. Organisation for Economic Co-operation and Development. (2025). Tokenisation of assets and distributed ledger 
technologies in ﬁnancial markets: Potential impediments to market development and policy implications. OECD 
Business and Finance Policy Papers, No. 75. https://www.oecd.org/en/publications/tokenisation-of-assets-and-
distributed-ledger-technologies-in-ﬁnancial-markets_40e7f217-en.html
151. The ValueExchange. (n.d.). DLT and digital assets. Retrieved April 14, 2025, from https://thevx.io/campaign/dlt-and-
digital-assets/
152. Committee on Payments and Market Infrastructures, & International Organization of Securities Commissions. (2012). 
Principles for ﬁnancial market infrastructures. Bank for International Settlements. https://www.bis.org/cpmi/info_pfmi.
htm
153. Fintech at Cornell. (2025). Cornell convenes 2024 roundtable forum: Tokenization of real-world assets. https://
business.cornell.edu/wp-content/uploads/sites/2/2025/02/Cornell_Convenes_Roundtable_Report_Tokenization_of_
Real-World_Assets_FINAL_2.3.25__VD_.pdf
154. OMFIF. (2024). Digital assets 2024. https://www.omﬁf.org/da2024/
155. Ledger Insights. (2025, February 17). ECB responds to market calls for permanent wholesale CBDC including from 
Deutsche Börse. https://www.ledgerinsights.com/ecb-responds-to-market-calls-for-permanent-wholesale-cbdc-
including-from-deutsche-borse/
156. Fnality. (2025, April 9). Broadridge Collaborates with Fnality to enable real-time settlement for intraday repo 
transactions [Press release]. https://fnality.com/news/broadridge-real-time-settlement
157. Herrick, J. (2025, February 26). Expanding market hours: Key considerations and the NYSE’s approach. LinkedIn. 
https://www.linkedin.com/pulse/expanding-market-hours-key-considerations-nyses-approach-jon-herrick-shuae/
158. Berkowitz, J., et al. (2025, March 14). The Bybit hack of 2025 — potential implications. Paul Hastings. https://www.
paulhastings.com/insights/crypto-policy-tracker/the-bybit-hack-of-2025-potential-implications
159. Nili, C., Patterson, T., & Dukatz, C. (2024, May 21). Safeguarding central bank digital currency systems in the post-
quantum computing age. World Economic Forum. https://www.weforum.org/stories/2024/05/safeguarding-central-
bank-digital-currency-systems-post-quantum-age/
160. The Digital Dollar Project. (2025). Modernizing the US dollar for the future of digital networks. https://
digitaldollarproject.org/wp-content/uploads/2025/03/Modernizing-the-US-Dollar-for-the-Future-of-Digital-Networks.
pdf
161. Financial Stability Board. (2024, October 22). The ﬁnancial stability implications of tokenisation. https://www.fsb.org/
2024/10/the-ﬁnancial-stability-implications-of-tokenisation/
162. Jiang, C., & Wallach, E. (2025, February 11). Headwinds becoming tailwinds. Pantera Capital. https://panteracapital.
com/blockchain-letter/headwinds-becoming-tailwinds/
163. Impuls Liechtenstein. (n.d.). Blockchain in Liechtenstein. Retrieved April 14, 2025, from https://impuls-liechtenstein.li/
en/blockchain/#tvtg
164. Trump, D. J. (2025, January 23). Strengthening American Leadership in Digital Financial Technology. Executive Order 
14178. The White House. https://www.whitehouse.gov/presidential-actions/2025/01/strengthening-american-
leadership-in-digital-ﬁnancial-technology/
165. Government of Hong Kong Special Administrative Region. (2025, February 26). Budget speech by the Financial 
Secretary. https://www.info.gov.hk/gia/general/202502/26/P2025022600116.htm
166. Financial Conduct Authority. (2025). Strategy 2025 to 2030. https://www.fca.org.uk/publication/corporate/our-
strategy-2025-30.pdf
Endnotes