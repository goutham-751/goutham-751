<!--
  GitHub Profile README — Goutham Kumar
  Paste this entire file as README.md in your github.com/goutham-751/goutham-751 repo.
  GitHub renders raw HTML inside Markdown files, so this works as-is.
-->

<div align="center"> <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=320&color=0:0f172a,30:2563eb,70:7c3aed,100:06b6d4&text=Goutham%20Kumar&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=40"/> </div> <div align="center"> <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=2500&pause=1000&color=38BDF8&center=true&vCenter=true&width=1200&lines=AI+Systems+Engineer;Building+Production+LLM+Systems;Multi-Tenant+RAG+Architect;Machine+Learning+Researcher;Full-Stack+Developer"/> </div> <br> <div align="center"> <a href="https://my-portfolio-three-dun-97.vercel.app"> <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/> </a> <a href="https://linkedin.com/in/goutham-kumar7"> <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/> </a> <a href="mailto:kgoutham2k5@gmail.com"> <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/> </a> </div> ---

<p>
  CS Engineering student at VIT Chennai &nbsp;·&nbsp; Full-Stack Developer &nbsp;·&nbsp; AI/ML Engineer
</p>

<p>
  <a href="mailto:kgoutham2k5@gmail.com">kgoutham2k5@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://my-portfolio-three-dun-97.vercel.app/" target="_blank">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/goutham-kumar7" target="_blank">LinkedIn</a>
</p>

</div>


## About

B.Tech CSE (Data Science) student at VIT Chennai . I build full-stack applications and AI-powered systems — from multi-tenant RAG APIs to recruitment platforms. My work sits at the intersection of backend engineering and applied ML, with a focus on systems that are production-ready rather than prototype-grade.

Currently researching self-supervised learning calibration on tabular data (under review).

---

## Experience

**SDE Intern — ItechFoundry Pvt. Ltd.** &nbsp;`Jun 2026 – Present` &nbsp;·&nbsp; Remote

Built a scalable educational platform using React + FastAPI with async PostgreSQL and Google OAuth 2.0. Engineered a 6-tier curriculum hierarchy with bulk CSV/XLSX ingestion and dry-run validation. Designed a multi-provider AI layer using the Factory Pattern to hot-swap between OpenAI, Anthropic, and Groq LLMs.

---

**Summer Research Intern — IGCAR, Dept. of Atomic Energy** &nbsp;`Jun – Jul 2025` &nbsp;·&nbsp; Kalpakkam

Worked in the Health & Industrial Safety Division on radiological dose mapping. Performed spatial analysis and anomaly detection on monitoring data, and contributed to safety assessment models using statistical trend analysis.

---

**Treasurer — CyberSecurity Student Community, VITC** &nbsp;`Jun 2025 – Jun 2026`

Managed financial budgeting for events, ran hands-on CTF workshops, and mentored members of a 200+ person community in cybersecurity fundamentals.

---

## Projects

<br/>

<!-- ── CampusHire.AI ── -->
<table>
  <tr>
    <td>
      <h3>🎯 &nbsp;CampusHire.AI</h3>
      <p><em>AI-powered recruitment platform with end-to-end candidate evaluation</em></p>
      <p>
        Real-time ATS resume scoring, speech-analytics-driven interview simulation, and multi-agent candidate ranking via Llama-3. Built for speed — async APIs handle concurrent live interviews without latency spikes.
      </p>
      <p>
        <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Llama--3-6B3FA0?style=flat&logo=meta&logoColor=white" />
        <img src="https://img.shields.io/badge/NLP-FF6F00?style=flat&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Agentic%20AI-0A66C2?style=flat&logo=openai&logoColor=white" />
      </p>
      <table>
        <tr>
          <td align="center" width="150"><b>ATS Scoring</b><br/><sub>Real-time resume analysis</sub></td>
          <td align="center" width="150"><b>Speech Analytics</b><br/><sub>Live interview evaluation</sub></td>
          <td align="center" width="150"><b>Multi-Agent</b><br/><sub>Automated ranking pipeline</sub></td>
          <td align="center" width="150"><b>React Dashboard</b><br/><sub>Live analytics + Framer Motion</sub></td>
        </tr>
      </table>
    </td>
  </tr>
