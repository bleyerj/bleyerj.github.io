---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% include base_path %}
{% include toc %}

## Main projects

### [Numerical tours of computational mechanics with FEniCSx](https://bleyerj.github.io/comet-fenicsx/)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10470942.svg)](https://doi.org/10.5281/zenodo.10470942)


These numerical tours will introduce you to a wide variety of topics in computational continuum and structural mechanics using the finite element software FEniCSx.


### [`dolfinx_materials`](https://github.com/bleyerj/dolfinx_materials)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13882184.svg)](https://doi.org/10.5281/zenodo.13882184)


`dolfinx_materials` is a Python add-on package to the `dolfinx` interface to the [FEniCSx project](https://fenicsproject.org/).
It enables the user to define **complex material constitutive behaviours** which are not expressible using classical [UFL](https://fenics.readthedocs.io/projects/ufl/en/latest/) operators.

### [`dolfinx_optim`](https://github.com/bleyerj/dolfinx_optim)


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15533016.svg)](https://doi.org/10.5281/zenodo.15533016)


`dolfinx_optim` is a Python library that aims at providing a simple user interface in FEniCSx for solving **convex optimization problems**. In particular, it relies on the [Mosek](https://www.mosek.com) mathematical programming library. In particular, Mosek is a state-of-the art solver for linear programming (LP), convex quadratic programming (QP), second-order conic programming (SOCP) and semi-definite programming (SDP).

## Supplementary materials

### Learning elastoplasticity with implicit layers (2025)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15516087.svg)](https://doi.org/10.5281/zenodo.15516087)

Companion code to:
> J. Bleyer. Learning elastoplasticity with implicit layers, Computer Methods in Applied Mechanics and Engineering 444 (2025): 118145. [doi:10.1016/j.cma.2025.118145](https://doi.org/10.1016/j.cma.2025.118145)

### Adaptive Eyre-Milton (2024)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11027973.svg)](https://doi.org/10.5281/zenodo.11027973)

These scripts are supplementary materials to the paper:

> K. Sab, J. Bleyer, S. Brisard and M. Dolbeau. An FFT-based adaptive polarization method for infinitely contrasted media with guaranteed convergence, Computer Methods in Applied Mechanics and Engineering 427 (2024): 117012. [doi:10.1016/j.cma.2024.117012](https://doi.org/10.1016/j.cma.2024.117012)


### Phase-Field Composites (2018)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4735521.svg)](https://doi.org/10.5281/zenodo.4735521)

Phase-Field Composites is distributed as supplemental material to the paper 

> J. Bleyer, R. Alessi, Phase-field approach to anisotropic brittle fracture including several damage mechanisms, Comput. Methods Appl. Mech. Engrg. (2018), [doi:10.1016/j.cma.2018.03.012](https://doi.org/10.1016/j.cma.2018.03.012)

This repository provides Python scripts based on the FEniCS project implementing the Longitudinal Transverse Damage (LTD) model for simulating brittle fracture of orthotropic materials as described in the paper. The Standard Damage (SD) model is also implemented. Scripts corresponding to the illustrative examples detailed in the paper along with the corresponding finite-element meshes are also provided.

### Viscoplastic flows (2017)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1038520.svg)](https://doi.org/10.5281/zenodo.1038520)

Interior-point and Augmented Lagrangian algorithms for antiplane viscoplastic flows (in FEniCS) Viscoplastic flows is distributed as supplemental material to the paper

> J. Bleyer, Advances in the simulation of viscoplastic fluid flows using interior-point methods, Comput. Methods Appl. Mech. Engrg. (2017), [doi:10.1016/j.cma.2017.11.006](https://doi.org/10.1016/j.cma.2017.11.006).

This repository is distributed to provide a minimal working implementation and examples of the methods discussed in the paper.