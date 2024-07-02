# Solayer swQoS Infrastructure

Stake-weighted quality of service (QoS) refers to the allocation of network resources, such as block space and transaction processing capacity, based on the amount of stake committed by validators or stakers. Under this model, a validator with 1% stake would have the right to transmit up to 1% of the packets to the epoch leader and would be capable of resisting Sybil attacks from the rest of the network. Commercial RPC infrastructure operators and entities hosting their own validator nodes and RPC nodes would benefit the most from this, as RPC nodes could include more transactions in blocks by agreeing to peer with validators, and validators may sell more capacity to RPC nodes.&#x20;

### How does swQoS work?

For example, if there are two validators—one holding 2% of the stake and the other holding 0.2%—the former will be able to submit up to 2% of the packets to the block producer, taking priority over the latter. This provides the higher-quality validator with better performance and increased Sybil resistance.

<figure><img src="../.gitbook/assets/image (4) (1) (1).png" alt=""><figcaption></figcaption></figure>

In simple terms, each transaction comes with weight. The heavier it is, the more likely your transactions get through. Consequently, the more you have at stake, the higher the quality of service you will receive, and the less likely it is that malicious flooding from lower-quality validators will affect you.

