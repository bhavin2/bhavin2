<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/timeline-dark.svg" />
  <img src="./assets/timeline-light.svg" alt="Bhavin Shah: career timeline" width="100%" />
</picture>

## The story so far

I worked on a Video Management System for Cisco, developing a Windows ActiveX control and RTSP client. I architected IoT ingestion pipelines supporting approximately 1 million smart water meter devices using Azure DPS and IoT Hub, and ran more than 50 performance and load tests on REST APIs and SQL stored procedures, improving API response times by 25%. I've worked across firmware, Android HMI, connectivity, and cloud microservices.

At Whirlpool I develop Android-based smart-appliance software—cooking controls, timers, state management, provisioning, claiming, Wi-Fi configuration, factory reset, and commercial laundry connectivity using AWS IoT Core. I troubleshoot device-to-device and system integration issues by analyzing logs, appliance events, and communication sequences, collaborating with firmware, hardware, connectivity, cloud, and product teams. I'm developing an agentic AI log-analysis and root-cause-analysis system using LLMs, RAG, LangGraph, and vector databases. I designed and delivered ArrowGPT—an enterprise generative AI application on Azure OpenAI with RAG-based, citation-backed responses serving 20K daily users with average response time under 200 ms, improving application performance by 35%.

## Milestone work

| Initiative | Scope | Outcome |
|-----------|-------|---------|
| Smart Cooking Appliance | Android HMI, appliance connectivity, provisioning, claiming, Wi-Fi configuration, factory reset, AWS IoT Core integration for commercial laundry | Delivered connected smart-appliance platform with device-to-device integration, state synchronization, and commercial laundry connectivity |
| ArrowGPT | Enterprise generative AI with Azure OpenAI, RAG pipelines, Azure AI Search, ASP.NET Core REST APIs, OAuth 2.0/JWT auth, AngularJS UI | Served 20K daily users with average response time under 200 ms, improved performance by 35% |
| Smart Water Meter Platform | Azure IoT Hub, DPS, Stream Analytics, Functions, Databricks, Spark, Kafka, Cosmos DB, SQL Database, Data Lake, ETL/ETP pipelines | Architected ingestion pipelines supporting approximately 1 million devices, ran more than 50 performance tests, improved API response times by 25% |
| Snapbricks Gateway Framework | Azure IoT stream processing, Wi-Fi/Bluetooth device discovery, Vue.js SPA, firmware updates, REST APIs, CI/CD automation | Shipped device-management framework with real-time data binding, responsive UI, and automated backend deployments |
| Video Management System | Windows ActiveX control, RTSP streaming, H.264/MJPEG codecs, PTZ joystick, cross-browser WebSocket player, FFmpeg integration, Bonjour discovery | Created RTSP audio/video streaming software with cross-browser support and camera discovery tools |
| Secure Building Panels | Multithreaded C#/.NET server, client-server APIs, WPF device-management app, CI/CD pipelines | Developed a multithreaded server application for continuous 24/7 operation and authored unit tests achieving over 90% code coverage |

<details>
<summary>Behind ArrowGPT</summary>

</details>

## Recent builds

