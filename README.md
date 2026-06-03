
# Data Science Salary Analytics Dashboard (Power BI Dashboard)

### Dashboard File: The dashboard can be simply downloaded from the files section above.

## Problem Statement

With the increasing globalization of the data science field and the shift towards remote work, it is essential to understand how factors such as experience level, employment type, company size, and geographical location influence salary outcomes in the industry. This analysis seeks to explore the relationship between these factors and standardized salary (in USD) to answer key questions: How does experience level impact salary? How do regional and company size variations affect salary distributions?

The insights from this analysis will provide valuable benchmarks for salary expectations across different job titles, experience levels, and employment types. These insights can help employers structure competitive compensation packages and guide job seekers in understanding how various factors might affect their earning potential within the data science field.

## Dashboard View (Power BI Desktop)

![dashboard-datascience](https://github.com/user-attachments/assets/f3b4fdb5-e93a-427c-97ab-6462e5e9d102)

### Steps followed 

- Step 1 : Load data into Power BI Desktop (from csv file). The full dataset is available here: 
https://www.kaggle.com/datasets/yusufdelikkaya/datascience-salaries-2024

- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution" and "column quality" options.

- Step 3 : It was observed that in none of the columns errors & empty values were present. It says that the dataset is clean and is ready to making charts. 

- Step 4 : For data clarity, values for columns: experience_level, employement_type and company_size have been swapped. Replaced values: FT by Full-Time, M by Medium, L by Large, SE by Senior etc. to avoid the shortcuts.

- Step 5 : The theme of the Dashboard was created manually. The boxes behind the charts were created by selecting: Insert > Shapes > Rectangle.

- Step 6 : Vizualizations used in the dashboard:
  
a) Filled Map - visual comparison of average salary (USD) across different regions based on employee residence 

b) Pie Chart - to illustrate the proportions of average salary by company size within the dataset

c) Stacked Column Chart - visualization of avarage salaries for each experience level along with variability

d) Stacked Bar Chart - comparison of average salary by job title (shown Top 10 results by average salary)

e) Line Chart - to show trends in salary over time (work year)

f) Slicers - to filter the charts/plots by different categories

Every type of chart was selected from the Visualization Pane.

- Step 7 : Visual filters (Slicers) were added for 3 fields named "Employment Type", "Work Year" & "Experience Level".


# Insights

The one-page report was created in Power BI Desktop. This is my first, basic project, so it is difficult to come to very in-depth insights.

Although, following example inferences can be drawn from the dashboard:

### [1] With no filters:
 - The highest average salary is noticed in the USA = 157 702 $
   
 ![map](https://github.com/user-attachments/assets/b29b6cdb-81cd-45fb-9fb3-07ce21537f91)
 
 - The highest salary is in the Medium companies = ~ 151K $
 - The lowest salary is in the Small companies = ~ 87K $

 ![med](https://github.com/user-attachments/assets/901853e6-2b79-494c-afc2-ea222a52c57f)

 - Analytics Engineering Manager earns the highest salary = 399 880 $
   
 ![dataman](https://github.com/user-attachments/assets/df3cd4ca-b34d-4abc-9ebe-1244c4e04056)

 - Salary difference between Entry and Executive experience level is over 100K $
   
 ![lvl](https://github.com/user-attachments/assets/7a924753-115c-4315-a71e-97aadfc8eb15)

 - From 2021 to 2024 average salary increased by 52K $
   
 ![line](https://github.com/user-attachments/assets/d314e655-5a54-464c-a2dc-fadb26523369)

### [2] Only Part-Time (filtered by employement type):

 - Data Architect is undoubtedly the best part-time choice:

 ![dataarch](https://github.com/user-attachments/assets/b7ac7b87-bddf-4388-874a-782bc16bdbd5)

 - On average, a part-time entry-level worker earns more than a more experienced one (mid level):

 ![da](https://github.com/user-attachments/assets/8f90a17c-3501-493d-9e63-15f5df809e19)





