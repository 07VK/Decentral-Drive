# Block Drive: Decentralized Image Upload and Sharing using Blockchain - Decentral Drive

This project facilitates decentralized image upload and sharing on the blockchain using Solidity for the smart contract and React for the front-end interface. It enables users to securely upload images to IPFS (InterPlanetary File System) and share access with specified users through smart contract functionality.

## Features

* **Decentralized Storage:** Images are uploaded to IPFS, ensuring decentralized and immutable storage.
* **Smart Contract:** Utilizes Solidity smart contracts on the Ethereum blockchain for access control and ownership management.
* **Access Control:** Users can grant or revoke access to their uploaded images to specific individuals through the smart contract.

## Technologies Used

* Solidity: Smart contract development for ownership and access control.
* React: Front-end interface for uploading images and managing access.
* IPFS: Decentralized storage protocol for hosting uploaded images.

## Getting Started

### Prerequisites

Ensure you have the following dependencies installed:

* Node.js
* npm (Node Package Manager)

### Installation

1.  Clone this repository to your local machine.
2.  Navigate to the `contracts` folder and create a file named `Upload.sol`. Copy and paste the provided Solidity code into this file.
3.  Install the necessary library packages by running the following commands in your terminal:

    ```bash
    npm install hardhat
    npm install ethers
    npm install react
    npm install @n...
    ```
4.  Navigate to the `client` folder.
5.  Replace the `App.js`, `FileUpload.js`, `Display.js`, `Modal.js`, and `index.js` files with the provided code.
6.  Use the respective CSS files for styling the React components.
7.  Start the React application:

    ```bash
    npm start
    ```
8.  Access the decentralized file sharing dApp through your browser at `http://localhost:3000`.

## Usage

Once the setup and configuration are complete, follow these steps to utilize the decentralized image upload and sharing system:

1.  **Install Metamask:**
    * Ensure Metamask is installed and configured in your browser for Ethereum interactions.

2.  **Update Contract Address:**
    * After smart contract deployment, make sure to update the contract address in `App.js` within the React application.

3.  **Upload Image before "Get Data
