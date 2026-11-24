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
- **Data Source:** [Dataset Name](link-to-dataset) — X rows, Y features (describe target variable and class balance).
- **Data Preprocessing:** Handled missing values via median imputation, applied one-hot encoding to categorical features, and used SMOTE to address class imbalance.
- **Models Evaluated:** Logistic Regression (Baseline), Random Forest, XGBoost, LightGBM.
- **Validation Strategy:** 5-fold stratified cross-validation tuned with Optuna.

## Project Structure
```text
├── data/               # Raw and processed datasets (or instructions to download)
├── notebooks/          # Exploratory data analysis (EDA) and experimentation
├── src/                # Clean, modular Python scripts for preprocessing and training
├── models/             # Saved model artifacts
├── requirements.txt    # Python dependencies
└── README.md
```

## Tech Stack
- **Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Matplotlib/Seaborn

## How to Reproduce
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd your-repo-name
   ```
2. **Create a virtual environment and install dependencies:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. **Run the pipeline:**
   ```bash
   python src/train.py
   ```

## Future Improvements
- Deploy the model as a REST API using FastAPI and Docker.
- Add data drift monitoring for production readiness.

## Contact
- **Your Name** — [LinkedIn Profile](https://linkedin.com) | [Portfolio Website]
