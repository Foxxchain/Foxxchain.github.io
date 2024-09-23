---
description: >-
  Blockchain technology is the concept or protocol behind the running of the
  blockchain. Blockchain technology makes cryptocurrencies like Bitcoin work
  just like the internet makes email possible.
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: false
  outline:
    visible: true
  pagination:
    visible: true
---

# ⚛️ Blockchain

## <mark style="color:blue;">Blockchain 101: Blockchain For Beginners</mark> <a href="#blockchain101" id="blockchain101"></a>

#### For many, blockchain technology is still a mysterious or even intimidating topic. Some even remain skeptical that we’ll use this technology in the future. This skepticism that exists today is understandable because we’re still very early in the development and widespread adoption of blockchain technology.

{% hint style="info" %}
[Upgrade](cryptocurrency-wallets/qs.foxxchain-network/#qs.foxxchain-network) for Live Updates and Tools
{% endhint %}

Blockchain technology is the concept or protocol behind the running of the blockchain. Blockchain technology makes [cryptocurrencies](http://blockgeeks.com/guides/what-is-cryptocurrency/) (digital currencies secured by cryptography) like Bitcoin work just like the internet makes email possible.

The blockchain is an immutable (unchangeable, meaning a transaction or file recorded cannot be changed) distributed digital ledger (digital record of transactions or data stored in multiple places on a computer network) with many use cases beyond cryptocurrencies.

![What is Blockchain](https://blockgeeks.com/wp-content/uploads/2016/09/blockchain.png)

Immutable and distributed are two fundamental blockchain properties. The immutability of the ledger means you can always trust it to be accurate. Being distributed protects the blockchain from network attacks.

Each transaction or record on the ledger is stored in a “block.” For example, blocks on the Bitcoin blockchain consist of an average of more than 500 Bitcoin transactions.

The information contained in a block is dependent on and linked to the information in a previous block and, over time, forms a chain of transactions. Hence the word blockchain.

### Types of Blockchains

There are four types of blockchains:

#### 1. Public Blockchains

Public blockchains are open, decentralized networks of computers accessible to anyone wanting to request or validate a transaction (check for accuracy). Those (miners) who validate transactions receive rewards.

Public blockchains use proof-of-work or proof-of-stake consensus mechanisms (discussed later). Two common examples of public blockchains include the Bitcoin and Ethereum (ETH) blockchains.

#### 2. Private Blockchains

Private blockchains are not open, they have access restrictions. People who want to join require permission from the system administrator. They are typically governed by one entity, meaning they’re centralized. For example, Hyperledger is a private, permissioned blockchain.

#### 3. Hybrid Blockchains or Consortiums

[Consortiums](https://blockchain.intellectsoft.net/blog/how-the-consortium-blockchain-works/) are a combination of public and private blockchains and contain centralized and decentralized features. For example, Energy Web Foundation, Dragonchain, and R3.

**Take note:** There isn’t a 100 percent consensus on whether these are different terms. Some make a distinction between the two, while others consider them the same thing.

#### 4. Sidechains

A sidechain is a blockchain running parallel to the main chain. It allows users to move digital assets between two different blockchains and improves scalability and efficiency. An example of a sidechain is the Liquid Network.

### History of Blockchain

_Blockchain isn’t just a database, it’s a new technology stack with ‘digital trust’ that is revolutionizing the way we exchange value and information across the internet, by taking out the ‘gatekeepers’ from the process. For a complete and more detailed deep dive check out our article:_ [_A Concise History of Blockchain Technology_](https://blockgeeks.com/guides/history-of-blockchain/)

Blockchain history goes back farther than you might imagine, but we’ve condensed it by answering four critical questions:

#### Who Invented Blockchain?

The first blockchain-like protocol was proposed by cryptographer David Chaum in 1982. Later in 1991, Stuart Haber and W. Scott Stornetta wrote about their work on [Consortiums](https://www.anf.es/pdf/Haber\_Stornetta.pdf).

But it was Satoshi Nakamoto (presumed pseudonym for a person or group of people) who invented and implemented the first blockchain network after deploying the world’s first digital currency, Bitcoin.

_Cryptography is a deep and fascinating discipline with a history that goes back further than blockchain. For a richer understanding of  how cryptography helps blockchain technology, check out:_ [_Why Cryptography Makes Blockchain Unstoppable_](https://blockgeeks.com/guides/blockchain-cryptography/)

#### Who Owns Blockchain Technology?

Because blockchain technology is the technology behind the blockchain, it cannot be owned. It’s like the internet. But anyone can use the technology to run and own their own blockchains.

#### Who Founded Bitcoin?

Satoshi Nakamoto.

#### Who Sent and Received the First Bitcoin Transaction?

Nakamoto sent ten bitcoins to Hal Finney, who built the first reusable proof-of-work system in 2004.

### How Does a Public Blockchain Work (Step-by-Step)

_For a more in-depth account of the next section, check out the thorough discussion in:_ [_What is Blockchain Technology and How Does it Work?_](https://blockgeeks.com/guides/how-does-blockchain-work/)

**Let’s start with an oversimplification.**

As a society, we created ledgers to store information—and they have a variety of applications. For example, we use ledgers in real estate to store a house’s records, such as when alterations were made or the house was sold. We also use ledgers in bookkeeping to record all the transactions a company makes.

Bookkeeping mostly relies on double-entry accounting to store transactions. Although this is a step-up from single-entry accounting that lacks transparency and accountability, double-entry accounting also has its pitfalls: Entries are accounted for separately, making it difficult for one counterparty to verify the other’s records.

Records stored using traditional ledgers are also easy to tamper with, meaning you can easily edit, remove, or add a record. As a result, you’re less likely to trust that the information is accurate.

Public blockchains solve both these problems – and the way we trust – by evolving the traditional bookkeeping model to [triple-entry bookkeeping](https://medium.com/dataseries/triple-entry-accounting-system-a-revolution-with-blockchain-768f4d8cabd8): transactions on a blockchain are cryptographically sealed by a third entry. This creates a tamper-proof record of transactions stored in blocks and verified by a distributed consensus mechanism.

These consensus mechanisms also ensure new blocks get added to any blockchain. An example of a consensus mechanism is proof-of-work (PoW), often referred to as “mining.”

Mining isn’t universal to all blockchains; it’s just one type of consensus mechanism currently used by Bitcoin and Ethereum, though Ethereum plans to move to another—proof-of-stake (PoS)— by 2022.

Here’s how this process works with Bitcoin. When sending Bitcoin, you pay a small fee (in bitcoin) for a network of computers to confirm your transaction is valid. Your transaction is then bundled with other transactions pending in a queue to be added to a new block.

The computers (nodes) then work to validate this list of transactions in the block by solving a complex mathematical problem to come up with a [hash](http://blockgeeks.com/guides/video-guide-what-is-hashing/), which is a 64-digit hexadecimal number.

Once solved, the block is added to the network—and your fee, combined with all other transaction fees in that block, is the miner’s reward. It’s that simple.

Each new block added to the network is assigned a unique key (via cryptography). To obtain each new key, the previous block’s key and information are inputted into a formula.

As new blocks are continually added through the ongoing mining process, they become increasingly secure and harder to tamper with. Anyone caught trying to edit a record will simply be ignored. All future blocks then depend on information from prior blocks—and this dependency from one block to the next forms a secure chain: the blockchain.

You can see this depicted below for house records stored on the blockchain. For example, Block 2 provides a key after taking all the information from Block 1 into account (including the key) and inputting it into a formula. Block 3, in turn, provides a new key after taking all the information from Block 1 and Block 2 into account (including the key) and inputting it into a formula. And so, the process repeats itself indefinitely.

**Now, let’s dig deeper**, exploring [proof-of-work (PoW) vs. proof-of-stake (PoS)](http://blockgeeks.com/guides/proof-of-work-vs-proof-of-stake/) and the blockchain trilemma, which are fundamental to the public blockchain’s functioning.

#### Proof of Work (PoW) vs. Proof of Stake (PoS)

A public blockchain functions through consensus mechanisms: the process for validating transactions without a third party like a bank.

PoW and PoS are two such mechanisms. While their goal—to reach a consensus that a transaction is valid—remains the same, how they get there is a little different.

**What Is PoW?**

PoW, the **technical term for mining**, is the original consensus mechanism. It is still used by Bitcoin and Ethereum as of writing but, as mentioned, Ethereum will move to PoS by 2022. PoW is based on cryptography, which uses mathematical equations only computers can solve.

The example in the previous section of how blocks get added to the Bitcoin Blockchain explains this system.

The two big problems with PoW are that it uses a lot of electricity and can only process a limited number of transactions simultaneously (seven for Bitcoin). Transactions typically take at least ten minutes to complete, with this delay increasing when the network is congested. Though compared to the days-long wait required to wire money across the globe, or even to clear a check, Bitcoin’s ten-minute delay is quite remarkable.

Other consensus mechanisms were created to solve these PoW problems; the most popular being PoS.

**What Is PoS?**

PoS still uses cryptographic algorithms for validation, but transactions get validated by a chosen validator based on how many coins they hold, also known as their stake.

Individuals aren’t technically mining, and there’s no block reward. Instead, blocks are ‘forged.’ Those participating in this process lock a specific number of coins on the network.

The bigger a person’s stake, the more mining power they have—and the higher the chances they’ll be selected as the validator for the next block.

To ensure those with the most coins aren’t always selected, other selection methods are used. These include randomized block selection (forgers with the highest stake and lowest [hash value](http://blockgeeks.com/guides/cryptographic-hash-functions/) are chosen) and coin age selection (forgers are selected based on how long they’ve held their coins)

The results are faster transaction times and lower costs. The NEO and Dash cryptocurrencies, for example, can send and receive transactions in seconds.

#### Blockchain or Scalability Trilemma: Decentralization, Security, and Scalability

Most blockchain projects are built around three core properties: decentralization, scalability, and security. Developers are constantly trying to balance these aspects, so one isn’t compromised.

But they often have to sacrifice one for the others. The ‘[blockchain trilemma](https://vitalik.ca/general/2021/04/07/sharding.html),’ concept was first coined the ‘scalability trilemma’ by Ethereum founder, Vitalik Buterin.

Let’s look at these concepts in more detail and explore the tradeoffs:

**Decentralization**

Decentralization means there’s no central point of control. Instead, decisions are made via consensus over a distributed network of computers.

There is, however, one significant tradeoff: speed. Sending transactions takes longer because multiple confirmations are required to validate a transaction. Hence why Bitcoin is slow.

**Scalability**

Scalability is the ability of the system to cope with a growing number of transactions. Scalability is crucial for mass adoption because any system needs to operate efficiently as more people use it.

Below is a rough breakdown of how many transactions Ethereum, Bitcoin, and credit card companies can process per second:

* Bitcoin: seven per second
* Ethereum: 30 per second
* Credit cards: 5,000 [credit card transactions](https://www.cardrates.com/advice/number-of-credit-card-transactions-per-day-year/) per second with the ability to process much more if needed. Visa, for example, can process up to 24,000 transactions per second.

But achieving scalability often comes at the expense of decentralization. EOS, for example, promises a maximum of 4000 TPS but has come under criticism for being too centralized.

**Security**

Security is the ability of a blockchain to be protected from attacks. Unfortunately, exchanges and source code have been hacked on many occasions, suggesting that many developers focus on [scalability and decentralization](http://blockgeeks.com/guides/decentralized-scalability/) at the expense of security.

### What Is the Difference Between Bitcoin and Ethereum Blockchains?

Bitcoin and Etherum are the two biggest cryptocurrencies and blockchains, so discussing and comparing them makes sense.

#### Bitcoin Basics

The Bitcoin network is a public, decentralized peer-to-peer payment network that allows users to send and receive [bitcoins](http://blockgeeks.com/guides/what-is-bitcoin/) without a bank getting involved. The digital currency or bitcoin token uses the ticker symbol BTC, and is the only cryptocurrency traded on the Bitcoin network.

Transactions are recorded using a digital ledger, and nodes ensure the PoW consensus mechanism is followed (or that mining happens). For many, Bitcoin seems complicated, but it isn’t when you view it as a combination of three things:

* **A peer-to-peer payment system**: You can send money (BTC) from one person or company to another without the need for a bank. Sending money this way is faster, more secure, and cheaper than using traditional methods.
* **A decentralized system like the internet**, so it’s not controlled by one entity and cannot be stopped by a third party.
* **A store of value like gold (often called digital gold)**, but much easier to transfer than gold.

#### Ethereum Basics

In 2013, after traveling, meeting with bitcoin developers, and discovering Bitcoin’s limitations, Vitlaik Buterin decided to improve upon the Bitcoin blockchain and built [Ethereum](http://blockgeeks.com/guides/ethereum/).

The Ethereum network is a public, decentralized peer-to-peer network. Like Bitcoin, it uses [nodes](http://blockgeeks.com/guides/what-are-ethereum-nodes-and-sharding/) and allows users to send and receive cryptocurrency—in this case, Ether.

The network is much more than a payment system—it was primarily created to deploy decentralized applications (dapps) and smart contracts.

Dapps are simply ‘decentralized apps,’ or computer programs that interact with the Ethereum blockchain. [Smart contracts](http://blockgeeks.com/guides/smart-contracts/), however, operate on the Ethereum blockchain, and are contracts that automatically execute without an intermediary once certain conditions (written into computer code) are met. For example, a smart contract could be programmed to send a designated person a portion of your Bitcoin when you die.

#### Ethereum vs. Bitcoin Blockchains

In summary, Bitcoin and Ethereum networks are public, decentralized peer-to-peer networks with their own tokens: bitcoins and Ether. Both rely on cryptography, and both use digital ledger technology. _For a complete Ethereum vs. Bitcoin match up check out our deep dive post:_ [_Ethereum Vs Bitcoin: What’s the Difference?_](https://blockgeeks.com/guides/difference-between-bitcoin-and-ethereum/)&#x20;

But they differ significantly in purpose and capability. Bitcoin is a decentralized payment system and a store of value. Its blockchain is a database of all bitcoin transactions and tracks their ownership. Ethereum is more than a payment system and allows smart contracts and apps to be built on it, making it a more sophisticated blockchain.

### What Are the Benefits of Blockchains Over Traditional Finance?

1. **Trustless**: The blockchain is immutable and automates trusted transactions between counterparties who do not need to know each other. Transactions are only executed when programmed conditions are met by both parties.
2. **Unstoppable**: Once the conditions programmed into a blockchain protocol are met, an initiated transaction cannot be undone, changed, or stopped. It’s going to execute and nothing – no bank, government, or third party – can stop it.
3. **Immutable**: Records on a blockchain cannot be changed or tampered with – Bitcoin has never been hacked. A new block of transactions is only added after a complex mathematical problem is solved and verified by a consensus mechanism. Each new block has a unique cryptographic key resulting from the previous block’s information and key being added into a formula.
4. **Decentralized**: No single entity maintains the network. Unlike centralized banks, decisions on the blockchain are made via consensus. Decentralization is essential because it ensures people can easily access and build on the platform, and there are multiple points of failure.
5. **Lower Cost**: In the traditional finance system, you pay third parties like banks to process transactions. The blockchain eliminates these intermediaries and reduces fees, with some systems returning fees to miners and stakers.
6. **Peer-to-Peer:** Cryptocurrencies like Bitcoin, let you send money directly to anyone, anywhere in the world, without an intermediary like a bank charging transaction or handling fees.
7. **Transparent**: Public blockchains are open-source software, so anyone can access them to view transactions and their source code. They can even use the code to build new applications and suggest improvements to the code. Suggestions are accepted or rejected via consensus.
8. **Universal Banking**: [2 Billion](https://globalfindex.worldbank.org/sites/globalfindex/files/chapters/2017%20Findex%20full%20report\_chapter2.pdf) people globally do not have a bank account. Because anyone can access the blockchain to store money, it’s a great way to bank the unbanked and protect against theft that can happen due to holding cash in physical locations.

### What Are the Disadvantages of Blockchains?

Public open source blockchains are not without their hazards and challenges. Here is a list of the top concerns:

#### 1. Environmental Impact

Blockchain networks like Bitcoin use a lot of electricity to validate transactions, leading to environmental concerns. For example, Bitcoin [consumes more electricity than a small, medium-sized European country](https://www.ft.com/content/1aecb2db-8f61-427c-a413-3b929291c8ac?segmentid=acee4131-99c2-09d3-a635-873e61754ec6), and [Bitcoin mining is threatening China’s climate change goals](https://www.cnbc.com/2021/04/08/chinas-bitcoin-mining-is-threatening-its-climate-change-targets.html).

However, many would argue that Bitcoin is held to higher environmental standards than anyone and anything. This may be true, especially if you consider that the blockchain and Bitcoin are an alternative to the traditional finance system that uses much more electricity and has a much larger environmental impact.

A [study by Galaxy Digital](https://docsend.com/view/adwmdeeyfvqwecj2) suggests Bitcoin energy consumption is less than half that of the traditional banking system. If anything, you could argue that Bitcoin is a step in the right direction for the environment.

No one is saying that making strides to lowering the carbon footprint shouldn’t be on the agenda (this is already happening with some mining farms shifting to renewable energy sources like solar panels and the [El Salvadoran President calling for a plan to use geothermal energy (volcanoes) to mine Bitcoin](https://www.forbes.com/sites/nicholasgans/2021/06/09/el-salvador-president-calls-for-a-volcanic-geothermal-bitcoin-mining-plan/?sh=5ab662a227ec)).

But it’s crucial to maintain a balanced view when viewing the cost, environmental impact, and blockchain benefits.

#### 2. Personal Responsibility

One of blockchains and cryptocurrencies’ most significant advantages is also its biggest weakness. When you invest in public open-source blockchains by mining or buying cryptocurrencies and store it in your cryptocurrency wallet (your wallet is like your bank account, except only you can access it and have the passwords), only you control your money.

You are your own bank— and this is great! But if you lose your seed phrases – the list of words that give you access to recover your wallets – there is no recourse (compared to banks where you can reset your password). Your money is lost forever.

Unsurprisingly, a large portion of Bitcoin remains permanently lost. According to [some estimates](https://decrypt.co/37171/lost-bitcoin-3-7-million-bitcoin-are-probably-gone-forever), 20% or 3.7 million of the currently minted Bitcoin is probably lost forever.

#### 3. Growing Pains

Even though public blockchains remain more efficient than traditional banking systems, decentralization comes at the cost of scalability. Trying to grow blockchain networks to global capacity, in turn, is the root cause of speed inefficiencies. It’s why, as we saw, Bitcoin and Ethereum can only process a maximum of seven and 30 transactions, respectively, compared to Visa’s 24,000.

Luckily solutions are being built to improve scalability and the speed of transactions. For example, the [lightning network](https://blockgeeks.com/guides/lightning-network/) allows transactions to happen off the Bitcoin blockchain to speed up transactions. On Ethereum, many innovative Layer 2 (L2) solutions are being developed to improve scalability and speed including rollups, zero-knowledge proofs and side chains.

#### 4. False Narratives

Some cryptocurrencies are undoubtedly used in unlawful activity. The most famous example is Silk Road: people laundered money and bought drugs on the platform using Bitcoin.

However, this is no different from the illegal activity that constantly happens when people use other currencies like the Dollar.

This false narrative that cryptocurrencies are only or mainly used for illicit activities only delays their inevitable adoption, which can hugely benefit everyone, including the financial system.

### Promising Blockchain Use Cases and Killer Applications

_For an even more in-depth discussion of the most interesting and disruptive blockchain use cases as of 2021 check our guide:_ [_Disruptive Blockchain Technology Use Cases 2021_](https://blockgeeks.com/guides/blockchain-use-cases/)

Blockchain technology is currently used across various industries like supply chain, healthcare, retail, media and advertising, financial services, insurance, travel and transportation, oil and gas, and gaming.

Here are some promising use cases:

1. **Cryptocurrencies**: The ‘killer app’ of blockchains today is internet money. Cryptocurrencies let you transfer value faster and cheaper across borders without a bank. Besides Bitcoin and Ethereum, other digital currency examples include Polkadot (DOT), NEO, [Cardano](http://blockgeeks.com/guides/what-is-cardano/) (ADA), Tether (USDT), Binance Coin (BNB), and Litecoin (LTC).
2. **Smart Contracts**: These [blockchain applications](https://blockgeeks.com/guides/blockchain-applications/) are contracts that automatically execute without an intermediary once conditions written into the computer code are met.
3. [Decentralized Banking](http://blockgeeks.com/guides/decentralized-banking/): The use of blockchain technology is also proliferating in banking. For example, many banks like Barclays, Canadian Imperial Bank, and UBS are interested in [how blockchain can make their back-office settlement systems more efficient](https://www.internationalinvestment.net/internationalinvestment/news/3504643/banks-blockchain-office-business).
4. **Video Games/Art**: You may have heard Crypto Kitties—a game launched on the Ethereum blockchain. One of the virtual pets in the game was sold for over $100,000.
5. [Peer-to-peer Energy Trading](https://www.sciencedirect.com/science/article/abs/pii/S0306261920316585): People buy or sell energy directly without an intermediary.
6. **Supply chain and logistics tracking**: Blockchain is being used to track precious metals’ origins and foods. For example, [Walmart and IBM worked together to create a food traceability system](https://theleadershipnetwork.com/article/how-walmart-used-blockchain-to-increase-supply-chain-transparency) based on open-source ledger technology, making it easier to trace contaminated food.
7. **Healthcare process optimization**: Blockchain can speed up the time required to pay health insurance payments to patients and store and securely share medical data and records.
8. **Real estate processing platform**: Property ownership records can be securely stored and verified on the blockchain. These records cannot be tampered with, so you can trust they’re accurate and more easily verify property ownership.
9. **NFT marketplaces**: These are marketplaces that allow you to buy nonfungible tokens (NFTs): digital tokens of things like paintings and clothing.
10. **Music royalties tracking**: Blockchain can trace music streams and immediately pay those who contributed to a song.
11. **Anti-money laundering tracking system**: Authorities can more easily track the original source of money because every transaction on the blockchain is recorded and leaves behind a tamper-proof trail.
12. **Personal identity security**: Traditional systems for storing identities are insecure and fragmented. Blockchain provides a unified, immutable, and interoperable infrastructure so you can store and manage records securely and efficiently.
13. **New insurance distribution methods**: For example, peer-to-peer insurance, parametric insurance, and microinsurance.
14. **Automated Advertising Campaigns**: Advertisers can use smart contracts to automate advertising campaigns, e.g., an audience is only shown an ad when specific criteria are met.

### How to Invest in Blockchain Technology

With blockchain offering some promising use cases, helping many companies become more efficient, and attracting big companies like Amazon and Tesla, it can be an attractive investment.

But there are risks: It’s a new technology, and many projects will not pan out. So, invest only what you can afford to lose, do your own research to determine if the project (or [initial coin offering](http://blockgeeks.com/guides/initial-coin-offering/)) is worth investing in, and decide what level of exposure you want.

For example, you can get more exposure by investing in cryptocurrencies directly instead of an exchange-traded fund (ETF).

That being said, here are a variety of ways you can invest in the blockchain depending on your goals and risk tolerance:

1. **Buy shares in companies using blockchain** (e.g., Visa, Walmart, and Siemens) on traditional stock exchanges like the NYSE. You can buy shares by using an online broker such as [Vanguard](https://investor.vanguard.com/home) and [Betterment](https://www.google.com/search?client=safari\&rls=en\&q=betterment\&ie=UTF-8\&oe=UTF-8) (U.S.).
2. **Invest in companies with Bitcoin on their balance sheet**, e.g., Square, WeWork, MicroStrategy, and Tesla. Again, use an online broker to buy shares.
3. [**Buy cryptocurrencies like Bitcoin**](http://blockgeeks.com/guides/how-to-buy-bitcoin/) or Ethereum directly on Centralized Finance (CeFi) or Decentralized (DeFi) exchanges. Centralized exchanges were the norm in the crypto world until decentralized exchanges arrived. With centralized exchanges, you don’t have your own private keys, and the exchange is the custodian for storing your funds. Decentralized exchanges are peer-to-peer, and there’s no intermediary. Examples of CeFi exchanges include [Binance](https://www.binance.com/en), [Kraken](https://www.kraken.com/), [Bittrex](https://global.bittrex.com/), [Bitfinex](https://www.bitfinex.com/), [Luno](https://www.luno.com/), and [Coinbase](https://www.coinbase.com/). Examples of DeFi exchanges include [Uniswap](https://uniswap.org/), [Compound](https://compound.finance/), [KyberSwap](https://kybenswap.com/swap), [Airswap](http://airswap.io/), [IDEX](https://idex.io/), [SushiSwap](https://sushi.com/), [Balancer](https://balancer.fi/), and [Totle](https://www.totle.com/).
4. **Invest in crypto exchange-traded funds (ETFs)**. ETFs are a basket of securities that track an asset or index you can buy or sell on an exchange throughout the day. For example, many traditional ETFs will include bonds, currencies, commodities, and stocks and track the S\&P 500 Index. In the crypto space, you get a variety of ETFs you can invest in, such as a Bitcoin ETF that tracks the price of Bitcoin. Each ETF will differ depending on who issues it. Companies that offer ETFs include [Grayscale](https://grayscale.com/), [Galaxy Digital](https://www.galaxydigital.io/), and [Gemini](https://www.gemini.com/).
5. **Invest in crypto mining companies such as** [**Riot**](https://www.riotblockchain.com/)**,** [**Hive**](https://www.hiveblockchain.com/)**, and** [**Marathon**](https://marathondh.com/). Many mining companies let investors participate indirectly by offering equity in their companies. To invest in Riot, use an American-based online broker like Robinhood. To invest in Hive and Marathon, use a Canadian-based broker like Questrade, TD Direct Investing, or BMO InvestorLine.
6. **Buy crypto hardware and mine cryptocurrency yourself**. While Bitcoin mining requires a large capital outlay, there are other tokens you can mine for a reasonably low barrier to entry. For example, Helium miners cost roughly $500 and mint HNT using the ‘proof of coverage’ consensus protocol to verify new blocks. Get started with cryptocurrency mining by reading our [short guide on Bitcoin mining](https://blockgeeks.com/what-is-bitcoin-mining-an-easy-guide/).
7. Invest in mining pools. An alternative to mining cryptocurrency yourself is to join a mining pool. Mining pools pool together the computational power of others on the network to improve the chances of mining a block. The rewards for all blocks mined are shared among miners in the pool. [Slush Pool](https://slushpool.com/home/) is a popular mining pool.

### Blockchain Companies to Invest in 2021

_If you’re looking to get started with crypto investing, we’ve created a comprehensive step-by-step guide you can follow to get started here:_ [_How To Invest in Cryptocurrencies: The Ultimate Beginners Guide_](https://blockgeeks.com/guides/how-to-invest-in-cryptocurrencies/)

Here is a comprehensive list of public blockchain companies to invest in. We have segmented them based on these categories: banking, supply chain, health care, energy, insurance, travel, real estate, exchanges, and mining.

These public companies are either using blockchain, have cryptocurrency on their balance sheets, allow you to trade cryptocurrency, or are mining cryptocurrency.

_\*Technically, Binance is not a public company, but you can invest in it by purchasing their own digital currency (BNB). You can use their currency to pay for transaction and trading fees on the exchange. This is also true for DeFi exchanges like Uniswap, 1inch, and PancakeSwap._

### Traditional Finance and Blockchain Investment Strategies

In some ways, the process of investing in shares and cryptocurrencies is the same. First, you can buy cryptocurrencies on exchanges like you can buy shares through an online broker.

Second, you are also able to apply traditional investment principles to investing in cryptocurrencies and the blockchain. For example, you can invest the same amount of money into Bitcoin each month regardless of price (dollar-cost averaging) to remove any emotion out of the investment process.

But there are also investment strategies that are unique to the blockchain and cryptocurrencies, like yield farming.

Read on to learn about ten common traditional finance and blockchain investment strategies you can use when investing in public blockchain companies and cryptocurrencies.

#### Overview of 10 Major Investment Strategies

*
  1. **Growth Investing:** Investors look for companies that demonstrate above-average growth. Investors using this strategy will often still invest in shares even if they seem expensive.To narrow down your search, focus on industries currently doing well or have historically performed. With the blockchain technology market expected to grow in size, there are bound to be several companies with strong growth potential.
  2. **Value Investing:** Investors look for undervalued companies, e.g., their price doesn’t fully reflect their value. Successful value investing often requires that you hold your shares for the long term.
  3. **Dividend Growth Investing:** Investors invest in companies that have a history of paying out dividends. You can look at a company’s financial statements to see if they pay out dividends. Look for a yield of between 2-6%.
  4. **Indexing:** This is more of a cautious and passive investment strategy, but indexed investors often outperform more active investors. These investors typically invest in an index fund.An index fund consists of pooled funds from investors, is managed by a fund manager, and automatically invests in the companies of a specific index like the S\&P 500 to effectively track against the index’s performance.It is different from an ETF in that you can only buy or sell index funds at the end of the day and not throughout. An example of a cryptocurrency index fund is the Bitwise 10 Crypto Index Fund ([BITW](https://www.investopedia.com/markets/quote?tvwidgetsymbol=bitw)).
  5. **Day Trading:** Day trading is a more active and aggressive short-term trading strategy. Investors frequently trade throughout the day to capitalize on small market movements to make a profit. Day traders will use technical analysis to develop trade ideas around how the market will move. Day trading cryptocurrency is equally lucrative and risky due to highly volatile assets.
  6. **Algorithmic Trading:** Also known as automatic trading, this investment strategy involves using computer programs to execute trades based on pre-programmed instructions such as price, time, etc. [A large portion of the American market consists of algorithmic trading](https://therobusttrader.com/what-percentage-of-trading-is-algorithmic/). AlgoTrader is an automated trading program you can use for Bitcoin trading.
  7. **Contrarian Investing:** Contrarian investors purposely go against the market sentiment. They buy when people are selling and sell when people are buying.By following the [Bitcoin Fear and Greed Index](https://blockgeeks.com/guides/bitcoin-fear-and-greed-index/), you can get a good idea of the prevailing sentiment in the Bitcoin market and then do the opposite: buy when people are fearful and sell when they’re greedy (_see Fear & Greed Index below)_.
  8. **Arbitrage:** This strategy involves taking advantage of price differences of the same asset between markets. You buy the asset in one market and then sell it for a higher price in another.Because cryptocurrencies like Bitcoin often differ in price between countries, there are great opportunities to profit from this strategy.In a nutshell, traders will buy cryptocurrency on an overseas exchange (for a lower price) and then transfer it to a local exchange and sell it for a higher price.As [Business Tech reports](https://businesstech.co.za/news/industry-news/486201/why-cryptocurrency-arbitrage-is-taking-the-industry-by-storm/), you can make 2-4% per trade using the right investment platform. Just make sure you follow local exchange control laws because there are usually limits to how much local currency you can move beyond the borders.
  9. **Yield Farming:** This blockchain-specific investment strategy involves lending your cryptocurrency to someone else via smart contracts.The lendee pays you a fee for your services. Yield farmers often move their cryptocurrency between different lending platforms to maximize returns. A few yield farming platforms include Compound Finance, Aave, and MarketDAO. Learn more about [DeFi yield farming](https://blockgeeks.com/guides/what-is-defi-yield-farming/).
  10. **Diversification**: Spread your risk and invest in different assets and companies to limit your overall downside while exposing you to more opportunities to make money. Diversification is more than just an investment strategy; it’s a smart way to invest that most financial experts and brokers encourage.This strategy works well for traditional finance and cryptocurrency.In traditional markets, you can spread risk across bonds, money markets, and shares— and even diversify your share portfolio by investing across industries.For cryptocurrencies and blockchain, you can invest in different public blockchain companies and also cryptocurrencies with different use cases like Bitcoin (payments), Ethereum (smart contracts), Monero (privacy), and XRP (cross border payments).If you really want to prioritize diversification, you should invest across traditional and crypto markets, and rebalance your portfolio as needed.

![Latest Crypto Fear & Greed Index](https://alternative.me/crypto/fear-and-greed-index.png)

#### How can businesses benefit from blockchain?

Let’s look at the business-specific advantages of blockchain technology.

– As mentioned above, the blockchain is a great way to build trust among entities that have never worked together. As such, it is an excellent way for businesses to work together without requiring a trusted third party.

– The blockchain can help create a consortium of businesses and provide an operational structure with no central “leader.” This can allows multiple businesses to interact effectively and share information.

– The fact that all data stored within blockchains are immutable has game-changing security implications. It’s no longer possible for malicious centralized parties to tamper with crucial data.

– By removing the need for trusted third parties, the overall organizational costs go down significantly. Plus, taking away these intermediaries drastically increases operational speeds. For example, Walmart used blockchain to trace the source of sliced mangoes in seconds. Normally, this process would take a week.

– The blockchain is a major boon for companies that rely on or operate supply chains. The blockchain’s transparency helps fix a majority of the issues present in traditional supply chain structures. For example, not only has Walmart successfully applied blockchain in their supply chain via IBM, but the medical industry is actively using the tech in their crackdown on counterfeit medication.

### Blockchain Is the Present and the Future

With many promising real-world use cases like faster cross-border payments and smart contracts, blockchain technology is here to stay.

As more companies realize how the blockchain can help them, they’ll commit more resources, money, and time into the technology—and even more use cases will emerge. While we understand that blockchain technology will remain a complex topic for many, it really doesn’t have to be for you.

We hope this guide gave you the confidence to have conversations with friends and acquaintances about the blockchain and that it demystified and simplified an often scary topic. Refer to it whenever you need to brush up on any blockchain concepts.

Most importantly, we hope it lit a small fire in you to learn even more about a technology that’s fundamentally changing the way we trust and exchange value.

{% content-ref url="../../policies/disclaimer.md" %}
[disclaimer.md](../../policies/disclaimer.md)
{% endcontent-ref %}
