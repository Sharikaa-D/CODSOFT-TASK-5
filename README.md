# CODSOFT-TASK-5

COMPANY : CODSOFT

NAME : SHARIKAA.D

ROLE : DATA SCIENCE

DURATION : 4 WEEKS

INTERN ID : CS25RY81758

# Credit Card Fraud Detection

This project is a machine learning solution to identify fraudulent credit card transactions. The dataset has a significant class imbalance, so techniques like SMOTE are used to address this issue. A Random Forest classifier is applied to categorize transactions as **fraudulent** or **genuine**.

---

## Dataset

- Dataset used: `creditcard.csv`
- Features include transaction data such as anonymized PCA components, `Amount`, and `Time`.
- Target variable: `Class` (0 = Genuine, 1 = Fraud)

---

## Key Steps

1. **Data Preprocessing**:
   - Normalized the `Amount` column.
   - Dropped irrelevant columns (`Time`, original `Amount`).
   - Handled missing values.

2. **Class Imbalance Handling**:
   - Used **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the dataset.

3. **Model Training**:
   - Used **Random Forest Classifier**.

4. **Model Evaluation**:
   - Evaluated using **Precision**, **Recall**, **F1-Score**, and **Confusion Matrix**.

---

## Model Performance

- The model accurately classified fraudulent transactions.
- SMOTE helped balance the dataset and improve recall for the minority (fraud) class.
- Performance metrics are included in the output.

---

## Libraries Used

- `pandas`, `numpy`
- `scikit-learn`
- `imblearn` (for SMOTE)
- `matplotlib`, `seaborn`

---

## How I Got This

This task was completed as part of my **CodSoft Data Science Internship (Task 5)**. I built the model, addressed class imbalance, and evaluated it using appropriate metrics. The goal was to accurately detect fraudulent transactions while keeping false positives minimal.

---


## Run it Yourself

```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
```

OUTPUT:

