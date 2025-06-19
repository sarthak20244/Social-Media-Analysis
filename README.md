Social Media Usage Analysis
Description
This project demonstrates a complete data analysis workflow using global student survey data on social media usage. It covers the end-to-end process of data ingestion, cleaning, analysis, and visualization using Python (pandas, NumPy, seaborn, matplotlib), Excel, and Power BI.

Project Goals
The goal of this project is to gain practical experience with key tools in the modern data analysis stack by building an insightful analysis pipeline. The analysis explores how social media usage affects student academic performance, sleep, mental health, and social conflicts.

Tech Stack
Tool	Purpose
Python (pandas, NumPy)	Data cleaning, transformation, and exploratory data analysis
Matplotlib, Seaborn	Data visualization and statistical plots
Excel	Initial data inspection and quick checks
Power BI	Interactive dashboards and KPI reporting
Jupyter Notebook	Reproducible, step-by-step analysis

Project Architecture
Workflow:
Raw survey data → Python for cleaning and EDA → Clean dataset → Power BI for dashboarding and business insights.

Setup and Getting Started
To run this project locally:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/sarthak20244/Social-Media-Analysis.git
cd Social-Media-Analysis
Open the Jupyter Notebook:
Run all cells in SocialMediaAnalysis.ipynb to perform data cleaning and exploratory data analysis.

Open the Power BI dashboard:
Open social_media.pbix in Power BI Desktop to view the interactive reports and insights.

Project Structure
File	Description
countries of the world.csv	Raw country-wise geographical data
ss.csv	Cleaned student survey responses
SocialMediaAnalysis.ipynb	Python notebook for data cleaning and EDA
social_media.pbix	Power BI dashboard

Data Ingestion, Cleaning, and Exploration
Raw Data:

countries of the world.csv
Contains country, region, area, and population data for regional enrichment.

ss.csv
Includes 705 survey responses covering daily usage hours, most used platforms, academic impact, mental health scores, sleep hours, and conflicts.

Notebook Highlights:

Load and merge datasets using pandas

Handle missing values and correct inconsistencies using NumPy

Analyze usage patterns by demographic segments

Correlate social media usage with academic performance, sleep, and mental health using seaborn and matplotlib

Export the cleaned dataset for dashboarding in Power BI

Key Findings
Metric	Insight
Gender	Balanced dataset with approximately 50% male and 50% female respondents
Average Daily Usage	Approximately 5 hours per day, about 30% higher than healthy recommendations
Most Addictive Platforms	WhatsApp and Snapchat show the highest average addiction scores (~7.4/10)
High Addiction Rate	28% of students have an addiction score greater than 7
Sleep Patterns	Highly addicted students sleep about 1.6 hours less than others
Mental Health	Students with high usage have lower mental health scores (4.97 vs. 6.71)
Social Conflicts	Strong positive correlation (0.93) between addiction and conflicts

Power BI Dashboard and Insights
The Power BI dashboard provides interactive visualizations and key performance indicators, including:

Filters for country, gender, and platform

KPIs highlighting high addiction rates, academic impact, and reduced sleep

Charts that illustrate the relationship between social media usage and its effects on academics, sleep, mental health, and social conflicts

KPI	Value	Insight
Average Daily Usage	4.9 hours	About 30% higher than recommended levels
High Addiction Rate	28%	Approximately 1 in 4 students are highly addicted
Average Sleep (High Addiction)	5.7 hours	About 1.6 hours less than less-addicted students
Average Mental Health Score (High Addiction)	4.97/10	Approximately 25% lower than for less-addicted students
Academic Impact	68%	Reported a decline in academic grades

How to Use This Project
Open SocialMediaAnalysis.ipynb in Jupyter Notebook and run all cells to replicate the data analysis.

Open social_media.pbix in Power BI Desktop to interact with the dashboard.

Connect to the provided CSV files if prompted for data sources.

Author
Sarthak Choubey
Email: sarthakchoubey2019@gmail.com
GitHub: https://github.com/sarthak20244

License
This project is for educational purposes only.
