---
mentor: Wolfgang Brightenburg
title: Introduction to Gaussian Processes
prereq: linear algebra, recommended comfort with probability to the level of STAT 394, basic understanding of coding in R 
year: 2024
quarter: autumn
---

In this project, we’ll explore Gaussian processes for machine learning, a beautiful modeling framework which connects to a variety of rich mathematical, computational, and statistical subjects. In brief, Gaussian processes are powerful general function approximators, offering competitive predictive performance while yielding simple uncertainty quantification on their predictions. Using “Gaussian Processes for Machine Learning” by C. E. Rasmussen & C. K. I. Williams as our guide (freely available online by the authors, just give it a quick google!), we’ll start from the fundamentals of Bayesian linear regression, building our intuition and working our way towards deriving Gaussian process models as Bayesian nonparametric regression, in which inference is done over a general function space, a more general paradigm than tuning regression coefficients directly. Throughout our reading, we’ll code up our own models along the way and use them of applications of personal interest.  Following our base readings, we can continue the DRP in a variety of directions based on your interests- some potential ideas include learning about the close connections of GPs and neural networks through the Neural Tangent Kernel, retooling GPs for classification, and multitask learning with GPs, but there are many others we can explore!