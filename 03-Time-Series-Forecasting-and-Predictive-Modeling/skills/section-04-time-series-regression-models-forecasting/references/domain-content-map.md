# Domain Content Map — Regression Models for Forecasting

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Build forecasting regressions with lags, trend, seasonal dummies, and Fourier terms, incorporate exogenous covariates with forecastability constraints.
2. Diagnose and correct serially correlated residuals, regularize and select lag features disciplined against leakage, and fit count-data GLMs for volume series.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the workhorse foundation: linear regression reviewed with forecasting orientation — assumptions, interpretation, and why they fail gracefully or catastrophically on time-ordered data; time-series regressors — lagged dependent variables (autoregressive structure), trend terms (linear, polynomial and their extrapolation dangers), seasonal dummies and Fourier terms for flexible periodicity; exogenous regressors — incorporating covariates (promotions, weather, economic indicators, other series) with lead-lag alignment and the strict requirement that regressors be known or forecastable at prediction time; the autocorrelated-residuals problem — why OLS inference breaks under serial correlation, Durbin-Watson and residual ACF checks, and Newey-West-style corrections at overview; regularization — ridge and lasso for many-lag and many-covariate settings, and lag selection discipline; feature engineering from time itself at depth — rolling statistics, differences, Fourier features, holiday distances; generalized linear models for count series (Poisson/negative-binomial regression for social-volume counts); regression versus dedicated time-series models — when each wins; and the leakage audit specific to regression forecasting — scaling, imputation, and lag construction across train/test boundaries.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the workhorse foundation
- linear regression reviewed with forecasting orientation — assumptions, interpretation, and why they fail gracefully or catastrophically on time-ordered data
- time-series regressors — lagged dependent variables (autoregressive structure), trend terms (linear, polynomial and their extrapolation dangers), seasonal dummies and Fourier terms for flexible periodicity
- exogenous regressors — incorporating covariates (promotions, weather, economic indicators, other series) with lead-lag alignment and the strict requirement that regressors be known or forecastable at prediction time
- the autocorrelated-residuals problem — why OLS inference breaks under serial correlation, Durbin-Watson and residual ACF checks, and Newey-West-style corrections at overview
- regularization — ridge and lasso for many-lag and many-covariate settings, and lag selection discipline
- feature engineering from time itself at depth — rolling statistics, differences, Fourier features, holiday distances
- generalized linear models for count series (Poisson/negative-binomial regression for social-volume counts)
- regression versus dedicated time-series models — when each wins
- and the leakage audit specific to regression forecasting — scaling, imputation, and lag construction across train/test boundaries

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
