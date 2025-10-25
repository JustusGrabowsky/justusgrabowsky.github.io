---
title: "Monte Carlo Simulation of the 3D Heisenberg Model"
summary: "Implementation and benchmarking of Metropolis and Wolff algorithms to study ferromagnetic phase transitions, critical phenomena, and finite-size scaling in the classical Heisenberg model."
date: 2024-03-01
tags: [statistical-physics, monte-carlo, computational-physics, past]
authors: ["Justus Grabowsky"]
---
As part of the Computational Statistical Physics course at ETH Zürich, we implemented Monte Carlo simulations of the three-dimensional classical Heisenberg model. The Heisenberg model is a lattice model used to describe ferromagnetism and phase transitions in magnetic materials.

The project involved implementing three different algorithms in C++: the standard Metropolis algorithm, an Adaptive Metropolis algorithm that optimizes acceptance rates, and the Wolff cluster algorithm. We studied the ferromagnetic-to-paramagnetic phase transition, determining the critical temperature and critical exponents through finite-size scaling analysis. The simulations included variable interaction strengths, external magnetic fields, and magnetic anisotropies.

My main contributions were implementing both Metropolis variants with different trial move strategies (small-step, Gaussian, and random spin-flips) and performing extensive data analysis. We characterized the convergence behavior of each algorithm, calculating non-linear and linear correlation times to determine thermalization. Our analysis showed that the Adaptive Metropolis algorithm performed best for small lattices across all temperatures, while the Wolff algorithm effectively overcame critical slowing down near the phase transition.

We determined critical exponents for magnetization (β), specific heat (α), and susceptibility (γ), finding good agreement with literature values. The project provided hands-on experience with Monte Carlo methods, parallel computing on the Euler cluster, and the statistical mechanics of critical phenomena.
