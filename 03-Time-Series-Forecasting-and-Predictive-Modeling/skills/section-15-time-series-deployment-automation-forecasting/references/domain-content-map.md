# Domain Content Map — Deployment, Automation, and the Forecasting Operations Capstone

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Architect end-to-end forecasting pipelines with feature stores and registries, automate retraining with drift-triggered and champion-challenger policies, monitor degradation via error control charts and coverage drift.
2. Integrate structured analyst judgment with model output.
3. Manage compute cost across model classes, and deliver complete probabilistic trend-forecasting systems classifying fads versus structural trends.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Builds the production system: pipeline architecture — ingestion, prep, feature stores, model training, backtesting, serving, and monitoring as distinct stages with the course's methods mapped into each; automation — scheduled retraining policies (calendar-based versus drift-triggered), model registries, and champion-challenger promotion gated on rolling backtests; drift and degradation monitoring — input-distribution shift, error-metric control charts, coverage drift for probabilistic outputs, and alerting thresholds; MLOps practice for forecasting — experiment tracking, versioned data and models, reproducible backtests, and the small-team stack (Airflow/Prefect-style orchestration, lightweight alternatives); serving patterns — batch forecast generation versus on-demand, storage of forecast distributions, and API/dashboard surfaces for analysts; failure-mode drills — platform API changes, series discontinuities, holiday-calendar shifts, and cold-start series; the human layer — forecast review meetings, override logging, and combining model output with analyst judgment (the documented value of structured judgmental adjustment); cost management — compute budgets across model classes, caching, and the accuracy-per-dollar frontier; ethics and communication — avoiding false precision in trend reports, stating uncertainty and assumptions; and the capstone — an end-to-end trend-forecasting system: ingest search and social series, prepare and decompose, backtest a benchmark ladder spanning ETS/ARIMA, boosting, deep, and foundation models, detect changepoints and classify fad-versus-structural trajectories with probabilistic forecasts, and operate it with monitoring and retraining.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Builds the production system
- pipeline architecture — ingestion, prep, feature stores, model training, backtesting, serving, and monitoring as distinct stages with the course's methods mapped into each
- automation — scheduled retraining policies (calendar-based versus drift-triggered), model registries, and champion-challenger promotion gated on rolling backtests
- drift and degradation monitoring — input-distribution shift, error-metric control charts, coverage drift for probabilistic outputs, and alerting thresholds
- MLOps practice for forecasting — experiment tracking, versioned data and models, reproducible backtests, and the small-team stack (Airflow/Prefect-style orchestration, lightweight alternatives)
- serving patterns — batch forecast generation versus on-demand, storage of forecast distributions, and API/dashboard surfaces for analysts
- failure-mode drills — platform API changes, series discontinuities, holiday-calendar shifts, and cold-start series
- the human layer — forecast review meetings, override logging, and combining model output with analyst judgment (the documented value of structured judgmental adjustment)
- cost management — compute budgets across model classes, caching, and the accuracy-per-dollar frontier
- ethics and communication — avoiding false precision in trend reports, stating uncertainty and assumptions
- and the capstone — an end-to-end trend-forecasting system: ingest search and social series, prepare and decompose, backtest a benchmark ladder spanning ETS/ARIMA, boosting, deep, and foundation models, detect changepoints and classify fad-versus-structural trajectories with probabilistic forecasts, and operate it with monitoring and retraining

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
