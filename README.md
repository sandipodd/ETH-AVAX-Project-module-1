# ETH-AVAX-Project-module-1
# Project Title

A simple Ethereum smart contract for managing a fund's balance.

## Description

This project consists of a Solidity smart contract named `FundManager`. The contract provides functionalities to manage a fund's balance, allowing users to contribute funds, withdraw funds, and set the fund's balance while enforcing constraints to ensure proper fund management.

## Getting Started

### Installing

To use the smart contract, you need an Ethereum development environment and a tool to deploy smart contracts, such as Remix or Truffle.

* Install [Remix](https://remix.ethereum.org/) or [Truffle](https://www.trufflesuite.com/truffle) on your local machine.

### Executing program

Follow these steps to deploy and interact with the smart contract:

1. Open Remix or Truffle on your local machine.
2. Create a new Solidity file and paste the content of the `FundManager.sol` contract into it.
3. Compile the contract to make sure there are no syntax errors.
4. Deploy the contract to an Ethereum network of your choice (e.g., Remix's JavaScript VM, Ropsten, etc.).
5. Once deployed, you can interact with the contract using its functions.

**Contributing Funds:**
Call the `contribute` function with the desired contribution amount. Make sure the amount is greater than 0.

**Withdrawing Funds:**
Call the `withdraw` function with the amount you want to withdraw. Ensure the amount is greater than 0 and doesn't exceed the available fund balance.

**Setting Fund Balance:**
Use the `setFundBalance` function to set the fund's balance to a specified value. This function will revert if you attempt to set a negative balance.

## Help

If you encounter any issues or need assistance, feel free to reach out to the contributors.

## Authors

### Sandip Thakur

## License

This project is licensed under the MIT ().
