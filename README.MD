# Financial Fraud Prediction

This repository contains a machine learning project focused on **Financial Fraud Detection**. The goal is to leverage historical transaction data to train a classification model capable of accurately predicting fraudulent activities. The project is implemented within a Jupyter Notebook, providing a step-by-step analysis and model development process.

## Project Contents

* `financial-fraud-prediction.ipynb`: The primary Jupyter Notebook containing the full code for data loading, exploratory data analysis (EDA), feature engineering, model training (likely including techniques for handling **imbalanced data**), and performance evaluation.

## Methodology Highlights

The workflow within the notebook typically covers:

1.  **Data Acquisition and Cleaning**: Initial inspection and preparation of the transaction dataset (often a synthetic one like PaySim).
2.  **Feature Engineering**: Transforming raw features and creating new ones to improve model discrimination.
3.  **Handling Imbalance**: Implementing techniques like **SMOTE** or **undersampling/oversampling** to address the severe class imbalance inherent in fraud data.
4.  **Model Selection and Training**: Training several machine learning classifiers (e.g., Logistic Regression, Decision Trees, or an **Ensemble** approach like a Voting Classifier).
5.  **Evaluation**: Focusing on metrics critical for fraud detection, particularly **Recall** (to minimize undetected fraud) and the **Area Under the ROC Curve (AUC)**.

## Key Dependencies

The following Python libraries are required to run the notebook:
* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `seaborn`

---

## 🤝 Acknowledgement and Credit

I would like to extend my sincere gratitude and deep appreciation to **Muhammad Khayruhanif**. His foundational code and extensive efforts were instrumental in initiating and structuring