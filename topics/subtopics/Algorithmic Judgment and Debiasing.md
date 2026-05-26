---
title: Algorithmic Judgment and Debiasing
page_type: topic
status: active
tags:
  - topic
  - ppe
  - behavioral-economics
  - ai
updated_on: 2026-05-26
related_pages:
  - [[AI, Algorithms, and New Frontiers]]
  - [[Clinical versus actuarial judgment]]
  - [[Dawes and Corrigan 1974]]
  - [[Bar-Gill et al. 2023]]
  - [[Kleinberg et al. 2016]]
  - [[Corbett-Davies et al. 2017]]
  - [[Narayanan 2026]]
  - [[Chouldechova and Roth 2020]]
  - [[Kleinberg et al. 2024]]
  - [[Kleinberg et al. 2018]]
  - [[Ludwig and Mullainathan 2021]]
  - [[Angwin et al. 2016]]
  - [[Algorithmic bias]]
  - [[Algorithmic harm]]
  - [[Statistical fairness criteria]]
  - [[Inversion problem]]
  - [[Predictive optimization]]
---

# Algorithmic Judgment and Debiasing

## Scope

This topic gathers the parts of the vault concerned with comparing human and algorithmic judgment and with improving decision quality in artificial systems. In the current vault, the key upstream page is [[Clinical versus actuarial judgment]], now strengthened by [[Dawes and Corrigan 1974]] as the clearest pre-AI explanation of why simple linear prediction rules can outperform human discretion in structured tasks. The contemporary branch is joined by [[Kleinberg et al. 2018]] as the clearest high-stakes case and by [[Ludwig and Mullainathan 2021]] as the clearest account of why real deployments remain fragile. [[Algorithmic bias]] supplies the fairness-and-legitimacy branch that keeps the topic from collapsing into a simple defense of prediction. [[Kleinberg et al. 2016]] now gives that branch a more formal anchor by showing that fairness conditions for risk scores can be structurally incompatible, while [[Corbett-Davies et al. 2017]] shows how those criteria can be treated as constraints relative to policy objectives. [[Narayanan 2026]] adds the system-level warning that fairness is not a property of the algorithm alone but of the whole algorithmic bureaucracy. [[Chouldechova and Roth 2020]], [[Statistical fairness criteria]], [[Inversion problem]], and [[Predictive optimization]] now give the branch clearer internal structure.

## Current focus

The topic page is currently a structural stub so [[AI, Algorithms, and New Frontiers]] can present a distinct algorithmic-judgment branch. A later drafting pass should explain how older debates about simple models and expert judgment connect to newer debates about AI systems. [[Dawes and Corrigan 1974]] supplies the pre-machine-learning logic: if the task has codable cues, monotone relationships, and noisy measurement, stable linear combination may beat human judgment even without sophisticated optimization. In the current vault, [[Kleinberg et al. 2018]] is the natural bridge source because it shows how the older actuarial-clinical argument changes once machine learning, selective labels, and fairness constraints enter the picture. [[Ludwig and Mullainathan 2021]] then explains why that bridge does not imply blind algorithmic optimism: algorithms are fragile because human designers choose labels, objectives, override structures, procurement standards, and regulatory safeguards. [[Angwin et al. 2016]] matters alongside it because it made the fairness and opacity problem publicly unavoidable, giving the branch a second anchor in [[Algorithmic bias]] rather than only in prediction quality. [[Kleinberg et al. 2016]] then adds the formal fairness-tradeoff theorem that helps explain why those disputes persist even under more precise statistical language. [[Corbett-Davies et al. 2017]] adds the constrained-optimization bridge: once criteria conflict, choosing a definition of bias means choosing a regulatory objective and a fairness constraint. [[Narayanan 2026]] then shifts the question from "which metric is fair?" to "what would make this whole decision-making system publicly defensible?" [[Chouldechova and Roth 2020]] then widens the same branch by showing that fairness problems are not only about metric choice in static classification, but also about biased data, dynamic systems, fair representation, and learning under feedback. [[Kleinberg et al. 2024]] adds a different challenge through [[Inversion problem]] by arguing that many systems predict behavior while institutions really hope to infer preferences, welfare, or reflective judgment. [[Bar-Gill et al. 2023]] adds a neighboring consumer-market path through [[Algorithmic harm]], where the central issue is not only comparative prediction quality but the use of algorithms to exploit information deficits and behavioral vulnerabilities.
