# COVID-19 Forecasting Using Prophet

## 📌 Project Overview

In this project, I used the **Prophet model** to predict COVID-19 cases.

The main goal was to understand the trend of COVID-19 cases and make short-term predictions using time-series forecasting.

## 🎯 Objectives

* Clean the COVID-19 data
* Understand the data
* Visualize COVID-19 cases
* Build a forecasting model
* Predict future cases
* Check how well the model performs

## 🛠️ Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Prophet
* Scikit-learn
* Google Colab

## 📊 Dataset

The dataset contains COVID-19 information such as:

* Date
* Province/State
* Country/Region
* Confirmed cases
* Deaths
* Recovered cases
* Active cases

I cleaned and prepared the data before using it for forecasting.

## 🔍 What I Did

### 1. Data Cleaning

I loaded the dataset and cleaned the data so it could be used for analysis.

### 2. Data Analysis

I looked at the COVID-19 cases over time and created graphs to understand the trend.

### 3. Data Preparation

For Prophet, I prepared the data in the required format:

* `ds` → Date
* `y` → Confirmed cases

### 4. Train-Test Split

I used the **last 7 days** as test data.

The remaining data was used to train the model.

### 5. Model Training

I trained the **Prophet model** using the historical COVID-19 data.

### 6. Model Evaluation

I checked the model using:

* MAE
* MSE
* RMSE
* MAPE

## 📈 Results

The model achieved:

**MAPE = 4.02%**

This means the predictions were fairly close to the actual values during the 7-day test period.

The model followed the overall trend, but it predicted fewer cases than the actual number during the last few days.

## 📝 Conclusion

Overall, Prophet worked well for understanding the trend and making short-term predictions.

Through this project, I learned about:

* Data cleaning
* Data analysis
* Data visualization
* Time-series forecasting
* Prophet
* Model evaluation

This project is mainly useful for **learning and short-term forecasting**.

## 🚀 Google Colab

I created this project using Google Colab.

👉 [**Open COVID-19 Forecasting Project in Google Colab**](https://colab.research.google.com/drive/1H66A9spwlKd3GkxknNKqRAzpDG8ImXHm?usp=sharing)

## 📁 Project Files


[Open the Jupyter Notebook](covid19_forecasting_prophet)


## ⚠️ Limitations

COVID-19 cases are affected by many factors, so the model may not always give accurate predictions.

The model should mainly be used for **short-term forecasting**, not as a perfect long-term prediction.

## 👨‍💻 Author

**Shaheen Khan**
