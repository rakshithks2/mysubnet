# ERC20 Token and Vault Contracts

This repository contains two Solidity smart contracts: `ERC20.sol` and `Vault.sol`, implementing the ERC20 token standard and a secure vault for storing tokens, respectively.

## ERC20 Token Contract

The `ERC20.sol` contract implements the ERC20 standard for Ethereum tokens. Key features include:

- **Token Metadata**: The contract provides metadata such as token name (`name`), symbol (`symbol`), and decimals (`decimals`).
- **Token Management**: Users can query their token balances (`balanceOf`), transfer tokens to other addresses (`transfer`), approve spending allowances for third-party addresses (`approve`), and transfer tokens on behalf of others (`transferFrom`).
- **Token Minting and Burning**: The contract allows the creation (`mint`) and destruction (`burn`) of tokens, managed by the contract owner.

## Vault Contract

The `Vault.sol` contract serves as a secure storage solution for ERC20 tokens. Key features include:

- **Token Storage**: Users can deposit tokens into the vault (`deposit`) and withdraw them later (`withdraw`).
- **Token Management**: The vault contract tracks users' token balances within the vault (`balanceOf`).
- **Safe Deposit and Withdrawal**: The vault contract ensures safe deposit and withdrawal operations, preventing unauthorized access to deposited tokens.

## Usage

To use these contracts, follow these steps:

1. Compile the contracts using a Solidity compiler compatible with version ^0.8.17.
2. Deploy the compiled contracts to an Ethereum blockchain or testnet.
3. Interact with the ERC20 token contract for token-related operations.
4. Utilize the vault contract to securely store and manage tokens.

## Development

- The contracts are written in Solidity version ^0.8.17.
- Unit tests and integration tests can be added to ensure contract functionality and integrity.
- Continuous integration (CI) pipelines can be set up for automated testing and deployment processes.

## License

This project is licensed under the MIT License.
