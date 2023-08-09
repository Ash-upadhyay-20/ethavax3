# Ash Token Smart Contract

This is a Solidity smart contract that represents a token named "Ash" with the symbol "A". It follows the [MIT License](https://opensource.org/licenses/MIT) and utilizes the Solidity version ^0.8.18.

## Introduction

The `Ash Token` smart contract is designed to provide basic token functionality on the Ethereum blockchain. It includes features for minting new tokens, transferring tokens between addresses, and burning (destroying) tokens. The contract is governed by the MIT License, ensuring its open and permissive use.

## Features

- Token Name: Ash
- Token Symbol: A
- Decimals: 18
- Total Supply: Customizable during contract deployment
- Token Balance: Maintained for each address
- Token Transfer: Users can transfer tokens to other addresses
- Token Burn: Users can burn (destroy) their own tokens
- Token Minting: Contract owner can mint new tokens and assign them to an address

## Getting Started

### Prerequisites

To interact with the `Ash Token` smart contract, you will need:

- An Ethereum development environment (e.g., Remix, Hardhat, Truffle)
- Access to an Ethereum wallet (e.g., MetaMask) for deployment and transactions

### Deployment

1. Deploy the `Ash Token` contract using a compatible Solidity compiler (version ^0.8.18 recommended) and an Ethereum development environment.
2. Customize the initial total supply during contract deployment.
3. The contract owner will be assigned the address that deploys the contract.

## Usage

Once deployed, the `Ash Token` contract offers the following functions:

- `mint(address to, uint256 amount)`: Mint new tokens and assign them to the specified address. Only the contract owner can perform this action.
- `transfer(address to, uint256 amount)`: Transfer tokens from the sender's address to the specified address.
- `burn(uint256 amount)`: Burn (destroy) a specific amount of tokens from the sender's address.

### Installing

To run the contract, follow these steps:

1. Install the project dependencies by running the following command:

   ```
   npm install
   ```
2. Start a blockchain locally by running the command: 
   ```
   npx hardhat node
   ```
3. Test the contract by running the command: 
   ```
   npx hardhat test
   ```

4. Deploy the Ash Token Smart Contract by running the deployment script:

   ```
   npx hardhat run scripts/deploy.js --network localhost
   ```

### Executing program

* Go to [remix](remix.ethereum.org) IDE.
* Paste the contract in the IDE.
* Compile the contract.
* Select the `Dev - Hardhat Provider` as the environment in Deploy tab.
* Paste your contract address in remix and click on `At Address`.
* Play with your contract in remix!!

## Disclaimer

This is a simple example of a token smart contract. It is recommended to conduct a thorough security audit before deploying any smart contract to a production environment. The contract owner assumes full responsibility for its deployment and usage.

## License

This smart contract is distributed under the terms of the [MIT License](https://opensource.org/licenses/MIT). You can find the full text of the license in the `LICENSE` file.
```

Feel free to adjust or modify the content as needed to fit your project's specifics.