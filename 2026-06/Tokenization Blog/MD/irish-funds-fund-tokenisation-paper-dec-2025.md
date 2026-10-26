# irish-funds-fund-tokenisation-paper-dec-2025

**Source:** irish-funds-fund-tokenisation-paper-dec-2025.pdf | **Pages:** 34

---

<!-- Page 1 -->

Mind the Gap                                         
Operational Considerations for the 
Tokenisation of Irish Domiciled Funds
FUND TOKENISATION

<!-- Page 2 -->

2
CONTENTS
Blockchain and DLT .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .  4
Types of Blockchains .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .  7
The Importance of Interoperability .  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .  8
Blockchain Governance .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .  8
Tokenisation of fund shares – moving value onchain .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   10
•  Potential Models for Tokenisation of Fund Share/Unit Classes .  .   .   .   .   .   .   .   .   .   .   .   .   .   13
•  Distributor level or sub register tokenisation .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   13
•  Hybrid or digital twin model:  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   13
•  Onchain native TA model:  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 14
An Investor’s Journey  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 15
Fund Discovery and Selection – Data Availability .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   15
Onboarding and Identity Verification .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   15
Wallet Creation and Whitelisting .  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   16
Subscription / Trade Instruction .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   17
Funding and settlement - Cash Leg Options .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 19
Holding, Management & Income .  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   21
Redemption and sale .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   22
What Does Not Change? .  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   24
Legal & Regulatory Considerations .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 25
Maintenance and Inspection of a Shareholder Register  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   26
Transfer of Tokens  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 26
Regulatory Framework Compliance .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  . 26
Future Developments and areas of further investigation  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 27
Blockchain as part of the fund construction process  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 28
Conclusion: A Call to Action .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 29
Appendix 1 – Glossary .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   30
Appendix 2 – Risk Assessment Questions .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   32
1. TokenStandard & Technical Architecture  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 33
2. Operational & Custody Considerations .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   33
3. Governance & Change Management .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   33
4. Strategic & BusinessModel Questions .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   34
Appendix 3 – Life Cycle Checklist  .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   .   . 34

<!-- Page 3 -->

3
FOREWORD
Irish Funds initiated Project Springboard to develop a structured analysis 
of the core concepts for a tokenised fund domiciled in Ireland.
This initiative involves an examination of the key technology features, 
operational process implications, and importantly, the potential benefits 
that technological innovation can deliver to the funds ecosystem. 
The objective is to provide a foundation for 
informed dialogue, enabling firms to identify and 
assess the key considerations necessary before 
embarking on a tokenisation strategy within the 
Irish regulatory and market context. 
This work aligns with broader European efforts 
to modernise capital markets. The European 
Commission’s Savings and Investment Union 
(SIU) strategy highlights the transformative 
potential of distributed ledger technology (DLT) 
in enhancing competition and efficiency across 
EU financial services. DLT is recognised as a key 
enabler for reducing operational inefficiencies, 
lowering transaction costs, fostering innovation, 
and increasing access for European investors. The 
Commission’s targeted consultation on integration 
of EU capital markets1 further explores DLT’s 
implications for competition, legal certainty, 
interoperability, and the adequacy of existing 
regulatory frameworks. Through a harmonised 
approach to DLT adoption, the SIU aims to cultivate 
a more inclusive and dynamic financial ecosystem.
In parallel, both the Central Bank of Ireland (the 
Central Bank) and the Department of Finance have 
acknowledged the strategic importance of DLT and 
tokenisation. The Central Bank has emphasised 
the opportunities these technologies present for 
improving transparency, accelerating settlement, 
and enhancing operational efficiency, while 
underscoring the need for robust governance and 
risk management.2 The Department of Finance, 
through its “Funds Sector 2030 Report” and the 
“Ireland for Finance”3 strategy has signalled its 
commitment to fostering a regulatory environment 
that supports innovation and aligns with EU 
standards. 
Ireland is a leading EU domicile for fund products 
notably in the money market funds (MMFs) space, 
in private asset strategies and has been at the 
forefront of innovation for exchange-traded funds 
(ETFs). Ireland offers a robust regulatory framework, 
global distribution reach, and operational expertise. 
Tokenisation, through the use of DLT, presents a 
transformative opportunity for funds by enabling 
faster settlement, enhanced transparency, and 
unlocking innovative and new functionality 
opportunities. For ETFs, tokenisation can streamline 
trading and improve liquidity, MMFs may benefit 
from real-time cash management and automated 
compliance, while private asset funds can unlock 
greater liquidity of traditionally illiquid assets and 
all may benefit from future expanded utility.
Tokenised fund offerings have gained momentum 
in recent years, evolving from pilots and proofs of 
concept to actual market adoption. In 2025, global 
tokenised real world assets (RWA) exceeded $36 
billion4, up from near-zero just a few years prior. 
This growth was driven by major asset managers 
launching tokenised products, primarily MMFs. 
Boston Consulting Group (“BCG”) estimates that 
tokenised fund assets under management (AUM) 
could reach 1% of global mutual funds and ETF 
AUM in just seven years. This would imply an AUM 
of more than US$600 billion by 20305 .
1.	 Targeted consultation on integration of EU capital markets 2025 - Finance
2.	 Regulatory & Supervisory Outlook Report 2025
3.	 2._Update_to_Ireland_For_Finance_AP_2025_web.pdf
4.	 RWA.xyz | Analytics on Tokenized Real-World Assets
5.	 According to BCG Exchange-traded funds (ETFs) reached about 1% of total fund AUM within 7 years of the launch of the first one in 1993. With features rivalling 
ETFs, tokenised funds could potentially reach 1% of total AUM by 2030, implying more than US$600 billion in AUM. Tokenized funds could scale even higher if 
clear and low-friction conversion pathways are established for converting (tokenizing) existing mutual funds and ETFs
6.	 JPMorgan Debuts Tokenized BlackRock Shares as Collateral with Barclays

<!-- Page 4 -->

4
FOREWORD
Ireland has emerged as an active participant in this 
trend. BlackRock and Fidelity International piloted 
projects in the tokenisation of their Irish domiciled 
MMFs for the use of collateral67 on JP Morgan’s 
Kinexys (previously Onyx) platform. Digital Platforms 
such as Archax, which offer tokenised access to Irish 
domiciled MMFs from firms such as BlackRock, 
State Street, Fidelity International, Legal & General 
Investment Management (LGIM) and Federated 
Hermes have made these products available to 
professional and institutional investors. 
Tokenisation activity spans multiple regions. Franklin 
Templeton launched its first European tokenised 
MMF8. Firms have partnered with FinTech platforms 
to bring funds onto distributed ledger infrastructure 
in Asia, US and Europe. Global banks and custodians 
were also engaged, supporting tokenisation services 
and distribution via proprietary networks.
The broader tokenised RWA market grew an 
estimated 85% year-over-year. Despite this 
momentum, tokenised fund AUM remains a small 
fraction of the $7 trillion U.S. money fund sector9, 
underscoring its early but rapidly evolving stage of 
adoption.
As the future state of fully onchain funds continues 
to evolve, it will require advancements in legal 
frameworks, regulatory clarity, technology, and 
market infrastructure. Accordingly, the content 
presented herein is offered as a thought leadership 
piece, intended to inform, educate, and support 
the transition from today’s practices to tomorrow’s 
possibilities. This analysis is not intended as legal, 
financial, or investment advice, but rather as a 
contribution to the ongoing conversation shaping the 
future of fund innovation in Ireland and beyond.
6.	
JPMorgan Debuts Tokenized BlackRock Shares as Collateral with Barclays
7.	
Fidelity International Tokenizes Money Market Fund on JPMorgan’s Blockchain
8.	
Franklin Templeton launches tokenized fund in Luxembourg - Ledger Insights - blockchain for enterprise
9.	
Release: Money Market Fund Assets | Investment Company Institute

<!-- Page 5 -->

5
Fully functioning blockchain technology emerged 
in 2009 with the creation of the Bitcoin 
blockchain, with the pseudonymous creator 
Satoshi Nakamoto having solved an ongoing 
prior technical problem of double-spend, which 
had previously impeded its full realisation. The 
solution enabled security and trust in a trustless 
environment via cryptography, a crucial step 
in moving the practical implementation of the 
technology forward. Blockchains represent types 
of databases which store data in cryptographically 
linked blocks making them tamperproof and 
immutable, by design they are decentralised (but 
do not have to be) and are extremely valuable for 
tracking ownership, a highly applicable feature  
set in the asset and fund management spaces.
Blockchain represents a type of implementation 
of a generic data structure referred to as a 
decentralised form of DLT while it is important 
to note that all blockchains are DLTs but not all 
DLTs are implemented as blockchains. The key 
difference lies in how data is structured and 
managed. However, blockchain and DLT share 
many of the same valuable features. Ultimately, as 
pieces of sophisticated software, they are subject 
 
to change and do not remain static but undergo 
refinement and development over time. Changes 
to a blockchain that are backward compatible 
i.e. still aligned with earlier versions, are called 
soft forks. New software versions that are not 
backward compatible are referred to as hard forks 
i.e. earlier versions of the blockchain software will 
not be able to run later upgrades of the software, 
this constitutes a risk from a fund and asset 
management perspective. Understanding these 
aspects is critical to tokenisation on any specific 
chain – hard forks, on public blockchains, can 
lead to two distinct DLTs with a shared history up 
to a certain point but diverge after such a point. 
This potentially leads to a position where two 
DLTs emerge from one, purely driven by a software 
deployment change.
BLOCKCHAIN AND DLT
“	You cannot step into 
the same river twice.”
	 – Heraclitus
