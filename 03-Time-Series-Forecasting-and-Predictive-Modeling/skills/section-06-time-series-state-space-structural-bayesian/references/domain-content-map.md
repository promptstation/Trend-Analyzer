# Domain Content Map — State-Space, Structural, and Bayesian Time-Series Models

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Apply state-space and structural time-series models with Kalman filtering intuition.
2. Run Bayesian structural time-series and CausalImpact analyses to estimate intervention effects and counterfactuals.
3. Configure and critically tune Prophet including changepoint behavior, reconcile hierarchical forecasts across aggregation levels.
4. Select statistical model families by interpretability and data conditions.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the modern statistical layer: state-space formulation — latent states, observation equations, and the Kalman filter/smoother as the computational engine, with intuition for filtering versus smoothing and missing-data handling for free; structural time-series models — local level, local linear trend with damped slopes, and seasonal components as interpretable building blocks; Bayesian structural time series (Scott-Varian lineage) and Google's CausalImpact for intervention analysis — estimating what would have happened without a campaign or event, the trend analyst's counterfactual tool; Prophet in depth — its additive decomposition of piecewise-linear/logistic trends, changepoint priors, holiday effects, uncertainty intervals via simulation, practical tuning, and documented failure modes; dynamic linear models and time-varying coefficients at overview; hierarchical and grouped forecasting — reconciliation across product/category/total series (MinT-style methods) so levels agree; Bayesian computation for time series — priors on trend and seasonality, posterior predictive checks, and when full Bayes is worth its cost; damped-trend methods as the empirically robust default for long horizons; and choosing within the statistical family by interpretability, data volume, and intervention-analysis needs.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the modern statistical layer
- state-space formulation — latent states, observation equations, and the Kalman filter/smoother as the computational engine, with intuition for filtering versus smoothing and missing-data handling for free
- structural time-series models — local level, local linear trend with damped slopes, and seasonal components as interpretable building blocks
- Bayesian structural time series (Scott-Varian lineage) and Google's CausalImpact for intervention analysis — estimating what would have happened without a campaign or event, the trend analyst's counterfactual tool
- Prophet in depth — its additive decomposition of piecewise-linear/logistic trends, changepoint priors, holiday effects, uncertainty intervals via simulation, practical tuning, and documented failure modes
- dynamic linear models and time-varying coefficients at overview
- hierarchical and grouped forecasting — reconciliation across product/category/total series (MinT-style methods) so levels agree
- Bayesian computation for time series — priors on trend and seasonality, posterior predictive checks, and when full Bayes is worth its cost
- damped-trend methods as the empirically robust default for long horizons
- and choosing within the statistical family by interpretability, data volume, and intervention-analysis needs

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
