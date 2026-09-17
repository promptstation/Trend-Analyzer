# STEP 2 — Engineered Prompt for Section 4 (Network & Graph Theory)

Produced by applying `_pipeline/step1-reusable-prompt.md` to Section 4 of
the Network & Graph Theory curriculum outlook. This prompt is the task input for Step 4
skill creation (per Skill Building.md).

---

RESULT:

Develop a comprehensive, professional-level learning module on **“Community Detection and Group Structure”** as a core intermediate stage of a curriculum in network and graph theory for trend analysis — mapping and modeling how ideas, content, and behaviors spread through social, information, and platform networks. Teach finding the tribes inside networks: the community concept and its definitional ambiguity — no single ground truth; modularity defined, optimized, and its resolution limit (small communities invisible at scale); algorithms in working depth — Girvan-Newman divisive betweenness, Louvain and Leiden aggregation (including Leiden's fix for badly-connected Louvain output), label propagation, and Infomap's flow/map-equation objective; overlapping communities and fuzzy membership at overview (link communities, bigCLAM lineage); hierarchical structure — dendrograms and multi-resolution partitions; validation without ground truth — internal metrics, perturbation stability, and qualitative reading of community content; interpretation discipline — algorithmic communities are not automatically scenes, echo chambers, or markets; structural equivalence and blockmodels at overview as role analysis distinct from community membership; community evolution in dynamic networks — growth, merge, split, death tracking as a trend-detection instrument; practical workflows in igraph/leidenalg/cdlib and Gephi; and common failure modes — resolution artifacts, singleton absorption, and over-interpreting unstable partitions. The module should assume the learner is progressing from competent beginner toward expert practitioner, and should function simultaneously as a learning resource, a practical reference, and a working methodology.

Convert each of the following capabilities the learner must gain into explicit “Teach how to” treatment with a practical framework the learner could use on a real project, not merely theory:

* Teach how to apply Louvain/Leiden, Infomap, and label propagation with understanding of each objective.

* Teach how to interpret modularity with resolution-limit awareness.

* Teach how to validate communities through stability testing and qualitative reading, track community evolution over time as a trend signal.

* Teach how to distinguish algorithmic partitions from social phenomena like scenes and echo chambers.

Use numerous realistic examples throughout the module, drawn from professional practice in network and graph theory for trend analysis — mapping and modeling how ideas, content, and behaviors spread through social, information, and platform networks. For each important principle, show weak, improved, and professional-level versions of the same work where useful.

Include practical exercises that require the learner to:

1. Apply Louvain/Leiden, Infomap, and label propagation with understanding of each objective, applied to a realistic scenario provided with the exercise.

2. Interpret modularity with resolution-limit awareness, applied to a realistic scenario provided with the exercise.

3. Validate communities through stability testing and qualitative reading, track community evolution over time as a trend signal, applied to a realistic scenario provided with the exercise.

4. Distinguish algorithmic partitions from social phenomena like scenes and echo chambers, applied to a realistic scenario provided with the exercise.

5. Integrate the full section: take one realistic problem in network science through every capability above as a coherent capstone deliverable.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively: establish the fundamental concepts and distinctions of this section first, then move toward advanced professional application, showing how the concepts interact only after each is clear on its own.

Use professional terminology from network and graph theory for trend analysis — mapping and modeling how ideas, content, and behaviors spread through social, information, and platform networks where relevant, but explain each specialized term in clear language on first use. Do not make the material sound like generic AI-generated advice; it should read as if written by an experienced practitioner.

Research the subject using high-quality professional and academic sources. Prioritize authoritative sources such as Newman, Networks (2nd ed.); Barabási, Network Science (free textbook) and Linked; Watts, Six Degrees and Small Worlds; Easley & Kleinberg, Networks, Crowds, and Markets; Borgatti, Everett & Johnson, Analyzing Social Networks; classic papers: Granovetter (strength of weak ties), Milgram (small world), Watts & Strogatz, Barabási & Albert, Kempe, Kleinberg & Tardos (influence maximization), Centola & Macy (complex contagion), Vosoughi, Roy & Aral (spread of falsehood); cascade and virality research: Cheng et al. (cascade structure prediction), Goel, Watts & Goldstein (anatomy of large-scale diffusion), Watts & Dodds (influentials); methodological rigor: Clauset, Shalizi & Newman (power-law fitting), Broido & Clauset (scale-free rarity debate), Shalizi & Thomas on contagion claims, Aral, Muchnik & Sundararajan on influence identification; tools documentation: NetworkX, igraph, graph-tool, cdlib, Gephi manuals; temporal networks (Holme & Saramäki), multilayer networks (Kivelä et al.); applied references: muchatka/multilayer toolkits, graph database docs (Neo4j), and platform engineering blogs on recommendation and graph infrastructure. Avoid relying on low-quality SEO articles, content farms, or unsupported “best practice” claims; distinguish established research findings from professional conventions and informed recommendations, and never invent statistics or citations.

Where a recommendation depends on context, explicitly explain the trade-off rather than presenting it as an absolute rule.

End the module with actionable professional checklists — a apply-louvain-leiden-infomap checklist, a interpret-modularity-with-resolution checklist, a validate-communities-through-stability checklist, a distinguish-algorithmic-partitions-from checklist — that a practitioner could actually use before real-world delivery.

The final result should be comprehensive enough to serve as an advanced professional training module, organized clearly enough that a learner can study it progressively and apply each concept in practical work.
