---
title: "Kang Threats to Validity"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - GIS
  - Science
---
## Threats to Validity in Kang et al. (2020)
Rapidly measuring spatial accessibility of COVID-19 healthcare resources: a case study of Illinois, USA [*link*](https://ij-healthgeographics.biomedcentral.com/articles/10.1186/s12942-020-00229-x). 

While my reanalysis of Kang et al. (2020) will not drastically change any procedures of geographic analysis, there are some important threats to the validity that matter when understanding the scope of the study. A concern around the spatial heterogeneity of hospitals is a threat to the validity of the study. The study assumes that the only factor when choosing a hospital is the closeness of the hospital to an individual. This assumption is necessary to run the study, but does not take into account that all hospitals are not the same, and patients often have very good reasons for choosing to go to a hospital that might not be the closest to their house, like type of insurance accepted, medical history with providers, and the type and specialty of hospital (academic medical center vs physician run clinics). This is especially true when considering what a hospitilization due to COVID-19 would look like. Unlike an ambulance rushing a patient to the nearest emergency room after a car accident, a COVID-19 patient, generally speaking, will have been getting increasingly more and more sick, with time to think about what hospital they might go to for treatment, when breathing or vitals reached a critical point. A bed or ventilator is not the same everywhere, and comparing them between hospitals as if they are all equal could be a threat to the validity of the study. 

While solving for this threat to validity is not within the scope of my reanalysis, including a few variables describing significant differences between hospitals could help control for preference amongst individuals. You could also look at how many covid patients hospitals received as a percentage of their total capacity, and use this percentage to weight more preferred hospitals higher in terms of their desireability, and more obscure hospitals less importance in the visualizations.