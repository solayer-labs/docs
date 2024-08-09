---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Liquidity

Liquidity is the most important factor for the adoption of any asset. Conversion delay and slippage are two key considerations.&#x20;

In an ideal world, there would be no slippage and instant conversion, so all Solana users should hold yield-bearing LSTs instead of SOL.&#x20;

What prevents this from happening is the liquidity of such LSTs. Each LST needs to have a deep pool with low swap fees and a significant amount of trading volume to offset the LP’s capital costs.&#x20;

<figure><img src="../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

To address this problem, Solayer introduces Superior Liquidity for AVS Tokens using a pooled liquidity design. Solayer AVS LST Tokens can be instantly unwrapped (or undelegated) back to the underlying representation, sSOL.&#x20;

Unlike others that use a multi-LST pool, where the liquidity for each LST depends on their LP pools (a less efficient design), Solayer consolidates all liquidity for Solayer AVS Tokens using the sSOL-SOL pair.

This strategy results in a significantly smaller price impact and significantly improved liquidity.
