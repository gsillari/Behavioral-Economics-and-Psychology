---
title: Source Review Dashboard
page_type: output
status: active
tags:
  - review
  - maintenance
  - sources
  - ppe
updated_on: 2026-04-06
query: Review all ingested paper-source notes and prioritize expansion
generated_on: 2026-04-06
sources_used:
  - [[Behavioral Economics]]
  - [[What Behavioral Economics Thinks Rationality Is]]
  - [[Prospect Theory]]
  - [[Heuristics and Biases]]
  - [[Field Evidence in Behavioral Economics]]
  - [[Behavioral public policy]]
  - [[Behavioral law and economics]]
related_pages:
  - [[Behavioral Economics]]
  - [[What Behavioral Economics Thinks Rationality Is]]
  - [[Behavioral Public Policy and Its Competing Paradigms]]
  - [[Field Evidence in Behavioral Economics]]
  - [[Behavioral public policy]]
  - [[Heuristics and Biases]]
  - [[Prospect Theory]]
---

# Source Review Dashboard

## Methodology

- Reviewed all 27 currently ingested paper notes in `wiki/sources/`.
- Used the existing source notes, [wiki/index.md](/Users/giacomosillari/Documents/llm-wiki-scratch/wiki/index.md), and [logs/source_index.csv](/Users/giacomosillari/Documents/llm-wiki-scratch/logs/source_index.csv) as the primary evidence base.
- Spot-checked key hub pages where prioritization depended on current integration quality: [[Behavioral Economics]], [[What Behavioral Economics Thinks Rationality Is]], [[Prospect Theory]], [[Heuristics and Biases]], [[Field Evidence in Behavioral Economics]], [[Behavioral public policy]], and [[Behavioral law and economics]].
- Treated this as a maintenance review, not a fresh re-ingest. Judgments are therefore conservative and keyed to what the wiki currently captures well or poorly.
- Ranked sources by a combined judgment about conceptual importance, likely course value for PPE students, present wiki coverage, and how much immediate downstream improvement further work would unlock.

## Ranked Table

