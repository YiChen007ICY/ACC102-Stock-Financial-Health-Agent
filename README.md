# Stock Financial Health Comparison Agent (AAPL vs TSLA 2018-2025)   

## 1. Problem & User 
This project addresses the need for a transparent, data-driven tool to compare the long-term financial health of two leading US public companies (Apple Inc. and Tesla, Inc.). It is designed for accounting students, beginner investors, and financial analysts to evaluate profitability, leverage, liquidity, and growth trends through a complete, reproducible Python workflow.   

## 2. Data 
• Source: Compustat (S&P Global) + verified public corporate annual financial reports (10-K filings)   
• Access Date: April 15, 2026   
• Time Period: Fiscal Years 2018 – 2025   
• Key Fields:   
◦ Raw financials: fyear, tic, ni (Net Income), at (Total Assets), lt (Total Liabilities), sale (Sales Revenue), che (Cash & Equivalents)   
◦ Calculated ratios: ROA, Debt_Ratio, Profit_Margin, Cash_Ratio, Revenue_Growth     
• Compliance: All data is publicly available, non-confidential, and used solely for academic educational analysis in ACC102, in full compliance with university academic integrity policies.    
## 3. Methods 
The project follows a complete end-to-end data analysis workflow implemented in Python:   
1. Data Loading & Display: Load verified historical financial data and output raw tables for full transparency.  
2. Financial Ratio Calculation: Compute core metrics for profitability, leverage, liquidity, and growth.  
3. Financial Health Scoring: Build a 0-100 scoring system to quantify overall financial performance.  
4. Comprehensive Analysis: Generate comparative summary tables, strength/risk analysis, and actionable conclusions.  
5. Visualization: Create multi-indicator trend charts to visualize year-over-year performance differences between AAPL and TSLA.  
6. Data Export: Save structured ratio data and high-resolution charts as standalone files for easy access.

## 4. Key Findings 
• AAPL: Maintains stable, high profitability (ROA ~29.75% in 2025) and strong liquidity, with a mature, low-risk business model and consistent profit margins.   
• TSLA: Delivers explosive revenue growth (peak 70.67% YoY) and rapidly improving profitability, but carries higher leverage and greater operational volatility.   
• Financial Health Score: Both companies achieve a 90/100 score in 2025, reflecting distinct strengths: AAPL excels in stability, while TSLA leads in growth potential.   
• Debt Ratio Trend: AAPL’s leverage remains elevated but stable (~78.85% in 2025), while TSLA’s leverage declines steadily from 78.89% (2018) to 60.23% (2025), showing deleveraging progress.   
• Cash Ratio: TSLA’s short-term liquidity outperforms AAPL in most years, driven by strong operating cash flow from growth.    

## 5. How to Run 
Environment Requirements   
• Python 3.8+   
• Required libraries: pandas, matplotlib   

Step-by-Step Execution   
1. Install dependencies: pip install pandas matplotlib  
2. Open the main notebook ACC102_Financial_Analysis.ipynb in Jupyter Notebook / Jupyter Lab.  
3. Run all cells in order to:  
◦ View raw financial data  
◦ See calculated financial ratios  
◦ Review the health score report  
◦ Generate comparative visualization charts  
4. The code will automatically export:  
◦ Financial_Data_2018_2025.csv: Structured ratio dataset  
◦ Visualization_Output.png: High-resolution comparison charts  

## 6. Product Link / Demo 
• GitHub Repository: https://github.com/YiChen007ICY/ACC102-Stock-Financial-Health-Agent   
• Demo: The notebook includes full, reproducible output with raw data, calculated ratios, and visualization charts. A 1-3 minute demo video is available in the submission package, showing the full execution workflow and key analysis conclusions.    

## 7. Limitations & Next Steps 
Limitations   
• The scoring system uses fixed, rule-based thresholds without industry-specific benchmarks.   
• The dataset is limited to 8 years of annual data, excluding quarterly performance and macroeconomic factors.   
• The analysis focuses on core financial ratios, excluding advanced metrics like DCF valuation or credit risk modeling.    
Next Steps   
• Integrate industry benchmark data to contextualize company performance.   
• Add interactive visualization tools (e.g., Plotly) for dynamic trend exploration.   
• Expand the dataset to include peer companies in the tech/automotive sectors for broader comparison.   
• Implement machine learning models to predict future financial health trends.
