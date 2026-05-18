# Dual Frame Research Group

The Dual-Frame Research Group develops a research program in the **Reciprocal System lineage** — beginning from Larson's motion-first postulates and deriving physical structure from them.

The current center of gravity is the **compact-fiber reconstruction**: a finite carrier

$$F = \mathbb{Z}_4 \times \mathbb{Z}_4 \times \mathbb{Z}_8$$

derived as the *canonical admissibility structure* for stable local discrete scalar motion. The two $\mathbb{Z}_4$ factors are magnetic; the $\mathbb{Z}_8$ factor is electric and functions as a degree-2 cover over the magnetic closure scale. The carrier has $|F| = 128$ states and sector capacities $N_m = 4$, $N_e = 8$.

From this single finite structure and its readout rules, the program derives results across atomic, radiation, quantum-representational, gravitational, constants, materials, and galactic-rotation domains — with no per-domain fitted parameters introduced at the carrier level.

---

## Published Results

| Domain | Paper | Key result | DOI |
|--------|-------|------------|-----|
| **Foundations** | Paper I — Canonical Admissibility | Necessity proof: the compact fiber is the unique admissibility structure under P1–P5, A5, P5′ | [Zenodo](https://zenodo.org/records/19423877) |
| **Atomic structure** | Paper II — Transport, Screening, Thresholds | 11 screening slopes/intercepts for IE, EA, fine-structure splitting, polarizability from carrier geometry; ~95 atom-observable comparisons at ~5.7% WMAE vs. NIST; zero per-element fitted parameters | [Zenodo](https://zenodo.org/records/19426035) |
| **Quantum & gravity** | Paper III — Hilbert, Born Rule, Metric | Hilbert space, Born rule, Bell correlations, measurement projection derived as representational consequences of the carrier; effective coordinate-time metric reproducing $\beta = \gamma = 1$ and four classical Solar System tests | [Zenodo](https://zenodo.org/records/19434653) |
| **Radiation** | Radiation from the Compact Fiber | Polarization, single-photon interference, Bell correlation, HOM bunching, OAM quantization, photoelectric architecture from one radiation-side hierarchy | [Zenodo](https://zenodo.org/records/19688975) |
| **Finite readout** | Readout Representations & Matching | Character-Readout Classification Theorem; factors 1/8, 1/4, 7/8, 1/16, 1/32, 128 as finite-character operations; no-retuning audit framework | [Zenodo](https://zenodo.org/records/19783370) |
| **Fine-structure constant** | Compact-Fiber $\alpha$ Prediction | Quartic equation with positive root $x_{\mathrm{fiber}} = 137.0359991771859\ldots$; no measured $\alpha$ input, no continuously adjusted coefficient | [Zenodo](https://zenodo.org/records/20100799) |
| **Planck & gravitational constants** | Secondary-Mass Context | Distinguishes $s_h = m + e$ (Planck/action) from $s_G = m$ (gravitational); residuals $\approx -7.8$ ppm ($h$), $+160.2$ ppm ($G$), $-32.8$ ppm ($\alpha_G^{(p)}$) | [Zenodo](https://zenodo.org/records/20100766) |
| **Materials** | Cation Coordination Admissibility | Fixed-input rule for cation CN in ionic crystals; ≥98.2% agreement across 17,947 structures (oxides, fluorides, chlorides, sulfides); zero fitted constants | [Zenodo](https://zenodo.org/records/20250407) |
| **Galactic rotation** | Galactic Rotation I | Zero-parameter rotation-curve model on 171 SPARC galaxies; median $\chi^2$/pt = 10.71 vs. MOND 11.25; covering degree $d = 2$ confirmed by sharp empirical selection | [Zenodo](https://zenodo.org/records/19446510) |
| **Galactic rotation** | Galactic Rotation II — Regime Split | Regime-split extension; median $\chi^2$/pt improves to 10.05; giant-class median drops from 47.34 to 29.11 | [Zenodo](https://zenodo.org/records/19548757) |

---

## Why a Closure Structure?

If atoms are stable combinations of scalar motion, their rotational displacements cannot be open-ended — a stable combination must complete a finite pattern. Larson's atomic triplets already show distinct magnetic and electric roles. When arranged in their natural order, they exhibit a cyclic, sinusoidal-phase-like pattern. The compact-fiber work asks: *what finite structure is required for those triplets to close?*

Candidate carriers were constrained by three rules: **compactness** (finite and closed), **minimality** (no unused sectors), and **fidelity to Larson** (preserves scalar motion, displacement, unit limits, and magnetic/electric role distinction). The result is $F = \mathbb{Z}_4 \times \mathbb{Z}_4 \times \mathbb{Z}_8$.

The carrier gives finite closure capacities $N_m = 4$ and $N_e = 8$. The degree-2 electric cover gives the scale $1/(2N_e) = 1/16$. Combined magnetic-electric transport gives $1/(N_m N_e) = 1/32$. These scales are not introduced to fit any single table — they arise from the carrier and recur across independent applications.

---

## Reading Order

The recommended entry point for new readers is **[rst-compact-fiber](https://github.com/arwells-research-group/rst-compact-fiber)**, which contains the foundational framework documents:

1. `foundations/POSTULATES.md`
2. `foundations/CORE_GEOMETRY.md`
3. `foundations/READOUT_CLASSES.md`
4. `foundations/DISPLACEMENT_ALGEBRA.md`
5. `foundations/CANONICAL_NOTATION.md`
6. `foundations/PART_I_CORE_FRAMEWORK.md`
7. `machinery/PART_II_GENERAL_DERIVED_MACHINERY.md`
8. `machinery/PROJECTION_AND_BRIDGE_STRUCTURE.md`
9. `machinery/UPSTREAM_VARIABLE_PREFERENCE.md`
10. `machinery/BRIDGE_VARIABLE_CROSSWALK.md`

For the broader program map, terminology, and later-layer materials, see **[sigma-order-core](https://github.com/arwells-research-group/sigma-order-core)**.

---

## Repository Structure

This research program uses two GitHub organizations:

- **[arwells-research-group](https://github.com/arwells-research-group)** — program-level orientation, core framework, and repository map (you are here)
- **[arwells-research](https://github.com/arwells-research)** — individual paper repositories with reproducibility materials, experiments, and data pipelines

### Core framework (arwells-research-group)

| Repository | Role |
|------------|------|
| [`rst-compact-fiber`](https://github.com/arwells-research-group/rst-compact-fiber) | Compact-fiber trunk: postulates, carrier geometry, readout classes, displacement algebra, derived machinery |
| [`sigma-order-core`](https://github.com/arwells-research-group/sigma-order-core) | Broader program hub: Σ-Order / Dual-Frame projection architecture, Σ₂ methodology, repository map |

### Paper and reproducibility repositories (arwells-research)

| Repository | Paper |
|------------|-------|
| [`compact-fiber-admissibility`](https://github.com/arwells-research/compact-fiber-admissibility) | Paper I — Canonical admissibility |
| [`compact-fiber-atomic-structure`](https://github.com/arwells-research/compact-fiber-atomic-structure) | Paper II — Atomic structure |
| [`compact-fiber-quantum-gravity`](https://github.com/arwells-research/compact-fiber-quantum-gravity) | Paper III — Quantum & gravitational structure |
| [`compact-fiber-galactic-rotation`](https://github.com/arwells-research/compact-fiber-galactic-rotation) | Galactic rotation I & II |

Additional paper repositories exist under `arwells-research` for radiation, finite readout, constants-sector, and materials papers.

---

## Program Layers

The compact-fiber reconstruction is the deepest current line, but the broader program includes additional layers:

- **Reciprocal System lineage** — motion-first ontological starting point (Larson's postulates)
- **Compact-fiber reconstruction** — finite carrier, closure structure, derived observables (current center of gravity)
- **Σ-Order / Dual-Frame** — reduced projection architecture preserving structural residue beyond standard QM
- **Σ₂ framework** — projection-closure admissibility methodology

These are not unrelated theories. They are different layers of one developmental research program.

---

## Naming and Lineage

This program historically used the name **Dual-Frame Theory (DFT)**. Because "DFT" is widely associated with density functional theory, the public-facing name of the reduced projection branch is now **Σ-Order theory (ΣO)**. The broader program is not exhausted by ΣO — the compact-fiber carrier level is deeper than the projection level.

---

## Research Standards

The research program operates under audit-grade, falsifiable, and independently reproducible standards:

- Parameters are frozen prior to evaluation
- Public datasets are cited and externally accessible
- Scripts regenerate reported figures and tables from raw data
- Each project defines an explicit falsification surface
- Negative results are preserved and logged
- Claims are limited to what the measurements warrant

---

> **Status:** Early-stage research program maintained by a non-dedicated researcher.
> Structural completeness claims remain falsifiable and under active stress-testing.
> Not all repositories are public yet.
