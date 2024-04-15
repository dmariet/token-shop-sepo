# token-shop-sepo

## Overview
The Token Shop contract is a decentralized application (dApp) deployed on the Sepolia network. It enables users to purchase tokens using Ether (ETH) based on the current ETH/USD price feed obtained from a Chainlink oracle.

## Features
- Allows users to purchase tokens with Ether (ETH) at the current market price.
- Retrieves the latest ETH/USD price feed from a Chainlink oracle.
- Calculates the amount of tokens to mint based on the amount of ETH sent by the user.
- Facilitates token minting to the user's address upon ETH payment.
- Provides a withdrawal function for the contract owner to withdraw accumulated ETH balance.

## Contracts
- **TokenShop.sol:** Main smart contract implementing the functionality of the Token Shop dApp.
  
## Usage
1. Deploy the TokenShop contract on the Sepolia network.
2. Ensure that the contract owner is set correctly to manage the contract.
3. Users can interact with the Token Shop by sending ETH to the contract address.
4. The contract calculates the equivalent amount of tokens based on the received ETH and mints tokens to the sender's address.
5. The contract owner can withdraw accumulated ETH balance using the `withdraw` function.

## Deployment
- Network: Sepolia
- Chainlink Oracle: ETH/USD (Address: 0x694AA1769357215DE4FAC081bf1f309aDC325306)

## Security Considerations
- Ensure that the contract owner address is secured and only accessible by authorized personnel.
- Validate inputs and perform appropriate checks to prevent unexpected behavior or exploits.

## License
This contract is released under the MIT License.
