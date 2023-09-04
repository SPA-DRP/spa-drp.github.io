---
mentor: Anna Neufeld
title: Multiple Testing
mentees:
  - name:  Cathy Qi
    slides: writeups/aut2021/slides/cathy.pdf
    writeup: writeups/aut2021/writeups/cathy.pdf
prereq: Stat 311 and some knowledge of R will be helpful, but not required.
year: 2021
quarter: autumn
---
In an introductory statistics course, you learn how to obtain a p-value to test a single null hypothesis. These p-values are constructed such that, when the null hypothesis is true, you will make a mistake and reject the null only 5% of the time. In the real world, scientists often wish to test thousands of null hypotheses at once. In this setting, making a mistake on 5% of the hypotheses could lead to a very high number of false discoveries. Multiple testing techniques aim to limit the number of mistakes made over a large set of hypotheses without sacrificing too much power. We will start with a review of hypothesis testing, then discuss the challenges posed by large numbers of hypotheses, and finally learn about modern multiple testing techniques. Towards the end of the quarter, we will apply the techniques we learned to real data.