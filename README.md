# FundManager Smart Contract

The FundManager contract demonstrates basic functionalities for managing a fund on the Ethereum blockchain. It includes methods for contributing, withdrawing, and performing mathematical division.

## Description

The FundManager contract allows users to contribute funds to a shared pool, withdraw from it while ensuring there are sufficient funds, and perform division calculations. The contract showcases various aspects of smart contract development, including input validation and mathematical operations.

## Functions

### `contribute(uint _amount)`

Contribute a specified amount to the fund. Requires the `_amount` to be greater than 0.

### `withdraw(uint _amount)`

Withdraw a specified amount from the fund. Requires the `_amount` to be greater than 0 and not exceeding the available fund balance.

### `divide(uint _numerator, uint _denominator)`

Perform a division operation and return the result. Requires `_numerator` to be greater than or equal to `_denominator`.

## Example Usage

1. Deploy the contract on a local or test Ethereum network.
2. Contribute funds using the `contribute` function.
3. Withdraw funds using the `withdraw` function.
4. Perform division calculations using the `divide` function.

## Contributors

This project is maintained by the following contributors:

### Sandip Thakur

## License

This project is licensed under the MIT (https://github.com/sandipodd/ETH-AVAX-Project-module-1/blob/main/LICENSE).
