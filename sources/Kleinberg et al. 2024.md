---
title: Kleinberg et al. 2024
page_type: source
source_path: raw/papers/Kleinberg et al. 2024.pdf
source_type: paper
status: ingested
tags:
  - ai
  - behavioral-economics
  - behavioral-public-policy
  - prediction
  - source
updated_on: 2026-04-17
related_pages:
  - [[Inversion problem]]
  - [[Behavioral economics of AI]]
  - [[Behavioral economics of AI]]
  - [[Predictive optimization]]
  - [[Clinical versus actuarial judgment]]
  - [[Target variable problem]]
  - [[Behavioral public policy]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Kleinberg et al. 2024: The inversion problem
## Summary

[[Kleinberg et al. 2024]] argues that many algorithms trained on human behavior face a hidden but serious problem: they predict observable behavior while implicitly aiming at an underlying mental state such as preference, welfare, expertise, or reflective judgment. The paper calls this the [[Inversion problem]]. In the current vault, that makes it a strong bridge source between behavioral science and the AI / prediction thread.

The paper's central point is that better behavioral prediction is not always the same thing as better inference about what people want, believe, endorse, or would judge under better conditions. A recommender system may predict clicks while really hoping to identify preferences. A system trained on expert decisions may predict the decisions experts actually make while really hoping to identify their considered expertise. In the current vault, that matters because it adds a psychological depth problem to the existing concerns tracked under [[Predictive optimization]] and [[Target variable problem]].

## Key claims

The first claim is that many machine-learning applications involving people are not pure prediction tasks. They are inversion tasks in which behavior is used as evidence about a latent psychological state.

The second claim is that more behavioral data alone do not solve this problem. Better prediction of observed behavior can still leave the underlying mental state badly misidentified.

The third claim is that psychology is not optional in these settings. If behavior is only a proxy for preference, welfare, attention, self-control, or expertise, then algorithm design needs a theory of how those mental states generate behavior.

The fourth claim is that inversion problems are widespread. The paper treats recommendation systems, social media, and expert-automation tasks as recurring examples rather than special cases.

## Evidence and methods

The paper is conceptual and programmatic rather than an empirical case study of one deployment. Its method is to contrast what the authors call the psychology culture with the machine-learning culture and then show why behavior-prediction systems often inherit a hidden mismatch between the measured outcome and the mental state that institutions actually care about.

That makes the paper valuable in the current vault as an architectural source. It does not mainly add one more fairness metric or one more applied case. It clarifies why behavioral science may still be necessary even in highly predictive algorithmic environments.

## Why it matters for PPE

For PPE students, [[Kleinberg et al. 2024]] matters because it makes a subtle point unusually teachable: the success of an algorithm depends not only on predictive accuracy but on whether it is predicting the right thing. It matters for economics because it complicates revealed-preference-style reasoning in algorithmic settings. It matters for philosophy because it distinguishes observable action from the mental state institutions may actually wish to respect or promote. And it matters for politics and public policy because it warns that AI systems can become behaviorally sophisticated while still aiming at the wrong human target.

Pedagogically, the paper is especially useful because it gives the AI branch a language for connecting older behavioral ideas such as self-control, hot-cold gaps, and reflective versus impulsive choice to newer debates about recommender systems and expert automation.

## Links into the wiki

This source should mainly strengthen [[Inversion problem]], [[Behavioral economics of AI]], [[Behavioral economics of AI]], [[Predictive optimization]], [[Clinical versus actuarial judgment]], and [[Behavioral public policy]]. It also sits naturally beside [[Target variable problem]], but it is not the same point. Target-variable mistakes concern the wrong proxy outcome inside an optimization problem; inversion problems concern the deeper mismatch between observable behavior and the mental state an institution really hopes to infer.

I do think the paper justifies one durable concept page in the current vault: [[Inversion problem]]. The label is strong enough, general enough, and likely to recur across later AI-governance and behavioral-policy sources.

## Open questions

When should institutions infer mental state rather than rely on behavior directly? Which psychological constructs are stable enough to guide algorithm design without becoming analyst fictions? And can inversion problems be handled in a transparent way once systems are deployed at scale?

## Bibliographic reference

Kleinberg, J., Ludwig, J., Mullainathan, S., & Raghavan, M. (2024). The inversion problem: Why algorithms should infer mental state and not just predict behavior. *Perspectives on Psychological Science, 19*(5), 827-838. https://doi.org/10.1177/17456916231212138
