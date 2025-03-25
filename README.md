📈 Netflix Stock Price Prediction

This repository contains a hybrid recommendation system to predict Netflix stock prices using Machine Learning models. The system is built using Flask (for API) and Streamlit (for UI) and leverages Linear Regression, XGBoost, and LSTM for forecasting.

🚀 Features

Stock Price Prediction: Predict future Netflix stock prices based on historical data.

Hybrid Approach: Combines time-series forecasting and regression models.

Interactive Web UI: Built with Streamlit for user-friendly interaction.

API Access: Flask-based API for integrating predictions with other applications.

📂 Project Structure

├── data/                        # Dataset folder
│   ├── Netflix_Stock.csv        # Historical stock price data
├── model/                       # Trained models
│   ├── netflix_stock_model.pkl  # Machine learning model
├── app.py                        # Streamlit Web App
├── api.py                        # Flask API for predictions
├── requirements.txt              # Dependencies
├── README.md                     # Project Documentation

📥 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/yourusername/netflix-stock-prediction.git
cd netflix-stock-prediction

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Streamlit App

streamlit run app.py

4️⃣ Run the Flask API (Optional)

python api.py

🔮 Usage

Enter a date (YYYY-MM-DD) to get a predicted stock price.

Click Predict to get the forecasted value.

Use the API for programmatic predictions.

🛠️ Model Training

The dataset is preprocessed using Pandas & NumPy.

Models include Linear Regression, XGBoost, and LSTM.

Trained models are saved as .pkl files for faster inference.

🚀 Deployment

This project can be deployed on:

Streamlit Cloud: https://share.streamlit.io/

Heroku / AWS (for Flask API)
