# ☀️ Episode Research: Solar Geoengineering

> **Podcast Series:** Climate Technology & Geoengineering  
> **Branch:** `solar-geoengineering`  
> **Last Updated:** September 2026  
> **Status:** Active Research

---

## 📌 Episode Overview

This episode covers **Solar Radiation Management (SRM)** — the class of geoengineering techniques that aim to reduce incoming solar radiation to cool the Earth. Key subtopics include Stratospheric Aerosol Injection (SAI), Marine Cloud Brightening (MCB), and space-based reflectors.

---

## 🔭 Key GitHub Projects Discovered

### 1. [CliMA/ClimaAtmos.jl](https://github.com/CliMA/ClimaAtmos.jl)
- **Stars:** 119 ⭐ | **Language:** Julia | **Status:** 🟢 EXTREMELY ACTIVE
- **Description:** The Climate Modelling Alliance's atmosphere model, designed to leverage data assimilation and machine learning for modeling and calibrating subgrid-scale processes.
- **Relevance to Solar Geoengineering:** Models atmospheric radiative transfer, albedo feedback, and cloud microphysics — all critical for simulating SAI and MCB scenarios. The `CouplerAlbedo` work is directly what SRM simulators need.
- **Notable:** Uses GPU acceleration for high-resolution global simulations.

### 2. [CliMA/Insolation.jl](https://github.com/CliMA/Insolation.jl)
- **Stars:** 17 ⭐ | **Language:** Julia | **Status:** 🟡 MAINTAINED
- **Description:** Calculates solar radiation and solar geometry, including solar zenith angle, azimuth angle, and incoming solar radiation at any point on Earth.
- **Relevance:** Core library for computing the baseline solar forcing that geoengineering interventions would modify. Essential dependency for any SRM simulation.

### 3. [ClimateMARGO/ClimateMARGO.jl](https://github.com/ClimateMARGO/ClimateMARGO.jl)
- **Stars:** 73 ⭐ | **Language:** Julia | **Status:** 🟠 INACTIVE (last commit Oct 2023)
- **Description:** Julia implementation of MARGO — an idealized climate-economic modelling framework for optimizing trade-offs between **M**itigation, **A**daptation, carbon **R**emoval, and **G**eo-engineering **O**ptions.
- **Relevance:** Directly models geoengineering as one of four climate levers. Useful for economic framing of solar geoengineering debates.

### 4. [JdeJong96/sai-git](https://github.com/JdeJong96/sai-git)
- **Stars:** — | **Language:** Jupyter Notebook | **Status:** 🟠 INACTIVE (last commit Aug 2025)
- **Description:** Tools for analyzing CESM geoengineering climate data, specifically focused on Stratospheric Aerosol Injection scenarios.

### 5. [jf678-cornell/CIDER](https://github.com/jf678-cornell/CIDER)
- **Stars:** 4 ⭐ | **Language:** Jupyter Notebook | **Status:** 🟡 RECENT (last commit March 2026)
- **Description:** The Climate Intervention Dynamical Emulator — a lightweight, reduced-order model for exploring highly dynamic geoengineering scenarios.
- **Relevance:** Emulator approach allows rapid prototyping of geoengineering scenarios without running full Earth System Models.

### 6. [brandonhimpfen/awesome-geoengineering](https://github.com/brandonhimpfen/awesome-geoengineering)
- **Stars:** 4 ⭐ | **Language:** Python | **Status:** 🟡 MAINTAINED (last commit Sep 2026)
- **Description:** A curated list of projects, research, organizations, tools, and resources related to geoengineering.
- **Relevance:** The best starting point for literature review and discovering additional SRM tools and datasets.

---

## 📊 Commit Trend Analysis: ClimateMARGO/ClimateMARGO.jl

| Commit | Author | Date | Message |
|--------|--------|------|---------|
| d916f36 | Fons van der Plas | 8/17/2026 | Update README.md |
| 6d9ba7a | Fons van der Plas | 8/17/2026 | Update README.md |
| 57d4da7 | Fons van der Plas | 10/18/2023 | Update unit_conversions.jl with comment from #86 |
| fbbe619 | Fons van der Plas | 7/6/2023 | add link to pluto in readme |
| 5063c42 | Fons van der Plas | 11/14/2022 | Update Project.toml |
| 12a0ce6 | Fons van der Plas | 11/12/2022 | JuMP and Ipopt compat upgrade (#85) |
| 32e66fd | Henri Drake | 2/10/2022 | Removed deprecated web apps |
| d609d49 | Henri Drake | 2/4/2022 | Added CITATION.bib |
| b2d9228 | Henri Drake | 1/13/2022 | Fixed typo |
| 8a7e012 | Henri Drake | 1/12/2022 | Updated arguments for doc version deployment |

**Trend:** Two active periods — (1) 2022 development surge by Henri Drake (core architecture, docs, citations); (2) 2023 maintenance by Fons van der Plas (compatibility upgrades). **INACTIVE since Oct 2023** (31+ months). MARGO is a research artifact, not a living codebase.

---

## 🎙️ Podcast Implications

1. **The Geoengineering Code Gap** — The most consequential climate technology has the least developed software. MARGO.jl's last substantive commit was 31 months ago.
2. **Julia vs. Everything Else** — While geoengineering application code is stagnant, the Julia-based climate simulation infrastructure beneath it is accelerating daily.
3. **Two Maintainers, Two Eras** — Henri Drake built the core; Fons van der Plas kept it running. The creator-to-maintainer transition is a common story in open-source climate software.

> **Suggested Angle:** *"The Geoengineering Code Gap" — Why the most consequential climate technology has the least developed software, and what the Julia ecosystem is doing about it.*
