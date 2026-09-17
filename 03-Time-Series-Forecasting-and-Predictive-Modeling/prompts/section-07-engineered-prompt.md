# STEP 2 — Engineered Prompt for Section 7 (Time-Series Forecasting & Predictive Modeling)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 7 of
the Time-Series Forecasting & Predictive Modeling curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Machine Learning Forecasting: Ensembles and Global Models”** as a core intermediate stage of a curriculum in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. Teach the ML turn: tabularizing time series — supervised-learning transformation with lag windows, rolling features, and multi-horizon strategies (direct, recursive, multi-output) and their error-accumulation trade-offs; gradient boosting for forecasting — XGBoost/LightGBM/CatBoost configured for temporal data, feature importance reading, and the M4/M5 evidence that boosted trees are extremely strong, often winning competitions with modest tuning; random forests and the broader ensemble picture at working level; global versus local models — training one model across many related series (cross-learning) versus per-series fits, with evidence that global models win at scale; cross-validation for time series — rolling-origin, expanding and sliding windows, purged/embargoed splits for leakage control, and why random K-fold is a category error; hyperparameter search under temporal validation; feature engineering at ML depth — calendar, lags, rolling statistics, exogenous signals, and NLP-derived features from text streams; handling many series and cold starts with shared models; interpretability — SHAP values for temporal features and their caveats; and the accuracy-effort frontier — where ML's gains over ETS/ARIMA are real versus marginal per competition evidence. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to convert series to supervised tabular problems with direct/recursive/multi-output strategies, train and tune gradient-boosting forecasters with temporal feature sets.

* Teach how to implement rolling-origin and purged cross-validation, exploit global cross-series learning and cold-start handling.

* Teach how to read SHAP-based explanations of temporal feature importance critically.

Use numerous realistic examples throughout the module, drawn from professional practice in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Convert series to supervised tabular problems with direct/recursive/multi-output strategies, train and tune gradient-boosting forecasters with temporal feature sets, applied to a realistic scenario provided with the exercise.

2. Implement rolling-origin and purged cross-validation, exploit global cross-series learning and cold-start handling, applied to a realistic scenario provided with the exercise.

3. Read SHAP-based explanations of temporal feature importance critically, applied to a realistic scenario provided with the exercise.

4. Integrate the full section: take one realistic problem in Time-series forecasting through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Hyndman & Athanasopoulos, Forecasting: Principles and Practice (OTexts, open edition); Chatfield, The Analysis of Time Series: An Introduction (Chapman & Hall/CRC); Shumway & Stoffer, Time Series Analysis and Its Applications (Springer open text); Makridakis, Spiliotis & Assimakopoulos, M-competition findings on statistical vs ML vs deep-learning forecast accuracy; Taylor & Letham, Facebook Prophet documentation and paper; Amazon, Google, and Nixtla documentation and papers for DeepAR, TimesFM, Chronos, and TimeGPT foundation models; Google Trends official documentation and the nowcasting literature (e.g., Preis, Moat & Stanley on search-volume prediction). Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a convert-series-to-supervised checklist, a implement-rolling-origin-and checklist, a read-shap-based-explanations checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
