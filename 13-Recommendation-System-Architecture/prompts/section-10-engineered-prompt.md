# STEP 2 — Engineered Prompt for Section 10 (Recommendation System Architecture)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 10 of
the Recommendation System Architecture curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Cold Start, Exploration, and How New Content Breaks Through”** as a core intermediate stage of a curriculum in Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends. Teach the mechanism by which unknown content becomes trends: the exploration-exploitation problem — systems must balance serving known-good content (exploitation) against discovering new content's quality (exploration), formalized through multi-armed bandits (epsilon-greedy, UCB, Thompson sampling at working level) as the standard framework; platform exploration budgets — the documented pattern of initial impressions for new items (TikTok's small first-audience tests, YouTube's initial-surface testing) with quality signals (retention, completion in the test cohort) determining escalation; the velocity-escalation ladder — how strong early engagement rates unlock larger audiences in successive rounds, producing the step-function growth curves analysts observe; explore-side biases — exploration is not neutral (new items compete against proven content, and exploration allocation itself may favor certain creators, formats, or topics), with audit questions per platform; cold-start for creators — follower bootstrapping, cross-platform migration, and the documented advantage of existing audiences; the trend-breaking analysis — decomposing a breakout's early hours: first-cohort composition, engagement rates versus category baselines, escalation rounds, and the point where organic sharing joins algorithmic amplification; failure modes — the good-content-that-died-in-exploration problem (variance, unlucky first cohorts, timing) and what it implies about survivorship bias in observed trends; gaming exploration — creator tactics targeting the test phase (hook engineering, posting-time optimization, engagement-baiting first comments) with platform counter-measures; exploration's trend-ecosystem role — how exploration budgets set the platform's innovation rate (the supply of new trends) as a structural parameter; and the analyst's breakout forensics — using cold-start knowledge to distinguish algorithmically-boosted breakouts from organically-spread ones in early data. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to apply bandit frameworks to understand platform exploration-exploitation budgets, decompose breakout trajectories through velocity-escalation ladders (first cohorts, engagement rates, escalation rounds).

* Teach how to identify exploration biases and survivorship implications for observed trends.

* Teach how to analyze creator cold-start tactics and platform counter-measures.

* Teach how to run breakout forensics distinguishing algorithmic boost from organic spread in early data.

Use numerous realistic examples throughout the module, drawn from professional practice in Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Apply bandit frameworks to understand platform exploration-exploitation budgets, decompose breakout trajectories through velocity-escalation ladders (first cohorts, engagement rates, escalation rounds), applied to a realistic scenario provided with the exercise.

2. Identify exploration biases and survivorship implications for observed trends, applied to a realistic scenario provided with the exercise.

3. Analyze creator cold-start tactics and platform counter-measures, applied to a realistic scenario provided with the exercise.

4. Run breakout forensics distinguishing algorithmic boost from organic spread in early data, applied to a realistic scenario provided with the exercise.

5. Integrate the full section: take one realistic problem in Recommendation systems through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from Recommender systems engineering, platform studies, and algorithmic-auditing methods applied to reverse-engineering how TikTok's For You feed, YouTube, and Google Trends curate and amplify signals that become trends where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Aggarwal, Recommender Systems: The Textbook, and Jannach et al. foundations for the classical architecture; Covington, Adams & Sargin, 'Deep Neural Networks for YouTube Recommendations' (RecSys 2016) — the canonical two-stage architecture disclosure; TikTok, YouTube, and Instagram official transparency disclosures on how recommendation systems work (TikTok's 'How TikTok recommends' and For You feed documentation; YouTube's recommendation guidance); Rendle-lineage matrix-factorization and factorization-machine literature; two-tower retrieval and ranking practice from industry engineering blogs; Chen et al. on top-K recommender evaluation pitfalls, and the offline-online evaluation gap literature; Algorithmic auditing research: sock-puppet and mystery-shopping methods (e.g., investigations of TikTok and YouTube recommendation dynamics), and the DSA transparency obligations for recommender disclosure; Google Trends methodology documentation and the search-suggest/query-log literature. Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a apply-bandit-frameworks-to checklist, a identify-exploration-biases-and checklist, a analyze-creator-cold-start checklist, a run-breakout-forensics-distinguishing checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
