<!--
  Profile README: https://github.com/Durgam-vamshi
  Design: AI engineering / terminal-inspired, with compact sections and expandable project details.
--><div align="center"><img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10172A,45:312E81,100:0F766E&height=210&section=header&text=Vamshi%20Durgam&fontSize=52&fontColor=F8FAFC&fontAlignY=38&desc=AI%20ENGINEER%20%20%E2%80%A2%20%20GENAI%20%20%E2%80%A2%20%20BACKEND%20SYSTEMS&descAlignY=60&descSize=15" alt="Vamshi Durgam — AI Engineer" /><a href="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1100&color=67E8F9&center=true&vCenter=true&width=760&lines=I+turn+LLM+ideas+into+working+systems.;RAG+%2B+Hybrid+Retrieval+%2B+Reranking.;Agents+%2B+MCP+%2B+Tool+Calling.;Real-time+Voice+AI+%2B+Backend+Engineering.">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1100&color=67E8F9&center=true&vCenter=true&width=760&lines=I+turn+LLM+ideas+into+working+systems.;RAG+%2B+Hybrid+Retrieval+%2B+Reranking.;Agents+%2B+MCP+%2B+Tool+Calling.;Real-time+Voice+AI+%2B+Backend+Engineering." alt="Animated AI engineering tagline" />
</a>
<a href="https://www.linkedin.com/in/vamshidurgam/"><img src="https://img.shields.io/badge/LINKEDIN-Let's%20connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://github.com/Durgam-vamshi"><img src="https://img.shields.io/badge/GITHUB-Follow%20my%20work-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="mailto:iamvamshidurgam@gmail.com"><img src="https://img.shields.io/badge/EMAIL-Say%20hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://x.com/DevXVamshi"><img src="https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>



<img src="https://komarev.com/ghpvc/?username=Durgam-vamshi&style=for-the-badge&color=0F766E&label=PROFILE+VIEWS" alt="Profile views" /></div>01 / About me
Hey! I'm Vamshi Durgam, an AI Engineer based in Hyderabad, India. I build LLM-powered applications and the backend systems that make them useful outside a notebook.

My day-to-day interests sit at the intersection of RAG, retrieval quality, AI agents, tool calling, MCP, and real-time voice AI. I care about more than getting a model to respond: I like engineering the ingestion, orchestration, evaluation, security, and reliability around it.
vamshi = {
    "role": "AI Engineer",
    "focus": ["GenAI", "RAG", "AI Agents", "Voice AI"],
    "building_with": ["Python", "FastAPI", "LangChain", "LangGraph"],
    "location": "Hyderabad, India",
    "mindset": "Build → Measure → Improve"
}
<div align="center">
  <img src="https://img.shields.io/badge/EXPERIENCE-2%2B%20YEARS-312E81?style=flat-square" alt="2 plus years experience" />
  <img src="https://img.shields.io/badge/CORE-Python%20%7C%20FastAPI-0F766E?style=flat-square" alt="Python and FastAPI" />
  <img src="https://img.shields.io/badge/FOCUS-Production%20GenAI-7C3AED?style=flat-square" alt="Production GenAI" />
</div>02 / What I work on
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 LLM Apps & Agent Workflows</h3>
      <sub>LANGCHAIN · LANGGRAPH · MCP</sub>
      <p>Structured outputs, tool/function calling, orchestration, and workflows that connect LLM decisions to reliable backend actions.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🔎 RAG & Retrieval Engineering</h3>
      <sub>EMBEDDINGS · BM25 · RERANKING</sub>
      <p>Document ingestion, semantic and sparse retrieval, hybrid search, query rewriting, reranking, and tenant-aware knowledge systems.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎙️ Real-Time Voice AI</h3>
      <sub>PIPECAT · SARVAM · EXOTEL</sub>
      <p>Streaming speech pipelines, WebSocket audio, VAD, turn detection, telephony integrations, and latency instrumentation.</p>
    </td>
    <td width="50%" valign="top">
      <h3>⚙️ AI Backend Engineering</h3>
      <sub>FASTAPI · ASYNCIO · POSTGRESQL</sub>
      <p>Async APIs, persistence, authentication, external integrations, observability, testing, and production reliability.</p>
    </td>
  </tr>
</table>03 / Featured builds
<details open>
  <summary><strong>🧑‍💻 LLM-Powered Repository-Level Software Repair Agent</strong> · <code>AI SWE Agent</code></summary>
  <br />
  <p><strong>Python · FastAPI · Groq · Llama 3.3 70B · AST · Docker · Pytest · Git</strong></p>
  An LLM-driven repair workflow that explores a repository, locates bugs, proposes patches, runs tests, and iterates on failures.
  <ul>
    <li>Built AST-based code analysis and traceback-driven localization to identify relevant repository symbols and create bounded context.</li>
    <li>Hardened patch execution with Unified Diff validation, path-traversal protection, AST validation, Git rollback, and isolated workspaces.</li>
    <li>Added Docker-isolated Pytest verification, structured failure classification, and retry-based recovery.</li>
    <li><strong>Evaluation:</strong> 20 internal Python bugs · <strong>85%</strong> first-attempt resolution · <strong>95%</strong> within three attempts.</li>
  </ul>
