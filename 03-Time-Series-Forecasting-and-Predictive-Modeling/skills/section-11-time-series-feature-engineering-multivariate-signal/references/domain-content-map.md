# Domain Content Map — Feature Engineering and Multivariate Signal Integration

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Engineer autoregressive, calendar, cross-series, and text-derived features with lag-selection discipline.
2. Classify exogenous variables by forecast-time availability and match them to model capabilities.
3. Apply VAR and cointegration thinking to jointly evolving series.
4. Manage feature dimensionality and drift.
5. Integrate NLP and network signals as forecast covariates.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Deepens the input side: the feature taxonomy for forecasting — autoregressive (lags, differences, rolling stats), calendar/temporal, exogenous covariates, cross-series features (aggregates, ratios, relative strength), and derived text features (sentiment scores, topic proportions, entity counts from NLP pipelines); lag selection — cross-correlation-guided choices, mutual information, and the bias-variance of long lag windows; exogenous variable discipline — classification by availability at forecast time (known-future like holidays, forecastable like weather, unavailable like realized sales) and matching model support (SARIMAX, Prophet regressors, DeepAR covariates); multivariate and vector approaches — VAR models and their modern ML rivals for jointly evolving series (search volume plus sales plus sentiment); cointegration and error-correction at awareness — long-run equilibrium relationships between series; dimensionality management — PCA on related series, regularization for wide feature sets; interaction and nonlinearity capture — where trees and deep models absorb engineering that linear models need by hand; feature drift — monitoring input distributions as series regimes change; documentation — feature dictionaries tying each feature to its hypothesis; and the integration blueprint — wiring course-1 NLP outputs and course-2 network metrics as covariates into forecast models.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Deepens the input side
- the feature taxonomy for forecasting — autoregressive (lags, differences, rolling stats), calendar/temporal, exogenous covariates, cross-series features (aggregates, ratios, relative strength), and derived text features (sentiment scores, topic proportions, entity counts from NLP pipelines)
- lag selection — cross-correlation-guided choices, mutual information, and the bias-variance of long lag windows
- exogenous variable discipline — classification by availability at forecast time (known-future like holidays, forecastable like weather, unavailable like realized sales) and matching model support (SARIMAX, Prophet regressors, DeepAR covariates)
- multivariate and vector approaches — VAR models and their modern ML rivals for jointly evolving series (search volume plus sales plus sentiment)
- cointegration and error-correction at awareness — long-run equilibrium relationships between series
- dimensionality management — PCA on related series, regularization for wide feature sets
- interaction and nonlinearity capture — where trees and deep models absorb engineering that linear models need by hand
- feature drift — monitoring input distributions as series regimes change
- documentation — feature dictionaries tying each feature to its hypothesis
- and the integration blueprint — wiring course-1 NLP outputs and course-2 network metrics as covariates into forecast models

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
