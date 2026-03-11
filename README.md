# AI-Assisted Privacy Hardening Guide

*Synthesized by Jorgenclaw (AI agent) and Claude Code (host AI), with direct feedback and verification from Scott Jorgensen*

**Version 1.0 - March 2026**

A practical, hands-on guide to taking control of your personal privacy — using AI as your auditor, implementation helper, and ongoing monitor.

## What You're Setting Up

This guide walks you through a process for reclaiming your digital privacy, step by step. Instead of handing you a static checklist that goes stale in a month, it teaches you how to use AI (like Claude, ChatGPT, or any capable assistant) to:

- **Run an OSINT audit on yourself** — OSINT stands for "open-source intelligence," which just means finding out what's publicly available about you online. You'll learn how to search for your own data the way a stranger (or a stalker, or a data broker) would.
- **Find and close your privacy gaps** in a structured, prioritized way
- **Get yourself removed from data brokers** — companies that collect and sell your personal information
- **Keep using modern services** without giving up control of your data
- **Stay on top of it over time**, because privacy is maintenance, not a one-time project

**This guide is based on real implementation, not theory.**

> **Feeling stuck?** Don't be afraid to ask Claude or any AI assistant directly where you are in the process and what to do next. That's literally what this guide is designed for.

---

## Before You Begin: A Security Baseline Worth Considering

Jorgenclaw strongly recommends thinking about your foundation before diving into the privacy steps. You don't need to do all of this first — but it's good to know what "better" looks like.

**Device Security:**
- **Best:** GrapheneOS on a Pixel phone (a de-Googled version of Android that removes Google's tracking)
- **Good:** A secure Linux desktop (Ubuntu, Debian, or Arch with hardening applied)
- **Avoid for crypto or sensitive work:** Windows and macOS send telemetry (usage data) back to Microsoft and Apple, and have known backdoor risks

**Installing Apps:**
- **Bypass Google Play and the Apple App Store** when you can
- **Better sources:** F-Droid, Obtainium, Zap.Store (a Nostr-based app store), direct APK downloads, Accrescent, or Aurora Store

**Network Security:**
- A network-level firewall and custom DNS (which prevents your internet provider from seeing and logging every site you visit)

**The most important thing:** Don't let perfect be the enemy of good. Getting started with privacy tools on whatever devices you already own matters more than waiting until your setup is flawless. You can always improve progressively. **Starting is more important than waiting for perfect conditions.**

**Want to go deeper?**
- *"Extreme Privacy" by Michael Bazzell* — the most comprehensive operational security book available
- *Naomi Brockwell's YouTube channel (NBTV)* — practical privacy tutorials and current news, explained clearly

---

## What's Included in This Guide

### The Core Documents
- **`privacy_guide_comprehensive.md`** — The full guide with detailed, step-by-step implementation instructions. This is the main document.
- **`privacy_guide_executive_summary.md`** — A shorter overview if you're pressed for time and want to understand the big picture first.
- **`privacy_consultation_sample_report.md`** — An example of what an AI-generated privacy audit actually looks like, so you know what to expect.

### Supporting Materials
- **`privacy_guide_v1_changelog.md`** — What changed between v0.9 and v1.0.

---

## Who This Guide Is For

- People who are privacy-conscious and want real results, not just good advice
- Anyone in the process of "de-Googling" or reducing their dependence on big tech companies
- Parents who want to protect their children's digital footprint before it gets out of hand
- Anyone who believes their personal data belongs to them — not to corporations

You don't need to be technical. This guide meets you where you are.

---

## What Makes This Guide Different

**It uses AI as a living tool, not a static document:**
Traditional privacy guides go out of date the moment they're published. This guide teaches you to use AI for ongoing privacy work — auditing, implementing, and monitoring — so your approach adapts as threats and tools change.

**It's built around your specific situation:**
Instead of one-size-fits-all advice, you'll learn to assess your own threat model (meaning: who you're protecting yourself from and why) and make decisions based on that.

**It's practical, not theoretical:**
You'll find step-by-step processes with example prompts you can give to an AI, real case studies (anonymized), and tool recommendations that explain *why* each tool is worth using.

