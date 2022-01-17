---
description: How to stake on Celo using Celowallet
---

# Celo

## Overview

Celo is an open platform that makes financial tools accessible to anyone with a mobile phone. When you stake your CELO tokens with Chorus One you can earn rewards up to 13.2% per annum.

| Category                         | Details                                                                                         |
| -------------------------------- | ----------------------------------------------------------------------------------------------- |
| **Chorus One Validator Address** | 0x81cef0668e15639D0b101bdc3067699309D73BED                                                      |
| **APY**                          | 13.2 %                                                                                          |
| **Wallet**                       | [https://celowallet.app/](https://celowallet.app)                                               |
| **Block Explorer**               | [https://explorer.celo.org/](https://explorer.celo.org)                                         |
| **Staking Rewards**              | [https://www.stakingrewards.com/earn/celo/](https://www.stakingrewards.com/earn/band-protocol/) |
| **Unlocking Period**             | 3 Days                                                                                          |

The native Celo token (CELO) is used to pay for transactions and these can also be staked by token-holders to earn rewards, participate in governance, and vote for validators.

## How to stake Celo tokens

You have to perform 3 steps to be able to stake your CELO tokens with Chorus One

### 1. Locking your CELO tokens

First, you will need to lock your CELO with the following command.

{% hint style="danger" %}
Please note that CELO tokens require 3 days to unlock
{% endhint %}

```
celocli lockedgold:lock --from 0xYourAddress --value 10000000000000000000000
```

{% hint style="info" %}
Be sure to change **0xYourAddress** to the address that is holding your CELO**. 10000000000000000000000** is equivalent to 10,000 CELO.
{% endhint %}

We recommend using a Ledger hardware wallet for the CELO tokens. If you are using a Ledger, add `-useLedger` to the above command

```
celocli lockedgold:lock --from 0xYourAddress --value 10000000000000000000000 --useLedger
```

### 2. Wait and Activate

Once you have completed this transaction, wait **one day** and activate your votes by using the following command

```
celocli election:activate --from 0xYourAddress --wait
```

### 3. Vote for Chorus One

Complete your staking process by voting for Chorus One Validator

```
celocli election:vote –for=0x81cef0668e15639D0b101bdc3067699309D73BED –from=0xYourAddress –value=1000000000000000000000
```

{% hint style="info" %}
Be sure to change **0xYourAddress** to the address that is holding your CELO.

In this example, **10000000000000000000000** is being used to vote for Chorus One with 10,000 CELO.
{% endhint %}

## Detailed Guide

For a detailed guide please visit the official documentation for Celo network

{% embed url="https://docs.celo.org/celo-owner-guide/quick-start" %}