| Rank | Tier | Source                           | Importance   | Course relevance | Expansion priority | Coverage depth | Canonical for                                                                                                                                                                     | Main reason                                                                                                                               | Wiki gap                                                                                                                                                     | Suggested actions                                                                                                                                                                                                                                                                                     |
| ---- | ---- | -------------------------------- | ------------ | ---------------- | ------------------ | -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | A    | [[Kahneman and Tversky 1979]]    | foundational | core             | now                | strong         | [[Prospect Theory]]; [[Loss aversion]]; [[Reference dependence]]; [[Framing effects]]; [[Expected utility theory]]                                                                | Core descriptive alternative to expected utility and still the most important single risky-choice source in the vault.                    | The source underwrites many pages, but the original architecture of the theory is still distributed too loosely across the main concept and synthesis pages. | Deepen [[Prospect Theory]] around value function, decision weights, and benchmark contrast; tighten links to [[Expected utility theory]], [[Allais 1953]], and [[Framing effects]]; strengthen the theory's role in [[Behavioral Economics]] and [[What Behavioral Economics Thinks Rationality Is]]. |
| 2    | A    | [[Tversky and Kahneman 1974]]    | foundational | core             | now                | strong         | [[Heuristics and Biases]]; [[Representativeness heuristic]]; [[Availability heuristic]]; [[Anchoring]]; [[Behavioral Economics]]                                                  | Supplies the canonical vocabulary for judgment under uncertainty and still structures the wiki's bias branch.                             | The mechanism pages exist, but the original experimental logic and normative targets are still thinner than they should be.                                  | Expand the three canonical heuristic pages with clearer classic patterns and benchmark norms; sharpen the source's relation to [[Nonstandard beliefs]] and [[Fast and slow thinking]]; integrate the source more explicitly with [[Gigerenzer 2008]], [[De Neys 2012]], and [[De Neys 2023]].         |
| 3    | A    | [[DellaVigna 2009]]              | major        | core             | now                | strong         | [[Field Evidence in Behavioral Economics]]; [[Nonstandard preferences]]; [[Nonstandard beliefs]]; [[Nonstandard decision-making]]; [[Strategic response to behavioral anomalies]] | Best empirical organizer in the vault for showing that behavioral economics is a field program rather than a lab-only story.              | The taxonomy is now present, but several mechanism pages still read more like labels than like a mapped empirical architecture.                              | Build a clearer field-evidence matrix across domains and mechanisms; distinguish the strongest field-backed mechanisms from thinner ones; strengthen the bridge from [[Field Evidence in Behavioral Economics]] into [[Behavioral public policy]].                                                    |
| 4    | A    | [[Jolls et al. 1998]]            | major        | core             | now                | adequate       | [[Behavioral law and economics]]; [[Bounded rationality]]; [[Time inconsistency]]; [[Social preferences]]; [[Behavioral public policy]]                                        | Foundational bridge from behavioral findings to institutional and legal analysis.                                                         | The source is well-placed, but the legal and normative consequences are still more asserted than organized.                                                  | Expand [[Behavioral law and economics]] as a structured branch rather than a single bridge page; make [[Bounded rationality]], [[Time inconsistency]], and [[Social preferences]] more distinct; connect the source more tightly to [[Behavioral Public Policy and Its Competing Paradigms]].      |
| 5    | A    | [[Madrian 2014]]                 | major        | core             | now                | strong         | [[Behavioral public policy]]; [[Internalities]]; [[Field Evidence in Behavioral Economics]]; [[Libertarian paternalism]]; [[Asymmetric paternalism]]                              | Best operational policy framework currently in the vault.                                                                                 | The policy branch is conceptually strong, but the intervention logic is not yet explicit enough page by page.                                                | Build a cleaner friction-to-tool map inside [[Behavioral public policy]]; strengthen [[Internalities]] as a bridge between evidence and justification; clarify how Madrian differs from and extends [[Libertarian paternalism]] and [[Asymmetric paternalism]].                                       |
| 6    | A    | [[Camerer and Loewenstein 2004]] | foundational | core             | soon               | adequate       | [[Behavioral Economics]]; [[Heuristics and Biases]]; [[Prospect Theory]]; [[Field Evidence in Behavioral Economics]]; [[Behavioral public policy]]                                | Best field-level self-description of behavioral economics as a research program.                                                          | It currently contextualizes the vault well, but it is not yet doing enough structural work in the main hub and course-level syntheses.                       | Use the source more aggressively inside [[Behavioral Economics]] as a map of subfields; strengthen its role in [[What Behavioral Economics Thinks Rationality Is]] as field-level framing; add a clearer chronology of strands it helps unify.                                                        |
| 7    | B    | [[Gigerenzer 2008]]              | major        | important        | soon               | adequate       | [[Ecological rationality]]; [[Adaptive toolbox]]; [[Rationality wars]]; [[Heuristics and Biases]]; [[Bounded rationality]]                                                        | Primary positive statement of the ecological alternative to the bias paradigm.                                                            | The counterposition is visible, but the ecological branch still feels more like a critique than a full alternative program.                                  | Deepen [[Ecological rationality]] and [[Adaptive toolbox]] as positive pages; connect Gigerenzer more concretely to [[Dawes 1979]] and [[Dawes et al. 1989]]; strengthen ecological-rationality material in the rationality synthesis.                                                                |
| 8    | B    | [[Sunstein and Thaler 2003]]     | major        | core             | soon               | adequate       | [[Libertarian paternalism]]; [[Behavioral public policy]]; [[Behavioral Public Policy and Its Competing Paradigms]]; [[Behavioral Economics]]                                     | Most influential broad justification for behaviorally informed choice architecture.                                                       | The main argument is present, but the liberty-welfare tension and the exact role of inevitability in choice architecture remain underdeveloped.              | Expand [[Libertarian paternalism]] around justification, objection, and limits; connect the source more explicitly to [[Jolls et al. 1998]], [[Camerer et al. 2003]], and [[Madrian 2014]]; sharpen its role in the policy synthesis.                                                                 |
| 9    | B    | [[Camerer et al. 2003]]          | major        | core             | soon               | adequate       | [[Asymmetric paternalism]]; [[Behavioral public policy]]; [[Behavioral Public Policy and Its Competing Paradigms]]; [[Heuristics and Biases]]                                     | Gives the vault the clearest low-burden intervention test rather than only a broad policy philosophy.                                     | The asymmetry criterion is noted, but not yet operationalized across policy domains or clearly distinguished from adjacent frameworks.                       | Tighten [[Asymmetric paternalism]] around criteria and tradeoffs; compare it directly to [[Libertarian paternalism]] and [[Madrian 2014]]; add domain examples inside [[Behavioral public policy]].                                                                                                   |
| 10   | B    | [[Hortal 2025]]                  | major        | important        | soon               | adequate       | [[Rationality wars]]; [[Ecological rationality]]; [[Behavioral public policy]]                                                                                                   | Strongest philosophical-pluralist source in the current rationality branch.                                                               | The branch captures the pluralist thesis, but not yet enough of its downstream consequences for concrete policy and benchmark choice.                        | Strengthen [[Rationality wars]] with a more explicit standards map; connect Hortal more tightly to [[Behavioral Public Policy and Its Competing Paradigms]]; compare the source more directly with [[Gigerenzer 2008]] and [[Samuels et al. 2002]].                                                   |
| 11   | B    | [[Allais 1953]]                  | foundational | core             | soon               | adequate       | [[Allais paradox]]; [[Expected utility theory]]; [[Prospect Theory]]; [[Behavioral Economics]]                                                                                    | Historical anomaly source that makes the expected-utility challenge legible from inside economics.                                        | Its historical importance is clear, but it is still used more as background than as a fully developed benchmark problem.                                     | Deepen [[Allais paradox]] as a canonical anomaly page; tighten the historical arc from [[Allais 1953]] to [[Kahneman and Tversky 1979]]; compare the source more explicitly with [[Ellsberg 1961]].                                                                                                   |
| 12   | B    | [[Ellsberg 1961]]                | foundational | important        | soon               | adequate       | [[Ambiguity aversion]]; [[Subjective probability]]; [[Expected utility theory]]; [[Nonstandard beliefs]]; [[Behavioral Economics]]                                                | Gives the vault a belief-side challenge to classical rationality, not just a preference-side one.                                         | The branch is clean but still narrow; ambiguity is not yet fully connected to PPE-relevant policy and benchmark disputes.                                    | Deepen [[Ambiguity aversion]] beyond the basic contrast with risk; tie the source more tightly to [[de Finetti 1937]] and [[Aumann 1962]]; extend its use in [[What Behavioral Economics Thinks Rationality Is]] and future policy-under-uncertainty work.                                            |
| 13   | B    | [[Ariely et al. 2003]]           | major        | important        | soon               | adequate       | [[Coherent arbitrariness]]; [[Constructed preferences]]; [[Anchoring]]; [[Nonstandard preferences]]; [[Behavioral law and economics]]                                             | Strongest current source for destabilizing welfare inference from observed valuation.                                                     | The main challenge is visible, but the downstream implications for welfare analysis and public policy remain thinner than they should be.                    | Deepen [[Constructed preferences]] and [[Coherent arbitrariness]] as welfare-problem pages; connect the source more explicitly to [[Behavioral public policy]] and [[Behavioral law and economics]]; pair it more tightly with [[Ariely et al. 2006]].                                                |
| 14   | B    | [[Ariely et al. 2006]]           | major        | important        | soon               | adequate       | [[Preference uncertainty]]; [[Constructed preferences]]; [[Behavioral public policy]]; [[Behavioral law and economics]]                                                           | Sharpens the constructed-preference problem by moving from goods to experiences.                                                          | The experience-goods angle is present, but not yet fully integrated into the welfare and policy branches.                                                    | Distinguish [[Preference uncertainty]] more clearly from generic constructed preferences; strengthen the source's role in [[Behavioral public policy]] and [[Behavioral Public Policy and Its Competing Paradigms]]; tie it more directly to [[Madrian 2014]].                                        |
| 15   | C    | [[de Finetti 1937]]              | foundational | important        | later              | adequate       | [[Subjective probability]]; [[Expected utility theory]]; [[Nonstandard beliefs]]; [[Behavioral Economics]]                                                                        | Valuable formal benchmark for the belief side of rationality.                                                                             | The benchmark branch exists, but it is still historically thin and underconnected to later uncertainty sources.                                              | Connect the source more tightly to [[Ellsberg 1961]]; eventually extend the benchmark branch with later decision-theory sources; keep it active in the rationality synthesis rather than isolated in formal background.                                                                               |
| 16   | C    | [[Coase 1960]]                   | supporting   | important        | later              | adequate       | [[Coase theorem]]; [[Transaction costs]]; [[Behavioral law and economics]]; [[Behavioral public policy]]                                                                          | Useful pre-behavioral benchmark for institutional comparison and policy analysis.                                                         | The source is well placed, but it currently acts more as a benchmark mention than as a live comparative framework.                                           | Clarify its contrastive role against behavioral policy sources; connect it more explicitly to [[Jolls et al. 1998]] and [[Madrian 2014]]; keep future expansion focused on comparative institutional reasoning, not general Coase exegesis.                                                           |
| 17   | C    | [[Benartzi and Thaler 1995]]     | supporting   | important        | later              | adequate       | [[Myopic loss aversion]]; [[Equity premium puzzle]]; [[Prospect Theory]]; [[Loss aversion]]                                                                                       | Best current behavioral-finance application in the vault.                                                                                 | The finance branch exists, but it still sits somewhat apart from the main course spine and policy material.                                                  | Strengthen the behavioral-finance branch inside [[Behavioral Economics]]; connect the source more to savings and retirement policy themes; use it to show prospect theory traveling into markets.                                                                                                     |
| 18   | C    | [[Dawes 1979]]                   | supporting   | important        | later              | adequate       | [[Clinical versus actuarial judgment]]; [[Bounded rationality]]; [[Heuristics and Biases]]; [[Ecological rationality]]                                                                        | Important procedural challenge to expert intuition and informal judgment.                                                                 | The source's role in procedural rationality is visible, but not yet well integrated into the main rationality and policy debates.                            | Pair the source more tightly with [[Dawes et al. 1989]]; connect it to [[Gigerenzer 2008]] and [[Behavioral law and economics]]; use it more explicitly in debates about institutional decision procedures.                                                                                           |
| 19   | C    | [[Dawes et al. 1989]]            | supporting   | important        | later              | adequate       | [[Clinical versus actuarial judgment]]; [[Behavioral law and economics]]; [[Bounded rationality]]                                                                                 | Strong institutional comparison source for when explicit procedures outperform discretion.                                                | The concept page exists, but the source is still underused in broader PPE discussions of expertise and governance.                                           | Integrate the source more into [[Behavioral law and economics]] and policy-comparison arguments; pair it with [[Dawes 1979]] and later AI/prediction material; use it to sharpen institutional competence questions.                                                                                  |
| 20   | C    | [[De Neys 2012]]                 | supporting   | important        | later              | adequate       | [[Logical intuitions]]; [[Fast and slow thinking]]; [[Heuristics and Biases]]; [[Rationality wars]]                                                                               | Helpful corrective to crude intuition-versus-reason readings of the bias literature.                                                      | The nuance is present, but still localized rather than distributed across the main rationality pages.                                                        | Fold the source more concretely into [[Heuristics and Biases]] and [[What Behavioral Economics Thinks Rationality Is]]; pair it tightly with [[De Neys 2023]]; use it to complicate simple anti-rationality narratives.                                                                               |
| 21   | C    | [[De Neys 2023]]                 | supporting   | important        | later              | adequate       | [[Fast and slow thinking]]; [[Logical intuitions]]; [[Heuristics and Biases]]; [[Rationality wars]]                                                                               | Keeps the dual-process branch current and theoretically careful.                                                                          | The page is useful, but the branch still functions more as a refinement note than as a deeply integrated interpretive lens.                                  | Use the source to revise dual-process framing across relevant pages; connect it more directly to [[Gigerenzer 2008]] and [[Hortal 2025]]; keep it paired with [[De Neys 2012]] rather than expanding it in isolation.                                                                                 |
| 22   | C    | [[Samuels et al. 2002]]          | supporting   | optional         | later              | adequate       | [[Rationality wars]]; [[Evolutionary psychology]]; [[Heuristics and Biases]]                                                                                                      | Useful deflationary source for reading the rationality wars more carefully.                                                               | The source helps with calibration, but it currently serves a narrower interpretive role than higher-priority debate sources.                                 | Keep it active in [[Rationality wars]]; compare it more explicitly with [[Hortal 2025]]; avoid major standalone expansion until the debate branch grows further.                                                                                                                                      |
| 23   | C    | [[Aumann 1962]]                  | supporting   | optional         | later              | adequate       | [[Completeness axiom]]; [[Expected utility theory]]; [[Behavioral Economics]]                                                                                                     | Useful internal softening of the classical benchmark.                                                                                     | The insight is clear, but the branch remains small and lower-yield than other benchmark challenges.                                                          | Keep the source connected to [[Expected utility theory]] and the rationality synthesis; revisit it later if the vault develops a fuller formal-choice branch; avoid overinvesting before that branch exists.                                                                                          |
| 24   | C    | [[Arkes and Blumer 1985]]        | supporting   | important        | later              | adequate       | [[Sunk cost effect]]; [[Prospect Theory]]; [[Nonstandard decision-making]]                                                                                                        | Classic anomaly source with clear PPE relevance for escalation and persistence.                                                           | The core anomaly is in place, but the source has not yet been expanded into wider institutional and policy contexts.                                         | Extend the source later into public-project and organizational examples; connect it more strongly to [[Behavioral public policy]] and escalation themes; keep it linked to [[Prospect Theory]].                                                                                                       |
| 25   | C    | [[Barnett et al. 2005]]          | supporting   | optional         | later              | adequate       | [[Regression to the mean]]; [[Field Evidence in Behavioral Economics]]                                                                                                            | Useful methods guardrail for reading field evidence responsibly.                                                                          | It is doing its current job, but it is a methods support note rather than a central course driver.                                                           | Keep referencing it when future empirical pages are added; use it to build a small methods sublayer later if the empirical branch thickens; do not prioritize major standalone expansion now.                                                                                                         |
| 26   | D    | [[Camerer 2019]]                 | peripheral   | optional         | none               | stub           | [[Behavioral economics of AI]]; [[Behavioral economics of AI]]; possible secondary link to [[Bounded rationality]]                                                  | Interesting AI-method bridge, but not yet central to the current PPE course spine.                                                        | The AI-method branch is still thin and not yet supported by enough companion sources to justify heavy investment.                                            | Retain and defer; expand only if an AI module becomes more central; if revisited, pair it with additional non-LLM AI/governance sources rather than extending it alone.                                                                                                                               |
| 27   | D    | [[Bini et al. 2026]]             | peripheral   | optional         | none               | stub           | [[Behavioral economics of AI]]; [[Behavioral economics of AI]]; possible secondary link to [[Expected utility theory]]                                                                  | Timely and interesting, but the branch currently rests on too little surrounding material to outrank the core behavioral-economics spine. | The AI branch is still shallow and weakly connected to the rest of the course-relevant vault.                                                                | Retain and defer; expand only after adding more AI-behavioral sources; if revisited, use it to compare benchmark types rather than letting it drift into a silo.                                                                                                                                      |

