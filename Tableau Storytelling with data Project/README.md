## Project Title (Tableau)

### 📌 Overview
Identify the cause of the high number of returned orders at the Superstore. Prepare an analysis for the CEO of the Superstore to help them understand what is causing customers to return their orders and how to reduce the volume of returned orders.

### 🛠 Tools & Skills
- Tableau
- Visualization, dashboards, Story.

### 📊 Dataset
- Source: [Sample Superstore Dataset (Tableau)](https://practicum-content.s3.us-west-1.amazonaws.com/data-eng/remodeled/files/Superstore.xls?etag=4616d537c163874941cf5fc3c9002fa8)
- Size: (9995 rows, 21 columns)  
- Notes: Returns LEFT JOIN’ed onto the `Orders` table.

### 🔍 Key Steps
1. Imported the dataset into Tableau
2. Making the Returned field into a calculated field  where NULL values are 0 and YES values are 1.
3. Built visualizations to analyze different views on return rates:
   - Returns by state (map)  
   - Top 25 more prone to return customers (bar chart)  
   - Monthly return rate trends (line chart)  
   - Returns/Sales vs Sub-category (scatter plot)
   - Returns by customer segments (Bar Chart)
5. Combined visuals into a single interactive dashboard.

### 💡 Insights
- UT, CA, and OR were found to be the states with the highest return rates (56.8%, 45.20% and 44.7% respectively).
- CA represents the highest amount of sales $671,595.00, suggesting that efforts should be put there.
- Returns the highest peaks in August with a 38.6% return rate.  
- Concluded that a combination of Std Class ship mode, consumer customer's segment, and some categories (table, paper, phones, and machines) are the root causes of the high volume of returns.  

### 📂 Project Files
- `/data` → [Superstore.xls](https://practicum-content.s3.us-west-1.amazonaws.com/data-eng/remodeled/files/Superstore.xls?etag=4616d537c163874941cf5fc3c9002fa8)


  

  ## 🖼️ Screenshots

  Dashboard Overview:

  ![Dashboard Overview](https://github.com/DiegoJCarballoG/TripleTen_projects/blob/main/Tableau%20Storytelling%20with%20data%20Project/screenshots/Dashboard%20returns%20causes.png?raw=true)

  Returns by state:  
  ![Returns by state](https://github.com/DiegoJCarballoG/TripleTen_projects/blob/main/Tableau%20Storytelling%20with%20data%20Project/screenshots/Returns%20by%20state.png?raw=true)

  

### 🔗 Links
- [View Tableau Dashboard](https://public.tableau.com/app/profile/diego.carballo/viz/StorytellingwithDataProject_17525532384360/Returnscauses)  
- [View Project Repo](https://github.com/DiegoJCarballoG/TripleTen_projects.git) 



