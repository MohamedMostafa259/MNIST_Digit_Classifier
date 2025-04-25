# MNIST Digit Classifier 

A machine learning project inspired by Chapter 3 of *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*. This repository walks through building classifiers to recognize handwritten digits from the MNIST dataset using a range of models and techniques.

## Topics Covered

- How to fetch and preprocess the MNIST dataset
- Binary classification with `SGDClassifier`
- Precision-Recall trade-off and ROC curves
- Multiclass classification using one-vs-rest strategy
- Multi-label classification using `KNeighborsClassifier`
- Multioutput classification using `KNeighborsClassifier`
- Performance evaluation using confusion matrices, F1-score, ROC AUC, and more
- Error analysis and visualization techniques

## Models and Techniques

| Task | Description |
|------|-------------|
| **Binary Classification** | Detect whether a digit is '5' or not using `SGDClassifier` |
| **Multiclass Classification** | Classify digits from 0 to 9 using OvR strategy |
| **Multilabel Classification** | Predict if a digit is large (≥7) and/or odd using `KNeighborsClassifier` |
| **Multioutput Classification** | Predicts the clean version of a noisy digit using `KNeighborsClassifier` |
| **Evaluation Metrics** | Accuracy, Precision, Recall, F1-score, PR Curve, ROC Curve |
