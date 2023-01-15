# It's The Settlement Assurances, Stupid

Being sure that your Bitcoin transaction is settled and final is fundamental.

Bitcoin miners allocate colossal $$$ into mining which gives high confidence that, once buried under a few blocks, a transaction is unlikely to be reversed.

Other cryptocurrencies aren’t like that.

# Quantifiable variables

- ***ledger costliness*** - the amount paid to miners per unit of time. Miners’ resource-expenditure is roughly equivalent to that. At $20k Bitcoin, miners get paid $6.57B a year. Further, they may have invested more than $6.57B collectively in anticipation of future appreciation.
Bitcoin is protected by the daily salary it pays miners and the discounted awards these miners expect to earn in the future.

People mistakenly compare block-time - but as depicted with Litecoin, it doesn’t matter if it has 4x faster blocks when 4 Litecoin blocks are worth **15x less** than one Bitcoin block.

https://howmanyconfs.com/

Bitcoin is resistant to copycats - you can copy the code but can’t copy the value and settlement assurances derived from it. As of January 2023, Bitcoin Cash is 170x slower in settlement.

Strong settlement assurances in a proof of work system cannot be planned for. They can only emerge.

- ***yield from reversal: transaction size*** - the amount an attacker may win from reversing a large transaction - e.g. reversing a 50k Bitcoin transaction. [It is recommended](https://www.bloomberg.com/opinion/articles/2019-01-16/bitcoin-and-other-cryptocurrencies-are-open-about-being-at-risk) people wait to confirm large tx until ledger costliness reaches that value.
- ***monopoly on hardware*** - addressable hardware vs. percent of that hardware used to mine that chain. [ASICs align incentives](https://medium.com/sia-tech/choosing-asics-for-sia-b318505b5b51).

GPU-mined coins can never have final settlement because there are always many more GPUs in the world than those used for mining said blockchain. This means that it’s trivial to divert the hardware to attack the chain. e.g if 10% of GPUs are used to mine Bitcoin, it’s trivial to redirect 30% of supply to attack it.

# Unquantifiable variables
- ***top heaviness*** - if Ethereum has a market cap of $100B but $1T of smart contract assets are secured on top of it, attackers can earn more by shorting the $1T assets and attacking the base layer.
- ***liquid derivatives market*** - heavily use leverage to short, gaining disproportionately from a small move and use new funds to attack, hoping it drops the price.


# Takeaways
1. Block time is arbitrary and changes very little. **Ledger costliness** accrual is the time metric that matters - block time simply splits said security flow into smaller bits.
2. Bitcoin has a massive lead on ledger costliness
3. Settlement is always **probabilistic**. Cryptocurrencies hype “absolute finality”, but there is no such thing.
4. Bitcoin’s transparent security model is great because it makes it easy to reason about what’s a reasonable settlement assurance. Other blockchains seek **security through obscurity**.


----------------------------------------------------------------------

# META
- Original Author: Nic Carter
- Original Word Count: 5776
- Original Posted Date: July 22, 2019
- Original Source: https://medium.com/@nic__carter/its-the-settlement-assurances-stupid-5dcd1c3f4e41
