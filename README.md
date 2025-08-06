# Advanced-Data-Mining-and-Language-Technology
Biomedical question-answering with hybrid RAG system (Kaggle Hackathon, 2nd place)

# 🧠 ADM-LT 2024-2025 Hackathon - RAG System

This repository contains our 2nd-place winning solution for the ADM-LT 2024-2025 Hackathon on Kaggle. The task was to build a **Retrieval-Augmented Generation (RAG)** system to answer biomedical questions using a given corpus of documents.

We designed a hybrid pipeline combining:
- **BM25** lexical retrieval (via Pyserini)
- **Dense vector retrieval** (with Sentence Transformers)
- **Reranking** (using Cross-Encoder)
- **Answer generation** (using Mistral-7B-Instruct)

---

## 🏆 Highlights

- ✅ Achieved **31.3 F1 score** (Baselines were 21 and 25)
- ✅ Ranked **2nd overall** in the competition
- ✅ Used **sentence chunking**, **hybrid retrieval**, and **LLM-based generation**

---

## 📁 Files

- `notebook.ipynb` – main Kaggle notebook
- `submission.csv` – final output
- `corpus.csv` – input corpus
- `train.csv` – used for local F1 evaluation
- `README.md` – this file

---

## 🚀 Quick Start

```bash
pip install -r requirements.txt
