# Aeroman Matrix Operations Guide

A bilingual, interactive linear-algebra laboratory that explains matrix operations through engineering intuition and applies them to composite-ply and laminate stiffness analysis.

[Open the live guide](https://davidnaev.github.io/aeroman-matricies/)

## Overview

This project bridges foundational linear algebra and aerospace structures. Each operation is introduced in plain language, made editable through a live browser laboratory, and then connected to a running carbon/epoxy ply example from Classical Laminated Plate Theory (CLPT).

The entire guide runs offline in one HTML file with no framework, backend, or installation requirement.

## Topics Covered

### Arithmetic and Transformations

- Matrix multiplication, addition, subtraction, and scalar multiplication.
- Transpose and matrix symmetry.
- Matrix inversion and identity verification.

### Solvability

- Determinant as area scaling and an invertibility test.
- Rank, nullity, dependent rows, and unconstrained directions.

### Spectral Analysis

- Eigenvalues and eigenvectors as invariant directions.
- Diagonalization and stiffness coupling under ply rotation.

### Matrix Factorizations

- LU decomposition for repeated structural load solves.
- QR decomposition for stable least-squares estimation.
- Singular value decomposition for conditioning, anisotropy, and data reduction.

## Interactive Features

- Editable matrices with immediate recalculation.
- Step-by-step row-by-column multiplication.
- Dimension controls for compatible and incompatible operations.
- Canvas visualizations for determinant, eigenvectors, diagonalization, and SVD.
- Contextual self-check questions with explanations.
- Instant English/Spanish language switching.
- A consistent 0° carbon/epoxy ply example tying every section together.

## Engineering Application

The guide uses stress, strain, stiffness, and compliance relationships such as:

```text
[σ] = [Q][ε]
[Q] = [S]⁻¹
[N] = [A][ε]
```

It shows how matrix symmetry reflects material reciprocity, how a zero determinant signals an invalid stiffness response, how eigenvectors recover principal material directions, and how off-axis plies introduce extension-shear coupling.

## Run Locally

1. Clone or download the repository.
2. Open `index.html` in a modern browser.

All styles, formulas, fonts, diagrams, and calculations are embedded. KaTeX output is pre-rendered, so mathematical notation remains available offline.

## Repository Structure

| Path | Purpose |
|---|---|
| `index.html` | Complete bilingual interactive guide |
| `Development/README.md` | Original topic and engineering-use outline |
| `Development/*.nb` | Mathematica notebooks exploring stress and strain transformations |

## Intended Use

This project is an educational visualization aid. Composite design, substantiation, and aircraft repair decisions must use validated material properties, approved analytical methods, and the applicable engineering authority.
