## Employee Turnover Prediction Project

### Overview
This project focuses on predicting employee turnover using machine learning techniques. The dataset used contains information about employees such as satisfaction level, last evaluation, number of projects, average monthly hours, time spent in the company, work accidents, promotions in the last 5 years, department, and salary level.

### Data Preprocessing
- The dataset was loaded using pandas and checked for missing values.
- Categorical variables were transformed into dummy variables for modeling.
- Unnecessary columns were dropped after creating dummy variables.

### Feature Selection
- Recursive Feature Elimination (RFE) with Logistic Regression was used to select the best features for predicting employee turnover.
- 10 features were selected based on the RFE rankings.

### Model Building
- Logistic Regression and Random Forest Classification models were trained on the selected features.
- The dataset was split into training and testing sets using `train_test_split`.

### Model Evaluation
- The accuracy of both models was evaluated using `accuracy_score`.
- Confusion matrices and classification reports were generated to assess model performance.
- ROC curves were plotted to visualize the performance of the models.

### Feature Importance
- The feature importance of the Random Forest model was analyzed to identify the most influential factors in predicting employee turnover.
- The most important feature was found to be the **satisfaction level**.

### Conclusion
- The Random Forest model outperformed the Logistic Regression model in predicting employee turnover.
- The satisfaction level was identified as the most crucial feature affecting employee turnover.

### Instructions
1. Ensure you have the necessary libraries installed (pandas, scikit-learn, seaborn, matplotlib).
2. Run the provided code in a Jupyter notebook or Python environment.
3. Analyze the results and explore further insights from the data and models.

### Future Steps
- Experiment with different models and hyperparameters to improve prediction accuracy.
- Explore additional features or external datasets to enhance the model's performance.

**Happy Coding!** 🙇‍♂️
