<p align="center">
  <img src="/media-kit/logos/cubert-coin-primary.png" width="220">
</p>
<h3 align="center">Proof of Burnout.</h3>
<p align="center">
  <em>The first cryptocurrency built for Corporate Survivors.</em>
</p>

---
 
# 🛡️ Security Policy
 
> *"This policy was reviewed during a meeting that should have been an email. It is, for once, the email."*

**Filing Ref.:** SEC-001  
**Effective Date:** Upon commit to `main`  
**Version:** 1.0  
**Status:** Active 🟢
 
This document defines how security issues, scam reports, and incident response work for the CubertCoin project — covering the GitHub repository, smart contract, official channels, and treasury infrastructure.
 
## 📣 Reporting a Vulnerability or Security Concern
 
If you discover a security vulnerability — in this repository, the smart contract (once deployed), or any official CubertCoin channel (e.g. a compromised Discord bot, a defaced website, a hijacked social account) — please report it responsibly.
 
### How to Report
 
**Preferred:** Open a [private security advisory](https://github.com/CubertCoin/cubertcoin/security/advisories) on GitHub. This keeps the report private until it's resolved.

> If the link above is unavailable, private vulnerability reporting may not yet be enabled for this repository — in that case, use the alternative method below.
 
**Alternative:** Contact the Founder directly via the official channels listed below. Do **not** disclose unpatched vulnerabilities publicly (Discord, Telegram, X, GitHub Issues) until the Founder has confirmed the report and a fix or mitigation is in place.
 
### What to Include
 
- A clear description of the issue
- Steps to reproduce (if applicable)
- Potential impact (funds at risk, contract behavior, etc.)
- Your contact information, if you'd like a response
### Response Timeline
 
| Step | Timeline |
|------|----------|
| Acknowledgment of report | Best-effort Within 48 hours |
| Initial assessment | Best-effort Within 5 days |
| Resolution or mitigation plan | Communicated as soon as available |
 
Responsible disclosure helps protect the community. Anyone who reports a valid issue in good faith will be credited (if desired) once the issue is resolved.
 
## 🚨 Scam, Impersonation, and Fraud Reports
 
This is the most common "security" issue a memecoin project faces — and the one most likely to affect holders directly.
 
CubertCoin operates a **zero-tolerance policy** for scams, impersonation, and contract address fraud, as defined in the [Governance Charter](./governance/) (Article VI).
 
### Official Sources — The Only Ones That Matter
 
The official $CUBE contract address, announcements, and links will **only ever** be published via:
 
| Channel | Link |
|---------|------|
| 🌐 Website | [cubertcoin.com](https://www.cubertcoin.com) |
| 🐦 X / Twitter | [@cubertcoin](https://x.com/cubertcoin) |
| 💬 Discord | [Corporate Survivors HQ](https://discord.gg/UqJwHACWhz) |
| 📢 Telegram | [Corporate Hotline](https://t.me/cubertcoin) |
 
**Any contract address, link, or announcement from any other source — including DMs, comments, or accounts impersonating the project — is unauthorized and should be treated as a scam.**

> 🔑 **No one from CubertCoin will ever DM you first, ask for your seed phrase, private key, or wallet approval "to verify your wallet," or ask you to connect your wallet to a site outside [cubertcoin.com](https://www.cubertcoin.com). Any message claiming otherwise — even from an account that looks like an admin or moderator — is a scam.
 
### How to Report a Scam
 
1. **Do not interact** with the suspicious link, contract, or account.
2. Report it via [GitHub Issues](https://github.com/CubertCoin/cubertcoin/issues) or the official Discord/Telegram.
3. Include screenshots, links, and contract addresses where possible.
### Incident Response Process
 
Per the Governance Charter, Article VI:
 
1. Core Contributors flag and document the incident.
2. A community warning is issued within **2 hours** across all official channels.
3. The Founder reviews and issues an official statement within **24 hours**.
4. The incident is logged in a public registry (to be established at launch).
 
## 🔐 Treasury and Token Security
 
The security of project funds and the $CUBE token itself relies on verifiable, on-chain mechanisms rather than promises:
 
| Mechanism | Status | Detail |
|-----------|--------|--------|
| Mint Authority | 🟡 Active until launch | Will be revoked permanently on-chain at launch |
| Freeze Authority | ✅ Never set | Was not set upon token creation — verified on Solscan |
| Treasury Multisig | ✅ Live | Squads Protocol, 2-of-3 — `7ay63WdfndoouyBqfXK1z5oy1s8CYoywR2ML9Aaf2cCF` |
| Team Vesting | ✅ Live | Streamflow, 6-month cliff + 12-month vesting — contract active |
| Liquidity Lock | ⚪ Pending launch | Streamflow, 12 months minimum — executed at launch |
 
Once executed, all of the above will be verifiable on-chain via the [On-Chain Verification table](./tokenomics/#-on-chain-verification) in the Tokenomics document — including direct links to Solscan/Solana Explorer for each contract and transaction.
 
### Operational Security Practices
 
While the project is in its current solo-founder phase:
 
- The Treasury multisig is self-custodied across **separate physical devices**, including at least one hardware wallet, to reduce single-device compromise risk.
- No single device or session has unilateral control over treasury funds.
- Liquidity and team token allocations, once locked via Streamflow, are governed by **immutable smart contracts** — not even the Founder can bypass them before the unlock date.
As the project grows, the plan is to evolve toward additional independent signers on the Treasury multisig, per the [Governance Charter](./governance/), Article IV.
 
## 🧯 Emergency Contacts
 
| Role | Contact |
|------|---------|
| Founder | Via official Discord or Telegram (see Official Channels below) |
| Security Reports (GitHub) | [Security Advisories](https://github.com/CubertCoin/cubertcoin/security/advisories) |
| Scam/Fraud Reports | [GitHub Issues](https://github.com/CubertCoin/cubertcoin/issues) or official Discord/Telegram |
 
> A dedicated security contact email may be added at launch.
 
## 🌐 Official Channels
 
| Platform | Link |
|----------|------|
| 🌐 Website | [Corporate Intranet](https://www.cubertcoin.com) |
| 🐦 X / Twitter | [Corporate Broadcast System](https://x.com/cubertcoin) |
| 💬 Discord | [Corporate Survivors HQ](https://discord.gg/UqJwHACWhz) |
| 📢 Telegram | [Corporate Hotline](https://t.me/cubertcoin) |
| 👽 Reddit | [Employee Forum](https://reddit.com/r/CubertCoin) |
| 📸 Instagram | [Corporate Gallery](https://www.instagram.com/cubertcoin) |
| 💻 GitHub | [Corporate Repository](https://github.com/CubertCoin/cubertcoin) |
| 📝 Paragraph | [Corporate Memos](https://paragraph.xyz/@cubertcoin) |
 
## 📁 Related Documents
 
- ❓ [FAQ](./faq.md)
- 📘 [Brand Book](./brand-book)
- 📋 [Changelog](./CHANGELOG.md)
- ⚖️ [Code of Conduct](./CODE_OF_CONDUCT.md)
- 📄 [The Cubert Thesis](./thesis/)
- 👔 [Employee Handbook](./employee-handbook)
- 📖 [Glossary](./GLOSSARY.md)
- 🏛️ [Governance Charter](./governance)
- 🎨 [Media Kit](./media-kit)
- ⚠️ [Risk Disclosure](./risks.md)
- 🗺️ [Roadmap](./roadmap)
- 📊 [Tokenomics](./tokenomics)
- 🤝 [Contributing Guide](./CONTRIBUTING.md)


### Version History
 
| Version | Date | Summary |
|---------|------|---------|
| 1.0 | June 2026 | Initial Security Policy |
 
---
 
**Proof of Burnout.**
 
*Another Meeting. Another Token.*
 
*CubertCoin Security Policy · v1.0 · Filed under: SEC-001*
