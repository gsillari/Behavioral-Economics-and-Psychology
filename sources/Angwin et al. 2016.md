---
title: Angwin et al. 2016
page_type: source
source_path: raw/web/Angwin et al. 2016.txt
source_type: article
status: ingested
tags:
  - ai
  - behavioral-public-policy
  - behavioral-economics
  - law
  - source
updated_on: 2026-04-15
related_pages:
  - [[Algorithmic bias]]
  - [[Kleinberg et al. 2016]]
  - [[Behavioral economics of AI]]
  - [[Clinical versus actuarial judgment]]
  - [[Behavioral law and economics]]
  - [[Behavioral public policy]]
  - [[Algorithmic Judgment and Debiasing]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Angwin et al. 2016: Machine Bias
## Summary

[[Angwin et al. 2016]] is the ProPublica investigation that made algorithmic risk scoring a major public controversy. Focusing on COMPAS scores used in Broward County, Florida, the article argues that a widely used proprietary risk-assessment tool was racially disparate in its errors: black defendants were more likely to be falsely flagged as high risk, while white defendants were more likely to be falsely labeled low risk.

In the current vault, the article matters less as the last word on fairness than as the agenda-setting source that forced the issue into public view. It made three things impossible to ignore at once: predictive tools can shape liberty decisions in criminal justice, proprietary scoring systems can be opaque to the public and to defendants, and "algorithmic objectivity" does not settle the problem of bias. That makes the piece foundational for the current AI-policy branch and especially important for the later literature on [[Algorithmic bias]].

## Key claims

The first claim is empirical and journalistic: COMPAS scores in the Broward County data showed substantial racial disparity in how errors were distributed across groups.

The second claim is institutional: risk scores were already being used in high-stakes criminal-justice settings, including sentencing and related release decisions, often without meaningful transparency or adversarial scrutiny.

The third claim is methodological: evaluating algorithms requires looking not only at overall predictive success, but also at who bears the errors and how those errors are structured.

The fourth claim is political and legal: a proprietary model can influence coercive state decisions while remaining largely shielded from public inspection. That raises due-process and accountability concerns that go beyond accuracy alone.

The fifth claim, especially important for the current vault, is that algorithmic tools do not eliminate older judgment problems. They relocate them into questions about data, objective functions, hidden design choices, and fairness criteria.

## Evidence and methods

The article is an investigative data-driven report rather than a peer-reviewed journal article. ProPublica obtained risk scores for more than 7,000 people arrested in Broward County in 2013 and 2014 and compared the scores with subsequent charges over a two-year horizon. The investigation also emphasized the opacity of the COMPAS system and the difficulty defendants faced in understanding or contesting the tool.

That means the article should not be treated as the entire fairness literature by itself. Its contribution is agenda-setting and publicly catalytic. It supplied the case that later academic work would formalize, criticize, refine, and reinterpret.

## Why it matters for PPE

For PPE students, [[Angwin et al. 2016]] matters because it turns abstract debates about prediction and bias into a concrete institutional problem. It matters for economics because it shows that predictive tools cannot be evaluated only by average accuracy when public decisions involve heterogeneous error costs and contested objectives. It matters for philosophy because it raises questions about fairness, opacity, explanation, and the legitimacy of delegating coercive decisions to proprietary systems. It matters for politics and law because it places all of those questions inside criminal justice, where state power is direct and liberty is at stake.

Pedagogically, the article is especially useful because it gives later academic debates a clear starting point. Many subsequent papers on fairness tradeoffs, recidivism prediction, and machine bias are best understood as responses to the controversy this piece crystallized, with [[Kleinberg et al. 2016]] providing one of the earliest and most influential formalizations of why fairness disputes persist.

## Links into the wiki

This source should primarily strengthen [[Algorithmic bias]], [[Behavioral economics of AI]], [[Clinical versus actuarial judgment]], [[Behavioral law and economics]], and [[Behavioral public policy]]. It also belongs under [[Algorithmic Judgment and Debiasing]] because it shows why the algorithmic-judgment branch cannot be treated as a simple success story about formal prediction replacing human discretion.

I do think this source justifies a standalone concept page in the current vault: [[Algorithmic bias]]. The article is not merely an instance of a broader issue already well housed elsewhere. It is the public touchstone around which a whole later branch of debate about fairness, opacity, and institutional use of predictive models coheres.

## Open questions

When should disparities in algorithmic error rates count as evidence of unfairness rather than as a byproduct of deeper social inequalities in the data? How transparent must predictive systems be before their use in high-stakes public decisions is legitimate? And how should later fairness papers be organized in relation to this original public controversy: as confirmation, correction, or reframing?

## Bibliographic reference

Angwin, J., Larson, J., Mattu, S., & Kirchner, L. (2016, May 23). Machine bias. *ProPublica*. https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
