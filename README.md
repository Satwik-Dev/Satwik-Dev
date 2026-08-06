<p align="center">
  <img src="header.svg" alt="Satwik Alla - Terminal Header" width="800"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/satwik-alla">
    <img src="https://img.shields.io/badge/-satwik--alla-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:allasatwik4@gmail.com">
    <img src="https://img.shields.io/badge/-allasatwik4-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://portfolio-satwikalla.vercel.app/">
    <img src="https://img.shields.io/badge/-Portfolio-000000?style=flat&logo=github&logoColor=white" alt="Portfolio"/>
  </a>
</p>

---

```python
class SatwikAlla:
    def __init__(self):
        self.role         = "AI Engineer @ Cosmo AGI"
        self.education    = ["MS Software Eng, UMBC (3.91 GPA)", "B.Tech, IIT Bhubaneswar"]
        self.currently    = "Shipping production LLM systems: retrieval, memory, caching, routing, safety"

    def tech_stack(self):
        return {
            "languages":  ["Python", "TypeScript", "JavaScript", "C++", "C", "Java"],
            "backend":    ["FastAPI", "Django REST", "SQLAlchemy", "Alembic", "WebSockets", "JWT"],
            "frontend":   ["Next.js 14", "React 19", "Three.js", "Tailwind CSS"],
            "databases":  ["PostgreSQL", "Redis", "MongoDB", "Supabase"],
            "ai_ml":      ["OpenAI GPT-4o", "Gemini", "RAG", "LangChain", "Embeddings", "Semantic Caching"],
            "vector":     ["Qdrant", "pgvector", "Vector Search", "Top-k Retrieval"],
            "voice":      ["Whisper", "ElevenLabs TTS", "Gemini Multimodal"],
            "streaming":  ["Apache Kafka", "Debezium", "PySpark", "HDFS", "CDC Pipelines"],
            "cloud":      ["GCP", "AWS", "Cloud Run", "Cloud SQL", "EKS"],
            "devops":     ["Docker", "Kubernetes", "GitHub Actions", "CI/CD"],
            "monitoring": ["Prometheus", "Grafana", "Sentry", "Coralogix"]
        }
```

---

### `> ls projects/`

**`cosmo-companion-ai/`** -- Founding AI engineer on a companion AI product. Long-term episodic memory with RAG over Qdrant + pgvector (automated fact extraction, top-k semantic retrieval). Redis semantic cache matching queries by embedding cosine similarity to skip redundant LLM calls. Context-pruning and token-budgeting engine. OpenAI + Gemini behind one streaming interface for per-persona routing, plus multimodal voice (Whisper, TTS) and a real-time safety pipeline (moderation, prompt-injection mitigation, self-harm crisis detection). FastAPI backend built from an empty repo: 64 endpoints, 19 Postgres tables, 26 Alembic migrations, async throughout on GCP. p95 latency -40%, token costs -30%.

**`cdc-streaming-pipeline/`** -- End-to-end event-driven pipeline streaming PostgreSQL transactions into a Hadoop data lake. Debezium captures row-level WAL mutations, a multi-broker Kafka cluster buffers events, and a PySpark Streaming engine parses nested JSON and runs stateful transformations. Sinks to HDFS as Parquet + Delta Lake for fault-tolerant, ordered processing with zero data loss.

**`sbom-manager/`** -- Full-stack SBOM ingestion, dependency analysis, and vulnerability tracking platform for supply chain security. FastAPI + PostgreSQL backend ingesting SPDX and CycloneDX files, Celery + Redis workers cross-referencing packages against NVD/OSV databases, and a React + TypeScript dashboard visualizing dependency graphs and CVE risk. JWT RBAC, Docker, and Cloud Build CI/CD for license compliance.

**`quiz-planner/`** -- RAG-powered learning platform converting study materials into tailored quizzes and real-time tutoring. FastAPI backend with LangChain/LlamaIndex chunking, vector search (Pinecone/FAISS), and open-source LLMs (Llama 3 / Mistral) generating structured JSON quiz schemas. React + TypeScript UI with a multi-turn context-aware chat.

---

### `> cat metrics.log`

```
┌──────────────────────────────────────────────────────────────────────┐
│  30K-100K+  daily requests served across distributed microservices   │
│  sub-200ms  API response times in production (FastAPI + Redis)       │
│  40%  p95 LLM inference latency cut via Redis semantic caching       │
│  30%  token cost reduction via context-pruning + token budgeting     │
│  64  FastAPI endpoints built from an empty repo, async throughout    │
│  35%  API latency drop from collapsing 3-tier architecture at BYJU'S │
│  99.95%  uptime SLA held on-call across production services          │
└──────────────────────────────────────────────────────────────────────┘
```

---

### `> git log --oneline career`

```
2025-present  Cosmo AGI ───────────────────────────── Founding AI Engineer, owns AI systems end to end
2025          University of Maryland Baltimore County ──── Teaching Assistant, SENG 701 capstone
2022-2023     BYJU'S (Think and Learn Private Ltd) ─────── SDE, backend serving 3 K-12 platforms, on-call
2022          Odisha Design Council ────────────────────── Full-stack event platform, led team of 5
2021          Ceremorphic Inc. ─────────────────────────── RISC-V microprocessor design, FPU timing optimization
```

---

<p align="center">
  <b>Currently open to full-time roles in AI/ML, forward-deployed, backend, or full-stack engineering.</b>
  <br/>
  If you're building something ambitious, let's talk.
</p>