CATEGORY 
BENEFIT
DESCRIPTION
Immutability & 
data integrity
Tamper-proof 
records
Once a transaction is recorded on the blockchain, it is 
nearly impossible to alter or delete. This creates a highly 
secure and verifiable record.
Reliable 
verification 
trails
The permanent and unchangeable nature of the ledger 
simplifies verification or auditing processes and ensures 
the integrity of financial records and asset history.
Decentralisation 
& trust
Trustless 
transactions
Participants can transact directly with each other 
without needing a central intermediary, as the network’s 
consensus mechanisms validate the transaction.
Reduced 
counterparty 
risk
The elimination of middlemen and the automation of 
agreements via smart contracts lower the risk of one 
party not fulfilling its obligations.
Distributed 
network
With data spread across many computers, the network is 
highly resilient to failures and cyberattacks, as there is 
no single point of failure.

<!-- Page 6 -->

6
Transparency & 
security
Enhanced 
transparency
All authorised network participants see the same shared, 
identical record of data in real-time, which increases 
accountability and discourages fraud.
Advanced 
security
The data is secured with advanced cryptography, making 
it extremely difficult for hackers to breach the network 
and alter records.
Fraud 
prevention
The transparency and immutability make fraudulent 
activities, such as counterfeiting products, much more 
difficult to get away with.
Efficiency & 
speed
Faster 
settlements
Transactions can be processed and settled in minutes 
or seconds, significantly faster than traditional financial 
systems that can take days. It is important to note that 
this benefit may be dependent on the chosen blockchain. 
Increased 
efficiency
By automating and streamlining processes that 
traditionally involve extensive manual verification 
and paperwork, blockchain dramatically increases 
operational efficiency.
Reduced costs
Eliminating intermediaries and automating workflows leads 
to lower administrative, processing, and transaction fees.
Automation & 
innovation
Smart contracts
These self-executing contracts automatically enforce and 
carry out the terms of an agreement once predefined 
conditions are met, removing the need for manual oversight.
Unlocking new 
functionality 
and possibilities
Tokenising traditional funds and assets enables those 
financial instruments to be used in new innovative ways. 
They can be traded, transferred, or lent instantaneously 
onchain. This makes it possible to create or unwind 
contractual arrangements in an instant, where tokens 
can be used in product layering, or aggregation, or 
fractionalised in new ways.
Improved data 
sharing
Blockchain provides a secure and unified framework 
for sharing sensitive data among authorized parties, 
improving coordination and decision-making.
Protection of 
intellectual 
property
A blockchain can create a timestamped, unchangeable 
record of an intellectual property asset’s existence and 
ownership, helping creators prove their rights and 
fight piracy.  
BLOCKCHAIN AND DLT

<!-- Page 7 -->

7
BLOCKCHAIN AND DLT
Blockchain is synonymous in people’s minds with 
Bitcoin and Ethereum which are cornerstones 
of the public blockchain space. However new, 
purpose-built, layer one and layer two blockchains 
are being developed and brought to market on a 
regular basis with certain chains tailoring their 
design to financial service use cases. 
A concept known as the blockchain trilemma 
exists in the industry where transaction speed, 
decentralisation and security need to be traded 
off against each other as part of the blockchain 
design process. This is important when it comes 
to choosing a blockchain for a specific use case 
and may incline the preference of one DLT over 
another. It is worth bearing in mind that as 
software, DLTs are subject to cyber security risk. 
In light of this, the longer a public DLT has been 
in existence the greater the amount of time it has 
been subject to attack and the more time it has 
had to shore up any weakness, this is referred to 
as “battle hardening”.  
Blockchain technology is important as it has 
significant potential from a market structure 
perspective and from a product delivery 
perspective. Tracking ownership of assets is a 
vital part of what the funds industry is built on; 
managing this in a risk-effective and trusted 
way is indispensable part of the value-add for 
the industry. DLTs can materially improve the 
efficiency, mobility, and availability of assets.
The 
Blockchain 
Trilemma
DECENTRALISATION
SECURITY
SPEED
Gas fees: gas is a concept in blockchain related to the cost 
of having an action undertaken by the blockchain. Gas is 
paid in the native “currency” of the blockchain which can 
be earned by participating in the consensus mechanism of 
a chain. The more complex the transaction the higher the 
resultant gas fee. On certain blockchains users can adjust 
their submitted gas fee to increase the likelihood of their 
transaction being included in the next block.

<!-- Page 8 -->

8
Types of Blockchains
The choice of blockchain is a critical design decision that impacts  
a fund’s governance, performance, and regulatory compliance.  
There are three main types, each with distinct characteristics.
The Importance of Interoperability 
As fund tokenisation expands across blockchains 
and wider DLT infrastructures, effective and 
secure cross-chain interoperability becomes 
essential to benefit from the efficiencies and 
value proposition. While this creates some level 
of technical complexity, for example ensuring that 
a token representation on one chain is “locked” 
if it is recreated on another chain, “bridges” 
have been created which act as an abstraction 
layer facilitating the transfer of tokens across 
bridges. These can be implemented in a number 
of different forms via relays, trusted bridges, 
atomic swaps etc. in a centralised or decentralised 
manner. It is imperative in any bridging solution 
that token information and standards and any 
necessary restrictions on access to the token are 
carried to the destination blockchain i.e. the token 
does not lose any of its attributes as part of such a 
bridging exercise.
Blockchain Governance
As noted above different blockchains have 
differing degrees of decentralisation which leads to 
the potential of decentralised governance. Certain 
blockchains are run by decentralised autonomous 
organisations (DAOs) which use developer 
input, user community input, and token holder 
mechanisms for making changes to the software 
or strategy of the blockchain. By implication 
then there is no centralised authority which is 
responsible for owning decisions around changes 
to such a fully decentralised blockchain nor its 
functionality, and not all parties will agree on any 
development. However, a consensus is usually 
found. If a consensus is not found it is possible 
that a hard fork emerges. 
BLOCKCHAIN AND DLT
Blockchain Type
Description
Potential Benefits
Potential Challenges
Public 
Permissionless
Open to anyone; no 
access restrictions. 
Examples: Ethereum, 
Bitcoin.
Global accessibility 
and liquidity, high 
transparency and strong 
decentralisation
Privacy concerns – 
all transaction data is 
publicly readable.
Public 
Permissioned
Open network with 
restricted validation 
rights. Examples: 
Hedera, Casper.
Controlled governance 
with public visibility 
and moderate 
decentralisation
Potential 
centralisation 
risks, integration 
complexity
Private 
Permissioned
Restricted access: only 
approved entities can 
participate. Examples: 
Hyperledger Fabric, 
Quorum.
Strong privacy and data 
control, customisable 
compliance and efficient 
performance.
Limited 
interoperability, 
reduced 
transparency,  
lower liquidity, and  
network effects

<!-- Page 9 -->

9
BLOCKCHAIN AND DLT
What questions do you need to ask yourself when 
considering a blockchain for deployment in a 
tokenised fund:
•	 Does our use case support a private chain  
over a public chain?
•	 What is the consensus mechanism used  
on the blockchain and how is it secured?
•	 How does a specific blockchain address the 
blockchain trilemma in its design balancing 
decentralisation/speed/security?
•	 Has the DLT experienced down time  
– if so, how long and what remediating  
action needed to be taken?
•	 What level of decentralisation exists for 
validators on the chain? How secure is it 
believed to be?
•	 Has the blockchain successfully been  
exploited? Have lessons been absorbed? 
•	 Does the blockchain have a history of  
hard-forking? 
•	 How would we integrate the chosen  
blockchain into existing systems?
•	 Do we have a business continuity plan (BCP) 
how does our blockchain strategy integrate 
into our BCP strategy?
•	 Do we have a cyber security policy and  
how does our blockchain strategy integrate  
into this policy? 
•	 Can we continue to be operationally resilient 
and what source of new risk(s), if any, to 
our operational resilience, does the use of 
blockchain introduce that can impact how we 
are able to respond and adapt, if such risks 
crystallise?  
•	 Digital Operational Resilience Act (DORA) has 
increased the responsibility on firms to be able 
to be held accountable how would we address 
this requirement with the use of a public chain?
•	 Will keeping control over our internal information 
still be important is we run a parallel internal 
blockchain to replicate onchain activity? 
•	 Ordering of trades – does the DLT support 
chronological ordering of trades in the  
creation of blocks?
•	 How are gas fees managed on the blockchain?
•	 What level of detail about the shareholder 
register will we be displaying onchain  
– in the knowledge that public chains  
facilitate data visibility.
•	 How is the blockchain governed? Is there 
a foundation overseeing its growth and 
development?  
•	 Is there a DAO responsible for managing  
the chain? Would we as users of the chain  
propose to input into its governance process?
Smart contracts: a smart contract is a piece of code which 
sits on a distributed ledger and is self-executing when certain 
events are triggered or can be called as a function of other 
smart contracts. Such trigger events may originate onchain or 
be from an external source or a real-world event.

<!-- Page 10 -->

