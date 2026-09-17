# STEP 2 — Engineered Prompt for Section 12 (Time-Series Forecasting & Predictive Modeling)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 12 of
the Time-Series Forecasting & Predictive Modeling curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Evaluation, Backtesting, and Model Selection”** as a core intermediate stage of a curriculum in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. Cover the following: instills the measurement rigor that separates forecasters from curve-fitters: evaluation philosophy — only out-of-sample performance counts, and the temporal ordering constraint on all splits; backtesting schemes — rolling-origin evaluation, expanding versus sliding training windows, multiple cut-offs, and the cost-benefit of scheme richness; point-forecast metrics — MAE, RMSE, MAPE and its zero/infinity pathologies, sMAPE's asymmetries, and MASE as the scale-free default; probabilistic metrics — quantile loss/pinball, CRPS, interval coverage and width; competition evidence — M3, M4, M5 findings on which model classes win under which conditions, and the recurring lesson that simple methods and ensembles dominate; model selection workflows — benchmark ladders (naive/seasonal-naive as the floor every model must beat), statistical comparison tests (DM test, MCS at awareness), and parsimony tie-breaks; ensemble methods — simple averaging robustness, weighted and stacking combinations; error analysis — diagnosing where and why models fail (horizon-dependent bias, regime sensitivity, holiday misses); the multiple-comparison trap — selecting the best of many backtested models inflates apparent skill; reporting standards — metric tables per horizon, uncertainty statements, and reproducibility of the backtest itself. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to design rolling-origin backtests with appropriate windows and cut-offs.

* Teach how to select and compute point and probabilistic metrics (MASE, pinball, coverage) matched to decision needs.

* Teach how to apply benchmark ladders and statistical comparison tests for model selection.

* Teach how to build and weight forecast ensembles.

* Teach how to diagnose error patterns by horizon and regime, and report backtested skill honestly against multiple-comparison inflation.

Use numerous realistic examples throughout the module, drawn from professional practice in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Design rolling-origin backtests with appropriate windows and cut-offs, applied to a realistic scenario provided with the exercise.

2. Select and compute point and probabilistic metrics (MASE, pinball, coverage) matched to decision needs, applied to a realistic scenario provided with the exercise.

3. Apply benchmark ladders and statistical comparison tests for model selection, applied to a realistic scenario provided with the exercise.

4. Build and weight forecast ensembles, applied to a realistic scenario provided with the exercise.

5. Diagnose error patterns by horizon and regime, and report backtested skill honestly against multiple-comparison inflation, applied to a realistic scenario provided with the exercise.

6. Integrate the full section: take one realistic problem in Time-series forecasting through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Hyndman & Athanasopoulos, Forecasting: Principles and Practice (OTexts, open edition); Chatfield, The Analysis of Time Series: An Introduction (Chapman & Hall/CRC); Shumway & Stoffer, Time Series Analysis and Its Applications (Springer open text); Makridakis, Spiliotis & Assimakopoulos, M-competition findings on statistical vs ML vs deep-learning forecast accuracy; Taylor & Letham, Facebook Prophet documentation and paper; Amazon, Google, and Nixtla documentation and papers for DeepAR, TimesFM, Chronos, and TimeGPT foundation models; Google Trends official documentation and the nowcasting literature (e.g., Preis, Moat & Stanley on search-volume prediction). Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a design-rolling-origin-backtests checklist, a select-and-compute-point checklist, a apply-benchmark-ladders-and checklist, a build-and-weight-forecast checklist, a diagnose-error-patterns-by checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
