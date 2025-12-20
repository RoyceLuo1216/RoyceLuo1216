# Royce Luo

Toronto, Canada • UofT Computer & Data Science (Co-op, May 2027)  
Email: royceluo1216@gmail.com • GitHub: @royceluo1216 • LinkedIn: royce-luo-uoft

## About me
I’m a Computer & Data Science student at the University of Toronto (GPA 3.93/4.0) who likes building end-to-end systems that feel “production real”: clean APIs, async workflows, measurable performance wins, and reliable deployments. I’m especially interested in commerce infrastructure, applied ML in products, and platform engineering.

- Current: Full Stack Developer @ Scotiabank GBM (Trade Floor Tech)
- Also: Software Developer @ Korotu • You’re Next Career Network
- Building: **ReturnFlow**, a Rails returns & exchanges platform (Hotwire + multi-tenant + Sidekiq + webhooks)

---

## What I’m working on
### ReturnFlow — Returns & Exchanges Platform (Rails)
A self-serve returns portal + merchant dashboard with workflow validation, audit logging, async processing, and webhook integrations.

**Highlights**
- Multi-tenant Rails 7 app (store-scoped data model)
- Validated state transitions (requested → approved → received → refunded/exchanged)
- Append-only event log for traceability/auditability
- Sidekiq + Redis for async jobs (notifications + webhook delivery)
- Webhooks with HMAC signatures and retry/backoff semantics
- Analytics: return reasons + SKU hotspots

> Repo: (link this once created) `https://github.com/royceluo1216/returnflow`

---

## Experience highlights
### Scotiabank — Global Banking & Markets (Full Stack Developer)
- Built an LLM-backed email triage pipeline with RAG + evaluation + safe routing, cutting manual triage by **80%**
- Owned an approvals platform end-to-end (APIs, data models, validation) reducing multi-team processing from **months → days**
- Built a cosine similarity REST service with caching + load testing to validate **10x scaling**

### Korotu (Software Developer)
- Reduced AWS containerization costs by **40%** using multi-stage builds, right-sized compute, and worker consolidation
- Built a geospatial scenario builder UI (React/TS) for ML-driven planning with OpenAI + Ollama
- Reduced Django + Postgres API latency by **35%** via profiling, ORM optimization, and indexing

### You’re Next Career Network (Software Developer)
- Saved **$12,000** by in-housing an event signup app serving **9,300+ users**
- Cut Firebase reads by **30%** via caching + query restructuring
- Reduced check-in time by **50%** by automating verification with SendGrid + QR codes

---

## Selected projects
- **Real-Time Market Simulation & Prediction Engine** (PyTorch): built a real-time FX simulator; sped ingestion **6x** using Polars vs pandas
- **Hurricane Preparedness Aid**: GenAI RAG over emergency documents + real-time tracking maps; Dockerized deployments

---

## Tech I use
**Languages:** Python, TypeScript/JavaScript, Java, C#, SQL, Ruby (learning)  
**Frameworks:** Rails, React, Django, Flask, PyTorch  
**Infra:** AWS, Docker, Kubernetes, Redis, Sidekiq, CI/CD, Postgres  
**Data/ML:** Transformers, RAG systems, Polars, Pandas, NumPy

---

## Contact
- Email: **royceluo1216@gmail.com**
- LinkedIn: **royce-luo-uoft**
