---
mentor: Nina Galanter
title: "Optimal Treatment Rules: Causal Inference and Statistical Learning"
mentees:
  - name: Max Bi
    slides: writeups/spring2022/slides/max.pdf
    writeup: writeups/spring2022/writeups/max.pdf
prereq: Some familiarity with conditional probability, linear regression, and R
year: 2022
quarter: spring
---
In many biomedical and public health applications of statistics we are interested in determining the best treatment. However, people and their specific situations will vary and in some cases one treatment does not fit all! Instead, we can create a treatment rule which will take in a subject and their variables and predict the best treatment for them.  Optimal treatment rules involve both causal inference and statistical learning as we create rules based on estimated treatment effects. This project will first go over causal inference foundations and then explore Q-learning methods for treatment rules, which might include regression, penalized regression, or generalized additive models depending on time and the student's background. We will use R to evaluate the methods with simulated data.