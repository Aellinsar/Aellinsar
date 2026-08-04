### Matthew Griffin
[cite_start]**Senior / Staff Full-Stack Engineer** (15+ yrs) — *Backend Heavy & UI/UX Systems* [cite: 3051, 3055]

[cite_start]📍 **Location:** Valencia, Spain (US Citizen) [cite: 3052]  
[cite_start]💳 **US Remote Work Compliance:** Fully compliant for US W2 remote payroll via Form CA3822 (US-Spain Totalization Agreement; zero foreign entity overhead for US employers)[cite: 3052, 3114]. [cite_start]Digital Nomad Visa (DNV) eligible[cite: 3053, 3114].

---

### Experience

* **SS&C Advent Black Diamond** | [cite_start]*Senior Software Engineer* [cite: 3090]
  * **Core APIs:** Core engineer (1 of 3) maintaining foundational domain microservices (Accounts, Portfolios, Users, Firms) on Kubernetes.
  * [cite_start]**Postgres Partitioning & CDC:** Rearchitected auditing off legacy SQL Server onto multi-level declarative PostgreSQL partitions (`Date Range` → `Change Domain`) using `jsonb`[cite: 3093]. [cite_start]Built C# CDC ingesters (1 per zone) using `COPY` and `INSERT ON CONFLICT` bulk writes[cite: 3094].
  * [cite_start]**Autoscaling & Migration:** Handled high message volume using KEDA queue-depth triggers on RabbitMQ, scaling pods from 1 to 16 max[cite: 3096]. [cite_start]Migrated 100M+ legacy MongoDB audit records directly into PostgreSQL partitions in under 30 minutes via `INSERT INTO ... SELECT`[cite: 3097].
  * [cite_start]**Observability:** Built custom Prometheus metrics and Grafana dashboards tracking zone/domain metrics to isolate batch database slowdowns[cite: 3095].

* **Outcomes / Cardinal Health** | [cite_start]*Staff Engineer* [cite: 3099]
  * [cite_start]**High-Surge Claims Engine:** Architected a 2-stage Transactional Inbox processing engine absorbing 10,000+ claims/min with 100x surge headroom on cost-effective AWS Spot instances using Spring Boot, AWS SQS FIFO, and Aurora PostgreSQL[cite: 3101, 3102, 3103].
  * **Upstream Re-Architecture:** Re-architected upstream Java integration engine (SRM) in under 1 week, resolving thread starvation, memory leaks, and sequence ordering bugs to scale throughput from 10 msgs/min to 100s msgs/sec.
  * [cite_start]**ACH Payment Rails:** Engineered financial payment distribution pipelines delivering ISO 20022 payloads to JPMorgan Chase using Apache Camel, `mwiede/jsch`, and BouncyCastle PGP encryption[cite: 3104].
  * [cite_start]**OS Boundary Diagnostics:** Diagnosed and resolved socket leaks and file descriptor handle leaks under sustained heavy load using `lsof`, JVM heap/thread dump analysis, and connection pool optimization[cite: 3105].

* **Westell Technologies / Kentrox** | [cite_start]*Senior Software Engineer* [cite: 3107]
  * [cite_start]**Async Telemetry Collector:** Re-architected asynchronous SNMP v3 polling engine using non-blocking I/O sockets, querying 1,500 rectifiers in under 4 seconds[cite: 3109, 3110].
  * [cite_start]**NOC UI Systems:** Built Sencha Ext JS network visualization dashboards using DOM recycling and client memory management to eliminate browser memory leaks during continuous updates[cite: 3109, 3111].

* **Professor Arwam** | [cite_start]*Independent Full-Stack AI Architect* [cite: 3082]
  * [cite_start]**Client-Side GenAI Engine:** Built a zero-backend, pure client-side React 19 / TypeScript application orchestrating Google Gemini REST APIs directly in-browser[cite: 3084, 3085].
  * [cite_start]**Stream Parsing & OCR:** Built a custom stream tokenizer parsing Markdown into rich UI cards mid-stream [cite: 3085][cite_start], HTML5 Canvas image compression [cite: 3086][cite_start], LLM multi-modal vision/OCR extraction [cite: 3086][cite_start], and serverless Google Drive OAuth2 state persistence[cite: 3088].

---

### Stack

* [cite_start]**Languages & Runtimes:** Java (8, 11, 17, 21), C# (.NET Core / Framework), TypeScript, JavaScript (ES6+), SQL, Python, Bash / Shell Scripting [cite: 3059]
* [cite_start]**Backend & Systems:** Spring Boot, Spring Cloud, ASP.NET Core, Hibernate / JPA, MyBatis, Enterprise Integration Patterns (EIP), Apache Camel [cite: 3059]
* [cite_start]**Messaging & Cloud:** AWS (SQS FIFO, Aurora, Spot Resilience), Kubernetes (K8s), KEDA Autoscaling, RabbitMQ, Docker, GitHub Actions CI/CD [cite: 3059]
* [cite_start]**Databases:** PostgreSQL (Declarative Multi-Level Partitioning, `jsonb`, `COPY` Bulk Import), AWS Aurora PostgreSQL, Microsoft SQL Server (CDC), MongoDB [cite: 3059]
* [cite_start]**OS Diagnostics & Security:** `lsof` Handle Leak Triage, Connection Pool Tuning, JVM Heap / Thread Dump Analysis, GC Tuning, Dropwizard Metrics, ISO 20022, PGP Cryptography (BouncyCastle), SFTP / SSH (`mwiede/jsch`), OWASP XSS Remediation [cite: 3059]
* [cite_start]**Frontend:** React 19, TypeScript, Sencha ExtJS (DOM Recycling), HTML5 Canvas Compression, Google Gemini REST API Orchestration, Google Drive OAuth2 API [cite: 3059]
