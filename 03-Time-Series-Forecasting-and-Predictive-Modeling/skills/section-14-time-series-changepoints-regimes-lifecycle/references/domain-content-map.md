# Domain Content Map — Changepoints, Regimes, and Lifecycle Classification: Fads Versus Structural Trends

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Detect and classify changepoints (level, slope, volatility) with PELT, CUSUM, and Bayesian online methods, attribute shifts to interventions via counterfactual analysis, fit logistic and Bass lifecycle curves to estimate saturation and inflection.
2. Apply fad-diagnostic signatures (reversion speed, structural support) versus durable-growth evidence.
3. Operate regime-switching models and re-estimation triggers for non-stationary series.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Tackles the course's namesake problem directly: changepoint detection — the CUSUM and PELT algorithms, Bayesian online changepoint detection for streaming series, binary segmentation, and the penalty-selection problem (BIC-style versus validated); distinguishing changepoint types — level shifts, trend-slope changes, and volatility shifts — each with different trend interpretations; intervention analysis — CausalImpact-style counterfactuals to attribute shifts to known events versus unexplained regime change; growth-curve and lifecycle models — logistic and Bass diffusion curves for adoption S-shapes, fitting saturation points and inflection timing, Gompertz variants, and the classic product-lifecycle shapes; fad diagnostics — impulse-response patterns, reversion speed after peaks, and the empirical signatures distinguishing viral spikes (sharp rise, fast decay, low structural support) from durable growth (sustained slope, cohort retention, cross-signal confirmation); regime-switching models — Markov-switching and hidden-Markov approaches at working level for series that alternate behaviors; unit-root versus trend-stationarity — why the distinction changes long-horizon forecasts fundamentally, with tests; combining detection with forecasting — re-estimation triggers after detected changepoints; multi-signal triangulation — confirming structural trends across search, social, sales, and network signals; and the classification deliverable — a fad-versus-trend scorecard with evidence standards.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Tackles the course's namesake problem directly
- changepoint detection — the CUSUM and PELT algorithms, Bayesian online changepoint detection for streaming series, binary segmentation, and the penalty-selection problem (BIC-style versus validated)
- distinguishing changepoint types — level shifts, trend-slope changes, and volatility shifts — each with different trend interpretations
- intervention analysis — CausalImpact-style counterfactuals to attribute shifts to known events versus unexplained regime change
- growth-curve and lifecycle models — logistic and Bass diffusion curves for adoption S-shapes, fitting saturation points and inflection timing, Gompertz variants, and the classic product-lifecycle shapes
- fad diagnostics — impulse-response patterns, reversion speed after peaks, and the empirical signatures distinguishing viral spikes (sharp rise, fast decay, low structural support) from durable growth (sustained slope, cohort retention, cross-signal confirmation)
- regime-switching models — Markov-switching and hidden-Markov approaches at working level for series that alternate behaviors
- unit-root versus trend-stationarity — why the distinction changes long-horizon forecasts fundamentally, with tests
- combining detection with forecasting — re-estimation triggers after detected changepoints
- multi-signal triangulation — confirming structural trends across search, social, sales, and network signals
- and the classification deliverable — a fad-versus-trend scorecard with evidence standards

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
