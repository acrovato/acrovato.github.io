---
permalink: /projects/
title: "Projects"
classes: wide
---

## DARTFlo
[DARTFlo](https://gitlab.uliege.be/am-dept/dartflo) (Discrete Adjoint for Rapid Transonic Flows, abbreviated as DART) is an open-source C++/python, unstructured finite-element, full potential solver, that I developed at the University of Liège with the active collaboration of [Romain Boman](https://rboman.github.io/), during my Ph.D. thesis.
DART is currently capable of rapidly solving steady transonic flows on arbitrary configurations, ranging from 2D airfoils to 3D full aircraft, as well as calculating the flow gradients using a discrete adjoint method. Furthemore, the code is interfaced with [CUPyDO](https://github.com/ulgltas/CUPyDO) and [openMDAO](https://openmdao.org/) so that aeroelastic computations and optimization can be easily carried out.

<img src="https://gitlab.uliege.be/am-dept/dartflo/-/wikis/pics/main.png">

## dg-flo
[dg-flo](https://github.com/acrovato/dg-flo) is a small python code implementing the Discontinuous Galerkin method to solve various partial differential equations. I wrote this small demonstrator right after completing my Ph.D. to gain a better understanding of this method, as I find it very elegant and efficient to solve high-fidelity fluid dynamics problem. In the future, I hope to work on a full-scale DG code and apply the method to aircraft design.

IMAGE OF DG FLO

## Enroute and Fluttair
When I performed my first solo cross-country flights, I was disapointed not to find a free application for Visual Flight Rules flying. Even if using a paper map is an important and required skill to learn, I think that having an app providing the real-time position on a moving map is reasuring for new pilots, and helps to avoid mistakes, especially in Belgium, where the airspace is crowded. In this regard, I started developing [Fluttair](https://github.com/acrovato/fluttair) towards the end of 2019. It also introduced me to a new type of programming. A few months later, I discovered that [Stefan Kebekus](https://github.com/kebekus) started to develop [Enroute Flight Navigation](https://github.com/Akaflieg-Freiburg/enroute). Due to the difficulty of maintaining up-to-date navigational data without renting a server, I decided to stop the development of Fluttair, and joined the Enroute development team. I initially implemented a few features, such as the integration of weather information. I currently help the team with translating the app in French.

IMAGE OF FLUTTAIR AND ENROUTE
