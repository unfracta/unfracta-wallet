# Unfracta Wallet

**Quantum-Resistant Wallet UI – Built for Today and Tomorrow**

Unfracta Wallet is the front-end interface for the Unfracta cryptographic SDK. Built in React (with TypeScript and Vite), it provides a simple, modern user interface for generating key pairs, signing messages, verifying signatures, and managing hybrid (classical + quantum) credentials.

---

## 🔐 Core Capabilities

- Generate Dilithium keypairs (post-quantum)
- Generate ECDSA keypairs (secp256k1)
- Sign messages with either or both
- Verify signatures
- Display QR code or copy-paste compatible outputs
- Prepare payloads for L2/DAO/validator tooling

---

## 🧱 Tech Stack

- **React** + **TypeScript**
- **Vite** for fast dev and build
- **Tailwind CSS** (planned) or Shadcn/UI
- Integrates with [unfracta-sdk](https://github.com/unfracta-io/unfracta-sdk) via local API bindings or WASM

---

## 🛠️ Getting Started

```bash
npm create vite@latest unfracta-wallet -- --template react-ts
cd unfracta-wallet
npm install
npm run dev

