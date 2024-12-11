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
* M.S in Artificial Intelligence, Nanyang Technological University, 2025 (expected)
* B.Tech in Computer Science and Engineering, Puducherry Technological University, 2024

Work experience
======
* August 2024 - Present: Research Intern
  * Speech and Language Lab @ NTU
  * Duties includes: Developing synthetic dialogue generation frameworks and code-switch dialogue summarization
  * Supervisor: Professor Eng Chng Siong

* Jan 2024 - June 2024: Machine Learning Engineer
  * Figr
  * Duties included: Backend of Figr AI
  

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
* Reviewer for COLING'25, 3rd DAI Workshop @ AAAI'25
