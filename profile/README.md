# Aperintel

**Governance-first AI infrastructure for regulated industries.**

Aperintel is an AI studio building the substrate, the platform, and the developer infrastructure that regulated firms need to prove what their AI did, to whom, when, and on what evidence. We ship open-source primitives that anyone can inspect and audit, and commercial products on top that make those primitives operationally useful for FCA-regulated firms, NHS trusts, and EU AI Act high-risk systems.

## Live products

| Product | Status | Surface |
|---|---|---|
| [Aperintel](https://aperintel.com) | Live | The studio's own front door |
| [Aperintel AI Academy](https://academy.aperintel.com) | Live | Cohort-based AI engineering education |
| [Aperintel AI Gateway](https://gateway.aperintel.com) | Live | Multi-provider AI router with per-request audit |
| [TekkieStack](https://tekkiestack.com) | Live | Gamified coding education for ages 8 to 16 |
| [Nexuscone](https://github.com/aperintel/nexuscone) | Live on PyPI (Apache 2.0) | Cryptographic audit substrate |
| [NovaBash](https://novabash.dev) | Phase A complete | BYOK developer infrastructure platform |

## In development

| Product | Status | Note |
|---|---|---|
| Hyperaxis | Design-partner intake | AI governance platform for regulated industries. Three-pillar product: Discover, Govern, Sign. Built on Nexuscone. |
| Hyperaxis Trace | Private build | Outcome verification on the same audit substrate. The second governance product on the Nexuscone family. |
| Metacarpal | Private build | Governed-autonomy operating system. Both personal and enterprise on one auditable spine. |

## Open source

- [**Nexuscone**](https://github.com/aperintel/nexuscone) - tamper-evident append-only audit ledger with SHA-256 hash chain, optional Ed25519 signing, and optional Bitcoin anchoring via OpenTimestamps. Apache 2.0. The substrate underneath every Aperintel governance product.
- [**NovaBash**](https://github.com/aperintel/novabash) - BYOK developer infrastructure platform. One workspace, one encrypted vault, one `.env`, every third-party service your stack runs on. Apache 2.0.

More public repos are coming, including the [shared landing template](https://aperintel.com) used across the product family, the AI governance glossary, and the regulated-AI deployment checklist drawn from the Hyperaxis build guide.

## Research

The [Aperintel Accountability Architecture Series](https://aperintel.com) is a programme of research papers on cryptographic accountability primitives for regulated AI. Four papers deposit to Zenodo, SSRN, and OSF; a fifth on counterfactual inclusion proofs is in private draft pending UK provisional patent filing. Research output anchors every product positioning Aperintel takes to a regulated buyer.

## Sponsor

[Sponsor Aperintel on GitHub](https://github.com/sponsors/osiabu) to support the open-source primitives that underpin the commercial products. Sponsorship funds maintenance of the Apache 2.0 substrate and the v0.3.x AWS-native roadmap.

## Contact

Design partner enquiries, regulated-buyer conversations, and academic collaboration: **enquiries@aperintel.com**.

Security disclosure: open a GitHub Security Advisory on the affected repo, or email **enquiries@aperintel.com** with the subject line `[<product> Security]`.

---

*Aperintel is based in London. The studio is one part of a larger thesis: the regulated firms deploying AI for decisions need a cryptographic substrate that proves what their AI did, before the EU AI Act high-risk obligations enforce on 2 August 2026.*
