# Domain Content Map — Machine Learning Forecasting: Ensembles and Global Models

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Convert series to supervised tabular problems with direct/recursive/multi-output strategies, train and tune gradient-boosting forecasters with temporal feature sets.
2. Implement rolling-origin and purged cross-validation, exploit global cross-series learning and cold-start handling.
3. Read SHAP-based explanations of temporal feature importance critically.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Teaches the ML turn: tabularizing time series — supervised-learning transformation with lag windows, rolling features, and multi-horizon strategies (direct, recursive, multi-output) and their error-accumulation trade-offs; gradient boosting for forecasting — XGBoost/LightGBM/CatBoost configured for temporal data, feature importance reading, and the M4/M5 evidence that boosted trees are extremely strong, often winning competitions with modest tuning; random forests and the broader ensemble picture at working level; global versus local models — training one model across many related series (cross-learning) versus per-series fits, with evidence that global models win at scale; cross-validation for time series — rolling-origin, expanding and sliding windows, purged/embargoed splits for leakage control, and why random K-fold is a category error; hyperparameter search under temporal validation; feature engineering at ML depth — calendar, lags, rolling statistics, exogenous signals, and NLP-derived features from text streams; handling many series and cold starts with shared models; interpretability — SHAP values for temporal features and their caveats; and the accuracy-effort frontier — where ML's gains over ETS/ARIMA are real versus marginal per competition evidence.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Teaches the ML turn
- tabularizing time series — supervised-learning transformation with lag windows, rolling features, and multi-horizon strategies (direct, recursive, multi-output) and their error-accumulation trade-offs
- gradient boosting for forecasting — XGBoost/LightGBM/CatBoost configured for temporal data, feature importance reading, and the M4/M5 evidence that boosted trees are extremely strong, often winning competitions with modest tuning
- random forests and the broader ensemble picture at working level
- global versus local models — training one model across many related series (cross-learning) versus per-series fits, with evidence that global models win at scale
- cross-validation for time series — rolling-origin, expanding and sliding windows, purged/embargoed splits for leakage control, and why random K-fold is a category error
- hyperparameter search under temporal validation
- feature engineering at ML depth — calendar, lags, rolling statistics, exogenous signals, and NLP-derived features from text streams
- handling many series and cold starts with shared models
- interpretability — SHAP values for temporal features and their caveats
- and the accuracy-effort frontier — where ML's gains over ETS/ARIMA are real versus marginal per competition evidence

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
