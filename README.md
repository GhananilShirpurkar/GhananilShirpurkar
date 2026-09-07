<div align="center">

<!-- Cinematic Header Title Card -->
<img src="https://capsule-render.vercel.app/api?type=slice&color=0:000000,50:090d16,100:000000&height=190&section=header&text=GHANANIL%20SHIRPURKAR&fontSize=46&fontColor=ffffff&fontAlignY=40&desc=KOANOIR%20%E2%80%A2%20AI%20%C3%97%20SYSTEMS%20%C3%97%20ENGINEERING&descSize=15&descAlignY=64&animation=fadeIn" width="100%" alt="Ghananil Shirpurkar Header" />

<br>

<!-- Live Monospace Terminal HUD -->
<a href="https://github.com/GhananilShirpurkar">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2800&pause=800&color=38BDF8&center=true&vCenter=true&width=740&lines=I+build+systems+that+survive+outside+the+demo.;AI+is+the+interface.+Systems+are+the+problem.;Autonomous+Multi-Agent+Graphs+%E2%80%A2+LangGraph;Deterministic+Multi-Tenant+RAG+%E2%80%A2+Zero+Hallucinations;Quantized+On-Device+Edge+Inference+%E2%80%A2+%3C20ms" alt="Terminal Typing" />
</a>

<br><br>

<!-- High-Contrast Navigation Links -->
<p align="center">
  <a href="https://portfolio-ghananil-shirpurkar.vercel.app/" target="_blank"><code>[ ◈ LIVE PORTFOLIO ↗ ]</code></a>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/ghananil-shirpurkar23" target="_blank"><code>[ ⚡ LINKEDIN ↗ ]</code></a>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <a href="mailto:shirpurkarghananil@gmail.com"><code>[ 📬 DIRECT DISPATCH ↗ ]</code></a>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <a href="https://leetcode.com/Ghananil_Shirpurkar" target="_blank"><code>[ 🧬 LEETCODE ↗ ]</code></a>
</p>

<br>

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  SYSTEM: ACTIVE RESEARCH & DEV       CORE: AUTONOMOUS AGENTS / RAG / EDGE   │
│  COORDINATES: NAGPUR, INDIA          ACADEMICS: B.TECH IT '28 [SGGSIE&T]    │
└─────────────────────────────────────────────────────────────────────────────┘
```

</div>

---

## 01 // THESIS

> ### **“Most AI software is a fragile wrapper waiting to break in production. I engineer the deterministic state machines, vector boundaries, and low-latency systems that make autonomous intelligence reliable.”**

```
┌── PRINCIPLES ──────────────────────────────────────────────────────────────┐
│                                                                            │
│  01. ARCHITECTURE > SYNTAX      Define contracts and state before code.    │
│  02. DETERMINISTIC CONTROL      Stochastic models require rigid supervisor │
│                                 state graphs. Never trust raw output.      │
│  03. ZERO DEMO-WARE             If it doesn't survive adversarial inputs,  │
│                                 tenant isolation, and network drops,       │
│                                 it doesn't ship.                           │
│  04. COMPUTE AT THE EDGE        Push inference to consumer silicon (<20ms) │
│                                 whenever cloud round-trips can be killed.  │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

---

## 02 // PROOF

<table width="100%">
  <tr>
    <td width="25%" align="center">
      <h3><code>&lt; 20ms</code></h3>
      <sub>On-Device Edge Latency<br><b>INT8 Quantized TFLite</b></sub>
    </td>
    <td width="25%" align="center">
      <h3><code>5+</code></h3>
      <sub>Coordinated Agents<br><b>LangGraph State Machine</b></sub>
    </td>
    <td width="25%" align="center">
      <h3><code>0.00%</code></h3>
      <sub>Cross-Tenant Leakage<br><b>Isolated Namespace RAG</b></sub>
    </td>
    <td width="25%" align="center">
      <h3><code>&lt; 1s</code></h3>
      <sub>Time-to-First-Token (TTFT)<br><b>Async SSE Streaming</b></sub>
    </td>
  </tr>
</table>

---

## 03 // SELECTED WORK

### ◈ 01 / LEXIS — Multi-Chat Production RAG Knowledge Engine
```
ARCHITECTURE: MULTI-TENANT ISOLATION · DYNAMIC COSINE GATING · REAL-TIME SSE STREAMING
STACK:        FASTAPI · REACT 18 · VITE · NEON POSTGRES · CHROMADB · GROQ (LLAMA-3) · CLERK
```

> **The Problem:** Enterprise RAG platforms leak documents across tenant workspaces and hallucinate when local document coverage drops.  
> **The Engineering:** Architected strict workspace-level collection partitioning in ChromaDB guarded by Clerk JWT session verification. Implemented dynamic cosine distance gating (`similarity < 0.72`): low-confidence queries automatically invoke a Tavily live web agent fallback before prompt compilation. Engineered an asynchronous FastAPI streaming engine delivering sub-second token generation via Groq Llama-3.

