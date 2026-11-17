# Symmetry!? NO Symmetry! ⚖️

**Why Exact 180° Equilibrium Means Stasis — And How Dimensionless Offsets Drive Dynamic Systems**

> *"If two opposing forces meet at an exact 180° mirror angle, they cancel out. Nature avoids standstill through minimal, unit-independent angular offsets."*

---

## 📖 Overview

This repository houses the LaTeX monograph **`TONE_Universal_Synthesis`** alongside self-contained, constructive **Lean 4** formalizations. It explores how algebraic self-inversion (**Scale Reciprocity**, $j^2 = 1$) and discrete state transitions (**Ruck-Inversion**, $\dddot{x}$) connect symmetry-breaking phenomena across multiple domains:

* **Astrophysics:** Analyzing the $165.4^\circ$ phase separation ($\delta\theta = 14.6^\circ$ offset from $180^\circ$) and opposite circular polarizations of the long-period radio transient `LPT J1555−5631`.
* **Particle Physics & QFT:** Examining quark flavor mixing (Cabibbo angle $\theta_C \approx 13.04^\circ$) and constructive lower energy bounds ($\Delta m > 0$) via prime resonance primitives ($\nu \ge 2$).
* **Number Theory:** Modeling the Riemann zeta functional reflection ($s \mapsto 1 - s$) as an involution anchored on the critical line $\text{Re}(s) = 1/2$.
* **Biology & Geometry:** Comparing biochemical homochirality and botanical phyllotaxis (Golden Angle $137.51^\circ$) against degenerate $50:50$ cancellation.
* **Thermodynamics of Computation:** Contrasting $O(N)$ software abstractions against reversible $O(1)$ operations and bare-metal execution (`no_std` / `wfi`) under Landauer's limit.

---

## 🗂 Repository Structure

| Path | Description |
| :--- | :--- |
| `paper/TONE_Universal_Synthesis.pdf` | Complete 13-section illustrated PDF monograph including Addendum & Glossary. |
| `paper/TONE_Universal_Synthesis.tex` | Full LaTeX source code (TikZ diagrams, PGFPlots, theorems, and beginner guides). |
| `lean/TONE_Universal_Verification.lean` | Constructive Lean 4 proofs using zero external dependencies and zero `Classical.choice`. |
| `lakefile.lean` & `lean-toolchain` | Build configuration for local Lean 4 verification. |
| `LICENSE` | Re-Inversion Public License (RIPL v1.0). |

---

## ⚙️ Verifying the Lean 4 Proofs Locally

All formal proofs in `lean/TONE_Universal_Verification.lean` rely strictly on Lean 4's core constructive type theory (`Int`, `Nat`, `omega`) without `Mathlib` or non-constructive choice axioms.

To check the proofs on your machine:
```bash
git clone https://github.com
cd Symmetry-No-Symmetry
lake build
```

---

## 📜 License

This repository and its contents are governed by the **Re-Inversion Public License (RIPL v1.0)** authored by **Johannes Geisen** (`@frintroper` / `@OverThePlaces`). See the `LICENSE` file for full terms.
