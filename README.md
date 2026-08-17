# The Gauss Hypergeometric Function

**Undergraduate Thesis (Trabajo de Fin de Grado) — BSc in Mathematics**
University of La Rioja · 2025–2026

**Author:** Daniel González Espinosa
**Tutor:** Óscar Ciaurri Ramírez

---

## Abstract

This project presents a comprehensive analytical study of the Gauss hypergeometric function, highlighting its significance as a unifying framework within the theory of special functions. In general terms, it addresses the theoretical construction of this function, exploring everything from its convergence and its analytic extension in the complex plane to its deep structural relationship with families of classical orthogonal polynomials, such as those of Jacobi. In addition to compiling and proving its properties, integral representations and algebraic transformations, the project culminates in a personal mathematical contribution: the development of original hypergeometric identities. Taken as a whole, the project illustrates the immense analytical potential of the hypergeometric function, both for generalising results and for discovering new mathematical relationships.

> The full thesis is written in Spanish. The abstract above is the author's own English translation, included on the first page of the document.

## Contents

**Chapter 1 — Definition and first properties.** Formal definition via power series and the Pochhammer symbol; radius of convergence via the ratio test; a full characterization of convergence on the boundary of the unit disk (absolute, conditional, and divergent regimes) using Stirling asymptotics and the Dirichlet test; Euler's integral representation and its use to construct the unique analytic continuation to the cut plane; linear transformations (Pfaff, Euler); closed-form evaluations at special points (Kummer, Bailey, Gauss's second summation theorem, Gosper's formula).

**Chapter 2 — Connection with orthogonal polynomials.** Jacobi polynomials via the Rodrigues formula; their differential equation; the reduction of this equation to the hypergeometric equation, yielding a hypergeometric representation for Jacobi polynomials; Gegenbauer and Legendre polynomials as special cases; proof of orthogonality and computation of the normalization constant; the three-term recurrence relation.

**Chapter 3 — Hypergeometric identities.** Starting from a recent geometric correspondence between Lamé curve sector areas and sinusoidal spiral arc length, a general family of integrals is defined and evaluated in closed form. This is used to recover known quadratic transformations, and — as an original contribution — to derive new hypergeometric identities not found in standard references (NIST DLMF, Prudnikov–Brychkov–Marichev).

## Repository structure

```
gauss_hypergeometric_tfg/
├── README.md
├── paper/
│   ├── gauss_hypergeometric_tfg.pdf
│   └── source/
│       ├── main.tex
│       ├── portada.pdf
│       ├── dominio_D.pdf
│       └── gauss.jpg
└── slides/
    ├── slides_tfg.pdf
    └── source/
        ├── main.tex
        ├── dominio_D.png
        ├── gauss.jpg
        └── logo_unirioja.png
```

## Image credit

Portrait of Carl Friedrich Gauss — public domain, via [PICRYL](https://picryl.com/) / [Wikimedia Commons](https://commons.wikimedia.org/).

## License

Released under the MIT License — see [LICENSE](LICENSE).
