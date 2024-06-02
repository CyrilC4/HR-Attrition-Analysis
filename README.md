# HR Attrition Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)



### Project Overview

This HR attrition analysis project aims to provide insight into the performance of employees in an HR company. By analyzing the various aspects of the attrition data, we seek to identify trends, make data-driven recommendations dedicated to enhancing human resources decision-making by focusing on data cleaning and visualization.

### Data Source
HR Employee Attrition: The primary dataset used for this analysis is the "HR Employee Attrition csv" file, containing detailed information about each employee of the company.

### Tools
- Power BI 
 1. Data Cleaning
 2. Data Analysis
 3. Creating reports.


- ### Data Cleaning/Preparation

In the initial data preparation phase, meticulous optimization of the HR dataset was the primary focus. The following tasks were performed: 

- Data Loading and Inspection
- Redundant columns were eliminated
- Labels were clarified
- Duplicates were resolved
- Inconsistencies across columns were standardized.
- Addressing NaN values was crucial to ensure data accuracy, establishing a strong foundation for analysis.




- ### 📝 Data Analysis
  ```Measures
  Active Employees = SUM('HR-Employee-Attrition'[Employee Count])- SUM('HR-Employee-Attrition'[Attraction Count])
  ```
  ```
  Attrition Count = SWITCH(true(), 'HR-Employee-Attrition'[Attrition]="Yes",1, 'HR-Employee-Attrition'[Attrition]="No",0,0)
  ```
  ```
  Total Attrition = COUNT('HR-Employee-Attrition'[Attrition])
  ```




### Results/Findings

1.Total Attrition Count was higher for Male (150) than Female (87

﻿﻿
2. ﻿﻿Male accounted for 63.29% of Total Attrition Count.﻿﻿

﻿﻿
3. ﻿﻿At 606, Life Sciences had the highest Total Attrition and was 2,144.44% higher than Human Resources, which had the lowest Total Attrition at 27.﻿﻿

﻿﻿
4. ﻿﻿Across all 6 Education Field, Total Attrition ranged from 27 to 606.﻿﻿

﻿﻿
﻿﻿5. Research & Development had the highest total Attrition Count at 133, followed by Sales at 92 and Human Resources at 12.﻿﻿
  
﻿﻿
6. ﻿﻿Research & Development accounted for 56.12% of Total Attrition Count.﻿﻿

﻿﻿
7. ﻿Manager had the highest Average Monthly Income of $17,181.68, and was 554.29% higher than Sales Representative, which had the lowest Average of Monthly Income at $2,626.00.﻿﻿

﻿﻿
﻿﻿8. Average Monthly Income and total Attrition Count are negatively correlated with each other.﻿﻿
  
﻿﻿
9. ﻿﻿Laboratory Technician accounted for 26.16% of Total Attrition Count.

﻿
10. Male gender between ﻿﻿31-45 made up 28.27% of Total Attrition Count.﻿﻿

﻿
﻿﻿11. Total Attrition Count for Male and Female diverged the most when the Age Bracket was 31-45, when Male were 31 higher than Female.﻿﻿
  
﻿﻿
12. Employees who were Satisfied with their jobs were 73, followed by Very Disatisfied at 66, Very Satisfied at 52, and Dissatified at 46.﻿﻿

﻿﻿
13. ﻿﻿Very Dissatified at their job accounted for 30.38% of Total Attrition Count.﻿﻿

﻿﻿
14. ﻿﻿Across all 4 Job Involvement, Total Attrition Count ranged from 13 to 125.﻿﻿




### Recommendations:

Based on the analysis, the following actions are recommended

- Conduct Detailed Surveys: To better understand the reasons behind attrition, conduct detailed employee surveys focusing on work conditions, job satisfaction, addressing income disparities, work environment, compensation packagaes, and career growth opportunities.

- Implement Retention Programs: Based on survey results, design and implement retention programs tailored to address the specific needs of different employee groups.

- Monitor and Evaluate: Continuously monitor attrition rates and evaluate the effectiveness of implemented strategies. Make adjustments as needed to ensure ongoing improvement in employee retention.

- By addressing these areas with targeted strategies, the organization can effectively reduce employee attrition and improve overall job satisfaction and retention rates.
﻿﻿
﻿
