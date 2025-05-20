# 📊 Chapter 2 – Data Analytics: Addressing Accounting Questions with Data

---

## ✅ LO 2-1: Impact of Data Analytics on Business & Accounting

- **Data analytics** enables companies to uncover trends, forecast outcomes, and improve decision-making.
- Adds value by increasing productivity, utilization, and identifying risks/opportunities.
- CEOs from surveys (PwC, McKinsey) prioritize data analytics as a key strategic investment.
- **Accounting Impact**:
  - 🔹 *Financial Reporting*: Improves estimates (e.g., bad debt, inventory obsolescence).
  - 🔹 *Managerial Accounting*: Supports budgeting, cost tracking, and performance measurement.
  - 🔹 *Auditing*: Enhances fraud detection, efficiency, and audit automation.
  - 🔹 *Tax Accounting*: Assists in tax planning and regulatory reporting.

---

## ✅ LO 2-2: The 4 Vs of Big Data

**1. Volume** – Massive quantities of data (e.g., sensor data, clickstreams)  
**2. Variety** – Structured, unstructured, and semi-structured formats  
**3. Velocity** – Speed at which data is generated/analyzed  
**4. Veracity** – Data quality, accuracy, and reliability

📌 These dimensions influence how data is processed and interpreted in accounting decisions.

---

## ✅ LO 2-3: The AMPS Model (Data Analytics Process)

**AMPS** stands for:
- 🔍 **Ask** the question  
- 📊 **Master** the data  
- 📈 **Perform** the analysis  
- 📣 **Share** the story

**Model is recursive:** After sharing, you may refine the question and repeat.

🛠️ *Example*: A Honda dealership forecasts inventory by asking questions, gathering past sales and economic data, analyzing trends, and communicating insights.

---

## ✅ LO 2-4: Ask the Question

- Begins the **analytics mindset**.
- Good questions are specific, decision-focused, and data-answerable.
- Examples:  
  - Which product is most profitable?  
  - What is the risk of financial restatement?

---

## ✅ LO 2-5: Master the Data

Key considerations:
- **Accessibility** – Can we access it? Is it worth the cost?
- **Reliability** – Is it clean and current?
- **Integrity** – Is it consistent and valid?
- **Ethics** – Is it used responsibly and privately?
- **Type** – Structured/unstructured; numerical/categorical

---

## 📦 Data Sources by Branch of Accounting

| Branch                 | Example Data Sources |
|------------------------|----------------------|
| Financial Accounting   | General ledger, SEC filings, financial statements |
| Managerial Accounting  | Budget data, CRM data, POS transactions |
| Auditing               | Audit data standards, subledgers |
| Tax Accounting         | Tax returns, journal entries, tax-specific records |

---

## 📌 Additional Concepts

- **ETL (Extract, Transform, Load)** – Process of preparing raw data for analysis
- **Audit Data Standards (ADS)** – Developed by AICPA to streamline external auditor/client data exchange
- Benefits:  
  - Lower audit costs  
  - Consistency  
  - Reduced risk of data issues

---

[[AMPS Model]]
[[Big Data]]
[[Analytics Mindset]]
[[LO Index]]


---

## ✅ LO 2-6: Perform the Analysis (AMPS)

Analytics Types:
1. **Descriptive** – What happened?  
2. **Diagnostic** – Why did it happen?  
3. **Predictive** – What will happen?  
4. **Prescriptive** – What should we do?

Each analytics type answers different decision questions across accounting domains.

📊 **Exhibit 2.7 – Example Questions by Analytics Type and Branch**:

| Type           | Financial Accounting                   | Managerial Accounting                 | Audit                                       | Tax Accounting                        |
|----------------|----------------------------------------|----------------------------------------|---------------------------------------------|----------------------------------------|
| Descriptive    | Inventory balance, ratios              | Revenue growth, product profitability | A/R aging, related-party sales              | Tax paid, effective tax rate          |
| Diagnostic     | SG&A changes, asset turnover           | Variance analysis, revenue shifts     | Approval issues, check sequence            | Rate changes, tax income differences  |
| Predictive     | Forecast revenues/cash flows           | Will borrower repay loan?             | Risk of misstatements                      | IRS audit prediction                  |
| Prescriptive   | Cost optimization based on constraints | Break-even sales, product strategy    | Scheduling efficiency, client assessment   | Strategic tax relocation decisions    |

---

## ✅ LO 2-7: Demonstrate Data Analysis with Excel (AMPS Model)

Exhibit 2.9: **Demonstration Labs** show 4 types of analysis applied to real accounting questions using Excel:

