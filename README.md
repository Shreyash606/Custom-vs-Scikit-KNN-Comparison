# Custom vs Scikit KNN Comparison

## Overview
This project compares the performance of custom k-NN (k-Nearest Neighbors) algorithm implementation with the k-NN algorithm provided by the scikit-learn library. The comparison is conducted on a breast cancer dataset using 10-fold cross-validation. The objective is to assess the accuracy and efficiency of the custom implementation against the widely-used scikit-learn implementation.

## Dataset
The breast cancer dataset used in this project is sourced from the UCI Machine Learning Repository. It consists of features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The dataset contains 286 instances with 9 features each.

## Algorithms
### Custom KNN Algorithm
The custom k-NN algorithm is implemented from scratch, including functions for calculating Minkowski distance, Euclidean distance, cross-validation, and prediction.

### Scikit-learn KNN Algorithm
Scikit-learn's KNeighborsClassifier is utilized to implement the k-NN algorithm using the same dataset and cross-validation setup as the custom implementation.

## Evaluation
The performance of both custom and scikit-learn k-NN algorithms is evaluated using 10-fold cross-validation. Accuracy scores are computed for each fold, and the average accuracy across all folds is calculated for comparison.

## Hypothesis Testing
A paired t-test is performed to determine if there is a significant difference between the performance of the custom and scikit-learn k-NN algorithms. The null hypothesis states that there is no significant difference in accuracy between the two implementations.

## Results
The average accuracy of both custom and scikit-learn k-NN algorithms is reported along with the results of the hypothesis testing. The significance level (alpha) is set to 0.05.

## Conclusion
Based on the results of the comparison and hypothesis testing, conclusions are drawn regarding the performance and efficiency of the custom k-NN implementation relative to the scikit-learn implementation.

## Usage
1. Ensure Python and necessary dependencies are installed.
2. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Custom-vs-Scikit-KNN-Comparison.git
   ```
3. Navigate to the project directory and run the main Python script:
   ```bash
   cd Custom-vs-Scikit-KNN-Comparison
   python main.py
   ```



---

