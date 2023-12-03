# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  - Overall Accuracy: 99.2%
  - Healthy loan:
    -  Precision: 99.7%
    -   Recall: 99.5%
  - High-risk loan:
    - Precision: 84.7%
    - Recall: 91.0%



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  - Overall Accuracy: 99.2%
  - Healthy loan:
    -  Precision: 100%
    -   Recall: 99.4%
  - High-risk loan:
    - Precision: 84.1%
    - Recall: 99.04%



## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Both models demonstrated impressive accuracy, indicating strong overall performance. Notably, Model 2, which was trained on oversampled data, exhibits enhanced recall for the high-risk class compared to Model 1. The choice between the two models hinges on specific objectives. If the paramount goal is to pinpoint high-risk loans, Model 2 may be preferable due to its superior recall for the high-risk class. Business implications should be carefully weighed: Is accurately identifying high-risk loans of utmost importance, even if it leads to more false positives, or does a balanced performance take precedence? The decision should be guided by a nuanced consideration of precision and recall, taking into account the business context and priorities. Opting for Model 2 may be prudent if a more cautious approach, aimed at minimizing false negatives, is deemed necessary.
