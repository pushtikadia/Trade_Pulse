# 📈 Trade Pulse
**Trade Pulse** is a lightweight, interactive web dashboard built with Python and Streamlit. It allows users to track real-time stock and cryptocurrency performance, visualize historical price trends, and analyze trading volume.

## 🚀 Features

* **Real-Time Data Fetching:** Pulls live market data using the Yahoo Finance API (`yfinance`).
* **Interactive Visualization:** Dynamic line charts for closing prices and bar charts for trading volume.
* **Key Metrics Display:** Instantly view Current Price, Price Change (Delta), Volume, and 52-Week Highs.
* **Customizable Timeframes:** Sidebar filters allow users to select specific date ranges for analysis.
* **Raw Data Access:** Expandable view to inspect the underlying dataframe.

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Frontend Framework:** [Streamlit](https://streamlit.io/)
* **Data Source:** [yfinance](https://pypi.org/project/yfinance/)
* **Data Manipulation:** Pandas

## 📂 Project Structure

```text
marketwatch-lite/
│
├── app.py              # Main application logic
├── README.md           # Project documentation
└── requirements.txt    # List of dependencies

```

##⚙️ Installation & SetupFollow these steps to run the project locally on your machine.

###1. Clone the Repository(Skip this step if you haven't pushed to GitHub yet)

```bash
git clone [https://github.com/your-username/marketwatch-lite.git](https://github.com/your-username/marketwatch-lite.git)
cd marketwatch-lite

```

###2. Create a Virtual Environment (Optional but Recommended)```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate

```

###3. Install DependenciesYou can install the required libraries directly:

```bash
pip install streamlit yfinance pandas

```

*Or, if you created a requirements.txt file:*

```bash
pip install -r requirements.txt

```

###4. Run the ApplicationExecute the following command in your terminal:

```bash
streamlit run app.py

```

##📖 How to Use1. **Launch the App:** Once the command runs, a local web server will start (usually at `http://localhost:8501`).
2. **Select a Ticker:** Use the sidebar dropdown to choose a stock (e.g., AAPL, TSLA) or Crypto (e.g., BTC-USD).
3. **Choose Dates:** Adjust the "Start Date" and "End Date" in the sidebar to change the historical range.
4. **Analyze:** View the price metrics, interact with the charts, or expand "View Raw Data" to see the table.

##🔮 Future ImprovementsHere are a few features planned for future updates:

* [ ] Add Moving Average (SMA/EMA) indicators.
* [ ] Implement a "Download CSV" button for data export.
* [ ] Add a search bar to input *any* ticker symbol manually.
* [ ] Dark mode toggle (or custom theming).

##📄 LicenseThis project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

```

---

### Suggested `requirements.txt`
If you want to make your project easy to share, create a file named `requirements.txt` in the same folder and add these three lines:

```text
streamlit
yfinance
pandas

```
