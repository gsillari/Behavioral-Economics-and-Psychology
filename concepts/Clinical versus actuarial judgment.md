---
title: Clinical versus actuarial judgment
page_type: concept
status: active
tags:
  - behavioral-economics
  - judgment
  - methodology
updated_on: 2026-04-17
source_count: 7
related_pages:
  - [[Dawes et al. 1989]]
  - [[Dawes 1979]]
  - [[Ludwig et al. 2024]]
  - [[Kleinberg et al. 2016]]
  - [[Kleinberg et al. 2024]]
  - [[Kleinberg et al. 2018]]
  - [[Wang et al. 2024]]
  - [[Angwin et al. 2016]]
  - [[Algorithmic bias]]
  - [[Predictive optimization]]
  - [[Bounded rationality]]
  - [[Behavioral economics of AI]]
  - [[Behavioral law and economics]]
  - [[Behavioral Economics]]
---

# Clinical versus actuarial judgment

## Core idea

[[Clinical versus actuarial judgment]] is the comparison between discretionary expert judgment and formal predictive procedures. In the current vault, the anchor source is [[Dawes et al. 1989]], which argues that actuarial methods generally outperform clinical judgment in predictive tasks. The central lesson is that consistency in combining cues often beats intuitive, case-by-case interpretation.

## Key distinctions

Clinical versus actuarial judgment is the larger institutional and methodological question of whether explicit procedures should outperform or constrain professional discretion. One important recurring lesson inside that broader debate is the success of simple cue-combination rules, including improper linear models in Dawes's sense. It also differs from a blanket defense of algorithms. The argument is comparative: the relevant benchmark is often not a perfect model, but unaided human judgment.

## Evidence and debate

[[Dawes et al. 1989]] synthesizes the literature comparing clinical and actuarial methods and concludes that actuarial procedures are usually superior. In the current vault, [[Dawes 1979]] works as an important precursor because it already shows why simple formal cue-combination rules, including improper linear models, can be powerful. [[Kleinberg et al. 2016]] adds an important intermediate step between the older actuarial literature and the later institutional AI papers: even if formal prediction is powerful, fairness evaluation of risk scores may involve incompatible desiderata rather than one obvious benchmark. [[Kleinberg et al. 2018]] then carries the branch further into the machine-learning era by comparing judges with predictive models in bail decisions. That later paper is useful because it shows both the continuity and the complication: formal prediction can outperform human judgment, but the modern debate also has to confront selective labels, fairness constraints, and disagreement about what outcome institutions should optimize. [[Kleinberg et al. 2024]] adds a different complication through [[Inversion problem]]: even when the predictive task is well specified, institutions may still care about a latent mental state rather than the observed behavior alone. [[Angwin et al. 2016]] adds a complementary caution from the public controversy side. It does not overturn the actuarial-clinical lesson, but it shows why contemporary algorithm debates cannot stop at the claim that formal prediction beats intuition. Once proprietary tools are used in coercive state settings, questions about disparate error rates, opacity, and contestability become central. [[Wang et al. 2024]] adds a more sweeping critique by arguing that [[Predictive optimization]] can fail even when developers frame it as neutral accuracy improvement. [[Ludwig et al. 2024]] adds a shorter, more didactic policy argument on top of that. The concept is therefore important both for critiques of overconfident expertise and for later disputes about algorithms, discretion, institutional design, and [[Algorithmic bias]].

## Practical or policy relevance

This concept matters in diagnosis, hiring, admissions, parole, sentencing, lending, and many other institutional settings where human experts make repeated predictive judgments. If actuarial methods often perform better, then questions of due process, fairness, transparency, and accountability become central. The issue is not only whether formal tools are more accurate, but also when institutions should trust them, how much discretion to preserve, and how to govern the interaction between rules and expert override.

## Related pages

The anchor source is [[Dawes et al. 1989]]. The closest neighboring pages are [[Bounded rationality]], [[Behavioral law and economics]], [[Behavioral economics of AI]], [[Inversion problem]], and [[Algorithmic bias]]. The broader topical home is [[Behavioral Economics]], with [[Dawes 1979]] as the key earlier source and [[Kleinberg et al. 2016]], [[Kleinberg et al. 2018]], [[Kleinberg et al. 2024]], [[Angwin et al. 2016]], and [[Ludwig et al. 2024]] as the main modern extensions in the vault.

## Open questions

When should actuarial tools be treated as advisory and when as authoritative? How should institutions handle cases where legitimacy or fairness concerns pull against pure predictive accuracy? Does the superiority of actuarial judgment generalize equally well across all kinds of decisions, or mainly structured prediction tasks?
