# 🌊 Episode Research: Ocean Intervention

> **Podcast Series:** Climate Technology & Geoengineering  
> **Branch:** `ocean-intervention`  
> **Last Updated:** September 2026  
> **Status:** Active Research

---

## 📌 Episode Overview

This episode covers **Ocean-Based Climate Interventions** — techniques including Ocean Alkalinity Enhancement (OAE), Iron Fertilization, Seaweed/Kelp Cultivation for carbon sequestration, and Artificial Upwelling. The ocean covers 71% of Earth's surface and has absorbed ~90% of excess heat from climate change.

---

## 🔭 Key GitHub Projects Discovered

### 1. [CliMA/Oceananigans.jl](https://github.com/CliMA/Oceananigans.jl)
- **Stars:** 1,333 ⭐ | **Language:** Julia | **Status:** 🟢 FLAGSHIP ACTIVE
- **Description:** Fast, friendly, flexible ocean-flavored fluid dynamics on CPUs and GPUs. The leading open-source ocean simulation framework.
- **Relevance:** Foundational simulation engine for modeling ocean circulation, mixing, and tracer transport — essential for evaluating OAE, iron fertilization, and heat/CO₂ uptake scenarios.
- **Notable:** GPU acceleration (NVIDIA CUDA, AMD ROCm), distributed computing, immersed boundary methods, Zarr I/O for cloud-native data.

### 2. [CliMA/OceanParameterizations.jl](https://github.com/CliMA/OceanParameterizations.jl)
- **Stars:** 22 ⭐ | **Language:** Julia | **Status:** 🟡 MAINTAINED (last update Feb 2026)
- **Description:** Machine learning and uncertainty quantification for climate model parameterizations using differentiable and probabilistic programming.
- **Relevance:** Addresses subgrid-scale mixing processes that determine how interventions (alkalinity, iron) disperse in the real ocean.

### 3. [NOAA-GFDL/SM2](https://github.com/NOAA-GFDL/SM2)
- **Stars:** 1 ⭐ | **Language:** Fortran | **Status:** 🔵 INSTITUTIONAL
- **Description:** GFDL Slab Ocean Model — NOAA's Geophysical Fluid Dynamics Laboratory ocean component.
- **Relevance:** Represents the institutional/operational side of ocean climate modeling. Fortran legacy vs. Julia newcomer — the generational divide.

### 4. [CrayLabs/NCAR_ML_EKE](https://github.com/CrayLabs/NCAR_ML_EKE)
- **Stars:** 20 ⭐ | **Language:** Jupyter Notebook | **Status:** 🟡 MAINTAINED (last update Aug 2026)
- **Description:** Using Machine Learning at Scale in HPC Simulations with SmartSim — an application to ocean climate modeling.
- **Relevance:** The intersection of AI and earth system simulation.

### 5. [CliMA/ClimaLand.jl](https://github.com/CliMA/ClimaLand.jl)
- **Stars:** 71 ⭐ | **Language:** Julia | **Status:** 🟢 ACTIVE (last update Jun 2026)
- **Description:** CliMA's land model — includes coastal and wetland processes relevant to blue carbon.
- **Relevance:** Coastal wetlands (mangroves, salt marshes, seagrasses) are among the most carbon-dense ecosystems on Earth. Blue carbon as nature-based ocean intervention.

---

## 📊 Commit Trend Analysis: CliMA/Oceananigans.jl

| Commit | Author | Date | Message |
|--------|--------|------|---------|
| aca5970 | Ali Ramadhan | 9/17/2026 | Restore closure fields from checkpoints when `closure` is a tuple (#6006) |
| ab99a39 | Ali Ramadhan | 9/16/2026 | Fix the face spacing above partial cells on `PartialCellBottom` grids (#6013) |
| 9ddbbb1 | Ali Ramadhan | 9/16/2026 | Apply the linear operator once per `ConjugateGradientSolver` iteration (#6012) |
| 1c8fe39 | Ali Ramadhan | 9/16/2026 | Bounce Lagrangian particles off immersed boundaries (#6005) |
| c1655e9 | Tomás Chor | 9/16/2026 | Add `TimeDerivative` for computing ∂ₜ of outputs during a simulation (#5823) |
| 72285df | Ali Ramadhan | 9/16/2026 | `SplitRungeKuttaTimeStepper`: evaluate time-dependent forcings and BCs at the correct time (#6009) |
| 23020f1 | Ali Ramadhan | 9/16/2026 | Fix the stage Δt used by AVID + RK3 (#6008) |
| d03dfdf | Ali Ramadhan | 9/16/2026 | Keep non-finite values in immersed cells out of the vertically implicit column solve (#5991) |

**Trend:** **EXTREMELY ACTIVE — 8 commits in 2 days**, PR-based workflow with detailed comments (2 on #6006). Ali Ramadhan is the primary contributor (7/8 commits). Recent work spans: checkpoint handling, partial cell grids, linear solver efficiency, Lagrangian particle dynamics, time-stepping accuracy, and immersed boundary methods.

**Primary Contributor:** Ali Ramadhan — core developer driving most of the recent work on numerical methods and solver performance.

---

## 🎙️ Podcast Implications

1. **The Ocean Model That Commits Daily** — 8 commits in 2 days across a 1,333-star codebase. NOAA-GFDL's operational models get commits measured in months, not hours.
2. **Ali Ramadhan = the Backbone** — 7 of 8 recent commits, spanning numerical methods, physics, and I/O. A singular devoting driving the project.
3. **Julia Advantage is Real** — PR-based workflow, rapid iteration, modern testing infrastructure. Commit messages reference sophisticated numerical methods (AVID+RK3, SplitRungeKuttaTimeStepper) that would be handwritten in Fortran in legacy models.
4. **Ocean Intervention Modeling is Becoming Tractable** — Immersed boundary methods and partial cell grids are exactly the features needed to model OAE plume dispersal, iron fertilization transport, and upwelling simulation.

> **Suggested Angle:** *"The Ocean Model That Commits Daily" — How a Caltech/MIT/NASA student project with 1,333 stars is out-committing billion-dollar institutional Fortran code, and what it means for ocean geoengineering research.*

> **Key Technical Themes for Audio:**
> - **Immersed boundary methods** = modeling complex coastlines and bathymetry for local ocean intervention scenarios
> - **Partial cell grids** = accurate representation of continental shelves where kelpin cultivation and OAE deployment would occur
> - **Lagrangian particle tracking** = simulating how an alkalinity plume disperses and mixes in the ocean over months/years
> - **Checkpoint/restoration** = ability to run long-duration climate simulations spanning months of wall-clock time
