# STEP 2 — Engineered Prompt for Section 3 (Network & Graph Theory)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 3 of
the Network & Graph Theory curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Centrality: Position, Brokerage, and Influence”** as a core intermediate stage of a curriculum in network and graph theory for trend analysis — mapping and modeling how ideas, content, and behaviors spread through social, information, and platform networks. Cover the most-used and most-abused toolkit: degree centrality with its directed split (in-degree as prestige, out-degree as expansiveness); betweenness centrality as brokerage measurement, closeness as independence-from-others, and their instability on sampled or incomplete graphs; eigenvector family — eigenvector centrality, Katz, PageRank with its damping parameter and search-engine history, and HITS hubs-and-authorities; the central lesson that centrality is a hypothesis family, not a single number — each measure answers a different question about position (reach, control, prestige) and they measurably disagree; weighted, temporal, and local variants at overview; the influence-identification literature — whether central nodes actually spread more (degree often suffices per Kempe-lineage results; the spreaders-versus-susceptibles distinction; retweet-influence studies showing retweetability is content-driven); practical influence ranking for trend work — who to monitor and who to seed, and why the answers differ; and the pitfalls — centrality computed on API-partial graphs, follower counts as manipulable signals, and verified-account confounds. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to compute degree, betweenness, closeness, eigenvector, and PageRank centralities and state what question each answers.

* Teach how to interpret disagreement among centrality measures on real networks.

* Teach how to evaluate influence claims using spreadability-versus-position evidence, rank nodes for monitoring versus seeding with sampling awareness, and avoid centrality misuse on incomplete or manipulated platform graphs.

Use numerous realistic examples throughout the module, drawn from professional practice in network and graph theory for trend analysis — mapping and modeling how ideas, content, and behaviors spread through social, information, and platform networks. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Compute degree, betweenness, closeness, eigenvector, and PageRank centralities and state what question each answers, applied to a realistic scenario provided with the exercise.

2. Interpret disagreement among centrality measures on real networks, applied to a realistic scenario provided with the exercise.

3. Evaluate influence claims using spreadability-versus-position evidence, rank nodes for monitoring versus seeding with sampling awareness, and avoid centrality misuse on incomplete or manipulated platform graphs, applied to a realistic scenario provided with the exercise.

4. Integrate the full section: take one realistic problem in network science through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from network and graph theory for trend analysis — mapping and modeling how ideas, content, and behaviors spread through social, information, and platform networks where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Newman, Networks (2nd ed.); Barabási, Network Science (free textbook) and Linked; Watts, Six Degrees and Small Worlds; Easley & Kleinberg, Networks, Crowds, and Markets; Borgatti, Everett & Johnson, Analyzing Social Networks; classic papers: Granovetter (strength of weak ties), Milgram (small world), Watts & Strogatz, Barabási & Albert, Kempe, Kleinberg & Tardos (influence maximization), Centola & Macy (complex contagion), Vosoughi, Roy & Aral (spread of falsehood); cascade and virality research: Cheng et al. (cascade structure prediction), Goel, Watts & Goldstein (anatomy of large-scale diffusion), Watts & Dodds (influentials); methodological rigor: Clauset, Shalizi & Newman (power-law fitting), Broido & Clauset (scale-free rarity debate), Shalizi & Thomas on contagion claims, Aral, Muchnik & Sundararajan on influence identification; tools documentation: NetworkX, igraph, graph-tool, cdlib, Gephi manuals; temporal networks (Holme & Saramäki), multilayer networks (Kivelä et al.); applied references: muchatka/multilayer toolkits, graph database docs (Neo4j), and platform engineering blogs on recommendation and graph infrastructure. Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a compute-degree-betweenness-closeness checklist, a interpret-disagreement-among-centrality checklist, a evaluate-influence-claims-using checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
