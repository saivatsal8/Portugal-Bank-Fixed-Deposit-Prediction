# Portugal-Bank-Fixed-Deposit-Prediction
This repository hosts a supervised learning project aimed at predicting client subscriptions to fixed deposit products offered by a Portuguese bank. Using the publicly available dataset from the UCI Machine Learning Repository, the project explores various machine learning algorithms to forecast which clients are most likely to subscribe to a FD
Approach
Several supervised learning models were implemented and evaluated:

Logistic Regression: A fundamental yet powerful binary classification model that provides interpretable insights into the influence of individual features.
Decision Tree Classifier: A tree-based model that splits data based on feature importance, offering simple, interpretable rules for classifying potential subscribers.
Random Forest Classifier: An ensemble approach that combines multiple decision trees to improve predictive accuracy, reduce overfitting, and increase robustness.
Methodology
The project begins with Data Preprocessing, which involves handling missing values, encoding categorical variables, and scaling numerical features. This ensures compatibility across models and improves model performance. Feature Selection was conducted to determine the most influential variables, helping to reduce noise and improve prediction accuracy.

Following preprocessing, each model was trained and evaluated using metrics like accuracy, AUC-ROC, precision, recall, and F1-score to gauge its effectiveness. Additionally, Hyperparameter Tuning was applied to optimize each model, particularly the Random Forest, enhancing its predictive performance.

Results and Insights
Among the models tested, Random Forest generally yielded the best overall performance due to its ability to capture complex interactions between features. Logistic Regression, while slightly less accurate, provided valuable interpretability, indicating which factors were most impactful in influencing client subscription behavior.

Repository Structure
data/: Original dataset
notebooks/: Jupyter notebooks for exploratory data analysis, model building, and evaluation
src/: Python scripts for data processing and model training
results/: Outputs and visualizations of model performance
Conclusion
This project highlights how machine learning can assist in targeted marketing efforts within the banking sector, ultimately helping financial institutions to improve campaign effectiveness and target clients more likely to subscribe to fixed deposits.
