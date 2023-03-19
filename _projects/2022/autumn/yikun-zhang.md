---
mentor: Yikun Zhang
title: Introduction to Density-based Clustering and its Applications
mentees:
  - name: Dongfeng Li
    slides: writeups/aut2022/slides/dongfeng.pdf
    writeup: writeups/aut2022/writeups/dongfeng.pdf
prereq: STAT 311 or STAT 340 or equivalent (knowledge of basic probability and statistics), some familiarity with programming in Python or R, etc.
year: 2022
quarter: autumn
---
In many, if not most, practical applications, the available observations do not spread evenly over the data space but are instead grouped into several clusters. This project is designed to investigate how to statistically uncover these clusters from observational (point cloud) data through density-based approaches. Such approaches, unlike the hierarchical clustering and other dissimilarity-based methods, leverage the (estimated) density from the data to define the clusters and do not require any dissimilarity metric in the clustering process. Among the family of density-based clustering approaches, we are planning to focus on mode clustering, during which the density kernel estimator and mean shift algorithm will be reviewed and discussed. Theoretically, we may study the consistency of mode clustering and its connection to the EM algorithm. Practically, we may apply the mode clustering to real-world data and present some interesting scientific analyses. Depending on the student's interest, the project can be either theory-oriented or coding-focused. We are also happy to survey more density-based clustering approaches such as DBSCAN or other clustering methods beyond the density-based domain according to any additional request from the student.