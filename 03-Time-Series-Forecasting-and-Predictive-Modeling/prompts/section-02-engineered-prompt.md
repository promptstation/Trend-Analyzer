# STEP 2 — Engineered Prompt for Section 2 (Time-Series Forecasting & Predictive Modeling)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 2 of
the Time-Series Forecasting & Predictive Modeling curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Data Preparation for Time Series”** as the opening foundation of a curriculum in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. Build the preprocessing discipline that determines everything downstream: ingestion and alignment — timestamps, time zones, irregular sampling, and resampling/aggregation (sum versus mean versus last) with the semantic care each requires; missing data — mechanisms (MCAR versus informative gaps), interpolation and imputation methods, and when missingness is itself signal; outliers and anomalies — spikes, level shifts, and data errors distinguished, with robust detection (rolling statistics, STL residuals) and principled treatment (winsorizing, indicator flags, robust models) rather than silent deletion; calendar features — day-of-week, month, holidays across regions, leap years, business-day effects — and their confounding with genuine trend shifts; transformations — log and Box-Cox for variance stabilization, the multiplicative-versus-additive choice, and back-transformation bias awareness; Google Trends–specific preparation — index normalization (0–100 relative scaling), the query-mix and geographic-scope choices that change results, sampling variability across pulls, and combining related terms; data versioning and the revision problem (sources that restate history); and building reproducible prep pipelines with leakage-proofing — no future information in any transformation fitted on training windows. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to build leakage-proof ingestion and resampling pipelines.

* Teach how to detect and treat outliers and missing data by mechanism rather than reflex, engineer calendar and holiday features.

* Teach how to apply variance-stabilizing transformations with back-transformation awareness.

* Teach how to prepare search-index and social-volume series handling their normalization and sampling peculiarities.

Use numerous realistic examples throughout the module, drawn from professional practice in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Build leakage-proof ingestion and resampling pipelines, applied to a realistic scenario provided with the exercise.

2. Detect and treat outliers and missing data by mechanism rather than reflex, engineer calendar and holiday features, applied to a realistic scenario provided with the exercise.

3. Apply variance-stabilizing transformations with back-transformation awareness, applied to a realistic scenario provided with the exercise.

4. Prepare search-index and social-volume series handling their normalization and sampling peculiarities, applied to a realistic scenario provided with the exercise.

5. Integrate the full section: take one realistic problem in Time-series forecasting through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Hyndman & Athanasopoulos, Forecasting: Principles and Practice (OTexts, open edition); Chatfield, The Analysis of Time Series: An Introduction (Chapman & Hall/CRC); Shumway & Stoffer, Time Series Analysis and Its Applications (Springer open text); Makridakis, Spiliotis & Assimakopoulos, M-competition findings on statistical vs ML vs deep-learning forecast accuracy; Taylor & Letham, Facebook Prophet documentation and paper; Amazon, Google, and Nixtla documentation and papers for DeepAR, TimesFM, Chronos, and TimeGPT foundation models; Google Trends official documentation and the nowcasting literature (e.g., Preis, Moat & Stanley on search-volume prediction). Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a build-leakage-proof-ingestion checklist, a detect-and-treat-outliers checklist, a apply-variance-stabilizing-transformations checklist, a prepare-search-index-and checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
