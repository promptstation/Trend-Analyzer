---
name: section-11-recommendation-reverse-engineering-methods
description: Develop comprehensive, professional-level learning modules and training materials on reverse-Engineering Methods — Auditing, Probing, and Observational Inference within Recommendation System Architecture — design algorithmic audits with sock-puppet, mystery-shopping, and panel protocols including ethics and ToS considerations; run single-factor sensitivity analyses isolating ranking inputs, engineer feed-capture pipelines (donation extensions, recordings) with consent awareness; combine creator-side and observational.... Use this skill whenever the user asks to create, teach, or deepen training on reverse, engineering, methods, auditing, probing, observational, inference, Recommendation systems, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Trend Analyzer course 13, section 11)
  version: 1.0.0
  category: professional-education
---

# Reverse-Engineering Methods: Auditing, Probing, and Observational Inference — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **reverse-Engineering Methods: Auditing, Probing, and Observational Inference** within Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends.

Subject scope: Teaches the outside-in methodology: algorithmic auditing defined — systematic external measurement of algorithmic behavior, with the audit question taxonomy (what content gets recommended, to whom, in what order, with what sensitivity to features); sock-puppet methodology — controlled synthetic accounts with designed profiles (interests, demographics, behavior patterns) receiving recommendations as treatment-response data, the field's dominant method, with ethics and terms-of-service considerations; mystery shopping — human-auditor account protocols, and the panel-audit design (many auditors, standardized scripts) reducing individual variance; sensitivity analysis — varying one input at a time (engagement history, follow graph, search queries, location settings) to isolate ranking factors; feed-capture engineering — data collection from personalized feeds (screen recording, accessibility APIs, data-donation extensions like RegretsReporter lineage) with consent and scale trade-offs; recommendation-explanation probing — using platform-provided explanations ('because you watched X') as disclosed-feature evidence; creator-side intelligence — systematic creator-economy experiments (posting variants, analytics reading) as crowd-sourced reverse engineering, and its selection biases; observational network methods — inferring amplification from aggregate data (co-recommendation patterns, cascade shapes) without direct feed access; the replication problem — audits measure one moment of a continuously-retrained, A/B-tested system, requiring repeated measures and confidence statements; inference discipline — from observed feed differences to algorithmic claims: confound control (time, device, account age), baseline comparison (popularity-free exploration cohorts), and the limits of n-small audits; documentation standards — audit protocols, raw captures, analysis code, and uncertainty statements as the professional deliverable; and the method selection matrix — matching audit questions to methods by access level, cost, and inference strength.

Write as an experienced practitioner, not as a summarizer of popular content. Every framework taught must be something a real team or professional could run: procedures they can execute, criteria they can judge with, and artifacts they can hand to a colleague. Do not present claims as settled when the field treats them as contested — the training must model evidence discipline.

The module deepens this section's capabilities for a learner progressing from competent beginner toward expert practitioner, and connects them to the surrounding discipline rather than teaching them in isolation.

## Use Cases

### Full learning module
When asked for a comprehensive module on this topic:
1. Scope audience, prerequisites, duration, and discipline mix.
2. Build the evidence base from the authoritative sources below.
3. Write the full progressive module from the template.
4. Include all exercises with model solutions and all gate checklists.
5. Validate against the gate below before delivery.

### Condensed workshop
When asked for a one-day or half-day workshop:
1. Prioritize the units that match where the group is stuck.
2. Compress content to frameworks plus one worked example each; run exercises live with the participants' own material.
3. Leave behind the relevant checklists as job aids.

### Working job aids
When a practitioner needs tools rather than teaching:
1. Deliver the applicable checklists and templates from `references/exercise-and-checklist-library.md`, customized to their situation.
2. Add a one-page rationale per aid so the user understands what each item protects against.

## Core Output Requirements

- Deliverables are Markdown documents: the module, exercise sets with model solutions, and checklists. No placeholders, no "TODO" sections.
- Ground content in authoritative sources:
- Aggarwal, Recommender Systems: The Textbook, and Jannach et al. foundations for the classical architecture
- Covington, Adams & Sargin, 'Deep Neural Networks for YouTube Recommendations' (RecSys 2016) — the canonical two-stage architecture disclosure
- TikTok, YouTube, and Instagram official transparency disclosures on how recommendation systems work (TikTok's 'How TikTok recommends' and For You feed documentation; YouTube's recommendation guidance)
- Rendle-lineage matrix-factorization and factorization-machine literature; two-tower retrieval and ranking practice from industry engineering blogs
- Chen et al. on top-K recommender evaluation pitfalls, and the offline-online evaluation gap literature
- Algorithmic auditing research: sock-puppet and mystery-shopping methods (e.g., investigations of TikTok and YouTube recommendation dynamics), and the DSA transparency obligations for recommender disclosure
- Google Trends methodology documentation and the search-suggest/query-log literature
- Maintain an evidence ledger while writing: every factual claim or number is either sourced, flagged as disputed/popular account, or omitted. Never invent statistics, studies, or citations.
- Distinguish established research findings from professional conventions and informed recommendations, and say which is which.
- Explain each specialized term in clear language on first use.

