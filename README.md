# Project: Defi Empire, A Simple DeFI Kingdom Clone

This GitHub repository contains Solidity contracts for an ERC20 token and a vault contract, along with instructions on how to deploy them locally and interact with them using MetaMask.

## Description

The repository includes two Solidity contracts:

1. **DragonToken**: This contract implements the ERC20 token standard and provides basic functionality for transferring tokens, approving spending, minting new tokens, and burning existing tokens.

2. **Vault**: This contract serves as a vault for storing ERC20 tokens. Users can deposit tokens into the vault, which mints shares representing ownership of the deposited tokens. Shares can be redeemed for tokens at any time.

## Contract Addresses

- DragonToken: [0x5aa01B3b5877255cE50cc55e8986a7a5fe29C70e]
- Vault: [0x5DB9A7629912EBF95876228C24A848de0bfB43A9]

## Getting Started

### Prerequisites

To deploy and interact with the contracts, you'll need:

- Avalanche CLI installed
- MetaMask browser extension

### Deployment

1. Create a subnet.
2. Deploy the created subnet.
3. Add the subnet network manually to your MetaMask.
4. Deploy the contracts to the subnet network using injected provided.
5. Interact with the deployed contracts by sending transactions through MetaMask.

### Contract Interaction

After deploying the contracts, you can interact with them as follows:

- **DragonToken**: Use this contract to create and manage ERC20 tokens. You can mint new tokens, transfer tokens between addresses, approve spending on behalf of other addresses, and burn tokens.
  
- **Vault**: This contract allows users to deposit ERC20 tokens into the vault in exchange for shares. Shares represent ownership of the deposited tokens and can be redeemed for tokens at any time. Users can deposit tokens into the vault and withdraw them as needed.

## Authors

[Omemgboji Emmanuel](mailto:omemgbojiemmanuel)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.