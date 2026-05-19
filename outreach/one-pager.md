# Swype — One-Pager
## For partners, press, and potential collaborators

---

## What is Swype?

Swype is the fastest way to trade crypto on Solana — a Tinder-style swipe-to-trade leveraged perp app built for the Solana Seeker phone. Users pick a coin, swipe to choose direction, and watch a time-gated trade play out in real-time. Zero order books, zero complexity, just swipe.

**Pitch:** "3 swipes from idea to position."

---

## The Product

- **Swipe card UX** — coins presented as cards, swipe right = long, swipe left = dismiss
- **Time-gated positions** — 30s / 60s / 5min auto-close depending on tier
- **Three tiers:** Chill (10x, 5min) / Degen (50x, 60s) / Retard (100x, 30s)
- **Zero popup trading** — session keys eliminate per-trade wallet confirmations
- **Sub-100ms execution** — MagicBlock Ephemeral Rollups
- **Non-custodial** — Seed Vault wallet, Swype never touches funds

---

## Why it matters

Mobile DeFi has a UX problem. Every trade requires wallet popups, order book navigation, and complexity that makes the average user feel like they're doing surgery. Swype strips all of that away.

**The insight:** trading doesn't need to be complicated. It needs to be fast, legible, and fun. Swipe is the interaction model that makes that work on a phone screen.

---

## Target user

18-35, crypto-curious but not necessarily deep into DeFi. Uses their phone in quick bursts — subway, bathroom, coffee line. Wants the feeling of trading without the overhead. Uses Solana because it's fast and cheap enough to make short-session trades viable.

---

## Current status

- Devnet complete with real on-chain txs via MagicBlock ER
- Session key flow verified on Solana Seeker hardware
- Paper trading (simulated PnL) — no SOL moves yet
- Jupiter Perps integration in progress (active development)

---

## Tech stack

- **Frontend:** Expo SDK 51, React Native 0.74.5, TypeScript, Zustand
- **On-chain:** Anchor 0.32.1, MagicBlock Ephemeral Rollups, Solana Mobile MWA
- **Execution:** Session keys (ephemeral keypairs, 4h lifetime, 100-trade cap)
- **Price feeds:** Pyth Hermes REST

---

## What makes this defensible

1. **Novel UX shape** — no one else is doing swipe-to-trade leveraged perps on mobile
2. **Session key architecture** — zero-popup trading on mobile is technically non-trivial; the implementation is the moat
3. **Mobile-first from day one** — most DeFi is web-first with mobile bolted on; Swype is built for the device

---

## What's next

- Jupiter Perps integration → real economic execution
- Mainnet deployment
- Social layer (leaderboards, achievements)
- Geo-blocking + compliance for regulated markets

---

## Who built it

0xnoot — fullstack dev, crypto gaming / Solana. Building One Arena (Solana TCG/gacha) and now Swype as a parallel project exploring mobile-first quick-session trading.

---

*For questions: 0xnoot@gmail.com*
*Swype — trade crypto in 3 swipes*