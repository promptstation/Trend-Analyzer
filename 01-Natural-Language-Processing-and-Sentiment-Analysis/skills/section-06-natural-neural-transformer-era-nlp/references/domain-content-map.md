# Domain Content Map — Neural and Transformer-Era NLP

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Fine-tune transformer encoders for text classification with modern library workflows.
2. Choose between fine-tuned small models and LLM prompting using cost, latency, calibration, and quality trade-offs.
3. Explain the attention and transformer shift at working level.
4. Evaluate models with contamination-aware benchmark literacy, and deploy computationally realistic NLP pipelines.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the deep-learning shift at practitioner depth: sequence models — RNN/LSTM/GRU intuition for text and the vanishing-context problem they partially solved; CNNs over text at overview; the attention mechanism and why it replaced recurrence; transformers and BERT — pretraining and fine-tuning, masked language modeling, subword tokenization — and the GPT-style decoder lineage leading to LLMs; fine-tuning encoder models for trend tasks (sentiment, topic, toxicity, irony) with HuggingFace-style workflows including data collators, learning-rate schedules, and early stopping; the LLM alternative — zero-shot and few-shot classification by prompting, structured output, and their trade-offs versus fine-tuned small models on cost, latency, calibration, and consistency; hybrid designs — LLMs for labeling assistance and synthetic data with human verification; benchmark culture — leaderboards, dataset staleness, and contamination caveats in the LLM era; computational realities — GPU basics, mixed precision, distillation, and quantization at working level; and choosing architecture by task, volume, and budget rather than fashion.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the deep-learning shift at practitioner depth
- sequence models — RNN/LSTM/GRU intuition for text and the vanishing-context problem they partially solved
- CNNs over text at overview
- the attention mechanism and why it replaced recurrence
- transformers and BERT — pretraining and fine-tuning, masked language modeling, subword tokenization — and the GPT-style decoder lineage leading to LLMs
- fine-tuning encoder models for trend tasks (sentiment, topic, toxicity, irony) with HuggingFace-style workflows including data collators, learning-rate schedules, and early stopping
- the LLM alternative — zero-shot and few-shot classification by prompting, structured output, and their trade-offs versus fine-tuned small models on cost, latency, calibration, and consistency
- hybrid designs — LLMs for labeling assistance and synthetic data with human verification
- benchmark culture — leaderboards, dataset staleness, and contamination caveats in the LLM era
- computational realities — GPU basics, mixed precision, distillation, and quantization at working level
- and choosing architecture by task, volume, and budget rather than fashion

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in NLP and sentiment analysis practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in NLP and sentiment analysis through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
