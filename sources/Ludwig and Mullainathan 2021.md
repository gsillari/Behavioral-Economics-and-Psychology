---
title: Ludwig and Mullainathan 2021
page_type: source
source_path: raw/papers/Ludwig and Mullainathan 2021.pdf
source_type: paper
status: ingested
tags:
  - ai
  - algorithmic-bias
  - behavioral-public-policy
  - criminal-justice
  - source
updated_on: 2026-05-07
related_pages:
  - [[Behavioral economics of AI]]
  - [[Algorithmic bias]]
  - [[Clinical versus actuarial judgment]]
  - [[Behavioral public policy]]
  - [[Kleinberg et al. 2018]]
  - [[Kleinberg et al. 2016]]
  - [[Angwin et al. 2016]]
  - [[Statistical fairness criteria]]
  - [[Algorithmic Judgment and Debiasing]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Ludwig and Mullainathan 2021: Fragile Algorithms and Fallible Decision-Makers

## Summary

[[Ludwig and Mullainathan 2021]] is a didactic review of algorithms in criminal justice. Its central claim is nicely balanced: algorithms are not doomed by their nature, but they are fragile because small-seeming human design choices about construction, evaluation, procurement, and deployment can make them ineffective, unfair, opaque, or harmful.

The paper is especially useful for the vault because it sits between [[Kleinberg et al. 2018]] and [[Ludwig et al. 2024]]. [[Kleinberg et al. 2018]] gives the technical bail-decision case; [[Ludwig and Mullainathan 2021]] generalizes the lessons into a framework for why algorithmic tools disappoint in practice; [[Ludwig et al. 2024]] then turns the same branch into a public-finance argument about ranking problems and high social returns.

## Key claims

The first claim is that the criminal-justice baseline is already deeply flawed. Human decision-making is inconsistent, error-prone, and discriminatory, so the right comparison is not algorithm versus ideal justice but algorithmic systems versus fallible institutional judgment.

The second claim is that supervised-learning algorithms can in principle reduce error, inconsistency, and bias because they can combine signals consistently and can be audited or redesigned more directly than human psychology.

The third claim is that many real-world tools fail because they are badly built or badly deployed. The problem is not merely "machine learning" in the abstract; it is human agency inside the construction, procurement, regulation, and use of the tool.

The fourth claim is that three technical-institutional problems organize many failures: [[Kleinberg et al. 2018]]'s selective-labels problem, omitted-payoff bias, and the override problem. Selective labels arise when past human decisions determine which outcomes are observed. Omitted-payoff bias arises when the algorithm predicts one measurable outcome while the institution actually cares about a richer objective. The override problem arises because algorithms usually advise humans rather than replace them, so designers must understand when human private information is useful and when it is noise.

The fifth claim is that [[Algorithmic bias]] should not be treated as an inevitable property of algorithms. Badly designed tools can reproduce or worsen racial disparity, but well-designed tools can incorporate fairness objectives, test calibration, adjust thresholds, and sometimes reduce disparity relative to human decision-making.

## Evidence and methods

The paper is synthetic rather than a single new empirical study. It reviews evidence on inconsistency, error, and discrimination in pretrial, sentencing, and parole decisions; surveys algorithmic applications in criminal justice; and uses the New York City pretrial-release tool as a concrete example of a better-designed system.

Its most useful teaching device is the contrast between fallible decision-makers and fragile algorithms. Humans create the baseline decisions, generate the data, choose the labels, specify the objective, procure the tool, and decide whether to follow or override the recommendation. That makes algorithmic governance a behavioral-public-policy problem rather than a purely technical problem.

## Why it matters for PPE

For PPE students, [[Ludwig and Mullainathan 2021]] matters because it shows that algorithmic governance is not a purely technical question. It matters for economics because the paper treats prediction tools as institutional mechanisms whose value depends on labels, objectives, evaluation, and incentives. It matters for philosophy because it asks when fairness, transparency, and due process should constrain accuracy-oriented tools. It matters for politics because criminal-justice algorithms operate inside coercive public institutions where procurement, regulation, and human override shape the final outcome.

## Didactic value for the vault

For [[Behavioral economics of AI]], the paper gives a clean way to avoid both naive algorithmic optimism and blanket anti-algorithmic pessimism. It says that algorithms are powerful only when embedded in a good institutional design process.

For [[Algorithmic bias]], the paper is useful because it treats bias as partly a design and governance problem. The same architecture that can transmit biased data can, under the right objective and audit structure, be used to detect and reduce bias.

For [[Clinical versus actuarial judgment]], the paper adds a modern qualification to the Meehl line: formal prediction may outperform unaided judgment, but real deployments require attention to labels, payoffs, human override, procurement, and legitimacy.

For [[Behavioral public policy]], the paper shows why algorithmic decision tools are not just neutral technical upgrades. They are policy instruments whose effects depend on institutional incentives, regulation, evaluation standards, and the behavioral response of human users.

## Links into the wiki

This source should mainly strengthen [[Behavioral economics of AI]], [[Algorithmic bias]], [[Clinical versus actuarial judgment]], [[Behavioral public policy]], and the topic [[AI, Algorithms, and New Frontiers]]. It should be read alongside [[Kleinberg et al. 2018]] for the selective-labels and bail-decision machinery, [[Angwin et al. 2016]] for the public controversy over machine bias, [[Kleinberg et al. 2016]] for the fairness-criteria conflict, and [[Ludwig et al. 2024]] for the later policy-cost-effectiveness argument.

I do not think it needs a separate concept page. "Fragile algorithms" is a useful phrase, but in this vault it does more work as a framing device inside the algorithmic judgment and public-policy branches than as a standalone concept.

## Open questions

How should public agencies be required to evaluate algorithms before deployment? When should humans override algorithmic recommendations, and how can systems distinguish valuable private information from noisy discretion? Can fairness objectives be incorporated without violating legal constraints originally designed for human discrimination? And when does the promise of debiasing become outweighed by due-process, transparency, or legitimacy concerns?

## Bibliographic reference

Ludwig, J., & Mullainathan, S. (2021). Fragile algorithms and fallible decision-makers: Lessons from the justice system. *Journal of Economic Perspectives, 35*(4), 71-96. https://doi.org/10.1257/jep.35.4.71
