# 🧠 SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION™

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20348538.svg)](https://doi.org/10.5281/zenodo.20348538)
![Version](https://img.shields.io/badge/version-v2.0.0-blue)
![License](https://img.shields.io/badge/license-CC--BY--4.0-lightgrey)

---

# Residual Cut Entropy for Tseitin Formulas

## An Information-Theoretic Perspective on Exponential OBDD Lower Bounds

> **Latest Release — v2.0.0**
>
> Official archived release published on Zenodo with:
>
> - Versioned preprint snapshot
> - PDF manuscript
> - LaTeX source
> - Citation metadata
>
> DOI:
>
> https://doi.org/10.5281/zenodo.20348538

---

## Overview

This repository contains the preprint:

> **Residual Cut Entropy for Tseitin Formulas**  
> *An Information-Theoretic Perspective on Exponential OBDD Lower Bounds*

The paper introduces **Residual Cut Entropy (RCE)**, an information-theoretic quantity associated with residual Boolean functions induced by variable cuts.

This framework provides:

- General lower bounds on OBDD width;
- Exact characterization for Tseitin formulas;
- Exponential lower bounds on bounded-degree expander graphs;
- A structural bridge between information theory and proof complexity.

---

## Abstract

Residual Cut Entropy is defined as the logarithm of the number of distinct residual functions induced across a variable cut.

For every variable ordering and every cut, the width of an Ordered Binary Decision Diagram (OBDD) is bounded below by the corresponding residual count.

For Tseitin formulas, this quantity admits an exact graph-theoretic characterization:

```math
H_C^{\mathrm{res}}(F_G) = c(T) - 1
```

where \( c(T) \) denotes the number of connected components of the residual graph.

As a consequence, every OBDD representing a Tseitin formula on bounded-degree expander graphs requires exponential size.

---

# Main Results

## General OBDD Lower Bound

```math
\mathrm{width}_C(F) \ge 2^{H_C^{\mathrm{res}}(F)}
```

---

## Exact Formula for Tseitin Formulas

```math
H_C^{\mathrm{res}}(F_G) = c(T) - 1
```

---

## Exponential Lower Bound

```math
\mathrm{OBDD}(F_G) \ge 2^{n/4 - 1}
```

for families of 3-regular expander graphs with \( n \) vertices.

---

# Repository Structure

```text
.
├── Paper.pdf
├── paper.tex
├── README.md
├── CITATION.cff
├── LICENSE
└── MANUAL-SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION.pdf
```

---

# Included Files

| File | Description |
|---|---|
| `Paper.pdf` | Full manuscript |
| `paper.tex` | LaTeX source |
| `README.md` | Project overview |
| `CITATION.cff` | Citation metadata |
| `LICENSE` | Repository license |

---

# Citation

If you use this work, please cite:

```bibtex
@misc{batista2026residual,
  author = {João Henrique de Souza Batista},
  title = {Residual Cut Entropy for Tseitin Formulas:
           An Information-Theoretic Perspective on Exponential OBDD Lower Bounds},
  year = {2026},
  doi = {10.5281/zenodo.20348538},
  url = {https://doi.org/10.5281/zenodo.20348538}
}
```

---

# Author

**João Henrique de Souza Batista**  
Independent Researcher — Brazil

- LinkedIn:
  https://www.linkedin.com/in/joaohenriquedigital/

- GitHub:
  https://github.com/Joao-supera

---

# Related Research Program

This repository is part of the broader:

> **SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION™**

research initiative connecting:

- Computational Complexity Theory
- Information Theory
- Proof Complexity
- AI Governance
- Cognitive Decision Systems

---

# License

This project is distributed under the CC BY 4.0 License.

See `LICENSE` for details.
