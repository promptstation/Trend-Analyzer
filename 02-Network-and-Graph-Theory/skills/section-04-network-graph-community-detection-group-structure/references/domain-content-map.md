# Domain Content Map — Community Detection and Group Structure

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Apply Louvain/Leiden, Infomap, and label propagation with understanding of each objective.
2. Interpret modularity with resolution-limit awareness.
3. Validate communities through stability testing and qualitative reading, track community evolution over time as a trend signal.
4. Distinguish algorithmic partitions from social phenomena like scenes and echo chambers.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Teaches finding the tribes inside networks: the community concept and its definitional ambiguity — no single ground truth; modularity defined, optimized, and its resolution limit (small communities invisible at scale); algorithms in working depth — Girvan-Newman divisive betweenness, Louvain and Leiden aggregation (including Leiden's fix for badly-connected Louvain output), label propagation, and Infomap's flow/map-equation objective; overlapping communities and fuzzy membership at overview (link communities, bigCLAM lineage); hierarchical structure — dendrograms and multi-resolution partitions; validation without ground truth — internal metrics, perturbation stability, and qualitative reading of community content; interpretation discipline — algorithmic communities are not automatically scenes, echo chambers, or markets; structural equivalence and blockmodels at overview as role analysis distinct from community membership; community evolution in dynamic networks — growth, merge, split, death tracking as a trend-detection instrument; practical workflows in igraph/leidenalg/cdlib and Gephi; and common failure modes — resolution artifacts, singleton absorption, and over-interpreting unstable partitions.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Teaches finding the tribes inside networks
- the community concept and its definitional ambiguity — no single ground truth
- modularity defined, optimized, and its resolution limit (small communities invisible at scale)
- algorithms in working depth — Girvan-Newman divisive betweenness, Louvain and Leiden aggregation (including Leiden's fix for badly-connected Louvain output), label propagation, and Infomap's flow/map-equation objective
- overlapping communities and fuzzy membership at overview (link communities, bigCLAM lineage)
- hierarchical structure — dendrograms and multi-resolution partitions
- validation without ground truth — internal metrics, perturbation stability, and qualitative reading of community content
- interpretation discipline — algorithmic communities are not automatically scenes, echo chambers, or markets
- structural equivalence and blockmodels at overview as role analysis distinct from community membership
- community evolution in dynamic networks — growth, merge, split, death tracking as a trend-detection instrument
- practical workflows in igraph/leidenalg/cdlib and Gephi
- and common failure modes — resolution artifacts, singleton absorption, and over-interpreting unstable partitions

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in network science practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in network science through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