```
[ ↗ INSPECT REPOSITORY ] ──▶ https://github.com/GhananilShirpurkar/Lexis
```

<br>

### ◈ 02 / MEDISYNC — Autonomous Pharmacy Multi-Agent Ecosystem
```
ARCHITECTURE: SUPERVISOR-WORKER STATE GRAPH · HARDCODED CLINICAL QUARANTINE GATES
STACK:        LANGGRAPH · FASTAPI · PYTORCH · WHISPER · EASYOCR · GROQ
```

> **The Problem:** Healthcare automation cannot tolerate stochastic drift. A single missed drug contraindication or dosage miscalculation is lethal.  
> **The Engineering:** Designed a deterministic LangGraph supervisor topology orchestrating 5 specialized worker nodes (Prescription Parsing, Drug Contraindication, Dosage Calculation, Inventory Audit, Patient Dispatch). Hardcoded non-bypassable clinical verification gates that halt execution and quarantine dangerous drug interactions before generation. Integrated Whisper voice transcription with EasyOCR handwriting parsing models.

```
[ ↗ INSPECT REPOSITORY ] ──▶ https://github.com/GhananilShirpurkar/Medisync
```

<br>

### ◈ 03 / SAFEGUARD-AI — Sub-20ms On-Device Edge Scam Detection
```
ARCHITECTURE: ON-CHIP NEURAL INFERENCE · ZERO-TELEMETRY PRIVACY · HYBRID CLOUD ESCALATION
STACK:        ANDROID NATIVE · TFLITE INT8 · SCIKIT-LEARN · GEMINI API · KOTLIN
```

> **The Problem:** Cloud-based scam scanners compromise user privacy by streaming sensitive calls and texts to remote servers, suffering from network latency.  
> **The Engineering:** Trained and distilled malicious pattern classifiers converted to INT8 post-training quantized TFLite tensor models executing directly on-chip in under 20ms with 100% offline zero telemetry. Built a hybrid trigger escalation pipeline that selectively wakes the Gemini API only when edge confidence scores detect nuanced multi-turn fraud patterns requiring deep contextual explanation.

```
[ ↗ INSPECT REPOSITORY ] ──▶ https://github.com/GhananilShirpurkar/SafeGuard-AI
```

<br>

### ◈ 04 / MIRU — High-Throughput Media Discovery Engine
```
ARCHITECTURE: CLIENT-SIDE CACHING · ZERO LAYOUT SHIFT · DEBOUNCED REST PIPELINE
STACK:        REACT 18 · VITE · JAVASCRIPT ES6+ · REST APIS · VERCEL EDGE CDN
```

> **The Engineering:** High-performance media discovery engine featuring instant debounced REST query caching, localized watchlist state synchronization, dynamic asset lazy loading, and an uncompromising minimalist dark aesthetic with zero layout shift.

```
[ ↗ LIVE SYSTEM ] ──▶ https://miru-anitrack.vercel.app
[ ↗ REPOSITORY ]  ──▶ https://github.com/GhananilShirpurkar/Miru
```

<br>

### ◈ 05 / SPECIALIZED PROTOCOLS & UTILITIES

```
┌── REPOSITORY ──────┬── DOMAIN ──────────────────┬── ARTIFACT ──────────────────────┐
│ CommitGuard        │ CI/CD & Automated Gates    │ PR review & verification actions │
│ IssueHawk          │ Repo Triage & NLP Pipeline │ Autonomous issue classification  │
│ Recall             │ Agentic Memory Subsystem   │ Persistent vector context cache  │
│ Cipher-Watch       │ Cryptographic Monitor      │ Data pipeline integrity suite    │
└────────────────────┴────────────────────────────┴──────────────────────────────────┘
```

---

## 04 // THE MATRIX

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4><code>01 // INTELLIGENCE & AGENTS</code></h4>
      <p>
        <code>LangGraph</code> · <code>LangChain</code> · <code>CrewAI</code><br>
        <code>ChromaDB</code> · <code>MongoDB Atlas Vector</code><br>
        <code>Groq LPU</code> · <code>Gemini SDK</code> · <code>Pydantic</code><br>
        <code>Whisper</code> · <code>EasyOCR</code> · <code>PyTorch</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><code>02 // SYSTEMS & RUNTIMES</code></h4>
      <p>
        <code>Python 3.11+</code> · <code>FastAPI Async</code> · <code>C / C++</code><br>
        <code>PostgreSQL (Neon)</code> · <code>SQLAlchemy</code> · <code>Alembic</code><br>
        <code>TFLite (INT8 Quantization)</code> · <code>scikit-learn</code><br>
        <code>Server-Sent Events (SSE)</code> · <code>Clerk JWT</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><code>03 // INTERFACE & CLIENT</code></h4>
      <p>
        <code>React 18+</code> · <code>Vite</code> · <code>TypeScript</code><br>
        <code>Tailwind CSS</code> · <code>Android Studio (Java/Kotlin)</code><br>
        <code>HTML5 Semantic</code> · <code>Deterministic State</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><code>04 // INFRASTRUCTURE & DISPATCH</code></h4>
      <p>
        <code>Docker</code> · <code>Linux / Bash</code> · <code>Git / GitHub</code><br>
        <code>GitHub Actions (CI/CD)</code> · <code>Vercel Edge</code><br>
        <code>REST APIs</code> · <code>Postman</code> · <code>Tavily API</code>
      </p>
    </td>
  </tr>
