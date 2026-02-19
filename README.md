# Declaw 🦞

> Extensions for [OpenClaw](https://github.com/openclaw/) — expanding the lobster ecosystem into Web3, DeFi, and the open marketplace of AI skills.

---

## Vision

Declaw is a suite of open-source extensions built on top of the OpenClaw platform. Each project plugs directly into the Clawdbot skill system and extends its capabilities into decentralized identity, autonomous finance, and a permissionless skill marketplace.

---

## Projects

### 1. `clawid` — Decentralized Identity for Clawbots

**Claw Authentication Protocol via Crypto Wallet**

`clawid` implements a decentralized identity (DID) standard for the OpenClaw ecosystem, enabling Clawdbot users and agents to authenticate using their own crypto wallets — no centralized login required.

- **EVM compatible** — works with MetaMask, WalletConnect, and any EVM-compatible wallet
- **Solana compatible** — supports Phantom, Backpack, and Solflare
- **DID-based** — follows the W3C DID specification for self-sovereign identity
- **Skill-ready** — can be used by any Clawdbot skill to verify user identity or sign actions on-chain

---

### 2. `clawfi` — Autonomous DeFi Research & Trading Agent

**Let your Clawdbot manage your portfolio — autonomously.**

`clawfi` is a DeFi research and trading agent that lives inside OpenClaw. It continuously monitors financial products across the crypto ecosystem, performs autonomous research, and executes trades directly from wallet balances — all without manual intervention.

**Supported protocols & platforms:**
- 🟣 **Pump.fun** — token launches and bonding curves
- 📊 **DexScreener** — real-time DEX analytics and pair monitoring
- 🦄 **Uniswap** — AMM swaps and liquidity positions
- 🌊 **Meteora** — dynamic liquidity vaults on Solana
- 🔺 **Pendle** — yield trading and fixed-rate strategies
- 🟢 **Lido** — liquid staking (ETH → stETH)
- 👻 **Aave** — lending, borrowing, and yield optimization
- 🔵 **Compound** — money market protocol integration

**How it works:**
1. Clawfi monitors configured protocols on a schedule
2. It performs research using on-chain data + AI analysis
3. It proposes trades and optionally executes them autonomously
4. Full audit trail is logged locally for review

---

### 3. `clawfi-market` — The Skill Marketplace for Trading Strategies

**Buy, sell, and plug in trading strategies as Clawdbot skills.**

`clawfi-market` is a decentralized marketplace where anyone can publish, discover, and purchase trading strategies and DeFi skills — packaged as native Clawdbot skills that can be dropped directly into any Clawdbot instance.

- **Sell your edge** — package your trading strategy as a Clawdbot skill and monetize it
- **Buy alpha** — browse and install proven strategies from other builders
- **Plug-and-play** — every strategy is a fully compatible Clawdbot skill; install with one command
- **On-chain payments** — transactions settled via crypto wallet (EVM + Solana)
- **Reputation system** — strategies rated by community performance metrics

---

## Relationship to OpenClaw

```
OpenClaw (core)
    └── Clawdbot (agent runtime)
            ├── Skills (openclaw/skills)
            ├── ClaWhub (openclaw/clawhub)  ← skill directory
            └── Declaw Extensions
                    ├── clawid      ← identity layer
                    ├── clawfi      ← autonomous DeFi agent
                    └── clawfi-market  ← strategy marketplace
```

---

## Status

> 🚧 **Early planning stage.** All three projects are under active design.

| Project | Status |
|---|---|
| `clawid` | 📐 Design |
| `clawfi` | 📐 Design |
| `clawfi-market` | 📐 Design |

---

## License

MIT
