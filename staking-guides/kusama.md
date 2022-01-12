---
description: How to stake Kusama with Polkadot JS and the Polkadot Browser Extension.
---

# Kusama

## Overview

| Category                         | Details                                                                                    |
| -------------------------------- | ------------------------------------------------------------------------------------------ |
| **Chorus One Validator Address** | JLKcPk652UTtQfyrk7keyU6vqAEj5JXzDAvQdPxB1DJTnZ3                                            |
| **Wallet**                       | PolkadotJS                                                                                 |
| **APR**                          | 14.85                                                                                      |
| **Block Explorer**               | https://kusama.subscan.io                                                                  |
| **Staking Rewards**              | [https://www.stakingrewards.com/earn/kusama/](https://www.stakingrewards.com/earn/kusama/) |

In this step-by-step guide, you will learn how to stake your KSMs, the native token of the Kusama blockchain, using Polkadot JS and the Polkadot Browser Extension. You will go through the following key steps:

1. Creating a Kusama Stash Account
2. Creating a Kusama Controller Account
3. Staking your KSM token
4. Managing your Kusama Staking Operations

### Before you get started <a href="#1cef" id="1cef"></a>

Since it is recommended by Polkadot / Kusama for most users to use the Polkadot.js Browser Extension to create their addresses, we are focusing on this method. In case you want to explore alternatives, have a look [here](https://wiki.polkadot.network/docs/en/learn-account-generation#polkadotjs-browser-plugin).

Make sure to install the Polkadot.js Browser Extension before you get started. You can download the extension for [Chrome/Brave](https://chrome.google.com/webstore/detail/polkadot%7Bjs%7D-extension/mopnmbcafieddcagagdcbnhejhlodfdd?hl=en) and [FireFox](https://addons.mozilla.org/en-US/firefox/addon/polkadot-js-extension/).

![](<../.gitbook/assets/image (70) (1) (1).png>)

### Step 1: Create a Kusama Account <a href="#1e2f" id="1e2f"></a>

Once you successfully installed the extension, click on the icon for Poladot extension - a `P` button in your browser bar to open the interface. You will be prompted to create an account if you don't have one already.

![](<../.gitbook/assets/image (61) (1) (1).png>)

Click the little _Gear Icon_ in the upper right corner and choose `Kusama Relay Chain` under `Display Address Format For`.&#x20;

Then, click on the `+` Icon followed by `Create new account`. Uncheck the box next to “Derive new account from existing” & click “Create an account from new seed”.

![](<../.gitbook/assets/image (49) (1).png>)![](<../.gitbook/assets/image (60) (1) (1).png>)![](<../.gitbook/assets/image (65) (1) (1).png>)![](<../.gitbook/assets/image (75) (1).png>)

Write down your mnemonic seed phrase and **securely store it**. Whoever has access to the mnemonic seed also has access to your funds! Check the box on the bottom and click “Next step”. Choose a descriptive name for your Stash account as well as a strong password. Then click “Add the account with the generated seed”.

{% hint style="danger" %}
Never share your Mnemonic Seed Phrase!
{% endhint %}

**Congratulations, you have successfully created your Kusama account.** You will now also find the address on the [Polkadot JS Website](https://polkadot.js.org/apps/#/accounts) under “Accounts” — reload the page, if this is not the case. You can now fund this account.

![](<../.gitbook/assets/image (54) (1).png>)

### Step 2: Create a Kusama Controller Account <a href="#c2b1" id="c2b1"></a>

In order to successfully bond your funds and nominate your validator set, you need a separate account, namely your `Controller Account`. You will perform everyday staking operations like changing validators or claiming rewards using this account.

To create your `Controller Account`, use the Polkadot browser extension. Click the plus icon in the top right corner. Then click `Create new account`.

Now you have two options:

1. Derive the new account from your existing account: it will be accessible with the same seed (mnemonic phrase) of the account it was derived from
2. Or, Create a new account with a new seed: the new account will be independent of the old one and have a separate seed (mnemonic phrase)

The second option is preferable because this lets you have independent keys. So, click `Create  new account`.

![](<../.gitbook/assets/image (73) (1).png>)![](<../.gitbook/assets/image (56) (1).png>)

Write down your mnemonic seed phrase and **securely store it**. Whoever has access to the mnemonic seed also has access to your funds! Check the box on the bottom and click `Next step`. In the next window, choose a descriptive name for your Controller account as well as a strong password. Then click `Add the account with the generated seed`.

**Congratulations, you have successfully created your Kusama Controller account**. You will now also find the address in Polkadot JS under `Accounts` — reload the page if this is not the case.

![](<../.gitbook/assets/Screenshot 2022-01-12 at 8.29.34 PM.png>)

### **Step 3: Stake your KSM token** <a href="#ead8" id="ead8"></a>

On the [Polkadot JS website](https://polkadot.js.org/apps/#/explorer), make sure that you are connected to the Kusama mainnet. You can change the network by clicking the network symbol in the top left corner of your screen.

![](https://miro.medium.com/max/1400/1\*SzMXa91i1S5K\_CK9QDNMyA.png)

Polkadot JS supports several networks, make sure to choose “Kusama” before you continue

Before starting the Nomination process, send some funds from your Stash to your Controller account in order to cover transactions fees (1 or 2 KSM should be plenty).

To start the staking process, click “Staking” in the “Network” drop-down menu.&#x20;

![](<../.gitbook/assets/Screenshot 2022-01-12 at 8.37.45 PM.png>)

Afterward, visit the “Account actions” tab and click the “+ Validator” — button.

![](https://miro.medium.com/max/1400/1\*VdCI\_Q6ZQcQrsV5zltdcQA.png)

You can perform all staking operations under the `Account actions` tab in the `Staking` menu

Choose the Stash & Controller accounts accordingly, choose the amount of KSMs you want to use for staking under `value bonded`. Make sure to leave some funds in your Stash account. **Bond a max. of 95% of your tokens so that you are still able to pay for transaction fees.**

Choose a destination account for your rewards under `payment destination`.

Then click `next` to bond your token.

![](https://miro.medium.com/max/1400/1\*B-4sd8gbUoMLaX1cf5UIAQ.png)

{% hint style="warning" %}
Make sure to leave some KSM unbonded, so that you can pay for the transaction fees
{% endhint %}

You can nominate up to 16 validators. Simply select the validators of your choice by clicking on them in the left box. You can unselect them from the right box by clicking on them again. Alternatively, you can also use the search bar at the top to look for specific validators by name or address.

Our Validator Addresses:

> 4gF1YM8TioXtEPheVfA2XwqS4iMcwHXBXquwULxPbuvMv2Si
>
> JLKcPk652UTtQfyrk7keyU6vqAEj5JXzDAvQdPxB1DJTnZ3
>
> HRMhY2CtVMp2yVSieKvq8Y8FHAhRKrGGMd6MoQe3iN6uJ2D
>
> Faaf2qgwtaFum78U8TdEPnUd4u7HPk65cdaFj7KbEA6wi2Y
>
> EyibGsAttxpNBkgjMxNTArskxkdEFFbwghYuuaZyvu9rmo2

![](<../.gitbook/assets/image (67).png>)

Then click `Bond & Nominate`.

Please note that you cannot specify the amount delegated to a particular validator. Your bonded DOTs will be spread out among the validators you selected according to the NPoS algorithm.

![](<../.gitbook/assets/image (59) (1).png>)

Choose your validators wisely — we recommend doing some research about them before your nomination

In the following window, click `Sign & Submit`. Afterward, enter your password and click “Sign the transaction” to conclude your nomination.

![](https://miro.medium.com/max/1400/1\*myRd-LyNGy1NDeSvG1I7GQ.png)

Almost done! The only thing left is signing the transaction!

> Congratulations, you are now a Nominator on the Kusama network!

Your nominations will be effective in the next era (\~ in up to 6 hours).

### Step 4: Manage your Kusama Staking Operations <a href="#e734" id="e734"></a>

You can manage your staking operations with Polkadot JS. In the `Staking` menu, click `Account Actions` and then click the three dots on the very right to perform the following operations:

* Bond more funds
* Unbond
* Change controller account
* Change reward destination
* Set nominees

![](https://miro.medium.com/max/1400/1\*etNnnqzR2qMByWADTjf7Mw.png)

{% hint style="info" %}
Please note that if you have bonded your tokens, a period of **7 days** needs to pass before you can unbond. Once your tokens are unbonded, you need to issue another transaction, namely `Withdraw Unbonded` in order to be able to transfer your funds.
{% endhint %}

{% hint style="info" %}
### Understanding Active Nominations <a href="#b82e" id="b82e"></a>

`Active nominations` & `Inactive nominations` are the validators of your nominations that are currently in the active validator set. In general, your only one validator will be shown as `active`. That is because the algorithm used to distribute your stake is optimized so that each validator in the set roughly has the same amount of stake backing him/her. Your stake is therefore usually only backing one of the validators you nominated.

`Waiting nominations` are the validators that are currently not in the active set.
{% endhint %}





