# Decentralized Escrow Application
## About
This is a decentralized escrow applicatoin, which facilitates the buying and selling of items with the help of an arbiter. Here you need three addresses:
1. Beneficiary
2. Depositer
3. Arbiter

The beneficiary is the person who is going to sell an item and get moeny for it. Depositer is the person who wants the item and is paying the beneficiary. Arbiter is the third person who is carrying out this transaction without any bias and malpractice.

The depositer deposits money in the contract. When the beneficiary gives the depositor the item he wants and the item is in good condition. Then the arbiter transfers money from the contract to the beneficiary. Only the arbiter can transfer the money. Nor the depositer or the beneficiary can transfer the moeny.

## How to use

Deploy the contract and send money using the depositor address. When you want to transfer money to the beneficiary you need to connect the website to the arbiter address and carry out the transfer.
## Project Layout

There are three top-level folders:

1. `/app` - contains the front-end application
2. `/contracts` - contains the solidity contract
3. `/tests` - contains tests for the solidity contract

## Setup

Install dependencies in the top-level directory with `npm install`.

After you have installed hardhat locally, you can use commands to test and compile the contracts, among other things. To learn more about these commands run `npx hardhat help`.

Compile the contracts using `npx hardhat compile`. The artifacts will be placed in the `/app` folder, which will make it available to the front-end. This path configuration can be found in the `hardhat.config.js` file.

## Front-End

`cd` into the `/app` directory and run `npm install`

To run the front-end application run `npm start` from the `/app` directory. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

