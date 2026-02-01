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
* B.S. in Deparment of IT Convergence, University of Ulsan (UOU), 2026

Work experience
======
* Mar, 2025 - Dec, 2025: Research Assistant
  * University of Ulsan (UOU)
  * Duties included: Multimodal Learning for Early Neurological Deterioration Prediction in Acute Ischemic Stroke
  * Collaboration with <i>Ulsan University Hospital</i>
  * Supervisor: Daehwan Kim

* Jan, 2025 - Feb, 2025: Research Intership
  * <a href="https://www.etri.re.kr/intro.html?t=1769935360101">Electronics and Telecommunications Research Institute (ETRI)</a>
  * Duties included: Performance analysis and benchmarking of large-scale data visualization tools

* Apr, 2024 - Dec, 2024: Research Assistant
  * University of Ulsan (UOU)
  * Duties included: Spinal Segmentation and Contrastive Learning for Lenke Classification in Adolescent Idiopathic Scoliosis
  * Collaboration with <i>Asan Medical Center</i>
  * Supervisor: Daehwan Kim
  
Skills
======
* Code
  * Python & PyTorch ... etc.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Academic activites
======
* Mentor, Medical AI Team, <a href="https://www.deepdaiv.com/">deep daiv.</a> `24 Spring Challenge
  * Provided guidance and led 2 teams
  * Biosignal team: ECG Arrhythmia classification using 1D-CNN-based network
	* Medical image team: Brain tumor segmentation using U-Net-based network

* Member (Team Leader), <a href="https://www.deepdaiv.com/">deep daiv.</a> `24 Winter Challenge
	* Biosignal team: EEG state classification using Mamba

* Member (Team Leader), Medical AI Team, deep daiv. `23 Summer Challenge
	* Clinical data team: Data engineering for MIMIC-IV database

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