## Tier A: Foundational and Expand Now

- [[Kahneman and Tversky 1979]]: central descriptive theory page; high existing coverage but still high return from deeper integration.
- [[Tversky and Kahneman 1974]]: canonical judgment-under-uncertainty source; mechanism pages need more original structure.
- [[DellaVigna 2009]]: strongest empirical organizer in the vault; several child pages still need clearer field architecture.
- [[Jolls et al. 1998]]: key bridge from findings to institutions; law-and-policy branch should become more structured.
- [[Madrian 2014]]: best operational policy framework; policy pages need a cleaner mechanism-to-intervention map.

## Tier B: Important and Strengthen Soon

- [[Camerer and Loewenstein 2004]]
- [[Gigerenzer 2008]]
- [[Sunstein and Thaler 2003]]
- [[Camerer et al. 2003]]
- [[Hortal 2025]]
- [[Allais 1953]]
- [[Ellsberg 1961]]
- [[Ariely et al. 2003]]
- [[Ariely et al. 2006]]

## Tier C: Useful Support Material

- [[de Finetti 1937]]
- [[Coase 1960]]
- [[Benartzi and Thaler 1995]]
- [[Dawes 1979]]
- [[Dawes et al. 1989]]
- [[De Neys 2012]]
- [[De Neys 2023]]
- [[Samuels et al. 2002]]
- [[Aumann 1962]]
- [[Arkes and Blumer 1985]]
- [[Barnett et al. 2005]]

