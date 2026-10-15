# 👋 Hey there, I'm Kuan-Chen Chen

🎓 I hold a Master of Science in Applied Data Science from the University of Florida (May 2026) and a B.S. in Applied Mathematics from National Sun Yat-Sen University, where I graduated as the Valedictorian of my department.

🌟 I'm a data scientist and ML engineer with hands-on experience building intelligent systems across sports analytics, bioinformatics, and LLM applications. I care about shipping production-ready solutions that deliver real, measurable impact.

⚡ I'm an open-source contributor to **NVIDIA NeMo Automodel**, NVIDIA's distributed LLM training library, with 2 merged PRs ([MiniCPM5-1B](https://github.com/NVIDIA-NeMo/Automodel/pull/2341), [Falcon H1](https://github.com/NVIDIA-NeMo/Automodel/pull/2334)) adding 7 fine-tuning recipes (SFT, LoRA) for models from 0.5B to 34B, including LoRA and tensor-parallelism configuration for 34B-scale training.

🏀 As a Data Scientist Intern with the **Florida Gators Women's Basketball** program, I replaced a manually-weighted player evaluation system with OA-Rating, an XGBoost + SHAP model validated against the legacy system (r = 0.78) across 120K+ observations; built an Elo-based team rating system with 83% agreement with NCAA's official national rankings; and shipped a production R Shiny dashboard — contributing to the team's improvement from 60th to 48th nationally.

🔬 At the **Bioinformatics Lab at UF**, I designed a stacking ensemble (XGBoost + LightGBM + Balanced Random Forest) to classify T-cell receptor CDR3 sequences under severe class imbalance (1:23), and developed a biologically-informed data augmentation algorithm using the BLOSUM62 substitution matrix, expanding the minority class 10× — reaching 87.6% accuracy (ROC-AUC 0.876) and outperforming the best individual model (85%).

🤖 On the project side, I built **CV Generator**, a JD-tailored résumé agent that combines hybrid retrieval (Chroma + BM25 with Reciprocal Rank Fusion), a LangGraph human-in-the-loop workflow, and an LLM supervisor that fact-checks every claim against source documents. I've also shipped two production versions of **cAIuldron** — an AI-powered recipe app where users photograph ingredients and receive complete recipes with AI-generated images. v1 used CLIP + DETR for ingredient detection and QLoRA fine-tuned Llama 3.2 1B; v2 was rebuilt as a cloud-native system with LangGraph orchestration, Groq Llama 4 Scout 17B for vision, and ChromaDB RAG — cutting latency from 40–80s to 10–20s.

🚀 I also built **DARTS**, a campus mobility prediction system using a hybrid ARIMA-LSTM model that achieved 86.1% accuracy, reached national finals (Top 10 among 121 teams), and had its insights adopted by the university to optimize bus schedules.

💻 My goal is to work with cross-functional teams to develop AI systems that are not just technically sound, but genuinely useful.

## 🛠️ Technical Skills

### Programming Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### ML / DL
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02A388?style=for-the-badge&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-FF6B6B?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### LLM & AI Agents
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logoColor=white)
![AssemblyAI](https://img.shields.io/badge/AssemblyAI-2545D3?style=for-the-badge&logoColor=white)

### Backend & Apps
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Data & Visualization
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-008DE4?style=for-the-badge&logo=plotly&logoColor=white)
![R Shiny](https://img.shields.io/badge/R_Shiny-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

## 💼 Work Experience

### NVIDIA NeMo Automodel — Open-Source Contributor
**May 2026 – Present | Open Source**
- Contributed 2 merged PRs ([MiniCPM5-1B](https://github.com/NVIDIA-NeMo/Automodel/pull/2341), [Falcon H1](https://github.com/NVIDIA-NeMo/Automodel/pull/2334)) to NVIDIA's distributed LLM training library, adding 7 fine-tuning recipes (SFT, LoRA) for models from 0.5B to 34B
- Configured LoRA hyperparameters (rank, alpha, target modules) and tensor parallelism for 34B-scale training; validated convergence on T4 GPU runs

### Florida Gators Women's Basketball — Data Scientist Intern
**Aug 2025 – May 2026 | Gainesville, FL**
- Replaced a manually-weighted player evaluation system with OA-Rating, an XGBoost + SHAP model validated against the legacy system (r = 0.78) across 120K+ observations, 5,500+ players, and 350+ teams
- Built an Elo-based team rating system with 83% agreement with NCAA's official national rankings, and clustered teams into 4 tactical archetypes to support real-time game preparation and opponent scouting
- Shipped a production R Shiny dashboard that contributed to the team's improvement from 60th nationally (16–17) to 48th nationally (18–15)

### Bioinformatics Lab, University of Florida — Student Research Assistant
**Dec 2024 – May 2026 | Gainesville, FL**
- Designed a stacking ensemble (XGBoost + LightGBM + Balanced Random Forest + logistic regression meta-learner) reaching 87.6% accuracy (ROC-AUC 0.876) in distinguishing brain- vs. blood-derived T-cell receptor CDR3 sequences, outperforming the best individual model (85%) on 10,486 sequences
- Developed a biologically-informed data augmentation algorithm using the BLOSUM62 substitution matrix, generating conservative sequence variants to expand the minority class 10× (432 → 4,622) and mitigate severe class imbalance (1:23 → 1:1.5)
- Engineered 42 physicochemical features from protein sequences and optimized decision thresholds under class imbalance, improving precision to 0.716 for high-confidence, interpretable predictions

### Glory Integrated Marketing Co. Ltd — Data Analyst Intern
**Aug 2023 – Dec 2023 | Taipei, Taiwan**

## 🔍 Research Interests
- **Sports Analytics:** Player evaluation, opponent modeling, game prediction
- **Bioinformatics:** Sequence classification, imbalanced learning, feature engineering on biological data
- **LLM & Generative AI:** Fine-tuning (SFT, LoRA/QLoRA), distributed training, RAG systems, AI agents, multi-modal pipelines, LangGraph orchestration
- **Predictive Modeling:** Time series analysis, ensemble methods, production ML systems

## 🚀 Featured Projects

### [Auto Job Apply](https://github.com/Ckcinnabar/auto-JOB-apply-docs)
**Autonomous Job-Application Agent**
- Built a Claude-powered browser agent (Playwright) that searches LinkedIn, screens each posting, and applies end to end — through LinkedIn Easy Apply and employer ATS sites (Workday, Greenhouse, Ashby, Oracle, SuccessFactors and more), including account creation, email verification, form filling, and résumé upload
- Submitted 85 confirmed applications across 10+ ATS platforms in its first 4 days, averaging $0.23 in API cost per confirmed application
- Designed cost-aware model routing: Claude Haiku screens postings (~$0.002 each) and fills forms, Claude Opus reviews employer-site forms against the candidate's data before submit and retries failed runs, with per-job and per-run spending caps
- Ran up to 4 applications in parallel in separate Chrome windows with memory-aware scheduling and per-company locks; forms blocked by CAPTCHAs or site errors stay open for a person to finish instead of being refilled
- Built an IMAP reader that classifies employer replies (confirmations, assessments, interview invitations, rejections) and matches them to applications, plus a desktop panel for progress, costs, and replies; credentials stay in Windows Credential Manager and are never sent to the model
- **Tech Stack:** Python, Claude API, Playwright, FastAPI, Groq, SQLite, pywebview, Gradio, Chrome Extensions

### [InterviewMate](https://github.com/Ckcinnabar/interviewmate)
**Real-Time Interview Assistant** | Electron desktop app
- Built an always-on-top overlay that transcribes live interview audio with AssemblyAI streaming speech-to-text (system audio, plus the candidate's microphone when enabled) and streams answers from Claude, starting automatically once the interviewer finishes a question
- Kept answers consistent across an interview by sending the full multi-turn history with every request, and grounded experience questions in the candidate's own write-ups and résumé, with Claude Opus condensing PDFs into notes cached by content hash
- Cut latency through model routing (Claude Haiku with thinking off for spoken questions, Claude Opus for on-screen coding problems) and prompt caching warmed at start: ~0.6 s to first word, ~1.2 s with ~62K tokens of context
- Added screen and region capture for on-screen problems, English and Traditional Chinese modes (OpenCC conversion), and job-description parsing that steers answers toward the skills a role needs
- Started as a fork of Open-Cluely; replaced Gemini/Ollama with Claude and trimmed it down to the interview workflow
- **Tech Stack:** JavaScript, Node.js, Electron, Claude API, AssemblyAI, WebSockets, OpenCC

### [CV Generator](https://ckcinnabar.github.io/projects/cv-generate.html)
**JD-Tailored Résumé Agent** | Gainesville, FL
- Built a hybrid retrieval pipeline — dense embeddings (Chroma) + BM25, fused via Reciprocal Rank Fusion — with a Claude Haiku selector ranking the top-5 most relevant items per job description
- Orchestrated via a LangGraph stateful graph with a human-in-the-loop interrupt for approval, and constrained Claude generation with hard-coded titles/dates to prevent hallucination
- Built an LLM supervisor that fact-checks every claim against source documents, plus a render-retry loop (docx2pdf → pypdf) that shortens content until it fits one page
- **Tech Stack:** Python, LangGraph, Claude API, ChromaDB, BM25, docx2pdf, pypdf

### [cAIuldron](https://ckcinnabar.github.io/projects/cauldron.html)
**AI-Powered Recipe Generation App** | Gainesville, FL
- Built two production versions of an app where users photograph ingredients and receive complete recipes with AI-generated food images; cut end-to-end pipeline latency from 40–80s (v1) to 10–20s (v2) through architectural redesign and parallel execution
- **v1:** CLIP + DETR for multi-ingredient detection across 525+ food classes (88% F1); QLoRA fine-tuned Llama 3.2 1B on 7,913 RecipeNLG recipes (only 0.23% of parameters updated), achieving 92/100 recipe quality score
- **v2:** Rebuilt as cloud-native with LangGraph StateGraph orchestration; replaced local GPU models with Groq Llama 4 Scout 17B (vision) and Llama 3.3 70B (generation); integrated ChromaDB RAG and Tavily web search via parallel fork/join, eliminating 4–6 GB VRAM dependency
- **Tech Stack:** Python, PyTorch, LangGraph, LangSmith, HuggingFace, Groq, ChromaDB, Gradio

### [DARTS - Campus Mobility System](https://ckcinnabar.github.io/projects/darts.html)
**Smart Campus Demand Prediction** | Climate Change Innovation Competition, Ministry of Education (Taiwan)
- Built a mobility prediction system integrating multi-source APIs (TDX/PTX) with an automated 24/7 data pipeline for real-time forecasting of pedestrian, bicycle, and bus demand
- Developed hybrid ARIMA-LSTM time-series model with data preprocessing and feature engineering, achieving 86.1% accuracy; insights adopted by the university to optimize bus schedules
- Reached national finals — Top 10 among 121 competing teams
- **Tech Stack:** Python, ARIMA-LSTM, TensorFlow, Time Series Analysis, Web Dashboard

## 📫 Connect With Me
- 📧 Email: champion3.chen@gmail.com
- 🌐 Portfolio: [ckcinnabar.github.io](https://ckcinnabar.github.io)
- 💼 LinkedIn: [linkedin.com/in/kuan-chen-chen](https://www.linkedin.com/in/kuan-chen-chen/)
- 📍 Location: Hacienda Heights, CA
- 🤝 Open to: Full-time ML Engineer, AI Engineer & Data Scientist Roles, Research Collaborations
