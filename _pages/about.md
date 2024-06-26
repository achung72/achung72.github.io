---
layout: page
title: about
permalink: /about/
description:
nav: true
nav_order: 1
---

I'm a current PhD student in the Department of Statistics at Harvard. I graduated from Princeton in 2022, where I majored in Math. My current research interests are in Probability Theory and Theoretical Machine Learning. Some problems that I'm interested in include Theory ML, Random Matrix Theory/Free Probability/University, and recent work in using Statistical Physics method to analyze High Dimensional Systems.

I've previously worked on problems in RL Theory and in Stochastic Calculus. In RL, I worked with Professor [Chi Jin](https://sites.google.com/view/cjin/home) on Partially Observable MDPs; we worked to extend previous theory in learning POMDPs to the Overcomplete case (when the State space is greater than the Observation space). The difficulty in this problem is that the overcomplete condition causes rank deficiencies in the omission matrix, and thus previous "Method of Moments" techniques, which results in bounds that depend inversely on the smallest eigenvalue, do not work, and thus different techniques are required. The paper can be found [here](https://arxiv.org/abs/2204.08967).

My Undergraduate Thesis, with Professor [Mykhaylo Shkolnikov](http://mykhaylo.princeton.edu/), was on the convergence of a particle system to the weak solution of the Fokker-Planck PDE equation. Concretely, a particle system is a system of diffusion processes, that is, a system of SDES, that are coupled only through their empirical measure. It is known that as the number of particles goes to infinity, e.g. [here](https://www.sciencedirect.com/science/article/pii/S0304414912000208), then the empirical measure of the system converges to the weak solution of a desired PDE. Here, the diffusion and drift coefficients depend on the coefficients of the PDE in question. Previous works require the PDE in question to be defined on $$\mathbb{R}$$ and require a nonnegative, increasing initial condition. Our work showed that these results can be extended to PDEs defined on compact spatial boundaries with arbitrary initial conditions that have bounded variation.
