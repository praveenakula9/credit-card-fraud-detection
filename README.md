# credit-card-fraud-detection
Detect fraudulent credit card transactions using machine learning models like Logistic Regression, Random Forest, and XGBoost. The project addresses class imbalance through oversampling and evaluates models using accuracy, precision, recall, and F1-score.
# Problem Statement
Credit card fraud is a significant issue in the financial sector. The goal is to build a machine learning model that can effectively identify fraudulent transactions while minimizing false positives.
# Dataset
📁 [Download Dataset](https://drive.google.com/file/d/1Zf163ZWz50fqnRgf1odqJjtImYJDSYZm/view?usp=drive_link)
- Features:
  - Time, Amount, V1 to V28 (PCA components)
  - Class (0 = Non-Fraud, 1 = Fraud)
# Technologies & Libraries Used
- Python 
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Imbalanced-learn (`OverSampling`)
- XGBoost
# Machine Learning Models
- Logistic Regression
- Random Forest
- XGBoost
# Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
# Visualizations
- Class distribution before and after oversampling
- Confusion matrix for each model
# Steps Followed
1. Load all Dependencies
   
    - Numpy
    - Pandas
    - Classification metrics
    - Classification Models
      
2. Data Exploration
   
    - Checked for null values
    - Examined class distribution (legit vs fraud)
      
3. Preprocessing

    - Standardized Amount and Time features using StandardScaler
    
4. Handling imbalance data

    - Applied Oversampling (SMOTE or RandomOverSampler) on the minority class
    - Tested mean imputation for missing values
    
5. Model Training

    - Logistic Regression
    - Random Forest
    - XGBoost
      
6. Model Evaluation

    - Confusion Matrix
    - Accuracy
    - Precision
    - Recall
    - F1 Score
  
# Conclusion
This project demonstrates how machine learning can be effectively applied to detect fraudulent credit card transactions by addressing class imbalance and using multiple evaluation metrics to ensure performance.
