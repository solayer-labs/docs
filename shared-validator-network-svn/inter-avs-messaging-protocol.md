# Inter-AVS Messaging Protocol

For the SVN Network to operate in a trustless fashion, we introduce Inter AVS communication protocol which allows the operator nodes within the SVN network to communicate with each other, this means an AVS can spin up a whole network of nodes and provide resilience and backups while being fully synced. The first implementation of inter-AVS communication protocol will be inspired by Arbitrum's Inbox contract which allows an AVS to post messages to an Inbox on Solana which can be picked up by the receiver through a First In First Out FIFO queue system.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
