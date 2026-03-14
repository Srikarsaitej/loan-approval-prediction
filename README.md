# 🏦 Loan Approval Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Pandas-green)
![Visualization](https://img.shields.io/badge/Visualization-Seaborn%20%7C%20Matplotlib-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project predicts whether a **bank loan application will be approved or rejected** using Machine Learning algorithms.

Financial institutions receive thousands of loan applications daily. Evaluating each application manually is time-consuming and error-prone. This system helps automate the process by analyzing applicant data and predicting the loan approval status.

The model evaluates factors such as:

* Applicant income
* Co-applicant income
* Credit history
* Loan amount
* Education level
* Employment status
* Property area

---

# 📊 Dataset Information

The dataset contains **614 loan applications** with multiple financial and demographic attributes.

| Feature           | Description                     |
| ----------------- | ------------------------------- |
| Loan_ID           | Unique loan ID                  |
| Gender            | Applicant gender                |
| Married           | Marital status                  |
| Dependents        | Number of dependents            |
| Education         | Education level                 |
| Self_Employed     | Employment status               |
| ApplicantIncome   | Applicant monthly income        |
| CoapplicantIncome | Co-applicant income             |
| LoanAmount        | Requested loan amount           |
| Loan_Amount_Term  | Loan repayment duration         |
| Credit_History    | Credit history record           |
| Property_Area     | Area type                       |
| Loan_Status       | Loan approval (Target variable) |

---

# 🛠 Technologies Used

| Tool             | Purpose                     |
| ---------------- | --------------------------- |
| Python           | Programming language        |
| Pandas           | Data manipulation           |
| NumPy            | Numerical computations      |
| Matplotlib       | Data visualization          |
| Seaborn          | Advanced visualizations     |
| Scikit-Learn     | Machine learning algorithms |
| Jupyter Notebook | Development environment     |

---

# 🔎 Exploratory Data Analysis

EDA was performed to understand the dataset and identify patterns.

### Visualizations used

* 📈 Correlation Heatmap
* 📊 Distribution Plots
* 📦 Boxplots for outlier detection
* 📉 Scatter plots
* 📊 Count plots for categorical variables

These analyses helped identify key factors affecting loan approval.

---

# ⚙️ Feature Engineering

Additional features were created to improve model performance.

| Feature         | Description                         |
| --------------- | ----------------------------------- |
| TotalIncome     | ApplicantIncome + CoapplicantIncome |
| TotalIncome_log | Log transformation of total income  |
| LoanAmount_log  | Log transformation of loan amount   |

These transformations helped normalize skewed distributions.

---

# 🤖 Machine Learning Models

The following classification models were implemented:

1️⃣ Random Forest
2️⃣ Naive Bayes
3️⃣ Decision Tree
4️⃣ K-Nearest Neighbors (KNN)

The dataset was split into:

* **Training Data → 80%**
* **Testing Data → 20%**

---

# 📈 Model Performance

| Model         | Accuracy  |
| ------------- | --------- |
| Naive Bayes   | **83.7%** |
| Random Forest | ~80%      |
| Decision Tree | ~78%      |
| KNN           | ~75%      |

Naive Bayes achieved the highest prediction accuracy.

---

# 📂 Project Structure

```
loan-approval-prediction
│
├── data
│   └── loan_dataset.csv
│
├── notebooks
│   └── loan_prediction.ipynb
│
├── reports
│   └── project_report.pdf
│
├── images
│   └── visualizations
│
├── requirements.txt
│
└── README.md
```

---

# ⚡ Installation

### Clone repository

```
git clone https://github.com/Srikarsaitej/loan-approval-prediction.git
```

### Move into project folder

```
cd loan-approval-prediction
```

### Install dependencies

```
pip install -r requirements.txt
```

### Run notebook

```
jupyter notebook
```

---

# 📊 Key Insights

Some important insights discovered during analysis:

✔ Credit history is the strongest factor influencing loan approval
✔ Applicants with higher income have a higher probability of approval
✔ Loan amount distribution is right-skewed
✔ Log transformations improve model performance

---

# 🚀 Future Improvements

Possible improvements to enhance the project:

* Deploy the model using **Flask / FastAPI**
* Build a **Loan Prediction Web Application**
* Use **XGBoost / Gradient Boosting models**
* Deploy the project on **cloud platforms**
* Integrate **real banking datasets**

---

# 👨‍💻 Author

**Srikar Sai Tej**
B.Tech Computer Science Engineering
Lovely Professional University

LinkedIn: https://www.linkedin.com/in/srikar-sai/

---

# 📜 License

This project is developed for **educational and research purposes**.
