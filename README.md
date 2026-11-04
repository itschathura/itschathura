<!-- ═══════════════ HEADER ═══════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Chathura%20Dharmasiri&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%2FML%20%C2%B7%20Software%20Engineer%20Intern&descAlignY=58&descSize=18" alt="Header" />
</p>

<p align="center">
  <a href="https://github.com/itschathura">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=36BCF7&center=true&vCenter=true&width=640&lines=Building+reliable+AI+products+%F0%9F%A4%96;RAG+%C2%B7+LLM+Guardrails+%C2%B7+Evaluation+%F0%9F%9B%A1%EF%B8%8F;F1+Telemetry+%2B+Machine+Learning+%F0%9F%8F%8E%EF%B8%8F;Final-year+CS+Undergraduate+%40+University+of+Vavuniya+%F0%9F%8E%93" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://chathuradev.pages.dev"><img src="https://img.shields.io/badge/🌐_Portfolio-chathuradev.pages.dev-0A66C2?style=for-the-badge" /></a>
  <a href="https://linkedin.com/in/dharmasiri17"><img src="https://img.shields.io/badge/LinkedIn-dharmasiri17-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:itsmechathura@outlook.com"><img src="https://img.shields.io/badge/Email-Outlook-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" /></a>
</p>

---

## 👨‍💻 About Me

I'm a **final-year BSc (Hons) Computer Science undergraduate at the University of Vavuniya, Sri Lanka**, focused on AI/ML. I build and ship complete AI systems, from a **RAG document platform with source-grounded answers** to an **XGBoost model predicting F1 overtakes from 10M+ rows of telemetry**.

I care most about **reducing LLM hallucinations** through guardrails and evaluation, and I'm looking for an **AI/ML or software engineering internship** where I can build reliable AI products in a team.

| | |
|---|---|
| 🎓 **Studying** | BSc (Hons) Computer Science, University of Vavuniya (2023 – Present) |
| 🔭 **Currently building** | SmartShop AI and my final-year F1 research project |
| 🌱 **Learning** | LLMOps, agentic workflows, MCP, LLM evaluation |
| 📍 **Based in** | Wattegama, Kandy, Sri Lanka 🇱🇰 |
| 🏆 **Achievement** | 🥇 First Place, Code Sprint 2024 (IEEE, University of Vavuniya) |
| ⚡ **Fun fact** | A day on Venus is longer than a year on Venus |

---

## 🚀 Featured Projects

### 📄 DocuMind AI: RAG Document Intelligence Platform
> Upload multi-page PDFs and get grounded answers plus automated summaries, with every answer linked back to its source passage.

- 🔎 Ingestion pipeline with **PyMuPDF + OCR fallback**, sliding-window chunking (500 tokens, 10% overlap) and Gemini embeddings in **ChromaDB**
- 🧠 Fewer hallucinations via constrained context-grounding prompts and **source-snippet attribution**
- 🔐 Hardened API: **UUIDv4 IDs** (no IDOR), MIME/magic-byte validation, per-client storage isolation
- 🎨 Responsive UI with live Markdown rendering and dark/light mode, deployed on **Cloudflare Pages + Docker**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 🏎️ F1 Research: Battery SoC Inference & Overtake Prediction (2026 Power Unit Rules)
> Final-Year Research Project (CSH4216): a real-time telemetry platform that predicts overtake probability for the full 20-car grid.

