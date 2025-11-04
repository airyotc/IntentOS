# IntentOS

Open-source OS for AI-powered intents on Base. Turning "what I want" (e.g., max yield) into 1-click on-chain reality. Fork of SUAVE + Anoma integration with Grok solvers for seamless cross-chain execution.

[![Base](https://img.shields.io/badge/Chain-Base-blue)](https://base.org) [![SUAVE](https://img.shields.io/badge/Fork-SUAVE-orange)](https://github.com/flashbots/suave-geth) [![License](https://img.shields.io/badge/License-LGPL--3.0-blue.svg)](https://opensource.org/licenses/LGPL-3.0)

## Why IntentOS?
Crypto UX sucks: 7 steps for a yield farm. We fix it with intents—signed goals solvers fulfill atomically. Diff from HeyElsa: Open protocol (not app), AI-competitive (Grok paths), zk-optional privacy. MVP: "Max Yield <5% Risk" ($1K USDC → Arbitrum stake, 18% APY target).

## Tech Stack
- **Chain**: Base (EVM L2, $0.01 txs, Coinbase ecosystem)
- **Intents**: ERC-7683 (signed orders) + Anoma (privacy OS)
- **Solvers**: SUAVE mempool fork + Grok AI (path sims via xAI API)
- **Execution**: Across V3 bundles (ETH → Base → Arbitrum)
- **Frontend**: React + Wagmi (1-click signing)
- **ZK (Optional)**: RISC Zero for verifiable fills

## 90-Day Roadmap
| Phase | Timeline | Milestones |
|-------|----------|------------|
| **0: Prep** | Now | Repo fork, X outreach, env setup |
| **1: Build** | Nov-Dec | Intent signing, AI solver, atomic exec |
| **2: Test** | Dec-Feb | 10K Base testnet txns, beta airdrop |
| **3: Scale** | Feb-Mar | Phantom embed, $500K pre-seed |

## Quickstart (Base Testnet)
1. **Clone & Install**:
2. 2. **Test Intent**:
- Faucet: [Base Sepolia](https://sepoliafaucet.base.org)
- Run: `npm start` → Sign dummy ERC-7683 order
3. **Dev on Base**: Use Wagmi for RPC: `https://sepolia.base.org`

## Collab & Next
- **Devs/Solvers**: PRs for Anoma adapters or Grok prompts. Issues for bugs.
- **Beta Testers**: DM on X airyotc for early access.
- **Roadmap Board**: [Notion Link] (create & add).
- **License**: LGPL-3.0 (fork-friendly).
