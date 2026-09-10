<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=260&color=0:0F2027,50:2C5364,100:8E2DE2&text=Arun%20Addagatla&fontAlignY=40&fontSize=52&desc=Founding%20AI%20Engineer%20%40%20Lamatic.ai%20·%20Agent%20Runtimes%20·%20Production%20LLM%20Ops&descAlignY=60&descSize=16&fontColor=ffffff" alt="banner" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3200&pause=900&color=8E2DE2&center=true&vCenter=true&width=920&lines=Infrastructure+for+durable+agents%2C+not+demos;Serverless+executors+at+1M%2B+runs+per+month;Multi-agent+harnesses+with+evals+%26+LLM-as-a-judge;From+MLOps+to+Agentic+AI+in+production)](https://git.io/typing-svg)

<a href="https://arunaddagatla.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-8E2DE2?style=flat-square&logo=vercel&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/arun-addagatla"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://arunaddagatla.medium.com/"><img src="https://img.shields.io/badge/Medium-12100E?style=flat-square&logo=medium&logoColor=white" /></a>
<a href="mailto:arun.a.addagatla@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/arun2728"><img src="https://komarev.com/ghpvc/?username=arun2728&style=flat-square&color=8E2DE2&label=Profile+Views" /></a>

</div>

---

## `~/whoami`

```ts
const arun = {
  role: "Founding AI Engineer @ Lamatic.ai",
  focus: ["agent runtimes", "multi-agent orchestration", "production LLM ops"],
  building: "infrastructure for durable autonomous systems — not slide-deck demos",
  firstHire: true,          // shipped 80%+ of the core platform
  stack: ["Python", "TypeScript", "Go", "Cloudflare Workers", "Kubernetes"],
  caresAbout: ["durability", "distributed execution", "eval", "what breaks after the millionth run"],
};
```

I'm **Arun Addagatla**, an AI systems engineer who builds the runtime glue that keeps agents alive past a single HTTP request — serverless execution, multi-agent orchestration, memory/RAG layers, and eval. As the first engineering hire at **[Lamatic.ai](https://lamatic.ai)** (TechCrunch Startup Battlefield 200 · Cloudflare Workers Launchpad), I've shipped over **80%** of the platform.

---

## 🛠️ Flow-Gen Agent Harness — _the thing I'm proudest of_

A **multi-agent harness** that turns a plain-English request into a validated, deployable Lamatic workflow. I first built a reusable multi-agent node primitive, then **dogfooded it** to build the harness itself.

```mermaid
flowchart LR
    P[🧭 Planner] --> A[🏗️ Architect]
    A --> W[🧵 Weaver]
    W <--> I[🔍 Inspector]
    I --> F[🧩 Filler]
    F <--> Au[🛡️ Auditor]
    Au --> V[✅ Validator]
    V --> O[(Deployable Flow)]
```

| Agent | Role |
|-------|------|
| **Planner** | Resolves intent · RAG over sample flows · single vs. multi-workflow |
| **Architect** | Selects nodes from the catalog |
| **Weaver ⇄ Inspector** | Builds skeleton/edges · edge dry-run with feedback loop |
| **Filler ⇄ Auditor** | Fills node config from schema · executes node + credential check with feedback loop |
| **Validator** | Final end-to-end retest → hands the user a working flow |

**Two-tier verification:** deterministic checks where ground truth exists; a rubric **LLM-as-a-judge** only for fuzzy output quality — and the judge *never* overrides a hard check.

---

## 🚀 Featured Work

### 🧩 [Content OS](https://github.com/arun2728/content-os) &nbsp;·&nbsp; _in development_
AI content-orchestration monorepo guiding the full pipeline — **clarify → outline → write → edit → publish** — with autonomous agents owning each stage.

### 🔌 [Dev.to MCP Server](https://github.com/arun2728/dev-to-mcp) &nbsp;·&nbsp; _live_
An MCP server exposing **35+ tools** over the Dev.to (Forem) API. Lets Claude & Cursor draft, edit, publish, and manage content. Supports **stdio · Streamable HTTP · Cloudflare Workers** transports, with a multi-arch Docker image on GHCR.

### 🤖 [jobapply](https://github.com/arun2728/jobapply) &nbsp;·&nbsp; _open source_
Local CLI that searches jobs, dedupes across runs, and drafts structured resumes + cover letters from your base profile using **LangGraph** agents — with checkpointing, optional PDF export, and pluggable models (Gemini, Anthropic, OpenAI, Ollama).

### 🧪 [LLMQuests](https://github.com/arun2728/LLMQuests) &nbsp;·&nbsp; _open source_
Hands-on collection of LLM & agent experiments — implementations and deep-dives that back my writing on memory, RAG, MCP, and multi-agent systems.

### 🎙️ Multilingual Indian Voicebot &nbsp;·&nbsp; _freelance_
End-to-end voice assistant across **10+ Indian languages**. Conformer S2T on Triton, Fastpitch TTS, and a LangChain RAG pipeline with embedding + reranker models.

---

## 💼 Experience

**`Lamatic.ai` — Founding Engineer, AI** · _Mar 2024 – Present · Miami, FL (remote)_
- Built **80%+** of the core stack as the first engineering hire — AI systems, backend, infra, and critical frontend.
- Architected a serverless **executor** at **1M+ monthly runs** and a deployment engine at **1K+ deploys/min**.
- Cut deployment latency **2 min → 15 s** (~**87%**).
- Built the **flow-gen multi-agent harness** and a configurable **LLM-as-a-judge** eval framework.
- Shipped an internal **hiring agent** (resume parsing + video analysis) cutting recruiter workload **70%**.
- Engineered secure VPC **Kubernetes ETL** for Drive/S3/SharePoint with OAuth, **Semantic RAG**, a **Multi-Agent Supervisor**, Slack/Teams webhooks, and a **native GitHub VCS** for flow sync.

