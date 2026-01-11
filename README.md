# 🔐 Network Intrusion Detection

Classical Machine Learning–Based Intrusion Detection System (IDS)

## 📌 Project Overview

This project focuses on **Network Intrusion Detection (IDS)** using structured network traffic data.
The objective is to detect malicious or abnormal network activities by building a robust, interpretable, and well-evaluated machine learning pipeline.

The project follows a **classical ML–oriented workflow**, emphasizing:
- Data integrity and preprocessing correctness
- Careful feature handling
- Fair model comparison
- Clear evaluation and diagnostics

The workflow is designed in a **Kaggle-style, ML Engineer–oriented manner**, where preprocessing and modeling are separated into dedicated notebooks for clarity and reproducibility.

---

## 🎯 Objectives
- Prepare clean and model-ready network traffic features
- Design a reproducible preprocessing pipeline
- Train multiple classical ML models suitable for tabular IDS data
- Evaluate models using proper classification metrics
- Compare models to identify the most effective approach for intrusion detection

---

## 🧠 Problem Formulation
- Task: Intrusion Detection
- Type: Classification (binary or multiclass)
- Input: Structured network traffic features
- Output: Intrusion / attack label
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

---

## 🧪 Models Used
The following classical machine learning models are implemented and compared:

- XGBoost
- CatBoost
- Random Forest
- Multi-Layer Perceptron (MLP)

Each model is evaluated using:
- Classification Report
- Confusion Matrix
- Metric-based comparison table

> Deep learning models are intentionally not used, as classical models are often more effective and efficient for structured IDS data.

---

## 🗂️ Project Pipeline
The project is organized into clear stages, each implemented in a separate notebook:

| Stage | Notebook | Description |
|------:|---------|-------------|
| 1 | `01_preprocessing.ipynb` | Data cleaning, encoding, scaling, and feature preparation |
| 2 | `02_modeling.ipynb` | Model training, evaluation, and comparison |

This separation ensures:
- Cleaner notebooks
- Easier debugging
- Reproducible experiments

---

## 📊 Key Highlights
✅ Structured preprocessing pipeline  
✅ Classical ML models tailored for tabular data  
✅ Fair model comparison under the same data split  
✅ Clear evaluation with confusion matrices & reports  
✅ Simple, readable, and reproducible workflow  

---

## 🛠️ Tech Stack
- Python
- NumPy, Pandas
- Scikit-learn
- XGBoost
- CatBoost
- Matplotlib, Seaborn

---

## 📌 Notes
- Dataset files are not included in this repository
- This project prioritizes **engineering clarity over excessive complexity**
- The workflow can be easily extended with:
  - Feature selection
  - Hyperparameter tuning
  - Ensemble methods

---

## 👤 Author
**Ardiyanto**  
Background: Statistics & Machine Learning
