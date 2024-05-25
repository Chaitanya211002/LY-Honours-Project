# Decentralized Image Upload and Sharing

## Features

- **Decentralized Storage:** Images are uploaded to IPFS, ensuring decentralized and immutable storage.
- **Smart Contract:** Utilizes Solidity smart contracts on the Ethereum blockchain for access control and ownership management.
- **Access Control:** Users can grant or revoke access to their uploaded images to specific individuals through the smart contract.

## Technologies Used

- **Solidity:** Smart contract development for ownership and access control.
- **React:** Front-end interface for uploading images and managing access.
- **IPFS:** Decentralized storage protocol for hosting uploaded images.

## Usage

### Installation

1. Install dependencies for the hardhat:

   ```bash
   # Navigate to the root directory
   # Install hardhat dependencies
   npm install
   ```
2. Compile the smart contract for artifacts:

   ```bash
   # Compile Smart Contract
   npx hardhat compile
   ```
3. Deploy the Solidity smart contract to an Ethereum testnet or local development environment.
   ```bash
   # Deploy Smart Contract
   npx hardhat run scripts/deploy.js --network <network-name>
   ```
4. Install dependencies for the React front end:
   ```bash
   # Navigate to the React client directory
   cd client 
   # Install React dependencies
   npm install
   ```
5. Run the react application:
   ```bash
   # Start React Application
   npm start
   ```
