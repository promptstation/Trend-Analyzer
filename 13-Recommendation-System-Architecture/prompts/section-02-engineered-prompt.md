# STEP 2 — Engineered Prompt for Section 2 (Recommendation System Architecture)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 2 of
the Recommendation System Architecture curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Data Foundations: Interactions, Feedback, and Features”** as the opening foundation of a curriculum in Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends. Cover the fuel of recommendation: interaction data types — explicit feedback (ratings, likes, follows) as sparse-but-intentional signals versus implicit feedback (views, dwell time, clicks, scrolls, replays, purchases) as dense-but-noisy behavior, with the preference-versus-confidence distinction for implicit data; the implicit-feedback problem — absence of interaction does not mean dislike (unobserved versus negative), and how systems handle it (negative sampling, confidence weighting); engagement signals ranked — completion rate, watch time, rewatch, share, save, comment depth as progressively stronger positive signals per platform disclosures, and their manipulation susceptibilities; user modeling — profiles built from demographics, declared interests, interaction history, device and context (time, location, session state), and the evolving nature of user representations; item modeling — content features (text, audio, video embeddings, metadata, creator identity) and behavioral features (aggregate engagement statistics); context features — session position, recency, and cross-user trends as ranking inputs; data engineering realities — event logging pipelines, feature stores, freshness requirements, and the training-serving skew problem; the cold-start data gap — new users and new items lacking interaction history, previewed as a structural problem with structural solutions; privacy-shaped data — aggregation, on-device processing, and post-ATT/cookie-deprecation signal loss changing what systems can observe (connecting to the attention course); and the analyst's mirror — understanding platform data foundations explains both what recommendation can do and what observational data the analyst can expect to see. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to distinguish explicit and implicit feedback signals with the unobserved-versus-negative problem, rank engagement signals by strength and manipulation susceptibility per platform disclosures.

* Teach how to analyze user, item, and context feature modeling in recommendation systems.

* Teach how to explain cold-start data gaps and privacy-driven signal loss as structural constraints, and infer platform data foundations from observable system behavior.

Use numerous realistic examples throughout the module, drawn from professional practice in Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Distinguish explicit and implicit feedback signals with the unobserved-versus-negative problem, rank engagement signals by strength and manipulation susceptibility per platform disclosures, applied to a realistic scenario provided with the exercise.

2. Analyze user, item, and context feature modeling in recommendation systems, applied to a realistic scenario provided with the exercise.

3. Explain cold-start data gaps and privacy-driven signal loss as structural constraints, and infer platform data foundations from observable system behavior, applied to a realistic scenario provided with the exercise.

4. Integrate the full section: take one realistic problem in Recommendation systems through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Aggarwal, Recommender Systems: The Textbook, and Jannach et al. foundations for the classical architecture; Covington, Adams & Sargin, 'Deep Neural Networks for YouTube Recommendations' (RecSys 2016) — the canonical two-stage architecture disclosure; TikTok, YouTube, and Instagram official transparency disclosures on how recommendation systems work (TikTok's 'How TikTok recommends' and For You feed documentation; YouTube's recommendation guidance); Rendle-lineage matrix-factorization and factorization-machine literature; two-tower retrieval and ranking practice from industry engineering blogs; Chen et al. on top-K recommender evaluation pitfalls, and the offline-online evaluation gap literature; Algorithmic auditing research: sock-puppet and mystery-shopping methods (e.g., investigations of TikTok and YouTube recommendation dynamics), and the DSA transparency obligations for recommender disclosure; Google Trends methodology documentation and the search-suggest/query-log literature. Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a distinguish-explicit-and-implicit checklist, a analyze-user-item-and checklist, a explain-cold-start-data checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
