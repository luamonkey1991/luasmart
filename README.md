# 🗳️ Lua Smart – Private Voting Example with FHE (Simulated)

This project is a demo of privacy-preserving voting using a simplified form of Fully Homomorphic Encryption (FHE). It simulates encrypted votes on-chain and decrypts them off-chain using a simple SDK.

## 🧩 Features

- Solidity smart contract to store encrypted votes
- TypeScript SDK for (fake) encryption/decryption
- Hardhat script and test file for demonstration

## 🚀 Quick Start

```bash
git clone https://github.com/YOUR_USERNAME/lua-smart-vote.git
cd lua-smart-vote
npm install
npx hardhat compile
npx hardhat test
npx hardhat run scripts/vote.ts
```

## 📂 Project Structure

- `contracts/PrivateVoting.sol`: Core smart contract
- `sdk/`: Encryption/decryption helpers
- `scripts/vote.ts`: Submit an encrypted vote
- `test/voting.test.ts`: Full test case with decrypt

---

🔐 *Note: FHE logic is simulated for demo purposes. This repo is intended for educational use only.*
