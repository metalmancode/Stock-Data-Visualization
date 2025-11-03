# Stock Data Extraction and Visualization

This project demonstrates the process of extracting stock data for Tesla (TSLA) and GameStop (GME) using the `yfinance` library and web scraping financial revenue data using `BeautifulSoup`. The extracted data is then visualized in interactive plots using `Plotly`.

This project is based on an assignment from the IBM Data Science Professional Certificate.

## Project Goals

* Use the `yfinance` library to extract historical stock price data.
* Use `requests` and `BeautifulSoup` to scrape quarterly revenue data from a webpage.
* Clean and process the extracted data using `pandas`.
* Define a reusable plotting function to create a dashboard displaying both historical share price and historical revenue.

## 🛠️ Tools and Libraries Used

* **Python 3**
* **Jupyter Notebook**
* **Pandas:** For data manipulation and cleaning.
* **yfinance:** To fetch historical stock market data.
* **Requests:** To make HTTP requests to the revenue webpage.
* **BeautifulSoup (bs4):** To parse HTML and scrape revenue data.
* **Plotly:** To create interactive, dashboard-style visualizations.

## 📈 Results / Output


The final output consists of two graphs, one for Tesla and one for GameStop, each displaying:
1.  **Historical Share Price** (up to June 2021)
2.  **Historical Quarterly Revenue** (up to April 2021)

### Tesla (TSLA)
![Tesla Stock and Revenue Graph](https://github.com/metalmancode/Stock-Data-Visualization/raw/main/tesla_plot.png)

### GameStop (GME)
![GameStop Stock and Revenue Graph](https://github.com/metalmancode/Stock-Data-Visualization/raw/main/GME_plot.png)



4.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook Stock_Data_Analysis.ipynb
    ```
