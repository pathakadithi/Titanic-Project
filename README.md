# Titanic-Project
Titanic Dataset Preprocessing 🚢
📌 Project Overview : 
    This project focuses on data preprocessing and cleaning of the Titanic dataset.
    The goal is to prepare the data for machine learning models by handling missing values, encoding categorical variables, scaling             numerical features, and removing outliers.

1. Import Dataset
  * Loaded Titanic dataset (Titanic-Dataset.csv) using pandas.
  * Explored data shape, column names, data types, and missing values.

2. Handle Missing Values
  * Imputed numerical features using mean/median.
  * Imputed categorical features using most frequent value.

3. Convert Categorical to Numerical
  * Applied One-Hot Encoding to categorical features (Sex, Embarked, etc.).

4. Normalize/Standardize Numerical Features
  * Standardized features like Age, Fare, SibSp, Parch using StandardScaler.

5. Outlier Detection & Removal
  * Visualized outliers using boxplots.
  * Removed extreme values (e.g., very high Fare, unrealistic Age) using the IQR method.

6. Train/Test Split
  * Split dataset into train (80%) and test (20%) for model training.

7. Save Preprocessed Data
  * Exported cleaned dataset as titanic_preprocessed.csv for further ML experiments.

.

📊 Tools & Libraries Used :

1. Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
2. Google Colab for preprocessing and visualization
3. GitHub for version control and sharing
