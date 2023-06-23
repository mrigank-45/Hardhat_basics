# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

To run locally, run "npx hardhat node" in one tab to open local blockchain network and run "npx hardhat run --network localhost scripts/deploy.js" to deploy the smart contract to this local blockchain network. This is Ganache equivalent from Hardhat, the Hardhat local node.
To deploy the smart contract to a testnet, configure the hardhat.congif.js file and run, npx hardhat run --network sepolia scripts/deploy.js
To verify the smart contract, run npx hardhat verify --contract "contracts/Staking.sol:Staking" --network sepolia <Deployed address> "constructor arg 1" "constructor arg 2"
