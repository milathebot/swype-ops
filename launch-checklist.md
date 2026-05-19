# Swype — Launch Readiness Checklist
## Solana Seeker dApp Store

---

## 1. dApp Store Listing

### App Metadata
- [ ] Name: "Swype" (confirm it's available on Seeker's store)
- [ ] Package ID: `com.swype.app`
- [ ] Category: Games / Casual / Trading
- [ ] Age rating: 17+ (gambling-adjacent, simulated)
- [ ] Short description (80 chars): "Swipe right to trade crypto. Done before your stop."
- [ ] Full description: see ~/.hermes/swype-ops/copy/store-description.md
- [ ] Demo video: user records on-device
- [ ] Screenshots: user takes on-device
- [ ] Keywords: solana, trading, crypto, leveraged, perp, swipe, game, mobile

### Screenshots
- [ ] Card stack showing an asset (BTC/SOL/MEME) with mini-chart
- [ ] Trade confirmation modal — leverage slider, size picker
- [ ] Live trade view — countdown ring, PnL chart, winning/losing moment
- [ ] Tier selection screen (chill/degen/retard)
- [ ] Profile/history screen
- [ ] 5-8 screenshots for the store listing
- [ ] Use rouge/azure/cyan palette — no neon green/yellow/purple

### Video (if supported)
- [ ] 15-30 second demo showing: card swipe → confirmation → live trade → result
- [ ] Demo uses real device footage if possible, not simulator
- [ ] No voiceover needed — just show the flow

### Store Assets
- [ ] App icon (high-res, 512x512 or whatever Seeker's spec is)
- [ ] Banner/hero image for the listing page

---

## 2. Pre-Launch Outreach Targets

### Persona
Quick-hit entertainment. Users scrolling while waiting — subway, bathroom, coffee line. 18-35, crypto-curious, not necessarily deep into DeFi. Want the *feeling* of trading without the complexity.

### Target Channels (in priority order)

**Phase 1 — Warm audience (your existing reach)**
- Your Twitter followers — you've built credibility in the Solana/gaming space
- Solana Discord groups you already sit in
- Specific friends/community who have Seekers

**Phase 2 — Seeker-native**
- Post in Seeker dev/user communities
- Seed Vault users (MWA context — people who already have the wallet flow)
- Solana Mobile Twitter — if you have contacts there

**Phase 3 — Organic growth**
- Crypto Twitter shitposting community
- degen accounts who post subway/metro content
- Reddit: r/cryptocurrency, r/solana, r/solanamobilemoney

### Outreach angle
Don't lead with "leverage trading app" — leads to immediate regulatory red flags in people's minds. Lead with the *moment*:
- "3 swipes and you're in a trade"
- "Tinder for your portfolio"
- "Trading that fits between subway stops"
- Casual, fun, not serious finance

### Content to have ready at launch
- [ ] Launch tweet (yours, not from a brand account — personal tone hits better)
- [ ] 10-15 second demo video for Twitter
- [ ] One-liner for when people ask "what is it"
- [ ] FAQ for friends/community who will want to try it
- [ ] Screenshot pack for anyone who wants to post about it

---

## 3. Launch Execution

### Timing
- [ ] Pick a launch window — Tuesday/Wednesday mid-morning typically works for crypto Twitter
- [ ] Post the demo video first, before the store link goes live (hype)
- [ ] Then drop store link + thread in the replies

### Day-of checklist
- [ ] Store listing live and working (test on a Seeker before launch day)
- [ ] Your phone nearby to respond to DMs
- [ ] Monitor for errors on the first day — have a debug flow for common issues
- [ ] Post a "it's live" tweet with demo video attached (not just text)

### Post-launch
- [ ] Screenshot any good reactions/mentions for future reference
- [ ] Note what questions people ask most — good signal for v1.1
- [ ] Decide how you want to handle feedback — Discord later, or just DMs for now

---

## 4. Operational Bits

### Monitoring (while you're heads down on Jupiter)
- [ ] Know your failure modes: ER down, price feed stale, session expired
- [ ] Have a simple alert set up — if you get a text saying something broke, you can triage
- [ ] Keep 2-3 SOL on the deployer wallet at all times for redeploys if needed

### Communication
- [ ] Decide now: launch updates go where? (just you messaging me is fine for now)
- [ ] What you should be messaged about immediately vs what can wait

### If something goes wrong on launch day
1. Check `tools/check-state.js` — is the program state healthy?
2. Check devnet RPC + ER router — are they responding?
3. Check Pyth feed — are prices updating?
4. If tx failing: session expired? validator unreachable? program ID mismatch?
5. Reach out to MagicBlock support on their Discord with the specific error

---

## 5. Soft Launches vs Big Bang

Given the app is simulated PnL and this is a UX/architecture demo in real-world clothing — consider whether you want to:

**A) Soft launch first** (lower pressure)
- Just post to your Twitter, close friends, Solana community you already know
- Gather 48h of feedback
- Fix the 2-3 things people trip up on
- Then push broader

**B) Go big from day one**
- Full outreach push, all channels
- Accept that first 24h feedback will be noisy
- Plan to patch fast

Both are valid. Soft launch is lower risk. But you know your audience and reach better than I do.

---

*Last updated: 2026-05-19*
