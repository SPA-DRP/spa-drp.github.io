---
mentor: Antonio Olivas
title: Estimation for cancer screening models using deconvolution
mentees:
  - name: Huayue Zou
    slides: writeups/spring2024/slides/lucia_slides.pdf
    writeup: writeups/spring2024/writeups/lucia_writeup.pdf
prereq: Calculus (MATH 126), exposure to probability theory (STAT 340), and experience with R.
year: 2024
quarter: spring
---
Cancer screening programs are an important component for secondary cancer prevention. To understand the conditions under which a cancer screening program provides the best benefit, mathematical models are used to estimate relevant quantities using information from cancer screening trials.
In the natural history of a cancer, the time to cancer onset (subclinical) and the sojourn/latent time (time between onset and clinical appearance) are two quantities of interest, but impossible to know separately.  However, by using a screening tool we obtain some information that allow us to differentiate between these two components.
In this project we will study a mathematical model that uses information at the aggregated level from a cancer screening trial to estimate mean time to onset, mean sojourn time, and sensitivity of the screening test, via the deconvolution formula and maximum likelihood estimation.