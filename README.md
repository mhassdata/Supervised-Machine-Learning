# Machine Learning Model Comparison

This repository compares the performance of two machine learning models, Support Vector Classifier (SVC) and Decision Tree, for a binary classification task. The dataset contains features related to a specific problem, and the goal is to predict the outcome, either class 0 or class 1.

## Models and Evaluation
SVC Model: Achieved an accuracy of 75.5% on the test data with balanced precision and recall for class 0 (0.77 and 0.88) but lower recall for class 1 (0.53).
Decision Tree Model: Achieved an accuracy of 73.4% on the test data with good precision and recall for class 0 (0.81 and 0.81) but lower recall for class 1 (0.56).


## Conclusion
Both models showed balanced performance for class 0, but they struggled to correctly identify instances of class 1. The SVC model slightly outperformed the Decision Tree in accuracy, but improving recall for class 1 remains crucial. Further model enhancements can be explored, such as hyperparameter tuning and resampling techniques.

Getting Started
Clone the repository.
Install the required dependencies.
Load and preprocess the dataset.
Train and evaluate the models using provided code.

