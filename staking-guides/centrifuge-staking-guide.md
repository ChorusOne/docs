---
description: How to stake on Centrifuge and other content related
---

# Centrifuge

## ![](../.gitbook/assets/centrifuge-3.png) Getting Started

Centrifuge is building the operating system to connect the global financial supply chain.

| Category                         | Details                                                                                      |
| -------------------------------- | -------------------------------------------------------------------------------------------- |
| **Chorus One Validator Address** | 4gF1YM8TioXtEPheVfA2XwqS4iMcwHXBXquwULxPbuvMv2Si                                             |
|                                  | 4g6s6HvkJX5ZMbf6vevVLLVSLmHRfJzqTfCHck6cUfQrtmXP                                             |
| **Wallet**                       | [Polkadot JS Chrome Extension](https://polkadot.js.org/extension/)                           |
| **Block Explorer**               | [https://portal.chain.centrifuge.io/#/staking](https://portal.chain.centrifuge.io/#/staking) |

Centrifuge is bridging real-world trade finance assets like company invoices into the world of decentralized finance through the Tinlake asset-backed lending protocol. Through Tinlake, users can tokenize non-liquid assets such as invoices (e.g. [ConsolFreight](https://medium.com/centrifuge/the-first-drop-for-defi-23e5240cadf2)) or streaming royalties (e.g. [Paperchain](https://medium.com/centrifuge/centrifuge-tinlake-and-paperchain-join-forces-to-accelerate-music-streaming-revenues-c83324d116e7,)) and borrow against these securitized assets.\
\
The Centrifuge Chain, which hosts the Tinlake protocol, is a Substrate-based Proof-of-Stake chain secured by a small set of validators including Chorus One. By delegating Centrifuge (CFG) tokens, stakers help maintain the network and its bridge to Ethereum, for which they earn staking rewards.&#x20;

## How to stake Centrifuge (CFG) tokens

### 1. Create a wallet using Polkadot JS extension

1. Download the extension [here](https://polkadot.js.org/extension/) and add it to your browser.&#x20;
2. Go to [https://portal.chain.centrifuge.io](https://portal.chain.centrifuge.io) and  authorize the connection to the extension
3. Go to `settings` and update the metadata
4. Now go to the extension and create a new address by adding an account
5. In the next step change the network name to `Centrifuge Mainnet` and create an account name and passphrase
6. You can then refresh the portal, check the `Accounts` tab. Your address should appear there.

{% hint style="danger" %}
Make sure to note down your mnemonic seed in a safe place! You will lose access to your funds if you forget or lose it. It is not recommended to store them on an unsecured laptop
{% endhint %}

![Polkadot JS Extension](<../.gitbook/assets/image (14).png>)

![Add Account](<../.gitbook/assets/image (15).png>)

![Save the mnemonic safely](<../.gitbook/assets/image (16).png>)

![Select Centrifuge Mainnet](<../.gitbook/assets/image (17).png>)

![View the account in the My Accounts section](<../.gitbook/assets/image (18).png>)

### 2. Create 2 accounts

To stake CFG tokens you require 2 funded wallets. Follow step 1 twice to create these two and some CFG to both.

1. **The stash account -** Main wallet
2. **The controller account** - Used for transactions and thus requires a small amount of tokens only.

![Two accounts](<../.gitbook/assets/image (19).png>)

### 3. Selecting a Nominator

1. Once you have both the wallets funded with some amount head over to the `Network` tab and select `Staking`.&#x20;
2. Under the Staking tab select `Account Actions` and add a nominator by clicking on `+Nominator`&#x20;
3. The `Setup Nominator` modal will appear. Make sure you select the correct stash and controller accounts.&#x20;
4. In the `value bonded` field add the number of tokens you want to stake.&#x20;
5. In the next step, nominate **Chorus One** as the validator.&#x20;
6. Finally, click on `Bond and Nominate` and authorize the transaction by clicking on `Sign and Submit`&#x20;
7. Your nomination will become active in the next session and your CFG tokens will start earning staking rewards

![Staking](<../.gitbook/assets/image (20).png>)

![Add Nominator](<../.gitbook/assets/image (21).png>)

![Setup Nominator](<../.gitbook/assets/image (22).png>)

![Staked! Waiting for nomination to become active!](<../.gitbook/assets/image (23).png>)
