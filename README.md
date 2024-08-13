# Stock Analysis and Prediction with LSTM and Random Forest

This project provides a Streamlit-based web application for stock analysis and prediction. The application utilizes historical stock data, technical indicators, and machine learning models to generate predictions and reports. It also integrates with OpenAI's GPT-3.5 to generate a concise summary of the analysis report.

## Features

- **Download Stock Data**: Automatically fetch historical stock data using the Yahoo Finance API.
- **Technical Indicators**: Calculate technical indicators such as Simple Moving Averages (SMA), Relative Strength Index (RSI), and Bollinger Bands.
- **Visualization**: Visualize the stock's closing price along with the calculated technical indicators.
- **LSTM Model**: Predict future stock prices using a Long Short-Term Memory (LSTM) model.
- **Random Forest Classifier**: Predict the bullish or bearish nature of the stock for the next day.
- **Generated Reports**: Generate a detailed report with the current stock status, predictions, and technical indicators.
- **OpenAI Integration**: Generate a concise summary of the report using OpenAI's GPT-3.5 model.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/stock-analysis-prediction.git
    cd stock-analysis-prediction
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

## Usage

1. **Input Stock Symbol**: Enter the stock symbol (e.g., `AAPL` for Apple) in the input field.
2. **View Data and Indicators**: The application will download the stock data, calculate technical indicators, and display visualizations.
3. **Predict Future Prices**: The LSTM model will predict the stock's closing prices for the next 30 days.
4. **Bullish Prediction**: The Random Forest model will predict whether the stock will be bullish or bearish for the next day.
5. **Generate Report**: A detailed report will be generated, and a summary will be provided using OpenAI's GPT-3.5.

## Project Structure

- `app.py`: The main application file containing the Streamlit app code.
- `requirements.txt`: Lists all the Python dependencies required for the project.
- `README.md`: This file, providing an overview and instructions for the project.

## Key Dependencies

- **Streamlit**: For building the web application.
- **yFinance**: For downloading stock data.
- **TensorFlow/Keras**: For building the LSTM model.
- **Scikit-learn**: For data processing and machine learning models.
- **OpenAI**: For generating a summary using the GPT-3.5 model.

## Note

- Ensure that you replace the `open_api_key` variable in the code with your actual OpenAI API key to use the GPT-3.5 model.
- The application may take some time to process the data, train models, and generate predictions.



