# Ergo-Skills

A repository for Ergo-based skills.

This project contains structured, agent-ready skill files designed to help AI systems and developer tools interact with the Ergo blockchain ecosystem.

Skills are modular knowledge + execution packets that define:

- Purpose
- Context
- Inputs
- Deterministic actions
- Structured outputs

The goal is to standardize how agents interact with Ergo nodes, wallets, transactions, and smart contracts.

---

## 📂 Structure

```
Ergo-Skills/
│
├── skills/
└── README.md
```

All skill definitions currently live inside the `skills/` directory.

---

## 🧠 Ecosystem Compatibility

Designed to integrate with:

- Nautilus Wallet
- Ergo WASM
- Ergo Appkit
- Ergo Node API
- Indexers and smart contract APIs

---

## 🛠 Skill Format

Each skill is written as a `.skill.md` file with clearly defined:

- Purpose  
- Inputs  
- Actions  
- Outputs  

Skills should remain deterministic, composable, and agent-safe.

---

## 🗺 Roadmap

- [ ] Core node interaction skills  
- [ ] UTXO selection & transaction construction  
- [ ] Nautilus signing workflows  
- [ ] Ergo WASM cryptographic operations  
- [ ] Appkit transaction builders  
- [ ] Token metadata resolution  
- [ ] DEX & DeFi interaction skills  
- [ ] Governance & DAO automation  
- [ ] Multi-sig & advanced wallet flows  
- [ ] Standardized JSON execution schema  

---

This repository is the foundation for structured, programmable intelligence on Ergo.
