# Shipping-Management-Using-Blockchain

A decentralized application (DApp) built on the Ethereum blockchain to manage shipping processes transparently and securely.

## 🚀 Features

- 🧾 Smart contract for tracking shipping orders and delivery status
- 🌐 Web interface for users to create and manage shipments
- 🔐 Tamper-proof transaction records via Ethereum blockchain
- 💬 Real-time shipment updates

## 🛠️ Tech Stack

- **Solidity** – Smart contract language
- **Ethereum** – Blockchain platform
- **Web3.js / Ethers.js** – Blockchain interaction
- **HTML/CSS/JavaScript** or **React.js** – Frontend interface
- **Truffle / Hardhat** – Smart contract development and testing

## 📦 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/YourUsername/Shipping-Blockchain.git
cd Shipping-Blockchain

2. Install Dependencies

npm install
3. Deploy Contracts (Truffle/Hardhat Example)

npx hardhat compile
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost

4. Run the Frontend

npm start

✅ Smart Contract Functionality
createShipment(address receiver, string memory details)

updateStatus(uint shipmentId, string memory newStatus)

getShipment(uint shipmentId)