## Module Development Workflow

### Phase 1 — Scope and audience
Determine delivery mode (full module / workshop / job aids), learner background, duration, and whether learners bring their own material to work on. Record these choices; they drive depth allocation in Phase 3.

### Phase 2 — Evidence base
Collect the strongest documented examples, findings, and case material for this topic from the authoritative sources. Note what is well established, what is contested, and what is merely conventional. Verify any numbers before publishing them.

### Phase 3 — Architecture
Sequence the material progressively and establish core conceptual distinctions before the concepts are used together. Suggested unit sequence:

1. Unit 1

### Phase 4 — Write the units
For each unit follow the internal structure: teach the framework → show a worked example (weak / improved / professional versions where useful) → connect back to the surrounding discipline → state trade-offs explicitly. Use `references/domain-content-map.md` as the unit-by-unit source of scope, bullets, and evidence guidance.

### Phase 5 — Exercises and assessment
Select and adapt exercises from `references/exercise-and-checklist-library.md`. Adapt scenarios to the audience's domain. For a full module, include expert-quality model solutions; for workshops, convert selected exercises into facilitated live activities.

### Phase 6 — Checklists and job aids
Include the gate checklists from the library, customized to the audience's context without diluting the decision each item forces.

### Phase 7 — Validation gate
Run the Validation Gate below against the finished material before delivery. Fix failures; do not ship and caveat.

## Module Template

ALWAYS use this exact template for full modules:

```markdown
# Reverse-Engineering Methods: Auditing, Probing, and Observational Inference [— audience/context subtitle]

## Who This Module Is For
## Prerequisites
## Learning Outcomes
## Unit 1 — Unit 1
## Integrated Capstone
## Practical Exercises
## Professional Checklists
## Sources and Evidence Notes
```

Each unit internally follows: framework → worked example(s) → disciplinary connection → trade-offs.

## Writing Standards

Throughout the material, prioritize language that is:

* Precise without becoming jargon-heavy
* Practical without discarding rigor
* Honest about limitations and contested findings without being defeatist
* Concrete — anchored in real cases, real artifacts, and verifiable numbers
* Progressive from fundamentals to expert judgment

Where a recommendation depends on context, explain the trade-off rather than presenting an absolute rule.

## Validation Gate

Before delivery, verify:

### Content
- all units present with correct depth for the scoped audience
- core distinctions established before they are used together
- every taught capability has a usable framework, not just an explanation

### Evidence
- every claim and number is sourced or explicitly flagged as disputed
- no invented statistics, studies, dates, or citations anywhere
- sources are authoritative; no SEO-farm or marketing claims presented as fact

### Capability
- each absorbed capability (3 in this section) is covered by teaching content AND at least one exercise with evaluation criteria
- exercises have model solutions in full-module mode

### Artifacts
- all gate checklists included and actionable as written
- template structure followed; no placeholder sections

### Quality
- trade-offs stated wherever recommendations are context-dependent
- terminology explained on first use
- reads as practitioner-written, not generic AI advice

## Anti-Patterns

Avoid: Treating platform disclosures as complete truth — official explanations are simplified, selective, and change without notice; Confusing correlation in observed feeds with algorithmic causation — personalization, social spread, and seasonality confound every observation; Auditing with single accounts and concluding population-level algorithmic behavior from n=1; Optimizing content for a guessed ranking formula rather than for documented engagement-quality signals, then calling it reverse engineering; Ignoring that recommendation systems retrain continuously — yesterday's reverse-engineered behavior may be obsolete; exercises without evaluation criteria; modules that stop at inspiration without a single decision the learner can now make better; and any content that overstates certainty beyond what the evidence supports.

## Decision Heuristic

When allocating depth under time or length limits, ask:

1. Where will this audience actually stall in practice?
2. Which unit protects the most value if taught well?
3. Can the learner run the framework tomorrow without me?
4. Is every example doing work a plain sentence could not?
5. What would a skeptical domain expert say about this material?

If two topics compete for space, keep the one that changes a decision.

## Final Principle

The goal is not more content about Recommendation systems. The goal is that a practitioner could take this material and perform: Design algorithmic audits with sock-puppet, mystery-shopping, and panel protocols including ethics and ToS considerations, combine creator-side and observational inference as complementary evidence, and document audits with replication caveats, confound control, and uncertainty statements — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
