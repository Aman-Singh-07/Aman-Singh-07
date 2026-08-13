# Aman Singh

**B.Tech CSE @ MMMUT · AI/LLM & Agent Engineering · Backend Systems · Competitive Programming**

## About

B.Tech CSE student at Madan Mohan Malaviya University of Technology (MMMUT), Gorakhpur — CGPA 9.81/10. I build multi-agent AI systems that combine LLMs, retrieval, and workflow orchestration with real backend and database engineering underneath them — not just prompt chains. My work spans RAG, embeddings, agentic workflows, PostgreSQL-backed state, and automation.

Alongside that, I compete in DSA/competitive programming — LeetCode Knight, Codeforces Pupil, CodeChef 2★.

## What I Build

**AI / LLM Systems** — RAG pipelines, embeddings, retrieval, prompt engineering
**Agentic Workflows** — multi-agent orchestration, DAGs, human-in-the-loop workflows
**Backend & Data Systems** — Python/Flask APIs, PostgreSQL/Supabase, workflow state, concurrency control
**Competitive Programming** — Java, DSA, algorithmic problem solving

## Featured Projects

### 01 · YaiyuResearch AI

An `n8n`-orchestrated research pipeline. Source documents are embedded and stored in `Supabase`/`PostgreSQL` with `pgvector`, where HNSW indexing supports similarity retrieval. `SHA-256` hashing deduplicates incoming sources so the same document doesn't repeatedly re-enter the pipeline. Workflow state is persisted in PostgreSQL, allowing the process to resume across stages and pause for human approval before final synthesis. External academic APIs feed the ingestion stage.

**Flow:** sources → ingestion → deduplication → embedding → vector storage → retrieval → agent processing → human approval → synthesis

`n8n` `Supabase` `PostgreSQL` `pgvector` `RAG` `Embeddings`

### 02 · FinVriksh AI

A multi-agent financial research architecture. Five specialized agents — Planner, MarketData, News, Filings, and ReportSynthesis — execute concurrently via `asyncio.gather`, coordinated through a Directed Acyclic Graph with finite-state workflow transitions. Shared state is `PostgreSQL`-backed with approval checkpoints between stages. Since multiple agents can attempt to update shared state at the same time, Optimistic Concurrency Control is used to prevent conflicting writes and race conditions.

This is a research/architecture project — not a live trading system or financial advisory tool.

`Python` `asyncio` `PostgreSQL` `Multi-Agent Orchestration` `Concurrency Control`

### 03 · AceInterview AI

An AI-powered interview preparation platform built during the IBM SkillsBuild internship. A `Flask` application that uses `IBM Granite` via `watsonx.ai` to generate interview questions and provide code-review feedback on submitted answers.

`Python` `Flask` `IBM watsonx.ai` `IBM Granite`

### 04 · Fairlytix

A hackathon prototype built at the IIT Jammu AI Summer School Hackathon with team Negoti-AI-tors (3 people). Explores quote-fairness assessment and market benchmarking to support negotiation decisions. My contributions covered product engineering, frontend development, and data architecture. This is a prototype, not a deployed or production system.

`Prototype` `Hackathon`

### Other AI Projects

**AcePilot AI** — AI career guidance agent built on `IBM watsonx Orchestrate` during the IBM SkillsBuild internship.

## Experience

### Indian Institute of Technology Jammu
**AI Summer School Intern — LLMs, GenAI, Automations & AI Agents**
Jun 2026 – Aug 2026 · Techible × I3C, IIT Jammu

Built n8n automation workflows integrating REST APIs, webhooks, and AI services. Designed and implemented YaiyuResearch AI and FinVriksh AI using Python, PostgreSQL/Supabase, RAG, embeddings, and multi-agent architectures.

### IBM SkillsBuild × Edunet Foundation
**Emerging Technologies Intern**
Jun 2026 – Jul 2026

Built AceInterview AI (Flask, IBM Granite, watsonx.ai) and AcePilot AI (IBM watsonx Orchestrate) as part of a program covering Generative AI, Agentic AI, Cybersecurity, and Quantum Computing.

## Technical Stack

**Languages:** Java · Python · C · TypeScript

**AI / LLM:** LLMs · Generative AI · AI Agents · RAG · Hugging Face Transformers · LangChain · Embeddings · Prompt Engineering

**Backend / Automation:** Flask · REST APIs · Webhooks · n8n · Workflow Automation

**Data:** PostgreSQL · Supabase · pgvector · Database Migrations

**Engineering:** Git · GitHub · Docker · Debugging

**IBM:** watsonx.ai · watsonx Orchestrate · Granite

**Core CS:** Data Structures & Algorithms · Competitive Programming · Object-Oriented Programming

## Competitive Programming

| Platform | Rank | Peak Rating | Volume |
|---|---|---|---|
| LeetCode | Knight | 2039 | 630+ solved · 500+ day streak |
| Codeforces | Pupil | 1259 | 640+ solved |
| CodeChef | 2★ | 1565 | 1400+ solved |

## Hackathons & Achievements

- **HACK IITK 2026** — Grand Finale Finalist, Top 24 (C3iHub, IIT Kanpur)
- **PsychCTF 2026** — Global Rank 56, team 5ev3n (SAIC, IIT Mandi)

## Education

**Madan Mohan Malaviya University of Technology (MMMUT), Gorakhpur**
B.Tech in Computer Science & Engineering
CGPA: **9.81/10**
Aug 2024 – Present

## Connect

[LinkedIn](YOUR_LINKEDIN_URL) · [Email](mailto:YOUR_EMAIL) · [GitHub](YOUR_GITHUB_URL) · [LeetCode](YOUR_LEETCODE_URL) · [Codeforces](YOUR_CODEFORCES_URL)
