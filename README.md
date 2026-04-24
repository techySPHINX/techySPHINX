<p align="center">
  <img src="./logo/banner1.png" alt="Banner" style="max-width: 100%; height: auto; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</p>

<h1 align="center">🙏 नमः विद्या! 👋</h1>

<h3 align="center">Backend Systems Engineer · Data Infrastructure Architect · DevOps Practitioner · Open Source Contributor</h3>

<p align="center">
  <a href="#-about-me"><img src="PNG/About.png" width="100"/></a>
  <a href="#-experience-highlights"><img src="PNG/Stats.png" width="100"/></a>
  <a href="#-connect-with-me"><img src="PNG/social.png" width="100"/></a>
</p>

---

## About Me

I'm a **Computer Science undergraduate** who builds systems at the intersection of **backend engineering, data infrastructure, and AI**. My work lives in the space where raw data transforms into business intelligence — and where distributed systems must remain correct under pressure.

My obsession is **data flow**: how information moves, transforms, gets validated, aggregated, and ultimately surfaces as actionable business metrics. Whether it's a real-time GPS telemetry pipeline processing 50,000 events per second, an enterprise payment ledger with zero-tolerance for duplicate charges, or a deep learning inference service with sub-100ms latency — I architect these systems with a single standard: **production-grade correctness, always**.

I've delivered across **government maritime surveillance, fintech payment orchestration, AI-powered automation, and data engineering consulting**. I've handled multiple client engagements as a freelancer, navigating ambiguous requirements, tight SLAs, and stakeholder communication alongside the engineering itself.

**What genuinely excites me:**
- The elegance of a perfectly modeled data pipeline
- Business metrics that are *trusted* because the data infrastructure beneath them is bulletproof
- Neural network architectures applied to real operational problems
- Systems that are still running flawlessly three years after I've moved on

> *"The goal is not just working software — it's infrastructure that becomes an organizational asset, where data integrity is non-negotiable and scale is an afterthought."*

📫 `jaganhotta357@outlook.com`

---

## Experience

| Role | Organization | Period | Focus |
|------|-------------|--------|-------|
| 🔵 **Data Engineering Intern** | Deloitte | Current | Data pipelines, ETL/ELT orchestration, cloud data warehousing, business metrics infrastructure |
| 🟢 **Freelance Backend & Data Engineer** | Odisha Coastal Police (Maritime Platform) | Ongoing | Government-grade real-time surveillance — 50,000+ GPS updates/sec, Kafka, TimescaleDB, Kubernetes, PostGIS |
| 🟢 **Contributor** | HCW-HOME | Jun 2025 – Oct 2025 | NestJS, WebRTC, Mediasoup, Prisma, WebSockets, Kubernetes |
| 🟡 **Cloud Lead** | E-Labs | Jan 2025 – Present | Git workflows, CI/CD, Infrastructure as Code, monitoring dashboards |
| 🟣 **Software Engineer** | ConvertAPI | Past | FastAPI, TDD, microservices architecture |
| 🟢 **DevOps Intern** | LectureNotes | Past | Docker, AWS, Jenkins, automated deployments |
| 🔴 **Backend Developer** | Zinfytech | Past | API backends, workflow optimization |
| 🟠 **Apprentice** | Quant Finance Cohort 2024 | 2024 | Statistical modeling, Python, financial analytics |

---

## Featured Projects

### 🏦 [AegisPay](https://github.com/techySPHINX/aegispay) — Enterprise Payment Orchestration Platform
An event-sourced, distributed payment processing system engineered for **10,000+ TPS** with mathematical guarantees against duplicate charges.

**Architecture highlights:** Distributed locking via Redis (Redlock), CQRS with full event sourcing, intelligent gateway routing with automatic failover, idempotency keys at every API boundary, PostgreSQL with optimistic concurrency control. The system treats financial correctness as a hard invariant — not a soft requirement.

**Business impact:** Zero duplicate charge incidents, deterministic audit trail for every transaction, designed for regulatory compliance from day one.

`Go · PostgreSQL · Redis · Kafka · Docker · Event Sourcing · CQRS`

---

### 🚢 Odisha Coastal Police Maritime Surveillance Platform *(Freelance)*
A government-grade, real-time maritime situational awareness system protecting **10,000+ active fishermen** along the Odisha coastline.

**Architecture highlights:** Kafka-based ingestion layer handling **50,000+ GPS telemetry events/second**, TimescaleDB for time-series storage and compression, PostGIS for geospatial analytics and zone-breach detection, Kubernetes for zero-downtime deployments, Prometheus/Grafana observability stack with custom operational dashboards.

**Data pipeline design:** Raw GPS → Kafka partitioned by vessel ID → stream processing for anomaly detection → TimescaleDB with hypertable partitioning → real-time WebSocket push to operator dashboards. Every layer optimized for throughput with sub-second end-to-end latency.

`Python · Kafka · TimescaleDB · PostGIS · Kubernetes · WebSockets · Grafana`

---

### 🤖 [Nexus](https://github.com/techySPHINX/Nexus) — AI-Enhanced Student Collaboration Network
A full-stack student networking platform combining real-time communication infrastructure with **AI-powered features**: intelligent content recommendations using embedding-based similarity search, automated moderation using fine-tuned classification models, and a RAG-based knowledge assistant trained on academic resources.

