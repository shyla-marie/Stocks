# Stock Price Prediction Projects with Machine Learning

## Project 1: NVDA Stock Price Prediction with LSTM.

### Data:
* **Training Data**: NVDA-Training_Set-v0.csv
* **Test Data**: NVDA-Test_Set-v0.csv
* Data retrieved from Yahoo Finance NDVA Historical Data: https://finance.yahoo.com/quote/NVDA/history?p=NVDA

### Required Packages:
* **Pandas**
* **Numpy**
* **Scikit-Learn**
* **Matplotlib.pyplot**
* from **sklearn.preprocessing** import **MinMaxScaler**
* from **sklearn.model_selection** import **train_test_split**
* from **keras.models** import **Sequential**
* from **keras.layers** import **LSTM**
* from **keras.layers** import **Dropout**
* from **keras.layers** import **Dense**

### Jupyter Notebook Includes:
* Data Visualization of Predicted vs Actual NVDA Stock Price
* Data Visualization of Training Loss vs Validation Loss


## Project 2: Correlated Tech Stock Price Prediction

### Training Datasets:
* Training Data retrieved from Yahoo Finance Historical Data
* **Date Range**: 05-18-2012 to 12-30-2022
* **Data Frequency**: Daily (Non-Holiday Weekdays)
* **Data Series**: Date (dd-mm-yyyy), Open, High, Low, Close, Adj Close, Volume
* **Number of Columns**: 7
* **Number of Rows**: 2,673
* **Apple**: APPL-Training_Set.csv
* **Amazon**: AMZN-Training_Set.csv
* **ASML**: ASML-Training_Set.csv
* **Electronic Arts**: EA-Training_Set.csv
* **General Dynamics**: GD-Training_Set.csv
* **Alphabet**: GOOG-Training_Set.csv
* **Intel**: INTC-Training_Set.csv
* **Meta**: META-Training_Set.csv
* **Microsoft**: MSFT-Training_Set.csv
* **Nokia**: NOK-Training_Set.csv
* **Nintendo**: NTDOY-Training_Set.csv
* **NVIDIA**: NVDA-Training_Set-v1.csv
* **Tesla**: TSLA-Training_Set.csv

### Test Datasets:
* Test Data retrieved from Yahoo Finance Historical Data:
* **Date Range**: 01-03-2023 to 01-12-2024
* **Data Frequency**: Daily (Non-Holiday Weekdays)
* **Data Categories**: Date (dd-mm-yyyy), Open, High, Low, Close, Adj Close, Volume
* **Number of Columns**: 7
* **Number of Rows**: 259
* **Apple**: APPL-Test_Set.csv
* **Amazon**: AMZN-Test_Set.csv
* **ASML**: ASML-Test_Set.csv
* **Electronic Arts**: EA-Test_Set.csv
* **General Dynamics**: GD-Test_Set.csv
* **Alphabet**: GOOG-Test_Set.csv
* **Intel**: INTC-Test_Set.csv
* **Meta**: META-Test_Set.csv
* **Microsoft**: MSFT-Test_Set.csv
* **Nokia**: NOK-Test_Set.csv
* **Nintendo**: NTDOY-Test_Set.csv
* **NVIDIA**: NVDA-Test_Set-v1.csv
* **Tesla**: TSLA-Test_Set.csv
