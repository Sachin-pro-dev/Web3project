# Krypt - Web 3.0 Blockchain Application
![Krypt](https://i.ibb.co/DVF4tNW/image.png)


## Features

- **Connect Wallet**: Users can connect their MetaMask wallet and interact with the app.
- **Send Transactions**: Send Ethereum to a specified account with a keyword and an optional message.
- **View Transactions**: All transactions are stored on the blockchain and displayed in the application.
- **Etherscan Integration**: View transaction details directly on Etherscan.
- **Test Network**: The application is built for the Ropsten test network.

---

## Demo Workflow

1. **Connecting Wallet**:
   - Click the `Connect Wallet` button.
   - Connect your wallet via MetaMask. You'll be prompted to select the account to connect.
   - The connected account address will appear on the Ethereum card in the app.

2. **Sending Ethereum**:
   - Switch to another MetaMask account (e.g., Account 2).
   - Copy the address of the second account.
   - Paste the copied address into the recipient field.
   - Enter the amount of Ethereum to send (e.g., `0.01` ETH).
   - Add a keyword to tag the transaction, which will be stored as metadata on the blockchain.
   - Optionally, include a message (e.g., "Hello from Account 1").
   - Click the `Send` button. MetaMask will prompt for confirmation twice:
     1. To send Ethereum.
     2. To interact with the smart contract.

3. **Viewing Transactions**:
   - Scroll down to the "Latest Transactions" section.
   - See details of all transactions, including:
     - Sender and recipient addresses.
     - Amount of Ethereum sent.
     - Associated keyword and message.
     - Date and time of the transaction.
   - Click on any address to view its details on Etherscan.

---

## Technology Stack

- **Frontend**: React.js
- **Blockchain Integration**: MetaMask, Web3.js
- **Smart Contracts**: Solidity
- **Test Network**: Ropsten Testnet

---

## Hardhat Project

This application uses **Hardhat** for compiling, deploying, and testing smart contracts.

### Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with:
- A sample contract.
- A test for the contract.
- A sample script to deploy the contract.
- A task implementation that lists available accounts.

### Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

---

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd web3-ethereum-transaction-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open the application in your browser at:
   ```
   http://localhost:3000
   ```

---

## Notes

- Ensure you have MetaMask installed and configured to use the Ropsten test network.
- Obtain test Ether from a Ropsten faucet to simulate transactions.
- Install Hardhat globally if not already installed:
  ```bash
  npm install --save-dev hardhat
  ```

---

## Features to Implement

- Enhance transaction filtering and search.
- Add support for multiple blockchain networks.
- Improve UI/UX for a more seamless user experience.

---

## License

This project is licensed under the MIT License.

---

Happy Coding! 🚀
```

This version incorporates the Hardhat project information and tasks. Let me know if you'd like additional details or adjustments!
