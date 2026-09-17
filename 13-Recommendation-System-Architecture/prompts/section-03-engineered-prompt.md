# STEP 2 — Engineered Prompt for Section 3 (Recommendation System Architecture)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 3 of
the Recommendation System Architecture curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Content-Based and Collaborative Filtering Foundations”** as a core intermediate stage of a curriculum in Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends. Teach the classical algorithms: content-based filtering — item profiles from content features (TF-IDF for text, embeddings for media), user profiles as aggregations of interacted-item features, and similarity matching, with strengths (no cross-user data, new-item friendly) and weaknesses (overspecialization, feature-engineering dependence); collaborative filtering — the behavior-pattern family: user-based CF (similar users' items), item-based CF (co-interaction similarity, the Amazon lineage), and their memory-based computation; matrix factorization — latent-factor models (SVD lineage, FunkSVD, ALS for implicit data) as the dominant classical approach, with factor interpretation and regularization; factorization machines at overview — feature interactions generalizing MF; the neighborhood-versus-model spectrum — computation and accuracy trade-offs; similarity measures — cosine, Pearson, Jaccard, and their data-type fitness; the cold-start problem structured — new-user (onboarding signals, demographics), new-item (content features, exploration budgets), and new-system variants with standard mitigations; sparsity and scale — why classical methods strain on billions of interactions and what approximations enable (sampling, dimensionality reduction, indexing); the hybrid principle — combining content and collaborative signals to cover each other's gaps, with weighted, switching, and feature-combination hybrid designs; the persistence lesson — classical methods remain production components (retrieval candidates, cold-start fallbacks, interpretable layers) inside modern deep systems; and practice — implementing basic CF and content-based recommenders to internalize their behavior before probing real platforms. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to implement and analyze content-based and collaborative filtering (user-based, item-based, matrix factorization) with similarity-measure selection.

* Teach how to diagnose cold-start variants and standard mitigations, handle sparsity and scale approximations in classical methods.

* Teach how to design hybrid combinations covering component gaps.

* Teach how to recognize classical components operating inside modern production systems.

Use numerous realistic examples throughout the module, drawn from professional practice in Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Implement and analyze content-based and collaborative filtering (user-based, item-based, matrix factorization) with similarity-measure selection, applied to a realistic scenario provided with the exercise.

2. Diagnose cold-start variants and standard mitigations, handle sparsity and scale approximations in classical methods, applied to a realistic scenario provided with the exercise.

3. Design hybrid combinations covering component gaps, applied to a realistic scenario provided with the exercise.

4. Recognize classical components operating inside modern production systems, applied to a realistic scenario provided with the exercise.

5. Integrate the full section: take one realistic problem in Recommendation systems through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Aggarwal, Recommender Systems: The Textbook, and Jannach et al. foundations for the classical architecture; Covington, Adams & Sargin, 'Deep Neural Networks for YouTube Recommendations' (RecSys 2016) — the canonical two-stage architecture disclosure; TikTok, YouTube, and Instagram official transparency disclosures on how recommendation systems work (TikTok's 'How TikTok recommends' and For You feed documentation; YouTube's recommendation guidance); Rendle-lineage matrix-factorization and factorization-machine literature; two-tower retrieval and ranking practice from industry engineering blogs; Chen et al. on top-K recommender evaluation pitfalls, and the offline-online evaluation gap literature; Algorithmic auditing research: sock-puppet and mystery-shopping methods (e.g., investigations of TikTok and YouTube recommendation dynamics), and the DSA transparency obligations for recommender disclosure; Google Trends methodology documentation and the search-suggest/query-log literature. Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a implement-and-analyze-content checklist, a diagnose-cold-start-variants checklist, a design-hybrid-combinations-covering checklist, a recognize-classical-components-operating checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
