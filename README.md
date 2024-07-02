# RYZEN ERC-20 Token

## Overview

RYZEN is an ERC-20 token deployed on the Ethereum blockchain. It is implemented using the OpenZeppelin library, providing standard ERC-20 features with additional functionalities such as burning and permit for easy token approvals.

## Contract Features

### ERC-20 Standard

RYZEN follows the ERC-20 standard, allowing it to be used with various decentralized applications (DApps), wallets, and exchanges that support ERC-20 tokens.

### Minting

The contract owner has the exclusive ability to mint new RYZEN tokens into any account. This feature enables the owner to increase the token supply when needed.

### Burning

Any token holder can burn their RYZEN tokens. Burning reduces the total supply, providing a mechanism for users to remove tokens from circulation.

### Permit

RYZEN supports the ERC-2612 permit function, allowing users to approve token transfers with a signature instead of a direct transaction. This feature enhances gas efficiency for certain interactions.

## Deployment

The RYZEN contract is deployed on the Ethereum mainnet with the initial supply of 10 RYZEN tokens. The contract owner is set to the specified initial owner address.
CODE WITH AHSAN
