# Team-40

Team - 4 Stars

Members:

1) Gaurav Sharan
2) Utkarsh Aryan
3) Jalavadi Shree Nikhila
4) Nishu Singh

Domain - BlockChain 

# Trux - The Decentralised Application

Trux is a Decentralized E2E Logistics Application that stores the whereabouts of product at every freight hub on the Blockchain. At consumer end, customers can simply scan the QR CODE of products and get complete information about the provenance of that product hence empowering consumers to only purchase authentic and quality products.

We have used web3.js, QRious among other js libraries for this project.
QRious is a pure JavaScript library for generating QR codes using HTML5 canvas.
web3.js is a collection of libraries that allow you to interact with a local or remote ethereum node using HTTP, IPC or WebSocket.

First, we use Ganache to create a local blockchain. Then we use Metamask extension in chrome to connect to ganache rpc and import an account using private key. 
Then we will compile the smart contract in any Solidity compiler (we used remix.ethereum.org). Then we will deploy the contract in remix with metamask using our ganache account. We can see in Ganache that the contract is deployed. 

Now we will paste the Contract ABI and address in the app.js file.

Now we can run this using Mamp or Xampserver in localhost. 

We can see the transactions in Ganache as we add product in the website, showing that the backend is working as expected. 

# About

This repo contains the necessary js libraries, webpages and smart contract. 

These steps will help you test this decentralized application on your own computer.

1) Download and install Ganache (https://www.trufflesuite.com/ganache).
2) Download and install Xampserver on windows (https://www.apachefriends.org/download.html) or MAMP on MacOS X (https://www.mamp.info/en/windows/).
3) Download and install Google Chrome. Go to Chrome store and download Metamask.
4) Create a metamask account.
5) Run Ganache.
6) In metamask, select Networks > Custom RPC
7) Give any name to network.
8) Copy RPC Server URL from Ganache.
9) Go to Metamask > Accounts > Import Account.
10) Open Ganache, go to Accounts tab, click on the key icon on the right side for any account and copy the private key.
11) Paste this key in Metamask import account section.
12) Copy the smartcontract.sol from this repo and paste it in https://remix.ethereum.org/ code section.
13) Save it, go to compile tab and compile the code.
14) Go to deploy tab, select Environment as 'Injected Web3'
15) Click deploy.
16) Copy the contract address and paste it in app.js file.
17) Copy the contract ABI from compile tab and paste it in app.js file.
18) Start MAMP or Xampserver.
19) Paste the project folder inside htdocs folder of the root directory.
20) Go to localhost or localhost:8888/
21) Open phpmyadmin, go to SQL and paste the sql queries provided inside the sql folder.
22) Execute the queries.
23) It should be running as expected.
