# Bank-Customer-Churn-Model
In this project, the aim is to develop a predictive model that determines whether a bank customer is likely to churn or not. Customer churn refers to the situation where a customer terminates their relationship with a business, and predicting it can help the bank take proactive measures to retain valuable customers.


#DATASET

The dataset used for this project contains information about bank customers, including their credit scores, geographical location, gender, age, tenure, balance, number of products, credit card status, activity status, estimated salary, and whether they have exited the bank (churned) or not.



#WORKFLOW


1. Data Preprocessing: The dataset was thoroughly preprocessed. Categorical features like "Geography" and "Gender" were one-hot encoded for compatibility with machine learning algorithms. Numeric features were scaled using standard scaling to ensure fair comparisons.

2. Handling Imbalanced Data: Since churned customers are often a minority in the dataset, we employed techniques to handle imbalanced classes. This includes using oversampling, undersampling, and synthetic sampling (SMOTE) to create a balanced training dataset.

3. Model Selection and Training: Multiple machine learning models were evaluated for their predictive performance, including Logistic Regression, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Decision Tree, Random Forest, Gradient Boosting, and XGBoost. The dataset was split into training and testing sets, and each model was trained and evaluated.

4. Hyperparameter Tuning: The best-performing model, XGBoost, underwent hyperparameter tuning using Grid Search. This process involves systematically searching through a predefined parameter grid to find the optimal combination of hyperparameters.

5. Evaluation and Visualization: The performance of each model was evaluated using metrics such as accuracy, precision, and recall. Visualizations, including bar plots and distribution plots, were generated to help visualize the model evaluation results.
