---
title: Dawes and Corrigan 1974
page_type: source
source_path: raw/papers/Dawes and Corrigan 1974.pdf
source_type: paper
status: ingested
tags:
  - behavioral-economics
  - judgment
  - methodology
  - source
updated_on: 2026-05-24
related_pages:
  - [[Robyn M. Dawes]]
  - [[Clinical versus actuarial judgment]]
  - [[Dawes 1979]]
  - [[Dawes et al. 1989]]
  - [[Meehl 1954]]
  - [[Bounded rationality]]
  - [[Behavioral law and economics]]
  - [[Algorithmic Judgment and Debiasing]]
  - [[Prediction and Models of Judgment]]
  - [[Behavioral Economics]]
---

# Dawes and Corrigan 1974: Linear models in decision making

## Summary

[[Dawes and Corrigan 1974]] is the deeper methodological source behind the later [[Dawes 1979]] argument for improper linear models. The paper asks why simple linear models so often work in judgment tasks where decisions are made from multiple codable inputs. Its answer is structural: many such tasks have cues that are conditionally monotone with the criterion, noisy measurement, and relatively low practical sensitivity to exact optimal weights.

In the current vault, the paper matters because it turns [[Clinical versus actuarial judgment]] from a simple contest between experts and formulas into a theory of task structure. The lesson is not that any formal model is good. It is that, in many predictive environments, consistent cue combination can beat intuitive judgment even when the weights are random or equal, provided the variables have the right direction and the task is sufficiently regular.

## Key claims

The central claim is that linear models succeed because many decision environments make approximate linear combination a good enough strategy. If each input variable can be scaled so that higher values normally point in the same direction for the criterion, then a linear rule can capture much of the useful information. Measurement error strengthens the case because it weakens the value of fine-grained nonlinear adjustment and makes exact weighting less important.

That claim reframes the clinical-statistical controversy. [[Meehl 1954]] had shown that actuarial prediction often beats informal clinical judgment. Dawes and Corrigan explain why the statistical side can be so robust: the hard part is often choosing relevant variables and signs, not estimating perfect weights. This is why random linear models and unit-weighted models can perform surprisingly well.

The paper also clarifies two neighboring ideas. A paramorphic model represents a judge's outputs without claiming to reproduce the judge's inner psychological process. Bootstrapping occurs when such a model of the judge predicts the criterion better than the judge does, because it preserves the judge's stable cue policy while stripping away inconsistency. Dawes and Corrigan then push further: if random or unit weights also do well, the success of bootstrapping should not be overread as evidence that the model has captured special expert insight.

## Evidence and methods

The paper is a methodological review and analysis rather than a single experiment. It organizes the evidence around four examples: predicting later psychiatric diagnosis from MMPI profiles, predicting graduate grade point average from admissions variables and ratings, predicting later faculty evaluations of graduate students from admissions information, and predicting assigned values of experimental ellipses from visible dimensions.

Across these examples, Dawes and Corrigan compare intuitive judgment, optimal linear models, paramorphic models of judges, random linear models, and unit-weighted models. The important result is not only that regression can outperform people. It is that even non-optimized linear rules can outperform human judges when the predictors are directionally valid and the task has the right structure. The paper then gives the mathematical and measurement-theoretic reason: monotone relationships, error in criteria, error in predictors, and flatness near the optimum jointly make precise weights less valuable than psychologists and decision makers often assume.

## Why it matters for PPE

For PPE students, [[Dawes and Corrigan 1974]] matters because it gives a clear institutional lesson about expertise. It matters for economics because many allocation, selection, and forecasting decisions depend on combining imperfect signals. It matters for philosophy because it complicates what counts as rational judgment: a simple rule can be epistemically superior to flexible expert interpretation when the task rewards consistency. It matters for politics and law because admissions, diagnosis, parole, hiring, lending, and public administration all face the question of when discretionary judgment should be constrained by explicit procedures.

The paper also helps students avoid a crude pro-algorithm reading. Dawes and Corrigan are not saying that formal models are automatically legitimate or fair. They are explaining why simple predictive procedures can be powerful in structured environments. Later algorithmic-governance debates add problems of labels, objectives, fairness, opacity, and contestability, but they inherit the older question this paper helps answer: why might a simple rule outperform a knowledgeable person?

## Links into the wiki

The main concept page is [[Clinical versus actuarial judgment]]. This source should sit between [[Meehl 1954]] and [[Dawes 1979]]: Meehl poses the clinical-statistical comparison, Dawes and Corrigan explain the robustness of linear cue-combination, and Dawes later gives the argument its most memorable formulation through improper linear models. [[Dawes et al. 1989]] then generalizes the lesson into a broader review of clinical versus actuarial judgment.

The paper also strengthens [[Bounded rationality]] because it shows one concrete way finite human judgment fails: people often use relevant cues inconsistently. It strengthens [[Behavioral law and economics]] because it gives legal and administrative institutions a reason to compare expert discretion with explicit procedures. It also belongs near [[Algorithmic Judgment and Debiasing]] because contemporary algorithmic decision support inherits the old actuarial-clinical comparison while adding new governance problems.

## Open questions

How far does the robustness of linear models depend on well-structured prediction tasks rather than judgment tasks in general? When should institutions prefer unit-weighted transparent rules over optimized but less interpretable models? And how should the older linear-model lesson be carried into modern algorithmic settings without ignoring fairness, proxy targets, and institutional legitimacy?

## Bibliographic reference

Dawes, R. M., & Corrigan, B. (1974). Linear models in decision making. *Psychological Bulletin, 81*(2), 95-106. https://doi.org/10.1037/h0037613
