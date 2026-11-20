<h1 align="center">Mohamed Ahmed Negm</h1>
<h3 align="center">AI Engineer · LLM Agents · Voice AI · Retrieval</h3>
<p align="center">
  <a href="https://negmeme2001.github.io">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/mohamed-ahmed-negm/">LinkedIn</a> ·
  <a href="mailto:mohamedahmednegm811@gmail.com">Email</a>
</p>

---

I build production LLM systems: tool-using agents, voice assistants and retrieval, with evaluation, authorization and cost tracking built in from the start.

- **Now:** AI Engineer at **ProCrew (PeakTime)**, where I own Peak Assistant, the AI agent B2B customers use inside PeakTime. Part-time AI Engineer at **LamasaTech**, a UK self-service kiosk company, on Ravo AI, its voice-first AI concierge.
- **Peak Assistant:** 15 tools with confirmation-gated write actions, role-based authorization across 24 intents, and an 85-case eval suite run weekly in CI (**93–97% routing**, **87–92% tool execution** on gpt-5-mini).
- **Open to:** AI Engineer roles, remote or relocation to the Gulf.

> Most of my production work lives in private repos. The projects below are public.

---

## Featured projects

### Ravo X-Ray: a voice assistant that shows where its time goes
*Retail assistant in Arabic and English, typed and spoken, where every answer carries a latency trace.*

- Traces showed pgvector search costs **3–6 ms** while **~90%** of answer time is the LLM.
- A Redis query-embedding cache cut embedding time from **~160 ms to ~3 ms**.
- A labelled eval scores retrieval at **81% top-1 / 84% top-5** and keeps known weak spots (negation, near-duplicates) on the scoreboard.
- A LiveKit voice agent with a speech-to-text bake-off, turn handling that waits through thinking pauses, and a fallback voice.

**Stack:** FastAPI · LiveKit Agents · PostgreSQL + pgvector (HNSW) · Redis · Deepgram · Cartesia · Vercel · Neon  
**Repo:** [ravo-xray](https://github.com/negmeme2001/ravo-xray) · **Demo:** [ravo-xray.vercel.app](https://ravo-xray.vercel.app) (access code on request)

### CoverPilot: an insurance assistant with grounded citations
*A LangGraph agent that answers policy questions with citations, looks up claims and files new ones.*

- Pipeline: injection guard → retrieval → agent ↔ tools, streamed over SSE.
- Citations come from the retriever, never from the model's text. A relevance floor makes out-of-scope questions answer "not covered".
- 94 tests, Docker Compose, and a zero-cost mode on Groq with local embeddings.

**Stack:** LangGraph · FastAPI · FAISS · Streamlit · Pydantic · Docker  
**Repo:** [coverpilot](https://github.com/negmeme2001/coverpilot)

### Peak Assistant Exporter: LLM cost and latency in Prometheus
A Python exporter that turns the assistant's MongoDB usage logs into Prometheus metrics (requests, latency, per-model cost, tokens, tool calls), with a Grafana dashboard included.

**Stack:** Python · MongoDB · Prometheus · Grafana · Docker  
**Repo:** [peak-assistant-exporter](https://github.com/negmeme2001/peak-assistant-exporter)

### Fantasy24Club: FPL predictions for 5,700 users (private)
I'm the sole engineer. A FastAPI service serves AIrsenal Bayesian models for player-point predictions and transfer suggestions, alongside a GPT-4o assistant with real-time web search and English/Arabic intent routing.

**Stack:** FastAPI · AIrsenal · Celery · Redis · GPT-4o · Tavily

---

## Tech stack

- **LLMs & agents:** OpenAI Agents SDK · LangGraph · MCP · tool calling · structured outputs (Zod, Pydantic) · prompt-injection defense
- **Retrieval:** pgvector (HNSW) · FAISS · embedding caches · retrieval evals
- **Voice:** LiveKit Agents · Deepgram · Cartesia · turn detection · Arabic/English
- **Evals & observability:** golden-set evals · LLM-as-judge · evals in CI · Prometheus · Grafana
- **Backend & frontend:** Python · TypeScript · FastAPI · NestJS · Celery · BullMQ · Next.js · Vue 3
- **Data & cloud:** PostgreSQL · MongoDB · Redis · Docker · GitHub Actions · Vercel · AWS

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=negmeme2001&theme=react-dark&hide_border=true&area=true" width="100%"/>
</p>
