# Functions-and-Errors---ETH-AVAX_Module2

In this project, you'll create a simple Solidity contract with a few functions and display the values of these functions on a website. The files index.js, MySmartContract.sol, and deploy.js will help you practice interacting with the smart contract through a front-end application.

# Prerequisites
Node.js (v14.0.0 or higher)
MetaMask wallet extension installed in your browser
Starter Next.js/Hardhat Project

# Steps to Set Up
Clone the GitHub Repository:

Open your terminal and navigate to the project directory.
Run npm i to install dependencies.
Open Terminals:

Open two additional terminals in your VS Code.
Run Hardhat Node:

In the second terminal, run npx hardhat node.
Deploy the Smart Contract:

In the third terminal, run npx hardhat run --network localhost scripts/deploy.js.
Launch the Front End:

In the first terminal, run npm run dev to start the front-end application.
Open the Application:

Open your browser and go to http://localhost:3000. The project should be running on your localhost.
Setting up the Local Host Network and a Dummy Account in MetaMask

# Configure MetaMask:

Open the MetaMask extension and click on the network selection button at the top center.
Click on "Add a Network".
Click on "Add a Network Manually".
Add a New Network:

Network Name: Choose any name you like.
New RPC URL: http://127.0.0.1:8545/
Chain ID: 31337
Currency Symbol: ETH
Switch Network:

Set the MetaMask wallet network to the newly created local network.

# Technologies Used
React: A JavaScript library for building user interfaces.
Ethereum: A blockchain network for decentralized applications.
MetaMask: A wallet and gateway to the Ethereum blockchain.
ethers.js: A library for interacting with Ethereum smart contracts.

# Authors
Kumar Abhishek Anand
By following these steps, you'll be able to interact with your smart contract through a front-end application, making it easier to visualize and manage the smart contract's functions and data.
