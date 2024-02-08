# Ionosphere Data Prediction

## Introduction

This project aims to analyze radar data collected by a system in Goose Bay, Labrador, focusing on the ionosphere's behavior. Machine learning models Random Forest Classifier and Logistic Regression were used to classify radar returns as either "Good" or "Bad" based on their ionospheric patterns. The Random Forest Classifier achieved an accuracy of 98%, while Logistic Regression achieved 90%.

## Problem Statement

This project addresses the binary classification problem of distinguishing between "Good" and "Bad" radar returns based on ionospheric behavior.

## About Dataset

- Contains 34 features.
- The 35th attribute classifies radar returns as "good" or "bad".
- Consists of 351 instances.
- Multivariate dataset with no missing values.

## Model Training and Selection

### Random Forest Classifier

Random Forest Classifier is an ensemble learning method known for its robustness and ability to handle large datasets. By aggregating the predictions of multiple decision trees, it achieves high accuracy and is less prone to overfitting. In this project, it achieved an impressive accuracy of 98%, making it a reliable choice for classification tasks.

#### Predictions

<p align="center">
  <img src="https://github.com/lexxus16/ionosphere_prediction/assets/69308391/7abd7e1a-0045-4d9b-acd4-5bb6ae3ddc4e" alt="Alt Text" width="500"/>
</p>

#### Metrics Score

<p align="center">
  <img src="https://github.com/lexxus16/ionosphere_prediction/assets/69308391/32358a5c-47bd-41ba-9374-679f2a46af97" alt="Alt Text" width="460"/>
</p>

### Logistic Regression

Logistic Regression is a simple yet powerful linear model commonly used for binary classification problems. It predicts the probability of an instance belonging to a certain class, making it interpretable and suitable for understanding feature importance. Despite its simplicity, logistic regression achieved a commendable accuracy of 90% in this project, showcasing its effectiveness in modeling binary outcomes.

#### Predictions

<p align="center">
  <img src="https://github.com/lexxus16/ionosphere_prediction/assets/69308391/fdfeb183-3ebe-47e5-85ac-5bd0a62026bd" alt="Alt Text" width="500"/>
</p>


#### Metrics Score

<p align="center">
  <img src="https://github.com/lexxus16/ionosphere_prediction/assets/69308391/27961d4c-2a6d-4099-85d5-aa4cc58b8fe4" alt="Alt Text" width="430"/>
</p>

## Contributing
You are welcome to contribute to enhancing and improving this project. Contribute by:
- Bug Reports: If you encounter any issues or unexpected behavior, please report them.
- Feature Requests: Share ideas for new features or improvements by submitting a feature request.
