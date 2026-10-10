# Parth Vaja

**Software Engineer · MS Data Science (CS track) @ UMBC · 4.0 GPA**

2.5 years of production engineering at [Knovos](https://www.knovos.com/) building backend systems, NLP pipelines, and distributed data infrastructure in Java, C#, and Python. Now building AI systems that ship to real users, not just notebooks.

[Portfolio](https://parthvaja.dev) · [LinkedIn](https://linkedin.com/in/parth-vaja) · [Email](mailto:parthmv1@umbc.edu)

---

## What I've Built

### [Verdict](https://github.com/parthvaja/verdict) — Multi-Agent AI Adjudication System
Two LLM advocate agents argue opposing positions before an AI judge issues a structured verdict with confidence scoring. Built to solve the problem of sycophantic convergence: agents run on separate providers (Anthropic + OpenAI) so they can't silently agree with each other. Eval harness gates every prompt change on judge calibration checks for false-balance and overconfidence.

`Next.js` `TypeScript` `FastAPI` `Python` `Anthropic API` `OpenAI API` `SSE streaming` `Pydantic` `Zod`

### [MindsetLens](https://github.com/parthvaja/mindsetlens) — AI-Powered Adaptive Learning Platform
RAG application that classifies student explanations into misconception categories and delivers personalized teaching recommendations. Piloted with 8 teachers and 200+ students; teacher approval of AI recommendations went from 60% to 85% after redesigning how outputs were grounded.

`Python` `FastAPI` `React` `PostgreSQL` `LangChain` `HuggingFace` `Claude API` `Docker`

**82% F1-score** · **sub-200ms inference** · **200+ active users** · **90% pilot satisfaction**

### [AI Code Review Bot](https://github.com/parthvaja/cloudflare-ai-code-review) — Agentic Code Evaluation on Cloudflare Workers
Production tool that generates AND critically evaluates AI-produced code before surfacing it. Uses Durable Objects for stateful review sessions with observability into the agent loop. Built to work within Workers isolate constraints.

`TypeScript` `Cloudflare Workers` `Durable Objects` `React`

### [Product Intelligence Service](https://github.com/parthvaja/solumina-knowledge-graph) — Knowledge Graph + MCP Server
FastAPI service backed by Neo4j that exposes a Solumina product-intelligence knowledge graph through an MCP server for AI agent consumption.

`FastAPI` `Neo4j` `MCP` `Python`

### [parthvaja.dev](https://parthvaja.dev) — Portfolio
Built from scratch. Next.js 15, React 19, TypeScript, TailwindCSS. Responsive, no template.

---

## Production Experience

**BeOne Medicines** (formerly BeiGene) · AI & Data Intern · Summer 2026, San Carlos, CA

Built a data-lineage and impact-analysis system over Amazon Redshift. Parsed stored procedures into ASTs, extracted table-level dependencies, and constructed a 740-node / 2,540-edge dependency graph. Made an architectural call: graph traversal over vector embeddings for provably complete impact analysis in a regulated domain. RAG layer grounded in the graph, surfaced via Microsoft Copilot Studio. Deployed on EC2 within IQVIA's AWS infrastructure.

**Knovos** · Software Engineer (promoted from Intern) · Jan 2023 to Jul 2025

Shipped production systems in legal tech / eDiscovery for 2.5 years:
- Debugged a race condition in an undocumented multithreaded C# system 48 hours before a court deadline. Zero crashes after the fix.
- Built data ingestion handling 5M+ files at 99.5% uptime with 40% throughput improvement.
- Optimized REST APIs serving 2M+ records: 40% throughput increase, 35% latency reduction (Redis, async, query tuning).
- Replaced a $200K/year third-party OCR vendor with an in-house pipeline: 98% accuracy, 90% faster, 1M+ files/year.
- Built a document redaction microservice: 1M+ files/year, $150K licensing cost eliminated.
- Production NLP for PII extraction: 94% accuracy across 60+ entity types, 100K+ legal documents.
- Distributed ETL with Hadoop MapReduce: 70% processing time reduction over 100K+ documents.

---

## What I Work With

**Day-to-day:** Python, Java, C#, TypeScript, SQL, FastAPI, Spring Boot, .NET, React, PostgreSQL, Redis, Docker, AWS, Git

**AI/ML:** LangChain, HuggingFace, RAG, prompt engineering, multi-agent orchestration, eval harnesses, Anthropic API, OpenAI API, scikit-learn, TensorFlow

**Data:** Hadoop MapReduce, Apache Solr, Amazon Redshift, MongoDB, Elasticsearch, Neo4j

---

## Education

**MS Data Science (Computer Science track)** — University of Maryland, Baltimore County · 4.0 GPA · May 2027

Coursework: Operating Systems, Data Structures, Algorithms, Databases, Machine Learning, Big Data Platforms, Statistical Analysis

**B.Tech Information Technology** — Institute of Advanced Research · April 2023
