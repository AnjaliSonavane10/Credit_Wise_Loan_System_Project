# 🏦 Loan Approval Prediction

A Machine Learning mini-project that predicts whether a loan application is likely to be **approved or rejected** based on applicant and financial information.

The project follows a complete Machine Learning workflow, including **data cleaning, exploratory data analysis, visualization, categorical encoding, feature scaling, model training, and model comparison**.

---

## 📌 Project Overview

Loan approval is an important decision for financial institutions. Traditionally, banks evaluate several factors such as an applicant's income, credit history, loan amount, employment status, and other financial details before approving a loan.

In this project, Machine Learning algorithms are used to analyze historical loan application data and predict the loan approval status.

The project compares multiple classification algorithms to identify the model that performs best on the given dataset.

---

## 🎯 Objectives

* Understand and preprocess the loan approval dataset.
* Perform data cleaning and handle missing values.
* Explore the dataset using statistical analysis and visualizations.
* Analyze relationships between different features.
* Encode categorical variables into numerical form.
* Scale numerical features where required.
* Train multiple Machine Learning classification algorithms.
* Compare the performance of different models.
* Select the best-performing model for loan approval prediction.

---

## 📊 Dataset

The dataset used in this project was obtained from **Kaggle**.

The dataset contains information about loan applicants, including features related to their personal, financial, and loan details.

Typical features include:

* Gender
* Married Status
* Dependents
* Education
* Self Employment
* Applicant Income
* Coapplicant Income
* Loan Amount
* Loan Amount Term
* Credit History
* Property Area
* Loan Status

> **Note:** The original Kaggle dataset and its license/attribution should be retained according to the dataset owner's requirements.

---

## 🔄 Machine Learning Workflow

The project follows these major steps:

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Encoding Categorical Features
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Best Model Selection
```

---

## 🧹 Data Cleaning

The dataset was inspected and cleaned before applying Machine Learning algorithms.

The preprocessing steps included:

* Checking the shape and structure of the dataset.
* Identifying missing values.
* Handling missing/null values.
* Checking duplicate records.
* Examining data types.
* Identifying categorical and numerical features.
* Checking the distribution of important variables.

Data cleaning was performed to improve the quality and consistency of the dataset before model training.

---

## 📈 Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand the dataset and identify important patterns.

The project uses:

* **Matplotlib**
* **Seaborn**

Different visualizations were created to analyze the relationship between features and loan approval status.

### Visualizations include:

* Count plots
* Bar plots
* Distribution plots
* Histograms
* Box plots
* Correlation heatmap

These visualizations helped in understanding the distribution of the data and identifying relationships between different variables.

---

## 🔥 Correlation Heatmap

A correlation heatmap was created using **Seaborn** to understand the relationship between numerical features.

The heatmap helps identify:

* Positively correlated features
* Negatively correlated features
* Weakly correlated features
* Potentially redundant features

This analysis was useful during the feature understanding and preprocessing stage.

---

## 🔤 Encoding

Since Machine Learning algorithms generally require numerical input, categorical variables were converted into numerical values.

Encoding techniques were applied to transform categorical features into a suitable numerical representation.

This allowed the classification algorithms to process both categorical and numerical information.

---

## ⚖️ Feature Scaling

Feature scaling was performed to bring numerical features onto a comparable scale.

This is particularly important for algorithms such as:

* K-Nearest Neighbors (KNN)
* Logistic Regression

Scaling helps prevent features with larger numerical ranges from dominating the model.

---

## 🤖 Machine Learning Algorithms

Multiple classification algorithms were trained and evaluated.

### 1. Logistic Regression

Logistic Regression was used as one of the baseline classification algorithms for predicting whether a loan application would be approved.

### 2. K-Nearest Neighbors (KNN)

KNN predicts the class of a new observation based on the classes of its nearest neighboring observations.

Feature scaling is particularly important for KNN because it relies on distance calculations.

### 3. Naive Bayes

Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem.

It assumes that the features are conditionally independent given the target class.

### 4. Other Models

Additional classification algorithms can also be included and compared depending on the experiments performed in the notebook.

---

## 📊 Model Comparison

After training the different classification models, their performance was analyzed and compared using appropriate evaluation metrics.

The main purpose of model comparison was to determine which algorithm provided the most suitable performance for this dataset.

### Model Evaluation

The models can be evaluated using metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The final model selection was based on the performance observed during experimentation.

---

## 🏆 Best Performing Model

After analyzing the performance of the different models, **Naive Bayes** performed best among the models tested in this project.

Therefore, **Naive Bayes was selected as the final model** for the Loan Approval Prediction task.

> The exact performance values can be added below based on the results from the notebook.

| Model               |       Accuracy |
| ------------------- | -------------: |
| Logistic Regression |     Add result |
| KNN                 |     Add result |
| Naive Bayes         | **Add result** |

---

## 🛠️ Technologies & Libraries

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn

### Development Environment

* Jupyter Notebook
* Git
* GitHub

---

## 📁 Project Structure

```text
Loan-Approval-Prediction/
│
├── Loan_miniProject.ipynb
├── dataset/
│   └── loan_dataset.csv
│
├── .gitignore
└── README.md
```

> The dataset may be excluded from the GitHub repository if it is covered by licensing restrictions or if you prefer not to upload raw data.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the project directory

```bash
cd Loan-Approval-Prediction
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open:

```text
Loan_miniProject.ipynb
```

Run the cells sequentially to reproduce the analysis and model training.

---

## 📌 Key Learnings

Through this project, I gained practical experience in:

* Data preprocessing
* Handling missing data
* Exploratory Data Analysis
* Data visualization using Matplotlib and Seaborn
* Categorical feature encoding
* Feature scaling
* Classification algorithms
* Model evaluation
* Comparing Machine Learning models
* Selecting the best-performing model

---

## 🔮 Future Improvements

The project can be further improved by:

* Performing hyperparameter tuning.
* Applying cross-validation.
* Testing additional classification algorithms.
* Performing feature selection.
* Handling class imbalance if present.
* Building an interactive prediction interface.
* Deploying the final model using FastAPI or Streamlit.
* Creating a complete end-to-end ML pipeline.

---

## 👩‍💻 Author

**Anjali Sonavane**

B.Tech – Computer Science Engineering

---

## ⭐ Conclusion

This project demonstrates an end-to-end approach to solving a **Loan Approval Prediction** problem using Machine Learning.

After preprocessing the data, performing exploratory analysis, encoding categorical variables, scaling features, and training multiple classification algorithms, **Naive Bayes achieved the best performance among the models tested** and was selected as the final model.

The project provides practical experience in applying Machine Learning techniques to a real-world classification problem.
