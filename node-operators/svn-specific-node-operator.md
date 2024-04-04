# SVN-Specific Node Operator

Sidecar-Specific Node Operators are superset of validators dedicated to specific sidecars, through nominated or random consensus algorithms. Their primary role is to manage sidecar operations, which involve collecting and sequencing transactions specific to a designated sidecar, and providing state commitments to General Purpose Node Operators for finalization.

**Type**

* Can operate as light nodes within the Solana validator set.

**Key Responsibilities**

1. **Transaction Collection and Sequencing**:
   * Collect transactions that are designated for the sidecar to which the operator is assigned.
   * Sequence the transactions in an orderly and efficient manner, ensuring that they are ready for inclusion in the Solana blockchain.
2. **State Commitment Provision**:
   * Generate state commitments for the sequenced transactions.
   * Provide these state commitments to General Purpose Node Operators, enabling them to finalize the transactions on the Solana blockchain.
3. **Sidecar Maintenance**:
   * Ensure the smooth operation of the sidecar, including monitoring its performance and handling any issues that arise.
   * Keep the sidecar software updated and in sync with the Solana network.\
