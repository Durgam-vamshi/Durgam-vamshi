<div align="center"><img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=235&text=VAMSHI%20DURGAM&fontSize=56&fontColor=FFFFFF&fontAlignY=38&desc=AI%20ENGINEER%20%20%E2%80%A2%20%20GENAI%20%20%E2%80%A2%20%20AGENTIC%20SYSTEMS&descAlignY=62&descSize=16&color=0:080B1A,30:172554,65:5B21B6,100:0891B2" alt="Vamshi Durgam — AI Engineer banner" /><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=19&duration=2600&pause=800&color=67E8F9&center=true&vCenter=true&width=900&height=55&lines=I+build+AI+systems%2C+not+just+LLM+demos.;RAG+%7C+Hybrid+Retrieval+%7C+Reranking;AI+Agents+%7C+MCP+%7C+Tool+Calling;Real-time+Voice+AI+%7C+Reliable+Backends" alt="Animated AI engineering tagline" /><table border="0">
<tr>
<td align="center" width="58%">
  <h3>⚡ Turning LLM capabilities into dependable software.</h3>
  <p>AI Engineer focused on retrieval quality, agent workflows, voice interfaces, and backend reliability.</p>
  <a href="https://www.linkedin.com/in/vamshidurgam/"><img src="https://img.shields.io/badge/LINKEDIN-LET'S_CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:iamvamshidurgam@gmail.com"><img src="https://img.shields.io/badge/EMAIL-SAY_HELLO-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Durgam-vamshi"><img src="https://img.shields.io/badge/GITHUB-EXPLORE_MY_CODE-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</td>
<td align="center" width="42%">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="280" alt="Looping developer coding animation" />
</td>
</tr>
</table><img src="https://komarev.com/ghpvc/?username=Durgam-vamshi&style=flat-square&color=7C3AED&label=PROFILE+VIEWS" alt="Profile views" />
<img src="https://img.shields.io/badge/EXPERIENCE-2%2B_YEARS-0891B2?style=flat-square" alt="2 plus years of experience" />
<img src="https://img.shields.io/badge/LOCATION-HYDERABAD%2C_INDIA-334155?style=flat-square&logo=googlemaps&logoColor=white" alt="Hyderabad, India" /></div>👋 About me
I'm Vamshi Durgam, an AI Engineer building LLM-powered applications, retrieval systems, agent workflows, and real-time voice experiences using Python and FastAPI.

I care about the engineering around the model call: data ingestion, retrieval quality, orchestration, evaluation, security, latency, and production reliability. I enjoy turning AI capabilities into useful backend systems rather than stopping at a prompt-and-response demo.
<div align="center">🧠 LLM applications	🔎 Retrieval engineering	🤖 Agentic workflows	🎙️ Voice AI
Structured outputs, tool calling	Hybrid search, reranking	LangGraph, MCP	Streaming STT/TTS, VAD


</div>🗺️ How I think about AI systems
01 · RAG and knowledge retrieval
```mermaid
flowchart LR
    A["📄 PDF / DOCX / TXT"] --> B["⚙️ FastAPI ingestion"]
    B --> C["✂️ Chunking + metadata"]
    C --> D["🔢 Embeddings"]
    D --> V[("🗄️ Pinecone")]

    Q["💬 User query"] --> API["⚡ FastAPI + tenant context"]
    API --> R["🧠 Query rewriting"]
    R --> DS["🔎 Dense retrieval"]
    R --> BM["📚 BM25 retrieval"]
    V --> DS
    DS --> F["⚖️ Hybrid fusion"]
    BM --> F
    F --> CE["🎯 Cross-Encoder reranking"]
    CE --> CTX["🧩 Relevant context"]
    CTX --> LLM["🤖 Groq / Llama"]
    LLM --> OUT["✅ Grounded answer"]
```
02 · Repository-level software repair agent
```mermaid
flowchart TD
    REPO["📦 Python repository"] --> AST["🧭 AST + traceback analysis"]
    AST --> CTX["✂️ Bounded code context"]
    CTX --> LLM["🧠 Llama 3.3 70B"]
    LLM --> PATCH["📝 Patch generation"]
    PATCH --> GUARD["🛡️ Diff, path and AST validation"]
    GUARD --> TEST["🐳 Docker-isolated Pytest"]
    TEST --> PASS{"Tests passed?"}
    PASS -->|Yes| DONE["✅ Verified repair"]
    PASS -->|No| FAIL["🧪 Failure classification"]
    FAIL --> LLM
```
03 · Real-time Telugu voice agent
```mermaid
flowchart LR
    CALL["☎️ Incoming call"] --> EXO["🔌 Exotel WebSocket"]
    EXO --> PIPE["🎛️ FastAPI + Pipecat"]
    PIPE --> VAD["👂 Silero VAD + turn detection"]
    VAD --> STATE["🧭 Lead qualification state machine"]
    STATE -->|Known intent| FAST["⚡ Deterministic action"]
    STATE -->|Needs language reasoning| LLM["🤖 Sarvam STT/TTS + Llama fallback"]
    FAST --> MCP["🔗 FastMCP server"]
    LLM --> MCP
    MCP --> TOOLS["📨 Gmail + internal call directory"]
    TOOLS --> AUDIO["🔊 Voice response"]
```
🚀 Featured builds
<details open>
<summary><strong>🧑‍💻 AI SWE Agent · Repository-level software repair</strong> <img src="https://img.shields.io/badge/95%25-resolved_within_3_attempts-16A34A?style=flat-square" alt="95 percent resolution within three attempts" /></summary>Python · FastAPI · Groq · Llama 3.3 70B · AST · Docker · Pytest · Git

