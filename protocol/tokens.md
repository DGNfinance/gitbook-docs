# Tokens

### DGN - dragonfinance.co Token

![dragonfinance.co (DGN)](<../.gitbook/assets/dgn.png>)

Contract: [0x2757d8A156536C230b5b8a15287B0C4a3F70b500](https://bscscan.com/address/0x2757d8A156536C230b5b8a15287B0C4a3F70b500)

The DGN token is designed to be used as a medium of exchange. The built-in stability mechanisms within the protocol aim to maintain DGN's peg of 100 DGN = 1 BNB in the long run.&#x20;

{% hint style="warning" %}
Note that DGN **actively pegs via an algorithm**, but that **does not mean** it will be valued at 100 DGN to 1 BNB at all times as **it is not collateralized**. **DGN is not to be confused for a crypto or fiat-backed stablecoin.**
{% endhint %}


### DSHARES - DGN Shares

![DSHARE](<../.gitbook/assets/dshares.png>)

Contract: [0x5D7C9dfCe171824EC74bd44C424019fAf3fc32a5](https://bscscan.com/address/0x5D7C9dfCe171824EC74bd44C424019fAf3fc32a5)

DGN Shares (DSHARE) are one of the ways to measure the value of the Dragon Finance Protocol and shareholder trust in its ability to consistently maintain DGN close to peg. During epoch expansions the protocol mints DGN and distributes it proportionally to all DSHARE holders who have staked their tokens in the [**Boardroom**](boardroom.md).

DSHARE has a **maximum total supply of 70,001** tokens distributed as follows:

1. _Treasury/DAO Allocation: 5,500_ DSHARE vested linearly 12 months\*
2. _Team Allocation: 5,000_ DSHARE vested linearly over 12 months
3. _Rewards: 59,500_ DSHARE are allocated for incentivizing liquidity providers in two farming pools for 12 months
4. Initial mint: 1 DSHARE minted upon contract creation for the initial pool

{% hint style="success" %}
The Dragon Finance team will use the treasury funds in any way that they feel is best for the long-term success of the protocol.&#x20;
{% endhint %}

### [DBOND - DGN Bonds](bonds-mechanism.md)

![DBOND](<../.gitbook/assets/DBond.png>)

Contract: [0x24a18BD578A8Bfe3B7C87477C78A9290451969ee](https://bscscan.com/address/0x24a18BD578A8Bfe3B7C87477C78A9290451969ee)

The main purpose of DGN Bonds (DBOND) is to help incentivize fluctuations in the DGN supply during epoch contraction periods. When the TWAP (time-weighted average price) of DGN falls below 100 to 1 BNB, DBONDs are issued and can be bought with DGN at the current price. Exchanging DGN for DBOND burns DGN tokens, taking them out of circulation (deflation) and helps to get the price back up to peg. These DBOND can be redeemed for DGN when the price is above peg in the future, plus a premium based on how high above peg we currently are. This conversely creates inflation and subsequent sell pressure for DGN when it is above peg, helping to push it back toward 100 DGN to 1 BNB ratio.

{% hint style="info" %}
Unlike early algorithmic protocols, DBONDs do not have expiration dates.
{% endhint %}

All DBOND holders will be able to redeem their DBOND for DGN tokens as long as the treasury has a positive DGN balance, which typically happens when the protocol is in epoch expansion periods.
