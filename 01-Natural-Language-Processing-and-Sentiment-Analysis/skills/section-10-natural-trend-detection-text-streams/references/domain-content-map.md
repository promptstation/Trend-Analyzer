# Domain Content Map — Trend Detection in Text Streams

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Implement burst and novelty detection on text streams with seasonal baselining, track emerging topics and entities over time.
2. Distinguish genuine signal from cascade and bot noise in volume spikes.
3. Design trend scores and alert thresholds with precision-recall trade-offs.
4. Build monitoring dashboards for emerging language with provenance.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the core operational task — spotting what is rising: trend defined for text streams — volume bursts, emerging terms and entities, topic share shifts, and sentiment shifts as distinct detectable signals; burst detection methods — Kleinberg's state-machine model, moving z-scores, CUSUM, and seasonal baselines controlling weekday, holiday, and platform-event cycles; novel-term detection — out-of-vocabulary tracking, embedding-distance-from-established-vocabulary methods, and candidate validation with human review; topic tracking over streams — incremental clustering, streaming topic models, and theme-share time series; event detection and first-story detection lineage; entity-emergence tracking for brands, products, and people; velocity and acceleration metrics as trend scores; the signal-versus-cascade discipline — distinguishing genuine interest growth from single-viral-post echoes and bot amplification; alert design — thresholds, precision-recall trade-offs in monitoring products, and analyst-review loops; historical spike archives as reference classes for calibration; and the dashboard layer — presenting detection results with context and provenance.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the core operational task — spotting what is rising
- trend defined for text streams — volume bursts, emerging terms and entities, topic share shifts, and sentiment shifts as distinct detectable signals
- burst detection methods — Kleinberg's state-machine model, moving z-scores, CUSUM, and seasonal baselines controlling weekday, holiday, and platform-event cycles
- novel-term detection — out-of-vocabulary tracking, embedding-distance-from-established-vocabulary methods, and candidate validation with human review
- topic tracking over streams — incremental clustering, streaming topic models, and theme-share time series
- event detection and first-story detection lineage
- entity-emergence tracking for brands, products, and people
- velocity and acceleration metrics as trend scores
- the signal-versus-cascade discipline — distinguishing genuine interest growth from single-viral-post echoes and bot amplification
- alert design — thresholds, precision-recall trade-offs in monitoring products, and analyst-review loops
- historical spike archives as reference classes for calibration
- and the dashboard layer — presenting detection results with context and provenance

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in NLP and sentiment analysis practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in NLP and sentiment analysis through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
