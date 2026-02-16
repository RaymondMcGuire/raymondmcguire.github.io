---
title: "Real-Time Position-Based Deformable Human Body Dynamics for Disaster Rescue Simulation: A Stress-Driven Approach using a Practical Neo-Hookean Constraint"
date: 2025-10-19 00:00:00 +0800
selected: true
pub: "IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS2025)"
pub_date: "2025"
abstract: >-
  Position Based Dynamics (PBD) has been widely adopted for interactive simulation, 
  particularly in applications such as virtual surgery and elastodynamics. 
  However, many existing frameworks focus exclusively on interactive deformation, 
  often neglecting the comprehensive analysis of stress distribution, 
  which is a critical factor in engineering assessments.
  In remote disaster rescue scenarios, real-time stress visualization can provide vital insights 
  that enable rescue teams to make informed decisions when interacting with deformable objects.
  In this work, we introduce a fully GPU-parallel, stress-driven simulation framework for 
  real-time deformable human body dynamics, specifically designed for disaster rescue applications. 
  Our approach computes the von Mises stress for each tetrahedral element using a practical Neo-Hookean material model, 
  projects the stress onto the corresponding mesh vertices, and maps these values onto the surface for intuitive rendering. 
  In particular, we address the convergence limitations of general Neo-Hookean constraints under a Jacobi parallel scheme by developing a robust, improved approach. 
  This improved approach avoids the typical volume loss observed in conventional methods and better replicates the qualitative behavior of the Gauss-Seidel scheme.
  Quantitative experiments using 100 human body models with diverse shapes, heights, and weights 
  demonstrate that our framework effectively maintains the original pose while delivering enhanced physical realism and informative stress visualization. 
  This capability provides disaster rescue teams with critical insights to optimize decision-making during emergencies.
cover: /assets/img/iros/2025.jpg
authors:
  - Xu Wang
  - Daichi Aoki
  - Zechen Zhu
  - Soichi Murakami
  - Takashi Shimoe
  - Taku Senoo1
  - Hiroaki Date
  - Toshiaki Shichinohe
  - Takashige Abe
  - Satoshi Kanai
  - Atsushi Konno
---