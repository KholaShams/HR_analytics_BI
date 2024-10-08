# Case Study_ HR Analytics and Employee Management
--
## Table of Contents

- [Introduction](#introduction)
- [Data Analysis Lifecycle Stages](#data-analysis-lifecycle-stages)
  - [1. Business Understanding](#1-business-understanding)
  - [2. Data Understanding](#2-data-understanding)
    - [2.1 Data Sources](#21-data-sources)
    - [2.2 Key Metrics](#22-key-metrics)
  - [3. Data Preparation (Cleaning)](#3-data-preparation-cleaning)
    - [3.1 Data Cleaning Steps](#31-data-cleaning-steps)
  - [4. Data Analysis](#4-data-analysis)
    - [4.1 Descriptive Analysis](#41-descriptive-analysis)
      - [4.1.1 Demographics Analysis](#411-demographics-analysis)
      - [4.1.2 Geographical Distribution](#412-geographical-distribution)
      - [4.1.3 Job Title and Department](#413-job-title-and-department)
      - [4.1.4 Salary Distribution](#414-salary-distribution)
    - [4.2 Diagnostic Analysis](#42-diagnostic-analysis)
      - [4.2.1 Gender and Leadership](#421-gender-and-leadership)
      - [4.2.2 Ethnic Disparity in Leadership](#422-ethnic-disparity-in-leadership)
      - [4.2.3 Salary Disparities by Location](#423-salary-disparities-by-location)
  - [5. Data Visualization](#5-data-visualization)
    - [5.1 Gender and Ethnicity Breakdown](#51-gender-and-ethnicity-breakdown)
    - [5.2 Salary and Bonus Distribution](#52-salary-and-bonus-distribution)
    - [5.3 Hiring and Exit Trends](#53-hiring-and-exit-trends)
    - [5.4 Tenure and Retention Analysis](#54-tenure-and-retention-analysis)
    - [5.5 Geographical Distribution of Employees](#55-geographical-distribution-of-employees)
  - [6. Data Interpretation and Insights](#6-data-interpretation-and-insights)
    - [6.1 Gender and Ethnic Diversity](#61-gender-and-ethnic-diversity)
    - [6.2 Salary Inequity](#62-salary-inequity)
    - [6.3 Turnover and Retention](#63-turnover-and-retention)
    - [6.4 Age and Tenure](#64-age-and-tenure)
  - [7. Recommendations](#7-recommendations)
    - [7.1 Strengthening Diversity and Inclusion](#71-strengthening-diversity-and-inclusion)
    - [7.2 Addressing Salary Disparities](#72-addressing-salary-disparities)
    - [7.3 Enhancing Retention Strategies](#73-enhancing-retention-strategies)
    - [7.4 Expanding Regional Workforce](#74-expanding-regional-workforce)
  - [8. Conclusion](#8-conclusion)


## Introduction

This report provides an in-depth analysis of HR data focusing on employee demographics, diversity, salary distribution, and retention trends. The insights aim to support decision-making related to recruitment, employee development, diversity initiatives, and compensation strategies. The report follows the Data Analysis Lifecycle, beginning from data collection, cleaning, and ending with actionable recommendations based on insights from data analysis.

## Data Analysis Lifecycle Stages

### 1. Business Understanding

The primary objective of this analysis was to gain insights into the following:
- The diversity and demographics of the workforce.
- Compensation patterns across various departments and job titles.
- Employee retention trends and areas with high turnover.
- The distribution of employees across different geographies.

The overall goal was to derive actionable recommendations for improving diversity, retention, compensation, and strategic hiring.

### 2. Data Understanding

#### 2.1 Data Sources

The data provided consisted of the following attributes:
- **Employee ID**: Unique identifier for each employee.
- **First Name/Last Name**: Employee's name.
- **Gender**: Gender of the employee.
- **Ethnicity**: Ethnic background of the employee.
- **Age**: Age of the employee.
- **Job Title**: Current role or position.
- **Department**: Department to which the employee belongs.
- **Salary**: Annual salary.
- **Bonus %**: Percentage of bonus relative to salary.
- **Date of Hire**: When the employee was hired.
- **Country/City**: Geographic location of the employee.
- **Tenure**: Number of years the employee has been with the company.

#### 2.2 Key Metrics

- **Diversity Metrics**: Gender, ethnicity, and age distribution.
- **Compensation Metrics**: Salary and bonus percentages by job title and department.
- **Retention Metrics**: Hire and exit trends, turnover rates, and employee tenure.

### 3. Data Preparation (Cleaning)

The data cleaning process focused on ensuring consistency and accuracy in the dataset:

#### 3.1 Data Cleaning Steps

1. **Correcting Data Types**:
   - Ensured that numeric fields like Salary, Bonus%, and Tenure were appropriately cast as numbers.
   - Text fields such as Job Title, Department, and Country were treated as categorical data.
   - Dates, such as Hire Date, were correctly formatted as date types.

2. **Handling Missing Data**:
   - Verified that all rows contained complete information for key metrics.
   - Where possible, inferred missing values or flagged incomplete records for future data collection.

3. **Removing Duplicates**:
   - Ensured that there were no duplicate employee entries.

4. **Standardizing Formats**:
   - Standardized the format of Country and City names to maintain consistency across geographic data.

The data was now ready for analysis, with appropriate data types and cleaned fields.

### 4. Data Analysis

#### 4.1 Descriptive Analysis

This phase focused on identifying general trends in the dataset using key metrics and visualizations.

##### 4.1.1 Demographics Analysis

- **Gender**: A balanced gender distribution, with women occupying more senior roles than men.
- **Ethnicity**: Diverse ethnic representation, though Black employees constituted a smaller portion (10%) of the workforce, particularly at senior levels.
- **Age**: Majority of employees were in their 40s, with fewer in their 20s and 60s.

##### 4.1.2 Geographical Distribution

- The majority of employees were based in Seattle, with Brazil (Manaus) being the least represented region.

##### 4.1.3 Job Title and Department

- IT and Engineering had the highest employee numbers, while Support Roles were underrepresented.

##### 4.1.4 Salary Distribution

- Salaries showed disparities across locations, with Seattle employees earning significantly higher than those in Manaus.

#### 4.2 Diagnostic Analysis

This phase focused on identifying reasons behind key trends and patterns.

##### 4.2.1 Gender and Leadership

- **Observation**: Women were more prevalent in senior roles than men.
- **Diagnosis**: This may be a result of promotion policies favoring gender diversity at leadership levels.

##### 4.2.2 Ethnic Disparity in Leadership

- **Observation**: Black employees were less represented in senior positions.
- **Diagnosis**: This may be due to barriers in career progression for minority employees or inadequate diversity-driven leadership programs.

##### 4.2.3 Salary Disparities by Location

- **Observation**: Salaries were significantly higher in Seattle than in Manaus.
- **Diagnosis**: This may be due to geographic cost-of-living differences or unequal compensation structures between regions.

### 5. Data Visualization

To enhance understanding and provide actionable insights, various visualizations were created using Power BI, supplemented with Python scripts where necessary, to display trends, relationships, and distributions across different HR aspects:

#### 5.1 Gender and Ethnicity Breakdown
- **Pie/Donut Charts:** Displayed the gender distribution within the company, helping to visualize the proportion of male and female employees across departments.
  
 ![2](https://github.com/user-attachments/assets/44202519-0f11-46e5-9e09-7a8ab122f283)

- **Stacked Bar Chart:** Used to show the ethnic distribution across different business units, highlighting areas with greater or lesser diversity.
  
![1](https://github.com/user-attachments/assets/9602b62c-0169-405a-b141-edd7333c36ad)

#### 5.2 Salary and Bonus Distribution
- **Histogram:** Visualized the distribution of annual salaries, showing the frequency of different salary ranges within the company.
  
![5](https://github.com/user-attachments/assets/946c8d76-e29d-4e23-9c47-3b82ff1fbe9f)

#### 5.3 Hiring and Exit Trends
- **Line Charts:** Depicted hiring trends over time, showing the number of employees hired during different time periods. Another line chart was created for exit trends, revealing which timeframes saw higher employee turnover.
  
![7](https://github.com/user-attachments/assets/ee95fba1-3773-4c0b-9443-f2d67eb1a87a)

- **Gauge Chart:** Calculated and displayed the overall turnover rate, providing a clear view of how many employees exited the company relative to the total number of employees.
  
![6](https://github.com/user-attachments/assets/5d06913a-0849-48b8-b58a-7fb2e73181fa)


#### 5.4 Tenure and Retention Analysis
- **Bar Chart:** Showcased average tenure by department and job title, helping to identify which areas of the business had the longest or shortest employee tenures.
- **Stacked Column Chart:** Analyzed tenure by demographics (e.g., gender, age, ethnicity), revealing patterns in retention across different demographic groups. This provided insight into whether certain groups had a higher or lower average tenure.
  
![4](https://github.com/user-attachments/assets/6e5bf30e-73a7-4026-9aad-90cc04175540)

#### 5.5 Geographical Distribution of Employees
- **Scatter Map:** Displayed the distribution of employees across countries and cities, providing a clear view of employee concentrations and helping identify regions with the largest employee presence.
- **Tree Map:** Used to visualize employee counts by city and country, emphasizing areas with higher concentrations of staff.
  
![3](https://github.com/user-attachments/assets/57a02134-2f33-4ae5-89ed-d71cb578120f)

Each of these visualizations played a key role in uncovering actionable insights related to diversity, retention, and compensation, providing the company with a data-driven foundation for optimizing HR practices.

### 6. Data Interpretation and Insights

This section interprets the findings from the data analysis and visualization phases:

![final](https://github.com/user-attachments/assets/b9d9f04f-5a3a-420b-bb9c-49bebec1ba9f)


#### 6.1 Gender and Ethnic Diversity

- **Insight**: The company has a gender-balanced workforce, but there is room for improvement in ethnic diversity at higher levels.
- **Action**: Implement targeted diversity initiatives and review career progression pathways for minority groups.

#### 6.2 Salary Inequity

- **Insight**: Significant salary disparities exist between different geographic locations.
- **Action**: Conduct a comprehensive review of compensation structures and adjust salaries to ensure fair pay relative to cost-of-living differences.

#### 6.3 Turnover and Retention

- **Insight**: High turnover rates in certain departments suggest possible dissatisfaction or burnout.
- **Action**: Investigate the causes of high turnover and develop strategies to improve employee satisfaction and retention.

#### 6.4 Age and Tenure

- **Insight**: A majority of employees are in their 40s, with fewer younger employees.
- **Action**: Develop programs to attract younger talent and create pathways for career development to retain experienced employees.

### 7. Recommendations

Based on the analysis and insights derived, the following recommendations are proposed:

#### 7.1 Strengthening Diversity and Inclusion

- **Recommendation**: Enhance diversity and inclusion programs, with a focus on improving ethnic diversity at senior levels.
- **Action Plan**: Implement mentorship programs and diversity training for employees and leaders.

#### 7.2 Addressing Salary Disparities

- **Recommendation**: Address salary inequities by reviewing and adjusting compensation structures.
- **Action Plan**: Conduct market comparisons and ensure salary adjustments are made based on cost-of-living and role responsibilities.

#### 7.3 Enhancing Retention Strategies

- **Recommendation**: Develop and implement strategies to reduce turnover, particularly in high-exit departments.
- **Action Plan**: Improve employee engagement, review career development opportunities, and adjust workload expectations.

#### 7.4 Expanding Regional Workforce

- **Recommendation**: Explore opportunities to expand the workforce in underrepresented regions.
- **Action Plan**: Develop localized recruitment strategies and evaluate the potential benefits of diversifying regional talent pools.

### 8. Conclusion

The HR data analysis provided valuable insights into workforce diversity, compensation structures, and employee retention trends. By implementing the recommended strategies, the company can enhance its diversity and inclusion efforts, address salary disparities, improve employee retention, and explore opportunities for expanding its regional workforce. The ongoing monitoring and evaluation of these initiatives will ensure continued alignment with the company's strategic objectives and foster a more inclusive and equitable workplace.
