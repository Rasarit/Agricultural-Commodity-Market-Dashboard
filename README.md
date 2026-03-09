# Agricultural Market Dashboard – Maize Price Analysis

## Project Overview

This project presents an **Agricultural Market Dashboard** built using **R** to summarize key insights from maize market data.

The dashboard combines multiple analyses into a single visual report, helping users quickly understand **price trends, seasonal patterns, supply effects, and market volatility**.

Dashboards like this are commonly used by analysts to **communicate market insights clearly and visually**.

---

## Dataset

The dataset contains historical maize market observations.

| Column   | Description                        |
| -------- | ---------------------------------- |
| date     | Date of observation                |
| price    | Maize market price (₹ per quintal) |
| arrivals | Market arrivals (supply volume)    |

The dataset includes **monthly observations across several years**, allowing trend and pattern analysis.

---

## Tools Used

* **R**
* **RStudio**
* **ggplot2** – data visualization
* **dplyr** – data manipulation
* **Base R plotting** – dashboard layout

---

## Project Structure

```
agri-market-dashboard
│
├── maize_price_arrivals_dashboard.csv
├── market_dashboard.R
├── agri_market_dashboard.png
└── README.md
```

---

## Dashboard Components

The dashboard contains four analytical panels:

### 1. Price Trend

Displays how maize prices change over time and highlights long-term market movement.

### 2. Monthly Price Distribution

Shows the seasonal distribution of maize prices across months.

### 3. Price vs Market Arrivals

Examines the relationship between market supply and price using a regression trend.

### 4. Monthly Price Change

Visualizes price fluctuations between consecutive months to identify volatility.

---

## Dashboard Output

The script generates a **4-panel dashboard** summarizing the analysis.

![Agricultural Market Dashboard](agri_market_dashboard.png)

---

## Methodology

The analysis followed these steps:

1. Load maize market data
2. Convert dates to time format
3. Calculate monthly price changes
4. Explore the relationship between price and arrivals
5. Visualize patterns using multiple charts
6. Combine charts into a single dashboard layout

---

## Key Insights

### Insight 1 — Price Trend

Maize prices show a gradual upward trend over the observed period.

### Insight 2 — Seasonal Pattern

Monthly price distribution suggests seasonal variation in maize markets.

### Insight 3 — Supply Impact

Higher market arrivals tend to be associated with lower prices.

### Insight 4 — Market Volatility

Monthly price changes highlight periods of higher market fluctuations.

---

## How to Run the Project

1. Clone this repository
2. Open the project in **RStudio**

Install required packages:

```r
install.packages("ggplot2")
install.packages("dplyr")
```

Run the script:

```
market_dashboard.R
```

The script will generate the dashboard image:

```
agri_market_dashboard.png
```

---

## Author

**Kiran Jala**
MBA Agribusiness Management

Interest areas: Agricultural market analysis, commodity price forecasting, and data analytics.
