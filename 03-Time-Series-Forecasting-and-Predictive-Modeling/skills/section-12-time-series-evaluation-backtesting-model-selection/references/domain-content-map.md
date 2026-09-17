# Domain Content Map — Evaluation, Backtesting, and Model Selection

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Design rolling-origin backtests with appropriate windows and cut-offs.
2. Select and compute point and probabilistic metrics (MASE, pinball, coverage) matched to decision needs.
3. Apply benchmark ladders and statistical comparison tests for model selection.
4. Build and weight forecast ensembles.
5. Diagnose error patterns by horizon and regime, and report backtested skill honestly against multiple-comparison inflation.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Instills the measurement rigor that separates forecasters from curve-fitters: evaluation philosophy — only out-of-sample performance counts, and the temporal ordering constraint on all splits; backtesting schemes — rolling-origin evaluation, expanding versus sliding training windows, multiple cut-offs, and the cost-benefit of scheme richness; point-forecast metrics — MAE, RMSE, MAPE and its zero/infinity pathologies, sMAPE's asymmetries, and MASE as the scale-free default; probabilistic metrics — quantile loss/pinball, CRPS, interval coverage and width; competition evidence — M3, M4, M5 findings on which model classes win under which conditions, and the recurring lesson that simple methods and ensembles dominate; model selection workflows — benchmark ladders (naive/seasonal-naive as the floor every model must beat), statistical comparison tests (DM test, MCS at awareness), and parsimony tie-breaks; ensemble methods — simple averaging robustness, weighted and stacking combinations; error analysis — diagnosing where and why models fail (horizon-dependent bias, regime sensitivity, holiday misses); the multiple-comparison trap — selecting the best of many backtested models inflates apparent skill; reporting standards — metric tables per horizon, uncertainty statements, and reproducibility of the backtest itself.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Instills the measurement rigor that separates forecasters from curve-fitters
- evaluation philosophy — only out-of-sample performance counts, and the temporal ordering constraint on all splits
- backtesting schemes — rolling-origin evaluation, expanding versus sliding training windows, multiple cut-offs, and the cost-benefit of scheme richness
- point-forecast metrics — MAE, RMSE, MAPE and its zero/infinity pathologies, sMAPE's asymmetries, and MASE as the scale-free default
- probabilistic metrics — quantile loss/pinball, CRPS, interval coverage and width
- competition evidence — M3, M4, M5 findings on which model classes win under which conditions, and the recurring lesson that simple methods and ensembles dominate
- model selection workflows — benchmark ladders (naive/seasonal-naive as the floor every model must beat), statistical comparison tests (DM test, MCS at awareness), and parsimony tie-breaks
- ensemble methods — simple averaging robustness, weighted and stacking combinations
- error analysis — diagnosing where and why models fail (horizon-dependent bias, regime sensitivity, holiday misses)
- the multiple-comparison trap — selecting the best of many backtested models inflates apparent skill
- reporting standards — metric tables per horizon, uncertainty statements, and reproducibility of the backtest itself

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