10
TOKENISATION OF FUND SHARES – MOVING VALUE ONCHAIN
Fund tokenisation generally refers to the digital 
representation of fund units or shares via tokens 
using blockchain or DLT, enabling investors to 
access traditional investment products through 
tokenised formats. According to the European Fund 
and Asset Management Association (EFAMA), Fund 
tokenisation is a way to offer investors who are 
keen to invest via blockchain, a means to diversify 
their investments from pure crypto and get access, 
through the same investment channels and via their 
wallet, to other less volatile investment products 
such as money market funds10.
The means by which users interact with blockchain 
is predominantly via software wallets. 
Wallets display the number of tokens allocated to 
a specific address on the blockchain and are used 
when interacting with a decentralised or centralised 
application. Tokens can be transferred between 
wallets i.e. “swapping” of one token for another, 
buying and selling tokens either on a peer-to-peer 
basis or via decentralised exchanges (DEXs). They 
can be used to pledge assets, they can integrate 
into decentralised platforms and a number of 
other possibles uses, only limited by what can be 
designed for the use of the tokens and the type of 
token represented. Wallets come in two distinct 
variants, hot wallets, and cold wallets.
Hot wallets are continuously connected to a 
network/internet (e.g., desktop apps, mobile apps, 
or browser extensions) and can send or receive 
funds instantly.
Cold wallets remain offline except for a short, 
intentional connection to a network/internet 
solely to sign a transaction; after signing, they are 
disconnected again.
Cold wallet storage is considered to be more secure. 
There are also hardware wallets and multiple 
different variations on how to securely store, split 
and manage private keys and wallet infrastructure, 
which are beyond the scope of this document, but 
each are important aspects when considering wallet 
infrastructure and management in a given use case. 
Token balances i.e. the quantities of a given token 
recorded onchain for a particular address, are 
10.  tokenisation-a-buyside-practitioner-s-guide.pdf
Digital Wallet: A wallet is a 
cryptographically secured interface 
– software, hardware, or hybrid – 
that stores a user’s private keys 
and public addresses, enabling the 
user to send, receive, and view any 
tokenised asset (traditional assets, 
cryptocurrencies, utility tokens, 
non-fungible tokens (NFTs), security 
tokens, or other blockchain based 
representations of value) that are 
recorded on supported distributed 
ledger networks. The wallet 
aggregates balances per asset, while 
allowing the user to sign transactions 
and interact with smart contracts 
that govern those assets.

<!-- Page 11 -->

11
TOKENISATION – MOVING VALUE ONCHAIN
intended to track onchain ownership for a wide 
range of assets including funds, cryptocurrencies, 
utility tokens, stablecoins, bonds, equity, 
derivatives contracts and a multitude of 
instruments, securities and assets. When assets 
are tracked via tokens on a blockchain they gain a 
number of attributes which make them more easily 
incorporated into automated processes.
We are focused on the tokenisation of existing 
shares classes i.e. bringing current share classes, 
whose shareholder register is tracked by the transfer 
agent (TA), onchain, where the shareholder register 
would be recorded on a blockchain alongside full 
or partial traditional methods of record keeping, 
or alternatively, where shares are initially issued 
via blockchain-based shareholder register. It is 
an important distinction, but the former refers to 
taking an existing class and bringing it onchain and 
speaks to either a digital twin model or a specific 
share class of a traditionally tracked shareholder 
register, the latter refers to a share class only ever 
intended to be issued via a blockchain.
The hybrid or digital twin model supports a phased 
approach to tokenisation. Shares are issued and 
transferred in the conventional manner, but they 
are also represented on the DLT as a “digital twin” 
register (an onchain replica) to track tokenised unit 
ownership. This model allows funds to leverage 
DLT’s benefits with a view to seeking to comply with 
the current regulatory environment. This transitional 
structure is designed to enable real-time updates 
and automated processes while ensuring the 
offchain ledger remains the definitive source of 
truth for legal ownership. The level of benefit in 
this model is limited to the functionality and speed 
of the primary means of tracking and updating the 
traditional shareholder register.
In either instance the process of creating tokens 
on the chain is referred to as “minting” and the 
process of destroying tokens is known as “burning.” 
From the perspective of a fund share class which 
has been tokenised this would mean issuing new 
tokens “owned” by a specific wallet for a buy order 
and redeeming said tokens “owned” by said wallet, 
by burning them in the event of a sell. Minting 
and burning also play a part when considering 
moving tokens across compatible or noncompatible 
blockchains, a process known as bridging.  
The token has a level of data payload, and/or 
transaction related metadata, which it can carry 
with it, which varies by blockchain and by token 
standard (the rules that define what a token of a 
specific type looks like and what it can and cannot 
do). This makes tokens incredibly useful and 
provides for the ability for greater reference data 
clarity for example, tokens carrying or linking to 
onchain storage, which provide information about 
their issuers, latest prices, latest available financial 
data, latest ESG scores, prospectus, KID document, 
factsheets etc.
Numerous types of tokenisation standards exist 
on the Ethereum blockchain for instance, each of 
which provide certainty functionality depending 
on requirements. New standards can be, and 
are, agreed by the community to be adopted over 
time depending on any bespoke requirements or 
functionality that is viewed as beneficial.
Of the various different standards available for 
implementing tokens on Ethereum not all are 
applicable to fund tokenisation, however, for 
illustrative purposes, a subset are included in the 
table below. Further investigation would be needed 
as to the most appropriate standard applicable 
to a given tokenisation issuance and would be 
blockchain dependant.

<!-- Page 12 -->

12
Standard 
Token Type
Primary Use Cases
ERC-20
Fungible (identical  
and interchangeable)
Currencies and utility tokens: Used for standard 
digital money, in-game currencies, and voting 
rights in DAOs.
Decentralised Finance (DeFi): Acts as the 
backbone for lending, borrowing, and swapping 
on DEXs.
Stablecoins: Support asset-pegged 
cryptocurrencies like USDT and USDC.
ERC-721
Non-Fungible (unique  
and indivisible)
Digital art and collectibles: Enables the 
creation and trading of unique digital 
items, such as the NFT seen in projects like 
CryptoPunks and Bored Ape Yacht Club.
Virtual real estate: Represents unique 
parcels of land in metaverse platforms like 
Decentraland.
Gaming assets: Provides true ownership 
of unique in-game items like weapons or 
characters.
Certificates and identification: Can be used 
to create and verify unique digital identities 
or tickets.
ERC-3643
Permissioned Fungible 
and Non-Fungible
Real-World Asset (RWA) tokenisation: 
Facilitates the compliant tokenisation of 
regulated, real-world assets like real estate, 
securities, and private equity.
Identity and compliance: Enforces identity 
verification (Know-Your-Client (KYC)) and 
transfer restrictions directly in the token, 
ensuring only eligible, verified participants can 
own or transfer the tokens.
Regulated finance: Provides the framework for 
managing the lifecycle of security tokens from 
issuance to transfer in a compliant manner.
Of the subset, this standard appears to be 
the most aligned with the tokenisation of 
fund shares.
TOKENISATION – MOVING VALUE ONCHAIN

<!-- Page 13 -->

13
TOKENISATION – MOVING VALUE ONCHAIN
ERC-1155
Multi-Token Standard 
(can include fungible, 
non-fungible, and semi-
fungible tokens)
Gaming and metaverses: Highly efficient for 
managing a wide range of game assets, such  
as fungible in-game currencies and unique,  
non-fungible items like special weapons.
NFT marketplaces: Allows for the creation of 
collections with both unique pieces (NFTs) and 
multiple editions of the same work.
Semi-fungible assets: Supports tokens that 
can change fungibility, such as a concert ticket 
that is interchangeable before the event but 
becomes a unique collectible afterward.
Batch operations: Its batch transfer functions 
significantly reduce transaction costs and 
complexity compared to ERC-20 or ERC-721.
Tokenising of share classes does not lead to the 
ceding of any control. Between the token standards 
themselves, smart contracts, and the whitelisting 
of participants an extremely high degree of control 
remains with the token issuer. When a share class 
is tokenised on a DLT it is not “in the wild” for 
anyone to interact with or control, it is very much 
restricted to those who have been granted access 
and proven their eligibility to, hold, interact or 
instruct on said token.
Potential Models for Tokenisation  
of Fund Share/Unit Classes
The primary ways that that tokenisation is 
envisaged by the industry hinges currently on three 
distinct solutions:
•	 Distributor level or sub register tokenisation: in 
this model an entity external to the fund, for 
instance a distributor, intermediary or nominee, 
purchases shares/units in the fund. The token 
issuance is then performed by the distributor 
not the fund. There are limitations with this 
model, and it creates added operational layers, 
albeit from both a governance and regulatory 
perspective, it is the most straightforward for 
making a tokenised share class available. In 
this model, the tokenisation is independent of 
the manufacturer, and we will not reference this 
example in further detail. An example would be 
a centralised digital exchange purchasing units 
in their account and tokenising such units in 
order to make them available on their platform 
to investors11.  
•	 Hybrid or digital twin model: this model sees 
a dual-register setup wherein the traditional 
register, which primarily uses traditional 
databases to track ownership, and method of 
instruction via platforms or other acceptable 
instruction format, existing alongside the 
blockchain shareholder register. In this model 
the primary ownership record remains the 
traditional register. The blockchain register via 
the wallet can be used to instruct orders but 
the traditional register retains primacy. There is 
an added layer of reconciliation required as the 
blockchain record needs to be synchronised, as 
close as possible to real-time, to the traditional 
record set. Therefore, the interoperability of 
the blockchain register with existing technology 
is of crucial importance for this model. This 
transitional structure is designed to enable 
real-time updates and automated processes 
while ensuring the offchain ledger remains the 
definitive source of truth for legal ownership.
•	 Onchain native TA model: under this model the 
primary shareholder register is the blockchain 
record, the authoritative register regarding 
legal ownership of a token. Investors interact 
11.	  Live examples would include Irish MMFs made available on FCA regulated digital platform Archax -  Archax: Invest in Funds & Start-ups Today

