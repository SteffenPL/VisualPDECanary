---
layout: page
title: Solitons in the Korteweg–De Vries equation
lesson_number: 80
thumbnail: /assets/images/KdV.webp
extract: Solitary movement through each other
equation: $\pd{\phi}{t}=-\pdn{\phi}{x}{3}-6\phi \pd{\phi}{x}$
---


Here is an implementation of the [Korteweg–De Vries (KdV) equation](https://en.wikipedia.org/wiki/Korteweg%E2%80%93De_Vries_equation) given by

$$\pd{\phi}{t}=-\pdn{\phi}{x}{3}-6\phi \pd{\phi}{x},$$

which is a very simple model of solitons, as described at the bottom of the page for the [nonlinear Schrödinger equation](/nonlinear-physics/nls-cgl).

The [interactive simulation](/sim/?preset=KdV) starts with two solitons of different amplitudes and speeds, with the larger one moving more quickly and hence overtaking the smaller one at first. While they occupy the same space, these solitons cannot be clearly distinguished as their ampltiudes locally add together, but as the faster soliton moves more quickly it eventually separates from the slower soliton, and neither speed nor amplitude of either soliton is changed.

This example was helpfully constructed by [Paul Sutcliffe](https://www.durham.ac.uk/staff/p-m-sutcliffe/).
