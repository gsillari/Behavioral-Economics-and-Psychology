---
title: Obermeyer et al. 2019
page_type: source
source_path: raw/papers/Obermeyer et al. 2019.pdf
source_type: paper
status: ingested
tags:
  - ai
  - behavioral-public-policy
  - health
  - source
updated_on: 2026-04-15
related_pages:
  - [[Target variable problem]]
  - [[Algorithmic bias]]
  - [[Predictive optimization]]
  - [[Behavioral economics of AI]]
  - [[Behavioral public policy]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Obermeyer et al. 2019: Dissecting racial bias in an algorithm used to manage the health of populations
## Summary

[[Obermeyer et al. 2019]] is one of the clearest empirical demonstrations of a now central source of algorithmic bias: the use of an apparently convenient and accurate proxy target that does not track the true normative objective. The paper studies a health-risk algorithm and shows that racial bias arose because the system predicted health care costs rather than illness, even though unequal access to care meant that cost was a systematically distorted proxy for need.

In the current vault, this paper matters because it identifies a mechanism of bias more specific than generic unfairness language. The problem is not only that the model makes unequal errors. It is that the target variable itself is wrong for the institutional purpose.

## Key claims

The first claim is that a widely used health-risk algorithm exhibited major racial bias.

The second claim is that the bias arose from predicting costs rather than health needs.

The third claim is that convenient, high-performing proxies for ground truth can encode structural inequality.

The fourth claim is that calibration or predictive success with respect to the chosen target does not settle whether the system is normatively adequate.

The fifth claim is that fixing algorithmic bias may require changing the target variable, not just debiasing the model.

## Why it matters for PPE

For PPE students, [[Obermeyer et al. 2019]] matters because it shows how technical design choices hide normative judgments. It matters for economics because it is a lesson about measurement and objective functions. It matters for public policy because it shows that institutions can optimize the wrong thing very effectively.

## Links into the wiki

This source should mainly strengthen [[Target variable problem]], [[Algorithmic bias]], [[Predictive optimization]], [[Behavioral economics of AI]], and [[Behavioral public policy]].

## Bibliographic reference

Obermeyer, Z., Powers, B., Vogeli, C., & Mullainathan, S. (2019). Dissecting racial bias in an algorithm used to manage the health of populations. *Science, 366*(6464), 447-453. https://doi.org/10.1126/science.aax2342
