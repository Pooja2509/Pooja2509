## Pooja Bhatnagar

**C++ Systems & Performance Engineer | ML Infrastructure | Backend**

4.5+ years building low-latency C++ backends, ML systems, and scalable microservices at Siemens and Samsung R&D. Deep experience across the full stack — from custom memory allocators and database optimization to production ML pipelines with TensorFlow, LangChain, and RAG. NIT Hamirpur CSE.

---

### Featured: [lsm-kvstore](https://github.com/Pooja2509/lsm-kvstore) — Storage engine from scratch in C++20

Built a persistent key-value store using LSM-tree architecture. 4800 lines, 68 tests.

`Custom arena allocator` · `Skip list with lock-free reads` · `Prefix-compressed SSTables` · `Bloom filters (0.8% FP)` · `WAL with CRC32 crash recovery` · `MVCC snapshots` · `Leveled compaction` · **500K writes/sec**

---

### What I've built at work

**Siemens Digital Industries Software** — Senior MTS (3 years)
- Cut C++ backend latency **15%** via custom memory pooling and thread scheduling optimization
- Engineered Redis caching that reduced PostgreSQL response time from **2.1s → 180ms** across 500K+ records
- Architected LLM-powered code navigation assistant using **Transformers, LangChain, RAG** (85% MRR@10) — async ingestion with vector store consistency, served on EKS at p99 < 3s
- Built RL-based optimization engine in TensorFlow with custom reward shaping: **20% throughput gain**, 35% fewer compute cycles, extended to multi-agent RL with experience replay (+28% success rate)
- Deployed fault-tolerant microservices on **Kubernetes (EKS)** with auto-scaling, health checks, circuit breakers

**Samsung R&D** — Software Developer (1.5 years)
- Owned C++ backend modules for Android platform across 3 product lines (millions of users)
- Led Android 11→12 platform migration — **zero critical regressions**
- Built face recognition framework with TensorFlow, OpenCV, FaceNet — **96.2% accuracy**, optimized with INT8 quantization for 15% inference latency reduction on-device

---

### Projects

| Project | Stack | Result |
|---------|-------|--------|
| **[lsm-kvstore](https://github.com/Pooja2509/lsm-kvstore)** | C++20, LSM-tree | 500K writes/sec, 68 tests, crash recovery, MVCC |
| [Visual Search Engine](https://github.com/Pooja2509/Visual-Search-Engine) | PyTorch, FAISS, FastAPI, Docker | 82.6% P@5, sub-50ms search on 44K products |
| [AlgoSim](https://github.com/Pooja2509/AlgoSim) | Unity, C# | Interactive 3D data structure & algorithm visualizer |
| [Neural Image Captioning](https://github.com/Pooja2509/Neural-Image-Captioning) | TensorFlow, VGG16+LSTM | Published paper, 675K+ image pairs |
| [Timetable Scheduler](https://github.com/Pooja2509/Timetable-Scheduler) | ReactJS | Constraint-based university timetable generator |
| [ALPR System](https://github.com/Pooja2509/ALPR-System) | TensorFlow, OpenCV, VueJS | 92% detection, 94% OCR on 10K+ images |

---

### Core skills

**C++ & Systems:** Custom allocators (arena/pool), memory pooling, cache optimization, thread scheduling, lock-free data structures, profiling (perf, Valgrind), C++17/20

**ML & AI:** TensorFlow, PyTorch, LangChain, RAG, FAISS, Transformers, Reinforcement Learning, model quantization (INT8), on-device inference optimization

**Databases & Storage:** PostgreSQL (query optimization, EXPLAIN ANALYZE, indexing), Redis (caching, TTL), LSM-trees, B-trees, bloom filters, WAL design

**Backend & Infra:** Microservices, FastAPI, Django, Kafka, gRPC, Docker, Kubernetes, AWS (EKS), CI/CD, Prometheus/Grafana

**Languages:** C++, Python, SQL, JavaScript, Go (learning)

---

### Publications

- **Enhancing Image Captioning with Neural Models** — [arXiv](https://arxiv.org/abs/your-paper-id) · Proposed novel quality metric, evaluated encoder-decoder architectures on 675K+ image-caption pairs

---

### Currently

- Building database internals knowledge (CMU 15-445) and learning Go for systems programming
- Exploring open-source contributions in ClickHouse, gRPC, ScyllaDB
- Open to: **Bangalore, Hyderabad, Pune, Gurgaon, Remote** · Immediate joiner

---

[![Email](https://img.shields.io/badge/Email-impooja37@gmail.com-red?style=flat&logo=gmail&logoColor=white)](mailto:impooja37@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pooja_Bhatnagar-blue?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pooja-bhatnagar)
