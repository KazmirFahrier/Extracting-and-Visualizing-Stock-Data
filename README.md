# **Stock Data Analysis using Web Scraping and `yfinance`**

This repository contains a Jupyter Notebook that extracts, analyzes, and visualizes stock data for **Tesla (TSLA) and GameStop (GME)** using **web scraping (`BeautifulSoup`) and `yfinance`**.

## **Project Overview**
This project aims to:
- Extract historical stock data for **Tesla** and **GameStop** using the `yfinance` library.
- Scrape **Tesla and GameStop revenue data** from a static webpage using `requests` and `BeautifulSoup`.
- Process and clean revenue data by removing unnecessary characters (`$`, `,`).
- Plot stock trends and revenue comparisons using `matplotlib`.

---

## **Technologies Used**
- Python
- Jupyter Notebook
- `yfinance` (for stock price data)
- `BeautifulSoup` (for web scraping)
- `requests` (to fetch HTML pages)
- `pandas` (for data processing)
- `matplotlib` (for visualization)

---

## **Dataset and Extraction Methods**
### **1. Stock Data Extraction (`yfinance`)**
- Tesla stock data: **`tesla_data`**
- GameStop stock data: **`gme_data`**

### **2. Revenue Data Extraction (Web Scraping)**
- Tesla revenue: **`tesla_revenue`**
- GameStop revenue: **`gme_revenue`**

---

## **Data Cleaning**
- **Removed commas and dollar signs (`$`)** from revenue data.
- **Dropped missing values** to ensure a clean dataset.

---

## **Visualizing Stock and Revenue Trends**
- A **custom function** (`make_graph`) is used to plot stock prices and revenue trends.
- Graphs for both Tesla and GameStop stock price trends are generated.

---

## **Results**
✅ Successfully extracted stock price data using `yfinance`.  
✅ Successfully scraped and cleaned revenue data using `BeautifulSoup`.  
✅ Plotted Tesla and GameStop stock trends.  

---


