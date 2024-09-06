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
* M.S. in Data Science, Salzburg University, 2022
* B.S. in Biology, Salzburg University, 2017
* Technical Informatics - Federal Higher Technical Institute Salzburg (June 2013)

Work experience
======
* June 2022 - Present: Researcher
  * Salzburg Research Forschungsgesellschaft
  * Duties includes:  Daten Visualisierung, Exploraitve Data Analysis, Modellentwicklung, Studiendesign, Datenaufzeichnung (Wearable sensors, motion tracking, IMU), Digital Signal Processing, Betreuung Forschungspartner, Literaturarbeit, Publikationen

* Juli 2019 - Dezember 2019: Data Analyst
  * Salzburg University (QM)
  * Duties included: Programming automated reporting of students evaluation, building Dashboards with Shiny
  
Skills
======
* R (tidyverse, knitR, shiny)
* Python (pandas, scipy, sklearn, pytorch)
* LaTeX
* Data Science
  * Data Visualisation 
  * Regression
  * Neuronal Networks (Deep learning)
  * Time Series Analysis
  * Exploraitve Data Analysis
* Modell Development
* Study design
* Field Measurements (Wearable sensors, motion tracking, IMU), * Digital Signal Processing
* Misc
  * Linux, Windows
  * Bash


Interests
======
* Sports
* Literature
* Gardening
* Fotography
* Biology - especially Neurobiology, Botany and Beahavioural Biology


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
  
