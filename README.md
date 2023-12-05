# Predicting-Heart-Disease-using-Machine-Learning

1. **Data Loading and Exploration:**
   - The dataset is loaded from Kaggle, containing various features related to heart disease.
   - Exploratory data analysis (EDA) is performed to understand the data structure and characteristics.

2. **Data Preprocessing:**
   - Features (`X`) and target (`y`) variables are defined based on the dataset columns.
   - The dataset is split into training and testing sets using the `train_test_split` function.

3. **Model Selection:**
   - Three different classification models are chosen: Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest.
   - The models are initialized and stored in a dictionary (`models`).

4. **Model Training and Evaluation:**
   - A function (`fit_and_score`) is defined to train and evaluate each model on the training and testing sets.
   - The accuracy scores of the models are then compared, and a bar plot is generated for visual representation.

5. **K-Nearest Neighbors (KNN) Tuning:**
   - The code explores the performance of K-Nearest Neighbors with different numbers of neighbors, and the results are plotted.

6. **Hyperparameter Tuning:**
   - Randomized search is performed for hyperparameter tuning of Logistic Regression and Random Forest using `RandomizedSearchCV`.
   - The best parameters and the corresponding model scores are displayed.

7. **Grid Search:**
   - Further hyperparameter tuning is conducted using grid search for Logistic Regression.
   - The best parameters and the corresponding model scores are displayed.

8. **Model Evaluation Metrics:**
   - Confusion matrix, classification report, and ROC curve are utilized to evaluate the performance of the tuned Logistic Regression model.

9. **Cross-Validation:**
   - Cross-validation scores for accuracy, precision, recall, and F1 score are calculated and visualized using bar plots.

10. **Feature Importance:**
    - The coefficients of the Logistic Regression model are examined to determine feature importance.
    - Bar plots are generated to visualize the importance of each feature.

11. **Conclusion:**
    - The code concludes by displaying cross-validated metrics and feature importance, providing insights into the trained model's performance and the importance of different features in predicting heart disease.
