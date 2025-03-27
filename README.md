# Credit-Risk-Classification

## Credit Risk Analysis Report

### Overview  
The goal was to figure out whether someone was likely to default on a loan or not. A logistic regression model was trained to classify loans as either healthy or high-risk based on the features in the dataset. The point of the analysis was to see if the model could catch red flags before loans go out.

---

### Model Performance  
Quick breakdown of the model’s results:

- **Accuracy**: 0.99  
- **Precision (Healthy Loans - 0)**: 1.00  
- **Precision (High-Risk Loans - 1)**: 0.84  
- **Recall (Healthy Loans - 0)**: 0.99  
- **Recall (High-Risk Loans - 1)**: 0.94  
- **F1-Score (High-Risk Loans)**: 0.89

---

### Summary & Recommendation  
The model was on point when it came to catching healthy loans. Most high-risk loans were caught too, though it missed a few. Still, performance was strong overall.

The logistic regression model crushed it on accuracy and recall. It flagged healthy loans almost perfectly and did a solid job picking up on high-risk ones too. Precision for risky loans wasn't perfect, but still strong enough to trust in a fast-paced workflow. Would definitely recommend the model for the company. It can help speed up decisions without losing much reliability. Human review should still back it up, but this model gives a solid head start when spotting loan risks early.
