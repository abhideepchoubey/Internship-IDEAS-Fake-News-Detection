# Fake News Detection and Evaluation with Confusion Matrix

Summer Internship 2026 project notebook for fake news classification using machine learning and natural language processing.

## Contents

* 10_Fake_News_Detection_and_Evaluation_Spring_2026.ipynb: Main project notebook.
* internship-data/dataset_info.txt: Dataset download information.
* confusion_matrix.png: Model evaluation visualization.
* classification_report.txt: Classification metrics.
* requirements.txt: Python package requirements.

The dataset is not committed because it contains large CSV files.

Download from:

https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets

After extraction:

Fake.csv
True.csv

must be available locally before running the notebook.

---

## Project Aim

This project demonstrates a complete machine learning pipeline for detecting fake news articles.

The project applies:

* Data preprocessing
* Text cleaning
* TF-IDF Vectorization
* Logistic Regression
* Decision Tree Classification
* Hyperparameter Tuning using GridSearchCV
* Model Evaluation using Confusion Matrix and Classification Report

---

## Covered Tasks

* Load and combine fake and true news datasets.
* Create target labels.
* Perform text preprocessing.
* Transform text into numerical features using TF-IDF.
* Split dataset into training and testing sets.
* Train Logistic Regression model.
* Train Decision Tree model.
* Evaluate model performance.
* Generate classification reports.
* Perform hyperparameter tuning.

---

## Local Setup

Requires Python 3.10 or newer.

### Install dependencies

pip install -r requirements.txt

### Start Jupyter

jupyter lab

Open and run:

10_Fake_News_Detection_and_Evaluation_Spring_2026.ipynb

---

## Expected Outputs

* TF-IDF feature matrix
* Logistic Regression Classification Report
* Decision Tree Accuracy Score
* Confusion Matrix
* Best Hyperparameters from GridSearchCV

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Author

Abhideep

IIEST Shibpur

IDEAS Summer Internship Program 2026
