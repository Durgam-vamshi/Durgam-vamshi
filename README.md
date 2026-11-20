<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&text=VAMSHI%20DURGAM&fontSize=54&fontColor=FFFFFF&fontAlignY=38&desc=AI%20ENGINEER%20%7C%20GENAI%20%7C%20AGENTIC%20SYSTEMS&descAlignY=62&descSize=16&animation=fadeIn&color=0:080B1A,35:172554,70:5B21B6,100:0891B2" alt="Vamshi Durgam - AI Engineer" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&duration=2600&pause=850&color=67E8F9&center=true&vCenter=true&width=850&height=50&lines=Building+production-minded+LLM+applications;RAG+%7C+Hybrid+Retrieval+%7C+Reranking;AI+Agents+%7C+MCP+%7C+Tool+Calling;Real-time+Voice+AI+%7C+Reliable+Backends" alt="Animated AI engineering tagline" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vamshidurgam/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:iamvamshidurgam@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Durgam-vamshi"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://x.com/DevXVamshi"><img src="https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Durgam-vamshi&style=flat-square&color=7C3AED&label=PROFILE+VIEWS" alt="Profile views" />
  <img src="https://img.shields.io/badge/ROLE-AI_ENGINEER-0891B2?style=flat-square" alt="AI Engineer" />
  <img src="https://img.shields.io/badge/EXPERIENCE-2_YEARS-7C3AED?style=flat-square" alt="2 years of experience" />
  <img src="https://img.shields.io/badge/LOCATION-HYDERABAD%2C_INDIA-334155?style=flat-square" alt="Hyderabad, India" />
</p>

---

## ⚡ About me

I'm **Vamshi Durgam**, an **AI Engineer at Sync AI Technologies** building LLM-powered applications, retrieval systems, agent workflows, and real-time voice experiences using Python and FastAPI.

I focus on the engineering around the model call: **document ingestion, retrieval quality, orchestration, evaluation, security, latency, and backend reliability**. I enjoy turning AI capabilities into useful systems rather than stopping at a prompt-and-response demo.

<p align="center">
  <strong>🧠 LLM Applications</strong> &nbsp; · &nbsp;
  <strong>🔎 Retrieval Engineering</strong> &nbsp; · &nbsp;
  <strong>🤖 Agentic Workflows</strong> &nbsp; · &nbsp;
  <strong>🎙️ Voice AI</strong>
</p>

---

## 🧭 How I think about AI systems

### 01 · RAG and knowledge retrieval

```mermaid
flowchart TD
    A[Documents: PDF, DOCX, TXT] --> B[FastAPI ingestion]
    B --> C[Chunking and metadata]
    C --> D[Embedding generation]
    D --> E[(Pinecone vector index)]

    Q[User query] --> R[Query rewriting]
    R --> S[Dense vector retrieval]
    R --> T[BM25 sparse retrieval]
    E --> S
    S --> U[Hybrid result fusion]
    T --> U
    U --> V[Cross-Encoder reranking]
    V --> W[Relevant context]
    W --> X[Groq-hosted Llama]
    X --> Y[Grounded answer]
```

### 02 · Repository-level software repair agent

```mermaid
flowchart TD
    A[Python repository] --> B[AST analysis]
    B --> C[Traceback-based localization]
    C --> D[Bounded code context]
    D --> E[Llama 3.3 70B]
    E --> F[Patch generation]
    F --> G[Diff and path validation]
    G --> H[Docker-isolated Pytest]
    H --> I{Tests pass?}
    I -->|Yes| J[Verified repair]
    I -->|No| K[Failure classification]
    K --> E
```

### 03 · Real-time Telugu voice agent

```mermaid
flowchart TD
    A[Incoming call] --> B[Exotel WebSocket]
    B --> C[FastAPI and Pipecat]
    C --> D[Silero VAD and turn detection]
    D --> E[Lead qualification state machine]
    E -->|Known intent| F[Deterministic action]
    E -->|Needs language reasoning| G[Sarvam streaming STT and TTS]
    G --> H[Llama conversational fallback]
    F --> I[FastMCP server]
    H --> I
    I --> J[Gmail and internal call directory]
    J --> K[Voice response]
```

---

## 🚀 Featured builds

### 🧑‍💻 AI SWE Agent — Repository-level software repair

**Python · FastAPI · Groq · Llama 3.3 70B · AST · Docker · Pytest · Git**

An LLM-driven software repair workflow that explores a repository, localizes bugs, proposes patches, executes tests, analyzes failures, and iteratively verifies repairs.

- 🧭 Built AST-based code analysis and traceback-driven localization to identify relevant repository symbols.
- 🧱 Constructed bounded code context to keep repair prompts focused.
- 🛡️ Added Unified Diff validation, path-traversal protection, AST validation, Git rollback, and isolated task workspaces.
- 🐳 Implemented Docker-isolated Pytest execution, structured failure classification, and retry-based recovery.

| Internal evaluation | Result |
|:---|---:|
| Python bugs evaluated | **20** |
| First-attempt resolution | **85%** |
| Resolution within three attempts | **95%** |

### 🔎 Multi-Tenant RAG Backend — Hybrid retrieval and reranking

**Python · FastAPI · PostgreSQL · Pinecone · Groq · Llama · BM25 · Cross-Encoder**

A multi-tenant RAG backend for customer-support knowledge bases and conversational queries.

