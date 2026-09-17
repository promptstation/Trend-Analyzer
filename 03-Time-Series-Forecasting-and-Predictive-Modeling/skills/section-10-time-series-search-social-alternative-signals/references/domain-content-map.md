# Domain Content Map — Search, Social, and Alternative Signals: Nowcasting and Leading Indicators

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Construct and stabilize Google Trends and social-volume series knowing their sampling and normalization quirks.
2. Measure lead-lag relationships with cross-correlation and Granger-causality tests interpreted cautiously.
3. Build nowcasting models combining alternative and traditional signals, guard against signal-mining overfitting.
4. Validate leading-indicator claims out-of-sample across periods.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the trend analyst's signature data: Google Trends in depth — how the index is constructed (relative search interest, sampling, geo and category scoping), documented pitfalls (repeated-pull variability, normalization drift, the 2024 changes to data access), and methods for stabilizing series (multiple pulls, related-query expansion, ratio transforms); the nowcasting and prediction literature — Preis-Moat-Stanley's search-volume-predicts-findings pattern, flu nowcasting, economic indicator prediction, and the mixed replication record teaching humility; leading-indicator logic — why search and social volume often precede sales and adoption (intent before action), with lead-lag measurement (cross-correlation functions) and Granger-causality tests interpreted as predictive-lead evidence, not true causation; social-volume signals — tweet/post counts, engagement rates, hashtag frequency — with bot contamination and platform-change discontinuities; combining alternative signals with traditional data — multivariate models and the overfitting risk of signal mining; revision and access realities — APIs deprecating, indices restating; case patterns — detecting emerging topics in search data before mainstream metrics move; and validation culture — every leading-indicator claim requires out-of-sample, multi-period testing.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the trend analyst's signature data
- Google Trends in depth — how the index is constructed (relative search interest, sampling, geo and category scoping), documented pitfalls (repeated-pull variability, normalization drift, the 2024 changes to data access), and methods for stabilizing series (multiple pulls, related-query expansion, ratio transforms)
- the nowcasting and prediction literature — Preis-Moat-Stanley's search-volume-predicts-findings pattern, flu nowcasting, economic indicator prediction, and the mixed replication record teaching humility
- leading-indicator logic — why search and social volume often precede sales and adoption (intent before action), with lead-lag measurement (cross-correlation functions) and Granger-causality tests interpreted as predictive-lead evidence, not true causation
- social-volume signals — tweet/post counts, engagement rates, hashtag frequency — with bot contamination and platform-change discontinuities
- combining alternative signals with traditional data — multivariate models and the overfitting risk of signal mining
- revision and access realities — APIs deprecating, indices restating
- case patterns — detecting emerging topics in search data before mainstream metrics move
- and validation culture — every leading-indicator claim requires out-of-sample, multi-period testing

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
