🚀 Features
📈 Market Overview
View latest, high, and low values of selected stock
Interactive candlestick chart
💼 Portfolio Tracker
Add stocks with number of shares
View portfolio data in a structured table
📰 Market News
Latest financial news updates
Clickable article links
👤 User Profile
Simple profile section
Clean dashboard layout
🔄 Auto Refresh
Dashboard updates automatically every few seconds

🛠️ Technologies Used
Python
Streamlit
Pandas
Plotly
Requests API

📂 Project Structure
stock_market_dashboard/
│
├── app.py              # Main dashboard file
├── data_loader.py      # Fetch stock data
├── prediction.py       # Price prediction logic
├── portfolio.py        # Portfolio management
├── news.py             # News API integration
├── data.csv            # Stored portfolio data
└── README.md
▶️ How to Run
Open terminal in project folder
Install dependencies:
pip install streamlit pandas plotly requests streamlit-autorefresh
Run the app:
streamlit run app.py
Open in browser:
http://localhost:8501

📌 Usage
Enter a valid stock symbol (Example: AAPL, TSLA)
View market data and trends
Add stocks to your portfolio
Check latest financial news

⚠️ Notes
Use valid stock symbols for correct data
Internet connection is required for API data
Data may take a few seconds to load

🎯 Future Improvements
Add top gainers & losers
Improve UI design
Add more analytics features
