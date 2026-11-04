# 🛠️ Phase 2: Engineering the Cure

### *A blockchain-based escrow system that automatically refunds customers when deliveries fail*

[← Back to Main Project](../README.md) · [← Phase 1: The Problem](../01-phase-1-olist-web2-analysis/)

---

> **Status: 🟡 Planned** — This phase will begin after completing Phase 1 and learning Solidity fundamentals.

## 🎯 Objective

Based on Phase 1 findings, design and simulate a **Smart Contract escrow** that:

- Holds payment in escrow until delivery is confirmed
- **Auto-refunds** if delivery exceeds the estimated date
- Provides transparent, immutable transaction records
- Eliminates manual dispute resolution

## 🔗 Why This Phase Exists

Phase 1 revealed that the centralized Olist system suffers from:
- Delivery delays causing customer distrust
- Opaque logistics with no real-time accountability
- Slow or absent refund processes for failed deliveries

**Blockchain escrow solves this** by encoding trust rules directly into code.

## 🏗️ Planned Architecture

```
Customer pays ──▶ 💰 Escrow Contract ──▶ Delivery confirmed? 
                                            │
                                     ┌──────┴──────┐
                                     │             │
                                   ✅ Yes        ❌ No / Late
                                     │             │
                              Release to      Auto-refund to
                                Seller          Customer
```

## 🔧 Tech Stack *(to learn)*

- **Solidity** — Smart contract language
- **Hardhat** — Development environment & local blockchain
- **Python + web3.py** — Simulation scripts
- **BigQuery data** — 50 failed orders from Phase 1 as test input

## 📂 Structure *(will be expanded)*

```
phase-2-web3-escrow-solution/
├── README.md            ← You are here
├── context/             ← Problem statement from Phase 1
├── contracts/           ← Solidity smart contracts
├── scripts/             ← Python simulation scripts
├── test/                ← Contract unit tests
└── findings/            ← Simulation results
```

## ➡️ Next

> *With the escrow solution designed and tested, Phase 3 examines real Ethereum data to validate cost-effectiveness and scalability.*

**[→ Continue to Phase 3: On-chain Analysis](../03-phase-3-ethereum-onchain-analysis/)**
