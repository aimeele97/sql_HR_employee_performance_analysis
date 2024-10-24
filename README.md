# HR Employee Performance Analysis

## Overview

This project addresses three main areas: KPI performance, employee ratings, and recruitment channels. It offers insights and actionable recommendations to assist the HR department in identifying key challenges and developing strategies to enhance KPI performance, boost employee ratings, and optimize recruitment processes.

## Data Source

The data for this analysis is sourced from Kaggle: [Employee Performance Dataset](https://www.kaggle.com/datasets/sanjanchaudhari/employees-performance-for-hr-analytics).

## List of Business Problems

#### Employee Distribution by Gender, Department, Age

#### KPI Performance
1. What is the overall KPI achievement rate across the organization?
2. How do KPIs correlate with awards won by employees?
3. Which departments have the highest and lowest KPI performance?
4. What is the impact of training on KPI achievement?
5. How does the length of service affect KPI performance?
6. Which age groups achieve the highest KPIs?
7. How does education level relate to KPI performance?

#### Employee Ratings
8. What is the average employee rating within the company?
9. How do gender and department correlate with employee ratings?
10. Which department has the lowest average rating?
11. What percentage of low ratings (1 and 2 stars) come from specific departments?

#### Recruitment Channels
12. How many employees were hired through different recruitment channels?
13. What is the distribution of education levels across various recruitment sources? 

---

## Analysis Process

1. **Identify Business Problems:** Define key business challenges and objectives.
2. **Data Cleaning:** Profile the data to identify issues, then clean and transform the dataset for analysis.
3. **Data Analysis:** Analyze the data to address the identified problems and derive insights.
4. **Document Findings:** Record key findings and formulate actionable recommendations.

---

### Data cleaning 

- The dataset contained duplicates and entry errors. I created a backup table for future reference, then cleaned the data by removing duplicates and errors in a new staging table. This was transformed into the main table for analysis. 

--> The table was reduced from 17,417 rows to 17,413 by removing 2 duplicate rows and 2 entry errors for employee ID 64573.

## Key Findings

### 1. Employee Distribution by Gender, Department, Age
   - **Finding:**
      - Males represent approximately 91% of the total workforce, while females account for only 9%. Sales and Marketing department has the highest number of employees, comprising around 31% of the total workforce.
      - Employee ages range from 20 to 60 years, with an average age of 34. The ages are normally distributed across each department that help enhance team dynamics and knowledge sharing.
   - **Recommendation:** Launch initiatives to attract and retain female talent in underrepresented areas through targeted recruitment and mentorship.

### 2. KPI Analysis Summary
**KPI Achievement Rate**
   - **Finding:** Only 36% of employees achieve KPIs above 80%, highlighting a need for improved performance management and support.
   - **Recommendation:** Implement targeted performance improvement plans and allocate additional resources to assist employees in meeting their KPIs.

**Correlation Between KPIs and Awards**
   - **Finding:** Employees can receive awards without meeting KPI targets; however, those who do meet KPIs win significantly more awards.
   - **Recommendation:** Adjust award criteria to align more closely with KPI achievement to encourage high performance.

**Departmental KPI Performance**
   - **Finding:** R&D has the highest KPI achievement rate at 45% but only 1% of total awards, while Sales & Marketing has the lowest KPI performance but the highest awards.
   - **Recommendation:** Reevaluate award distribution practices to ensure recognition corresponds with KPI performance.

**Impact of Training on KPIs**
   - **Finding:** Training sessions have varying effects on KPI achievement, with some leading to notable improvements.
   - **Recommendation:** Identify and promote the most effective training programs, ensuring accessibility for all employees.

**Length of Service and KPI Performance**
   - **Finding:** Employees with 1 to 10 years of service achieve KPIs at rates of 30% to 40%, while performance slightly declines after 10 years.
   - **Recommendation:** Provide ongoing training sessions to help long-tenured employees update their skills and adapt to new technologies or processes.

**Age and KPI Achievement**
   - **Finding:** Employees aged 27 to 37 perform best in terms of KPI achievement.
   - **Recommendation:** Develop targeted training and support programs for both younger and older employees to bridge performance gaps.

**Education and KPI Performance**
   - **Finding:** Employees with a bachelor's degree achieve 65% KPI performance, whereas those with a master's degree achieve only 29%.
   - **Recommendation:** Explore other factors influencing performance, such as practical experience, and consider providing role-specific training to boost effectiveness.

### 3. Company Ratings
   - **Finding:** The average employee rating is 3.35 last year, with 18% low rating their experience (1 and 2) significantly in Sales and Marketing department. 
   - **Recommendation:** Conduct surveys to gather feedback on dissatisfaction and implement changes to improve job satisfaction.

### 4. Recruitment Effectiveness
   - **Finding:**
      The company recruited via 3 main channels: "Other" recruitment channels include job boards and company careers pages, "source" channels involve online postings and direct outreach, and referals fro current employees. Over 50% of hires come from "other" channels, 42% from direct sourcing, and only 1.8% from referrals, with balanced education levels across channels.
   - **Recommendation:** To improve recruitment quality, optimize sourcing strategies and provide training for hiring managers to better leverage the employee referral program.
Got it! Here’s the table without any merging and without empty rows:

---

## Key Findings and Recommendations

| **Group**                    | **Finding**                                                                                         | **Recommendation**                                                        |
|------------------------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| **Employee Overview**        | The company has 17,417 employees across 9 departments, with Sales and Marketing comprising 31% of the workforce. | Monitor departmental growth and implement workforce planning strategies. |
|                              | Male employees constitute over 50% of the total workforce in each department, while females are primarily found in Procurement, HR, and Operations. | Launch initiatives to attract and retain female talent in underrepresented areas. |
|                              | Average employee age varies by department, indicating diverse demographics.                         | Consider age diversity in team-building and training initiatives.        |
| **KPI Analysis**             | Only 36% of employees achieve KPIs above 80%.                                                     | Implement targeted performance improvement plans.                         |
|                              | Employees who meet KPIs win significantly more awards.                                             | Align award criteria with KPI achievement.                               |
|                              | R&D has the highest KPI achievement rate at 45%, but only 1% of total awards are given in this department. | Reevaluate award distribution practices.                                 |
|                              | Training sessions have varying effectiveness on KPI achievement.                                   | Identify and promote effective training programs.                        |
|                              | Employees with 1-10 years of service achieve KPIs at rates of 30%-40%.                            | Provide ongoing training for long-tenured employees.                    |
|                              | Employees aged 27-37 perform best in terms of KPI achievement.                                     | Develop support programs for both younger and older employees.          |
|                              | Employees with bachelor's degrees achieve 65% KPI performance, while those with master's degrees achieve only 29%. | Explore factors influencing performance and consider role-specific training. |
| **Employee Ratings Last Year** | The average employee rating is 3.35, with 18% of employees rating their experience low (1 and 2 stars), particularly in the Sales and Marketing department. | Conduct surveys to gather feedback on dissatisfaction and implement changes to improve job satisfaction. |
| **Recruitment Channels**     | Over 50% of hires come from "other" channels, while only 1.8% are sourced through referrals.       | Optimize sourcing strategies and enhance the employee referral program by providing training for hiring managers. |

## Overall Recommendation

Establish a continuous feedback loop with employees to gather insights and enhance organizational processes. Promoting a culture of transparency and engagement will lead to improved performance and employee satisfaction.

## License

MIT license

Copyright (c) [2024] [Aimee Le]
