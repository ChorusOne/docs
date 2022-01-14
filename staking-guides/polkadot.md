---
description: How to stake your DOTs with PolkadotJS UI
---

# Polkadot

## Overview

| Category                         | Details                                                                                                              |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| **Chorus One Validator Address** | 121GBc2ZK53Uoc6JovJjU7zARH8fys5efyUfHKT9vABpqajx                                                                     |
| **Wallet**                       | Polkadot JS                                                                                                          |
| **APR**                          | 13%                                                                                                                  |
| **Block Explorer**               | [https://polkadot.subscan.io/](https://polkadot.subscan.io/account/12C9U6zSSoZ6pgwR2ksFyBLgQH6v7dkqqPCRyHceoP8MJRo2) |
| **Staking Rewards**              | [stakingrewards.com/earn/polkadot/](https://www.stakingrewards.com/earn/polkadot/)                                   |

## How to stake using Polkadot UI

You can nominate validators (also known as **staking**) on Polkadot-JS UI using the following steps

### 1. Create an account

[Create a Polkadot account](https://wiki.polkadot.network/docs/en/learn-account-generation) if you don’t have one already. Get the browser extension by visiting Polkadot.js.org/extension&#x20;

![](<../.gitbook/assets/image (115) (1) (1).png>)

Click on the extension card and add it to your browser.

![](<../.gitbook/assets/image (84) (1).png>)

After adding to your browser it will appear as a **P** icon in the toolbar

![](<../.gitbook/assets/image (118) (1).png>)

{% hint style="info" %}
Please note **it is recommended to create two accounts:** one to use as the controller account and one to use as your stash account. Learn more about this [here](https://wiki.polkadot.network/docs/en/learn-staking/#accounts)
{% endhint %}

![](<../.gitbook/assets/image (73) (1).png>)

If you want to know more details about how to create an account you can visit the official docs [here](https://wiki.polkadot.network/docs/learn-account-generation).\
Also, _**make sure you leave a small amount of DOT transferrable in your stash account and that your controller has more than 1 DOT in it**_. This is in order to have enough liquid funds for paying transaction fees when bonding and unbonding funds.\
\


![](<../.gitbook/assets/image (98) (1) (1) (1) (1).png>)

![](<../.gitbook/assets/image (49) (1).png>)

![](<../.gitbook/assets/image (116) (1).png>)

### 2. Bonding the DOTs

In this step, we will actually go through the process of staking which is comprised of bonding the tokens and nominating the validators.

![](<../.gitbook/assets/image (59).png>)

{% hint style="danger" %}
* _**Nominating currently requires a minimum of 120 DOT staked funds on Polkadot (0.1 KSM on Kusama)**_. Please make sure you are above that minimum, otherwise you won't be able to nominate with your staked funds.&#x20;
* _**There is also a maximum of 22,500 nominators**_ in place at the moment. That means, if there are already 22,500 nominators, you will not be able to nominate, even if you have more than the minimum of 120 DOT staked. You can double-check the current number of nominators on the [Staking Overview](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frpc.pinknode.io%2Fpolkadot%2Fexplorer#/staking) page. &#x20;
{% endhint %}

![](<../.gitbook/assets/image (114) (1).png>)

Go to the [Polkadot-JS UI main page](https://polkadot.js.org/apps/#/explorer). Click the Staking link under the [Network tab at the top](https://polkadot.js.org/apps/#/staking). Click “Account actions” (on top). It may take a while to load. **If you're using a Ledger, skip the following steps and check the section below.**

![](<../.gitbook/assets/image (66).png>)

**You need to bond funds to nominate a validator.** So go ahead and click  the `+ Nominator button`(top right).

![](<../.gitbook/assets/image (76).png>)

Choose your Stash and Controller accounts. It is more **secure** to choose separate stash and controller accounts. So make sure you create a separate controller account first in the same manner as you created your stash account. Again, make sure you have funds in your controller account.

![](<../.gitbook/assets/image (108) (1) (1) (1).png>)

&#x20;Then select the amount you want to bond and the rewards destination and click "Next"

### 3. Select validator and nominate

In the next screen select Chorus One as the validator. Finally, click `Bond and Nominate`.

![](<../.gitbook/assets/image (50) (1).png>)

Enter the password for your account and click `Sign & submit`.

![](<../.gitbook/assets/image (92) (1).png>)

Sign the transaction using your stash account

![](<../.gitbook/assets/image (88) (1).png>)

Additionally, if you need to change the nominated validators or unbond your balance you just need the controller account to perform the transaction.

{% hint style="info" %}


**Before you begin staking, please pay close attention to these important points:**&#x20;

* **Do not bond ALL your funds**. Leave a small amount _transferable_ in your account, so that you can pay transaction fees from that (changing validators, bonding more or unbonding your tokens are all transactions that will cost a small fee).
* **Any changes you make will take affect in the next era (which lasts 24 hours on Polkadot),** provided you made the changes at least 4 hours before the era ended (whether it's setting up staking for the first time, or changing your validators, bonding more funds, etc), and rewards are distributed after an era ends. So, when you first stake, your rewards will begin to come at the soonest after 1 day and 4 hours, and at the latest after 2 days.
{% endhint %}

## How to stake using Ledger

### 1. Create a Polkadot account on Ledger Live

&#x20;Make sure both the ledger live app and device are up to date

![](<../.gitbook/assets/image (105).png>)

Go to manager in the left panel and install Polkadot app if you haven't already

![](<../.gitbook/assets/image (53).png>)

Add your account by going to the Accounts tab in the left panel and clicking on the `Add Account`

![](<../.gitbook/assets/image (85) (1).png>)

Choose Polkadot in the popup that appears upon clicking **Add Account**

![](<../.gitbook/assets/image (64) (1).png>)

Follow the instructions to create the new account

![](<../.gitbook/assets/image (56) (1).png>)

### 2. Send/Receive DOTs

Once you have an account you can buy DOTs directly from the Ledger Live app.

![](<../.gitbook/assets/image (117) (1).png>)

In case you are unable to buy DOTs directly from Ledger Live you may use an exchange to do so.

### 3. Stake/Unstake DOTs

To stake go to the **Accounts** tab in the left panel and click on the account for which you want to perform the staking operation

![](<../.gitbook/assets/image (71).png>)

Once you have your account opened click on `Manage` on the top-right and under it select `Earn Rewards`

![](<../.gitbook/assets/image (110) (1).png>)

Then enter the amount of DOTs you want to bond

![](<../.gitbook/assets/image (111).png>)

To compound your rewards you can select the `Bonded Balance` tab instead of the `Available Balance` tab. Click `Continue` and confirm the bonding transaction on your device. Finally **Nominate** a validator in the next step

![](<../.gitbook/assets/image (99) (1) (1).png>)

Polkadot allows Nominated proof of staking where you are allowed to nominate up to 16 validators. By clicking on the `Nominate` byou will be able to select the validator. Search for **Chorus One** and click `Continue.`

![](<../.gitbook/assets/image (78).png>)

Congratulations!! You are now staking your Polkadot! You may see your rewards in the portfolio section

![](<../.gitbook/assets/image (60) (1).png>)

You can also see the video tutorial on the official Polkadot youtube channel

{% embed url="https://www.youtube.com/watch?v=jL-N_IWiYVA" %}
