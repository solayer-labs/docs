# SVN Modules

Shared Validator Network is a primitive-focused design that extends beyond the traditional AVS interface within the Solana Virtual Machine to ensure the code can be executed in a Solana contract should a dispute arise and not solvable by honest majority assumption.&#x20;

_In this documentation, we will detail the initial SVN primitives, but with a gradual release over time._

**Staking Module:** This module handles the staking of supported Liquid Staking Tokens (LSTs) and issues Re-Staked Tokens (RSTs) to users. RSTs can be deposited into the Delegator Module to earn additional yield through delegation to an Operator, thereby enhancing the security of the Shared Validator Network (SVN).

**Delegator Module**: Responsible for delegating RSTs issued by Solayer to an Operator who runs the AVS code. Operators, along with users who choose them, can be slashed for malicious behavior. Users have the flexibility to switch to a different Operator, provided the current one has not been slashed.

**Operator Module**: This module maintains a record of Operators and their statuses within the SVN, indicating whether they are active, slashed, or have exited the network.

**Slashing Module**: The Slashing Module is tasked with penalizing malicious Operators and updating their status in the Operator Module to reflect that they have been slashed. The Withdrawal Module relies on the Operator's status to enable withdrawals.

**Yield Module**: Responsible for the accounting and distribution of yield generated from the SVN network. This yield is derived from various AVS that are charged a fee for utilizing Solayer's Shared Security.

\
