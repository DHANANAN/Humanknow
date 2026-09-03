# Human Rights Law & Remedy Index
**Pilot Legal Aid Engine • Factual Harm Parsing • Statutory-Treaty Mapping • Procedural Remedy Directives**

[![Deploy to GitHub Pages](https://github.com/DHANANAN/Humanknow/actions/workflows/deploy.yml/badge.svg)](https://github.com/DHANANAN/Humanknow/actions/workflows/deploy.yml)
[![Live App](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-10b981?style=flat&logo=github)](https://dhananan.github.io/Humanknow/)

🌐 **Live Deployment**: [https://dhananan.github.io/Humanknow/](https://dhananan.github.io/Humanknow/)

---

## ⚖️ Overview

The **Human Rights Law & Remedy Index** is an authoritative, clinical-grade legal technology platform and AI remedy engine designed for citizens, paralegals, and human rights defenders. It bridges the gap between everyday factual descriptions of violations and technical procedural law by:

1. **Translating non-technical, plain-language statements** of harm into **direct, actionable legal findings and emergency procedural roadmaps**.
2. **Progressively streaming relevant landmark judicial precedents** from the Supreme Court of India with binding legal ratios, judgment quotes, and case-specific remedy applications.
3. **Performing dual cross-jurisdictional statutory mapping**, aligning domestic Indian statutes (**Bharatiya Nagarik Suraksha Sanhita - BNSS 2023**, **Bharatiya Nyaya Sanhita - BNS 2023**, **Bharatiya Sakshya Adhiniyam - BSA 2023**, and the **Constitution of India**) against binding international human rights covenants (**ICCPR**, **ICESCR**, **UN CAT**, **ILO Conventions**, **ICERD**).
4. **Generating ready-to-file court drafts** with the Procedural Motion Drafter and an interactive evidentiary dossier builder.

---

## 🎨 Design System: Caramel Dark & Warm Silk

- **Dark Caramel Espresso** (Default): Deep roasted mocha background (`#0e0a07`), dark caramel cards (`#201710`), honey-caramel accents (`#e59a42`, `#f4b266`), and warm glowing borders.
- **Warm Caramel Silk**: High-contrast warm parchment background (`#fbf7f1`) with rich espresso typography.
- **Editorial Legal Typography**: `Cinzel` & `Newsreader` for dignified case titles; `Plus Jakarta Sans` for UI; `JetBrains Mono` for statutory citations and docket codes.

---

## 🏛️ Platform Portions (Expanded Architecture)

The application is structured into five accessible, specialized modules:

1. **🔍 AI Remedy Console & Search**:
   - Natural language search field with real-time scoring.
   - Quick topic presets: *Unlawful Detention*, *Custodial Torture*, *Bulldozer Demolition*, *Forced Labour & Bondage*, *Caste Access Denial*, and *Peaceful Assembly (Sec 163 BNSS)*.
   - Direct Legal Finding & Immediate 0–24 Hour Procedural Roadmap.
   - **Progressive Precedent Stream**: Smooth, staggered discovery of landmark Supreme Court rulings.
2. **📚 Landmark Precedent Library**:
   - Comprehensive repository of 11+ landmark Supreme Court authorities (*D.K. Basu*, *Arnesh Kumar*, *Rudul Sah*, *Nilabati Behera*, *Paramvir Singh Saini*, *Olga Tellis*, *Sudama Singh*, *Bandhua Mukti Morcha*, *PUDR*, *Prathvi Raj Chauhan*, *Anuradha Bhasin*).
   - Real-time search by case name, citation, or right.
3. **📜 BNSS & Treaty Comparative Codex**:
   - Side-by-side concordance table mapping BNSS 2023, BNS 2023, BSA 2023 against legacy CrPC/IPC sections and international treaty provisions.
4. **✍️ Procedural Motion Drafter**:
   - Auto-generates complete, ready-to-file legal petitions:
     - *Habeas Corpus Petition (Article 226)*
     - *Search Warrant Application (Section 100 BNSS / Sec 97 CrPC)*
     - *Independent Medical Examination Prayer (Section 53/54 BNSS)*
     - *Digital Evidence & CCTV Preservation Legal Notice*
   - Includes one-click copy and clean print formatting.
5. **🆘 Legal Aid & Emergency Directory**:
   - Institutional helpline directories: NALSA (15100), District Legal Services Authorities (DLSA), 24/7 Duty Magistrate protocols, and NHRC emergency cells.

---

## 🤖 Google Gemini AI Environment

The platform features a hybrid AI architecture:
- Directly connects to Google Gemini models for live natural language query interpretation.
- API keys or tokens are managed locally via browser `localStorage` to ensure full user privacy and prevent credential leakage.
- Autonomous fallback to a comprehensive Constitutional Reasoning Engine for uninterrupted, high-accuracy offline operation.

---

## 🚀 Deployment & Local Setup

### Live Deployment
Visit: **[https://dhananan.github.io/Humanknow/](https://dhananan.github.io/Humanknow/)**

### Running Locally
```bash
git clone https://github.com/DHANANAN/Humanknow.git
cd Humanknow
# Open index.html directly in any modern browser:
# start index.html
```

---

## 📜 License

MIT License. Designed and built as an open-access legal technology contribution.

