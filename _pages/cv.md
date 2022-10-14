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
* B.S. in Electrical and Computer Engineering, Shanghai Jiao Tong University, 2016 - 2018
* B.S. in Computer Engineering, University of Michigan, 2018 - 2020
* Ph.D in Computer Science, Georgia Institute of Technology, 2021 - Now

Work experience
======
* Systems Technology Research Intern (May - Aug 2022)
  * Studied Samsung’s SmartSSD prototype product and designed a performance model to predict the acceleration performance based on device experiments
  * Designed and developed a tool with Intel pin to divide and profile separate workload regions for offload performance prediction
  * Collaborator: Sahand Salamat, Rekha Pitchumani

* Hardware Engineer @ SambaNova Systems (2020 - 2021)
  * Designed and optimized hardware programming for layer normalization algorithms with in-house assembly and integrated the template across software stack
  * Implemented DDR shim RTL for new chip generation; Adapted from single-channel DDR4 to dual-channel DDR5
  * Optimized DDR shim microarchitecture: proposed fine-grained credit management to adapt to more requesters; proposed fifo and arbitration structure to improve shim response throughput
  * Automated performance analysis of parallelization factors in convolutional templates with python; collected throughput and resource utilization information and analyzed patterns for optimal resource efficiency

  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Other experience
======

* Teaching Assistant for EECS470 - Computer Architecture (2019 - 2020)
  * Coordinate course projects and hold office hours
  * Give and grade homework and exam problems
  * Supervisor: Prof. Ronald Dreslinski

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
