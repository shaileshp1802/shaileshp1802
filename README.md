<h1 align="center">Hi, I'm Shailesh Paliwal 👋</h1>
<h3 align="center">AI Engineer · GenAI, RAG & Agentic Systems · Jaipur, India</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/shaileshp1802/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:work.shailesh.paliwal@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://twitter.com/shaileshp1802"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://chatcraft.in"><img src="https://img.shields.io/badge/ChatCraft-chatcraft.in-FF6B4A?style=for-the-badge" alt="ChatCraft" /></a>
</p>

I build production GenAI systems: RAG pipelines, multi-agent workflows and document-AI automation. By day I'm an AI Engineer at **Celebal Technologies**, shipping enterprise solutions on Azure AI and Databricks. After hours I build and run my own AI products.

- 🤖 Building **[ChatCraft](https://chatcraft.in)**, a multi-tenant platform for AI customer-support chatbots
- 🧠 Focus: RAG, agentic AI (Semantic Kernel, LangGraph), LLMs & VLMs, prompt engineering
- 🏅 Claude Certified Architect (Professional) · Databricks ML Engineer Professional · Databricks GenAI Engineer Associate
- 📫 Reach me at **work.shailesh.paliwal@gmail.com**

---

## 🚀 What I've built

### Products

**[ChatCraft](https://chatcraft.in)**: AI customer support that answers from your own docs
- Multi-tenant chatbot builder: sign up, upload docs or crawl a site, and publish a bot as a link, a one-line website widget or a **WhatsApp Business** channel
- Hybrid retrieval: follow-up query rewriting, pgvector + Postgres full-text search fused with RRF, a local cross-encoder reranker and a relevance gate that refuses off-topic questions without calling the LLM
- Azure OpenAI (AI Foundry) with automatic Groq fallback, SSE token streaming, per-tenant vector isolation, metered plans and billing (Polar/Stripe), admin answer traces and analytics
- Lifted top-5 retrieval accuracy from 82% to 89% on a 28-question eval, with correct handling of follow-ups and off-topic queries
- `FastAPI` `Next.js` `PostgreSQL/pgvector` `Azure OpenAI` `Groq` `Docker` `Caddy`

**Keep Posting**: a self-hosted social publishing pipeline
- Schedules and publishes posts to **Instagram, Threads and X** from one entry with per-platform copy, with an approval gate, a web UI and a `kp` CLI
- Converts images and video per platform (ffmpeg), handles carousels, Reels and Stories, refreshes Meta tokens automatically and prevents double-posting through idempotent container reuse
- Runs on Docker, GitHub Actions cron or an Azure VM, with Telegram/webhook failure alerts
- `Node.js` `Meta Graph API` `X API (OAuth 1.0a)` `Cloudflare R2` `GitHub Actions` `Docker`

**WhatsApp RAG Service**: a WhatsApp assistant that answers from your own content
- Crawls a website into markdown, embeds it locally (fastembed) into pgvector and answers over the WhatsApp Cloud API with Groq
- Admin panel for live chats, AI-to-human handoff, source toggles, prompt management and a retrieval tester
- `FastAPI` `PostgreSQL/pgvector` `fastembed` `Groq` `WhatsApp Cloud API`

### Enterprise work at Celebal Technologies

| Project | What it does | Stack |
|---|---|---|
| **Enterprise Banking RAG Chatbot** | Production chatbot for a major Indian bank that answers from 700+ enterprise PDFs and handles 4,000+ queries a day | Azure OpenAI, Document Intelligence, AI Search, Blob Storage, Redis |
| **PDF → SAP Contract Automation** | Parses contract PDFs, structures them with Agent Bricks, applies business logic and generates SAP-ready payloads, cutting manual data entry | Databricks AI Parser, Agent Bricks, PySpark, Delta Lake, SAP |
| **Agentic AI with Vision** | VLM agents that analyse industrial images, detect anomalies and send automatic alerts | Azure OpenAI, AWS Bedrock, Semantic Kernel, LangGraph |
| **NL → SQL Analytics Agent** | Multi-agent pipeline covering intent extraction, schema-aware SQL, validation, execution and a natural-language summary, with guardrails and SQL auto-correction | Semantic Kernel, Azure OpenAI, Azure SQL |

---

## 🛠️ Tech stack

**Languages & ML:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**GenAI & Agents:**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Semantic Kernel](https://img.shields.io/badge/Semantic%20Kernel-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![OpenAI Agents SDK](https://img.shields.io/badge/OpenAI%20Agents%20SDK-412991?style=flat-square&logo=openai&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)

**Cloud & Data:**
![Azure](https://img.shields.io/badge/Azure%20AI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=flat-square&logo=openai&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

**Backend & Databases:**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)

**DevOps:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🏅 Certifications

- Claude Certified Architect: Professional (2026)
- Claude Certified Architect: Foundations (2026)
- Claude Certified Associate (2026)
- Databricks Machine Learning Engineer Professional (2025)
- Databricks Machine Learning Engineer Associate (2025)
- Databricks Generative AI Engineer Associate (2024)

## 🎓 Education

**B.Tech, Computer Science & Engineering (AI & ML specialization)**, JIET, Jodhpur (2024)

---

<details>
<summary>🎨 Earlier work: 3D web & ML experiments</summary>

Before moving into GenAI I built interactive 3D websites with Three.js and React, plus some early ML projects: [portfolio](https://shaileshp1802.github.io/portfolio/), [3D product configurator](https://github.com/shaileshp1802/configurator), [FaceGAN](https://github.com/shaileshp1802/FaceGAN) and [drug name detection with Detectron2](https://github.com/shaileshp1802/drug_name_detection_detectron2).
</details>
