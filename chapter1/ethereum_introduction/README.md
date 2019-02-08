# The Ethereum Blockchain

Now that you have a basic grasp of blockchain, let's dive into the specifics of one of the fastest growing blockchain platforms on which to build decentralized applications.

Ethereum is often described as the ‘world computer’. What does that mean exactly? Ethereum is a platform on which anyone can build decentralized applications, where every program and action is universally accessible and verifiable because everything happens on the global Ethereum blockchain \(mainnet\). The feature of Ethereum that makes it so extensible is that it is a programmable blockchain. It is similar to a programmable distributed ledger, where everyone agrees to run the same applications with the same data. It is not just a ledger, but global, shared data processing protocol. Hence, the idea of a world computer.

The main Ethereum blockchain is permissionless, meaning anyone can join the network. There are a few caveats to this, but basically, as long as you have an internet connection and follow the protocol, you can participate. Every participant running the protocol is a node in the network and executes and records the same activity. An action on the network is called a transaction. Transactions are grouped into blocks. Only one block can be added at a time and mathematical proofs verify the order of the blocks. This keeps the ‘distributed spreadsheet' in sync.

Every participant in the network processing every transaction results in a system that is expensive to maintain and change. To reduce spam and disincentivize valueless transactions, every operation on the network costs **gas.** Gas is the fuel of the Ethereum network. It is required to cause any modification to the blockchain. Users can choose how much to pay for gas for each transaction - the more they are willing to pay, the faster their transaction is likely to be processed by the network. At the time of this writing \(February 1st 2018\) the average cost of a transaction converts to rougly $1.30 USD. Gas is paid for with Ether \(ETH\), the native token of the Ethereum blockchain, which is explained in more depth in the Consensus section below.

Operating on the main Ethereum means that a user will be exchanging value for the services provided by miners. For those who do not want to spend any money, there are several public test networks that essentially follow the same protocol as the main network \(mainnet\), but are free to use. These test networks are useful for developing and testing applications for Ethereum, but do not have the same reliability or security as the main network so they should not be trusted to handle real value. The test networks are called Ropsten, Rinkeby and Kovan.

## **Public or Private Networks using Ethereum**

The Ethereum main network is a public network that is open to anyone, but it is possible to run an Ethereum network in a private consortium as well \(as previously discussed\). A closed network allows for certain advantages like faster processing and private transactions as the participants in the network are known. JP Morgan is developing a permissioned, enterprise ready blockchain platform based on Ethereum called **Quorum**.

## **Smart Contracts**

The programs that run on the Ethereum blockchain are called **smart contracts**. Smart contracts digitally facilitate, verify or enforce arrangements between multiple parties where the blockchain plays the role of the intermediary - the blockchain is acknowledged as the source of truth to settle disputes. This can lower costs associated with making agreements and settling disputes, and reduce or eliminate opportunities for deceitful actions among participants in a contract. While this is technically feasible on the Bitcoin blockchain, the protocols of the Ethereum blockchain were designed to allow for smart contracts.

## **Consensus**

Currently, agreement on the state and the security of the Ethereum blockchain is maintained by a mechanism called **proof of work**. This mechanism rewards miners that help update the current state of the blockchain with Ether. Ether, a cryptocurrency, the unit of value on the Ethereum blockchain. It is the token for Ethereum.

Maintaining the network through proof of work is expensive and vulnerable to certain kinds of exploitation. There are plans to migrate Ethereum from a proof of work consensus mechanism to **proof of stake.** Proof of stake allows holders of Ether to stake a large amount of Ether as collateral for the opportunity to extend the blockchain. Honest actors in this system are rewarded with a small amount of Ether and dishonest actors are punished by losing the Ether they staked. The implementation of proof of stake planned for Ethereum is called Casper.

## Learning More

If you'd like to learn more, Dan Finley, project lead at Metamask \(an internet browser extension for interacting with the Ethereum blockchain\), gives a succinct technical overview of how Ethereum and blockchains work at the opening talks of the IPFS Ethererum Hackathon in [**Intro to How Ethereum Works**](https://www.youtube.com/watch?v=-SMliFtoPn8).

