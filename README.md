📘 Banking Default Loan – Quant Risk Modelling
🧠 Overview

Banking Default Loan is a predictive analytics project developed as part of the J.P. Morgan Chase & Co Quantitative Research Virtual Experience.
This notebook explores credit-risk modelling — estimating the probability of loan default using statistical and machine-learning techniques on anonymized customer data.

The project simulates a real-world quant environment where mathematical reasoning meets financial data to optimize lending strategies and reduce portfolio risk.

💹 Objective

To build a data-driven model that predicts whether a borrower will default on a loan, based on financial attributes and behavioral patterns.
The outcome helps banks price risk more efficiently and improve capital allocation across portfolios.

📊 Key Components

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Feature engineering (credit history, income-to-loan ratio, etc.)

Logistic Regression & Random Forest modelling

Model performance evaluation using ROC-AUC and Confusion Matrix

Profit/Loss sensitivity analysis

🧮 Core Formulae
🧠 Logistic Regression Formula

The probability that a customer will default on a loan is given by:

### 🧮 Logistic Regression Formula

The probability that a customer will **default on a loan** is calculated as:

$$
P(Y = 1 | X) = \frac{1}{1 + e^{-(\beta_0 + \beta_1 X_1 + \beta_2 X_2 + \dots + \beta_n X_n)}}
$$

Where:  
- \( Y = 1 \) → Customer defaults on loan  
- \( Y = 0 \) → Customer does not default  
- \( \beta_0, \beta_1, \dots, \beta_n \) → Model coefficients  
- \( X_1, X_2, \dots, X_n \) → Feature variables (like income, credit score, etc.)

→ Feature variables (like income, credit score, etc.)

⚖️ Credit Risk Metrics

Expected Loss (EL) is calculated as:

EL=PD×LGD×EAD

Where:

PD → Probability of Default

LGD → Loss Given Default

EAD → Exposure at Default

These parameters together quantify how a bank measures and manages expected credit loss within its loan portfolio.

🧰 Tech Stack

Language: Python
Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, Joblib
Environment: Jupyter Notebook
Version Control: Git & GitHub

⚙️ Setup

Clone the repository and install dependencies:

git clone https://github.com/HarishxWEB3/Banking_Default_Loan.git
cd Banking_Default_Loan
pip install -r requirements.txt


Launch the notebook:

jupyter notebook Banking_default_loan.ipynb

📈 Insights

Identified key drivers influencing loan default probability

Compared multiple ML models for predictive accuracy

Visualized risk distribution across borrower segments

Simulated expected loss under varying macroeconomic scenarios

💡 Future Enhancements

Integrate Bayesian credit-risk models

Incorporate macroeconomic indicators for stress testing

Deploy as an interactive risk dashboard with real-time analytics

👨‍💻 Author

Harish R
Aspiring Quant Researcher | AI & Finance Enthusiast

🌐 GitHub Profile

🧾 License

This project is licensed under the MIT License — you’re free to use, modify, and distribute it with attribution.
This project is open-source and available under the MIT License.

=======
# Banking_default_Loan
a8fbd0633ad7c87c0b38607b7109aba38fb3a58c
