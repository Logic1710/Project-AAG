# Project SGU X AAG [Fundraiser]

This project was created as a collaboration between AAG and SGU in order to better understand the Web 3.0 world and teach students through lectures, networking, and project work. This specific project focuses on the creation and deployment of a Web 3.0 crowdfunding/fundraiser platform designed to accept payments through connected wallets and allows users to create projects within the website that need funding.

## Images / Examples

![website screenshot 1](https://i.ibb.co/YfgW224/Example1.jpg)

Profile view of a wallet's active campaigns

![website screenshot 2](https://i.ibb.co/pfHNFDK/Example2.png)

Detailed view of an active dummy campaign

## Quickstart

After downloading/cloning the repository, you will be presented with a "client" and "web3" file. These are two separate web project folders and will be used separately.

**First, the web3 folder:**

Before running any commands, the first step is to input your wallet's private key into the web3 folder in the form of an ***.env*** file. See below:

```env
PRIVATE_KEY=<INSERT YOUR WALLET'S PRIVATE KEY HERE>
```
Name this file `.env`

Next, run the following command to build and deploy the contract:
```shell
npm run build
# or
yarn build

npm run deploy
# or
yarn deploy
```
Your web3 contract should now be ready to handle transactions.

*Note: This project uses the Saakuru Testnet suggested and implemented by AAG, change the relevant code within the web3 folder to suit your needs.*

**Second, the client folder:**

The client folder is ready to go straight from the repo, just run the following command to get the website up and running:

```shell
npm start
```

## Additional Information

![License](https://img.shields.io/badge/License-Unlicensed-black.svg)  
![Dev Status](https://img.shields.io/badge/Development-InProgress-blue.svg)  


## Acknowledgements

 - [AAG](https://aag.ventures/)
 - [thirdweb](https://thirdweb.com/)
 - [JavaScript Mastery](https://www.youtube.com/@javascriptmastery)

