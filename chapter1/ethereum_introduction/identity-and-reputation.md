# Self-Sovereign Identity and Reputation

### Adapted from [**The Identity Crisis**](https://medium.com/@ConsenSys/identity-is-defined-in-merriam-s-dictionary-as-who-someone-is-a3d6a69f5fa4) - By Dr. Christian Lundkvist and Andrew Keys, ConsenSys, 2015

For those of us lucky enough to be in the first world, we have the luxury of claiming our identity because there are centralized organizations or governments that affirm who we say we are through birth certificates, identification numbers, and other means. The blockchain enables a new shift in this space where we can have multiple, decentralized sources attest to our identification while we still maintain control of this data.

In this section we will explore what a self sovereign identity is and the significance of being able to control your identifying information through a blockchain.

## Identity

**Identity** is defined in Merriam’s dictionary as “who someone is”. As the world and technology evolves one can’t help but notice the changes to the notion of who someone is and how this affects their relation to the world. We’ll focus on the problems that affect humans in regards to their identities, dividing the conversation into developed and developing economies.

## **The Problems** <a id="f299"></a>

**Developing Economies**

Notwithstanding the millions of humans on Earth that literally have no identity, the members of the developing world are victimized and hindered without official forms of identification. Cost and inefficient infrastructure make simple transactions like opening a bank account, obtaining credit, renting shelter, or purchasing transportation impossible.

Human trafficking is fueled by the lack of identification whereby humans are unable to prove their age or origin, creating oppressive environments.

**Developed Economies**

We live in a world where our identity is not commonly possessed by the rightful owner. Mark, Sergey, and Larry have earned an exceptional livelihood selling the attributes of digital identities of members of the developed world. In mainstream products like Facebook, you are the _product_. You are being sold to marketing companies as a product based upon your interests, locations, and demographics. Moreover, specific attributes of identity have become vulnerable to attack. Countless stories of cyber-theft occurs where social security and financial data are the eventual goal of hackers worldwide.

## **The Solutions** <a id="2ce5"></a>

**Developed Economies**

In the developed world the solution to having our identities owned and monetized by third parties is to introduce **self-sovereign identity**. This is a concept where the individual has ultimate control over their identity and is the final arbiter of who can access and use their data and personal information. This is a new concept, in that previous thought around digital identity has always hinged on “identity providers”, which are the entities that own and control our identity. Some discussions on “decentralized identity” have defined “decentralized” as having the option of choosing your identity provider. Self-sovereign identity goes further by having the individual be in control.

Note, with self-sovereign identity the individual still has the option of letting a trusted identity provider manage their identity, so we get the best of both worlds.

What makes self-sovereign identity possible today is the convergence of several technologies: Blockchain technology like Ethereum allows for shared, trusted computation that can fulfill the role played by identity providers today. Distributed data storage systems like Inter Planetary File System \([IPFS](http://ipfs.io/)\) have the ability to store data in a more efficient way than a blockchain but still benefit from the security of the blockchain. Finally, modern encryption technologies allow for combining privacy with the public nature of the blockchain.

**Developing Economies**

In the developing world, digital self-sovereign identity can be a big help to refugees and other disenfranchised people. Digital identities registered and controlled through a blockchain require no central company or organization to maintain, and can survive political and social turmoil so that refugees can retain access to their digital identities even under such difficult conditions.

​Furthermore, by using bleeding-edge technologies like [Enigma](http://enigma.media.mit.edu/) & [Hawk](http://oblivm.com/hawk/), it would even be possible to maintain a biometrics database that can be linked to the identities in privacy-preserving ways. Even without these future technologies policy architectures like those introduced by [Vinay Gupta](http://guptaoption.com/cheapid/) can provide a policy separation between biometrics databases and digital identifiers to implement privacy protection for biometrics.

## **Implementations**

We at ConsenSys have already started building the next generation of digital identity systems, built using the Ethereum blockchain and IPFS. Our [uPort](https://uport.me/) digital identity platform is used as a basis for digital identity based on **AML/KYC** \(Anti-Money Laundering/Know Your Customer\) protocols for our derivatives prototype, the Ethereum Total Return Swap \(eTRS\), the EtherLoan P2P-lending platform, the Inflekt Events management platform, educational credential issuance through [Ethense](https://consensys.net/academy/products/), and a threaded-discussions platform.

We are currently working on the designs and implementation of our Selective Disclosure features, where the user can encrypt the attributes associated to their identity and selectively choose which other identities they wish to share those attributes with. This is crucial in digital identity systems for governments and banks where the data attributes can be very personal and sensitive.

## **An Example** 

Let's explore a use case that many individuals experience. You go to a restaurant and attempt to purchase a beer. The waiter or server asks to see your identification in order to confirm you are the correct age to purchase a beer in the jurisdiction you are in. Currently, this entails providing the server or wait staff with a copy of a state or national identity card, that oftentimes has much more information displayed on it than you would like to share with the wait staff - for example, your home address, height, weight, eye color, and more. You have to trust that the wait staff will not take down this information or use it in any way that could bring harm to you. With self-sovereign identity, you would only have to provide confirmation that you are the appropriate age, not even what age you are. Scanning a QR code on your phone, the wait staff would be given a simple Yes or No to whether they can serve you that beer.

## **Expanding upon that Example**

Centralized repositories of information are similar to our example of trying to purchase that drink, just at a larger scale. Instead of just checking the age, oftentimes an organization will store information about the user, and often more information than was needed to give access to a certain benefit or service. Centralized repositories also carry risk for the users and the organization maintaining the central database - if it is hacked and data gets in the hands of those who would exploit it, the individuals whose data was stored in that database incur a major cost and the business or organization maintaining the central repository is often legally liable and will suffer consequences from users reluctant to trust them. In order to prevent this, the organization often have to invest in preventative measures, which raises costs for their users either directly or indirectly. Wouldn't it be better if no one had to take on that level of risk?

