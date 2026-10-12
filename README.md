<div align="center">

<!-- Hero Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,45:0b1120,100:000000&height=170&section=header&text=GHANANIL%20SHIRPURKAR&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=KOANOIR%20%20%C2%B7%20%20AI%20%C3%97%20SYSTEMS%20%C3%97%20ENGINEERING&descSize=16&descAlignY=64&descAlign=50&animation=fadeIn" width="100%" alt="Ghananil Shirpurkar" />

<br>

<!-- Typing banner -->
<a href="https://github.com/GhananilShirpurkar">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2600&pause=800&color=38BDF8&center=true&vCenter=true&width=720&lines=I+build+systems+that+survive+outside+the+demo.;AI+is+the+interface.+Systems+are+the+problem.;Agents+%E2%86%92+State+%E2%86%92+Control+%E2%86%92+Recovery.;Edge+inference.+Deterministic+RAG.+Autonomous+systems." alt="Typing Banner" />
</a>

<br><br>

<p>
  <a href="https://portfolio-ghananil-shirpurkar.vercel.app/" target="_blank"><b>◈ Portfolio</b></a> ·
  <a href="https://github.com/GhananilShirpurkar"><b>⚡ GitHub</b></a> ·
  <a href="https://www.linkedin.com/in/ghananil-shirpurkar23" target="_blank"><b>🔗 LinkedIn</b></a> ·
  <a href="mailto:shirpurkarghananil@gmail.com"><b>📬 Contact</b></a>
</p>

<br>

