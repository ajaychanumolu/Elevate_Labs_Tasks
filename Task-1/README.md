#  Titanic Dataset - Data Cleaning & Preprocessing

This project demonstrates how to clean and preprocess the Titanic dataset using Python, Pandas, and Scikit-learn. The goal is to prepare the dataset for machine learning by handling missing values, encoding categorical variables, scaling features, and splitting the data.

##  Dataset

The dataset used is the famous Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data), containing information about passengers and whether they survived the Titanic disaster.

##  Steps Performed

1. **Loading the Dataset**
2. **Cleaning the Data**
   - Removing irrelevant columns
   - Handling missing values (`Age`, `Embarked`)
3. **Encoding Categorical Features**
   - One-hot encoding for `Sex` and `Embarked`
4. **Scaling Numerical Features**
   - Standardization using `StandardScaler`
5. **Splitting into Train/Test Sets**

## Requirements

- Python 3.x
- pandas
- scikit-learn

Install requirements with:

```bash
pip install pandas scikit-learn
