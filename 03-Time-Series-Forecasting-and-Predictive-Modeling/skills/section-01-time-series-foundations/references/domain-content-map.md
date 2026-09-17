# Domain Content Map — Foundations: Time Series, Components, and the Fad-Versus-Trend Question

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Frame trend questions as component-decomposition and forecast problems.
2. Articulate the operational difference between transient fads and structural trends.
3. Select measurement sources and series granularity with awareness of normalization and sampling quirks.
4. Apply differencing and transformations to reach workable stationarity.
5. Set forecast horizons matched to decision needs.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Introduces the field and its central trend-analysis mission: time series defined — ordered observations of a measured quantity, with the distinction between the data-generating process and its sampled trace; the component framework — level, trend, seasonality, cycles, and irregular noise — with additive versus multiplicative decomposition intuition; stationarity defined and why so many methods assume it (constant mean and autocorrelation structure), with differencing and transformation as remedies; the course's orienting problem stated precisely — a fad is a transient level shift or short-lived growth impulse that reverts, while a structural trend is persistent growth with regime-level support, and distinguishing them requires models that separate signal components and quantify uncertainty; measurement sources for trend series — search indices (Google Trends), social volume counts, sales and demand data, app analytics — each with its own normalization, sampling, and revision quirks; frequency and granularity choices (hourly to yearly) and the aliasing/aggregation trade-off; forecasting horizons — nowcasting, short-, medium-, long-range — and why difficulty scales with horizon; evaluation culture preview (out-of-sample only); and the course map from data preparation through classical, ML, and deep models to changepoint detection, lifecycle classification, and deployment.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Introduces the field and its central trend-analysis mission
- time series defined — ordered observations of a measured quantity, with the distinction between the data-generating process and its sampled trace
- the component framework — level, trend, seasonality, cycles, and irregular noise — with additive versus multiplicative decomposition intuition
- stationarity defined and why so many methods assume it (constant mean and autocorrelation structure), with differencing and transformation as remedies
- the course's orienting problem stated precisely — a fad is a transient level shift or short-lived growth impulse that reverts, while a structural trend is persistent growth with regime-level support, and distinguishing them requires models that separate signal components and quantify uncertainty
- measurement sources for trend series — search indices (Google Trends), social volume counts, sales and demand data, app analytics — each with its own normalization, sampling, and revision quirks
- frequency and granularity choices (hourly to yearly) and the aliasing/aggregation trade-off
- forecasting horizons — nowcasting, short-, medium-, long-range — and why difficulty scales with horizon
- evaluation culture preview (out-of-sample only)
- and the course map from data preparation through classical, ML, and deep models to changepoint detection, lifecycle classification, and deployment

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
