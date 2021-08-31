---
layout: single
title: "My Research"
permalink: /research/
date: 2021-8-30
categories: pages
---
## Diabatization
Most molecular simulations are based on the Born-Oppenheimer approximation, where nucleus obey Newton's laws while electrons provide nothing but a potential energy surface. However, when the electronic dynamics is essential, e.g. in photochemical process or charge transport, the Born-Oppenheimer approximation breaks. Under such circumstances, diabatization is prerequisite for the coupled electronic and nuclear dynamics

{% include figure image_path="/assets/images/research/cyclohexoxy_double-cone.jpg" caption="The coupled electronic potential energy surfaces around cyclohexoxy conical intersection"%}

One way to globally diabatize the ab initio adiabatic wave functions is to fit the ab initio energy, energy gradients, and nonadiabatic couplings with a real-symmetric matrix (as the diabatic Hamiltonian). The independent matrix elements can in turn be expanded in arbitrary functional forms, e.g. deep neural networks

We have developed a theory and code that can diabatize even the extreme cases, e.g. conical intersections. We are extending it to photodissociation scenarios 

## Vibronic spectrum
An example of the coupled electronic and nuclear dynamics is the vibronic spectrum, where spectroscopy measures the transition between the coupled vibrational and electronic (vib-ronic) states

{% include figure image_path="/assets/images/research/cyclohexoxy_spectrum.png" caption="The photoelectron spectrum of cyclohexoxy"%}

Since spectroscopy is governed by quantum mechanics, the simulation used to be limited to extremely small molecules (less than 10 atoms). We have developed a theory and code that can treat 18+ atoms. Our upper limit has not been reached yet, so we are still trying out larger and larger molecules

## Semiclassical Moyal Dynamics
Nuclei is usually considered classical because of its mass. However, in the coupled electronic and nuclear dynamics, a classical description of nuclear dynamics misses out quantum mechanical electronic-nuclear couplings, e.g. quantum coherence. Other than adding an ad hoc coupling, a quantum mechanical or a semiclassical description is the only way. Since quantum mechanics is cursed by dimensionality, semiclassical mechanics is the theory for the next generation.

{% include figure image_path="/assets/images/publications/2018jcp_SMD.jpeg" caption="The tunneling in a double well"%}

We have derived a semiclassical Moyal dynamics theory from phase-space formulation of quantum mechanics. We are working to improve its robustness and efficiency