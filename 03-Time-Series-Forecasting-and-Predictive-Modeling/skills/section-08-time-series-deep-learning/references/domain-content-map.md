# Domain Content Map — Deep Learning for Time Series: RNNs, CNNs, and Seq2Seq

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Configure LSTM/GRU and seq2seq forecasters with attention for multi-step horizons.
2. Apply TCN and N-BEATS/N-HiTS architectures.
3. Implement DeepAR-style probabilistic deep forecasting with quantile losses.
4. Manage deep-model training craft (normalization, early stopping, sequence length), and decide by data conditions when deep learning justifies its cost over ML and statistical baselines.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers neural sequence models: the case for deep learning — automatic representation learning, long-horizon direct forecasting, and multi-series training, weighed against the persistent evidence that gains over strong ML baselines are data-dependent; RNN foundations — recurrence, vanishing gradients, and why raw RNNs fail on long series; LSTM and GRU architectures — gating mechanisms explained functionally, sequence-input/forecast-output configurations, and practical training concerns (initialization, sequence length, teacher forcing versus scheduled sampling); encoder-decoder seq2seq models for multi-step forecasting with attention introduced; temporal convolutional networks — dilated causal convolutions and WaveNet-lineage models; deep state-space models — DeepAR's probabilistic multi-series forecasting with quantile outputs as the industry pattern; N-BEATS and N-HiTS — interpretable basis-expansion architectures that beat classical methods on benchmarks; training craft — normalization layers, dropout placement, early stopping on validation horizons, and the small-data overfitting regime; hyperparameter sensitivity and compute cost realities; and the honest selection rule — deep models earn their complexity at scale (many series, long histories, rich covariates), not on single short series.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers neural sequence models
- the case for deep learning — automatic representation learning, long-horizon direct forecasting, and multi-series training, weighed against the persistent evidence that gains over strong ML baselines are data-dependent
- RNN foundations — recurrence, vanishing gradients, and why raw RNNs fail on long series
- LSTM and GRU architectures — gating mechanisms explained functionally, sequence-input/forecast-output configurations, and practical training concerns (initialization, sequence length, teacher forcing versus scheduled sampling)
- encoder-decoder seq2seq models for multi-step forecasting with attention introduced
- temporal convolutional networks — dilated causal convolutions and WaveNet-lineage models
- deep state-space models — DeepAR's probabilistic multi-series forecasting with quantile outputs as the industry pattern
- N-BEATS and N-HiTS — interpretable basis-expansion architectures that beat classical methods on benchmarks
- training craft — normalization layers, dropout placement, early stopping on validation horizons, and the small-data overfitting regime
- hyperparameter sensitivity and compute cost realities
- and the honest selection rule — deep models earn their complexity at scale (many series, long histories, rich covariates), not on single short series

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
