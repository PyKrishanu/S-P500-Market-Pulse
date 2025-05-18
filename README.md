# S&P 500 Market Pulse

## 🎯 Project Goal:
Summarize the overall year on year performance of S&P 500 Index
Consistently strong-performing stocks to be considered for long term investment
Investment overview based on industries and sectors in S&P 500 Index


## 📁 Files Included
<a href="https://github.com/PyKrishanu/S-P500-Market-Pulse/blob/main/S%26P%20500%20Stock.pbix">PBIX</a>
<a href="https://github.com/PyKrishanu/S-P500-Market-Pulse/blob/main/S%26P%20500%20Pulse%20Model%20View.jpg">Model view</a>
<a href="https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks">Dataset</a>

## 📊 𝐖𝐡𝐚𝐭 𝐢𝐭 𝐫𝐞𝐯𝐞𝐚𝐥𝐬:
✅ Sum of S&P 500 index by Year
✅ Top Performing Industries in S&P 500 by Year
✅ Top 3 Stocks over the last 8 years based on average of adj close price
✅ Stock performance as per S&P 500 index
✅ S&P 500 Sector Weighting 

- ## 📊 Dashboard Preview
 <a href="https://github.com/PyKrishanu/S-P500-Market-Pulse/blob/main/S%26P%20500%20Pulse%20Dashboard.jpg">Dashboard</a>

💡 Tools & Skills Used:
 Power BI Desktop
 Power Query for data cleaning and data wrangling
 DAX for dynamic metrics conversion, dates, KPIs and calculations
 Data modelling, slicer sync, and visualization design

 ## 🧪 Process Followed
   - Imported `sp500_companies.csv`,`sp500_index.csv`and `sp500_stocks.csv` containing relevant information on Stock Name, Adj Close Price, Sector, Industry and weight.
   - Used **Power Query** to clean and standardize:
   - Created a Date Table and built hierarchy of Month Year 
   - Defined relationships between categorical and numerical data
   - Designed Power BI report with visuals like:
   - Bar charts,Line Chart,Pie Chart,Clustered Column Chart and Ribbon Chart
   - Identified top performing stocks, industries, sector and time periods
 
## ⚠️ Challenges Faced
- Stock short names were inconsistent (e.g., "WELL = "Welltower INC." vs "WELL = "Wells Fargo & Company")
- Conversion of Market Cap measure to billion using DAX Marketcap = 
FORMAT(
    sp500_companies[Marketcap_old] / 1000000000, 
    "0"
) & " Bn"
- Some current share price data had missing values
- Managing readability and aesthetics in diverging color setting

 
## ✅ Final Conclusion
The project provides an year on year general overview of S&P 500 market index. The objective is to highlight the well perfoming industries, sectors and suggest for stocks which can be considered for long term investment.

Future improvements can include breaking down the date category to a particular week to provide real time stock performance.
 
