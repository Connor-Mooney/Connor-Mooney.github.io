---
title:  "Research"
permalink: "/research/"
mathjax: true
layout: page
---
{::options parse_block_html="true" /}

## Overview

I am broadly interested in the intersection of condensed matter physics, quantum information science, and mathematical physics. Some more specific questions I am interested in are:
* What are the effects of locality constraints on 
dynamics, eigenstate structure, and the performance of quantum algorithms?
  * How can we extend Lieb-Robinson bounds? How can we strengthen them in more restricted cases?
  * How can we construct state-transfer protocols that saturate these extended/strengthened bounds?
* What rigorous results can we bring to bear on understanding quantum dynamics?
  * How can we extend the adiabatic theorem to understand dynamics outside of that limit, such as those seen in diabatic annealing?
* How can we use tools from functional analysis and operator algebrae to analyze many-body quantum systems?
  * How does the algebraic approach to QFT clarify the discussion of quantum phases of matter?
* How can we use quantum computers to better understand physical phenomena?
* What are the underlying complexity-theoretic properties of quantum many-body systems?
  
This list is by no means exhaustive.

## Previous Work

### Projective Toric Designs
![Torus design](/assets/Torus_design.png){:width="30%" : style="padding:0.7em; float:left"}
Designs are sets of points in a probability space which capture the behaviour of the total space up to some level of complexity; more explicitly, averaging a sufficiently simple function over the points of a design equals the function's average over the whole probability space. Designs are of interest to the QIS community for their applicability to a wide variety of subfields, such as quantum sensing, tomography, cryptography, and error correction. In joint work with [Joseph Iosue][iosue], [Adam Ehrenberg][ehrenberg], and [Alexey Gorshkov][gorshkov], we investigated a new type of design, a toric design, which is in some sense a design on the phase information of the space of quantum states. They can be combined with designs on the unit simplex (the amplitude information) to construct quantum state designs. We found that the problem of constructing minimal toric designs was related to open questions in the field of additive number theory, specifically regarding notoriously unstructured objects called Sidon sets, as well as the study of mutually unbiased bases. See our paper [here][toruspaper].

### Intermediate-Time (A)diabatic theorems
![intermediate timescale](/assets/Indermediate_adiabatic.png){:width="30%" : style="padding:0.7em; float:left"} 
At slow-enough timescales, quantum dynamics starting in the ground state are rigorously governed by the adiabatic theorem, which guarantees approximate spectral transport, with error (heuristically) scaling like $$\sim(\Gamma^2 T)^{-1}$$ where $$\Gamma$$ is the spectral gap of the Hamiltonian. These guarantees have been harnessed, for instance, to give an alternative method of quantum computing equivalent in computational power to the standard one; to perform a computation, one need only evolve a given input state by a family of Hamiltonians whose initial ground state is the input state and whose final ground state is the output.

However, while the adiabatic theorem serves as a rigorous bound, in some cases, it is only that, a bound. For some systems one can arrive at the final ground state much quicker than would be suggested by the adiabatic theorem's error scaling. However, these examples have mainly been studied only heuristically and numerically. In joint work with [Michael Jarret][jarret] and [Jacob Bringewatt][bringewatt], we used techniques from spectral graph theory and matrix analysis to more rigorously understand the error behaviour in these sub-adiabatic regions. See our paper [here][adiabaticpaper]. 


### Lefschetz Thimble Monte Carlo for Spin Systems

[jarret]: https://science.gmu.edu/directory/michael-jarret
[bringewatt]: https://www.jacobbringewatt.com
[gorshkov]: https://jqi.umd.edu/people/alexey-gorshkov
[ehrenberg]: https://www.quics.umd.edu/people/adam-ehrenberg
[iosue]: https://jtiosue.github.io
[adiabaticpaper]: https://arxiv.org/abs/2303.13478
[toruspaper]: https://arxiv.org/abs/2311.13479
