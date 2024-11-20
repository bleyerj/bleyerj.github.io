---
title: "Automating convex optimization problems in FEniCSx"
collection: talks
type: "Talk"
venue: "[PDESoft 2024](https://pdesoft.org/)"
date: 2024-07-1
location: "Cambridge, UK"
slides: "../files/PDESoft_2024.pdf"
excerpt: ""
---

Convex optimization problems arise in many fields of physics, applied mathematics, fluid and solid mechanics or even mathematical finance. Interesting applications usually involve non-smooth terms which require well-designed optimization algorithms for their resolution. In this work, we consider PDE-based non-smooth convex optimization problems and present a Python package built on top of the FEniCSx finite element library. We leverage conic representation of convex functions to design a domain-specific language which enables to automate the formulation, discretization and resolution of non-smooth convex problems. The resulting conic problems are solved by the primal-dual interior-point solver Mosek. We finally present various applications regarding viscoplastic fluids, elastoplastic solids, topology optimization and form-finding of optimal shells.

* **Github repository**: [https://github.com/bleyerj/dolfinx_optim](https://github.com/bleyerj/dolfinx_optim)
* **Online documentation**: [https://bleyerj.github.io/dolfinx_optim/](https://bleyerj.github.io/dolfinx_optim/)
