---
title: Corbett-Davies et al. 2017
page_type: source
source_path: raw/papers/Corbett-Davies et al. 2017.pdf
source_type: paper
status: ingested
tags:
  - ai
  - algorithmic-bias
  - behavioral-public-policy
  - law
  - source
updated_on: 2026-05-26
related_pages:
  - [[Algorithmic bias]]
  - [[Statistical fairness criteria]]
  - [[Kleinberg et al. 2016]]
  - [[Kleinberg et al. 2018]]
  - [[Angwin et al. 2016]]
  - [[Hellman 2020]]
  - [[Hedden 2021]]
  - [[Behavioral economics of AI]]
  - [[Behavioral law and economics]]
  - [[Behavioral public policy]]
  - [[Algorithmic Judgment and Debiasing]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Corbett-Davies et al. 2017: Algorithmic decision making and the cost of fairness

## Summary

[[Corbett-Davies et al. 2017]] is a central paper for understanding the policy side of algorithmic-fairness impossibility results. The paper reformulates algorithmic fairness as constrained optimization: policymakers choose an objective, such as maximizing public safety net of detention costs, and then decide whether to impose formal fairness constraints such as statistical parity, conditional statistical parity, or predictive equality.

In the current vault, the paper matters because it sharpens the meaning of "bias" after [[Kleinberg et al. 2016]]. If fairness criteria can conflict, then the question is not simply which metric is mathematically valid. The deeper question is which regulatory or policy goal the decision system is supposed to serve. On this view, a system can be called biased relative to one fairness constraint or policy objective, while looking appropriate relative to another. That does not make bias arbitrary; it makes the normative benchmark explicit.

## Key claims

The first claim is that algorithmic fairness can be modeled as constrained optimization. A decision-maker first specifies an objective, then imposes constraints meant to reduce racial disparities or satisfy a fairness definition.

The second claim is that several familiar fairness constraints lead to race-specific decision thresholds. In the pretrial-release setting, satisfying statistical parity or predictive equality may require detaining defendants at different risk thresholds depending on group membership.

The third claim is that the unconstrained utility-maximizing rule applies a single uniform risk threshold. The authors treat this as satisfying one important conception of equality: holding individuals to the same standard regardless of race.

The fourth claim is that the tradeoff is not only formal. Using Broward County data, the paper argues that fairness constraints can impose large public-safety costs, while optimizing public safety alone can produce substantial racial disparities.

The fifth claim is that the analysis does not settle policy by itself. The paper's utility function reflects proximate costs and benefits, such as violent crimes prevented and detention costs. It does not automatically capture long-run systemic effects, historical injustice, group-level institutional goals, or all individualized costs of detention.

## Evidence and methods

The paper is formal and empirical. It first defines decision rules, group membership, welfare-relevant outcomes, and several fairness criteria. It then derives optimal decision rules under different constraints and applies the analysis to Broward County pretrial-release data, the same broad setting made public by [[Angwin et al. 2016]].

Its most important methodological move is to distinguish fairness of risk scores from fairness of decisions. Calibration concerns whether a score has the same empirical meaning across groups. Decision fairness concerns what action is taken given the score, the policy objective, and any constraints. That distinction helps explain why debates about COMPAS can become unstable when score evaluation, classification thresholds, public safety, detention costs, and racial disparity are collapsed into one word: bias.

## Why it matters for PPE

For PPE students, [[Corbett-Davies et al. 2017]] matters because it turns algorithmic fairness from a purely technical metrics debate into a policy-design problem. It matters for economics because it treats decision rules as optimization under constraints and makes tradeoffs between detention costs, public safety, and disparity visible. It matters for philosophy because it shows that fairness criteria encode competing conceptions of equality: equal thresholds, equal outcomes, equal error rates, and equalized burdens are not the same moral demand. It matters for politics and law because it asks who should choose the objective and which fairness constraints public agencies should be allowed or required to impose.

The paper is especially useful for the current course architecture because it gives one way to understand the "correct" definition of algorithmic bias: not as a free-standing statistical fact, but as a judgment relative to regulatory or policy goals. A risk tool may be biased if it violates the fairness constraint that the institution has reason to adopt; but choosing that constraint is itself a normative and political act.

## Links into the wiki

This source should strengthen [[Algorithmic bias]] by adding the policy-goal-relative interpretation of bias. It should strengthen [[Statistical fairness criteria]] by showing how fairness metrics function as constraints on an objective rather than as self-interpreting measures. It should sit between [[Kleinberg et al. 2016]], which establishes incompatibility among fairness desiderata, and [[Hellman 2020]] and [[Hedden 2021]], which ask which criteria are morally salient.

It also belongs near [[Kleinberg et al. 2018]] and [[Ludwig and Mullainathan 2021]] because all three papers insist that algorithmic judgment in criminal justice must be evaluated as a decision system with objectives, costs, labels, and institutional constraints, not merely as a prediction machine.

## Open questions

When should equal thresholds matter more than equal error burdens? Can a public agency legitimately use race-specific thresholds to satisfy a fairness constraint, or does that violate an independent legal or political norm of equal treatment? How should long-run social effects, historical injustice, and institutional legitimacy enter the utility function rather than appearing only as caveats? And who should choose the regulatory goal relative to which an algorithm is judged biased or fair?

## Bibliographic reference

Corbett-Davies, S., Pierson, E., Feller, A., Goel, S., & Huq, A. (2017). Algorithmic decision making and the cost of fairness. In *Proceedings of the 23rd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining* (pp. 797-806). Association for Computing Machinery. https://doi.org/10.1145/3097983.3098095
