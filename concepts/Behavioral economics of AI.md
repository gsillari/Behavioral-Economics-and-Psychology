---
title: Behavioral economics of AI
page_type: concept
status: active
tags:
  - ai
  - behavioral-economics
updated_on: 2026-04-18
source_count: 17
related_pages:
  - [[Bar-Gill et al. 2023]]
  - [[Angwin et al. 2016]]
  - [[Chouldechova and Roth 2020]]
  - [[Kleinberg et al. 2016]]
  - [[Hellman 2020]]
  - [[Binns 2018]]
  - [[Hedden 2021]]
  - [[Obermeyer et al. 2019]]
  - [[Camerer 2019]]
  - [[Bini et al. 2026]]
  - [[Ludwig et al. 2024]]
  - [[Sunstein 2025]]
  - [[Ludwig et al. 2025]]
  - [[Kleinberg et al. 2023]]
  - [[Kleinberg et al. 2024]]
  - [[Wang et al. 2024]]
  - [[Kleinberg et al. 2018]]
  - [[Algorithmic bias]]
  - [[Statistical fairness criteria]]
  - [[Target variable problem]]
  - [[Inversion problem]]
  - [[Predictive optimization]]
  - [[Algorithmic harm]]
  - [[Behavioral economics 2.0]]
  - [[Clinical versus actuarial judgment]]
  - [[Behavioral public policy]]
  - [[Heuristics and Biases]]
  - [[Expected utility theory]]
  - [[Behavioral Economics]]
---

# Behavioral economics of AI

NB: This is a stub.

## Core idea

[[Behavioral economics of AI]] studies the interaction between behavioral economics and AI. In the current vault, that now has seventeen layers. [[Camerer 2019]] treats AI and machine learning as tools, analogies, and institutional forces that can reshape behavioral research and human decision environments. [[Bini et al. 2026]] then extends the branch by studying LLMs directly as decision-making agents that may exhibit stable patterns analogous to human behavioral biases. [[Angwin et al. 2016]] adds an agenda-setting public layer by showing that algorithmic systems can become objects of fairness controversy and legal scrutiny, not only tools of better prediction. [[Kleinberg et al. 2016]] then adds a formal layer by showing that some fairness conditions for risk scores are structurally incompatible. [[Chouldechova and Roth 2020]] adds a survey layer by showing that the fairness branch is broader than static metric conflict and now includes biased data, dynamic feedback, exploration, and fair representation learning. [[Hellman 2020]], [[Binns 2018]], and [[Hedden 2021]] deepen that branch by interpreting the fairness metrics philosophically and normatively rather than treating them as interchangeable statistics. [[Obermeyer et al. 2019]] adds a design layer by showing how the wrong proxy target can generate severe bias even in a high-performing system. [[Kleinberg et al. 2023]] adds an engagement-optimization layer by showing, in a full formal model, that platforms can increase user engagement while reducing user welfare when preferences are inconsistent. [[Kleinberg et al. 2024]] then generalizes that problem into a broader psychological-alignment layer through [[Inversion problem]] by arguing that many algorithms predict behavior while really hoping to recover mental states such as preference, welfare, expertise, or reflective judgment. [[Bar-Gill et al. 2023]] adds a market-governance layer by showing that algorithms can also exploit information deficits and behavioral biases in consumer markets, now tracked under [[Algorithmic harm]]. [[Ludwig et al. 2024]] adds a policy-analytic layer by arguing that algorithms may be unusually powerful public tools because they improve ranking decisions at scale and low cost. [[Sunstein 2025]] adds a choice-architecture layer by treating AI as a personalized steering instrument. [[Ludwig et al. 2025]] adds a manifesto-like layer through [[Behavioral economics 2.0]]. [[Wang et al. 2024]] adds a broader legitimacy critique through [[Predictive optimization]], and [[Kleinberg et al. 2018]] adds an institutional layer by showing how machine learning enters concrete public decisions such as bail, where prediction, discretion, fairness, and coercive state power all meet. The page now also absorbs the older subpages on machine learning in behavioral economics and LLM behavioral biases, because in the current vault those branches are not yet developed enough to warrant separate concepts.

## Key distinctions

This concept is narrower than generic AI safety or fairness analysis. Its focus is not primarily toxic outputs, misinformation, or demographic bias. Instead it asks how AI interacts with behavioral benchmarks and behavioral mechanisms. One branch asks whether AI systems display systematic deviations from rational benchmarks or human-like judgment patterns in domains such as risky choice, forecasting, and investment. Another asks how machine learning changes the discovery of behavioral variables and the institutional ability to predict, steer, or exploit human behavior. A third, now anchored partly by [[Angwin et al. 2016]], asks how algorithmic systems become objects of dispute when fairness, opacity, and public legitimacy come into view. A fourth, now anchored partly by [[Bar-Gill et al. 2023]], asks how algorithms can exploit information deficits and behavioral biases in consumer markets. A fifth, now anchored by [[Kleinberg et al. 2024]], asks whether behavior-prediction systems are even aimed at the right human target in the first place, now tracked under [[Inversion problem]]. A sixth branch, represented by [[Sunstein 2025]], asks how AI can function as personalized choice architecture inside law and policy. A seventh, represented by [[Ludwig et al. 2025]], asks whether AI can partially reconfigure behavioral welfare economics itself. The page therefore now does the work previously split across a method-facing machine-learning note and an object-level LLM-bias note. It sits at the intersection of [[Behavioral Economics]], [[Heuristics and Biases]], classical benchmarks such as [[Expected utility theory]], and the policy branch gathered under [[Behavioral public policy]].

