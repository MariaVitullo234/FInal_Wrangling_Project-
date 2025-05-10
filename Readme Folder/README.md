# FInal_Wrangling_Project-
# ESG & NASDAQ Financial Data Analysis

##  Project Authors
Maria Vitullo, Amira Eid

---

##  Overview
This project explores the relationship between ESG (Environmental, Social, and Governance) ratings and financial performance for companies listed on the NASDAQ. Our goal is to uncover patterns and correlations between ESG factors and financial indicators like Earnings Per Share (EPS), growth rates, and liquidity ratios.

---

## Folder Structure  

```bash
FINAL_WRANGLING_PROJECT/
├── Data/
│   ├── Final/
│   │   └── Model_CSV.csv
│   └── Raw/
│       ├── esg_data_full.csv
│       └── raw_sp500.csv
│   └── README.md
│
├── Extra Files/
│   ├── Data Dictionary.xlsx
│   ├── extra_files.md
│   └── mvitullo_ameid_notes.md
│
├── Final_Project_PDF/
│   ├── Final_Project.pdf
│   └── PDF.md
│
├── NoteBooks/
│   ├── CheckPoint.ipynb
│   ├── Final_Dataframe_cleaned.ipynb
│   ├── Updated_Proposal.ipynb
│   ├── Analysis_Q1.ipynb
│   ├── Analysis_Q2.ipynb
│   └── Analysis_Q3.ipynb
│   └── Jupyter.md
│
├── Readme Folder/
│   └── README.md
│
├── .gitignore
└── README.md

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

---

## References
- [Sustainalytics ESG Ratings](https://www.sustainalytics.com/esg-ratings)
- [Wikipedia S&P 500 Ticker](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies)

