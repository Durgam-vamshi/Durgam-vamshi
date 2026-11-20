<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&text=VAMSHI%20DURGAM&fontSize=54&fontColor=FFFFFF&fontAlignY=38&desc=AI%20ENGINEER%20%E2%80%A2%20GENAI%20%E2%80%A2%20AI%20BACKEND%20SYSTEMS&descAlignY=61&descSize=16&color=0:080B1A,35:1E3A8A,70:6D28D9,100:0891B2" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=19&duration=2800&pause=850&color=67E8F9&center=true&vCenter=true&width=820&height=55&lines=I+build+AI+systems%2C+not+just+LLM+demos.;RAG+%7C+Hybrid+Retrieval+%7C+Reranking;Agents+%7C+MCP+%7C+Tool+Calling;Real-time+Voice+AI+%7C+Reliable+Backends" />

<br/>

<a href="https://www.linkedin.com/in/vamshidurgam/">
<img src="https://img.shields.io/badge/LinkedIn-LET'S_CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/Durgam-vamshi">
<img src="https://img.shields.io/badge/GitHub-EXPLORE_MY_CODE-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="mailto:iamvamshidurgam@gmail.com">
<img src="https://img.shields.io/badge/Email-SAY_HELLO-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://x.com/DevXVamshi">
<img src="https://img.shields.io/badge/X-FOLLOW-000000?style=for-the-badge&logo=x&logoColor=white"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Durgam-vamshi&style=for-the-badge&color=7C3AED&label=PROFILE+VIEWS"/>
<img src="https://img.shields.io/badge/EXPERIENCE-2_YEARS-0891B2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/BASED_IN-HYDERABAD,_INDIA-334155?style=for-the-badge&logo=googlemaps&logoColor=white"/>

</div>

---

## ⚡ THE QUICK INTRO

I'm **Vamshi Durgam**, an **AI Engineer** building production-oriented LLM applications, retrieval systems, agent workflows, and real-time voice experiences.

I enjoy the engineering behind the model call:

- 🧠 LLM orchestration and AI agents
- 🔍 RAG pipelines and retrieval quality
- ⚡ Hybrid search, embeddings and reranking
- 🔗 MCP and tool/function calling
- 🎙️ Real-time conversational Voice AI
- 🏗️ Scalable asynchronous AI backend systems

My focus is turning AI capabilities into reliable, measurable systems that people can actually use.

<div align="center">

### 🧠 LLM APPLICATIONS
### 🔍 RETRIEVAL ENGINEERING
### 🤖 AGENTIC WORKFLOWS
### 🎙️ REAL-TIME VOICE AI
### ⚙️ BACKEND ARCHITECTURE

</div>

---

# 🧩 THE SYSTEMS I BUILD

## 🔍 01 — RAG / KNOWLEDGE SYSTEMS

<div align="center">

<img src="https://img.shields.io/badge/01-DOCUMENT_INGESTION-2563EB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/02-HYBRID_RETRIEVAL-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/03-RERANKING-0891B2?style=for-the-badge"/>

</div>

```mermaid
flowchart TD
    A["📄 PDF / DOCX / TXT"] --> B["⚙️ FastAPI Ingestion"]
    B --> C["✂️ Chunking"]
    C --> D["🔢 Embeddings"]
    D --> E[("🗄️ Pinecone")]

    Q["💬 User Query"] --> API["⚡ FastAPI"]
    API --> QR["🧠 Query Rewriting"]
    QR --> DS["🔎 Dense Retrieval"]
    QR --> BM["📚 BM25 Retrieval"]

    E --> DS
    DS --> F["⚖️ Hybrid Fusion"]
    BM --> F
    F --> R["🎯 Cross-Encoder Reranking"]
    R --> CTX["🧩 Relevant Context"]
    CTX --> LLM["🤖 Groq / Llama"]
    LLM --> OUT["✅ Grounded Answer"]

    classDef input fill:#172554,stroke:#60A5FA,color:#fff
    classDef processing fill:#164E63,stroke:#22D3EE,color:#fff
    classDef retrieval fill:#312E81,stroke:#A5B4FC,color:#fff
    classDef model fill:#581C87,stroke:#D8B4FE,color:#fff
    classDef output fill:#14532D,stroke:#4ADE80,color:#fff

    class A,Q input
    class B,C,D,API,QR processing
    class E,DS,BM,F,R,CTX retrieval
    class LLM model
    class OUT output
```

## 🛠️ 02 — AI SOFTWARE REPAIR AGENT

<div align="center">

<img src="https://img.shields.io/badge/LLM-REASONING-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AST-CODE_ANALYSIS-2563EB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/DOCKER-ISOLATED_TESTING-0891B2?style=for-the-badge"/>

</div>

