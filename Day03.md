# Continued Working on the Blockchain App

We've successfully created the skeleton for the EthSwap smart contract. <br/>
Next, we want to create a second smart contract as seen in the diagram below.

![](../100DaysOfWeb3//Images/blockchain4.png)

This second smart contract will be the token that we buy and sell with Ether inside of our exchange. The EthSwap smart contract will talk directly to this token smart contract to facilitate all of the buying and selling functionality

### How this token works ?
Ethereum allows you to create your own cryptocurrency without creating your own blockchain.

Therefore, we'll create our own cryptocurrency with a smart contract.
Specifically, Ethereum has a standard for creating token smart contracts called ERC-20. 

This standard exists to ensure that all tokens work the same way so that they can be used inside of blockchain wallets, and traded on cryptocurrency exchanges. It specifies the types of functions that the token must have, and how they work.

For example, it specifies that these tokens must have a balanceOf() function that returns the user's account balance, and a transfer() function that allows the user to send tokens to someone else.

Because ERC-20 tokens are standardized, I'm going to import a basic ERC-20 token into this project, rather than coding it out step by step. This will save time, and it will allow us to focus on building the exchange.