# From Staked SOL to Endogenous AVS Tokens

Solayer provides decentralized applications (dApps) with a simple method to create their own AVS LST. These tokens come with Solana’s native staking yield as their base rewards, along with additional MEV yields. Solayer optimizes the staking yield by delegating it to the highest yield-bearing validators. \
\
Additionally, Solayer runs its own validator implementation that supports app-level stake-weighted quality of service provisioning. Moreover, dApps can receive a portion of the staking commission and will be able to configure the underlying operators for stake delegation in the future. The Solayer AVS Token is a delegated representation of sSOL, which is the Solayer-managed LST token on Solana.\
\
In the future, we envision dApps having direct control over the validators to which the underlying SOL is delegated. They should also be able to configure the required stake-weighted quality of service with a dynamic pricing mechanism depending on the current network workload.

### General Flow of sSOL

1. _**Deposit and Receive sSOL:**_

* Users deposit their stake into the native SOL pool and receive sSOL tokens in return.

2. _**Delegate sSOL:**_

* Restakers delegate their sSOL into the e-AVS (endogenous Actively Validated Services) pool and receive AVS wrapper SPL tokens.

3. _**Provision and Inclusion:**_

* e-AVS directly receives the delegated stake with an assigned validator, increasing the probability of block space provisioning and transaction inclusion.

4. _**Incentives:**_

* e-AVS can reward and incentivize more delegates to enhance participation.

5. _**Yield Commission:**_

* e-AVS earns a commission from the staking yield.

### Getting an AVS Token&#x20;

First, users convert SOL into its natively staked form, sSOL. Staked SOL will be delegated to Solayerrecommended validators. They then delegate it to an endogenous dApp AVS on Solayer, which converts 2 sSOL to a delegated form. Finally, Solayer AVS mints AVS tokens which can later be used as a stake proof to retrieve staked SOL back and claim rewards.

<figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>
