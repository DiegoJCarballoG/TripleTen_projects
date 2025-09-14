## Project Title (Tableau)

### 📌 Overview
Identify what is causing the high number of returned orders at the Superstore. Prepare an analysis for the CEO of the Superstore to help them understand what is causing customers to return their orders and how to reduce the volume of returned orders.

### 🛠 Tools & Skills
- Tableau
- Visualization, dashboards, Story.

### 📊 Dataset
- Source: https://practicum-content.s3.us-west-1.amazonaws.com/data-eng/remodeled/files/Superstore.xls?etag=4616d537c163874941cf5fc3c9002fa8
- Size: (#9995 rows, 21 columns)  
- Notes: Returns LEFT JOIN’ed onto the `Orders` table.

### 🔍 Key Steps
1. Making the Returned field into a calculated field  where NULL values are 0 and YES values are 1.
2. Building worksheets analyzing different views on return rates: scatterplot, bar chart, map, line chart, composite charts.
4. Built a dashboard showing the analysis' findings.

### 💡 Insights
- Ut, CA and OR were found to be the states with the highest return rates (56.8%, 45.20% and 44.7% respectively).
- CA represents the highest amount of sales $671,595.00, suggested to concentrate efforts there.
- Returns highest peak's on August with a 38.6% return rate.  
- Concluded that a combination of Std Class ship mode, consumer customer's segment and some categories (table, paper, phones and machines) are the root causes of the high volume of returns.  

### 📂 Project Files
- `/data` → [Superstore.xls](https://practicum-content.s3.us-west-1.amazonaws.com/data-eng/remodeled/files/Superstore.xls?etag=4616d537c163874941cf5fc3c9002fa8)

- `/notebooks` or `/scripts` → SQL queries, code, or Sheets formulas  

- `/screenshots` → dashboard images  ![image-20250912170043822](C:\Users\diego\AppData\Roaming\Typora\typora-user-images\image-20250912170043822.png)

  ![image-20250912170122731](C:\Users\diego\AppData\Roaming\Typora\typora-user-images\image-20250912170122731.png)

  ![image-20250912170200236](C:\Users\diego\AppData\Roaming\Typora\typora-user-images\image-20250912170200236.png)

  ![image-20250912170218836](C:\Users\diego\AppData\Roaming\Typora\typora-user-images\image-20250912170218836.png)

  ![image-20250912170239603](C:\Users\diego\AppData\Roaming\Typora\typora-user-images\image-20250912170239603.png)

  ![image-20250912170254465](C:\Users\diego\AppData\Roaming\Typora\typora-user-images\image-20250912170254465.png)

  ![image-20250912170317332](C:\Users\diego\AppData\Roaming\Typora\typora-user-images\image-20250912170317332.png)

  ![image-20250912170332337](C:\Users\diego\AppData\Roaming\Typora\typora-user-images\image-20250912170332337.png)

  ![image-20250912170345234](C:\Users\diego\AppData\Roaming\Typora\typora-user-images\image-20250912170345234.png)

  ![image-20250912170354536](C:\Users\diego\AppData\Roaming\Typora\typora-user-images\image-20250912170354536.png)

  

### 🔗 Links
- [View Tableau Dashboard](https://public.tableau.com/app/profile/diego.carballo/viz/StorytellingwithDataProject_17525532384360/Returnscauses)  
- [View Project Repo](https://github.com/DiegoJCarballoG/TripleTen_projects.git) 

