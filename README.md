# Azure-Project-Churn-Analysis
Churn Analysis for Telecom Company through Python Notebook and Azure Piepline, creating a comparison of the performance of Machine Learning Models using the two environments
markdown
#  Customer Churn Prediction Model

Predicted customer churn with 52% recall using Logistic Regression, RandomForest, Support Vector Machines, identifying key retention drivers for a telecom dataset.

## Key Results & Business Impact
- **Model Performance:** Achieved **0.78 AUC** and **61% F1-Score** using Logistic Regression in Azure, outperforming the Random Forest Classifier in Python envirment by 3%.
- **Top Insights:** Identified that month-to-month contracts and high monthly charges were the strongest predictors of churn.
- **Actionable Recommendation:** Targeting the top 20% highest-risk customers with retention offers could save customers from leaving the company.

## Visual Highlights
<img width="884" height="384" alt="AzureModelwinner" src="https://github.com/user-attachments/assets/9518abdc-3aef-48f0-8a46-0b35e800dbbf" />





## Dataset & Methodology
- **Data Source:** [Telco customer churn: IBM dataset]https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset?resource=download — 7043 rows, 33 features (target variable is Churn Value, imabalnced data with 1869 Churn records available).
- **Data Preprocessing:** Handled missing values via median imputation, applied one-hot encoding to categorical features, and used stratificat_on to preserve imabalnce.
- **Models Evaluated:** Logistic Regression (Baseline), Random Forest, Support Vector Machines (SVM).


## Project Structure
```text
├── data/               # Raw dataset from Kaggle
├── notebooks/          # Exploratory data analysis (EDA) and experimentation
├── src/                # Clean, modular Python scripts for preprocessing and training
├── models/             # Saved model artifacts
└── README.md
```

## Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, RandomForest (Ensemble), Support Vector Machines, Matplotlib/Seaborn





## Contact
- **Sobia Pervaiz** — [LinkedIn Profile]https://www.linkedin.com/in/sobia-pervaiz-071848215/ | 
