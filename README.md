<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=00D9FF&center=true&vCenter=true&width=650&lines=Hi+%F0%9F%91%8B%2C+I'm+Sonu+Kumar;AI+%2F+ML+Engineer+%7C+GenAI+Builder;RAG+%C2%B7+LLMs+%C2%B7+Multi-Agent+AI+%C2%B7+MLOps;7+AI+Systems+Built+%E2%86%92+6+Deployed+Live)

<p>
  <a href="https://linkedin.com/in/sonu-kumar-ai/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:sonukumar848213@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://sonu-portfolio-omega.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-00D9FF?style=flat&logo=vercel&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/u/sonu_kumar_123/">
    <img src="https://img.shields.io/badge/LeetCode-200%2B%20Problems-FFA116?style=flat&logo=leetcode&logoColor=white"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=Sonu0701&color=00D9FF&style=flat&label=Profile+Views"/>
</p>

<img src="https://img.shields.io/badge/Open%20to%20Work-AI%2FML%20Engineer-brightgreen?style=for-the-badge&logo=briefcase&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/B.Tech%20CS-Graduated%202026-blue?style=for-the-badge&logo=graduation-cap&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/Based%20in-Pune%2C%20India-orange?style=for-the-badge&logo=googlemaps&logoColor=white"/>

</div>

---

## 👨‍💻 About Me

> AI Engineer who **ships, not just studies** — production-grade AI systems, not just notebooks.
> Every deployed project is **Dockerised, live, and built to be actually used**.

- 🎓 B.Tech Computer Science, Shivalik College of Engineering, Dehradun — Graduated 2026 (CGPA 7.8/10)
- 📍 Based in Pune, India — actively interviewing for AI/ML Engineer roles
- 🤖 Focused on **Multi-Agent AI · RAG Pipelines · LLM Orchestration (LangGraph/LangChain) · MLOps**
- 🚀 **7 AI/ML systems built · 6 deployed live** on Render
- 🏆 Top 3 academic rank campus-wide (2024) · OpenAI Academy AI Foundations certified
- 🧩 Solved **200+ DSA problems** on LeetCode
- 💼 Open to **AI/ML Engineer · MLOps · Generative AI** roles
- 📫 Reach me: **sonukumar848213@gmail.com**

---

## 🚀 Deployed & Live

