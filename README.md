# Crypto-Currencies Design and Development (Engineering)  
### Author: Jean-Francois Giraud eng.
### Contacts:  
[Facebook](https://www.facebook.com/jeanfrancois.giraud.52/)  
[Twitter](https://twitter.com/8289468)  
[LinkedIn](https://linkedin.com/in/jfgiraudengineer)  
[Github](https://github.com/jean-francoisgiraud/DigitalCurrenciesKnowledgeBase)  
[Google Sites](https://sites.google.com/site/8289468canadainc)  

# Support
To hire the author please use the contacts section.  

Donations to this project are appreciated.   
BTC (Bitcoin): 1PUfrMWUUGPccf3kuUDu7MGHpbddJEqhFo  
BCH (Bitcoin Cash): qzt7xx2ujd4ukj4yqcyqeeq8rc6d0fazeyapn75syv  
KIP (kippu on SLP): qz67exr580g5wz0rrsypnfea9jc9w93arqkv7sfxws  

<!-- below is 'commented out' or invisible to the reader unless in edit mode
# Donations
Donations to this project are going directly to the developing team.  
BTC (Bitcoin):  
BCH (Bitcoin Cash):  
BSV (Bitcoin Satoshi Vision):  
DOGE (Dogecoin):  
LTC (LiteCoin):  
DASH (Dash):  
ETH (Ethereum):  
-->

# Table of Contents
[Contacts](#contacts)  
[Support](#support)  
[Definitions and Acronyms](#Definitions-and-acronyms)  
[Disclaimer](#Disclaimer)  
[Abstract](#Abstract)  
[FAQ Frequently Asked Questions](#FAQ-Frequently-Asked-Questions)  
[What is money](#What-is-money)  
[What are the problems with modern money](#What-are-the-problems-with-modern-money)  
[How can money be improved to make society better](#How-can-money-be-improved-to-make-society-better)  
[How to obtain CC](#How-to-obtain-CC)  
[Uses](#Uses)  
[Storage](#Storage)  
[Regulatory compliance requirements](#regulatory-compliance-requirements)  
[kippu](#kippu)  
[SLP](#SLP)  
[ERC-20](#erc-20)  
[SLP vs ERC-20](#SLP-vs-ERC-20)  
[What is a CC wallet](#What-is-a-CC-wallet)  
[How to protect a CC wallet](#How-to-protect-a-CC-wallet)  
[How to spend CC](#How-to-spend-CC)  
[Innovations and Disruptions](#Innovations-and-disruptions)  
[DAG Directed Acyclic Graph vs blockchain](#DAG-Directed-Acyclic-Graph-vs-blockchain)  
[The money flower a taxonomy of money](#The-money-flower-a-taxonomy-of-money)  
[Offline Crypto](#Offline)  
[Cloud based supporting documents](#Cloud-based-supporting-documents)  
[Notes Tips LL Lessons Learned](#Notes-Tips-LL-Lessons-Learned)  
[Contributing](#Contributing)  
[Legal](#Legal)  
[References](#References)  
[Appendix](#Appendix)
[Changelog](#changelog)  

# Definitions and Acronyms: 
CC = Crypto Currencies. (Bitcoin Ether LiteCoin Dash Dogecoin etc)  
DAO = Decentralized Autonomous Organization.  
ICO = Initial coin offering.  
P2P = Peer To Peer (a replicated network of ledger-database-records the opposite of a centralised database). Ex: BitTorent.  
tldnr = too long did not read.  
SLP = Simple Ledger Protocol (similar to ERC-20 but for BCH)  
SPV = Simplified Payment Verification  
WIF = Wallet Import Format (WIF, also known as Wallet Export Format) is a way of encoding a private ECDSA key so as to make it easier to copy. A private key is a secret code that allows bitcoins to be spent.  

Public-key cryptography, or asymmetric cryptography, is a cryptographic system that uses pairs of keys: public keys, which may be disseminated widely, and private keys, which are known only to the owner. The generation of such keys depends on cryptographic algorithms based on mathematical problems to produce one-way functions. Effective security only requires keeping the private key private; the public key can be openly distributed without compromising security. In such a system, any person can encrypt a message using the receiver's public key, but that encrypted message can only be decrypted with the receiver's private key.  

[SPV (Simplified Payment Verification)](https://electroncash.org/) was first described by Satoshi Nakamoto in the original Bitcoin whitepaper. This method allows a wallet to provide strong security without the need for downloading the blockchain or running a full node. SPV lets you validate your own transactions by ensuring they are confirmed in the blockchain. It uses the best header chain with the most cumulative proof of work and the correct hashing difficulty level. Electron Cash relies on a distributed network of servers which handle the heaviest part of blockchain operations. Your private keys sign transactions locally. They are never sent to the servers.  

Tokenization: combining public-private key cryptography and a public ledger, any number of tokens can be created on a blockchain.  

# Disclaimer: 
This is not financial advice (there are no warranties of any types). It is an analysis of the risks and opportunities of CC.  
CC is a fast changing environment some information herein may have changed since the latest revision.

# Abstract
"Bitcoin is the most abstract form of money ever created. Bitcoin is not a currency or a payment network it is a protocol and a network centric platform for recording ownership and trust on a peer to peer basis. Saying that bitcoin is a currency is like saying that the internet is email, currency is just the first application. If you have a platform that allows you to record ownership and trust the first type of asset that you are likely to use this ledger for is currency but that is just the begining. Bitcoin is the internet of money and currency is just the first application. It changes the nature of money. " Ref. Andreas M. Antonopoulos speech. "Bitcoin is Punk-Rock, You Cannot Control it WIRED". The current centralised banking system is based on clearing systems (databases of financial transactions synchronizing their ledgers typically once a day at nignt) between existing financial institutions (ACH  ACSS SWIFT). Decentralised alternatives are ((credits currencies) based on (crypto mutual civic community)). Decentralised money is more democratic (money by and for the people).   

# FAQ (Frequently Asked Questions)

## What is money 
A way to exchange and store value. A social agreement (contract) on what is good and valuable. It starts naturally as a decentralised peer to peer agreement, contract, protocol on what is valuable and how much value it has. For example:  

IF a group of individuals want to exchange products  
AND they agree (based on the amount of resources (time effort) required to produce the products) that for example 10 fish = 1 chicken  
AND that 1 fish = 1 seashell (representing products with a symbol like seashells or gold instead of products is more practical)  
THEN seashells become a) a medium of exchange (a currency) and b) a way to store wealth (money) for future use within that group  

## What are the problems with modern money
With time money becomes institutionalised, centralised, debt-based in fiat national currencies (backed only by the power governments give themselves to tax its people) which are controlled by governments banks organisations in their best interest. The natural p2p market economy is corrupted by inflation and interests and other shenanigans. This creates problems such as debts inequalities world-wars terrorism corruptions exploitations from continuously growing third parties (inflation interests fees commissions taxations (for wars armies armaments) etc.). No longer money by the people for the people.  

## How can money be improved to make society better
Returning to "money by the people for the people". That means a system of decentralised peer to peer agreement a "language and agreement for money" on what is valuable and can be used as currency for the exchange of goods and services and as money for storing value and investing).  Money based on value-equity-services instead of debt.  
CC built on cryptology and the internet makes money that is trans-national decentralised yet controlled and verifiable with complete traceability and an auditable database of all past transactions.  
This technology was invented by Satoshi Nakamoto and made public in his 2008 bitcoin white paper.   
It is a decentralised p2p-replicated public trust-less (crypto verified by 'miners' with trial and error (POW)) blockchain 
It was partly in response to the 2007-2008 worldwide systemic financial and real-estate crash.  
This crash left millions of people in debts and made banks even richer than they already were (because of questionable financial practices designed to transfer funds from the public to private entities).  
These practices included commercial banks engaging in investments banking which was the cause of the great depression and had been outlawed after the great depression by the Glass-Steagall act which was repelled in 1999 which then caused the 2007-2008 financial crisis.  
  
Abstract from Merkle, R. (2016) DAOs, Democracy and Governance.  
"Democracies are typically seen as governments which call upon the governed to make the major decisions of government: who shall lead, what policies to follow, what laws to enact. In all these matters democracies call upon ordinary citizens to make complex decisions with eventful consequences.
We do not call upon ordinary untrained citizens to perform surgery, fly airplanes, design computers, or carry out the other myriad tasks needed to keep society functioning, what makes governance different?
The problem is readily understood: if we give governance to “experts” they will make decisions in their own best interests, not in the best interests of us all. As we have seen too often in the past, this leads to enrichment of a small elite and the enslavement or worse of the vast majority. Can we take advantage of the expertise of the best and brightest, while insulating the system from attempts they might make to gain control?
Modern research into “the wisdom of crowds” provides new insights into how to combine the expertise of all participants without handing over control to “experts”. Combined with research on Decentralized Autonomous Organizations (DAOs), this allows us to design a new form of democracy which is more stable, less prone to erratic behavior, better able to meet the needs of its citizens, and which better uses the expertise of all its citizens to make high-quality decisions.
We call this new form of democracy a DAO Democracy."  
Ref: Merkle, R. (2016) DAOs, Democracy and Governance. Cryonics Magazine, July- August, Vol 37:4, pp 28-40; Alcor, www.alcor.org. https://alcor.org/cryonics/Cryonics2016-4.pdf#page=28 Version 1.9 2 2016-05-31  

## How to obtain CC 
Charge for your products services in CC, exchange regular money for CC, mine it, get tipped in dogecoin.  
See appendix for details on exchanges.  

Beware of scams and hacks and illegal unregulated trades-exchanges and unethical operations (pre-mining).  
ex Mt.Gox (handled 70% of bitcoin exchange in Tokyo in 2013)). Tether (it is pegged to the USD which is illegal (in court following a subpoena in December 2017)). Bitfinex (second biggest hack of stolen bitcoin $72million on 2016.aug.02). Ponzi, pyramid scheme ICO.  
For example one of the biggest scams in history was [OneCoin](https://en.wikipedia.org/wiki/OneCoin) a 2019 multi-level marketing Ponzi scheme promoted as a cryptocurrency which caused losses of about $4 billion worldwide.  

## Uses 
Peer to peer value exchanges of products and services (currency), store of value (money and investments).  

## Storage 
Your CC can be stored, saved invested as follows (from the safest to least safe):    
Multiple cold paper wallets backed up and stored in several locations and protected from environmental damage(1).    
Cold electronic wallet.  
Smartphone wallet.  
Online wallet.  
Exchange.  

(1) Such as (fire, water and UV) and printed from a computer never connecting to the internet and with a clean OS with only the paper wallet software installed from the original canonical (ex from the source code on a github which has been tested and peer reviewed for malicious software).

## Regulatory compliance requirements
It depends on the country where the CC are used. see https://en.wikipedia.org/wiki/Legality_of_bitcoin_by_country_or_territory.  

In Canada crypto currencies are regulated under provincial securities laws.  
A “security” means “an investment contract” which require: an investment of money in a business which may succeed or fail depending of the quantity and quality of the work of the business managers.  
This means that if you buy and sell them at a profit, you have income (capital gains) that needs to be reported for tax purposes.  

## kippu  
kippus (KIP) are tokens representing real-world assets, products, services. People can earn kippu credits by providing products/services to their community. kippus can be sent/received and are issued on the BCH/SLP (bitcoin cash) network instead of running on their own blockchain.  

To anyone interested in learning and experimenting with cryptocurrencies. The kippu coin is listed on bitcoin.com here:  
https://explorer.bitcoin.com/bch/token/0565328b0ff0062b9782e9056b88bddcea582ecce3e7e4184411111896969935  

You can earn, spend KIP (kippu) by trading, providing, receiving, bartering products or services to your community for which you will earn KIPs. KIPs are derived from bitcoin cash. Data integrity and the prevention of double spending is provided by Proof of Stake.  

To receive the KIPs you earned.  
- Install the wallet "Electron Cash SLP" from here https://simpleledger.cash/project/electron-cash-slp-edition/  
- Goto "Receive". Have your customer Scan the QRL code or send the "Receiving address" to your customer.  
- Your customer will send your KIPs, she/he will paste it in the SLP address from his/her KIP account (from a bitcoin wallet or from his/her bitcoin cash portfolio in https://mint.bitcoin.com/#/portfolio) to pay for your product, service in KIP. 

The original kippus were developed in Japan as a sectoral(1) civic mutual credit currencies (not crypto) in 1995. [Wikipedia Reference](https://en.wikipedia.org/wiki/Fureai_kippu)  
(1) A sectoral currency is a form of complementary currency that is restricted to a specific sector it can make people provide the type of services they themselves require or intend to use in the future.  

## SLP
[SLP is the Simple ledger Protocol](https://simpleledger.cash) A simple token system for Bitcoin Cash. Similar to the ERC-20 standard.  
[Electron Cash - Lightweight Bitcoin Cash client](#https://github.com/Electron-Cash/Electron-Cash).  
SLP is used for token implementation and is similar to bitcoin. SLP tokens are valuable real-world assets, products, services represented in the SLP blockchain which can be sent and received. SLP tokens (like our own KIP) are issued on the BCH (bitcoin cash) network instead of running on their own blockchain.  

## ERC-20  
[What is erc20](https://www.investopedia.com/news/what-erc20-and-what-does-it-mean-ethereum/)  
ERC-20 is a standard used for smart contracts on the Ethereum blockchain. ERC-20 is used for token implementation and is similar to bitcoin. ERC-20 tokens are valuable real-world assets, products, services represented in the ethereum blockchain which can be sent and received. ERC-20 tokens are issued on the Ethereum network instead of running on their own blockchain.  

## SLP vs ERC-20
SLP vs ERC-20 pros and cons  

SLP pros: Simpler (no need to code in solidity). Transaction fees are much cheaper.  
ERC-20 pros: compatible with metamask a crypto wallet for chrome and brave.  Transactions are faster (15 sec/block). Smart contracts.  

SLP cons: Transactions are slower (10 min/block vs ERC-20 15 sec/block). Require the electron cash wallet.  
ERC-20 cons: More smart contracts functions requires specialists capable of coding in solidity. Harder to understand and maintain.  

## What is a CC wallet 

This page contains sample addresses and/or private keys. Do not send bitcoins to or import any sample keys; you will lose your money.  

Reference (bitaddress.org).  
A CC wallet is a single pairing of a CC public address (32 characters) with its corresponding CC private key (64 char.).  
QR codes are used to simplify the entry of the addresses.  
Below are 3 examples (among many other types) of bitcoin paper wallet (combination of public and private keys).  

Example 1 - A simple paper wallet with one Address and PrivateKey (each with their QR codes).  
Example 2 - A fancier paper wallet with one Address and PrivateKey (each with their QR codes).  
Example 3 - CSV Comma Separated Values: Index,Address,PrivateKey.  
(DO NOT USE THE FOLLOWING WALLETS THEY ARE NOT MONITORED).  
1,"1MooziU1pXx9hhNEPKLrEHXfmKLjv1PWoR","Kz4zuZcestwPZw8BkzFRYvjTaGFXrzH2XTcnNJj1gQ2BY8FFch7u".  
2,"1AtXJay4uzSoYBEzSGunDXfKV4XhF4B21e","Kwr4sGtkQCAoaWLc86EvJjJ1AUtoJAbuy93Z9BzRuYb9A4ZoPB63".  
3,"1HwWtATHCoVQFdpyTfNRAwmodgDtioUod8","KzdG4LFgPgfBMDJ6iiZ9LgPD1JXrree5hapaETBpmrsVuCH9NjGD".  

Notes: these paper wallet have been impaired with red lines to prevent their use.  
This is a simple option but you can make your own public and private keys compatible with your chosen CC. 

A cryptocurrency wallet is a way (physical medium, program or a service) to store public and/or private keys for cryptocurrency transactions. It can also encrypt and sign information. Signing is the evidence of the execution of a smart contract. Smart contracts are digitally signed in the same way a cryptocurrency transaction is signed. The signing keys are held in a cryptocurrency wallet. 

A bitcoin wallet example from bitadress.org.  
A Bitcoin wallet is as simple as a single pairing of a Bitcoin address with its corresponding Bitcoin private key. Such a wallet has been generated for you in your web browser and is displayed above.  
To safeguard this wallet you must print or otherwise record the Bitcoin address and private key. It is important to make a backup copy of the private key and store it in a safe location. This site does not have knowledge of your private key. If you are familiar with PGP you can download this all-in-one HTML page and check that you have an authentic version from the author of this site by matching the SHA256 hash of this HTML with the SHA256 hash available in the signed version history document linked on the footer of this site. If you leave/refresh the site or press the "Generate New Address" button then a new private key will be generated and the previously displayed private key will not be retrievable. Your Bitcoin private key should be kept a secret. Whomever you share the private key with has access to spend all the bitcoins associated with that address. If you print your wallet then store it in a zip lock bag to keep it safe from water. Treat a paper wallet like cash.  
Add funds to this wallet by instructing others to send bitcoins to your Bitcoin address.  
Check your balance by going to blockchain.info or blockexplorer.com and entering your Bitcoin address.  
Spend your bitcoins by going to blockchain.info and sweep the full balance of your private key into your account at their website. You can also spend your funds by downloading one of the popular bitcoin p2p clients and importing your private key to the p2p client wallet. Keep in mind when you import your single key to a bitcoin p2p client and spend funds your key will be bundled with other private keys in the p2p client wallet. When you perform a transaction your change will be sent to another bitcoin address within the p2p client wallet. You must then backup the p2p client wallet and keep it safe as your remaining bitcoins will be stored there. Satoshi advised that one should never delete a wallet.  
Your Bitcoin Private Key is a unique secret number that only you know. It can be encoded in a number of different formats. Below we show the Bitcoin Address and Public Key that corresponds to your Private Key as well as your Private Key in the most popular encoding formats (WIF, WIFC, HEX, B64). Bitcoin v0.6+ stores public keys in compressed format. The client now also supports import and export of private keys with importprivkey/dumpprivkey. The format of the exported private key is determined by whether the address was generated in an old or new wallet.  

Why should I use a paper wallet ? Advantages of a paper wallet:  
Not subject to malwares and keyloggers.  
Relying on a third party (honesty or capacity to protect your coins) is not required.  
Hardware failure. You won't lose your coins when or if your device break and you have inadequate backup.  

Example generating a bitcoin wallet using walletgenerator.
Step 0 goto https://walletgenerator.net/  
Step 1. Generate new address. Choose your currency and click on the "Generate new address" button.  
Step 2. Print the Paper Wallet. Click the Paper Wallet tab and print the page on high quality setting. Never save the page as a PDF file to print it later since a file is more likely to be hacked than a piece of paper.  
Step 3. Fold the Paper Wallet. Fold your new Paper wallet following the lines. Fold in half lengthwise, and then in three widthwise.
You can insert one side inside the other to lock the wallet.  
Step 4. Share your public address. Use your public address to receive money from other crypto-currency users. You can share your public address as much as you want.  
Step 5. Keep your private key secret. The private key is literally the keys to your coins, if someone was to obtain it, they could withdraw the funds currently in the wallet, and any funds that might be deposited in that wallet.  
Security: Test spending a small amount before receiving any large payments.  

Generating your own private key using a dice and bitadress.org  
How do I make a wallet using dice? What is B6?  
An important part of creating a Bitcoin wallet is ensuring the random numbers used to create the wallet are truly random. Physical randomness is better than computer generated pseudo-randomness. The easiest way to generate physical randomness is with dice. To create a Bitcoin private key you only need one six sided die which you roll 99 times. Stopping each time to record the value of the die. When recording the values follow these rules: 1=1, 2=2, 3=3, 4=4, 5=5, 6=0. By doing this you are recording the big random number, your private key, in B6 or base 6 format. You can then enter the 99 character base 6 private key into the text field above and click View Details. You will then see the Bitcoin address associated with your private key. You should also make note of your private key in WIF format since it is more widely used. [WIF Wallet Import Format, also known as Wallet Export Format is a way of encoding a private ECDSA key so as to make it easier to copy.A testing suite is available for encoding and decoding of WIF at: http://gobittest.appspot.com/PrivateKey](https://en.bitcoin.it/wiki/Wallet_import_format)

Further reading:  
[Wiki Digital wallet](https://en.wikipedia.org/wiki/Digital_wallet)  
[Cryptocurrency wallet (cold storage)](https://en.wikipedia.org/wiki/Cryptocurrency_wallet)  
[An example paper printable bitcoin wallet consisting of one bitcoin address for receiving and the corresponding private key for spending.](https://en.wikipedia.org/wiki/Cryptocurrency_wallet#/media/File:A_paper_printable_Bitcoin_wallet_consisting_of_one_bitcoin_address_for_receiving_and_the_corresponding_private_key_for_spending.png)  

## How to protect a CC wallet 
Print or record the address and private key.  
Backup the private key.  
(optional) download from github to check the authenticity by matching the SHA256 hash of the HTML with the SHA256 hash available in the signed version history document linked on the footer of this site.).  
Your private key is a secret do not share it is not public. Whoever you share your private key with can then access and spend all the CC at that address.  
Your paper wallet is like cash.  
Add funds to your wallet by asking for CC to be sent to your CC address.  
Your balance can be verified on your smart phone or on blockchain.info or blockexplorer.com by scanning or typing or entering your CC address.  
Risks.  
CC stored on a device are lost if you lose it so you MUST back it up and keep it safe offsite or online and remember your backup location and password. Payments are irreversible (CC sent into the void are lost forever). If you uninstall a wallet you must transfer its funds beforehand. When you delete a CC wallet the wallet's transactions and funds become inaccessible. If an active online wallet needs to be deleted you must first transfer its fund in another wallet such as a cold storage paper wallet. You should then inform whoever will inherit your money when you pass away about the wallet location and secret key otherwise all funds will remain in the wallet forever and never accessible or usable so they will be lost for your posterity. 
Only install apps you fully trust, malicious apps could be trying to steal your funds.  
Only keep on your smart phone a small reasonable amount for your routine use and keep your main investments offline.  
If you have an important amount or CC you should transfer it in cold storage (paper wallet backed up and kept in safe and different location) that is how CC investors keep their funds.  

## How to spend 
Go to [blockchain.com/explorer](https://www.blockchain.com/explorer)  
In the search tool enter your public Bitcoin Adress to see how much funds you have.  
Or store your funds on your smartphone wallet (bitcoin litecoin ether dash dogecoin) to be spent later. 

## Innovations and disruptions  
Disruption is a new buzzword.  
Bitcoin is about the 6 billions unbanked people.  
Personal identifiable information/data in centralized system cannot be protected (even the NSA has been hacked and leaked). The only way to protect it is to not collect it.  
Unlike the centralized systems cryptocurrencies do not require personal data to operate.  
The blochain is a very slow ledger but what makes it special and different from the existing systems is the possibility of completely decentralized consensus.  
The revolutionary disruption is how tansactions can be done peer to peer without requiring a third party 'authority'.  

## DAG Directed Acyclic Graph vs blockchain
Blockchain vs. DAG  
Blockchains are cryptographically verifiable linked flat, sequential lists. Each new entry (block) includes a reference to a previous one. Traceable blocks are written in a ledger but this type of configuration also causes scalability issues.  
Directed Acyclic Graphs are implementation of Graphs that allow the network to avoid the limitations found in blockchains.  

## The money flower a taxonomy of money
[My facebook](https://www.facebook.com/photo/?fbid=10226436295602291&set=a.10201657964639503&__cft__[0]=AZUEWd6LnbUgzJicug5_dry1wW1BTbfCZCubfX5rb05751p4jU5pwuY8k7nUTy_eeIXc9oTeb2puO-G7MdLK3e_yWyP2yR-y-HXjsMKArYhQtw&__tn__=EH-R)

Wikipedia png (https://en.wikipedia.org/wiki/Digital_currency#/media/File:Money_flower.png)

MoneyFlower git jpg (https://github.com/jean-francoisgiraud/DigitalCurrenciesKnowledgeBase/blob/master/MoneyFlower.jpg)

## Offline  
[Offline transactions Crypto without the interne] (https://cointelegraph.com/news/offline-transactions-the-final-frontier-for-global-crypto-adoption)  
Why? Because a cold wallet (not connected to the internet) is protected from online hackers and internet failures or controls by ISPs.  
These are based on [meshnets and wireless radio](https://en.wikipedia.org/wiki/Mesh_networking)

## Cloud based supporting documents  
[My google document](https://docs.google.com/document/d/1MYqwP2GnMW79AKyrDpBttQ4l4NXbyVyBKYrGOTze8oU)  

## Notes Tips LL Lessons Learned
Check user reviews ex bestbitcoinexchange.io (etoro BVC cryptogo binance coinbase localbitcoins CEX.io).  
Always Transfer funds to cold wallets.  
Transferring CC to national currencies via banks is never fast or easy.  
Beware of scams verify validate companies background and transfer funds to cold wallet.  
CC Canadian Company can trade with Canadian banks and offer lower fees because they do not pay Visa 1.5%.   
Only CO and QU do $CDN to crypto.  
All exchanges take commissions on buy sell exchange.   
cryptocompare.com coinbase 4/5 binance 4.8/5.  
Quadriga (exits BTC to $CDN are very difficult exchange or banks fault?).  
Low trade volume (for example in Canada) lead to higher spreads (wider gaps in bid vs ask).  

## Contributing
You can contribute to this project by reporting issues or bugs by creating a Github-Issue. To improve the code you can fork the project in github, create a branch, file a pull request against development.  

## Legal
Signed contributor agreement - ContributorName
2021-01-12. I hereby agree to the terms of this document "https://github.com/jean-francoisgiraud/DigitalCurrenciesKnowledgeBase", with SHA-1 checksum commit 0bd5eeb0e117c00b50615cf848dca8706e0cf993. I furthermore declare that I am authorized and able to make this agreement and sign this declaration.  Signed, ContributorName https://github.com/ContributorName.  

Example: Signed contributor agreement - ContributorName
2021-01-12. I hereby agree to the terms of this document "https://github.com/jean-francoisgiraud/DigitalCurrenciesKnowledgeBase", with SHA-1 checksum commit 0bd5eeb0e117c00b50615cf848dca8706e0cf993. I furthermore declare that I am authorized and able to make this agreement and sign this declaration.  Signed, JF Giraud https://github.com/jean-francoisgiraud.  
Notes: 

## References
bitaddress.org (to generate bitcoin adresses with open source javascript client-side bitcoin wallete generator)  
https://github.com/pointbiz/bitaddress.org  
https://github.com/bitaddress/bitaddress (a non GUI alternative).  
https://walletgenerator.net  
https://en.bitcoin.it/wiki/Wallet_import_format  
https://allprivatekeys.com/  
https://en.wikipedia.org/wiki/Dogecoin  
https://en.wikipedia.org/wiki/BitTorrent
http://merkle.com/papers/DAOdemocracyDraft.pdf  
http://wiki.p2pfoundation.net/DAOs,_Democracy_and_Governance	 
http://merkle.com/papers/DAOdemocracyDraft.pdf  
https://letstalkbitcoin.com/blog/post/epicenter-252-ralph-merkle-revolutionizing-democracy-using-daos-rebroadcast  
https://www.coindesk.com/ralph-merkle-is-back-and-he-wants-to-resurrect-daos  
https://hackernoon.com/daos-and-the-future-of-work-97b4c076f288  
https://en.wikipedia.org/wiki/Digital_currency  
https://medium.com/ostdotcom/decoding-token-economics-insights-from-our-token-engineering-token-economy-design-workshop-at-cfd1a0e39421 https://medium.com/prysmeconomics/economics-of-tokenized-incentives-1-intro-to-pay-for-performance-84e3b9cfffa  
https://medium.com/coinmonks/incentive-fundamentals-for-a-token-economy-3f161ac04ac4  
https://medium.com/coinmonks/hyperledger-fabric-smart-contract-data-model-protobuf-to-chaincode-state-mapping-191cdcfa0b78  
https://medium.com/coinmonks/why-ethereum-1-0-failed-and-bitcoin-succeeded-72e9594b9789  
https://medium.com/coinmonks/crypto-governance-the-startup-vs-nation-state-approach-d36df341878a  
https://medium.com/@pierre_rochard/bitcoin-governance-37e86299470f  
https://medium.com/blockchannel/the-crypto-governance-manifesto-2326e72dc3d0  
https://blog.goodaudience.com/blockchain-governance-101-eea5201d7992  
https://medium.com/amentum/blockchain-communities-and-their-emergent-governance-cfe5627dcf52  
https://medium.com/@FEhrsam/blockchain-governance-programming-our-future-c3bfe30f2d74  
https://medium.com/alpineintel/on-governance-coordination-layers-and-structural-integrity-81a722ba1bc0  
https://a16z.com/2018/07/26/cryptonetworks-cities-analogies/  
https://en.wikipedia.org/wiki/Token_economy  
https://en.wikipedia.org/wiki/Ralph_Merkle  
https://wiki.linuxfoundation.org/_media/openchain/openchainspec-current.pdf  
https://www.linuxfoundation.org/resources/open-source-guides/setting-an-open-source-strategy/  
https://www.openchainproject.org/resources/faq  
https://www.globallegalinsights.com/practice-areas/blockchain-laws-and-regulations/canada

## Appendix
BUY SELL TRADE CRYPTOCURENCIES IN CANADA.  
ID,COMPANY,FEES%,NOTES.  
KR,Kraken,,world#2 in volume; serve NA except NY (because BitLicense).  
CO,Coinbase,4,limited amounts high fees are for buy-only) the limited cryptos (BTC ETH LTC).  
BI,Binance,,note only crypto-crypto best used to exchange cryptos low trading fees (dynamic ~0.1%).  
KU,Kucoin,note,low fees.  
LB,LocalBTC,high,LocalBitcoins.com several traders (cash in person for BTC at their offices).  
QU,Quadriga,1.5-5,complex,CanadianCompany.  

[Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)  
Satoshi Nakamoto satoshin@gmx.com www.bitcoin.org  

Abstract.  
A purely peer-to-peer version of electronic cash would allow online payments to be sent directly from one party to another without going through a financial institution. Digital signatures provide part of the solution, but the main benefits are lost if a trusted third party is still required to prevent double-spending. We propose a solution to the double-spending problem using a peer-to-peer network. The network timestamps transactions by hashing them into an ongoing chain of hash-based proof-of-work, forming a record that cannot be changed without redoing the proof-of-work. The longest chain not only serves as proof of the sequence of events witnessed, but proof that it came from the largest pool of CPU power. As long as a majority of CPU power is controlled by nodes that are not cooperating to attack the network, they'll generate the longest chain and outpace attackers. The network itself requires minimal structure. Messages are broadcast on a best effort basis, and nodes can leave and rejoin the network at will, accepting the longest proof-of-work chain as proof of what happened while they were gone.  

Introduction
Commerce on the Internet has come to rely almost exclusively on financial institutions serving as trusted third parties to process electronic payments. While the system works well enough for most transactions, it still suffers from the inherent weaknesses of the trust based model. Completely non-reversible transactions are not really possible, since financial institutions cannot avoid mediating disputes. The cost of mediation increases transaction costs, limiting the minimum practical transaction size and cutting off the possibility for small casual transactions, and there is a broader cost in the loss of ability to make non-reversible payments for nonreversible services. With the possibility of reversal, the need for trust spreads. Merchants must be wary of their customers, hassling them for more information than they would otherwise need. A certain percentage of fraud is accepted as unavoidable. These costs and payment uncertainties can be avoided in person by using physical currency, but no mechanism exists to make payments over a communications channel without a trusted party. What is needed is an electronic payment system based on cryptographic proof instead of trust, allowing any two willing parties to transact directly with each other without the need for a trusted third party. Transactions that are computationally impractical to reverse would protect sellers from fraud, and routine escrow mechanisms could easily be implemented to protect buyers. In
this paper, we propose a solution to the double-spending problem using a peer-to-peer distributed timestamp server to generate computational proof of the chronological order of transactions. The system is secure as long as honest nodes collectively control more CPU power than any cooperating group of attacker nodes.  

Conclusion  
We have proposed a system for electronic transactions without relying on trust. We started with the usual framework of coins made from digital signatures, which provides strong control of ownership, but is incomplete without a way to prevent double-spending. To solve this, we proposed a peer-to-peer network using proof-of-work to record a public history of transactions that quickly becomes computationally impractical for an attacker to change if honest nodes control a majority of CPU power. The network is robust in its unstructured simplicity. Nodes work all at once with little coordination. They do not need to be identified, since messages are not routed to any particular place and only need to be delivered on a best effort basis. Nodes can leave and rejoin the network at will, accepting the proof-of-work chain as proof of what happened while they were gone. They vote with their CPU power, expressing their acceptance of
valid blocks by working on extending them and rejecting invalid blocks by refusing to work on them. Any needed rules and incentives can be enforced with this consensus mechanism.  

[Lightning Network Scalable, Instant Bitcoin/Blockchain Transactions](https://lightning.network/)  
[Summary](https://lightning.network/lightning-network-summary.pdf)  
The Lightning Network is a decentralized system for instant, high-volume micropayments that removes the risk of delegating custody of funds to trusted third parties. Bitcoin, the world's most widely used and valuable digital currency, allows anyone to send value without a
trusted intermediary or depository. Bitcoin contains an advanced scripting system allowing users to program instructions for funds. There are, however, some drawbacks to bitcoin's decentralized design. Transactions confirmed on the bitcoin blockchain take up to one hour before they are irrevesible. Micropayments, or payments less than a few cents, are inconsistently confirmed, and fees render such
transactions unviable on the network today. The Lightning Network solves these problems. It is one of the first implementations of a multi-party Smart Contract (programmable money) using bitcoin's built-in scripting. The Lightning Network is leading technological development in multiparty financial computations with bitcoin.  
How it Works. Funds are placed into a two-party, multisignature "channel" bitcoin address. This channel is represented as an entry on the bitcoin public ledger. In order to spend funds from the channel, both parties must agree on the new balance. The current balance is stored as the most recent transaction signed by both parties, spending from the channel address. To make a payment, both parties sign a new exit transaction spending from the channel address. All old exit transactions are invalidated by doing so. The Lightning Network does not require cooperation from the counterparty to exit the channel. Both parties have the option to unilaterally close the channel, ending their relationship. Since all parties have multiple multisignature channels with many different users on this network, one can send a payment to any other party across this network. By embedding the payment conditional upon knowledge of a secure cryptographic hash, payments can be made across a network of channels without the need for any party to have unilateral custodial ownership of funds. The 
Lightning Network enables what was previously not possible with trusted financial systems vulnerable to monopolies—without the need for custodial trust and ownership, participation on the network can be dynamic and open for all.  

[Wikipedia Lightning_Network](https://en.wikipedia.org/wiki/Lightning_Network)  
The Lightning Network is a "layer 2" payment protocol that operates on top of a blockchain-based cryptocurrency (like bitcoin). It is intended to enable fast transactions among participating nodes and has been proposed as a solution to the bitcoin scalability problem. It features a peer-to-peer system for making micropayments of cryptocurrency through a network of bidirectional payment channels without delegating custody of funds. Lightning Network implementation also simplifies atomic swaps. Normal use of the Lightning Network consists of opening a payment channel by committing a funding transaction to the relevant base blockchain (layer 1), followed by making any number of Lightning Network transactions that update the tentative distribution of the channel's funds without broadcasting those to the blockchain, optionally followed by closing the payment channel by broadcasting the final version of the settlement transaction to distribute the channel's funds. To perform as intended, Lightning Network required a transaction malleability fix in the layer 1 blockchain, such as Segregated Witness (SegWit) in bitcoin.  

[blockstream.com lightning](https://blockstream.com/lightning/)  
The Lightning Network reduces Bitcoin transaction times and fees. This is achieved by reducing the number of transactions that need to be forever stored on the blockchain. Instead, funds are held in smart contract “payment channels,” and transactions are exchanged outside of the blockchain between transacting users. The final state of the payment channel balance can be broadcast to the Bitcoin network at any time, securely settling the funds on the blockchain.

[Blockchain vs Tangle: Untangling The IOTA Tangle](https://academy.ivanontech.com/blog/blockchain-vs-tangle-untangling-the-iota-tangle)  

# Changelog  
To Do: figure out how to show images, links to images in this folder do not appear automatically.  
You can send us a pull request to modify this document then the full history of changes will be available to you.  
20210111 added section on kippu (KIP) and BCH SLP.  
20210111 added sections after 9 and removed numbering where not necessary. Index is now hyperlinked to sections.  
2019 may. Minor editions and added data quality control (Accuracy	Completeness	Consistency	Credibility	Currentness	Accessibility	Compliance. Confidentiality	Efficiency	Precision	Traceability	Understandability	Availability	Portability	Recoverability).  
2018 march. Visa, MC, Amex from all Canadian Banks disabled digital currency purchases (tried coinbase and others).  
