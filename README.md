# Zebracoin Smart Contract

## Overview

Zebracoin is a custom Ethereum smart contract for managing a simple ERC20-like token. The contract includes functionalities for minting new tokens, burning existing tokens, and tracking balances. This implementation is basic and serves as an introductory example for creating and managing a token on the Ethereum blockchain.

## Features

- **Public Variables:**
  - `tokenName`: Name of the token ("Zebracoin")
  - `tokenAbbrv`: Abbreviation of the token ("Zbr")
  - `totalSupply`: Total supply of Zebracoin tokens

- **Mapping:**
  - `balances`: Mapping of addresses to their respective token balances

- **Functions:**
  - `mint(address _address, uint _value)`: Mint new tokens and assign them to a specified address
  - `burn(address _address, uint _value)`: Burn tokens from a specified address, ensuring sufficient balance

## Prerequisites

To deploy and interact with this smart contract, you will need:

- **Solidity Compiler:** Version ^0.8.0
- **Ethereum Development Environment:** Such as Truffle, Hardhat, or Remix
- **Ethereum Wallet:** Such as MetaMask

## Installation

1. **Clone the Repository:**
    ```sh
    git clone https://github.com/your-username/Zebracoin.git
    cd Zebracoin
    ```

2. **Install Dependencies (if using Truffle or Hardhat):**
    ```sh
    npm install
    ```
## Authors
@DevelKar
