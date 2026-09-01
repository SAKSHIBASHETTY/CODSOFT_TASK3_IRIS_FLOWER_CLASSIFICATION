# CODSOFT_TASK3_IRIS_FLOWER_CLASSIFICATION
# 🌸 Iris Flower Classification

## 📌 Project Overview

This project focuses on building a machine learning classification model to classify Iris flowers into three species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

The classification is performed using sepal and petal measurements from the Iris dataset.

## 🎯 Objective

The objective of this project is to develop a machine learning model that learns from the measurements of Iris flowers and accurately classifies them into their respective species.

## 📊 Dataset

The project uses the `IRIS.csv` dataset.

### Dataset Features

- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`

### Target Variable

- `species`

The original dataset contained **150 records and 5 columns**.

After checking for duplicate records, **3 duplicate rows were removed**, resulting in a final dataset of **147 records**.

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

- Loaded the `IRIS.csv` dataset using Pandas
- Checked the dataset structure and data types
- Checked for missing values
- No missing values were found
- Checked for duplicate records
- Removed 3 duplicate rows
- Encoded the species labels into numerical values for machine learning

## 📈 Exploratory Data Analysis

The following analysis and visualizations were performed:

- Species distribution
- Statistical summary of numerical features
- Feature relationship analysis using a pairplot
- Correlation analysis using a heatmap

### Correlation Analysis

Some important correlations observed were:

- Sepal Length vs Petal Length: **0.871**
- Sepal Length vs Petal Width: **0.817**
- Petal Length vs Petal Width: **0.962**

## 🤖 Machine Learning Models

Two classification models were trained:

1. Logistic Regression
2. Random Forest Classifier

The dataset was divided into training and testing sets using an 80:20 split.

## 📊 Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | **96.67%** |
| Random Forest Classifier | **96.67%** |

Both models achieved the same accuracy on the test dataset.

## 🏆 Final Model

Since both models achieved the same accuracy, **Logistic Regression** was selected as the final model because it provides the same classification performance with a simpler model.

### Final Results

- **Final Model:** Logistic Regression
- **Accuracy:** 96.67%
- **Test Samples:** 30
- **Correct Predictions:** 29
- **Incorrect Predictions:** 1

## 🌸 Prediction Example

The final model was tested using new flower measurements.

Example:

- Sepal Length: 6.5 cm
- Sepal Width: 3.0 cm
- Petal Length: 5.2 cm
- Petal Width: 2.0 cm

### Prediction

**Iris-virginica**

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 📁 Project Files

- `CODSOFT_TASK3_IRIS_FLOWER_CLASSIFICATION.ipynb` — Complete Google Colab notebook
- `IRIS.csv` — Dataset used for the project

## ✅ Conclusion

The project successfully developed a machine learning classification system for identifying Iris flower species using sepal and petal measurements.

Both Logistic Regression and Random Forest Classifier achieved an accuracy of **96.67%**. Logistic Regression was selected as the final model due to its simplicity while maintaining the same predictive performance.

This project demonstrates the application of data preprocessing, exploratory data analysis, feature engineering, classification algorithms, model evaluation, and prediction using machine learning.
