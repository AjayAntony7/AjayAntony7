# MyToken Smart Contract

This is a Solidity smart contract for a custom token called MyToken (META).

## Description

The `MyToken` contract is a basic example of a custom token on the Ethereum blockchain. It includes functionalities for minting new tokens and burning tokens from an address. 

## Contract Details

- Token Name: META
- Token Abbreviation: MTA

## Usage

### Prerequisites

To interact with this contract, you'll need:

- A development environment with Solidity compiler (e.g., Remix, Truffle, Hardhat)
- An Ethereum wallet (e.g., MetaMask) for sending transactions

### Deployment

1. Deploy the `MyToken` contract to an Ethereum blockchain using your preferred development environment.

2. After deployment, you can interact with the contract through its functions.

### Minting Tokens

To mint new tokens and add them to the total supply:

```solidity
function mint(address _address, uint _value) public {
    // Your minting logic here
}
