# 🌱 Episode Research: Carbon Capture

> **Podcast Series:** Climate Technology & Geoengineering  
> **Branch:** `carbon-capture`  
> **Last Updated:** September 2026  
> **Status:** Active Research

---

## 📌 Episode Overview

This episode covers **Carbon Dioxide Removal (CDR)** — the family of technologies and approaches designed to remove CO₂ directly from the atmosphere or point sources. This spans Direct Air Capture (DAC), Bioenergy with Carbon Capture and Storage (BECCS), enhanced weathering, forest carbon markets, and soil carbon sequestration.

---

## 🔭 Key GitHub Projects Discovered

### 1. [openair-collective/openair-cyan](https://github.com/openair-collective/openair-cyan)
- **Stars:** 76 ⭐ | **Language:** Python | **Status:** 🟡 MAINTAINED (last commit Feb 2024)
- **Description:** DIY small-scale open hardware direct air carbon capture device. OSHWA-certified (UID US001095).
- **Relevance:** The ultimate "citizen DAC" story — open-source hardware reaching climate infrastructure.

### 2. [carbonplan/cdr-database](https://github.com/carbonplan/cdr-database)
- **Stars:** 29 ⭐ | **Language:** JavaScript | **Status:** 🟡 MAINTAINED (last commit Feb 2025)
- **Description:** A public database of reports on carbon removal projects and technologies, covering permanence, additionality, co-benefits, and risks.
- **Relevance:** The most comprehensive open-source CDR project evaluation framework publicly available. CarbonPlan is the de facto independent auditor of voluntary carbon markets.

### 3. [carbonplan/forest-risks](https://github.com/carbonplan/forest-risks)
- **Stars:** 35 ⭐ | **Language:** Jupyter Notebook | **Status:** 🟠 INACTIVE (last commit Nov 2022)
- **Description:** Statistical models of forest carbon potential and risks, including wildfire, drought, and pest-driven carbon loss scenarios.
- **Relevance:** Directly challenges the permanence assumptions of forest-based carbon offsets. Used in landmark papers questioning California's forest carbon buffer pool.

### 4. [CliMA/ClimaLand.jl](https://github.com/CliMA/ClimaLand.jl)
- **Stars:** 71 ⭐ | **Language:** Julia | **Status:** 🟢 ACTIVE (last commit Jun 2026)
- **Description:** CliMA's land model, simulating soil, vegetation, and land-surface processes.
- **Relevance:** Essential for quantifying natural carbon sinks and evaluating nature-based CDR solutions.

### 5. [ClimateMARGO/ClimateMARGO.jl](https://github.com/ClimateMARGO/ClimateMARGO.jl)
- **Stars:** 73 ⭐ | **Language:** Julia | **Status:** 🟠 INACTIVE (last commit Oct 2023)
- **Description:** MARGO framework includes carbon Removal (R) as one of four climate levers.
- **Relevance:** Models CDR deployment rates and costs within an integrated climate-economic framework.

### 6. [openair-collective/openair-sorbent-tester](https://github.com/openair-collective/openair-sorbent-tester)
- **Stars:** 3 ⭐ | **Language:** Python | **Status:** 🟡 MAINTAINED (last commit Jan 2026)
- **Description:** Open-hardware sorbent tester for moisture swing DACC sorbents.
- **Relevance:** The "lab in a box" for DIY carbon capture research.

---

## 📊 Commit Trend Analysis: openair-collective/openair-cyan

| Commit | Author | Date | Message |
|--------|--------|------|---------|
| b5422b3 | KCollins | 2/12/2024 | Update README.md — added OSHWA UID link |
| b164257 | KCollins | 2/12/2024 | Add files via upload |
| 828f496 | KCollins | 2/12/2024 | Added OSHWA UID logo (OSHWA UID US001095) |
| b731cd8 | KCollins | 2/12/2024 | Add files via upload |
| 4b08fb3 | KCollins | 2/12/2024 | Create CITATION.cff |
| 859bfa8 | KCollins | 2/12/2024 | Update README.md |
| d12008e | DaOfficialWizard | 7/20/2022 | Update README.md |
| b8621ba | ZanzyTHEbar | 5/17/2022 | add files to improve useability |
| d025674 | DaOfficialWizard | 5/15/2022 | Update README.md |
| 784ace5 | DaOfficialWizard | 5/15/2022 | Update README.md |

**Trend:** Three activity bursts — (1) May 2022: initial community building (DaOfficialWizard, ZanzyTHEbar); (2) Feb 2024: formalization burst (KCollins — OSHWA certification, citation file, README polish). **Last commit Feb 2024** (28+ months ago). Got OSHWA-certified but then went quiet.

---

## 📊 Commit Trend Analysis: carbonplan/cdr-database

| Commit | Author | Date | Message |
|--------|--------|------|---------|
| 08fa4d9 | Shane Loeffler | 2/11/2025 | Merge PR #266 from carbonplan/Shane98c/rm-ga |
| f4dc9ab | Shane Loeffler | 2/10/2025 | Merge branch 'main' into Shane98c/rm-ga |
| 2213b8e | Shane Loeffler | 2/10/2025 | remove google analytics |
| 8d94dba | Shane Loeffler | 2/7/2025 | Merge PR #265 from carbonplan/plausible |
| 1f91cd8 | Shane Loeffler | 2/6/2025 | use script |
| 5055d4c | Shane Loeffler | 2/5/2025 | fix prettier |
| 07fb6aa | Shane Loeffler | 2/4/2025 | keep tracking for now |
| 9628fae | Shane Loeffler | 2/4/2025 | swap to plausible |

**Trend:** All 8 commits are from Feb 2025 — a single maintenance sprint focused on switching from Google Analytics to Plausible. **Shane Loeffler is the sole contributor.** Research complete, policy uptake phase.

---

## 🎙️ Podcast Implications

1. **The DAC Software Desert** — Carbon capture has billion-dollar startups but only 76 stars of open-source hardware on GitHub.
2. **Open-Source Hardware Hits a Certification Ceiling** — openair-cyan got OSHWA certified in Feb 2024 (a major milestone), then stalled. Certification requires commitment, but sustained development requires different incentives.
3. **CarbonPlan: Research Complete, Policy Uptake** — The only recent activity is removing Google Analytics and switching to Plausible. This is a mature project: the science is locked in, now it's infrastructure hygiene.

> **Suggested Angle:** *"The DAC Software Desert" — Why carbon capture has billion-dollar startups but only 76 stars of open-source hardware on GitHub.*
