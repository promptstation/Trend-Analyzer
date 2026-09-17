# Domain Content Map — Data Acquisition: APIs, Archives, Vendors, and Ethics

Read this during Phase 3 (architecture) and Phase 4 (writing) of the module
development workflow. Verify all factual claims and numbers against the
authoritative sources before publishing (Phase 2 evidence base); flag
anything disputed rather than repeating it.

## Absorbed capabilities this module must produce
1. Evaluate and combine acquisition channels (APIs, vendors, archives, scraping, public traces) with legal and ToS literacy, work with Google Trends and pageview data accounting for their measurement quirks, engineer collection pipelines with deduplication and bot-aware filtering.
2. Operate within ethical and privacy frameworks for public text data, and make build-versus-buy decisions for social listening infrastructure.

## Table of Contents
1. Unit 1 — Unit 1
2. Capstone integration

---

## Unit 1 — Unit 1

**Scope:** Teaches getting the text legally and reliably: the platform-API landscape and its erosion — the X/Twitter API pricing history, Reddit's third-party shutdown, TikTok's Research API constraints — and what each access tier actually provides; commercial archive vendors (Brandwatch, Meltwater, Talkwalker, Sprinklr) versus build-your-own collection — coverage, history depth, cost, and query-language realities; scraping — technical fundamentals, robots.txt and terms-of-service analysis, the hiQ-versus-LinkedIn legal arc, and platform countermeasures; research corpora and public datasets — the Pushshift legacy and its loss, academic data-access programs, and dataset staleness; search and trace data — Google Trends mechanics and quirks (relative scaling, sampling variability, geo aggregation, the API and its limits), Wikipedia pageviews as behavioral traces, app-store reviews, and job postings; data quality engineering — deduplication of copy-paste cascades, bot and spam filtering at overview, and volume-inflation awareness; ethics and compliance — GDPR/CCPA duties on public text, consent debates in internet research, AoIR guidelines, minimization and aggregation practices; and pipeline engineering — scheduled incremental collection, storage formats, and failure recovery.

**What to teach (decompose and expand each bullet into framework-level treatment):**
- Teaches getting the text legally and reliably
- the platform-API landscape and its erosion — the X/Twitter API pricing history, Reddit's third-party shutdown, TikTok's Research API constraints — and what each access tier actually provides
- commercial archive vendors (Brandwatch, Meltwater, Talkwalker, Sprinklr) versus build-your-own collection — coverage, history depth, cost, and query-language realities
- scraping — technical fundamentals, robots.txt and terms-of-service analysis, the hiQ-versus-LinkedIn legal arc, and platform countermeasures
- research corpora and public datasets — the Pushshift legacy and its loss, academic data-access programs, and dataset staleness
- search and trace data — Google Trends mechanics and quirks (relative scaling, sampling variability, geo aggregation, the API and its limits), Wikipedia pageviews as behavioral traces, app-store reviews, and job postings
- data quality engineering — deduplication of copy-paste cascades, bot and spam filtering at overview, and volume-inflation awareness
- ethics and compliance — GDPR/CCPA duties on public text, consent debates in internet research, AoIR guidelines, minimization and aggregation practices
- and pipeline engineering — scheduled incremental collection, storage formats, and failure recovery

**Evidence anchors:** select documented examples and findings from the authoritative sources listed in SKILL.md that illustrate unit 1; grade every claim (established / convention / contested) before teaching it.

**Misconceptions:** identify and correct the most common practitioner misconceptions about unit 1 in NLP and sentiment analysis practice; state the corrected view explicitly.

**Trade-offs to make explicit:** depth vs breadth, rigor vs speed, and the context-dependencies that change the recommendation for unit 1.

## Unit 2 — Capstone integration

**Purpose:** integrate every capability above on one realistic problem end to end.

**Structure:** the learner takes a single problem in NLP and sentiment analysis through each unit's framework in sequence, producing a coherent deliverable that mirrors real professional documentation. Evaluation criteria: internal consistency across artifacts, evidence discipline, honest trade-off statements, and demonstrable use of each unit's framework.
