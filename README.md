# 🏡 Predicting Housing Prices – Supervised ML Workflow (HIT)

<em>Machine learning pipeline for predicting median house values using the Housing dataset</em>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/lankdaniel14/Housing_Prices_ML_Project_HIT?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
  <img src="https://img.shields.io/github/languages/top/lankdaniel14/Housing_Prices_ML_Project_HIT?style=flat&color=0080ff" alt="repo-top-language">
  <img src="https://img.shields.io/github/languages/count/lankdaniel14/Housing_Prices_ML_Project_HIT?style=flat&color=0080ff" alt="repo-language-count">
</p>

![House Image](House%20image.jpg)


---

## 📌 Table of Contents

- [📖 Project Overview](#-project-overview)
- [⚙️ Features](#️-features)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
  - [🔧 Prerequisites](#-prerequisites)
  - [📦 Installation](#-installation)
  - [▶️ Usage](#️-usage)
- [📊 Model Summary](#-model-summary)
- [🧠 Key Learnings](#-key-learnings)
- [🤖 AI Use Disclaimer](#-ai-use-disclaimer)
- [📬 Contact](#-contact)

---

## 📖 Project Overview

This project was developed as part of an academic assignment in the Supervised Learning course at HIT.  
It demonstrates how to train and evaluate multiple regression models to predict housing prices using the **Housing dataset**.

The project follows a full machine learning pipeline:
- Data loading and exploration (EDA)
- Feature preprocessing
- Model selection via `GridSearchCV`
- Final training
- Prediction and performance evaluation

---

## ⚙️ Features

| Component         | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| 🔍 **EDA**         | Visual exploration of income, rooms, age vs price relationships             |
| 🧱 **Models Used** | Linear Regression, Decision Tree, and MLP Regressor                         |
| 🔧 **Tuning**       | GridSearchCV with 5-fold cross-validation                                  |
| 🧪 **Evaluation**   | `R²` score computed for model comparison on test set                       |
| 📈 **Visualization**| Boxplots, scatter plots, and feature importance charts                     |
| 📘 **Documentation**| Inline markdown explanations throughout the Jupyter notebook               |

---

## 📁 Project Structure

```text
HOUSING_PRICES_ML_PROJECT_HIT/
├── Assignment2_supervised_learning_flow.ipynb     # Main notebook with full ML pipeline
├── housing_train.csv                              # Training dataset
├── housing_test.csv                               # Test dataset
├── house_pricing_description.txt                  # Description of the dataset
└── README.md                                      # This documentation file
```

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.8+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn

### 📦 Installation

```bash
cd "Name_A_Folder"
git clone https://github.com/lankdaniel14/Housing_Prices_ML_Project_HIT

```

### ▶️ Usage

```bash
jupyter notebook Assignment2_supervised_learning_flow.ipynb
```

Follow the notebook step-by-step to run data exploration, training, and prediction.

---

## 📊 Model Summary

| Model               | CV Best R² | Test R² | Notes                              |
|---------------------|------------|---------|------------------------------------|
| Linear Regression   | ~0.60      | ~0.60   | Simple baseline                     |
| Decision Tree       | ~0.68      | ~0.72   | Captures non-linear relationships  |
| MLP Regressor (ANN) | ~0.79      | ~0.81   | Best overall performance            |

---

## 🧠 Key Learnings

- GridSearchCV makes model selection more systematic and effective.
- The MLP model outperformed others but was not sensitive to additional epochs beyond a point.
- Feature scaling (StandardScaler) was crucial for MLP and Linear Regression.
- Visual analysis (EDA) revealed clear patterns between income and price.

---

## 🤖 AI Use Disclaimer

Some parts of the project were developed using guidance from ChatGPT 4.0.  
The AI was used to support learning, not to replace critical thinking, and all implementations were reviewed and understood.

---

## 📬 Contact

Created by **Daniel Lankry**  
As part of the HIT course: *Supervised Learning – 2024/2025*

[🔗 GitHub Profile](https://github.com/lankdaniel14)
