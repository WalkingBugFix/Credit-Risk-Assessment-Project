# Credit-Risk-Assessment-Project

**Context**
In the realm of modern finance, businesses encounter the perpetual challenge of managing debt obligations effectively to maintain a favorable credit standing and foster sustainable growth. Investors keenly scrutinize companies capable of navigating financial complexities while ensuring stability and profitability. A pivotal instrument in this evaluation process is the balance sheet, which provides a comprehensive overview of a company's assets, liabilities, and shareholder equity, offering insights into its financial health and operational efficiency. In this context, leveraging available financial data, particularly from preceding fiscal periods, becomes imperative for informed decision-making and strategic planning

**Business Problem**
A group of venture capitalists want to develop a Financial Health Assessment Tool. With the help of the tool, it endeavors to empower businesses and investors with a robust mechanism for evaluating the financial well-being and creditworthiness of companies. By harnessing machine learning techniques, they aim to analyze historical financial statements and extract pertinent insights to facilitate informed decision-making via the tool. Specifically, they foresee facilitating the following with the help of the tool:

Debt Management Analysis: Identify patterns and trends in debt management practices to assess the ability of businesses to fulfill financial obligations promptly and efficiently, and identify potential cases of default.
Credit Risk Evaluation: Evaluate credit risk exposure by analyzing liquidity ratios, debt-to-equity ratios, and other key financial indicators to ascertain the likelihood of default and inform investment decisions.
They have hired you as a data scientist and provided you with the financial metrics of different companies. The task is to analyze the data provided and develop a predictive model leveraging machine learning techniques to identify whether a given company will be tagged as a defaulter in terms of net worth next year. The predictive model will help the organization anticipate potential challenges with the financial performance of the companies and enable proactive risk mitigation strategies.


![feature_importances](https://github.com/user-attachments/assets/06940365-b19e-4059-bcae-c6faa32ae468)


**Data Dictionary**
The data consists of financial metrics from the balance sheets of different companies. The detailed data dictionary is given below.

Networth Next Year: Net worth of the customer in the next year
Total assets: Total assets of customer
Net worth: Net worth of the customer of the present year
Total income: Total income of the customer
Change in stock: Difference between the current value of the stock and the value of stock in the last trading day
Total expenses: Total expenses done by the customer
Profit after tax: Profit after tax deduction
PBDITA: Profit before depreciation, income tax, and amortization
PBT: Profit before tax deduction
Cash profit: Total Cash profit
PBDITA as % of total income: PBDITA / Total income
PBT as % of total income: PBT / Total income
PAT as % of total income: PAT / Total income
Cash profit as % of total income: Cash Profit / Total income
PAT as % of net worth: PAT / Net worth
Sales: Sales done by the customer
Income from financial services: Income from financial services
Other income: Income from other sources
Total capital: Total capital of the customer
Reserves and funds: Total reserves and funds of the customer
Borrowings: Total amount borrowed by the customer
Current liabilities & provisions: current liabilities of the customer
Deferred tax liability: Future income tax customer will pay because of the current transaction
Shareholders funds: Amount of equity in a company which belongs to shareholders
Cumulative retained profits: Total cumulative profit retained by customer
Capital employed: Current asset minus current liabilities
TOL/TNW: Total liabilities of the customer divided by Total net worth
Total term liabilities / tangible net worth: Short + long term liabilities divided by tangible net worth
Contingent liabilities / Net worth (%): Contingent liabilities / Net worth
Contingent liabilities: Liabilities because of uncertain events
Net fixed assets: The purchase price of all fixed assets
Investments: Total invested amount
Current assets: Assets that are expected to be converted to cash within a year
Net working capital: Difference between the current liabilities and current assets
Quick ratio (times): Total cash divided by current liabilities
Current ratio (times): Current assets divided by current liabilities
Debt to equity ratio (times): Total liabilities divided by its shareholder equity
Cash to current liabilities (times): Total liquid cash divided by current liabilities
Cash to average cost of sales per day: Total cash divided by the average cost of the sales
Creditors turnover: Net credit purchase divided by average trade creditors
Debtors turnover: Net credit sales divided by average accounts receivable
Finished goods turnover: Annual sales divided by average inventory
WIP turnover: The cost of goods sold for a period divided by the average inventory for that period
Raw material turnover: Cost of goods sold is divided by the average inventory for the same period
Shares outstanding: Number of issued shares minus the number of shares held in the company
Equity face value: cost of the equity at the time of issuing
EPS: Net income divided by the total number of outstanding share
Adjusted EPS: Adjusted net earnings divided by the weighted average number of common shares outstanding on a diluted basis during the plan year
Total liabilities: Sum of all types of liabilities
PE on BSE: Company's current stock price divided by its earnings per share
 

**Note:** A company will not be tagged as a defaulter if its net worth next year is positive, or else, it'll be tagged as a defaulter.
