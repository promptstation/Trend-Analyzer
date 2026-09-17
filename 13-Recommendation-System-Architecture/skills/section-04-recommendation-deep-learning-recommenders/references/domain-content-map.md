# Domain Content Map — Deep Learning Recommenders: Embeddings, Sequences, and Two-Tower Architectures

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Explain neural embeddings and two-tower retrieval-rank architectures as industry-standard design.
2. Analyze sequence and feature-interaction models (SASRec, Wide&Deep lineage) and multi-task objectives, reason from architecture choices to observable recommendation behaviors, understand continuous retraining and feedback-loop implications.
3. Design component-isolating probes informed by architecture knowledge.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the modern algorithmic core: neural embeddings — learned dense representations of users and items replacing hand-built features, with embedding-space geometry (similarity as distance) as the conceptual key; the YouTube architecture — Covington-Adams-Sargin's canonical two-stage disclosure: candidate generation (treat recommendation as extreme multi-class classification, retrieving hundreds from millions) followed by ranking (feature-rich scoring of candidates), the pattern now industry-standard; two-tower models — user tower and item tower producing embeddings scored by dot product, enabling efficient approximate-nearest-neighbor retrieval (ANN indexing: HNSW and product quantization at working level); sequence modeling — user histories as sequences (RNN/attention architectures, SASRec-lineage self-attention models) capturing evolving interests and session context; feature interaction models — Wide&Deep, DeepFM, and DCN lineage combining memorization and generalization for ranking; multi-task learning — jointly predicting click, completion, like, share as related objectives with shared representations; transformer-based recommenders and the scaling question — whether recommendation benefits from LLM-style scaling laws, and LLM-integration patterns (LLM feature extraction, conversational recommendation) at frontier level; training realities — massive log data, negative sampling strategies, position and selection bias in training data (feedback loops previewed), and continuous retraining cycles; the analyst's inference — how architecture choices produce observable behaviors (embedding similarity explaining lookalike recommendations, sequence models explaining session coherence, multi-task objectives explaining engagement-mix optimization); and the bridge to probing — knowing what components exist lets auditors design tests that isolate them (similarity tests for embeddings, session tests for sequence models).

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the modern algorithmic core
- neural embeddings — learned dense representations of users and items replacing hand-built features, with embedding-space geometry (similarity as distance) as the conceptual key
- the YouTube architecture — Covington-Adams-Sargin's canonical two-stage disclosure: candidate generation (treat recommendation as extreme multi-class classification, retrieving hundreds from millions) followed by ranking (feature-rich scoring of candidates), the pattern now industry-standard
- two-tower models — user tower and item tower producing embeddings scored by dot product, enabling efficient approximate-nearest-neighbor retrieval (ANN indexing: HNSW and product quantization at working level)
- sequence modeling — user histories as sequences (RNN/attention architectures, SASRec-lineage self-attention models) capturing evolving interests and session context
- feature interaction models — Wide&Deep, DeepFM, and DCN lineage combining memorization and generalization for ranking
- multi-task learning — jointly predicting click, completion, like, share as related objectives with shared representations
- transformer-based recommenders and the scaling question — whether recommendation benefits from LLM-style scaling laws, and LLM-integration patterns (LLM feature extraction, conversational recommendation) at frontier level
- training realities — massive log data, negative sampling strategies, position and selection bias in training data (feedback loops previewed), and continuous retraining cycles
- the analyst's inference — how architecture choices produce observable behaviors (embedding similarity explaining lookalike recommendations, sequence models explaining session coherence, multi-task objectives explaining engagement-mix optimization)
- and the bridge to probing — knowing what components exist lets auditors design tests that isolate them (similarity tests for embeddings, session tests for sequence models)

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Recommendation systems practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Recommendation systems through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
