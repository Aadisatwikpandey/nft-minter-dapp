# NFT Minter dApp

A simple Decentralized Application (dApp) for minting a custom Non-Fungible Token (NFT).

## Technologies Used

*   **Smart Contract Language:** [Solidity](https://soliditylang.org/)
*   **Smart Contract Framework:** [OpenZeppelin Contracts](https://openzeppelin.com/contracts/)
*   **Frontend Framework:** [React](https://react.dev/)
*   **Web3 Library:** [Ethers.js](https://docs.ethers.org/v6/)

## Key Features

*   **Custom ERC721 Token:** A unique NFT token with a custom name and symbol.
*   **Owner-only Minting:** Only the contract owner can mint new NFTs.
*   **Simple Frontend:** A user interface to interact with the smart contract and mint NFTs.

## Setup Instructions

### Smart Contract

1.  **Install Hardhat (or your preferred development environment):**
    ```bash
    npm install --save-dev hardhat
    ```
2.  **Compile the contract:**
    ```bash
    npx hardhat compile
    ```
3.  **Deploy the contract:** (This will depend on your chosen network and deployment method)
    ```bash
    npx hardhat run scripts/deploy.js --network <your-network>
    ```

### Frontend

1.  **Navigate to the frontend directory:**
    ```bash
    cd frontend
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Start the development server:**
    ```bash
    npm start
    ```
4.  **Open your browser and visit:** [http://localhost:3000](http://localhost:3000) (or the port indicated by `npm start`)

## Visual Representation

### Screenshots

*   **[Placeholder for Screenshot 1]**
*   **[Placeholder for Screenshot 2]**

### GIFs

*   **[Placeholder for GIF 1]**

