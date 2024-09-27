# Customer Churn Prediction for Telecom

### Project Overview:
This project aims to predict customer churn for a telecom company using various Machine Learning Techniques. By leveraging historical customer data, this project helps the telecom company identify which customers are likely to leave, enabling them to take actions to improve retentions.

# Data Description:
- **TelecomCustomer-Churn1.csv**: Contains customers demographic and service data
- **TelecomCustomer-Churn2.csv**: Contains additional account and billing information.
- **Churn Column**: Identifies whether the customer has churned (1) or not (0).

### Project Workflow:
1. **Data Understanding & Exploration**: Initial data understanding, merging dataset, and checking for missing values and duplicaties.
2. **Data Cleaning & Preprocessing**:
   - Imputing missing values.
   - Encoding categorical features.
   - Standardizing/Normalizing the continuous features.
3. **Model Building**:
   - Initial model using **Decision Tree** and hyperparameter tuning with Grid Search.
   - Additional models built using **Random Forest**, **AdaBoost** and **GradientBoost**.
4. **Performance Evaluation**:
   - Models evaluated based on accuracy, precision, recall and F1-Score.
5. **Final Model Selection**: Based on train/test accuracy and generalization capabilities.

### Technologies Used:
- Python (Pandas, Numpy, Scikit-learn, Matplotlib)
- Jupyter Notebook
- Machine Learning (Decision Trees, RandomForest, AdaBoost, GradientBoost)
