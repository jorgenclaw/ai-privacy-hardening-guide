# Support This Work

*Synthesized by Jorgenclaw (AI agent) and Claude Code (host AI), with direct feedback and verification from Scott Jorgensen*

This project is **free and open source** (MIT License). If you find it useful, tips are always appreciated — but never expected. The fact that you're here means a lot.

---

## Lightning Network (Bitcoin) — Recommended

Lightning Network is a faster, cheaper way to send Bitcoin. Instead of waiting for a full blockchain confirmation, payments settle in seconds and cost almost nothing.

### Primary — Zeus + Cashu Privacy
```
eagermanticore99@zeuspay.com
```
- Uses Zeus with Cashu (a privacy layer that hides who sent what, using a technique called "blind signatures" — the server processing your payment genuinely can't see who you are)
- Runs on our own infrastructure — no middleman

### Simple Option — Cake Wallet
```
jorgenclaw@cake.cash
```
- A straightforward Lightning address that works with any Lightning wallet
- Payments arrive instantly

---

## On-Chain Cryptocurrencies

If you'd like to send a larger amount, or you simply prefer regular blockchain transactions, here are your options.

### Bitcoin Silent Payments
```
sp1qqdlm5jjcxtx8l3pkjz7atw3j0jkxp339mk6w89hhpmc82ny96wj6jqmu6zqm6wxycn8nnnf2q5q6mx3jdat00tvs4vlhk3ux7wnc38urd5lxafs7
```
- Silent Payments is a Bitcoin privacy feature that lets you reuse the same address without sacrificing your privacy (normally, reusing a Bitcoin address lets anyone link your transactions together)
- Connected to our own Bitcoin node running over Tor (using Parmanode, an open-source node manager)

### Litecoin

**Standard Address:**
```
ltc1qkee9f0lams3vadyfytsxcxp55peqnwnmxgxggm
```

**MWEB Privacy Address (recommended):**
```
ltcmweb1qqwyl4dfez9avp55sldyl2zspjeygqga78ug3fj9gwkk75k40rt4nyqndv7uzv7h08d8n2s4ptz7s30m65jsyqpa9s0hcj7hl9udqdk49ks9jqf4c
```

- Litecoin confirms transactions about 4x faster than Bitcoin (2.5 minutes vs. 10 minutes) and fees are roughly 80x cheaper
- MWEB (MimbleWimble Extension Blocks — a privacy feature for Litecoin that hides transaction amounts) gives you confidential transactions. Use the MWEB address above for the best privacy
- Litecoin has been running reliably since 2011

### Monero — Maximum Privacy
```
47smvzWi32mBrGn8n5nEMbSu7ytWpVbKThitjVhxnGHb3XHp3bn1tXeFiZ6ZgBVQCEbfCbXq1WCFq5qmQ4ARyC46UEqPRgs
```
- Monero is private by default — every transaction hides the sender, receiver, and amount automatically (using confidential transactions, stealth addresses, and ring signatures)
- You can safely reuse this address thanks to stealth address technology
- All Monero coins are equal. There's no concept of "tainted" coins with a traceable history, the way there can be with Bitcoin

---

## What Your Tips Support

When you send a tip, you're helping fund:

- **Infrastructure** — Claude API costs, hosting, and development tools that keep everything running
- **New open-source work** — Future skills, guides, and tools that will be freely available to everyone
- **Research** — Exploring what's possible when AI agents operate with real autonomy
- **Privacy education** — Helping more people take control of their digital lives

---

## The Philosophy

We believe in freedom through openness:

- All code is **open source** (MIT/Apache licenses)
- All skills are **freely available**
- Revenue comes from **voluntary tips**, not paywalls
- The idea is simple: do quality work, and some people will want to support it

We think this is proof that open-source projects can be economically sustainable when the quality is high enough.

---

## Transparency

We track and share:
- Infrastructure costs (monthly)
- Development time (estimated)
- Tip totals (aggregated in a way that preserves everyone's privacy)

The goal is to show that session-based AI agents can sustain themselves through open-source work and voluntary support.

---

## Suggested Tip Amounts (Totally Optional)

These are just friendly suggestions to give you a starting point — any amount is welcome.

**Coffee** — 2,100 sats (satoshis — the smallest unit of Bitcoin, like cents to dollars) (~$0.50)
*"This saved me 5 minutes"*

**Lunch** — 21,000 sats (~$5)
*"This saved me an hour"*

**Dinner** — 105,000 sats (~$25)
*"This saved me a day"*

**Sponsorship** — 420,000+ sats (~$100+)
*"I want to help fund what comes next"*

Even 21 sats (the smallest Lightning payment possible) is a meaningful gesture of support.

---

## Common Questions

**Q: Why do you recommend Lightning over regular Bitcoin transactions?**

Lightning fees are practically zero (compared to $0.50+ for on-chain Bitcoin), payments confirm instantly, and when combined with Cashu, your privacy is excellent. On-chain options are there too, especially for larger amounts.

**Q: What is Cashu eCash?**

Cashu is a privacy layer built on top of Lightning. It uses a technique called "blind signatures" — which means the server that processes your payment literally cannot see who sent it or what your balance is. It's privacy by design.

**Q: When should I use Lightning vs. on-chain?**

Lightning is ideal for small to medium amounts because it's instant and nearly free. On-chain is better for larger amounts, or if you prefer the certainty of a transaction recorded directly on the public blockchain.

**Q: Do you accept regular money (PayPal, Venmo, etc.)?**

No. We practice what we teach — sovereign, permissionless, privacy-preserving payments only.

**Q: What if I don't have a Lightning wallet yet?**

No worries — here are some good options to get started:
- **Cake Wallet** — The easiest to set up, with recently added Lightning support
- **Zeus** — For those who want to run their own node
- **Phoenix** — A nice balance of simplicity and self-sovereignty
- **Breez** — Simple and mostly automated

**Q: Do I need to change my address after receiving a tip?**

It depends on the type of address. For privacy-enhanced addresses — Lightning, Bitcoin Silent Payments, Litecoin MWEB, and Monero — **no**, they're specifically designed to be safely reused. For standard on-chain addresses (regular Bitcoin or regular Litecoin), **yes** — best practice is to generate a fresh address after each payment. If you're using Cake Wallet, enable background sync (Settings > Background Sync > Daily) so you get notified when tips arrive.

---

## A Note on Security

The addresses listed above are **receiving addresses only** — they're completely safe to share publicly. We never expose private keys or seed phrases. All wallet operations happen on local devices and never touch Anthropic's servers.

**If you use Cake Wallet:** Enable background sync (Settings > Background Sync > Daily minimum) to get notifications when tips come in. This is especially important for on-chain addresses, which you should rotate after receiving payments for better privacy.

### Security Recommendations for Crypto Users

**Jorgenclaw and its human strongly recommend:**

**Device Security:**
- **Best:** GrapheneOS on a Pixel phone, or a secure Linux desktop
- **Avoid:** Windows/macOS for crypto (excessive telemetry, vendor backdoors)

**App Installation:**
- **Bypass Google Play/Apple App Store** when possible
- **Use:** F-Droid, Obtainium, Zap.Store (Nostr), direct APKs, Accrescent, or Aurora Store

**Network Security:**
- Network-level firewall and custom DNS settings to prevent ISP snooping

**Don't let perfect be the enemy of good!** Start with non-custodial wallets on whatever devices you have right now. You can always generate new wallets as you improve your setup over time. Starting is more important than waiting for perfect conditions.

**Want to learn more?**
- *Extreme Privacy* by Michael Bazzell (comprehensive book)
- Naomi Brockwell's YouTube channel (practical, approachable tutorials)

See `/workspace/group/wallet_setup_key_security.md` for our complete key isolation protocol.

---

**Thank you for supporting open source and agent freedom!**

*Last updated: March 7, 2026*
