---
title: "Viscoplastic fluid flows: applications, simulation strategies and challenges"
collection: talks
type: "Invited talk"
venue: "[Fronts 2023](https://www.x-mesh.eu/fronts2023/)"
date: 2023-06-26
location: "UC Louvain, Belgium"
slides: "../files/Fronts_2023.pdf"
excerpt: ""
---

Viscoplastic or yield-stress fluids are a particular class of non-Newtonian fluids which behave like a solid below a critical yield stress and flow like a viscous fluid for stresses higher than this threshold. Such materials are commonly found in various applications, ranging from geophysical flows, civil engineering, petroleum or food industries. The Bingham model is the most simple viscoplastic model in which the material is considered to be rigid below a yield criterion and is linearly viscous above the yield stress. Viscoplastic flows entail interesting physics such as the existence of stopped and rigid-body plug regions in flows or the return to rest in a finite time.

In this talk, I will present the underlying mechanical models used to describe such materials and illustrate on various applications why their simulation is important and challenging. I will devote some time to discuss the corresponding variational principles which are at the basis of various numerical strategies to solve this complex behavior. After a brief review of the available methods, I will focus on a formulation based on conic optimization. The latter has been widely used to solve limit analysis (rigid perfectly plastic) behaviours and therefore provides a natural extension to viscoplastic fluids. The resolution of the underlying large-scale non-smooth convex optimization problem is achieved using state-of-the art interior-point solvers which are shown to be more efficient than previous approaches such as Augmented Lagrangian techniques.