<!-- Page 14 -->

14
TOKENISATION – MOVING VALUE ONCHAIN
via a platform which could use application 
program interfaces (API) to abstract away 
wallet functionality or uses a wallet to interact 
with the issuer (directly or perhaps to an 
aggregating intermediary). Under this model 
the additional factors are introduced which 
need to be considered namely, how to apply 
the value of the tokenised share class, into the 
blockchain. Additionally, while the blockchain 
is the primary record of legal ownership of a 
token, it is prudent to have backup for BCP and 
DORA purposes. This could be in the form of a 
data snapshot taken from the block explorer on 
a regular basis, or it could be a parallel internal 
blockchain or layer 2 internal blockchain. It is 
advisable that a point-in-time alterative data 
record should be available independently of 
the blockchain.
Future developments in respect of blockchain 
integration may involve an onchain digitally native 
model with end-to-end digitalisation of fund 
operations where all fund units are natively issued 
as tokens, investor interactions are automated 
via smart contracts, and regulatory compliance is 
embedded into the technology stack. In this model, 
as a future state, we intend to examine this in more 
detail in the “Future Developments and areas of 
further investigation” chapter.  
What initial questions do you need to ask yourself 
when considering tokenising funds for distribution 
to investors:
•	 What token standard will be used?
•	 What blockchains do we intend on deploying 
on? Are they compatible as a group? 
•	 What will the investor be able to do with the 
tokenised share class?
•	 How much functionality will our wallet  
provide for?
•	 What is the process for cancelling and reissuing 
tokens to an investor in the event of a loss of 
wallet access? 
•	 Does our smart contract and/or token standard 
provide for remediation?
•	 Is there an existing token standard which covers 
all of our requirements?
•	 Do we have an understanding of what the token 
standard allows and how/if it might change in 
the future?
Appendix 3 explores further questions which would 
provide a more expansive risk assessment matrix 
to help serve as a high-level guide for firms when 
considering compliance, operational bottlenecks, 
or investor experience issues.

<!-- Page 15 -->

15
AN INVESTOR’S JOURNEY 
Fund Discovery and Selection 
 – Data Availability
A key feature of a blockchain is the high level 
of data availability. This feature could become a 
useful attribute to help investors meet their specific 
investment needs when investing in tokenised 
funds. All fund manufacturers may not display the 
same level of data or linked metadata onchain; 
however, those who do provide more information 
onchain will be providing a useful service to their 
prospective investors.
High data availability should enable potential 
investors to view a broad range of competing 
products through onchain scanners. This will 
enhance the comparability of products and allow 
investors to produce sophisticated screeners on a 
broad range of data from a fund’s attributes to its 
performance and potentially modelling a portfolio 
using the available data.
Hence, DLT could serve as the foundational 
infrastructure for a new wave of transparent, secure, 
and accessible investor financial information. By 
enhancing the financial planning process, it can 
encourage retail investors to engage more actively 
with investment decisions, ultimately leading to 
a greater allocation of assets into the market. 
Providing investors more tools built on blockchain 
that can simulate investment scenarios, helping 
users understand risk, diversification, and portfolio 
dynamics, encourages further education and 
ultimately helps investors to make more informed 
investment decisions.
Onboarding and Identity Verification
How wallets interact with tokens and the issuance 
and sale of tokens is an area that needs to have 
particular attention from fund manufacturer’s 
perspective. The wallet must be linkable to an 
identifiable natural person or entity. This is a 
fundamental requirement for funds to ensure they 
know who their investors are or have delegated that 
function with adequate oversight to a party that can 
establish same.
Under the current model potential investors are 
identified by providing supporting documentation to 
prove they are who they say they are. This is done 
via identification (ID) submission, proof of address 
and source of funds, with additional documentation 
being required depending on the level of risk 
associated with the investor type or their location. 
Likewise for institutional investors, the burden 
of documentation is dependent on their location, 
organisation type, and risk profile. In the near term 
this exercise will not be impacted by tokenisation, 
there may be technology-based solutions that ease 
the process, such as Optical Character Recognition 
(OCR) scanning of documents and reference 
APIs into corporate information listing databases. 
However, there is a point at which the result of such 
investor verification needs to be married to a means 
of tracking ownership on the blockchain namely, 
this means we need to associate a wallet with a 
known a verified entity from a KYC perspective. 
The EU is transforming how digital identity is managed across Member States, with 
the concept of a Digital Identity Wallet progressing from abstract policy to imminent 
rollout. The means by which this is being progressed is the Electronic Identification, 
Authentication and Trust Services (eIDAS) framework updated as eIDAS2 in 2024.
The cornerstone of the evolution of this framework is the European Digital 
Identity Wallet – a secure mobile app that allows EU citizens and businesses to 
store, manage and share digital credentials such as ID documents, professional 
certificates and business licenses. By the end of 2026, each Member State must 
make at least one Wallet available, and all public and semi-public organizations 
must accept it. By December 2027, certain regulated industries, including banks, 
credit institutions, e-money institutions, payment service providers, will be required 
to accept them as a way for citizens to verify identity and other credentials.

<!-- Page 16 -->

16
 Wallet Creation and Whitelisting
Should an investor elect to engage with a fund 
via a wallet, the TA will need to ascertain the 
wallet address of the investor. For example, 
the investor will need to provide their wallet 
address which generally comes in the form 
(depending on the DLT in question) of 
multiple characters that together are relatively 
meaningless to the human mind, such as 
2aB7eC4a1F3b9dE8C7A1f9B2cD4e5F6A7B8C9 
to the TA. There may then be an additional step 
to ensure that the investor who has provided 
the wallet address is in control of the wallet in 
question by requesting they send a random, 
pre-agreed, non-material amount (most tokens 
are rounded to 18 decimal places) to ensure the 
person who has been identified is in control of said 
wallet and has not for example introduced a typo. 
This is sometimes referred to as a “Satoshi test”. 
With this activity complete we can now whitelist 
the investor’s wallet. This is to say that we can 
instruct tokens to be applied to said wallet. The 
wallet address will be associated with other 
on-file client records so that the investor can 
instruct buys, sells and transfers (only to another 
whitelisted wallet) and begin to open up further 
potential utility of having their ownership record 
stored onchain.
In the future it is likely we will see an evolution 
of onchain identity becoming a self-sovereign 
mechanism wherein an investor has had their KYC/
anti-money-laundering (AML) process undertaken 
once, which is then portable across different 
providers. This is not without its own trust 
consideration. Research is underway to examine 
how such an investor’s own, portable ID would be 
managed in a compliant manner onchain.
What initial questions do you need to ask yourself 
when considering tokenising funds for distribution 
to investors:
•	 Who would fulfil the tokenisation role process? 
For a hybrid tokenisation model this may be  
the fund’s current TA, or we may see  
the evolution of dedicated tokenisation  
agents in the future. 
•	 Can a single investor have multiple linked  
and whitelisted wallets depending on  
business need?
•	 How is oversight of tokenised activities  
catered for? 
•	 How do we deal with instances of fraud?
•	 How is an investor’s identity established via 
traditional means and by whom? 
•	 How will we verify an identified investor’s 
ownership of a wallet? 
Appendix 3 focuses on the wallet and KYC 
lifecycle: from legal classification, KYC/AML, and 
tax reporting, through technical key management 
and smart contract governance, to investor 
experience and exit strategies.
AN INVESTOR’S JOURNEY 
As an alternative to the moving of 
actual funds a request can be sent to 
a wallet-driven message, that when 
signed by the wallet owner, proves 
control of the private key without 
moving funds, optionally complemented 
by an onchain zero value transaction for 
an immutable anchor.
Special wallet types (custodial, 
multisig, hardware air gap) need 
tailored workflows, but the core 
principle remains: cryptographic proof 
of control + documented KYC linkage.
Implementing a multi step workflow 
similar to the above will give a prudent 
process for onboarding token holding 
investors while still offering a smooth 
user experience for the retail audience.

<!-- Page 17 -->

17
AN INVESTOR’S JOURNEY 
Subscription / Trade Instruction
When an investor has been, verified from a KYC 
and AML perspective, has a wallet setup, the 
wallet has been whitelisted, and we are now ready 
to move forward with an investment we reach 
a point of branching, regardless of whether the 
fund is in hybrid or onchain native model. The 
reason for this branching is due to the cash leg 
processing of a given transaction and optionality 
that exists around same.
Option1: Hybrid/Digital Twin or Onchain model  
– Traditional Cash Settlement 
An investor wishes to subscribe for the share 
class of a fund directly with the issuer via their TA 
paying with fiat money.  
1.	 Order is generated by a whitelisted wallet and 
sent to the TA.
2.	 TA confirms receipt of order for specific trade 
date.
3.	 Confirmation of order receipt is issued  
to the investor.
4.	 Primary offchain shareholder register and the 
blockchain “twin” register update to reflect the 
issuance of shares/units.
5.	 The payment leg in this instance is in fiat 
currency hence the standard banking ecosystem 
is used, and the investor sends their monies to 
the necessary collection account.
6.	 A contract note is then issued to the investor.
7.	 Cash is received to the fund’s custody accounts 
for deployment.
Units 
allocated 
to wallet
Model 1
Model 2
Confirmaton issued
Contractual 
settlement
ShareRegister 
Updated
USD  
(Fiat currency 
from bank)
Buy order 
generated  
from wallet
Contract  
Note issued
To custody 
accounts
Traditional 
settlement
Payment Leg
NAV Applied
Order Leg
Received

