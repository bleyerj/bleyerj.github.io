---
title: "Advanced material modeling in FEniCSx"
collection: talks
type: "Talk"
venue: "[FEniCS 2023](https://fenicsproject.org/fenics-2023/)"
date: 2023-06-15
location: "Cagliari, Italy"
slides: "../files/FEniCS_2023.pdf"
excerpt: ""
---


Solid mechanics involves studying the behavior of materials, and many of them exhibit complex non-linear constitutive relations. While hyperelastic materials can be formulated using UFL operators and a free energy potential, materials with elastoviscoplastic behavior require solving for the evolution of internal state variables at the material point level. This approach involves a two-level nonlinear procedure in computational mechanics, where the stress state and internal state variables are solved for at each iteration of the global problem. The constitutive update must also provide the corresponding consistent tangent operator to achieve quadratic convergence of the global Newton algorithm. However, this two-level procedure is not easily enabled by FEniCSx, which is not designed for it. This work aims to provide a simple way of defining such implicit constitutive equations, albeit with a slight computational and memory overhead. The library can handle various implementation types of constitutive equations, starting with user-defined constitutive updates using Numpy and Scipy, which are ideal for educational purposes. For better computational performance and behavior complexity, the library also supports material models defined by the MFront code generator. Additionally, two advanced material modeling techniques are presented in this work: highly non-smooth behaviors using conic optimization solvers such as CVXPY, and multiscale material models using Thermodynamics-based Artificial Neural Networks (TANN).