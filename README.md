# Exact Renewal Structure in Accelerated Collatz Dynamics

**Hiroki Kamanoi**  
Draft — 2026

Paper A in a series on Collatz dynamics through finite Markov chain theory.

## Overview

This repository contains the paper and supporting material for a symbolic and operator-theoretic approach to induced Collatz dynamics.

The paper develops:

- an exact countable-state renewal system;
- a shift-and-kill operator identity;
- exact covariance and entropy formulas;
- a 2-adic symbolic realization.

**The project does NOT claim a proof of the Collatz conjecture.**

The focus is the exact symbolic and operator structure associated with the induced Type A dynamics — the subsequence of odd iterates under the accelerated Collatz map.

## Main Result

The central operator identity is:

$$P^N f = S^N f$$

on the mean-zero subspace of the renewal system.

This identity yields explicit formulas for:

- covariance decay;
- spectral contraction;
- entropy;
- mutual information memory.

These results hold unconditionally, independent of any conjecture about orbit behavior.

## Logical Structure of the Series

| Paper | Core result | Status |
|-------|-------------|--------|
| **A (this paper)** | Exact operator structure and renewal systems | Proved |
| B | Exact TV mixing: $T_\mathrm{mix}(K) = K-1$ | Proved |
| C | One-bit spectral jump $\delta_{K,1} \approx 0.29$; Open Gap Problem | Numerical / Open |
| D | Simultaneous scale coherence; conditional diverging mixing | Open / Conditional |

## Repository Structure

```
collatz-renewal-structure/
├── paper/
│   ├── collatz_paper_a_final.pdf — final version
│   ├── Paper_A_arxiv_final.tex   — LaTeX source
│   ├── Paper_A_arxiv_final.pdf   — compiled draft
│   └── references.bib            — bibliography
├── figures/                      — figures and diagrams
├── notes/
│   └── roadmap.md                — research scope and future directions
└── src/                          — supporting code
```

## Paper

[**Paper PDF (final)**](paper/collatz_paper_a_final.pdf)

[**Paper PDF (arXiv draft)**](paper/Paper_A_arxiv_final.pdf)

LaTeX source: [`paper/Paper_A_arxiv_final.tex`](paper/Paper_A_arxiv_final.tex)

## Suggested arXiv Categories

Primary: `math.DS`  
Secondary: `math.NT`, `math.PR`

## License

MIT License
