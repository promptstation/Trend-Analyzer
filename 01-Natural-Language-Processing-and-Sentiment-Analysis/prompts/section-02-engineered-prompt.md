# STEP 2 — Engineered Prompt for Section 2 (Natural Language Processing & Sentiment Analysis)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 2 of
the Natural Language Processing & Sentiment Analysis curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Preprocessing and Text Representation”** as the opening foundation of a curriculum in natural language processing and sentiment analysis for trend intelligence — processing millions of social media posts, reviews, and search queries to measure the emotional undercurrents of the public. Cover turning raw text into analysis-ready data: tokenization — word, subword (BPE and friends), and the challenges of social text (hashtags, handles, emojis, URLs, elongation like "soooo"); normalization decisions — casing, slang handling and its trade-offs, stemming versus lemmatization, and what normalization destroys; stop words reconsidered; the vector-space model and bag-of-words representations; TF-IDF derived and its variants; n-grams, collocations, and pointwise mutual information for phrase discovery; sparsity, dimensionality, and hashing tricks at overview; feature hygiene — fitting preprocessing only on training data to avoid leakage; character-level representations for morphology and noise robustness; corpus construction discipline — deduplication, language filtering, boilerplate removal; and the bridge to models — how representation choices constrain everything downstream. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to build preprocessing pipelines appropriate to social and review text, compute and interpret TF-IDF, n-gram, and collocation features.

* Teach how to choose tokenization and normalization strategies with awareness of what each destroys, avoid preprocessing leakage in evaluation pipelines.

* Teach how to construct clean analysis-ready corpora from raw platform text.

Use numerous realistic examples throughout the module, drawn from professional practice in natural language processing and sentiment analysis for trend intelligence — processing millions of social media posts, reviews, and search queries to measure the emotional undercurrents of the public. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Build preprocessing pipelines appropriate to social and review text, compute and interpret TF-IDF, n-gram, and collocation features, applied to a realistic scenario provided with the exercise.

2. Choose tokenization and normalization strategies with awareness of what each destroys, avoid preprocessing leakage in evaluation pipelines, applied to a realistic scenario provided with the exercise.

3. Construct clean analysis-ready corpora from raw platform text, applied to a realistic scenario provided with the exercise.

4. Integrate the full section: take one realistic problem in NLP and sentiment analysis through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from natural language processing and sentiment analysis for trend intelligence — processing millions of social media posts, reviews, and search queries to measure the emotional undercurrents of the public where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Jurafsky & Martin, Speech and Language Processing (3rd ed. draft); Manning & Schütze, Foundations of Statistical Natural Language Processing; Liu, Sentiment Analysis: Mining Opinions, Sentiments, and Emotions; Pang & Lee, Opinion Mining and Sentiment Analysis (foundations and trends); canonical papers: Mikolov et al. (word2vec), Pennington et al. (GloVe), Blei et al. (LDA), Devlin et al. (BERT), Vaswani et al. (Attention Is All You Need), Hamilton et al. (diachronic word embeddings); social-media NLP: Eisenstein, Natural Language Processing for Social Media; Blodgett et al. on dialect bias; Barbieri et al. (emoji and Twitter semantics); VADER (Hutto & Gilbert) documentation and SemEval shared-task archives (sentiment, ABSA, stance, irony); annotation and evaluation: Pustejovsky & Stubbs, Natural Language Annotation for Machine Learning; datasheets for datasets (Gebru et al.); benchmark-contamination literature; platform data docs: Google Trends methodology documentation, Wikipedia pageviews API docs, current platform API terms (X, Reddit, TikTok Research API); AoIR ethical guidelines for internet research; Bender & Gebru, On the Dangers of Stochastic Parrots. Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a build-preprocessing-pipelines-appropriate checklist, a choose-tokenization-and-normalization checklist, a construct-clean-analysis-ready checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
