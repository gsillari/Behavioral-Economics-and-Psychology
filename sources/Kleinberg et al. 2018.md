---
title: Kleinberg et al. 2018
page_type: source
source_path: raw/papers/Kleinberg et al. 2018.pdf
source_type: paper
status: ingested
tags:
  - ai
  - behavioral-economics
  - behavioral-public-policy
  - judgment
  - methodology
  - source
updated_on: 2026-05-07
related_pages:
  - [[Clinical versus actuarial judgment]]
  - [[Dawes et al. 1989]]
  - [[Dawes 1979]]
  - [[Behavioral economics of AI]]
  - [[Behavioral law and economics]]
  - [[Behavioral public policy]]
  - [[Algorithmic Judgment and Debiasing]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Kleinberg et al. 2018: Human decisions and machine predictions
## Summary

[[Kleinberg et al. 2018]] asks whether machine learning can improve high-stakes human judgment, using bail decisions in New York City as the test case. The paper argues that predictive models can substantially outperform judges on the narrow task of forecasting pretrial misconduct, but it also insists that this comparison is not straightforward. The core difficulty is that policy decisions are not pure prediction problems: the data are selectively observed because judges decide whom to release, and judges may care about multiple objectives rather than the single outcome a model predicts.

In the current vault, that makes the paper important as a modern continuation of the Meehl-to-[[Dawes 1979]]-to-[[Dawes et al. 1989]] line, but now in a setting shaped by machine learning, fairness concerns, and institutional design. It is best treated as a bridge source between [[Clinical versus actuarial judgment]], [[Behavioral law and economics]], [[Behavioral public policy]], and the AI branch.

## Key claims

The first claim is that machine learning can generate better predictions than human judges in bail decisions when the relevant task is forecasting failure to appear or rearrest risk.

The second claim is that evaluating such tools requires solving the selective-labels problem. The "label" is the outcome one wants to predict, but in bail we only observe it for defendants judges release; for jailed defendants, we do not observe what they would have done if released. Naive comparisons are therefore biased because the judge's own decision determines which outcomes enter the dataset.

The third claim is that prediction and decision should not be collapsed into each other. A model may predict one outcome well while a judge is implicitly optimizing over a broader bundle of concerns, such as violent crime, detention costs, or racial disparities.

The fourth claim is that, even after these complications are taken seriously, predictive algorithms can produce large gains: lower crime at the same jailing rate, or lower jailing at the same crime rate, with some simulations also reducing racial disparities.

The fifth claim is that machine learning is most useful when placed inside an explicit economic and institutional framework. Prediction quality matters, but so do payoff definitions, counterfactual evaluation, and governance of the resulting tool.

## Evidence and methods

The paper is an empirical study of New York City bail decisions using very large administrative data and machine-learning prediction models. Its methodological contribution is not just the model comparison itself, but the treatment of the selective-labels problem and the effort to separate predictive performance from policy objectives. The authors use quasi-random assignment of cases to judges with different leniency levels: lenient judges reveal outcomes for some defendants stricter judges would have jailed. This lets the paper estimate or bound how algorithmic release rules would compare with existing judicial practice.

This matters in the current vault because the paper does more than say "algorithms beat people." It shows that the modern version of the actuarial-clinical debate runs through counterfactual identification, fairness constraints, and institutional objective functions.

## Why it matters for PPE

For PPE students, [[Kleinberg et al. 2018]] matters because it turns an old methodological dispute into a live political and legal question. It matters for economics because it is about prediction policy problems, tradeoffs among multiple objectives, and the institutional use of machine learning. It matters for philosophy because it raises questions about what should count as a better decision rule when accuracy, liberty, fairness, and legitimacy do not line up automatically. It matters for politics because pretrial detention is a coercive state practice, so any claim that an algorithm improves judgment immediately becomes a question about accountability, public authority, and due process.

Pedagogically, the paper is especially useful because it shows exactly how the older [[Clinical versus actuarial judgment]] literature travels into contemporary AI governance without becoming a simple pro-algorithm argument.

## Links into the wiki

This source should primarily strengthen [[Clinical versus actuarial judgment]], [[Behavioral economics of AI]], [[Behavioral law and economics]], and [[Behavioral public policy]]. It also belongs naturally under [[Algorithmic Judgment and Debiasing]] because it makes that topic concrete in one of the highest-stakes domains in the current vault.

I do not think it warrants a separate concept page at this stage. Its main contribution is to modernize and deepen an existing branch rather than to coin a durable new conceptual label.

## Open questions

When should predictive tools in law be treated as advisory rather than authoritative? How should institutions specify the outcome they want to optimize when prediction accuracy, liberty, and fairness can come apart? And how far should the lessons of bail prediction generalize to other domains of public decision-making?

## Bibliographic reference

Kleinberg, J., Lakkaraju, H., Leskovec, J., Ludwig, J., & Mullainathan, S. (2018). Human decisions and machine predictions. *The Quarterly Journal of Economics, 133*(1), 237-293. https://doi.org/10.1093/qje/qjx032
