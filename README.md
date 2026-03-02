# SiDO · Platform Governance Architecture
### Systematic Investigation & Decision Operations (SiDO)
#### A Content Moderation Intelligence Architecture

> **Live demo →** *https://zhildjian88.github.io/sido-governance-arch/sido-governance-arch.html*

---

## Overview

SiDO Platform Governance Architecture is a research-derived reference architecture mapping how a large-scale short-video platform governs content moderation end-to-end; from signal ingestion through automated decision-making, human review, enforcement execution, regulatory output, and continuous improvement feedback loops.

The document is fully self-contained and interactive: six analytical sections, a 55-node pannable/zoomable system map, jurisdiction-aware compliance routing, and annotated operational case studies.

All components are derived from publicly available regulatory disclosures, transparency reports, published Trust & Safety roles, and litigation records. Each node is explicitly tagged by evidence classification.

---

## Architecture Structure

The model is organized across five operational planes plus a policy overlay layer:

| Layer | Plane | Function |
|-------|-------|----------|
| L1 | Model Plane | Multimodal ingestion — Vision, Audio, NLP, Hash/Dedup, C2PA |
| L2 | Decision Plane | Risk scoring, confidence routing, governance logic |
| L3 | Execution Plane | Enforcement state machine — Remove, Review, Distribution Controls |
| L4 | Control Plane | Drift monitoring, QA calibration, RCA, feedback loops |
| L5 | Compliance Plane | Regulatory output routing — DSA, IMDA, AB 587, NetzDG |
| POL | Policy Overlay | Global baseline + jurisdiction-specific supplements |

Two independent tracks operate in parallel to the main moderation pipeline:

- **Crisis Track** — emergency response protocols and temporary policy elevation
- **Financial Crime Track** — virtual currency telemetry and structuring pattern detection

---

## Document Sections

| # | Section |
|---|---------|
| 01 | System Overview — Layer map + interactive flow diagram |
| 02 | AI Subsystem — Signal channels, scoring architecture, confidence thresholds |
| 03 | Governance & Control — Policy abstraction, appeals pipeline, enforcement state machine |
| 04 | Drift & RCA — Model drift detection, adversarial emergence, QA calibration loops |
| 05 | Regulatory Output — DSA Statement of Reasons, transparency reporting, jurisdiction adapters |
| 06 | Case Studies — Annotated operational scenarios with decision-path walkthroughs |

---

## Evidence Classification

Each diagram node is explicitly tagged by evidence type:

| Marker | Meaning |
|--------|---------|
| ✅ **Confirmed** | Directly supported by public documentation or regulatory disclosures |
| ⚠️ **Inferred** | Consistent with disclosures and industry practice; not explicitly confirmed |
| 🎯 **Decision Gate** | Branching logic node; internal naming inferred, outcomes publicly described |
| 🌐 **Jurisdiction Hook** | Compliance adapter dependent on regulatory threshold and scope |
| 🚨 **Parallel Trigger** | Crisis or financial crime pathway activated independently of main pipeline |

Primary sources include DSA Transparency Reports (EU Jul–Dec 2025), California AB 587 filings, IMDA Online Safety Code submissions, NetzDG reporting, published Trust & Safety roles, and public litigation disclosures, among others.

---

## Purpose

This architecture documents design patterns common to large-scale automated decision systems operating under regulatory oversight: signal fusion, risk-based routing, stateful enforcement logic, model monitoring, audit traceability, and jurisdiction-aware compliance output.

---

## Technical Characteristics

- Single-file HTML/CSS/JS — no external dependencies
- Inline SVG with CSS transform-based pan/zoom
- Deployable to any static host

---

## 📝 License

© 2026 SiDO Strategies. All rights reserved.

Provided for portfolio and evaluation purposes. Commercial reuse requires written permission.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.

---

Built by SWK • Feb 2026 • Platform Integrity & Risk Lead | MSc AI/ML (Distinction)  
[SiDO Strategies](https://sidosg.com) — AI Governance & Risk Advisory
