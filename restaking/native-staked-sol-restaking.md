# Native Staked SOL Restaking

**Native SOL stake**

For native SOL restaking, Solayer first converts your SOL to an intermediary form called sSOL-raw, which is the Liquid Staking Token (LST) issued by the stake pool manager. This entire process is non-custodial, ensuring that staked SOL is delegated to validators who earn MEV-boosted returns. The sSOL-raw is then converted to sSOL after another interaction with the Solayer restaking pool manager. All these steps are executed in a single transaction for efficiency.



**Restaking pool manager**

The restaking pool manager manages the flow of assets into the protocol. When users deposit LST or SOL (which is first converted to sSOL raw), they receive a fungible token representation in return. Currently illiquid, this representation will be made liquid in the future to encourage composability with DeFi.

Once delegation to AVSs and Node managers is live, users will select the node operators and will be issued a non-fungible token. This token is non-fungible due to the idiosyncratic risks associated with the selected node operators and the SVNs.

The Solayer native restaking pool rebalances the asset across different validators to achieve maximum base yield etc, starting with Jupiter validator.&#x20;

_Note: sSOL is **not** redeemable and transferable until Epoch 6._&#x20;



**General Architecture of Native restaking**&#x20;

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>



