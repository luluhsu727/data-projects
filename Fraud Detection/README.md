**Credit Card Fraud Detection(H1)**

**Overview**
This project focuses on detecting fraudulent credit card transactions using machine learning. Our goal is to maximize fraud detection while maintaining a balance between precision and recall.

**Models Evaluated**
We tested the following models:

Random Forest

Gradient Boosting

XGBoost (Best Performing Model)

**Best Model: XGBoost**
Recall: 91% (threshold = 0.3)

Precision: 25% (threshold = 0.3)

Accuracy: 98% (threshold = 0.3)

F1-score: 39% (threshold = 0.3)

**Business Impact**
Fraud Prevention: Reduces financial losses by detecting fraudulent transactions early.

Customer Trust: Enhances reputation as a secure financial institution.

Operational Efficiency: Automates fraud detection, reducing manual review costs.

**Deployment & Future Improvements**
Deploy XGBoost in real-time transaction processing.

Continuously retrain the model to adapt to new fraud patterns.

Fine-tune classification thresholds for optimal fraud detection.

Improve customer communication to handle false positives effectively.
