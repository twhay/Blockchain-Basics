# Ethereum Limitations and Scaling Solutions

While there is a lot of excitement surrounding Ethereum and its future, it's important to stay realistic about the current state of affairs and the amount of hard work still needed for success. In this section we will touch several areas of concern about the state of Ethereum outlined by Vitalik.

The following list is expanded from a [Reddit post](https://www.reddit.com/r/ethtrader/comments/6lgf0l/vitalik_drops_the_mic_on_rbtc/dju1y8q/) by Vitalik Buterin from mid-2017**.**

## Scalability

First and most importantly, Ethereum as it exists today will not scale to serve the needs of the projects that are currently being built on it, let alone handle future projects. The current design of the system requires that individual nodes process every transaction on the entire network. This provides security and verifiability to the system, but severely limits the scalability.

At the time of this writing \(January 9th, 2018\) Ethereum reached peak transaction volume on January 4th, processing an average of 15.6 transactions per second. To compare, Facebook processes around 175,000 requests per second - Ethereum at its peak performance runs more than 10,000 times slower than Facebook. With the explosion of projects and tokens using the network, demand is sure to continue increasing in the near future.

Thankfully there is active research and support for solving this problem. Vitalik announced [“Ethereum scalability research and development subsidy programs”](https://blog.ethereum.org/2018/01/02/ethereum-scalability-research-development-subsidy-programs/) in the domains of **sharding** and layer-2 systems like **Plasma**, State channels and Raiden.

**Sharding** is a scaling solution for Ethereum that would eliminate the need for every Ethereum node to process every transaction on the network. The proposition is to limit certain nodes' processing requirements to a subset of the total processing requirements of the system, with each node processing a shard of the whole and then facilitating communication between shards.

**Plasma** also reduces the total processing requirements of nodes in the network. It is a scaling solution that consists of a system of smart contracts that will run on the main Ethereum blockchain. The main blockchain only stores small amounts of verified data from "child" blockchains, each of which are required to maintain their own integrity. Implementing many "child" chains would greatly expand the storage and computing potential of the entire network.

## Proof of Work Consensus

Proof of work, the mechanism by which Ethereum maintains system consensus and security, uses a [lot of energy](https://medium.com/thebeammagazine/the-energy-consumption-of-the-crypto-world-b20e3628e0d2). As of December 2017, Ethereum was consuming just over 11 TWh of electricity. That works out to be enough energy to power 1.7 US homes per transaction.

Additionally proof of work is vulnerable to certain types of network attacks whose threats can be mitigated or eliminated by switching to a different consensus mechanism, such as proof of stake.

Fortunately there is ongoing research in this domain as well and there is a [roadmap](https://bitcoinmagazine.com/articles/ethereum-killer-ethereum-20-vitalik-buterins-roadmap/) for migrating Ethereum from proof of work to proof of stake. The planned Ethereum implementation of proof of stake is called **Casper.**

## **Privacy \(or lack thereof\)**

There is a lack of privacy on Ethereum. As a public ledger where data is visible to everyone, there are plenty of reasons to keep any sensitive information off of the blockchain. Nevertheless, there are many applications where making private data accessible on the blockchain would be beneficial - consider applications handling financial data or systems dealing with medical records. There needs to be a way that people can conceal data while still allowing it be used reliably in transactions on the blockchain.

Ethereum took a step closer to achieving this with the Byzantium network upgrade that took place in October of 2017. The Byzantium upgrade included support for **zk-SNARKS** which allow for verifying correctness of computation without revealing the contents of computation. This technology can be used to meaningfully use sensitive data in smart contracts while maintaining privacy.

## Risk of theft or loss

Your private keys are the only way to access your account. This means that if you lose your key or someone who shouldn’t gets ahold of it, you are out of luck. There are no fail-safes and no one can help you. The finality of this is unfamiliar to the average computer user and will likely cause many unhappy users as the technology gains greater adoption.

## Trusting applications

Contracts on Ethereum are being trusted to hold greater and greater amounts of value. Most of us trust that contracts that we send our Ether to are secure without ever glancing at the code, but there are scammers and hackers out there and honest mistakes happen.

Realistically, it will not be possible for Ethereum users to validate and verify smart contracts before they start interacting with them. Users place trust in application developers that the program is going to do what they say it is going to do, but still bugs persist and hackers get in.

There is currently work being done to programmatically verify that contracts on the blockchain are 100% bug free. Using formal verification, auditors will be able to put a stamp of approval that a smart contract is free of bugs. Issues of honesty and trust will remain, but reducing the number of accidental losses will be a big win for the ecosystem.