## Tier D: Retain with Low Immediate Investment

- [[Camerer 2019]]
- [[Bini et al. 2026]]

## Top 5 to Expand First

### 1. [[Kahneman and Tversky 1979]]

- Why it matters: this is the vault's most important single source on descriptive choice under risk and the most important bridge between formal benchmark theory and behavioral explanation.
- What is missing in the current wiki: the original theory's internal architecture is still too compressed, especially the relation between reference dependence, loss aversion, decision weights, and the contrast with expected utility.
- Pages that should be updated:
  - [[Prospect Theory]]
  - [[Loss aversion]]
  - [[Reference dependence]]
  - [[Framing effects]]
  - [[Expected utility theory]]
  - [[Behavioral Economics]]
  - [[What Behavioral Economics Thinks Rationality Is]]

### 2. [[Tversky and Kahneman 1974]]

- Why it matters: this source still sets the vocabulary for heuristics, bias, and judgment under uncertainty across economics, philosophy, and public reasoning.
- What is missing in the current wiki: the canonical heuristics are present, but the original task logic, benchmark norms, and relation to later critiques are still too generic.
- Pages that should be updated:
  - [[Heuristics and Biases]]
  - [[Representativeness heuristic]]
  - [[Availability heuristic]]
  - [[Anchoring]]
  - [[Nonstandard beliefs]]
  - [[Behavioral Economics]]
  - [[What Behavioral Economics Thinks Rationality Is]]

