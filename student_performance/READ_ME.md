# Student Performance Analysis and Prediction

### This Jupyter Notebook provides an end-to-end analysis and prediction of student performance using a synthetic dataset. The notebook explores the factors influencing academic success and builds a linear regression model to predict the **Performance Index** of students.

## 📋 Table of Contents
1. [Dataset Overview](#dataset-overview)
2. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Building](#model-building)
5. [Model Evaluation](#model-evaluation)
6. [Results and Export](#results-and-export)

---

## Dataset Overview

The dataset contains **10,000 synthetic student records** with the following features:
- **Hours Studied**
- **Previous Scores**
- **Extracurricular Activities**
- **Sleep Hours**
- **Sample Question Papers Practiced**

The target variable is the **Performance Index**, a score ranging from 10 to 100.

Source: [Kaggle - Student Performance Dataset](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression)

---

## Exploratory Data Analysis (EDA)

The notebook performs the following EDA steps:
- Distribution analysis of features and target variable.
- Correlation analysis using a heatmap.
- Outlier detection using boxplots and statistical methods.

---

## Data Preprocessing

The preprocessing steps include:
- Encoding categorical variables (e.g., `Extracurricular Activities`).
- Splitting the dataset into training and testing sets.

---

## Model Building

A **Linear Regression Model** is trained to predict the `Performance Index`. The model uses the following features:
- Hours Studied
- Previous Scores
- Sleep Hours
- Sample Question Papers Practiced
- Encoded Extracurricular Activities

---

## Model Evaluation

The model performance is evaluated using:
- **Mean Absolute Error (MAE)**: Measures the average deviation of predictions from actual values.
- **R-squared**: Indicates how well the model explains the variance in the target variable.

Additional visualizations include:
- Predicted vs Actual Performance Index
- Residual Plot
- MAE and R-squared Bar Chart

---

## Results and Export

The notebook generates a CSV file (`predictions.csv`) containing:
- Actual Performance Index
- Predicted Performance Index
- Features used for prediction

## Power BI report

This project also includes a PBIX file, where the data and linear regression model has been visualised in a Power BI report

---

## How to Use

1. Clone this repository and download the dataset from the [Kaggle link](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression).
2. Place the dataset (`Student_Performance.csv`) in the same directory as the notebook.
3. Run the notebook cells sequentially to reproduce the analysis and predictions.
4. Use Microsoft Power BI to open the .pbix file and view the Power BI report

---

## Requirements

The following Python libraries are required:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install them using `pip install pandas numpy matplotlib seaborn scikit-learn`

Download Microsoft Power BI Desktop from [Microsoft Power BI Desktop download link](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
