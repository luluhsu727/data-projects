# Breast Cancer Diagnosis Prediction - README

## Objective
The goal of this analysis is to predict whether breast cancer is **benign (B)** or **malignant (M)** using machine learning models.

## Data Overview
The dataset includes features from breast cancer biopsies (e.g., mean radius, texture, area) with a target variable, **'diagnosis'**, indicating benign or malignant tumors.

## Data Preprocessing
- **Erroneous Data Removal**: Removed incorrect 'diagnosis' values.
- **Label Encoding**: Converted the target variable to numerical values (0 = benign, 1 = malignant).
- **Missing Values**: Imputed missing data with column averages.
- **Feature Selection**: Dropped the 'id' column.

## Models Used
- **Random Forest Classifier**
- **Logistic Regression**
- **Gradient Boosting Classifier**

These models were configured to handle class imbalance effectively.

## Model Training & Evaluation
Models were trained on 80% of the data and evaluated on accuracy, precision, recall, F1 score, and AUC-ROC.

## Results
| Model                | Accuracy | Precision | Recall  | F1 Score | AUC-ROC |
|----------------------|----------|-----------|---------|----------|---------|
| Random Forest        | 96.4%    | 95.3%     | 95.3%   | 95.3%    | 99.6%   |
| Logistic Regression  | 96.4%    | 97.5%     | 93.0%   | 95.2%    | 99.6%   |
| Gradient Boosting    | 96.4%    | 97.5%     | 93.0%   | 95.2%    | 99.5%   |

**Key Insights**: 
- **Random Forest** outperforms the other models in precision, recall, and AUC-ROC, making it the best choice for identifying malignant tumors.

## Feature Importance
Top 3 important features in the **Random Forest model**:
1. Area worst
2. Concave points worst
3. Concave points mean

## Next Steps
- **Deploy the Random Forest model** for real-world use.
- **Ongoing Monitoring**: Set up regular retraining with new data.
- **Further Investigation**: Explore more advanced models like deep learning.

## Recommendations
1. Deploy **Random Forest** due to its high performance.
2. Monitor the model and retrain periodically.
3. Investigate key features further for improved diagnosis.

## Access
Code and model available at:  
[GitHub Repository](https://github.com/yourusername/breast-cancer-diagnosis-prediction)


