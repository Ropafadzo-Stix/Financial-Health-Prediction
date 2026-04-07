# 🏦 SME Financial Health Index - Zindi Challenge

> Predicting the financial health of small and medium-sized enterprises across Southern Africa using machine learning.

---

## 📌 Overview

This repository contains my work for the [Zindi SME Financial Health Index Challenge](https://zindi.africa). The goal is to build a machine learning model that predicts a **Financial Health Index (FHI)** for SMEs — classifying businesses as having **Low**, **Medium**, or **High** financial health.

The FHI is a composite measure built across four key dimensions:
- 💰 Savings and assets
- 📉 Debt and repayment ability
- 🛡️ Resilience to shocks
- 🏦 Access to credit and financial services

The dataset covers SMEs from four Southern African countries: **Eswatini, Lesotho, Zimbabwe, and Malawi**, and includes socio-economic and business features such as traded commodities, export/import activity, firm size, demographics, and location.

---

## 🗂️ Repository Structure

```
├── data/
│   ├── raw/                  # Original competition data (not tracked in git)
│   └── processed/            # Cleaned and feature-engineered datasets (to be added)
├── notebooks/
│   ├── Starter Notebook.ipynb          # Notebook provided by Zindi
│   ├── Financial health dataipynb          # Contains the complete project i.e., EDA, Processing and Modelling.  
│   └── 03_modelling.ipynb
├── src/
│   ├── features.py           # Feature engineering logic
│   ├── train.py              # Model training scripts
│   └── predict.py            # Inference scripts
├── models/                   # Saved model artifacts
└── README.md
```

> ⚠️ **Note:** This structure is a work in progress and will evolve as the project develops.

---

---

## 🚀 Approach

*This section will be updated as the project progresses.*

**Current status:** 🟡 In progress

Planned steps:
- [ ] Exploratory data analysis (EDA)
- [ ] Data cleaning and preprocessing
- [ ] Feature engineering
- [ ] Baseline model
- [ ] Model tuning and ensembling
- [ ] Final submission

---

## 📊 Results

| Model | CV Score | 
|-------|----------|
| *TBD* | — | — |

*Results table will be updated as experiments are run.*

---

## 🧠 Key Insights

*To be added as the project progresses.*

---

## 📦 Dependencies

See `requirements.txt`. Key libraries used:
- pandas, numpy
- scikit-learn
- xgboost / lightgbm
- matplotlib, seaborn

---

## 📄 License

This project is for competition and educational purposes. Data is sourced from Zindi and may not be redistributed.

---

## 🙏 Acknowledgements

- [Zindi Africa](https://zindi.africa) for hosting the challenge
- The researchers and organisations behind the SME survey data across Southern Africa
