# 🏦 Customer Churn Prediction — Churn Modelling Dataset

## 📌 Objective
Predict which bank customers are likely to leave (churn) using machine learning and interactive data analysis.  
This project is Task 2 of my Data Science Internship at DevelopersHub Corporation.

---

## 📊 Dataset
- **Churn Modelling Dataset** ([Kaggle link](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling))
- 10,000 records, 14 features
- Target: `Exited` (1 = Churned, 0 = Stayed)

---

## 🔧 Approach

1. **Data Cleaning:** Removed irrelevant columns, handled categorical variables.
2. **Feature Engineering:** Encoded categorical features (Geography, Gender).
3. **Exploratory Data Analysis (EDA):** Interactive visualizations with Plotly for demographics, financials, and activity.
4. **Feature Scaling:** Standardized numerical features.
5. **Model Training:** Compared Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.
6. **Evaluation:** Used accuracy, F1, precision, recall, ROC curve, and confusion matrix.
7. **Feature Importance:** Identified key drivers of churn.
8. **Business Insights:** Actionable recommendations for customer retention.

---

## 📈 Results

| Model                | Accuracy | F1 Score | AUC   |
|----------------------|----------|----------|-------|
| Logistic Regression  | ~81%     | ~0.45    | ~0.77 |
| Decision Tree        | ~79%     | ~0.50    | ~0.72 |
| Random Forest        | ~86%     | ~0.58    | ~0.86 |
| Gradient Boosting    | ~86%     | ~0.60    | ~0.87 |

- **Best Model:** Gradient Boosting (~86% accuracy, ~0.60 F1)

---

## 💡 Key Insights

- **Age** is the strongest predictor — older customers churn more.
- **Geography:** German customers have 2x higher churn.
- **Inactive members** and those with 3+ products are at highest risk.
- **Credit score and salary** have minimal impact on churn.

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- Plotly (interactive EDA & model evaluation)
- Scikit-learn

---

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/churn-modelling.git
    cd churn-modelling
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and run the notebook:
    - `customer_churn_prediction.ipynb` 

---

## 📂 Project Structure

```
├── README.md
├── requirements.txt
├── customer_churn_prediction.ipynb   # Main notebook
└── data/
    └── Churn_Modelling.csv           # Dataset (add or download from Kaggle)
```

---

## 📬 Contact

For questions or feedback, please [open an issue](https://github.com/yourusername/churn-modelling/issues) or connect on 
[LinkedIn](www.linkedin.com/in/kinza-eman-747059361).

---

*Completed as part of Data Science Internship at Developers Hub Corporation).

