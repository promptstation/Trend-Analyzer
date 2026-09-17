# Domain Content Map — Exponential Smoothing and ARIMA Family

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Fit and forecast with ETS/Holt-Winters and ARIMA/SARIMA/SARIMAX models.
2. Execute Box-Jenkins identification with unit-root tests and residual diagnostics.
3. Use auto-tuning search strategies effectively.
4. Interpret the forecast functions implied by each model component, and deploy classical methods as rigorous baselines with awareness of their interval fragility.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Teaches the classical statistical core in working depth: exponential smoothing — simple, Holt's linear-trend, and Holt-Winters seasonal methods, the error-trend-seasonality (ETS) taxonomy, and state-space interpretation with automatic model selection (Hyndman-Khandakar-style algorithms); ARIMA — AR, I, and MA components explained, the Box-Jenkins identification workflow (ACF/PACF-informed orders), differencing for stationarity with unit-root tests (ADF, KPSS) and their disagreement handling, estimation and diagnostics, and the forecast functions each component implies; SARIMA — seasonal differencing and seasonal orders, with the practical limits on long seasonal periods; SARIMAX — adding exogenous regressors; auto-tuning practice — auto-ARIMA search strategies, stepwise versus exhaustive, and why automatic beats eyeballed in benchmarks; model diagnostics — residual whiteness tests (Ljung-Box), residual ACF inspection, and overfitting signs; the Hyndman-Athanasopoulos framing of ETS and ARIMA as overlapping-but-distinct model classes with a mapping between some members; forecast-interval construction under normal-error assumptions and its fragility; and position in the modern stack — strong baselines that deep models must beat per M-competition evidence.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Teaches the classical statistical core in working depth
- exponential smoothing — simple, Holt's linear-trend, and Holt-Winters seasonal methods, the error-trend-seasonality (ETS) taxonomy, and state-space interpretation with automatic model selection (Hyndman-Khandakar-style algorithms)
- ARIMA — AR, I, and MA components explained, the Box-Jenkins identification workflow (ACF/PACF-informed orders), differencing for stationarity with unit-root tests (ADF, KPSS) and their disagreement handling, estimation and diagnostics, and the forecast functions each component implies
- SARIMA — seasonal differencing and seasonal orders, with the practical limits on long seasonal periods
- SARIMAX — adding exogenous regressors
- auto-tuning practice — auto-ARIMA search strategies, stepwise versus exhaustive, and why automatic beats eyeballed in benchmarks
- model diagnostics — residual whiteness tests (Ljung-Box), residual ACF inspection, and overfitting signs
- the Hyndman-Athanasopoulos framing of ETS and ARIMA as overlapping-but-distinct model classes with a mapping between some members
- forecast-interval construction under normal-error assumptions and its fragility
- and position in the modern stack — strong baselines that deep models must beat per M-competition evidence

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
