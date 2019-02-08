# Connecting Blockchains Together

The blockchain ecosystem is exploding. There are 1,491 cryptocurrencies listed on coinmarketcap.com at the time of writing. Many of these currencies share an underlying blockchain infrastructure, but many are deployed on their own blockchain with unique features. Implementing different blockchain protocols offers particular benefits for users of the system, so various blockchains are created to suit their creators goals.

Variety in design creates a healthy, scalable, and resilient ecosystem, but creates its own problems. Disparate blockchains are isolated environments and transferring value between them is difficult. We currently rely on centralized exchanges which can be slow and expensive. Creating programmatic connections between blockchains to ease transfer of value is an important factor for mass adoption of these systems. In this chapter we explore several approaches in connecting blockchains, such as pegs and relay blockchains.

## The Two Way Peg

A **two way peg** allows users of a blockchain to deposit the native cryptocurrency of a blockchain and receive the cryptocurrency of another blockchain on the other network. A classic example of this system is BTC Relay, which acts as a peg between Bitcoin \(BTC\) and Ethereum \(ETH\). Holders of bitcoin can send BTC to a Bitcoin address, thereby releasing a certain amount of ETH on their behalf on the Ethereum blockchain. This enables Bitcoin holders to access functionality built on the Ethereum blockchain.

## An Internet of Blockchains

The two way peg is a step in the right direction in terms of enabling cross chain functionality, but the goal is to achieve greater interoperability, analogous to the internet in the sense that it is a network of networks. The current blockchain landscape is similar to the web in 1994 - we couldn’t imagine social networks, e-commerce or pervasive video conferencing and look where we are almost 25 years later. Designing systems that can scale as effectively as the internet is important for the future of the blockchain technology.

Paul Kohlhass writes in his [**Introduction to Polkadot and Parachains**](https://keepingstock.net/a-dummies-guide-to-polkadot-and-parachains-93708bd90775)**:**

> "A future of multiple blockchain networks is increasingly likely. A Web 3.0 architecture of buzzing public blockchains, private consortium ledgers, anonymous zero knowledge proof chains and all the countless applications running on top of each of them. Not one chain to rule them all, but a world of diversity where individual chains serve specific use cases and specifications.”

Each blockchain has advantages and disadvantages. An internet of blockchains would allow us to transfer value between blockchains to take advantage of specific features relevant to specific applications, regardless of which network holds each stakeholders assets.

If Bitcoin truly emerges at “the gold of the internet” the network will continue to hold massive amounts of value, but with potentially high transactions fees and longer block times it may not be ideal for applications requiring microtransactions. Another blockchain might be better suited for this application.

Additionally, the programmability of Ethereum makes it valuable for applications requiring smart contracts, but if we want additional privacy we might want to conduct transactions on a different network that enables greater privacy, like Zcash. If each blockchain has huge utility, they can do even more when connected.

There are several projects that aim to tackle this enormous challenge. Polkadot facilitates authenticated transaction between blockchains using a central relay chain with parachains and bridges to external blockchains. The project Cosmos is a team working on hub \(called the Cosmos Hub\) connected to other blockchains via an inter-blockchain communication protocol. Cosmos is planning their main network launch for the end of February 2018.

Inter-chain operability is an important area of research in the blockchain space and could help lead to improvements regarding scalability, consensus and privacy.

