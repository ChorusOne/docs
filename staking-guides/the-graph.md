---
description: Hot stake GRT with Chorus One Indexer
---

# The Graph

## Overview

| **Category**                     | **Details**                                                                          |
| -------------------------------- | ------------------------------------------------------------------------------------ |
| **Chorus One Validator Address** | chorusone.eth                                                                        |
| **Wallet**                       | Metamask                                                                             |
| **APR**                          | 7.6%                                                                                 |
| **Block Explorer**               | [https://thegraph.com/explorer/#/](https://thegraph.com/explorer/#/)                 |
| **Staking Rewards**              | [stakingrewards.com/earn/the-graph/](https://www.stakingrewards.com/earn/the-graph/) |
| **Unbonding Period**             | 28 Days                                                                              |

To perform the following steps we will need the Network Beta dApp and Metamask. We will cover the following steps to delegate GRT

> Step 1: Setup your GRT delegation operations
>
> Step 2: Delegate your GRT via the Network Beta dApp
>
> Step 3: Manage your GRT staking operations

{% hint style="info" %}
Before you get started, please **make sure to have the latest version of the** [**Metamask Browser Extension**](https://metamask.io/download.html) **installed and to have enough ETH in your wallet to cover transaction fees**. Furthermore, ensure that Metamask is connected to “Ethereum Mainnet”.
{% endhint %}

{% hint style="info" %}
Using the Network Beta dApp with Metamask allows you to use a hardware wallet such as a Ledger Nano device for your delegation operations and is highly encouraged as it adds another layer of security. In case you want to use a hardware device for your delegation operations, connect Metamask to your device via the Metamask Browser Extension. **Make sure to have the ETH app open on your Ledger device and to have ‘Contract Data’ allowed within the ETH app on your device.**
{% endhint %}

![In case you want to use a Ledger device, connect it to Metamask before getting started](https://miro.medium.com/max/1400/1\*2d6rj7mW8BwtCDm0t49wMg.png)

### 1. Create/log in to your account <a href="#db34" id="db34"></a>

If you do not have an ERC-20 address yet, create one using the Metamask wallet.

![Get the metamask extension](<../.gitbook/assets/image (70) (1).png>)

Add the extension to your browser

![](<../.gitbook/assets/image (120).png>)

Create a new account.

![Create a new account](<../.gitbook/assets/image (77).png>)

Follow on-screen instructions to create the account.

![](<../.gitbook/assets/image (75).png>)

### 2. Setup your GRT delegation operations <a href="#db34" id="db34"></a>

To have Metamask display your GRT token, you need to add GRT to the list of displayed tokens. Open Metamask, Look for `GRT` in the Metamask search bar and directly add it without going through the custom token tab.

> Alternatively,  switch to the `Custom Token` tab. Input the following information, click `Next` and then `Add Tokens`.\
> \- Token Contract Address: 0xc944e90c64b2c07662a292be6244bdf05cda44a7\
> \- Token Symbol: GRT\
> \- Decimals of Precision: 18

![How to add GRT to Metamask](https://miro.medium.com/max/1400/1\*MnuO1b3seAg9S2TuwYVfOg.png)

In case you already own GRT with this address, you will now see your tokens displayed within Metamask. Otherwise, you need to fund this address properly before you can continue. Simply copy your address and withdraw/send funds to it. Once you successfully funded your account, you can find your token balance under `Assets` on Metamask.

{% hint style="warning" %}
Again, make sure to have enough ETH in your wallet to cover transaction fees.
{% endhint %}

![Properly fund your account and make sure to have enough ETH to cover transaction fees](https://miro.medium.com/max/1400/1\*jp\_-C12B48iPWTmmPtmC2w.png)

### 3. Delegate your GRT via the Network Beta dApp <a href="#ff01" id="ff01"></a>

Now it’s time to delegate! Head over to [https://network.thegraph.com/](https://network.thegraph.com). This is the Network Beta dApp and the Graph's main Staking UI.

Click `Connect Wallet` and `Metamask` in the pop-up. Now choose the address you want to be using in the Metamask Notification window, click `Next,` and then `Connect`.

![How to connect Metamask to the Network Beta dApp](https://miro.medium.com/max/1400/1\*s6sZSIHO8GW2SZqeDTojJQ.png)

You will now find your account displayed in the upper right corner of the Network Beta dApp. You can click it to see your GRT balance as well as to disconnect or switch accounts.

![You can find more information about your account in the upper right corner of the UI](https://miro.medium.com/max/1400/1\*C69BFcdzolRs\_t1cOOcwAg.png)

If you scroll down in the Network Beta dApp, you can find a list of all the available Indexers as well as some parameters relevant for your staking operations.

> You can find us as: **chorusone.eth**
>
> Our full Indexer address: 0xe63e935fba572784d5aa40715e372e7948bbdb12

The `Fee Cut %` shows the percentage of query fee rebates that an Indexer keeps for him/herself, whereas the “Reward Cut %” indicates the percentage of indexer rewards that an indexer keeps for him/herself.

To start the delegation process, click on the delegation icon on the very right of the indexer that you would like to delegate to. Then click “Delegate”.

![](<../.gitbook/assets/image (93).png>)

In the overlay menu that appears, you can choose the amount of GRT you want to delegate to the respective validator. Please note that delegating incurs a fee of 0.5% on the amount you are delegating.

Click `Submit Transaction` to continue. Then click `Confirm` in the Metamask Notification window to allow the dApp to spend your GRT. Afterward, click `Confirm` to transmit your delegation transaction.

{% hint style="info" %}
_Parameters Cooldown_ refers to the amount of time that needs to pass before an Indexer can change its’ query fee or its’ indexing reward cut.
{% endhint %}

In case you are using a Ledger, you need to approve and sign the transactions on your device as well.&#x20;

{% hint style="danger" %}
This might take a while. **Do not** reload the page.
{% endhint %}

![Finalize the delegation process by confirming the transactions](<../.gitbook/assets/image (94) (1).png>)

> And that’s it, you are now a delegator on The Graph network and help to secure the query and indexing layer of web3! Welcome aboard and thank you for delegating to our Indexer.

{% hint style="info" %}
Please note that the network is bootstrapped and subgraphs will transition from the hosted service to mainnet in the course of the next few weeks. Hence, the amount of query fees one can earn is limited at the moment.
{% endhint %}

## Step 3: Manage your GRT delegation operations <a href="#52e7" id="52e7"></a>

You can manage your delegation operations via the Network Beta dApp.

Click on your address in the upper right corner of the Network Beta dApp to find an overview of the Indexers you are delegating to. Within this menu, you can choose to undelegate or delegate more GRT to the respective delegator. Alternatively, you can also do this within the Indexer overview that you find on the main page of the Network Beta dApp.

Please note that when you unbond your GRT, they remain locked and illiquid for a period of 28 days. There is no delegator slashing implemented in The Graph and you can choose to delegate any amount of GRT.

![How to manage your GRT staking operations
](https://miro.medium.com/max/1400/1\*JkwqVnrjPKt3Rj5AlsviHg.png)
