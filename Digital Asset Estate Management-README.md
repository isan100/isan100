# 🧬 Web3 Digital Inheritance on ICP

A blockchain-based application that enables secure and automated transfer of digital assets to rightful beneficiaries upon confirmation of the owner's death—leveraging Internet Computer Protocol (ICP), smart contracts, multisig access control, and oracle-based verification.

## 🌐 Project Description

This dApp empowers users to:

- Create legally structured **digital wills**
- Register and manage **digital assets**
- Link their identity to a **national ID registry**
- Implement **multisignature redundant key access** involving the user, executor, and backup
- Store sensitive credentials and documents in an **access vault** with programmable or time-locked logic
- Trigger **asset distribution automatically** upon death verification via oracle or government registry.

---

## 🧩 Modules

### 1. Digital Will
Create and update a digital testament with defined beneficiaries and asset allocations.

### 2. National ID Registry Integration
Links a user’s identity to an official government-issued national ID system for legal authentication.

### 3. Asset Register
Users register and track all digital assets—wallets, tokens, NFTs, credentials, etc.—with metadata.

### 4. Multisig Key Management
Implements a 3-party signing model involving:
- The user (owner)
- The executor (trusted individual or institution)
- A backup/recovery agent (e.g., legal guardian or automated fallback)

### 5. Access Control Vault
A secure vault for storing sensitive credentials, documents, or asset access keys, with unlock conditions such as:
- Date/time unlock
- Death confirmation
- Multisig authorization

---

## 🛠 Tech Stack

- **Blockchain Platform:** [Internet Computer Protocol (ICP)](https://internetcomputer.org)
- **Smart Contract Language:** Motoko
- **Frontend:** HTML/CSS/JS (expandable to React/Svelte)
- **Oracle Integration:** Chainlink-compatible or mock service (in development)
- **Identity Management:** Internet Identity (II) integration planned

---

## 🚀 Getting Started

### Prerequisites

- [DFINITY SDK (DFX)](https://smartcontracts.org/docs/quickstart/quickstart.html)
- Git
- Node.js (for frontend if extended)

### Clone & Deploy Locally

```bash
git clone https://github.com/your-username/digital-inheritance-icp.git
cd digital-inheritance-icp
dfx start --background
dfx deploy
```

---

## 📁 Directory Structure

```
.
├── dfx.json                    # Canister configuration
├── motoko/                     # Smart contract source files
│   ├── digital_will.mo
│   ├── national_id.mo
│   ├── asset_register.mo
│   ├── multisig_manager.mo
│   └── access_vault.mo
├── src/frontend                # (Optional) Frontend app folder
│   └── index.html
└── README.md                   # Project documentation
```

---

## 🧠 Future Features

- ✅ Oracle-based **death verification** integration
- ✅ Triggered asset transfer with **proof-of-death**
- 🔒 Zero-knowledge proof integration for privacy
- 💼 DAO governance support for estate executors
- 📱 Mobile access with biometric verification
- ✉️ Notifications system (email/SMS for beneficiaries)
- 📜 Legal compliance and smart will certification

---

## 🤝 Contributing

We welcome contributions to improve functionality, security, and interoperability with legal systems. To contribute:

```bash
git checkout -b feature/my-feature
git commit -am 'Add my feature'
git push origin feature/my-feature
```

Then submit a Pull Request.

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- [DFINITY Foundation](https://dfinity.org)
- [Chainlink Oracles](https://chain.link)
- [Motoko Language](https://smartcontracts.org/docs/language-guide/motoko.html)
- All contributors and early adopters building the future of decentralized inheritance

---
