---
title: "Independent Project: Simplifying and optimizing Kang (2020) with GeoPandas"
excerpt_separator: "<!--more-->"
categories:
  - Analysis
tags:
  - GIS
  - Science
---

## Simplifying and optimizing Kang (2020) with GeoPandas

Published in 2020, [Kang et al.](https://ij-healthgeographics.biomedcentral.com/articles/10.1186/s12942-020-00229-x)  measured the spatial accesibilty of COVID-19 resources in Illinois. A workflow I made for my replication of their study is shown below.

![workflow](/assets/images/workflow.jpg)

My contributions to the study:

# Making code more efficient and easier to read with GeoPandas
  Using native GeoPandas methods I improved two functions, __pop_centroid__ and __hospital_setting__ cutting down 5 minutes of combined processing time to less than a second.

# Simplifying code for future students
- Removed parallel processing from __overlapping_function__, __measure_acc_par__
- Removed the dropdown option that allowed the user to choose their population type, hospitals, and resource. This customization was not providing value other than to show that changes made did not make much difference. It also made code much less readable, and more likely for inconsistency in a replication. 
- Wrote detailed comments in every function, describing data structures, methods, and reasoning
- Removed of unneccessary codeblocks

My pre-registration of my reanalysis can be found [here.](https://github.com/benjamincordola/RPr-Kang-2020/blob/main/docs/report/cordola-reanalysis-plan.md)

Our updated paper can be found at this [GitHub Repository](https://github.com/benjamincordola/RPr-Kang-2020). You can view it as a [HTML Document](https://benjamincordola.github.io/RPr-Kang-2020/) here. 