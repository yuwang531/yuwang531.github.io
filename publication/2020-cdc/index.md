---
title: "Statistically Model Checking PCTL Specifications on Markov Decision Processes via Reinforcement Learning"
date: 2020-07-16
publishDate: 2020-07-16
authors: ["Yu Wang", "Nima Roohi", "Matthew West", "Mahesh Viswanathan", "Geir E. Dullerud"]
publication_types: ["1"]
abstract: "Probabilistic Computation Tree Logic (PCTL) is frequently used to formally specify control objectives such as probabilistic reachability and safety. In this work, we focus on model checking PCTL specifications statistically on Markov Decision Processes (MDPs) by sampling, e.g., checking whether there exists a feasible policy such that the probability of reaching certain goal states is greater than a threshold. We use reinforcement learning to search for such a feasible policy for PCTL specifications, and then develop a statistical model checking (SMC) method with provable guarantees on its error. Specifically, we first use upper-confidence-bound (UCB) based Q-learning to design an SMC algorithm for bounded-time PCTL specifications, and then extend this algorithm to unbounded-time specifications by identifying a proper truncation time by checking the PCTL specification and its negation at the same time. Finally, we evaluate the proposed method on case studies."
featured: false
publication: "*59th IEEE Conference on Decision and Control (CDC)*"
url_pdf: "https://arxiv.org/abs/2004.00273"
---

