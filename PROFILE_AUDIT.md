# GitHub profile audit

Audit date: 2026-09-19  
Account reviewed: [HarishNamasivayamM](https://github.com/HarishNamasivayamM)  
Scope: public repository metadata, repository READMEs, the supplied portfolio workspace, and reachable project/demo links.

## Executive recommendation

Lead with a small, coherent set of repositories that shows the progression from governed data foundations to analytics products and grounded AI systems. The new profile README uses that story rather than mirroring the account's chronological order.

The account currently has 14 public repositories, including the profile repository. The strongest public work is concentrated in RetailIQ, FinDocs-RAG, ChurnShield, PartsFlow, CampusGuide-RAG, CTA TransitPulse, RideCast, and Crypto Tweet Impact.

## Recommended six pinned repositories

1. [RetailIQ-retail-data-platform](https://github.com/HarishNamasivayamM/RetailIQ-retail-data-platform) - strongest end-to-end data engineering and analytics architecture.
2. [FinDocs-RAG](https://github.com/HarishNamasivayamM/FinDocs-RAG) - source-aware RAG, hybrid retrieval, citations, evaluation, and security considerations.
3. [ChurnShield](https://github.com/HarishNamasivayamM/ChurnShield) - machine learning connected to Kafka, Snowflake, BI, Docker, and CI.
4. [PartsFlow](https://github.com/HarishNamasivayamM/PartsFlow) - forecasting connected to inventory policy and measurable synthetic backtests.
5. [CampusGuide-RAG-Grounded-Institutional-Knowledge-Assistant](https://github.com/HarishNamasivayamM/CampusGuide-RAG-Grounded-Institutional-Knowledge-Assistant) - deployed multi-domain assistant with routing, retrieval, reranking, and structured search.
6. [cta-transitpulse](https://github.com/HarishNamasivayamM/cta-transitpulse) - compact operational analytics product with an accessible live dashboard.

Strong alternates: [RideCast](https://github.com/HarishNamasivayamM/RideCast-Divvy-Bike-Demand-Forecasting) if forecasting/statistics is a target role; [crypto-tweet-impact](https://github.com/HarishNamasivayamM/crypto-tweet-impact) if research and statistical analysis are a target; [bandaid-maps](https://github.com/HarishNamasivayamM/bandaid-maps) if applied product work and the LA Hacks award are especially relevant.

## Repository-level recommendations

### Highest priority

| Repository | Suggested description | Suggested topics |
| --- | --- | --- |
| RetailIQ-retail-data-platform | End-to-end retail analytics platform with Python validation, Snowflake, dbt, Airflow, dimensional modeling, and Power BI. | `data-engineering`, `analytics-engineering`, `dbt`, `snowflake`, `airflow`, `power-bi`, `data-quality` |
| FinDocs-RAG | Source-aware financial document Q&A with hybrid retrieval, traceable citations, offline evaluation, and Streamlit UI. | `rag`, `document-ai`, `hybrid-search`, `faiss`, `langchain`, `financial-services`, `streamlit` |
| PartsFlow | Forecast-driven parts replenishment system connecting demand backtesting, safety stock, reorder points, and inventory policy simulation. | `demand-forecasting`, `inventory-optimization`, `time-series`, `duckdb`, `streamlit`, `supply-chain` |
| CampusGuide-RAG-Grounded-Institutional-Knowledge-Assistant | Multi-domain institutional RAG assistant with query routing, structured search, hybrid retrieval, reranking, and Streamlit deployment. | `rag`, `llm`, `semantic-search`, `elasticsearch`, `streamlit`, `information-retrieval` |
| cta-transitpulse | Chicago transit analytics pipeline and Streamlit dashboard for route reliability, arrival predictions, heatmaps, and operational KPIs. | `transit-analytics`, `data-pipeline`, `sqlite`, `streamlit`, `plotly`, `python` |

### Next polish pass

- **Fix metadata consistency.** At audit time, 11 of the 13 project repositories had no GitHub description, and only ChurnShield had repository topics. Add descriptions and 5-8 precise topics to the pinned set first.
- **Refresh the PartsFlow demo link.** The Streamlit URL present in the portfolio material returned HTTP 404 during validation. Keep the repository link prominent until a replacement deployment URL is verified.
- **Add a concise project-status line** to each pinned README: `demo`, `local-only`, `synthetic data`, or `external credentials required`. This makes review scope clear immediately.
- **Add a consistent preview image** only where it improves comprehension. Prioritize RetailIQ architecture/data lineage, FinDocs retrieval trace, CTA dashboard, and PartsFlow policy comparison.
- **Keep metric provenance visible.** RetailIQ, PartsFlow, and CTA use synthetic or deterministic demo data; label those numbers in the first screen of each README.
- **Keep live links current.** The portfolio, resume, FinDocs demo, CampusGuide demo, CTA demo, and Crypto Tweet Impact site were reachable during this audit; recheck deployment URLs after future redeployments.

## Repositories to keep secondary

- **RideCast** is technically credible and has a clear fixed-holdout evaluation, but it reads more like a focused academic forecasting project. Keep it visible as an alternate unless forecasting is a primary target.
- **Crypto Tweet Impact** is a polished research snapshot with a useful caution about association versus causation. Keep it discoverable, but do not let it dominate a data-engineering-first profile.
- **Bandaid Maps** is worth keeping public because the demo mode, tests, CI, and LA Hacks award provide strong product evidence; feature it when targeting applied AI/product roles.
- **scalable-food-delivery-database-system** demonstrates relational modeling, SQL safety, and a Flask explorer, but it is less distinctive than the six recommendations above.

## Candidates to archive/private later

Do not delete or rename automatically. Consider archiving or moving out of the public spotlight after confirming they are no longer active:

- **python-primer** - currently has little public-facing context and no clear portfolio narrative.
- **ai110-module1tinker-playlistchaos-starter** - starter/coursework framing is weaker than the project repositories.
- Older duplicate or reconstruction checkouts should remain secondary if a more complete successor is public. In particular, keep the public ChurnShield name consistent even though the implementation package retains the `churnstream` module name for compatibility.

## Profile-level inconsistencies to fix

- The GitHub account bio still says **“Data Science Grad Student at Illinois Institute of Technology.”** Replace it with a concise professional line such as **“Data Engineering · Analytics · Applied AI | Chicago, IL.”**
- Repository names, descriptions, and portfolio names should use the same canonical spellings: `RetailIQ`, `FinDocs RAG`, `ChurnShield`, `PartsFlow`, `CampusGuide RAG`, and `CTA TransitPulse`.
- Keep the profile README's metrics scoped: distinguish professional outcomes from synthetic-data backtests and academic/research results.
- Add topics to the strongest repositories before adding more badges or statistics widgets. Discoverability will improve more from metadata and README clarity than from extra visuals.
- Keep the profile repository itself focused on the README and its supporting files; do not turn it into another project archive.

## Audit evidence

- [GitHub account](https://github.com/HarishNamasivayamM)
- [Portfolio repository README](https://github.com/HarishNamasivayamM/portfolio)
- [RetailIQ README](https://github.com/HarishNamasivayamM/RetailIQ-retail-data-platform)
- [FinDocs RAG README](https://github.com/HarishNamasivayamM/FinDocs-RAG)
- [ChurnShield README](https://github.com/HarishNamasivayamM/ChurnShield)
- [CTA TransitPulse README](https://github.com/HarishNamasivayamM/cta-transitpulse)
- [CampusGuide RAG README](https://github.com/HarishNamasivayamM/CampusGuide-RAG-Grounded-Institutional-Knowledge-Assistant)
- [PartsFlow README](https://github.com/HarishNamasivayamM/PartsFlow)
