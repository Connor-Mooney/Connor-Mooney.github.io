---
title:  "Research"
permalink: "/research/"
mathjax: true
layout: page
---
{::options parse_block_html="true" /}

## Overview

I am broadly interested in the intersection of condensed matter physics, quantum information science, and condensed matter physics. A few more specific areas:
* Results understanding the effects of locality constraints on 
dynamics, eigenstate structure, and the performance of quantum algorithms, such as extended Lieb-Robinson bounds and state-transfer protocols
* Rigorous results in quantum dynamics, such as extensions of the adiabatic theorem
* Results using tools from functional analysis and operator algebrae to analyze many-body quantum systems

## Previous Work

### Projective Torus Designs

### Intermediate-Time (A)diabatic theorems
![intermediate timescale](/assets/Indermediate_adiabatic.png){:width="30%" : style="padding:0.7em; float:left"} 
At slow-enough timescales, quantum dynamics starting in the ground state are rigorously governed by the adiabatic theorem, which guarantees approximate spectral transport, with error (heuristically) scaling like $$\sim(\Gamma^2 T)^{-1}$$ where $$\Gamma$$ is the spectral gap of the Hamiltonian. These guarantees have been harnessed, for instance, to give an alternative method of quantum computing equivalent in computational power to the standard one; to perform a computation, one need only evolve a given input state by a family of Hamiltonians whose initial ground state is the input state and whose final ground state is the output.

However, while the adiabatic theorem serves as a rigorous bound, in some cases, it is only that, a bound. For some systems one can arrive at the final ground state much quicker than would be suggested by the adiabatic theorem's error scaling. However, these examples have mainly been studied only heuristically and numerically. In joint work with [Michael Jarret][jarret] and [Jacob Bringewatt][bringewatt], we used techniques from spectral graph theory and matrix analysis to more rigorously understand the error behaviour in these sub-adiabatic regions. See our paper [here][adiabaticpaper]. 


### Lefschetz Thimble Monte Carlo for Spin Systems

[jarret]: https://science.gmu.edu/directory/michael-jarret
[bringewatt]: https://www.jacobbringewatt.com
[adiabaticpaper]: https://arxiv.org/abs/2303.13478
