# Arabic Dialect Classification (Senior Project)

A **final-year group project** specializing in **Arabic Natural Language Processing (NLP)**.  
The project focuses on classifying **Arabic dialects** using a combination of **classical machine learning** and **transformer-based deep learning models**.  

> 📘 *Developed as a team project for the Diploma in Data Science at the University of Jeddah (2025–2026).*

---

## 👥 Team Members
| Name | Student ID |
|------|-------------|
| **Shahad Almutairi** | 2316095 |
| **Ruba Alfageeh** | 2315366 |
| **Tala Melaih** | 2317013 |
| **Safaa Alsufyani** | 2315828 |

**Supervisor:** Dr. Roshayu Mohammed  
**Program:** Applied College – Diploma in Data Science  

---

## 🎯 Project Overview
Arabic dialects differ widely between regions (Najdi, Hijazi, Khaliji, Egyptian, Levantine, etc.), which makes automatic understanding difficult for NLP systems.  
This project investigates and compares different modeling techniques to automatically detect the dialect used in Arabic text.

### Objectives
- Build an NLP system that recognizes Arabic dialects.
- Compare **Logistic Regression**, **AraBERT**, and **MARBERT** models.
- Analyze the impact of preprocessing and class imbalance on model performance.
- Contribute to Arabic NLP research through a clear performance comparison.

---

## 🧠 Models Used
| Model | Description |
|--------|--------------|
| **Logistic Regression (TF‑IDF)** | Baseline classical model |
| **AraBERT** | Transformer model trained on Modern Standard Arabic and news data |
| **MARBERT** | Transformer trained on dialectal Arabic tweets and social text |

---

## 📊 Dataset
**SADA 2022 Dataset** (Saudi Data and AI Authority).  
Used the following features:
- `GroundTruthText` → Arabic text input  
- `SpeakerDialect` → dialect label  

---

## 🧹 Preprocessing Pipeline
- Text normalization and diacritics removal  
- Noise removal (emojis, punctuation, English characters)  
- Stop‑word removal  
- Tokenization  
- Character repetition handling  

---

## ⚙️ Tools & Technologies
Python | Google Colab | Scikit‑learn | PyTorch | Hugging Face Transformers | Pandas | NLTK | Matplotlib | Seaborn  

---

## 📈 Results

| Model | Accuracy | Macro F1 | Macro Recall |
|--------|-----------|-----------|---------------|
| **AraBERT** | 55.7 % | 0.249 | 0.238 |
| **MARBERT** | **56.7 %** | **0.258** | **0.246** |
| Logistic Regression (weighted) | 43 % | 0.20 | 0.33 |

---

## 🔍 Key Findings
- **MARBERT** achieved the best overall performance.  
- **AraBERT** performed strongly on formal Arabic.  
- **Logistic Regression** proved valuable for balanced, interpretable baselines.  
- **Class imbalance** was a major modeling challenge.

---

## 🧩 My Contribution – Shahad Almutairi

Within the group project, my main role focused on **data processing, analysis, and baseline model development**.  
I contributed to both the technical implementation and the analytical evaluation of model performance.

### Responsibilities
- **Data Preprocessing & Cleaning:**  
  Designed and implemented the Arabic text preprocessing pipeline (diacritics and punctuation removal, normalization, stop‑word filtering, and tokenization) using Python & NLTK.

- **Exploratory Data Analysis (EDA):**  
  Performed data visualization using **Matplotlib** and **Seaborn** to analyze dialect distribution, detect imbalance, and highlight frequent linguistic patterns.

- **Model Building:**  
  Developed and fine‑tuned the **Logistic Regression baseline** with **TF‑IDF** features, applied class‑weight balancing, and evaluated model accuracy, precision, recall, and F1‑score.

- **Documentation & Results Analysis:**  
  Authored portions of the final report, including methodology and results sections, and created performance charts comparing AraBERT, MARBERT, and Logistic Regression.

### Impact
My contributions helped ensure clean, high‑quality text data and provided a strong quantitative baseline that guided deeper model experiments with AraBERT and MARBERT.

---

## 🚀 Future Work
- Data augmentation for under‑represented dialects  
- Audio‑text multimodal learning  
- Hyperparameter tuning and cross‑validation  
- Ensemble methods  
- Explainability using SHAP or LIME  

---

## 📁 Repository Structure
```bash
arabic-dialect-classification/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   ├── preprocessing_and_AraBERT.ipynb
│   ├── MARBERT.ipynb
│   └── LogisticRegression.ipynb
├── reports/
│   └── final_report.pdf
└── images/
```

---

## 🏆 Acknowledgment
Special thanks to **Dr. Roshayu Mohammed** for supervision and guidance throughout the project.

---

## 📎 Reference Links
- [SADA Dataset (Kaggle)](https://www.kaggle.com/datasets/sdaiancai/sada2022/data)  
- [AraBERT Paper – LREC 2020](https://arxiv.org/abs/2003.00104)  
- [MARBERT Paper – NAACL 2021](https://arxiv.org/abs/2101.01785)

---

📍 *University of Jeddah – Applied College – Diploma in Data Science ( 2025 / 2026 )*

