# Classification with Logistic Regression

## Objective

The objective of this project is to build a binary classification model using Logistic Regression. The model predicts whether a tumor is malignant or benign using the Breast Cancer Wisconsin Dataset.

## Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Dataset

Breast Cancer Wisconsin Dataset from Scikit-learn.

Dataset Information:

* Total Samples: 569
* Features: 30
* Target Classes:

  * 0 = Malignant
  * 1 = Benign

## Steps Performed

1. Imported required libraries.
2. Loaded the Breast Cancer Wisconsin Dataset.
3. Split the dataset into training and testing sets.
4. Standardized the feature values using StandardScaler.
5. Trained a Logistic Regression model.
6. Generated predictions on the test dataset.
7. Evaluated model performance using:

   * Accuracy
   * Precision
   * Recall
   * ROC-AUC Score
   * Confusion Matrix
8. Plotted the ROC Curve.
9. Visualized the Sigmoid Function.
10. Performed Threshold Tuning using different probability thresholds.

## Evaluation Metrics

The following metrics were calculated:

* Accuracy
* Precision
* Recall
* ROC-AUC Score
* Confusion Matrix

## Results

Example output:

```text
Accuracy      : 0.97
Precision     : 0.97
Recall        : 0.99
ROC-AUC Score : 0.99
```

*Results may vary slightly depending on train-test split and random state.*

## Threshold Tuning

Different thresholds were tested:

* Threshold = 0.3
* Threshold = 0.5
* Threshold = 0.7

Observations:

* Lower thresholds generally increase Recall.
* Higher thresholds generally increase Precision.
* Threshold selection depends on the problem requirements.

## Sigmoid Function

The sigmoid function converts any real-valued number into a probability between 0 and 1.

Formula:

```text
σ(x) = 1 / (1 + e^(-x))
```

It is used by Logistic Regression to estimate the probability of belonging to a particular class.

## Key Learnings

* Binary Classification
* Logistic Regression
* Feature Scaling
* Confusion Matrix
* Precision and Recall
* ROC-AUC Score
* Threshold Tuning
* Sigmoid Function

## Conclusion

A Logistic Regression model was successfully built and evaluated on the Breast Cancer Wisconsin Dataset. The model achieved high classification performance and demonstrated the effectiveness of Logistic Regression for binary classification problems.
