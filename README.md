# 👋 Hey there, I'm Kuan-Chen Chen

🎓 Pursuing my Master of Science in Applied Data Science at the University of Florida (Expected May 2026), with a background in Applied Mathematics from National Sun Yat-Sen University — where I graduated as the Valedictorian of my department.

🌟 I'm a data scientist and ML engineer with hands-on experience building intelligent systems across sports analytics, bioinformatics, and LLM applications. I care about shipping production-ready solutions that deliver real, measurable impact.

🏀 As a Data Scientist Intern with the **Florida Gators Women's Basketball** program, I built an opponent-strength-adjusted player evaluation system (OA-Rating) using XGBoost and SHAP across 120K+ game-level observations, implemented an Elo-based team rating system (ρ = 0.83 vs. NCAA NET), and developed a production R Shiny dashboard for player comparison and scouting — contributing to the team improving from NET 60 to NET 48.

🔬 At the **Bioinformatics Lab at UF**, I designed a stacking ensemble (XGBoost + LightGBM + Balanced Random Forest) to classify T-cell receptor CDR3 sequences under severe class imbalance (1:23), and developed a biologically-informed data augmentation algorithm using the BLOSUM62 substitution matrix, expanding the minority class 10× to reach ROC-AUC 0.876.

🤖 On the project side, I've shipped two production versions of **cAIuldron** — an AI-powered recipe app where users photograph ingredients and receive complete recipes with AI-generated images. v1 used CLIP + DETR for ingredient detection and QLoRA fine-tuned Llama 3.2 1B; v2 was rebuilt as a cloud-native system with LangGraph orchestration, Groq Llama 4 Scout 17B for vision, and ChromaDB RAG — cutting latency from 40–80s to 10–20s.

🚀 I also built **DARTS**, a campus mobility prediction system using a hybrid ARIMA-LSTM model that achieved 86.1% accuracy, reached national finals (Top 10 among 121 teams), and had its insights adopted by the university to optimize bus schedules.

💻 My goal is to work with cross-functional teams to develop AI systems that are not just technically sound, but genuinely useful.

## 🛠️ Technical Skills

### Programming Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

### ML / DL & AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-FF6B6B?style=for-the-badge&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logoColor=white)

### Web & Visualization
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-008DE4?style=for-the-badge&logo=plotly&logoColor=white)
![R Shiny](https://img.shields.io/badge/R_Shiny-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

## 💼 Work Experience

### Florida Gators Women's Basketball — Data Scientist Intern
**Aug 2025 – Present | Gainesville, FL**
- Built OA-Rating player evaluation system using XGBoost and SHAP, analyzing 120K+ game-level observations across 5,500+ NCAA players and 350+ teams
- Implemented Elo-based team rating system (ρ = 0.83 vs. NCAA NET) for real-time team strength tracking and game preparation
- Developed production R Shiny dashboard for player comparison and opponent scouting; contributed to team improvement from NET 60 to NET 48

### Bioinformatics Lab, University of Florida — Student Research Assistant
**Dec 2024 – Present | Gainesville, FL**
- Designed stacking ensemble (XGBoost + LightGBM + Balanced Random Forest + logistic regression meta-learner) to classify 10,486 T-cell receptor CDR3 sequences, achieving ROC-AUC 0.876 on highly imbalanced data (1:23)
- Developed biologically-informed data augmentation using BLOSUM62 substitution matrix, expanding minority class 10× (432 → 4,622) and improving class balance from 1:23 to 1:1.5
- Engineered 42 physicochemical features and optimized decision thresholds, achieving precision of 0.716 for high-confidence predictions

### Glory Integrated Marketing Co. Ltd — Data Analyst Intern
**Aug 2023 – Dec 2023 | Taipei, Taiwan**

## 🔍 Research Interests
- **Sports Analytics:** Player evaluation, opponent modeling, game prediction
- **Bioinformatics:** Sequence classification, imbalanced learning, feature engineering on biological data
- **LLM & Generative AI:** RAG systems, fine-tuning, multi-modal pipelines, LangGraph orchestration
- **Predictive Modeling:** Time series analysis, ensemble methods, production ML systems

## 🚀 Featured Projects

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
- 📍 Location: Gainesville, FL
- 🤝 Open to: ML Engineering Roles, Data Science Internships, Research Collaborations
