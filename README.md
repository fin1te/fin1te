<a href="https://fin1te.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
    <img src="assets/banner-light.svg" alt="Rishabh Mehta, Cloud & Data Engineer at Jio Platforms. I build data platforms and cloud infrastructure, then make them smaller." width="100%" />
  </picture>
</a>

I'm Rishabh, a cloud and data engineer on the Jio Cloud team at Jio Platforms, Mumbai. Most of my work is infrastructure nobody sees until it breaks: data platforms, streaming pipelines, analytics at telecom scale, and lately the cloud and network layer of an AI datacenter.

**Right now:** building cloud infrastructure and networking for India's largest AI datacenter from the ground up. That means BlueField-3 DPUs provisioned out-of-band over Redfish, a self-hosted WireGuard mesh into GPU pods, and Temporal and Crossplane workflows that automate firewall changes on F5 BIG-IP.

### Selected work

| | |
| :-- | :-- |
| **Spark → Rust** | Designed DataCraft, a Rust ETL framework and SDK, and moved real-time log parsing for 17 application groups off Spark. The MyJio pilot went from 480 cores to 10; the fleet from 8.7 TB of executor RAM to under 200 GB. |
| **Structured Streaming** | Migrated our in-house Spark framework and the 400+ production jobs on it from DStreams to Structured Streaming, about 25% more throughput per core. Built a custom Spark UI into the framework for per-batch history and real Kafka lag. |
| **ClickHouse at scale** | IPDR analytics on 200+ PB with tables past two trillion rows. Co-located sharding for zero-shuffle joins, sub-20 ms subscriber lookups, on roughly a tenth of the servers first planned. |
| **SLA engine** | The daily Spark job that decides which seconds of downtime count against cloud SLAs: HA pairs checked second by second, silent outages back-dated, change windows cut out. |
| **AI cloud infra** | Zero-trust bare-metal onboarding through DPUs, Bastion-as-a-Service, and end-to-end ACL automation across tenant route domains. |

Almost all of this is internal, so the code isn't here. The architecture diagrams and the numbers behind them are on **[fin1te.com](https://fin1te.com)**.

### Writing

- [Moving 400+ Spark jobs from DStreams to Structured Streaming](https://fin1te.com/writing/dstream-to-structured-streaming)
- [Building the Spark UI that Structured Streaming should have had](https://fin1te.com/writing/a-spark-ui-for-structured-streaming)
- [Replacing a 480-core Spark job with 10 cores of Rust](https://fin1te.com/writing/spark-to-rust)
- [Sub-20 ms lookups on trillion-row tables: ClickHouse sort keys in practice](https://fin1te.com/writing/clickhouse-sort-keys)
- [The 497-day bug](https://fin1te.com/writing/the-497-day-bug)
- [How a cloud SLA is actually calculated](https://fin1te.com/writing/how-cloud-slas-are-calculated)

### What I work with

**Every day:** Rust · Scala · Python · SQL · Apache Spark · Kafka · ClickHouse · Kubernetes · Docker · Azure DevOps

**Infrastructure:** NVIDIA BlueField-3 · DOCA DPF · Redfish · WireGuard / Headscale · F5 BIG-IP · Temporal · Crossplane · OpenTofu · KubeVirt · OVN-Kubernetes

**Data & observability:** Elasticsearch · Oracle · PostgreSQL · Trino · Prometheus · Grafana · Superset · Vector · Fluent Bit

The full list, with how deeply I know each one, is at [fin1te.com/stack](https://fin1te.com/stack).

### Before Jio

I spent college writing Android apps and running developer communities. I was Google Developer Student Clubs Lead at PHCET (2021–22), a GirlScript Summer of Code project admin, a Google Android Educator, and lead organiser of the HackOverflow national hackathon, for which I also [built the app](https://github.com/fin1te/HackOverflow-Android). I graduated in Computer Engineering with a 9.3 CGPA. The older repos on this profile are from that time.

### Elsewhere

[fin1te.com](https://fin1te.com) · [LinkedIn](https://www.linkedin.com/in/fin1te) · [X](https://x.com/rishabh_apk) · [rishabhmehta00@gmail.com](mailto:rishabhmehta00@gmail.com)
