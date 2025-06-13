
# 🧠 Proof-of-Play Consensus Protocol (PoPX Protocol)

> **The Consensus Engine of Verified Competition**  
> “If it wasn’t PoP-CP, it didn’t really happen.”

## 🎮 Overview

**PoPX Protocol** is a decentralized, verifiable consensus framework built to authenticate gameplay, validate outcomes, and immutably record competitive interactions. Whether between humans, AI agents, or hybrids — if there are stakes, reputation, or rewards involved, PoP-CP ensures the result is provable, tamper-proof, and trustworthy.

Designed originally for **ChessGrid0x**, this protocol can power any game, sport, or agentic task system where **truth matters**.

---

## 📁 What It Does

- ✅ Verifies match authenticity (human or agent)
- ✅ Generates `.popcp` proof files of play
- ✅ Updates player reputation via the **Monetized Truth Protocol (MTP)**
- ✅ Anchors verified matches to **GenesisGrid**
- ✅ Enables staking, dispute resolution, and token rewards

---

## 🔐 Core File: `.popcp`

Each verified match outputs a `.popcp` file containing:
- Player identities & signatures
- Moveset hash (e.g., chess PGN)
- Timestamped result
- Reputation updates (MTP delta)
- GenesisGrid anchor (IPFS CID or similar)

View an [example `.popcp` file ➜](./examples/sample.popcp.json)

---

## 🧱 Architecture

```mermaid
graph TD
    A[Play Match] --> B[Verify Identity (zkID/PlayCard0x)]
    B --> C[PoP-CP Engine]
    C --> D[Generate .popcp]
    D --> E[MTP Score Updated]
    D --> F[Anchor to GenesisGrid]
    F --> G[Claim Rewards or Distribute NFTs]
```

---

## ⚒️ Use Cases

| Context | Application |
|--------|-------------|
| 🎮 Esports & Gaming | Match verification, leaderboard validation |
| 🤖 AI Agent Leagues | Prove autonomous agent participation |
| 🧑‍⚖️ Dispute Systems | Settle outcomes based on consensus proof |
| 💸 Wagering / Betting | Oracle-compatible game result feeds |
| 🏆 Tournament Prizes | Token rewards or NFTs triggered by `.popcp` |

---

 Quick Start

```bash
npm install popcp-sdk
```

```ts
import { generatePopcp } from 'popcp-sdk'

const popcp = generatePopcp(matchData)
```

---

## 📦 SDK Structure

- `src/` – Core logic for match verification & `.popcp` generation
- `examples/` – Demo match files and validation scripts
- `docs/` – MTP + GenesisGrid + staking integration
- `tests/` – Full coverage of validator logic

---

## 🌐 Ecosystem Integrations

- ✅ GenesisGrid – Immutable anchor layer
- ✅ MTP – Reputation & trust scoring
- ✅ TradeTag – Embedded task/transaction context
- ✅ PlayCard0x – Player identity & wallet binding
- ✅ `.popcp` – Open file format for match receipts

---

## 🔖 Keywords
`proof-of-play` `agentic-consensus` `gaming-protocol` `match-verification` `mtp` `genesisgrid` `playcard0x` `popcp` `trust-mining` `veriplay`

---

Built By
RealWorldNative |originator: robertanderson.nft 2025
_Truth-first infrastructure for agentic systems._  
[realworldnative.eth](https://realworldnative.eth) | [@realworldnative](https://twitter.com/realworldnative)

---
 License
MIT – Use it, fork it, verify everything.

---

Would you like to verify a match, stream it, mine trust, and claim your `.popcp`?  
📩 Get started today.
