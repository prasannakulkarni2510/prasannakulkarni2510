# Prasanna Kulkarni

**AI Engineer** based in Pune, India — building LLM systems that are designed before they are coded.

---

## What I do

I build RAG pipelines, agentic systems, and LLM-powered tools — from architecture to deployment. My background in mechanical engineering means I think in systems, not just features. I am comfortable working on domain-specific problems where general-purpose AI falls short.

Currently at Neilsoft Technologies, where I shipped a document processing platform that reduced 120 hours of manual CAD review work to under a week for a team of 4.

---

## What I am building now

**Knowledge Governance RAG System** *(March 2025 — ongoing)*

A production-oriented RAG system with a deliberate design choice: two separate vector indexes instead of one. Unverified documents go into a staging index. Only verified, approved content reaches the trusted index that powers generation. This is not how most RAG tutorials are built — it is how production systems should be built.

- Role-based access control across three user types
- Semantic deduplication across three tiers: hash matching, metadata overlap, embedding similarity
- Bounded LangGraph agent with deterministic state machine and a single controlled revision loop
- Offline RAGAS evaluation and LangSmith observability

Stack: Python, FastAPI, LangChain, LangGraph, Pinecone, OpenAI API, RAGAS, LangSmith, PostgreSQL

---

**Document Q&A Chatbot** *(Dec 2025 — Feb 2026)*

Multi-turn document chatbot with a LangGraph state machine across three nodes: retrieval, context formatting, and answer generation. Validated across 150 test queries covering answer quality, edge cases, and temperature variation. FAISS runs fully locally — no API cost for retrieval.

Stack: Python, LangGraph, LangChain, FAISS, SentenceTransformers, FastAPI, OpenAI API

---

## Toolbox

```
AI / LLM      LangChain  LangGraph  FAISS  OpenAI API  SentenceTransformers
              Prompt Engineering  Vector Databases  RAGAS  LangSmith

Backend       Python  FastAPI  Flask  PostgreSQL  MySQL  SQL

Deployment    AWS EC2  Streamlit  Git

Domain        AEC  Generative Design  Computational Geometry  Shapely
```

---

## A few numbers

- 80%+ reduction in processing time for a 63-file CAD review pipeline
- 150 test queries run against the document chatbot across quality, edge cases, and temperature variation
- 60+ engineers across 2 departments at Neilsoft attended an internal LLM knowledge session I delivered
- Top 5% in Engineering Mathematics 1, 2, and 3 — scored 100, 99, and 93 out of 100

---

## Background

**PG Diploma in Big Data Analytics** — CDAC Sunbeam Infotech, Pune (2023–2024)
Capstone: Analysed 10 years of bird migration data using SARIMA to identify climate-linked seasonal shifts. Deployed forecasting API on AWS EC2.

**B.E. Mechanical Engineering** — SPPU, Pune (2018–2022) — CGPA 9.11

---

## Get in touch

- LinkedIn: [linkedin.com/in/prasanna-kulkarni-032650180](https://linkedin.com/in/prasanna-kulkarni-032650180)
- Email: kulkarniprasanna25@gmail.com
- Open to: AI Engineer and ML Engineer roles in Pune or Bangalore — remote preferred

---

*I read papers. I build things. I ask why before I ask how.*