- 🔎 Combined dense semantic retrieval with BM25 sparse retrieval, followed by Cross-Encoder reranking.
- 🧠 Implemented conversational query rewriting using Llama and PostgreSQL-backed conversation history.
- 📄 Built asynchronous PDF, DOCX, and TXT ingestion with chunking, embedding generation, BM25 indexing, and batched vector upserts.
- 🔐 Added JWT authentication, tenant ownership validation, and metadata filtering.

### 🎧 Telugu AI Voice Agent — Real-time real-estate lead qualification

**Python · FastAPI · Pipecat · Exotel · FastMCP · Sarvam AI · Silero VAD · Llama · Groq**

A real-time Telugu voice-agent pipeline for real-estate lead qualification over telephony, combining deterministic workflow logic with conversational AI fallback.

- ☎️ Integrated Exotel WebSockets with Sarvam streaming STT/TTS and Llama-based conversational fallback.
- 🔗 Built a custom MCP server using FastMCP to connect the voice agent with Gmail and internal call directories.
- 🎚️ Implemented bidirectional audio streaming, Silero VAD, turn detection, buffering, and μ-law media serialization.
- 📈 Added turn-latency instrumentation, token/context tracking, barge-in analytics, transcript logging, and SQLite/JSON persistence.

---

## 🧰 Engineering toolkit

<p align="center"><strong>Languages and backend</strong></p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,js,nextjs,nodejs,express,fastapi&perline=6" alt="Python, JavaScript, Next.js, Node.js, Express, and FastAPI" />
</p>

<p align="center"><strong>LLMs, orchestration, and observability</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-202020?style=for-the-badge" alt="LangGraph" />
  <img src="https://img.shields.io/badge/MCP-0F766E?style=for-the-badge" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/FastMCP-115E59?style=for-the-badge" alt="FastMCP" />
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge" alt="LangSmith" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white" alt="Groq" />
  <img src="https://img.shields.io/badge/OpenRouter-202020?style=for-the-badge" alt="OpenRouter" />
  <img src="https://img.shields.io/badge/Llama-0467DF?style=for-the-badge" alt="Llama" />
</p>

<p align="center"><strong>Retrieval and search</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge" alt="Pinecone" />
  <img src="https://img.shields.io/badge/BM25-Sparse_Search-475569?style=for-the-badge" alt="BM25" />
  <img src="https://img.shields.io/badge/Semantic_Search-2563EB?style=for-the-badge" alt="Semantic search" />
  <img src="https://img.shields.io/badge/Hybrid_Search-7C3AED?style=for-the-badge" alt="Hybrid search" />
  <img src="https://img.shields.io/badge/Cross_Encoder-Reranking-0891B2?style=for-the-badge" alt="Cross-Encoder reranking" />
  <img src="https://img.shields.io/badge/Embeddings-6D28D9?style=for-the-badge" alt="Embeddings" />
</p>

<p align="center"><strong>Databases and infrastructure</strong></p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis,sqlite,docker,git,github&perline=8" alt="PostgreSQL, MongoDB, MySQL, Redis, SQLite, Docker, Git, and GitHub" />
  <br />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge" alt="Pydantic" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=222222" alt="Firebase" />
  <img src="https://img.shields.io/badge/Appwrite-FD366E?style=for-the-badge&logo=appwrite&logoColor=white" alt="Appwrite" />
</p>

<p align="center"><strong>Voice AI</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/Pipecat-5B21B6?style=for-the-badge" alt="Pipecat" />
  <img src="https://img.shields.io/badge/Sarvam_AI-0F766E?style=for-the-badge" alt="Sarvam AI" />
  <img src="https://img.shields.io/badge/Exotel-2563EB?style=for-the-badge" alt="Exotel" />
  <img src="https://img.shields.io/badge/Silero_VAD-475569?style=for-the-badge" alt="Silero VAD" />
</p>

---

## 📊 GitHub stats

<p align="center">
  <a href="https://github.com/Durgam-vamshi">
    <img height="170" src="https://github-readme-stats.vercel.app/api?username=Durgam-vamshi&show_icons=true&hide_border=true&rank_icon=github&theme=tokyonight" alt="Vamshi's GitHub statistics" />
  </a>
  <a href="https://github.com/Durgam-vamshi">
    <img height="170" src="https://streak-stats.demolab.com?user=Durgam-vamshi&hide_border=true&theme=tokyonight" alt="Vamshi's GitHub contribution streak" />
  </a>
</p>

---

## 🐍 Contribution snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Durgam-vamshi/Durgam-vamshi/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Durgam-vamshi/Durgam-vamshi/output/github-snake.svg" />
    <img src="https://raw.githubusercontent.com/Durgam-vamshi/Durgam-vamshi/output/ocean.gif" alt="Animated snake travelling across my GitHub contribution graph" width="100%" />
  </picture>
</p>

<p align="center">
  <sub>If the snake is not visible immediately after adding the workflow, run the <a href="https://github.com/Durgam-vamshi/Durgam-vamshi/actions">GitHub Actions workflow</a> once to generate the images.</sub>
</p>

---

## 🤝 Let's connect

<p align="center">
  I'm always interested in conversations about <strong>GenAI engineering, RAG quality, agentic systems, Voice AI, and backend architecture.</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vamshidurgam/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
  <a href="mailto:iamvamshidurgam@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Send email" /></a>
  <a href="https://github.com/Durgam-vamshi"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="Follow on GitHub" /></a>
</p>

<p align="center">
  <strong>DESIGN THE SYSTEM · BUILD THE WORKFLOW · MEASURE THE RESULT · SHIP IT</strong>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:0891B2,50:6D28D9,100:080B1A" alt="Gradient footer banner" width="100%" />
</p>
