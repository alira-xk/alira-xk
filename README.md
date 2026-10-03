<div align="center">

# Ali Raza

**Software Engineer · Backend Systems · Applied AI**

I build backend systems, retrieval engines, and applied AI — from a C++20 vector database to simulated spacecraft mission control.

[Portfolio](https://portfolio-psi-cyan-90.vercel.app) &nbsp; / &nbsp; [LinkedIn](https://www.linkedin.com/in/aliraza-se21) &nbsp; / &nbsp; [Email](mailto:alira7640@gmail.com)

![C++20](https://img.shields.io/badge/C%2B%2B20-1f2937?style=flat-square&logo=cplusplus&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-1f2937?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-1f2937?style=flat-square&logo=python&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1f2937?style=flat-square&logo=postgresql&logoColor=white)

Lahore, Pakistan · Software Engineering graduate

</div>

---

## Selected engineering work

### 01 / VectorForge

**A vector database and retrieval engine built from scratch in C++20.**

Built to make the mechanics of search inspectable: vector mathematics, graph construction, lexical ranking, storage, and synchronization live in the implementation.

- **Retrieval:** exact and HNSW vector search, BM25 keyword search, and Reciprocal Rank Fusion for hybrid results.
- **Storage and concurrency:** typed metadata filters, checksummed snapshots, atomic file replacement, reader/writer locks, and a draining thread pool.
- **Integration:** HTTP server, CLI, and optional Python document ingestion and RAG gateway.
- **Verification:** unit, process, allocation-failure, and concurrency checks; Windows/Linux CI; documented performance experiments and deployment limits.

`C++20` `HNSW` `BM25` `Python` `CMake` `GitHub Actions`

[Explore the code](https://github.com/alira-xk/vector) · [Architecture](https://github.com/alira-xk/vector/blob/main/docs/architecture.md) · [Testing](https://github.com/alira-xk/vector/blob/main/docs/testing.md) · [Performance](https://github.com/alira-xk/vector/blob/main/docs/performance.md)

### 02 / ORBITAL-X

**Simulated spacecraft mission control, from telemetry to human-approved recovery.**

An end-to-end system that streams spacecraft telemetry, detects developing anomalies, correlates incidents, and helps operators investigate failures with AI.

- **Live operations:** Redis Streams telemetry pipeline, PostgreSQL persistence, WebSocket updates, and a React/Three.js mission dashboard.
- **Detection and investigation:** Isolation Forest and engineering rules, semantic search with pgvector, and evidence-backed RAG investigations.
- **Recovery controls:** role-based permissions, audited commands, and two distinct operator approvals for critical recovery actions. AI remains advisory.
- **Replay and verification:** incident-scoped mission replay, automated checks, and a documented local recovery flow using PostgreSQL and Redis.

`TypeScript` `React` `Node.js` `Python / FastAPI` `PostgreSQL` `Redis` `Three.js`

[Explore the code](https://github.com/alira-xk/orbital-x) · [System overview](https://github.com/alira-xk/orbital-x#architecture) · [Verification evidence](https://github.com/alira-xk/orbital-x/tree/main/docs/evidence)

---

## More projects

| Project | What I built | Core tools |
| :--- | :--- | :--- |
| [Patient Management Backend](https://github.com/alira-xk/Patient-Management--Backend) | APIs for patient records, appointments, and medical histories, with JWT authentication and role-based access. | Node.js · Express · MongoDB |
| [Forensic Timeline Reconstructor](https://github.com/alira-xk/forensic-timeline-reconstructor) | Evidence metadata extraction, searchable timelines, SHA-256 integrity checks, and CSV/JSON export. | Node.js · Python · MongoDB · React Native |
| [Food Calorie Estimator](https://github.com/alira-xk/Food-Calorie-Estimator---Text-Based) | A DistilBERT-based application for estimating calories from food descriptions, including training and inference. | Python · PyTorch · Hugging Face · Flask |

Frontend explorations: [Pokédex](https://github.com/alira-xk/Pokedex) · [Netflix Clone](https://github.com/alira-xk/Netflix-Clone) · [Fitify](https://github.com/alira-xk/fitify)

## Technical toolkit

| Area | Technologies and practices |
| :--- | :--- |
| Systems & retrieval | C++20, HNSW, BM25, hybrid ranking, binary persistence, concurrency, CMake |
| Backend & data | TypeScript, Node.js, Express, PostgreSQL, Redis, MongoDB, REST APIs, WebSockets |
| AI & ML | Python, FastAPI, PyTorch, Hugging Face Transformers, pgvector, RAG, anomaly detection |
| Interfaces & delivery | React, Three.js, Git, GitHub Actions, automated testing, architecture documentation |

## How I approach engineering

I care about what happens beyond the happy path: invalid inputs, failed allocations, concurrent requests, recovery, and permissions. My strongest projects include source code, architecture notes, verification evidence, and explicit limits so the work can be evaluated rather than taken on trust.

My current focus is backend engineering, vector retrieval, and AI applications with inspectable behavior.

---

<div align="center">

**Let's talk about backend, systems, or applied AI engineering.**

[alira7640@gmail.com](mailto:alira7640@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aliraza-se21) · [Portfolio](https://portfolio-psi-cyan-90.vercel.app)

</div>
