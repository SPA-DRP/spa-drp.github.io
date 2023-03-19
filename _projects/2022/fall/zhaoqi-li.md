---
mentor: Zhaoqi Li
title: Introduction to Adaptive Experimental Design
mentees:
  - name: Zilin Huang
    slides: writeups/aut2022/slides/zilin.pdf
    writeup: writeups/aut2022/writeups/zilin.pdf
prereq: Either some mathematical maturity at the level of STAT 394, or some familiarity with Python.
year: 2022
quarter: autumn
---
Suppose you are in Vegas facing three lottery machines, each with a different probability of winning a prize. You would like to figure out which one wins the most, so you try out these machines. After trying out many times, you start thinking about strategies: should I find the lottery machine that has the highest probability of winning the prize and keep playing that machine, or should I find the best way to play so I could lose the least amount of money in 100 rounds? Surprisingly, these two strategies lead to different answers, and lead to two branches in multi-armed bandits. This field has close applications to large tech companies like Amazon, Google, Meta, etc, and connects between statistics, computer science, and economics. In this project, we will first review some well-known approaches in multi-armed bandits, and either give a broad overview of the latest approaches for adaptive experimental design or conduct some experiments to visualize the power of these methods depending on student's background.