## Evidence and debate

The branch now has seventeen anchors. [[Camerer 2019]] argues that machine learning can help identify new behavioral predictors, that some human judgment failures can be usefully compared with poor prediction systems, and that AI-enabled firms may both overcome and exploit human limits. [[Bini et al. 2026]] then adapts behavioral experiments originally designed for humans to multiple LLM families and reports structured patterns rather than noise. One important result from Bini and coauthors is that task type matters: in preference-based tasks, more capable models can become more human-like, while in belief-based tasks larger models can become more rational. [[Angwin et al. 2016]] adds the public-controversy anchor: algorithmic systems may be challenged not because they fail mechanically, but because their errors are distributed unequally and their design is opaque. [[Kleinberg et al. 2016]], [[Chouldechova and Roth 2020]], [[Hellman 2020]], [[Binns 2018]], and [[Hedden 2021]] together build the fairness branch more fully, showing both the structural conflict among metrics and the wider frontier around data bias, dynamic feedback, fair representation, and unresolved definitions. [[Obermeyer et al. 2019]] adds the [[Target variable problem]] branch by showing that optimization around a bad proxy can generate large disparities. [[Kleinberg et al. 2024]] adds a different but closely related lesson: even when algorithms predict observed behavior well, they may still fail at the harder task of inferring the mental state an institution really cares about, now tracked under [[Inversion problem]]. [[Bar-Gill et al. 2023]] adds a complementary consumer-market branch: algorithms may create harm not by mispredicting or discriminating in the fairness-metrics sense, but by using personalization to exploit absent information and behavioral bias, now tracked under [[Algorithmic harm]]. [[Ludwig et al. 2024]] adds a compact public-finance argument: algorithms may be unusually attractive policy tools because their ranking improvements can generate large welfare gains at very low marginal cost. [[Sunstein 2025]] then shows that AI also matters as an institutional steering technology: recommendation systems and choice engines may help people overcome information deficits, present bias, or limited attention, but they may also become more opaque and manipulable than earlier forms of nudging. [[Ludwig et al. 2025]] pushes the branch further by arguing that algorithms should not merely recommend or predict, but help people approximate more considered judgment. [[Wang et al. 2024]] then adds the strongest legitimacy critique through [[Predictive optimization]], while [[Kleinberg et al. 2018]] adds an older but still highly relevant institutional case: predictive systems may outperform judges in pretrial release decisions, but only if the comparison accounts for selective labels and remains explicit about what the institution is trying to optimize. Taken together, these sources make the branch broader than simple LLM bias measurement.

## Practical or policy relevance

This concept matters because AI is increasingly used not only in advice and forecasting but also in the design of the choice environments people inhabit. If models display predictable behavioral distortions, organizations need methods for benchmarking, comparing, and correcting those patterns before deployment. If firms or regulators can use AI to detect and exploit attention limits, framing sensitivity, preference instability, or future-self conflict, behavioral economics also becomes a framework for AI governance and institutional design rather than only model evaluation.

## Related pages

The anchor sources are [[Camerer 2019]], [[Bini et al. 2026]], [[Angwin et al. 2016]], [[Kleinberg et al. 2016]], [[Chouldechova and Roth 2020]], [[Hellman 2020]], [[Binns 2018]], [[Hedden 2021]], [[Obermeyer et al. 2019]], [[Kleinberg et al. 2023]], [[Kleinberg et al. 2024]], [[Bar-Gill et al. 2023]], [[Ludwig et al. 2024]], [[Sunstein 2025]], [[Ludwig et al. 2025]], [[Wang et al. 2024]], and [[Kleinberg et al. 2018]]. The closest neighboring concepts are [[Algorithmic bias]], [[Algorithmic harm]], [[Statistical fairness criteria]], [[Target variable problem]], [[Inversion problem]], [[Predictive optimization]], [[Behavioral economics 2.0]], [[Clinical versus actuarial judgment]], and [[Behavioral public policy]]. Upstream conceptual links run through [[Heuristics and Biases]], [[Expected utility theory]], and the broader topic [[Behavioral Economics]].

## Open questions

Are LLM biases best understood as borrowed human biases, model-specific artifacts, or something more like a new class of behavioral regularity? Which benchmarks should dominate when models are used as advisors rather than autonomous choosers? How should this field handle the rapid turnover of model versions?
