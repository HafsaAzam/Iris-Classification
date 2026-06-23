# Iris Flower Classification using K-Nearest Neighbors (KNN)

## Overview
This project implements a K-Nearest Neighbors (KNN) classifier to predict the species of Iris flowers based on their physical characteristics.
The model classifies flowers into one of three categories:
- Setosa
- Versicolor
- Virginica

## Dataset
The Iris dataset contains 150 flower samples with the following features:
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

Target Variable:
- Species

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Machine Learning Algorithm
K-Nearest Neighbors (KNN)
Parameters:
```python
KNeighborsClassifier(n_neighbors=5)
```
## Evaluation Matrix: 
- Confusion Matrix
- Accuracy Score
- Classification Report
  
## Conclusion
The KNN model successfully classified all test samples and achieved 100% accuracy. The confusion matrix and classification report indicate perfect precision, recall, and F1-score for all three Iris species.