<!-- Page 18 -->

18
Option 2: Hybrid/Digital Twin or Onchain model 
– Onchain (Digital) Cash Settlement (where 
permissible from a regulatory perspective)
An investor wishes to subscribe for the share 
class of a fund directly with the issuer via their TA 
paying with stablecoins.
1.	 Order is generated by a whitelisted wallet and 
sent to the TA.
2.	 The payment leg in this instance is in 
stablecoins and does not use the standard 
banking ecosystem. The order leg and the 
settlement leg can be simultaneous and 
included in a single block record. The 
transaction is said to be atomic. 
 
3.	 TA can now confirm the receipt of order  
for the specific trade date.
4.	 TA can immediately issue a contract note after 
the striking of the day’s NAV.
5.	 Blockchain register updates to reflect 
the issuance of shares/units (a secondary 
offchain shareholder register may also be 
asynchronously updated depending on solution 
implementation).
6.	 The stablecoins received into the collection 
account wallet need to be exchanged (we will 
nominally refer to the process as FX herein) 
into a fiat currency that the fund can use (this 
may change in the future if a fund can accept 
stablecoins as subscription monies). It is then 
sent to the custody account for deployment.
AN INVESTOR’S JOURNEY 
Units 
allocated 
to wallet
Model 1
Model 2
Confirmaton issued
ShareRegister 
Updated
Stablecoin
Received
Buy order 
generated  
from wallet
Contract  
Note issued
To custody 
accounts
Onchain 
settlement
Payment Leg
NAV Applied
Order Leg
“FX” from 
stablecoin to fiat

<!-- Page 19 -->

19
AN INVESTOR’S JOURNEY 
Funding and settlement  
- Cash Leg Options
Fiat money: USD/EUR/CHF etc the investor chooses 
to settle their trade by instructing cash from their 
bank account to the fund’s collection account.
Tokenised deposits/deposit tokens: tokenised 
deposit are deposits held in bank accounts which 
are locked and reflected on a blockchain for 
transactions. Deposit tokens are bank balances 
issued and tracked specifically onchain. The 
current implementation of these types of onchain 
cash tends to be specific to a given bank i.e. as 
yet they have limited to no interoperability outside 
of a given bank’s internal, onchain ecosystem. 
While this is likely to be solutioned in the longer 
term, they are unlikely to be viable, near-term, 
solutions to fund structures with a diverse  
investor base.
Stablecoins: stablecoins come in a variety of 
formats however the goal shared across their 
implementations is for a coin to be pegged to a 
reference asset. The reference asset to which most 
stablecoins are currently pegged is the US dollar. 
Asset Backed/Asset Referenced: asset backed 
stablecoins reference a fiat currency and 
they are generally backed 1:1 with reserve 
assets of high-quality liquid assets (HQLA). 
The intention here is that the onchain cash 
representative of a fiat currency is fully backed 
by real world near-cash assets. It is worth 
bearing in mind that there are a number of 
other permutations of reserve collateral which 
could be used in the future.
Over-collateralised: this form of stablecoin 
is a type of cryptocurrency that is backed 
by collateral worth more than the value of 
the stablecoin itself, providing a buffer to 
maintain price stability even during market 
volatility. Should the collateral begin to move 
in a negative direction the collateral will be 
liquidated for the stablecoin thus retaining 
the overall balance in the protocol’s pool of 
stablecoin issuance versus available collateral. 
Algorithmic: this implementation of a 
stablecoin can use sophisticated derivative 
strategies, rebasing mechanisms, arbitrage 
reference assets, and a number of other 
potential mechanisms to retain their peg. 
In general, they have been less successful 
than the other forms of stablecoins however 
newer algorithmic stablecoins have come to 
the market and have maintained their peg in 
stressed market conditions.
CBDC: Central Bank Digital Currency (CBDC) – 
there are a multitude of CBDC trials in progress 
globally and the European Central Bank (ECB) 
has announced plans to issue a wholesale (i.e. 
non-retail) CBDC in the near future. CBDCs are 
not onchain native by definition (they could and 
can be tracked by traditional means) but do lend 
themselves to onchain issuance. It remains to 
be seen whether central banks will allow for (a 
somewhat confusing acronym) wwCBDC meaning a 
wrapped wholesale Central Bank Digital Currency 
i.e. wholesale CBDC in a tokenised wrapper, to be 
brought onchain or central banks could issue a 
portion of their CBDC directly onto a DLT.
Settlement possibilities: Of the above range of 
potential payment solutions for the investor’s 
subscription we will discount all of the options 
except fiat and HQLA asset-backed stablecoins. 
The reason for this is that algorithmic stablecoins 
carry a higher risk of de pegging, and CBDCs have 
not yet reached onchain maturity, making both 
impractical in the near to intermediate future.
This then leaves us with two settlement options 
fiat or HQLA-asset-referenced stablecoin. 
For the former the process is familiar, an 
investor would pay for their share tokens using 
the currency of their choice as accepted by the 
fund. This process would use traditional banking 
infrastructure, and a contract note issued directly 
to the investor’s wallet or via email/standard 
method, would be used. At this point, the investor 
could access their tokens i.e. send them to 
another whitelisted wallet they control, or redeem, 
or in the future send them to an exchange, a peer-
to-peer compliant order matching facility or some 
other KYC/AML/countering financing terrorism 
(CFT)/sanction-checks approved 
onchain application.
In the event that an investor wishes to pay for 
their subscription using an onchain cash option, 
which given the onchain nature of tokenisation

<!-- Page 20 -->

20
AN INVESTOR’S JOURNEY 
is a possibility that should be given serious 
consideration by tokenised fund operators, then, 
in the Irish context a conversion mechanism will 
need to be deployed. This conversion mechanism 
would, until such time as an Irish fund can 
accept non-fiat currency as part of its dealing 
proceeds, be carried out externally to the fund. 
Notwithstanding this, the concept is analogous to 
a USD investor investing in a GBP class currency 
in a multicurrency dealing fund. The USD on 
receipt needs to be FX’ed into GBP to affect the 
settlement of the order. In our stablecoin example 
we then need to find a party (be it internal or 
external) to “FX” the USDC (for example) into a 
fiat currency accepted by the fund e.g. GBP. While 
the exchange rate tends to be pegged there are 
deviations between asset backed stablecoins and 
their fiat counterpart. In any event, the investor 
would likely take on this deviation risk as part of 
their subscription (and redemption). Again, at 
this point the investor could access their tokens 
i.e. send them to another whitelisted wallet they 
control or redeem or in the future send them to an 
exchange, a peer-to-peer compliant order matching 
facility or another KYC/AML/CFT/sanction-checks 
approved onchain application.
Holding, Management & Income
In a passive buy and hold portfolio, holding 
a token should not lead to any additional 
complications however any fund manufacturer at 
the very least will need to communicate to their 
clients on occasion. Notifications could potentially 
be sent directly to an investor’s wallet; however, 
consideration of compliance with any legal or 
regulatory obligations regarding the format of 
investor notifications would need to be borne  
in mind. 
Funds are not by their nature static; they have 
qualities that allow them to be refined and 
changed, as markets change impacting investment 
theses behind a fund’s mandate. This means that 
parties issuing fully onchain native share classes 
should spare a thought for future eventualities 
such as a liquidation, name changes, mergers 
between two tokenised funds and a non-tokenised 
and a tokenised fund etc. While not all fund 
events would impact the tokenisation aspect of a 
fund, it is prudent to entertain future possibilities.
An event that is guaranteed to occur on 
distributing tokenised share classes is the 
distribution of income. Tokenisation provides 
interesting possibilities with regard to the income 
and frequency of dividend payments which can be 
automated in a tokenised scenario. While similar 
in practice to a dividend reinvestment, an investor 
can be paid in more tokens of the same share 
class and have them delivered to their wallet. It 
could be possible to pay an investor in tokens 
of another fund or another share class if a suite 
of tokenised share classes were offered. This 
could be possible to implement in a low overhead 
way given the automation made possible by 
tokenisation.
•	 An investor could choose to be paid in fiat 
currency or in the stablecoin in which they 
subscribed. 
•	 We could see distributions being made directly 
as stablecoins to an investor’s wallet, again the 
investor would need a foreign exchange (FX) 
solution to fulfil this function. 
•	 Another intriguing possibility is streaming 
payments hence investors could be paid 
interest on a quite granular basis i.e. per hour, 
materially reducing an investor’s reinvestment 
risk but there would be a challenge in aligning 
such a payout schedule to the income accrued 
and cash received at the portfolio level, albeit 
this is not an intractable problem today. The FX 
costs would also be an important consideration.
In providing reporting and other information to 
investors, data can be taken from the blockchain 
record and synthesised into a reporting format 
that is acceptable to them or in line with the 
manufacturer’s preferences. Another interesting 
possibility would be for the fund manufacturer to 
create an app to which an investor connects their 
whitelisted wallet. The app then can be used to 
create a pre-prepared number of aforementioned 
reports, or the investor can themselves use the 
raw data to create bespoke reports for their own 
requirements. 
Redemption and sale
The redemption process is largely a mirrored 
reflection of the subscription process. Giving 
the investor the options to receive proceeds

<!-- Page 21 -->

