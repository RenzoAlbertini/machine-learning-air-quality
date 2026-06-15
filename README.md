# Air Quality Prediction and Classification using Machine Learning

![Correlation Heatmap](images/decision_tree_model.pdf)

End-to-end Machine Learning project focused on air quality prediction and classification using real-world environmental data collected across Taiwan.

## Project Overview

This project explores a complete supervised Machine Learning workflow, from data preprocessing and feature engineering to model training, evaluation and interpretation.

The objective is to analyze air pollution indicators and develop predictive models capable of estimating air quality conditions using environmental measurements collected over multiple years.

---

## Dataset

**Taiwan Air Quality Index Dataset (2016–2024)**

The dataset contains millions of environmental observations and includes measurements such as:

* PM2.5
* PM10
* O3
* CO
* NO2
* SO2
* Wind speed and direction
* Geographical coordinates
* Temporal information

---

## Data Analysis

The initial phase focused on data cleaning, preprocessing and exploratory analysis to identify relationships between environmental variables and air quality indicators.

### Correlation Analysis

![Correlation Heatmap](images/correlation_heatmap.png)

The correlation matrix highlights strong relationships between pollutant concentrations and AQI-related variables, providing valuable insights for feature selection and model development.

---

## Machine Learning Models

### Decision Tree Classification

A Decision Tree classifier was developed to predict air quality status categories from environmental measurements.

The model identifies the most relevant variables influencing air quality conditions and provides interpretable decision rules for classification tasks.

### Regression Analysis

![Regression Results](images/Multivariate_regression_plot.png)

Multivariate Linear Regression was used to estimate AQI values from pollutant concentrations and environmental measurements.

The regression model demonstrates a strong relationship between actual and predicted AQI values, providing a reliable baseline for air quality forecasting.

### Polynomial Regression

Polynomial Regression was implemented to capture non-linear relationships between environmental variables and AQI values, allowing comparison with standard linear approaches.

---

## Machine Learning Pipeline

### Data Preparation

* Missing value handling
* Feature selection
* Feature engineering
* Categorical encoding
* AQI discretization
* Correlation analysis

### Exploratory Data Analysis

* Statistical summaries
* Correlation heatmaps
* Scatter plots
* Feature relationship analysis

---

## Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib

---

## Repository Structure

```text
01_Data_Preprocessing.ipynb
02_Decision_Tree_Classification.ipynb
03_Linear_and_Polynomial_Regression.ipynb
```

---

## Key Topics

* Supervised Learning
* Classification
* Regression
* Feature Engineering
* Data Visualization
* Environmental Data Analysis

---

## Author

Renzo Albertini