### 🧠 [ResearchMind — Multi-Agent AI Research System](https://github.com/Sonu0701/multi-agent-ai-research-system)
> **[🌐 Live Demo](https://multi-agent-ai-research-system-zr25.onrender.com)**

A LangGraph `StateGraph` (not a linear chain) where a **Critic Agent scores every generated report 1–10** and automatically loops the Writer back for up to 2 refinement passes until quality threshold is met — fully checkpointed to SQLite and traced in LangSmith.

`Python` `LangGraph` `Mistral AI` `Tavily API` `BeautifulSoup4` `LangSmith` `Streamlit` `Docker` `Render`

**Highlights:**
- 🔁 Conditional-edge auto-refinement loop: `score < 7 → retry Writer with feedback`
- 📡 Full per-run observability — node latency, token usage, retry traces
- ⚡ Token-level streaming with live cursor in the UI

---

### 💬 [Dynamic RAG Chatbot](https://github.com/Sonu0701/dynamic-rag-chatbot)
> **[🌐 Live Demo](https://dynamic-rag-chatbot-tgpt.onrender.com)**

Upload any PDF and chat with it — with **verified vector deletion** (polls Pinecone until old vectors are fully purged before re-indexing), MMR retrieval for diverse context, and a hallucination guard that blocks off-topic questions before they reach the LLM.

`Python` `FastAPI` `LangChain` `Pinecone` `Mistral AI` `React.js` `Docker` `Render`

**Highlights:**
- 🛡️ Similarity-threshold hallucination guard (0.75 cutoff)
- ⚡ Auto model fallback chain on Mistral rate limits (nemo → 7b → small)
- 📚 Every answer cites exact source page number

---

### 📊 [Telco Customer Churn Prediction System](https://github.com/Sonu0701/Telco-Customer-Churn-Prediction-System)
> **[🌐 Live Demo](https://telco-customer-churn-prediction-system.onrender.com)**

End-to-end ML pipeline from raw data to live API — **MLflow experiment tracking, XGBoost (ROC-AUC 0.83), and a real-time Streamlit dashboard**, with a modular train/serve-consistent codebase.

`Python` `XGBoost` `Scikit-learn` `MLflow` `FastAPI` `Streamlit` `Docker` `Render`

**Highlights:**
- 🔬 Full pipeline: preprocessing → feature engineering → training → serving
- 📈 ROC-AUC 0.83 · Recall 0.83, tuned for business impact over raw accuracy
- 🧱 Layered architecture built for train/serve consistency

---

### 🕵️ [AI-Powered Transaction Fraud Detection System](https://github.com/Sonu0701/AI-Powered-Transaction-Fraud-Detection-System)
> **[🌐 Live Demo](https://fraud-detection-app-actu.onrender.com)**

Real-time fraud detection combining **XGBoost + Isolation Forest + a Graph Neural Network** in a weighted ensemble, with SHAP explainability on every decision. Trained on the real Kaggle Credit Card Fraud dataset (284,807 transactions, 492 real fraud cases), reaching **AUC-ROC 0.979** on XGBoost.

`Flask` `XGBoost` `PyTorch Geometric (GNN)` `SHAP` `SciPy` `Chart.js` `Docker` `Render`

**Highlights:**
- 🕸️ GNN detects fraud rings via transaction relationship graphs
- 📊 SHAP shows the top features driving each individual fraud score
- 🔄 Concept-drift detection (KS test + Mahalanobis distance) with weekly auto-retraining

---

### 🤖 [Agentic RAG Chatbot](https://github.com/Sonu0701/Agentic-RAG-Chatbot)
> **[🌐 Live Demo](https://agentic-rag-chatbot-cxi4.onrender.com)**

A chatbot that **decides which tool to use per question** — RAG over an uploaded PDF, live web search, a calculator, or a real-time stock price lookup — orchestrated as a LangGraph state graph with conditional tool routing, not a hardcoded if/else chain.

`Python` `LangGraph` `Mistral AI` `ChromaDB` `Streamlit` `Docker`

**Highlights:**
- 🧭 4-tool router: `rag_tool`, web search, calculator, live stock price
- 💾 Persistent multi-thread memory via LangGraph's SQLite checkpointer
- 🖥️ Live tool-execution status streamed into the chat UI

---

### 🎬 [AI Meeting Assistant](https://github.com/Sonu0701/ai-meeting-assistant)
> **[🌐 Live Demo](https://ai-meeting-assistant-2msw.onrender.com)**

Turns a meeting recording or YouTube link into a transcript, summary, action items, and a grounded RAG chatbot — with **dual-engine transcription** (local Whisper for English, Sarvam AI for Hindi-English code-switching).

`Python` `Streamlit` `LangChain` `ChromaDB` `Mistral AI` `Whisper` `Sarvam AI`

**Highlights:**
- 🔁 Vector store fully wiped and rebuilt per meeting — zero cross-meeting contamination
- ✅ Auto-extracts action items, decisions, sentiment, and formal minutes
- 📥 One-click branded PDF export

---

## 🧪 In Development

### ✈️ Multi-Agent Travel Planning System *(Work in Progress)*

A LangGraph multi-agent trip planner extended with a **Supervisor Agent, guardrails, and human-in-the-loop approval**, integrating live flight data (AviationStack MCP), weather (Weather MCP), and web search (Tavily) with PostgreSQL-backed memory.

`Python` `LangGraph` `MCP` `PostgreSQL` `Groq` `Tavily` `Streamlit`

**Highlights:**
- 🧑‍✈️ Supervisor Agent coordinates specialist sub-agents (flights, weather, search)
- 🛑 Guardrails + human-in-the-loop checkpoints before booking-style actions
- 🔌 Real MCP server integrations (AviationStack, Weather) — not just API wrappers

> 🚧 Currently in active development — not yet deployed.

---

## 🧠 Tech Stack

**AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**Generative AI & LLMs**

![Mistral](https://img.shields.io/badge/Mistral%20AI-FF6B35?style=flat&logo=openai&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat&logo=groq&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat&logo=pinecone&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat&logo=databricks&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=anthropic&logoColor=white)

**MLOps & Deployment**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

**Backend & Frontend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sonu0701&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sonu0701&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" height="160"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Sonu0701&theme=tokyonight&hide_border=true" height="160"/>
</div>

---

<div align="center">
  <i>"Build things that work in production, not just in notebooks."</i>
  <br><br>
  <b>⭐ Star my repos if you find them useful!</b>
</div>
