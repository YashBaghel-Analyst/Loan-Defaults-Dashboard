# Loan-Defaults-Dashboard

## Recommended Structure and Order

### 1. Project Title / Headline
**Credit Risk Insights: Loan Default Analysis Dashboard**
An interactive Power BI dashboard designed to uncover key drivers of loan defaults across a large customer base—focusing on risk segmentation, borrower behavior, and strategic decision-making for financial institutions.

### 2. Short Description / Purpose
The Loan Default Analysis Dashboard provides a data-driven approach to understanding and reducing loan default risks. Built using Power BI, SQL, and DAX, it helps banks, lenders, and financial analysts identify risky borrower segments and optimize lending strategies.

### 3. Tech Stack
The dashboard was built using the following tools and technologies:
* 📊 **Power BI Desktop** – Used to create dynamic visuals, KPIs, and interactive filters.
* [cite_start]🧠 **DAX (Data Analysis Expressions)** – Used for calculated fields, Default Rate measures, Repayment Rate, and dynamic risk bands.
* 🧹 **Power Query** – Performed data transformation, type conversion, and cleansing.
* 🐍 **Python** – Performed EDA, 5-Number summary, and correlation analysis.
* [cite_start]⚡ **DirectQuery Mode** – Implemented incremental refresh for near real-time analytics and portfolio monitoring.
* 📄 **File Format** – `.pbix` for development and `.png` for report previews.

### 4. Data Source
**Source:** Internal Bank Loan Data (synthetic for privacy)
* [cite_start]Analyzed 255K+ loan records to identify high-risk borrowers.
* **Attributes included:** Credit score, debt-to-income ratio (DTI), co-signer status, employment length, loan type, interest rate, and default status.
* **Time period:** 2013-2018.
* Includes default history and repayment timelines.

### 5. Features / Highlights

* **Business Problem**
Banks and financial institutions struggle to minimize default rates while expanding credit access. Understanding what factors contribute most to defaults—especially across different borrower profiles—is critical to manage risk effectively.

* **Goal of the dashboard**
To create a decision-support tool that identifies high-risk borrower segments, highlights key indicators contributing to loan defaults, supports strategy planning around credit risk (co-signer policies, interest rates), and enables risk mitigation through interactive segmentation.

* **Walk through of key visuals (briefly!)**
  * **Key Metrics (KPI Cards):** Displays Total Applications (255,000+), Overall Default Rate, High-Risk Segments (e.g., DTI > 40%, no co-signer), and Average Interest Rate and Loan Amount.
  * **Default Rate by DTI Range (Bar Chart):** Visualizes how higher debt-to-income ratios correlate with increased default likelihood.
  * **Impact of Co-signers (Stacked Bar Chart):** Highlights how having a co-signer reduces default probability—especially in high-risk DTI segments.
  * **Loan Type vs. Default Status (Matrix Table):** Compares default rates across personal, home, auto, and student loans.
  * **Customer Profile Filter Panel:** Slicers for filtering by employment length, income range, and education level.

* **Business Impact & Insights**
  * [cite_start]**Employment & Loan Purpose Risk:** Discovered a 14%+ default rate among unemployed individuals taking out business loans.
  * [cite_start]**Safest Asset Classes:** Identified that home loans showed the highest repayment success rate across the portfolio at 89.7%.
  * [cite_start]**Segment Performance Tracking:** Built dynamic dashboards to track repayment success and segment performance by employment type and loan purpose.
