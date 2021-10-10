---
permalink: /projects/
title: "Projects"
classes: wide
galleryFluttair:
  - url: https://github.com/acrovato/fluttair
    image_path: https://github.com/acrovato/fluttair/blob/master/demo/map2.png
  - url: https://github.com/acrovato/fluttair
    image_path: https://github.com/acrovato/fluttair/blob/master/demo/map1.png
  - url: https://github.com/acrovato/fluttair
    image_path: https://github.com/acrovato/fluttair/blob/master/demo/archived.png
  - url: https://github.com/acrovato/fluttair
    image_path: https://github.com/acrovato/fluttair/blob/master/demo/db3.png
galleryEnroute:
  - url: https://akaflieg-freiburg.github.io/enroute/
    image_path: https://github.com/Akaflieg-Freiburg/enroute/blob/master/propaganda/GooglePlay/phone-00-Flight.png
  - url: https://akaflieg-freiburg.github.io/enroute/
    image_path: https://github.com/Akaflieg-Freiburg/enroute/blob/master/propaganda/GooglePlay/phone-02-Map.png
  - url: https://akaflieg-freiburg.github.io/enroute/
    image_path: https://github.com/Akaflieg-Freiburg/enroute/blob/master/propaganda/GooglePlay/phone-03-Info.png
  - url: https://akaflieg-freiburg.github.io/enroute/
    image_path: https://github.com/Akaflieg-Freiburg/enroute/blob/master/propaganda/GooglePlay/phone-04-Route.png
---

## DARTFlo
[DARTFlo](https://gitlab.uliege.be/am-dept/dartflo) (Discrete Adjoint for Rapid Transonic Flows, abbreviated as DART) is an open-source C++/python, unstructured finite-element, full potential solver, that I developed at the University of Liège with the active collaboration of [Romain Boman](https://rboman.github.io/), during my Ph.D. thesis.
DART is currently capable of rapidly solving steady inviscid transonic flows on arbitrary configurations, ranging from 2D airfoils to 3D full aircraft, as well as calculating the flow gradients using a discrete adjoint method. Furthemore, the code is interfaced with [CUPyDO](https://github.com/ulgltas/CUPyDO) and [openMDAO](https://openmdao.org/) so that aeroelastic computations and optimization can be easily carried out. A viscous-inviscid interaction modeling technique is also being implemented so that viscous flows can also be rapidly computed.

<img src="https://gitlab.uliege.be/am-dept/dartflo/-/wikis/pics/main.png">

## dg-flo
[dg-flo](https://github.com/acrovato/dg-flo) is a small python code implementing the Discontinuous Galerkin method to solve various partial differential equations. I wrote this small demonstrator right after completing my Ph.D. to gain a better understanding of this method, as I find it very elegant and efficient to solve high-fidelity fluid dynamics problem. In the future, I hope to work on a full-scale DG code and apply the method to aircraft design.

<figure>
  <img src="https://user-images.githubusercontent.com/39187559/105607872-48f3ff00-5da1-11eb-915c-ebe5c6d45641.png">
  <figcaption>dg-flo solution for the Sod's shock tube using the Euler equations.</figcaption>
</figure>

<figure>
  <img src="https://user-images.githubusercontent.com/39187559/105607735-dedb5a00-5da0-11eb-8b38-b21f4b53a02c.png">
  <figcaption>dg-flo solution for the propagation of a tsunami in shallow water using the Saint-Venant equations.</figcaption>
</figure>

## Enroute and Fluttair
When I performed my first solo cross-country flights, I was disapointed not to find a free Android application for Visual Flight Rules flying. Even if using a paper map is an important and required skill to learn, I think that having an app providing the real-time position on a moving map is reasuring for new pilots, and helps to avoid mistakes. This is especially true in Belgium, where the airspace is very crowded. In this regard, I started developing [Fluttair](https://github.com/acrovato/fluttair) towards the end of 2019. It also introduced me to a new type of programming. A few months later, I discovered that [Stefan Kebekus](https://github.com/kebekus) started to develop [Enroute Flight Navigation](https://github.com/Akaflieg-Freiburg/enroute). Due to the difficulty of maintaining up-to-date navigational data without renting a server, I decided to stop the development of Fluttair, and joined the Enroute development team. I initially implemented a few new features, such as the integration of weather information, and I currently help the team with translating the app in French.

{% include gallery id="galleryFluttair" caption="Sample screenshots from Fluttair." %}

{% include gallery id="galleryEnroute" caption="Sample screenshots from Enroute." %}
