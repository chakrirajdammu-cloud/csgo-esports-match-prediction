# CS:GO Esports Match Outcome Prediction Using Machine Learning

## Project Overview

This project focuses on predicting the outcomes of Counter-Strike: Global Offensive (CS:GO) esports matches using machine learning techniques.

The objective is to analyse historical match data, identify important patterns and develop predictive models that estimate match winners.

## Project Objectives

- Analyse historical CS:GO esports match data.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis.
- Engineer relevant features for predictive modelling.
- Develop and evaluate machine learning models.
- Compare model performance to identify an effective prediction approach.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The project uses historical CS:GO match data containing team-related and match-performance features.

Key features include:
- CT team score
- T team score
- Team rankings
- Match results
- Score difference

**Target variable:** `map_winner`

## Data Preprocessing and Feature Engineering

The project includes:
- Checking dataset quality and missing values.
- Preparing the data for machine learning.
- Selecting relevant predictive features.
- Creating a `score_difference` feature using the absolute difference between match result scores.

## Machine Learning Algorithms

The following models were implemented and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

Different model configurations were compared to evaluate predictive performance.

## Model Performance

The Logistic Regression model achieved a reported accuracy of **96.49%** using the evaluated configuration.

The Decision Tree and Random Forest models were also tested and compared.

*Note: Results represent the evaluation performed in this project and should be interpreted in the context of the dataset and validation methodology.*

## Project Structure

```text
csgo-esports-match-prediction/
│
├── csgo_match_prediction.ipynb
├── results.csv
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Ensure the dataset is available in the expected location.
5. Run the notebook cells sequentially.

## Key Learning Outcomes

- Practical experience in Python-based data analysis.
- Data preprocessing and feature engineering.
- Implementation of supervised machine learning algorithms.
- Model evaluation and comparison.
- Predictive analytics using real-world-style esports data.

## Author

**Chakri Raj Dammu**

MSc Artificial Intelligence for Business Intelligence  
University of Leicester, United Kingdom

GitHub: https://github.com/chakrirajdammu-cloud
