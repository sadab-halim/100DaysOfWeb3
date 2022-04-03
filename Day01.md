# Blockchain

## What is a Blockchain ?
- A blockchain is a distributed database that is shared among the nodes of a computer network.
- It stores information electronically in digital format.
- It is known for maintaining and securing and decentralized record of transactions.

### Difference between a typical database and a blockchain ?
A blockchain collects information together in groups known as **blocks** that holds set of information. <br/>
Blocks have certain storage capacities and, when filled, are closed and linked to the previously filled block, forming a chain of data which is known as the **blockchain**. <br/>

All new information that follows that freshly added block is compiled into a newly formed block that will then also be added to the chain once filled. <br/>

A database usually structures its data into tables, whereas a blockchain, like its name implies, structures its data into blocks that are strung together. <br/>

As new data comes in, it is entered into a fresh block. Once the block is filled with data, it is chained onto the previous block, which makes the data chained together in chronological order.

### Points to Remember

- Different types of information can be stored on a blockchain, but the most common use so far has been as a ledger for transactions.

- In Bitcoin’s case, blockchain is used in a decentralized way so that no single person or group has control—rather, all users collectively retain control.

- Decentralized blockchains are immutable, which means that the data entered is irreversible. For Bitcoin, this means that transactions are permanently recorded and viewable to anyone.

### How Does a Blockchain Work ?
A blockchain collects information together in groups, known as blocks, that hold sets of information. <br/>
Blocks have certain storage capacities and, when filled, are closed and linked to the previously filled block, forming a chain of data known as the blockchain.

### Why Blockchain is called a Decentralized Technology ?
Blockchain is called a Decentralized Technology as the complete list of data stored in the blockchain is not in control of any central authority but is like a distributed public ledger which anyone and everyone can have a copy of.

### What type of information can be stored in a block ?
- Data: For example transaction in case of Bitcoin
- Hash of the current block: Cryptographically aggregated transaction information of the block
- Hash of previous block

### How is it secure ?
Since every block contains the hash of the previous block, in order to make change in any one of the blocks the hacker will have to make changes to every other previous block as well, which is next to impossible & that's how it is secured

### How does a transaction goes through ?
- Transaction is sent to the network
- All the nodes gets notified who then start solving a complex mathematical puzzle
-  Whoever solves it first let the rest of the nodes know who then start validating it
- If at least 50% nodes validate it to be true, the transaction is added to blockchain & the node who solved it is rewarded with crypto
- The nodes who participate in solving the puzzle are called "Miners"
- Also, once the information is added it can never be removed or edited