</table>

<br/>

<!-- ── Multi-Tenant RAG API ── -->
<table>
  <tr>
    <td>
      <h3>🗄️ &nbsp;Multi-Tenant RAG API</h3>
      <p><em>Production SaaS backend for natural language querying over private documents</em></p>
      <p>
        Per-tenant ChromaDB vector isolation, hybrid Dense + BM25 retrieval with Reciprocal Rank Fusion, bcrypt API key auth, sliding-window rate limiting, and in-memory TTL caching. Containerised and deployed to HuggingFace Spaces.
      </p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white" />
        <img src="https://img.shields.io/badge/ChromaDB-FF5A1F?style=flat&logo=databricks&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
        <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black" />
      </p>
      <table>
        <tr>
          <td align="center" width="150"><b>Dense Embeddings</b><br/><sub>Sentence-Transformers</sub></td>
          <td align="center" width="150"><b>BM25 Sparse Search</b><br/><sub>Keyword retrieval layer</sub></td>
          <td align="center" width="150"><b>RRF Fusion</b><br/><sub>Ranked result merging</sub></td>
          <td align="center" width="150"><b>Multi-Tenant</b><br/><sub>Isolated per-client data</sub></td>
        </tr>
      </table>
    </td>
  </tr>
</table>

<br/>

<!-- ── PricePilot.AI ── -->
<table>
  <tr>
    <td>
      <h3>📈 &nbsp;PricePilot.AI</h3>
      <p><em>Pricing intelligence platform for revenue-optimised decision making</em></p>
      <p>
        Synthesises competitor pricing, market trends, and demand signals into actionable recommendations. Includes a historical analytics pipeline for price elasticity modelling, backed by Supabase and served via an executive React dashboard.
      </p>
      <p>
        <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
      </p>
      <table>
        <tr>
          <td align="center" width="150"><b>Competitor Data</b><br/><sub>Ingestion pipeline</sub></td>
          <td align="center" width="150"><b>Demand Forecasting</b><br/><sub>Predictive signals</sub></td>
          <td align="center" width="150"><b>Elasticity Model</b><br/><sub>Historical analytics</sub></td>
          <td align="center" width="150"><b>Exec Dashboard</b><br/><sub>React + Supabase</sub></td>
        </tr>
      </table>
    </td>
  </tr>
</table>

<br/>

<!-- ── Predictive Maintenance ── -->
<table>
  <tr>
    <td>
      <h3>⚙️ &nbsp;Predictive Maintenance System</h3>
      <p><em>End-to-end ML pipeline for industrial machine failure forecasting</em></p>
      <p>
        Classifies failure risk and estimates Remaining Useful Life from raw sensor streams. Class-imbalance techniques significantly improved failure detection accuracy. Served via FastAPI with a live Streamlit dashboard for both real-time and batch modes.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white" />
      </p>
      <table>
        <tr>
          <td align="center" width="150"><b>Failure Classification</b><br/><sub>Sensor data → risk label</sub></td>
          <td align="center" width="150"><b>RUL Estimation</b><br/><sub>Regression on remaining life</sub></td>
          <td align="center" width="150"><b>Imbalance Handling</b><br/><sub>SMOTE + class weights</sub></td>
          <td align="center" width="150"><b>Live Dashboard</b><br/><sub>Streamlit + FastAPI</sub></td>
        </tr>
      </table>
    </td>
  </tr>
</table>

<br/>

---

## Technical Skills

