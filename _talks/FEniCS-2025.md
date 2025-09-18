---
title: "Differentiable Constitutive Modeling with FEniCSx and JAX"
collection: talks
type: "Talk"
venue: "[FEniCS 2025](https://fenicsproject.org/fenics-2025/)"
date: 2025-06-19
location: "Groningen, The Netherlands"
slides: "../files/FEniCS_2025.pdf"
excerpt: ""
---


The field of computational mechanics is increasingly converging with machine learning, particularly in the area of constitutive modeling. Constitutive models, which are inherently data-driven, share formal similarities with neural network layers. Beyond simply learning constitutive models from data, there is significant potential in developing implementations of traditional constitutive models that are compatible with machine learning frameworks.

Automatic differentiation (AD) has transformed machine learning by enabling complex computations to be composed from simpler operations while automating the calculation of derivatives. In this talk, we will explore the application of AD to constitutive modeling, with a special emphasis on two key areas: efficient tangent operator computation and material parameter sensitivity. These developments are now part of the dolfinx_materials package [1] which leverages implementations in JAX [2].

First, AD can be used to automatically derive consistent tangent operators, which are essential for the efficient integration of constitutive models in large-scale simulations. We will discuss various strategies for obtaining these operators, including applying AD directly to the unrolled algorithm or using the more efficient method of implicit differentiation [3]. 

Second, AD can also be leveraged to compute sensitivities of material parameters, enabling more efficient model calibration. Finally, we will explore how AD and implicit differentiation can be extended to handle more complex constitutive models, such as multi-surface plasticity, which require advanced nonlinear solvers.

This is joint work with Andrey Latyshev (University of Luxembourg), Corrado Maurini
(Sorbonne Université), Jack S. Hale (University of Luxembourg).

## References

[1] Bleyer, J. (2024). dolfinx_materials: A Python package for advanced material modelling (v0.3.0).
Zenodo. https://doi.org/10.5281/zenodo.13882184

[2] Bradbury, J., Frostig, R., Hawkins, P., Johnson, M. J., Leary, C., Maclaurin, D., et al. (2018). JAX:
composable transformations of Python+ NumPy programs. http://github.com/jax-ml/jax

[3] Blondel, M., Berthet, Q., Cuturi, M., Frostig, R., Hoyer, S., Llinares-López, F., et al. (2022).
Efficient and modular implicit differentiation. Advances in Neural Information Processing Systems,
35, 5230–5242.