| Project | What it does | Stack |
|---------|-------------|-------|
| [tagvault](https://github.com/bhavin2/tagvault) | Process historian for plant telemetry: MQTT Sparkplug B ingest, swinging-door compression with a proven error bound (up to **374x** fewer points on tank-level tags), Gorilla-encoded storage and a crash-safe WAL | Rust, MQTT, Sparkplug B |
| [contextforge](https://github.com/bhavin2/contextforge) | Self-hostable docs answer bot that cites its sources and abstains below a confidence threshold; **0%** hallucination rate on a 30-case eval | TypeScript, Next.js, RAG, pgvector |
| [driftguard-llm](https://github.com/bhavin2/driftguard-llm) | RAG service with query-embedding drift detection (PSI, KS, centroid) and LLM-as-judge scoring that raise alerts and trigger re-embedding | Python, FastAPI, Prometheus, Grafana |
| [streamguard-cdc](https://github.com/bhavin2/streamguard-cdc) | Change-data-capture pipeline: Postgres WAL → Debezium → Kafka → Python stream processor (dedupe, schema evolution, windowed aggregation) → ClickHouse | Python, Kafka, Debezium, ClickHouse |
| [enterprise-employee-portal](https://github.com/bhavin2/enterprise-employee-portal) | HR self-service for leave, timesheets, documents and the org chart, with two-stage approval and a gated Jenkins pipeline with blue-green deploys and automatic rollback | Angular, Node.js, MySQL, Jenkins |

## Credentials

- **Bachelor of Engineering**, Computer Engineering – Gujarat University
- **Azure AI Fundamentals (AI-900)** certification

## What's next

[Email](mailto:bhavin44@gmail.com) · [LinkedIn](https://www.linkedin.com/in/bhavin-shah-49726034/) · [GitHub](https://github.com/bhavin2)

## Projects

- [tagvault](https://github.com/bhavin2/tagvault) — A process historian for plant telemetry in Rust, with MQTT Sparkplug B ingest, bounded-error swinging-door compression and a crash-safe write-ahead log.
- [contextforge](https://github.com/bhavin2/contextforge) — A self-hostable docs answer bot that cites its sources and abstains when it isn't sure.
- [driftguard-llm](https://github.com/bhavin2/driftguard-llm) — Catch silent RAG/LLM quality regressions with embedding drift detection and LLM-as-judge scoring.
- [streamguard-cdc](https://github.com/bhavin2/streamguard-cdc) — Change-data-capture pipeline: Postgres WAL → Debezium → Kafka-compatible broker → Python stream processor → ClickHouse.
- [enterprise-employee-portal](https://github.com/bhavin2/enterprise-employee-portal) — HR self-service portal with two-stage leave approval and a gated Jenkins CI/CD pipeline.
- [fwaudit](https://github.com/bhavin2/fwaudit) — Offline firmware image auditor for embedded Linux and IoT that extracts containers in memory under safety limits and reports hardcoded credentials, private…
- [netcode-arena](https://github.com/bhavin2/netcode-arena) — Server-authoritative multiplayer netcode: a 2-player arena with client-side prediction, server reconciliation, and snapshot interpolation, tested under…
- [lsmkv](https://github.com/bhavin2/lsmkv) — An LSM-tree key-value storage engine in Rust with a checksummed WAL and group commit, SSTables with bloom filters, leveled compaction, MVCC snapshots and crash…
- [plugbox](https://github.com/bhavin2/plugbox) — A sandboxed WebAssembly plugin runtime for edge HTTP handlers on wasmtime, with a WIT host interface, deny-by-default capabilities, fuel, epoch and memory…
- [agentguard](https://github.com/bhavin2/agentguard) — Capability-based permission engine for LLM agent tool calls, with YAML policies, argument constraints, taint tracking, human approvals, and a hash-chained…
- [privkit](https://github.com/bhavin2/privkit) — A privacy toolkit for data pipelines covering PII detection, NIST FF1/FF3-1 format-preserving tokenization, k-anonymity and l-diversity, and differential…
- [hybridkem](https://github.com/bhavin2/hybridkem) — ML-KEM (FIPS 203) implemented from the standard in Rust, with an X25519 hybrid KEM, X-Wing, and a Noise-style authenticated handshake; educational and not…
- [logsculpt](https://github.com/bhavin2/logsculpt) — A fast, memory-safe Rust CLI that parses mixed JSON/syslog/plaintext logs into one normalized timeline, flags rate spikes and rare-error clusters, and renders…
- [hnswops](https://github.com/bhavin2/hnswops) — HNSW approximate-nearest-neighbor index written from scratch in Rust, with memory-mapped snapshots, online recall monitoring, and zero-downtime re-embedding…
- [wasmlet](https://github.com/bhavin2/wasmlet) — A from-scratch WebAssembly 2.0 interpreter in safe Rust with a decoder, spec validator, compact IR, WASI preview1 subset and fuel metering.
