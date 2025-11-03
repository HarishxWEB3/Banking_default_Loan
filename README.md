<<<<<<< HEAD
📊 Banking Default Loan – Credit Risk Analysis (J.P. Morgan Quant Research)



🧠 Overview



Banking\_Default\_Loan is a predictive modeling project designed as part of the J.P. Morgan Chase Quantitative Research Virtual Internship on Forage.

This notebook applies data science and quantitative finance techniques to assess loan default risk, analyze borrower behavior, and model credit probability using real-world-inspired datasets.



🎯 Objective



To develop a data-driven model that estimates the probability of loan default based on borrower and loan attributes — enabling financial institutions to balance profitability and risk exposure.



🧮 Mathematical Foundation



The project leverages Logistic Regression, a probabilistic model that estimates the likelihood of default 

𝑃

(

Default

)

P(Default) given borrower characteristics 

𝑋

X.



𝑃

(

Default

)

=

1

1

\+

𝑒

−

(

𝛽

0

\+

𝛽

1

𝑋

1

\+

𝛽

2

𝑋

2

\+

⋯

\+

𝛽

𝑛

𝑋

𝑛

)

P(Default)=

1+e

−(β

0

&nbsp;	​



\+β

1

&nbsp;	​



X

1

&nbsp;	​



\+β

2

&nbsp;	​



X

2

&nbsp;	​



\+⋯+β

n

&nbsp;	​



X

n

&nbsp;	​



)

1

&nbsp;	​





Where:



𝛽

0

β

0

&nbsp;	​



&nbsp;= intercept



𝛽

𝑖

β

i

&nbsp;	​



&nbsp;= model coefficients



𝑋

𝑖

X

i

&nbsp;	​



&nbsp;= borrower and loan features



The log-odds of default can also be expressed as:



log

⁡

(

𝑃

(

Default

)

1

−

𝑃

(

Default

)

)

=

𝛽

0

\+

∑

𝑖

=

1

𝑛

𝛽

𝑖

𝑋

𝑖

log(

1−P(Default)

P(Default)

&nbsp;	​



)=β

0

&nbsp;	​



\+

i=1

∑

n

&nbsp;	​



β

i

&nbsp;	​



X

i

&nbsp;	​





Model evaluation is performed using metrics like:



Accuracy

=

𝑇

𝑃

\+

𝑇

𝑁

𝑇

𝑃

\+

𝑇

𝑁

\+

𝐹

𝑃

\+

𝐹

𝑁

Accuracy=

TP+TN+FP+FN

TP+TN

&nbsp;	​



Precision

=

𝑇

𝑃

𝑇

𝑃

\+

𝐹

𝑃

;

Recall

=

𝑇

𝑃

𝑇

𝑃

\+

𝐹

𝑁

Precision=

TP+FP

TP

&nbsp;	​



;Recall=

TP+FN

TP

&nbsp;	​



F1-score

=

2

×

Precision

×

Recall

Precision

\+

Recall

F1-score=2×

Precision+Recall

Precision×Recall

&nbsp;	​



🚀 Features



Exploratory Data Analysis (EDA) for credit and demographic patterns



Logistic Regression and Decision Tree modeling



ROC Curve \& AUC performance visualization



Outlier detection and normalization pipeline



Financial insights derived from quantitative results



🧰 Tech Stack



Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Environment: Jupyter Notebook

Version Control: Git, GitHub



📊 Workflow



Data Cleaning \& Preprocessing



Exploratory Data Analysis (EDA)



Feature Engineering \& Scaling



Model Design \& Training



Evaluation \& Statistical Interpretation



Credit Risk Insights \& Recommendations



💡 Key Insights



Borrowers with high debt-to-income ratios have the highest default likelihood.



Credit score and employment stability strongly reduce risk probability.



Optimal threshold tuning improved F1-score and reduced Type II errors.



⚙️ Setup



Clone and install dependencies:



git clone https://github.com/HarishxWEB3/Banking\_Default\_Loan.git

cd Banking\_Default\_Loan

pip install -r requirements.txt





Launch the notebook:



jupyter notebook Banking\_Default\_Loan.ipynb



🧾 License



This project is open-source under the MIT License.



🧑‍💻 Author



Harish R

Aspiring Quant Researcher | Data Science \& AI Enthusiast



🌐 GitHub Profile

=======
# Banking_default_Loan
>>>>>>> a8fbd0633ad7c87c0b38607b7109aba38fb3a58c
