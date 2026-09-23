<h1 align="center">Hi 👋, I'm Yassine Khefifi</h1>
<h3 align="center">AI Engineer — RAG, Knowledge Graphs & Agentic Systems</h3>

<p align="center">
  <a href="https://linkedin.com/in/yassine-khefifi">LinkedIn</a> •
  <a href="mailto:yassine.khefifi@sesame.com.tn">Email</a>
</p>

---

## 🧠 About Me

I build **LLM systems that are measured, not vibes-checked.**

Software engineer specialised in applied AI — retrieval design, evaluation, and the reliability
engineering that keeps LLM systems working in production. I care less about what a model *can* do in a
demo and more about what it does *correctly, repeatably, and honestly* when real users depend on it.

🎓 Engineering degree in Software Engineering (SESAME, Tunisia) · 🌍 Based in Tunis · Open to relocation

---

## 🔭 What I've Been Building

### **Lore** — AI knowledge-retention platform · *Neuraluna AI (Seattle, remote)*
> End-of-studies project · closed source

AI-led interviews turn senior experts' undocumented reasoning into a **Neo4j knowledge graph**.
Colleagues then query an expert "clone" that answers with **inline citations, a confidence state, and
honest refusals** — and surfaces both sides when stored knowledge contradicts itself.

**Measured across a frozen 22-question benchmark, over seven logged iterations:**

| Metric | Baseline | Final |
|---|---|---|
| Answer correctness *(LLM-as-judge)* | 0.28 | **0.88** |
| Retrieval hit@5 | 0.19 | **0.56** |
| Correct-refusal rate | 0.67 | **1.00** |
| **Hallucinated answers** *(false-answer rate)* | 0.17 | **0.00** |

What made it work: three-stage hybrid retrieval inside Neo4j (vector + full-text + graph expansion
across `CAUSES` / `REQUIRES` / `CONTRADICTS`), an **LLM relevance gate** adopted after measuring that
answerable and unanswerable similarity ranges *overlap* — so no single threshold separates them —
dedup-on-write with contradiction detection, a human-in-the-loop correction loop, and a local **MCP
server** exposing the query pipeline as tools.

`Python` `FastAPI` `Neo4j` `PostgreSQL` `Redis` `sentence-transformers` `React 19` `MCP` `Terraform` `Cloud Run`

<!-- Add PaperTrail here once the repo is public:
### **PaperTrail** — Contradiction-aware GraphRAG research agent
Open-source agent over arXiv AI papers. Atomic claims (not chunks) in Neo4j with SUPPORTS/CONTRADICTS
edges, hybrid retrieval with rank fusion, a bounded LangGraph agent with self-critique and a token
budget, an MCP server, and an evaluation suite gating every change in CI.
→ [Repository](LINK) · [Live demo](LINK)
-->

---

## 🛠️ Tech I Work With

**LLM & RAG** — RAG & GraphRAG · hybrid retrieval · embeddings (BGE, sentence-transformers) ·
vector indexes (Neo4j, ChromaDB) · citations & grounding · confidence gating · structured outputs ·
fine-tuning (Hugging Face) · LangChain · LangGraph · MCP

**Evaluation & Reliability** — frozen gold datasets · LLM-as-judge · false-answer vs false-refusal
analysis · baseline-first protocol · provider abstraction & failover · token budgeting ·
retry/backoff · degraded modes

**ML & Deep Learning** — PyTorch · TensorFlow · Keras · CNNs (ResNet) · ensemble methods ·
ONNX · DJL · NumPy · Pandas

**Backend** — Java · Spring Boot · Spring AI · LangChain4j · Python · FastAPI · Django ·
Node.js · microservices · REST · Kafka · RabbitMQ · JUnit

**Frontend** — React 19 · Angular · Next.js · TypeScript · Vite · Tailwind

**Data** — Neo4j (Cypher) · PostgreSQL · MongoDB · MySQL · Redis · ChromaDB

**Cloud & DevOps** — Docker · Kubernetes · Terraform · GitHub Actions · Google Cloud Run · AWS ·
Keycloak · Kong · OAuth/OIDC

---

## 📜 Certifications

**AWS Academy Graduate — Cloud Foundations** · **IT Specialist: Java** · **IT Specialist: Software Development**

---

## 📫 Get In Touch

📧 **yassine.khefifi@sesame.com.tn** · 💼 **[linkedin.com/in/yassine-khefifi](https://linkedin.com/in/yassine-khefifi)**

Currently open to **AI Engineer / ML Engineer** roles — remote, or relocating to Europe or Canada.
Arabic (native) · French (fluent) · English (fluent)
