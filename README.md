---
layout: default
title: Lunar Formation via Triple Phase Transition
---

# Lunar Formation via Triple Phase Transition in the Differentiating Proto-Earth

**Michel Debailleul** — Geophysicist, Université libre de Bruxelles (ULB)
ORCID: [0009-0003-1222-1433](https://orcid.org/0009-0003-1222-1433)
Email: michel.debailleul@yahoo.fr
License: CC BY 4.0

[![DOI](https://img.shields.io/badge/DOI-Zenodo-blue)](https://doi.org/10.5281/zenodo.20626204)
[![EarthArXiv](https://img.shields.io/badge/EarthArXiv-preprint-orange)](https://doi.org/10.31223/X5XB6H)
[![OSF](https://img.shields.io/badge/OSF-mirror-green)](https://doi.org/10.17605/OSF.IO/XTN4Q)

🇫🇷 [Lire en français](README.fr.md)

---

## Abstract

Where does the Moon come from?

For fifty years, the giant impact has been the default answer. But it does not explain the Earth–Moon isotopic identity. It does not explain the crustal dichotomy. It does not explain the 350-Myr delay of the terrestrial dynamo. It does not explain the Chang'e-6 olivines.

This work proposes a different answer: the Moon was born from the Earth itself — not from a collision, but from the internal instability of a fully molten, rapidly rotating proto-Earth.

The logic is explicit. Accretion energy exceeds the energy required to melt the entire silicate mantle by a factor of ≈155. The proto-Earth was therefore a magma body rotating in 3.5 hours, without a Moon to stabilise it, its axis wobbling chaotically within [40°,70°] in its own frame.

A single engine — the progressive segregation of iron and nickel toward the forming core — drives three coupled transitions: the emergence of a Coherent Magmatic Torus, two to three hypersonic ejections that build the Moon layer by layer, and the delayed onset of the terrestrial dynamo (≈350 Myr, no free parameter).

Every lunar layer is a frozen archive of the state of Hadean differentiation at the moment of its accretion.

This is not a philosophical claim. It is a set of quantitative, falsifiable predictions.

One or more seismic interfaces between 200 and 530 km depth — where successive layers, increasingly iron-rich toward the interior, produce a measurable echo — will be tested by Chang'e-7 in August 2026 and by Artemis III. Mantle ejecta from the South Pole–Aitken basin are predicted to carry a high Fe/Si signature, testable in Chang'e-6 samples and by Artemis III direct sampling.

This version adds a distributed treatment of angular momentum transport by ejecta and a corrected, dimensionally consistent derivation of the double-well potential governing the ejection mechanism, yielding three new falsifiable predictions (P20–P22). It also introduces a complementary geochemical test based on the South Pole–Aitken (SPA) basin, and acknowledges two remaining limitations: impact mixing in SPA ejecta (L9) and the current absence of direct deep-mantle samples (L10) — both of which Chang'e-7 and Artemis III are expected to help address.

All hypotheses are ranked. All limitations are acknowledged.

The theory will stand or fall on the data.

---

## 🔴 ▶ LAUNCH THE INTERACTIVE SIMULATION

[**Open the interactive simulation**](https://orion4622.github.io/moon-formation-triple-phase-transition/Animation_Formation_de_la_Lune_v2.html) — No installation required, opens directly in any browser.

---

## Five Arguments for ε ∈ [40°, 70°]

1. **Absence of tidal stabiliser** — logically necessary: no Moon → no lunar tidal damping
2. **Laskar et al. (1993)** — without a satellite, chaotic zone extends from 0° to ≈85°
3. **Rapid rotation at 3.5 h** — precession too fast for Laskar-type resonances; obliquity diffuses stochastically
4. **Continuous planetesimal bombardment** — τ_pert ≪ τ_relax ≈ 10⁶ yr
5. **T-Tauri CME torques** — daily impulsive perturbations on the spin vector

---

## Falsifiable Predictions

| ID | Prediction | Mission | Timeline |
|----|------------|---------|----------|
| P1 | Seismic interface at d ≈ 200–315 km (N=3) or ≈ 177 km (N=2), \|R\| ∈ [0.01, 0.04] | Chang'e 7, FSS, LEMS, Artemis III | August 2026 |
| P2 | Seismic asymmetry, nearside vs. farside | Multi-station seismic / tomography | 2026–2030 |
| P3 | Fe/Si gradient increasing with depth | Chang'e-6, Artemis III | 2026–2029 |
| P4 | Dynamo delay 290–360 Myr, gradual paleointensity growth (no abrupt onset) | Jack Hills zircons | Ongoing |
| P5 | Instability window ε ∈ [57°, 70°] | N-body obliquity simulations | — |
| P6 | Polar ejecta signature at high latitudes (South Pole) | Chang'e 7 (South Pole) | August 2026 |
| P7 | Hf-W signature: 100 ± 10 Myr after CAIs (vs. 60 ± 10 Myr for giant impact) | Artemis III | 2028–2029 |
| P8 | Formation age > 4.45 Ga (LMO solidification ≠ formation) | Artemis III | 2028–2029 |
| P9 | Mare basalt melting depth compatible with Layer 1 | Apollo / Chang'e-5 geochemistry | — |
| P10 | Seismic interface at d ≈ 177 km for N = 2 (weak reflector, 150–200 km) | Chang'e 7, FSS | August 2026 |
| P17 | Capture efficiency f_cap ≳ 0.65–0.70, beyond the classical 10–55% disk-accretion interval | 3D SPH simulation | Pending (L1, L2) |
| P20 | Asymptotic regime indicator: true L_loss lies between monokinetic and broad-spectrum bounds | Monte Carlo simulation | Pending (L2) |
| P21 | Numerical closure of angular momentum budget to within ~5% | 3D SPH simulation | Pending (L1, L2) |
| P22 | Double-well emergence threshold: ~13% reduction in effective gravity required for ejection mechanism to activate | 3D SPH simulation | Pending (L1, L2) |

**Falsification condition (P1):** no phase conversion detected in the 200–530 km window after deployment of at least 3 seismic stations and detection of at least 10 lunar events with M > 2.5.

---

## Acknowledged Limitations

| # | Limitation | Status |
|---|------------|--------|
| L1 | Spontaneous CMT organisation | Qualitatively motivated; Priority 2 |
| L2 | Numerical value of f_cap | SPH simulation required |
| L3 | Cohesion at small scales | BiKH ≫ 1 at large scales |
| L4 | Dynamo delay ±50 Myr | Simple exponential model |
| L5 | Super-rigid rotation profile α > 1 | Physically motivated; Level-3 hypothesis |
| L6 | Flow → POB transition | Qualitative; SPH required |
| L7 | Crustal dichotomy | Qualitative; double remelting of farside accounted for |
| L8 | Rossby-wave speed in BH fluid | Channel analogue; open problem |
| L9 | Impact mixing in SPA ejecta | Complicates primary mantle identification |
| L10 | Absence of samples constraining the deep lunar mantle | No existing direct constraint; awaiting Artemis III |

---

## Validation Roadmap

1. **Priority 1 — Seismology:** Chang'e 7, FSS, LEMS, Artemis III (2026–2030)
2. **Priority 2 — 3D SPH simulations** on oblate Maclaurin spheroid (3–5 yr)
3. **Priority 3 — Geochemistry:** Fe/Si gradient, SPA basin (2026–2030)
4. **Priority 4 — Hf-W high-precision chronometry** (ongoing)
5. **Priority 5 — Mathieu resonance**, magma-atmosphere coupling
6. **Priority 6 — Rigorous derivation** of c_Rossby^(BH) (analytical, open problem)

---

## Canonical Deposits

| Platform | Identifier | Date | Status |
|----------|-----------|------|--------|
| Zenodo (all versions) | [10.5281/zenodo.20626204](https://doi.org/10.5281/zenodo.20626204) | June 23, 2026 | ✅ ⭐ |
| OSF | [10.17605/OSF.IO/XTN4Q](https://doi.org/10.17605/OSF.IO/XTN4Q) | June 23, 2026 | ✅ |
| Figshare | [10.6084/m9.figshare.32306832](https://doi.org/10.6084/m9.figshare.32306832) | — | ✅ |
| EarthArXiv | [10.31223/X5XB6H](https://doi.org/10.31223/X5XB6H) | Updated | ⏳ |
| HAL | hal-05648861 | Updated | ⏳ |
| ESSOAr | 10.22541/essoar.15003588 | Updated | ⏳ |
| GitHub | [Orion4622/moon-formation-triple-phase-transition](https://github.com/Orion4622/moon-formation-triple-phase-transition) | — | ✅ |
| PSJ/AAS | manuscript #AAS77321 | submitted May 27, 2026 | ⏳ |

---

## Repository Contents

| File | Description |
|------|-------------|
| `Moon_Formation_Triple_Phase_Transition_EN_21_06_2026.pdf` | Full manuscript — English (latest) |
| `La_formation_Lune_Triple_Transition_Phase_Fr-21_06_2026.pdf` | Manuscrit complet — français (dernière version) |
| `Animation_Formation_de_la_Lune_v2.html` | Interactive simulation |
| `Animation_Screen_Shot.png` | Simulation screenshot |
| `Double_Puits_Debailleul.png` | Double-well potential figure (FR) |
| `Double_Well_EN.png` | Double-well potential figure (EN) |

---

## Citation

DEBAILLEUL, M. (2026). *Lunar Formation via Triple Phase Transition in the Differentiating Proto-Earth.* Zenodo. https://doi.org/10.5281/zenodo.20626204

---

## About

A theoretical framework proposing that the Moon formed through a triple phase transition within the differentiating proto-Earth. The model links rheological, mechanical and magnetic transitions driven by progressive Fe–Ni segregation, and predicts testable lunar internal stratigraphy verifiable by Chang'e 7 seismic data (August 2026) and Artemis III (2028–2029).
