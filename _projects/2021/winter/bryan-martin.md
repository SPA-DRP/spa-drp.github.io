---
mentor: Bryan Martin
title: Statistical Learning with Sparsity
mentees:
  - name: Jerry Su
prereq: Familiarity with regression, up to a STAT 311 level
year: 2021
quarter: winter
---
Many modern applications benefit from the principle of less is more. Whether due to practical computation concerns from big data, overfitting concerns from too many parameters, or estimability concerns from a small sample size, statistical models often require sparsity. Sparsity can improve our predictions, help make the patterns we observe in our data more reproducible, and give our model parameters desirable properties.

Often, sparsity is imposed through penalization, where we include a term in our model to enforce that some parameters are set equal to zero. We will learn about some of the statistical theory underlying how penalization works, and how it impacts our model output, both mathematically and computationally. We will also learn about and compare different sparsity schemes, such as lasso, group lasso, elastic net, and more. We will focus on understanding the different settings in which we might be interested in different forms of sparsity and apply these tools to real data.