# Exponential Sums and Weil Bounds

<p align="center">
  <a href="https://www.tifr.res.in" target="_blank">
    <img src="https://img.shields.io/badge/TIFR-MSc Project-2D4889?style=for-the-badge&logo=latex&logoColor=white" alt="TIFR Badge">
  </a>
</p>

<h2 align="center">Exponential Sums and Weil Bounds:<br>A Survey of Elementary Methods and Decoding Applications</h2>

<p align="center">
  <a href="msc-project.pdf">
    <img src="https://img.shields.io/badge/PDF-Download-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Download PDF">
  </a>
  <a href="https://sohamch08.github.io">
    <img src="https://img.shields.io/badge/Website-sohamch08.github.io-1E90FF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=open-source-initiative&logoColor=white" alt="License">
  </a>
</p>

---

This repository contains the source for my **MSc Project Report** submitted at the **Tata Institute of Fundamental Research (TIFR), Mumbai** in **May 2026**.

**Author:** [Soham Chatterjee](https://sohamch08.github.io/)  
**Supervisor:** [Prof. Mrinal Kumar](https://www.tcs.tifr.res.in/~mrinal/)  
**Institute:** School of Technology and Computer Science, TIFR, Mumbai  
**Contact:** soham.chatterjee@tifr.res.in

---

## Overview

The report is a survey of the theory of exponential (character) sums over finite fields, centered on the Weil bounds and their proofs via elementary polynomial methods, together with a presentation of Kopparty's polynomial-time decoding algorithms for codes constructed from character evaluations.

The central theme is the interplay between three ideas:
- **Character sums and pseudorandomness** — how Weil bounds capture the near-uniform distribution of character values of polynomials
- **Elementary proofs** — Stepanov's polynomial method and Bombieri's extension as self-contained routes to sharp bounds
- **Algorithmic consequences** — the first polynomial-time decoding of quadratic character codes and dual BCH codes from a constant fraction of errors, via pseudopolynomials

---

## Contents

The report is organized as follows:

1. **Finite Fields** — Field extensions, Frobenius, trace and norm maps
2. **Exponential Sums over Finite Fields** — Additive and multiplicative characters, Gaussian sums, Jacobi sums, Kloosterman sums, Salié sums, and Dirichlet $L$-functions over $\mathbb{F}_q[X]$
3. **Equations over Finite Fields** — Chevalley–Warning theorem, diagonal equations, quadratic forms, average solution counts
4. **Weil Bounds on Special Cases** — Stepanov's polynomial method for $Y^d = f(X)$, Bombieri's method for $Y^q - Y = f(X)$, $L$-function machinery, and the general Weil bound via lifting
5. **Decoding from Character Evaluations** — Pseudopolynomials, their theory, and Kopparty's decoding algorithms for the quadratic character code and dual BCH codes; alternate elementary proofs of the Weil bounds via pseudopolynomials

---

## Appendices

- **Algebraic and Analytic Background** — Galois theory facts, meromorphic continuation, Fermat's little theorem, roots of unity identity, elementary symmetric polynomials
- **Modulus Bounds from Power Sum Estimates** — Four lemmas (Diophantine approximation → large real parts → modulus bounds) used in the Weil bound argument
- **Continued Fractions over Polynomial Rings** — Euclidean algorithm, convergents, determinant identity, coprimality
- **Hasse Derivatives** — Multivariate and univariate theory, product rule, $\Lambda(X) = X^q - X$ computations

---

## References

The primary references for this report include:

- **Equations over Finite Fields** — W. M. Schmidt (Springer, 1976)
- **Algebraic Curves over a Finite Field** — Hirschfeld, Korchmáros, Torres (Princeton, 2008)
- **Finite Fields** — Lidl and Niederreiter (Cambridge, 2nd ed., 1997)
- **Analytic Number Theory** — Iwaniec and Kowalski (AMS, 2004)
- **An Invitation to Modern Number Theory** — Miller and Takloo-Bighash (Princeton, 2006)
- **Recovering polynomials over finite fields from noisy character values** — Kopparty (2026)

---

## Typesetting

The report is typeset in LaTeX using a custom theorem and layout style.
Source files are organized as follows:

```
msc-project.tex          ← main file
chapters/
  finite-fields/
  character_sums/
  equations-over-fq/
  weil/
  decoding/
  appendix/
images/                  ← tifr-logo.pdf
refs.bib                 ← bibliography
```

Build with any standard LaTeX compiler (`pdflatex` or `lualatex`).
