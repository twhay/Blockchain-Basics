# Prediction Markets

### Adapted from [**Why & How Decentralized Prediction Markets Will Change Just About Everything**](https://medium.com/@ConsenSys/why-how-decentralized-prediction-markets-will-change-just-about-everything-15ff02c98f7c) ****- ConsenSys, 2015 and [**Markets for the Future**](https://medium.com/@ConsenSys/markets-for-the-future-c73fa73fe35d) - ConsenSys, 2016

## What are Prediction Markets? <a id="edc0"></a>

Prediction markets \(or the original coined term by Robin Hanson: “idea futures”\) aren’t new. What are they?

[**Prediction markets**](https://en.wikipedia.org/wiki/Prediction_market) \(also known as **predictive markets**, [**information markets**](https://en.wikipedia.org/wiki/Information_markets), **decision markets**, **idea futures**, **event derivatives**, or **virtual markets**\) are exchange-traded markets created for the purpose of trading the outcome of events.

You essentially bet against each other \(the market\) how an outcome will turn out. For example one could bet that Bernie Sanders will be the Democratic candidate vs Hillary Clinton in the next election.

You buy shares of each outcome that basically correlate to a percentage chance that the event will occur. Once the event has occurred, the prediction market will allow your shares to be redeemed for $1, while the other shares become worthless. For example, if you buy a Bernie Sanders outcome at $0.6 and Hillary Clinton outcome at $0.4, and Bernie becomes the candidate, you believed with a 60% chance that it will happen. Your Bernie token becomes worth $1. And your Hillary Clinton token becomes worth $0. Getting tokens is as simple as paying $1, upon which you get both. You can then precede to buy or sell them with others at various prices. If you don’t trade either of the outcomes that you bought, you will just get your money back \(since one will go to zero and the other to 1\).

Prediction markets have existed prior to the invention of the blockchain and still do exist. [Intrade was popular but had to exclude US traders](https://en.wikipedia.org/wiki/Intrade). It’s not an easy space to be in, since in some jurisdictions it is seen gambling, while in others it is seen options trading. The other worry is that it could create controversial incentives such as predicting the death of a global leader.

A global prediction market has thus not flourished as well as it could have. Even if it worked properly, building on top of it as a platform \(with APIs and such\) is also not an easy job, and there’s little guarantee that there won’t be another clamp down.

## Enter Decentralization <a id="7d87"></a>

Decentralized systems where innovation can happen without permission have allowed new \(& old ideas\) to flourish in wondrous new ways. We wouldn’t have Facebook, Wikipedia, or Twitter if the Web was not open. Free permission to innovate with information has led to where we are today. An open prediction market platform will come. It will most likely come to live on a blockchain. It not only helps with maintaining an open infrastructure for it, but it also allows separation of concerns \(who is doing what in this market\).

Currently there are three known decentralized prediction market efforts underway: Truthcoin/[Hivemind](http://bitcoinhivemind.com/) \(Bitcoin-based sidechain\), [Augur](http://www.augur.net/) \(recently raised $5.3m from a crowdsale, built on Ethereum\) and [Gnosis](http://groupgnosis.com/) \(working prediction market platform on Ethereum\). We will focus on what this will look like on Ethereum.

Ultimately, a prediction market will exist that will allow anyone to create markets, bet on outcomes and resolve/report the outcomes. The difference comes in when you add the following to this:

## **An Arbitration Market for Reporting**

At the end of the limit, the outcome of an event must be reported. In the past, this was usually reported by the people who ran the prediction market itself \(and you had to trust them to report correctly\). With a decentralized system you can swap this out for various systems. A market for an event can have one person decide.

If this person is trusted, then liquidity will come. If they are not, then multiple persons can report an outcome \(where 2 of 3 need to agree, for example\). Market participants can vote for who they want to report as well. Systems such as Augur have a token system where those who hold the token and vote on outcomes as a crowd. All these styles are swappable. In some circumstances you wouldn’t even need a report to be submitted. If the information is already on Ethereum, the resolution will happen without requiring a trusted source to report. For example, if someone is selling their song on Ethereum, and that is publicly accessible by other contracts, you can use that as is.

Finally, and perhaps the most interesting, is that all you need is a threat of an outcome for the market converge to the right outcome. The closer to the time an event comes, the more it starts to converge to the actual outcome as clarity increases. Thus, in a way, the tokens become worth zero on the one side and 1 on the other, automatically resolving itself. In a scenario where this actually ended up wrong, users can put up a deposit to dispute it: which results in arbitrator that has to come in and decide.

## **Automatic Betting**

This is arguably the most important. If it is an open layer any program can start predicting. Prediction markets only played by slow humans who have to do the thinking won’t ever have enough liquidity to be useful. Programs can absorb much more and make much better predictions about the future.

Automatically gathering knowledge about the world & combining it correctly will result in financial gain. Thus, companies like Google & Facebook will be at a considerable advantage, betting on these prediction markets. Dumb sensors in every avenue could either predict themselves or sell the information \(more on this later\). And finally, you can build bots that predict based on some model: it could be based off a person, a group, or any combination \(also more on this later\).

The difference here vs. a traditional market maker is subtle. The purpose is not facilitate trading, but to automate predictions.

## The Result? <a id="0f38"></a>

Once you add these parts, you get wonderful potential emergent behavior. Here are some examples:

## **Information Markets**

You sell your information to be used in markets. If the information is in the same ecosystem as the prediction markets \(say, Ethereum\), then you can sell this information to be used in a trust-less manner inside the market itself. This is a holy grail for several reasons. The oft talked about “Internet of Things” will be extremely useful here. A sensor can produce information, & put it on the blockchain \(public\). If it's used for reporting, it can charge for that information. It could also result in markets where the information is not made public, but encrypted, upon which it can then be sold to others to gain knowledge to predict more effectively. So, information markets can develop around selling information to help predict & report. This won’t just exist for sensor data. It would eventually become the norm to report any kind of data into the blockchain, especially for reporting purposes. It not only means that you can have audited & transparent information in there, but it also means you immediately provide a trust source for information to be bet on, at very little cost to the producer.

## **New Kinds of Organizations** 

With the rise of social media, people have been seeing its ability to move people together in new ways: driven by a common goal, bereft of normal bureaucratic process. The Arab Spring is a good example, where these movements remain relatively head-less. Recently, in South Africa a movement to reduce tertiary tuition fees rallied around a hashtag \(\#feesmustfall\) that formed the locus of the liquid organization.

These organizations are unlike what we’ve seen before because social media allows near instant communication and allows important news & events to immediately filter up \(based on retweets\) and then subsequently affect and inform the rest of the organization. Affiliation is as easy as using the hashtag. It’s the network’s version of an organization. There is no permission to be a part of it.

How does one build ways to incentivize these new organizations and how do you help it make decisions? You use prediction markets. Just as these hashtag organizations move like crowds do, so should its decision making. As the organization goes about its goals, various outcomes are constantly generated, upon which the people in the organization and those outside of it, bet on the outcomes, leading it automatically towards outcomes which serve the goals of the organization.

Since these network organizations move at the speed of social media, you might need some help from our bot friends to bet on your behalf. And this leads to the next part...

## **Wealth Sharing** 

If prediction markets will be so useful in creating wealth for those in the know, then you might want to developed automated personalized prediction bots. These bots automatically bet on events based on who you are & what you do. If you join a hashtag organization \(the tweet appears in your feed\), then the bot automatically detects this and assumes this as indicator that marginally this movement might succeed and thus bets on those outcomes \(resulting in automatic financial gain\). Another example is where if you frequent a coffee shop, your bot will automatically start betting on the revenue that will be posted by this shop. You are directly influencing its success by being a patron and thus you can partake in the financial gain of it.

This presents a potentially whole new way of looking at organizations. Perhaps into the future we won’t even need things like shares/equity. Money simply flows towards some locus, upon which it is used to improve a metric that can be predicted upon. It paints a new model of “investment”. If you donate $10,000 to an organization or group, you know that its metric of success will improve and thus you can benefit from that financial gain. There are countless metric which could be influenced in this manner- just by “being alive”, you affect them. These opportunity will become available to all, at any scale.

## **Protecting Natural Systems**

Is it possible to use prediction markets to protect our climate & environment? [Karl Schroeder describes such a potential system in this forum post](https://forum.ethereum.org/discussion/392/deodands-dacs-for-natural-systems).

In essence, you have AI automatically interacting with a natural system, in order to protect it. At the base of this could be prediction markets. A metric could be something like: growth of new trees in an area.

If you are interested in seeing the ecosystem flourish, you can get financial gain from it, by simply protecting & fostering it \(you first predict, then enact the change\). You make sure that a certain amount of trees are planted. Sensors can provide much more nuanced feedback and reporting vs more concrete outcomes \(such as trees planted\). For example, measuring pollution. This information will be sold to interested parties. To bring these sensors into existence they can be crowdfunded by a group of environmentalists, who will earn these fees, which subsequently can result in further creating a sustainable ecosystem.

## **Futarchies**

Policy decisions are at the core of all governance models. Organizations must make decisions on which policies to implement in order to maximize future welfare. For a government, this could mean deciding budget allocation. Should a portion of the budget be allocated for infrastructure projects or for education? Which will result in greater GDP?

Within a corporation, disputes could arise over whether or not to acquire a company. Metrics on share price or future revenue may be the deciding factors. In most cases of governance, such decisions are made using a range of Democratic or Autocratic processes. The former involves a voting process in which members of an organization or government cast votes \(allocated through an egalitarian or proportional representation\) where a plurality, majority, or supermajority is required to implement a decision. The latter involves a hierarchical model in which designated individuals make absolute decisions over their areas of control. Both of these models suffer from information inefficiencies, often resulting in the implementation of policies that poorly optimize future welfare.

## Futarchy - An Alternative Market-Based Approach to Governance.

In Futarchy, markets are used to decide on and implement policies. These markets follow a general form of “What will a future welfare metric be if a policy is implemented?”

For example, a corporation could ask, “What will our Q4 revenue be if we fire our CEO?” and conversely, “What will our Q4 revenue be if we don’t fire our CEO?” Following this, speculators who believe they hold unique insights into the outcome of firing or keeping the CEO are incentivized to participate in these markets. If they think that revenue will be maximized by firing the CEO, then they will buy long shares in the expected revenue if the CEO is fired and short shares in the expected revenue if the CEO is not fired. Upon market closure, a decision is made corresponding to the greater expected outcome. In our CEO example, if the market value for expected Q4 revenue if the CEO is fired is greater than the revenue if CEO is not fired market, then the organization fires the CEO. Market participants are then rewarded depending on their accuracy in predicting future revenue.

In this model, governance is both marketized and automated. Policies are determined by values found on an open market and implemented through bound delegates or an automated process. Prediction markets have shown to be the most efficient information aggregation tool leading to the prediction that Futarchy can more accurately identify policies that will optimize outcomes while also lowering bureaucratic overhead.

## Futarchy Applications in a Variety of Institutions

Nearly all existing organizations can improve their model of governance by using an implementation of Futarchy. State governments can allow citizens to democratically vote on which metrics to optimize for and create markets to let the wisdom of the crowd inform how to reach those goals. Corporations can overhaul stockholder decision making using Futarchy while also reducing the need for high level management. Perhaps most interesting to the Ethereum and Blockchain ecosystem is the ability for Futarchy to provide a governance model for Decentralized Autonomous Organizations which is both effective and less reliant on centralized trust and decision-making processes.

Robin Hanson, the inventor of Futarchy and father of modern prediction markets, argues that

> Futarchy seems promising if we accept the following three assumptions:
>
> 1. Democracies fail largely by not aggregating available information.
> 2. It is not that hard to tell rich happy nations from poor miserable ones.
> 3. Betting markets are our best known institution for aggregating information.

The first of these conditions has become evident through political gridlock between parties, as well as yellow and captured journalism leading to a poorly informed populace. The second condition is provided by widely available metrics such as income per capita, GDP and the World Happiness Index, and the last is a conclusion of the efficient market hypothesis. Primary barriers to Futarchy adoption are lack of real world case studies, lack of general purpose Futarchy solutions, and entrenched institutions that are resistant to new models.

## Conclusion <a id="5d7f"></a>

A prediction market is a powerful idea. A decentralized prediction market is an even more powerful idea. Once we combine the capability to automate predictions with AI, Machine Learning, and the Internet of Things, it becomes something that could change just about everything. It will result in being able to model externalities in a much better fashion.

