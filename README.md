# CodeAlpha_HeartDiseasePrediction

## 📌 Project Overview
This project was developed during my **Machine Learning Internship at CodeAlpha**. The goal is to apply classification techniques to a structured medical dataset to predict the likelihood of heart disease in patients.

## 🎯 Objective
To build an accurate diagnostic tool using patient symptoms, age, and clinical test results (like cholesterol and heart rate) to predict heart disease presence.

## 🛠️ Tech Stack & Tools
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib
*   **Platform:** Kaggle / Jupyter Notebook

## 🚀 Machine Learning Workflow
1.  **Data Loading:** Utilized the **Heart Disease UCI** dataset.
2.  **Exploratory Data Analysis (EDA):** Analyzed correlations between medical features (chest pain, heart rate) and disease presence.
3.  **Data Preprocessing:** Confirmed no missing values and utilized numerical encoding.
4.  **Train-Test Split:** Used an 80/20 split **before scaling** to prevent data leakage.
5.  **Feature Scaling:** Applied `StandardScaler` to ensure all medical metrics (e.g., Blood Pressure vs. Age) are on a comparable scale[cite: 1].
6.  **Model Implementation:** Trained a **Random Forest Classifier**.

## 📊 Evaluation Results
Following the internship guidelines, the model was assessed using the following key metrics:

| Metric | Score |
| :--- | :--- |
| **Accuracy** | 84% |
| **ROC-AUC Score** | 0.92 |
| **Precision** | 0.84 |
| **Recall** | 0.84 |

### Insights
With an **ROC-AUC of 0.92**, the model demonstrates an excellent ability to distinguish between patients with and without heart disease, making it a reliable predictive model.

## 📂 Repository Structure
*   `Disease_Prediction.ipynb`: Complete source code and analysis.
*   `heart.csv`: Dataset used for training and testing.
*   `README.md`: Project documentation.

## 🔗 Internship Context
*   **Task 4:** Disease Prediction from Medical Data.
*   **Company:** CodeAlpha.
*   **Status:** Task Completed ✅
