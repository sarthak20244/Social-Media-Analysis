# Social Media Usage Analysis

## Description

This project demonstrates a complete data analysis workflow using global student survey data on social media usage. It covers the end-to-end process of data ingestion, cleaning, exploratory analysis, and interactive visualization using Python, Excel, and Power BI.

## Project Goals

The objective of this project is to gain practical experience with a modern data analysis stack and uncover insights about how social media usage impacts students' academic performance, sleep patterns, mental health, and social behavior.

## Tech Stack

| Tool | Purpose |
|------|---------|
| **Python (pandas, NumPy)** | Data cleaning, transformation, and exploratory data analysis |
| **Matplotlib, Seaborn** | Statistical visualizations and plots |
| **Excel** | Initial data inspection and validation |
| **Power BI** | Interactive dashboards and KPI reporting |
| **Jupyter Notebook** | Reproducible step-by-step analysis |

## Project Architecture

**Workflow:**  
Raw survey data → Python (cleaning & EDA) → Clean dataset → Power BI dashboards for interactive insights.

## Setup and Getting Started

To run this project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/sarthak20244/Social-Media-Analysis.git
cd Social-Media-Analysis


Run the Jupyter Notebook:
Open SocialMediaAnalysis.ipynb and run all cells to perform data cleaning and exploratory data analysis.

Open the Power BI dashboard:
Open social_media.pbix in Power BI Desktop to explore the interactive dashboard and KPIs.

Project Structure
File	Description
countries of the world.csv	Raw country-wise geographical information
ss.csv	Cleaned student survey responses
SocialMediaAnalysis.ipynb	Python notebook for data cleaning and exploratory analysis
social_media.pbix	Power BI dashboard for interactive visualization

Data Ingestion, Cleaning, and Exploration
Raw Data:

countries of the world.csv:
Includes country, region, area, and population information for regional enrichment.

ss.csv:
Contains 705 survey responses covering daily usage hours, most used platforms, perceived academic impact, mental health score, sleep hours, and conflicts due to social media.

Python Notebook Highlights:

Load and merge datasets with pandas

Handle missing values and inconsistencies with numpy

Analyze usage patterns across demographic groups

Correlate social media usage with academics, sleep, and mental health using seaborn and matplotlib

Export the cleaned dataset for visualization in Power BI

Key Findings
Metric	Insight
Gender	Balanced dataset with approximately 50% male and 50% female respondents
Average Daily Usage	Approximately 5 hours per day, about 30% higher than healthy recommendations
Most Addictive Platforms	WhatsApp and Snapchat have the highest average addiction scores (~7.4/10)
High Addiction Rate	28% of students have an addiction score above 7
Sleep Patterns	Highly addicted students sleep about 1.6 hours less than others
Mental Health	High usage correlates with lower mental health scores (4.97 vs. 6.71)
Social Conflicts	Strong positive correlation (0.93) between high usage and conflicts

Power BI Dashboard
The Power BI dashboard provides:

Filters for country, gender, and platform

KPIs for social media addiction rate, academic impact, and sleep duration

Visualizations highlighting how social media usage affects academic performance, sleep, mental health, and conflicts

KPI	Value	Insight
Average Daily Usage	4.9 hours	About 30% higher than recommended levels
High Addiction Rate	28%	About 1 in 4 students are highly addicted
Average Sleep (High Addiction)	5.7 hours	About 1.6 hours less than low-addiction students
Mental Health (High Addiction)	4.97/10	Approximately 25% lower than low-addiction students
Academic Impact	68%	Reported a decline in academic performance

How to Use
Open SocialMediaAnalysis.ipynb in Jupyter Notebook and run all cells to replicate the full analysis.

Open social_media.pbix in Power BI Desktop to explore the interactive dashboard.

Connect to the provided CSV files if prompted for data sources in Power BI.

Author
Sarthak Choubey
Email: sarthakchoubey2019@gmail.com
GitHub: https://github.com/sarthak20244

License
This project is for educational purposes only.
