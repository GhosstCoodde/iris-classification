# Iris Flower Classification

## Project Overview
This project uses machine learning to classify Iris flowers into three species based on their petal measurements.

## Dataset
The Iris dataset contains 150 samples and 3 species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Features
The model uses two features:
- Petal Length
- Petal Width

## Machine Learning Models
Several classification algorithms were evaluated:
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

## Final Model
The final model is an SVM classifier with StandardScaler in a Scikit-learn Pipeline.

## Results
- Best cross-validation accuracy: 96.67%
- Final test accuracy: 93.33%

## Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Joblib

## Project Structure
```text
iris-classification/
├── data/
│   └── iris.data
├── models/
│   └── iris_svm_pipeline.joblib
├── notebooks/
│   └── iris_classification.ipynb
├── README.md
└── requirements.txt
```

## How to Run
1. Install dependencies:
   `pip install -r requirements.txt`
2. Open the Jupyter Notebook.
3. Run the notebook cells to explore the analysis and train the model.

## Author
GhosstCoodde