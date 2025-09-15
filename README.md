# Data Science Assignment â€“ Web3 Trading Team

## Overview
This project analyzes the relationship between **trader behavior** (profitability, risk, volume, leverage) 
and **market sentiment** (Fear vs Greed). The goal is to identify hidden patterns that could influence 
smarter trading strategies.

## Project Structure
```
ds_umairaAnsari/
notebook_1.ipynb     # Main analysis notebook (Google Colab)
csv_files/           # Intermediate/processed CSV files
outputs/             # Graphs, charts, and visual outputs
ds_report.pdf        # Final summarized insights
README.md            # Project documentation
```

##  Datasets
1. **Bitcoin Market Sentiment Dataset**  
   - Columns: `Date`, `Classification` (Fear / Greed)

2. **Historical Trader Data (Hyperliquid)**  
   - Columns include: `account`, `symbol`, `execution price`, `size`, `side`, 
   `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.

Dataset Links:  
- [Historical Trader Data]- [Fear & Greed Index](https://colab.research.google.com/drive/1B8xAHPRjGzvS2Q66FY43Tj8u_-IlyUL0?usp=drive_link)  


## How to Run
1. Open `notebook_1.ipynb` in **Google Colab**.
2. Ensure you have access to the dataset links.
3. Run all cells to generate EDA outputs and insights.
4. Processed CSVs will be saved inside `csv_files/`.
5. Charts/plots will be saved inside `outputs/`.

## Key Analysis Performed
- Data Preprocessing & Cleaning  
- Trade behavior comparison in Fear vs Greed  
- Leverage & PnL analysis  
- Correlation heatmap  
- Visual insights with boxplots, line charts, and bar plots  

##  Report
Final summarized findings are documented in **ds_report.pdf**.

## Author
- Candidate Name: `Umaira Ansari
- Submission for **Web3 Trading Team“ Data Science Assignment**
