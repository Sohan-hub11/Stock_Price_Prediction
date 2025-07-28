# Stock_Price_Prediction
This project demonstrates how to use an LSTM (Long Short-Term Memory) neural network to predict future stock prices based on historical data. The data is sourced from Yahoo Finance using the yfinance library.

---

## 🔍 Features

- Developed an LSTM-based model to forecast stock prices using historical financial data from 
Yahoo Finance. 
- Preprocesses data with MinMaxScaler
- Trains and saves an LSTM model using Keras
- Predicts future closing prices and compares predicted prices vs actual prices. 
- Visualization of stock trends using Matplotlib.
- Provides an interactive web interface via Flask

---

## 🧠 Technologies Used

- Python
- Flask
- Pandas, NumPy
- Matplotlib
- Keras / TensorFlow
- Scikit-learn
- yfinance

---

## 🏗️ Project Structure

- static/ # Static files (CSS/images)
- templates/ # HTML templates
- stock__model.keras # Trained LSTM model
- app.py # Flask application script
- requirements.txt # Required Python packages
- Stock_predict.ipynb # Jupyter Notebook (training + visualization)
- README.md # Project overview

---

## 🚀 How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sohan-hub11/Stock_Price_Prediction.git
   cd Stock_Price_Prediction
   
2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
  
3. **Start Flask App**

   ```bash
   python app.py
  
4. **Open in Browser**

   ```bash
   Visit http://127.0.0.1:5000 to use the prediction interface.

---

## 👨‍💻 Author

Made with ❤️ by [Sohan Samanta](https://github.com/Sohan-hub11)

---

⭐ If you found this helpful, give it a **star** and consider contributing!

