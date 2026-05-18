# Linear Diophantine Representation Systems
### N = 25A + 12B | A₀ = N mod 12 | Clock Structure

**Author:** Bilal el Issaoui  
**Independent Researcher** | Amsterdam  
**Year:** 2026

---

## 📄 Paper

> *"A₀ = N mod 12 | N = 25A + 12B | Clock Structure"*

The core result of this work: in the linear Diophantine system **N = 25A + 12B**, the minimal A-coordinate of any representation equals **N mod 12**:

$$A_0 = N \bmod 12$$

This follows directly from the structural condition **25 ≡ 1 (mod 12)**, which causes B to vanish from the equation modulo 12. The theory developed here is the exact analogue of the (19,9)-system — with digital root replaced by residue mod 12, and the clock as the natural analogy.

---

## 🔑 Key Results

| Result | Value |
|---|---|
| **Structural condition** | 25 ≡ 1 (mod 12) |
| **Minimal A-coordinate** | A₀ = N mod 12 |
| **Counting formula** | R(N) = ⌊(⌊N/25⌋ − A₀) / 12⌋ + 1 |
| **Frobenius boundary** | 263 |
| **Last residue class** | r = 11 (analogue of dr=8 in the (19,9)-system) |
| **Period p×q** | 300 |
| **Family boundary formula** | G(k) = 300k − 288 |
| **First complete family** | N = 564–575 (12 consecutive integers, each ≥ 2 representations) |
| **Anchor family** | N = 2964–2975 (each exactly 10 representations) |
| **The gap** | N = 2963, r=11: only 9 representations (analogue of N=1682 in (19,9)) |

---

## 🗂️ Repository Structure

```
/paper/        → Publication-ready HTML and PDF versions
/code/         → Python: R(N) computation, residue verification, family analysis
/figures/      → JavaScript/Canvas figures used in the paper
README.md      → This file
```

---

## 💻 Code

The `/code/` folder contains Python scripts for:

- Computing all representations N = 25A + 12B for given N
- Verifying A₀ = N mod 12 computationally
- Generating family tables (first complete family, anchor family)
- Comparing structure with the (19,9)-system

---

## 🔗 Related Work

This paper is part of a series on linear Diophantine representation systems with p ≡ 1 (mod q):

- **(19,9)-system:** A₀ = dr(N) — [https://doi.org/10.5281/zenodo.19474707](https://doi.org/10.5281/zenodo.19474707)
- **(25,12)-system:** A₀ = N mod 12 — this repository

Both systems share the same algebraic core. The (19,9)-system uses the digital root; the (25,12)-system uses the clock.

---

## 📜 License

Released under **Creative Commons Attribution 4.0 (CC BY 4.0)**.  
Free to share and adapt with attribution.

---

## 📬 Contact

**Bilal el Issaoui**  
✉️ [elissa.oui.amster@gmail.com](mailto:elissa.oui.amster@gmail.com)  
✉️ [elissa_oui@outlook.com](mailto:elissa_oui@outlook.com)

Or open an **Issue** or start a **Discussion** in this repository.

---

*"25 ≡ 1 (mod 12) — just like the clock restarts after 12."*
