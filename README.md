# 🌬️ Wind Power Generation Forecasting

A data preprocessing and exploratory data analysis project for wind power generation forecasting using meteorological data collected from multiple locations.

## 📌 Overview

This project focuses on preparing weather and wind data for future machine learning models that can predict wind power generation.

The dataset contains meteorological observations from four different locations and includes features such as temperature, humidity, wind speed, wind direction, and wind gusts.

## 🚀 Features

- Load weather datasets from multiple locations
- Merge datasets into a single dataframe
- Perform data cleaning and validation
- Check for missing values and duplicates
- Generate statistical summaries
- Encode categorical variables
- Prepare data for machine learning models
- Perform exploratory data analysis

## 📊 Dataset Features

- Temperature at 2m
- Relative Humidity
- Dew Point
- Wind Speed at 10m
- Wind Speed at 100m
- Wind Direction at 10m
- Wind Direction at 100m
- Wind Gust Speed
- Power Output
- Location Information

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Project Structure
Wind_Power_Generation_Forecasting/
│
├── Location1.csv
├── Location2.csv
├── Location3.csv
├── Location4.csv
├── merged_locations.csv
├── Wind_Power_Generation_Forecasting.ipynb
├── requirements.txt
└── README.md


## ⚙️ Installation

```bash
git clone https://github.com/RajSarkar4/Wind_Power_Generation_Forecasting.git
cd Wind_Power_Generation_Forecasting
pip install -r requirements.txt

▶️ Usage
jupyter notebook

Open:

Wind_Power_Generation_Forecasting.ipynb

Run all notebook cells sequentially to reproduce the preprocessing and EDA pipeline.

📈 Current Progress
✅ Data Loading
✅ Data Merging
✅ Data Cleaning
✅ Missing Value Analysis
✅ Duplicate Detection
✅ Feature Engineering
✅ Exploratory Data Analysis
⏳ Machine Learning Model Training
⏳ Model Evaluation
⏳ Deployment
🔮 Future Improvements
Train regression models for power forecasting
Evaluate model performance using RMSE and R²
Deploy prediction APIs using Flask or FastAPI
Integrate real-time weather data
👨‍💻 Author
Raj Sarkar
