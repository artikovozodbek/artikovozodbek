<p align="center">
  <img src="assets/header.svg" alt="Ozodbek Artikbayev, AI/ML Engineer" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-AI%2FML%20internships-3be0c3?style=flat-square" alt="Open to AI/ML internships">
  <img src="https://img.shields.io/badge/Based%20in-Tashkent%20%C2%B7%20UTC%2B5-2aabee?style=flat-square" alt="Tashkent, UTC+5">
  <img src="https://img.shields.io/badge/Languages-Uzbek%20%C2%B7%20English%20B1-7a5cff?style=flat-square" alt="Uzbek, English B1">
</p>

### Hi, I'm Ozod 👋

I build **AI systems that do real work and prove it with numbers**: retrieval-augmented
generation that cites its sources, agents that act inside real accounts, and classical ML
evaluated the honest way. When something is slow, I profile it before I touch it.

<p align="center">
  <img src="assets/impact.svg" alt="Impact: 4x faster Telegram tasks, ~2 s chat replies, 100% Hit@1 on the legal RAG test set, R² 0.95 with a time-aware split, 9 public documented projects" width="100%">
</p>

## ⭐ Featured work

<table>
  <tr>
    <td width="50%"><a href="https://github.com/artikovozodbek/uzbek-legal-rag"><img src="assets/card-legal.png" alt="Uzbek Legal RAG: 559 articles, 100% Hit@1 on 14 checked questions"></a></td>
    <td width="50%"><a href="https://github.com/artikovozodbek/openclaw-telegram-assistant"><img src="assets/card-claw.png" alt="ClawAI Assistant: Telegram tasks 57 s to 14 s, chat in about 2 s, 69 tests passing"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://github.com/artikovozodbek/crop-yield-prediction"><img src="assets/card-crop.png" alt="Crop Yield Prediction: R² 0.95 time-aware split, 7 models, 101 countries"></a></td>
    <td width="50%"><a href="https://github.com/artikovozodbek/wikipedia-hybrid-rag"><img src="assets/card-wiki.png" alt="Wikipedia Hybrid RAG: 18,656 chunks, Hit@5 0.72, 50 auto-generated questions"></a></td>
  </tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br>

| Project | What it is |
|---|---|
| [ai-data-analysis-platform](https://github.com/artikovozodbek/ai-data-analysis-platform) | FastAPI multi-agent platform: dataset understanding, cleaning suggestions, visualization, automated reports |
| [ai-teaching-assistant](https://github.com/artikovozodbek/ai-teaching-assistant) | Offline AI tutor: hybrid RAG (Chroma + BM25) over your own slides and books, Llama 3.2 via Ollama |
| [realtime-face-recognition](https://github.com/artikovozodbek/realtime-face-recognition) | Real-time webcam face recognition (InsightFace / ArcFace) with live enrollment, no retraining |
| [classical-machine-learning](https://github.com/artikovozodbek/classical-machine-learning) | KNN, SVM, trees, ensembles, XGBoost, applied to a churn-prediction case study |
| [python-learning-journey](https://github.com/artikovozodbek/python-learning-journey) | Python fundamentals to ML: basics → OOP → GUI → SQL → machine learning |

</details>

## 🧭 How I work

- **Measure first.** ClawAI felt "slow"; a CPU profile showed the model was fine (2.3 s) and
  the real cost was file-system calls over a Windows mount. Fixing that, plus a fast-lane
  plugin, took tasks from 57 s to 14 s and chat to ~2 s.
- **Evaluate honestly.** In crop-yield prediction, random K-Fold reported R² 0.987; a
  time-aware split gave 0.952, the number that reflects the real use. I report the lower one.
- **Cite, don't invent.** My RAG systems return the article or passage they used, and each
  README states the size and limits of its test set.
- **Ship it end to end.** Docker, tests, setup scripts, safety rules and a README a stranger
  can follow.

## 🛠️ Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,nodejs,docker,postgres,redis,linux,git&theme=dark" alt="Python, PyTorch, scikit-learn, FastAPI, Node.js, Docker, PostgreSQL, Redis, Linux, Git">
</p>

| Area | Tools |
|---|---|
| **LLM, RAG and agents** | FAISS, BM25, cross-encoder reranking, Reciprocal Rank Fusion, ChromaDB, LangGraph, OpenClaw, Gemini / OpenAI-compatible APIs, Ollama |
| **Machine learning** | scikit-learn, XGBoost, LightGBM, CatBoost, pandas, NumPy, PyTorch (fundamentals) |
| **Computer vision** | OpenCV, InsightFace (ArcFace) |
| **Backend and infrastructure** | FastAPI, Node.js, Docker Compose, PostgreSQL, Redis, Telegram Bot API / MTProto |

## 📍 Right now

- Studying in the **AI/ML program at Najot Ta'lim** and working as a **support teacher**
  for Python, SQL and C.
- Growing **ClawAI** into a bigger product: Uzbek voice, scheduled tasks, safe payments.
- Looking for an **AI/ML engineering internship** where models go to production.

<p align="center">
  <img src="assets/footer.svg" alt="Build it. Measure it. Ship it." width="100%">
</p>
