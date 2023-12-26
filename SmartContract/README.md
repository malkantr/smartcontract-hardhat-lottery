# Hardhat - Lottery : 

Smart Contract / Backend

## basics and hardhat setup 
```
yarn add --dev hardhat

yarn hardhat  -> empty hardhat.config.js

yarn add --dev @nomiclabs/hardhat-ethers@npm:hardhat-deploy-ethers ethers @nomiclabs/hardhat-etherscan @nomiclabs/hardhat-waffle chai ethereum-waffle hardhat hardhat-contract-sizer hardhat-deploy hardhat-gas-reporter prettier prettier-plugin-solidity solhint solidity-coverage dotenv

// copy dependencies to hardhat.config.js
// copy settings to .prettierrc

```

## raffle setup

```
create Raffle.sol

yarn hardhat compile
yarn add --dev "@nomicfoundation/hardhat-ethers@^3.0.2"

yarn add --dev @chainlink/contracts@0.5.1

```