### 3. [[DellaVigna 2009]]

- Why it matters: this is the strongest current source for showing that behavioral economics is an empirically serious field program rather than a lab anthology.
- What is missing in the current wiki: the survey's taxonomy exists, but the field structure is not yet explicit enough about domains, robustness, and strategic responses.
- Pages that should be updated:
  - [[Field Evidence in Behavioral Economics]]
  - [[Nonstandard preferences]]
  - [[Nonstandard beliefs]]
  - [[Nonstandard decision-making]]
  - [[Strategic response to behavioral anomalies]]
  - [[Behavioral public policy]]
  - [[Behavioral Economics]]

### 4. [[Jolls et al. 1998]]

- Why it matters: this source is the earliest major institutional translation layer between behavioral findings and legal-policy reasoning in the vault.
- What is missing in the current wiki: the three-part framework is visible, but the branch still lacks enough structure around legal applications, normative stakes, and its relation to later policy paradigms.
- Pages that should be updated:
  - [[Behavioral law and economics]]
  - [[Bounded rationality]]
  - [[Time inconsistency]]
  - [[Social preferences]]
  - [[Behavioral public policy]]
  - [[Behavioral Public Policy and Its Competing Paradigms]]

### 5. [[Madrian 2014]]

- Why it matters: this is the clearest source in the vault on how behavioral economics becomes an operational policy framework rather than only a critique of standard theory.
- What is missing in the current wiki: the source is well represented, but the policy branch still needs a clearer intervention logic tied to specific behavioral frictions and welfare assumptions.
- Pages that should be updated:
  - [[Behavioral public policy]]
  - [[Internalities]]
  - [[Field Evidence in Behavioral Economics]]
  - [[Libertarian paternalism]]
  - [[Asymmetric paternalism]]
  - [[Behavioral Public Policy and Its Competing Paradigms]]

## Uncertainty Notes

- The ordering among [[Camerer and Loewenstein 2004]], [[Gigerenzer 2008]], and [[Hortal 2025]] would change if the near-term goal were more philosophical framing rather than course-core consolidation.
- The ranking of [[Coase 1960]], [[de Finetti 1937]], and [[Aumann 1962]] depends on how much formal benchmark material you want in the PPE teaching spine. Their current placement assumes the next maintenance pass should prioritize behavioral-economics core over background theory.
- The AI branch is deliberately deprioritized here. If the course or wiki is about to add a serious AI/governance module, [[Camerer 2019]] and [[Bini et al. 2026]] should move up together rather than separately.
