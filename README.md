📈 Google Stock Price Prediction

This project predicts Google’s stock price using Facebook Prophet, a powerful time series forecasting library. The dataset is processed, visualized, and forecasted for future stock price trends.



📂 Project Structure

google_stock_price.py → Main script for data preprocessing, visualization, and stock price prediction.

Dataset.xlsx → Input dataset (Google stock historical data).



⚙️ Requirements

Make sure you have the following Python libraries installed:

pip install pandas numpy matplotlib pandas_datareader prophet openpyxl





▶️ How to Run

1. Clone this repository:

git clone https://github.com/your-username/google-stock-price-prediction.git
cd google-stock-price-prediction


2. Place your dataset file (Dataset.xlsx) inside the project folder.

3. Run the script:

python google_stock_price.py


4. The script will:

Load and clean the dataset.

Visualize Google’s stock closing price history.

Train a Prophet model on the data.

Forecast stock prices for the next 365 days.

Plot prediction and trend components.





📊 Sample Outputs

Historical stock price visualization.

Forecast of Google stock price with Prophet.

Trend and seasonal components analysis.





🛠️ Technologies Used

Python

Pandas & NumPy

Matplotlib

Prophet





🚀 Future Improvements

Add support for live stock data fetching using yfinance or pandas_datareader.

Improve visualizations with interactive charts (e.g., Plotly).

Extend predictions to other companies.




📜 License

This project is open-source and available under the MIT License.
