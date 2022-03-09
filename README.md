---
description: About dragonfinance.co
---

# Introduction

Welcome to Dragon Finance! If this is your first time here, please take some time to read through this documentation before you begin using the protocol. This documentation is intended to take you through the entire process of how to get started using Dragon Finance to earn stable, high yields that are only possible through the power of DeFi, but with the stability and security of exposure to BNB, the world's largest and most stable crypto asset. Let's dive in!

## Origins

Dragon Finance is based upon the work of the brilliant **tomb.finance** project on the Fantom network. At the time, it was hard to believe that nothing similar existed on any other larger networks, so it was a great opportunity to bring an amazingly stable and robust DeFi protocol like **tomb.finance** with a few unique twists to the masses. As far as networks go, Binance Smart Chain (BSC) seemed like the perfect choice with its fast transaction speeds, low gas fees, and much larger user base, so one thing led to another and now here we are!\
\
This project would certainly not be possible without the work of the [tomb.finance](https://tomb.finance) team. Their project being fully open source and developed exceptionally well made it a pleasure to work with, and we would not be here today without their efforts, so we want to give a special thank you to them for that.

{% hint style="info" %}
Dragon Finance will be launched on March 15, 2022.
{% endhint %}

## What's the point?

Ultimately, the purpose of the Dragon Finance protocol is to provide the means for its underlying DGN asset to maintain a value that is algorithmically pegged to the value to BNB  at a 100 to 1 ratio.

So, what good is that? We will explore this idea further throughout this documentation, but for now without getting _too_ technical, this opens up a world of possibilities for existing, long-time BNB holders, people already familiar with DeFi, as well as new users just coming into the space.

BNB transactions are slow and expensive. There are not nearly as many attractive yield earning opportunities in DeFi for people to put their precious BNB to work for them. DGN, through the Dragon Finance protocol, can solve many of these problems and more, generating immense value for our users in the process.

As the Dragon Finance ecosystem grows over time, the potential future applications are quite literally endless. And, as you proceed through this documentation and learn more about how the Dragon Finance protocol works, we will explore some of that potential in more detail.

{% hint style="info" %}
DGN is the native token of the Dragon Finance protocol. The built-in stability mechanisms within the protocol aim to maintain DGN's peg of 100 DGN = 1 BNB  in the long run.
{% endhint %}

## What are the Dragon Finance protocol tokens?&#x20;

Dragon Finance multi-token protocol currently consists of the following three tokens, and each plays a critical role in how the protocol works to maintain peg:

1. **DGN Tokens ($DGN)** - The DGN token is designed for use as a medium of exchange, and is intended to have many other use cases as the Dragon Finance ecosystem grows. DGN is algorithmically pegged to BNB  at a ratio of 100 DGN to 1 BNB.
2. **DGN Shares ($DSHARE)** - DSHARE can be staked in the [Boardroom](protocol/boardroom.md) to earn a portion of minted DGN as rewards to those DSHARE holders for investing in the health and stability of the protocol.
3. ****[**DGN Bonds ($DBOND)**](protocol/bonds-mechanism.md) - DBOND’s main job is to help incentivize and reward users for helping to regain peg during times of supply contraction below peg.

## How does it work?

The Dragon Finance protocol works through a synergistic design of unique tokens and mechanisms that create an automatic, self-reinforcing system to help maintain the peg (100 DGN = 1 BNB). Each of these tokens and mechanisms will be explained in further detail within this documentation, but for now let's have a look at a brief overview of how it all works:

* When **DGN price is over the peg**, new DGN are minted by the protocol to inflate the supply in an attempt to drive the price down towards the peg. These new DGN are allocated to DSHARE holders in the Boardroom, as a reward for their investment and trust in the protocol. This in turn increases the demand for and the value of DSHARE.
* When **DGN price is at the peg**, no new DGN will be minted, keeping the supply fixed during this time. Since there will be no new supply coming in, the peg will be maintained indefinitely at this point unless there is a shift in demand. More buying pressure during this time will push the price back up above the DGN minting threshold. Conversely, more selling pressure will push the price below the peg.
* When **DGN price drops below the peg**, the protocol will begin to mint DBONDs (up to a maximum debt limit). Experienced investors will have the ability to exchange their DGN for these DBOND, which they can then redeem for DGN at a premium above peg in the future. This removes DGN from the total supply, applying upward pressure on the price towards the peg. Besides this, investors who believe in the protocol's ability to maintain peg can just buy DGN to essentially purchase BNB at a discount to the market. Both of these incentives are intended to create upward pressure on DGN's price when under the peg so that the peg can be regained over time.

{% hint style="info" %}
There are so many different ways you can utilize the mechanisms of the Dragon Finance protocol to earn yield. Pick a strategy that is right for you, based upon your own knowledge and experience. Even the most simple and basic of strategies can earn great returns, but feel free to experiment with more complex strategies as you learn how the protocol works!
{% endhint %}

## What exactly is the peg?

DGN is a token that is intended to track the price of BNB  algorithmically. The ratio for this peg is set at 100 DGN to 1 BNB. DGN **actively tracks this peg via an algorithm**, but that **does not mean** it will be valued at 100 DGN to 1 BNB at all times as **it is not collateralized**. **DGN is not to be confused for a crypto or fiat-backed stablecoin.**&#x20;

The entire design of the Dragon Finance protocol is intended to try and maintain this peg as closely as possible, but as it is an algorithmic peg, this will never be a completely stable process. In fact, some of the unique profit-generating opportunities offered by the protocol actually only exist because of these price fluctuations.

To put it simply, there will **almost certainly be times when the price of DGN is below peg**. This is a natural part of the process, and opens up opportunities for active investors/traders to "buy the dip" and help support the protocol by regaining peg, while also profiting from the discounted price.

![A visualization of DGN price in relation to peg](<.gitbook/assets/DGN Price Visualization.png>)

When the protocol is healthy and stable, the price of DGN will likely look similar to above, with price fluctuating above and below peg as the mechanisms of the protocol work to influence supply and demand and maintain an average price around the peg.

Keep this in mind when developing your strategies and when taking a more active role in the protocol.
