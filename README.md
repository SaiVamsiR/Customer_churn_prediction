# Customer Churn Prediction Using Logistic Regression

## Overview
This repository contains a machine learning project that predicts customer churn using **logistic regression**. Churn prediction helps businesses identify at-risk customers and take proactive measures to retain them.

## Dataset
The dataset used for this project includes customer information such as:
- **Demographic data** (age, gender, location)
- **Account details** (tenure, subscription plan)
- **Usage behavior** (monthly charges, total spend)
- **Customer support interaction** (number of complaints, resolution time)

## Dependencies
To run this project, install the required dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Model Training
The logistic regression model is built using **scikit-learn** and follows these key steps:
1. **Data Preprocessing** – Handling missing values, encoding categorical variables, and scaling numerical features.
2. **Feature Selection** – Selecting relevant features for better prediction accuracy.
3. **Model Training** – Using logistic regression to classify customers as likely to churn or not.
4. **Evaluation Metrics** – Assessing performance using accuracy, precision, recall, and F1-score.



## Results
The trained model provides predictions with insights into the most influential factors affecting churn. The output includes:
- **Confusion Matrix**
- **ROC Curve**
- **Feature Importance Analysis**

## Future Improvements
Potential enhancements include:
- Hyperparameter tuning for optimization
- Exploring alternative classification algorithms
- Implementing real-time customer monitoring

## Contributing
Feel free to fork the repository and submit pull requests with improvements.

## License
This project is licensed under the MIT License.
