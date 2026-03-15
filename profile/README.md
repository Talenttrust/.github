# TalentTrust  
### Decentralized Freelancer Escrow Protocol

TalentTrust is a decentralized freelancer payment and reputation protocol built on the **Stellar network**.  
It enables secure escrow payments, milestone-based contracts, and **portable reputation identity** for freelancers.

Unlike traditional freelance marketplaces, TalentTrust does not lock freelancers into a single platform. Instead, it provides an **open infrastructure layer** where freelancers own their work history and reputation.

The protocol significantly reduces fees, improves cross-border payments, and allows reputation to move freely across different marketplaces and hiring platforms.

---

## 1. Problem

The global freelance economy is growing rapidly, but existing platforms introduce major limitations.

| Problem | Impact |
|---------|--------|
| High platform fees | Upwork and Fiverr take 20–30% |
| Platform lock-in | Freelancers lose reputation when switching platforms |
| Cross-border payment delays | Payments take several days |
| Dispute resolution inefficiency | Centralized decision making |
| Lack of ownership | Freelancers do not own their reputation data |

Freelancers depend heavily on centralized platforms, which control payments, reputation, and client access.

The **global freelance economy exceeds $455B annually** and continues to grow.

---

## 2. Solution

TalentTrust provides a **decentralized escrow and reputation protocol** built on the Stellar blockchain.

### Core Concepts

1. Clients deposit funds into a smart contract escrow.
2. Work is delivered by freelancers.
3. Payments are released automatically.
4. Reputation credentials are issued as **tokenized digital identity records**.

This enables:

- secure escrow payments
- portable freelancer reputation
- milestone-based work contracts
- borderless payments

---

## 3. Key Features

### Decentralized Escrow

Payments are held in **smart contract escrow** until work is completed.

### Portable Reputation Identity

Freelancers receive **reputation credentials** representing their work history. These credentials can be used across freelance marketplaces, DAO work platforms, hiring systems, and professional networks.

### Milestone-Based Payments

Projects can be split into milestones. Payments are automatically released as milestones are completed.

### Cross-Border Payments

Stablecoin-based payments enable **instant global payments**.

---

## 4. Why Stellar

TalentTrust uses the **Stellar network** for its global payment capabilities.

| Feature | Benefit |
|---------|---------|
| Ultra low transaction fees | Ideal for freelancer payments |
| Fast settlement | Payments confirm in seconds |
| Stablecoin ecosystem | Enables global payments |
| Asset issuance | Used for credentials and reputation |
| Global accessibility | Borderless infrastructure |

---

## 5. Repository Structure

| Repository | Description |
|------------|-------------|
| [talenttrust-frontend](talenttrust-frontend/) | Next.js web app and dashboard |
| [talenttrust-backend](talenttrust-backend/) | Express API and services |
| [talenttrust-contracts](talenttrust-contracts/) | Soroban smart contracts on Stellar |

Each sub-project has its own git history, CI/CD, and contributor onboarding in its README.

---

## 6. Tech Stack

- **Frontend:** Next.js, React, TailwindCSS, Stellar wallet integration
- **Backend:** Node.js, Express, REST APIs
- **Blockchain:** Stellar Network, Soroban smart contracts, Stellar SDK, Horizon API
- **Infrastructure:** Docker, PostgreSQL, Redis

---

## License

MIT
