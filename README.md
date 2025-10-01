# Information Retrieval Models

This repository contains my contribution to a group research project for 
**Machine Learning for Natural Language Processing (IFN647, QUT, 2025)**.

🏆 Team Project – Group 8: *BM25IR (Steve Ryenchindorj)
📌 My contribution: **Okapi BM25-based Information Retrieval Model** (BM25IR)

---

## 📌 Project Overview
We investigated three information retrieval models for ranking documents:
- **BM25IR** (Okapi BM25) – frequency-based ranking model
- **LMRM** (Language Model with Jelinek-Mercer smoothing)
- **PRRM** (Pseudo-Relevance Ranking Model)

The models were tested on subsets of the **RCV1 dataset (Reuters Corpus)**, across 50 queries and document sets.

---

## 🔬 My Contribution
- Implemented the **BM25IR model** in Python (`BM25UPDATED.ipynb`).
- Designed scoring and ranking pipeline for queries across all datasets.
- Conducted evaluation using MAP, Precision@12, and DCG12.
- Contributed to the final poster by editing and verification.

---

## 📊 Evaluation
- BM25IR achieved comparable performance to LMRM and PRRM.
- MAP and Precision@12 results showed consistent early ranking effectiveness.
- Paired t-tests confirmed **no statistically significant difference** between models (p > 0.05).

---

## 📂 Repository Structure
- `notebooks/` → BM25IR implementation (Python / Jupyter)
- `docs/` → Project poster (PDF export)

---

## 🚀 Tech Stack
- Python
- scikit-learn, NumPy, pandas, matplotlib
- Jupyter Notebooks

---

## 📖 Note
- This repository showcases **my personal contribution** (BM25IR) to the group project.
- The full project also included LMRM and PRRM models, implemented by teammates.
- Dataset (RCV1) is **not included** due to licensing restrictions.
