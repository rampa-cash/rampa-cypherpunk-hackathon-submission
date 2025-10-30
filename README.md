# 🪙 Rampa — Cypherpunk Hackathon 2025 Submission 🚀

**Rampa** is our submission for the **Colosseum's Cypherpunk Hackathon 2025**.  
It’s a **decentralized remittance platform built on Solana**, designed to make cross-border transfers as easy as sending a message — simple, secure, and crypto-powered under the hood.

Rampa enables users to:
- 🌍 On-ramp fiat into stablecoins (USDC/EURC)
- 💸 Send and receive stablecoins using the power of Solana!
- 🏦 Off-ramp to local currencies in the recipient's country
- 🔒 Abstract away crypto complexity through a smooth, user-friendly UX

---

## 🔗 Links & Social Media

- 🌐 **Website:** [rampa.cash](https://rampa.cash)
- 📘 **Facebook:** [facebook.com/go.rampacash](https://www.facebook.com/go.rampacash)
- 📷 **Instagram:** [instagram.com/rampa.cash](https://www.instagram.com/rampa.cash)
- 💼 **LinkedIn:** [linkedin.com/company/rampa-cash](https://www.linkedin.com/company/rampa-cash/)
- 🐦 **X (Twitter):** [x.com/rampa_cash](https://x.com/rampa_cash)

---

## 🧩 Architecture Overview

Rampa is composed of multiple repositories, each responsible for a specific layer of the stack:

### **1. Backend API**
Handles all **core business logic**, **data persistence**, and **blockchain interactions**.

- Integrates with **Solana** to manage wallets and on-chain transactions  
- Exposes REST endpoints for the frontend and mobile apps  
- Manages fiat ↔ crypto operations and transaction metadata  
- Stores user and transaction data securely in the database  

👉 [rampa-cash-api](https://github.com/rampa-cash/rampa-cash-api)

---

### **2. Web App (Landing Page)**
A simple **landing page** that introduces Rampa and explains its vision.

- Serves as an informational front for users 
- Describes the core idea, problem, and proposed solution  
- Will later evolve into a full user-facing web dashboard  

👉 [rampa-cash-web](https://github.com/rampa-cash/rampa-cash-web)

---

### **3. Mobile App (Kotlin)**
The current **Android-only app**, providing a native experience to end users.

- Implements wallet creation, authentication, and transfers  
- Fully integrates with the backend and Solana  
- Used as the initial MVP to validate the user experience  

👉 [rampa-cash-mobile](https://github.com/rampa-cash/rampa-cash-mobile)

---

### **4. Mobile App (React Native — Next-Gen)**
We are transitioning to a **React Native** app for the following reasons:

1. 📱 **Cross-platform availability** — Launch on **iOS and Android** from day one  
2. 🔗 **MPC Wallet Migration** — Move from **Web3Auth** to **Para SDK**, which currently supports only React Native  
3. ⚡ **Faster iteration and unified codebase** for mobile development

This version will become our main mobile client moving forward.

👉 [rampa-app](https://github.com/rampa-cash/rampa-app)

---

## ⚙️ Setup Instructions

Each repository contains its own setup and environment configuration details.

To run the full stack locally:
1. **Clone and start** the backend API (`rampa-cash-api`)
2. **Run** the web app (`rampa-cash-web`)
3. **Launch** the mobile app (`rampa-cash-mobile`) or try the new React Native app (`rampa-app`)

---

## 🏗️ Tech Stack

- **Solana** — blockchain layer for remittance operations  
- **Para SDK** — MPC wallet management (React Native integration)  
- **Node.js / NestJS** — backend API  
- **PostgreSQL** — database  
- **NextJS / Kotlin / React Native** — frontends  
- **Docker** — containerized services  

---

## 🎥 Demo & Materials

- 🎬 [Demo video](https://youtu.be/htyF1RL2hms)  
- 🖼️ [Pitch deck](https://youtu.be/RhoQbIFk3dQ)

---

## 💡 Vision

Rampa aims to make decentralized remittances **as intuitive as traditional fintech apps**, while preserving the benefits of **self-custody, transparency, and borderless access**.

---

🛠️ Built with care by the **Rampa Team** for the **Cypherpunk Hackathon 2025**.