\# Loan Approval Prediction



A machine learning project that predicts whether a loan application will be approved, based on applicant details such as income, credit score, DTI ratio and savings.



\## Dataset

`loan\_approval\_data.csv` - 1000 applicants, 19 features (income, age, credit score, loan amount, employment status, etc.) and the target `Loan\_Approved` (Yes/No).



\## What I did

\- Handled missing values (mean for numeric, most frequent for categorical)

\- Exploratory data analysis (class balance, distributions, outliers, correlations)

\- Encoded categorical features (Label Encoding + One-Hot Encoding)

\- Feature scaling with StandardScaler

\- Trained and compared Logistic Regression, KNN and Naive Bayes

\- Feature engineering (squared Credit Score and DTI Ratio)



\## Results

Best model: \[model name] - Accuracy: \[xx%], Precision: \[xx%], Recall: \[xx%]



\## How to run

1\. Clone this repo

2\. Install the libraries: `pip install pandas numpy seaborn matplotlib scikit-learn jupyter`

3\. Open `loan\_proj\_fixed.ipynb` in Jupyter and run all cells



\## Tech stack

Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn

