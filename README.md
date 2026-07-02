# Comment Category Classification using Machine Learning

An end-to-end machine learning project developed on Kaggle to classify comments into their respective categories. This project demonstrates the complete ML workflow, from data exploration and preprocessing to model training, hyperparameter tuning, ensemble learning, and submission generation.

---

## Project Overview

The objective of this project is to build a robust classification model capable of accurately predicting the category of a given comment.

The notebook follows a structured machine learning pipeline consisting of:

- Data Loading
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Data Preprocessing
- Model Training
- Hyperparameter Optimization
- Ensemble Learning
- Prediction & Submission Generation

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- LightGBM
- Kaggle Notebook Environment

---

## Machine Learning Pipeline

### 1. Data Exploration

- Dataset inspection
- Missing value analysis
- Feature understanding
- Distribution analysis

### 2. Data Preprocessing

- Data cleaning
- Feature engineering
- Train-validation split
- Data transformation

### 3. Models Evaluated

- Logistic Regression
- Linear SVC
- SGD Classifier
- Multi-Layer Perceptron (MLP)
- XGBoost
- LightGBM

### 4. Hyperparameter Tuning

RandomizedSearchCV was used to optimize the LightGBM model for improved predictive performance.

### 5. Ensemble Learning

A weighted voting ensemble was implemented to combine predictions from multiple models and improve overall performance.

---

## Results

Multiple models were trained and evaluated using the Kaggle leaderboard. Performance comparisons were made across different algorithms before selecting the final model.

---

## Repository Structure

```
.
├── notebook.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## Running the Notebook

### Clone the repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Open the notebook

```bash
jupyter notebook
```

---

## Dataset

The notebook was originally developed using the Kaggle environment.

If running locally:

- Download the dataset from the corresponding Kaggle competition.
- Update the dataset paths accordingly, as Kaggle uses `/kaggle/input/...` by default.

---

## Future Improvements

- Better feature engineering
- Cross-validation
- Transformer-based NLP models
- Explainable AI (SHAP/LIME)
- Model deployment with Streamlit or Flask

---

## Acknowledgements

- Kaggle
- Scikit-learn
- XGBoost
- LightGBM