21
AN INVESTOR’S JOURNEY 
in the form of stablecoins, if permissible from 
a regulatory perspective in the future, and 
facilitation for atomic (i.e. instant) settlement 
will need close consideration. As monies in a 
redemption scenario are leaving the funds, it 
is critical to ensure that funds leaving by fiat 
currency (if invested via stablecoins) are going to a 
bank account of an identified person. If funds are 
leaving by stablecoin (if initially invested via fiat 
currency), it is critical to ensure that funds leaving 
are being sent to an identified whitelisted wallet 
and not to a third party.
What questions do you need to ask yourself when 
considering tokenising funds for distribution 
to investors in the context of settlement 
arrangements:
•	 Will we accept an onchain cash solution?
•	 If so what forms of onchain cash solutions 
will we accept and what will the conversion 
mechanism be?
•	 Who would do the conversion?
•	 What level of functionality will be given  
to the wallet?
•	 Will we allow investors to redeem  
to stablecoin?
•	 How will the mismatch in liquidity offered 
via instant settlement be offset against the 
limitations of the current speed of liquidating 
the underlying portfolio?
•	 Is the stablecoin you plan to accept licensed 
under a relevant regime?
•	 Do we need to hedge our positions or cashflows 
against a stablecoin de-pegging event? Where is 
this risk evident and who holds it?
•	 Will the fund hedge stable coin de pegging risk 
(e.g., via futures, options, or a basket of fiat 
backed assets)?
•	 Who holds the hedge position (the fund’s 
treasury, a third-party insurer, a market maker)?
•	 How is the cost of the hedge allocated 
(absorbed by the fund, passed to investors via a 
fee, or absorbed by the conversion provider)?
•	 Does the smart contract reject the transaction 
if the stablecoin amount does not match the 
required subscription amount (including fees)?
•	 Which settlement finality level is required 
before the TA can issue a contract note (e.g., 
12 Ethereum confirmations, or instant finality 
on a permissioned DLT)?
•	 How are transaction fees (gas, network fees, 
conversion spreads) allocated – to the investor, 
the fund, or shared?
•	 What is the fallback plan if the chosen 
blockchain experiences a prolonged outage 
(e.g., network halt, hard fork)?
•	 Is there insurance covering loss of funds due 
to smart contract bugs, key compromise, or 
stablecoin de pegging?

<!-- Page 22 -->

22
Other Operational Implications
TA activities do not of course operate in a vacuum 
and are part of the integrated process involving 
multiple actors coming together to support the 
running of fund structures. If we tokenise the fund 
wrapper for distribution what are the impacts to 
other functions within this process? Albeit not 
within the remit of this exercise it is important 
for a fund manufacturer to consider these 
implications. One of the benefits of having data on 
a blockchain is a greater degree of data availability 
that results from same. While various non-TA 
processes themselves do not change, where they 
send or take data from may change depending  
on the level of blockchain integration used.  
Below are examples of some very high-level 
potential impacts:
AN INVESTOR’S JOURNEY 
Fund  
Accounting:
•	 Applying NAV pricing to capital stock activity possibly via an oracle
•	 Analysing flows and ensuring hedge ratios are applied/maintained
•	 Data flows to and from the distribution calculation engine
Depositary:
•	 Monitor ownership possibly via blockchain ledger or smart contract registry
•	 Oversight of subscription and redemption processes 
Custody:
•	 Reconciliation of positions held by other funds, of tokenised share  
classes, will need to be tracked 
Performance 
Measurement:
•	 A higher level of data availability via the blockchain should make this process 
for the tokenised share class more streamlined
Financial 
Reporting:
•	 Aggregation and data related to flows and investor activity as required should 
be eased by greater data availability
Pricing:
•	 A higher level of data availability via the blockchain should make this process 
for the tokenised share class more straightforward
Front Office, 
Investment Risk, 
and Investment 
Compliance:
•	 Expected impact to be minimal with the exception of holdings in other funds 
tokenised share classes.
•	 Does not impact the process design directly
Regulatory 
Reporting:
•	 Access to data can be enhanced.
•	 The regulator can get a real time view of capital activity and holdings

<!-- Page 23 -->

23
What Does Not Change?
As noted to a large extent to date, the tokenisation 
of a share class does not necessarily lead to 
wholesale change outside of the TA function but 
rather data sourcing changes for functions that 
send data to, or take data from, the shareholder 
register, and TA related activities. What does not 
lessen are the oversight and legal and regulatory 
obligations a fund and a service provider have, 
they still need to ensure they have adequate 
oversight on any and all activities and processes, 
regular reporting and remediation, and have the 
necessary BCPs in place to ensure rollbacks and 
remediation can be applied in the event of say a 
NAV error, or a means to remediate any aspect of 
the process that has been made in error. Needless 
to say, adequate due diligence and internal 
expertise is advisable when taking into account 
the choice of tokenisation partners. Many of 
the traditional IT due diligence and information 
security requirements will be applied in addition to 
all of the standard business verification steps that 
would be undertaken in the event of onboarding a 
service provider of any description.
AN INVESTOR’S JOURNEY 
Oracle: an oracle is a means by which “real world” information is injected 
into the blockchain i.e. think of the latest market price of a leading 
equity. An oracle plays an important part of DeFi and a core enabler for 
sophisticated smart contracts. An oracle would be a data delivery service 
that imports verifiable, signed information from an external, licensed source 
(e.g., market price vendor, NAV valuation committee, central bank rate) onto 
a blockchain.  The oracle publishes the data as an immutable on chain event 
(or state variable) that can be read by the fund’s smart contract, which then 
executes the fund specific logic (subscription pricing, redemption eligibility, 
dividend distribution, collateral valuation).

<!-- Page 24 -->

24
LEGAL & REGULATORY CONSIDERATIONS
Regardless of the technology used or the form of 
fund tokenisation model, funds and their service 
providers will need to ensure that the use of such 
technology that is deployed as part of a selected 
fund tokenisation model complies with existing 
legal and regulatory requirements. This paper’s 
key focus is to inform readers on the core concepts 
and operational considerations. However, this 
section provides a high-level insight into some of 
the key legal and regulatory considerations for 
fund tokenisation.
Data Protection Considerations
One of the core elements of blockchain technology 
is that it is immutable. While this can offer benefits 
already outlined in this document, this aspect 
needs to be considered in the context of compliance 
with the Irish Data Protection Acts 2018 (as may 
be amended) which incorporated the provisions 
of Regulation (EU) 2016/679 (the General Data 
Protection Regulation (GDPR)) (Data Protection 
Acts). Compliance with the Data Protection Acts 
will need to be considered where there is processing 
of personal data. While compliance with the Data 
Protection Acts in full will need to be considered, 
some of main matters to bear in mind, particularly 
for controllers of personal data are:
Identifying a “controller” of the personal data 
that is processed on the blockchain. A controller 
in essence is a natural or legal person, public 
authority, agency, or other body which, alone or 
jointly with others, determines the purposes and 
means of the processing of personal data.
Identifying a lawful basis for processing. All 
processing of personal data must be lawful. This 
includes identifying a legal basis from Article 6 
of the GDPR.
Compliance with the key principles under the 
GDPR related to the processing of personal data. 
These include, but are not limited to:
•	 Data minimisation and storage limitation;
•	 Purpose limitation; and
•	 Data accuracy.
Compliance with data subject rights. These 
include, but are not limited to:
•	 Right to rectification;
•	 Right to erasure; and
•	 Right to object.
Given the nature of blockchain technology, there 
may be challenges with ensuring compliance 
with the Data Protection Acts. As a result, it is 
important for funds implementing tokenisation 
and fund service providers involved in same to 
ensure this is addressed early in the engagement 
process to understand how requirements will be 
complied with.

<!-- Page 25 -->

25
LEGAL & REGULATORY CONSIDERATIONS
Maintenance and Inspection of a 
Shareholder Register
Regard should be given to the requirements 
imposed under applicable laws, particularly those 
governing the legal structure of a fund, in respect of 
the use DLT generally. In particular, regard should 
be had to the location and format of the shareholder 
register where DLT is proposed to constitute the 
register of shareholders, i.e. a fund and its TA for 
example, will need to examine if it is permissible 
for the register of shareholders to be maintained in 
Ireland, and if it can be stored on DLT. 
Certain requirements exist pursuant to domestic 
laws that require the shareholder register and 
other information to be available for inspection. 
The information displayed on the DLT will not be 
in a readable format. As a result, funds and their 
service providers may need to consider the use of 
blockchain reading technology, that in essence 
facilitates the translation of the blockchain into 
readable text, and if such technology can assist with 
achieving compliance with the requirement for the 
relevant content being capable of inspection.
Transfer of Tokens
One of the main benefits of the use of DLT as 
part of a fund tokenisation model is the speed at 
which transactions can occur. Therefore, regardless 
of the selected tokenisation model, funds and 
their manufacturers will likely want to pass this 
benefit on to investors to facilitate investors having 
the ability to transfer their tokens on the DLT to 
other existing or potentially new investors. This 
is especially relevant for funds and investors that 
deal daily or on an intra-day basis. If the intention 
is to transfer ownership of a unit in the fund, then 
certain domestic regimes, pursuant to which the 
legal structure of a fund is governed by, may require 
an instrument of transfer to be used to effect a 
transfer. As a result, if an instruction by an investor 
to transfer their token on the DLT is intended to 
be used as the instrument of transfer (rather than 
traditional instruments of transfer, such as for 
example, stock transfer forms) then the domestic 
laws that govern the legal structure of the fund 
should be reviewed to determine that an instruction 
to transfer on the DLT complies with the domestic 
requirements in this area.
Regulatory Framework Compliance
Where DLT is deployed as part of a fund’s 
operations, the regulatory framework that the 
fund is authorised pursuant to (UCITS or AIFMD 
framework) will need to be reviewed to ensure 
compliance with the terms of such framework. 
While EU legislative acts on financial services 
are generally guided by the principles of same 
activities, same risks, same rules and of technology 
neutrality, there may be terminology included in 
such acts that may not have envisioned at the 
time of drafting, new technology such as DLT. 
Correspondingly, an assessment of existing UCITS 
and AIFMD framework provisions may need to be 
completed to understand if they can be interpreted 
to include DLT, as relevant.
Finally, funds and their service providers will 
also need to assess the impact of the chosen 
tokenisation model on compliance with 
other important areas such as AML/KYC/CFT 
requirements, treatment under and compliance 
with tax laws, beneficial ownership laws, treatment 
of tokenised shares in the context of insolvency 
or enforcement scenarios or the categorisation of 
tokenised shares in respect of property rights.

