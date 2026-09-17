# Domain Content Map — Transformer Models and Time-Series Foundation Models

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Apply transformer-based and patching architectures with awareness of benchmark context.
2. Use zero-shot and fine-tuned foundation models (Chronos, TimesFM, Moirai, TimeGPT lineage) with probabilistic outputs.
3. Combine foundation models into backtested ensembles.
4. Position LLMs as feature and reasoning layers rather than raw predictors, and independently validate frontier-model claims on domain series before adoption.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Teaches the current frontier: transformers for time series — self-attention's fit to long-range dependencies, and the architectural adaptations (Informer's sparse attention, Autoformer's decomposition, PatchTST's patching and channel independence) with evidence that simple linear models remained competitive, tempering early claims; the foundation-model shift — large pre-trained models (TimeGPT, Chronos, TimesFM, Moirai, Lag-Llama) trained on billions of time points and applied zero-shot or fine-tuned, with how tokenization of values works (Chronos's binning approach) and the in-context-learning framing; zero-shot versus fine-tuned performance — current benchmark evidence, where foundation models beat and trail specialist models, and the fast-moving nature of these results; probabilistic outputs — quantile and distributional forecasts from foundation models, and ensemble/consensus strategies across models; LLMs as forecasters — direct numeric prediction limitations versus LLMs as feature extractors and reasoning layers over forecasts; covariate handling in foundation models — the current weakness and workarounds; inference cost, latency, and hosting realities; integration patterns — foundation models as one candidate in a backtested ensemble rather than a replacement for the stack; and evaluation discipline for frontier models — reproduce claims on your own series before adoption.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Teaches the current frontier
- transformers for time series — self-attention's fit to long-range dependencies, and the architectural adaptations (Informer's sparse attention, Autoformer's decomposition, PatchTST's patching and channel independence) with evidence that simple linear models remained competitive, tempering early claims
- the foundation-model shift — large pre-trained models (TimeGPT, Chronos, TimesFM, Moirai, Lag-Llama) trained on billions of time points and applied zero-shot or fine-tuned, with how tokenization of values works (Chronos's binning approach) and the in-context-learning framing
- zero-shot versus fine-tuned performance — current benchmark evidence, where foundation models beat and trail specialist models, and the fast-moving nature of these results
- probabilistic outputs — quantile and distributional forecasts from foundation models, and ensemble/consensus strategies across models
- LLMs as forecasters — direct numeric prediction limitations versus LLMs as feature extractors and reasoning layers over forecasts
- covariate handling in foundation models — the current weakness and workarounds
- inference cost, latency, and hosting realities
- integration patterns — foundation models as one candidate in a backtested ensemble rather than a replacement for the stack
- and evaluation discipline for frontier models — reproduce claims on your own series before adoption

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Time-series forecasting practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Time-series forecasting through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
