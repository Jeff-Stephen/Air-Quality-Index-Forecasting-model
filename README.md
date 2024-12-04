---  
# 📊 AQI Prediction using Time Series Forecasting  

This repository contains the implementation of a machine learning project aimed at forecasting the Air Quality Index (AQI) of Gurugram from 2020 to the present. The project employs time series analysis techniques to clean, analyze, and model the data for accurate predictions.  

## 📁 Project Structure  
The repository is organized as follows:  
- **sector_51_daily_aqi** : Contains the raw and cleaned datasets.  
- **Model** : Jupyter notebook documenting the entire workflow, scripts for data cleaning, feature engineering, and model building.  
- **README.md** : Project documentation (you’re here!).  

## 📝 Problem Statement  
Air quality plays a critical role in health and environmental decision-making. Predicting AQI helps in proactive planning and mitigation of air pollution effects. This project aims to forecast AQI values using historical data from 2020 to the present, employing time series models to uncover trends, seasonality, and other patterns.  

## 📊 Dataset  
The dataset comprises daily AQI values for Gurugram from 2020 onward. The data was acquired from reliable sources, cleaned, and preprocessed for analysis.  

### Key Features:  
- Date  
- AQI Value  

## 🚀 Project Workflow  
### 1. Data Preprocessing  
- **Loading the Data**: Imported the dataset into Python.  
- **Cleaning**: Handled missing values and outliers, and ensured data integrity.  
- **Stationarity Check**: Conducted the **Dickey-Fuller Test** to verify stationarity. While the mean and variance were constant, seasonality was evident in the data.  

### 2. Seasonality Removal  
Explored four techniques to handle seasonality:  
1. **Seasonal Decomposition**  
2. **Seasonal Differencing**  
3. **Moving Average Smoothing**  
4. **Resampling**  

### 3. ACF and PACF Analysis  
Analyzed **Autocorrelation (ACF)** and **Partial Autocorrelation (PACF)** plots to determine lag values and relationships in the data.  

### 4. Model Building  
- Selected the **ARIMA (AutoRegressive Integrated Moving Average)** model based on the data analysis.  
- Tuned parameters (p, d, q) for optimal performance.  

### 5. Forecasting  
Used the ARIMA model to generate AQI forecasts and validated the predictions using appropriate metrics.  

## 📈 Results  
- **Visualizations**: Plotted actual vs. predicted AQI values to evaluate model performance.  
- **Insights**: The model effectively captured AQI trends and provided actionable forecasts.  

## 💻 Technologies Used  
- **Programming Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, statsmodels, seaborn  

## 🔧 Installation and Usage  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/yourusername/AQI-Prediction.git  
   ```  
2. Navigate to the directory:  
   ```bash  
   cd AQI-Prediction  
   ```  
3. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
4. Run the notebooks or scripts to reproduce the analysis and forecasts.  

## 🌟 Key Learnings  
- Stationarity is crucial for time series modeling.  
- Seasonality removal improves the accuracy of predictions.  
- ARIMA is a powerful model for univariate time series forecasting.  

## 🤝 Contributions  
Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request.  

## 📬 Contact  
If you have any questions, feel free to reach out:  
- **Email**: jeffstephen02@gmail.com  
- **LinkedIn**: www.linkedin.com/in/jeff-stephen-26422922a  

---
