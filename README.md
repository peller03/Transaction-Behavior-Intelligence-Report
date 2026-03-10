# Personal-Finance-Transaction-Analytics-2025
---
## Table of Contents
- [Project Scope](#project-scope)
- [Data Sources](#data-sources)
- [Tool Used](#tool-used)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis Performed](#exploratory-data-analysis-performed)
- [EDA Visual Insights](#eda-visual-insights)
- [Data Analysis](#data-analysis)
- [Results / Findings](#results--findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

---

### Project Scope
This project analyzes **personal banking transaction data for the year 2025** to uncover financial behavior patterns, spending dominance, and income sustainability.

The objective is to transform raw transaction history into **behavioral financial intelligence** by identifying how income flows in, how expenses accumulate, and which financial habits create the most pressure on personal finances.

## Dashboard Preview

 ![_3385_Opay_page-0001__4216_Opay_page-0002__9912_Opay_page-0003](https://github.com/user-attachments/assets/204ebba7-18fa-405d-b06d-93553dcaaaa5)


The dashboard focuses on answering key questions such as:

- Where does most of the money go?
- Which spending categories dominate total expenses?
- How often do debit transactions occur compared to income inflows?
- Are there seasonal or behavioral spending patterns?
- What recurring financial activities contribute to long-term financial pressure?

The analysis is structured into **two main analytical views**:

- **Expense Behavior & Financial Leakages**
- **Income Stability & Growth Analysis**

This approach demonstrates how transaction data can evolve from simple records into **actionable financial insights**.

---

### Data Sources
The dataset used for this project consists of **personal bank transaction records for the year 2025**.

The dataset includes the following attributes:

- Transaction Date
- Transaction Description
- Transaction Type
- Category (Airtime, Transfer, Betting, Charges, etc.)
- Debit Amount
- Credit Amount
- Account Balance
- Transaction Channel

Additional analytical fields were derived during the cleaning process to support behavioral analysis.

---

### Tool Used
- **Microsoft Power BI** – Data modeling, DAX measures, and dashboard visualization  
- **Power Query** – Data transformation and cleaning  
- **Microsoft Excel** – Initial data exploration and preprocessing  

---

### Data Cleaning & Preparation
The dataset required preprocessing before analysis.

The following steps were performed:

1. Standardized transaction date formats to enable time-based analysis.
2. Extracted temporal fields such as **Month, Quarter, Weekday, and Year**.
3. Classified transactions into **Income or Expense categories**.
4. Created **transaction categories** such as Airtime, Betting, Transfers, Charges, and Mobile Data.
5. Identified **recurring transactions** to analyze long-term financial impact.
6. Cleaned and normalized description fields for accurate categorization.
7. Verified debit and credit fields to ensure financial consistency.
8. Removed null or incomplete records where necessary.

These steps ensured that the dataset was reliable for meaningful financial analysis.

---

### Exploratory Data Analysis Performed
The EDA focused on understanding **financial behavior patterns and transaction dominance**.

Key KPIs analyzed include:

- Total Transactions
- Total Expenses
- Total Income
- Net Balance
- Debit vs Credit Distribution
- Monthly Expense Trends
- Monthly Income Trends
- Highest Spending Month
- Average Monthly Income
- Recurring Transaction Impact

These metrics help evaluate **financial pressure points and income sustainability**.

---

### EDA Visual Insights
Key patterns observed during visualization include:

- **Transfer transactions dominate total expenses**, significantly exceeding other categories.
- **Debit transactions account for a large majority of total activity**, indicating stronger outflow than inflow.
- **Wednesday recorded the highest spending activity**, reflecting behavioral patterns linked to daily routines.
- **December recorded the highest expenses**, largely influenced by festive spending periods.
- Income patterns show **project-based inflows**, with irregular but high-value deposits.
- Recurring expenses such as **airtime, betting, and data purchases** contribute consistently to financial outflows.

These patterns demonstrate how everyday financial behaviors accumulate into significant yearly financial outcomes.

---

### Data Analysis
Using **Power BI and DAX**, several analytical measures were developed to evaluate financial trends.

Key calculations include:

- Total Expense and Total Income aggregation
- Net Balance computation
- Month-over-Month transaction comparisons
- Category-level expense dominance analysis
- Average monthly income calculation
- Peak spending weekday identification
- Drill-through capability enabling transaction-level inspection

The drill-through feature allows users to move from **high-level category summaries to individual transaction details**, improving transparency and traceability.

---

### Results / Findings
From the analysis:

- **Transfer transactions account for the largest share of expenses**, indicating behavioral spending concentration.
- Debit transactions represent **over 80% of total financial activity**, significantly exceeding credit inflows.
- Spending behavior shows **clear weekly patterns**, with certain days consistently recording higher expenses.
- Seasonal spikes occur, with **December showing the highest expense levels**.
- Income inflows appear **irregular and project-driven**, rather than evenly distributed monthly.
- Recurring transactions, although individually small, accumulate to meaningful yearly financial impact.

Overall, the analysis highlights how **behavioral spending patterns drive financial pressure more than single large purchases**.

---

### Recommendations
Based on the insights derived from the dashboard:

1. Monitor dominant expense categories, particularly **transfer-based spending**, to reduce unnecessary financial leakage.
2. Track recurring expenses such as airtime, data purchases, and subscriptions to control cumulative costs.
3. Establish **monthly budgeting thresholds** based on historical spending behavior.
4. Implement periodic financial reviews to identify emerging spending trends.
5. Use behavioral insights to improve financial awareness and long-term financial planning.

These insights demonstrate how financial data analysis can support **better personal finance decision-making**.

---

### Limitations
While the analysis provides valuable insights, certain limitations exist:

- The dataset represents **a single individual's financial records**, limiting broader generalization.
- Some transaction descriptions required manual categorization due to inconsistent labeling.
- External factors influencing income or expenses (such as personal events or business activities) were not fully captured in the dataset.
- The analysis relies on historical transaction data and does not predict future financial behavior.

Future work could expand the model to support **automated categorization, predictive financial trends, and multi-user financial behavior analysis**.
