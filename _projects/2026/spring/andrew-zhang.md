---
mentor: Andrew Zhang
title: Optimization and Sampling
prereq: Math 424. Familiarity with abstract integration is helpful.
bestfor: Junior (3rd year) or Senior (4th year or beyond)
numbermentees: 2
year: 2026
quarter: spring
mode: In-person only
---

Consider the problem of sampling from a distribution P, and suppose that we have a function f(Q) which measures the discrepancy between Q and the target P. For this notion of discrepancy to be meaningful, f should be minimized at P. The problem of sampling from P can therefore be thought of as trying to minimize f. In euclidean space, the fundamental optimization algorithm is gradient descent, but it is far from clear how to develop gradient descent on the space of probability measures. Remarkably, there is a way to do gradient descent on f: this fact is known as "Langevin dynamics is the Wasserstein gradient flow of relative entropy." We will try to understand what this means. Along the way, we will learn bits of optimization, stochastic calculus, optimal transport, and Riemannian geometry.