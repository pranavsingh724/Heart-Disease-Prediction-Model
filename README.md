# Heart-Disease-Prediction-Model
The Heart Disease Prediction System is a machine learning-based tool designed to assess an individual’s risk of heart disease using clinical data.  The system includes libraries like Panda, Matplotlib and scikit-learn and has key steps like data preprocessing, feature selection, and model training to ensure reliable results.

Data Collection and Preprocessing: 
  The dataset for this project is sourced from Kaggle, specifically the Cleveland Heart Disease Dataset, which contains patient records with features like age, sex, chest pain type, blood pressure, cholesterol 
  levels, and more, labeled with the presence or absence of heart disease.
  The data undergoes several preprocessing steps:
  Handling Missing Data: Missing values are either filled with mean/median (for numerical) or mode (for categorical) values, or records with excessive missing data are removed.
  Data Cleaning: Outliers and incorrect entries are identified and corrected to ensure valid ranges.
  Encoding Categorical Variables: Categorical features are encoded using techniques like one-hot or label encoding.
  Feature Scaling: Numerical features are standardized or scaled to ensure consistency across the dataset.
  Train-Test Split: The data is split into training and testing sets (typically 80:20 or cross validated) for model evaluation.
  Various machine learning algorithms are applied to predict heart disease:
  Logistic Regression: Used for binary classification, predicting the likelihood of heart disease.
  Random Forest: An ensemble method that improves accuracy by combining multiple decision trees.
  K-Nearest Neighbors (KNN): A simple algorithm based on feature similarity for classification.
  These models are trained on the preprocessed dataset and evaluated for performance.
 
Model Evaluation:
  The performance of the machine learning models is evaluated using metrics like:
  Accuracy: Percentage of correct predictions.
  Precision: Proportion of positive predictions that are actually correct.
  Recall: Ability to correctly identify positive cases.
  F1-Score: Harmonic mean of precision and recall.
  ROC-AUC: Measures the model's ability to distinguish between classes.
  Cross-validation is used to ensure the model generalizes well to unseen data
