---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
{% assign sorted_degrees = site.data.education | sort: "start_date" | reverse %}
{% for degree in sorted_degrees %}
  {% include education-item-cv.md %}
{% endfor %}

Work experience
======
* <strong>Graduate Research Assistant, 2019.9 \- 2023.8</strong>
  * The University of British Columbia - Mathematics & Mechanical Engineering
  * Supervisor: Prof. Anthony Wachs
  * Duties: 
    1. Developing state-of-the-art numerical algorithms for solving partial differential equations.
    1. Leveraging machine learning methods and neural networks to explore certain patterns underlying the big data obtained from simulations.
    1. Data post-processing and visualization using Python (matplotlib, numpy, pandas, etc.) and MATLAB.

* <strong>Graduate Teaching Assistant, 2021.1 \- 2022.4</strong>
  * The University of British Columbia - Mechanical Engineering - MECH 358: Engineering Analysis
  * Instructor: Prof. Gwynn Elfring
  * Topics: Review of linear algebra. Iterative methods for linear and nonlinear systems. Review of ordinary differential equations (ODEs). Numerical solution of ODEs. Introduction to partial differential equations (PDEs). Classification of PDEs. Derivation and solution of the advection equation, heat equation and wave equation. Applications to mechanical engineering and practical computing emphasized.
  * Duties: 
    1. Delivering MATLAB tutorials of numerical methods for solving ordinary and partial differential equations.
    1. Delivering lessons of linear algebra for solving discretized equations.
    1. Marking assignments and quizzes.

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Skills
======
* C/C++/C#
* Python
  * Numpy, Matplotlib, Seaborn, Pandas...
  * Scikit-Learn, Scipy, XGBoost, TensorFlow (Keras API)
* MATLAB
* FORTRAN
* Git (entry level)
* SQL (entry level)
* Tableau (entry level)

<!-- Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
   -->

