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
* Ph.D in Neuroscience, Indian Institute of Science, 2027 (expected)
* M.Tech. in Digital Signal Processing, Indian Institute of Space Science and Technology, 2021
* B.Engg. in Electronics and Communication Engineering, Chaitanya Bharati Institute of Technology, Osmania University, 2019
  
Skills
======
* Programming
  * Matlab, Python 
* Experimental Methods
  * Psychophysics (Psychtoolbox)
  * Electroencephalography (Biosemi, OpenBCI)
  * Eye Tracking (SMI & Eye Link)
* Signal Processing
* Machine Learning and Basics of Deep Learning
* Hypothesis testing & Statistics
* Scientific Communication
* Basic Electronic Design
* Misc.
 * Git, Shell scripting, Adobe Illustrator, Latex.

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
