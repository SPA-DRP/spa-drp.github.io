---
mentor: Nina Galanter
title: "Optimal Treatment Rules: Causal Inference and Statistical Learning"
mentees:
  - name: Leah Jia
    slides: writeups/win2022/slides/leah.pdf
    writeup: writeups/win2022/writeups/leah.pdf
prereq: Some familiarity with conditional probability, linear regression, and R.
year: 2022
quarter: winter
---
In many biomedical and public health applications of statistics we are interested in determining the best treatment. However, people and their specific situations will vary and in some cases one treatment does not fit all! Instead, we can create a treatment rule which will take in a subject and their variables and predict the best treatment for them. We want to predict this as well as possible, and so we are looking for "optimal" rules. Optimal treatment rules involve both causal inference and statistical learning as we create rules based on estimated treatment effects. This project will first go over causal inference foundations and then explore Q-learning methods for treatment rules, which might include regression, penalized regression, and support vector machines depending on time and the student's background. We will use R to evaluate the methods with simulated and real data. If there is extra time, we could look into classification-based methods or dynamic treatment regimes.