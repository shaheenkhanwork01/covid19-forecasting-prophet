# COVID-19 Forecasting Using Prophet

## 📌 Project Overview

This project uses the **Prophet model** to predict COVID-19 cases.

The main goal is to understand the trend of COVID-19 cases and make **short-term forecasts** using time-series forecasting.

## 🎯 Objectives

* Clean and prepare the COVID-19 data
* Analyze COVID-19 cases
* Visualize the trends
* Build a Prophet forecasting model
* Predict future COVID-19 cases
* Evaluate the model
* Understand the limitations of forecasting

## 🛠️ Technologies Used

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

The data was cleaned and prepared before analysis and forecasting.

## 🔍 Methodology

### 1. Data Cleaning

The COVID-19 dataset was loaded and cleaned for analysis.

### 2. Data Analysis

I analyzed the COVID-19 cases over time and used graphs to understand the trend.

### 3. Data Preparation

The data was prepared for Prophet using:

* `ds` → Date
* `y` → Confirmed cases

### 4. Train-Test Split

The **last 7 days** were used as test data.

The remaining data was used to train the model.

### 5. Model Training

I trained the **Prophet model** using the historical COVID-19 data.

### 6. Model Evaluation

The model was evaluated using:

* MAE — Mean Absolute Error
* MSE — Mean Squared Error
* RMSE — Root Mean Squared Error
* MAPE — Mean Absolute Percentage Error

## 📈 Results

The Prophet model achieved:

**MAPE = 4.02%**

This means the predictions were fairly close to the actual values during the 7-day test period.

The model followed the overall trend but predicted fewer cases than the actual values during the last few days.

## 🧠 Final Interpretation

I used the **Prophet model** to predict COVID-19 cases.

The model was tested on the last **7 days** of data. The MAPE was **4.02%**, which shows that the predictions were fairly close to the actual values.

However, the model predicted fewer cases than the actual number during the last few days.

## ✅ Conclusion

Overall, the Prophet model was able to understand the general trend and make fairly good **short-term predictions**.

This project helped me learn:

* Data cleaning
* Data analysis
* Data visualization
* Time-series forecasting
* Prophet model implementation
* Model evaluation

However, COVID-19 cases can change because of many outside factors. Therefore, the model may not always give accurate predictions.

**Final conclusion:** The model is useful for **short-term forecasting**, but it should not be considered a perfect long-term prediction model.

## 🚀 Google Colab

The complete project can be viewed and run in Google Colab:

👉 [**Open COVID-19 Forecasting Project in Google Colab**](https://colab.research.google.com/drive/1H66A9spwlKd3GkxknNKqRAzpDG8ImXHm?usp=sharing)

## 📁 Project Files

* `covid19_forecasting_prophet.ipynb` — Complete project notebook
* `README.md` — Project documentation

## 📚 Learning Outcomes

Through this project, I learned:

* Data cleaning
* Data analysis
* Data visualization
* Time-series forecasting
* Prophet model implementation
* Train-test splitting
* Model evaluation
* Result interpretation

## ⚠️ Limitations

COVID-19 cases can change because of many external factors. Therefore, the model may not always produce accurate predictions.

This project is mainly focused on **short-term forecasting**.

## 👨‍💻 Author

**Shaheen Khan**
