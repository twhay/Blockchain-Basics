# Decentralized Storage

### Adapted from [**Decentralized Storage: The Backbone of the Third Web**](https://media.consensys.net/decentralized-storage-the-backbone-of-the-third-web-d4bc54e79700) - ConsenSys Media, 2016 and [**An Introduction to IPFS**](https://medium.com/@ConsenSys/an-introduction-to-ipfs-9bba4860abd0) - ConsenSys Media, 2016

In the last decade much of the internet has moved onto "cloud storage" which has powered the new web. Most of the applications we use on a daily basis have our data stored in server farms owned by Amazon, Google, or Microsoft. In this new era of decentralized applications, developers are turning to decentralized storage as a way to avoid censorship, server outages, and hacks. This section will explore some of the solutions for storage in Web 3:

Since the World Wide Web hit the mainstream in 1994, we have seen the network expand to encompass almost every aspect of human life. The underlying infrastructure of the Internet and the services built on top of it are interdependent, one informing the other as new use cases and technologies arise. There have been two clear generations in the services and structure of the web thus far, but today we are moving into a third. This section will look at what characterized Web 1.0 and 2.0 and what may characterize Web 3.0. We will then look at the storage technologies that are likely to form its backbone: the decentralized storage network [IPFS](https://ipfs.io/) and its incentive platform [Filecoin](http://filecoin.io/) and Swarm, an emerging Ethereum oriented storage platform that uses IPFS.

## **Web 1.0 & 2.0** <a id="ab9d"></a>

Web 1.0 was the birth of a new idea. If we can connect all of the computers in the world through a global network, the Internet, then we should be able to make the collective content pool universally accessible. For this mass of data to be usable it needed to be indexed and browsable. This necessity was behind the innovation that led to the first generation of the World Wide Web.

Web 2.0 took this new global resource, a universally accessible pool of content, and began plugging things into it. Programs could connect and use the Web as a way to store information and communicate with each other. Central intermediaries, today’s Googles and Facebooks, assumed the roles of data silos and switchboards, offering scalable resources and routing traffic. While these new corporations have changed the way we live and provide amazing services, they also leverage their centralized position for profit and power.

In their orange paper, [“Swap, Swear and Swindle: Incentive System for Swarm”, Viktor Trón, Aron Fischer, Dániel a. Nagy, Zsolt Felföldi, Nick Johnson](http://swarm-gateways.net/bzz:/swarm/ethersphere/orange-papers/1/sw^3.pdf) writes that:

_Context-sensitive targeted advertising offered a Faustian bargain to content producers. As in ‘We give you scalable hosting that would cope with any traffic your audience throws at it, but you give us substantial control over your content; we are going to track each member of your audience and learn — and own — as much of their personal data as we can, we are going to pick who can and who cannot see it, we are going to proactively censor it and we may even report on you, for the same reason.’ Thus, millions of small content producers created immense value for very few corporations, getting only peanuts \(typically, free hosting\) in exchange._

As the Web grew, we reached scaling limits. Central nodes required ever more bandwidth to cope with even increasing data flows. Over time, as things were shuffled around, links broke and content was lost, vanishing due to unsearchably into the mass of information.

To compound these problems, security never achieved a level appropriate for the new communication and commerce services provided through the Web. The client-server model relies on a system of digital certificates, which are issued by third parties to secure connections. The problem is that if the third party is compromised, so, potentially, are all the connections made using its certificates.

According to [Juniper Research](http://www.juniperresearch.com/press/press-releases/cybercrime-cost-businesses-over-2trillion), “the rapid digitization of consumers’ lives and enterprise records will increase the cost of data breaches to $2.1 trillion globally by 2019, increasing to almost four times the estimated cost of breaches in 2015.” Thus, the scene is set for a paradigm shift and a cluster of new technologies are emerging. They promise to solve the problems plaguing the existing system and create a new way of using the Web.

## **Web 3.0** <a id="ac77"></a>

Following the trend set by earlier iterations, the idea of Web 3.0 posits a change in the way content and programs interact. If central intermediaries like Facebook and Google are cut out of the picture, many of the problems we have today will go with them. Instead, [_content addressing_](https://en.wikipedia.org/wiki/Content-addressable_storage) and related techniques will allow content and programs to link to one another directly and in a more robust fashion. Blockchain technologies like the digital currency Bitcoin and the smart contract platform Ethereum use unbreakable [_public key cryptography_](https://media.consensys.net/2016/06/01/1499/) to secure the connection between programs and protect data.

This is an alternative to the centrally issued SSL \(Secure Sockets Layer\) Certificates used today. Because there is no central intermediary routing traffic, connections can dynamically find the most efficient pathway through the Internet and route around congestion or damage.

These systems were designed for financial transactions though. They are not suited to storing and relaying the volume of information required to replace a central server. BitTorrent is a popular solution that has excellent storage and scaling characteristics. However, navigating the [_Distributed Hash Table_](https://en.wikipedia.org/wiki/Distributed_hash_table) used to index content on the network can take seconds. This kind of latency \(wait time\) is fine for large file transfers but no good for datacenter use cases.

## InterPlanetary File System \(**IPFS\)** <a id="cdfd"></a>

Described by Viktor Tron as “the lego kit for the third web,” [IPFS](https://ipfs.io/) is a new system for storing data on a large number of computers. It is transport layer agnostic, meaning that it can communicate through transport layers like transmission control protocol \(TCP\), uTP, UDT, QUIC, TOR, and even Bluetooth\)

Instead of a central server, a [_peer to peer network_](https://en.wikipedia.org/wiki/Peer-to-peer) is used to establish connections. [Public key cryptography](https://media.consensys.net/2016/06/01/1499/) is built into the node addressing system and [_content addressing_](https://en.wikipedia.org/wiki/Content-addressable_storage) is used to index content. Both node and content addresses are stored in a decentralized naming system called InterPlanetary Naming System \(IPNS\).

**Node addressing and connection security**

* Nodes in the peer to peer network each hold private keys and release public keys, just like in Bitcoin or Ethereum.
* Node addresses are derived through [_hashing_](https://media.consensys.net/2016/06/03/guide-hashing/) their public keys. Allowing connection verification through message signing.
* Their public keys can be used to encrypt data before it is transferred, preventing interception and theft.

Solutions to the security issues of today’s web are built into this addressing system. There is no need for a trusted central certificate issuer to provide connection verification tools and all connections can easily be encrypted by default. No more SSL.

## A High Level Approach to IPFS

At its core, IPFS is a versioned file system that can take files and manage them and also store them somewhere and then tracks versions over time. IPFS also accounts for how those files move across the network so it is also a distributed file system.

IPFS has rules as to how data and content move around on the network that are similar in nature to bittorrent. This file system layer offers very interesting properties such as:

* websites that are completely distributed
* websites that have no origin server
* websites that can run entirely on client side browsers
* websites that do not have any servers to talk to

## **HTTP vs. IPFS to find and retrieve a file**

HTTP has a nice property where in the identifier is the location so it is easy to find the computers hosting the file and talk to them. This is useful and generally works very well but not in the offline case or in large distributed scenarios where you want to minimize load across the network.

In IPFS you separate the steps into two parts;

1. Identify the file with content addressing
2. Go and find it — when you have the hash then you ask the network you’re connected to ‘who has this content? \(hash\)’ and you connect to the corresponding nodes and download it.

The result is a peer to peer overlay that gives you very fast routing.

To learn more, watch the [Alpha Video](https://www.youtube.com/watch?v=8CMxDNuuAiQ).

## **Content Addressing**

A content address is derived by hashing a piece of content.

* That content address is then hashed again to derive a _key name._
* The key name is associated with a human readable name in IPNS \(IPFS’ address registry\).

Instead of referring to objects \(pictures, articles, videos\) by which server they are stored on, IPFS refers to everything by the hash on the file. The idea is that if in your browser you want to access a particular page then IPFS will ask the entire network “does anyone have this file that corresponds to this hash?” and a node on IPFS that does can return the file allowing you to access it.

IPFS uses content addressing at the HTTP layer. This is the practice of saying instead of creating an identifier that addresses things by location, we’re going to address it by some representation of the content itself. This means that the content is going to determine the address. The mechanism is to take a file, hash it cryptographically so you end up with a very small and secure representation of the file which ensures that someone can not just come up with another file that has the same hash and use that as the address. The address of a file in IPFS usually starts with a hash that identifies some root object and then a path walking down. Instead of a server, you are talking to a specific object and then you are looking at a path within that object.

In today’s web, if a file is moved, all links to that file need to be updated if they are to resolve. Because IPFS addresses are derived from the content they refer to, if the content still exists anywhere on the network, links will always resolve. This removes any need for duplication of content, except for the purposes of greater persistence security or for scaling up serving capabilities.

However, for a decentralized storage system to grow to replace the current model, it needs a way to incentivize the storage and serving of content.

Filecoin is one solution being developed by Protocol Labs, Swarm is another being developed by the Ethereum foundation. Both projects make use of IPFS technology but have different philosophies on how to incentivize participation.

## **Filecoin** <a id="68d4"></a>

[Filecoin](https://filecoin.io/) is a protocol launched by Protocol Labs, the same entity that developed IPFS. If you want to dive in in much greater detail, we will refer you to the [Filecoin White Paper](https://filecoin.io/filecoin.pdf).

Filecoin uses an established consensus process already in use securing a financial network. By requiring nodes to solve puzzles based on randomly selected data chunks, a Proof of Work algorithm can be built, which will reward the nodes that store more data chunks and have better connectivity. Tools for adding redundancy and the ability to select nodes based on reputation, whether that be tracked within the protocol or outside it, will address the problem of persistent storage.

## **Swarm** <a id="c58a"></a>

Swarm was conceived of as a storage protocol tailored for interoperation with the Ethereum smart contract ecosystem. Like Filecoin, it will piggyback on Ethereum’s consensus process in order to provide a decentralized alternative to our existing client/server infrastructure. Incentivising persistent storage is a challenge, however. The downside of a node deleting data and losing some income is potentially much less significant than a user losing his or her valuable data.

Swarm takes the approach of rewarding nodes for serving content. Because more often requested content is more profitable to store than rarely requested content, rewarding nodes only for recall would incentivise the trashing of rarely accessed data. Failure to store every last piece of a large data set can result in the entire set being rendered useless, so in these cases a solution must exist to balance this downside asymmetry.

Using content recall as the base reward mechanism and distributing content randomly among nodes, weighted for location, puts Swarm in a good place to start solving the persistence problem:

* Nodes offering “promissory” storage, or storage with a promise of persistence, must first post a security deposit covering the time for which they are offering storage.
* If data is lost during this period, the bond is forfeited.

The smart contract infrastructure of Ethereum automates this whole process, making the “upload and forget” experience seamless.