**Technical depth:** WebSocket-based messaging with Redis pub/sub fanout, JWT + RBAC authentication, PostgreSQL/Prisma backend, LangChain integration for semantic search, vector embeddings stored in pgvector, deep learning text classification pipeline for content quality scoring.

`TypeScript · NestJS · PostgreSQL · Redis · LangChain · pgvector · WebSockets · PyTorch`

---

### 🧠 Deep Learning & AI Systems *(Research & Production)*
A collection of applied AI/ML work spanning computer vision, NLP, and intelligent automation:

- **Neural Network Pipelines**: End-to-end training pipelines with MLflow experiment tracking, automated hyperparameter tuning, and model versioning — designed for reproducibility and production deployment
- **RAG Architectures**: Retrieval-augmented generation systems with custom chunking strategies, embedding model fine-tuning, and hybrid dense-sparse retrieval
- **LLM Integration Layer**: Multi-provider abstraction (OpenAI, Anthropic, local models) with semantic caching, token budget management, and structured output validation using Pydantic
- **Data-Driven ML Ops**: Feature stores built on Apache Arrow/Parquet, training data versioning with DVC, automated drift detection on production models

`Python · PyTorch · TensorFlow · LangChain · MLflow · DVC · Hugging Face · FastAPI`

---

### 📊 Data Infrastructure & Business Intelligence Work
Recurring theme across client engagements: organizations have data but lack the infrastructure to trust it.

- **ELT Pipelines**: dbt-based transformation layers on top of raw event data, with automated data quality checks (Great Expectations), lineage tracking, and business metric definitions as code
- **Streaming Analytics**: Flink/Kafka Streams jobs computing real-time business KPIs — revenue per cohort, funnel conversion, churn signals — with sub-minute latency
- **Observability as Data**: Custom Prometheus exporters turning application behavior into structured business metrics, feeding executive dashboards built in Grafana
- **Data Contracts**: Schema registry enforcement across microservice boundaries to prevent silent data corruption in distributed pipelines

`Apache Kafka · dbt · Apache Flink · Airflow · Prometheus · Grafana · PostgreSQL · TimescaleDB · Parquet`

---

## Current Focus

- ☁️ **Advanced Data Engineering at Deloitte** — cloud-scale ETL, data warehousing patterns, business metric instrumentation
- 🧠 **Deep Learning Applications** — applied neural networks for time-series forecasting and anomaly detection in operational data
- 🤖 **AI Agents & MCP** — building autonomous agents with structured memory, tool use, and semantic reasoning capabilities
- 🕸️ **Web3 Infrastructure** — full-stack dApp development with Next.js + StarkNet, exploring on-chain data pipelines
- 📐 **Systems Design** — daily study of distributed systems papers, database internals, and consensus algorithms
- 🧩 **Competitive Programming** — C++ STL, template meta-programming, algorithmic problem solving

---

## Achievements

- 🥈 **Runner-up** — Smart India Hackathon 2024 (SIH'24)
- 🌟 **Selected Contributor** — C4GT-DMP-2025 @ Iabsis (open-source)
- 🚀 **Selected** — KPI Fellowship Program 2025
- 🏆 **Finalist** — Buildfest 2025
- 📊 **Apprentice** — Quant Finance Cohort 2024
- ☁️ **Cloud Lead** — E-Labs, driving technical community workshops
- 🤝 **Member** — Google Developer Group Cloud Bhubaneswar
- 👨‍💻 Professional experience across Deloitte, ConvertAPI, LectureNotes, Zinfytech

---

## Tech Stack

**Languages**
`C++ · Go · Python · TypeScript · JavaScript · Java · Solidity · SQL`

**Backend & APIs**
`NestJS · FastAPI · Express · Node.js · Flask · gRPC`

**Data & AI**
`Apache Kafka · Apache Flink · Apache Airflow · dbt · TimescaleDB · PostgreSQL · Redis · MongoDB · Supabase`
`PyTorch · TensorFlow · LangChain · Hugging Face · MLflow · DVC · pgvector · Apache Arrow`

**Cloud & DevOps**
`AWS · GCP · Azure · Kubernetes · Docker · Terraform · Helm · GitHub Actions · Jenkins · GitLab CI`

**Observability**
`Prometheus · Grafana · OpenTelemetry · Jaeger`

**Frontend**
`React · Next.js · Angular · Redux`

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=techySphinx&rank_icon=percentile&bg_color=0000&text_color=aaa&title_color=70a5fd&icon_color=70a5fd&show_icons=true&border_color=0d1117&border_radius=20" alt="GitHub Stats" width="47%"/>
&nbsp;
<img src="https://streak-stats.demolab.com/?user=techySphinx&theme=tokyonight&hide_border=true&border_radius=0&background=FFFFFF00&hide_longest_streak=true" alt="GitHub Streak" width="47%"/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=techySphinx&theme=radical&hide_border=true" width="96%"/>

</div>

---

<div align="center">

*Building systems where data integrity is non-negotiable, scale is engineered from the start, and every business metric has a trustworthy pipeline behind it.*

**If something here resonates — let's build something that matters.**

💬 Always open to conversations, collaborations, and hard engineering problems.

</div>

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=170&section=footer&fontSize=42&fontColor=fff&animation=twinkling"/>
