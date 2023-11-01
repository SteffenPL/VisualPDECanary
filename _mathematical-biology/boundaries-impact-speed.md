---
layout: page
title: "Boundaries impact travelling waves speed"
# permalink: 
lesson_number: 150
thumbnail: /assets/images/bistableTravellingWaves.webp
extract: Waves speed in the sharp interface limit depend on opening angles of the boundary
equation: $\pd{u}{t}=D\nabla^2 u + \frac{K}{\varepsilon^2} (1 - u^2) (u-\varepsilon a)$
---

The following is based on theoretical predictions from Prof. Hiroshi Matano.

The wavefronts in reaction--diffusion equations can become very sharp when the reaction terms strong enough to compress the diffusion at the wavefront. One example is this [Allen-Cahn](bistable-travelling-waves.html) equation 

$$
\pd{u}{t}=D\nabla^2 u + \frac{1}{\varepsilon^2} (1 - u^2) (u-\varepsilon a)
$$

where $D$ is the diffusion coefficient, $\varepsilon > 0$ determines the sharpness of the interface, and $a$ determines the inbalance of the reaction term. 

Typically, the wave speed proportional to 

$$
c \propto \frac{1}{\varepsilon^2} \int_{-1}^1 (1-u^2) (u - \varepsilon a ) \, \d u =
-\frac{4}{3 \varepsilon} a.
$$

However, the boundary conditions for the equation can impact this wave speed even in the sharp interface limit $\varepsilon \to 0$. One can demonstrate this by using a domain $\Omega \subset \mathbb{R}^2$ with a sawtooth-like boundary and Neumann boundary conditions

$$
\pd{u}{n} = 0 \quad \text{on } \partial \Omega
$$

where $n$ denotes the normal vector to the boundary.

In the sharp interface limit, the wavefronts need to be orthogonal to the boundary, but this can slow down the waves or even stop them completely. 

In the following we will explore this phenomenon using interactive simulations.

# Which direction is faster?

First, it is important to notice that the opening angle of the boundary impact the wave speed. 

* Try to guess which of the following wave fronts will first reach the center:

IMAGE

* Load and run the [interactive simulation](/sim/?preset=bistableTravellingWave). 

TODO

# Sometimes more obstacles are better

The following simulation shows that the wave propagation can sometimes only continue by adding obstacles.