### Languages
<p>
  <img src="https://skillicons.dev/icons?i=python" height="40" alt="Python" title="Python" />
  <img src="https://skillicons.dev/icons?i=java" height="40" alt="Java" title="Java" />
  <img src="https://skillicons.dev/icons?i=js" height="40" alt="JavaScript" title="JavaScript" />
  <img src="https://skillicons.dev/icons?i=c" height="40" alt="C" title="C" />
  <img src="https://skillicons.dev/icons?i=cpp" height="40" alt="C++" title="C++" />
  <img src="https://skillicons.dev/icons?i=r" height="40" alt="R" title="R" />
  <img src="https://skillicons.dev/icons?i=matlab" height="40" alt="MATLAB" title="MATLAB" />
</p>

### Frameworks & Libraries
<p>
  <img src="https://skillicons.dev/icons?i=react" height="40" alt="React" title="React" />
  <img src="https://skillicons.dev/icons?i=nodejs" height="40" alt="Node.js" title="Node.js" />
  <img src="https://skillicons.dev/icons?i=express" height="40" alt="Express" title="Express" />
  <img src="https://skillicons.dev/icons?i=fastapi" height="40" alt="FastAPI" title="FastAPI" />
  <img src="https://skillicons.dev/icons?i=pytorch" height="40" alt="PyTorch" title="PyTorch" />
  <img src="https://skillicons.dev/icons?i=tensorflow" height="40" alt="TensorFlow" title="TensorFlow" />
  <img src="https://skillicons.dev/icons?i=sklearn" height="40" alt="Scikit-learn" title="Scikit-learn" />
</p>

### Databases
<p>
  <img src="https://skillicons.dev/icons?i=postgres" height="40" alt="PostgreSQL" title="PostgreSQL" />
  <img src="https://skillicons.dev/icons?i=mysql" height="40" alt="MySQL" title="MySQL" />
  <img src="https://skillicons.dev/icons?i=supabase" height="40" alt="Supabase" title="Supabase" />
  <img src="https://skillicons.dev/icons?i=sqlite" height="40" alt="SQLite" title="SQLite" />
</p>

### Cloud & DevOps
<p>
  <img src="https://skillicons.dev/icons?i=aws" height="40" alt="AWS" title="AWS" />
  <img src="https://skillicons.dev/icons?i=docker" height="40" alt="Docker" title="Docker" />
  <img src="https://skillicons.dev/icons?i=git" height="40" alt="Git" title="Git" />
  <img src="https://skillicons.dev/icons?i=github" height="40" alt="GitHub" title="GitHub" />
</p>

### AI / ML & Data
<p>
  <img src="https://skillicons.dev/icons?i=pytorch" height="40" alt="PyTorch" title="PyTorch" />
  <img src="https://skillicons.dev/icons?i=tensorflow" height="40" alt="TensorFlow" title="TensorFlow" />
  <img src="https://go-skill-icons.vercel.app/api/icons?i=langchain" height="40" alt="LangChain" title="LangChain" />
  <img src="https://skillicons.dev/icons?i=opencv" height="40" alt="OpenCV" title="OpenCV" />
  <img src="https://go-skill-icons.vercel.app/api/icons?i=huggingface" height="40" alt="HuggingFace" title="HuggingFace" />
  <img src="https://go-skill-icons.vercel.app/api/icons?i=pandas" height="40" alt="Pandas" title="Pandas" />
  <img src="https://skillicons.dev/icons?i=sklearn" height="40" alt="Scikit-learn" title="Scikit-learn" />
</p>

---

## Research

**CalibSSL: Reliability and Calibration of Self-Supervised Neural Networks on Tabular Data** &nbsp;*(Under Review, Jan 2026 – Present)*

Designed a calibration-aware training objective combining cross-entropy with entropy-based confidence penalty. Implemented ViME for self-supervised pretraining and benchmarked across 6 baselines and 5 label-scarcity settings with full statistical significance testing.

---

<div align="center">
  <sub>Last updated · June 2026</sub>
</div>
