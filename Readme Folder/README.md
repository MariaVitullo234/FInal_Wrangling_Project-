# FInal_Wrangling_Project-
# ESG & NASDAQ Financial Data Analysis

##  Project Authors
Maria Vitullo, Amira Eid

---

##  Overview
This project explores the relationship between ESG (Environmental, Social, and Governance) ratings and financial performance for companies listed on the NASDAQ. Our goal is to uncover patterns and correlations between ESG factors and financial indicators like Earnings Per Share (EPS), growth rates, and liquidity ratios.

---

##  Folder Structure

    ```plaintext
    esg_nasdaq_analysis/
    ├── data/
    │   ├── raw/
    │   │   ├── esg_scraped_data.csv
    │   │   └── nasdaq_full_data.csv
    │   └── processed/
    │       ├── esg_cleaned.csv
    │       └── financial_ratios_subset.csv
    ├── notebooks/
    │   ├── 01_data_collection_scraping.ipynb
    │   ├── 02_data_cleaning.ipynb
    │   ├── 03_analysis.ipynb
    │   └── 04_visualization.ipynb
    ├── outputs/
    │   ├── plots/
    │   └── results_summary.csv
    ├── README.md
    └── requirements.txt


##  Data Dictionary

| Column Name          | Data Type | Description                                                                 |
|----------------------|-----------|-----------------------------------------------------------------------------|
| `Ticker`             | String    | Stock ticker symbol representing the company.                              |
| `Company`            | String    | Full legal name of the company.                                            |
| `P/E Ratio`          | Float     | Ratio of share price to earnings per share.                                |
| `Forward P/E`        | Float     | Projected future ratio of share price to earnings per share.               |
| `Revenue (TTM)`      | Float     | Total revenue over the trailing twelve months.                             |
| `Gross Profits`      | Float     | Total profits after subtracting cost of goods sold over the past 12 months.|
| `Net Income`         | Float     | Total earnings after all expenses and taxes.                               |
| `EBITDA`             | Float     | Earnings before interest, taxes, depreciation, and amortization.           |
| `Market Cap`         | Float     | Total market value of a company's outstanding shares.                      |
| `Sector`             | String    | Industry sector classification.                                            |
| `ESG Score`          | Float     | Numeric measure of environmental, social, and governance performance.      |
| `ESG Risk`           | String    | Categorical ESG risk classification (Negligible, Low, Medium, Severe).     |
| `ESG Risk Numeric`   | Integer   | Numeric encoding of ESG Risk category.                                     |

