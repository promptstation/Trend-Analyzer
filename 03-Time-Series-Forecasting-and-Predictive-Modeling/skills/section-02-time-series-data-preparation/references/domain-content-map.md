# Domain Content Map — Data Preparation for Time Series

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Build leakage-proof ingestion and resampling pipelines.
2. Detect and treat outliers and missing data by mechanism rather than reflex, engineer calendar and holiday features.
3. Apply variance-stabilizing transformations with back-transformation awareness.
4. Prepare search-index and social-volume series handling their normalization and sampling peculiarities.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Builds the preprocessing discipline that determines everything downstream: ingestion and alignment — timestamps, time zones, irregular sampling, and resampling/aggregation (sum versus mean versus last) with the semantic care each requires; missing data — mechanisms (MCAR versus informative gaps), interpolation and imputation methods, and when missingness is itself signal; outliers and anomalies — spikes, level shifts, and data errors distinguished, with robust detection (rolling statistics, STL residuals) and principled treatment (winsorizing, indicator flags, robust models) rather than silent deletion; calendar features — day-of-week, month, holidays across regions, leap years, business-day effects — and their confounding with genuine trend shifts; transformations — log and Box-Cox for variance stabilization, the multiplicative-versus-additive choice, and back-transformation bias awareness; Google Trends–specific preparation — index normalization (0–100 relative scaling), the query-mix and geographic-scope choices that change results, sampling variability across pulls, and combining related terms; data versioning and the revision problem (sources that restate history); and building reproducible prep pipelines with leakage-proofing — no future information in any transformation fitted on training windows.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Builds the preprocessing discipline that determines everything downstream
- ingestion and alignment — timestamps, time zones, irregular sampling, and resampling/aggregation (sum versus mean versus last) with the semantic care each requires
- missing data — mechanisms (MCAR versus informative gaps), interpolation and imputation methods, and when missingness is itself signal
- outliers and anomalies — spikes, level shifts, and data errors distinguished, with robust detection (rolling statistics, STL residuals) and principled treatment (winsorizing, indicator flags, robust models) rather than silent deletion
- calendar features — day-of-week, month, holidays across regions, leap years, business-day effects — and their confounding with genuine trend shifts
- transformations — log and Box-Cox for variance stabilization, the multiplicative-versus-additive choice, and back-transformation bias awareness
- Google Trends–specific preparation — index normalization (0–100 relative scaling), the query-mix and geographic-scope choices that change results, sampling variability across pulls, and combining related terms
- data versioning and the revision problem (sources that restate history)
- and building reproducible prep pipelines with leakage-proofing — no future information in any transformation fitted on training windows

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
