---
name: section-07-information-detection-methods-ii
description: Develop comprehensive, professional-level learning modules and training materials on detection Methods II — Accounts, Coordination, and Networks within Information Ecosystems — analyze account authenticity with behavioral signals and bot-detection limits; detect coordinated inauthentic behavior via network clustering, synchrony, and infrastructure linkage using platform-disclosure evidence; identify astroturf patterns in reviews and comments. Use this skill whenever the user asks to create, teach, or deepen training on detection, methods, accounts, coordination, networks, Information ecosystems, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Trend Analyzer course 14, section 7)
  version: 1.0.0
  category: professional-education
---

# Detection Methods II: Accounts, Coordination, and Networks — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **detection Methods II: Accounts, Coordination, and Networks** within Media ecology, misinformation science, and platform governance applied to tracking misinformation lifecycles, echo chamber formation, and the shifting balance between legacy and digital media.

Subject scope: Covers behavior-level detection: account-authenticity analysis — behavioral signals (posting rhythms, sleep patterns, content diversity, network position), bot-detection methods (ML classifiers on activity features, the documented arms race with hybrid cyborg accounts), and their false-positive risks (activists and high-volume humans misflagged); coordinated inauthentic behavior (CIB) — the platform-disclosure category: networks of accounts acting together deceptively (shared infrastructure, synchronized posting, recycled content, artificial amplification), with the Meta/Graphika-style disclosure reports and takedown statistics as the primary public evidence; coordination-detection methods — network clustering of account behavior (the network-course connection), temporal-synchrony analysis, content-similarity graphs, and infrastructure linkage (registrations, devices, funding traces); state-operation patterns — documented tactics from platform disclosures (persona networks, cross-platform laundering, local-voice mimicry) and their evolution; astroturf detection — manufactured grassroots signals: review-burst analysis, comment-pattern forensics, and the fake-follower economy's measurable traces; crowd-sourced and community detection — volunteer fact-checker networks (Community Notes' bridging-based ranking as the documented innovation), their strengths and gaming dynamics; the mundane-majority caveat — most harmful misinformation is organic, unaudited, and uncoordinated, so coordination detection addresses the smaller but structured threat slice (the meta-pitfall honored); detection-evaluation standards — precision-recall trade-offs, adversarial robustness, and the disclosure-versus-detection tension (platforms revealing methods helps adversaries adapt); analyst workflows — integrating account, coordination, and content detection into ecosystem threat assessment; and the attribution standard — from detected coordination to actor attribution with evidence grades (infrastructure, tactics, language, timing) and appropriate uncertainty.

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
- Wardle & Derakhshan, Information Disorder: Toward an Interdisciplinary Framework — the misinformation/disinformation/malinformation taxonomy
- Vosoughi, Roy & Aral, 'The Spread of True and False News Online' (Science 2018) and the diffusion-of-misinformation research program
- Pennycook, Rand, and the accuracy-motivation literature on misinformation psychology; Lewandowsky-lineage debunking and inoculation research
- The Reuters Institute Digital News Report for legacy-versus-digital media consumption shifts across countries
- Starbird, Ridert & the CICU lineage on rumor cascades, mass-shooting misinformation, and crisis-information dynamics
- The EU DisinfoCode / DSA and the platform-governance literature on coordinated inauthentic behavior detection (Meta/Graphika disclosure reports)
- Postill, Coleman and the media-ecology tradition (McLuhan to platform ecology) for ecosystem framing
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
# Detection Methods II: Accounts, Coordination, and Networks [— audience/context subtitle]

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
- each absorbed capability (4 in this section) is covered by teaching content AND at least one exercise with evaluation criteria
- exercises have model solutions in full-module mode

### Artifacts
- all gate checklists included and actionable as written
- template structure followed; no placeholder sections

### Quality
- trade-offs stated wherever recommendations are context-dependent
- terminology explained on first use
- reads as practitioner-written, not generic AI advice

## Anti-Patterns

Avoid: Using misinformation, disinformation, and malinformation interchangeably — intent and harm distinctions carry analytic and legal weight; Assuming exposure equals belief, and belief equals behavior change — the documented gaps are large; Treating corrections as automatic fixes — backfire and familiarity effects require careful debunking design; Reading coordinated-campaign disclosures as the whole threat — mundane organic misinformation usually outweighs operations; Legacy-versus-digital framing as generational war — actual consumption is hybrid, and trust patterns vary more by country than by age; exercises without evaluation criteria; modules that stop at inspiration without a single decision the learner can now make better; and any content that overstates certainty beyond what the evidence supports.

## Decision Heuristic

When allocating depth under time or length limits, ask:

1. Where will this audience actually stall in practice?
2. Which unit protects the most value if taught well?
3. Can the learner run the framework tomorrow without me?
4. Is every example doing work a plain sentence could not?
5. What would a skeptical domain expert say about this material?

If two topics compete for space, keep the one that changes a decision.

## Final Principle

The goal is not more content about Information ecosystems. The goal is that a practitioner could take this material and perform: Analyze account authenticity with behavioral signals and bot-detection limits, evaluate crowd-sourced verification systems (Community Notes lineage) with gaming awareness, and attribute detected operations with evidence-graded uncertainty honoring the organic-majority caveat — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
