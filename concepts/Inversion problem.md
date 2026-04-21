---
title: Inversion problem
page_type: concept
status: active
tags:
  - ai
  - behavioral-economics
  - behavioral-public-policy
updated_on: 2026-04-17
source_count: 2
related_pages:
  - [[Kleinberg et al. 2023]]
  - [[Kleinberg et al. 2024]]
  - [[Behavioral economics of AI]]
  - [[Predictive optimization]]
  - [[Target variable problem]]
  - [[Clinical versus actuarial judgment]]
  - [[Behavioral public policy]]
  - [[Behavioral economics 2.0]]
  - [[Internalities]]
  - [[Behavioral Economics]]
---

# Inversion problem

## Core idea

[[Inversion problem]] is the problem that arises when an algorithm is trained to predict observable behavior but is really being used to infer an underlying mental state such as preference, welfare, expertise, self-control, or reflective judgment. In the current vault, the anchor source is [[Kleinberg et al. 2024]]. The core claim is that better behavioral prediction does not by itself imply better identification of the human state an institution actually cares about.

## Key distinctions

This concept differs from [[Target variable problem]]. A target-variable problem arises when an institution optimizes the wrong proxy outcome, as in predicting health-care spending instead of illness burden. An inversion problem is deeper and more psychological: even if the behavioral target is measured exactly, the target may still fail to reveal the underlying mental state the institution hopes to respect or promote.

The easiest way to keep the distinction clear is by pairing examples. In [[Obermeyer et al. 2019]], the system predicts a measurable but normatively bad proxy, cost, when the institution really cares about sickness and need: that is a target-variable problem. In [[Kleinberg et al. 2023]] and [[Kleinberg et al. 2024]], a platform may predict clicks or engagement very well and still fail to learn what users actually endorse or benefit from: that is an inversion problem. One gets the observable target wrong; the other gets the relation between behavior and the relevant mental state wrong.

It also differs from [[Predictive optimization]]. Predictive optimization is the broader institutional practice of using predictive models to allocate burdens, opportunities, or resources. Inversion problems explain one reason that practice can fail even before fairness or governance objections enter: prediction of behavior may not recover preference, welfare, expertise, or reflective endorsement.

## Evidence and debate

[[Kleinberg et al. 2024]] gives the anchor statement in the current vault. The paper argues that recommendation systems, social media ranking, and expert-automation systems often predict clicks, choices, or judgments while really aiming at something else. In that sense, many apparently successful algorithms may still be badly aligned with human welfare or agency. [[Kleinberg et al. 2023]] is an important precursor because it makes the same problem concrete in one especially vivid setting: engagement optimization on online platforms. It shows that even an altruistic platform can make users worse off if it treats engagement as a transparent signal of welfare, and the full paper makes that point precise through a two-minds model of inconsistent preferences.

This is also why psychology is not optional in the paper's framework. If institutions care about reflective endorsement, expertise, temptation, self-control, or welfare, then observable behavior alone underdetermines the object of concern. Something like a model of attention, conflict, or preference structure has to enter somewhere, even if only implicitly. The inversion problem is therefore not just a machine-learning problem; it is a problem at the boundary between prediction and theories of the person.

Nearby sources make the concept more concrete. [[Obermeyer et al. 2019]] shows how systems can optimize the wrong proxy target and thereby generate large disparities. [[Wang et al. 2024]] generalizes the broader legitimacy challenge under [[Predictive optimization]]. [[Sunstein 2025]] and [[Ludwig et al. 2025]] then show why the concept matters for behavioral public policy and algorithmic assistance: once institutions want to help people choose better, they need some account of what "better" means beyond raw behavior. [[Kleinberg et al. 2018]] adds a different institutional angle by showing that even when prediction is useful, policy objectives are not reducible to one measured outcome.

## Practical or policy relevance

This concept matters because AI systems increasingly operate in settings where institutions care not merely about what people do, but about what they want, what they know, what they would choose under reflection, or what experts really judge. If those mental states are not directly observed, prediction systems may become powerful while still being pointed at the wrong human target.

For behavioral public policy, the concept matters because it raises the same question in a new form: should systems infer what helps people flourish, or only react to their observed behavior? For behavioral economics, it matters because it imports older worries about self-control, preference construction, and welfare inference directly into algorithm design.

## Related pages

The anchor sources are [[Kleinberg et al. 2024]] and [[Kleinberg et al. 2023]]. The closest neighboring pages are [[Predictive optimization]], [[Target variable problem]], [[Behavioral economics of AI]], [[Clinical versus actuarial judgment]], and [[Behavioral public policy]]. The broader topical homes are [[AI, Algorithms, and New Frontiers]] and [[Behavioral Economics]].

## Open questions

When is it legitimate for algorithms to infer latent mental states at all? Which mental states should count as policy-relevant or welfare-relevant targets? And can behavioral science help solve inversion problems without simply giving analysts a new excuse to impose their own preferred model of the person?
