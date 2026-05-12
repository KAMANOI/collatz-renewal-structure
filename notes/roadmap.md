# Research Roadmap

## Scope of This Paper (Paper A)

Paper A establishes the exact symbolic and operator-theoretic structure of the induced Type A Collatz dynamics. The main result is the operator identity:

```
P^N f = S^N f
```

on the mean-zero subspace of the renewal system. This yields:

- Exact covariance decay formulas
- Spectral contraction
- Entropy of the renewal measure
- Mutual information memory

These results are unconditional — independent of any assumption about orbit behavior.

---

## What Is NOT Addressed Here

This paper does not:

- Claim or attempt a proof of the Collatz conjecture
- Address the global behavior of arbitrary starting values
- Establish recurrence or convergence of orbits

---

## Possible Future Directions (Exploratory)

The following are research questions suggested by the structure developed in Paper A.
These are speculative and not claimed results.

### Direction 1: Spectral gap and the renewal operator

The operator identity `P^N = S^N` on the mean-zero subspace raises the question of whether
the peripheral spectrum (eigenvalues of modulus 1) can be fully characterized.

### Direction 2: Thermodynamic formalism and pressure

The renewal system is a countable-state Markov shift. Sarig's thermodynamic formalism
applies in principle. The question is whether the pressure function has a particularly
clean form in the Collatz case, given the exact symbolic structure.

### Direction 3: 2-adic structure and coding

The 2-adic symbolic realization gives an exact coding of Type A trajectories.
Whether this coding admits a natural inverse — recovering the starting value from
the symbolic path — is an open question with potential number-theoretic implications.

### Direction 4: Extensions to other accelerated maps

The Type A induction procedure applies to any map of the form `x → (ax + b) / 2^v(ax+b)`.
The renewal structure may admit a uniform description for this family.

---

## Status

| Item | Status |
|------|--------|
| Renewal system construction | Complete |
| Operator identity proof | Complete |
| Covariance / entropy formulas | Complete |
| 2-adic symbolic realization | Complete |
| arXiv submission | Pending refinement |
| Figures | Forthcoming |
| Supporting code | Forthcoming |
