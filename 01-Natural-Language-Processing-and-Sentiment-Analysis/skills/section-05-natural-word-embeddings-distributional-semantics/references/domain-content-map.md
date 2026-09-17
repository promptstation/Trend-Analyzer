# Domain Content Map — Word Embeddings and Distributional Semantics

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Train and evaluate word embeddings with intrinsic and extrinsic checks.
2. Use similarity and analogy operations with appropriate skepticism about artifacts.
3. Apply diachronic embedding methods to detect semantic drift as a trend signal.
4. Diagnose and mitigate bias in embedding spaces.
5. Integrate embedding features into downstream classification pipelines.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Teaches meaning as geometry: the distributional hypothesis and its consequences; static embedding methods — word2vec (skip-gram and CBOW with negative sampling), GloVe, and fastText's subword handling of morphology and out-of-vocabulary terms; using embeddings — similarity, clustering, and analogy arithmetic with the hype properly deflated (analogy performance depends on corpus and frequency artifacts); embeddings as cultural records — bias embedded in vector spaces (gender and ethnicity analogies) and debiasing approaches; diachronic semantics — measuring meaning change over time with alignment methods (Hamilton-style local/global alignment) as a genuine trend-early-warning signal (words acquiring new connotations before volume spikes); limitations — polysemy averaging in static vectors and the contextualized fix previewed; embedding features inside classical classifiers; training practice — corpus size, window, dimension choices; evaluation — intrinsic (similarity sets) versus extrinsic (downstream task) and why extrinsic wins; and the practitioner's view of embeddings as infrastructure across the whole trend stack.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Teaches meaning as geometry
- the distributional hypothesis and its consequences
- static embedding methods — word2vec (skip-gram and CBOW with negative sampling), GloVe, and fastText's subword handling of morphology and out-of-vocabulary terms
- using embeddings — similarity, clustering, and analogy arithmetic with the hype properly deflated (analogy performance depends on corpus and frequency artifacts)
- embeddings as cultural records — bias embedded in vector spaces (gender and ethnicity analogies) and debiasing approaches
- diachronic semantics — measuring meaning change over time with alignment methods (Hamilton-style local/global alignment) as a genuine trend-early-warning signal (words acquiring new connotations before volume spikes)
- limitations — polysemy averaging in static vectors and the contextualized fix previewed
- embedding features inside classical classifiers
- training practice — corpus size, window, dimension choices
- evaluation — intrinsic (similarity sets) versus extrinsic (downstream task) and why extrinsic wins
- and the practitioner's view of embeddings as infrastructure across the whole trend stack

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in NLP and sentiment analysis practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in NLP and sentiment analysis through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
