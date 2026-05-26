---
title: Algorithmic bias
page_type: concept
status: active
tags:
  - ai
  - behavioral-economics
  - behavioral-public-policy
  - law
updated_on: 2026-05-26
source_count: 13
related_pages:
  - [[Bar-Gill et al. 2023]]
  - [[Angwin et al. 2016]]
  - [[Chouldechova and Roth 2020]]
  - [[Kleinberg et al. 2016]]
  - [[Corbett-Davies et al. 2017]]
  - [[Kleinberg et al. 2018]]
  - [[Ludwig and Mullainathan 2021]]
  - [[Hellman 2020]]
  - [[Binns 2018]]
  - [[Hedden 2021]]
  - [[Obermeyer et al. 2019]]
  - [[Wang et al. 2024]]
  - [[Narayanan 2026]]
  - [[Statistical fairness criteria]]
  - [[Target variable problem]]
  - [[Predictive optimization]]
  - [[Algorithmic harm]]
  - [[Behavioral economics of AI]]
  - [[Clinical versus actuarial judgment]]
  - [[Behavioral law and economics]]
  - [[Behavioral public policy]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Algorithmic bias

## Core idea

[[Algorithmic bias]] is the problem that predictive or decision-support systems can generate systematically distorted, unequal, or unjust outcomes across persons or groups. In the current vault, the concept is anchored first by [[Angwin et al. 2016]], which made the issue publicly salient through the COMPAS controversy, then by [[Kleinberg et al. 2016]], which formalizes why different fairness criteria can conflict, and then by [[Kleinberg et al. 2018]], which shows that the evaluation of such systems also depends on objective functions, counterfactual data problems, and institutional tradeoffs rather than on a single simple notion of fairness.

The important point is that algorithmic bias is not just "the algorithm made mistakes." The concept becomes interesting when the mistakes are patterned, when they burden some groups more than others, or when the system encodes hidden assumptions that are hard to contest.

## Key distinctions

First, [[Algorithmic bias]] is not identical to low predictive accuracy. A system can be reasonably accurate on average and still distribute its errors in troubling ways.

Second, the concept is not reducible to intentional discrimination. A model may generate disparate outcomes even when protected traits are excluded from the inputs, because the data, proxies, and target variables can still transmit unequal social structures.

Third, [[Algorithmic bias]] is not the whole of algorithmic governance. Some pages in the vault focus on prediction, ranking, and decision support more generally. This page is narrower: it is about the fairness and legitimacy problems that arise when those systems produce unequal or opaque burdens.

Fourth, the concept differs from [[Algorithmic harm]]. [[Bar-Gill et al. 2023]] shows that algorithms can also harm consumers by exploiting information deficits and behavioral biases in markets, even when the primary issue is not group-differentiated fairness. That neighboring concept belongs to the same branch, but it should not be collapsed into the fairness-metrics literature.

## Evidence and debate

[[Angwin et al. 2016]] is the agenda-setting source in the current vault because it made three linked concerns vivid at once: racial disparity in error distribution, opacity of proprietary scoring systems, and the use of such systems in high-stakes criminal-justice decisions. The article is not the end of the debate, but it is the starting point that later papers repeatedly answer.

[[Kleinberg et al. 2016]] adds the clearest formal lesson: some fairness properties that seem jointly desirable cannot generally all be achieved at the same time. In the current vault, this matters because it explains why the COMPAS debate quickly became a dispute about calibration, false positives, and base rates rather than settling into a simple question of whether one side had found a bug. [[Corbett-Davies et al. 2017]] then adds a policy-design interpretation of the same problem: fairness criteria can be treated as constraints on a regulatory objective, such as public safety net of detention costs. On that view, the "correct" definition of algorithmic bias is not a freestanding statistical fact. It depends on which policy objective and fairness constraint the institution has reason to adopt.

[[Hellman 2020]], [[Binns 2018]], and [[Hedden 2021]] deepen the debate over [[Statistical fairness criteria]]. Together they show that fairness metrics are not morally interchangeable, that they reflect different philosophical ideas, and that some of the most prominent criteria may be evidentially useful without being necessary for fairness itself. [[Corbett-Davies et al. 2017]] belongs in this same branch because it asks how a policymaker should choose among decision rules once a fairness constraint is imposed. [[Chouldechova and Roth 2020]] is then especially useful as a field map: it shows that fairness disputes are not exhausted by metric conflict in static classification, but also involve biased data, majority-fit effects, feedback loops, exploration in dynamic settings, and the difficulty of giving fairness definitions meaningful individual-level semantics.

[[Obermeyer et al. 2019]] identifies a more specific source of bias than metric conflict alone: the [[Target variable problem]]. A system can be accurate with respect to its chosen label and still be deeply unfair because it is optimizing the wrong proxy for the institution's true objective. [[Wang et al. 2024]] then widens the frame through [[Predictive optimization]], arguing that this whole style of decision-making often inherits legitimacy problems that are not solved by better prediction. [[Narayanan 2026]] pushes the institutional critique further by arguing that "algorithmic fairness" may be a category error when fairness is treated as a property of the technical subsystem. On this view, the relevant unit is the whole sociotechnical decision-making system: objectives, policies, human adjudication, appeals, explanations, institutional incentives, and the wider political setting.

[[Kleinberg et al. 2018]] then complicates the discussion in a second, more institutional way. It does not deny that fairness matters. Instead it shows that algorithmic evaluation also depends on selective labels, on what outcome the institution is trying to predict, and on the difference between prediction and policy choice. Its racial analysis is best read as a comparative disparate-impact or racial-outcome analysis: the paper asks whether algorithmic bail rules can improve the detention-crime tradeoff while also reducing racial disparities in detention, or while not jailing more Black defendants than judges. That is weaker than showing false-positive parity, false-negative parity, or equalized odds, especially because outcomes are not observed for detained defendants. [[Ludwig and Mullainathan 2021]] turns this into a useful teaching framework: algorithmic bias is often not an intrinsic property of machine learning but a consequence of human choices about labels, payoffs, thresholds, audits, and deployment. This does not make bias less serious; it makes it more institutionally tractable, because some algorithmic disparities can be diagnosed and redesigned more directly than human prejudice.

In the current vault, that matters because it keeps [[Algorithmic bias]] from collapsing into a purely journalistic or purely moralized label. The debate is partly technical, partly institutional, and partly normative.

This is why the concept belongs near [[Clinical versus actuarial judgment]] but should not be absorbed into it. The older actuarial-clinical literature asked whether formal prediction can outperform human discretion. The algorithmic-bias literature adds a further question: even if predictive systems outperform humans on some benchmark, under what conditions are their disparities, opacity, and governance structure acceptable?

## Practical or policy relevance

This concept matters because algorithms are increasingly used in criminal justice, credit, hiring, education, insurance, and public administration. Once such systems begin to allocate opportunities or burdens, questions about fairness, transparency, explainability, and contestability become institutional design questions rather than abstract technical ones.

In the current vault, the concept sits especially close to [[Behavioral public policy]] and [[Behavioral law and economics]] because those pages ask how real institutions should respond to human and machine fallibility. [[Algorithmic bias]] is one of the clearest cases where predictive efficiency and legitimacy can pull in different directions.

## Related pages

The anchor source for the public controversy is [[Angwin et al. 2016]]. The anchor source for the fairness-tradeoff theorem is [[Kleinberg et al. 2016]]. [[Corbett-Davies et al. 2017]] is the anchor for the constrained-optimization and policy-goal-relative interpretation of fairness. [[Ludwig and Mullainathan 2021]] is the best didactic anchor for explaining why real deployments fail even when prediction is promising. The anchor sources for the metrics and philosophical branch are [[Hellman 2020]], [[Binns 2018]], and [[Hedden 2021]]. [[Chouldechova and Roth 2020]] is the clearest survey anchor for how that branch widens into data bias, dynamic learning, and open frontier problems. The anchor source for the proxy-target mechanism is [[Obermeyer et al. 2019]]. The anchor source for the broader predictive-optimization critique is [[Wang et al. 2024]], while [[Narayanan 2026]] is the anchor for the category-error and algorithmic-bureaucracy critique. [[Bar-Gill et al. 2023]] is most useful here as a boundary marker, because it shows how a neighboring branch on [[Algorithmic harm]] can overlap with bias concerns without being reducible to them. The closest neighboring pages are [[Statistical fairness criteria]], [[Target variable problem]], [[Predictive optimization]], [[Algorithmic harm]], [[Behavioral economics of AI]], [[Clinical versus actuarial judgment]], [[Behavioral law and economics]], and the broader topic [[AI, Algorithms, and New Frontiers]].

## Open questions

Which fairness criteria should matter most when they cannot all be satisfied at once? How much opacity is tolerable in a public-risk tool used by courts or agencies? And when a model is said to be biased, is the right response to fix the model, change the institution, or question the target being predicted in the first place?
