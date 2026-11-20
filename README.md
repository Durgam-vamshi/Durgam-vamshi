<!-- Profile README for github.com/Durgam-vamshi --><div align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,50:172554,100:312E81&height=190&section=header&text=Vamshi%20Durgam&fontSize=48&fontColor=FFFFFF&fontAlignY=38&desc=AI%20Engineer%20%7C%20GenAI%20%7C%20RAG%20%7C%20AI%20Agents&descAlignY=60&descSize=17" alt="Vamshi Durgam profile header" /><a href="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1000&color=8B9DFF&center=true&vCenter=true&width=850&lines=Building+production-oriented+GenAI+systems;RAG+%7C+Hybrid+Retrieval+%7C+Reranking;LLM+Agents+%7C+LangGraph+%7C+MCP;Real-time+Voice+AI+%7C+Backend+Engineering" target="_blank">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1000&color=8B9DFF&center=true&vCenter=true&width=850&lines=Building+production-oriented+GenAI+systems;RAG+%7C+Hybrid+Retrieval+%7C+Reranking;LLM+Agents+%7C+LangGraph+%7C+MCP;Real-time+Voice+AI+%7C+Backend+Engineering" alt="Animated introduction" />
</a><p>
  <a href="https://www.linkedin.com/in/vamshidurgam/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/Durgam-vamshi"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:iamvamshidurgam@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://x.com/DevXVamshi"><img src="https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
</p><img src="https://komarev.com/ghpvc/?username=Durgam-vamshi&style=flat-square&color=6366F1&label=PROFILE+VIEWS" alt="Profile views" /></div>$ whoami
I'm Vamshi Durgam, an AI Engineer with 2 years of experience based in Hyderabad, India. I build production-oriented LLM applications and AI-powered backend systems, with a focus on making them useful, measurable, secure, and reliable.

My work spans the engineering behind GenAI products: RAG pipelines, hybrid retrieval, reranking, agent workflows, tool/function calling, asynchronous APIs, and real-time voice AI. I enjoy taking an AI use case from system design through implementation, evaluation, and operational debugging.
- Currently: AI Engineer at Sync AI Technologies
- Core focus: Python, FastAPI, LangChain, LangGraph, RAG, MCP, and backend systems
- Interested in: Reliable AI agents, retrieval quality, LLM evaluation, and low-latency voice experiences
- Based in: Hyderabad, Telangana, India
⚙️ What I Build
<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 LLM Applications & Agents</h3>
      <p>LLM-powered workflows, structured outputs, function/tool calling, orchestration, and agent integrations that connect model reasoning to deterministic backend actions.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🔎 RAG & Retrieval Systems</h3>
      <p>Document ingestion, chunking, embeddings, semantic and BM25 retrieval, hybrid search, query rewriting, reranking, and tenant-aware knowledge retrieval.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎙️ Real-Time Voice AI</h3>
      <p>Streaming speech pipelines, WebSocket audio transport, turn detection, voice activity detection, telephony integrations, and latency instrumentation.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🛠️ AI Backend Engineering</h3>
      <p>Async APIs, persistence, authentication, integrations, observability, testing, and reliability practices for production-oriented AI services.</p>
    </td>
  </tr>
</table>🚀 Selected Projects
1. LLM-Powered Automated Repository-Level Software Repair System
Python · FastAPI · Groq · Llama 3.3 70B · AST · Docker · Pytest · Git

An LLM-driven software repair workflow that inspects a code repository, localizes bugs, generates patches, runs tests, and iteratively verifies fixes.
- Built AST-based code analysis and traceback-driven localization to identify relevant repository symbols and create bounded code context.
- Added safeguards around patch execution: Unified Diff validation, path-traversal protection, AST validation, Git rollback, and isolated task workspaces.
- Implemented Docker-isolated Pytest verification, structured failure classification, and retry-based recovery.
- Evaluation: tested against 20 internal Python bugs, reaching 85% first-attempt resolution and 95% resolution within three attempts.
2. Multi-Tenant RAG Backend with Hybrid Retrieval & Reranking
Python · FastAPI · PostgreSQL · Pinecone · Groq · Llama · BM25 · Cross-Encoder

A multi-tenant RAG backend for customer-support knowledge bases, designed to retrieve relevant context and support conversational questions.
- Combined dense semantic retrieval with BM25 sparse retrieval, followed by Cross-Encoder reranking.
- Implemented conversational query rewriting with Llama and PostgreSQL-backed conversation history to resolve ambiguous follow-up questions.
- Built asynchronous PDF, DOCX, and TXT ingestion with chunking, embedding generation, BM25 indexing, and batched vector upserts.
- Added JWT authentication, tenant ownership validation, and metadata filtering.
3. Real-Time Telugu AI Voice Agent for Real Estate Lead Qualification
Python · FastAPI · Pipecat · Exotel · FastMCP · Sarvam AI · Silero VAD · Llama · Groq

