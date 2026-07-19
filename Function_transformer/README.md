# 📘 FunctionTransformer in Scikit-learn

This repository demonstrates how to use **FunctionTransformer** from **Scikit-learn** to apply custom mathematical transformations to features before training machine learning models. Using the **Titanic dataset**, the notebook shows how transformations such as logarithmic scaling can improve feature distributions and potentially enhance model performance.

## 📌 Overview

The notebook covers the complete workflow of applying function-based transformations, including:

- Loading and preparing the Titanic dataset
- Selecting relevant features (`Age`, `Fare`, and `Survived`)
- Handling missing values
- Exploring feature distributions
- Applying `FunctionTransformer` with built-in functions like `np.log1p`
- Creating custom transformation functions
- Using `ColumnTransformer` to transform selected columns
- Splitting data into training and testing sets
- Training machine learning models
- Evaluating model performance using accuracy and cross-validation
- Comparing results before and after feature transformation

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Dataset

- **Dataset:** Titanic Dataset
- **Features Used:**
  - Age
  - Fare
  - Survived (Target)

## 🎯 Learning Outcomes

After completing this notebook, you will understand how to:

- Use `FunctionTransformer` for feature engineering.
- Apply mathematical transformations without manually modifying datasets.
- Create and use custom transformation functions.
- Integrate transformations into Scikit-learn pipelines.
- Improve feature distributions for machine learning models.
- Evaluate the impact of transformed features on model performance.

## 🚀 Who is this for?

This notebook is suitable for:

- Beginners learning Feature Engineering
- Data Science students
- Machine Learning enthusiasts
- Anyone exploring Scikit-learn preprocessing techniques

## 📄 Conclusion

`FunctionTransformer` is a simple yet powerful preprocessing tool that allows custom feature transformations while maintaining compatibility with Scikit-learn workflows. This notebook provides practical examples of applying both built-in and custom functions, making it an excellent resource for understanding feature transformation in machine learning projects.
