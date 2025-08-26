# 🗝️ Treasure DAO Hunt – Proof of Concept

**Treasure DAO Hunt** is a **community-driven treasure hunt game** powered by a DAO (Decentralized Autonomous Organization).  
Players solve clues, submit answers, and collectively decide the next steps of the quest through DAO voting. Rewards are distributed on-chain to successful hunters.

This Proof of Concept (PoC) demonstrates the core mechanics of a **community-governed game flow** with on-chain rewards.

---

## ✨ Key Features
- 🔍 **Clues & Puzzles** – Players receive and solve challenges.
- ✅ **Answer Submission** – Answers are verified by a smart contract.
- 🪙 **On-Chain Rewards** – Successful players receive tokens or NFT badges.
- 🗳️ **DAO Voting** – Community votes to decide the direction of the next quest.

---

## 🛠 Tech Stack
- **Smart Contracts** – Solidity (Hardhat/Foundry)
- **Frontend** – React + Tailwind
- **Blockchain Interaction** – Ethers.js / Web3.js
- **Testing** – Hardhat/Foundry test suite

---

##  Getting Started

## 1. Clone the Repository
```
git clone https://github.com/Kaelvnode/treasure-dao-hunt.git
cd treasure-dao-hunt-poc
```
## Install Dependencies
```
npm install
```
## Deploy Contracts (Testnet)
```
npx hardhat run scripts/deploy.js --network testnet
```
## Run Frontendcd frontend
```
cd frontend
npm install
npm run dev

```
Open http://localhost:3000 in your browser.

## 🧪 How to Test

- Open the dApp.

- View the first clue.

- Submit an answer → contract verifies it.

- If correct, you receive a reward (token/NFT).

- DAO members can vote on the next clue or quest direction.

## 📌 Roadmap

 - Basic treasure hunt flow (clue → answer → reward)

 - DAO voting integration

 - Token/NFT reward system

 - Enhanced UI/UX with multiple quests

 ## 📜 License

MIT License © 2025 Treasure DAO Hunt Contributors
