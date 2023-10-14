# SmartContract Solidity Smart Contract

## Description
The "SmartContract" Solidity smart contract is an example contract showcasing various concepts in Ethereum smart contract development. It includes features such as ownership control, modifier usage, and assertions.

## Content Overview
This contract includes the following key components:

1. **Token Details**:
   - The contract has a state variable to store the Ethereum address of the contract owner (`contractOwner`).
   - It also stores an unsigned integer value (`value`).

2. **Constructor**:
   - The constructor sets the `contractOwner` to the Ethereum address of the account that deploys the contract.

3. **setValue Function**:
   - This function allows the contract owner to set the `value` variable.
   - It uses the `require` to check if the new value is greater than 1.

4. **assertDemo Function**:
   - The `assertDemo` function uses the `assert` statement to check if the product of two input numbers is greater than one of those numbers.

5. **revertDemo Function**:
   - The `revertDemo` function uses the `revert` statement to revert the transaction with a custom error message if the input value is less than or equal to 1; otherwise, it performs a calculation.

## Getting Started
### Execution
- You can deploy and test this contract using the Remix Online IDE or any Ethereum development environment.
- Make sure to specify the contract owner during deployment.
- After deployment, interact with the contract using the provided functions.

### Interacting with the Contract
- The `setValue` function allows the contract owner to set the `value`.
- The `assertDemo` function demonstrates the use of the `assert` statement.
- The `revertDemo` function showcases the use of the `revert` statement.

# Authors
Deanne Joy R. Santos

