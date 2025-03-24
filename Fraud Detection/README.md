# Credit Card Fraud Detection Report

## Executive Summary
To establish itself as the safest option in the U.S. credit card market, [Company Name] developed a machine learning model to detect fraudulent transactions. XGBoost was found to be the most effective model for balancing fraud detection accuracy and recall, prioritizing fraud detection while accepting some false positives for maximum security.

## Problem Overview
Credit card fraud costs financial institutions billions each year. The challenge is to detect fraud effectively without blocking too many legitimate transactions. Our approach prioritizes fraud detection over avoiding false positives, in line with our risk-averse strategy.

## Key Insights
- **Best Model: XGBoost** achieved:
  - **Recall:** 91% (threshold = 0.3), significantly higher than other models.
  - **Precision:** Lower than other models, but this trade-off is acceptable to catch more fraud.
  - **F1-score:** 39% at threshold = 0.3.
  - **Accuracy:** 98% at threshold = 0.3.
  
- **Random Forest** had high precision (83%) but lower recall (65%) at default settings.
- **Gradient Boosting** showed high recall (87%) but very low precision (21%).

## Model Performance in the Context of Business Goals
XGBoost is preferred for its high recall, helping to identify 91% of fraudulent transactions. While precision suffers, it aligns with our goal of detecting as many fraudulent transactions as possible.

## Business Impact
- **Fraud Prevention:** Early fraud detection reduces potential financial losses.
- **Customer Trust:** A proactive fraud detection model strengthens trust and retention.
- **Operational Efficiency:** Automating detection reduces manual intervention and speeds up responses.

## Recommendations
1. **Fine-Tune the Model:**
   - Further improve recall by adjusting thresholds and combining multiple models.
   - Refine features by incorporating real-time data and external fraud databases.
2. **Real-Time Deployment:**
   - Implement in real-time transaction processing systems.
   - Integrate with existing security measures like spending habits and anomaly detection.
3. **Continuous Monitoring:**
   - Retrain models periodically to adapt to evolving fraud patterns.
   - Track false positives and customer feedback to refine thresholds.
4. **Customer Communication:**
   - Provide easy verification for flagged transactions.
   - Enhance customer experience with added security options.

## Conclusion
XGBoost is the optimal model for fraud detection, balancing recall and precision. By deploying it in real-time, adjusting thresholds, and continuously monitoring performance, [Company Name] can prevent financial losses and enhance customer satisfaction.

## Model and Data Access
For further review, the trained model, code, and dataset are available at:  
[GitHub Repository](https://github.com/luluhsu727/data-science-portfolio/tree/main/Fraud%20Detection)
