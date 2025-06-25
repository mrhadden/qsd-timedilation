# QSD Time Dilation

**Time Dilation Physically Derived Through Quantum Substrate Dynamics**  
_A Coherence-Based Origin for Relativistic Delay and Causal Structure_

## Overview

This repository contains the full source for the paper:

> **Time Dilation Physically Derived Through Quantum Substrate Dynamics:  
A Coherence-Based Origin for Relativistic Delay and Causal Structure**

Quantum Substrate Dynamics (QSD) is a Lorentz-invariant, coherence-based framework in which all observable physical phenomena—mass, time, gravity, and quantization—arise from causal interactions within a conserved substrate. This paper presents the first axiom-free derivation of time dilation from substrate principles alone, replacing postulated spacetime geometry with physical coherence delay.

## Highlights

- Derives time dilation using only substrate recovery constraints:

- Reproduces full relativistic time behavior for:
- GPS satellite clocks
- Muon lifetime dilation
- Matches Lorentz factor without using coordinate transformations
- Introduces coherence geometry as the origin of time itself

## Key Concepts

- **L_coh**: Local coherence support length of the substrate
- **c_s**: Scalar recovery speed governing phase reconstitution
- **Coherence Triangle**: Conservation structure between transverse spread, scalar recovery, and motion
- **QSD vs. Relativity**: QSD reproduces relativistic effects without requiring geometric assumptions

## Repository Contents

| File | Description |
|------|-------------|
| `QSD_TimeDilation.tex` | Full LaTeX source of the paper |
| `QSD_TimeDilation.pdf` | Compiled submission-ready PDF |
| `figures/` | Diagrams illustrating coherence projection and gravitational stretch |
| `README.md` | This file |

## How to Compile

Requires a LaTeX installation with the following packages:
- `pgfplots`, `tikz`, `amsmath`, `graphicx`, `caption`, `subcaption`, `hyperref`, `geometry`, `xcolor`, `float`

To compile:

```bash
pdflatex QSD_TimeDilation.tex
bibtex QSD_TimeDilation
pdflatex QSD_TimeDilation.tex
pdflatex QSD_TimeDilation.tex
