---
name: section-09-network-graph-social-analysis
description: Develop comprehensive, professional-level learning modules and training materials on social Network Analysis — Sociological Method and Data within Network & Graph Theory — design network data collection with boundary specification and instrument choice; conduct ego-network and whole-network analyses appropriately, work with affiliation data, multiplexity, and tie-strength measures, visualize networks with layout literacy, and handle the sampling, missingness, and third-party-privacy.... Use this skill whenever the user asks to create, teach, or deepen training on social, network, analysis, sociological, method, network science, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Trend Analyzer course 02, section 9)
  version: 1.0.0
  category: professional-education
---

# Social Network Analysis: Sociological Method and Data — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **social Network Analysis: Sociological Method and Data** within network and graph theory for trend analysis — mapping and modeling how ideas, content, and behaviors spread through social, information, and platform networks.

Subject scope: Covers the research tradition behind the math: SNA lineage — Moreno's sociometry, the Hawthorne studies, and the Manchester school's situational analysis; network data collection — the boundary-specification problem (who counts as inside the network), roster versus name-generator instruments, position versus relational data, and digital-trace substitutes; ego-network analysis — alters, alter-alter ties, composition and structure measures — as the method when whole networks are unavailable; whole-network survey practice and its attrition problems; two-mode affiliation data (events, groups, hashtags) and projection practice; multiplexity and tie strength — Granovetter's strength construct and its measurement via frequency, intimacy, and duration; sampling hidden populations — snowball and respondent-driven sampling with estimator caveats; software lineage and modern practice — UCINET/NodeXL to Python/R stacks, and Gephi visualization craft including layout choices (ForceAtlas2) and how layouts mislead; documentation and reproducibility for network studies; and relational-data ethics — the third-party privacy problem (non-consenting alters in egos' data).

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
- Newman, Networks (2nd ed.); Barabási, Network Science (free textbook) and Linked; Watts, Six Degrees and Small Worlds
- Easley & Kleinberg, Networks, Crowds, and Markets; Borgatti, Everett & Johnson, Analyzing Social Networks
- classic papers: Granovetter (strength of weak ties), Milgram (small world), Watts & Strogatz, Barabási & Albert, Kempe, Kleinberg & Tardos (influence maximization), Centola & Macy (complex contagion), Vosoughi, Roy & Aral (spread of falsehood)
- cascade and virality research: Cheng et al. (cascade structure prediction), Goel, Watts & Goldstein (anatomy of large-scale diffusion), Watts & Dodds (influentials)
- methodological rigor: Clauset, Shalizi & Newman (power-law fitting), Broido & Clauset (scale-free rarity debate), Shalizi & Thomas on contagion claims, Aral, Muchnik & Sundararajan on influence identification
- tools documentation: NetworkX, igraph, graph-tool, cdlib, Gephi manuals; temporal networks (Holme & Saramäki), multilayer networks (Kivelä et al.)
- applied references: muchatka/multilayer toolkits, graph database docs (Neo4j), and platform engineering blogs on recommendation and graph infrastructure
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
# Social Network Analysis: Sociological Method and Data [— audience/context subtitle]

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
- each absorbed capability (2 in this section) is covered by teaching content AND at least one exercise with evaluation criteria
- exercises have model solutions in full-module mode

### Artifacts
- all gate checklists included and actionable as written
- template structure followed; no placeholder sections

### Quality
- trade-offs stated wherever recommendations are context-dependent
- terminology explained on first use
- reads as practitioner-written, not generic AI advice

## Anti-Patterns

Avoid: confusing co-occurrence or co-engagement with causal spread; claiming power laws or scale-free structure without rigorous fitting and goodness-of-fit testing; treating platform follow-graphs as complete social graphs despite API sampling bias; running influence maximization theory as if platform algorithmic curation did not intervene; computing centrality on partial graphs and ranking 'influencers' without fake-engagement checks; static network metrics answering dynamic questions, and homophily mistaken for influence; exercises without evaluation criteria; modules that stop at inspiration without a single decision the learner can now make better; and any content that overstates certainty beyond what the evidence supports.

## Decision Heuristic

When allocating depth under time or length limits, ask:

1. Where will this audience actually stall in practice?
2. Which unit protects the most value if taught well?
3. Can the learner run the framework tomorrow without me?
4. Is every example doing work a plain sentence could not?
5. What would a skeptical domain expert say about this material?

If two topics compete for space, keep the one that changes a decision.

## Final Principle

The goal is not more content about network science. The goal is that a practitioner could take this material and perform: Design network data collection with boundary specification and instrument choice, conduct ego-network and whole-network analyses appropriately, work with affiliation data, multiplexity, and tie-strength measures, visualize networks with layout literacy, and handle the sampling, missingness, and third-party-privacy issues specific to relational data — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
