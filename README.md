



![Screenshot 2024-03-14 183537](https://github.com/Poovarasi5603/CrowdFunding-Contract/assets/155304678/66103a88-e91d-4f53-8ef5-01af1556a7c0)


Getting Started
=================================================

**Try running the below commands :**

truffle init

sudo npm install -g ganache             // to install Ganache

**Start Ganache RPC server on localhost 8545**

ganache

truffle console --network ganache        //javascript interactive console to interact with smart contract connected to ganache

**Create a JavaScript migration script,**

01-Crowdfunding-deployment.js

**Add Ganache network in truffle-config.js file,**

ganache: {
    host : "127.0.0.1",
    port: 8545,
    network_id:"*",
},

**Deploy on Ganache blockchain at localhost 8545,**

truffle migrate --network ganache





