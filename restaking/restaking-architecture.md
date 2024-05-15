# Restaking architecture

**Restaking architecture**

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

The restaking pool manager oversees the flow of assets into the protocol. When users deposit LST or SOL (which is first converted to sSOL-raw), they receive a fungible token representation in return. Currently illiquid, this representation will become liquid in the future to encourage composability with DeFi.

Once delegation to SVNs and node operators is live, users will construct their restaking portfolio by selecting the node operators to delegate to and SVNs to secure. They will then be issued a non-fungible token. This token is non-fungible due to the idiosyncratic risks associated with the selected node operators and the SVNs.



**Native SOL restaking**

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

For native SOL restaking, Solayer first converts your SOL to an intermediary form called sSOL-raw, which is the Liquid Staking Token (LST) issued by the stake pool manager. This entire process is non-custodial, ensuring that staked SOL is delegated to validators who earn MEV-boosted returns. The sSOL-raw is then converted to sSOL after another interaction with the Solayer restaking pool manager. All these steps are executed in a single transaction for efficiency.





