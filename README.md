# Hi, I'm Priyank 👋

**Backend & Distributed Systems Engineer** · M.Tech, IIT Kanpur

I design and operate distributed services that stay correct under failure — async pipelines, idempotency, and observable systems at scale. 4.5 years in production, most of it owning cloud backend at Microsoft.

🔗 **[Portfolio](https://priyanksingh02.github.io)** · [Résumé](https://priyanksingh02.github.io/resume.html) · [LinkedIn](https://linkedin.com/in/priyanksingh02)

---

### At a glance

- 🏗️ **4.5 years** building and operating production backend systems
- ☁️ Owned Azure services at **~4M requests/month, 99.99% availability** at Microsoft
- ⚙️ Strongest in **async design, idempotency, observability, and concurrency**
- 🎓 **M.Tech, IIT Kanpur** · GATE 2019 (CS) — AIR 410, 99.6 percentile
- 💼 Open to **backend / distributed-systems roles and freelance engagements**

---

### What I work with

**Languages:** Go · C# · Python · C++ · SQL · JavaScript
**Backend:** REST · gRPC · Microservices · Async Workflows · Idempotency · Rate Limiting · Distributed Tracing
**Cloud & Infra:** Azure (Durable Functions, Service Bus, App Service, Key Vault) · Docker · IaC (ARM/Bicep) · CI/CD · Linux
**Storage & Messaging:** Kafka · Redis · Service Bus · SQL Server · Cosmos DB

---

### Selected projects

| Project | What it does |
|---|---|
| **Raft Consensus** (Go) | Leader election, log replication, and snapshotting from the paper, with a KV store on top — handles partition-recovery and uncommitted-entry safety. |
| **Distributed Rate Limiter** (Go · Redis · gRPC) | Atomic check-and-decrement in a Redis Lua script so replicas can't race at the limit boundary. Token-bucket and sliding-window modes, benchmarked. |
| **Kafka Stream Pipeline** (Go) | At-least-once delivery plus an idempotent sink, with a dead-letter queue, replay, and Prometheus metrics. |
| **Secure Storage** (Go) | Encrypted file store with access revocation *without* re-encryption — per-user envelope-wrapped keys; server never sees plaintext. |
| **TradeLog** (Flutter) | On-device FIFO trade audit for retail traders — realised PnL with corporate actions, no account, no telemetry. |

More detail and write-ups on my **[portfolio](https://priyanksingh02.github.io)**.

---

> *A thread runs through most of what I build: making operations safe to repeat. In any system with retries or at-least-once delivery, correctness lives in idempotency — not in preventing repeats.*
