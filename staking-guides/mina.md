---
description: How to stake Minawith Clorio wallet
---

# Mina

## Overview

| Category                         | Details                                                                                |
| -------------------------------- | -------------------------------------------------------------------------------------- |
| **Chorus One Validator Address** | B62qmFf6UZn2sg3j8bYLGmMinzS2FHX6hDM71nFxAfMhvh4hnGBtkBD                                |
| **Wallet**                       | Clorio                                                                                 |
| **APR**                          | 11.59%                                                                                 |
| **Block Explorer**               | [https://mina.staketab.com/](https://mina.staketab.com)                                |
| **Staking Rewards**              | [https://www.stakingrewards.com/earn/mina/](https://www.stakingrewards.com/earn/mina/) |

## How to stake <a href="#db34" id="db34"></a>

### 1. Create Account and Login

First of all, you have to log into your wallet.

Head to the [Clorio web app](https://mainnet.clor.io) or open the Clorio Desktop App and select **Access with Ledger** or **Access with Private key**.

![](<../.gitbook/assets/image (53) (1) (1) (1).png>)

In case you do not have an account click on `Create a wallet` and note down the passphrase and private key in a secure place.

{% hint style="warning" %}
Do not share your passphrase or private key with anyone. Doing so may cause loss of funds!
{% endhint %}

![](<../.gitbook/assets/image (60) (1) (1) (1) (1).png>)

If you already have a wallet, insert your Private key to log in to your wallet. Once the Private key is inserted, the button **Access the wallet** will be enabled, allowing you to enter inside your wallet.

![](<../.gitbook/assets/image (65) (1) (1) (1) (1) (1) (1).png>)

### 2. Delegate to Chorus One

On the left-side-menu click on **Staking Hub** item.

![](<../.gitbook/assets/image (76) (1) (1) (1).png>)

You will be brought to a new page, here you will have the staking status and the list of Validators.

To start delegating, you can scroll to **Chorus One** and click on the `Delegate` button, or you can manually delegate by clicking on the `Custom delegation` button.

After you click the `Delegate` button, a confirmation screen will show up.

![](<../.gitbook/assets/image (63) (1) (1) (1) (1).png>)

Once you click on `Confirm` button you will be asked to insert a fee. The field will be pre-compiled with the Average fee, but you can choose the one that you want.

![](<../.gitbook/assets/image (57) (1) (1) (1).png>)

After you click on `Proceed` button, you will be asked to put your Private key in order to proceed with the delegation.

![](<../.gitbook/assets/image (71) (1) (1).png>)



If the Private key is valid the modal will disappear, then will pop out an alert on the bottom right side of the screen confirming that your transaction has been successfully broadcasted to the network.

### 3. Using Ledger to delegate

If you are using a Ledger, Clorio will send all the information of the delegation to your Ledger in order to sign them on the device.

{% hint style="info" %}
For instructions on how to install Ledger App for Mina visit [here](https://docs.minaprotocol.com/en/advanced/ledger-app-mina)
{% endhint %}

Please be sure that your Ledger is connected, Ledger Mina app is open and your device is unlocked and your [browser meets the minimum requirements](broken-reference).

If there are no issues with the delegation data, Clorio will wait for the Ledger signature and then broadcast the transaction to the network.

![](<../.gitbook/assets/image (77) (1) (1) (1) (1).png>)

### 4. Delegation done

After entering your private key or signing with Ledger you will see the message `Delegator successfully broadcasted`. This means that delegation was successfully done!

![](<../.gitbook/assets/image (66) (1) (1) (1).png>)

Congratulations you are now staking Mina!!

### **5. (Optional) MINA **_**Staking with Command-Line Interface (CLI)**_

If you are technically savvy and have a hardware wallet, we’ve included how to delegate to Mina using CLI.  First, if you haven’t already, you’ll need to [generate a keypair](https://minaprotocol.com/docs/keypair) and [connect to the network](https://minaprotocol.com/docs/connecting).&#x20;

**Second, make sure you’ve unlocked your account and enter the following in the terminal:**

```
mina account unlock -public-key $MINA_PUBLIC_KEY
```

**Then run this command to delegate your stake:**

```
mina client delegate-stake \
-receiver <DELEGATE-PUBLIC-KEY> \
-sender $MINA_PUBLIC_KEY \
-fee 0.1
```

* The receiver is the public key of the validators to receive your stake delegation.&#x20;
* The sender is the public key of the account from which you want to delegate
* The fee is the transaction fee required to record your transaction.

**Chorus One's Public Key**: `B62qmFf6UZn2sg3j8bYLGmMinzS2FHX6hDM71nFxAfMhvh4hnGBtkBD`

{% hint style="info" %}
There is a 2-4 week delay (also known as a latency period) before your new stake delegation comes into effect.
{% endhint %}
