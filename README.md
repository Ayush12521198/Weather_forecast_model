# 🌦️ Weather Forecasting using Machine Learning

## 📌 Project Overview
This project performs weather data analysis and temperature forecasting using Machine Learning techniques.  
It explores historical temperature trends, seasonal patterns, clustering behavior, and predicts future monthly temperatures using regression models.

---

## 🚀 Features
- Time-series analysis of historical temperature data
- Seasonal temperature trend analysis
- Temperature clustering using K-Means
- Forecasting monthly temperatures using Decision Tree Regressor
- Interactive visualizations using Plotly

---

## 🛠️ Tech Stack
- Python
- NumPy
- Pandas
- Plotly
- Scikit-learn
- Statsmodels

---

## 📊 Project Workflow

### 1️⃣ Data Cleaning & Preprocessing
- Removed unwanted index column
- Converted month & year into datetime format
- Reshaped dataset using `pd.melt()`

### 2️⃣ Exploratory Data Analysis
- Time-series visualization
- Monthly & seasonal temperature distribution
- Clustering analysis using K-Means

### 3️⃣ Forecasting Model
- Feature engineering using One-Hot Encoding
- Decision Tree Regressor model
- Model evaluation using R² Score (~0.96)
- Forecasted monthly temperature for 2018

---

## 📈 Key Insights
- January is the coldest month, May is the hottest.
- Temperature shows a gradual increasing trend post-1980.
- Seasonal analysis confirms rising mean temperatures over time.
- Three major temperature clusters identified using K-Means.

---

## 📂 Project Structure

```
Weather-Forecasting/
│
├── Weather.csv  
├── weather_forecasting.ipynb  
├── README.md  
└── requirements.txt  
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/weather-forecasting-ml.git
cd weather-forecasting-ml

Install dependencies
pip install -r requirements.txt

Run the notebook
jupyter notebook
```

## Future Improvements

Implement LSTM for advanced time-series forecasting

Perform hyperparameter tuning

Deploy as a web application using Streamlit
