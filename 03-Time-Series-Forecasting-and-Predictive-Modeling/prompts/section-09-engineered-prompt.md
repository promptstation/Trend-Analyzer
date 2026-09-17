# STEP 2 — Engineered Prompt for Section 9 (Time-Series Forecasting & Predictive Modeling)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 9 of
the Time-Series Forecasting & Predictive Modeling curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Transformer Models and Time-Series Foundation Models”** as a core intermediate stage of a curriculum in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. Teach the current frontier: transformers for time series — self-attention's fit to long-range dependencies, and the architectural adaptations (Informer's sparse attention, Autoformer's decomposition, PatchTST's patching and channel independence) with evidence that simple linear models remained competitive, tempering early claims; the foundation-model shift — large pre-trained models (TimeGPT, Chronos, TimesFM, Moirai, Lag-Llama) trained on billions of time points and applied zero-shot or fine-tuned, with how tokenization of values works (Chronos's binning approach) and the in-context-learning framing; zero-shot versus fine-tuned performance — current benchmark evidence, where foundation models beat and trail specialist models, and the fast-moving nature of these results; probabilistic outputs — quantile and distributional forecasts from foundation models, and ensemble/consensus strategies across models; LLMs as forecasters — direct numeric prediction limitations versus LLMs as feature extractors and reasoning layers over forecasts; covariate handling in foundation models — the current weakness and workarounds; inference cost, latency, and hosting realities; integration patterns — foundation models as one candidate in a backtested ensemble rather than a replacement for the stack; and evaluation discipline for frontier models — reproduce claims on your own series before adoption. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to apply transformer-based and patching architectures with awareness of benchmark context.

* Teach how to use zero-shot and fine-tuned foundation models (Chronos, TimesFM, Moirai, TimeGPT lineage) with probabilistic outputs.

* Teach how to combine foundation models into backtested ensembles.

* Teach how to position LLMs as feature and reasoning layers rather than raw predictors, and independently validate frontier-model claims on domain series before adoption.

Use numerous realistic examples throughout the module, drawn from professional practice in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Apply transformer-based and patching architectures with awareness of benchmark context, applied to a realistic scenario provided with the exercise.

2. Use zero-shot and fine-tuned foundation models (Chronos, TimesFM, Moirai, TimeGPT lineage) with probabilistic outputs, applied to a realistic scenario provided with the exercise.

3. Combine foundation models into backtested ensembles, applied to a realistic scenario provided with the exercise.

4. Position LLMs as feature and reasoning layers rather than raw predictors, and independently validate frontier-model claims on domain series before adoption, applied to a realistic scenario provided with the exercise.

5. Integrate the full section: take one realistic problem in Time-series forecasting through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Hyndman & Athanasopoulos, Forecasting: Principles and Practice (OTexts, open edition); Chatfield, The Analysis of Time Series: An Introduction (Chapman & Hall/CRC); Shumway & Stoffer, Time Series Analysis and Its Applications (Springer open text); Makridakis, Spiliotis & Assimakopoulos, M-competition findings on statistical vs ML vs deep-learning forecast accuracy; Taylor & Letham, Facebook Prophet documentation and paper; Amazon, Google, and Nixtla documentation and papers for DeepAR, TimesFM, Chronos, and TimeGPT foundation models; Google Trends official documentation and the nowcasting literature (e.g., Preis, Moat & Stanley on search-volume prediction). Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a apply-transformer-based-and checklist, a use-zero-shot-and checklist, a combine-foundation-models-into checklist, a position-llms-as-feature checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
