# Domain Content Map — The Bass Diffusion Model: Forecasting Adoption Mathematically

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Specify and estimate Bass models (p and q coefficients) from adoption series with minimum-data discipline.
2. Interpret parameter profiles as diffusion-mechanism indicators, extend to multi-generation and price-variable formulations, avoid the documented pitfalls (short-series instability, causal over-reading, ceiling misspecification), and deliver adoption forecasts with bootstrap intervals, milestone timing, and documented assumptions.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Covers the field's workhorse forecasting model: the Bass model setup — new adoption driven by external influence (innovation coefficient p, the advertising-and-media term) and internal influence (imitation coefficient q, the word-of-mouth term), producing the differential equation whose solution is the S-curve; parameter interpretation — typical empirical ranges (p small, roughly 0.001-0.03; q substantially larger, roughly 0.3-0.5 per the meta-analytic literature) and what high-q versus high-p profiles imply (word-of-mouth-driven versus marketing-driven diffusion); estimation practice — fitting the model to adoption time series (OLS on the regression form, NLS, MLE), the minimum data requirements (roughly through the inflection point for stable estimates), and the documented instability of early-data fits; the forecast use — projecting the remaining curve from partial data with confidence intervals, and the classic application history (durable-goods, technology adoption); extensions — Bass with price, advertising-varying p, multi-generation models (Norton-Bass for successive generations), and the choice-based extensions for competing innovations; model comparison — Bass versus logistic versus Gompertz versus machine-learning alternatives, with the evidence that simple parametric models remain competitive for pure adoption curves; the pitfalls in depth — overfitting short series, treating p and q as causal mechanisms rather than curve-shape summaries, ignoring saturation-ceiling misspecification, and the re-estimation discipline as new data arrives; software practice — implementing Bass estimation in Python/R with bootstrap uncertainty; the model's trend-analysis role — quantifying where an innovation sits on its curve (the inflection passed or not), and scenario-testing marketing-effect assumptions via p/q variations; hybrid practice — combining Bass with judgment (ceiling revisions, cohort splits) as the professional standard; and the forecasting deliverable — parameter estimates, projected curves with intervals, milestone timing, and assumption documentation.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Covers the field's workhorse forecasting model
- the Bass model setup — new adoption driven by external influence (innovation coefficient p, the advertising-and-media term) and internal influence (imitation coefficient q, the word-of-mouth term), producing the differential equation whose solution is the S-curve
- parameter interpretation — typical empirical ranges (p small, roughly 0.001-0.03
- q substantially larger, roughly 0.3-0.5 per the meta-analytic literature) and what high-q versus high-p profiles imply (word-of-mouth-driven versus marketing-driven diffusion)
- estimation practice — fitting the model to adoption time series (OLS on the regression form, NLS, MLE), the minimum data requirements (roughly through the inflection point for stable estimates), and the documented instability of early-data fits
- the forecast use — projecting the remaining curve from partial data with confidence intervals, and the classic application history (durable-goods, technology adoption)
- extensions — Bass with price, advertising-varying p, multi-generation models (Norton-Bass for successive generations), and the choice-based extensions for competing innovations
- model comparison — Bass versus logistic versus Gompertz versus machine-learning alternatives, with the evidence that simple parametric models remain competitive for pure adoption curves
- the pitfalls in depth — overfitting short series, treating p and q as causal mechanisms rather than curve-shape summaries, ignoring saturation-ceiling misspecification, and the re-estimation discipline as new data arrives
- software practice — implementing Bass estimation in Python/R with bootstrap uncertainty
- the model's trend-analysis role — quantifying where an innovation sits on its curve (the inflection passed or not), and scenario-testing marketing-effect assumptions via p/q variations
- hybrid practice — combining Bass with judgment (ceiling revisions, cohort splits) as the professional standard
- and the forecasting deliverable — parameter estimates, projected curves with intervals, milestone timing, and assumption documentation

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Innovation diffusion practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Innovation diffusion through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
