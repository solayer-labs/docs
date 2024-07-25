---
description: Unstaking activated at 3 AM UTC (8 PM PST) on July 8th.
---

# Unstake sSOL

### Solayer Native SOL Unstaking Functions

Tokens can only be withdrawn from a stake account when they are not delegated. When you first un-delegate a stake account, it enters a "cooldown" phase. Tokens cannot be withdrawn until this process is complete and they are "inactive," meaning they no longer earn staking rewards. Once tokens in a stake account are inactive, they can be immediately withdrawn to your main wallet address. For details on the duration of this transition, please refer to [**Timing Considerations**](https://solana.com/staking#overview/delegation-timing-considerations).

### Withdraw

Withdrawing LSTs is simple. Select the amount you wish to withdraw, and the tokens will be sent back to your main wallet address.

* Upon withdrawing, you will be able to see the full amount of rewards, as well as the deductions from your account.&#x20;
* It is important to note that we are not deducting anything from your deposit but take a percentage of the accrued credits so far.

### Accounting Deduction

Our accounting system works as follows:

* The base calculation for rewards = deposit \* time-weight \* boost

Currently, native SOL has a significant priority over other LSTs. However, we may begin campaigns to boost other LST deposits. If you withdraw prematurely, you will incur a 50% reduction on the rewards accrued by the amount you are withdrawing. Check the [unstaking-credit-deduction.md](../../../community/solayer-valley-episodes/unstaking-credit-deduction.md "mention")page for more information.

***

## Examples

_**Withdrawing All Tokens from a Stake Account**_

1. User has a wallet with a balance of 900 SOL and a single stake account with 100 SOL delegated to a validator.
2. The user uses the wallet interface to deactivate their stake delegation. The stake account shows in the wallet interface and on the Explorer that it is “Deactivating.” Once it is “Inactive,” the staked tokens stop earning rewards and can be withdrawn.&#x20;
3. The wallet interface can be used to withdraw all tokens back into the main wallet account. The wallet balance now shows 1,000 SOL and the stake account is closed.

_**Reducing the Delegation Staked to a Given Validator**_

1. User has a wallet with a balance of 800 SOL and a single stake account with 200 SOL delegated to a validator.
2. User wants to reduce the amount of stake delegated to the validator by 100 SOL.
3. Use the wallet interface to “Split” the stake account and specify 100 SOL as the amount to split.
4. There are now 2 stake accounts, each with 100 SOL, delegated to the same validator.
5. The user can then use the wallet interface to deactivate one of their stake delegations. The stake account shows in the wallet interface and on the Explorer that it is “Deactivating.” Once it is “Inactive,” the staked tokens stop earning rewards and can be withdrawn.&#x20;
6. Once the account is inactive, the user can then choose to delegate the account to a different validator, withdraw the tokens back into the main wallet, or further split the inactive stake account and delegate to multiple different validators.

**Note:** Tokens in a stake account with a lockup may not be withdrawn until the lockup expires, regardless of the delegation state of that account. Once the lockup expires, undelegated tokens may be withdrawn immediately. There is no action required by the account holder to specifically unlock the account.
