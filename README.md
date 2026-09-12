# Cryptocurrency guide for beginners
**Language**: [english (current)](https://github.com/crysao/crypto-guide) | **Язык**: [русский](https://github.com/crysao/crypto-guide_ru)

> [!IMPORTANT]
> Translated by AI

# Contents
1. [**What is cryptocurrency. Basic concepts**](https://github.com/crysao/crypto-guide#what-is-cryptocurrency-basic-concepts)
2. [**How blockchain works in simple terms**](https://github.com/crysao/crypto-guide#how-blockchain-works-in-simple-terms)
3. [**Bitcoin and other well-known coins, blockchain networks**](https://github.com/crysao/crypto-guide#bitcoin-and-other-well-known-coins-blockchain-networks)
4. [**Types of wallets. Choosing and creating your first wallet**](https://github.com/crysao/crypto-guide#types-of-wallets-choosing-and-creating-your-first-wallet)
5. [**Security. Fraud**](https://github.com/crysao/crypto-guide#security-fraud)

# What is cryptocurrency. Basic concepts
**Cryptocurrency** is a digital currency that has no physical form _(banknotes, coins)_ and no single central bank, while the security of transactions with it _(transfer of digital assets from one wallet to another)_ is ensured through encryption.

All transactions are recorded in a shared database called the **blockchain** _(a continuous sequential chain of blocks with transaction records, stored simultaneously on many independent computers)_. To store/send and perform other operations with cryptocurrency, a special **wallet** is required _(a tool for storing access keys and managing digital assets in the blockchain)_, which is created on the basis of a **seed phrase** _(a secret set of words (usually 12 or 24), which is the key to accessing your digital assets)_.

If a non-custodial wallet is used, you are responsible for the safe storage of the seed phrase, since if it leaks, an attacker will be able to freely withdraw all your funds. In custodial wallets, you shift responsibility for storing the phrase to a third party, which on the one hand gives an easy start for beginners, but on the other hand transfers **FULL** control over your funds to that very third party

# How blockchain works in simple terms
**Blockchain** is a digital ledger that is stored in a decentralized network of thousands of computers using special tools to exchange information about the latest transactions. Such a storage system _(unlike a single server)_ is more resistant to various failures and hacks. Each time one of the participants in the decentralized blockchain network _(a node)_ completes a transaction, it is time-stamped, registered and added to the digital ledger _(block)_ of that user. All transactions are distributed among the network nodes. After being added, the data is almost impossible to change or delete unnoticed. Cryptography is used to protect information: each block has a unique hash and is linked to the previous one, which helps prevent data forgery _(changing one signature breaks the entire chain)_

The operation of the blockchain begins with the user creating a transaction _(for example, sending data or cryptocurrency to another person through a special wallet)_. Then the network computers (nodes) check whether the transaction is really possible and complies with the rules. After that, the network participants use a consensus mechanism to agree that the transaction is correct. Verified transactions are combined into a block, which is linked to the previous block and added to the chain. After the block is added, the transaction receives confirmation and becomes part of the permanent history of the blockchain. The more confirmations it receives, the harder it is to change or fake it

# Bitcoin and other well-known coins, blockchain networks
**Bitcoin** is a decentralized digital monetary system and the first cryptocurrency, created by Satoshi Nakamoto in 2009. Its key feature is limited emission of 21 million BTC and the absence of a single issuer: the issuance of new coins and transaction processing are regulated by the protocol. To protect the Bitcoin network, it uses the Proof of Work mechanism, in which miners solve computational problems and receive rewards for adding new blocks. Network rules: the longest chain _(with the greatest accumulated work)_ is considered true; if two miners find a block at the same time, the network temporarily forks, but then the longer branch is chosen; to change history, an attacker would need to control more than 50% of computing power, which is economically unprofitable. Thanks to this, Bitcoin can function as an independent system for transferring and storing value, not requiring trust in a particular bank or state

## The most well-known blockchain networks at the moment:
- [Ethereum (ETH)](https://ethereum.org/ru/) - the main network for smart contracts and decentralized applications (dApps). Most projects in the field of finance (DeFi) and NFT are launched on it
- [Bitcoin (BTC)](https://bitcoin.org/ru/) - the first and most reliable cryptocurrency network. It works as digital gold and a means of saving capital
- [Solana (SOL)](https://solana.com/ru/) - a high-performance network with high throughput. It is popular due to high transaction speed, low fees and meme tokens
- [Tron (TRX)](https://tron.network/) - a blockchain platform created for fast and inexpensive transactions and the operation of decentralized applications. It is especially known for the use of USDT on the TRON network (TRC-20), thanks to which the network is widely used for stablecoin transfers
- [Ton (TON)](https://ton.org/) - a cryptocurrency network focused on high speed, scalability and cheap transactions, closely integrated with the Telegram ecosystem

### Commonly used tokens:
- [USDT (Tether)](https://tether.to/en/) — the largest stablecoin, whose value is pegged to the US dollar. Widely used for transfers, trading and storing funds in cryptocurrency
- [USDC (Circle)](https://www.usdc.com/) - a stablecoin also aimed at maintaining a rate around 1 dollar. Often used in DeFi and cryptocurrency payments
- [ETH](https://ethereum.org/ru/) — this is the native cryptocurrency of the Ethereum network, performing the role of "fuel" for the entire ecosystem _(payment of fees for transfers (gas), staking)_
- [SOL](https://solana.com/ru/) — the native token of the Solana network, necessary for paying transactions and operating applications on the blockchain
- [TRX](https://tron.network/) — the main cryptocurrency of the TRON network, used to pay fees and conduct operations, including with TRC-20 tokens
- [GRAM](https://ton.org/) - the native token of The Open Network, used to pay fees, transfers and interact with applications of the TON ecosystem

### Which token and network to choose
The choice of a specific token and network depends on goals, risk tolerance and areas of application.

**If we talk about stablecoins** _(independence from price fluctuations)_:

**USDT on the Tron network (TRC-20)** will be a good option for fast and inexpensive transfers, **USDT on the Ethereum network (ERC-20)** is a reliable solution, but usually fees are higher (depending on network load), **USDC on Ethereum/Tron/Solana** differs from USDT in that Circle (the issuer of USDC) blocks user assets _(at the request of law enforcement agencies, due to a wallet being included in sanctions lists (for example, OFAC), as well as when suspicious operations are detected related to hacker attacks, fraud, darknet and money laundering)_ much less often than Tether (the issuer of USDT): during the period 2023–2025, this company blacklisted more than 7,200 addresses _(which excludes any further possibility of using USDT assets)_ for a total of over $3 billion _(most of the blockings occurred on the Tron network)_, during the same period Circle blocked only about 372 addresses, and the total amount of frozen funds was around $109 million

**If we talk about other tokens:**

**BTC** is considered "digital gold", the oldest and most reliable cryptocurrency, it is suitable for the goal of buying and forgetting for several years, hoping for profit. **ETH** is considered a platform for applications; most DeFi services, stablecoins and NFTs operate on it; it is worth choosing if you plan to work with the Ethereum ecosystem _(as mentioned earlier, it is necessary for paying gas (fees) on the Ethereum network)_, as well as storing/transferring stablecoins _(such as USDC and USDT)_ on the ERC-20 network. **TRX** is worth choosing if you plan to store tokens on the Tron network _(TRX will be required to pay fees for transfers on the Tron network (TRC-20), as in the case of ETH and ERC-20)_

# Types of wallets. Choosing and creating your first wallet
### Cryptocurrency wallets are classified as follows:
1. **By control over keys**
   - Non-custodial - only you store the private keys, and only you have access to the wallet; the advantage is full control over your funds _(if desired, you can import the seed phrase/private key into another wallet)_; the disadvantage is that if you lose the seed phrase/private key, no one will be able to help you restore the wallet _(for example, Trust Wallet, Cake Wallet, Solflare)_
   - Custodial - the private keys are stored by a third party, similar to familiar online banks; the advantage is simplicity for a beginner; if necessary, access to the wallet can be restored through support; the main disadvantage is that the exchange may freeze the account, go bankrupt or be attacked and your funds will be irretrievably lost _(for example, CryptoBot/xRocket in Telegram, Binance, Bybit exchanges)_
2. **By device**
   - Hot (software) - an application on a smartphone/PC, convenient for everyday use, but more vulnerable than cold wallets _(for example, Trust Wallet, Metamask, Phantom)_
   - Cold (hardware) - a physical device, private keys never reach the internet, maximally secure and suitable for storing large sums _(for example, Ledger, Trezor, Tangem)_
3. **By supported networks**
   - Multi-currency - wallets supporting many networks simultaneously _(for example, Trust Wallet, Metamask, OKX Wallet)_
   - Specialized for a specific network _(for example, Rainbow, TronLink)_

### Which wallet to choose?
If you plan to store large sums - a cold Ledger/Trezor/Tangem, if you often sell/buy/exchange cryptocurrency for fiat, work with little-known meme tokens - an exchange wallet _(for example, Binance, however KYC - identity verification will be required)_, for small/medium sums and most users, a hot non-custodial wallet will be suitable _(Trust Wallet, Metamask and others)_

1. **Install Trust Wallet from your app store**
2. **In the welcome window, select "Create a new wallet":**

   <img src="https://github.com/crysao/crypto-guide/blob/main/img/trust1.jpg" width="300" alt="trust1">
3. **The wallet will be successfully created _(if desired, you can top it up right away)_:**

   <img src="https://github.com/crysao/crypto-guide/blob/main/img/trust2.jpg" width="300" alt="trust2">
4. **Next, you land in the main menu of the wallet, where you need to tap the button in the upper-left corner "Main wallet":**

   <img src="https://github.com/crysao/crypto-guide/blob/main/img/trust3.jpg" width="300" alt="trust3">
5. **In the window that opens, choose to copy the seed phrase "Manual", write the seed phrase down on a piece of paper, and then pass a short check of whether the seed phrase was written down correctly _(you will need to specify the 1st, 4th, 7th and 10th words from the phrase)_:**

   <img src="https://github.com/crysao/crypto-guide/blob/main/img/trust4.jpg" width="300" alt="trust4">
# Security. Fraud
The most important rule to remember is that the private key and/or seed phrase give **full access** to all your tokens. **Under no circumstances should they be shown to anyone, stored in notes on your phone/messengers/screenshots, or entered on any websites _(except for verified browser extensions like Metamask)_**. The best way to store them is a physical written record on a piece of paper kept in safe places _(possibly even in several copies)_. For large sums, as mentioned earlier, it is worth looking into cold wallets

Even if you store your tokens on a cold wallet / wrote down the seed phrase on paper, responsibly hid it and never showed it to anyone, scammers still have ways to steal your funds _(although not all of them apply to cold wallets)_. Fake exchange/exchanger/wallet websites and other resources pose a danger. When following links, you should double-check the spelling of the domain several times _(for example, whether it is really metamask.io, and not some metamask.cc or metama.sk)_. You should not connect your main wallets to suspicious applications; it is better to use a second wallet with a tiny balance or even create a new empty one. There are malicious scripts — **drainers**, which are a common and dangerous type of fraud in the cryptocurrency space. Scammers trick you into signing a transaction that may outwardly look like receiving a free NFT or airdrop. After the transaction is signed, the scammers gain full access to your funds and instantly withdraw them

As a result, a safe setup would be a **cold wallet**, on which most of the sum is stored, a **hot wallet** used for staking/other safe operations, whose seed phrase is saved physically and hidden in a safe place, an **exchange account** (if desired) for buying cryptocurrency with fiat, and a **second hot wallet** for risky operations

(Guide is a work in progress...)

[If the guide turned out to be useful](https://github.com/crysao/crysao/blob/main/tips.md)
