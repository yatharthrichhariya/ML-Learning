# 🚢 Titanic Survival Prediction (Without Pipeline)

This project demonstrates a complete Machine Learning workflow on the Titanic dataset **without using Scikit-learn Pipelines**. Each preprocessing step is performed manually, making it ideal for beginners who want to understand how data transformation works behind the scenes before learning pipelines.

---

## 📌 Project Overview

The notebook walks through the entire ML process, including:

- Loading the Titanic dataset
- Data preprocessing
- Handling missing values
- Encoding categorical features
- Splitting data into training and testing sets
- Training a Decision Tree Classifier
- Evaluating model performance
- Saving trained preprocessing objects and model using Pickle

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Pickle

---

## 📂 Workflow

### 1. Data Loading
- Import Titanic dataset
- Explore the dataset

### 2. Data Cleaning
- Remove unnecessary columns
- Check missing values

### 3. Train-Test Split
- Split features and target
- Create training and testing datasets

### 4. Missing Value Imputation
- Handle missing values in numerical columns
- Handle missing values in categorical columns

### 5. Feature Encoding
- One-Hot Encoding for categorical features
- Manual preprocessing without Pipeline

### 6. Feature Combination
- Concatenate transformed numerical and categorical features

### 7. Model Training
- Train a Decision Tree Classifier

### 8. Model Evaluation
- Predict survival
- Calculate Accuracy Score

### 9. Model Saving
Save the trained objects using Pickle:
- Decision Tree Model
- One-Hot Encoder
- Other preprocessing objects

---

## 📁 Project Structure

```
Titanic-Without-Pipeline/
│
├── Titanic without using pipeline.ipynb
├── Titanic.csv
├── models/
│   ├── model.pkl
│   ├── ohe_sex.pkl
│   └── ...
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Titanic-Without-Pipeline.git
```

2. Install dependencies

```bash
pip install pandas numpy scikit-learn
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells sequentially.

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

- Manual preprocessing in Machine Learning
- Train-Test Split
- Missing Value Imputation
- One-Hot Encoding
- Feature Engineering
- Decision Tree Classification
- Model Evaluation
- Saving ML models using Pickle
- Why Pipelines are useful by understanding the manual approach first

---

## 📚 Future Improvements

- Implement the same workflow using Scikit-learn Pipeline
- Try different ML algorithms
- Perform Hyperparameter Tuning
- Add Cross Validation
- Build a Prediction Web App

---

## ⭐ If you found this project helpful, consider giving it a star on GitHub!
