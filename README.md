**Purpose of the Report**
This Power BI report was developed to provide actionable insights into employee attrition, performance trends, and workforce demographics at a fictional company, Atlas Labs. The **goal** was to answer key human resource management questions, including:

- What is the overall attrition rate, and how has it changed over time?
- Which departments and roles are most affected by attrition?
- What employee characteristics (e.g., travel frequency, tenure, overtime) are most associated with high attrition?
- How do individual employee performance metrics evolve over time?
- Which departments are growing or shrinking based on hiring trends?
- How do satisfaction ratings and work-life balance relate to performance?

🧩 **Data Sources**
The report was built by merging five separate CSV datasets containing:
- Employee details
- Job roles and departments
- Performance reviews
- Satisfaction ratings
- Attrition records

_These datasets were cleaned, transformed, and joined using Power Query and DAX in Power BI to create a unified analytical model._

📁 **Pages Overview**
The report is structured into four interactive pages:

***1. Overview***
This page provides a high-level snapshot of the organization's workforce.
Insights:
- Clear growth and decline patterns in hiring over the years.
- Technology department leads in employee strength.
- Sales has high employee count and is a critical area for monitoring attrition and performance.

***2. Demographics***
This page breaks down the workforce and attrition trends based on employee attributes.
Insights:
- Highest attrition among recruiters and sales representatives.
- Employees who travel frequently or work overtime are more prone to leaving.
- A steep drop in attrition rate as employee tenure increases—highlighting the importance of employee retention in early years.

***3. Performance Tracker***
This page tracks individual employee satisfaction and performance over time.
Use Case:
- Ideal for HR managers to assess individual employee trends over multiple years.
- Helps identify employees at risk of attrition due to decreasing satisfaction or poor manager feedback.

***4. Attrition***
This page consolidates and deep-dives into the specific causes and patterns of attrition.
Insights:
- Over 30% attrition among new employees with less than 2 years at the company.
- Strong correlation between frequent business travel and attrition.
- Overtime significantly increases likelihood of employee turnover.

⚙️ **Steps Taken to Create the Report**
***Data Integration:***
- Merged five CSV datasets using Power Query, ensuring consistent keys and schema alignment.
***Data Cleaning and Transformation:***
- Removed duplicates, handled nulls, formatted dates and categories.
- Created calculated columns and measures using DAX (e.g., Attrition Rate, Active Employees).
***Data Modeling:***
- Designed a star schema for performance and attrition analysis.
- Established relationships between employee, job, satisfaction, and attrition datasets.

📌 **Key Insights**
- Attrition is highest among sales and recruiting roles, especially within the first 2 years of tenure.
- Frequent business travel and overtime are strongly linked to higher attrition rates.
- Performance and satisfaction metrics decline in some departments before attrition, highlighting the importance of early intervention.
- Departments like Technology and R&D show consistent employee retention and performance stability.

📌 **Takeaways & Reflections**
- Early attrition is a major issue; intervention programs like mentorship and onboarding optimization can help.
- Work-life balance and managerial support are leading indicators of satisfaction and retention.
- Frequent travelers and overtime workers are at high attrition risk—flexible work arrangements could reduce churn.
- The dashboard allows both macro-level insights (company-wide trends) and micro-level insights (individual employee performance).