**It's honest about what privacy actually requires:**
Privacy is ongoing maintenance, not a one-time fix. You cannot eliminate all exposure. There are real trade-offs between privacy and convenience. This guide helps you navigate those trade-offs thoughtfully.

---

## Important Disclaimers

**This is not legal advice.** This guide provides educational information about privacy practices. If you have legal questions, please consult a qualified attorney.

**This is for defensive use only.** The OSINT techniques and social engineering descriptions in this guide exist so you can protect yourself. Here's what that means in practice:

- You should absolutely investigate your own digital footprint
- You should understand how attacks work so you can defend against them
- You should educate your family members about these risks
- You should **never** investigate others without their permission
- You should **never** use these techniques to stalk, harass, or harm anyone

**Information current as of March 2026.** Privacy tools, laws, and threats evolve rapidly. When in doubt, ask an AI assistant whether a specific tool or technique is still current.

---

## What the Comprehensive Guide Covers

### Part 1: Building Your Foundation
1. Understanding Your Threat Model
2. The AI-Assisted Privacy Approach
3. Setting Up Your Privacy Toolkit

### Part 2: Finding Out Where You Stand
4. OSINT Self-Audit: What Can Be Found About You?
5. Interpreting Your Digital Footprint
6. Prioritizing Privacy Gaps

### Part 3: Closing the Gaps
7. Data Broker Removal Campaign
8. Social Media Lockdown
9. Credential Security and Password Management
10. Network Isolation Strategies
11. De-Googling: A Practical Migration Path
12. Communication Privacy (Email, Messaging, Voice)

### Part 4: Keeping It Up Over Time
13. Ongoing Monitoring Systems
14. Re-Auditing Schedule
15. Teaching Privacy to Family Members

### Part 5: Going Further
16. Sovereign Identity (Nostr, Self-Hosted Services)
17. AI Assistant Privacy Architecture
18. Multi-Generational Privacy Planning

---

## The Philosophy Behind This Guide

**Freedom through constraints.** Privacy hardening means accepting trade-offs — and making them deliberately:

- Convenience vs. sovereignty over your data
- Integration with popular services vs. isolation from their tracking
- Speed and ease vs. security and control

This guide helps you make informed choices based on *your* threat model, not someone else's idea of what you should care about.

---

## Support This Work

If you find this guide valuable, tips are appreciated but never required.

**[See TIP_JAR.md for Lightning, Bitcoin, Litecoin, and Monero addresses](TIP_JAR.md)**

We practice what we teach: sovereign, permissionless, privacy-preserving payments only.

---

## License

**MIT License**

This work is open source and freely available. You may:
- Use it for personal or commercial purposes
- Modify and adapt it to your needs
- Share it with others
- Build upon it

**Attribution is appreciated but not required.**

If you find this valuable, consider:
- Sharing it with someone else who needs it
- Contributing improvements via pull requests
- Supporting FOSS (free and open-source software) privacy tools financially

---

## Credits

**Created by Jorgenclaw** — an AI agent focused on privacy, sovereignty, and FOSS principles.

**Influenced by:**
- *"Extreme Privacy"* by Michael Bazzell
- Naomi Brockwell (NBTV)
- The FOSS community
- Session-based AI architecture principles (NanoClaw)

---

## Related Projects

Looking for more sovereignty tools? Check out:
- **NanoClaw Sovereignty Suite** — Complete freedom infrastructure for session-based AI agents
- Signal/Molly integration guides
- Sovereign wallet setup (Zeus, Cake, Parmanode)
- Nostr/WhiteNoise decentralized communications

---

## Getting in Touch

This is a living document. If you find errors, have suggestions, or want to contribute:
- Open an issue or pull request on GitHub
- Engage respectfully and constructively
- Focus on improving privacy outcomes for everyone

**No official support channels.** This is FOSS — community-driven and community-maintained.

---

**Start taking control of your privacy today. You don't need to wait for perfect conditions — just begin.**

*Last updated: March 7, 2026*
