# Rock or Mine Prediction Project

## Overview
This project predicts whether an object is a **rock** or a **mine** using sonar data. The data consists of 60 features for each sample, representing energy levels at various frequencies. The target variable is binary, with 'R' indicating rock and 'M' indicating mine. Multiple machine learning algorithms were tested, and **Support Vector Machine (SVM)** achieved the best performance on this dataset.

## Algorithms Used
The following algorithms were applied to build predictive models:
- **Logistic Regression**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**

### Best Performing Model:
- **SVM** achieved the highest accuracy with the following results:
  - **Train Accuracy**: 92.17%
  - **Test Accuracy**: 83.33%

## Dataset
The dataset used for this project consists of sonar signals reflected off different objects. The dataset includes 208 instances, with 60 features and a target label ('R' for rock and 'M' for mine). Each feature represents the strength of the sonar return signal at different angles and frequencies.

- **Features**: 60 numerical values representing the sonar signal strength at various frequencies.
- **Target**: A single value indicating the type of object (`R` for Rock, `M` for Mine).




## Model Training and Evaluation

The project splits the dataset into training and testing sets, applies three different machine learning algorithms, and evaluates their accuracy on both training and testing data.

### Algorithms and Results

1. **Logistic Regression**:
   - **Train Accuracy**: ~82%
   - **Test Accuracy**: ~73%

2. **Random Forest Classifier**:
   - **Train Accuracy**: ~98%
   - **Test Accuracy**: ~71%

3. **Support Vector Machine (SVM)**:
   - **Train Accuracy**: **92.17%**
   - **Test Accuracy**: **83.33%** (Best model)

### Why SVM was the best:
The SVM model was able to generalize better to the test data compared to Logistic Regression and Random Forest. Its ability to find the optimal decision boundary between the two classes helped it perform well even on unseen data.

## Conclusion

This project demonstrates that **SVM** is the best-performing model for predicting whether an object is a rock or a mine based on sonar data. With an accuracy of **83.33%** on the test set, the model has shown strong predictive power.