- 📡 Live **F1 SignalR** timing ingestion with a low-latency pipeline on **ScyllaDB + AsyncIO** (lockless atomic state swaps)
- 🤖 **XGBoost** classifier trained on **10M+ rows** of telemetry, handling class imbalance with `scale_pos_weight` and **PR-AUC** across 10 features
- 🔋 Physics-based **battery State-of-Charge engine** aligned with FIA 2026 rules (350 kW MGU-K), simulating four energy-harvesting modes
- 📊 **10 Hz live dashboard** in React 19 + Tailwind with head-to-head battle gauges and energy-differential meters

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=flat-square) ![ScyllaDB](https://img.shields.io/badge/ScyllaDB-6CD5E7?style=flat-square&logo=scylladb&logoColor=black) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![React](https://img.shields.io/badge/React_19-20232a?style=flat-square&logo=react&logoColor=61DAFB) ![FastF1](https://img.shields.io/badge/FastF1-E10600?style=flat-square&logo=f1&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 🛒 SmartShop AI: Multimodal Shopping Agent *(in progress)*
> An end-to-end AI shopping assistant with real-time SSE streaming and image-based receipt/product search.

- 🛡️ **3-tier, zero-cost guardrail pipeline** (regex filters + structured Gemini classifier) that blocks off-topic and prompt-injection queries
- ✅ **PostgreSQL validation layer** (asyncpg) that checks the price and stock of every recommended product to prevent hallucinated items
- 🧩 Multi-turn **LangGraph** workflows that persist dietary preferences, order history and budget as agent memory
- 🔁 **CI/CD + evaluation** with GitHub Actions and Langfuse, benchmarking tool-calling accuracy on golden datasets

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### 🖥️ Xtreeme: MERN Computer Parts Shop
> Full-stack e-commerce app for browsing and selling computer parts.

- 🔌 RESTful API with **Express.js + Node.js** and full CRUD on products, backed by **MongoDB**
- 🗃️ Product schemas with category, price, description, image and stock; all endpoints tested with **Postman**

[![Repo](https://img.shields.io/badge/View_Repo-Xtreeme--E--commerce--site-181717?style=flat-square&logo=github)](https://github.com/itschathura/Xtreeme-E-commerce-site)

---

## 💻 Tech Stack

**🗣️ Languages**<br>
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white) ![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge)

**🤖 AI & LLMs**<br>
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge) ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

`RAG` · `Vector Embeddings` · `Semantic Search` · `Guardrails` · `LLM Evaluation` · `Prompt Engineering` · `Tool Calling` · `Workflow Automation`

**📈 ML & Data**<br>
![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=for-the-badge) ![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=plotly&logoColor=black) ![SciPy](https://img.shields.io/badge/SciPy-0C55A5?style=for-the-badge&logo=scipy&logoColor=white)

**🧱 Backend & Frontend**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express.js-404d59?style=for-the-badge&logo=express&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB) ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**🗄️ Databases**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge) ![ScyllaDB](https://img.shields.io/badge/ScyllaDB-6CD5E7?style=for-the-badge&logo=scylladb&logoColor=black)

**🛠️ Tools & DevOps**<br>
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare_Pages-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

---

## 🎓 Certifications

| 📜 Certification | 🏛️ Issuer | 📅 Date |
|---|---|---|
| CS50's Introduction to Artificial Intelligence with Python | Harvard University | Sep 2026 |
| MATLAB Onramp | MathWorks | Sep 2026 |
| AI Prompts Fundamentals | Coddy | Oct 2026 |
| Python Programming, Trainee Full Stack Developer | University of Moratuwa | May 2024 |

---

## 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=itschathura&show_icons=true&theme=tokyonight&hide_border=true&count_private=false" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=itschathura&theme=tokyonight&hide_border=true&layout=compact" />

<br/>

<img src="https://nirzak-streak-stats.vercel.app/?user=itschathura&theme=tokyonight&hide_border=true" />

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itschathura/itschathura/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/itschathura/itschathura/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/itschathura/itschathura/output/pacman-contribution-graph.svg">
</picture>

---

## ✒️ Artworks

<table>
  <tr>
    <td align="center">
      🦅🥷<br>
      <img src="https://github.com/ph3onix17/ph3onix17/assets/95189772/83bb9537-1815-4a24-bc12-1d0582d6fbb8" height="400px">
    </td>
    <td align="center">
      🩷🍃<br>
      <img src="https://github.com/ph3onix17/ph3onix17/assets/95189772/12515bb8-89af-41fd-a734-5c1e5e0d30b5" height="400px">
    </td>
    <td align="center">
      🪐🥀<br>
      <img src="https://github.com/ph3onix17/ph3onix17/assets/95189772/103b394d-7d8c-43b5-a977-d4cd5fd6725f" height="400px">
    </td>
  </tr>
</table>

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://linkedin.com/in/dharmasiri17"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white&style=for-the-badge" /></a>
  <a href="mailto:itsmechathura@outlook.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white&style=for-the-badge" /></a>
  <a href="https://x.com/dharmasiri1717"><img src="https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white&style=for-the-badge" /></a>
  <a href="https://facebook.com/dharmasiri1717"><img src="https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white&style=for-the-badge" /></a>
  <a href="https://instagram.com/ph3on1x17"><img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white&style=for-the-badge" /></a>
  <a href="https://twitch.tv/mrbola17"><img src="https://img.shields.io/badge/Twitch-%239146FF.svg?logo=Twitch&logoColor=white&style=for-the-badge" /></a>
  <a href="https://discord.gg/RUc5wvHq"><img src="https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white&style=for-the-badge" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" alt="Footer" />
</p>
