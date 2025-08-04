# Titanic Dataset - Data Cleaning & Preprocessing 

## Task Objective
This project is part of an **AI & ML Internship** aimed at understanding the essentials of data preprocessing — a crucial first step in any machine learning pipeline.

---

##  Dataset
The dataset used is the classic [Titanic Dataset](https://www.kaggle.com/competitions/titanic/data), which contains information about passengers aboard the Titanic.

---

##  Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- scikit-learn

---

## Tasks Performed

### 1. **Data Exploration**
- Checked data types and missing values.
- Observed the shape and basic statistics of the dataset.

### 2. **Handling Missing Values**
- `Age`: Filled using **median**.
- `Embarked`: Filled using **mode**.
- `Cabin`: Dropped due to excessive missing data.

### 3. **Encoding Categorical Variables**
- Used **Label Encoding** for `Sex` and `Embarked`.

### 4. **Feature Scaling**
- Applied **StandardScaler** to normalize `Age` and `Fare`.

### 5. **Outlier Detection & Removal**
- Used **Interquartile Range (IQR)** to identify and remove outliers from `Age` and `Fare`.

### 6. **Data Export**
- Exported the cleaned dataset to `titanic_cleaned_dataset.csv`.

---

## Visualizations
Boxplots were generated to visualize outliers in:
- Age
- Fare

_Image saved as `outliers_boxplot.png`_

---

## Files Included
- `Titanic-Dataset.csv` – Original dataset
- `titanic_cleaned_dataset.csv` – Cleaned dataset
- `data_cleaning.py` – Python code for preprocessing
- `outliers_boxplot.png` – Visualization of outliers
- `README.md` – This file

---

##  What I Learned
- Dealing with missing data
- Label encoding vs one-hot encoding
- Feature scaling: **Normalization vs Standardization**
- Outlier detection using IQR
- Importance of preprocessing in improving model accuracy


