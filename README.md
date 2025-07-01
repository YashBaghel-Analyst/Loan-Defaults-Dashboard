# Loan-Defaults-Dashboard

 Credit Risk Insights: Loan Default Analysis Dashboard
An interactive Power BI dashboard designed to uncover key drivers of loan defaults across a large customer base—focusing on risk segmentation, borrower behavior, and strategic decision-making for financial institutions.

 Short Description / Purpose
The Loan Default Analysis Dashboard provides a data-driven approach to understanding and reducing loan default risks. Built using Power BI, SQL, and DAX, it helps banks, lenders, and financial analysts identify risky borrower segments and optimize lending strategies.

Tech Stack
The dashboard was built using the following tools and technologies:

 Power BI Desktop – Used to create dynamic visuals, KPIs, and interactive filters.

 DAX (Data Analysis Expressions) – Used for calculated fields, risk segmentation logic.

 Power Query – Performed data transformation, type conversion, and cleansing.

 Python – Performed EDA, 5-Number summary, and co-relation analysis.

 DirectQuery Mode – Ensured near real-time analytics with incremental refresh capabilities.

 File Format – .pbix for development and .png for report previews.


 Data Source
Internal Bank Loan Data (synthetic for privacy):
• 200,000+ loan applications with attributes including: credit score, debt-to-income ratio (DTI), co-signer status, employment length, loan type, interest rate, and default status.
• Time period: 2013-2018.
• Includes default history, repayment timelines etc.


 Features / Highlights
• Business Problem
Banks and financial institutions struggle to minimize default rates while expanding credit access. Understanding what factors contribute most to defaults—especially across different borrower profiles—is critical to manage risk effectively.

• Goal of the Dashboard
To create a decision-support tool that:

Identifies high-risk borrower segments

Highlights key indicators contributing to loan defaults

Supports strategy planning around credit risk, co-signer policies, and interest rates

Enables risk mitigation through interactive segmentation

• Walkthrough of Key Visuals
Key Metrics 

Total Applications: 255,000+

Overall Default Rate

High-Risk Segments (e.g., DTI > 40%, no co-signer)

Average Interest Rate and Loan Amount

Default Rate by DTI Range (Bar Chart)
Visualizes how higher debt-to-income ratios correlate with increased default likelihood.

Impact of Co-signers (Stacked Bar)
Highlights how having a co-signer reduces default probability—especially in high-risk DTI segments.

Loan Type vs. Default Status (Matrix Table)
Compares default rates across personal, home, auto, and student loans.

Customer Profile Filter Panel
Slicers for filtering by employment length, income range, and education level.

 Business Impact & Insights
For insigets check Loans Defaults Report.
