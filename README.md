# Titanic-Survival
Titanic Survival Prediction using Machine Learning
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/idhaa15/Titanic-Survival/blob/main/Model.ipynb)

![Titanic](https://img.shields.io/badge/Dataset-Kaggle-blue)
![Language](https://img.shields.io/badge/Language-Python-green)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-orange)

## Project Overview
This project involves building a predictive model to determine the survival probability of passengers aboard the RMS Titanic. Using the classic Titanic dataset, I performed Exploratory Data Analysis (EDA), data cleaning, and implemented a **Logistic Regression** model to classify passengers as survivors or non-survivors.

## Key Features
- **Data Preprocessing**: Handled missing values in the `Age` and `Embarked` columns using mean and mode imputation. Dropped the `Cabin` column due to high sparsity.
- **Exploratory Data Analysis (EDA)**: Visualized survival rates across different features like `Sex`, `Pclass`, and `Age` using **Seaborn** and **Matplotlib**.
- **Categorical Encoding**: Converted categorical variables (`Sex`, `Embarked`) into numerical format for model compatibility.
- **Machine Learning**: Utilized `Scikit-Learn` to split data into training/testing sets and trained a Logistic Regression model.

## Tech Stack
- **Python** (NumPy, Pandas)
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-Learn

## Performance Results
- **Training Accuracy**: ~80.7%
- **Test Accuracy**: ~78.2%

The model shows a strong correlation between passenger class/gender and the likelihood of survival, consistent with historical accounts.

## File Structure
- `data/`: Contains the Titanic training dataset.
- `Titanic_Survival_Analysis.ipynb`: The main notebook containing the data pipeline and model.
- `README.md`: Project documentation.

## How to Run
1. Clone this repository.
2. Ensure you have `scikit-learn`, `pandas`, and `seaborn` installed.
3. Run the notebook in Google Colab or Jupyter Notebook.
