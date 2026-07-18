# 📊 Column Transformer using Scikit-learn

This repository demonstrates how to use **ColumnTransformer** from **Scikit-learn** to preprocess different types of features in a dataset within a single pipeline. It shows how numerical and categorical columns can be transformed using appropriate preprocessing techniques before training a machine learning model.

## 🚀 Overview

In machine learning, datasets often contain multiple types of features that require different preprocessing methods. Instead of applying transformations separately, **ColumnTransformer** allows multiple preprocessing steps to be applied to specific columns simultaneously, making the workflow cleaner, faster, and less error-prone.

This notebook provides a practical implementation using a real dataset and demonstrates how to combine multiple preprocessing techniques efficiently.

## 📌 Features

* Importing and exploring a dataset using Pandas
* Splitting data into training and testing sets
* Handling missing values with **SimpleImputer**
* Encoding ordinal categorical features using **OrdinalEncoder**
* Encoding nominal categorical features using **OneHotEncoder**
* Applying multiple preprocessing techniques using **ColumnTransformer**
* Transforming training data into a machine learning-ready format
* Creating a clean and reusable preprocessing pipeline

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

## 📂 Project Structure

```text
Column Transformer.ipynb   # Complete preprocessing implementation
```

## ▶️ Getting Started

1. Clone this repository.
2. Install the required libraries:

```bash
pip install pandas numpy scikit-learn jupyter
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run the notebook cells sequentially to understand how different preprocessing techniques are combined using `ColumnTransformer`.

## 🎯 Learning Outcomes

After completing this notebook, you will understand:

* Why different columns require different preprocessing techniques.
* How to preprocess numerical and categorical features together.
* How **ColumnTransformer** simplifies machine learning preprocessing.
* How to prepare datasets efficiently before model training.

## 📖 Conclusion

This project provides a beginner-friendly introduction to **ColumnTransformer**, one of the most useful preprocessing utilities in Scikit-learn. It demonstrates how multiple transformations can be combined into a single, organized workflow, making data preprocessing more efficient, scalable, and suitable for real-world machine learning projects.

---

⭐ If you found this project helpful, consider giving the repository a star!
