# Tata-business-data-visualization
Executive-level Power BI dashboard analyzing sales, profitability, and regional performance (inspired by Tata Forage internship)


##### **Tata Group – Data Visualization: Empowering Business with Effective Insights**
This project was independently developed and inspired by the Tata Group – Data Visualization virtual internship on Forage.
The objective was to practice transforming business data into executive-level insights using Power BI

###### 📎 Notes
This project was independently implemented and is inspired by a virtual internship experience.
All analysis, modeling, and visualization work was performed end-to-end as part of portfolio development.

#### Tata Business Performance Analysis
#### Power BI | Data Analytics | Executive Dashboard

📌 **Project Background**
This project was independently developed as an end-to-end business analytics and visualization solution, inspired by the Tata Group – Data Visualization: Empowering Business with Effective Insights virtual internship on the Forage platform.

The objective was to simulate how a data analyst would transform raw business data into executive-ready insights that support strategic decision-making.
Rather than focusing only on charts, the project emphasizes:
1. Business understanding
2. Data preparation
3. Analytical modeling
4. Executive storytelling
---------------------------------------------------------------------------------------------------------------------
###### **🎯 Business Objective**

Senior leadership often needs quick, reliable answers to questions such as:
1. How is the business performing overall?
2. Are we growing year over year?
3. Which regions and products are profitable or loss-making?
4. Are issues driven by low sales volume or poor margins?

This project aims to answer those questions using a structured, decision-focused analytics approach.

----------------------------------------------------------------------------------------------------------------------
** Dataset Overview**

Dataset: Global Superstore (enterprise-style sales data)
Records: ~51,000 transactions
Key dimensions:

Time (Order Date, Ship Date)
Geography (Region, Country, Market)
Products (Category, Sub-Category, Product)
Customers (Segment, Customer)

The dataset closely resembles real-world retail and enterprise sales data used in consulting and analytics teams.

--------------------------------------------------------------------------------------------------------------------

**🛠 Tools \& Technologies Used**

Python (Pandas, NumPy) – data cleaning \& feature engineering
Power BI Desktop – data modeling, DAX, dashboards
DAX – KPI calculations and time-intelligence measures
GitHub – project documentation \& versioning

---------------------------------------------------------------------------------------------------------------------

🔄 **Step-by-Step Project Workflow**

🔹 Phase 1: Data Preparation \& Optimization (Python)
What was done

Loaded and inspected raw data
Standardized column names for BI compatibility
Handled missing values and duplicates responsibly
Converted date fields to proper datetime formats
Engineered business-driven features:
Time dimensions (Year, Month, Quarter)
Profit margin and profitability flags
Order value segmentation (High / Medium / Low)
Shipping delay metrics for operational insight

Why this matters

Power BI dashboards should focus on analysis and insights, not raw data fixing.
Preparing a decision-ready dataset improves accuracy, performance, and interpretability.

🔹 Phase 2: Power BI Data Modeling \& DAX

What was done
Loaded cleaned data into Power BI
Created a dedicated Measures table (best practice)
Built reusable DAX measures:
1. Total Sales
2. Total Profit
3. Profit Margin %
4. Year-over-Year Sales Growth
5. Running Total Sales
6. Customer ranking \& contribution analysis

Why this matters
1. Using DAX measures (instead of calculated columns) ensures:
2. Dynamic filtering
3. Reusability
4. Accurate executive-level KPIs

🔹 Phase 3: Dashboard Design \& Analytics
The dashboard is structured into two purpose-driven pages.

---------------------------------------------------------------------------------------------------
📊 Dashboard Pages

🟢 Page 1: Executive Overview
Purpose:
Provide leadership with a one-glance summary of overall business performance.

Key elements:
1. KPI cards: Sales, Profit, Margin, YoY Growth
2. Sales trend over time
3. Regional performance comparison
4. Profitability by product category
5. Interactive slicers (Year, Region, Segment)

Why this page exists
1. Executives need clarity, not complexity.
2. This page answers what is happening in the business.

🟢 Page 2: Regional \& Product Analysis
Purpose:
Diagnose why performance issues exist and where to act.

Key elements:
1. Profitability heatmap (Region × Category)
2. Sub-category profit deep-dive
3. Sales vs Profit scatter (volume vs margin analysis)

Why this page exists
1. Once leaders know what is happening, they need to understand:
2. Which combinations cause losses
3. Whether issues are volume-driven or margin-driven
4. Where optimization or corrective action is required

--------------------------------------------------------------------------------------------------
💡 Key Insights (Example)

1. Certain regions generate high sales but low or negative profit
2. Specific sub-categories consistently drive losses despite strong revenue
3. Some low-volume products deliver high margins and represent growth opportunities
4. Shipping delays correlate with weaker profitability in certain segments
-----------------------------------------------------------------------------------------------

📈 Business Recommendations

1. Prioritize margin optimization in high-sales but low-profit regions
2. Review pricing, discounting, and logistics for loss-making sub-categories
3. Invest in high-margin product segments with growth potential
4. Monitor operational KPIs (like shipping delays) alongside sales metrics

-----------------------------------------------------------------------------------------------
🧠 Key Learning Outcomes

1. Translating raw data into executive-ready insights
2. Applying business logic during data preparation
3. Writing reusable and scalable DAX measures



Designing dashboards for decision-making, not just reporting



Structuring analytics projects professionally for real-world use
