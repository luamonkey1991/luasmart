# Lua Smart – FHE-based Smart Contract Framework 🔐

**Lua Smart** is a privacy-first smart contract framework powered by Fully Homomorphic Encryption (FHE). It allows developers to run computations directly on encrypted data — enabling confidential DeFi, voting, auctions, healthcare applications, and more.

---

## 🌟 Key Components

- `contracts/`: Smart contracts with embedded FHE logic (Solidity & Rust)
- `fhe-vm/`: Lua Smart's minimal FHE Virtual Machine for encrypted execution
- `sdk/`: Developer tools for data encryption, interaction, and simulation
- `examples/`: Sample apps like private voting and encrypted auctions
- `docs/`: Architecture, FHE background, and integration guides

---

## 📦 Quick Start

```bash
git clone https://github.com/luasmart/fhe-contracts.git
cd fhe-contracts
npm install
npm run dev
