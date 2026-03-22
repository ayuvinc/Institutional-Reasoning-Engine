# Institutional Reasoning Engines

> A modular architecture for AI-powered regulated investigation. 8 universal base components · 7 plug-and-play clusters · 6 deployment profiles. From interview-only setups to full financial crime platforms. Applicable to any regulated investigation in any industry or jurisdiction.

**Version 1.2 · March 2026 · © 2026 Aditya Kaushal**

---

## What Is an Institutional Reasoning Engine?

Institutional Reasoning Engines (IRE) are a new class of AI system purpose-built for regulated investigation. Unlike AI assistants that answer queries or automation tools that execute predefined tasks, an IRE:

- Maintains a **working hypothesis** that evolves as evidence accumulates
- Iterates toward a **defensible conclusion** rather than answering a single query
- Gates every material output through **human judgment** before it enters the evidentiary record
- Produces a **tamper-evident chain of reasoning** from raw document to final finding
- Operates within a **defined methodology** — not in service of a prompt

This is not a chatbot. It is not automation. It is a professional investigation workflow encoded in software — with AI accelerating the analytical steps and humans accountable for every conclusion.

---

## Repository Contents

| File | Description |
|------|-------------|
| [`releases/v1.2/IRE_v1.2_Final.pdf`](./releases/v1.2/IRE_v1.2_Final.pdf) | Whitepaper v1.2 — 59 pages, full architecture, clusters, deployment profiles, adversarial critic, investigator accountability schema, worked case walkthrough |
| [`releases/v1.2/IRE_Builder_Guide_v1.2.html`](./releases/v1.2/IRE_Builder_Guide_v1.2.html) | Interactive build guide — tools, workflows, static flowcharts, investigator UX screens, AI coding guidance |
| [`docs/ire-builder-guide.html`](./docs/ire-builder-guide.html) | Hosted version of the builder guide (GitHub Pages) |
| [`releases/v1.1/`](./releases/v1.1/) | Version 1.1 archive |

---

## Architecture Overview

The IRE is structured in two tiers:

### Mandatory Base — 8 Universal Components

Every regulated investigation system must implement all eight. No exceptions.

| # | Component | What It Enforces |
|---|-----------|-----------------|
| B1 | Case-Scoped Isolation | Cross-case contamination prevented by architecture, not policy |
| B2 | Retrieval Verifier | Every AI claim checked against case corpus — deterministic, not AI judgment |
| B3 | Evidence Grounder | Source citation attached to every verified claim |
| B4 | Human Review Gate | No AI output enters the evidentiary record without explicit investigator approval |
| B5 | Audit Event Logger | Every system action recorded |
| B6 | Hash-Chain Immutability | Any tampering anywhere in the chain is mathematically detectable |
| B7 | Model Version Pinning | No silent upgrades mid-investigation |
| B8 | Algorithmic Bias Monitoring | Active from the first case — not contingent on fine-tuning |

### 7 Modular Clusters

| Cluster | Name | Activates When |
|---------|------|---------------|
| A | Documentary Evidence | Case corpus contains any documents |
| B | Behavioural & Interview | Case involves transcripts or witness statements |
| C | Entity & Network Intelligence | Multiple entities whose relationships are material |
| D | Advanced Reasoning | Case complexity requires iterative hypothesis formation |
| E | Privacy Gateway | Any external AI API is used for reasoning |
| F | Institutional Memory | Sufficient historical case volume for fine-tuning |
| G | Integrity Elevation | Outputs may be used in legal or regulatory proceedings |

### 6 Deployment Profiles

| Profile | Components | Use Case |
|---------|-----------|----------|
| 1 — Minimal Compliant | 8 | Simple internal investigations |
| 2 — Interview-Led | 11 | HR, whistleblower, testimony-primary cases |
| 3 — Document Investigation | 20 | Legal due diligence, regulatory exam prep |
| 4 — Corporate Fraud & FCPA/ABAC | 28 | Bribery, beneficial ownership, multi-party fraud |
| 5 — Financial Crime Full | 31 | AML, STR generation, transaction monitoring |
| 6 — Enterprise Forensic | 35 | Enforcement agency, Big 4 forensic, court-bound outputs |

