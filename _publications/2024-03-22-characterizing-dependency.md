---
title: "Characterizing Dependency Update Practice of NPM, PyPI, and Cargo Packages"
collection: publications
permalink: /publication/2024-03-22-characterizing-dependency
excerpt: 'We quantified the updatedness of dependencies and updatedness of vulnerable dependencies in the context of open source dependencies in this project. The idea is very common in Reliability domain (e.g., Mean-Time-To-Update, Mean-Time-To-Repair, Mean-Time-To-Remediate). We did a large-scale study of our proposed update metrics in NPM, PyPI, and Cargo packages.'
date: 2024-03-22
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2403.17382'
citation: '@article{rahman2024characterizing,
  title={Characterizing Dependency Update Practice of NPM, PyPI and Cargo Packages},
  author={Rahman, Imranur and Zahan, Nusrat and Magill, Stephen and Enck, William and Williams, Laurie},
  journal={arXiv preprint arXiv:2403.17382},
  year={2024}
}'
---

Keeping dependencies up-to-date prevents software supply chain attacks through outdated and vulnerable dependencies. Developers may use packages' dependency update practice as one of the selection criteria for choosing a package as a dependency. However, the lack of metrics characterizing packages' dependency update practice makes this assessment difficult. To measure the up-to-date characteristics of packages, we focus on the dependency management aspect and propose two update metrics: Time-Out-Of-Date (TOOD) and Post-Fix-Exposure-Time (PFET), to measure the updatedness of dependencies and updatedness of vulnerable dependencies, respectively. We design an algorithm to stabilize the dependency relationships in different time intervals and compute the proposed metrics for each package. Using our proposed metrics, we conduct a large-scale empirical study of update metrics with 2.9M packages, 66.8M package versions, and 26.8M unique package-dependency relations in NPM, PyPI, and Cargo, ranging from the year 2004 to 2023. We analyze the characteristics of the proposed metrics for capturing packages' dependency update practice in the three ecosystems. Given that the TOOD metric generates a greater volume of data than the PFET metric, we further explore the numerical relationship between these metrics to assess their potential as substitutes for vulnerability counts metrics. We find that PyPI packages update dependencies faster than NPM and Cargo. Conversely, Cargo packages update their vulnerable dependencies faster than NPM and PyPI. We also find that the general purpose update metric, TOOD, can be a proxy for the security-focused update metric, PFET.
