# Price Stabilization

### Adapted from [**StabL Bringing Stable Tokens and Derivative Products to the Ethereum Blockchain**](https://blog.variabl.io/stabl-bringing-stable-tokens-and-derivative-products-to-the-ethereum-blockchain-df4d5eba89d9) - VariabL Blog, 2017

One of the big problems holding back users from spending and vendors from accepting cryptocurrencies is the price volatility. Risk averse users avoid adopting crypto and risky investors hold and trade crypto rather than spend it. This has led to price fluctuations that have occurred over the last quarter of 2017 and the start of 2018.

In this section we explore a specific ConsenSys project looking to solve this problem by attempting to peg the value of crypto to more traditional assets like the United States Dollars \(USD\) or gold.

## Stable Tokens

Stable tokens have been a leading topic of discussion since the birth of Ethereum. Using the decentralized platform that is the public Ethereum blockchain makes it necessary to hold Ether, not only to use it as gas or fuel, but also to gain access to the shared public resource of the mainnet. This also makes it a standing store of value. The problem with using Ether as a currency is that it is a currency with a variable price. If this obstacle of volatile price were overcome with the introduction of a cryptographic asset that tracks, for example, USD, it would pave the way for massive acceleration of Ethereum adoption.

## What is at Stake? <a id="b3b1"></a>

A Stable token is a crypto-token that keeps a stable value against a specific index like the price of one US Dollar.

A crypto-token is a transferable asset stored on a blockchain. Every token stored on the Ethereum blockchain benefits from the properties of Ether itself: distributed verification of transactions, pseudo-anonymity, almost instantaneous and low-fee transfers, censorship-resistance, access to smart contracts etc. A USD Stable token means mainly two things:

1. **Crypto-properties are added to dollars.** \(You have an asset that has the same value as one USD bill but with better properties: you can do much more with it\)
2. It is now possible to **store USD-stable values** within the blockchain with these tokens.

## The Spectrum of Stable Assets

A stable asset is something you can own that keeps a stable value against an index. For instance a gold-stable asset that is worth 500g of gold today will be worth 500g of gold for its entire lifetime. There are plenty of different assets that fit this definition. Here is a list of them and an analysis of how they differ from one another:

Assets that directly represent gold:

* 500g of gold buried in a desert.
* 500g of gold ingots.
* 500g of gold coins in a purse.
* Bank deposit box that contains 500g of gold
* 500 DGX tokens \(Ethereum tokens, cheer guys :\)\)

Assets that are valued at a stable gold weight but do not directly represent gold:

* A contract with a friend that states they owe you 500g of gold, with a set due date that is 6 months from now.
* Gold ETF shares. \([SPDR Gold Shares ETF](http://etfdb.com/etf/GLD/) for instance\). Shares of a fund with variations that follow gold price variations.
* Position in a Contract For Difference \(CFD\) USD vs Gold \(i.e: In 6 months from now, I will buy 500g of gold at a specific price determined today\)
* Gold StabL Tokens bought on StabL platform \(Ethereum tokens that represent a position in an on-chain cash settled future contract. We will not focus on Gold StabL tokens in our early stages, but this is a good example to explain our approach\)

Every previously listed asset has different properties. Let’s try to compare our listed assets with the most important properties.

## Value Storage Property: Ownership of your Asset and its Underlying Value

What guarantees you that the underlying value of your asset will remain?

**How secure is your ownership?**

When you store gold yourself \(coins, lingots, buried gold\), you trust yourself. When you use a bank deposit box, you trust your bank not to be robbed \(or to have good insurances\). When you use an Ethereum token \(StabL, DGX\), you trust the Ethereum technology and yourself with the way that you store your private key.

It is difficult to rate these assets against this property since it depends a lot on ourselves? \(How do I bury gold? How do I keep my private key? What bank do I choose? How do I store the written contract I signed with my friend?\).

Long term, we are convinced that owning a token that lives on a blockchain like Ethereum is the most secure way to own an asset. The Ethereum community is still in the early stage, but mature tools to store and back up private keys along with privacy will make owning tokens seamless yet secure.

**Given that your ownership is secure what makes its value guaranteed?**

Of course when owning physical gold, there is no risk of your asset losing value. When owning physical gold through a proxy \(bank deposit box, DGX\), you trust this proxy.

When owning a financial asset like Gold ETFs or Gold futures, it is a bit more complicated. The value is guaranteed by the robustness of the theoretical financial mechanism that includes an ecosystem of traders, arbitragers, hedgers, index providers, laws enforcers, etc. You also usually trust the exchange that gives you access to these assets.

## Transferability: Ability to Transfer the Asset.

Gold coins are more transferable than lingots or raw gold but still need to be exchanged in the physical world. Buried gold or gold stored in a deposit box have poor transferability properties.

Ethereum tokens that represent a stable value of gold \(DGX or Gold StabL Tokens\) are definitely the assets that have the best transferability properties \(20 sec on-chain transfers, instant using state channels, low fees, secure\).

## Liquidity: Ability to Trade the Asset.

For an asset to be liquid \(meaning you can sell/buy a large amount of it quickly\), you need it to be available on exchanges that have large volumes. Volume is one of the key factors that relate to velocity. The most liquid assets are positions in CFD/Futures and ETFs. Indeed, since they don’t represent physical gold but positions in a financial system, it is easy to buy/sell them. You don’t need to move any physical good.

New CFD/Future contracts can be created \(on the so called primary markets\) as soon as two parties agree on a Future contract. Then these two parties can sell their position in the Future contract \(on secondary markets\).

In today’s financial world it harder for small investors to trade on the primary market. With Ethereum and easy digital contracts creations, this market becomes way more accessible: the difference between primary markets and secondary markets are blurred, making for an overall more efficient market.

StabL Tokens have the same mechanical properties: if our on-chain financial products \(Futures-like products\) attract a large number of traders \(lot of Future contracts created\), our tokens \(that represent a position in one of these contracts\) will be much more liquid than any gold-backed token. If there does not exist enough Future positions that are stable against USD \(represented by a USD StabL token\), you just create some by being matched with a trader around a Future contract as easily.

## Non-Financial Properties: What can you do with these Assets?

Gold can be used to store value, to transfer value, to wear value, even to lend value as vehicles in contracts. Futures and ETFs have better trading properties since they are well suited for the internet world, yet they rely on centralized parties whereas gold, as a chemical element, relies on, well, physical trust-less laws.

On-chain stable tokens open a whole new world to gold. Both DGX and StabL Tokens can be used in smart contracts. For instance, they can be used as a currency in a trust-less crowdfunding platform like WeiFund. What is even more powerful with StabL tokens is that since their value is guaranteed by a decentralized game theoretical mechanism \(based on Futures market\), the only potential point of failure lies in the design or the implementation of the mechanism. Even if we think we have found a design that works in the on-chain world, we are very well aware that offering such a mechanism at all once is near impossible \(especially in the current youth of the Ethereum ecosystem\) and we differentiate ourselves by taking a lean approach.

