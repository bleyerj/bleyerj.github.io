---
title: "Advanced material modeling in FEniCSx"
collection: talks
type: "Talk"
venue: "[MFront User Days 2024](https://github.com/thelfer/tfel-doc/blob/master/MFrontUserDays/TenthUserDay/Agenda/talks.md)"
date: 2024-11-19
location: "Maison de la Simulation, Saclay, France"
slides: "../files/Mfront_UDays_2024.pdf"
excerpt: ""
---


[`FEniCSx`](https://fenicsproject.org/) is a powerful code-generation software package for automating complex PDE systems. While hyperelastic materials can be formulated using UFL operators and automatic differentiation (AD) of a free energy potential, more complex materials often require solving for the evolution of internal state variables at the material point level.

However, this two-level procedure is not easily enabled by [`FEniCSx`](https://fenicsproject.org/), which is not designed for it. This work aims to provide a simple way of defining such implicit constitutive equations, albeit with a slight computational and memory overhead.

The library can handle various implementation types of constitutive equations, starting with user-defined constitutive updates using [`NumPy`](https://numpy.org/) and [`JAX`](https://jax.readthedocs.io/en/latest/quickstart.html), which are ideal for educational purposes [1]. For better computational performance and behavior complexity, the library also supports material models defined by the `MFront` code generator.

Additionally, advanced material modeling techniques such as multiscale material models using Thermodynamics-based Artificial Neural Networks (TANN) can also be used very easily.


* **Github repository**: [https://github.com/bleyerj/dolfinx_materials](https://github.com/bleyerj/dolfinx_materials)
* **Online documentation**: [https://bleyerj.github.io/dolfinx_materials/](https://bleyerj.github.io/dolfinx_materials/)

## References

[1] Andrey Latyshev, Jérémy Bleyer, Corrado Maurini, Jack S Hale. [Expressing general constitutive models in FEniCSx using external operators and algorithmic automatic differentiation](https://hal.science/hal-04735022v1). 2024.