**`Samespace` — SDE, AI/ML** · _Oct 2022 – Mar 2024 · Mumbai_
- Chat/voicebots handling **95%** of queries (embeddings, reranking, tuned Zephyr & GPT-4).
- Fine-tuned **Mistral / LLaMA-2** with LoRA/PEFT (+30% fluency); LLM inference engine at **106 tok/s**.
- Optimized **Whisper V3** with ONNX/TensorRT + Triton → **0.1–0.4s** latency; multimodal search (+60%).

**`Enterpret` — ML Intern, NLP** · _Sep 2021 – Aug 2022 · Bangalore_
- Serverless multilingual sentiment on AWS (−50% processing time); CI/CD; NER/classification (+30%); anomaly detection (−60% false positives).

**`Algoritmo Labs` — Data Science Intern** · _2020_ — ML model → ONNX → **Go** runtime for client-side deployment.

---

## 🧰 Toolbox

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Web & Backend**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**AI / LLM / ML**

![LangChain](https://img.shields.io/badge/LangChain%2FLangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![RAG](https://img.shields.io/badge/RAG-FF6B6B?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-9B59B6?style=flat-square)
![Agent Harness](https://img.shields.io/badge/Agent%20Harness-8E2DE2?style=flat-square)
![Evals](https://img.shields.io/badge/Evals%20%2F%20LLM--as--a--Judge-00B894?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=flat-square)
![LoRA/PEFT](https://img.shields.io/badge/LoRA%20%2F%20qLoRA%20%2F%20PEFT-6C3483?style=flat-square)

**Inference & Model Serving**

![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Triton](https://img.shields.io/badge/NVIDIA%20Triton-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper%20ASR-412991?style=flat-square&logo=openai&logoColor=white)

**Data & Vector Stores**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-00C9A7?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Airbyte](https://img.shields.io/badge/Airbyte-615EFF?style=flat-square&logo=airbyte&logoColor=white)

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS%20(Lambda%2FECR%2FS3)-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP%20(CloudRun%2FBigQuery%2FGCS%2FVPC)-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare%20(Workers%2FQueues%2FR2%2FDO)-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**Observability & CI/CD**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 🎤 Talks & ✍️ Writing

**Recent talks**
- **Why LLMs Need Memory** — Lamatic Community (Mar 2026) · [YouTube](https://www.youtube.com/watch?v=iwrBZWDOnSo)
- **Applications of AI** — Omkaranada Institute (Apr 2026) · live-shipped a web app in <8 min
- **Why Prompting Isn't Enough: The Case for RAG** — Lamatic Community (Jan 2026)
- **What is MCP & How It Works** — Daytona Developers Club Tour '25, Mumbai (May 2025)

**Recent writing** (70k+ reads across Medium · GoPenAI · Nerd For Tech · [Lamatic Labs](https://labs.lamatic.ai/authors/arun-addagatla))
- [Why LLMs Need Memory — Building AI Agents Hands-On](https://medium.com/@arunaddagatla/why-llms-need-memory-building-ai-agents-with-a-hands-on-implementation-849dbbf6fd0d) · Mar 2026
- [Inside NVIDIA Nemotron 3: Hybrid MoE for Multi-Agent AI](https://medium.com/gopenai/inside-nvidia-nemotron-3-hybrid-moe-models-built-for-multi-agent-ai-2aabcc056e93) · Dec 2025
- [Cut Token Costs by 60%: TOON vs JSON for AI Workflows](https://medium.com/@arunaddagatla/cut-token-costs-by-60-how-toon-outperforms-json-for-ai-workflows-cf67d038db2d) · Nov 2025
- [Lamatic — The Operating System for AI Agents](https://labs.lamatic.ai/p/lamatic-ai-the-operating-system-for-ai-agents)

---

## 🔭 Currently

Building reliable **GenAI + Agentic AI** for enterprise · durable **execution/inference** platforms · production **MLOps** · **RAG**, **MCP** integrations, and autonomous workflow automation.

---

<div align="center">

### 📊 GitHub

<img src="https://github-readme-stats-eight-theta.vercel.app/api?username=arun2728&show_icons=true&hide_border=true&bg_color=0D1117&title_color=8E2DE2&icon_color=22D3EE&text_color=C9D1D9&ring_color=8E2DE2" height="165" />
<img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=arun2728&layout=compact&hide_border=true&bg_color=0D1117&title_color=8E2DE2&text_color=C9D1D9" height="165" />

<br><br>

<img src="https://streak-stats.demolab.com/?user=arun2728&hide_border=true&background=0D1117&ring=8E2DE2&fire=C084FC&currStreakLabel=C9D1D9&sideLabels=C9D1D9&currStreakNum=22D3EE&sideNums=22D3EE&dates=6B7280" width="500" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=arun2728&bg_color=0d1117&color=c9d1d9&line=8E2DE2&point=22d3ee&area=true&area_color=c084fc&hide_border=true&custom_title=Contribution%20Graph" width="95%" />

</div>

---

<div align="center">

### ✨ _"Build useful AI. Ship it fast. Scale it responsibly."_ ✨

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=140&color=0:8E2DE2,50:2C5364,100:0F2027" alt="footer" />

</div>
