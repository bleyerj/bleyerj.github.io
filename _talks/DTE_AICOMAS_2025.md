---
title: "Differentiable constitutive modeling in a machine learning-compatible framework"
collection: talks
type: "Talk"
venue: "[DTE & AICOMAS 2025](https://dte_aicomas_2025.iacm.info)"
date: 2025-02-20
location: "Paris, France"
excerpt: ""
---

The field of computational mechanics is increasingly converging with machine learning, particularly in the area of constitutive modeling. Constitutive models, which are inherently data-driven, share formal similarities with neural network layers. Beyond learning constitutive models from data, there is significant potential in developing implementations of traditional constitutive models that are compatible with machine learning frameworks. Automatic differentiation (AD) has transformed machine learning by enabling complex computations to be composed from simpler operations while automating the calculation of derivatives. In this talk, we will explore the application of AD to constitutive modeling, with a special emphasis on two key areas: efficient tangent operator computation and material parameter sensitivity. First, AD can be used to automatically derive consistent tangent operators, which are essential for the efficient integration of constitutive models in large-scale simulations. We will discuss various strategies for obtaining these operators, including applying AD directly to the unrolled algorithm or using the more efficient method of implicit differentiation. Second, AD can also be leveraged to compute sensitivities of material parameters, enabling more efficient model calibration. Finally, we will delve into how AD and implicit differentiation can be extended to handle more complex constitutive models, such as multi-surface plasticity, which require advanced nonlinear solvers.