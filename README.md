# Analysis of factors that influence Employee Attrition in an Organization

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparations](#data-cleaningpreparations)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview

This project sought to explore factors within an organization that influence employee attrition by analyzing factors such as job satisfaction, job involvement, renumerations and relationship with management. The aim of this analysis was to identify key drivers that influence employees’ decisions to leave an organization. Insights gained from this analysis can aid in improving retention strategies, ultimately reducing employee turnover rates. 

<img width="994" alt="EA_JS" src="https://github.com/user-attachments/assets/5b339c86-e7c6-4ead-b62c-dd3a46f74274" />

<img width="983" alt="EA_JS_RM" src="https://github.com/user-attachments/assets/22483e76-bf7b-47ab-9d6c-d2dd83b8723f" />

<img width="966" alt="EA_JL_MI" src="https://github.com/user-attachments/assets/39e121dc-ad0d-4c3e-97f3-7d81e8a12eb4" />


### Data Sources 

The dataset used for this analysis is “employee_attrition_dataset_10000.csv”  from kaggle datasets containing demographic, job-related and performance metrics of 10,000 employees that left an organization. [Download here](https://www.kaggle.com/datasets/ziya07/employee-attrition-prediction-dataset)  

### Tools

- Excel- Data Cleaning and Formatting
- Excel- Analysis using Pivot Tables 
- Power Bi -Data Visualization

### Data Cleaning/Preparations 

The following tasks were performed during the data preparation stage
- Data loading and Inspection 
- Handling missing values
- Data Cleaning and Formatting

### Exploratory Data Analysis 

This analysis involved exploring some factors in an organization that influence employee attrition and answer key questions such as: 
- What are some of the likely factors within an organization that result in employee attrition? 
- Does job satisfaction impact employee attritions? 
- Can the relationship with a manager and engagement in the organization mitigate some factors that lead to employee attrition? 
- How does renumeration impact employee attrition?

### Data Analysis 

Formulae such as IFS function in Excel were employed to categorize monthly income and also provide explanation for number rating of some factors that influence attrition. 
Example of Formulae used were;

``` =IFS(I2<7000,"Low",I2<=14000,"Medium",I2>=14000,"High")```				

``` =IFS(Z2=1,"Poor",Z2=2,"Fair",Z2=3,"Good",Z2=4,"Very Good")``` 

Job Satisfaction, Relationship with Manager and Job Involvement rated on an ordinal scale were translated into descriptive terms in Excel in order to create dashboards in Power bi. Monthly Income was categorized into high, medium and low. (Low- below £7,000, Medium £7,000- £14,000, High – above £14000) in order to analyze the relationship between renumerations and employee attrition. Pivot tables were then used to explore the relationships between the various factors and employee attrition. 

### Results/Findings 

The results of the analysis were summarized as follows: 

1. Employees with low job satisfaction are more likely to leave the organization as high attrition was observed in satisfied and very dissatisfied employee, while the highest number of people that stay in their employment were very satisfied.
2. The lowest attrition was noticed in employees who had very good relationship with their manager.
3. An ideal relationship with manager mitigated attrition especially among employees that had job satisfaction.
4. A careful balance between job involvement, opportunity for career progression and job satisfaction is required to retain employees.
5. Employees with considerably good renumeration are likely to leave an organization if other factors such as career progression and recognition are absent in the organization.

### Recommendations  

Based on the analysis, the following actions are recommended:
- Strategies that address job satisfactions such as career growth and work-life balance should be implemented. Additionally, interviews and surveys should be conducted to unearth issues encountered by employees. 
- Employees that are highly satisfied can be engaged to act as positive role models for other employees to promote a positive work environment. 
- Managers should be trained in programs to help improve their relations with employee and ensure effective communication. 
- Management should focus on programs that equip and involve employees in decision making processes. For employees with high job involvement, ensure that their contributions are recognized and provide career development opportunities.  
- Introduce career development opportunities for low and medium earning employees to provide the opportunity for promotions and earning high monthly income as well as some additional benefits that would motivate employees to stay.

### Limitations 

This analysis focused on quantitatively analyzing factors that influence attrition. Other emotional and psychological factors that lead to attrition could not be addressed in this analysis. 

### References 

1. McLeod, S. A., 2017. Ordinal scale. Simply Psychology. [Available at](https://www.simplypsychology.org/ordinal-scale.html)
2. McCollege, 2025. Cleaning the data: The crucial step that powers data science insights. [Available at](https://mccollege.edu/data-science/about-the-career-data-science/cleaning-the-data-the-crucial-step-that-powers-data-science-insights/) 
