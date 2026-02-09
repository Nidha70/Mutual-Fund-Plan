# Mutual-Fund-Plan
## Project Overview
This project focuses on designing a **mutual fund investment plan** using Python by analyzing **Nifty 50 stock closing prices**.  
The goal is to identify stocks that provide **high returns with relatively low risk**, making them suitable for **long-term investment strategies**.

---

## Objective
- Analyze historical stock price data of Nifty 50 companies  
- Measure **risk (volatility)** and **returns (ROI & growth rate)**  
- Select optimal stocks for a mutual fund portfolio  
- Allocate investment weights using risk-based logic  
- Simulate **SIP-based returns** over multiple time horizons  

---

## Dataset
- **Name:** Nifty 50 Closing Prices  
- **Format:** CSV  
- **Content:** Daily closing prices of 50 Indian companies  
- **Key Column:**
  - `Date` – Trading date
  - Company-wise closing prices (e.g., `TCS.NS`, `RELIANCE.NS`, `INFY.NS`)

---

## Tools & Libraries
- **Language:** Python  
- **Libraries Used:**
  - `pandas` – Data handling and preprocessing  
  - `numpy` – Mathematical calculations  
  - `plotly` – Interactive visualizations  

---

## Project Workflow

### 1. Data Loading & Cleaning
- Loaded the dataset using Pandas  
- Converted `Date` column to DateTime format  
- Checked for missing values  

✔️ Dataset contained **no missing values**

---

### 2. Exploratory Data Analysis (EDA)
- Visualized stock price trends for all companies  
- Observed price movements and volatility patterns over time  

📈 Insight: Certain stocks showed high fluctuations, while others remained stable.

---

### 3. Risk & Return Analysis
- **Volatility (Risk):** Standard deviation of closing prices  
- **Growth Rate:** Percentage change in prices  
- **Return on Investment (ROI):**
  
ROI = ((Final Price - Initial Price) / Initial Price) * 100

✔️ Identified:
- High-risk stocks  
- High-growth stocks  
- High-ROI stocks  

---

### 4. Mutual Fund Stock Selection
To create a balanced mutual fund:
- Selected companies with **ROI above the median**
- Selected companies with **volatility below the median**

Result: Stocks offering **high return with low risk**

---

### 5. Investment Allocation Strategy
- Used **inverse volatility weighting**
- Lower risk → Higher allocation  
- Calculated percentage allocation for each stock  

✔️ Created a diversified mutual fund portfolio

---

### 6. Performance Comparison
Compared:
- **Mutual fund companies**
- **High-growth companies**

Metrics:
- Volatility (Risk)
- Expected ROI

📊 Conclusion:
- Growth stocks → High risk, high return  
- Mutual fund stocks → Lower risk, stable returns  

---

### 7. SIP Return Simulation
Simulated real-world investing:
- Monthly SIP: ₹5,000  
- Annual increase in SIP amount: 10%  
- Investment periods:
- 1 year  
- 3 years  
- 5 years  
- 10 years  

📈 Demonstrated the **power of compounding** for long-term investors.

---

## Key Insights
- Diversification reduces risk  
- High returns often come with higher volatility  
- Mutual funds balance risk and reward effectively  
- Long-term SIP investing leads to exponential wealth growth  

---

## Final Deliverables
- Cleaned and analyzed Nifty 50 data  
- Identified optimal mutual fund stocks  
- Designed investment allocation strategy  
- Compared risk vs return  
- Simulated long-term SIP returns  

---

## Conclusion
This project demonstrates how **Python-based financial analysis** can be used to design a **realistic mutual fund investment plan**.  
The methodology closely resembles how professional investment firms analyze risk, returns, and diversification for long-term investment decisions.

---



