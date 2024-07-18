# MyToken Project

## Overview
The MyToken project is a simple smart contract implementation on the Ethereum blockchain. This project demonstrates the basic functionality of a token contract, including minting and burning tokens.

## Description
The MyToken smart contract is designed to manage a basic cryptocurrency token named "META" with the abbreviation "MTA". This contract allows for the creation of new tokens (minting) and the destruction of existing tokens (burning). The total supply of tokens and individual balances are tracked using public variables and mappings.

## Functions

### mint

The `mint` function's primary purpose is to create new tokens and add them to the total supply. When this function is called, it takes two parameters:
* `_address`: The recipient address
* `_value`: The amount of tokens to be minted

The function first increases the `totalSupply` by the value specified in `_value`. This action reflects the creation of new tokens and updates the total number of tokens in existence. Subsequently, the balance of the specified address (`_address`) is increased by the same `_value`, thereby crediting the newly minted tokens to the recipient's account.
 
### burn

The `burn` function is designed to destroy tokens, effectively reducing the total supply of tokens. This function accepts two parameters:
* `_address`: The address from which tokens will be burned
* `_value`: The number of tokens to be burned

The function first checks if the balance of the specified address (`_address`) is greater than or equal to `_value`. This ensures that an address cannot burn more tokens than it currently possesses. If the balance check is satisfied, the `totalSupply` is decreased by `_value`, reflecting the reduction in the total number of tokens. Additionally, the balance of the specified address is decreased by the same `_value`, removing the tokens from the account.

## Installing

* Clone the repository from GitHub:
  git clone https://github.com/PiiDeeGy/MyToken.git
* Navigate to the project directory:
  cd MyToken
* Install the necessary dependencies:
  npm install

## Help

For common issues or troubleshooting, please do not hesitate to contact me through my email. 

## Authors

- Angel Cruz - https://github.com/PiiDeeGy
