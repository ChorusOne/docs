---
description: How to stake your Injective using Metamask
---

# Injective

## About

The Injective Chain is a layer-2 sidechain and Cosmos Zone connected to Ethereum. Injective supports permissionless trading on arbitrary derivative markets, allowing individuals to create and trade on any derivative market of their choosing. The Injective protocol is implemented on top of Tendermint using the Cosmos-SDK which hosts Injective's decentralized order-book and trade execution coordinator.

| Category               | Details                                                                                                                                                                                           |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Delegation Address** | injvaloper14yeq3lkajldaggj28hmq8xng9xux7x5g46hezv                                                                                                                                                 |
| **APY**                | 4.36 %                                                                                                                                                                                            |
| **Wallet**             | Metamask, Ledger                                                                                                                                                                                  |
| **Block Explorer**     | [https://explorer.injective.network/](https://explorer.injective.network)                                                                                                                         |
| **Staking Rewards**    | [https://www.stakingrewards.com/earn/injective-protocol/](https://www.stakingrewards.com/earn/injective-protocol/)                                                                                |
| **Unbonding Period**   | **Withdrawal Delay:** After withdrawing, your staked funds will only become accessible after the unbonding period (1 day) has passed. It takes a further 7 days to withdraw INJ back to Ethereum. |

## How to Delegate <a href="#8662" id="8662"></a>

### 1. Connect Your Wallet <a href="#8662" id="8662"></a>

![](<../.gitbook/assets/image (45) (1) (1).png>)

Click on `Metamask` and complete the signature request by clicking **Sign**. This will enable you to access the dashboard dapp, where you will be able to view validators and delegate your INJ tokens to them.

![](<../.gitbook/assets/image (43) (1) (1) (1).png>)

### 2. Pre-stake your ERC-20 INJ Tokens <a href="#6fff" id="6fff"></a>

Staking allows INJ holders to delegate their tokens to active validators and share part of the rewards obtained by the validator as a part of the Proof of Stake consensus. Specifically, It allows native token holders to take part in the consensus process without running a validator themselves.

The first step to staking your INJ on the Equinox testnet is to pre-stake your INJ on Ethereum. During this step, your INJ tokens will be locked on Ethereum for 7 days and you will receive an equivalent amount of INJ tokens on the Kovan Ethereum testnet which you can then transfer to the Injective Chain.

Click `Stake` from the header.

\


![](<../.gitbook/assets/image (42) (1).png>)

Click the unlock button on the Stake page to approve the transfer of your INJ tokens by the deposit manager smart contract.&#x20;

![](<../.gitbook/assets/image (60) (1) (1) (1) (1) (1) (1) (1).png>)

Approve the transaction in Metamask by clicking `Confirm`

{% hint style="warning" %}
_Depending on how much gas you submitted with the transaction and the current load on the Ethereum network, your transaction may either complete quickly or take several minutes._
{% endhint %}

Once the transaction is completed on Ethereum, the Stake page will display a form where you can enter the amount of your ERC20 INJ tokens you would like to pre-stake.&#x20;

![](<../.gitbook/assets/image (52) (1) (1) (1) (1) (1) (1).png>)

{% hint style="warning" %}
_Staking will lock your INJ for 7 days. If you choose to withdraw your tokens before the staking competition is completed, you will not be eligible to receive any rewards._
{% endhint %}

A modal will appear to confirm your stake. Please note the message about the lock schedule, and then click the `Stake` button to confirm.

![](<../.gitbook/assets/image (65) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)

Confirm the transaction in Metamask. Once your transaction is completed on Ethereum with enough confirmations, this amount will be reflected on the Pre-stake page under `Total Pre-Staked INJ`. The amount should take about 2 minutes to appear.

![](<../.gitbook/assets/image (56) (1) (1) (1) (1) (1).png>)

### 3. Connect to Kovan Network and confirm your staked INJ balance <a href="#709c" id="709c"></a>

The next steps involve transferring your INJ to the Injective Chain through the Injective to Ethereum bidirectional ERC-20 Bridge. To save on gas costs, all INJ pre-stakers are airdropped the equivalent amount of Kovan INJ on the Kovan Ethereum testnet.

After your pre-stake is complete, your Kovan INJ Balance will be updated and you will be able to transfer your Kovan INJ to the Injective Chain.

To do so, click `Wallet` from the top menu bar to open the wallet page.

![](<../.gitbook/assets/image (49) (1) (1) (1) (1) (1).png>)

Open Metamask and connect to the Kovan network from the dropdown as shown below. Refresh the page after you switch.

![](<../.gitbook/assets/image (50) (1) (1) (1) (1) (1).png>)

Under _My Balances_ you should be able to see how many INJ tokens you have in your wallet on three networks: Mainnet (Ethereum Network), Kovan (Ethereum Testnet), and on Injective Chain (Equinox Injective Testnet).

![](<../.gitbook/assets/image (58) (1) (1) (1) (1).png>)

### 4. Approve Transfer of your KINJ (Kovan INJ) Tokens <a href="#346f" id="346f"></a>

Before you can fully transfer your INJ tokens to Injective, you will have to approve the transfer of your Kovan INJ (KINJ) tokens by the smart contract on Kovan. Under the _Transfer_ section, click the lock icon to initiate the approval/unlock process.

![](<../.gitbook/assets/image (48) (1) (1) (1).png>)

This will open a transaction request in Metamask. Your wallet will be provided with Kovan ETH to cover the gas fee. Confirm the transaction request to approve the transfer. Once your approval is confirmed, you will see a _Token Unlocked_ notification appear at the bottom right of the page. You will now be able to transfer your KINJ (Kovan INJ) tokens to the Injective Chain.

### 5. Transfer KINJ from Kovan to Injective Chain <a href="#220a" id="220a"></a>

Enter the amount of KINJ tokens you would like to send from Kovan to Injective Chain and then click **Transfer**. This will open a transaction confirmation in Metamask. Once again, you have been supplied with the necessary Kovan ETH to cover the gas fee. Click **Confirm**.

![](<../.gitbook/assets/image (62) (1) (1) (1) (1) (1) (1) (1).png>)

Once your transaction is confirmed on Kovan, you should see a _Successfully Transferred_ notification appear in the bottom right of your screen. Your balances under _My Balances_ should update to reflect your transfer between networks.

![](<../.gitbook/assets/image (66) (1) (1) (1) (1) (1) (1) (1).png>)

### 6. Delegate INJ Tokens to Validators

Open the Validators page by clicking **Validators** from the top menu bar. Select `Chorus One` from the Validators list. In the same row under _Actions_, click **Delegate**.

![](<../.gitbook/assets/image (53) (1) (1) (1) (1) (1) (1).png>)

This will open up a modal where you can enter the amount of INJ to delegate to this validator. Enter the amount and click **Delegate**.

This will open Metamask with a transaction for you to sign. Sign the transaction and wait a few moments.

When the modal closes, return back to the Wallet page to confirm that the _Delegations_ table reflects delegations you have made to validators.

![](<../.gitbook/assets/image (64) (1) (1) (1) (1) (1) (1).png>)

Congratulations! Your INJ is now staked!

### 7. Claiming Rewards

After you have delegated INJ to validators and waited some time, you will have accrued delegation rewards which can be claimed from the Wallet page. Under the _Delegation Rewards_ table, you are shown a _Total Reward (INJ)_ balance. Click **Claim** and sign the transaction.

![](<../.gitbook/assets/image (57) (1) (1) (1) (1) (1).png>)
