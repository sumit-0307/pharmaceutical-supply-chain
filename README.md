# 💊 Pharmaceutical Supply Chain

A decentralized pharmaceutical supply chain tracking system powered by **Ethereum smart contracts**, **MetaMask**, **React.js**, and **Web3.js**. The system ensures full traceability of drugs from raw material suppliers to end retailers, preventing counterfeit products and ensuring transparency at every stage.

---

## 🚀 Overview

This dApp (Decentralized Application) simulates a supply chain with key participants:

- 🧪 **Raw Material Supplier**
- 🏭 **Manufacturer**
- 🚚 **Distributor**
- 🏪 **Retailer**

Each role is assigned and authenticated via Ethereum accounts using **MetaMask**. Transactions and product flows are handled by smart contracts deployed on a local Ethereum blockchain (Ganache).

---

## 🛠️ Tech Stack

| Layer       | Technology                                 |
|-------------|---------------------------------------------|
| Frontend    | React.js, HTML, CSS                        |
| Wallet      | MetaMask (Ethereum wallet extension)       |
| Blockchain  | Ethereum, Solidity, Web3.js, Ganache       |
| Contracts   | Deployed via Truffle                       |
| Communication | Web3.js → Smart Contracts                |

---

## 📸 Key Features

- 🎭 **Assign Roles**: Use MetaMask to assign supply chain roles (RMS, MAN, DIS, RET)
- 🔐 **MetaMask Integration**: Secure transaction signing and authentication
- 🧾 **Smart Contract Interactions**: Create & track product batches
- 🔗 **Blockchain Storage**: Immutable tracking of all supply chain events
- 🔍 **Real-time Role-Based View**: See different data based on logged-in Ethereum account

---

## ⚙️ Getting Started

### ✅ Step 1
Open ganache UI/cli and configure truffle-config.js file. Not required for most cases.

### ✅ Step 2
Import the ganache local blockchain accounts in metamask using the mnemonic provided.

### ✅ Step 3
Clone the repo 
```bash
git clone https://github.com/sumit-0307/pharmaceutical-supply-chain.git
cd pharmaceutical-supply-chain
```

### ✅ Step 4
Compile and deploy the smart contract
```bash
npx truffle compile
npx truffle migrate
```
NOTE: If you make changes in the smart contract you have to redeploy it using npx truffle migrate --reset

### ✅ Step 5
Install node_modules using yarn
```bash
cd client
yarn
```
Install node_modules using npm
```bash
cd client
npm install
```
### ✅Step 6
Start the development server using yarn
```bash
yarn start
```
Start the development server using npm
```bash
npm start
```
The site is now running at http://localhost:3000! Open the source code and start editing!
