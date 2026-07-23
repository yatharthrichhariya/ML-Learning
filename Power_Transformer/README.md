# 🔄 Power Transformer in Machine Learning

This repository demonstrates how to use **Power Transformer** techniques to improve data distribution and enhance the performance of machine learning models. The notebook applies **Box-Cox** and **Yeo-Johnson** transformations on the Concrete Strength dataset and compares model performance before and after transformation using **Linear Regression**.

---

## 📌 Project Overview

Power Transformation is a feature engineering technique used to make data more Gaussian (normally distributed). It helps reduce skewness, stabilize variance, and improve the performance of algorithms that assume normally distributed data.

This notebook covers:
- Loading and exploring the dataset
- Data preprocessing
- Training a Linear Regression model without transformation
- Applying **Box-Cox Transformation**
- Applying **Yeo-Johnson Transformation**
- Comparing model performance using **R² Score** and **Cross Validation**
- Visualizing feature distributions before and after transformation

---

## 📂 Dataset

- **Dataset:** `concrete.csv`
- **Target Variable:** `strength`

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

---

## 📚 Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.linear_model import LinearRegression
from sklearn.preprocessing import PowerTransformer

from scipy import stats
```

---

## 📈 Workflow

1. Import required libraries
2. Load the dataset
3. Perform exploratory data analysis (EDA)
4. Split the data into training and testing sets
5. Train a baseline Linear Regression model
6. Evaluate the model
7. Apply Box-Cox Transformation
8. Retrain and evaluate the transformed data
9. Apply Yeo-Johnson Transformation
10. Compare model performance
11. Visualize the transformed distributions

---

## 📊 Model Evaluation

The notebook evaluates the model using:

- R² Score
- Cross Validation Score

Performance is compared:

- Before applying Power Transformation
- After Box-Cox Transformation
- After Yeo-Johnson Transformation

---

## 📉 Visualizations

The notebook contains visualizations such as:

- Distribution plots
- Q-Q plots
- Before vs After transformation comparisons
- Lambda values of transformations

These graphs help understand how Power Transformation improves feature distributions.

---

## 🎯 Learning Outcomes

By completing this notebook, you will learn:

- What is Power Transformation
- Why Power Transformation is required
- Difference between Box-Cox and Yeo-Johnson
- When to use each transformation
- How transformed features improve Linear Regression performance
- How to evaluate models after feature transformation

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
```

### Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn
```

### Launch the Notebook

```bash
jupyter notebook "Power Transformer.ipynb"
```

Run all the cells sequentially.

---

## 📁 Repository Structure

```
Power Transformer/
│
├── Power Transformer.ipynb
├── concrete.csv
└── README.md
```

---

## ⭐ Key Concepts Covered

- Feature Engineering
- Power Transformation
- Box-Cox Transformation
- Yeo-Johnson Transformation
- Distribution Normalization
- Linear Regression
- Cross Validation
- Model Evaluation
- Data Preprocessing

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, improve the notebook, and submit a pull request.

---

## 📜 License

This project is intended for educational and learning purposes.
