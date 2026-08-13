<div align="center">

# Aman Singh

**AI/LLM & Agent Engineering · Backend Systems · Competitive Programming**

B.Tech CSE @ MMMUT, Gorakhpur · CGPA 9.81/10

</div>

<br>

## About

An AI system isn't just an API call to an LLM. It's ingestion, deduplication, retrieval, state, concurrency, and failure handling — the same engineering problems as any backend system, with a model in the loop. That's the lens I build with: multi-agent systems that combine LLMs and retrieval with real backend and database engineering underneath them.

Alongside that, I compete in DSA/competitive programming in Java — LeetCode Knight, Codeforces Pupil, CodeChef 2★.

Currently: AI Summer School Intern at IIT Jammu · Emerging Technologies Intern at IBM SkillsBuild via Edunet Foundation.

<br>

## Systems

### 01 · YaiyuResearch AI
**Multi-agent research pipeline, orchestrated with n8n**

```text
sources
 ↓
ingest
 ↓
dedup
 ↓
embed
 ↓
vector store
 ↓
retrieve
 ↓
agents
 ↓
approval
 ↓
synthesis
```

Source documents are embedded and stored in Supabase/PostgreSQL with `pgvector`. HNSW indexing supports similarity retrieval. `SHA-256` hashing deduplicates incoming sources so the same document doesn't repeatedly re-enter the pipeline. Workflow state is persisted in PostgreSQL, allowing the process to resume across stages and pause for human approval before final synthesis. External academic APIs feed the ingestion stage.

| Component | Why it's there |
|---|---|
| `pgvector` + HNSW | Efficient similarity retrieval |
| `SHA-256` deduplication | Prevents redundant ingestion of the same source |
| PostgreSQL state | Resumability across pipeline stages |
| Human approval | Controlled synthesis rather than unchecked output |

`n8n` `Supabase` `PostgreSQL` `pgvector` `RAG` `Embeddings`

[GitHub](https://github.com/Aman-Singh-07/YaiyuResearch-AI) · [Demo Video](https://drive.google.com/file/d/1fbRZ5nTf2KxS5bZnOCVAypzCMDEvsfkx/view?usp=sharing)

---

### 02 · FinVriksh AI
**Multi-agent financial research architecture**

```text
Planner
 ↓
MarketData / News / Filings
 ↓
ReportSynthesis
 ↓
PostgreSQL state ↔ OCC
```

Five specialized agents — Planner, MarketData, News, Filings, and ReportSynthesis — coordinate through a DAG with finite-state workflow transitions. MarketData, News, and Filings execute concurrently via `asyncio.gather`. Shared state is PostgreSQL-backed with approval checkpoints between stages. Because multiple agents can attempt to update shared state at the same time, Optimistic Concurrency Control (OCC) is used to mitigate conflicting writes and race conditions.

> Research/architecture project — not a live trading system or financial advisory tool.

`Python` `asyncio` `PostgreSQL` `Multi-Agent Orchestration` `Concurrency Control`

[GitHub](https://github.com/Aman-Singh-07/FinVriksh-AI) · [Live Demo](https://fin-vriksh-ai.vercel.app) · [Demo Video](https://drive.google.com/file/d/1r0s5RYi6pNk0KWiVogQTc3SUQCQNX2u8/view?usp=sharing)

<br>

## Applied AI

### AceInterview AI

AI-powered interview preparation platform built during the IBM SkillsBuild internship. A Flask application using IBM Granite via watsonx.ai to generate interview questions and provide code-review feedback on submitted answers.

`Python` `Flask` `IBM watsonx.ai` `IBM Granite`

[GitHub](https://github.com/Aman-Singh-07/AceInterview-AI) · [Live Demo](https://aceinterview-ai-26i2.onrender.com)

### Fairlytix

AI-assisted fairness and negotiation platform built during the IIT Jammu AI Summer School Hackathon with team **Negoti-AI-tors** (3 people). The system explores quote-fairness assessment, market benchmarking, and negotiation support. My contributions focused on **Product Engineering, Frontend Development, and Data Architecture**.

**Status:** Working hackathon implementation with a deployed demo.

`Hackathon` `AI-Assisted Fairness Analysis` `Negotiation Support`

[GitHub](https://github.com/FairlytixHQ/fairlytix) · [Live Demo](https://fairlytix-deploy.vercel.app)

### AcePilot AI

AI career guidance agent built using IBM watsonx Orchestrate during the IBM SkillsBuild internship.

<br>

## Experience

### Indian Institute of Technology Jammu

**AI Summer School Intern — LLMs, GenAI, Automations & AI Agents**
Jun 2026 – Aug 2026 · Techible × I3C, IIT Jammu

Built n8n automation workflows integrating REST APIs, webhooks, and AI services. Designed and implemented YaiyuResearch AI and FinVriksh AI, working with Python, PostgreSQL/Supabase, RAG, embeddings, and multi-agent architectures.

### IBM SkillsBuild × Edunet Foundation

**Emerging Technologies Intern**
Jun 2026 – Jul 2026

Built AceInterview AI and AcePilot AI as part of a program covering Generative AI, Agentic AI, Cybersecurity, and Quantum Computing.

<br>

## Stack

| | |
|---|---|
| **Languages** | Java · Python · C · TypeScript |
| **AI / LLM** | LLMs · Generative AI · AI Agents · RAG · Hugging Face Transformers · LangChain · Embeddings · Prompt Engineering |
| **Backend / Automation** | Flask · REST APIs · Webhooks · n8n · Workflow Automation |
| **Data** | PostgreSQL · Supabase · pgvector · Database Migrations |
| **Engineering** | Git · GitHub · Docker · Debugging |
| **IBM** | watsonx.ai · watsonx Orchestrate · Granite |
| **Core CS** | Data Structures & Algorithms · Competitive Programming · OOP |

<br>

## Competitive Programming

| Platform | Rank | Peak Rating | Volume |
|---|---|---:|---|
| LeetCode | Knight | 2039 | 630+ solved · 500+ day streak |
| Codeforces | Pupil | 1259 | 640+ solved |
| CodeChef | 2★ | 1565 | 1400+ solved |

**HACK IITK 2026** — Grand Finale Finalist, Top 24 (C3iHub, IIT Kanpur)
**PsychCTF 2026** — Global Rank 56, team 5ev3n (SAIC, IIT Mandi)

<br>

## Education

**Madan Mohan Malaviya University of Technology (MMMUT), Gorakhpur**
B.Tech in Computer Science & Engineering · CGPA 9.81/10 · Aug 2024 – Present

<br>

<div align="center">

[LinkedIn](https://www.linkedin.com/in/aman-singh-3a4a06327) ·
[Email](mailto:amansingh17112004@gmail.com) ·
[GitHub](https://github.com/Aman-Singh-07) ·

</div>
