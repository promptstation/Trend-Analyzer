# Domain Content Map — Centrality: Position, Brokerage, and Influence

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Compute degree, betweenness, closeness, eigenvector, and PageRank centralities and state what question each answers.
2. Interpret disagreement among centrality measures on real networks.
3. Evaluate influence claims using spreadability-versus-position evidence, rank nodes for monitoring versus seeding with sampling awareness, and avoid centrality misuse on incomplete or manipulated platform graphs.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the most-used and most-abused toolkit: degree centrality with its directed split (in-degree as prestige, out-degree as expansiveness); betweenness centrality as brokerage measurement, closeness as independence-from-others, and their instability on sampled or incomplete graphs; eigenvector family — eigenvector centrality, Katz, PageRank with its damping parameter and search-engine history, and HITS hubs-and-authorities; the central lesson that centrality is a hypothesis family, not a single number — each measure answers a different question about position (reach, control, prestige) and they measurably disagree; weighted, temporal, and local variants at overview; the influence-identification literature — whether central nodes actually spread more (degree often suffices per Kempe-lineage results; the spreaders-versus-susceptibles distinction; retweet-influence studies showing retweetability is content-driven); practical influence ranking for trend work — who to monitor and who to seed, and why the answers differ; and the pitfalls — centrality computed on API-partial graphs, follower counts as manipulable signals, and verified-account confounds.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the most-used and most-abused toolkit
- degree centrality with its directed split (in-degree as prestige, out-degree as expansiveness)
- betweenness centrality as brokerage measurement, closeness as independence-from-others, and their instability on sampled or incomplete graphs
- eigenvector family — eigenvector centrality, Katz, PageRank with its damping parameter and search-engine history, and HITS hubs-and-authorities
- the central lesson that centrality is a hypothesis family, not a single number — each measure answers a different question about position (reach, control, prestige) and they measurably disagree
- weighted, temporal, and local variants at overview
- the influence-identification literature — whether central nodes actually spread more (degree often suffices per Kempe-lineage results
- the spreaders-versus-susceptibles distinction
- retweet-influence studies showing retweetability is content-driven)
- practical influence ranking for trend work — who to monitor and who to seed, and why the answers differ
- and the pitfalls — centrality computed on API-partial graphs, follower counts as manipulable signals, and verified-account confounds

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in network science practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in network science through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
