# Web3
Update the follwing variables stored in the .env file

PRIVATE_KEY = Metamask PRIVATE KEY
API_URL_KEY = Alchemy HTTPS KEY
API_KEY =  Alchemy API Key
CONTRACT_ADDRESS = CONTRACT ADDRESS , after deployement


Run the following commands in order.
**1. npx hardhat run scripts/deploy.js --network goerli**
this will generate the contract address once its deployed on the blockchain.

**2. npx hardhat run scripts/interact.js --network goerli** 
This will output the result.

For better inderstanding please refer the https://metaschool.so/course/writing-your-first-hello-world-contract-in-solidity
    
