# Sabyh Ahmad

<p align="left">
    <a href="https://git.io/typing-svg">
        <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono+Nl&size=23&duration=1&color=F6C177&vCenter=true&repeat=false&width=435&lines=Sabyh+Ahmad" alt="Typing SVG" />
    </a>
</p>

**`Producer of Bugs (Software Engineer)`**  
**Senior Backend, Data & AI Platform Engineer** — Specializing in cloud-native microservices, event-driven data pipelines, serverless AI platforms, and real-time collaboration systems.

📧 **sabyhahmed@outlook.com** • 📍 **Lahore, Pakistan**  
🔗 [LinkedIn](https://www.linkedin.com/in/sabyh/) • [Portfolio](https://sabyh-ahmad.netlify.app/) • [YouTube](https://www.youtube.com/channel/UCWam55wUh-OOcvrGJisq0zA)

---

## 👨‍💻 Professional Summary

Lead Backend Developer with **8+ years** of experience designing and shipping cloud-native microservices, serverless AI platforms, and real-time collaboration infrastructure on **AWS** and **GCP**. Specialist in **Go** and **TypeScript** with deep, production-proven expertise in:

- **LLM Integration**: AWS Bedrock, OpenAI, Gemini — provider-agnostic orchestration with tool/function-calling
- **Vector Search**: Weaviate, pgvector, hybrid semantic + keyword retrieval for AI-powered search
- **Data & Analytics**: AWS Athena, Glue Catalog, event-driven pipelines, analytics-ready datasets
- **Multi-Agent Orchestration**: Building scalable AI systems with deterministic dialog control
- **Cloud Infrastructure**: AWS CDK, Terraform, Kubernetes (CKA certified)

Track record of leading architecture decisions across high-complexity platforms — from **AR/VR enterprise collaboration** and **blockchain analytics** to **franchise intelligence** and **AI-powered real estate systems**.

---

## 🏆 Certifications

- **CKA** — Certified Kubernetes Administrator
- **AWS Solutions Architect** — Associate
- **AWS Developer** — Associate  
- **Microsoft AZ-204** — Developer Associate
- **Microsoft AZ-900 & AI-900** — Azure Fundamentals
- **Azure Machine Learning** — Nanodegree

---

## 🛠️ Core Skills

| Category | Technologies |
|----------|--------------|
| **Languages** | Go, TypeScript, JavaScript, Python, Node.js |
| **Backend Frameworks** | Fiber (Go), Express.js, Fastify, NestJS, REST, gRPC, WebSocket, SSE, Socket.IO |
| **AI / LLM** | AWS Bedrock (Claude, Titan), OpenAI, Gemini, Weaviate, pgvector, RAG pipelines, Prompt Engineering, Function Calling |
| **Databases** | PostgreSQL (pgx / Aurora), MongoDB, DynamoDB, Redis, MySQL |
| **AWS Services** | Lambda, API Gateway, SQS, SNS, S3, Bedrock, Lex, CloudWatch, CDK, ECR, EKS, App Runner, ECS Fargate, RDS Postgres, Route53, VPC, Secrets Manager, SageMaker, Polly, SES |
| **DevOps / Infra** | Docker, Kubernetes (CKA), Terraform, AWS CDK, GitHub Actions (CI/CD, blue/green), GitLab CI, SonarQube, Grafana, Cloudflare DNS |
| **Other** | OAuth 2.0, SAML SSO, PKCE, JWT, Photon Realtime, multi-tenancy, structured logging, observability, incident response, secrets management |

---

## 💼 Professional Experience

### Lead Backend Developer — Arthur Digital (Jun 2022 – 2026)
*Enterprise AR/VR collaboration platform for immersive remote meetings & training*

- Led design and delivery of **5 production backend systems** (AI agents, semantic search, real-time collaboration, SSO, serverless infra) maintaining **99.9% uptime**.
- Architected a **provider-agnostic LLM orchestration layer** (AWS Bedrock, OpenAI, Gemini) with tool/function-calling for deterministic dialog control, serving multi-turn AI meeting bots.
- Built a **multi-tenant AI document search platform** ingesting PDF, DOCX, Excel, images into Weaviate with hybrid semantic + keyword retrieval.
- Engineered **multi-environment serverless infrastructure** using AWS CDK (TypeScript) with Lambda dependency graphs, IAM wiring, X-Ray, and CloudFormation exports.
- Implemented **flexible SSO** (Google, Microsoft, OAuth2, PKCE/Cognito) with JWT-based role-aware access control for enterprise multi-tenancy.
- Led **AWS → GCP infrastructure migration** automated via Terraform & GitHub Actions; introduced SonarQube quality gates, improving test coverage by 15% and **reducing release cycle time by 60%**.

### Senior Backend & AI Engineer (Contract) — Innovative (2025 – 2026)
*Franchise intelligence platform turning KPI data into AI-powered insights*

- Architected AI/LLM orchestration on **AWS Bedrock (Claude 3 Haiku)** to auto-generate KPI narrative summaries with async job handling via SQS.
- Delivered **7 Dockerized Lambda microservices** (KPI Writer, Catalog, Watchlist, Alerts, LLM Orchestration, Scheduler) fronted by API Gateway with unified event-routing.
- Built automated **Watchlist Scheduler** (EventBridge cron) pulling data from Aurora PostgreSQL, generating AI snapshots, and dispatching HTML email reports with PDF attachments via SES — with SNS alerting and DLQ error handling.
- Provisioned all infrastructure with **modular Terraform** across dev/prod, cutting environment setup from days to minutes.

### Senior Backend Developer — Big Immersive / Virtua (Nov 2018 – Jun 2022)
*NFT Marketplace & Blockchain Analytics*

- Built event-driven auction scheduler (SNS + SQS + Lambda) handling **50,000+ concurrent bids** with guaranteed delivery.
- Reduced listing API P95 latency from **900 ms → 180 ms (80% improvement)** via query optimisation and page-level caching.
- Architected **Blockchain Eye ETL pipeline** ingesting multi-chain data into Athena/Parquet data lake, enabling scalable analytics.
- Built a **WebSocket gateway** for real-time notifications (TypeScript + API Gateway), removing client polling and reducing server load significantly.

---

## 🔬 Key Projects

### AI Vibe Agent — Meeting Intelligence Bot
*Go · AWS Lambda · Bedrock · OpenAI · Gemini · Redis · S3 · Polly*
- Serverless Go service supporting multi-turn interview/meeting bots with strict, balanced, and freeflow conversation modes.
- Provider-agnostic LLM adapter/factory with tool/function-calling (`request_clarifier`, `redirect_to_topic`, `endConversation`) for deterministic, safe dialog control.
- Redis-backed session state with TTLs, pipelines, and idempotent resets — managing message history, question progress, and AI config across concurrent sessions.
- LLM-based structured note extraction and edit-note command parser; multilingual transcript support via LLM translation with JSON schema preservation.
- Integrated AWS Polly TTS (Neural → Standard fallback) for real‑time client delivery.

### AI Document Search Platform
*Python · AWS Bedrock (Titan) · Weaviate · MongoDB · Lambda · SQS · Terraform*
- End-to-end AI search pipeline: ingestion of PDF, DOCX, Excel, images → MongoDB → Bedrock embeddings → Weaviate with per‑tenant isolation.
- Hybrid semantic + keyword search API combining vector similarity with tenant-scoped filters, ensuring strict data isolation while preserving retrieval quality.
- Idempotent ingestion pipeline handling INSERT/UPDATE/DELETE across multiple collections with configurable chunking, retry logic, and DLQ error handling.

### Bode Real Estate AI — Serverless Infrastructure
*AWS CDK TypeScript · Lambda · Bedrock Agents · Lex · Node.js 20.x*
- Designed reusable `BodeInfraStack` provisioning Lambdas, IAM, logging, and tagging across dev/staging/prod with environment-specific configs (timeouts, memory, concurrency, log retention).
- Implemented Lambda factory pattern (`LambdaFactory` + `CustomLambdaFunction`) standardising Node.js 20.x provisioning — runtime, bundling, X‑Ray toggles, tagging, env injection.
- Modelled Lambdas as dependency graphs with automatic fine‑grained IAM invoke permissions and ARN injection, enabling agent-style orchestration without hard‑coded wiring.

### Arthur Vibe Platform — Go REST API
*Go · Fiber · PostgreSQL (pgx) · MongoDB · pgvector · OpenAI · Gemini · JIRA · S3*
- Production Go (Fiber) REST API managing vibe/scenario lifecycle, meetings, pipelines, rooms, analytics, and real‑time SSE + WebSocket endpoints with JWT auth.
- Dual‑database architecture (PostgreSQL + MongoDB, selectable via DB_TYPE), repository pattern, rate limiting, and standard middleware stack.
- Integrated LLM providers for chat API with meeting context and vector Q&A over meetings using pgvector; built JIRA integration with tool‑style function calling for AI‑driven task management.

### Innovative Franchise Platform — DevOps & Infrastructure
*Terraform · GitHub Actions · ECS Fargate · App Runner · RDS Postgres · Secrets Manager · Route53 · VPC · Cloudflare*
- Owned AWS infrastructure across production, beta, and nonprod — App Runner, ECS Fargate, ECR, RDS Postgres with automated snapshot DR.
- Authored GitHub Actions CI/CD pipelines with pre‑deploy gates, post‑deploy health checks, E2E smoke tests, and blue/green cutover patterns.
- Led Terraform‑only IaC migration (sunsetting CDK) with modular workspaces, one‑command environment setup, and full secrets lifecycle via Secrets Manager.
- Managed Cloudflare + Route53 DNS cutovers under live traffic; debugged VPC, security group, and secret ARN issues with postmortems within 48 hours.
- Implemented monitoring/alerting with CloudWatch alarms, Grafana dashboards, and structured logging — every customer‑facing flow alarmed and paged.

### Innovative Franchise Intelligence — AI FBC Platform
*Go · Python · Aurora PostgreSQL · MongoDB · Bedrock · EventBridge · SES · Terraform*
- Designed microservice architecture in Go (Fiber) and Python with repository pattern across PostgreSQL, MongoDB, and Aurora PostgreSQL.
- Built Watchlist Scheduler pipeline (EventBridge cron → Aurora → Bedrock → SES/ReportLab PDF) fully automating franchise KPI reporting with SNS alerting and DLQ-based failure handling.

---

## 📊 GitHub Stats

![Most Used Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Sin-cy&layout=compact&theme=rose_pine&show_icons=true)

---

## 📫 Let's Connect!

<p align="left">
    <a href="https://www.linkedin.com/in/sabyh/" target="_blank">
        <img width="48px" alt="LinkedIn" title="LinkedIn" src="https://img.icons8.com/fluency/48/linkedin.png" />
    </a>
    &#8287;&#8287;&#8287;&#8287;&#8287;
    <a href="https://sabyh-ahmad.netlify.app/#contact" target="_blank">
        <img width="48px" alt="Contact" title="Website Contact" src="https://cdn-icons-png.flaticon.com/128/3296/3296464.png" />
    </a>
    &#8287;&#8287;&#8287;&#8287;&#8287;
    <a href="https://www.youtube.com/channel/UCWam55wUh-OOcvrGJisq0zA" target="_blank">
        <img width="48px" alt="YouTube" title="YouTube" src="https://img.icons8.com/fluency/48/youtube-play.png" />
    </a>
</p>

- 📧 **Email**: [sabyhahmed@outlook.com](mailto:sabyhahmed@outlook.com)
- 🔗 **LinkedIn**: [linkedin.com/in/sabyh](https://www.linkedin.com/in/sabyh/)
- 🌐 **Portfolio**: [sabyh-ahmad.netlify.app](https://sabyh-ahmad.netlify.app/)
- 📺 **YouTube**: [@SabyhAhmad](https://www.youtube.com/channel/UCWam55wUh-OOcvrGJisq0zA)

---

### 🎯 What I'm Currently Up To

- Building AI-powered platforms with multi-agent orchestration and RAG pipelines.
- Exploring advanced LLM integration patterns and provider-agnostic abstractions.
- Contributing to open-source, creating tech content, and sharing insights on system design.
- Deepening expertise in cloud-native infrastructure and observability.

---

<p align="center">
    <i>Building the future, one cloud-native microservice at a time 🚀</i>
</p>
