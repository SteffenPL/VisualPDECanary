---
layout: page
title: Swift–Hohenberg equation
lesson_number: 10
thumbnail: /assets/images/swiftHohenberg.webp
extract: Simplistic pattern formation 
equation: $\pd{u}{t}=ru - (1+D\nabla^2)^2u+au^2+bu^3+cu^5$ with periodic boundary conditions
---
Swift–Hohenberg equation:

$$\pd{u}{t} = ru - (k_c^2+\nabla^2)^2u+au^2+bu^3+cu^5,$$

with periodic boundary conditions, and we need $c<0$ (or $b<0$ if $c=0$) for stability.

* Load the [interactive simulation](/sim/?preset=swiftHohenberg). 

* Depending on the signs of $r$, $a$, and $b$, this system can support a wide range of patterns and dynamical behaviour. One important class of behaviour is subcriticality, where the dynamics of the system can become quite complicated and include things like multistability of homogeneous and patterned states, and localised solutions as described below.

# Localised solutions

When $r<0$, $a>0$, and $b<0$, the system can be in a subcritical regime that supports both stable patterned states and the stable homogeneous state $u=0$. Specific initial conditions can induce localised patterns, which fall off to the background of $u=0$ throughout most of the domain. [Here](/sim/?preset=swiftHohenbergLocalised) is one example, where you can change the initial conditions or click to induce localised structures throughout the domain, but only if they are sufficiently far from the homogeneous state (as otherwise perturbations will decay back to it).

This example is based on this [paper by Dan Hill and collaborators](https://iopscience.iop.org/article/10.1088/1361-6544/acc508) which studies symmetric localised solutions of the Swift-Hohenberg equation. 
* The default initial condition picks out a solution with $D_4$ symmetry. 
* If you change the parameter $P$ to the value $2$ and then press {{ layout.erase }}, this will replace the initial condition with one that evolves to a hexagonal solution ($D_6$ symmetry). 
* If you set $P=3$ and press {{ layout.erase }}, this will replace the initial condition with one that evolves to a $D_{12}$-symmetric solution.
