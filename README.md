# 🚀 Web3 Full-Stack Crypto DApp

This is a full-stack decentralized application (DApp) built with **Next.js**, **Hardhat**, and **Ethers.js**. It includes a custom ERC20 token and a frontend to interact with the blockchain.

## 🛠 Tech Stack

- **Frontend**: Next.js, Tailwind CSS, Shadcn UI
- **Blockchain**: Solidity, Hardhat, Ethers.js
- **Wallet Connection**: RainbowKit / Wagmi
- **Network**: Ethereum (Sepolia Testnet / Localhost)

## 📁 Project Structure

- `packages/blockchain`: Smart contracts, deployment scripts, and tests.
- `packages/frontend`: Next.js application to interact with the contract.

## 🚀 Getting Started

### 1. Smart Contract Setup
```bash
cd packages/blockchain
npm install
npx hardhat compile
# Run a local node
npx hardhat node
# Deploy locally
npx hardhat run scripts/deploy.js --network localhost
