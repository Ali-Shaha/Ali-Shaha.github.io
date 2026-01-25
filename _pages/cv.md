---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Mechanical Engineering, Aalto University, 2019-2024
* M.Sc. in Mechanical Engineering, Tarbiat Modares University, 2015-2018  
* B.Sc. in Mechanical Engineering, Amirkabir University of Technology, 2011-2015

Work experience
======
* **2023-Present: CFD Expert, Elcogen Oy**
  * CFD modeling of solid oxide fuel cells and electrolyzers at unit-layer, stack, and module scales
  * Developing thermo-electrochemical simulation models
  * Stack-module thermal balance concepts and CFD simulation methodologies

* **2019-2023: Research Assistant , Aalto University**
  * Conducted combustion modeling on gasoline surrogates (PRF and PRF-ethanol blends)
  * Performed chemical kinetics analysis (ignition delay, flame speed) and developed skeletal mechanisms
  * Simulated end-gas flame-ignition characteristics and hotspot-induced auto-ignition regimes (knock/super-knock)
  * Implemented analytical Jacobian calculators and ODE solvers for faster chemistry solutions

* **2017-2019: Researcher, Tarbiat Modares University (CFD LAB)**
  * Conducted research on Large Eddy Simulation (LES) of Turbulent Jet Flames
  * Investigated extinction and re-ignition events in turbulent combustion
  * Advised MSc students for simulation and C++ programming in OpenFOAM
  
Skills
======
* **Programming Languages:** C/C++, Python, MATLAB, R, Fortran, LaTeX
* **CFD & Engineering Software:** OpenFOAM, COMSOL, ANSYS Fluent, Cantera, Star CCM+, CHEMKIN
* **Computational Methods:** Finite Volume, Finite Difference, Statistical Modeling
* **Research Areas:**
  * Computational Fluid Dynamics (CFD)
  * Electrochemistry & Multiphysics Modeling 
  * Combustion Modeling & Chemical Kinetics
  * Turbulence Modeling (LES, RANS)
  * Multi-Phase Fluid Dynamics
  * Internal Combustion Engines
  * High-Performance Computing
  * Optimization Techniques

Languages
======
* Persian (Native), English (Fluent), Finnish (Intermediate)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
