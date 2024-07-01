# Create a Token

'MyToken' is a simple token contract built on the Ethereum Blockchain. This contract implements a token with basic minting and burning functionalities. The token allows for creation and destruction of token, making it suitable for a variety of decentralized application and token management systems.

## Description

In this, we have used two function i.e. mint function and burn function. 

1. function mint(address _address, uint _value)public
   
   here, two parameters i.e. '_address' which the address where the token will be minted and another parameter is '_value' which is the amount of token to mint.
This function increase the total supply of tokens and credit the specified address with the new tokens.

2. function burn(address _address, uint _value)public

   This function decrease the total supply of tokens and debits the specified address. It includes a check to ensure that the address has a sufficient balance to burn the requested amount of tokens.

   ## Getting Started

   ### Installing

   Solidity compiler: The contract is written in Solidity version 0.8.18. Ensure you have the appropriate compiler version.
   Ethereum Wallet: A wallet like metamask to interat with the Ethereum blockchain.
   Ethereum Node: An Ethereum node provider to deploy the contract.

   ### Executing program

   Step 1: Open Remix IDE, create a new file, paste the contract code and compile.
   
   Step 2: Deploy the contract from Remix IDE using a suitable environment.

   ## License

   This project is licensed under the MIT License. See the LICENSE file for more details.
