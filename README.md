# Tesla and GameStop Stock Analysis

A Python project that collects, cleans, and visualizes stock market data for Tesla (TSLA) and GameStop (GME).

The project combines stock price data and company revenue data to explore whether business growth is reflected in stock market performance.

---

## Project Objectives

- Extract historical stock price data using Python
- Collect revenue data through web scraping
- Clean and transform the datasets
- Visualize stock price and revenue trends
- Compare business performance with market valuation

---

## Technologies Used

- Python
- Pandas
- BeautifulSoup
- Requests
- yfinance
- Matplotlib

---

## Data Sources

### Stock Price Data

Retrieved using the `yfinance` library.

### Revenue Data

Extracted through web scraping from publicly available financial data sources.

---

## Workflow

1. Download historical stock price data
2. Scrape company revenue data
3. Clean and transform datasets
4. Convert dates into datetime format
5. Visualize stock prices and revenues
6. Analyze observed trends

---

## Tesla (TSLA)

The visualization shows Tesla's historical stock price alongside company revenue.

### Key Observation

Between 2018 and 2021, both Tesla's revenue and stock price increased significantly, indicating strong business growth and increasing investor confidence.

![Tesla Graph](images/tesla_stock_graph.png)

---

## GameStop (GME)

The visualization compares GameStop's stock price and revenue over time.

### Key Observation

GameStop experienced a dramatic increase in stock price despite relatively stable revenue, highlighting the impact of market sentiment and the 2021 short squeeze event.

![GameStop Graph](images/gme_stock_graph.png)

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/stock-price-vs-revenue-analysis.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook stock_analysis.ipynb
```

---

## Project Preview

This project demonstrates:

- Web Scraping
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Financial Data Analysis
- Data Visualization

---

## Author

Nurdini Khairunnisa
