<h1 align="center">hi, I'm Max</h1>

<p align="center"><strong>ML Engineer • Hackathon enthusiast</strong></p>

<p align="center">
  <a href="mailto:kxwarvta@mail.ru"><img alt="Email" src="https://img.shields.io/badge/email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/shadxwkxw"><img alt="GitHub" src="https://img.shields.io/badge/github-24292e?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

I'm a Master's student in Intelligent Media Technologies at DSTU (BSc in Machine Learning & AI). I build production-grade ML systems — from fraud detection to RAG platforms and recommender systems — with a real MLOps loop behind them: training, orchestration, deployment, monitoring. I also come from a frontend background, which means I can take a model all the way from a notebook to something a person can actually click on.

## What I do

- **ML systems that leave the notebook** — training pipelines, batch + online inference, the infrastructure that keeps a model alive in production.
- **NLP / LLM plumbing** — hybrid RAG over private documents, summarization, structured extraction with LLMs.
- **The boring half that makes it real** — FastAPI → Docker → Kubernetes, Airflow for orchestration, CI/CD with real test coverage.

## Highlights

**Five first-place finishes in 18 months**, most of them Center-Invest Bank cases at the Southern IT Forum:

- 🥇 [**III Case Championship, IT University Consortium**](https://news.donstu.ru/news/studenty-dgtu-vyigrali-tretiy-regionalnyy-keys-chempionat-po-mashinnomu-obucheniyu) — multi-label banking product classifier, ROC-AUC ≈ 0.66 on the hidden leaderboard
- 🥇 [**Spring Hackathon 2026**](https://www.centrinvest.ru/about/press-releases/bank-tsentr-invest-na-iuzhnom-it-forume) — AI knowledge-processing platform with RAG over a private document base · Center-Invest Bank case
- 🥇 [**Autumn Hackathon 2025**](https://www.centrinvest.ru/about/press-releases/bank-tsentr-invest-provel-khakaton-osen-2025) — route optimizer for field sales visits · Center-Invest Bank case
- 🥇 [**AIST-2 ML Hackathon**](https://donstu.ru/news/about-new/?code=institut-skvoznykh-tekhnologiy-provodit-khakaton-po-iskusstvennomu-intellektu-aist-) — UAV search-and-rescue detection system
- 🥇 [**AIST ML Hackathon**](https://www.centrinvest.ru/about/press-releases/bank-tsentr-invest-podderzhal-otkrytie-unikalnoi-laboratorii-po-razrabotke-igr-i-iskusstvennogo-intellekta) — PII filtering system for text · Center-Invest Bank case

## Projects

- **AI Research Platform** — NotebookLM-style platform I kept developing after the Spring 2026 win: hybrid RAG (dense Qwen3 embeddings in Qdrant + BM25 rerank), document chunking, LLM-powered summaries, flashcards, table extraction, mind maps and a web crawler that feeds the knowledge base. FastAPI, JWT auth, Docker Compose.
- **Music Recommender** *(in progress)* — content-based music recommendations with a collaborative boost from user likes. Audio is turned into vectors (82 librosa features or CLAP embeddings: same-genre share in top-10 **0.53 vs 0.34**), searched in a FAISS index; personal recs split a user's likes into separate interests instead of one blurry average. Normalization, metric, feature weights and boost are tuned with Optuna on likes. Versioned index with atomic swaps, FastAPI + batch CLI, Airflow DAGs, Alembic migrations, CI with tests on Postgres.
- **Anti-fraud ML System** — production-grade fraud detection: batch + online inference, Airflow orchestration, Kubernetes deployment, FastAPI, CI/CD with 93% test coverage, Clean Architecture.

In September 2026 I took part in the [**International AI Summer Camp**](https://en.ncut.edu.cn/info/1007/1884.htm) at North China University of Technology in Beijing, a Chinese Government Scholarship summer school program: machine learning coursework with hands-on labs (PyTorch, PaddlePaddle) and a visit to Baidu. My Bachelor's thesis applied computer vision to traffic-light phase optimization based on conflict analysis.

## Stack

<p align="center">
  <a href="https://skillicons.dev"><img alt="stack" src="https://skillicons.dev/icons?i=python,sklearn,tensorflow,pytorch,docker,kubernetes,postgres,sqlite,opencv,react,nextjs,ts,git,github&perline=7"></a>
</p>

- **ML & Data:** Python, pandas, NumPy, scikit-learn, CatBoost, XGBoost, PyTorch, SHAP
- **NLP & LLM:** RAG, Qdrant, embeddings, BM25, OpenAI-compatible LLM APIs
- **Recommender & Search:** FAISS, Optuna, librosa, CLAP embeddings
- **MLOps & Infra:** Apache Airflow, Docker, Kubernetes, FastAPI, PostgreSQL, CI/CD
- **Frontend:** TypeScript, React, Next.js

## One more thing

I also work as a **frontend developer** — most of the hackathon projects above shipped with an interface I built: React/Next.js dashboards, chat UIs for RAG systems, map-based route visualizations. A couple of self-directed projects if you want to see the range:

- **Spotify Clone** — fullstack music player: JWT auth, playback queue, Spotify Web API integration (React, Vite, Node.js/Express, PostgreSQL)
- **Admin Panel** — CRUD tables, auth, Zod-validated forms (Next.js 14, TypeScript, Zustand)

<p align="center">
  <a href="https://github.com/shadxwkxw/btx-admin-panel"><img alt="Admin Panel" src="https://img.shields.io/badge/admin_panel-111111?style=for-the-badge&logo=github&logoColor=white"></a>
</p>
