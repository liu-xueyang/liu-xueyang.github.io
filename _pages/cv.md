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
* Graduate Research Assistant @ [HPArch](https://sites.gatech.edu/hparch/) (Sep 2021 - May 2024)
  * Researched heterogeneous systems where GPUs are directly connected to storage; built cycle-lev
simulators for such platform by connecting macsim(GPU) and MQSim(SSD) simulators
  * Identified SSD contention bottlenecks; evaluated GPU threadblock scheduling algorithms and
proposed the new CA-scheduler that accounts for SSD internal property
  * Built infrastructure to evaluate large GPU benchmarks including graph and machine learning
  * Mentor: Hyesoon Kim

* Computing Research Intern @ Lawrence Livermore National Laboratory (May - Aug 2023)
  * Integrated ZHW accelerator into MoSAIC, a heterogeneous tile-based SoC platform at RTL level
  * Implemented compression software using MoSAIC APIs; evaluated and optimized date
movement between CPU and memory by proposing bew commands
  * Mentor: Maya Gokhale

* Systems Technology Research Intern @ Samsung (May - Aug 2022)
  * Studied Samsung’s SmartSSD prototype product and designed a performance model to predict
the acceleration performance based on device experiments
  * Designed and developed a Intel pin tool to divide and profile separate workload regions for
offload performance prediction
  * Mentor: Sahand Salamat

* Hardware Engineer @ SambaNova Systems (Jun 2020 - Jun 2021)

  
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

* Chair, Graduate Student Association Mental Health Committee (Sep 2023 - May 2024)
  * Led bi-weekly discussions on mental health challenges specific to graduate students and
brainstorm on actions
  * Connect with directors and staff at Center for Mental Health and Resource(CMHCR) to clarify
on-campus resources, seek support for collaborations
  * Held mental health town hall meeting in spring 2024, bringing together CMHCR staff and the
student body to promote on-campus mental health service and address student questions

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
