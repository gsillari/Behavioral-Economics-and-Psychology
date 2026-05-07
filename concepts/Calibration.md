---
title: Calibration
page_type: concept
status: active
tags:
  - behavioral-economics
  - methodology
  - risk
updated_on: 2026-04-26
source_count: 3
related_pages:
  - [[Rabin and Thaler 2001]]
  - [[Lichtenstein et al. 1982 - Calibration of Probabilities (in Kahneman et al. 1982, ch. 22)]]
  - [[Kleinberg et al. 2016]]
  - [[Statistical fairness criteria]]
  - [[Subjective probability]]
  - [[Risk attitudes]]
  - [[Expected utility theory]]
  - [[Von Neumann-Morgenstern utility theory]]
  - [[Loss aversion]]
  - [[Mental accounting]]
---

# Calibration

## Core idea

[[Calibration]] is the question of whether a judgment, score, or model parameter means what it is supposed to mean when checked against other cases, frequencies, or implications. The concept matters in the vault because it appears in two different but connected senses.

In judgment research, calibration is about whether stated probabilities match observed frequencies. If a person says "70 percent" many times, about 70 percent of those events should occur. In the current vault, the anchor is [[Lichtenstein et al. 1982 - Calibration of Probabilities (in Kahneman et al. 1982, ch. 22)]].

In economic modeling, calibration is about whether a parameter value or functional form that explains one set of choices also gives plausible implications elsewhere. In the current vault, [[Rabin and Thaler 2001]] is the key source: when expected-utility curvature is calibrated to ordinary small-stakes risk aversion, it implies absurd large-stakes risk aversion.

## Key distinctions

The first distinction is between probability calibration and model calibration. Probability calibration evaluates beliefs or forecasts against realized frequencies. Model calibration evaluates whether a model's parameters, once fixed by one domain of behavior, generate plausible predictions in another domain.

The second distinction is between calibration and coherence. A set of beliefs can be internally coherent while poorly calibrated to the world. Conversely, a prediction system can be statistically calibrated in one sense while still raising normative or practical questions. This is why [[Subjective probability]] and [[Statistical fairness criteria]] need calibration but cannot be reduced to it.

The third distinction is between calibration and fit. A model can fit a local pattern by choosing a parameter value, yet fail calibration if the same parameter has wild implications elsewhere. This is the point of the Rabin-Thaler critique of expected utility as an explanation of ordinary risk aversion.

## Main branches in the vault

### 1. Probabilistic judgment

The probability-calibration branch belongs near [[Subjective probability]], [[Overconfidence]], and expert judgment. [[Lichtenstein et al. 1982 - Calibration of Probabilities (in Kahneman et al. 1982, ch. 22)]] shows that calibration is a distinct dimension of judgment quality. It is not enough to be confident; confidence should track truth frequencies.

### 2. Risk-aversion calibration

The risk-aversion branch belongs near [[Risk attitudes]] and [[Expected utility theory]]. [[Rabin and Thaler 2001]] argues that standard expected utility cannot plausibly explain ordinary aversion to favorable small gambles through diminishing marginal utility of wealth. The issue is calibration across stakes: the same concavity that explains rejecting a small gamble implies rejecting enormous favorable gambles.

This does not show that expected utility cannot represent risk aversion at all. It shows that the usual wealth-curvature explanation is descriptively fragile when calibrated to ordinary choices. The behavioral replacement is not simply "more risk aversion"; it is [[Loss aversion]] plus [[Mental accounting]] or narrow bracketing.

### 3. Algorithmic fairness

The algorithmic-fairness branch uses calibration in a different but related way. In [[Statistical fairness criteria]], calibration means that a score should have the same empirical meaning across groups. [[Kleinberg et al. 2016]] and later fairness discussions show why that desideratum can conflict with error-rate parity when base rates differ.

## Why it matters here

Calibration matters because it forces the vault to ask whether an explanation travels. A local model that explains one choice pattern may become implausible once its implications are checked elsewhere. This is especially important for behavioral economics, where the same formal benchmark may function as a normative ideal, a descriptive model, and a measurement tool.

For PPE students, the concept is useful because it connects epistemology, economics, and policy. Calibrated beliefs matter for rational inference. Calibrated utility models matter for risk and welfare analysis. Calibrated scores matter for institutions that allocate burdens and benefits.

## Related pages

The main anchors are [[Lichtenstein et al. 1982 - Calibration of Probabilities (in Kahneman et al. 1982, ch. 22)]], [[Rabin and Thaler 2001]], and [[Kleinberg et al. 2016]]. The closest neighboring pages are [[Subjective probability]], [[Risk attitudes]], [[Expected utility theory]], [[Von Neumann-Morgenstern utility theory]], [[Loss aversion]], [[Mental accounting]], and [[Statistical fairness criteria]].

## Open questions

When should calibration be treated as a normative requirement, and when only as an empirical diagnostic? How should the vault distinguish poor calibration of beliefs from poor calibration of a model? And when a benchmark fails calibration, should the response be to repair the benchmark, restrict its domain, or replace it with a different descriptive theory?