</details><details open>
  <summary><strong>🔍 Multi-Tenant RAG Backend with Hybrid Retrieval & Reranking</strong></summary>
  <br />
  <p><strong>Python · FastAPI · PostgreSQL · Pinecone · Groq · Llama · BM25 · Cross-Encoder</strong></p>
  A multi-tenant knowledge retrieval backend for customer-support use cases, designed for relevant context retrieval across conversational queries.
  <ul>
    <li>Combined dense semantic retrieval with BM25 sparse retrieval, then applied Cross-Encoder reranking.</li>
    <li>Implemented conversational query rewriting with Llama and PostgreSQL-backed history for ambiguous follow-up questions.</li>
    <li>Built asynchronous PDF/DOCX/TXT ingestion, chunking, embeddings, BM25 indexing, and batched vector upserts.</li>
    <li>Added JWT authentication, tenant ownership validation, and metadata filtering.</li>
  </ul>
</details><details open>
  <summary><strong>🎧 Real-Time Telugu AI Voice Agent for Lead Qualification</strong></summary>
  <br />
  <p><strong>Python · FastAPI · Pipecat · Exotel · FastMCP · Sarvam AI · Silero VAD · Llama · Groq</strong></p>
  A Telugu voice-agent pipeline for real-estate lead qualification over telephony, with business-tool integrations and an LLM fallback path.
  <ul>
    <li>Integrated Exotel WebSockets with Sarvam streaming STT/TTS and Llama-based conversational fallback.</li>
    <li>Built a custom MCP server with FastMCP to connect the agent to Gmail and internal call directories.</li>
    <li>Implemented bidirectional audio streaming, Silero VAD, turn detection, buffering, and μ-law media serialization.</li>
    <li>Designed a deterministic five-stage qualification state machine and added latency, token/context, barge-in, and transcript instrumentation.</li>
  </ul>
</details>04 / My toolbox
<p align="center"><sub>THE STACK I USE TO BUILD, SHIP, AND DEBUG AI SYSTEMS</sub></p>🐍 Languages
<p>
  <img src="https://skillicons.dev/icons?i=python,js,sql" alt="Python, JavaScript and SQL" />
</p>🧠 GenAI, LLMs & orchestration
<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-202020?style=for-the-badge" alt="LangGraph" />
  <img src="https://img.shields.io/badge/RAG-5B4BDB?style=for-the-badge" alt="RAG" />
  <img src="https://img.shields.io/badge/AI_Agents-6D28D9?style=for-the-badge" alt="AI Agents" />
  <img src="https://img.shields.io/badge/MCP-0F766E?style=for-the-badge" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/FastMCP-115E59?style=for-the-badge" alt="FastMCP" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge" alt="Groq" />
  <img src="https://img.shields.io/badge/OpenRouter-202020?style=for-the-badge" alt="OpenRouter" />
  <img src="https://img.shields.io/badge/Llama-0467DF?style=for-the-badge" alt="Llama" />
</p>🔎 Retrieval & databases
<p>
  <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white" alt="Pinecone" />
  <img src="https://img.shields.io/badge/BM25-475569?style=for-the-badge" alt="BM25" />
  <img src="https://img.shields.io/badge/Hybrid_Search-0F766E?style=for-the-badge" alt="Hybrid search" />
  <img src="https://img.shields.io/badge/Reranking-7C3AED?style=for-the-badge" alt="Reranking" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
</p>⚙️ Backend & web
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge" alt="Pydantic" />
  <img src="https://img.shields.io/badge/AsyncIO-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python AsyncIO" />
  <img src="https://img.shields.io/badge/REST_APIs-334155?style=for-the-badge" alt="REST APIs" />
  <img src="https://img.shields.io/badge/WebSockets-2563EB?style=for-the-badge" alt="WebSockets" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
</p>🎙️ Voice AI
<p>
  <img src="https://img.shields.io/badge/Pipecat-5B21B6?style=for-the-badge" alt="Pipecat" />
  <img src="https://img.shields.io/badge/Sarvam_AI-0F766E?style=for-the-badge" alt="Sarvam AI" />
  <img src="https://img.shields.io/badge/Exotel-2563EB?style=for-the-badge" alt="Exotel" />
  <img src="https://img.shields.io/badge/Silero_VAD-475569?style=for-the-badge" alt="Silero VAD" />
</p>🧪 Shipping, testing & observability
<p>
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge" alt="LangSmith" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=222222" alt="Firebase" />
  <img src="https://img.shields.io/badge/Appwrite-FD366E?style=for-the-badge&logo=appwrite&logoColor=white" alt="Appwrite" />
</p>05 / GitHub corner
<div align="center"><a href="https://github.com/Durgam-vamshi">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Durgam-vamshi&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="Vamshi's GitHub stats" />
</a>
<a href="https://github.com/Durgam-vamshi">
  <img height="165" src="https://streak-stats.demolab.com?user=Durgam-vamshi&theme=tokyonight&hide_border=true" alt="Vamshi's GitHub streak" />
</a>
<img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Durgam-vamshi&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Most used languages" /></div>🐍 Contribution snake
<div align="center"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake.svg" />
  <img alt="Animated GitHub contribution snake" src="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake.svg" width="100%" />
</picture></div>06 / Let's connect
Got an interesting problem around RAG, agentic workflows, voice AI, or AI backend engineering? Let's talk.
<div align="center">
  <a href="https://www.linkedin.com/in/vamshidurgam/"><img src="https://img.shields.io/badge/LinkedIn-vamshidurgam-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:iamvamshidurgam@gmail.com"><img src="https://img.shields.io/badge/Email-iamvamshidurgam%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Durgam-vamshi"><img src="https://img.shields.io/badge/GitHub-Durgam--vamshi-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</div><div align="center">
  <br />
  <b>Less hype. More engineering. More shipping. ⚡</b>
  <br /><br />
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F766E,50:312E81,100:10172A&height=115&section=footer" alt="Decorative footer" />
</div>
