---
title: FAQ - wPOKT Bridging
menuTitle: Bridging FAQ
weight: 20
aliases:
  - /home/pokt
  - /home/pokt/wpokt
  - /pokt/wpokt
  - /pokt/wrapped
  - /pokt/bridging
description: Guidance for bridging your POKT to Ethereum & back.  
---

### How can I swap my POKT for wPOKT?

Before getting started, note that the end-to-end wrapping process is expected to take ~30 mins, and that minting wPOKT will cost gas (in ETH).

- Prepare to wrap your POKT by connecting Ledger or SendWallet to the bridge. If you don’t have a Ledger wallet yet, see [here](https://support.ledger.com/hc/en-us/articles/12976051037853-Pocket-POKT-?docs=true) for the docs. And if you want to use SendWallet yet, you can download it [here](https://www.sendwallet.net/).
- Prepare to mint your wPOKT by connecting your Ethereum wallet. Make sure your Ethereum wallet has some ETH for gas fees. If you don’t have enough gas, the bridge app will tell you.
- You will not be able to initiate the wrap transaction until you have connected both wallets.

 {{% notice style="note" %}}
You will be required to sign 2 transactions, first to deposit your POKT and then to mint your wPOKT. We recommend you keep the modal open and stay in the app until both transactions have been confirmed. If you leave the app before both transactions complete, it will remain pending until you return and finish them. 

If you're wondering why wPOKT isn't in your wallet after 30 minutes, double check you've completed both transactions.
{{% /notice %}}   
 
- Specify the amount of POKT tokens to wrap into wPOKT tokens, then click Wrap.
- After ~30 minutes, if you've completed all the steps, you will receive your wPOKT.

### What wallets are approved for wrapping POKT?

### Why haven’t I received my wPOKT yet?

- **Are you looking in the right place?** First check that you’re looking at the correct blockchain. wPOKT lives on the Ethereum blockchain, so you will not see wPOKT in your Ethereum wallet unless you are connected to the Ethereum RPC. You can easily connect your wallet to the Ethereum RPC via Pocket Network using this [site](https://rpclist.info/). To cross-check, you can also search your ETH wallet address on [Etherescan](https://etherscan.io/) to see if the wPOKT balance appears there.
- **Have you waited long enough?** An end-to-end wrapping of POKT is expected to take approximately 30 minutes. In some cases, it may take up to an hour.

If you have confirmed you’re looking in the right place and you have waited a little longer, but you still do not see your tokens, please contact us for support on our [discord](https://discord.gg/pokt).

### How can I unwrap my wPOKT back to POKT?

Before getting started, note that the end-to-end unwrapping process is expected to take ~30 mins.

- Prepare to burn your wPOKT by connecting your Ethereum wallet to the bridge. Make sure your Ethereum wallet has some ETH for gas fees. If you don’t have enough gas, the bridge app will tell you.
- Prepare to unwrap your POKT by connecting your SendWallet.
- You will not be able to initiate the unwrap transaction until you have connected both wallets.
- Specify the amount of wPOKT tokens to unwrap into POKT tokens, then click Unwrap.
- After X minutes, you should receive your POKT.

### Why haven’t I received my POKT yet?

- **Are you looking in the right place?** Make sure you are checking your POKT wallet for the balance, not your Ethereum wallet.
- **Have you waited long enough?** An end-to-end unwrap of POKT is expected to take approximately 30 minutes. If it has not been 30 minutes or it has only recently turned 30 mins, please try waiting a little longer.

If you have confirmed you’re looking in the right place and you have waited a little longer, but you still do not see your tokens, please contact us for support on our discord: 
discord.gg/pokt

### Why does the bridge take ~30 mins?

- **Pocket Network block times.** Pocket Network blocks complete every 15 minutes. Depending on when you sign the transaction, it may take up to 15 minutes for your transaction to appear on-chain.
- **Bridge validation time.** The wPOKT bridge verifies your request between chains. It takes a few minutes to reach consensus and start a transaction on-chain.
- **Ethereum block times.** Ethereum blocks complete every 12 seconds. For large balances, it is common to wait for up to 32 blocks before proceeding with a transaction.