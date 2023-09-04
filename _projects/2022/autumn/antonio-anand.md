---
mentor: Antonio Olivas and Anand Hemmady
title: Introduction to Survival Analysis
mentees:
  - name: Bao Han Ngo
    slides: writeups/aut2022/slides/baohan.pdf
    writeup: writeups/aut2022/writeups/baohan.pdf
  - name: Nathan Dennis
    slides: writeups/aut2022/slides/nathan.pdf
    writeup: writeups/aut2022/writeups/nathan.pdf
prereq: Familiarity with basic probability theory (random variables, distribution functions, expectation)
year: 2022
quarter: autumn
---
How can we understand and estimate the length of time that will elapse before some outcome of interest happens? This question is important for a wide range of applications, including (but certainly not limited to) problems in medicine and public health. To answer this question, we use tools from survival analysis. Analyzing survival data comes with a unique set of challenges that distinguish survival analysis from other fields of statistics. The most notable of these challenges is that survival data are often censored, meaning we can't see whether or when the event happened among some observations. We will first see the kind of problems that survival analysis can be used to address, with particular attention to problems involving censoring. We will then explore both parametric (e.g. MLE) and nonparametric (e.g. Kaplan Meier) methods for handling these problems, contrasting these approaches and learning about the advantages and disadvantages of each. Depending on student interest, we may also talk about the Cox regression model. We also plan to see how to compare survival curves with parametric models and the log rank test, and finally we will apply what we have learned to a particular problem (to be chosen in conjunction with the student).