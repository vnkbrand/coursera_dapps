<!-- WEEK 1 -->
INTRO TO DAPPs
DApp is an end-to-end application on a blockchain

In its simplest form, a DApp has a client interface as a front-end, and a back-end that includes a blockchain and a smart contract.

The client or the front-end can be a web app, HTML and Javascript framework. A command line interface, CLI, a desktop application, a mobile application, or even an IoT, Internet of Things.

Additionally, a DApp can be created with a non-blockchain back-end. Interplanetary file system, IPFS, is an example of such an architecture.

DApps Stack
1. Verticals - End to end user apps
2. Application Framework - Smart Contracts
3. EVM & Ethereum Blockchain
4. Peer-to-Peer Network and OS
5. Hardware

DApp - Web3
A Dapp, or decentralized application, solves a problem that requires blockchain services and blockchain infrastructure for realizing its purpose. Typically, a Dapp has a web front-end, and a blockchain back end, and the code connecting the two.

In such an architecture, the front-end of a Dapp channels any external stimulus from the users to the blockchain infrastructure and returns any response back to them.

It initiates transactions to invoke functions on the smart contract. That in turn, records the transactions and state transition and receipts on the blockchain. The front-end of a Dapp can be as simple as a command line interface.

In contrast to Web2 applications, Web3 applications need a connection to the blockchain, which is managed by a special application called “wallet.” It keeps a record of the private keys and blockchain address, which represents the unique 30 identities and point of reference. Without a so ware that manages our digital identity, we will not be able to interact with the blockchain. The Web3, therefore, builds on the current Web2 stack and introduces additional elements on an application level. In the backend, the Web3 adds a whole new infrastructure layer for decentralized applications to interact with – the decentralized protocol stack. Decentralized apps need to have a component that manages a user’s private keys, with which one can sign transactions on the state layer, the blockchain

ETHEREUM API's
2 Major API's

MANAGEMENT API

The first one is the management APIs, that includes admin, debug, miner, personal, and txpool. They support methods for management of the geth node.

Admin API - the Admin API allows you to use functions to work with your Geth instance, including network peer and the RPC endpoint management. Examples, admin.addPeer(), admin.nodeInfo(). In this case, admin is the API, and addPeer and nodeInfo are functions of the admin API. You can observe that admin supports functions for management of the node.

Debug API - Debug.dumpBlock(16). This will display the block header details of block 16. You can observe that the debug API provides you the ability to peek into the blockchain, study it, and debug any issues by looking at the block.

Miner API - Miner API, the miner API allows you to control the nodes mining operation and set various mining specific settings. Example, miner.start(), miner.stop() are sample functions that will start and stop the miner. You can also say miner.start(6), where 6 parallel threads are assigned to the mining operation.

Personal API - deals with the creation and management of accounts within a node. It also manages private keys in the key store. Example, personal.newAccount() will create a new account within a node.

TxPool API -  transaction pool API, gives you access to several non-standard RPC methods to inspect the contents of the transaction pool, containing all the currently pending transaction, as well as those queued for future processing. Example, txpool.inspect() lists you all the pending transactions for you to peruse and collect for building a block of transactions.

WEB3 API
The second one is the web3 API, web3, eth, and net. They support methods for development of Dapps. Web3.js library, when included into Dapp, lets you use web3 object provided by the web3.js library and all its objects. It also lets you communicate with a local node through the RPC port. 

Web3 is a JavaScript library that's specifically designed for use with web client or Ethereum Dapps. It's a portal through which all the underlying operations of the Ethereum node on the blockchain server can be invoked. For example, a Smart Contract deployment and Smart Contract function invocation.

You will use web3 in the development in the front-end of the Dapp and for interacting with the blockchain.

It also provides access to the eth object and its function via web3.eth, and net object via web3.net, and their respective function. 

You can also access other management APIs to the web3 object.

There is also Whisper API, web3.ssh. It is used for secure gossiping and enables the Whisper protocol.

SUMMARY
For a Dapp, the geth client has to expose an RPC endpoint using RPC port command. A web3 object is instantiated in the web page script. Recall that web3.js is a JavaScript library. Requests or calls are invoked on the web3 object.

Requests are transmitted as a JSON or RPC pipeline between the web client and the geth client.

Requested call and function is executed using appropriate API and Smart Contract code.

Result returned to we client.






