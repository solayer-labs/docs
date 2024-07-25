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

# Use Ledger

**NOTE: Currently for all ledger users, please connect to Phantom for ease of experience.**&#x20;

1. First, we assume you already have Phantom downloaded in your browser extension. If not, please  set up with Phantom ([setup instructions](https://help.phantom.app/hc/en-us/articles/8071074929043-How-to-create-a-new-wallet)).&#x20;
2. Click on the top left menu icon&#x20;

<figure><img src="../../.gitbook/assets/image (7) (2).png" alt="" width="181"><figcaption></figcaption></figure>

3. Click on the "plus" button&#x20;

<figure><img src="../../.gitbook/assets/image (8) (2).png" alt="" width="183"><figcaption></figcaption></figure>

4.  Click "Connect Hardware Wallet"&#x20;

    <figure><img src="../../.gitbook/assets/image (9) (2).png" alt="" width="179"><figcaption></figcaption></figure>
5. Complete the process of connecting wallet with Phantom

<figure><img src="../../.gitbook/assets/image (10) (2).png" alt="" width="188"><figcaption></figcaption></figure>

6. Please make sure to enable blind signing, as the smart contract transactions cannot be displayed on Ledger. Therefore for third party integrations, you will only be able to sign the transaction if blind signing is on. [Please DYOR before doing so as well](https://www.ledger.com/academy/enable-blind-signing-why-when-and-how-to-stay-safe).&#x20;
7. You may see "unrecognized" as Ledger cannot read smart contract details, therefore Ledger will automatically display as "unrecognized"&#x20;
8. Direct back to app.solayer.org and make sure to click on “I am using Ledger with Phantom”

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

9. Click on Phantom tab
10. Confirm the transaction ([For ledger, message signature is not supported. The network fee you see here will not be broadcasted](https://spl.solana.com/memo))

<figure><img src="../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

11. Select "Confirm" transaction by confirming on your hardware device.

<figure><img src="../../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

12. You have successfully staked Native SOL.

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

13. You will see sSOL or sLST-SOL in your wallet as a representation SPL. Please note that it is NOT transferrable and will be made redeemable/transferrable at a later Epoch noted in our release schedule. Read more under the [restaking](https://docs.solayer.org/solayer-docs/restaking/restaking-architecture) [guide](https://docs.solayer.org/solayer-docs/restaking/restaking-architecture) to understand the denotation.&#x20;
14. As whitelisted individuals, you will be directly taken to app.solayer.org staking page.&#x20;
15. If you are not invited, please wait for Epoch 1. We work closely with supporters and collaborators for Epoch 0 for security reasons.&#x20;

***

**More details for Ledger users**

To ensure smooth functionality when interacting with smart contracts, it is essential to enable blind signing on your Ledger device. This is necessary because smart contract transaction details cannot be displayed on the Ledger screen. Consequently, for third-party integrations, you will only be able to sign transactions if blind signing is enabled. Here’s a clearer explanation:

#### Instructions for Enabling Blind Signing:

1. **Purpose:** Blind signing allows you to authorize transactions that cannot be fully displayed on the Ledger device, which is often the case with smart contract interactions.
2. **Requirement:** For any third-party application or integration that involves smart contracts, blind signing must be enabled on your Ledger device. Without this, you will not be able to complete the transaction signing process.
3. **Steps to Enable Blind Signing:**
   * Open the Ledger Live application on your computer.
   * Connect your Ledger device and unlock it.
   * Navigate to the settings menu.
   * Enable blind signing in the device settings.

By enabling blind signing, you ensure that you can seamlessly interact with smart contracts and complete necessary transactions, even when detailed transaction data cannot be displayed on the Ledger screen.\
