---
title: Kleinberg et al. 2023
page_type: source
source_path: raw/papers/Kleinberg et al. 2023.pdf
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
  - [[Kleinberg et al. 2024]]
  - [[Behavioral economics of AI]]
  - [[Predictive optimization]]
  - [[Behavioral public policy]]
  - [[Internalities]]
  - [[Time inconsistency]]
---

# Kleinberg et al. 2023: The Challenge of Understanding What Users Want
## Summary

[[Kleinberg et al. 2023]] is a substantial theoretical paper on inconsistent preferences and engagement optimization in online platforms. Its central claim is that platforms often assume they can infer what users want from what users do, but this revealed-preference move breaks down when behavior is shaped by myopia, mindless choice, temptation, or other preference inconsistencies. In the current vault, the paper matters as a major bridge between older behavioral ideas about self-control and the newer AI-and-prediction literature gathered under [[Inversion problem]].

The paper's core example is online engagement. A platform may increase clicks, watch time, or session length while making users worse off. That matters because it shows that the difficulty is not only bad incentives or manipulative firms. Even an altruistic platform that genuinely wants to help users can fail if it treats engagement as a transparent signal of welfare. The full paper goes well beyond the earlier conference preview by building a formal two-minds model, introducing the idea of a content manifold, and proving conditions under which higher engagement and higher user welfare diverge.

## Key claims

The first claim is that user behavior on platforms may be inconsistent with what users actually want, especially when choice is myopic, habitual, or temptation-driven.

The second claim is that engagement optimization can therefore diverge from welfare optimization even when the platform is trying to serve users well.

The third claim is that whether increased engagement helps or harms depends on the direction of change in the content space. Some changes can make users both more engaged and better off, while others can make them more engaged and less happy.

The fourth claim is that behavioral economics is needed to model these cases, because standard revealed-preference assumptions do not capture inconsistent or unstable wants.

The fifth claim is that platforms need richer design and measurement strategies than raw engagement. The paper discusses breaks, friction, user choice sets, and related design levers as ways to think about when more interaction is helping users and when it is exploiting or amplifying inconsistent preferences.

## Evidence and methods

This paper is a theoretical and modeling piece rather than an empirical platform study. It develops a model of media consumption with inconsistent preferences and uses a two-minds architecture, labeled system 1 and system 2, to formalize internal conflict in user behavior. It then studies how a platform that only observes engagement behaves when it optimizes over a large set of possible content characterized as a content manifold.

That makes the paper valuable in the current vault as a conceptual bridge. It connects classic behavioral ideas about temptation, myopia, and self-control to algorithm design and platform optimization. Relative to the earlier abstract, the full paper matters because it supplies the model, the characterization theorems, and the richer discussion of design interventions rather than only the high-level platform example.

## Why it matters for PPE

For PPE students, [[Kleinberg et al. 2023]] matters because it shows that digital platforms revive an old behavioral question in a new technical form: does observed behavior really reveal what people want? It matters for economics because it challenges naïve welfare inference from engagement data. It matters for philosophy because it raises questions about whether fleeting, impulsive, and reflective preferences should be treated equally. And it matters for politics and public policy because platform optimization can shape attention and behavior at scale even when its welfare target is unclear.

Pedagogically, the paper is useful because it translates familiar behavioral themes such as inconsistent preferences and temptation goods into a platform-design vocabulary. It is also one of the clearest cases in the vault where a behavioral welfare problem becomes an algorithm-design problem without changing its basic philosophical structure.

## Links into the wiki

This source should mainly strengthen [[Inversion problem]], [[Behavioral economics of AI]], [[Predictive optimization]], [[Behavioral public policy]], [[Internalities]], and [[Time inconsistency]]. It sits very close to [[Kleinberg et al. 2024]], but plays a different role. The 2023 paper gives a focused platform-and-engagement model with full formal machinery; the 2024 paper generalizes the problem into a broader claim about algorithms inferring mental state from behavior in multiple institutional settings.

I do not think it warrants another concept page. Its best role is to deepen the already-created [[Inversion problem]] branch.

## Open questions

When should platforms optimize engagement at all? Which kinds of behavioral inconsistency are serious enough to undermine revealed-preference reasoning in digital environments? And can platforms infer user welfare without simply imposing a paternalist model of what users should want?

## Bibliographic reference

Kleinberg, J., Mullainathan, S., & Raghavan, M. (2023). The Challenge of Understanding What Users Want: Inconsistent Preferences and Engagement Optimization. *Management Science*, 70(9), 6336-6355. https://doi.org/10.1287/mnsc.2022.03683
