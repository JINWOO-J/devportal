# Change network in ICONex

When you develop a DApp, you will spend most of your time to test your smart contract on the testnet. ICONex chrome app is a good utility helping DApp development, as you can invoke smart contract functions from the web app without writing a single line of code, as well as sending ICX to test accounts. However, when you install the ICONex chrome app, the default configuration is connected to the mainnet, so, you can not send transactions to the accounts or smart contracts on the testnet. Thus, in this document, we will explain how to connect your ICONex chrome app to the testnet.

### Intended Audience

Someone who wants to send transactions to the testnet from the ICONex Chrome extension.

### Purpose

Following the below guideline will connect their ICONex Chrome wallet to the testnet.

### Prerequisites

* ICONex Chrome extension

  If you do not have the ICONex Chrome Wallet yet, please install the [extension](https://chrome.google.com/webstore/detail/iconex/flpiciilemghbmfalicajoolhkkenfel).

### How to Change Network in ICONex Chrome

* Open the Chrome DevTools by pressing F12, then go to the **Application** tab. In the **Storage** section, expand **Local Storage**.
* Add a new key/value pair, **isDev/true**, by clicking on the empty row at the bottom of the table.

![](https://raw.githubusercontent.com/icon-project/documentation/master/howto/images/iconex-isdev.png)

* Reload your wallet, then you will see the menu in the bottom. Click the **ICX \(SERVER\)** button to open the dropup list of the available networks. You can choose predefined one, or manually set a custom node.

![](https://raw.githubusercontent.com/icon-project/documentation/master/howto/images/iconex-network.png)

### What about on iOS and Andoird ICONex

You can enable developer mode on the ICONex apps to change the network. Please follow the guidelines below.

* Android OS: [https://github.com/icon-project/iconex\_android\#developer-mode](https://github.com/icon-project/iconex_android#developer-mode)
* iOS: [https://github.com/icon-project/iconex\_ios\#developer-mode](https://github.com/icon-project/iconex_ios#developer-mode)

