# Text_classifier_as_+ve_-ve_ML
Projects related to Machine learning and data science
Sentiment Analysis of Book Reviews
This project aims to classify book reviews as positive or negative using various machine learning models. The dataset used contains 10,000 book reviews, and we have experimented with four different models: Linear SVM, Decision Tree, Naive Bayes, and Logistic Regression. Among these models, Logistic Regression achieved the highest mean accuracy score of 81.73% and an F1 score of 0.823.

Project Structure
 1) data/: Directory containing the dataset used for training and evaluation.
 2) models/: Code for each of the machine learning models implemented.
 3)svm_model.py: Linear SVM model implementation.
 4)decision_tree_model.py: Decision Tree model implementation.
 5)naive_bayes_model.py: Naive Bayes model implementation.
 6)logistic_regression_model.py: Logistic Regression model implementation.
 7)evaluation/: Scripts for evaluating the models and generating performance metrics.
 8)evaluate_model.py: Evaluation script that computes accuracy, precision, recall, and F1 scores.
README.md: This file, providing an overview of the project, how to use it, and the results obtained.

Requirements
1)Python 3.x
2)Libraries: scikit-learn, pandas, random, pickel

Dataset
The dataset used for this project consists of 10,000 book reviews, labeled as positive or negative sentiment.

Models Implemented
1. Linear SVM
Accuracy: 80.12%
F1 Score: 0.798

2. Decision Tree
Accuracy: 76.45%
F1 Score: 0.764

3. Naive Bayes
Accuracy: 78.91%
F1 Score: 0.786

4. Logistic Regression (Best Performer)
Accuracy: 81.73%
F1 Score: 0.823
Precision (Positive Class): 0.810
Recall (Positive Class): 0.810
Precision (Negative Class): 0.811
Recall (Negative Class): 0.812

How to Use
Clone this repository to your local machine.
Navigate to the project directory.
Install the required dependencies using pip install -r requirements.txt.
Run each model's script to train and evaluate the models.
