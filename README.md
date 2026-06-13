# Sonar Rock vs Mine Prediction

A Machine Learning project that predicts whether an underwater object is a Rock or a Mine using Sonar signal data.

## Project Overview

This project uses Logistic Regression to classify sonar signals reflected from underwater objects. The model is trained on the Sonar Dataset containing 60 numerical features extracted from sonar returns.

The goal is to determine whether the detected object is:

- Rock (R)
- Mine (M)

## Dataset Information

- Dataset: Sonar Dataset
- Total Records: 208
- Features: 60
- Target Classes:
  - R → Rock
  - M → Mine

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-Learn
- Google Colab

## Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Feature and Label Separation
4. Train-Test Split
5. Logistic Regression Model
6. Model Evaluation
7. Predictive System

---

## Project Screenshots

### 1. Data Preparation

![Data Preparation](images/01-data-preparation.png)

Features and labels were separated before training.

---

### 2. Train-Test Split

![Train Test Split](images/02-train-test-split.png)

The dataset was split into training and testing sets using `train_test_split()`.

---

### 3. Model Training

![Model Training](images/03-model-training.png)

Logistic Regression model was trained using the training dataset.

---

### 4. Model Evaluation

![Model Evaluation](images/04-model-evaluation.png)

Results:

- Training Accuracy: 83.42%
- Testing Accuracy: 76.19%

---

### 5. Prediction System

![Prediction System](images/05-prediction-system.png)

The trained model successfully predicts whether the object is a Rock or Mine based on sonar input data.

---

## Model Used

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm commonly used for binary classification problems.

Since the target variable has only two classes (Rock and Mine), Logistic Regression is a suitable choice.

## How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/Sonar-Rock-vs-Mine-Prediction.git
```

### Install Dependencies

```bash
pip install numpy pandas scikit-learn
```

### Run Project

```bash
python sonar_prediction.py
```

## Project Structure

```text
Sonar-Rock-vs-Mine-Prediction/
│
├── sonar_prediction.ipynb
├── sonar_prediction.py
├── sonar_data.csv
├── README.md
│
└── images/
    ├── 01-data-preparation.png
    ├── 02-train-test-split.png
    ├── 03-model-training.png
    ├── 04-model-evaluation.png
    └── 05-prediction-system.png
```

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Streamlit Web Application
- Model Deployment

## Author

Pranav Agneesh

Machine Learning Project Series | Day 1 of #30Days30MLProjects
