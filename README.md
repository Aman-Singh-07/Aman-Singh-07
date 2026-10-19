<div align="center">

# Aman Singh

**AI Systems & Backend Engineering · LLMs, RAG & Agentic Workflows · Java DSA**

B.Tech CSE @ MMMUT, Gorakhpur · **CGPA: 9.86/10**

[LinkedIn](https://www.linkedin.com/in/aman-singh-3a4a06327) · [Email](mailto:amansingh17112004@gmail.com) · [GitHub Repositories](https://github.com/Aman-Singh-07?tab=repositories)

</div>

## About

An AI system is more than an API call to an LLM. It also needs ingestion, deduplication, retrieval, persistent state, concurrency control, and failure handling. I build AI workflows with backend and database engineering underneath them.

My current interests are reliable LLM applications, retrieval-augmented generation (RAG), multi-agent workflows, and backend systems. Alongside project work, I practise data structures and algorithms in Java through competitive programming.

## Featured Systems

### 01 · [YaiyuResearch AI](https://github.com/Aman-Singh-07/YaiyuResearch-AI)

**Multi-agent research pipeline orchestrated with n8n**

```text
Sources → Ingestion → Deduplication → Embeddings → Vector Store
        → Retrieval → Agents → Human Approval → Synthesis
```

- Stores embeddings in Supabase/PostgreSQL with `pgvector`; HNSW indexing supports similarity retrieval.
- Uses SHA-256 hashing to avoid repeatedly ingesting the same source.
- Persists workflow state in PostgreSQL to support stage-by-stage progress and resumption.
- Includes human-approval checkpoints before final synthesis and connects to external academic APIs for ingestion.

`n8n` · `Python` · `Supabase` · `PostgreSQL` · `pgvector` · `RAG` · `Embeddings`

[Repository](https://github.com/Aman-Singh-07/YaiyuResearch-AI) · [Demo Video](https://drive.google.com/file/d/1fbRZ5nTf2KxS5bZnOCVAypzCMDEvsfkx/view?usp=sharing)

### 02 · [FinVriksh AI](https://github.com/Aman-Singh-07/FinVriksh-AI)

**Multi-agent financial research architecture**

```text
Planner → Market Data / News / Filings → Report Synthesis
                         PostgreSQL state + approval checkpoints
```

- Organizes five specialist agents-Planner, MarketData, News, Filings, and ReportSynthesis-through a DAG and finite-state workflow.
- Runs MarketData, News, and Filings tasks concurrently using `asyncio.gather`.
- Uses PostgreSQL-backed state and optimistic concurrency control (OCC) to help mitigate conflicting updates.

`Python` · `asyncio` · `PostgreSQL` · `DAG Orchestration` · `Concurrency Control`

[Repository](https://github.com/Aman-Singh-07/FinVriksh-AI) · [Live Demo](https://fin-vriksh-ai.vercel.app) · [Demo Video](https://drive.google.com/file/d/1r0s5RYi6pNk0KWiVogQTc3SUQCQNX2u8/view?usp=sharing)

> FinVriksh AI is a research/architecture project, not a live trading system or financial advisory tool.

## Applied AI Projects

### [AceInterview AI](https://github.com/Aman-Singh-07/AceInterview-AI)

An AI-powered interview preparation application built with Flask and IBM Granite through watsonx.ai. It generates interview questions and provides code-review feedback on submitted answers.

`Python` · `Flask` · `IBM watsonx.ai` · `IBM Granite`

[Repository](https://github.com/Aman-Singh-07/AceInterview-AI) · [Live Demo](https://aceinterview-ai-26i2.onrender.com)

### [AcePilot AI - Multi-Agent Career Copilot](https://github.com/Aman-Singh-07/AcePilot-AI)

A career-guidance assistant built around a coordinator and specialist agents for résumé feedback, project recommendations, learning roadmaps, and interview preparation. The public repository documents Google ADK, Gemini 2.0 Flash, GitHub API access through MCP, and a Streamlit interface.

`Python` · `Google ADK` · `Gemini` · `MCP` · `Streamlit`

[Repository](https://github.com/Aman-Singh-07/AcePilot-AI) · [Live Demo](https://acepilot-ai-6kkhfyjhsyzgh7n46n2rhb.streamlit.app/)

### [Fairlytix](https://github.com/FairlytixHQ/fairlytix)

An AI-assisted fairness and negotiation platform developed during the IIT Jammu AI Summer School hackathon with the three-person team **Negoti-AI-tors**. The project explores quote-fairness assessment, market benchmarking, and negotiation support. My contributions focused on product engineering, frontend development, and data architecture.

`AI-Assisted Analysis` · `Product Engineering` · `Data Architecture`

[Repository](https://github.com/FairlytixHQ/fairlytix) · [Live Demo](https://fairlytix-deploy.vercel.app)

## Experience

### IIT Jammu - AI / Generative AI Summer School Intern

**Jun 2026 - Aug 2026** · Techible × Institute Incubation and Innovation Council (I3C)

Built n8n automation workflows integrating REST APIs, webhooks, and AI services. Worked on AI systems involving Python, PostgreSQL/Supabase, RAG, embeddings, and multi-agent architectures.

### IBM SkillsBuild × AICTE × Edunet Foundation - Emerging Technologies Intern

**Jun 2026 - Jul 2026**

Built AceInterview AI using Python, Flask, and IBM Granite via watsonx.ai. The programme covered Generative AI, Agentic AI, Cybersecurity, and Quantum Computing.

## Leadership & Service

### Special Invitee Member - Students’ Grievance Redressal Committee (SGRC), MMMUT

**Oct 2026 – Oct 2028** · Appointed for a two-year term

Appointed as a Special Invitee Member of MMMUT’s university-level Students’ Grievance Redressal Committee.

## Technical Stack

| Area | Technologies |
|---|---|
| Languages | Java · Python · C · TypeScript |
| AI / LLM | LLMs · Generative AI · AI Agents · RAG · Hugging Face Transformers · LangChain · Embeddings · Prompt Engineering |
| Backend / Automation | Flask · REST APIs · Webhooks · n8n · Workflow Automation |
| Data | PostgreSQL · Supabase · pgvector · Database Migrations |
| Engineering Tools | Git · GitHub · Docker · Debugging |
| IBM | watsonx.ai · watsonx Orchestrate · Granite |
| Core CS | Data Structures & Algorithms · Competitive Programming · OOP |

## Competitive Programming & Achievements

| Platform | Rank | Peak Rating | Progress |
|---|---|---:|---|
| LeetCode | Knight | 2039 | 630+ solved · 550+ day streak |
| Codeforces | Pupil | 1259 | 700+ solved |
| CodeChef | 2★ | 1565 | 1,450+ solved |

- **HACK IITK 2026:** Grand Finale Finalist, Top 24 - C3iHub, IIT Kanpur.
- **PsychCTF 2026:** Global Rank 56 - Team 5ev3n, SAIC, IIT Mandi.

## Education

**Madan Mohan Malaviya University of Technology (MMMUT), Gorakhpur**  
B.Tech in Computer Science & Engineering · **CGPA: 9.86/10** · Aug 2024 – Present

---

<div align="center">

[LinkedIn](https://www.linkedin.com/in/aman-singh-3a4a06327) · [Email](mailto:amansingh17112004@gmail.com) · [GitHub](https://github.com/Aman-Singh-07)

</div>
