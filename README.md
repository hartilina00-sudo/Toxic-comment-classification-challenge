# 🧹 Toxic Comment Classification Challenge

## Overview
Multi-label text classification system to detect and categorize toxic comments online.
Based on the **Kaggle Jigsaw Toxic Comment Classification Challenge**.

**Team:** Ikram Oialili, Lina Harti, Ismail Ibenouazi, Aymane Aboulhouda, Aya Ait Kassi  
**Supervisor:** Hakim Hafidi  
**Course:** Integrated Machine Learning Project — 2026/2027

---

##  Objective
Predict the probability of a comment belonging to one or more of 6 toxicity classes:
`toxic` · `severe_toxic` · `obscene` · `threat` · `insult` · `identity_hate`

**Evaluation Metric:** F1-score (micro-average)

---

##  Models Used
| Model | F1-score (micro) | Training Time |
|---|---|---|
|  Logistic Regression | **0.84** | ~2 min |
| BERT | 0.76 | ~45 min |
| SVM (LinearSVC) | 0.70 | ~8 min |

**Winner: Logistic Regression** — Best balance of performance, speed, and interpretability.

---

 Tech Stack
- **Language:** Python
- **ML:** scikit-learn, Transformers (HuggingFace)
- **NLP:** TF-IDF Vectorization, BERT Tokenization
- **Platform:** Kaggle

---

 Key Results
- Logistic Regression achieved **91.92% accuracy**
- BERT shows high potential but limited by computational resources
- Main challenge: extreme class imbalance ("threat" is 32x rarer than "toxic")

---

##  How to Run
Open the notebook directly on Kaggle or run locally:
```bash
jupyter notebook notebook4ba66695e8.ipynb
```
