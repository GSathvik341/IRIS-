# IRIS-
This project demonstrates a fundamental machine learning workflow by building and evaluating two classifiers on the classic Iris dataset. The goal is to classify iris flowers into one of three species (Setosa, Versicolor, Virginica) based on sepal and petal measurements.
## Project Overview
This repository contains a Jupyter Notebook (iris_classifier.ipynb) that walks through the entire process of:
 * Loading the Iris dataset.
 * Splitting the data into training and testing sets.
 * Training two distinct machine learning models.
 * Evaluating the performance of each model using standard metrics.
## Dataset
The project uses the well-known Iris dataset, which is included with scikit-learn.
 * Features:
   * Sepal Length (cm)
   * Sepal Width (cm)
   * Petal Length (cm)
   * Petal Width (cm)
 * Target Classes:
   * Setosa
   * Versicolor
   * Virginica
## Models and Evaluation
Two different classification models were trained and evaluated:
 * Logistic Regression: A robust linear model for classification.
 * Random Forest: An ensemble model composed of multiple decision trees, capable of capturing more complex patterns.
The models were evaluated on the test set (30% of the data) using two key metrics:
 * Accuracy Score: The percentage of correct predictions.
 * Confusion Matrix: A table showing the detailed breakdown of correct and incorrect predictions for each class.
## Results 
Both models performed exceptionally well on this dataset, highlighting its relatively clean and separable nature.
 * Logistic Regression Accuracy: ~93.3%
 * Random Forest Accuracy: ~91.1%
   
The confusion matrices for both models revealed a common pattern:
 * The Setosa species was perfectly classified every time.
 * A single misclassification occurred where a Virginica flower was mistaken for a Versicolor, indicating these two species have more similar features.
## How to Run
To run this project, clone the repository and ensure you have the required Python libraries installed.
### Prerequisites
You'll need Python 3 and the following libraries:
 * scikit-learn
 * numpy
 * matplotlib
### Installation
You can install the necessary packages using pip:
pip install scikit-learn numpy matplotlib

### Execution
Open and run the iris_classifier.ipynb notebook in a Jupyter environment to see the code, outputs, and visualizations.
The confusion matrices for both models revealed a common pattern:
 * The Setosa species was perfectly classified every time.