An LLM-driven software repair workflow that explores a repository, localizes bugs, proposes patches, executes tests, analyzes failures, and iteratively verifies repairs.
- 🧭 AST-based code analysis and traceback-driven localization to identify relevant repository symbols.
- 🧱 Bounded code-context construction to keep repair prompts focused.
- 🛡️ Unified Diff validation, path-traversal protection, AST validation, Git rollback, and isolated task workspaces.
- 🐳 Docker-isolated Pytest execution with structured failure classification and retry-based recovery.
Internal evaluation	Result
Python bugs evaluated	20
First-attempt resolution	85%
Resolution within three attempts	95%


</details><details open>
<summary><strong>🔎 Multi-Tenant RAG Backend · Hybrid retrieval and reranking</strong> <img src="https://img.shields.io/badge/DENSE_%2B_BM25-HYBRID_SEARCH-2563EB?style=flat-square" alt="Dense and BM25 hybrid search" /></summary>Python · FastAPI · PostgreSQL · Pinecone · Groq · Llama · BM25 · Cross-Encoder

A tenant-aware RAG backend for customer-support knowledge bases and conversational queries.
- 🔎 Combined dense semantic retrieval with BM25 sparse retrieval, followed by Cross-Encoder reranking.
- 🧠 Implemented conversational query rewriting using Llama and PostgreSQL-backed conversation history.
- 📄 Built asynchronous PDF/DOCX/TXT ingestion, chunking, embedding generation, BM25 indexing, and batched vector upserts.
- 🔐 Added JWT authentication, tenant ownership validation, and metadata filtering.
</details><details open>
<summary><strong>🎧 Telugu AI Voice Agent · Real-time real-estate lead qualification</strong> <img src="https://img.shields.io/badge/STREAMING-STT_%2B_TTS-7C3AED?style=flat-square" alt="Streaming speech to text and text to speech" /></summary>Python · FastAPI · Pipecat · Exotel · FastMCP · Sarvam AI · Silero VAD · Llama · Groq

