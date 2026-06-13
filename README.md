# Fake News Detection and Evaluation with Confusion Matrix

Summer Internship 2026 project notebook for fake news classification using Machine Learning, Natural Language Processing (NLP), and model evaluation techniques.

---

## Contents

* `04-Fake_News_Detection_and_Evaluation_with_Confusion_Matrix_Summer_2026.ipynb` : Main project notebook.
* `internship-data/dataset_info.txt` : Dataset information and download instructions.
* `classification_report.txt` : Logistic Regression classification report.
* `confusion_matrix.png` : Confusion Matrix visualization.
* `requirements.txt` : Python package requirements.

The dataset files (`Fake.csv` and `True.csv`) are not committed because they are large.

Download the dataset from:

https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets

After downloading and extraction, the folder should contain:

```text
Fake.csv
True.csv
```

Place these files locally before running the notebook.

---

## Project Aim

This project demonstrates a complete machine learning pipeline for automated fake news detection.

The objective is to classify news articles as either:

* Fake News (Class = 1)
* True News (Class = 0)

using textual content and supervised machine learning models.

The project covers:

* Data Loading
* Data Cleaning
* Text Preprocessing
* TF-IDF Vectorization
* Logistic Regression
* Decision Tree Classification
* Hyperparameter Tuning using GridSearchCV
* Model Evaluation using Classification Report and Confusion Matrix

---

## Dataset Overview

The project utilizes a publicly available dataset consisting of two classes of news articles.

### True News

* Source: Reuters
* Category: Legitimate news articles
* Label: 0

### Fake News

* Sources: Various websites identified by Politifact and Wikipedia
* Category: Fake or misleading news articles
* Label: 1

### Dataset Statistics

* Total Articles: 44,898
* Fake News Articles: 23,481
* True News Articles: 21,417

### Dataset Link

https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets

---

## Covered Tasks

### Data Preparation

* Load Fake.csv and True.csv datasets.
* Create target labels.
* Merge datasets.
* Shuffle records.
* Remove unnecessary columns.
* Prepare clean text data.

### Text Preprocessing

* Convert text to lowercase.
* Remove URLs.
* Remove special characters.
* Remove extra spaces.

### Feature Engineering

* Convert text into numerical vectors using TF-IDF Vectorization.

### Model Training

* Logistic Regression
* Decision Tree Classifier

### Model Evaluation

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

### Hyperparameter Optimization

* GridSearchCV
* Parameter tuning for Logistic Regression

---

## Local Setup

Requires Python 3.10 or newer.

### Create Virtual Environment

```bash
python -m venv .venv
```

Activate environment:

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter notebook
```

Open:

```text
04-Fake_News_Detection_and_Evaluation_with_Confusion_Matrix_Summer_2026.ipynb
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook
* Google Colab

---

## Machine Learning Workflow

1. Load Dataset
2. Create Labels
3. Merge Dataset
4. Shuffle Data
5. Clean Data
6. Text Preprocessing
7. Train-Test Split
8. TF-IDF Vectorization
9. Logistic Regression Training
10. Decision Tree Training
11. Hyperparameter Tuning
12. Performance Evaluation

---

## Key Outputs

### Dataset Split

* Training Samples: 33,673
* Testing Samples: 11,225

### TF-IDF Vectorization

* Successfully transformed textual news articles into numerical feature vectors.
* Generated sparse feature matrices for model training and testing.

### Logistic Regression Results

#### Classification Report

| Class         | Precision | Recall | F1-Score |
| ------------- | --------- | ------ | -------- |
| True News (0) | 0.99      | 0.99   | 0.99     |
| Fake News (1) | 0.99      | 0.99   | 0.99     |

#### Accuracy

```text
0.99
```

### Decision Tree Results

#### Accuracy

```text
0.9964
```

### Hyperparameter Tuning Results

Best Parameters Found:

```python
{'C': 10, 'solver': 'liblinear'}
```

---

## Confusion Matrix

Add the generated image below:

```markdown
![Confusion Matrix](confusion_matrix.png)
```

---

## Expected Outputs

* TF-IDF Feature Matrix
* Classification Report
* Confusion Matrix
* Logistic Regression Predictions
* Decision Tree Predictions
* Accuracy Scores
* GridSearchCV Best Parameters

---

## Repository Structure

```text
Internship-IDEAS-Fake-News-Detection/
│
├── .gitignore
├── README.md
├── requirements.txt
├── .python-version
│
├── internship-data/
│   └── dataset_info.txt
│
├── 04-Fake_News_Detection_and_Evaluation_with_Confusion_Matrix_Summer_2026.ipynb
│
├── classification_report.txt
├── confusion_matrix.png
└── fake_news_sample.png
```

---

## Author

**Abhideep**

IIEST Shibpur

Summer Internship Program 2026

IDEAS – Institute of Data Engineering, Analytics and Science Foundation

---

## License

This project is intended for educational and internship demonstration purposes.
