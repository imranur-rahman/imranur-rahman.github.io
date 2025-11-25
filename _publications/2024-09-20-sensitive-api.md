---
title: "What's in a Package? Getting Visibility Into Dependencies Using Security-Sensitive API Calls"
collection: publications
permalink: /publication/2024-09-20-sensitive-api
excerpt: 'We made a list of Security Sensitive APIs in Java using JDK documentation, past CVE fixes, and CWE examples. We then measured the prevalence of these Security-Sensitive API usage in our chosen 45 Java packages and in their dependencies. We finally conducted a developer survey to validate whether security-sensitive API information can be helpful in selecting dependencies.'
date: 2024-03-22
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2408.02846'
# citation: '@misc{rahman2024moremixedmethodsstudysecuritysensitive,
#       title={Less Is More: A Mixed-Methods Study on Security-Sensitive API Calls in Java for Better Dependency Selection}, 
#       author={Imranur Rahman and Ranidya Paramitha and Henrik Plate and Dominik Wermke and Laurie Williams},
#       year={2024},
#       eprint={2408.02846},
#       archivePrefix={arXiv},
#       primaryClass={cs.CR},
#       url={https://arxiv.org/abs/2408.02846}, 
# }'
---

Security sensitive APIs provide access to security-sensitive resources, e.g., the filesystem or network resources. Including such API calls -- directly or through dependencies -- increases the application's attack surface. An example of such a phenomenon is Log4Shell, which rendered many applications vulnerable due to network-related capabilities (JNDI lookup) in log4j package. Before the Log4Shell incident, alternate logging libraries to log4j were available that do not make JNDI lookup calls. The impact of such an incident would be minimal if information about network-related API calls by logging libraries were available to the developers. And so the lack of visibility into the calls to these security sensitive APIs by functionally similar open-source packages makes it difficult for developers to use them as a dependency selection criterion. The goal of this study is to aid developers in selecting their dependency by understanding security sensitive APIs in their dependency through call graph analysis. We conducted a mixed-methods study with 45 Java packages and defined a list of 219 security sensitive APIs. We then used call graph analysis to analyze the prevalence of these APIs in our selected package versions, with and without their dependencies. Finally, we conducted a survey with open-source developers (110 respondents) showing the comparison of functionally similar packages w.r.t. Security sensitive API calls to understand the usefulness of this API information in the dependency selection process. The number of Security sensitive API calls of functionally similar packages can vary from 0 to 368 in one API category and 0 to 429 in total. Our survey results show that 73% developers agree that information about the number and type of security-sensitive API calls of functionally similar packages would have been useful in their dependency selection.