A real-time Telugu voice-agent pipeline for real-estate lead qualification over telephony, combining deterministic workflow logic with conversational AI fallback.
- ☎️ Integrated Exotel WebSockets with Sarvam streaming STT/TTS and Llama-based conversational fallback.
- 🔗 Built a custom MCP server using FastMCP to connect the voice agent with Gmail and internal call directories.
- 🎚️ Implemented bidirectional audio streaming, Silero VAD, turn detection, buffering, and μ-law media serialization.
- 📈 Added turn-latency instrumentation, token/context tracking, barge-in analytics, transcript logging, and SQLite/JSON persistence.
</details>🧰 Engineering toolkit
<div align="center">Languages and backend
<img src="https://skillicons.dev/icons?i=python,js,nextjs,nodejs,express,fastapi&perline=6" alt="Python, JavaScript, Next.js, Node.js, Express and FastAPI" />LLMs, orchestration and observability
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/LangGraph-202020?style=for-the-badge" alt="LangGraph" />
<img src="https://img.shields.io/badge/MCP-0F766E?style=for-the-badge" alt="Model Context Protocol" />
<img src="https://img.shields.io/badge/FastMCP-115E59?style=for-the-badge" alt="FastMCP" />
<img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge" alt="LangSmith" />
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white" alt="Groq" />
<img src="https://img.shields.io/badge/OpenRouter-202020?style=for-the-badge" alt="OpenRouter" />
<img src="https://img.shields.io/badge/Llama-0467DF?style=for-the-badge" alt="Llama" />Retrieval and search
<img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge" alt="Pinecone" />
<img src="https://img.shields.io/badge/BM25-SPARSE_SEARCH-475569?style=for-the-badge" alt="BM25" />
<img src="https://img.shields.io/badge/SEMANTIC_SEARCH-2563EB?style=for-the-badge" alt="Semantic search" />
<img src="https://img.shields.io/badge/HYBRID_SEARCH-7C3AED?style=for-the-badge" alt="Hybrid search" />
<img src="https://img.shields.io/badge/CROSS_ENCODER-RERANKING-0891B2?style=for-the-badge" alt="Cross-Encoder reranking" />
<img src="https://img.shields.io/badge/EMBEDDINGS-6D28D9?style=for-the-badge" alt="Embeddings" />Databases and infrastructure
<img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis,sqlite,docker,git,github&perline=8" alt="PostgreSQL, MongoDB, MySQL, Redis, SQLite, Docker, Git and GitHub" /><img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge" alt="Pydantic" />
<img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=222222" alt="Firebase" />
<img src="https://img.shields.io/badge/Appwrite-FD366E?style=for-the-badge&logo=appwrite&logoColor=white" alt="Appwrite" />Voice AI
<img src="https://img.shields.io/badge/Pipecat-5B21B6?style=for-the-badge" alt="Pipecat" />
<img src="https://img.shields.io/badge/Sarvam_AI-0F766E?style=for-the-badge" alt="Sarvam AI" />
<img src="https://img.shields.io/badge/Exotel-2563EB?style=for-the-badge" alt="Exotel" />
<img src="https://img.shields.io/badge/Silero_VAD-475569?style=for-the-badge" alt="Silero VAD" /></div><sub>Frontend/UI technologies are intentionally trimmed down; JavaScript and Next.js are retained as requested.</sub>
📈 GitHub stats
<div align="center"><a href="https://github.com/Durgam-vamshi">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Durgam-vamshi&show_icons=true&hide_border=true&rank_icon=github&theme=tokyonight&include_all_commits=true" alt="Vamshi's GitHub stats" />
</a>
<a href="https://github.com/Durgam-vamshi">
  <img height="170" src="https://streak-stats.demolab.com?user=Durgam-vamshi&hide_border=true&theme=tokyonight" alt="Vamshi's GitHub contribution streak" />
</a>
<img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Durgam-vamshi&layout=compact&hide=css,html&hide_border=true&theme=tokyonight&langs_count=8" alt="Most used programming languages, excluding HTML and CSS" /></div>🐍 Contribution snake · animated
<div align="center"><img src="https://raw.githubusercontent.com/Durgam-vamshi/Durgam-vamshi/output/ocean.gif" width="100%" alt="Animated ocean-colour snake game moving across Vamshi's GitHub contribution graph" /><sub>Alternative themes: <a href="https://raw.githubusercontent.com/Durgam-vamshi/Durgam-vamshi/output/github-snake.svg">light SVG</a> · <a href="https://raw.githubusercontent.com/Durgam-vamshi/Durgam-vamshi/output/github-snake-dark.svg">dark SVG</a></sub>
</div>🤝 Let's connect
<div align="center">Always happy to talk about GenAI engineering, RAG quality, agentic systems, Voice AI, and backend architecture.

<a href="https://www.linkedin.com/in/vamshidurgam/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
<a href="mailto:iamvamshidurgam@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Send email" /></a>
<a href="https://github.com/Durgam-vamshi"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="Follow on GitHub" /></a>



DESIGN THE SYSTEM · BUILD THE WORKFLOW · MEASURE THE RESULT · SHIP IT
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:0891B2,50:6D28D9,100:080B1A" alt="Animated gradient footer" /></div>
