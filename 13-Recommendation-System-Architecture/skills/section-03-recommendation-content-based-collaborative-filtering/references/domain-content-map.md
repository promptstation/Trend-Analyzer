# Domain Content Map — Content-Based and Collaborative Filtering Foundations

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Implement and analyze content-based and collaborative filtering (user-based, item-based, matrix factorization) with similarity-measure selection.
2. Diagnose cold-start variants and standard mitigations, handle sparsity and scale approximations in classical methods.
3. Design hybrid combinations covering component gaps.
4. Recognize classical components operating inside modern production systems.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Teaches the classical algorithms: content-based filtering — item profiles from content features (TF-IDF for text, embeddings for media), user profiles as aggregations of interacted-item features, and similarity matching, with strengths (no cross-user data, new-item friendly) and weaknesses (overspecialization, feature-engineering dependence); collaborative filtering — the behavior-pattern family: user-based CF (similar users' items), item-based CF (co-interaction similarity, the Amazon lineage), and their memory-based computation; matrix factorization — latent-factor models (SVD lineage, FunkSVD, ALS for implicit data) as the dominant classical approach, with factor interpretation and regularization; factorization machines at overview — feature interactions generalizing MF; the neighborhood-versus-model spectrum — computation and accuracy trade-offs; similarity measures — cosine, Pearson, Jaccard, and their data-type fitness; the cold-start problem structured — new-user (onboarding signals, demographics), new-item (content features, exploration budgets), and new-system variants with standard mitigations; sparsity and scale — why classical methods strain on billions of interactions and what approximations enable (sampling, dimensionality reduction, indexing); the hybrid principle — combining content and collaborative signals to cover each other's gaps, with weighted, switching, and feature-combination hybrid designs; the persistence lesson — classical methods remain production components (retrieval candidates, cold-start fallbacks, interpretable layers) inside modern deep systems; and practice — implementing basic CF and content-based recommenders to internalize their behavior before probing real platforms.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Teaches the classical algorithms
- content-based filtering — item profiles from content features (TF-IDF for text, embeddings for media), user profiles as aggregations of interacted-item features, and similarity matching, with strengths (no cross-user data, new-item friendly) and weaknesses (overspecialization, feature-engineering dependence)
- collaborative filtering — the behavior-pattern family: user-based CF (similar users' items), item-based CF (co-interaction similarity, the Amazon lineage), and their memory-based computation
- matrix factorization — latent-factor models (SVD lineage, FunkSVD, ALS for implicit data) as the dominant classical approach, with factor interpretation and regularization
- factorization machines at overview — feature interactions generalizing MF
- the neighborhood-versus-model spectrum — computation and accuracy trade-offs
- similarity measures — cosine, Pearson, Jaccard, and their data-type fitness
- the cold-start problem structured — new-user (onboarding signals, demographics), new-item (content features, exploration budgets), and new-system variants with standard mitigations
- sparsity and scale — why classical methods strain on billions of interactions and what approximations enable (sampling, dimensionality reduction, indexing)
- the hybrid principle — combining content and collaborative signals to cover each other's gaps, with weighted, switching, and feature-combination hybrid designs
- the persistence lesson — classical methods remain production components (retrieval candidates, cold-start fallbacks, interpretable layers) inside modern deep systems
- and practice — implementing basic CF and content-based recommenders to internalize their behavior before probing real platforms

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in Recommendation systems practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in Recommendation systems through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
