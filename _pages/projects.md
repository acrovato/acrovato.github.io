---
permalink: /projects/
title: "Projects"
classes: wide
galleryFluttair:
  - url: https://github.com/acrovato/fluttair
    image_path: https://media.githubusercontent.com/media/acrovato/fluttair/master/demo/map2.png
  - url: https://github.com/acrovato/fluttair
    image_path: https://media.githubusercontent.com/media/acrovato/fluttair/master/demo/archived.png
  - url: https://github.com/acrovato/fluttair
    image_path: https://media.githubusercontent.com/media/acrovato/fluttair/master/demo/db3.png
galleryEnroute:
  - url: https://akaflieg-freiburg.github.io/enroute/
    image_path: https://akaflieg-freiburg.github.io/enroute/assets/images/00-Map.jpg
  - url: https://akaflieg-freiburg.github.io/enroute/
    image_path: https://akaflieg-freiburg.github.io/enroute/assets/images/01-Map_TFC.jpg
  - url: https://akaflieg-freiburg.github.io/enroute/
    image_path: https://akaflieg-freiburg.github.io/enroute/assets/images/03-Info.jpg
---

## DARTFlo
[DARTFlo](https://gitlab.uliege.be/am-dept/dartflo) (Discrete Adjoint for Rapid Transonic Flows, abbreviated as DART) is an open-source C++/python, unstructured finite-element, full potential solver, that I developed at the University of Liège during my Ph.D. thesis, with the active collaboration of [Romain Boman](https://rboman.github.io/).
DART is currently capable of rapidly solving steady inviscid transonic flows on arbitrary configurations, ranging from 2D airfoils to 3D full aircraft, as well as calculating the flow gradients using a discrete adjoint method. Furthemore, the code is interfaced with [CUPyDO](https://github.com/ulgltas/CUPyDO) and [OpenMDAO](https://openmdao.org/), allowing aeroelastic analysis and optimization to be easily carried out. A viscous-inviscid interaction modeling technique is also being implemented so that viscous flows can also be rapidly computed.
{: .text-justify}

<p style="text-align:center">
<img src="https://gitlab.uliege.be/am-dept/dartflo/-/wikis/pics/main.png">
<figcaption style="text-align:center">Various aircraft models computed using DART.</figcaption>
</p>

<p style="text-align:center">
<img src="https://acrovato.github.io/assets/pics/m6.gif">
<figcaption style="text-align:center">Aerodynamic shape optimization of the ONERA M6 wing.</figcaption>
</p>

## dg-flo
[dg-flo](https://github.com/acrovato/dg-flo) is a small python code implementing the Discontinuous Galerkin method to solve various partial differential equations. I wrote this small demonstrator right after completing my Ph.D. to gain a better understanding of this method, as I find it very elegant and efficient to solve high-fidelity fluid dynamics problems. In the future, I hope to work on a full-scale DG code and apply the method to aircraft design.
{: .text-justify}

<p style="text-align:center">
<img src="https://user-images.githubusercontent.com/39187559/105607872-48f3ff00-5da1-11eb-915c-ebe5c6d45641.png">  
<figcaption style="text-align:center">dg-flo solution for the Sod's shock tube using the Euler equations.</figcaption>
</p>

<p style="text-align:center">
<img src="https://user-images.githubusercontent.com/39187559/105607735-dedb5a00-5da0-11eb-8b38-b21f4b53a02c.png">  
<figcaption style="text-align:center">dg-flo solution for the propagation of a tsunami in shallow water using the Saint-Venant equations.</figcaption>
</p>

## Enroute and Fluttair
When I performed my first solo cross-country flights, I was disapointed not to find a free Android application for Visual Flight Rules flying. Even if using a paper map is an important and required skill to learn, I think that having an app providing the real-time position on a moving map is reasuring for new pilots, and helps to avoid mistakes. This is especially true in Belgium, where the airspace is very crowded. In this regard, I started developing [Fluttair](https://github.com/acrovato/fluttair) towards the end of 2019. It also introduced me to a new type of programming. A few months later, I discovered that [Stefan Kebekus](https://github.com/kebekus) started to develop [Enroute Flight Navigation](https://github.com/Akaflieg-Freiburg/enroute). Due to the difficulty of maintaining up-to-date navigational data without renting a server, I decided to stop the development of Fluttair, and joined the Enroute development team. I initially implemented a few new features, such as the integration of weather information, and I currently help the team with translating the app in French.
{: .text-justify}

{% include gallery id="galleryFluttair" %}
<figcaption style="text-align:center">Sample screenshots from Fluttair.</figcaption>

{% include gallery id="galleryEnroute" %}
<figcaption style="text-align:center">Sample screenshots from Enroute.</figcaption>