| Lab                          | Question                                 | Data Source                                    | Analysis Type          |
|------------------------------|------------------------------------------|------------------------------------------------|------------------------|
| **Lab 1: Descriptive**       | How long have A/R been outstanding?      | A/R ledger, CRM                                | Pivot table (aging)    |
| **Lab 2: Diagnostic**        | Segregation of duties issues?            | Journal entries (created/approved by whom)     | Pivot table (cross-tab)|
| **Lab 3: Predictive**        | Probability of bankruptcy?               | Financial ratios                               | Altman Z-score model   |
| **Lab 4: Prescriptive**      | Sales needed to break even?              | Unit cost, revenue, fixed costs                | Excel what-if analysis |

📁 **Steps for Lab 1 (Accounts Receivable Aging)**:
1. Prepare working table with Days Past Due
2. Use PivotTable to group by 30-day buckets
3. Format results (e.g., group: 1–30, 31–60, ..., 151–180)
4. Double-click totals to drill into invoices
5. Use filters and search to analyze specific invoices
6. Calculate total A/R and verify doubtful account amounts

📌 **Final Output**: Use PivotTable to show total aging by bucket and identify specific overdue accounts.

---

[[AMPS Model]]
[[Descriptive Analytics]]
[[Predictive Analytics]]
[[Excel Analysis]]
[[LO Index]]


---

## ✅ Chapter 2 Closure – Summary, Key Terms, and Questions

---

### 📘 Summary (Page 86)

- **Big Data** = too large/complex for traditional systems; **Data Analytics** = extracting meaningful insight from it.
- High **costs** often exist to acquire and prepare data for analysis.
- Data analytics unlocks business value (e.g., improved marketing, risk forecasting, productivity).
- Impacts areas like **financial reporting**, **auditing**, **tax planning**, **internal control**, etc.
- **AMPS model** = Ask → Master → Perform → Share.
- **AICPA's Audit Data Standards (ADS)** streamline external auditor data use.

---

### 🧠 Keywords

| Term                     | Meaning                                                                 |
|--------------------------|-------------------------------------------------------------------------|
| **ADS**                  | AICPA standard for audit data file structures                          |
| **ETL**                  | Extract, transform, load – prepare raw data for analysis               |
| **Data Ethics**          | Responsible, ethical use of collected data                             |
| **Data Integrity**       | Accuracy and consistency of data                                       |
| **Structured Data**      | Neatly formatted data (e.g., financial statements)                     |
| **Unstructured Data**    | Social media, blog posts, images                                       |
| **Semi-structured Data** | Mix of both (e.g., PDFs with fields)                                   |
| **Categorical Data**     | Non-numeric, unordered (e.g., gender)                                  |
| **Numerical Data**       | Quantitative, ordered (e.g., price, quantity)                          |
| **Descriptive Analytics**| Summarizes what happened                                               |
| **Diagnostic Analytics** | Explains why it happened                                               |
| **Predictive Analytics** | Forecasts what will happen                                             |
| **Prescriptive Analytics**| Recommends action based on forecasts                                  |

---

### ✅ Answers to Progress Checks

1. Analytics gives auditors more time to interpret data and reduce judgment errors.
2. It helps identify write-downs, bad debts, and reactions based on public commentary.
3. Corn and weather → using data patterns = analytics.
4. Big Data = size; Analytics = value extraction.
5. Multiple iterations may be needed in AMPS loop.
6. “Master the Data” = identify right datasets and access them.
7. ADS = allows standardized data extraction for audits (less cleanup).
8. ADS also ensures consistent, audit-ready exports from accounting systems.
9. Altman Z-Score uses liquidity & solvency metrics to forecast bankruptcy.
10. Bankruptcy models are predictive, not guarantees.
11. Predictive = determines if something *will* happen.
12. Prescriptive = determines best strategy based on predicted outcomes.

---

### 💬 Discussion Questions (Page 89)

1. How might an airline use analytics to improve customer services? → [[LO 2-1]]
2. Difference between Big Data and Data Analytics? → [[LO 2-2]]
3. Why do vendors (like ACL Inc.) matter in using ADS? → [[LO 2-5]]
4. How do ADS improve external audit efficiency? → [[LO 2-5]]
5. Why is **Field 17 (Approved By)** useful to auditors?  
   What about **Field 19 (Modified By)** and **Field 20 (Modified Date)?** → [[LO 2-5]]
6. How do Descriptive vs Diagnostic analytics differ? → [[LO 2-6]]
7. What kind of analytics helps identify sales to break even? → Prescriptive → [[LO 2-6]]

---

[[Chapter 2]]
[[LO Index]]
[[ADS]]
[[AMPS Model]]
[[Data Analytics]]


---

