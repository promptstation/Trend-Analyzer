# STEP 2 — Engineered Prompt for Section 8 (Time-Series Forecasting & Predictive Modeling)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 8 of
the Time-Series Forecasting & Predictive Modeling curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Deep Learning for Time Series: RNNs, CNNs, and Seq2Seq”** as a core intermediate stage of a curriculum in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. Cover neural sequence models: the case for deep learning — automatic representation learning, long-horizon direct forecasting, and multi-series training, weighed against the persistent evidence that gains over strong ML baselines are data-dependent; RNN foundations — recurrence, vanishing gradients, and why raw RNNs fail on long series; LSTM and GRU architectures — gating mechanisms explained functionally, sequence-input/forecast-output configurations, and practical training concerns (initialization, sequence length, teacher forcing versus scheduled sampling); encoder-decoder seq2seq models for multi-step forecasting with attention introduced; temporal convolutional networks — dilated causal convolutions and WaveNet-lineage models; deep state-space models — DeepAR's probabilistic multi-series forecasting with quantile outputs as the industry pattern; N-BEATS and N-HiTS — interpretable basis-expansion architectures that beat classical methods on benchmarks; training craft — normalization layers, dropout placement, early stopping on validation horizons, and the small-data overfitting regime; hyperparameter sensitivity and compute cost realities; and the honest selection rule — deep models earn their complexity at scale (many series, long histories, rich covariates), not on single short series. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to configure LSTM/GRU and seq2seq forecasters with attention for multi-step horizons.

* Teach how to apply TCN and N-BEATS/N-HiTS architectures.

* Teach how to implement DeepAR-style probabilistic deep forecasting with quantile losses.

* Teach how to manage deep-model training craft (normalization, early stopping, sequence length), and decide by data conditions when deep learning justifies its cost over ML and statistical baselines.

Use numerous realistic examples throughout the module, drawn from professional practice in Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Configure LSTM/GRU and seq2seq forecasters with attention for multi-step horizons, applied to a realistic scenario provided with the exercise.

2. Apply TCN and N-BEATS/N-HiTS architectures, applied to a realistic scenario provided with the exercise.

3. Implement DeepAR-style probabilistic deep forecasting with quantile losses, applied to a realistic scenario provided with the exercise.

4. Manage deep-model training craft (normalization, early stopping, sequence length), and decide by data conditions when deep learning justifies its cost over ML and statistical baselines, applied to a realistic scenario provided with the exercise.

5. Integrate the full section: take one realistic problem in Time-series forecasting through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from Statistical learning, econometrics, and forecasting science applied to trend trajectory analysis where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Hyndman & Athanasopoulos, Forecasting: Principles and Practice (OTexts, open edition); Chatfield, The Analysis of Time Series: An Introduction (Chapman & Hall/CRC); Shumway & Stoffer, Time Series Analysis and Its Applications (Springer open text); Makridakis, Spiliotis & Assimakopoulos, M-competition findings on statistical vs ML vs deep-learning forecast accuracy; Taylor & Letham, Facebook Prophet documentation and paper; Amazon, Google, and Nixtla documentation and papers for DeepAR, TimesFM, Chronos, and TimeGPT foundation models; Google Trends official documentation and the nowcasting literature (e.g., Preis, Moat & Stanley on search-volume prediction). Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a configure-lstm-gru-and checklist, a apply-tcn-and-n checklist, a implement-deepar-style-probabilistic checklist, a manage-deep-model-training checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
