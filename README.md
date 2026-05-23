# Mohammed Baquer

I built my first ML project to settle an argument with myself: could a neural network tell Batman from Iron Man? Turns out, yes — 94% of the time. I'm a data scientist from New York, and that's basically how I approach everything: find a problem that actually interests me, then build something that works.

B.S. Applied Mathematics & Statistics + Technology Management, Stony Brook University. Starting my **M.S. in Data Science at Hofstra** in August 2026. **Open to Fall 2026 internships in Machine Learning, Data Science, Generative AI, and Analytics.**

**[Portfolio →](https://mohammed-baquer-portfolio.vercel.app/)**

---

## 🛠️ Stack

**Languages:** Python · SQL · Java  
**Machine Learning:** scikit-learn · LightGBM · XGBoost · Optuna · MLflow  
**Deep Learning & CV:** PyTorch · torchvision · OpenCV · MediaPipe  
**Generative AI & LLMs:** LangChain · LangGraph · RAG pipelines · Hugging Face  
**Deployment & MLOps:** FastAPI · Streamlit · Gradio  
**Data Engineering:** pandas · NumPy · automated ETL pipelines · Jupyter  

---

## 📂 Projects

### 🏎️ [F1 Race Outcome Predictor](https://github.com/Ehte08/F1-Predictor)

Eight seasons of Formula 1 data, one LightGBM model, and a question I genuinely wanted answered: can you predict the podium before the race starts? The answer is yes — **NDCG@3 of 0.91**, Spearman 0.67 on a chronological hold-out. The pipeline handles everything from FastF1 + Ergast ingestion to Optuna hyperparameter search (30 trials), MLflow experiment tracking, a FastAPI REST endpoint, and a Streamlit dashboard on top. Leak-free rolling feature snapshots. Full pytest suite.

`LightGBM` `MLOps` `FastAPI` `Streamlit` `learning-to-rank` `hyperparameter-optimization`

---

### 🦸 [Superhero Detector](https://github.com/Ehte08/Computer-Vision-Projects/tree/main/Superhero-detector)

I scraped ~3,900 images of 10 Marvel and DC heroes, then watched transfer learning do its thing: TinyCNN hit 55%, ResNet18 got to 89%, ResNet50 landed at **94% top-1 accuracy**. The Gradio demo runs hardware-aware inference — MPS on my Mac, CUDA on a GPU machine, CPU as a fallback.

`PyTorch` `ResNet50` `transfer-learning` `computer-vision` `Gradio`

---

### 🤖 [GenAI Chatbot](https://github.com/Ehte08)

Built a generative AI chatbot that cut response times from 4–6 hours to under 10 minutes and deflected a significant volume of support tickets. Grounded in internal documentation through a retrieval layer — so it's fast and accurate.

`Generative AI` `LLM` `RAG` `NLP`

---

### 📊 [Data Automation Pipeline](https://github.com/Ehte08)

Turned two days of manual reporting into same-day delivery. Automated ingestion, transformation, and output across 10K+ rows of operational data in Python and SQL.

`Python` `SQL` `data-engineering` `ETL` `automation`

---

### 🤏 [PinchToHeart](https://github.com/Ehte08/Computer-Vision-Projects/tree/main/PinchToHeart)

A real-time CV app that detects a pinch gesture via webcam and fires a heart emoji over iMessage — no third-party APIs, just MediaPipe's 21-point 3D hand landmarks with a depth-aware false-positive filter running natively on macOS. Yes, I built this.

`MediaPipe` `OpenCV` `real-time` `computer-vision`

---

## 🔨 In progress

**Bone Fracture Detection (YOLOv8)** — object detection on X-ray data, from annotation to mAP evaluation with a full writeup.

**RAG Agent** — end-to-end retrieval-augmented generation with LangChain, a vector store, and an evaluation framework measuring retrieval quality and hallucination rate.

**Causal Inference study** — Difference-in-Differences with parallel-trends validation, robustness checks, and event-study plots on a public-policy dataset.

---

## 🎯 Right now I'm into

LLM fine-tuning, agentic AI workflows with LangGraph, and LLM evaluation and safety frameworks. Also poking at LLM-driven code optimization over at [openevolvetest](https://github.com/Ehte08/openevolvetest).

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/mohammedehteshaambaquer/)
[![Portfolio](https://img.shields.io/badge/Portfolio-black?logo=vercel)](https://mohammed-baquer-portfolio.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-000?logo=github)](https://github.com/Ehte08)
