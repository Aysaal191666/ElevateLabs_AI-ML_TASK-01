# ElevateLabs_AI-ML_TASK-01
Data Cleaning &amp; Pre-processing task using the Titanic dataset
# 🧹 Task 1: Data Cleaning & Preprocessing

## 🔍 Objective
The goal of this task is to clean and preprocess raw data to make it suitable for machine learning models. This includes handling missing values, encoding categorical features, scaling numerical features, and identifying/removing outliers.

---

## 📁 Dataset
- **Name**: Titanic Dataset
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **File Used**: `titanic.csv`

---

## 🚀 Steps Performed

1. **Data Loading**: Loaded CSV file using Pandas.
2. **Exploratory Data Analysis**:
   - Viewed data structure and missing values.
3. **Missing Value Handling**:
   - Filled `Age` using median.
   - Filled `Embarked` using mode.
   - Dropped `Cabin` column due to many nulls.
4. **Categorical Encoding**:
   - Used One-Hot Encoding for `Sex` and `Embarked`.
5. **Feature Scaling**:
   - Used `StandardScaler` and `MinMaxScaler` on `Age` and `Fare`.
6. **Outlier Detection & Removal**:
   - Visualized with boxplots.
   - Removed outliers using IQR method.

---

## 🛠 Tools & Libraries Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn

---


