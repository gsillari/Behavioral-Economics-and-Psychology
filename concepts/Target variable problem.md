---
title: Target variable problem
page_type: concept
status: active
tags:
  - ai
  - behavioral-public-policy
  - methodology
updated_on: 2026-04-15
source_count: 2
related_pages:
  - [[Obermeyer et al. 2019]]
  - [[Wang et al. 2024]]
  - [[Algorithmic bias]]
  - [[Predictive optimization]]
  - [[Behavioral economics of AI]]
  - [[Behavioral public policy]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Target variable problem

## Core idea

[[Target variable problem]] is the problem that an algorithm may optimize a measurable proxy rather than the institution's real objective. In the current vault, the anchor source is [[Obermeyer et al. 2019]], with [[Wang et al. 2024]] as the broader extension. The core lesson is that a system can be accurate with respect to its chosen label and still be normatively defective because the label is the wrong target.

## Key distinctions

This concept differs from [[Algorithmic bias]] in general. Bias can arise from many sources. The target variable problem identifies one especially important source: the institution has asked the system to predict the wrong thing.

It also differs from a simple data-quality problem. Better data will not solve the problem if the target itself is conceptually misaligned with the real objective.

## Evidence and debate

[[Obermeyer et al. 2019]] gives the canonical case in the current vault. A health algorithm used cost as a proxy for need, and because cost reflected unequal access to care, Black patients were systematically underserved despite the model performing well against its chosen label. [[Wang et al. 2024]] generalizes this insight by showing that predictive systems often inherit contested and shifting targets, so apparent optimization gains may rest on dubious proxies or on objectives that institutions cannot defend.

This makes the target variable problem one of the strongest bridges between technical design and institutional legitimacy. It shows that the bias question is often upstream of the model.

## Practical or policy relevance

This concept matters because public and private institutions often choose targets for convenience, measurability, or legacy availability. If the target is a distorted proxy for the actual purpose of the system, then optimization can amplify injustice while still looking technically successful.

## Related pages

The anchor sources are [[Obermeyer et al. 2019]] and [[Wang et al. 2024]]. The closest neighboring pages are [[Algorithmic bias]], [[Predictive optimization]], [[Behavioral economics of AI]], and [[Behavioral public policy]].

## Open questions

How can institutions tell when a target variable is an acceptable proxy and when it is distorting the real objective? When should a proxy be treated as evidence of deeper institutional injustice rather than as a neutral measurement shortcut? And can target misalignment be fixed locally, or does it often require redesign of the surrounding institution?
