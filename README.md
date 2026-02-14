# Main
Home of DMND1, DMND5, DMND 10 Project Files 
# The Diamond Standard
### Fiat Inflates — Diamonds Harden

### DMND1 / DMND5 / DMND10

---

## Abstract

The Diamond Standard (DMND protocol — DMND1 / DMND5 / DMND10) is a decentralized monetary system designed to introduce a **hard-backed, non-inflationary digital asset** with an **on-chain redeemable floor**.

Unlike fiat currencies that expand supply through discretionary issuance, the DMND ecosystem hardens over time through immutable rules, fixed supply, and mechanically enforced backing.

The DMND protocol does not rely on governance, emissions, or active management.  
It operates entirely through transparent smart contracts and market behavior.

The system consists of **three independent monetary tiers**:

- **DMND-1** — 1% exit friction  
- **DMND-5** — 5% exit friction  
- **DMND-10** — 10% exit friction  

Each tier represents a different balance between **liquidity, velocity, and long-term hardness**, allowing the market to choose which monetary profile it values.

---

## Core Thesis

Fiat currencies inflate.  
Scarce assets harden.

Bitcoin demonstrated that **fixed supply + credible immutability** creates a new monetary class.

The Diamond Standard (DMND protocol — DMND1 / DMND5 / DMND10) extends this idea by adding a **redeemable floor**, allowing value to harden not only through scarcity, but through **verifiable backing**.

No trust.  
No discretion.  
No governance.  

Only math.

---

## System Overview

Each tier in the DMND ecosystem consists of **two immutable smart contracts**:

1. **DMND Token**
2. **DMND Vault**

There are **no owner controls**, **no upgrade paths**, and **no parameter changes after deployment**.

All tiers operate independently.

---

## DMND Token

- Fixed total supply (50,000 tokens per tier)
- No minting
- No rebasing
- No governance
- No admin keys

### Fee Mechanics

- **Sell-side fee only**
- Fee applies **only when selling into the AMM**
- Buys and wallet-to-wallet transfers are fee-free
- Fees accumulate inside the token contract

### Fee Flow

1. Sell occurs  
2. Fee is retained in DMND  
3. Anyone may trigger conversion  
4. Fees are swapped for USDC  
5. USDC is sent directly to the Vault  

This ensures:

- Permissionless upkeep
- No custodians
- No trusted operators

---

## DMND Vault

The Vault holds **USDC reserves** backing the token.

It provides a **guaranteed redemption mechanism** for each tier within the DMND ecosystem.

### Redemption Formula 
USDC out = (DMND redeemed × Vault Balance) ÷ Total Supply



Key properties:

- Redemption is **available at all times**
- Redeemed tokens are burned permanently
- Remaining supply becomes harder
- Floor increases mechanically after every redemption

There are **no time locks**, **no windows**, and **no approvals required** beyond ERC-20 allowance.

---

## Floor Definition

The **floor** within the DMND protocol (DMND1 / DMND5 / DMND10) is defined as: Floor per DMND = Vault USDC ÷ Total Supply

Key properties:

- Redemption is **available at all times**
- Redeemed tokens are burned permanently
- Remaining supply becomes harder
- Floor increases mechanically after every redemption

There are **no time locks**, **no windows**, and **no approvals required** beyond ERC-20 allowance.

---

## Floor Definition

The **floor** within the DMND protocol (DMND1 / DMND5 / DMND10) is defined as: Floor per DMND = Vault USDC ÷ Total Supply

The floor:

- Is fully on-chain
- Is independently verifiable
- Cannot be manipulated by governance or admins

If market price ever drops below the floor, rational arbitrage incentivizes redemption.

---

## The Three Tiers

Each tier uses **identical code**, differing only by exit friction.

### DMND-1
- **1% sell fee (100 bps)**
- Lowest friction
- Highest velocity
- Comparable to: short-duration bonds / cash-like instruments

### DMND-5
- **5% sell fee (500 bps)**
- Moderate friction
- Stronger floor accumulation
- Comparable to: intermediate bonds / value assets

### DMND-10
- **10% sell fee (1000 bps)**
- Highest friction
- Maximum floor hardening
- Comparable to: long-duration hard assets / reserve instruments

No tier is “better.”  
The market chooses.

---

## Monetary Design Philosophy

Traditional systems rely on:

- Central banks
- Policy committees
- Discretionary supply changes

The DMND ecosystem relies on:

- Fixed supply
- Immutable contracts
- Market behavior
- Transparent math

There is no attempt to manage price.  
There is only a **mechanism that hardens value over time** if volume exists.

---

## Liquidity & Participation

- Anyone may add liquidity
- Anyone may redeem
- Anyone may trigger fee conversion
- No privileged roles
- No whitelists
- No exclusions

Participation is voluntary and permissionless across the DMND protocol.

---

## Security & Audits

- Contracts are immutable
- Audited source code is publicly available
- All tiers use identical logic
- No external dependencies beyond ERC-20 standards and canonical AMMs

Users are encouraged to:

- Verify contract addresses
- Review audit reports
- Read the code directly

---

## Name Clarification & Non-Affiliation

**The Diamond Standard (DMND protocol — DMND1 / DMND5 / DMND10)** is not affiliated with any other token, protocol, or project using similar names or tickers.

Names are not identifiers.  
**Contract addresses are.**

The canonical definition of the DMND ecosystem is:

- Verified contract addresses
- This repository
- Official documentation

---

## What the DMND Ecosystem Is Not

- Not a stablecoin
- Not a governance token
- Not a yield farm
- Not a meme coin
- Not a promise of price appreciation

The DMND protocol is a **monetary experiment**.

---

## Conclusion

When fiat inflates, savings decay.  
When supply is fixed and backing hardens, value consolidates.

The DMND ecosystem does not promise outcomes.  
It provides rules.

The market decides the rest.

---

**Fiat Inflates — Diamonds Harden**  
**The Diamond Standard (DMND protocol — DMND1 / DMND5 / DMND10)**

---

## License

MIT