<!-- Page 26 -->

26
FUTURE DEVELOPMENTS AND AREAS OF FURTHER INVESTIGATION
While we are at the early stages of practical 
implementation of blockchains and tokenisation 
in the financial services provision process, in a 
regulated environment, it is a fast-moving space. 
Various global regulatory jurisdictions and providers 
are forging ahead with the development of the 
technology in a responsible and investor protecting 
manner and we are seeing use cases for tokenised 
share classes materialise. Some of the most 
promising areas:
•	 The use of tokenised MMFs (TMMF) as 
collateral needed in derivatives positions or 
for security lending. Principally composed of 
HQLA, using TMMFs would reduce the amount 
of churn in the system and particular would be 
useful in market stress events such as the LDI 
crisis in the UK, where additional sell pressure 
on underlying government securities could be 
reduced. Global Digital Finance has recently 
published “The Case for Collateral Mobility in 
Europe & The UK using Money Market Funds” 
to which Irish Funds contributed. This paper 
outlines the value proposition that TMMFs offer 
qualities that are hard to replicate with other 
kinds of assets in the collateral use case (e.g., 
cash and stablecoins). Unlike cash, they accrue 
yield making them a more attractive form of 
posted collateral, particularly in a high-interest 
rate environment.12  
•	 Secondary market trading prompting the 
introduction of greater liquidity. This is composed 
of two core benefits from the perspective of daily 
traded funds (1) that there are intraday trading 
possibilities on exchanges supporting tokenised 
funds’ share classes where eligible whitelisted 
investors can trade the products intraday and (2) 
introducing a greater degree of liquidity to less 
liquid funds with interval liquidity, again arriving 
at a point where investor’s gain greater liquidity 
via secondary markets which adhere to necessary 
regulations and reporting standards in their 
relevant jurisdiction. 
•	 Using tokenised funds in DeFi applications. 
As a greater number of assets and instruments 
become available onchain interaction between 
onchain digitally native assets and traditional 
finance (TradFi) types becomes more prevalent 
e.g. using a fund token as collateral to borrow 
against a stablecoin.
•	 Enhanced distribution opportunities via 
accessing a generation who are more digitally 
native and comfortable with the use of 
blockchain and delivery though online or 
web3.0 channels such a cohort are  
familiar with.
•	 Introduction of assets onchain joining liquidity 
pools increasing all round liquidity depth.
12.  GDF_-UKEU_TMMF-_report.pdf

<!-- Page 27 -->

27
FUTURE DEVELOPMENTS AND AREAS OF FURTHER INVESTIGATION
The technology continues to advance unabated, 
for example significant strides are being made 
in aspects of onchain identity and privacy. The 
former via self-sovereign identity as outlined 
earlier in the paper. It also follows the principle of 
data minimisation, whereby only the data needed 
for specific purposes is shared and no more. 
Zero knowledge proofs are also gaining traction, 
a cryptography enabled mechanism where is it 
possible to verify a piece of information being 
provided, without knowing the information itself, 
helping to ensure privacy preservation.
It’s important to note that as the future state of fully 
onchain funds continues to evolve, advancements in 
legal frameworks, regulatory clarity, technology, and 
market infrastructure may be required.
Blockchain as part of the fund 
construction process
Blockchains are a relatively new type of database 
specifically useful for the tracking of value and 
acting as a single source of truth.  
Hence, wherever we have databases which are 
co-ordinated among each other, that need to have 
a high degree of accuracy, we will find possible 
use cases for blockchains. The fund and asset 
management spaces abound with such siloed data 
stores, not solely across industry participants but 
even within firms. 
As DLT continues to gain traction and the data 
availability that is onchain increases, we will see the 
possibility of having more actions being completed 
onchain. For example, if we envisage a fund of 
funds solely comprised of tokenised share classes, 
we can see how the fund accounting function might 
leverage smart contracts and oracles to begin to 
build the NAV construction process onchain. This 
is a very simple example but the more assets that 
can be held or are wrapped onchain the greater 
the degrees of smart contract utility that can be 
introduced, expanding the instances in which we 
could see advantages of blockchains, and tokenised 
assets increase dramatically.

<!-- Page 28 -->

28
CONCLUSION: A CALL TO ACTION 
Irish Funds recognises that tokenising funds 
or share classes unlocks new opportunities to 
enhance the end-investor experience through 
improved utility and cost efficiency. To support this 
evolution, we have established a dedicated Digital 
Assets Working Group tasked with monitoring 
market developments and assessing both current 
and future implications for fund servicing and 
asset management in Ireland. 
We believe it is essential that any firm considering 
the issuance of a tokenised share class carefully 
evaluates the innovative capabilities of DLT 
alongside the established regulatory and legal 
obligations that must be upheld.  
A comprehensive review of the investor journey, 
from client onboarding and capital deployment to 
position management and redemption, must be  
undertaken to ensure operational integrity  
and investor protection.
It is important to acknowledge that not all 
components of fund construction or ongoing 
operations will be affected by a share class-level 
tokenisation initiative, whether implemented as 
a digital twin structure or a fully native onchain 
model. This distinction underscores the need for 
a nuanced understanding of the practical impacts 
and limitations of tokenisation.
The use of DLT for fund tokenisation could 
demonstrate real improvements, faster settlement, 
better transparency, automated workflows, and 
expanded functionality of fund shares. These 
benefits align well with the policy goals of more 
efficient and resilient market infrastructure. As 
this technology transitions from pilot initiatives 
to global adoption, it is crucial that Ireland, and 
Europe more broadly, continue to strengthen the 
supporting ecosystem and regulatory framework. 
Doing so will be essential to maintaining 
competitiveness and positioning the region as a 
leader in digital financial innovation.

<!-- Page 29 -->

29
APPENDIX 1 – GLOSSARY
The following glossary provides key word definitions drawn directly from the source 
documents, presented in a structured format for enhanced visual clarity.
Term or Acronym
Definition Derived from Sources
DLT (Distributed Ledger 
Technology)
A technology that offers a decentralised data model with powerful cryptography, which  
may serve to revolutionise the funds industry. DLT is a digital system for recording transactions and data 
across multiple locations simultaneously. Unlike traditional databases that are centralized, DLT spreads 
data across a network of computers (called nodes), ensuring that each participant has access to the 
same, up-to-date record. It acts as the core infrastructure for token issuance, trading, and ownership 
tracking in future state models.
Blockchain
Blockchain is a type of DLT where data is grouped into blocks and  
linked cryptographically. All blockchains are DLTs, but not all DLTs use  
blockchain structures.
Fund tokenisation
Fund tokenisation refers to the process of representing an investor’s ownership  
of a share or unit in a collective investment scheme, such as a fund, as a  
digital token recorded on a blockchain or DLT.
Token
Depending on the fund tokenisation model selected and the legal structure of fund (corporate vehicle 
etc.), a digital representation of fund units or shares.
Gas fees
Gas is a protocol defined unit that quantifies the computational and storage resources a transaction 
(including any smart contract code it invokes) consumes on a blockchain. The sender specifies a 
gas limit and a gas price; the product of the two determines the fee paid in the blockchain’s native 
cryptocurrency. This fee is awarded to the miner or validator who produces the block, thereby 
rewarding participants in the consensus mechanism. Because more complex transactions require more 
EVM (or other VM) operations, they consume more gas and therefore incur a higher fee.
Smart Contract
A piece of code which sits on a distributed ledger and is self-executing when certain events are 
triggered or can be called as a function of other smart contracts. Such trigger events may originate 
onchain or be from an external source or a real-world event.
Subscription Contract
A specific type of smart contract that handles buy/sell orders with built-in KYC/AML checks. The 
application form itself may be a Smart Contract.
Oracle
A smart contract responsible for external data feeds.
Atomic Settlement
A type of settlement that ensures the simultaneous exchange of payment and asset tokens. It ensures 
simultaneous token burn and payment execution.

<!-- Page 30 -->

