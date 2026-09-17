# Domain Content Map — Classical Supervised Text Classification

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Implement and compare naive Bayes, logistic regression, and SVM text classifiers with proper evaluation splits, handle imbalanced text datasets through weighting and threshold tuning.
2. Interpret linear model coefficients as calibrated evidence, establish strong baselines before adding complexity.
3. Run systematic error analysis to drive model improvement.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Teaches the workhorse modeling layer before neural methods: the classification task formalized — labels, features, and the train/validation/test discipline for text; multinomial naive Bayes with its bag-of-words independence assumption and why it remains competitive on small text datasets; logistic regression with L1/L2 regularization and coefficient interpretation as evidence; linear SVMs and the margin intuition; tree ensembles on text features at awareness level; handling class imbalance — class weighting, resampling, and threshold tuning; probability calibration and why raw scores mislead; multiclass strategies; baseline discipline — majority-class and lexicon baselines before any complex model; systematic error analysis — reading misclassifications as the primary improvement tool; when classical models still win — small data, interpretability needs, latency budgets; and the scikit-learn-style workflow with pipelines that bundle preprocessing and model.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Teaches the workhorse modeling layer before neural methods
- the classification task formalized — labels, features, and the train/validation/test discipline for text
- multinomial naive Bayes with its bag-of-words independence assumption and why it remains competitive on small text datasets
- logistic regression with L1/L2 regularization and coefficient interpretation as evidence
- linear SVMs and the margin intuition
- tree ensembles on text features at awareness level
- handling class imbalance — class weighting, resampling, and threshold tuning
- probability calibration and why raw scores mislead
- multiclass strategies
- baseline discipline — majority-class and lexicon baselines before any complex model
- systematic error analysis — reading misclassifications as the primary improvement tool
- when classical models still win — small data, interpretability needs, latency budgets
- and the scikit-learn-style workflow with pipelines that bundle preprocessing and model

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in NLP and sentiment analysis practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in NLP and sentiment analysis through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
