# Bonds (DBOND)

![The "Pit", where you can interact with the protocol's bonding mechanism](<../.gitbook/assets/bond.png>)

### What are DBOND (Bonds)?

Bonds are unique tokens that can be utilized to help stabilize DGN price around peg (100 DGN = 1 BNB) by reducing the circulating supply of DGN if the TWAP (time-weighted average price) goes below peg.

### When can I buy DBOND (Bonds)?

DBOND can be purchased only during periods of supply contraction and when the TWAP of DGN is below 1.

At the beginning of every new epoch during contraction periods, DBONDs are issued in the amount of 3% of DGN's circulating supply, with a max debt amount of 35%. This means that if bonds reach 35% of the circulating supply of DGN, no more bonds will be issued.

{% hint style="info" %}
Note that during a zen epoch (when an epoch ends with a TWAP between 1.0 - 1.01), **no DBOND will be issued, even though the Boardroom does not print.**
{% endhint %}

{% hint style="danger" %}
DBOND TWAP (time-weighted average price) is based on the DGN TWAP from the previous epoch as it ends. In other words, the DGN TWAP is real-time but the DBOND TWAP is not.
{% endhint %}

### Where can I buy DBOND (Bonds)?

You can buy DBONDs if any are available through [dragonfinance.co](https://dragonfinance.co/bond) in the [Pit](https://dragonfinance.co/bond). Anyone can buy as many DBONDs as they want as long as they have enough DGN to pay for them.

There is a limit of available DBONDs per epoch during contraction periods (3% of DGN's current  circulating supply), and are sold first-come-first-serve.

### Why should I buy DBOND (Bonds)?

The first and most important reason to buy DBOND is that they help to maintain the peg, but they are not the only measure in place to keep the protocol on track.&#x20;

DBONDs don't have an expiration date, so you can view them as an investment in the long-term health of the protocol to be redeemed for a premium at a later date.

#### Incentives for Holding DBOND

The idea is to reward DBOND buyers for helping the protocol, while also protecting the protocol from being manipulated by big players.

So after you buy DBOND using DGN, you have two possible ways to get your DGN back:

1. Sell back your DBOND for DGN **while the peg is between 1 - 1.1** (100 DGN = 1 BNB) with no redemption bonus. This is in place to prevent an instant dump as soon as peg is recovered.
2. Sell back your DBOND for DGN **while the peg is above 1.1** (100 DGN = 1 BNB) with a bonus redemption rate.

The longer you hold, the more both the protocol and you benefit from DBOND.

{% hint style="success" %}
Example:

1. When DGN = 0.8, burn 1 DGN to get 1 DBOND (DBOND price = 0.8)
2. When DGN = 1.15, redeem 1 DBOND to get 1.105 DGN (DBOND price = 1.27)&#x20;
{% endhint %}

So, which one is better?

If I buy DGN at 0.8, and hold it until 1.15 and then sell, I'm getting +$0.35 per DGN.

But, if I buy DGN at 0.8, burn it for DBOND, and redeem it at 1.15, I'm getting 1.105 DGN \* 1.15 (DGN current price) = 1,271 (+$0.47) per DBOND redeemed.

But, what if getting back to peg is taking too long?

We will adjust our use cases to have different behaviors on contraction and expansion periods to benefit both DGN and DBOND holders when needed.

### What is the formula to calculate the redemption bonus for DBOND?

To encourage the redemption of DBOND for DGN when DGN's TWAP > 1.1 and in order to incentivize users to redeem bonds at a higher price, DBOND redemption is designed to be more profitable with a higher DGN TWAP value. The DBOND to DGN ratio is 1:R, where R can be calculated using the formula as shown below:

$$
R=1+[(DGNtwapprice)-1)*coeff)]
$$

$$
coeff = 0.7
$$

### When can I swap DBOND for a premium?

You can only redeem DBONDs for a premium when the previous epoch's TWAP is greater than 1.1.