[![AI / ML](https://img.shields.io/badge/CORE-AI%20%C3%97%20ML-0b0f19?style=for-the-badge&logo=openai&logoColor=38bdf8)](#-core-technology-stack)
[![Agentic Systems](https://img.shields.io/badge/SYSTEMS-AGENTIC%20GRAPHS-0b0f19?style=for-the-badge&logo=python&logoColor=38bdf8)](#-core-technology-stack)
[![Production RAG](https://img.shields.io/badge/RETRIEVAL-PRODUCTION%20RAG-0b0f19?style=for-the-badge&logo=databricks&logoColor=38bdf8)](#-core-technology-stack)
[![Edge AI](https://img.shields.io/badge/LATENCY-EDGE%20AI%20%3C20MS-0b0f19?style=for-the-badge&logo=tensorflow&logoColor=38bdf8)](#-core-technology-stack)

</div>

<br>

> ### I don't build AI demos.
>
> I build systems around unreliable models — with **deterministic control**, **explicit state**, and **failure modes that can actually be reasoned about**.

<br>

## ⚡ What I Build

<table width="100%">
  <tr>
    <td width="33.3%" align="center" valign="top">
      <br>
      <img src="https://img.shields.io/badge/CAPABILITY-AUTONOMOUS%20AGENTS-38bdf8?style=flat-square&logo=python&logoColor=black" alt="Agents" /><br><br>
      <b>AUTONOMOUS AGENTS</b><br><br>
      <sub>Multi-agent state machines, supervisor topologies, and cyclic control graphs with deterministic recovery.</sub><br><br>
      <code>LangGraph</code> · <code>CrewAI</code> · <code>Groq</code>
      <br><br>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br>
      <img src="https://img.shields.io/badge/CAPABILITY-PRODUCTION%20RAG-38bdf8?style=flat-square&logo=databricks&logoColor=black" alt="RAG" /><br><br>
      <b>PRODUCTION RAG</b><br><br>
      <sub>Multi-tenant knowledge engines with isolated vector namespaces, hybrid search, and live web fallback.</sub><br><br>
      <code>ChromaDB</code> · <code>MongoDB Vector</code> · <code>Gemini</code>
      <br><br>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br>
      <img src="https://img.shields.io/badge/CAPABILITY-EDGE%20AI%20%26%20SYSTEMS-38bdf8?style=flat-square&logo=cpu&logoColor=black" alt="Edge AI" /><br><br>
      <b>EDGE AI & SYSTEMS</b><br><br>
      <sub>On-chip INT8 quantized neural execution (&lt;20ms latency) and high-concurrency async streaming services.</sub><br><br>
      <code>TFLite INT8</code> · <code>FastAPI</code> · <code>Neon Postgres</code>
      <br><br>
    </td>
  </tr>
</table>

<br>

## 🚀 Selected Work

### `01 ///` [LEXIS](https://github.com/GhananilShirpurkar/Lexis) — Multi-Tenant Production RAG Knowledge Engine

<a href="https://github.com/GhananilShirpurkar/Lexis" target="_blank">
  <img src="https://opengraph.githubassets.com/1/GhananilShirpurkar/Lexis" width="100%" alt="Lexis Repository Preview" />
</a>

Enterprise documents · Isolated tenant namespaces · Sub-second token streaming.

[![Tenant Isolation](https://img.shields.io/badge/SIGNAL-TENANT%20ISOLATION-0b0f19?style=flat-square&logoColor=38bdf8)](https://github.com/GhananilShirpurkar/Lexis)
[![Adaptive Grounding](https://img.shields.io/badge/SIGNAL-ADAPTIVE%20GROUNDING-0b0f19?style=flat-square&logoColor=38bdf8)](https://github.com/GhananilShirpurkar/Lexis)
[![Async SSE Streaming](https://img.shields.io/badge/SIGNAL-ASYNC%20SSE%20STREAMING-0b0f19?style=flat-square&logoColor=38bdf8)](https://github.com/GhananilShirpurkar/Lexis)
[![Stack](https://img.shields.io/badge/STACK-FASTAPI%20%C2%B7%20REACT%20%C2%B7%20CHROMADB-38bdf8?style=flat-square&logoColor=black)](https://github.com/GhananilShirpurkar/Lexis)

- **Strict Vector Isolation** — Workspace-level collection partitioning in ChromaDB with Clerk JWT verification preventing cross-tenant data leaks.
- **Adaptive Live Fallback** — Real-time cosine similarity gating routes low-confidence queries directly to Tavily web search before prompt compilation.
- **Low TTFT Engine** — Asynchronous FastAPI backend delivering real-time streaming tokens via Groq Llama-3.

<br>

### `02 ///` [MEDISYNC](https://github.com/GhananilShirpurkar/Medisync) — Autonomous Pharmacy Multi-Agent Ecosystem

<a href="https://github.com/GhananilShirpurkar/Medisync" target="_blank">
  <img src="https://opengraph.githubassets.com/1/GhananilShirpurkar/Medisync" width="100%" alt="Medisync Repository Preview" />
</a>

Clinical workflow automation · Coordinated agent supervisor · Deterministic safety gates.

[![Supervisor Graph](https://img.shields.io/badge/SIGNAL-SUPERVISOR%20GRAPH-0b0f19?style=flat-square&logoColor=38bdf8)](https://github.com/GhananilShirpurkar/Medisync)
[![Clinical Safety Gates](https://img.shields.io/badge/SIGNAL-CLINICAL%20SAFETY%20GATES-0b0f19?style=flat-square&logoColor=38bdf8)](https://github.com/GhananilShirpurkar/Medisync)
[![Multimodal Ingestion](https://img.shields.io/badge/SIGNAL-MULTIMODAL%20INGESTION-0b0f19?style=flat-square&logoColor=38bdf8)](https://github.com/GhananilShirpurkar/Medisync)
[![Stack](https://img.shields.io/badge/STACK-LANGGRAPH%20%C2%B7%20PYTORCH%20%C2%B7%20WHISPER-38bdf8?style=flat-square&logoColor=black)](https://github.com/GhananilShirpurkar/Medisync)

- **Supervisor State Machine** — LangGraph coordination across 5 specialized worker agents with dynamic conditional state transitions.
- **Clinical Quarantine Gates** — Hardcoded contraindication verification automatically quarantines execution when hazardous drug combinations are detected.
- **Multimodal Clinical Ingestion** — Combines Whisper voice dictation transcription with EasyOCR handwriting recognition for physician notes.

<br>

### `03 ///` [SAFEGUARD-AI](https://github.com/GhananilShirpurkar/SafeGuard-AI) — Sub-20ms On-Device Scam Detection

<a href="https://github.com/GhananilShirpurkar/SafeGuard-AI" target="_blank">
  <img src="https://opengraph.githubassets.com/1/GhananilShirpurkar/SafeGuard-AI" width="100%" alt="SafeGuard-AI Repository Preview" />
</a>

Mobile threat classification · On-chip INT8 inference · Zero-telemetry privacy.

[![On-Chip TFLite](https://img.shields.io/badge/SIGNAL-ON--CHIP%20TFLITE-0b0f19?style=flat-square&logoColor=38bdf8)](https://github.com/GhananilShirpurkar/SafeGuard-AI)
[![INT8 Quantized](https://img.shields.io/badge/SIGNAL-INT8%20QUANTIZED-0b0f19?style=flat-square&logoColor=38bdf8)](https://github.com/GhananilShirpurkar/SafeGuard-AI)
[![<20ms Latency](https://img.shields.io/badge/SIGNAL-%3C20MS%20LATENCY-0b0f19?style=flat-square&logoColor=38bdf8)](https://github.com/GhananilShirpurkar/SafeGuard-AI)
[![Stack](https://img.shields.io/badge/STACK-ANDROID%20%C2%B7%20TFLITE%20%C2%B7%20GEMINI-38bdf8?style=flat-square&logoColor=black)](https://github.com/GhananilShirpurkar/SafeGuard-AI)

- **Sub-20ms Edge Execution** — Distilled neural classifiers converted to INT8 post-training quantized TFLite tensors running locally on-chip.
- **Zero Telemetry** — SMS, phishing, and call classification operates 100% offline without external server dependencies.
- **Hybrid Cloud Escalation** — Selectively wakes the Gemini API only when edge confidence scores flag nuanced multi-turn fraud patterns.

<br>

<details>
<summary><b>◈ Other Repositories & Experiments</b></summary>
<br>

| Project | Description | Stack |
| :--- | :--- | :--- |
| [Miru](https://github.com/GhananilShirpurkar/Miru) | High-throughput anime discovery engine with debounced REST caching & zero layout shift · [Live Demo ↗](https://miru-anitrack.vercel.app) | `React` `Vite` |
| [CommitGuard](https://github.com/GhananilShirpurkar/CommitGuard) | Automated PR evaluation & merge gate infrastructure for GitHub Actions | `Python` `CI/CD` |
| [IssueHawk](https://github.com/GhananilShirpurkar/IssueHawk) | Intelligent issue triage and automated repository management pipeline | `NLP` `GitHub API` |
| [Recall](https://github.com/GhananilShirpurkar/Recall) | Persistent vector context cache and memory indexing utility for conversational agents | `Vector Search` `FastAPI` |
| [Cipher-Watch](https://github.com/GhananilShirpurkar/Cipher-Watch) | Cryptographic monitor and data pipeline integrity verification suite | `Security` `Python` |

</details>

<br>

## 🧬 Core Technology Stack

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4><code>01 // LANGUAGES</code></h4>
      <img src="https://skillicons.dev/icons?i=python,c,cpp,java,kotlin,js,ts,bash,html,css&theme=dark" alt="Languages" />
      <br><br>
      <b>Primary:</b> <code>Python 3.11+</code> · <code>C / C++</code> · <code>TypeScript</code><br>
      <b>Also:</b> <code>Kotlin</code> · <code>Java</code> · <code>JavaScript (ES6+)</code> · <code>SQL</code> · <code>Bash</code>
    </td>
    <td width="50%" valign="top">
      <h4><code>02 // AI & MACHINE LEARNING</code></h4>
      <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,scikitlearn&theme=dark" alt="ML Frameworks" />
      <br><br>
      <b>Frameworks & Models:</b> <code>PyTorch</code> · <code>TFLite</code> · <code>scikit-learn</code> · <code>Whisper</code> · <code>EasyOCR</code><br>
      <b>Inference & Quantization:</b> <code>INT8 PTQ</code> · <code>Model Distillation</code> · <code>Groq LPU (Llama-3)</code> · <code>Gemini API</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <br>
      <h4><code>03 // AGENTIC SYSTEMS (SPECIALIZATION)</code></h4>
      <img src="https://img.shields.io/badge/LangGraph-38bdf8?style=flat-square&logo=python&logoColor=black" alt="LangGraph" />
      <img src="https://img.shields.io/badge/LangChain-38bdf8?style=flat-square&logo=python&logoColor=black" alt="LangChain" />
      <img src="https://img.shields.io/badge/CrewAI-38bdf8?style=flat-square&logo=python&logoColor=black" alt="CrewAI" />
      <br><br>
      • <code>Supervisor-Worker State Graphs</code><br>
      • <code>Cyclic State Machines & Conditional Routing</code><br>
      • <code>Deterministic Clinical / Operational Quarantine Gates</code><br>
      • <code>Structured Pydantic Output Schemas</code><br>
      • <code>Isolated Node-Level State & Retry Logic</code>
    </td>
    <td width="50%" valign="top">
      <br>
      <h4><code>04 // RAG & VECTOR RETRIEVAL</code></h4>
      <img src="https://img.shields.io/badge/ChromaDB-38bdf8?style=flat-square&logo=databricks&logoColor=black" alt="ChromaDB" />
      <img src="https://img.shields.io/badge/MongoDB%20Atlas-38bdf8?style=flat-square&logo=mongodb&logoColor=black" alt="MongoDB" />
      <img src="https://img.shields.io/badge/Neon%20Postgres-38bdf8?style=flat-square&logo=postgresql&logoColor=black" alt="Neon" />
      <br><br>
      • <code>Strict Per-Tenant Namespace Isolation</code><br>
      • <code>Cosine Distance Gating (Similarity Thresholding)</code><br>
      • <code>Dense Semantic Embeddings (Gemini SDK)</code><br>
      • <code>Dynamic Live Web Fallback (Tavily Search API)</code><br>
      • <code>SQLAlchemy ORM & Alembic Migrations</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <br>
      <h4><code>05 // BACKEND & ASYNC SYSTEMS</code></h4>
      <img src="https://skillicons.dev/icons?i=fastapi,postgres,mongodb&theme=dark" alt="Backend" />
      <br><br>
      <b>Runtimes & Architecture:</b> <code>FastAPI Async</code> · <code>Pydantic</code> · <code>REST</code> · <code>Uvicorn</code><br>
      <b>Streaming & Security:</b> <code>SSE</code> · <code>Low TTFT Streaming</code> · <code>Clerk JWT Guards</code> · <code>Session Isolation</code>
    </td>
    <td width="50%" valign="top">
      <br>
      <h4><code>06 // FRONTEND & MOBILE</code></h4>
      <img src="https://skillicons.dev/icons?i=react,vite,ts,tailwind,androidstudio&theme=dark" alt="Frontend & Mobile" />
      <br><br>
      <b>Web:</b> <code>React 18</code> · <code>Vite</code> · <code>TypeScript</code> · <code>Tailwind CSS</code><br>
      <b>Mobile:</b> <code>Android Studio</code> · <code>Kotlin</code> · <code>Java</code> · <code>On-Device TFLite Runtime</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <br>
      <h4><code>07 // INFRASTRUCTURE & DEVOPS</code></h4>
      <img src="https://skillicons.dev/icons?i=docker,linux,git,githubactions,vercel&theme=dark" alt="DevOps" />
      <br><br>
      <b>Platforms:</b> <code>Docker</code> · <code>Linux (Ubuntu/Debian)</code> · <code>Bash Scripting</code> · <code>Vercel Edge</code><br>
      <b>CI/CD & Testing:</b> <code>GitHub Actions</code> · <code>Automated PR Merge Gates</code> · <code>Postman</code>
    </td>
    <td width="50%" valign="top">
      <br>
      <h4><code>08 // CAPABILITY HIERARCHY</code></h4>
      <br>
      <b>PRIMARY FOCUS:</b> <code>Python</code> · <code>FastAPI</code> · <code>LangGraph</code> · <code>PyTorch</code> · <code>ChromaDB</code> · <code>React</code> · <code>Docker</code> · <code>Linux</code><br><br>
      <b>SECONDARY STACK:</b> <code>CrewAI</code> · <code>MongoDB</code> · <code>TFLite INT8</code> · <code>scikit-learn</code> · <code>TypeScript</code> · <code>Vite</code> · <code>Kotlin</code><br><br>
      <b>SPECIALIZED TOOLING:</b> <code>Whisper</code> · <code>EasyOCR</code> · <code>Groq LPU</code> · <code>Gemini API</code> · <code>Tavily</code> · <code>Clerk</code>
    </td>
  </tr>
</table>

<br>

## 📈 Engineering Signals

<table width="100%">
  <tr>
    <td width="25%" align="center">
      <h2><code>&lt;20ms</code></h2>
      <b>EDGE LATENCY</b><br>
      <sub>INT8 Quantized On-Device</sub>
    </td>
    <td width="25%" align="center">
      <h2><code>5+</code></h2>
      <b>SUPERVISOR AGENTS</b><br>
      <sub>LangGraph Coordinated Graph</sub>
    </td>
    <td width="25%" align="center">
      <h2><code>0</code></h2>
      <b>TENANT LEAKS</b><br>
      <sub>Partitioned ChromaDB Tenancy</sub>
    </td>
    <td width="25%" align="center">
      <h2><code>&lt;1s</code></h2>
      <b>TIME TO FIRST TOKEN</b><br>
      <sub>Groq Llama-3 Async SSE</sub>
    </td>
  </tr>
</table>

<br>

## 📊 GitHub Telemetry

<div align="center">
  <img src="https://raw.githubusercontent.com/GhananilShirpurkar/GhananilShirpurkar/output/github-snake-dark.svg" width="100%" alt="Contribution Snake" />
</div>

<br>

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="https://github-stats-alpha.vercel.app/api?username=GhananilShirpurkar&cc=38bdf8&tc=e2e8f0&ic=38bdf8&bc=0b0f19" width="100%" alt="GitHub Stats" />
    </td>
    <td width="50%" align="center">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=GhananilShirpurkar&theme=github_dark" width="100%" alt="Language Breakdown" />
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="https://streak-stats.demolab.com?user=GhananilShirpurkar&theme=dark&hide_border=true&background=0b0f19&ring=38bdf8&fire=38bdf8&currStreakLabel=38bdf8&sideLabels=94a3b8&dates=64748b&sideNums=e2e8f0&currStreakNum=ffffff" width="100%" alt="Streak Stats" />
    </td>
    <td width="50%" align="center">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=GhananilShirpurkar&theme=github_dark" width="100%" alt="Activity Summary" />
    </td>
  </tr>
</table>

<br>

## ◈ Currently

- 🛠️ **Engineering** — Autonomous multi-agent graphs and deterministic clinical supervisor loops.
- 🔬 **Research** — Edge model distillation and low-latency INT8 inference on consumer silicon.
- 🎓 **Academic** — Pre-final year B.Tech in Information Technology ('28) at SGGSIE&T.
- ✅ **Certifications** — MongoDB Vector Search & RAG Certified · Oracle AI Foundations Associate.

<br>

## 📬 Connect

<div align="center">

*Open for AI/ML engineering roles, early-stage systems architecture, and research collaborations.*

<br>

[![Email](https://img.shields.io/badge/EMAIL-shirpurkarghananil%40gmail.com-0B0F19?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:shirpurkarghananil@gmail.com)
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-Visit%20Site-0B0F19?style=for-the-badge&logo=vercel&logoColor=38BDF8)](https://portfolio-ghananil-shirpurkar.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-ghananil--shirpurkar23-0B0F19?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/ghananil-shirpurkar23)
[![GitHub](https://img.shields.io/badge/GITHUB-GhananilShirpurkar-0B0F19?style=for-the-badge&logo=github&logoColor=FFFFFF)](https://github.com/GhananilShirpurkar)

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,50:38bdf8,100:000000&height=4&section=footer" width="100%" alt="" />

<br>

<sub><code>SYSTEMS OVER DEMOS • RESILIENT BY DESIGN • 2026</code></sub>

</div>
