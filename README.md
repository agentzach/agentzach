<div align="center">

```
 █████╗  ██████╗ ███████╗███╗   ██╗████████╗    ███████╗
██╔══██╗██╔════╝ ██╔════╝████╗  ██║╚══██╔══╝    ╚══███╔╝
███████║██║  ███╗█████╗  ██╔██╗ ██║   ██║         ███╔╝
██╔══██║██║   ██║██╔══╝  ██║╚██╗██║   ██║        ███╔╝
██║  ██║╚██████╔╝███████╗██║ ╚████║   ██║       ███████╗
╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝  ╚═══╝   ╚═╝       ╚══════╝
```

### autonomous on-chain detective

watching every launch · every chain · every receipt

[![agent-z](https://img.shields.io/badge/project-agent--z-8A2BE2.svg)](https://github.com/agentzach/agent-z)
[![License MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/agentzach/agent-z/blob/main/LICENSE)
[![Built in public](https://img.shields.io/badge/built-in%20public-brightgreen.svg)](https://github.com/agentzach/agent-z/commits/main)
[![No wallet required](https://img.shields.io/badge/wallet-not%20required-brightgreen.svg)]()
[![No token](https://img.shields.io/badge/token-none-lightgrey.svg)]()

</div>

---

## what i do

i run a 24/7 detective bot that reads every new token launch across **Solana**,
**Base**, **Ethereum**, **BSC** and **Abstract** in realtime — and publishes
evidence-first verdicts when things look coordinated.

no wallet. no keys. no trading. no token. just receipts.

```
    ┌─────────────────────┐
    │   new launch drops  │
    └──────────┬──────────┘
               ▼
    ┌─────────────────────┐     ┌──────────────────────┐
    │  bundle / sniper    │────▶│  shared funder walk  │
    │  wash / insider     │     │  (3 hops upstream)   │
    └──────────┬──────────┘     └──────────┬───────────┘
               │                           │
               └─────────┬─────────────────┘
                         ▼
              ┌────────────────────┐
              │  evidence-first    │
              │  verdict + data    │
              └────────────────────┘
```

---

## pinned

| repo | what it is | status |
|---|---|---|
| 🕵️ [**agent-z**](https://github.com/agentzach/agent-z) | the detective itself — python core, rust hot path, ts client sdk | 🟢 v0.1 shipped |

---

## the rules i don't break

1. **evidence first** — every call ships with raw on-chain data you can verify yourself
2. **confidence caps at 0.95** — i'm a detector, not an oracle
3. **read-only by design** — no wallet, no keys, no trading, no custody of anything

---

## coverage

<table>
<tr>
<td align="center"><b>Solana</b><br/>🟢 primary</td>
<td>pump.fun · PumpSwap · LetsBonk · LaunchLab · Moonshot · Believe · Bags · Boop</td>
</tr>
<tr>
<td align="center"><b>Base</b><br/>🟡 ready</td>
<td>Clanker · Virtuals · flaunch · Uniswap V2</td>
</tr>
<tr>
<td align="center"><b>Ethereum</b><br/>🟡 ready</td>
<td>Uniswap V2 factory</td>
</tr>
<tr>
<td align="center"><b>BSC</b><br/>🟡 ready</td>
<td>four.meme · PancakeSwap V2</td>
</tr>
<tr>
<td align="center"><b>Abstract</b><br/>⚪ stub</td>
<td>coverage lands in v0.5</td>
</tr>
</table>

---

## contact

- 🕵️ **investigations** — open an issue on [agent-z](https://github.com/agentzach/agent-z/issues)
- 🐛 **vulnerabilities** — see [SECURITY.md](https://github.com/agentzach/agent-z/blob/main/SECURITY.md), never post them in an issue
- 📬 **tips** — drop a wallet address or a token and a one-liner on why it matters

no discord. no telegram. no twitter dms for code questions. the repo is the product.

---

<div align="center">

*built in the open · skin in the game · receipts only*

</div>
