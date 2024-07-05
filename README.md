# ETH-AVAX
# Project on functions and errors in ETH+AVAX

# AssertionExample Smart Contract

This smart contract is a basic example that demonstrates the use of `require()`, `assert()`, and `revert()` statements in Solidity. It includes simple deposit and withdrawal functions with validation checks.

## Functions

### Deposit

The `deposit` function allows users to deposit funds. It includes the following checks:

- Uses `require()` to check if the deposit value is greater than zero.
- Uses `assert()` to ensure that adding the deposit value does not result in an overflow.

### Withdraw

The `withdraw` function enables users to withdraw funds. It includes the following checks:

- Uses `require()` to check if the withdrawal value is greater than zero.
- Uses `revert()` to unconditionally revert the transaction if the withdrawal value exceeds the available funds.

## Usage

1. Deploy the smart contract to a compatible Ethereum network or the Remix IDE.
2. Interact with the contract by calling the `deposit` and `withdraw` functions.

**Note:** Make sure to test the contract in a suitable development environment before deploying to a mainnet.
