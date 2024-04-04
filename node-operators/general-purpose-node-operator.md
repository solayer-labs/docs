# General Purpose Node Operator

General Purpose Node Operators play a crucial role in maintaining the security and integrity of the Solana blockchain. They are responsible for finalizing blocks, validating transactions, and participating in the consensus mechanism.



### Type&#x20;

1. Must be a full node in the Solana validator set&#x20;

### High level responsibilities:&#x20;

1. **Block Validation and Finalization**:
   * Validate the correctness of transactions and blocks on Solana.
   * Finalize blocks, ensuring they are added to the blockchain in a secure and orderly manner.
   * Collaborate with other validators to reach consensus and maintain the chain's integrity.
2. **State Commitment Handling**:
   * Receive state commitments from sidecar-specific node operators.
   * Incorporate these state commitments into the blockchain to finalize transactions that originated from sidecars.
   * Validate for sidecar state accuracy and integrity.
3. **Consensus Participation**:
   * Actively participate in the Solana consensus mechanism (Proof of History and Tower BFT).
   * Propose and vote on blocks as part of the consensus process.
   * Work collaboratively with other validators to achieve network-wide consensus.



