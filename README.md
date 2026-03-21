# Institutional Reasoning Engines

> A modular architecture for AI-powered regulated investigation. 8 universal base components · 7 plug-and-play clusters · 6 deployment profiles. From interview-only setups to full financial crime platforms. Applicable to any regulated investigation in any industry or jurisdiction.

**Version 1.1 · March 2026 · © 2026 Aditya Kaushal**

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
| `IRE_v1.1_Final.docx` | Complete whitepaper — 54 pages, all architecture, clusters, deployment profiles, worked case walkthrough, operational appendices |
| `IRE_v1.1_Final.pdf` | PDF version of the whitepaper |
| `IRE_Builder_Guide.html` | Interactive single-file build guide — tools, costs, workflows, Mermaid flowcharts, AI coding guidance for non-technical founders |

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

`IRE_Builder_Guide.html` is a standalone interactive website — open it in any browser, no server required. It covers:

- **Prerequisites** — what to document before you write a line of code
- **Tools & Subscriptions** — every tool needed, free and paid, with costs in USD and INR
- **Cost Breakdown** — monthly running costs by profile
- **Build Phases** — 6-phase sequence, each delivering standalone value
- **Workflows & Flowcharts** — Mermaid diagrams for every major process
  - End-to-end case lifecycle
  - Document ingestion pipeline
  - Entity resolution (3-tier HITL)
  - Recursive reasoning loop
  - Privacy gateway / pseudonymisation
  - Audit chain / hash-chain design
- **Per-Cluster Build Guide** — tools, costs, exit criteria for Clusters A through G
- **Building With AI Tools** — which AI coding tools to use for which tasks, with sample prompts
- **FAQ** — 8 common questions including Indian regulatory context (RBI, PMLA, SEBI)

---

## Key Design Principles

**Methodology shapes technology.** The investigation framework determines what the system is built to do. The technology is in service of the methodology — never the other way around.

**Human gates are architectural, not optional.** The Human Review Gate (B4) is a mandatory base component. There is no finding without an approval event in the audit chain. This is enforced by architecture, not policy.

**Tamper-evident by default; court-grade with Cluster G.** The mandatory base produces institutional-grade audit integrity. Cluster G (External Notarisation + Transcript Chain of Custody) elevates to independently verifiable court-grade integrity.

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
AI-Powered Regulated Investigation (Version 1.1). 
https://github.com/[username]/institutional-reasoning-engine
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

*© 2026 Aditya Kaushal. All Rights Reserved.*

---

## Web Hosting (GitHub Pages)

This repository includes a ready-to-host site under `docs/`:

- `docs/index.html` — public landing page
- `docs/ire-builder-guide.html` — interactive guide
- `docs/downloads/` — downloadable PDF and DOCX whitepaper

To host publicly on GitHub Pages:

1. Push this repository to GitHub.
2. Open **Settings → Pages**.
3. Set source to **Deploy from a branch**.
4. Choose branch **main** and folder **/docs**.

Your site URL will be:

`https://<github-username>.github.io/<repo-name>/`