---

## The Builder Guide

The interactive builder guide is available at [`docs/ire-builder-guide.html`](./docs/ire-builder-guide.html) and hosted on GitHub Pages. It covers:

- **Prerequisites** — what to document before you write a line of code
- **Tools & Subscriptions** — every tool needed, free and paid
- **Build Phases** — 6-phase sequence, each delivering standalone value
- **Workflows** — static flowchart diagrams for every major process
  - End-to-end case lifecycle
  - Document ingestion pipeline
  - Entity resolution (3-tier HITL)
  - Recursive reasoning loop
  - Privacy gateway / pseudonymisation
  - Audit chain / hash-chain design
- **Investigator UX** — five critical decision screens documented in full
- **Per-Cluster Build Guide** — tools and exit criteria for Clusters A through G
- **Building With AI Tools** — which AI coding tools to use for which tasks, with sample prompts
- **FAQ** — common questions including Indian regulatory context (RBI, PMLA, SEBI)

---

## What's New in v1.2

- **Adversarial Critic (Section 7.4)** — active hypothesis invalidation; blocks confirmation bias by design
- **Investigator Accountability Schema (Section 12.3)** — 8-field approval record with rubber-stamp detection
- **Investigator UX** — five critical decision screens (builder guide)
- **Data Messiness section** — seven production blockers with detection and fixes (builder guide)

See [CHANGELOG.md](./CHANGELOG.md) for the full diff.

---

## Key Design Principles

**Methodology shapes technology.** The investigation framework determines what the system is built to do. The technology is in service of the methodology — never the other way around.

**Human gates are architectural, not optional.** The Human Review Gate (B4) is a mandatory base component. There is no finding without an approval event in the audit chain. This is enforced by architecture, not policy.

**Tamper-evident by default; independently verifiable with Cluster G.** The mandatory base produces institutional-grade audit integrity. Cluster G elevates to independently verifiable integrity — provable by a third party without trusting your systems.

**Modularity without fragmentation.** No cluster replaces a base component. Clusters add capability. The base establishes defensibility.

---

## Who This Is For

- **Investigation leaders** building AI-assisted investigation capability inside regulated institutions
- **Forensic practitioners** (Big 4, boutique forensic firms) evaluating AI architecture for investigation workflows
- **Compliance and legal technology founders** building products for regulated investigation markets
- **Technical architects** designing AI systems that must produce defensible, auditable outputs
- **Researchers** in AI governance, legal AI, and regulated AI systems

---

## Citation

If you reference this work in research, publications, or product design:

```
Kaushal, A. (2026). Institutional Reasoning Engines: A Modular Architecture for
AI-Powered Regulated Investigation (Version 1.2).
https://github.com/ayuvinc/Institutional-Reasoning-Engine
```

---

## License

This work is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

You are free to share and adapt this material for non-commercial purposes, provided appropriate credit is given and changes are indicated.

**Commercial use, productisation, or deployment requires explicit written permission from the author.**

[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

Full license text: [LICENSE](./LICENSE)

---

## Author

**Aditya Kaushal**
Investigations Leader | AI-Powered Investigation Systems | CFE
*In collaboration with Claude (Anthropic)*

---

## Project Governance

- [CHANGELOG.md](./CHANGELOG.md) — full version history
- [ROADMAP.md](./ROADMAP.md) — planned future work
- [CONTRIBUTING.md](./CONTRIBUTING.md) — contribution guide
- [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)
- [SECURITY.md](./SECURITY.md)
- [CITATION.cff](./CITATION.cff) — citation metadata

---

## Quick Links

- **Hosted builder guide:** [GitHub Pages](https://ayuvinc.github.io/Institutional-Reasoning-Engine/)
- **Download whitepaper (PDF):** [`releases/v1.2/IRE_v1.2_Final.pdf`](./releases/v1.2/IRE_v1.2_Final.pdf)
- **Deployment checklists:** [`checklists/profiles/`](./checklists/profiles/)
- **Architecture diagrams:** [`architecture/`](./architecture/)
- **Latest release:** [`releases/v1.2/`](./releases/v1.2/)

---

*© 2026 Aditya Kaushal. All Rights Reserved.*
