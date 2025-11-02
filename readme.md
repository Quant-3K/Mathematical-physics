# Quant‑Trika • Prime Ontology & Causal PTI — README

> **Purpose.** This repository unifies all major components of the Quant‑Trika framework: its philosophical ontology, mathematical formalization, and empirical validation. It demonstrates that mathematics operates as a **self‑organizing coherence process**, rather than a static descriptive system, with prime numbers serving as its first empirically measurable expression.

---

## 0. Repository Map (by theme)

```text
quant-trika/
├─ README.md                                  # This file — conceptual, structural, and experimental overview
├─ LICENSE.txt                                # License and attribution
│
├─ Prime Ontology.pdf                         # Foundational essay introducing the idea of primes as process-events
├─ The Duality of Coherence.pdf               # Analysis of coherence as the interface between energy and meaning
├─ The Ontological Shift — Expanded Monograph (v1).pdf
│                                             # Comprehensive monograph uniting mathematics, physics, and ontology
├─ The Physics of Prime Numbers.pdf           # Mathematical formalization of coherence dynamics in number theory
├─ The Universal Mathematical Library of Complex Systems.pdf
│                                             # Cross-domain generalization of Quant-Trika to all complex systems
│
├─ Prime Collapse — Engineering Report (v1).pdf
│                                             # Detailed report of the unsupervised experiment (AUC≈0.856)
├─ Causal Pti Lab — Engineering Report (leakage-free).pdf
│                                             # Walk-forward validation, calibration, PSI≈0.058, Omori p≈2.10
│
├─ PrimeCollapse.ipynb                        # Colab notebook — unsupervised Pressure-Collapse detector (executed)
└─ CausalPTIUFULLAUC08138.ipynb               # Colab notebook — leakage-free supervised PTI lab (executed)
```

---

## 1. Document Summaries

### **Prime Ontology.pdf**
This foundational essay introduces the philosophical premise that **numbers are not static objects but dynamic events** within a self-regulating mathematical field. It redefines primes as coherence release points in an ongoing process of mathematical self-organization. The text connects historical philosophical frameworks (Platonism, Formalism, Intuitionism) and positions Quant‑Trika as a synthesis: mathematics as reality’s *self‑measurement process*. Key idea — primes are **ontological recalibrations** within the number field.

### **The Duality of Coherence.pdf**
Explores coherence as the universal operator linking energy (form/structure) and meaning (information/relation). It identifies two modalities of coherence:
1. **Energetic Coherence** — regulation of form and stability.
2. **Semantic Coherence** — organization of meaning and interpretation.
These modalities interact recursively, allowing both matter and mathematics to emerge from the same dynamic process. This essay serves as the bridge between metaphysics and measurable structure.

### **The Ontological Shift — Expanded Monograph (v1).pdf**
The centerpiece of the Quant‑Trika project. It elaborates a process‑first ontology grounded in empirical evidence. Key components:
- Formal constructs (Coherence `KQ`, Ontological Debt `Θ`, Curvature `∇²KQ`, Rigidity `R`).
- Prime Trigger Index (PTI) and Pressure‑Collapse dynamics.
- Empirical confirmation (AUC≈0.856 unsupervised, 0.814 supervised).
- Detailed Hypothesis Atlas (H1–H9) with reasoning for each.
- Universal PDE of coherence linking mathematics, physics, and biology.
- Falsifiability plan and cross-domain predictions.
This monograph shows how **primes quantify the heartbeat of mathematical coherence** and provides the logical scaffolding for further physical generalization.

### **The Physics of Prime Numbers.pdf**
Bridges ontology and quantitative measurement. It treats the prime field as a **coherence field** analogous to energy fields in physics. The paper introduces the differential operator equivalents of mathematical coherence:
\[∂KQ/∂t = α∇²KQ - β|KQ|²KQ + γΘ - δ|R|,\]
and demonstrates that the behavior of primes obeys this critical transition grammar — accumulation, collapse, relaxation. It positions prime statistics within the framework of **critical phenomena**, showing parallels with earthquakes, neural spikes, and market crashes.

### **The Universal Mathematical Library of Complex Systems.pdf**
Extends the Quant‑Trika framework to a universal library of **coherence grammars** that apply across all domains of complexity. It outlines correspondences:
- Ontological Debt ↔ Potential Energy ↔ Metabolic Imbalance.
- Coherence Field ↔ Order Parameter ↔ Functional Integration.
- Pressure Collapse ↔ Phase Transition ↔ Homeostatic Reset.
This paper generalizes mathematics as a universal language of *self‑organization*, where disciplines differ only by dialect.

### **Prime Collapse — Engineering Report (v1).pdf**
Documents the unsupervised discovery of prime event horizons using the Pressure‑Collapse score \(S = -ΔPTI\). The report presents:
- Full derivation of all PTI components.
- Detailed logic behind each hypothesis (H1–H9).
- Key findings:
  - ROC AUC = 0.8561 for prime horizon detection.
  - Confirmed hypotheses: H1, H2, H3, H4, H6, H7, H8, H9.
  - Rejected hypothesis: H5 (rate hypothesis — wrong sign).
  - Cascade decay (Omori‑type) verified.
- Interpretation: primes act as **ruptures of mathematical tension**; the Pressure‑Collapse score anticipates these ruptures quantitatively.