```mermaid
flowchart TD
    A["📦 Python Repository"] --> B["🧭 AST Analysis"]
    B --> C["🔍 Traceback Localization"]
    C --> D["✂️ Bounded Code Context"]
    D --> E["🧠 Llama 3.3 70B"]
    E --> F["📝 Patch Generation"]
    F --> G["🛡️ Unified Diff Validation"]
    G --> H["🐳 Docker Isolated Pytest"]
    H --> I{"Tests Passed?"}
    I -->|Yes| J["✅ Verified Repair"]
    I -->|No| K["🧪 Failure Classification"]
    K --> E

    classDef source fill:#172554,stroke:#60A5FA,color:#fff
    classDef analysis fill:#312E81,stroke:#A5B4FC,color:#fff
    classDef safety fill:#7C2D12,stroke:#FB923C,color:#fff
    classDef testing fill:#164E63,stroke:#22D3EE,color:#fff
    classDef success fill:#14532D,stroke:#4ADE80,color:#fff

    class A source
    class B,C,D,E,F analysis
    class G,K safety
    class H,I testing
    class J success
```

## 🎙️ 03 — REAL-TIME TELUGU VOICE AI

<div align="center">

<img src="https://img.shields.io/badge/SPEECH-STREAMING-0891B2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MCP-TOOL_INTEGRATION-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/TELEPHONY-EXOTEL-2563EB?style=for-the-badge"/>

</div>

```mermaid
flowchart TD
    A["☎️ Incoming Call"] --> B["🔌 Exotel WebSocket"]
    B --> C["🎛️ FastAPI + Pipecat"]
    C --> D["👂 Silero VAD"]
    D --> E["🧭 Turn Detection"]
    E --> F["🧠 Lead Qualification State Machine"]

    F -->|Known Intent| G["⚡ Deterministic Action"]
    F -->|Requires LLM| H["🤖 Sarvam STT / TTS + Llama"]

    G --> I["🔗 FastMCP Server"]
    H --> I

    I --> J["📨 Gmail Integration"]
    I --> K["📞 Internal Call Directory"]

    J --> L["🔊 Voice Response"]
    K --> L

    classDef input fill:#172554,stroke:#60A5FA,color:#fff
    classDef processing fill:#164E63,stroke:#22D3EE,color:#fff
    classDef reasoning fill:#312E81,stroke:#A5B4FC,color:#fff
    classDef tools fill:#581C87,stroke:#D8B4FE,color:#fff
    classDef output fill:#14532D,stroke:#4ADE80,color:#fff

    class A input
    class B,C,D,E processing
    class F,G,H reasoning
    class I,J,K tools
    class L output
```

---

# 🚀 FEATURED BUILDS

<details open>
<summary><strong>🧑‍💻 AI SWE AGENT — REPOSITORY-LEVEL SOFTWARE REPAIR</strong></summary>

<div align="center">

<img src="https://img.shields.io/badge/PYTHON-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FASTAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/GROQ-F55036?style=flat-square"/>
<img src="https://img.shields.io/badge/DOCKER-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/PYTEST-0A9EDC?style=flat-square"/>
</div>

An LLM-driven software repair workflow that analyzes repositories, localizes bugs, generates patches, executes tests, analyzes failures, and iteratively verifies repairs.

**Core engineering:**

- 🧭 AST-based code analysis and traceback-driven localization.
- ✂️ Bounded code context construction for relevant repository symbols.
- 🛡️ Unified Diff validation, path-traversal protection, AST validation, Git rollback and isolated task workspaces.
- 🐳 Docker-isolated Pytest execution.
- 🔄 Structured failure classification and retry-based recovery.

**Evaluation results**

| Metric | Result |
|---|---:|
| Internal Python bugs evaluated | 20 |
| First-attempt resolution | 85% |
| Resolution within three attempts | 95% |

**Stack:** Python · FastAPI · Groq · Llama 3.3 70B · AST · Docker · Pytest · Git

</details>

<details open>
<summary><strong>🔎 MULTI-TENANT RAG BACKEND — HYBRID RETRIEVAL & RERANKING</strong></summary>

<div align="center">

<img src="https://img.shields.io/badge/FASTAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/POSTGRESQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/PINECONE-000000?style=flat-square"/>
<img src="https://img.shields.io/badge/BM25-SPARSE_SEARCH-475569?style=flat-square"/>
<img src="https://img.shields.io/badge/CROSS_ENCODER-RERANKING-7C3AED?style=flat-square"/>

</div>

A multi-tenant RAG backend for customer-support knowledge bases using Python, FastAPI, PostgreSQL, Pinecone, and Groq-hosted Llama models.

**Core engineering:**

- 🔎 Two-stage hybrid retrieval combining dense semantic search with BM25 sparse retrieval.
- ⚖️ Cross-Encoder reranking to select high-relevance context.
- 🧠 Conversational query rewriting using Llama and PostgreSQL-backed conversation history.
- 📄 Asynchronous PDF/DOCX/TXT ingestion, chunking and embedding generation.
- 📦 BM25 indexing and batched vector upserts.
- 🔐 JWT authentication, tenant ownership validation and metadata filtering.