30
Term or Acronym
Definition Derived from Sources
DvP (Delivery versus 
Payment)
The process enabled by DLT-based forms of money that allows for simultaneous, onchain exchange of 
fund tokens and payment.
CBDC (Central Bank 
Digital Currency)
Central bank digital currency providing direct sovereign money settlement. This is seen as a low-risk 
settlement asset in DLT environments. CBDCs are not necessarily blockchain native by design. 
Retail CBDCs are designed for households and businesses to make payments for everyday 
transactions. Wholesale CBDCs are designed for financial institutions and operate similarly to central 
bank reserves.
Stablecoin
Asset-backed tokens like USDC or USDT used for stable value transfer. 
Self-Sovereign Identity 
(SSI)
An architecture or automated self-certification process for investor verification. It leverages 
Decentralised Identifiers (DIDs) and Verifiable Credentials (VCs).
DIDs (Decentralised 
Identifiers)
Blockchain-anchored identities that investors control without relying on centralised authorities.
VCs (Verifiable Credentials)
Cryptographically signed credentials issued by trusted authorities (banks, government agencies) that 
prove identity attributes.
ZKP (Zero-Knowledge 
Proof)
A privacy-enhancing technology that allows investors to prove compliance requirements without 
revealing sensitive personal information.
Whitelisting
A process where an investor’s wallet must pass KYC/AML and accreditation to be approved for token 
receipt and transfer. Wallet initiated actions are only authorised between whitelisted wallet holders.
Immutability (Blockchain)
A feature of distributed ledgers where ledger entries are permanently recorded once transcribed. Note 
that in regulated funds, this principle is supplemented by centralised controls (e.g., error correction).
Public Permissionless 
Blockchain
A fully open blockchain network where anyone can participate without approval. Users can read, write, 
and validate transactions. These networks are decentralised, transparent, and censorship-resistant, 
making them ideal for global accessibility and innovation. Examples include Ethereum and Bitcoin, 
which support trustless applications and tokenised assets without intermediaries.
Public Permissioned 
Blockchain
A blockchain network that is publicly visible but restricts transaction validation to approved 
participants. Anyone can access data, but only selected nodes can write to the ledger. This model 
balances transparency with governance control, making it suitable for regulated environments that 
require accountability, such as financial services or fund tokenisation.
Private Permissioned 
Blockchain
A network where access to read and write data is restricted to approved, fully known, and vetted 
participants. It is designed specifically for compliance and control.
Digital Twin Register
A transitional structure that is an onchain replica of the official shareholder register.  
It tracks ownership of tokenised units while the off-chainoffchain shareholder register remains  
the official legal record.

<!-- Page 31 -->

31
APPENDIX 2 – RISK ASSESSMENT QUESTIONS
Term or Acronym
Definition Derived from Sources
Hard forking
A hard fork is a permanent divergence in a blockchain protocol that creates two incompatible versions 
of the network. It occurs when consensus rules change, requiring all nodes to upgrade. Hard forks can 
result in a split chain, often leading to the creation of a new cryptocurrency or protocol variant.
Fractionalisation
A process by which high-value assets (or shares) are divided into smaller, tradable units.
Final Settlement
The irrevocable and unconditional transfer of an asset or financial instrument, or the discharge of an 
obligation.
Below are the main gaps and ambiguities in the checklist drafted, grouped by theme. Note that this is a 
non-exhaustive list.
1.  Token Standard & Technical Architecture
•	 Question: “Do the selected chains share a common virtual machine such as Ethereum Virtual Machine 
or WebAssembly Virtual Machine and support the same token standard so that a single smart contract 
codebase can be deployed unchanged?”
•	 Question: “Is the contract deployed behind an upgradable proxy, and do we have a governance 
process for future standard amendments that complies with the UCITS/AIFMD framework amendment 
procedures?”
•	 Question: “Have any deployed smart contracts involved in delivery been independently audited, and do 
we have a bug bounty or insurance arrangement for post deployment vulnerabilities?”
•	 Question: “Which oracle provider will deliver the NAV to the blockchain, or will it be done internally, if 
external how will we guarantee data integrity, and what fallback mechanisms exist if the oracle fails?”
2. Operational & Custody Considerations
•	 Question: “Will the fund use a multi signature escrow (e.g., 2 of 3: management company, custodian, 
independent trustee) for the token issuer keys, and what SLA governs key loss recovery?”
•	 Question: “Will the wallet support only token transfer, or also voting, dividend claim, KYC/AML/CFT/
sanction-checks onboarding, and onchain compliance checks?”
•	 Question: “What interoperability is required to connect the DLT technology with the existing technology 
stack to bridge between the blockchain and traditional architecture?”
•	 Question “Will we list the token on a regulated DLT exchange, operate an internal order book, or rely on 
over-the-counter(OTC) bilateral trades, and how will price disclosure be aligned with the fund’s NAV?”
•	 Question: “What is the block finality time on the selected chain, and does it satisfy the fund’s risk 
management policy for settlement risk?”
•	 Question: “What educational material, help desk processes, and dispute resolution pathways will we 
provide to investors unfamiliar with private key management?”key management?

<!-- Page 32 -->

32
3. Governance & Change Management
•	 Question: “What onchain governance model (multisig, DAO, board approved admin) will control critical 
contract functions, and how does that map to the fund’s internal governance procedures?”
•	 Question: “Do we have a documented migration pathway to revert to a traditional shareholder register, 
and what triggers would activate that plan?”
•	 Question: “How will we extract a regulator ready report (e.g., comma-separated values (CSV) file of token 
holder addresses, balances, and linked investor IDs) without breaching data privacy rules?”
4. Strategic & Business Model Question:s
•	 Question: “What is the projected return-on-investment (ROI) (reduced intermediaries, faster settlement, 
new distribution channels) versus the incremental operational and regulatory cost?”
•	 Question: “What are the upfront and ongoing licensing, transaction, and custody fees, and how are they 
reflected in the fund’s expense ratio?”
•	 Question: “How will we handle conversion of legacy shares into tokens (mandatory or optional), and what 
rights will those investors retain during the transition?”
APPENDIX 3 – LIFE CYCLE CHECKLIST
•	
Question: “Who is carrying out the fund tokenisation (fund manager, TA, dedicated tokenisation 
service)?”
•	 Question: “Which jurisdiction(s) host the nodes and data?” 
•	 Question: “At what frequency will we perform ongoing sanctions screening of onchain addresses?”
•	 Question: “How will tax residency be captured and reported (FATCA/CRS) for token holders?”
•	 Question: What distribution mechanism will be used for dividends/capital returns (fiat payout, stablecoin, 
onchain token)?
•	 Question: Who holds the token issuer private keys (multi sig custodial service, in house hardware security 
module (HSM), threshold crypto)?
•	 Question: What is the key loss / disaster recovery plan (backup shards, legal burn and re mint, court 
order)?
•	 Question:Are contract wallets or custodial wallets accepted? If yes, how will control be verified (signed 
message, custodial attestation)?
•	 Question: What governance process governs smart contract upgrades (proxy pattern, DAO vote, pre 
approved upgrade key)?
•	 Question: What audit regime (annual third party audit, internal controls) will cover both onchain code 
and offchain AML/KYC processes?
•	 Question: What wallet experience will be offered to investors (native app, web wallet, custodial service)?
•	 Question: How will lost wallet cases be handled for retail investors (social recovery, custodial fallback, 
legal process)?
•	 Question: Will the token be listed on a regulated DLT exchange, an OTC platform, or remain private? 
What listing criteria apply?

<!-- Page 33 -->

33
•	 Question: How will transfer restrictions (lock up, investor type limits, AML filters) be enforced?
•	 Question: What is the cost model for onchain operations (who pays gas for NAV updates, dividend 
distributions, token transfers)?
•	 Question: What dispute resolution mechanism applies to token related conflicts (arbitration, 
jurisdiction, admissibility of onchain evidence)?
•	 Question: Can a single investor hold multiple whitelisted wallets? How will the linkage be recorded 
and kept in sync with the AML/KYC record?
•	 Question: How will oversight of tokenised activities be organised (internal compliance team, external 
regulator liaison, reporting cadence)?
•	 Question: What is the fraud prevention & remediation framework (real time monitoring, token burn, 
compensation, legal recourse)?
•	 Question: How is investor identity established (documents, source of wealth)?
•	 Question: How will we verify wallet ownership (signed message challenge, sign in with Ethereum 
SIWE flow, custodial attestation) and store the proof in the AML/KYC dossier?
•	 Question: Are there any future proofing considerations (upgradeable token standards, modular oracle 
architecture, scalability to additional DLTs)?
•	 Question: What exit strategy exists if the tokenisation model proves unviable (migration back to paper 
certificates, conversion to traditional units)?

<!-- Page 34 -->

34
Dublin
Ashford House, 18-22 Tara Street, 
Dublin 2, D02 VX67, Ireland.
T:	+353 (0) 1 675 3200 
F:	+353 (0)1 675 3210 
E:	info@irishfunds.ie
www.irishfunds.ie
The Irish Funds Industry Association (Irish Funds) is the representative body for the international investment funds industry 
in Ireland. Our members include fund managers, fund administrators, transfer agents, depositaries, professional advisory 
firms, and other specialist firms involved in the international fund services industry in Ireland. By enabling global investment 
managers to deploy capital around the world for the benefit of internationally based investors, we support saving and investing 
across economies. Ireland is a leading location in Europe and globally for the domiciling and administration of investment 
funds. The funds industry employs over 19,000 professionals across every county in Ireland, with over 37,000 of a total 
employment impact right across the country and provide services to almost 8,900 Irish regulated investment funds with assets 
over EUR 5 trillion. 
Disclaimer: The material contained in this document is for general information and reference purposes only and is not 
intended to provide legal, tax, accounting, investment, financial or other professional advice on any matter, and is not to 
be used as such. Further, this document is not intended to be, and should not be taken as, a definitive statement of either 
industry views or operational practice or otherwise. The contents of this document may not be comprehensive or up-to-date, 
and neither IF, nor any of its member firms, shall be responsible for updating any information contained within this document.
Brussels
6th Floor, 
Square de Meêus 37, 
1000, 
Brussels.