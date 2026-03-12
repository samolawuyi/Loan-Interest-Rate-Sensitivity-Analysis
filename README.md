# Loan-Interest-Rate-Sensitivity-Analysis
This project is a Financial Decision-Support Tool designed to calculate and compare the total cost of ownership for loans with varying interest rates. By isolating the interest rate as the independent variable, the model provides a clear view of how borrowing costs scale over a fixed term.
How it Works
​The model uses a deterministic approach to calculate loan outcomes based on a standard $20,000 principal:
​Calculation Logic
​The workbook follows a linear financial logic:
​Interest Paid: Calculated as Principal \times Interest\ Rate. (Assuming a 12-month term where t=1).
​Total Loan Paid: Principal + Interest\ Paid.
​Monthly Payments: Total\ Loan\ Paid / 12.
​Scenario Comparison
​The model compares four loan tiers:
​Loan A (9%): The high-end benchmark for total interest cost ($1,800).
​Loan D (6%): The optimized "ideal" scenario with the lowest monthly burden ($1,766.67).
​Visualization
​Monthly Payments Chart: A bar graph that visualizes the "stepped" increase in monthly installments. This helps non-financial stakeholders quickly grasp the impact of a 100-basis-point (1%) rate hike.
​Technical Implementation
​Absolute & Relative Referencing: Used to maintain principal consistency while iterating through different interest rate inputs.
​Data Formatting: Applied currency and percentage accounting styles for professional-grade reporting.
​UI Clarity: Minimalist design focused on key KPIs (Total Interest and Monthly Payment).
​Impact
​This tool is highly effective for:
​Personal Finance: Comparing credit card or personal loan offers.
​Small Business: Evaluating short-term bridge loans or equipment financing.
​Budgeting: Understanding monthly cash flow requirements before committing to debt.