A real-time Telugu voice-agent pipeline that qualifies real-estate leads over telephony and connects conversations with business tools.
- Integrated Exotel WebSockets with streaming speech-to-text and text-to-speech using Sarvam AI, with an LLM-based conversational fallback.
- Built a custom MCP server with FastMCP to connect the agent to Gmail and internal call directories for lead context and follow-ups.
- Implemented bidirectional audio streaming, Silero VAD, turn detection, audio buffering, and μ-law media serialization.
- Designed a deterministic five-stage lead-qualification state machine, with an LLM fallback for unresolved intents.
- Added turn-latency instrumentation, token/context tracking, barge-in analytics, transcript logging, and SQLite/JSON persistence.
🧰 Technology Stack
Focused on the tools I use across AI engineering and backend development. Keeping the web stack lean: JavaScript and Next.js only.

Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=222222" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>AI, LLMs & Orchestration
<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-202020?style=for-the-badge" alt="LangGraph" />
  <img src="https://img.shields.io/badge/RAG-5B4BDB?style=for-the-badge" alt="RAG" />
  <img src="https://img.shields.io/badge/AI_Agents-6D28D9?style=for-the-badge" alt="AI Agents" />
  <img src="https://img.shields.io/badge/MCP-0F766E?style=for-the-badge" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/FastMCP-115E59?style=for-the-badge" alt="FastMCP" />
  <img src="https://img.shields.io/badge/Prompt_Engineering-475569?style=for-the-badge" alt="Prompt Engineering" />
  <img src="https://img.shields.io/badge/Embeddings-2563EB?style=for-the-badge" alt="Embeddings" />
  <img src="https://img.shields.io/badge/Tool_Calling-7C3AED?style=for-the-badge" alt="Tool calling" />
  <img src="https://img.shields.io/badge/Structured_Outputs-334155?style=for-the-badge" alt="Structured outputs" />
</p>Retrieval & Data
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
</p>Backend, APIs & Web
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge" alt="Pydantic" />
  <img src="https://img.shields.io/badge/AsyncIO-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python AsyncIO" />
  <img src="https://img.shields.io/badge/REST_APIs-334155?style=for-the-badge" alt="REST APIs" />
  <img src="https://img.shields.io/badge/WebSockets-2563EB?style=for-the-badge" alt="WebSockets" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
</p>Voice AI & Model Providers
<p>
  <img src="https://img.shields.io/badge/Pipecat-5B21B6?style=for-the-badge" alt="Pipecat" />
  <img src="https://img.shields.io/badge/Sarvam_AI-0F766E?style=for-the-badge" alt="Sarvam AI" />
  <img src="https://img.shields.io/badge/Exotel-2563EB?style=for-the-badge" alt="Exotel" />
  <img src="https://img.shields.io/badge/Silero_VAD-475569?style=for-the-badge" alt="Silero VAD" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge" alt="Groq" />
  <img src="https://img.shields.io/badge/OpenRouter-202020?style=for-the-badge" alt="OpenRouter" />
  <img src="https://img.shields.io/badge/Llama-0467DF?style=for-the-badge" alt="Llama" />
</p>LLMOps, Testing & Developer Tools
<p>
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge" alt="LangSmith" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=222222" alt="Firebase" />
  <img src="https://img.shields.io/badge/Appwrite-FD366E?style=for-the-badge&logo=appwrite&logoColor=white" alt="Appwrite" />
</p>📈 GitHub Activity
<div align="center"><img height="165" src="https://github-readme-stats.vercel.app/api?username=Durgam-vamshi&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="Vamshi's GitHub stats" />
<img height="165" src="https://streak-stats.demolab.com?user=Durgam-vamshi&theme=tokyonight&hide_border=true" alt="Vamshi's GitHub streak" /><img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Durgam-vamshi&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" /><img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Durgam-vamshi&theme=tokyo-night&hide_border=true" alt="GitHub contribution activity graph" /></div>🤝 Let's Connect
I'm always interested in conversations around GenAI engineering, RAG quality, agentic systems, voice AI, and backend architecture.
<p>
  <a href="https://www.linkedin.com/in/vamshidurgam/">LinkedIn: vamshidurgam</a> ·
  <a href="https://github.com/Durgam-vamshi">GitHub: Durgam-vamshi</a> ·
  <a href="mailto:iamvamshidurgam@gmail.com">Email: iamvamshidurgam@gmail.com</a>
</p><div align="center">Design. Build. Evaluate. Improve.
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:312E81,50:172554,100:0B1020&height=100&section=footer" alt="Decorative footer wave" /></div>
