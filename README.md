## Pooja Bhatnagar

**Software Engineer | C++ Systems · Backend Infrastructure · ML Pipelines**

4.5+ years building high-performance backends, scalable platforms, and data infrastructure at Siemens and Samsung R&D. I've worked across the full stack — from custom memory allocators and database optimization to event-driven microservices, CI/CD pipelines, and production ML systems. NIT Hamirpur CSE.

---

### What I've built at work

**Siemens Digital Industries Software** — Senior MTS (3 years)

- Architected a **regression and build management platform for 500+ engineers** — scheduling builds, executing 50K+ test cases per run, managing queues with rerun support, Celery + Redis async tasks, Kafka event ingestion → **reduced manual workflows by 60%**. Adopted org-wide as the primary CI dashboard.
- Cut C++ backend latency **15%** via custom memory allocators (arena/slab) and thread scheduling redesign. Applied compiler-level optimizations → **~40% fewer cache misses, 35% less lock contention**.
- Diagnosed PostgreSQL bottlenecks on 500K+ record APIs — composite indexes, N+1 elimination, Redis cache-aside with TTL → **p95: 2.1s → 180ms (12x)**
- Integrated **Elasticsearch** for full-text search across 200K+ records, **MongoDB** for flexible per-team config, structured logging with correlation IDs → **debugging time reduced 40%**
- Established **CI/CD (GitHub Actions)**, Docker builds, deployment to **Kubernetes on AWS**, Prometheus/Grafana dashboards, CloudWatch alerts

**Samsung R&D** — Software Developer (1.5 years)

- Owned performance-critical **C++ backend modules for Android** across 3 product lines (millions of users). API versioning, memory management, IPC handlers. Led Android 11→12 migration.
- Built on-device face recognition (TensorFlow, FaceNet, INT8 quantization) → **96.2% accuracy, 15% latency reduction**

---

### Featured Project: [lsm-kvstore](https://github.com/Pooja2509/lsm-kvstore)

Persistent key-value storage engine built from scratch in **C++20** using LSM-tree architecture.

`Custom arena allocator` · `Skip list with lock-free reads` · `Prefix-compressed SSTables` · `Bloom filters (0.8% FP)` · `WAL with CRC32 crash recovery` · `MVCC snapshots` · `Leveled compaction` · **500K writes/sec · 68 tests**

---

### Projects

| Project | Stack | Result |
|---------|-------|--------|
| **[lsm-kvstore](https://github.com/Pooja2509/lsm-kvstore)** | C++20, LSM-tree | 500K writes/sec, crash recovery, MVCC |
| [Visual Search Engine](https://github.com/Pooja2509/Visual-Search-Engine) | PyTorch, FAISS, FastAPI, Docker | 82.6% P@5, sub-50ms on 44K products |
| [Neural Image Captioning](https://github.com/Pooja2509/Neural-Image-Captioning) | TensorFlow, VGG16+LSTM | Published paper, 675K+ image pairs |
| [AlgoSim](https://github.com/Pooja2509/AlgoSim) | Unity, C# | Interactive 3D algorithm visualizer |
| [Timetable Scheduler](https://github.com/Pooja2509/Timetable-Scheduler) | ReactJS | Constraint-based generator for NIT Hamirpur |
| [ALPR System](https://github.com/Pooja2509/ALPR-System) | TensorFlow, OpenCV, VueJS | 92% detection, 94% OCR on 10K+ images |

---

### Skills

**Backend & APIs:** REST APIs, Microservices, FastAPI, Django, Celery, Kafka, gRPC, async task queues, event-driven architecture

**C++ & Systems:** C++17/20, custom allocators, memory pooling, lock-free structures, cache-line optimization, concurrency (std::atomic, memory ordering)

**Databases:** PostgreSQL (query optimization, indexing, EXPLAIN ANALYZE), Redis (caching, TTL, pub/sub), MongoDB, Elasticsearch, Kafka

**Infra & Cloud:** Docker, Kubernetes, AWS (EC2, EKS, CloudWatch), Terraform, CI/CD (GitHub Actions), Prometheus, Grafana

**ML & AI:** TensorFlow, PyTorch, LangChain, RAG, FAISS, Transformers, INT8 quantization

**Languages:** C++, Python, JavaScript, Go

---

### Publications

- **Enhancing Image Captioning with Neural Models** — [arXiv](https://arxiv.org/abs/2312.00435) · Novel quality metric, encoder-decoder evaluation on 675K+ image-caption pairs

---

### Currently

- Deepening database internals (CMU 15-445) and building Go proficiency
- Exploring open-source contributions in ClickHouse, gRPC, ScyllaDB
- Open to: **Bangalore, Hyderabad, Pune, Gurgaon, Remote** · Immediate joiner

---

[![Email](https://img.shields.io/badge/Email-impooja37@gmail.com-red?style=flat&logo=gmail&logoColor=white)](mailto:impooja37@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pooja_Bhatnagar-blue?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pooja-bhatnagar-b80202144/)
