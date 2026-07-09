# Hi, I'm Prakhar Srivastava 👋

**Data Analyst | Data Scientist | AI Engineer**

I build end-to-end data and AI systems — from SQL-driven BI dashboards to production-style MLOps pipelines and LLM-powered agents. Most of my work lives in this GitHub, structured as if it were shipping to production: versioned data, tracked experiments, tested code, and CI.

- 🔭 Currently building **AI agents** for task automation and exploring agentic workflows for data analysis
- 🌱 Currently deepening skills in **multimodal AI agents, MLOps at scale, and applied deep learning**
- 🤝 Open to collaborating on **AI-powered tools, SaaS products, and data platforms**
- 💬 Ask me about **LLM evaluation pipelines, EDA & dashboards, SQL, object detection, or CI/CD for ML**
- ⚡ Fun fact: I've trained a Faster R-CNN vehicle detector as part of an autonomous-driving pipeline, and separately built a system that automatically scores LLM outputs against a golden dataset to catch quality regressions before they ship

---

## ✨ Highlights

- 🚀 **17+ open-source projects** spanning BI dashboards, deployed ML/DL pipelines, NLP, RAG, LLMOps, and agentic AI.
- 🛠️ **Production-grade MLOps** — live deployments on AWS and Hugging Face, CI/CD quality gates, Docker/Kubernetes, MLflow tracking, and Prometheus/Grafana observability.
- 📏 **Evaluation-first engineering** — models reported with honest, measured metrics (test accuracy, mAP, R²) and documented failure modes, not just happy-path demos.

---

## 🚀 Featured Projects

| Project | What it does | Key result |
|---|---|---|
| [LLM-Regression-Guard](https://github.com/prakhar-189/LLM-Regression-Guard) | MLOps pipeline that scores PRs against a golden dataset to catch LLM output regressions before production | MLflow + DVC + Celery + TimescaleDB + shadow traffic, full CI gates |
| [Stock-Chart-Predictor](https://github.com/prakhar-189/Stock-Chart-Predictor) | Vision Transformer that classifies candlestick chart trends (up/sideways/down) | Live demo on Hugging Face Spaces; honestly-reported 0.40 test accuracy vs 0.33 baseline |
| [Autonomous-Driving-Deep-Learning](https://github.com/prakhar-189/Autonomous-Driving-Deep-Learning) | Faster R-CNN (MobileNetV3) vehicle detector + Tesla Autopilot incident analysis | mAP@0.5 0.128, precision 0.685 on 1,134 held-out images — real numbers, real limitations documented |
| [Math-Solver-DeepLearning](https://github.com/prakhar-189/Math-Solver-DeepLearning) | Handwritten arithmetic solver: CRNN + CTC recognizer trained on synthetic data, evaluated on real handwriting, solved with SymPy (Streamlit app) | 99.5% in-domain accuracy; honestly measured synthetic→real gap and root-caused the dominant failure mode (the handwritten digit `1`) |
| [Agentic-Data-Analyst-Assistant](https://github.com/prakhar-189/Agentic-Data-Analyst-Assistant) | Self-correcting EDA agent built on LangGraph + a local Qwen2.5-Coder model | Multi-step agentic loop with automatic error correction, fully local (Ollama) |
| [RAG-LocalLLM](https://github.com/prakhar-189/RAG-LocalLLM) | 100% local, zero-API RAG chatbot over your PDFs (LangChain + FAISS + Phi-3 via Ollama) | Semantic chunking, strict grounding + citations, 3-signal eval harness (ROUGE-L / BERTScore / LLM-as-Judge), content-hash vector cache, pytest + CI + Docker |
| [Online-Retail-SQL-PowerBI](https://github.com/prakhar-189/Online-Retail-SQL-PowerBI) | Retail analytics: RFM segmentation + cohort retention on transaction data | MySQL (CTEs/window functions) → Power BI dashboard |
| [Student-ML-Project](https://github.com/prakhar-189/Student-ML-Project) | Flask app (web form + JSON API) predicting student exam scores, deployed to the cloud | Live on AWS Elastic Beanstalk; MLflow tracking, cross-validated model selection (test R² 0.88), pytest + GitHub Actions CI, Docker |

*(Full list of 17+ repos on my [profile](https://github.com/prakhar-189?tab=repositories) — spanning NLP, clustering, computer vision, and BI dashboards.)*

---

## 🧠 Tech Stack

**Languages & Core**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

**Data Analysis & BI**
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge) ![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge)

**Machine Learning & Deep Learning**
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=for-the-badge) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![NLTK](https://img.shields.io/badge/NLTK-154F3C?style=for-the-badge&logo=python&logoColor=white)

**LLMs & Agentic AI**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white) ![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white) ![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)

**MLOps & DevOps**
![MLflow](https://img.shields.io/badge/mlflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white) ![DVC](https://img.shields.io/badge/DVC-945DD6?style=for-the-badge&logo=dvc&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

**Cloud & Infra**
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) ![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)

**Web & Apps**
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)

---

## 🎓 Certifications

- **Professional Certificate — Data Analytics & Generative AI** · E&ICT Academy, IIT Guwahati × Simplilearn *(Jun 2025 – Apr 2026)*
- **Microsoft AI Engineer Program** · Microsoft × Simplilearn *(Dec 2025)*

---

## 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api?username=prakhar-189&theme=shadow_blue&hide_border=false&include_all_commits=true&count_private=false)
![](https://nirzak-streak-stats.vercel.app/?user=prakhar-189&theme=shadow_blue&hide_border=false)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=prakhar-189&theme=shadow_blue&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

---

## 🌐 Connect with me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/prakhar-srivastava-080743322) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/prakhar__189) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/Prakhar15506135) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:srivastavaprakhar189@gmail.com)

[![](https://visitcount.itsvg.in/api?id=prakhar-189&icon=4&color=12)](https://visitcount.itsvg.in)
