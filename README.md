INSTALLATION GUIDE FOR DEVELOPMENT AND PRODUCTION

# DRYFACTORY Decentralized Application 
Full Stack NFT Marketplace on top of Ethereum Blockchain Ledger developed using Polygon, Hardhat, React and Node.js.

## Installation
Node.js & Node Package Manager Install:

https://nodejs.org/en/download/


Check Node.js and NPM version (Use Command Prompt to check) -
$ node -v
v14++

$ npm -v
7++


Metamask Wallet Browser Extension Install:

https://metamask.io/download.html



## Setup
Using Git commands from Zip Folder:

Open the project folder using -

//   Terminal - MacOS   //
//   Command Prompt - Windows   //
//   Powershell - Windows/Linux   //


Clone the Project locally, change into the directory, and install the dependencies:

$ cd dryfactory
$ npm install



Start the local Hardhat Node:

$ npx hardhat node


With the network running, deploy the contracts to the local network in a separate terminal window:

$ npx hardhat run scripts/deploy.js --network localhost


Start the app

$ npm run dev



## App Info
### Author

Dibakar Sutra Dhar (https://www.dibakar.me)

### Version

1.0.0

### License

This Project is licensed under the MIT License


