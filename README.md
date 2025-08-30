# Diabetes USA Market Analysis

## Overview:

Welcome to my analysis of type 2 diabetes, focusing on disease analysis in the USA and Marketing analysis for the top 5 drugs in the US managing this disease. Diabetes mellitus is a condition that happens when your blood sugar (glucose) is too high. It develops when your pancreas doesn’t make enough insulin or any at all, or when your body isn’t responding to the effects of insulin properly. This project was created out of a desire to understand the disease burden, its prevalence, risk factors, occurrence at the county level, and to analyze the marketing strategies of the top 5 drugs. It delves into the disease status in the USA market and companies' marketing performance to help find optimal marketing activities to tackle this disease.

The data was sourced from two separate sources; the USA disease data was sourced from the Centers for Disease Control and Prevention (CDC) website. The disease data contains detailed information on age groups, genders, diagnosed percentage per county, obesity percentages/county for US race and ethnicity, Social Vulnerability Index (SVI)/county, and diagnosed/undiagnosed percentages across years. Due to the proprietary nature of pharmaceutical sales/marketing data, this project utilized a simulated dataset that mirrors a real-world scenario. The simulated data was supplemented with real figures for drug sales and marketing expenditures from the company's 10-K filing, as well as trusted blogs on pharma websites, such as xtalks. The data was created to demonstrate my ability to analyze key marketing metrics, including market share, sales trends, and campaign effectiveness. The simulated data contains detailed information on drug name, prescriptions filled, new patients started, sales, marketing spend on digital Ads, marketing spend on Healthcare professionals, and competitors' prescriptions.

## Tools I Used:
For my deep dive into the data analyst job market, I harnessed the power of several key tools:
  - Python: The backbone of my analysis, allowing me to analyze the data and find critical insights. I also used the following Python libraries:
      - Pandas Library: This was used to analyze the data.
      - Matplotlib Library: I used it to visualize the data.
      - Seaborn Library: Helped me create more advanced visuals.
  - Jupyter Notebooks: The tool I used to run my Python scripts, which let me easily include my notes and analysis.
  - Visual Studio Code: My go-to for executing my Python scripts.

## The Questions:
The questions are divided into two parts, the Medical Part and the Marketing Part:
      - Diabetes Disease State Questions:
          - What are the demographic characteristics of the American population with diabetes?
          - What are the most prevalent health risk factors among people with diabetes?
          - Is there a relationship between child Poverty and the prevalence of diabetes?
          - How has the percentage of undiagnosed and diagnosed diabetes changed over time in the US?
          - Which US counties have the highest diagnosed diabetes rates, and what is the total population of those counties?
          - What are the top 20 states with the highest overall percentage of diagnosed diabetes?
          - What are the top 20 counties/states with the highest overall cases of diagnosed diabetes?
          - How does the percentage of children in poverty correlate with diagnosed diabetes rates at the county level?
          - Is there a relationship between race and ethnicity and the prevalence of obesity and physical inactivity in a county?
          - What is the relationship between the overall obesity rate and the diagnosed diabetes rate at the county level?
          - Which counties have a high percentage of diagnosed diabetes? 



## The Analysis:
The Jupyter notebook for this part of the project aimed at investigating specific aspects of the US diabetes disease state. Here’s how I approached each question:

### What are the demographic characteristics of the American population with diabetes?

To find the main demographics of the American population with diabetes, I filtered the data for the age groups of diabetes diagnosed/undiagnosed, then I filtered for the gender diagnosed/undiagnosed diabetes percentage, and then for the percentage of diabetes diagnosed for each ethnic group. I plotted a subplots bar chart for the age group to identify the difference between the groups diagnosed and the undiagnosed numbers. In the same way, I plotted subplot pie charts for the gender data. For the ethnic groups data, I plotted it on a bar chart to demonstrate the differences in diabetes occurrence across different ethnicities.

### Results

![Visualization for age gp diagnoes with diabetes](Age_gps_Diabetes.png)

![Visualization for Gender gp diagnoes with diabetes](Diabetes_by_Gender.png)

![Visualization for race and ethinicity diagnoes with diabetes](Race_and_Ethinicity.png)

### Insights


