# bellabeat-smart-device-usage-analysis
Data cleaning, SQL analysis, and Tableau visualization of Bellabeat smart device usage to guide marketing strategy.
📄 Bellabeat Smart Device Usage Analysis (SQL + Tableau)
📈 Project Overview
Analyzed smart device usage data to uncover user trends and provide marketing strategy recommendations for Bellabeat, a women's health-focused tech company.

🛠 Tools Used
-BigQuery SQL (Data Cleaning, Joining, Querying)

-Tableau Public (Data Visualization)

-Kaggle (Source Dataset: Fitbit Fitness Tracker Data)

-Wisconsin Health Services Dataset (Calories Burned)

🚀 Project Workflow
1. Data Preparation
-Uploaded Fitbit activity, sleep, and calories data into BigQuery.

-Added an external dataset (Calories Burned Per Hour by Activity) for enhanced analysis.

2. Data Cleaning:
-Verified and standardized data types across tables.

-Handled NULL values dynamically across tables.

-Removed duplicates to ensure data quality.

-Standardized and normalized column names.

-Added derived metrics (e.g., total_hours_asleep, weekday).

3. Data Integration:
Created a final cleaned table (bellabeatfitbit_cleaned) joining activity, calories, and steps data.

4. Visualization:
Built a Tableau dashboard showing:

-Activity levels

-Sleep patterns

-Calories burned

-Steps vs sleep comparisons

📊 Key Insights:
Users who had consistent moderate activity had better sleep quality.

Most users had relatively low active minutes despite decent step counts.

Bellabeat could focus marketing on promoting consistent low-to-moderate daily movement for better sleep and wellness.

🎯 Business Recommendations: 
Promote daily movement challenges through Bellabeat app gamification.

Develop marketing content focusing on the connection between movement, calories burned, and improved sleep.

Target ads around habit-building rather than only weight loss or fitness.

🔗 Links
View Tableau Dashboard ([Insert Tableau Public Link Here](https://public.tableau.com/views/BellaBeatFitbitDataAnalysis/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))


📚 Learnings
Real-world SQL data cleaning and transformation at scale.

Using external datasets to improve project depth.

Combining SQL analysis with visualization storytelling.

Business-oriented recommendation building based on data insights.

