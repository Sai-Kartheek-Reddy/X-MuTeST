# X-MuTeST: A Multilingual Benchmark for Explainable Hate Speech Detection and A Novel LLM-consulted Explanation Framework

**Accepted at AAAI 2026 (AI for Social Impact Track)** - *CORE A\* Conference*
Preprint available soon...
---

# About X-MuTeST

**_X-MuTeST_** (e**X**plainable **M**ultilingual ha**T**e **S**peech de**T**ection) is a multilingual benchmark and framework designed for explainable hate speech detection across Telugu, Hindi, and English.

It introduces token-level human rationales and a two-stage explainability-guided model training pipeline, integrating insights from LLMs and n-gram-based attention mechanisms to improve both classification and interpretability in under-resourced languages.

## 🚀 Core Contributions

- **Multilingual Explainable Benchmark**  
  - One of the first works to provide **token-level human rationales** for hate speech detection in **Indic languages**, including **Telugu (first of its kind)** and **Hindi (limited prior work)**, along with **English**.
  - Covers over 6K Hindi, 4.5K Telugu, and 6.3K English samples, each annotated by three native experts.

- **Two-Stage Explainability Framework**  
  - **Stage 1:** Guides model attention using human-provided rationales.  
  - **Stage 2:** Refines attention using n-gram-based explainability scores.

- **LLM-Consulted Explanations**  
  - Combines model-driven rationales with LLM-generated explanations (via LLaMA-3.1) for context-aware and faithful interpretability.

- **Explainability-Centric Evaluation**  
  - Evaluates both model accuracy and interpretability using **Plausibility** (Token-F1, IOU-F1) and **Faithfulness** (Comprehensiveness, Sufficiency).

- **Multilingual and Cross-Lingual Focus**  
  - Bridges the explainability gap for **under-resourced Indic languages**, highlighting cultural and linguistic nuances often missed by monolingual models.



# Overview of LLM-consulted Explanation Framework

<img src=https://github.com/Sai-Kartheek-Reddy/X-MuTeST/blob/main/X-MuTeST.png width="1000" />


