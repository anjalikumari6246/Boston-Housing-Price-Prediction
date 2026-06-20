# 🏠 Boston Housing Price Prediction

A machine learning project that predicts housing prices using the Boston Housing dataset. The project focuses on data preprocessing, exploratory data analysis (EDA), feature engineering, and comparative evaluation of multiple regression models.

## 📌 Project Overview

The objective of this project is to analyze factors affecting housing prices and build predictive models capable of estimating property values. Various machine learning algorithms were trained and evaluated to identify the best-performing approach.

## ✨ Key Features

* Performed Exploratory Data Analysis (EDA) to understand feature distributions and relationships.
* Conducted correlation analysis to identify important predictors of housing prices.
* Implemented data preprocessing using:

  * Missing value imputation
  * Feature scaling
  * Automated preprocessing pipelines
* Applied feature engineering techniques to improve model performance.
* Trained and evaluated multiple machine learning models:

  * Linear Regression
  * Decision Tree Regressor
  * Random Forest Regressor
* Used Cross-Validation and RMSE (Root Mean Squared Error) for model evaluation.
* Saved the final trained model using Joblib for future predictions.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Joblib
* Jupyter Notebook

## 📊 Machine Learning Workflow

1. Data Collection and Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Preprocessing
4. Feature Engineering
5. Model Training
6. Cross-Validation
7. Performance Evaluation
8. Model Serialization

## 📈 Models Implemented

| Model                   | Purpose                                       |
| ----------------------- | --------------------------------------------- |
| Linear Regression       | Baseline regression model                     |
| Decision Tree Regressor | Non-linear prediction model                   |
| Random Forest Regressor | Ensemble learning model for improved accuracy |

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/anjalikumari6246/Boston-Housing-Price-Prediction.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn joblib
```

3. Open the notebook:

```bash
jupyter notebook Boston_Housing_Price_Prediction.ipynb
```

## 📁 Project Structure

```text
Boston-Housing-Price-Prediction/
│
├── Boston_Housing_Price_Prediction.ipynb
├── feature_descriptions.txt
├── model_results.txt
├── data_housing.csv
└── README.md
```


## 📚 Learning Outcomes

* Data preprocessing and feature engineering
* Building end-to-end machine learning pipelines
* Model evaluation using cross-validation
* Comparing regression algorithms
* Saving and loading trained models for deployment

## 📄 Additional Files

### feature_descriptions.txt

Contains detailed descriptions of all dataset attributes used in the Boston Housing dataset, including crime rate, number of rooms, property tax rate, accessibility metrics, and other socioeconomic indicators.

### model_results.txt

Stores the performance metrics obtained from model evaluation, including mean RMSE and standard deviation values for:

* Linear Regression
* Decision Tree Regression
* Random Forest Regression

## 📊 Model Performance

| Model                    | Mean RMSE | Standard Deviation |
| ------------------------ | --------- | ------------------ |
| Linear Regression        | 5.03      | 1.06               |
| Decision Tree Regression | 4.24      | 0.86               |
| Random Forest Regression | 3.28      | 0.67               |

### Best Performing Model

Random Forest Regression achieved the lowest RMSE (3.28), indicating superior predictive performance on the housing dataset.

```
```


## 👩‍💻 Author

Anjali Kumari
B.Tech, Mechanical Engineering
Aspiring Data Analyst / Data Science Professional
