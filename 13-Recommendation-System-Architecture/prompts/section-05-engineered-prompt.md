# STEP 2 — Engineered Prompt for Section 5 (Recommendation System Architecture)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 5 of
the Recommendation System Architecture curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“The Ranking Pipeline: Retrieval, Ranking, Re-Ranking, and Production Constraints”** as a core intermediate stage of a curriculum in Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends. Teach the full serving system: the funnel architecture — millions of candidates through retrieval (thousands), coarse ranking (hundreds), fine ranking (dozens), to re-ranking (final display order), with each stage's models, features, and latency budgets; retrieval sources — multiple parallel candidate generators (embedding similarity, popularity, trending, social graph, topic affinity, exploration) whose mixture shapes what can ever appear; ranking features — the feature classes used at fine-ranking stage (user-item affinity, item quality and freshness, creator signals, context, predicted engagement by objective) per disclosed and reverse-engineered knowledge; re-ranking concerns — diversity injection, deduplication, creator and topic variety, business rules and policy filters, and slate-level optimization; scoring and blending — how multiple predicted objectives (watch time, like probability, share probability) combine into final scores with weighted formulas that platforms adjust (the documented YouTube watch-time weighting history); freshness and recency handling — new-content pipelines, the initial-impression budget for unproven items, and velocity signals; system-level constraints — latency (hundreds of milliseconds end-to-end), throughput, model-size budgets, and feature-freshness limits as the engineering realities bounding sophistication; experimentation infrastructure — A/B testing at platform scale, interleaving, and how ranking changes ship gradually, explaining behavior drift users observe; failure modes — filter degradation, popularity collapse, and objective gaming by creators as observed pipeline pathologies; and the trend-analyst's pipeline map — using funnel understanding to locate where amplification happens (retrieval inclusion versus ranking boost versus re-ranking placement) and what signals matter at each stage. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to map the retrieval-ranking-reranking funnel with per-stage models, features, and latency constraints.

* Teach how to analyze multi-objective score blending and freshness/velocity handling.

* Teach how to explain how experimentation infrastructure produces observable algorithm drift.

* Teach how to diagnose pipeline pathologies (popularity collapse, objective gaming), and locate amplification points in the funnel for trend analysis.

Use numerous realistic examples throughout the module, drawn from professional practice in Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Map the retrieval-ranking-reranking funnel with per-stage models, features, and latency constraints, applied to a realistic scenario provided with the exercise.

2. Analyze multi-objective score blending and freshness/velocity handling, applied to a realistic scenario provided with the exercise.

3. Explain how experimentation infrastructure produces observable algorithm drift, applied to a realistic scenario provided with the exercise.

4. Diagnose pipeline pathologies (popularity collapse, objective gaming), and locate amplification points in the funnel for trend analysis, applied to a realistic scenario provided with the exercise.

5. Integrate the full section: take one realistic problem in Recommendation systems through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Aggarwal, Recommender Systems: The Textbook, and Jannach et al. foundations for the classical architecture; Covington, Adams & Sargin, 'Deep Neural Networks for YouTube Recommendations' (RecSys 2016) — the canonical two-stage architecture disclosure; TikTok, YouTube, and Instagram official transparency disclosures on how recommendation systems work (TikTok's 'How TikTok recommends' and For You feed documentation; YouTube's recommendation guidance); Rendle-lineage matrix-factorization and factorization-machine literature; two-tower retrieval and ranking practice from industry engineering blogs; Chen et al. on top-K recommender evaluation pitfalls, and the offline-online evaluation gap literature; Algorithmic auditing research: sock-puppet and mystery-shopping methods (e.g., investigations of TikTok and YouTube recommendation dynamics), and the DSA transparency obligations for recommender disclosure; Google Trends methodology documentation and the search-suggest/query-log literature. Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a map-the-retrieval-ranking checklist, a analyze-multi-objective-score checklist, a explain-how-experimentation-infrastructure checklist, a diagnose-pipeline-pathologies-popularity checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
