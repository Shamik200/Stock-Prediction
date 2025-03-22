### **📈 Stock Price Prediction using LSTM**  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange.svg)](https://www.tensorflow.org/)  
[![Keras](https://img.shields.io/badge/Keras-API-red.svg)](https://keras.io/)  
[![Pandas](https://img.shields.io/badge/Pandas-DataProcessing-blue.svg)](https://pandas.pydata.org/)  
[![yfinance](https://img.shields.io/badge/yfinance-StockData-green.svg)](https://pypi.org/project/yfinance/)  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow.svg)](https://matplotlib.org/)  

---

## 🚀 Features  
✅ **LSTM-based Deep Learning Model** for time-series forecasting.  
✅ **Stock Data Fetching** using `yfinance`.  
✅ **Data Preprocessing & Feature Engineering** (EMA, RSI).  
✅ **Hyperparameter Tuning** using `Keras Tuner`.  
✅ **Candlestick Chart & Moving Averages Visualization**.  

---

## 📦 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Shamik200/Stock-Prediction.git
cd Stock-Prediction
```  

### 2️⃣ Create and Activate Python Environment  
```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```  

### 3️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Model  
```bash
jupyter notebook
# Open and run 'Stock_Prediction_LSTM.ipynb'
```

---

## 📡 Model Workflow  
1️⃣ **Fetch Data** from `yfinance` (Yahoo Finance).  
2️⃣ **Preprocess Data** (Normalization, Moving Averages, RSI).  
3️⃣ **Train LSTM Model** with `TensorFlow/Keras`.  
4️⃣ **Predict Future Prices** using test data.  
5️⃣ **Visualize Results** (Candlestick Chart, Predictions vs Actual).  

---

## 📂 Project Structure  
```
📂 Stock-Prediction
 ┣ 📂 Data/                               # Stock data CSVs
 ┣ 📜 README.md                           # Project details
 ┣ 📜 Stock_Prediction_LSTM.ipynb         # Jupyter Notebook
 ┣ 📜 model.h5                             # Saved LSTM model
 ┣ 📜 requirements.txt                     # Dependencies
 ┣ 📜 utils.py                             # Utility functions
```  

---

## 🛠 Built With  
- **Python** (3.8+)  
- **TensorFlow/Keras** (Deep Learning Framework)  
- **NumPy & Pandas** (Data Processing)  
- **Matplotlib & Plotly** (Data Visualization)  
- **yfinance** (Stock Data Fetching)  

---

🚀 **Made by [Shamik](https://github.com/Shamik200)**  
