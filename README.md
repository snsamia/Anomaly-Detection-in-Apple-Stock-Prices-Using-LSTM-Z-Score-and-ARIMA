
# 📈 Apple Stock Price Anomaly Detection

![Project Banner]([https://github.com/snsamia/Anomaly-Detection-in-Apple-Stock-Prices-Using-LSTM-Z-Score-and-ARIMA/main/anomaly.png](https://github.com/snsamia/Anomaly-Detection-in-Apple-Stock-Prices-Using-LSTM-Z-Score-and-ARIMA/blob/main/anomaly.png)
![Project Banner](https://raw.githubusercontent.com/snsamia/Anomaly-Detection-in-Beehive-Environmental-Data-Autoencoder-ML-Methods-/main/beehive_project_banner_fancy.png)
This project applies **three anomaly detection techniques** to Apple stock price data from the last 5 years:


- 🔴 **LSTM** (Long Short-Term Memory neural network)
- 🟠 **Z-Score** (statistical thresholding)
- 🟢 **ARIMA** (AutoRegressive Integrated Moving Average)

---

## 🧠 Techniques Compared

| Model      | Approach Type    | Summary |
|------------|------------------|---------|
| LSTM       | Deep Learning    | Learns temporal dependencies and detects deviations from predicted price |
| Z-Score    | Statistical      | Flags points with large standard deviations from the mean |
| ARIMA      | Time Series Model | Flags anomalies based on residuals from ARIMA forecasts |

---

## 📊 Output

The chart below visualizes the detected anomalies on Apple's stock price:

- **Red "X"** → LSTM anomalies  
- **Orange circles** → Z-score anomalies  
- **Green triangles** → ARIMA anomalies  

![Anomaly Plot](./52643a37-ab8c-4fa0-b000-70181785a086.png)

---


---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `statsmodels`
- `torch` (PyTorch)
