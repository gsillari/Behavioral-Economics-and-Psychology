---
title: Kleinberg et al. 2016
page_type: source
source_path: raw/papers/Kleinberg et al. 2016.pdf
source_type: paper
status: ingested
tags:
  - ai
  - behavioral-public-policy
  - behavioral-economics
  - law
  - source
updated_on: 2026-05-26
related_pages:
  - [[Algorithmic bias]]
  - [[Angwin et al. 2016]]
  - [[Corbett-Davies et al. 2017]]
  - [[Kleinberg et al. 2018]]
  - [[Behavioral economics of AI]]
  - [[Behavioral economics of AI]]
  - [[Clinical versus actuarial judgment]]
  - [[Behavioral law and economics]]
  - [[Behavioral public policy]]
  - [[Algorithmic Judgment and Debiasing]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Kleinberg et al. 2016: Inherent trade-offs in the fair determination of risk scores
## Summary

[[Kleinberg et al. 2016]] is one of the foundational formal papers in the fairness literature around algorithmic risk scoring. Its central claim is that several fairness conditions that are each individually appealing cannot, except in special cases, all be satisfied at once. In the current vault, this matters as the clearest formal counterpart to [[Angwin et al. 2016]]. ProPublica made the public controversy vivid; this paper explains why the controversy does not disappear once analysts become more mathematically precise.

The paper is especially important because it shows that the fairness problem is not simply a matter of fixing one defective classifier. When base rates differ across groups, properties such as calibration and balanced error rates can come apart. That result makes the later literature on machine bias more intelligible: some disputes are empirical and institutional, but some are also structural. [[Corbett-Davies et al. 2017]] is a natural successor in the vault because it asks what institutions should do once those conflicts are acknowledged: treat fairness criteria as constraints relative to a policy objective.

## Key claims

The first claim is that three widely discussed fairness conditions for risk scores cannot generally be satisfied simultaneously except in constrained special cases.

The second claim is that this incompatibility persists even if one weakens the demands and looks for approximate rather than perfect simultaneous satisfaction.

The third claim is that debates over algorithmic fairness often involve genuine trade-offs rather than mere confusion or bad faith. Different parties may be emphasizing different fairness properties that cannot all be achieved together.

The fourth claim is that the criminal-justice risk-score debate, including the controversy around COMPAS, should be understood partly through these incompatibilities rather than only through allegations of sloppiness or bias in a colloquial sense.

The fifth claim is methodological: algorithmic evaluation needs to distinguish prediction, calibration, classification thresholds, and group-specific error profiles. Without that, public debate about fairness becomes conceptually unstable.

A further lesson, developed more explicitly by [[Corbett-Davies et al. 2017]], is that the choice among fairness criteria is also a regulatory and policy choice. If criteria conflict, institutions must say what objective the system is meant to serve and which fairness constraint should bind that objective.

## Evidence and methods

The paper is theoretical and formal rather than journalistic or policy-simulation based. It identifies three fairness conditions, proves incompatibility results, and uses the criminal-justice risk-score debate as a motivating case. Its value in the current vault is therefore not as a case study of one institution, but as a clarification of what kinds of fairness conflicts are structurally possible in risk scoring.

That means the paper should not be treated as refuting the relevance of [[Angwin et al. 2016]]. Its real contribution is to show why the ProPublica controversy could persist even when later analysts shifted to more formal language about calibration and error rates.

## Why it matters for PPE

For PPE students, [[Kleinberg et al. 2016]] matters because it turns a public scandal into a conceptual problem. It matters for economics because it is about constrained optimization under competing objectives. It matters for philosophy because it shows that "fairness" is not a single criterion and that apparently reasonable moral demands can conflict at the level of formal decision rules. It matters for politics and law because institutions using risk scores cannot avoid choosing which fairness properties to prioritize and must justify those choices publicly.

Pedagogically, the paper is especially useful because it helps students see why later machine-bias debates are not just empirical disputes over who analyzed one dataset better. They are also disputes over incompatible normative and statistical desiderata.

## Links into the wiki

This source should primarily strengthen [[Algorithmic bias]], [[Behavioral economics of AI]], [[Behavioral economics of AI]], [[Behavioral law and economics]], and [[Behavioral public policy]]. It also belongs under [[Algorithmic Judgment and Debiasing]] because it formalizes one of the central reasons why algorithmic judgment cannot be evaluated by accuracy alone.

I do not think it warrants a new standalone concept page right now. The paper gives structure to the fairness branch, but that structure is still best housed under [[Algorithmic bias]] rather than split into a thin new page on trade-off theorems or fairness impossibility.

## Open questions

Which fairness criteria should public institutions prioritize when they cannot all be met at once? How much of the apparent conflict around machine bias comes from structural incompatibility rather than poor system design? When should a fairness criterion be treated as a constraint on a public objective rather than as the objective itself? And when institutions choose one fairness profile over another, what sort of public justification do they owe?

## Bibliographic reference

Kleinberg, J., Mullainathan, S., & Raghavan, M. (2016). Inherent trade-offs in the fair determination of risk scores. *arXiv*. https://arxiv.org/abs/1609.05807
