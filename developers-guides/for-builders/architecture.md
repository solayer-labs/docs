# Architecture

<figure><img src="../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

The restaking pool manager oversees the flow of assets into the protocol. When users deposit LST or SOL (which is first converted to sSOL-raw), they receive a fungible token representation in return. Collectively, we call them Solayer assets. Currently illiquid to facilitate points calculation for the liquidity reward program, this representation will become liquid in the future to encourage composability with DeFi.

Solayer assets at this layer won't have any unbinding lockups since they unwrap into the respective LSTs. The AVS unbinding process is separately managed by the delegation manager. To offer more flexibility, Solayer allows them to design their unbinding process with a maximum unbinding period of 2 days. Solayer will also provide an emergency exit mechanism to release the bound stake from users should the AVS cease to function.

Stage 2 of our protocol development will enable users to pledge their Solayer assets to secure additional networks by delegating them to a Solayer operator responsible for managing the AVS nodes. Should an operator engage in malicious behavior, they will be subject to penalties, potentially resulting in a loss of the user's deposit. Consequently, users must exercise caution when selecting operators to delegate to, ensuring that they possess a trustworthy track record and fulfill the requisite criteria of the AVS.

Once delegation to SVNs and node operators is live, users will construct their restaking portfolio by selecting the node operators to delegate to and SVNs to secure. They will then be issued a non-fungible token. This token is non-fungible due to the idiosyncratic risks associated with the selected node operators and the SVNs.

Rewards accounting is calculated offline. Solayer has implemented a state watcher to keep track of deposits and withdrawals. Together with the invite relationship data, additional rewards will be applied to user accounts in real time.

The Restake method on Solayer is permissioned and requires an additional signature from the server. This is to allow us to enforce deposit limits in the first few epochs. The Unstake method does not require an additional signature from Solayer.
