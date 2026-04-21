---
title: Statistical fairness criteria
page_type: concept
status: active
tags:
  - ai
  - behavioral-public-policy
  - law
updated_on: 2026-04-18
source_count: 5
related_pages:
  - [[Kleinberg et al. 2016]]
  - [[Chouldechova and Roth 2020]]
  - [[Hellman 2020]]
  - [[Binns 2018]]
  - [[Hedden 2021]]
  - [[Algorithmic bias]]
  - [[Predictive optimization]]
  - [[Behavioral public policy]]
  - [[Behavioral law and economics]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Statistical fairness criteria

## Core idea

[[Statistical fairness criteria]] are formal conditions used to evaluate whether algorithmic predictions or classifications treat groups fairly. In the current vault, this concept is anchored by [[Kleinberg et al. 2016]], [[Hellman 2020]], [[Binns 2018]], and [[Hedden 2021]]. Together they show that fairness metrics are neither interchangeable nor purely technical. They encode different ideas about what should matter: calibration, error parity, equalized opportunity, or the fair distribution of burdens.

## Key distinctions

This concept differs from [[Algorithmic bias]], which is the broader problem of patterned, unequal, or unjust algorithmic outcomes. Statistical fairness criteria are one family of tools for diagnosing and debating that broader problem.

It also differs from [[Predictive optimization]]. Predictive optimization is a model of institutional decision-making built around predictions. Statistical fairness criteria are among the standards used to evaluate such systems, but they do not settle whether predictive optimization is legitimate in the first place.

For teaching purposes, four criteria are especially useful to keep separate. Calibration means that a given score should have the same empirical meaning across groups: for example, a risk score of 7 should correspond to roughly the same observed risk in each group. False-positive parity means groups should not face different rates of being wrongly flagged as high risk. False-negative parity means groups should not face different rates of wrongly being treated as low risk. Equalized odds combines both error-rate constraints, while equal opportunity usually focuses only on parity in the true-positive side of the decision. These are not interchangeable desiderata; they express different ideas about what it would mean for an algorithmic decision rule to be fair.

## Evidence and debate

[[Kleinberg et al. 2016]] gives the best-known formal result: some attractive fairness conditions cannot generally all be satisfied at once when base rates differ. [[Chouldechova and Roth 2020]] is then useful as the best survey source in the current vault for locating those criteria inside a broader map of the field. It shows why work has concentrated on statistical definitions, why those definitions remain attractive, and why they still leave unresolved the problem of individual-level meaning. [[Hellman 2020]] then interprets the metrics more normatively, arguing that predictive parity is closer to a norm of belief while error-rate disparities matter more directly for the fairness of action. [[Binns 2018]] places these metrics inside older disputes in political philosophy by showing that different formal definitions echo different moral ideas about equality, discrimination, and justice. [[Hedden 2021]] adds a sharper critique by arguing that many purported statistical criteria are not necessary for fairness at all and by defending calibration as especially significant.

Taken together, these sources show why algorithmic-fairness debate is so persistent. Some of the conflict is empirical, but much of it comes from the fact that the criteria themselves track different normative concerns. The impossibility result therefore should not be read as a technical nuisance affecting only specialists. It shows that fairness is not a single scalar property of a predictive system. Institutions often have to choose between preserving the cross-group meaning of scores and equalizing how prediction errors are distributed across groups.

## Practical or policy relevance

This concept matters because institutions often ask whether an algorithm is fair before asking what fairness metric they are using. In criminal justice, lending, health, and hiring, different choices among calibration, false-positive parity, false-negative parity, and related conditions can redistribute burdens dramatically. That is why the metric question is not a side issue. It is part of the policy decision itself.

## Related pages

The anchor sources are [[Kleinberg et al. 2016]], [[Chouldechova and Roth 2020]], [[Hellman 2020]], [[Binns 2018]], and [[Hedden 2021]]. The closest neighboring pages are [[Algorithmic bias]], [[Predictive optimization]], [[Behavioral public policy]], and [[Behavioral law and economics]].

## Open questions

Which fairness criteria should matter most in high-stakes public decisions? Are some metrics only evidentially useful while others are morally necessary? And when criteria conflict, who should decide which trade-off an institution ought to accept?
