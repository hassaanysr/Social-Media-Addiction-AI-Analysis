# Social-Media-Addiction-AI-Analysis
AI Course Final Project analyzing the impact of social media addiction on student mental health using XGBoost.

# AI-Assisted Analysis of Social Media Addiction Prediction Models 🧠📱

**Course:** Artificial Intelligence (Fall 2025)
**Group Members:**
* Hassaan Yasir [BSMT22028]
* Aimen Naseem [BSMT22046]
* Masooma Altaf [BSMT22093]
**Supervisor:** Dr. Zulkifl Hasan

---

## 📌 Project Overview
This project aims to replicate and enhance a benchmark study on **Social Media Addiction (SMA)**. Using a dataset of 705 students, we utilized Machine Learning to predict mental health outcomes based on usage patterns, sleep deprivation, and addiction scores.

## 🚀 Key Results
We compared a traditional **Linear Regression** baseline against an AI-enhanced **Tuned XGBoost** model.

| Model | Accuracy ($R^2$) | Error (RMSE) | Performance |
| :--- | :--- | :--- | :--- |
| **Linear Regression** | 89.4% | 0.1268 | Baseline |
| **Tuned XGBoost** | **96.5%** | **0.0451** | **Best** |

## 🛠️ Methodology
1.  **Preprocessing:** Label Encoding & Standard Scaling.
2.  **Benchmark:** Reimplemented the study by Zewude et al. (2025).
3.  **Enhancement:** Applied **Ensemble Learning** (Random Forest & XGBoost) to capture non-linear behavioral patterns.
4.  **Tuning:** Optimized Hyperparameters using `GridSearchCV`.

## 📂 Files Included
* `AI_Project.ipynb`: The complete Python code (Google Colab).
* `Students Social Media Addiction.csv`: The dataset used for training and testing.

## 📊 Key Findings
* **Addiction Score** is the #1 predictor of mental health decline.
* AI models reduced the prediction error by **60%** compared to traditional statistics.
* This project supports **UN SDG Goal 3: Good Health and Well-being**.

---
*Created for the Information Technology University (ITU) AI Course.*
