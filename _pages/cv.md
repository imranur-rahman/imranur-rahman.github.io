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
* Ph.D in Computer Science, North Carolina State University, 2026 (expected)
* M.S. in Computer Science, North Carolina State University, 2024
* B.Sc. in Computer Science and Engineering, Bangladesh University of Engineering and Technology, 2018

Work experience
======
* August 2022 - Present: Graduate Research Assistant, North Carolina State University
  * Designed two metrics to characterize dependency update practice of open-source packages
  * Measured security-sensitive API usage by open-source packages and compared similar functioning packages with their respective security-sensitive API usage

Tech: Program Analysis, Data Analysis, Statistical Methods, Measurement, Qualitative Methods

* Dec 2018 - July 2022: Sr. Software Engineer, Samsung Research Bangladesh
  - Led a team to implement and maintain the Media Capture and Playback functionalities of Chromium Engine for Samsung smartwatches
  - Added W3C API support that facilitate Samsung's 50% web apps in the Galaxy Store
  - Implemented two new features for audio/video playback in Samsung's smartwatches, controlling volume by swiping up/down from the UI and buffering beforehand to handle network failure
  - Developed a new approach (using NLP) to optimize the Recommendation Engine of Samsung
  - Proposed a federated learning approach in the recommendation engine to maintain user's privacy

Tech: Chromium, C++, NLP, Federated Learning, Java

* Conributor: Chromium Open Source Project
  * Contributed to issues from diverse modules (e.g., Multimedia, Autofill etc) and gave others support
  
Skills
======
* Code: C/C++, Python, Java, Javascript, Node.js, React, Django, Tensorflow, Keras
* Tools: Git, Latex, Android, Oracle, Postgresql, Docker

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
* Artifact Evaluation Committee Member: Wisec '22, '23, CCS '23, '24, USENIX Security '22, '23, '24, PETS '23, '25, OSDI '23, USENIX ATC '23
<!-- - Conference Reviewer -->
* PC Member: MSR4PS '25
* Junior PC Member: MSR '24
* External Reviewer: ICNP '21, NDSS '22, USENIX Security '22, FSE '25
* CTF Problem Setter: HackPack CTF '24, '25
