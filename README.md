# Trade Bridge

## Description
This project is a decentralised smart contract built using solidity and hardhat.It provide a plateform for buying and selling of commodities and also issueing NFT as a proof of transaction between the buyer and the seller.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Running Tests](#running-tests)
4. [Deployment](#deployment)
5. [Features](#features)
6. [Future Features / Roadmap](#future-features-roadmap)
7. [Technologies](#technologies)
8. [Contributing](#contributing)
9. [License](#license)

## Installation
1. clone the repository
```
git clone https://github.com/dimka90/Block-Bridge.git
```

1.1 ## Navigate to the project directory ##:
    ```bash
    cd Block-Bridge
    ```

 ## Install dependencies##:
    ``` bash
     npm install
    ```

## Usage

### Compile Contracts:
```bash
npx hardhat compile
```
### Running Test
```bash
npx hardhat test
```

### Deploy the project
```bash
npx hardhat run /scripts/deploy.ts --network Lisk
```
### Present Features

1. Register Buyers and Sellers using there wallet address.
### Seller
- The seller can add commodity to the plateform.
- The seller can sell goods on the plateform.
- 
### Buyers 
- The buyer can buy goods using Lisks native token.
- On Successfull payment, an NFT will be issued to the Buyer to signify the own the commodity.
### System
- The smart contract provide the plateform for the buyers and sellers to trade.
- The smart contract gives rating upon successfull 