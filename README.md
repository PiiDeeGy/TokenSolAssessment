---

# MyToken Project

## Overview
The MyToken project is a simple smart contract implementation on the Ethereum blockchain. This project demonstrates the basic functionality of a token contract, including minting and burning tokens.

## Description
The MyToken smart contract is designed to manage a basic cryptocurrency token named "META" with the abbreviation "MTA". This contract allows for the creation of new tokens (minting) and the destruction of existing tokens (burning). The total supply of tokens and individual balances are tracked using public variables and mappings.

## Getting Started

### Installing
To download and set up the MyToken contract, follow these steps:

1. Clone the repository:
   git clone https://github.com/yourusername/MyToken.git

2. Navigate to the project directory:
   cd MyToken

### Executing Program
To compile and deploy the MyToken contract, follow these steps:

1. Open the project in your preferred Ethereum development environment (e.g., Remix, Truffle).
2. Compile the contract:
   // In Remix, select the MyToken contract and click on the "Compile" button
   // In Truffle, run the following command in the terminal
   truffle compile

3. Deploy the contract to your desired Ethereum network:
   // In Remix, select the "Deploy & Run Transactions" tab, configure the environment, and click on "Deploy"
   // In Truffle, run the following command in the terminal
   truffle migrate --network <network_name>

### Help
If you encounter any issues, here are some common problems and solutions:

- **Error during compilation**: Ensure that your Solidity version is compatible with the contract code. You may need to specify the correct version in your compiler settings.
- **Deployment issues**: Verify that your network settings and credentials (e.g., Infura project ID, private key) are correct.

For additional help, you can run the following command if the program contains helper info:
truffle help

## Authors
- Angel Cruz - https://github.com/PiiDeeGy
---
