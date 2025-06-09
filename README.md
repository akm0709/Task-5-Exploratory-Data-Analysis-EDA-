# Exploratory Data Analysis - Titanic Dataset 🚢

## 📌 Objective
Perform Exploratory Data Analysis (EDA) to uncover patterns, relationships, and trends in the Titanic dataset using Python.

## 📁 Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- Files used:
  - `titanic.csv` (main analysis)
  - `test.csv`
  - `gender_submission.csv`

## 🛠 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (for basic model validation)

## 📊 Key Tasks Completed
- Loaded and explored dataset with `.info()`, `.describe()`, and `.value_counts()`
- Checked for and visualized missing data
- Visualized distributions and relationships:
  - Histograms (Age)
  - Count plots (Survived, Sex, Pclass, SibSp, Parch, Embarked)
  - Boxplots (Age vs Survived, Fare vs Survived)
  - Pairplot and Heatmap for correlation
  - Multivariate visualization using `FacetGrid`
- Engineered new feature: `FamilySize`
- Handled missing values using group-wise median imputation
- Detected outliers in `Fare` using boxplots
- Built a basic logistic regression model for survival prediction

## ✅ Outcome
- Identified key features impacting survival: **Sex**, **Pclass**, **Fare**, and **Family Size**
- Achieved a validation accuracy of **~73%** using logistic regression
- Gained hands-on experience with univariate, bivariate, and multivariate analysis
- Practiced feature engineering, visualization, and model evaluation

## 📌 Deliverables
- Jupyter Notebook (`.ipynb`)
- PDF Report (`eda_titanic.pdf`)
- README file (this)

