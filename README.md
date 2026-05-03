# CSE422 Diabetes Prediction — ML Project

A machine learning project for **CSE422 Lab** using the **Diabetes Dataset** (100,000 records).

## 📋 Project Overview
Predicts whether a patient has diabetes based on clinical features using supervised and unsupervised learning.

## 📁 Files
| File | Description |
|---|---|
| `CSE422_Diabetes_Project_Final.ipynb` | **Main project notebook** (submit this) |
| `CSE422_Diabetes_Project.ipynb` | Extended version (4 supervised models) |
| `diabetes_dataset.csv` | Dataset (100,000 rows, 9 columns) |
| `project_guideline.md` | Project requirements |

## 🤖 Models Used
| Model | Type |
|---|---|
| Decision Tree | Supervised |
| Logistic Regression | Supervised |
| Neural Network (MLP 128→64→32) | Supervised (Mandatory) |
| KMeans Clustering (k=2) | Unsupervised |

## 📊 Results
| Model | Accuracy | AUC |
|---|---|---|
| Decision Tree | 97.0% | 0.971 |
| Logistic Regression | 95.9% | 0.956 |
| Neural Network | 96.9% | 0.972 |

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone <your-repo-url>
   cd CSE422
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook CSE422_Diabetes_Project_Final.ipynb
   ```
   Or upload to **Google Colab** and upload `diabetes_dataset.csv` via the Files panel.

## 📦 Dataset
The dataset contains 100,000 patient records with features:
`gender`, `age`, `hypertension`, `heart_disease`, `smoking_history`, `bmi`, `HbA1c_level`, `blood_glucose_level` → target: `diabetes`
