# Aperintel

**Governance-first AI infrastructure for regulated industries.**

Aperintel builds the substrate, the platform, and the developer infrastructure that regulated firms need to prove what their AI did, to whom, when, and on what evidence. We ship open-source primitives that anyone can inspect and audit, and commercial products on top that make those primitives operationally useful for FCA-regulated firms, NHS trusts, and EU AI Act high-risk systems.

## Open source projects

- [**Nexuscone**](https://github.com/aperintel/nexuscone) - tamper-evident append-only audit ledger with SHA-256 hash chain, optional Ed25519 signing, and optional Bitcoin anchoring via OpenTimestamps. Apache 2.0 on PyPI. The substrate underneath the Aperintel governance product family.
- [**NovaBash**](https://github.com/aperintel/novabash) - BYOK developer infrastructure platform. One workspace, one encrypted vault, one `.env`, every third-party service your stack runs on. Apache 2.0. Phase A complete.
- [**Mini-Assistant-Swarm**](https://github.com/aperintel/Mini-Assistant-Swarm) - fork-friendly personal subagent toolkit. VERIFIER-gated outputs, never sends on the operator's behalf, always writes to disk. Apache 2.0.
- [**awesome-ai-governance**](https://github.com/aperintel/awesome-ai-governance) - curated list of resources for building, shipping, and auditing AI in regulated environments. Regulations, standards, OSS primitives, governance platforms, security tools. CC0.
- [**regulated-ai-checklist**](https://github.com/aperintel/regulated-ai-checklist) - practitioner pre-deployment checklist for shipping AI in regulated environments. Governance, audit, security, data protection, monitoring, incident response, supply chain. CC BY 4.0.

More open-source repos are on the way, including the shared landing template used across the product family and an AI governance glossary aligned to the EU AI Act vocabulary.

## Research

The [Aperintel Accountability Architecture Series](https://aperintel.com) is a programme of research papers on cryptographic accountability primitives for regulated AI. Four papers deposit to Zenodo, SSRN, and OSF; a fifth on counterfactual inclusion proofs is in private draft pending UK provisional patent filing. Research output anchors every product positioning Aperintel takes to a regulated buyer.

## Sponsor

[Sponsor Aperintel on GitHub](https://github.com/sponsors/osiabu) to support the open-source primitives that underpin the commercial products. Sponsorship funds maintenance of the Apache 2.0 substrate and the v0.3.x AWS-native roadmap.

## Contact

Design partner enquiries, regulated-buyer conversations, and academic collaboration: **enquiries@aperintel.com**.

Security disclosure: open a GitHub Security Advisory on the affected repo, or email **enquiries@aperintel.com** with the subject line `[<product> Security]`.

---

*Aperintel is based in London. The work is one part of a larger thesis: the regulated firms deploying AI for decisions need a cryptographic substrate that proves what their AI did, before the EU AI Act high-risk obligations enforce on 2 August 2026.*
