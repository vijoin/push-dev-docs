---
description: >-
  A simple walkthrough guide to setup a Channel on Push protocol for sending
  Notifications to your Web3 subscribers
---

# Creating A Channel



Creating a channel is the very first step for sending notifications via Push. Having a Channel on Push dApp (_and Smart Contracts_) allows you to establish a communication pathway with your users in Web3.0

While there are quite a few [protocol level details about channels](../../developer-tooling/push-smart-contracts/epns-core-contract/channel-creation-process-on-smart-contract.md), let us first begin with understanding the overall Channel creation process.

Using the Push dapp or smart contracts, anyone with a wallet address on the Ethereum network can create their own channel. It can be deployed on:

1. The Ethereum Mainnet ([via Prod dApp](http://app.push.org/)), or
2. Goerli Test Network ([via Staging dApp](https://staging.push.org/))

The Prod dApp is mainly useful for fully functional dapps & smart contracts that are live on Blockchain networks. Creating your channel on Prod requires 50 PUSH, and it's recommended if you have a good user base or active community who wants notifications.

The Staging dapp is very useful for Builders/Developers to test out channels, send dummy notifications, and understand the functionalities of the Push Protocol. In the upcoming sections, we will set up a channel on Staging App.

## Requirements for Setting Up a Channel

Ideally, there are six crucial requirements for creating a Channel. Make sure you are ready with the below list (required for both Prod and Staging)👇🏼

1. **A Channel Name**
2. **Channel Logo (**_an image of size 128px \* 128px_**)**
3. **An amount of 50 $PUSH tokens in your Wallet (**and some ETH :innocent:**)**
4. **A brief Channel Description (**250 Characters**)**
5. **Channel CTA** (Call To Action link).
6. **Network & Alias Address**

**Quick Important Note on Network & Alias Address**

* The **Network** dropdown allows you to select the network/chain on which you want to send notifications. It is set to **Ethereum chain** by default but allows you to select other chains as well. (_Currently Polygon & BSC_).
* The **Alias Address** field appears only when you select any chain other than Ethereum for your channel's notification. Alias address is basically the representation of your original Ethereum channel on the selected chain of your choice.
* The alias address basically allows you to provide an address that will represent your channel on the other chain selected in the **Network** dropdown section. It is imperative to note that the address you pass as an alias, must be your own as it will be further verified as a part of the channel creation process. Read more about Alias Addresses👇.

{% content-ref url="../../concepts/create-your-notif-channel/what-is-a-channel-alias.md" %}
[what-is-a-channel-alias.md](../../concepts/create-your-notif-channel/what-is-a-channel-alias.md)
{% endcontent-ref %}

{% hint style="info" %}
**Note:** You can pass the same Ethereum (EVM-compatible) address, being used for channel creation, as an alias address for other EVM-compatible chains as well.

The Alias address is quite crucial to activate your channel on other chains. Read more about it in [enabling-channel-on-other-chains](enabling-channel-on-other-chains/ "mention") page.
{% endhint %}

## How to setup your channel

1. Ensure that you have the above requirements ready.
2. Head to the Push [Prod dapp ](https://app.push.org/#/channels)or [Staging dapp](https://staging.push.org/#/channels) based on your channel creation requirement. **Note:** Channel creation is a protocol-based event which means you can also create the channel by interacting with [EPNS Core Smart Contract](../../developer-tooling/push-smart-contracts/epns-core-contract/channel-creation-process-on-smart-contract.md).
3. Visit Create Channel and follow the instructions to create your channel. _Optionally you can visit_  [deploying-your-first-channel.md](../examples/deploying-your-first-channel.md "mention") _guide for step-by-step tutorial._
4. If you wish to create a channel using a Gnosis safe, please visit[creating-a-channel-using-gnosis-safe.md](channel-creation-guides/creating-a-channel-using-gnosis-safe.md "mention") and follow the guide to create one.
5. Ensure that you have the above requirements ready.
6. Head to [the Push prod dapp](http://app.push.org/) or the staging dapp based on your channel creation requirement. **Note:** Channel creation is a protocol-based event which means you can also create the channel by interacting with [EPNS Core Smart Contract](../../developer-tooling/push-smart-contracts/epns-core-contract/channel-creation-process-on-smart-contract.md).
7. Visit Create Channel and follow the instructions to create your channel. _Optionally you can visit_  [deploying-your-first-channel.md](../examples/deploying-your-first-channel.md "mention") _guide for step-by-step tutorials._
8. If you wish to create a channel using a Gnosis safe, please visit[creating-a-channel-using-gnosis-safe.md](channel-creation-guides/creating-a-channel-using-gnosis-safe.md "mention") and follow the guide to create one.

{% hint style="warning" %}
**Need Goerli-PUSH tokens for staging dapp?**

If you are setting up a Channel on Staging dApp, you can get Free Goerli $PUSH tokens from the dApp & online faucets. Alternatively, you can also directly mint Goerli Push from [Etherscan](https://goerli.etherscan.io/address/0x2b9bE9259a4F5Ba6344c1b1c07911539642a2D33).\
You won't need for real PUSH or ETH on the Staging app 😁
{% endhint %}

{% hint style="success" %}
If you are setting up a Channel on Prod dApp (Ethereum Mainnet), you can request for **channel creation gas fee reimbursement** within 24 hrs by [filling out this form](https://docs.google.com/forms/d/e/1FAIpQLScNQ2\_mACRQgyIPsr47woE69\_FOds8aLIGupT20QIEUMfgnQw/viewform). See [this medium article for more information](https://medium.com/ethereum-push-notification-service/calling-all-hobbyist-devs-channel-creation-gas-fee-is-now-refundable-6631ccd01baf).
{% endhint %}
