# Domain Content Map — Uncertainty Quantification and Probabilistic Forecasting

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Produce calibrated probabilistic forecasts via simulation, quantile, and distributional model outputs.
2. Implement conformal prediction wrappers with temporal adaptation.
3. Diagnose interval coverage and sharpness with calibration plots.
4. Build scenario analyses around structural assumptions.
5. Communicate forecast uncertainty in decision-ready fan charts and probability language.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Teaches forecasting as distributions, not numbers: why uncertainty matters for trend decisions — the difference between "growing" and "growing with 80% probability," and risk-calibrated action; sources of forecast uncertainty — parameter, model, and future-shock components; classical intervals — ARIMA and ETS analytic intervals, their normality assumptions, and empirical coverage failure at longer horizons; simulation approaches — bootstrapping residuals, Prophet's trend-uncertainty simulation; probabilistic model outputs — quantile regression, DeepAR's parametric likelihoods, and distributional forecasts from foundation models; conformal prediction — distribution-free interval calibration with temporal-adaptive variants (ACI), implemented as a wrapper over any point forecaster; ensembles as uncertainty — spread across model families as epistemic signal, and mixture-density approaches; scenario analysis — combining forecasts with structural assumptions (what if the platform changes, what if a competitor launches); communicating uncertainty — fan charts, interval tables, and language discipline (probability statements versus hedges); calibration diagnostics — coverage checks, PIT/quantile calibration plots, and interval sharpness trade-offs; and decision integration — expected-value and regret framings for acting on probabilistic trend forecasts.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Teaches forecasting as distributions, not numbers
- why uncertainty matters for trend decisions — the difference between "growing" and "growing with 80% probability," and risk-calibrated action
- sources of forecast uncertainty — parameter, model, and future-shock components
- classical intervals — ARIMA and ETS analytic intervals, their normality assumptions, and empirical coverage failure at longer horizons
- simulation approaches — bootstrapping residuals, Prophet's trend-uncertainty simulation
- probabilistic model outputs — quantile regression, DeepAR's parametric likelihoods, and distributional forecasts from foundation models
- conformal prediction — distribution-free interval calibration with temporal-adaptive variants (ACI), implemented as a wrapper over any point forecaster
- ensembles as uncertainty — spread across model families as epistemic signal, and mixture-density approaches
- scenario analysis — combining forecasts with structural assumptions (what if the platform changes, what if a competitor launches)
- communicating uncertainty — fan charts, interval tables, and language discipline (probability statements versus hedges)
- calibration diagnostics — coverage checks, PIT/quantile calibration plots, and interval sharpness trade-offs
- and decision integration — expected-value and regret framings for acting on probabilistic trend forecasts

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
