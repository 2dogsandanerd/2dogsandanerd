### Hi there, I'm Stefan 👋

> **"Most RAG projects don't fail because of the LLM. They fail because they treat PDF ingestion as a simple file upload."**

I am an **AI-Native Architect** focused on solving the hardest problem in the current AI hype cycle: **The Ingestion Gap.**
My mission is to replace "Digital Paper" (dead PDFs) with structured, semantic knowledge that allows Local AI to reason without hallucinations.

---

### 🚀 The Ecosystem

I build modular, production-ready kits to fix the "Garbage In" problem for high-compliance environments (Public Sector / Enterprise).

#### 🏗️ Architecture & Platforms
*   **[RAG Enterprise Core](https://github.com/2dogsandanerd/rag_enterprise_core)** (⭐ New)
    *   The Blueprint for BSI-compliant, self-hosted RAG.
    *   Features: **Ingestion Triage**, **GraphRAG**, **Semantic Caching**, and **Full Observability**.
    *   *Status: Architecture Preview / Closed Source Engine.*

#### 🛠️ Essential Tooling
*   **[Validated Table Extractor](https://github.com/2dogsandanerd/validated-table-extractor)**
    *   The proof that RAG *can* handle complex tables if you use **Docling + Vision Validation**.
    *   *Status: Open Source Audit Tool.*
*   **[Smart Ingest Kit](https://github.com/2dogsandanerd/smart-ingest-kit)**
    *   Production-grade document ingestion pipeline using Docling v2.
    *   Solves: Layout Analysis, Table Reconstruction, Markdown Conversion.

#### 🤖 Proven in Production
*   **Mail Modul Alpha** (Private)
    *   A fully autonomous, privacy-first AI email assistant running locally.
    *   *The proof that my ingestion engine works in the wild.*

---

### 🧠 The "Ingestion-First" Stack

I don't believe in "One Model Fits All". I believe in **Triage**.

| Layer | Tools & Tech |
| :--- | :--- |
| **Ingestion** | `Docling v2` (Layout Analysis), `Qwen2-VL` (Vision Fallback), `PyMuPDF` (Fast Lane) |
| **Storage** | `ChromaDB` (Vector), `Neo4j` (Graph/Relationships), `Redis` (Semantic Cache) |
| **Orchestration** | `LangGraph` (Agentic Workflows), `FastAPI` (Microservices) |
| **Observability** | `Sentry`, `Grafana`, `Jaeger` (Tracing) |
| **Infrastructure** | `Docker Compose` (Local First), `Ollama` (Inference) |

---

### 🌱 Philosophy

*   **Structure > Vectors:** Embeddings are useless if the input table was ripped apart. I reconstruct structure (Markdown) first.
*   **Local > Cloud:** Data sovereignty (GDPR/BSI) is not optional. I build for air-gapped reality.
*   **Logic > Magic:** I prefer deterministic code for business rules over probabilistic LLM guessing.

---

### 📫 Connect & Context

*   **Reddit:** [u/ChapterEquivalent188](https://www.reddit.com/user/ChapterEquivalent188/) - Discussing the "PoC Trap" & Ingestion Realities.
*   **Focus:** Currently open for strategic dialogue regarding **High-Compliance RAG Architectures** (Public Sector / Industry).
