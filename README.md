# 📉 Customer Churn Prediction using Logistic Regression

This project applies a **Logistic Regression** model to predict **customer churn** based on behavioral, demographic, and account-related data. It includes data cleaning, preprocessing, exploratory data analysis, model training, and evaluation.

---

## 🧠 Objective

The goal is to build a predictive model that can help companies **identify customers likely to churn** so they can take preventative action.

---

## 📁 Repository Structure

customer-churn-logreg/
│
├── data/
│ └── customer_churn.csv # Raw input dataset
│
├── notebooks/
│ └── churn_eda_modeling.ipynb # Data analysis & model building
│
├── model/
│ └── churn_model.pkl # Saved trained logistic model
│
├── utils/
│ └── preprocess.py # Data preprocessing functions
│
├── train_model.py # Script to train logistic model
├── requirements.txt # Python package requirements
└── README.md # Project documentation

markdown
Copy
Edit

---

## 🧾 Dataset Details

- **Source:** Telco Customer Churn Dataset (e.g. from Kaggle)
- **Rows:** ~7,000 records
- **Target:** `Churn` (Yes = customer left, No = customer stayed)
- **Features:**
  - Demographics: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - Account info: `tenure`, `Contract`, `MonthlyCharges`, `TotalCharges`
  - Services: `PhoneService`, `InternetService`, `TechSupport`, etc.

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/customer-churn-logreg.git
cd customer-churn-logreg
2. Set Up Virtual Environment (Optional but Recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate         # Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
⚙️ Training the Model
Run the model training script:

bash
Copy
Edit
python train_model.py
This will:

Preprocess the data

Train a logistic regression model

Save the trained model as model/churn_model.pkl

📈 Model Evaluation
After training, the following metrics are calculated:

Accuracy

Confusion Matrix

Precision / Recall / F1 Score

ROC-AUC Curve

🔍 Highlights
End-to-end pipeline for binary classification

Clean preprocessing and modular code

Logistic Regression with hyperparameter tuning

Easy to extend with other ML models (e.g., Random Forest, XGBoost)

📊 Tools & Libraries Used
Python 3.9+

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Joblib (for model persistence)

🚀 Future Enhancements
Try other ML models like Random Forest, XGBoost

Feature selection and regularization

Use SMOTE to handle class imbalance

Add unit tests and logging
