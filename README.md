# Functions-and-Errors---ETH-AVAX_Module2
 In this project, you'll create a simple Solidity contract with a few functions and display the values of these functions on a website. The files index.js, 
 MySmartContract.sol, and deploy.js will help you practice interacting with the smart contract through a front-end application.

# Prerequisites
1. Node.js (v14.0.0 or higher)
2. MetaMask wallet extension installed in your browser
3. Starter Next.js/Hardhat project

# Clone the GitHub Repository
 1. Open your terminal and navigate to the project directory.
 2. Run npm i to install dependencies.
 3. Open Terminals
 4. Open two additional terminals in your VS Code.
 5. Run Hardhat Node
 6. In the second terminal, run:
     npx hardhat node
 7. Deploy the Smart Contract
 8. In the third terminal, run:
     npx hardhat run --network localhost scripts/deploy.js
 9. Launch the Front End  
     npm run dev
 10. Open your browser and go to http://localhost:3000. The project should be running on your localhost.

# Configure MetaMask

# Setting up the Local Host Network and a Dummy Account in MetaMask
1. Open the MetaMask extension and click on the network selection button at the top center.
2. Click on "Add a Network".
3. Click on "Add a Network Manually".
   
# Add a New Network
1. Network Name: Choose any name you like.
2. New RPC URL: http://127.0.0.1:8545/
3. Chain ID: 31337
4. Currency Symbol: ETH

# Switch Network
 1.Set the MetaMask wallet network to the newly created local network.

# Technologies Used
1. React: A JavaScript library for building user interfaces.
2. Ethereum: A blockchain network for decentralized applications.
3. MetaMask: A wallet and gateway to the Ethereum blockchain.
4. ethers.js: A library for interacting with Ethereum smart contracts.
   
# Authors
Kumar Abhishek Anand
