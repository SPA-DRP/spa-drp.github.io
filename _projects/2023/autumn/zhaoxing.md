---
mentor: Zhaoxing Wu
title: Classify High-Dimensional Data
mentees:
    - name: Elvin Liu
      slides: writeups/aut2023/slides/elvin.pdf
      writeup: writeups/aut2023/writeups/elvin.pdf
prereq:  Some programming experience with R
year: 2023
quarter: autumn
---
In machine learning, classification is a task that assigns a class label to examples from the problem domain. However, high dimensionality poses significant statistical challenges and renders many traditional classification algorithms impractical to use. In this project, we will first learn or review (depends on student’s background) some classical supervised classification techniques and discuss the curse of dimensionality. Next, we will mainly explore Penalized Discriminant Analysis (PDA) which is designed to classify high-dimensional data as an extension of the classical Linear Discriminant Analysis. It classifies data by finding the optimal lower-dimension projections that reveal "interesting structures" in the original dataset. If time permits, students will implement PDA to analyze a real-life dataset of the student’s choice or some simple toy examples.