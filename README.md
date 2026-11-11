# Diabetes Risk Prediction — Machine Learning Pipeline 🩺

An end-to-end supervised and unsupervised machine learning pipeline predicting diabetes onset using clinical diagnostic data (100,000 patient records).

---

## 📋 Project Overview
This project builds, benchmarks, and evaluates multiple machine learning classifiers to predict diabetes risk based on medical diagnostics. It explores feature scaling, handling class imbalance, exploratory data analysis (EDA), and deep classification performance metrics.

---

## 🤖 Models & Benchmarks

| Model | Architecture / Type | Accuracy | AUC Score |
|---|---|---|---|
| **Decision Tree** | Supervised Classifier | **97.0%** | **0.971** |
| **Neural Network** | Multilayer Perceptron (MLP: 128 → 64 → 32) | **96.9%** | **0.972** |
| **Logistic Regression** | Linear Probabilistic Classifier | **95.9%** | **0.956** |
| **K-Means Clustering** | Unsupervised Pattern Discovery (k=2) | — | Cluster Analysis |

---

## 📁 Repository Structure
| File / Directory | Description |
|---|---|
| `CSE422_Diabetes_Project_Final.ipynb` | Comprehensive ML pipeline notebook: EDA, preprocessing, model training, ROC-AUC curves |
| `CSE422_Diabetes_Project.ipynb` | Supervised model benchmarking & hyperparameter tuning |
| `diabetes_dataset.csv` | Clinical dataset (100,000 records, 9 diagnostic features) |

---

## 📊 Dataset Features
The dataset contains 100,000 records with diagnostic indicators:
* Demographic: `gender`, `age`
* Medical History: `hypertension`, `heart_disease`, `smoking_history`
* Clinical Biomarkers: `bmi`, `HbA1c_level`, `blood_glucose_level`
* **Target Label:** `diabetes` (0: Non-Diabetic, 1: Diabetic)

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/zhnverse/diabetes-prediction-ml.git
   cd diabetes-prediction-ml
   ```

2. **Install requirements:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook CSE422_Diabetes_Project_Final.ipynb
   ```
