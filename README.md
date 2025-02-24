# Stock-prediction-model
Overview -
This project is a web-based stock price prediction system using a deep learning model (LSTM) and Flask. It fetches historical stock data, processes it, and predicts future stock prices using an LSTM model. The results are visualized through interactive charts.

Features
1.Fetches real-time stock data using Yahoo Finance (yfinance).

2.Uses an LSTM model (stock_dl_model.h5) to predict stock prices.

3.Displays historical trends using Exponential Moving Averages (EMA).

4.Provides interactive charts for stock trend analysis.

5.Allows users to download stock data as a CSV file.

6.Built with Flask for an easy-to-use web interface.

Tech Stack -

Python (Numpy, Pandas, Matplotlib, Sklearn, Keras, Flask, Yahoo Finance API)

Deep Learning (LSTM Model for Time-Series Forecasting)

Frontend (HTML, CSS, Bootstrap)

Installation & Setup -

1. Clone the Repository

    git clone https://github.com/yourusername/stock-prediction-flask.git
    cd stock-prediction-flask

2. Create a Virtual Environment (Optional but Recommended)

    python -m venv venv
    source venv/bin/activate  # For Linux/Mac
    venv\Scripts\activate     # For Windows

3. Install Dependencies

    pip install -r requirements.txt

4. Ensure Model File is Present

Make sure you have the LSTM model file (stock_dl_model.h5) in the root directory.

5. Run the Application

    python app.py

Access the app at http://127.0.0.1:5000/ in your browser.

Usage

Enter a stock ticker symbol (e.g., AAPL, GOOGL, TSLA).

Click "Submit" to fetch historical stock data and make predictions.

View the interactive charts and download the dataset if needed.

Project Structure

📂 stock-prediction-flask
 ├── static/               # Stores generated plots & datasets
 ├── templates/            # HTML templates for Flask
 ├── stock_dl_model.h5     # Pre-trained LSTM model
 ├── app.py                # Flask application
 ├── requirements.txt      # List of dependencies
 ├── README.md             # Project documentation


Future Enhancements - 

Implement additional technical indicators (RSI, MACD, Bollinger Bands).

Improve model accuracy by training on more datasets.

Deploy the app using Heroku or AWS.

License

This project is open-source and available under the MIT License.

Contact - 

For any queries, feel free to reach out or open an issue in the repository.

