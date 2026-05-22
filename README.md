[README (2).md](https://github.com/user-attachments/files/28158720/README.2.md)
# 🏎️ Predicting F1 Pit Stops — Kaggle Playground S6E5

![Kaggle](https://img.shields.io/badge/Kaggle-Playground%20S6E5-20BEFF?style=flat&logo=kaggle)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=flat&logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat)

> **Competition:** [Kaggle Playground Series - Season 6, Episode 5](https://www.kaggle.com/competitions/playground-series-s6e5)  
> **Goal:** Predict whether an F1 driver will pit on the next lap  
> **Evaluation Metric:** Area Under the ROC Curve (AUC-ROC)  
> **Deadline:** May 31, 2026

---

## 📌 Problem Overview

This is a **binary classification** problem. Given lap-level telemetry and race data, the model must predict the probability that a Formula 1 driver will make a pit stop on the **next lap**.

- `PitNextLap = 1` → Driver will pit next lap  
- `PitNextLap = 0` → Driver will not pit next lap  

The dataset is synthetically generated from real-world F1 historical data.

---

## 🧰 Tools & Libraries

| Tool | Purpose |
|------|---------|
| `pandas` | Data loading & manipulation |
| `numpy` | Numerical operations |
| `scikit-learn` | Modeling, preprocessing, evaluation |
| `matplotlib` / `seaborn` | EDA & visualizations |

---

## 📁 Project Structure

```
kaggle-f1-pitstop-prediction/
│
├── notebook.ipynb          ← Main working notebook (EDA + Modeling)
├── README.md               ← You are here
└── submissions/            ← Saved submission CSV files
```

---

## 🗺️ Approach & Roadmap

- [x] **Phase 1 — Data Understanding**: Load data, inspect shape, dtypes, missing values
- [ ] **Phase 2 — EDA**: Distributions, correlations, class imbalance analysis
- [ ] **Phase 3 — Feature Engineering**: Encoding, scaling, new features
- [ ] **Phase 4 — Baseline Model**: Logistic Regression
- [ ] **Phase 5 — Improved Models**: Random Forest, other sklearn models
- [ ] **Phase 6 — Submission**: Generate probabilities & submit to Kaggle

---

## 📈 Progress Log

| Day | What I Did |
|-----|-----------|
| Day 1 | Repo setup, data loading, initial exploration |

---

## 📊 Results

| Model | AUC-ROC (CV) | AUC-ROC (LB) |
|-------|-------------|--------------|
| Baseline | — | — |

---

## 💡 Key Learnings

> *(Updated as the project progresses)*

---

## 👤 Author

**Abdallah** — AI Engineering Student @ Cyprus International University  
🔗 [GitHub Profile](https://github.com/)

