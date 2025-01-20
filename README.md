# Healthcare-Data-Analysis
Power BI dashboard and analysis for healthcare data insights

Introduction

This project involves a comprehensive analysis of healthcare data, leveraging Power BI, SQL, and Python to extract insights and create predictive models. The objective of the project was to analyze patient demographics, billing, medication usage, and medical conditions while also predicting the length of stay for various medical conditions and test results.

The project workflow includes:

1. Loading and analyzing the healthcare dataset in MySQL using SQL queries.
2. Data modeling, cleaning, transformation, and visualization using Power BI.
3. Integration of Python visuals within Power BI to predict patient recovery times based on test results and medical conditions.
4. Creating a dynamic and interactive dashboard for presenting insights.



Data Understanding: The healthcare dataset used in this project includes features such as Gender, Blood Type, Medical Conditions, Insurance Provider, Medication Usage, Billing Amounts, and Test Results. These attributes allow for an in-depth exploration of patient demographics, health conditions, and financial metrics, creating a foundation for actionable insights and decision-making.


Data Preprocessing -
1. ETL Process in Power BI:
Data Cleaning: Handled missing and inconsistent values to ensure data accuracy.
Data Transformation: Split and transformed tables for better data organization, making the analysis more structured and efficient.
Data Modeling: Established relationships between tables, enabling seamless integration of different dataset features.

2. DAX Calculations:
Created calculated fields and measures, such as total billing amounts and patient counts, for advanced aggregation and summarization.
Implemented measures to dynamically calculate KPIs like the average billing amount, common medical conditions, and patient distribution by gender and blood type.



Visual Insights-
The dashboard provides several insights into key aspects of healthcare metrics:


Patient Demographics
  1. Gender Distribution: Male and female patient counts are nearly equal, with a slight male majority of 50.02%.
This balance suggests the hospital caters to a broad and diverse patient demographic.
      
  2. Blood Type Distribution: Blood types show varying distribution, with common types like O+ and A+ having the highest counts.
Less common blood types, such as AB- and O-, represent smaller patient groups.


Medical Conditions and Medication Usage
  1. Common Medical Conditions: Arthritis is identified as the most common medical condition among patients.
Other conditions analyzed include diabetes, obesity, hypertension, and cancer, contributing to overall patient trends.


  2. Medication Usage: Popular medications include Aspirin, Ibuprofen, and Paracetamol, with each accounting for around 20% of total usage.
The consistent distribution across medications suggests a balanced prescription pattern.



Insurance and Billing Analysis
  1. Average Billing Amounts: The average billing amount is $25.56K, providing a benchmark for financial analysis.
Billing is categorized by insurance providers, with UnitedHealthcare, Medicare, and Blue Cross being prominent contributors.

  2. Billing by Medical Conditions: Conditions like cancer and diabetes contribute to higher billing amounts compared to other conditions.
This reflects the resource-intensive nature of treating such illnesses.



Trends and Patterns
  1. Yearly Distribution: The dataset allows filtering by year, providing insights into patient trends over time.
  
  2. Predicted Length of Stay: Using Python visuals, the dashboard predicts patient recovery times based on medical conditions and test results.
Conditions like arthritis and cancer show longer recovery times, aiding operational planning for resource allocation.
  
  3.Insurance Provider Analysis: Trends across insurance providers reveal billing patterns and patient distribution, helping to understand the financial dynamics of the hospital.





Interactive Dashboard Features

The Power BI dashboard is highly interactive, enabling users to:
Filter data by year, insurance provider, and gender.
Dynamically view patient demographics, billing trends, and medical conditions.
Gain actionable insights from Python-based predictive visuals.




Summary 

This project showcases a robust analysis of healthcare data, enabling data-driven decision-making in patient management, financial analysis, and operational planning. The integration of SQL, Power BI, and Python ensures a comprehensive approach to data handling and visualization.



