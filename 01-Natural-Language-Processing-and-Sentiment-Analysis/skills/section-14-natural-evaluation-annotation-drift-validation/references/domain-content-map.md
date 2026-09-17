# Domain Content Map — Evaluation, Annotation, Drift, and Validation

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Build annotation protocols with guideline development and agreement measurement.
2. Conduct systematic error analysis and calibration assessment.
3. Detect and respond to concept and data drift with retraining triggers.
4. Validate aggregate indices against external ground truth with lead-lag analysis.
5. Operate reproducible evaluation regimes including bias-aware LLM-as-judge setups.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the discipline that makes measurements trustworthy: gold-standard construction — annotation guideline development, labeler selection and training, adjudication, and inter-annotator agreement (Cohen's and Fleiss's kappa, Krippendorff's alpha) including when disagreement is signal rather than noise; dataset documentation — datasheets and data statements, provenance tracking; offline evaluation — precision/recall/F1 with macro-versus-micro choices, calibration assessment, and error analysis as primary practice; benchmark staleness and contamination in the LLM era; drift in all its forms — concept drift (words changing meaning: "based", "sick"), data drift (platform composition, format shifts, new features), and model decay with retraining triggers; online evaluation — A/B testing NLP-driven features, human-in-the-loop QA sampling, and drift dashboards; validating aggregate indices — does the sentiment or trend index track external reality (surveys, sales, searches) with lead-lag analysis; reproducibility — seeds, pinned environments, versioned models and data; and LLM-as-judge evaluation with its documented position and verbosity biases.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the discipline that makes measurements trustworthy
- gold-standard construction — annotation guideline development, labeler selection and training, adjudication, and inter-annotator agreement (Cohen's and Fleiss's kappa, Krippendorff's alpha) including when disagreement is signal rather than noise
- dataset documentation — datasheets and data statements, provenance tracking
- offline evaluation — precision/recall/F1 with macro-versus-micro choices, calibration assessment, and error analysis as primary practice
- benchmark staleness and contamination in the LLM era
- drift in all its forms — concept drift (words changing meaning: "based", "sick"), data drift (platform composition, format shifts, new features), and model decay with retraining triggers
- online evaluation — A/B testing NLP-driven features, human-in-the-loop QA sampling, and drift dashboards
- validating aggregate indices — does the sentiment or trend index track external reality (surveys, sales, searches) with lead-lag analysis
- reproducibility — seeds, pinned environments, versioned models and data
- and LLM-as-judge evaluation with its documented position and verbosity biases

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in NLP and sentiment analysis practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in NLP and sentiment analysis through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
