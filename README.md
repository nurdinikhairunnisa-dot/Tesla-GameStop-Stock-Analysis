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

The visualization compares Tesla's stock price and revenue over time.

### Key Observation

Tesla shows a positive relationship between business growth and stock market performance. As revenue increased, the stock price generally moved upward, indicating growing investor confidence in the company.

![Tesla Graph](https://github.com/nurdinikhairunnisa-dot/Tesla-GameStop-Stock-Analysis/blob/main/image/graphs_of_tesla.png?raw=true)

---

## GameStop (GME)

The visualization compares GameStop's stock price and revenue over time.

### Key Observation

GameStop does not show a strong relationship between business growth and stock market performance during this period. The sharp increase in stock price was not supported by revenue growth, suggesting that other factors, such as market sentiment and speculative trading activity, had a greater influence on the stock price.

![GameStop Graph](https://github.com/nurdinikhairunnisa-dot/Tesla-GameStop-Stock-Analysis/blob/main/image/graphs_of_gme.png?raw=true)

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
