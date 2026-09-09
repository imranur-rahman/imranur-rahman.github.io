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
* Ph.D in Computer Science, North Carolina State University, Aug 2022 - 2026 (expected)
  * Advisor: [Dr. Laurie Williams](https://www.csc.ncsu.edu/people/lawilli3)
  * Research Domain: Software Supply Chain Security
  * Dissertation: Reducing Attack Surface Through Vulnerable Dependencies
* M.S. in Computer Science, North Carolina State University, 2022 - 2024
  * Relevant Courses: Software Engineering, Software Security, Cryptography, System Attack & Defense, Advanced Network Security, OS Security, LLM Security, Generative AI for Software Engineering
* B.Sc. in Computer Science and Engineering, Bangladesh University of Engineering and Technology, 2014 - 2018

Work experience
======
* Sep 2026 - Dec 2026 (Ongoing): Research Fellow, [Supervised Program for Alignment Research (SPAR)](https://sparai.org/)
  * Project: ["Towards Automated Vulnerability Discovery and Repair with Safety-Governed AI Agents"](https://sparai.org/projects/f26/recNXku4CYlP490of/)
  * Mentor: [Dr. Yige Li](https://bboylyg.github.io/)

* August 2022 - Present: Graduate Research Assistant, North Carolina State University
  * Designed two novel metrics to characterize dependency-update practices of OSS packages, guiding dependency selection decisions for developers
  * Identified which dependency version constraints (pinning vs. floating) minimize outdated and vulnerable dependencies, published at ASE 2025
  * Measured security-sensitive API usage across open-source packages; compared functionally equivalent packages by their respective security-sensitive API usage
  * Devised a RAG pipeline using hybrid BM25 + FAISS retrieval for efficient context collection from repositories, winning 3rd Place at JetBrains/Mistral AI's ASE 2025 Context Collection Competition

Tech: Program Analysis, Data Analysis, Statistical Methods, Measurement, Qualitative Methods

* Dec 2018 - July 2022: Sr. Software Engineer, Samsung Research Bangladesh
  - Led a team to implement and maintain the Media Capture and Playback functionalities of Chromium Engine for Samsung smartwatches (Samsung Internet app)
  - Added W3C API support that facilitate Samsung's 50% web apps in the Galaxy Store
  - Shipped two user-facing features: gesture-based volume control (swipe up/down) and predictive buffering for network-interrupted playback
  - Developed a new approach (using NLP) to optimize the Recommendation Engine of Samsung
  - Proposed and prototyped a federated-learning recommendation engine to improve suggestions while preserving on-device user privacy

Tech: Chromium, C++, NLP, Federated Learning, Java

* Jun 2019 - July 2022: Contributor, [Chromium Open Source Project](https://chromium-review.googlesource.com/q/owner:ir.shimul%2540gmail.com)
  * Contributed to issues from diverse modules (e.g., Multimedia, Autofill etc) and gave others support
  
Skills
======
* Languages: Python, C/C++, Java, Javascript, TypeScript, Rust, Go
* Frameworks: React, Django, Tensorflow, Keras, PyTorch, LangChain, LLVM
* Research: Quantitative Research, Qualitative Research, Software Supply Chain Security, Software Security, Security Assessment, Statistical Modeling, Causal Inference, Survival Analysis, Empirical Software Engineering, Mining Software Repositories, Program Analysis, Static Analysis, Vulnerability Discovery, Vulnerability Fixing, AI agents, AI Security, AI Safety, Survey Design and Analysis
* Tools: Git, Docker, PostgreSQL, Oracle/SQL, LaTeX, Android, Linux, LLM APIs

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Patents
======
* "[Methods and Apparatus for Capturing Puddlegram in Smartphone Camera](https://patents.google.com/patent/US20250247609A1/en?q=%28imranur+rahman%29&oq=imranur+rahman&peid=63c83e2a28908%3A2c%3Ae8085f3c)." Chakraborty, T., Hossain, M.I., Hossain, M.J., Rahman, I.; US Patent 2025.

Awards & Honors
======
* [3rd Place in ASE 2025 Context Collection Competition](https://lp.jetbrains.com/research/context-collection-competition/) organized by JetBrains and Mistral AI

Service and leadership
======
* Artifact Evaluation Committee Member: Wisec '22, '23, CCS '23, '24, USENIX Security '22, '23, '24, PETS '23, '25, OSDI '23, USENIX ATC '23
<!-- - Conference Reviewer -->
* PC Member: MSR4PS '25, SecDev '26
* Journal Reviewer: TDSC, DTRAP
* Junior PC Member: MSR '24
* External Reviewer: ICNP '21, NDSS '22, USENIX Security '22, FSE '25, ICSE '26, '27
* CTF Problem Setter: HackPack CTF '24, '25
