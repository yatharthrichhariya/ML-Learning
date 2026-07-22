# 🚢 Titanic Survival Prediction Using Scikit-Learn Pipeline

This project demonstrates how to build an end-to-end Machine Learning pipeline for predicting passenger survival on the Titanic dataset using Scikit-Learn. Instead of performing preprocessing manually, the complete workflow is automated using `Pipeline` and `ColumnTransformer`, making the model reusable, organized, and production-friendly.

---

## 📌 Project Overview

The project follows a structured machine learning workflow by combining data preprocessing, feature engineering, feature selection, model training, and prediction into a single pipeline.

The pipeline ensures that every transformation applied during training is also applied consistently during prediction, reducing data leakage and simplifying deployment.

---

## ✨ Features

- Automated data preprocessing using Scikit-Learn Pipeline
- Missing value imputation
- Categorical feature encoding
- Feature scaling
- Feature selection using SelectKBest
- Decision Tree Classifier for prediction
- Hyperparameter tuning with GridSearchCV
- Clean and modular ML workflow

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-Learn
- Jupyter Notebook

---

## 📂 Workflow

1. Load Titanic dataset
2. Split data into training and testing sets
3. Handle missing values
4. Encode categorical variables
5. Scale numerical features
6. Select important features
7. Train Decision Tree model
8. Tune hyperparameters using GridSearchCV
9. Evaluate model performance
10. Make predictions using the trained pipeline

---

## 📚 Concepts Covered

- Pipeline
- ColumnTransformer
- SimpleImputer
- OneHotEncoder
- MinMaxScaler
- SelectKBest
- Chi-Square Feature Selection
- Decision Tree Classifier
- GridSearchCV
- Model Evaluation

---

## 📈 Benefits of Using Pipeline

- Prevents data leakage
- Keeps preprocessing and model together
- Simplifies training and prediction
- Makes code cleaner and reusable
- Easy deployment for real-world applications

---

## 🚀 Future Improvements

- Try multiple classification algorithms
- Perform feature engineering
- Optimize hyperparameters further
- Save the trained pipeline using Pickle
- Deploy the model using Flask or Streamlit

---

## 📖 Learning Outcome

This project provides practical experience in building a complete machine learning workflow using Scikit-Learn Pipelines. It demonstrates how preprocessing, feature selection, and model training can be combined into a single reusable pipeline for efficient and reliable predictions.

---

## 👨‍💻 Author

**Yatharth Richhariya**

BBA – Business Intelligence & Analytics  
Learning Machine Learning, Data Analytics, and Artificial Intelligence through hands-on projects.

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
