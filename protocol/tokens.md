# Tokens

### DRAGON - dragonfinance.co Token

![dragonfinance.co (DRAGON)](<../.gitbook/assets/bomb-256 (1).png>)

Contract: [0x522348779DCb2911539e76A1042aA922F9C47Ee3](https://bscscan.com/address/0x522348779dcb2911539e76a1042aa922f9c47ee3)

The DRAGON token is designed to be used as a medium of exchange. The built-in stability mechanisms within the protocol aim to maintain DRAGON's peg of 100 DRAGON = 1 BNB in the long run.&#x20;

{% hint style="warning" %}
Note that DRAGON **actively pegs via an algorithm**, but that **does not mean** it will be valued at 100 DRAGON to 1 BNB at all times as **it is not collateralized**. **DRAGON is not to be confused for a crypto or fiat-backed stablecoin.**
{% endhint %}


### DSHARES - DRAGON Shares

![DSHARE](<../.gitbook/assets/dshare-256 (1).png>)

Contract: [0x531780FAcE85306877D7e1F05d713D1B50a37F7A](https://bscscan.com/address/0x531780face85306877d7e1f05d713d1b50a37f7a)

DRAGON Shares (DSHARE) are one of the ways to measure the value of the Bomb Money Protocol and shareholder trust in its ability to consistently maintain DRAGON close to peg. During epoch expansions the protocol mints DRAGON and distributes it proportionally to all DSHARE holders who have staked their tokens in the [**Boardroom**](boardroom.md).

DSHARE has a **maximum total supply of 70,001** tokens distributed as follows:

1. _Treasury/DAO Allocation: 5,500_ DSHARE vested linearly 12 months\*
2. _Team Allocation: 5,000_ DSHARE vested linearly over 12 months
3. _Rewards: 59,500_ DSHARE are allocated for incentivizing liquidity providers in two farming pools for 12 months
4. Initial mint: 1 DSHARE minted upon contract creation for the initial pool

{% hint style="success" %}
The Bomb Money team will use the treasury funds in any way that they feel is best for the long-term success of the protocol.&#x20;
{% endhint %}

### [DBOND - DRAGON Bonds](bonds-mechanism.md)

![DBOND](<../.gitbook/assets/dbond-256 (1).png>)

Contract: [0xDA1d9C79240003195d0a67f202efcCCC3F78b994](https://bscscan.com/address/0xda1d9c79240003195d0a67f202efcccc3f78b994)

The main purpose of DRAGON Bonds (DBOND) is to help incentivize fluctuations in the DRAGON supply during epoch contraction periods. When the TWAP (time-weighted average price) of DRAGON falls below 100 to 1 BNB, DBONDs are issued and can be bought with DRAGON at the current price. Exchanging DRAGON for DBOND burns DRAGON tokens, taking them out of circulation (deflation) and helps to get the price back up to peg. These DBOND can be redeemed for DRAGON when the price is above peg in the future, plus a premium based on how high above peg we currently are. This conversely creates inflation and subsequent sell pressure for DRAGON when it is above peg, helping to push it back toward 100 DRAGON to 1 BNB ratio.

{% hint style="info" %}
Unlike early algorithmic protocols, DBONDs do not have expiration dates.
{% endhint %}

All DBOND holders will be able to redeem their DBOND for DRAGON tokens as long as the treasury has a positive DRAGON balance, which typically happens when the protocol is in epoch expansion periods.
