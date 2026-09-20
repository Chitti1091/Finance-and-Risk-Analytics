# Finance-And-Risk-Analytics

## Problem Statement

The wealth management industry has expanded rapidly, increasing the demand for data-driven investment advisory services. Portfolio managers must evaluate multiple assets across sectors, assess risk–return tradeoffs, and construct portfolios aligned with individual investor objectives.

In this project, you are tasked with providing **investment consultation** to two investors:

- **Mr. Patrick Jyenger**
- **Mr. Peter Jyenger**

Each investor has unique financial goals and risk appetites. The objective is to analyze historical stock performance, compare sector-wise behavior against the **S&P 500**, calculate key financial metrics, and construct **customized investment portfolios**.

---

## Objectives

- Analyze historical stock performance across multiple sectors  
- Compare individual stocks against the S&P 500 benchmark  
- Evaluate risk–return characteristics using financial metrics  
- Support portfolio construction using quantitative insights  
- Provide explainable, visualization-driven investment recommendations  

---

## Dataset Overview

The analysis uses historical price data for:

- 24 individual stocks  
- 4 sectors: Finance, Aviation, Technology, Healthcare & Pharma  
- S&P 500 index as the benchmark  

The dataset spans multiple years, enabling long-term trend, volatility, and crisis-period analysis.

---

## Solution Approach

### 1. Data Gathering

- Historical stock price data was collected for selected stocks from each sector.
- S&P 500 index data was included for benchmark comparison.

---

### 2. Data Preprocessing

Using Python, the dataset was cleaned and standardized:

- Handled missing values  
- Normalized stock prices  
- Aligned time-series data  
- Created sector-wise and multi-year datasets  

---

### 3. Exploratory Data Analysis & Visualization

Sector-wise performance was analyzed using normalized price movements.

#### Finance Sector vs S&P 500
![Finance Sector](Screenshots/Finance%20Sector.png)

Finance stocks exhibit higher volatility and stronger drawdowns during market stress.

---

#### Aviation Sector vs S&P 500
![Aviation Sector](Screenshots/Aviation%20Sector.png)

Aviation stocks show cyclical behavior and heightened sensitivity to economic shocks.

---

#### Technology Sector vs S&P 500
![Technology Sector](Screenshots/Tech%20Sector.png)

Technology stocks demonstrate strong long-term growth with periodic volatility.

---

#### Healthcare & Pharma Sector vs S&P 500
![Healthcare & Pharma Sector](Screenshots/Health%20and%20Pharma%20Sector.png)

Healthcare stocks tend to be defensive and relatively stable during downturns.

---

#### Stocks vs S&P 500 (Multi-Sector Comparison)
![Stocks vs S&P500](Screenshots/Stocks%20Vs%20S%26P500.jpg)
![Stocks vs S&P500 Extended](Screenshots/Stocks%20Vs%20S%26P500%202.jpg)

---

## Metric Calculation

The following financial metrics were computed using Python:

- Average Daily Return  
- Average Daily Risk (Volatility)  
- Annualized Return  
- Annualized Risk  
- Cumulative Return  
- Sharpe Ratio  

These metrics form the basis for portfolio selection.

---

## Portfolio Construction

- **Mr. Patrick Jyenger**  
  - Growth-oriented portfolio  
  - Higher return tolerance  
  - Emphasis on Technology and selected Finance stocks  

- **Mr. Peter Jyenger**  
  - Conservative portfolio  
  - Lower risk tolerance  
  - Emphasis on Healthcare, Pharma, and low-volatility stocks  

---

## Visualization & Reporting

- Interactive Power BI dashboards were created to analyze:
  - Sector-wise performance
  - Risk–return tradeoffs
  - Portfolio comparisons
- A final presentation summarizes all findings and recommendations.

---

## Tools & Technologies

- Python (Pandas, NumPy, Matplotlib)  
- Power BI  
- Jupyter Notebook  
- Git & GitHub  

---

## Repository Structure

Finance-And-Risk-Analytics/
│
├── Finance and Risk Analytics.ipynb
├── Cleaned_data_final.csv
├── normalized_data.csv
├── normalized_5_Years_data.csv
├── Stocks Vs S&P500.pbix
├── Dataset/
├── Screenshots/
└── README.md

---

## Conclusion

This project demonstrates an end-to-end **Finance and Risk Analytics** workflow, integrating quantitative analysis, visualization, and portfolio construction to support informed investment decisions.

---

## Disclaimer

This project is for educational purposes only and does not constitute financial advice.
