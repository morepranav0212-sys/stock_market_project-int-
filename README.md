An interactive **Stock Market Dashboard** built using **Streamlit** that allows users to track stock prices, manage portfolios, and stay updated with the latest financial news — all in one place.

---

## 🚀 Features

### 📈 Market Overview
The dashboard provides real-time stock insights, including latest price, highest value, and lowest value. It also features an interactive candlestick chart for better trend visualization.

### 💼 Portfolio Tracker
Users can add stocks along with the number of shares they own and monitor their portfolio in a structured and easy-to-read table.

### 📰 Market News
Stay informed with the latest financial news. Articles are displayed with clickable links so users can read full stories instantly.

### 👤 User Profile
Includes a simple profile section and a clean dashboard layout for a smooth user experience.

### 🔄 Auto Refresh
The dashboard automatically refreshes every few seconds to ensure up-to-date market data.

---

## 🛠️ Technologies Used

- Python  
- Streamlit  
- Pandas  
- Plotly  
- Requests API  

---

## 📂 Project Structure
stock_market_dashboard/
│
├── app.py # Main dashboard file
├── data_loader.py # Fetch stock data
├── prediction.py # Price prediction logic
├── portfolio.py # Portfolio management
├── news.py # News API integration
├── data.csv # Stored portfolio data
└── README.md


---

## ▶️ How to Run
### 1️⃣ Clone the Repository
git clone https://github.com/your-username/stock_market_dashboard.git

cd stock_market_dashboard 

### 2️⃣ Install Dependencies

pip install streamlit pandas plotly requests streamlit-autorefresh


### 3️⃣ Run the Application

streamlit run app.py


### 4️⃣ Open in Browser

http://localhost:8501


---

## 📌 Usage

- Enter a valid stock symbol (e.g., `AAPL`, `TSLA`)  
- View real-time market data and trends  
- Add stocks to your portfolio  
- Track investments easily  
- Read the latest financial news  

---

## ⚠️ Notes

- Ensure you enter valid stock symbols for accurate results  
- Internet connection is required for fetching API data  
- Data loading may take a few seconds depending on network speed  

---

## 🎯 Future Improvements

- Add Top Gainers & Losers  
- Improve UI/UX design  
- Add advanced analytics and prediction models  
- Export portfolio reports (PDF/CSV)  
- Add user authentication system

  
