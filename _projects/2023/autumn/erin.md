---
mentor: Erin Lipman
title: "Bayesian perspectives on probability and statistics: Part 2"
mentees:
    - name: Leila Peitsch
      slides: writeups/aut2023/slides/leila.pdf
      writeup: writeups/aut2023/writeups/leila.pdf
prereq: This is a continuation of a DRP project from Spring 2023, and is not open for new applications
year: 2023
quarter: autumn
---
The simplest Bayesian models are those that use a conjugate prior, meaning that the posterior distribution can be computed directly (i.e. we can write down its probability density function). In most real-world analyses however, especially those with more than one parameter, this is not the case. In general, the posterior distribution has to be approximated in another way, usually using a method called Markov Chain Monte Carlo. In this continuation of a Spring 2023 DRP, we will learn about and implement methods for sampling from the posterior distribution of a Bayesian model.