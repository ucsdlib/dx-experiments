# UC Library Search strategy: extreme heat, health, and wellbeing in urban communities

## Metadata

- **Topic:** UC Library Search strategy: extreme heat, health, and wellbeing in urban communities
- **Generated:** 2026-10-03T07:50:13-07:00
- **Time zone:** America/Los_Angeles
- **Model:** api-glm-5.3
- **Runtime:** TritonAI Harness
- **Scope:** Full conversation
- **Detail:** Full interaction
- **Exchanges:** 1
- **Snapshot ID:** tritonai-snapshot-2026-10-03t07-50-13-07-00-9efdb8b2
- **Redaction:** Automatic category-labeled redaction

## Conversation

### User

$uc-library-search - How does extreme heat affect health and wellbeing in urban communities? I'm writing a literature review and need recent, peer-reviewed articles.

### Assistant

Running: **extreme heat AND health/wellbeing AND urban communities**, articles only, peer-reviewed only, 2019–2026 — I've assumed "recent" means the last ~7 years; adjust the date filter if you want a different window.

## 🎯 Initial Search Strategy

This search combines three concepts — heat events, health/wellbeing, and urban settings — with filters for peer-reviewed journal articles published 2019–2026.

**[Run this search with its filters](https://search-library.ucsd.edu/discovery/search?query=any,contains,(%22extreme%20heat%22%20OR%20%22heat%20wave%22%20OR%20%22heat%20waves%22%20OR%20heatwave%20OR%20heatwaves)%20AND%20(health%20OR%20wellbeing%20OR%20%22well-being%22%20OR%20%22mental%20health%22)%20AND%20(urban%20OR%20cities%20OR%20%22urban%20areas%22%20OR%20%22urban%20communities%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk)**

```
("extreme heat" OR "heat wave" OR "heat waves" OR heatwave OR heatwaves) AND (health OR wellbeing OR "well-being" OR "mental health") AND (urban OR cities OR "urban areas" OR "urban communities")
```

**If you paste the query instead:** use the simple search box, then apply Peer-reviewed Journals, Articles, and 2019–2026 from the left sidebar.

### Concept Breakdown
- **Concept 1 — Heat exposure:** `"extreme heat"` is the dominant phrase; heat wave / heatwave variants catch spelling and plural differences.
- **Concept 2 — Health and wellbeing:** `health` anchors the set; `wellbeing`, `"well-being"`, and `"mental health"` cover the wellbeing dimension and its spelling variant.
- **Concept 3 — Urban setting:** `urban`, `cities`, and urban place phrases keep results in the community/context you care about.

### Search Design Decisions
- **Phrase searching:** All multi-word concepts use quotes so terms appear together (Primo has no proximity operators).
- **Synonym selection:** Deliberately selective — 2–5 terms per concept rather than exhaustive lists, to balance recall with precision.
- **Parentheses:** Mandatory here — Primo applies AND before OR, so each OR group must be wrapped.
- **Filters:** Peer-reviewed + articles-only match your request for peer-reviewed articles; the date filter enforces "recent."

### What to Expect
- Results will vary: some directly on point, some adjacent (e.g., rural or non-health studies), some off-topic.
- Browsing is part of the process — scan titles/abstracts and note new vocabulary to feed back into the search.
- Use the left-sidebar subject facets to discover how the literature labels this topic.

## 🔍 Increasing Precision with Advanced Search

**[Run the query in Title field, Advanced Search](https://search-library.ucsd.edu/discovery/search?query=title,contains,(%22extreme%20heat%22%20OR%20%22heat%20wave%22%20OR%20%22heat%20waves%22%20OR%20heatwave%20OR%20heatwaves)%20AND%20(health%20OR%20wellbeing%20OR%20%22well-being%22%20OR%20%22mental%20health%22)%20AND%20(urban%20OR%20cities%20OR%20%22urban%20areas%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mode=advanced&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk)** — every concept group is searched in article titles.

To adapt in the Advanced Search interface:
- **Line 1 (Title):** contains `("extreme heat" OR heatwave OR heatwaves)`
- **Line 2 (Title):** AND contains `(health OR wellbeing OR "well-being")`
- **Line 3 (Any field):** AND contains `(urban OR cities OR "urban areas")`

A single URL applies one field to the whole query; for mixed-field layouts, build the lines manually in the interface.

## 🔄 Alternative Search Strategies

### Broader (more results, exploratory)
**[Run the broader search](https://search-library.ucsd.edu/discovery/search?query=any,contains,(%22extreme%20heat%22%20OR%20%22heat%20wave%22%20OR%20%22heat%20waves%22%20OR%20heatwave%20OR%20heatwaves%20OR%20%22heat%20events%22%20OR%20%22hot%20weather%22)%20AND%20(health%20OR%20wellbeing%20OR%20%22well-being%22%20OR%20%22mental%20health%22%20OR%20%22public%20health%22%20OR%20%22social%20wellbeing%22)%20AND%20(urban%20OR%20city%20OR%20cities%20OR%20metropolitan%20OR%20%22urban%20areas%22%20OR%20%22urban%20communities%22%20OR%20%22urban%20populations%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD)** — no filters

```
("extreme heat" OR "heat wave" OR "heat waves" OR heatwave OR heatwaves OR "heat events" OR "hot weather") AND (health OR wellbeing OR "well-being" OR "mental health" OR "public health" OR "social wellbeing") AND (urban OR city OR cities OR metropolitan OR "urban areas" OR "urban communities" OR "urban populations")
```

**What this changes:** Adds heat-event and population synonyms and removes filters — useful for scoping the landscape before narrowing.

### Narrower (higher precision)
**[Run the narrower search](https://search-library.ucsd.edu/discovery/search?query=title,contains,(%22extreme%20heat%22%20OR%20%22heat%20wave%22%20OR%20heatwave%20OR%20heatwaves)%20AND%20(health%20OR%20wellbeing%20OR%20%22well-being%22)%20AND%20(urban%20OR%20cities)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk)**

```
("extreme heat" OR "heat wave" OR heatwave OR heatwaves) AND (health OR wellbeing OR "well-being") AND (urban OR cities)
```

**What this changes:** Requires the concepts in titles only, with tighter synonym sets — the most relevant articles will likely surface here first.

### Lens 1 — Vulnerability and equity
**[Run the equity-focused search](https://search-library.ucsd.edu/discovery/search?query=any,contains,(%22extreme%20heat%22%20OR%20heatwave%20OR%20heatwaves%20OR%20%22heat%20wave%22%20OR%20%22heat%20waves%22)%20AND%20(%22heat%20vulnerability%22%20OR%20%22health%20equity%22%20OR%20%22environmental%20justice%22%20OR%20%22heat%20equity%22)%20AND%20(urban%20OR%20cities%20OR%20%22urban%20areas%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk)**

```
("extreme heat" OR heatwave OR heatwaves OR "heat wave" OR "heat waves") AND ("heat vulnerability" OR "health equity" OR "environmental justice" OR "heat equity") AND (urban OR cities OR "urban areas")
```

**What this adds:** Captures literature on who is most affected within urban communities — a common framing in recent heat-health research.

### Lens 2 — Mental health and wellbeing
**[Run the mental-health/wellbeing search](https://search-library.ucsd.edu/discovery/search?query=any,contains,(%22extreme%20heat%22%20OR%20heatwave%20OR%20heatwaves%20OR%20%22heat%20wave%22%20OR%20%22heat%20waves%22)%20AND%20(%22mental%20health%22%20OR%20wellbeing%20OR%20%22well-being%22%20OR%20%22psychological%20distress%22)%20AND%20(urban%20OR%20cities%20OR%20%22urban%20areas%22%20OR%20%22urban%20communities%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk)**

```
("extreme heat" OR heatwave OR heatwaves OR "heat wave" OR "heat waves") AND ("mental health" OR wellbeing OR "well-being" OR "psychological distress") AND (urban OR cities OR "urban areas" OR "urban communities")
```

**What this adds:** Isolates the wellbeing side of your question, which often uses different vocabulary than physical-health research.

### Lens 3 — Urban heat islands
**[Run the urban-heat-island search](https://search-library.ucsd.edu/discovery/search?query=any,contains,(%22urban%20heat%20island%22%20OR%20%22urban%20heat%20islands%22)%20AND%20(health%20OR%20wellbeing%20OR%20%22well-being%22%20OR%20mortality%20OR%20morbidity)%20AND%20(urban%20OR%20cities%20OR%20%22urban%20areas%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk)**

```
("urban heat island" OR "urban heat islands") AND (health OR wellbeing OR "well-being" OR mortality OR morbidity) AND (urban OR cities OR "urban areas")
```

**What this adds:** Targets the built-environment mechanism specific to cities, connecting urban planning and health literatures.

## 🔍 Next Steps

1. Run the main search first; if the results are too broad, switch to the Title-field version.
2. Mine references and "Cited by" links from 2–3 highly relevant articles — heat-health research is heavily cross-cited.
3. Save promising searches and set up alerts so new 2026 publications come to you.
4. Export candidates to Zotero or EndNote as you go, and tag by lens (physical health, mental health, equity, built environment) to structure your review.

## 🔭 Future Research

**Curated database starting points:**

1. **[PubMed (Medline)](https://ucsd.libguides.com/pubmeducsd)** — Core biomedical and public-health database; use MeSH terms like *Hot Temperature*, *Heat Wave*, and *Urban Health*.
2. **[Embase](https://ucsd.libguides.com/embase)** — Strong European and biomedical coverage that complements PubMed for health-sciences searching.
3. **[Web of Science](https://ucsd.libguides.com/webofscience)** — Multidisciplinary and strong for citation chaining across public health, urban studies, and climate science.
4. **[Environment Complete](https://ucsd.libguides.com/environcomplete)** — Adds environmental-studies and urban-planning perspectives on heat and urban environments.

Run the same concept groups in each database, then use its native filters and controlled vocabulary. If you'd like, tell me which lens matters most or whether results feel too broad/narrow, and I'll refine the strategy.
<details>
<summary>Tool calls: read UC Library Search skill references</summary>

```bash
cat [redacted-local-path: response-template.md]
cat [redacted-local-path: primo-ve-syntax.md]

[Output: Loaded the required response template (layout and worked example) and the verified Primo VE syntax rules — single-query-parameter URLs, encoding rules, uppercase Booleans with mandatory parentheses, phrase searching, truncation, field codes, verified filters, and the chained-query pitfall.]
```

</details>
<details>
<summary>Tool calls: check script usage</summary>

```bash
python3 scripts/build_url.py --help
python3 scripts/recommend_databases.py --help

[Output: build_url.py supports --field {any,creator,sub,title}, repeatable --filters, --advanced, and --self-test; recommend_databases.py supports --query, --subjects, --types, --limit, and --input.]
```

</details>
<details>
<summary>Tool calls: build primary and alternative search URLs</summary>

```bash
python3 scripts/build_url.py --filters peer_reviewed --filters articles --filters 2019-2026 '("extreme heat" OR "heat wave" OR "heat waves" OR heatwave OR heatwaves) AND (health OR wellbeing OR "well-being" OR "mental health") AND (urban OR cities OR "urban areas" OR "urban communities")'
→ https://search-library.ucsd.edu/discovery/search?query=any,contains,(%22extreme%20heat%22%20OR%20%22heat%20wave%22%20OR%20%22heat%20waves%22%20OR%20heatwave%20OR%20heatwaves)%20AND%20(health%20OR%20wellbeing%20OR%20%22well-being%22%20OR%20%22mental%20health%22)%20AND%20(urban%20OR%20cities%20OR%20%22urban%20areas%22%20OR%20%22urban%20communities%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk

python3 scripts/build_url.py --field title --advanced --filters peer_reviewed --filters articles --filters 2019-2026 '("extreme heat" OR "heat wave" OR "heat waves" OR heatwave OR heatwaves) AND (health OR wellbeing OR "well-being" OR "mental health") AND (urban OR cities OR "urban areas")'
→ https://search-library.ucsd.edu/discovery/search?query=title,contains,(%22extreme%20heat%22%20OR%20%22heat%20wave%22%20OR%20%22heat%20waves%22%20OR%20heatwave%20OR%20heatwaves)%20AND%20(health%20OR%20wellbeing%20OR%20%22well-being%22%20OR%20%22mental%20health%22)%20AND%20(urban%20OR%20cities%20OR%20%22urban%20areas%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mode=advanced&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk

python3 scripts/build_url.py '("extreme heat" OR "heat wave" OR "heat waves" OR heatwave OR heatwaves OR "heat events" OR "hot weather") AND (health OR wellbeing OR "well-being" OR "mental health" OR "public health" OR "social wellbeing") AND (urban OR city OR cities OR metropolitan OR "urban areas" OR "urban communities" OR "urban populations")'
→ https://search-library.ucsd.edu/discovery/search?query=any,contains,(%22extreme%20heat%22%20OR%20%22heat%20wave%22%20OR%20%22heat%20waves%22%20OR%20heatwave%20OR%20heatwaves%20OR%20%22heat%20events%22%20OR%20%22hot%20weather%22)%20AND%20(health%20OR%20wellbeing%20OR%20%22well-being%22%20OR%20%22mental%20health%22%20OR%20%22public%20health%22%20OR%20%22social%20wellbeing%22)%20AND%20(urban%20OR%20city%20OR%20cities%20OR%20metropolitan%20OR%20%22urban%20areas%22%20OR%20%22urban%20communities%22%20OR%20%22urban%20populations%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD

python3 scripts/build_url.py --field title --filters peer_reviewed --filters articles --filters 2019-2026 '("extreme heat" OR "heat wave" OR heatwave OR heatwaves) AND (health OR wellbeing OR "well-being") AND (urban OR cities)'
→ https://search-library.ucsd.edu/discovery/search?query=title,contains,(%22extreme%20heat%22%20OR%20%22heat%20wave%22%20OR%20heatwave%20OR%20heatwaves)%20AND%20(health%20OR%20wellbeing%20OR%20%22well-being%22)%20AND%20(urban%20OR%20cities)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk
```

</details>
<details>
<summary>Tool calls: build lens-specific search URLs</summary>

```bash
python3 scripts/build_url.py --filters peer_reviewed --filters articles --filters 2019-2026 '("extreme heat" OR heatwave OR heatwaves OR "heat wave" OR "heat waves") AND ("heat vulnerability" OR "health equity" OR "environmental justice" OR "heat equity") AND (urban OR cities OR "urban areas")'
→ https://search-library.ucsd.edu/discovery/search?query=any,contains,(%22extreme%20heat%22%20OR%20heatwave%20OR%20heatwaves%20OR%20%22heat%20wave%22%20OR%20%22heat%20waves%22)%20AND%20(%22heat%20vulnerability%22%20OR%20%22health%20equity%22%20OR%20%22environmental%20justice%22%20OR%20%22heat%20equity%22)%20AND%20(urban%20OR%20cities%20OR%20%22urban%20areas%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk

python3 scripts/build_url.py --filters peer_reviewed --filters articles --filters 2019-2026 '("extreme heat" OR heatwave OR heatwaves OR "heat wave" OR "heat waves") AND ("mental health" OR wellbeing OR "well-being" OR "psychological distress") AND (urban OR cities OR "urban areas" OR "urban communities")'
→ https://search-library.ucsd.edu/discovery/search?query=any,contains,(%22extreme%20heat%22%20OR%20heatwave%20OR%20heatwaves%20OR%20%22heat%20wave%22%20OR%20%22heat%20waves%22)%20AND%20(%22mental%20health%22%20OR%20wellbeing%20OR%20%22well-being%22%20OR%20%22psychological%20distress%22)%20AND%20(urban%20OR%20cities%20OR%20%22urban%20areas%22%20OR%20%22urban%20communities%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk

python3 scripts/build_url.py --filters peer_reviewed --filters articles --filters 2019-2026 '("urban heat island" OR "urban heat islands") AND (health OR wellbeing OR "well-being" OR mortality OR morbidity) AND (urban OR cities OR "urban areas")'
→ https://search-library.ucsd.edu/discovery/search?query=any,contains,(%22urban%20heat%20island%22%20OR%20%22urban%20heat%20islands%22)%20AND%20(health%20OR%20wellbeing%20OR%20%22well-being%22%20OR%20mortality%20OR%20morbidity)%20AND%20(urban%20OR%20cities%20OR%20%22urban%20areas%22)&tab=ArticleBooksEtc&search_scope=ArticlesBooksEtc&vid=01UCS_SDI:UCSD&mfacet=tlevel,include,peer_reviewed,1&mfacet=rtype,include,articles,1&facet=searchcreationdate,include,2019%7C,%7C2026,lk
```

</details>
<details>
<summary>Tool calls: recommend complementary databases</summary>

```bash
python3 scripts/recommend_databases.py --query 'extreme heat urban health wellbeing climate environmental health' --limit 4
[Output: Policy Commons; Environment Complete; SimplyAnalytics; Environmental Issues Online — score-ranked recommendations.]

python3 scripts/recommend_databases.py --query 'heat health epidemiology medicine biomedical public health literature' --subjects 'Public Health' --limit 6
[Output: PubMed (Medline); Embase; PAIS International; Roper Center for Public Opinion Research; Web of Science; GIDEON — score-ranked recommendations. The response curated PubMed, Embase, Web of Science, and Environment Complete as starting points.]
```

</details>

---

Local paths, credentials, email addresses, IP addresses, and phone numbers are redacted by default.
