# Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this analysis was to build a machine learning model that predicts the likelihood of a loan being either healthy or high-risk. By using logistic regression, we aimed to evaluate the model's ability to accurately classify loans based on the given data, helping the company assess credit risk and make informed lending decisions.

## Results
### Model Performance Metrics

    Accuracy: 99.1%
        The model correctly classified loans 99.1% of the time.
    Precision:
        Healthy loans (0): 99.4%
        High-risk loans (1): 84.5%
            Indicates the proportion of loans predicted as healthy/high-risk that are actually correct.
    Recall:
        Healthy loans (0): 99.8%
        High-risk loans (1): 94.0%
            Represents the model's ability to identify actual healthy and high-risk loans.

## Confusion Matrix

[[18658,   107],  # Healthy loans: True Positives, False Positives
 [   37,   582]]  # High-risk loans: False Negatives, True Negatives

## Summary

The logistic regression model demonstrated excellent performance, achieving an overall accuracy of 99.1%. The model is highly effective in predicting healthy loans, with precision and recall both exceeding 99%. For high-risk loans, the model achieved a precision of 84.5% and recall of 94.0%, indicating a strong ability to identify risky loans while minimizing false negatives.
Recommendation

We recommend the logistic regression model for use by the company because:

    It provides a reliable way to identify high-risk loans, reducing the likelihood of default.
    The high accuracy and recall for high-risk loans ensure that most potential risks are flagged effectively.
    The low number of false positives and negatives minimizes operational inefficiencies.

If the company requires further improvements, such as reducing false positives, additional fine-tuning or alternative algorithms (e.g., ensemble methods) can be explored.