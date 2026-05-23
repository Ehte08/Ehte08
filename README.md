# Mohammed Baquer

Data scientist from New York. I build ML systems end-to-end — scraped data to deployed model — and document them so the work is reproducible and the results speak for themselves.

B.S. Applied Mathematics & Statistics + Technology Management, Stony Brook University. Starting my **M.S. in Data Science at Hofstra** in August 2026. **Open to Fall 2026 internships in Machine Learning, Data Science, Generative AI, and Analytics.**

## **[Portfolio →](https://mohammed-baquer-portfolio.vercel.app/)**

---

## Stack

**Languages:** Python · SQL · Java  
**Machine Learning:** scikit-learn · LightGBM · XGBoost · Optuna · MLflow  
**Deep Learning & CV:** PyTorch · torchvision · OpenCV · MediaPipe  
**Generative AI & LLMs:** LangChain · LangGraph · RAG pipelines · Hugging Face  
**Deployment & MLOps:** FastAPI · Streamlit · Gradio  
**Data Engineering:** pandas · NumPy · automated ETL pipelines · Jupyter  

---

## Projects

### [F1 Race Outcome Predictor](https://github.com/Ehte08/F1-Predictor)
Learning-to-rank model that predicts Formula 1 podium finishes — **NDCG@3 of 0.91**, Spearman 0.67 on a chronological hold-out — using LightGBM trained on 8 seasons of Grand Prix data. The pipeline runs FastF1 + Ergast ingestion, Optuna hyperparameter search (30 trials), and MLflow experiment tracking, with a FastAPI REST endpoint and Streamlit dashboard on top. Leak-free rolling feature snapshots. Full pytest suite.

`LightGBM` `MLOps` `FastAPI` `Streamlit` `learning-to-rank` `hyperparameter-optimization`

---

### [Superhero Detector](https://github.com/Ehte08/Computer-Vision-Projects/tree/main/Superhero-detector)
Image classifier hitting **94% top-1 accuracy** across 10 Marvel and DC heroes, fine-tuned from ResNet50. I built the full pipeline: scraped and deduplicated ~3,900 images, then watched the transfer learning gains stack up — TinyCNN at 55%, ResNet18 at 89%, ResNet50 at 94%. Live Gradio demo with hardware-aware inference across Apple MPS, CUDA, and CPU.

`PyTorch` `ResNet50` `transfer-learning` `computer-vision` `Gradio`

---

### [PinchToHeart](https://github.com/Ehte08/Computer-Vision-Projects/tree/main/PinchToHeart)
Real-time CV app that detects a pinch gesture via webcam and fires a heart emoji over iMessage — no third-party APIs, just MediaPipe's 21-point 3D hand landmarks with a depth-aware false-positive filter running natively on macOS.

`MediaPipe` `OpenCV` `real-time` `computer-vision`

---

## In progress

**Bone Fracture Detection (YOLOv8)** — object detection on X-ray data, from annotation to mAP evaluation with a full writeup.

**RAG Agent** — end-to-end retrieval-augmented generation system with LangChain, a vector store, and an evaluation framework for retrieval quality and hallucination rate.

**Causal Inference study** — Difference-in-Differences with parallel-trends validation, robustness checks, and event-study plots on a public-policy dataset.

---

## Right now I'm digging into

LLM fine-tuning, agentic AI workflows with LangGraph, and LLM evaluation and safety frameworks. Also experimenting with LLM-driven code optimization over at [openevolvetest](https://github.com/Ehte08/openevolvetest).

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/mohammedehteshaambaquer/)
[![Portfolio](https://img.shields.io/badge/Portfolio-black?logo=vercel)](https://mohammed-baquer-portfolio.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-000?logo=github)](https://github.com/Ehte08)
