# Restake Points

This page details the point calculation for Stage 1 of Solayer development.&#x20;

**Token weighting**

| Token                    | Weighting |
| ------------------------ | --------- |
| Native Restaking         | 3         |
| Marinade-SOL restaking   | 2         |
| Blaze-SOL restaking      | 2         |
| JITO-SOL restaking       | 2         |
| Other LSTs (coming soon) | 1         |

\
**Epoch weighting**&#x20;

| Epoch            | Weighting |
| ---------------- | --------- |
| Genesis Epoch 0  | 3         |
| Epoch 1          | 2         |
| Epoch 2          | 1         |

**Referred restaking**&#x20;

Every restaker has 5 invite codes to begin with. We calculate and add 15% of their invited restaker's contribution and their derived points into your cumulative points.



**Points deduction**&#x20;

Restaked assets that are withdrawn before the conclusion of Epoch 2 will be deducted based on few parameters:&#x20;

1. Time of SOL entry into the protocol&#x20;
2. Amount of SOL withdrawal&#x20;

Total Point = Earned + Pending

Up on the withdrawal of X tokens:

* Earned = Earned + Pending  points due to X / 2
* Pending = Pending - Pending  points due to X / 2

\
\
