# Human Rights Law & Remedy Index
**Pilot Legal Aid Engine • Factual Harm Parsing • Statutory-Treaty Mapping • Procedural Remedy Directives**

[![Deploy to GitHub Pages](https://github.com/DHANANAN/Humanknow/actions/workflows/deploy.yml/badge.svg)](https://github.com/DHANANAN/Humanknow/actions/workflows/deploy.yml)
[![Live App](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-10b981?style=flat&logo=github)](https://dhananan.github.io/Humanknow/)

🌐 **Live Deployment**: [https://dhananan.github.io/Humanknow/](https://dhananan.github.io/Humanknow/)

---

## ⚖️ Overview

The **Human Rights Law & Remedy Index** is a responsive, single-page legal technology web platform designed for citizens, paralegals, and human rights defenders. It bridges the gap between everyday factual descriptions of violations and technical procedural law by:

1. **Translating non-technical, plain-language statements** of harm into formal legal taxonomies.
2. **Performing dual cross-jurisdictional statutory mapping**, aligning domestic Indian statutes (**Bharatiya Nagarik Suraksha Sanhita - BNSS**, **Bharatiya Nyaya Sanhita - BNS**, **Bharatiya Sakshya Adhiniyam - BSA**, and the **Constitution of India**) against binding international human rights conventions (**ICCPR**, **ICESCR**, **UN CAT**, **ILO Conventions**, **ICERD**).
3. **Generating step-by-step procedural remedy directives** with targeted court jurisdictions and an **interactive evidence checklist**.

---

## 🏛️ Core Architectural Matrix (3-Tier Engine)

```
┌────────────────────────────────────────────────────────────────────────┐
│                        Hero Natural Language Query                     │
│   e.g. "Police detained someone for over 24 hours without magistrate"   │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                    TIER 1: VIOLATION TAXONOMY ENGINE                   │
│   • Parsed Legal Harm (e.g. Unlawful Police Detention)                 │
│   • Fundamental Rights Infringed (Articles 21 & 22(2))                │
│   • Severity & Intent Classification (Critical / Tort)                 │
│   • Jurisdictional Tier (Magisterial & Constitutional Concurrent)      │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                   TIER 2: DUAL LEGAL MAPPING MATRIX                    │
│   ┌───────────────────────────────┐ ┌──────────────────────────────┐   │
│   │    INTERNATIONAL STANDARDS    │ │        DOMESTIC CODES        │   │
│   │ • Article 9(1) & 9(3) ICCPR   │ │ • Section 58 BNSS (Sec 57)   │   │
│   │ • UN Body of Principles       │ │ • Article 22(2) Constitution │   │
│   │ • Treaty Body General Comments│ │ • Section 100 BNSS (Sec 97)  │   │
│   └───────────────────────────────┘ └──────────────────────────────┘   │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                  TIER 3: PROCEDURAL REMEDY DIRECTIVES                  │
│   • Competent Judicial Forums (CJM, High Court, NHRC/SHRC)             │
│   • Immediate Statutory Motions (Emergency Sec 100 BNSS application)   │
│   • Interactive Evidence Checklist & Evidentiary Threshold Progress    │
└────────────────────────────────────────────────────────────────────────┘
```

---

## ⚡ Key Features

- **Semantic Query Parsing & Instant Scoring**: Free-form natural language search that parses factual statements, weights keywords, and links to constitutional legal taxonomies.
- **Quick-Select Taxonomy Pills**: Instant 1-click loading of pre-calibrated test cases:
  1. *Unlawful Detention* (BNSS Sec 58 / Art 22(2) / ICCPR Art 9)
  2. *Custodial Violence* (BNSS Sec 53/54 & 196 / BSA Sec 23 / ICCPR Art 7 / UN CAT)
  3. *Housing Eviction* (Article 21 / LARR Act / ICESCR Art 11)
  4. *Workplace Exploitation* (Article 23 / Bonded Labour Act 1976 / ILO 29)
  5. *Discriminatory Access* (Article 15(2) & 17 / SC/ST PoA Act / ICERD Art 5)
- **Clinical Mode Switch**: Instant toggle between:
  - *Layperson Guidance*: Plain language rights summaries, safety directives, and practical steps.
  - *Practitioner Clinical Mode*: Formal court docket citation syntax, statutory presumptions, limitation periods, and burden of proof standards.
- **Interactive Evidence & Filing Builder**:
  - Live progress tracking (`66% of evidentiary threshold satisfied`).
  - Readiness tags (`Insufficient Documentation`, `Prima Facie Threshold Satisfied`, `Court-Ready Dossier`).
  - Add custom document entries and evidentiary affidavits dynamically.
- **Academic & Compliance Metrics Footer**:
  - Statutory-treaty compliance gap breakdown.
  - Competent forum escalation pathways.
  - Burden of proof & evidential presumption guidelines.
- **Official Case Brief Export**:
  - One-click generation of an official, print-ready legal assessment sheet.
  - Formatted for clean printing (`@media print`) and PDF export.

---

## 🎨 Design System

- **Color Palette**: Deep Navy (`#0A1128` / `#0F172A`), Slate Panels (`#1E293B`, `#141E33`), Emerald Green (`#10B981`), Amber (`#F59E0B`), Cyan (`#38BDF8`), and Crimson (`#F43F5E`).
- **Typography**: `Inter` for clean readability; `JetBrains Mono` for statutory citations and docket codes.
- **Micro-Interactions**: Real-time progress bar animations, reactive status indicators, and glassmorphic panel depth.

---

## 🚀 Getting Started

The platform is completely self-contained with **zero external dependencies or build steps**.

### Running Locally

Simply clone the repository and open `index.html` in any web browser:

```bash
git clone https://github.com/DHANANAN/Humanknow.git
cd Humanknow
# Open directly in browser or serve with any static server:
# python -m http.server 8000
# or npx serve .
```

---

## 📜 License

MIT License. Designed and built as an open-access legal technology contribution.
