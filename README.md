# 📈 Trading Bot

This project implements an automated trading bot that uses machine learning models to predict stock prices and execute trades based on those predictions. It integrates with the Alpaca Trading API to perform real-time trading operations.

## 🚀 Features

- 📊 Stock price forecasting using **ARIMA**, **LSTM**, and **Prophet** models.
- 🔁 Real-time trading execution using the **Alpaca API**.
- 🧠 Modular, educational notebooks for each model.
- ✅ Easily extendable and beginner-friendly code.

## 🛠️ Setup Instructions

### 1. Clone the Repository

git clone https://github.com/guptatanish/Trading-Bot.git
cd Trading-Bot

### 2. Install Dependencies
Make sure you have Python 3.7+ installed, then:

bash
Copy
Edit
pip install -r requirements.txt
3. Configure Alpaca API
Create a .env file in the project root.

Add your Alpaca paper trading API keys:

env
Copy
Edit
API_KEY='your_api_key'
SECRET_KEY='your_secret_key'
You can get your keys by creating a free account at https://alpaca.markets/.

🧠 Models Included
Model	Type	Notebook
ARIMA	Statistical	ARIMA_model.ipynb
LSTM	Deep Learning	LSTM_based_ML_Model.ipynb
Prophet	Time Series	ProphetForecasts.ipynb
Each notebook contains:

Data loading

Model training

Visualization

Evaluation metrics

🧪 How to Run
To run the repository get Alpaca credentials from Alpaca Trading API and place them in .env file in root directory of project, in the format below :

API_KEY = 'PKSJHASK5764675L8'

SECRET_KEY = 'SXdf4g61sdf5rrgdfrb64df1nfgLeVP'

💼 Start the Trading Bot
Once you have selected a model, integrate its predictions into the app.py script.

Then run:

bash
Copy
Edit
python app.py
⚠️ Make sure your .env is configured and you're using Alpaca paper trading mode.

📁 Project Structure
bash
Copy
Edit
Trading-Bot/
├── ARIMA_model.ipynb
├── LSTM_based_ML_Model.ipynb
├── ProphetForecasts.ipynb
├── app.py
├── requirements.txt
├── .env                # (Not uploaded to GitHub)
└── README.md
📊 Sample Results

LSTM achieves low RMSE on closing prices.

Prophet gives interpretable trend and seasonal components.

ARIMA is lightweight and works well on short-term predictions.
