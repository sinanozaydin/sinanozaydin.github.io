---
permalink: /
title: "Sinan Özaydın"
excerpt: "About me"
author_profile: true
header:
  overlay_color : "#000"
  overlay_filter: "0.5"
  overlay_image: banner_about.jpeg
  actions:
  caption: ""
excerpt: "Earth Scientist"
redirect_from:
  - /about/
  - /about.html
---

About Me
======
I am an Earth scientist and postdoctoral research associate at the University of Sydney. My research focuses on understanding how the electrical conductivity structure of Earth's lithosphere relates to tectonic and magmatic processes. Using magnetotelluric data, I combine insights from petrophysical measurements, geochemistry, petrology, and thermomechanical modelling to develop quantitative interpretations of deep Earth processes.

A key component of my work involves developing open-source software tools that bridge the gap between laboratory petrophysical measurements and field observations, enabling more robust and reproducible geophysical interpretations:

---
<img src="/images/pide_logo.png">

<https://github.com/sinanozaydin/pide>

`pide` is a Python3 library for calculating geophysical parameters (e.g., electrical conductivity, seismic velocity), employing the results from experimental petrology, mineral/rock physics, and thermomechanical modelling studies. `pide` can calculate the theoretical electrical conductivity of any earth material that exists in the literature. `pide` can also calculate seismic velocity utilising the external 'sister' library `santex`. Using these theoretical calculations, users can utilise inversion modules to decode geophysical anomalies compositionally or convert thermomechanical models into geophysical observables. With a given spatial mapping of earth materials, which can preferentially be loaded from a thermomechanical model, `pide`  can be used to build synthetic electrical conductivity and seismic velocity models and generate gravity and magnetic anomalies. Moreover, it is built as a modular tool, so users can easily build their functions.

<img src="/images/website_pide.png">

---
<img src="/images/mate_full.png">

<https://github.com/sinanozaydin/MATE>

MATE is an easy-to-use piece of software written in python3 for making interpretations of magnetotelluric models of the mantle. The software does this by combining the information of many high-pressure and temperature experimental studies (e.g., conductivity, hydrogen diffusion, hydration of minerals) for given compositional and thermal profile.

<img src="/images/mate_prog.png">

---
SAnTex
======
 <https://github.com/utpal-singh/SAnTex>

Developed by Utpal Singh, `SAnTex` is a Python library which calculates the full elastic tensor of rocks from modal mineral composition, crystallographic orientation, and a crystal stiffness tensor catalogue that accounts for the dependency of elasticity with pressure and temperature.

<img src="/images/website_santex.png">