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
* B.Sc. in Electrical Engineering, KTH Royal Institute of Technology, 2016
* Exchange Year, Imperial College London, 2016-2017
* M.Sc. in Electrical Engineering, KTH Royal Institute of Technology, 2018

Work experience
======
* 2018-present: Machine Learning Engineering
  * SAAB
  * I conduct research into ways of improving electronic warfare systems on fighter jets with machine learning.
  * During my research, I have implemented several signal processing simulators for data generation, together with multiple deep learning and decision tree models. The results of the studies have been promising compared to existing algorithms.
  * Developed my knowledge of segmentation models, signal processing, particle filters, and time series analysis. Almost all code is developed in Python, and most machine learning models are built with PyTorch.

* Spring 2018: Master Thesis Student
  * Ericsson
  * Built a natural language processing algorithm using Hierarchical Temporal Memory (HTM) able to detect anomalies in system logs.
  * Concluded that anomaly detection using the HTM algorithm was able to preform as well or better than the existing machine learning systems. Leading to further development of products using HTM at Ericsson.
  * Gained in-depth knowledge in HTM theory and semantic vector encodings with natural language processing. The project was carried out in Python together with NuPIC and pandas.
  * Supervisor: Armin Catovic

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
