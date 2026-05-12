# Exact Renewal Structure in Accelerated Collatz Dynamics

### A 2-adic Symbolic Model and Exact Operator Theory

---

## Overview

This repository contains working papers and supporting material related to a symbolic and operator-theoretic approach to induced Collatz dynamics.

The main paper develops:

- an exact countable-state renewal system,
- a shift-and-kill operator identity,
- exact covariance and entropy formulas,
- a 2-adic symbolic realization.

**The project does NOT claim a proof of the Collatz conjecture.**

Instead, the focus is the exact symbolic and operator structure associated with the induced Type A dynamics — the subsequence of odd iterates under the accelerated Collatz map.

---

## Main Result

The central operator identity is:

```
P^N f = S^N f
```

on the mean-zero subspace of the renewal system.

This identity yields explicit formulas for:

- covariance decay,
- spectral contraction,
- entropy,
- mutual information memory.

These results hold unconditionally, independent of any conjecture about orbit behavior.

---

## Repository Structure

```
collatz-renewal-structure/
├── paper/
│   ├── Paper_A_arxiv_final.tex   — LaTeX source
│   ├── Paper_A_arxiv_final.pdf   — Compiled PDF
│   └── references.bib            — Bibliography
├── figures/                      — Figures and diagrams (forthcoming)
├── notes/
│   └── roadmap.md                — Research scope and future directions
└── src/                          — Supporting code (forthcoming)
```

---

## Paper

[**Paper PDF**](paper/Paper_A_arxiv_final.pdf)

The LaTeX source is available at [`paper/Paper_A_arxiv_final.tex`](paper/Paper_A_arxiv_final.tex).

---

## Mathematical Context

The paper works within the following framework:

- **Renewal systems** (Krieger, symbolic dynamics)
- **Countable-state Markov shifts** (Sarig, thermodynamic formalism)
- **Operator theory on function spaces** (shift and kill operators)
- **2-adic symbolic realization** (exact coding of Type A trajectories)

The induced Type A map — iterating only the odd-output steps of the accelerated Collatz map — admits an exact renewal structure. This structure is the central object of study.

---

## Status

> **Status: working mathematical draft.**

The paper is currently being refined for public mathematical discussion and possible arXiv submission.

Feedback and comments are welcome via GitHub Issues.

---

## License

MIT License. See [LICENSE](LICENSE).
