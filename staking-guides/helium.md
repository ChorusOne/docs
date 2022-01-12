---
description: >-
  Helium is a network with a native cryptocurrency (HNT) used to incentivise
  individuals around the world to provide coverage on a global peer-to-peer
  wireless network.
---

# Helium

## How to stake with Ledger

### Installing in Ledger Live

* Make sure the Helium app has been installed by going to `Ledger Live > Settings > Experimental Features > Enable Developer mode.`
* Once enabled, go to Manager and search "Helium".
* Click Install.

**You must make sure Ledger Live is closed before following the next steps!** The companion app cannot run when Ledger Live is blocking the USB device.

### Using CLI

1. To stake HNT with your Ledger device, you must use CLI
   1. Download the latest [Helium CLI release from their Github repo](https://github.com/helium/helium-ledger-cli/releases)
   2. You will have the option to download it for Mac, Linux or Windows
2. Once downloaded, unzip the file
3. Now, open terminal and navigate to the folder where you downloaded the helium-ledger-cli file
4. Ensure your ledger is connected to your computer, then type `./helium-ledger-cli`

At any time use `-h or --help` to get more help for a command

1. Check Balance and Receive HNT
   1. Type `./helium-ledger-cli balance` to see your new Ledger address and balance.
   2. Make sure you have a little more than 10,000 HNT in this address so you are able to stake
2. Stake your HNT with the validator address Chorus One has provided you - **make sure you replace the **_**'Chorus One validator address'**_** with the actual address found in the agreement**
   1. `helium-ledger-cli validators stake one 'Chorus One validator address' 10000 --commit`
   2. Sign this transaction by inputting your passphrase made when creating the wallet
3. It should take \~15 mins before your node is activated on Helium network
4. You can track the status of your validator using [https://api.helium.io/v1/validators/](https://api.helium.io/v1/validators/)\<validator\_address\_provided\_by\_Chorus\_One>
5. You should see JSON output that looks similar to this. You are looking for `"online": "online" and "stake_status": "staked"`
6. Congrats! If you are seeing the above output, your node is live and available to participate in consensus on Helium network.
7. You can track your node's rewards using [this tutorial](https://www.notion.so/Checking-Your-Helium-Validator-Rewards-23b4d4dd0658453d910f943f238c1153)

### Helium-wallet

1. Install [Helium CLI wallet](https://github.com/helium/helium-wallet-rs/releases/tag/v1.6.4)
2. After installing the CLI locally, create your wallet using the following command:
   1. `helium-wallet create basic`

At any time use `-h or --help` to get more help for a command

1. You'll be prompted to supply a new passphrase to complete it. This is used to encrypt/decrypt the wallet.key file, and is needed to sign transactions. Don't lose it.
2.  This command will produce a wallet.key file on your machine, along with output similar to the following:

    ```
    +--------------------------------------- ---+---------+--------+------------+
    | Address                                   | Sharded | Verify | PwHash     |
    +------------------------------------------+---------+--------+------------+
    | 1aP7nm6mGLMFtgiHQQxbPgKcBwnuQ6ehgTgTN8zj | false   | true   | Argon2id13 |
    +--------------------------------- --------+---------+--------+------------+
    ```
3. Make your you have just over 10000 HNT available to stake by running the following command to check your balance
   1. `helium-wallet balance`
4. Stake your HNT with the validator address Chorus One has provided you. **Make sure you change the 'validator address provided by Chorus One' with the actual validator address Chorus One has provided you in the agreement.**
   1. `helium-wallet validators stake one 'validator address provided by Chorus One' 10000 --commit`
   2. Sign this transaction by inputting your passphrase made when creating the wallet
5. It should take \~15 mins before your node is activated on Helium network
6. You can track the status of your validator using[https://api.helium.io/v1/validators/](https://api.helium.io/v1/validators/)\<validator\_address\_provided\_by\_Chorus\_One>
7. You should see JSON output that looks similar to this. You are looking for `"online": "online" and "stake_status": "staked"`
8. Congrats! If you are seeing the above output, your node is live and available to participate in consensus on Helium network.
9. You can track your node's rewards using [this tutorial](https://www.notion.so/Checking-Your-Helium-Validator-Rewards-23b4d4dd0658453d910f943f238c1153)
