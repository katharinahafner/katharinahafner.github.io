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
* Ph.D in Physics, University of Bremen, 2026
  * Supervisor: Prof. Veronika Eyring
  * Thesis: [Interpreting and improving the radiation parameterization for ICON with machine learning](https://doi.org/10.26092/elib/5535)
* M.Sc. in Physics, RWTH Aachen University, 2021
  * Supervisor: Prof. Martin Erdmann
  * Thesis: [Autoencoder-extended Conditional Invertible Neural Networks for Unfolding of Radio Signals at the Pierre Auger Observatory](https://www.institut3a.physik.rwth-aachen.de/global/show_document.asp?id=aaaaaaaabiiadjg)
* B.Sc. in Physics, RWTH Aachen University, 2019
  * Supervisor: Prof. Martin Erdmann
  * Thesis: [Refinement of Simulated Air Shower Detector Traces using Cycle-Consistent Adversarial Networks](https://www.institut3a.physik.rwth-aachen.de/global/show_document.asp?id=aaaaaaaaaiqjfjo)

Work experience
======
* Since March 2026: Postdoctoral Researcher
  * University of Lausanne
  
* Feb 2022 - Feb 2026: Research Assistant
  * University of Bremen

Skills
======
* Machine Learning
  * Supervised Learning
  * Generative Modelling
  * explainable AI
* Climate Modelling
  * Atmosphere
  * Radiation
  * ICON
* Programming
  * Python 
  * LaTeX
  * Bash
  * Fortran
  * TypeScript/JavaScript
* Languages
  * German (native)
  * English (fluent)
  * French (basic)

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
  
Service and leadership
======
* Reviewer for JAMES
* Convener for Machine Learning for Climate Science at EGU General Assembly 2026
