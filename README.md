# credit-risk-classification

**Overview**
- This project utilizes a credit lending database to generate a binary classification model capable of determining whether a specific loan's attributes classify it as healhty or unhealhty.
- Process: Load data, define target outcome and input/features, train/test split, model compilation/fit, generate predictions via testing data, evaluation via confusion matrix and classification report

**Results**
- Logistic Model:
  - 'Healthy (0)' - precision: 1.00, recall: 0.99, F1-score: 1.00, Support: 18765
  - 'Unhealhty (1)' - precision: 0.85, recall: 0.91, F1-Score: 0.88, Support: 619
  - Overall Accuracy - F1-Score: 0.99, Support: 19384
  - Macro Avg - precision: 0.92, recall: 0.95, F1-Score: 0.94, Support: 19384
  - Weighted Avg - precision: 0.99, recall: 0.99, F1-Score: 0.99, Support: 19384
 
**Summary**
- The logistic regression model performs quite well with an overall accuracy score of 99%. Due to a larger sample size of healhty loans (0), the model performs the best at identifying healhty loans and slightly worse when compared to predicting unhealhty loans(1). Please refer to results above for specific performance metrics.
