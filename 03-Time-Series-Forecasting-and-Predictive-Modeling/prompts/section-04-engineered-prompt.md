# STEP 2 — Engineered Prompt for Section 4 (Time-Series Forecasting & Predictive Modeling)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 4 of
the Time-Series Forecasting & Predictive Modeling curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Regression Models for Forecasting”** as a core intermediate stage of a curriculum in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. Cover the workhorse foundation: linear regression reviewed with forecasting orientation — assumptions, interpretation, and why they fail gracefully or catastrophically on time-ordered data; time-series regressors — lagged dependent variables (autoregressive structure), trend terms (linear, polynomial and their extrapolation dangers), seasonal dummies and Fourier terms for flexible periodicity; exogenous regressors — incorporating covariates (promotions, weather, economic indicators, other series) with lead-lag alignment and the strict requirement that regressors be known or forecastable at prediction time; the autocorrelated-residuals problem — why OLS inference breaks under serial correlation, Durbin-Watson and residual ACF checks, and Newey-West-style corrections at overview; regularization — ridge and lasso for many-lag and many-covariate settings, and lag selection discipline; feature engineering from time itself at depth — rolling statistics, differences, Fourier features, holiday distances; generalized linear models for count series (Poisson/negative-binomial regression for social-volume counts); regression versus dedicated time-series models — when each wins; and the leakage audit specific to regression forecasting — scaling, imputation, and lag construction across train/test boundaries. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to build forecasting regressions with lags, trend, seasonal dummies, and Fourier terms, incorporate exogenous covariates with forecastability constraints.

* Teach how to diagnose and correct serially correlated residuals, regularize and select lag features disciplined against leakage, and fit count-data GLMs for volume series.

Use numerous realistic examples throughout the module, drawn from professional practice in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Build forecasting regressions with lags, trend, seasonal dummies, and Fourier terms, incorporate exogenous covariates with forecastability constraints, applied to a realistic scenario provided with the exercise.

2. Diagnose and correct serially correlated residuals, regularize and select lag features disciplined against leakage, and fit count-data GLMs for volume series, applied to a realistic scenario provided with the exercise.

3. Integrate the full section: take one realistic problem in Time-series forecasting through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Hyndman & Athanasopoulos, Forecasting: Principles and Practice (OTexts, open edition); Chatfield, The Analysis of Time Series: An Introduction (Chapman & Hall/CRC); Shumway & Stoffer, Time Series Analysis and Its Applications (Springer open text); Makridakis, Spiliotis & Assimakopoulos, M-competition findings on statistical vs ML vs deep-learning forecast accuracy; Taylor & Letham, Facebook Prophet documentation and paper; Amazon, Google, and Nixtla documentation and papers for DeepAR, TimesFM, Chronos, and TimeGPT foundation models; Google Trends official documentation and the nowcasting literature (e.g., Preis, Moat & Stanley on search-volume prediction). Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a build-forecasting-regressions-with checklist, a diagnose-and-correct-serially checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