</table>

<div align="center">
  <br>
  <img src="https://skillicons.dev/icons?i=python,fastapi,react,vite,ts,postgres,mongodb,docker,linux,cpp&theme=dark&perline=10" alt="Core Technologies" />
</div>

---

## 05 // TELEMETRY & PULSE

<div align="center">

<!-- GitHub Contribution Snake Animation -->
<img src="https://raw.githubusercontent.com/GhananilShirpurkar/GhananilShirpurkar/output/github-snake-dark.svg" width="100%" alt="Contribution Matrix Snake" />

<br><br>

<table border="0">
  <tr>
    <td align="center" width="50%">
      <img src="https://streak-stats.demolab.com?user=GhananilShirpurkar&theme=dark&hide_border=true&background=000000&ring=38bdf8&fire=38bdf8&currStreakLabel=38bdf8&sideLabels=94a3b8&dates=64748b&sideNums=e2e8f0&currStreakNum=ffffff" height="175" alt="Streak Pulse" />
    </td>
    <td align="center" width="50%">
      <img src="https://github-stats-alpha.vercel.app/api?username=GhananilShirpurkar&cc=38bdf8&tc=e2e8f0&ic=38bdf8&bc=000000" height="175" alt="Engineering Velocity" />
    </td>
  </tr>
</table>

</div>

---

## 06 // VERIFIED ACCREDITATIONS

```
┌── CREDENTIAL ──────────────────────────┬── AUTHORITY ───────────────┬── STATUS ────────┐
│ RAG with MongoDB                       │ MongoDB / GeeksforGeeks    │ [ Credly Valid ] │
│ Vector Search Fundamentals             │ MongoDB                    │ [ Credly Valid ] │
│ Core Concepts & Architecture           │ MongoDB                    │ [ Credly Valid ] │
│ Oracle AI Foundations Associate        │ Oracle Corporation         │ [ Certified ]    │
│ Generative AI Studio                   │ Simplilearn                │ [ Verified ]     │
│ Data Science with Python               │ LetsUpgrade                │ [ Completed ]    │
│ Power BI Workshop                      │ Office Master              │ [ Verified ]     │
└────────────────────────────────────────┴────────────────────────────┴──────────────────┘
```

<div align="center">
  <a href="https://www.credly.com/users/ghananil-shirpurkar" target="_blank">
    <img src="https://img.shields.io/badge/CREDLY%20TRANSCRIPT-VERIFIED%20INDEX-47A248?style=flat-square&logo=credly&logoColor=white" alt="Credly Verification" />
  </a>
</div>

---

## 07 // TERMINAL DISPATCH

```
╭─ koanoir@workstation:~$ ./dispatch --status --open
╰─► [LINK ESTABLISHED // READY FOR HIGH-IMPACT COLLABORATION]
    ├── Entity:       Ghananil Shirpurkar (koanoir)
    ├── Coordinates:  Nagpur, Maharashtra, India [21.1458° N, 79.0882° E]
    ├── Core Focus:   Autonomous Multi-Agent Graphs • Deterministic RAG • Edge Silicon
    └── Signal:       Open to AI Engineering roles, early-stage systems, & research labs.
```

<div align="center">

<br>

<a href="mailto:shirpurkarghananil@gmail.com">
  <img src="https://img.shields.io/badge/DISPATCH%20EMAIL-shirpurkarghananil%40gmail.com-000000?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email" />
</a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/ghananil-shirpurkar23" target="_blank">
  <img src="https://img.shields.io/badge/LINKEDIN-ghananil--shirpurkar23-000000?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" />
</a>&nbsp;&nbsp;
<a href="https://portfolio-ghananil-shirpurkar.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/LIVE%20PORTFOLIO-ghananil--shirpurkar.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=38BDF8" alt="Portfolio" />
</a>&nbsp;&nbsp;
<a href="https://github.com/GhananilShirpurkar">
  <img src="https://img.shields.io/badge/GITHUB-GhananilShirpurkar-000000?style=for-the-badge&logo=github&logoColor=FFFFFF" alt="GitHub" />
</a>

<br><br>

<!-- Footer Slice Banner -->
<img src="https://capsule-render.vercel.app/api?type=slice&color=0:000000,50:090d16,100:000000&height=100&section=footer&animation=fadeIn" width="100%" alt="Footer Slice" />

<br>

<sub><code>SYSTEMS OVER DEMOS • RESILIENT BY DESIGN • 2026</code></sub>

</div>
