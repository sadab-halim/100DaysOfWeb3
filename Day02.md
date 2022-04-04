# Blockchain

## How Blockchain Works ?
- A blockchain is basically a giant world-wide computer.

- Instead of using a single computer that stores data and runs programs, blockchains use thousands of computers to handle this. 
- Each computer is called a `node`, and they all talk to one another.

![blockchain](/100DaysOfWeb3/Images/blockchain1.png)

- Each node gets a copy of all the code and data stored on the blockchain. This data is stored in bundles of records called `blocks` which are chained together to make up this public ledger

- All of the code is stored in `smart contracts` which are immutable programs that run on the blockchain.

**Example of Blockchain:** <br/>
You can create a cryptocurrency with a blockchain because each node in the network is responsible for processing transactions and tracking your balance.

Whenever you send cryptocurrency, the network achieves `consensus` that your transaction is valid, and your balance is updated properly on the public ledger.

## How Blockchain App Works ?
In this example, we're going to use Ethereum to show working of "dApp" or Decentralized App.

![blockchain2](/100DaysOfWeb3/Images/blockchain2.png)

- To access the application, you use your browser to connect to a front end website written in HTML, CSS, and JS.

- Then, instead of talking to a backend web server, this website talks directly to the blockchain. This is where all of the code and data and code for the application live.

- This code is contained in Smart Contracts, written in with the Solidity Programming language, which looks a lot like JavaScript. 

- These smart contracts are immutable, which means the the code cannot change.

- All of the data is stored on the public ledger, which is also immutable. Any time we add new data to the blockchain, it will be permanent publicly verifiable.

## Overview of EthSwap (Blockchain App)
EthSwap lets you buy and sell cyrptocurrencies at a fixed price.

We'll create a fictional cryptocurrency called "Dapp Token" together, which can be purchased with Ether, the native cryptocurrency of the Ethereum blockchain.

Diagram of how the application will work? <br/>

![blockchain3](/100DaysOfWeb3/Images/blockchain3.png)

We'll create a client side website that with React.js that talks directly to two Ethereum smart contracts on the blockchain:

1. The first smart contract "EthSwap" will facilitate buying and selling cryptocurrencies.
2. The second smart contract will power the fictional "DApp Token" that we'll create together.

Each of these smart contract will be coded in the Solidity programming language, for tests it will be written in JavaScript and will be deployed them to the blockchain.

