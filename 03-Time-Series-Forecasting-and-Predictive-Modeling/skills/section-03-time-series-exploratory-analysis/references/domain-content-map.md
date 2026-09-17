# Domain Content Map — Exploratory Time-Series Analysis and Decomposition

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Diagnose series structure with seasonal subseries, lag, and ACF analysis.
2. Apply STL and classical decomposition and interpret component strengths.
3. Extract trends with moving-average and loess methods knowing their endpoint biases.
4. Detect evolving and multiple seasonalities.
5. Translate exploratory diagnostics into defensible model-class choices.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Teaches seeing structure before modeling: visual diagnostics — line plots, seasonal subseries plots, lag plots, and month/week heatmaps that expose patterns summary statistics hide; autocorrelation analysis — the ACF defined and computed, interpreting decay shapes, partial autocorrelation at working level, and what ACF patterns suggest about AR, MA, seasonal, and unit-root behavior; decomposition methods — classical additive/multiplicative decomposition and its limitations, STL (loess-based, robust to evolving seasonality and outliers) in depth, X-11/X-13 lineage for official statistics, and MSTL for multiple seasonalities; trend extraction choices — moving averages, Hodrick-Pfilter critique (endpoint bias), and loess smoothing with bandwidth selection; seasonality diagnosis — strength measures, changing seasonal shape over time, and multiple seasonal periods in high-frequency data; frequency-domain analysis — periodograms and spectral peaks at awareness level; changepoints previewed — eyeballing versus formal detection (formalized later); EDA-to-model handoff — what each diagnostic implies for model class choice; and documentation practice — turning EDA into modeling decisions with recorded rationale.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Teaches seeing structure before modeling
- visual diagnostics — line plots, seasonal subseries plots, lag plots, and month/week heatmaps that expose patterns summary statistics hide
- autocorrelation analysis — the ACF defined and computed, interpreting decay shapes, partial autocorrelation at working level, and what ACF patterns suggest about AR, MA, seasonal, and unit-root behavior
- decomposition methods — classical additive/multiplicative decomposition and its limitations, STL (loess-based, robust to evolving seasonality and outliers) in depth, X-11/X-13 lineage for official statistics, and MSTL for multiple seasonalities
- trend extraction choices — moving averages, Hodrick-Pfilter critique (endpoint bias), and loess smoothing with bandwidth selection
- seasonality diagnosis — strength measures, changing seasonal shape over time, and multiple seasonal periods in high-frequency data
- frequency-domain analysis — periodograms and spectral peaks at awareness level
- changepoints previewed — eyeballing versus formal detection (formalized later)
- EDA-to-model handoff — what each diagnostic implies for model class choice
- and documentation practice — turning EDA into modeling decisions with recorded rationale

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
