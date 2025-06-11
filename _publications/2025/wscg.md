---
title: "Extending Bonded DEM for Solid-Fluid Interaction: A Coupled BDEM-SPH Simulation Framework"
date: 2025-05-27 00:00:00 +0800
selected: true
pub: "33th International Conference in Central Europe on Computer Graphics, Visualization and Computer Vision (WSCG)"
pub_date: "2025"
abstract: >-
  We present a novel fully Lagrangian simulation framework that couples Bonded Discrete Element Method (BDEM) with Smoothed Particle Hydrodynamics (SPH) to simulate the complex interactions between elastic solids and fluids. While particle-based methods have shown success in fluid-solid interaction simulations, most existing approaches focus on rigid or granular materials. Our framework extends this capability to elastic solids that can undergo deformations, fracture, and topological changes. The BDEM component represents solids as particles connected by elastic bonds that can stretch, bend, shear, twist and break, while SPH handles fluid dynamics with free surface flows. We introduce a parallel implementation strategy for bond computation that allows static bonds to be processed in parallel on GPU architectures. Our method naturally handles challenging phenomena such as fluid percolation through fractured solids and cracking of objects caused by water pushing into their internal structure, without requiring complex interface tracking or remeshing operations. We demonstrate the framework's effectiveness through various scenarios including elastic objects interacting with fluid flows, solids breaking apart when pressed by fast-moving water, and objects with different elastic properties submerged in water. Our coupling particle-based framework naturally handles complex physical phenomena while maintaining computational efficiency, making it particularly suitable for computer graphics applications where visually believable simulation and computational efficiency are prioritized over strict physical accuracy.
cover: /assets/img/wscg2025.gif
authors:
  - Wei Cui*
  - Xu Wang*
  - Makoto Fujisawa
---
