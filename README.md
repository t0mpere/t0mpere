# Hello there 🙂

Data Platform Engineer @ [Depop](https://www.depop.com), London. I build and run large-scale batch and streaming data platforms (Spark, Kafka, Flink, Pinot, Iceberg, Delta Lake), and I like making them cheaper, faster and easier to use.

## Writing

- [How we cut our largest Spark pipeline's cost by 52%](https://engineering.depop.com/how-we-cut-our-largest-spark-pipelines-cost-by-52-014faa81d179), Depop Engineering, 2026
- [From click-ops to Claude Code: building an AI-powered Optimizely flag toolkit](https://engineering.depop.com/from-click-ops-to-claude-code-building-an-ai-powered-optimizely-flag-toolkit-c5cf3fc5eef6), Depop Engineering, 2026
- [Data anonymization layer using Snowflake and dbt](https://towardsdatascience.com/data-anonymization-layer-using-snowflake-and-dbt-c5f84e398358), Towards Data Science

## OSS Contributions

### [apache/pinot](https://github.com/apache/pinot)

Release 1.1.0: [Notable Features](https://docs.pinot.apache.org/basics/releases/1.1.0#notable-features)

#### Merged PRs
- Add compression configuration for functionColumnPairs to StarTreeIndexConfigs [#11744](https://github.com/apache/pinot/pull/11744) (2023)
- Support for configuration through environment variables [#12307](https://github.com/apache/pinot/pull/12307) (2024)
- MergeRollupTask config behaviour fix for `output.segment.dir.uri` [#17015](https://github.com/apache/pinot/pull/17015) (2025)

#### Issues
- How to disable forward and inverted index on a BYTES metric column [#11659](https://github.com/apache/pinot/issues/11659)
- Upgrade inconsistency: confusing behaviour with noDictionaryConfig and fieldConfig for enabling compression on raw forward index [#11745](https://github.com/apache/pinot/issues/11745)
- Enable compression on BYTES star-tree index [#11485](https://github.com/apache/pinot/issues/11485)
- Minion batch ingestion scheduling bottleneck [#11282](https://github.com/apache/pinot/issues/11282)
- Minion HLL merge rollup aggregation function [#9971](https://github.com/apache/pinot/issues/9971)

### [pinot-contrib/pinot-docs](https://github.com/pinot-contrib/pinot-docs)

#### PRs
- Dynamic environment configuration documentation [#289](https://github.com/pinot-contrib/pinot-docs/pull/289)
- `aggregationConfigs` example for `starTreeIndexConfigs` [#258](https://github.com/pinot-contrib/pinot-docs/pull/258)
- Note on `noDictionary` compression for metric columns in forward-index.md [#244](https://github.com/pinot-contrib/pinot-docs/pull/244)
- Hint to avoid having too many files in `inputDirURI` [#178](https://github.com/pinot-contrib/pinot-docs/pull/178)

## CV ([PDF](https://github.com/t0mpere/t0mpere/blob/main/tompere_cv.pdf))

### Work
- **Data Platform Engineer @ Depop**, London · Feb 2026 – Present
  - Led the cost optimisation of the company's largest Spark ingestion pipeline (Databricks, Delta Lake), cutting its cost by ~52% without degrading downstream query performance.
  - Built an AI-powered self-service toolkit for A/B-test feature flags (Claude Code, Backstage, GitHub Actions, Python), cutting flag creation time by ~97%; adopted for 50% of new flags within weeks.
- **Data Platform Engineer @ Bumble Inc.**, London · Apr 2022 – Jan 2026
  - Designed a cloud lakehouse architecture (Iceberg, Polaris, Kafka, Flink, Spark on GCP) to migrate a 200+ node on-prem Hadoop/YARN cluster.
  - Technical leadership for the data platform team; mentored Data and Analytics Engineers and led knowledge sharing across the data org.
  - Rebuilt the backend of the in-house data discovery tool on Apache Pinot, owning research, system design, GKE provisioning, deployment, data generation and UI redesign: >10x faster page responses.
  - Built in-house platform tooling: DDL schema generators, schema registry, client SDKs, orchestrators and UIs (Java, Python, TypeScript, PHP).
  - Maintained hybrid PB-scale data infrastructure on the on-call rotation (Kafka, Hadoop, Spark, Snowflake, ClickHouse, Pinot); ran high-availability Airflow on Kubernetes.
- **Data Engineer @ HousingAnywhere**, Rotterdam · Aug 2020 – Mar 2022
  - Restructured the Snowflake data warehouse schema, designed its permission model and built the dbt anonymisation layer.

### Education
- Politecnico di Milano · MSc & BSc in Computer Science Engineering · 2015 – 2021