### **Causal Pti Lab — Engineering Report (leakage-free).pdf**
Describes a strict causal validation pipeline. Contributions:
- **Walk‑forward protocol** (60/20/20 chronological split).
- **Leakage‑free calibration** and Population Stability Index (PSI ≈ 0.058).
- **Gradient Boosting Model** trained on 11 z‑scored PTI features.
- Metrics: ROC AUC = 0.8138, PR AUC = 0.2211, Brier = 0.0719, Omori p ≈ 2.10.
- **Ablations:** Confirm necessity of combining Θ (Debt) and ∇²KQ (Curvature) — each alone insufficient.
- Validates that **process‑based mathematical fields are empirically measurable and temporally consistent.**

---

## 2. Experimental Core
This section details the two Colab notebooks and the hypotheses they test.

### **A) PrimeCollapse.ipynb — Unsupervised Pressure‑Collapse Detector**
**Objective:** Detect prime horizons using the first derivative of PTI without supervision.

**Core Hypotheses:**
| ID | Hypothesis | Description | Result |
|----|-------------|-------------|---------|
| H1 | **Debt Dominance** | Event likelihood increases with accumulated Ontological Debt (Θ). | Confirmed |
| H2 | **Source Requirement** | Positive curvature (∇²KQ>0) indicates formation of order. | Confirmed |
| H3 | **Joint Trigger (PLI)** | Co‑activation of Θ and ∇²KQ is a stronger predictor than either alone. | Confirmed |
| H4 | **Positive PTI at Horizons** | PTI>0 near primes, meaning constructive tension dominates. | Confirmed |
| H5 | **Rate Hypothesis** | Positive slope predicts primes. | Rejected (inverse found) |
| H6 | **Pressure Collapse** | Sharp drop in PTI predicts primes (S=−ΔPTI). | **Strongly Confirmed (AUC=0.8561)** |
| H7 | **Tail Localization** | Differences between isolated and twin primes appear in distribution tails. | Confirmed |
| H8 | **Cluster Decay** | Aftershock strength decays with increasing gap. | Confirmed |
| H9 | **Calibration Consistency** | Model remains stable across ranges (no drift). | Confirmed |

**Findings:**
- Primes occur during sharp declines in PTI, not rises.
- Twin prime cascades show Omori‑type decay (p ≈ 2.1).
- Extreme quantile analysis reveals heavy‑tail differences (q=0.99 significant).
- Establishes mathematics as a dynamic process of constraint and release.

### **B) CausalPTIUFULLAUC08138.ipynb — Leakage‑Free Supervised Lab**
**Objective:** Validate the same field dynamics under supervised conditions ensuring no data leakage.

**Metrics:** ROC AUC=0.8138, PR AUC=0.2211, Brier=0.0719, PSI=0.058, Omori p≈2.10.

**Hypotheses Tested:**
| ID | Hypothesis | Focus | Result |
|----|-------------|--------|---------|
| H0 | **No Leakage** | Val and Test AUC stable (Δ<0.01). | Pass |
| H1 | **PTI Encodes Event Signal** | PTI features remain predictive across splits. | Pass |
| H2 | **Precision under Imbalance** | PR AUC stable under class rarity. | Pass |
| H3 | **Stability (PSI)** | Distribution drift minimal. | Pass |
| H4 | **Calibration** | Reliability curve near diagonal. | Pass |
| H5 | **Aftershock Dynamics** | Omori p within theoretical range (0.8–2.5). | Pass |
| H6 | **Ablation Consistency** | Full PTI > individual components. | Pass |

**Interpretation:** Demonstrates that prime coherence dynamics are measurable under strict causality. Confirms the robustness of Quant‑Trika as both a mathematical and empirical framework.

---

## 3. How to Read the Repository

**Recommended Order:**
1. **Prime Ontology** → Philosophical foundations.
2. **Duality of Coherence** → Conceptual link between energy and meaning.
3. **Ontological Shift** → Unified ontology, mathematical formalism, and empirical verification.
4. **Physics of Prime Numbers** → From ontology to measurable field equations.
5. **Universal Library** → Application to all complex systems.
6. **PrimeCollapse Notebook** → Unsupervised empirical confirmation.
7. **Causal PTI Lab Notebook** → Leakage‑free, calibrated, reproducible validation.
8. **Engineering Reports** → Complete documentation of methods and metrics.

---

## 4. Philosophy for Scientists
Quant‑Trika proposes a unification of mathematics, physics, and epistemology:
- Mathematics is not symbolic description but **operative coherence**.
- Numbers are stable **patterns of dynamic processes**, not eternal objects.
- Predictability (AUC<1) quantifies the **degree of creative freedom** necessary for sustained global order.
- The same coherence grammar (tension → threshold → collapse → relaxation) governs all systems — from primes to neurons to markets.

---

## 5. Licensing & Contact
- © 2025 **Artem Brezgin / Spanda Foundation**
- License: Academic use with attribution.
- Contact: **artem@quant-trika.org**

---

## 6. Closing Note
This repository is both **philosophical and empirical**: it documents the transition from mathematics as a human abstraction to mathematics as a living process within reality itself. Each included document and notebook builds one layer of this vision — from metaphysical insight to quantitative validation. Together, they form a complete demonstration that **the structure of numbers is the structure of reality’s self‑organization.**

