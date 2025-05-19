🏡USA Housing Price Prediction 
📌 Project Overview
This project implements Linear Regression to predict house prices using the USA_Housing dataset from Kaggle. The dataset consists of various features like Avg. Area Income, Avg. Area House Age, Avg. Area Number of Rooms, Price, etc.
⚙️ Key Steps
1️⃣ Data Loading: Importing the dataset from Kaggle.
2️⃣ Data Exploration: Using info(), isnull() to check missing values and data structure.
3️⃣ Data Visualization:
  - Distribution Plot (displot) – Checking normality of feature distributions.
  - Boxplot – Detecting outliers.
  - IQR Method – Handling outliers.
  - Pairplot – Understanding relationships between features.
4️⃣ Data Preprocessing:
  - Splitting data (train_test_split).
  - Standardizing features (StandardScaler).
5️⃣ Model Training:
  - Applying Linear Regression to predict housing prices.
  - Evaluating model performance using R² score (90%).
📊 Results
  - The model achieved an R² score of 90%, indicating strong predictive accuracy.
  - It provides meaningful insights into house pricing trends in the dataset