**Stack:** Python · FastAPI · PostgreSQL · Pinecone · Groq · Llama · BM25 · Cross-Encoder

</details>

<details open>
<summary><strong>🎧 REAL-TIME TELUGU AI VOICE AGENT — LEAD QUALIFICATION</strong></summary>

<div align="center">

<img src="https://img.shields.io/badge/PIPECAT-5B21B6?style=flat-square"/>
<img src="https://img.shields.io/badge/SARVAM_AI-0F766E?style=flat-square"/>
<img src="https://img.shields.io/badge/EXOTEL-2563EB?style=flat-square"/>
<img src="https://img.shields.io/badge/FASTMCP-115E59?style=flat-square"/>
<img src="https://img.shields.io/badge/SILERO_VAD-475569?style=flat-square"/>

</div>

A real-time Telugu voice-agent pipeline for real-estate lead qualification over telephony, integrating speech processing, deterministic workflows and AI-powered conversational fallback.

**Core engineering:**

- ☎️ Exotel WebSockets with Sarvam streaming STT/TTS.
- 🤖 Llama-based conversational fallback.
- 🔗 Custom MCP server using FastMCP to integrate Gmail and internal call directories.
- 🎚️ Bidirectional audio streaming, Silero VAD, turn detection and audio buffering.
- 📡 μ-law media serialization for telephony.
- 📈 Turn-latency instrumentation, token/context tracking, barge-in analytics and transcript logging.
- 💾 SQLite/JSON persistence for debugging conversational behavior.

**Stack:** Python · FastAPI · Pipecat · Exotel · FastMCP · Sarvam AI · Silero VAD · Llama · Groq

</details>

---

# 🧰 THE ENGINEERING TOOLKIT

<div align="center">

## 💻 LANGUAGES & BACKEND

<img src="https://skillicons.dev/icons?i=python,js,nextjs,nodejs,express,fastapi&perline=6" />

<br/>

## 🧠 GENAI & ORCHESTRATION

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-202020?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MCP-0F766E?style=for-the-badge"/>
<img src="https://img.shields.io/badge/FastMCP-115E59?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenRouter-202020?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Llama-0467DF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge"/>

<br/>

## 🔍 RETRIEVAL & SEARCH

<img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white"/>
<img src="https://img.shields.io/badge/BM25-SPARSE_SEARCH-475569?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Semantic_Search-2563EB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Hybrid_Search-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Cross--Encoder-RERANKING-0891B2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Embeddings-6D28D9?style=for-the-badge"/>

<br/>

## 🗄️ DATABASES & INFRASTRUCTURE

<img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis,sqlite,docker,git,github&perline=8"/>

<br/>

<img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=222222"/>
<img src="https://img.shields.io/badge/Appwrite-FD366E?style=for-the-badge&logo=appwrite&logoColor=white"/>

<br/>

## 🎙️ VOICE AI

<img src="https://img.shields.io/badge/Pipecat-5B21B6?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Sarvam_AI-0F766E?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Exotel-2563EB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Silero_VAD-475569?style=for-the-badge"/>

</div>

---

# 📊 GITHUB COMMAND CENTER

<div align="center">

<a href="https://github.com/Durgam-vamshi">
<img height="180" src="https://github-readme-stats.vercel.app/api?username=Durgam-vamshi&show_icons=true&hide_border=true&rank_icon=github&theme=tokyonight&include_all_commits=true"/>
</a>

<a href="https://github.com/Durgam-vamshi">
<img height="180" src="https://streak-stats.demolab.com?user=Durgam-vamshi&hide_border=true&theme=tokyonight"/>
</a>

<br/><br/>

<img width="50%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Durgam-vamshi&layout=compact&hide_border=true&theme=tokyonight&langs_count=8"/>

</div>

---

# 🐍 THE CONTRIBUTION SNAKE

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Durgam-vamshi/Durgam-vamshi/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Durgam-vamshi/Durgam-vamshi/output/github-contribution-grid-snake.svg"/>
  <img alt="Animated GitHub contribution snake" src="https://raw.githubusercontent.com/Durgam-vamshi/Durgam-vamshi/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>

</div>

---

# 🤝 LET'S CONNECT

<div align="center">

### Always interested in conversations around:

**GenAI Engineering • RAG Quality • Agentic Systems • Voice AI • Backend Architecture**

<br/>

<a href="https://www.linkedin.com/in/vamshidurgam/">
<img src="https://img.shields.io/badge/LinkedIn-Connect_with_me-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:iamvamshidurgam@gmail.com">
<img src="https://img.shields.io/badge/Gmail-Say_Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://github.com/Durgam-vamshi">
<img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

### ⚡ DESIGN THE SYSTEM. BUILD THE WORKFLOW. MEASURE THE RESULT. SHIP IT.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:0891B2,50:6D28D9,100:080B1A"/>

</div>
