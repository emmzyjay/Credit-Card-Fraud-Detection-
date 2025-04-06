# Credit-Card-Fraud-Detection-
A machine learning-based fraud detection system that identifies suspicious credit card transactions in real-time using XGBoost. Designed for FinTech applications.
this project includes: 

### Key Features 
✔ **Machine Learning Model**: 
   - Trained on imbalanced data (284,807 transactions, 492 frauds). 
   - Uses **XGBoost** (optimized via Bayesian hyperparameter tuning). 
   - Achieves **96% precision** and **83% recall**. 

✔ **Smart Thresholding**: 
   - Dynamically adjusts fraud alerts to minimize costs: 
     - **False Positive Cost**: $10 (customer service). 
     - **False Negative Cost**: $500 (fraud loss). 

✔ **Data Engineering**: 
   - Handles class imbalance with **SMOTE oversampling**. 
   - Scales features using **StandardScaler**. 
