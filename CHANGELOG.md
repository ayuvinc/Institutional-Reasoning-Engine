# Changelog

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog, and this project uses semantic-style release labels for documentation milestones.

## [Unreleased]

### Added
- Contribution workflow docs (`CONTRIBUTING.md`)
- Conduct policy (`CODE_OF_CONDUCT.md`)
- Security policy (`SECURITY.md`)
- Citation metadata (`CITATION.cff`)
- Issue and pull request templates
- Project roadmap (`ROADMAP.md`)

## [v1.2] - 2026-03-22

### Added
- **Section 7.4 — Adversarial Critic** (Whitepaper + Builder Guide): Active hypothesis invalidation component. Fires when evidence score exceeds 0.70. Four adversarial query types: alternative explanation, counter-entity, timeline invalidation, typology mismatch. Blocks evidence score from exceeding 0.85 until hypothesis survives genuine challenge. Prevents confirmation bias by architecture.
- **Section 12.3 — Investigator Accountability Schema** (Whitepaper + Builder Guide): 8-field approval record capturing quality and basis of human judgment — not just that approval occurred. Includes `confidence_level`, `disagreement_flag`, `elapsed_review_time`, and `rationale` fields. Rubber-stamp detection: review times under 30 seconds per section trigger quality review flag.
- **Investigator UX — Decision Screens** (Builder Guide only): Five critical investigator-facing screens documented in full: Entity Resolution Decision, Finding Review, Contradiction Alert, Graph + Evidence Unified View, Adversarial Review. Includes graph visualisation library comparison and 4-step build approach.
- **Data Messiness section** (Builder Guide only): Seven production blockers documented with detection and fix strategies: scanned PDFs without OCR layer, password-protected files, non-standard CSV encodings, inconsistent date formats, garbled OCR entity names, inconsistent column headers, handwritten annotations. Rejected Documents Log pattern added.
- **Two Documents — Two Roles framing** (Builder Guide): Explicit positioning of whitepaper (strategic/why) vs builder guide (execution/how).
- `releases/v1.2/` folder with PDF, DOCX, HTML, and SHA256 checksums.
- `docs/downloads/` updated with v1.2 PDF and DOCX alongside v1.1 files.

### Changed
- Builder Guide version badge updated from v1.1 to v1.2.
- Reasoning Correctness Limitation disclosure added to Section 12 (Whitepaper): clarifies that the Retrieval Verifier, Adversarial Critic, and Evidence Scorer do not guarantee logical soundness — the Human Review Gate remains the primary control.

## [v1.1] - 2026-03-21

### Added
- IRE v1.1 whitepaper (`DOCX`, `PDF`)
- Interactive builder guide (`IRE_Builder_Guide.html`)
- Public GitHub Pages site under `docs/`
- Automated GitHub Pages deployment workflow
