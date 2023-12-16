# Wine-Quality-prediction
This project does a  classification task focused on predicting the quality of red wine based on various features. Here's a brief overview of the steps in the code:

1. **Data Import and Exploration:**
   - The code starts by importing necessary libraries such as NumPy, Matplotlib, Pandas, and Seaborn.
   - It reads a dataset ("winequality-red.csv") into a Pandas DataFrame and prints the first few rows of the dataset.

2. **Data Analysis:**
   - It visualizes the distribution of features using box plots.

3. **Data Preprocessing:**
   - It creates a new binary target variable, 'goodquality,' where wines with a quality score of 7 or higher are labeled as 1, and others are labeled as 0.
   - It separates the feature variables (X) from the target variable ('goodquality').

4. **Model Training:**
   - It uses an Extra Trees Classifier to determine the importance scores of each feature.
   - It splits the dataset into training and testing sets.
   - It trains several classification models, including Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, Decision Tree, Gaussian Naive Bayes, Random Forest, and XGBoost.
   - The accuracy scores of each model on the test set are printed.

5. **Model Comparison:**
   - The accuracy scores of each model are summarized in a DataFrame ('results').

6. **Results Display:**
   - The final DataFrame ('result_df') is created to display and compare the accuracy scores of different models in descending order.

In summary, the project aims to compare the performance of various classification algorithms in predicting whether a red wine is of good quality based on its features. The models are trained, and their accuracy scores are presented in a tabular format for easy comparison.
