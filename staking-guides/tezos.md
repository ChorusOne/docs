---
description: How to bake your XTZ with
---

# Tezos

## Overview



| **Category**                     | **Details**                                                                                                   |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Chorus One Validator Address** | bandvaloper15urq2dtp9qce4fyc85m6upwm9xul3049fz627w                                                            |
| **APY**                          | 11.2 %                                                                                                        |
| **Wallet**                       | Keplr                                                                                                         |
| **Block Explorer**               | [https://cosmoscan.io/](https://cosmoscan.io) \| [https://www.mintscan.io/band](https://www.mintscan.io/band) |
| **Staking Rewards**              | [https://www.stakingrewards.com/earn/band-protocol/](https://www.stakingrewards.com/earn/band-protocol/)      |
| **Unstaking Period**             | 21 Days                                                                                                       |

## How to stake using Atomex Wallet

It’s quite simple to delegate purchased Tezos coins (XTZ). The main steps  for delegating Tezos remain the same for most wallets

1. Open the wallet.
2. Choose a baker from the list.
3. Press “Delegate”.

Let us see an example of each of these steps using Atomex wallet

### 1. Create/log in to your account

Go to [https://wallet.atomex.me/](https://wallet.atomex.me). Select `My Wallets` in case you already have an account otherwise click on `CREATE NEW WALLET`&#x20;

![](<../.gitbook/assets/image (84).png>)

If you are creating a new wallet then follow the onscreen instructions.

1. Select the wallet type (Mainnet)
2. Enter the wallet name of your choice
3. Enter the word length (24 is preferable)
4. Enter a derived key password
5. Enter a storage password

There you go! You have your Tezos wallet.

![Your tezos wallet](<../.gitbook/assets/image (102).png>)

### 2. Select a bakery

Press `Wallets`, select **`Tezos`** and press `Delegate`.&#x20;

1. Search for Chorus One in that list,&#x20;
2. Set the amount you want to delegate
3. Verify the **To** and **From** addresses,&#x20;
4. Select the default fee option and&#x20;
5. Click `Delegate`

![](<../.gitbook/assets/image (115).png>)

Upon the successful completion of your transaction, you will see the success message as below

![](<../.gitbook/assets/image (90).png>)

Congratulations now you are baking your XTZ!!

After you click “Delegate”, the corresponding operation is sent to the blockchain and your delegation status becomes “Pending”. You can check that everything went well in [Tezos explorer](https://tzkt.io).

![Delegation Pending](https://baking-bad.org/img/delegation\_pending.png)





## Understanding delegation status <a href="#delegation-status-3a-pending-3e-confirmed-3e-active" id="delegation-status-3a-pending-3e-confirmed-3e-active"></a>

As you can see, your delegation is not applied immediately right after delegating. You need to wait a while before it’s confirmed. There are three stages of delegation:

### **1. Pending**

{% hint style="info" %}
This stage lasts 2 cycles = \~ 6 Days
{% endhint %}

> 1 cycle = 8192 blocks = 4096 minutes (each block every \~30 seconds) = \~2.8 days

In this stage you’ve successfully delegated, but your rights are not transferred to the baker yet. This delay is required to prevent the network from some forms of abuse. See [more details](https://tezos.gitlab.io/whitedoc/proof\_of\_stake.html#roll-snapshots) in the Tezos documentation.

### **2. Confirmed**

{% hint style="info" %}
**This stage lasts 5 cycles = \~ 14 Days**
{% endhint %}

Your delegation is confirmed and the baker received future baking rights (to produce and endorse future blocks). So, now you know that you will definitely participate in Tezos staking in the near future and therefore you can estimate future staking rewards.

![Future Rewards](https://baking-bad.org/img/future\_rewards.png)

### **3. Active.**

Now you are completely in Tezos staking and earning rewards. As you can see, you have to wait **\~20 days** after delegating to start staking.&#x20;

### Receiving Tezos staking reward payments <a href="#receiving-tezos-staking-reward-payments" id="receiving-tezos-staking-reward-payments"></a>

All Tezos staking rewards are credited to the baker and not to delegators directly. Moreover, every time baker receives rewards, those rewards are frozen for the next 5 cycles (\~14 days), so the baker can’t spend them. Only after \~14 days rewards are unfrozen and the baker can transfer it to someone else.

That’s why you can see that Tezos staking rewards for cycle `N` usually comes in cycle `N + 6` (after \~17 days):

![Payout Delay](https://baking-bad.org/img/reward\_lag.png)

### What happens if you add or withdraw funds? <a href="#what-happens-if-you-add-or-withdraw-funds-3f" id="what-happens-if-you-add-or-withdraw-funds-3f"></a>

Every time the balance of a delegated account is changed (e.g. you raise additional funds, or withdraw funds, or even receive reward payments) you have to wait the same time as described above (37 or 23 days) until these changes are applied.

\
