# 🏷️ Label Encoding & Ordinal Encoding in Machine Learning

This repository demonstrates how to preprocess categorical data using **Ordinal Encoding** and **Label Encoding** in Python with Scikit-learn. It explains how to convert categorical features and target labels into numerical values before training a machine learning model.

The notebook follows a practical workflow, including loading a dataset, selecting features, splitting the data into training and testing sets, applying appropriate encoding techniques, and transforming categorical values into machine-readable format while avoiding data leakage.

## 🚀 Features

- Load and prepare a dataset using Pandas
- Select relevant feature columns
- Split data into training and testing sets
- Apply **OrdinalEncoder** to ordered categorical features
- Apply **LabelEncoder** to the target variable
- Transform train and test datasets correctly
- Understand encoder categories and class mappings
- Follow preprocessing best practices for machine learning

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## 📂 Project Structure

```
Label_encoder.ipynb
README.md
customer.csv
```

## 🎯 Learning Outcome

After completing this notebook, you will understand:

- When to use Ordinal Encoding
- When to use Label Encoding
- Difference between feature encoding and target encoding
- Why encoders should be fitted only on training data
- How to transform testing data using the trained encoder
- Best practices to prevent data leakage

## 📌 Prerequisites

Install the required libraries before running the notebook:

```bash
pip install pandas numpy scikit-learn
```

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open `Label_encoder.ipynb` in Jupyter Notebook or VS Code.
4. Ensure `customer.csv` is in the same directory.
5. Run the notebook cells sequentially.

## 📖 About

This notebook is part of my **Machine Learning Learning Journey**, where I document practical implementations of data preprocessing techniques using real datasets and Scikit-learn.

---

⭐ If you found this project helpful, consider giving the repository a star!
