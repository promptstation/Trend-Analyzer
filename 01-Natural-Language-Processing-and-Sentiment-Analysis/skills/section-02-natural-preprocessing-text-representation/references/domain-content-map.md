# Domain Content Map — Preprocessing and Text Representation

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Build preprocessing pipelines appropriate to social and review text, compute and interpret TF-IDF, n-gram, and collocation features.
2. Choose tokenization and normalization strategies with awareness of what each destroys, avoid preprocessing leakage in evaluation pipelines.
3. Construct clean analysis-ready corpora from raw platform text.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers turning raw text into analysis-ready data: tokenization — word, subword (BPE and friends), and the challenges of social text (hashtags, handles, emojis, URLs, elongation like "soooo"); normalization decisions — casing, slang handling and its trade-offs, stemming versus lemmatization, and what normalization destroys; stop words reconsidered; the vector-space model and bag-of-words representations; TF-IDF derived and its variants; n-grams, collocations, and pointwise mutual information for phrase discovery; sparsity, dimensionality, and hashing tricks at overview; feature hygiene — fitting preprocessing only on training data to avoid leakage; character-level representations for morphology and noise robustness; corpus construction discipline — deduplication, language filtering, boilerplate removal; and the bridge to models — how representation choices constrain everything downstream.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers turning raw text into analysis-ready data
- tokenization — word, subword (BPE and friends), and the challenges of social text (hashtags, handles, emojis, URLs, elongation like "soooo")
- normalization decisions — casing, slang handling and its trade-offs, stemming versus lemmatization, and what normalization destroys
- stop words reconsidered
- the vector-space model and bag-of-words representations
- TF-IDF derived and its variants
- n-grams, collocations, and pointwise mutual information for phrase discovery
- sparsity, dimensionality, and hashing tricks at overview
- feature hygiene — fitting preprocessing only on training data to avoid leakage
- character-level representations for morphology and noise robustness
- corpus construction discipline — deduplication, language filtering, boilerplate removal
- and the bridge to models — how representation choices constrain everything downstream

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in NLP and sentiment analysis practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in NLP and sentiment analysis through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
