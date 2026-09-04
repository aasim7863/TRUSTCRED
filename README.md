# TrustCred 🔗

A blockchain-based credential verification platform built on **Ethereum/Solidity**. TrustCred allows institutions to issue tamper-proof academic and professional credentials, and lets anyone verify their authenticity on-chain — no intermediaries, no forgeries.

## ✨ Features

- **Tamper-proof issuance** — Credentials are recorded on the Ethereum blockchain via smart contracts, making them immutable once issued.
- **Instant verification** — Anyone can verify a credential's authenticity without contacting the issuing institution.
- **Decentralized trust** — Removes reliance on centralized databases that can be altered or lost.
- **Smart contract-based access control** — Only authorized issuers (institutions) can mint new credentials.

## 🛠️ Tech Stack

- **Blockchain:** Ethereum
- **Smart Contracts:** Solidity
- *(Add your specific frameworks here, e.g. Hardhat/Truffle, Web3.js/Ethers.js, React frontend, etc.)*

## 📦 Getting Started

### Prerequisites

- Node.js and npm
- Hardhat or Truffle (for compiling/deploying contracts)
- MetaMask (or another Web3 wallet)

### Installation

```bash
git clone https://github.com/aasim7863/trustcred.git
cd trustcred
npm install
```

### Compile & Deploy Contracts

```bash
npx hardhat compile
npx hardhat run scripts/deploy.js --network <your-network>
```

### Run Locally

```bash
npm start
```

## 📖 How It Works

1. An authorized institution issues a credential by calling the smart contract, which records a hash of the credential data on-chain.
2. The credential (or a QR code / link to it) is given to the recipient.
3. Anyone can verify the credential by querying the smart contract with the credential's identifier — confirming it was issued, by whom, and that it hasn't been tampered with.

## 🗺️ Roadmap

- [ ] IPFS integration for storing credential metadata
- [ ] Multi-institution support with role-based permissions
- [ ] Frontend dashboard for issuers and verifiers
- [ ] Mobile-friendly verification portal

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Aasim Ullah Khan**
- GitHub: [@aasim7863](https://github.com/aasim7863)
- LinkedIn: [aasim-ullah-khan](https://linkedin.com/in/aasim-ullah-khan-47b052271)
