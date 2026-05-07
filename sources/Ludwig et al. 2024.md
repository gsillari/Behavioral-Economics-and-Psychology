---
title: Ludwig et al. 2024
page_type: source
source_path: raw/papers/Ludwig et al. 2024.pdf
source_type: paper
status: ingested
tags:
  - ai
  - behavioral-economics
  - behavioral-public-policy
  - methodology
  - source
updated_on: 2026-05-06
related_pages:
  - [[Behavioral economics of AI]]
  - [[Clinical versus actuarial judgment]]
  - [[Behavioral public policy]]
  - [[Kleinberg et al. 2018]]
  - [[Ludwig et al. 2025]]
  - [[AI, Algorithms, and New Frontiers]]
---

# Ludwig et al. 2024: The unreasonable effectiveness of algorithms
## Summary

[[Ludwig et al. 2024]] is a short, didactic policy paper arguing that algorithms deserve much more attention as public-policy tools than they currently receive. The core claim is not merely that algorithms can predict well, but that in several policy settings they appear to generate extraordinarily high social returns relative to cost. The authors use the marginal value of public funds framework to argue that algorithms in areas such as pretrial release, education, health, and regulation can amount to a kind of policy "free lunch": large benefits with little or even negative net fiscal cost.

In the current vault, the paper matters less as a source of one new concept than as a compact argument for why the older actuarial-versus-clinical branch has become newly important in the age of machine learning. It therefore belongs close to [[Kleinberg et al. 2018]], but it is broader and more programmatic in its policy pitch.

## Key claims

The first claim is that many important policy problems are ranking problems, and algorithms can substantially improve those rankings.

The second claim is that the resulting welfare gains can be unusually large because better ranking reduces deadweight loss while algorithms often operate at scale with low marginal cost.

The third claim is that these advantages are visible across multiple policy domains rather than being confined to one special case.

The fourth claim is that the right response is not immediate blind deployment, but much more policy research and development: better algorithm design, careful pilots, and rigorous in situ evaluation.

The fifth claim is that economists should compare algorithms with other policy tools using the same welfare framework rather than treating them as an entirely separate class of intervention.

## Figures 1 and 2

The paper's two initial figures carry much of the conceptual argument. Figure 1 presents the standard public-policy picture: if the state expands an intervention from one quantity to a larger quantity, it gains welfare where marginal benefits exceed marginal costs. This picture assumes that cases are already reasonably ranked by expected benefit, so expanding the policy reaches additional cases with lower marginal returns.

Figure 2 shows why algorithms can be unusually powerful in ranking problems. Here the gain does not come primarily from doing more of the same policy. It comes from improving who is selected at a fixed threshold. If human decision-makers misrank cases, then an algorithm can steepen the marginal-benefit schedule by concentrating attention, detention, inspection, testing, or services on the cases where predicted social returns are higher. The algorithm therefore reduces deadweight loss by improving prioritization rather than simply increasing policy volume.

This is the bridge to the vault's older [[Clinical versus actuarial judgment]] branch. Ludwig, Mullainathan, and Rambachan turn the Meehl-style point that statistical prediction can outperform human judgment into a modern public-finance argument: better prediction can generate welfare gains when policy allocation is itself a prediction-and-ranking problem.

## Evidence and methods

The paper is synthetic and policy-analytic rather than a single new empirical study. It draws on existing evidence from criminal justice, education, health, and regulation, then evaluates algorithms using the marginal value of public funds framework associated with Hendren and Sprung-Keyser. The paper's distinctive contribution is therefore not a new anomaly or a new dataset, but a common evaluative language for algorithmic public-policy tools.

That makes it especially useful for the current vault because it turns several scattered AI and prediction discussions into one more legible policy argument: algorithms may be important not only because they predict well, but because they can be unusually cost-effective public interventions.

## Why it matters for PPE

For PPE students, [[Ludwig et al. 2024]] matters because it shows how algorithmic decision tools can be compared with ordinary policy levers rather than being treated as a futuristic side issue. It matters for economics because it uses welfare analysis and public-finance reasoning to evaluate algorithms. It matters for philosophy because it raises the question of whether predictive improvement is enough to justify intervention once fairness, opacity, and legitimacy are considered. It matters for politics because the relevant applications involve high-stakes public decisions in courts, schools, hospitals, and regulators.

Pedagogically, the paper is valuable because it gives a compact and memorable statement of why algorithms might be unusually powerful policy instruments without pretending that cost-effectiveness settles every normative question.

## Links into the wiki

This source should mainly strengthen [[Behavioral economics of AI]], [[Clinical versus actuarial judgment]], and [[Behavioral public policy]]. It is especially useful when read alongside [[Kleinberg et al. 2018]]: the earlier paper shows how one institutional comparison works in detail, while this one generalizes the lesson into a broader policy argument.

I do not think it warrants a separate concept page. The paper is better used to give sharper policy and teaching structure to concepts the vault already has.

## Open questions

How robust are these very high estimated social returns once algorithm deployment costs, compliance frictions, and institutional resistance are included? When should algorithmic ranking be treated as a welfare-improving public tool and when as a threat to legitimacy or fairness? And how much of the paper's optimism depends on policy settings being unusually well suited to ranking problems?

## Bibliographic reference

Ludwig, J., Mullainathan, S., & Rambachan, A. (2024). The unreasonable effectiveness of algorithms. *AEA Papers and Proceedings, 114*, 623-627. https://doi.org/10.1257/pandp.20241072
