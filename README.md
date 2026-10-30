# Iris Flower Classification using Machine Learning

## Project Overview

This project implements an Iris Flower Classification system using supervised machine learning algorithms.

The objective is to predict the species of an Iris flower based on four measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The project uses the Iris dataset from Kaggle and compares multiple machine learning algorithms to identify the best-performing model.

## Dataset

**Source:** [Iris Flower Dataset – Kaggle](https://www.kaggle.com/datasets/saurabh00007/iriscsv)

- Total samples: 150
- Number of features: 4
- Target classes: 3
- Samples per species: 50

### Species

- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Environment Setup
2. Dataset Loading and Inspection
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Logistic Regression Baseline Model
6. Machine Learning Model Comparison
7. Model Evaluation
8. Hyperparameter Tuning using GridSearchCV
9. Flower Species Prediction
10. Conclusion

## Machine Learning Algorithms

The following algorithms were implemented:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## Model Performance

| Model | Test Accuracy |
|---|---:|
| Logistic Regression | 96.67% |
| Support Vector Machine | 96.67% |
| Decision Tree | 93.33% |
| K-Nearest Neighbors | 93.33% |
| Random Forest | 90.00% |

## Hyperparameter Tuning

GridSearchCV was used to optimize the Logistic Regression model.

**Best Parameters:**
- C: 1
- Solver: lbfgs

**Best Cross-Validation Accuracy:** 96.67%

**Tuned Model Test Accuracy:** 96.67%

## Prediction

A reusable prediction function was developed to classify Iris flowers using their four measurements.

Example:

```python
predict_iris(5.1, 3.5, 1.4, 0.2)
```

Output:

```text
Iris-setosa
```

## Project Structure

```text
CodeAlpha_IrisFlowerClassification/
│
├── Iris.csv
├── iris_classification.ipynb
├── requirements.txt
└── README.md
```

## How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open `iris_classification.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells sequentially.

## Learning Outcomes

Through this project, I gained practical experience in:

- Data cleaning and preprocessing
- Exploratory Data Analysis
- Supervised machine learning
- Classification algorithms
- Model evaluation and comparison
- Hyperparameter tuning
- Building prediction functions

## Internship

This project was completed as part of the **CodeAlpha Machine Learning Internship**.