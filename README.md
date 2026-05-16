<h1 align="center">👋 Mohamed Ahmed Negm</h1>
<h3 align="center">AI/ML Engineer — LLM Agents · Evaluation · Observability</h3>

---

### 🧠 About Me

AI/ML Engineer with 2+ years of experience shipping production LLM systems end-to-end. Currently at **ProCrew (PeakTime)** building agents, multi-turn evaluation harnesses, and the Prometheus/Grafana observability layer that proves they work.

Day-to-day stack: Python · TypeScript · NestJS · FastAPI · MongoDB · Redis · PostgreSQL · OpenAI Agents SDK · PyTorch · Prometheus · Grafana.

Latest production agent: **96.3% routing / 95.1% execution / 80% multi-turn accuracy** across 54 + 5 cases, with per-release trend tracking.

> Most production work lives in private repos. Architecture write-ups on LinkedIn & dev.to.

---

## 🚀 Featured Projects

### 📊 Peak Assistant Exporter — Prometheus Exporter for LLM Cost & Latency

*MLOps · Observability · Custom Prometheus Exporter*

Production Python exporter pulling LLM usage metrics from MongoDB and exposing them as Prometheus gauges — request volume, latency, per-model cost (USD), token usage (prompt/completion), and per-tool call counts. Background thread caches aggregations every 15s so scrapes are non-blocking. Includes a pre-built Grafana dashboard JSON.

- 🚀 **Real-time metrics:** API usage, latency, cost, tokens, tool calls
- ⚙️ **Non-blocking design:** background aggregation thread, 15s cache
- 🐳 **Production-ready:** Dockerized, robust error handling, structured logging
- 📊 **Grafana-ready:** dashboard JSON included

**Tech Stack:** Python · MongoDB · Prometheus · Grafana · Docker · UV
**Repo:** [peak-assistant-exporter](https://github.com/negmeme2001/peak-assistant-exporter)

---

### 🧩 Peak-Time AI — Jira Summary Demo
*LLM · Streamlit · Jira API · Productivity Tooling*

Streamlit demo that pulls Jira Software issues (by project search or board feed) and passes the curated payload to an LLM for human-readable weekly summaries. Useful for productivity overviews tied to a board, date range, or assignee.

**Tech Stack:** Streamlit · Jira REST API · OpenRouter/OpenAI · UV
**Repo:** [Peak-Time-AI---Jira-Summary-Demo](https://github.com/negmeme2001/Peak-Time-AI---Jira-Summary-Demo)

---

### ⚽ Fantasy24Club — Retrieval-Augmented FPL Assistant
<img src="https://github.com/negmeme2001/negmeme2001/blob/main/assets/Fantasy24club.png?raw=true" width="90" align="left" />
<br clear="left"/>

*Production ML · Retrieval-Augmented LLM · Bilingual (EN/AR)*

Large-scale AI service for Fantasy Premier League. Deploys AIrsenal ML models behind FastAPI for player point prediction and transfer suggestions. Adds a **retrieval-augmented LLM assistant** on GPT-4o with real-time web search (Tavily) scoped to current gameweek fixtures and squad context. Includes a bilingual (English + Arabic) intent classifier across fact / why / opinion / squad / news.

- 🎯 **ML prediction:** AIrsenal models behind FastAPI
- 🌐 **Web-search RAG:** GPT-4o + Tavily for live grounding
- 🗣️ **Bilingual:** Arabic + English intent routing
- ⚡ **40% latency reduction** via Celery async pipelines

**Tech Stack:** FastAPI · AIrsenal · Celery · Redis · GPT-4o · Tavily · Node.js · Docker
> *Repo is private (ProCrew product). Description above reflects shipped architecture.*

---

### 🎓 Student Performance Predictor
<img src="https://github.com/negmeme2001/negmeme2001/blob/main/assets/Student_Performance.png?raw=true" width="90" align="left" />
<br clear="left"/>

*Supervised ML · Education Analytics*

Predicts students' final grades from socio-academic data using regression models on the UCI Student Dataset. EDA, feature importance, model evaluation (R² up to 0.82).

**Tech Stack:** Python · Scikit-learn · XGBoost · Pandas · Matplotlib
**Repo:** [student-performance-predictor](https://github.com/negmeme2001/student-performance-predictor)

---

### 🧠 Topic Modeling — AWS NLP Project
<img src="https://github.com/negmeme2001/negmeme2001/blob/main/assets/Topic_Modeling_Aws.png?raw=true" width="90" align="left" />
<br clear="left"/>

*Unsupervised ML · NLP · AWS*

Topic modeling using Latent Dirichlet Allocation (LDA) on the CMU Movie Summary Corpus. Preprocessing, feature extraction, visualization. Deployed on AWS.

**Tech Stack:** Python · Scikit-learn · NLTK · AWS · Matplotlib · Seaborn
**Repo:** [Topic-Modeling--AWS](https://github.com/negmeme2001/Topic-Modeling--AWS)

---

### 🖼️ Imagen App — Generative AI Image Tool
<img src="https://github.com/negmeme2001/negmeme2001/blob/main/assets/Imagenapp.png?raw=true" width="90" align="left" />
<br clear="left"/>

*Generative AI · Gemini API · Streamlit*

Streamlit app that generates and edits images using Google Gemini. Iterative editing with a mini-gallery of generated images.

**Tech Stack:** Streamlit · Google Gemini API · Pillow · UV
**Repo:** [Imagen-app](https://github.com/negmeme2001/Imagen-app)

---

### 🧮 Text Classification using PySpark
<img src="https://github.com/negmeme2001/negmeme2001/blob/main/assets/Text_Classification.png?raw=true" width="90" align="left" />
<br clear="left"/>

*Big Data NLP · Spark ML Pipeline*

PySpark ML project classifying disaster tweets. Scalable text preprocessing and classification using Spark DataFrames and MLlib.

**Tech Stack:** PySpark · NLP · Pandas · Python
**Repo:** [Textclassification-pyspark](https://github.com/negmeme2001/Textclassification-pyspark)

---

## 🧰 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tavily-0A66C2?style=for-the-badge&logo=duckduckgo&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

---

## 📈 Contributions Graph
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=negmeme2001&theme=react-dark&hide_border=true&area=true" width="100%"/>
</p>

---

### 🌐 Contact
- 📧 **Email:** [mohamedahmednegm811@gmail.com](mailto:mohamedahmednegm811@gmail.com)
- 🔗 **LinkedIn:** [linkedin.com/in/mohamed-ahmed-negm](https://www.linkedin.com/in/mohamed-ahmed-negm/)
- 💻 **GitHub:** [github.com/negmeme2001](https://github.com/negmeme2001)

---

<h3 align="center">✨ Let's Build Smarter AI Together</h3>
<p align="center"><i>"From notebook experiments to production LLM systems with eval harnesses and dashboards that prove they work."</i></p>
