# Swype — FAQ
## For friends, community, press inquiries

---

## What is Swype?

Swype is a swipe-to-trade leveraged perpetual trading app built for Solana Seeker. You pick a coin, swipe right to go long or left to go short, choose your leverage and size, and trade plays out over 30 seconds to 5 minutes depending on your tier.

---

## How does it work?

1. Connect your Seed Vault wallet (Solana Seeker)
2. Pick your tier: Chill (10x, 5min), Degen (50x, 60s), Retard (100x, 30s)
3. Swipe cards — trending coins appear as trading cards
4. Swipe right = long, swipe left = dismiss
5. Confirm leverage and size in the modal
6. Watch the live trade view — chart, countdown, PnL
7. Auto-close at deadline — win or lose, it just ends

---

## Is this real trading?

Right now: paper trading. No SOL actually moves — the program records the math but there's no real PnL settlement. The UX and on-chain execution are real, but the economics are simulated.

Full Jupiter Perps integration is coming, which would bring real economic execution.

---

## Is this gambling?

Everything in crypto is gambling if you want to be reductive about it. Swype doesn't pretend to be anything other than what it is — a fast, time-gated trade with leverage. Use responsibly.

---

## Do I need a Seeker phone?

Right now yes — Swype is built for the Solana Seeker dApp store. It won't work on iOS, Android, or web.

---

## Does Swype hold my funds?

No. Swype never touches your funds. You connect via Seed Vault (Mobile Wallet Adapter), sign with your wallet directly. Swype's program is non-custodial — it can't move your SOL.

---

## What's the session key thing?

Session keys let you trade without signing a popup for every transaction. You sign once when you open a session (4 hours / up to 100 trades), and the session key handles the rest. It's how Swype achieves zero-popup-per-trade.

---

## What's MagicBlock?

MagicBlock Ephemeral Rollups handle the execution speed. Instead of waiting ~400ms for devnet confirmation, the ER gives sub-100ms finality. This is what makes "swipe and it's done" actually feel fast on-chain.

---

## Can I close early?

No — and that's intentional. Trades are time-gated. You commit to the duration when you open. No tap-to-close, no second-guessing. It's part of the product identity.

---

## What's the limit?

Currently single-position only. One trade at a time per wallet. When you close, you're free to open again.

---

## What's the max I can lose?

Your balance is simulated right now. When real trading goes live, the tier system sets caps:
- Chill: max 10x leverage, max 10% of balance per trade
- Degen: max 50x, max 50% of balance
- Retard: max 100x, max 100% of balance

The program doesn't prevent you from losing more than your balance in a trade — that's a known gap for the full mainnet build.

---

## Are you a financial advisor?

No. Don't listen to me.

---

*Last updated: 2026-05-19*