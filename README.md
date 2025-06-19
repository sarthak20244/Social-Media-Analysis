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

## 📊 Workflow

Raw Survey Data  
⬇  
Python (Cleaning & Exploratory Data Analysis)  
⬇  
Clean Dataset  
⬇  
Power BI Dashboards (Interactive Insights)


## Setup and Getting Started

To run this project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/sarthak20244/Social-Media-Analysis.git
cd Social-Media-Analysis
```
## Run the Jupyter Notebook

Open `SocialMediaAnalysis.ipynb` and run all cells to perform data cleaning and exploratory data analysis.

## Open the Power BI Dashboard

Open `social_media.pbix` in Power BI Desktop to explore the interactive dashboard and KPIs.

## Project Structure

| File | Description |
|------|--------------|
| `countries of the world.csv` | Raw country-wise geographical information |
| `ss.csv` | Cleaned student survey responses |
| `SocialMediaAnalysis.ipynb` | Python notebook for data cleaning and exploratory analysis |
| `social_media.pbix` | Power BI dashboard for interactive visualization |

## Data Ingestion, Cleaning, and Exploration

### Raw Data

- **countries of the world.csv**: Includes country, region, area, and population information for regional enrichment.
- **ss.csv**: Contains 705 survey responses covering:
  - Daily usage hours
  - Most used platforms
  - Perceived academic impact
  - Mental health score
  - Sleep hours
  - Conflicts due to social media

### Python Notebook Highlights

- Load and merge datasets with **pandas**
- Handle missing values and inconsistencies with **NumPy**
- Analyze usage patterns across demographic groups
- Correlate social media usage with academics, sleep, and mental health using **Seaborn** and **Matplotlib**
- Export the cleaned dataset for visualization in Power BI

## Key Findings

| Metric | Insight |
|--------|---------|
| **Gender** | Balanced dataset with approximately 50% male and 50% female respondents |
| **Average Daily Usage** | Approximately 5 hours per day, about 30% higher than healthy recommendations |
| **Most Addictive Platforms** | WhatsApp and Snapchat have the highest average addiction scores (~7.4/10) |
| **High Addiction Rate** | 28% of students have an addiction score above 7 |
| **Sleep Patterns** | Highly addicted students sleep about 1.6 hours less than others |
| **Mental Health** | High usage correlates with lower mental health scores (4.97 vs. 6.71) |
| **Social Conflicts** | Strong positive correlation (0.93) between high usage and conflicts |

## Power BI Dashboard

The Power BI dashboard provides:

- Filters for country, gender, and platform
- KPIs for social media addiction rate, academic impact, and sleep duration
- Visualizations highlighting how social media usage affects academic performance, sleep, mental health, and conflicts

### KPI Summary

| KPI | Value | Insight |
|-----|-------|---------|
| **Average Daily Usage** | 4.9 hours | About 30% higher than recommended levels |
| **High Addiction Rate** | 28% | About 1 in 4 students are highly addicted |
| **Average Sleep (High Addiction)** | 5.7 hours | About 1.6 hours less than low-addiction students |
| **Mental Health (High Addiction)** | 4.97/10 | Approximately 25% lower than low-addiction students |
| **Academic Impact** | 68% | Reported a decline in academic performance |

## How to Use

1. Open `SocialMediaAnalysis.ipynb` in Jupyter Notebook and run all cells to replicate the full analysis.
2. Open `social_media.pbix` in Power BI Desktop to explore the interactive dashboard.
3. Connect to the provided CSV files if prompted for data sources in Power BI.

## Author

**Name:** Sarthak Choubey  
**Email:** sarthakchoubey2019@gmail.com  
**GitHub:** [sarthak20244](https://github.com/sarthak20244)

## License

This project is for educational purposes only.

# 📊 Dashboards & Insights

## Dashboard Overview

Here’s the main dashboard layout that brings together all key insights:
![social_media _page-0001](https://github.com/user-attachments/assets/270b7a3a-05f3-4aba-b532-edee6047a66b)

## Below are the key visualizations and insights created in Power BI.

## 1. Social Media Addiction by Age
- Question: Which age groups are most affected by social media addiction?
  ![Capture](https://github.com/user-attachments/assets/3b5ef37a-2ac1-4bb1-89cf-c6e0d3ed37cf)

- Insight:
  
           1.Age 20 (23.89%) and 24 (23.56%) top the chart, making up nearly half (47.45%) of all cases.
 
           2.Age 21 follows closely with 22.65%, indicating that early 20s are the most vulnerable group.

## 2. Mental Health Score vs Risk
- Question: How does mental health score correlate with addiction, academic, and sleep risks?
  ![Capture1](https://github.com/user-attachments/assets/3e259c75-739e-41b8-9640-abf6a7a6bb0f)

- Insight:

           1.Risk levels peak at a mental health score of 6, suggesting moderate mental health is associated with the highest vulnerability.

           2.As scores increase beyond 6, risk sharply drops — indicating better mental health correlates with reduced risk.

## 3. Academics and Sleep Affected (by Gender)
- Question: How do gender and addiction impact academic performance and sleep?
  ![Capture2](https://github.com/user-attachments/assets/9fe60533-280e-4fe0-9934-493765fc53d0)

- Insight:

            1.Both academic performance and sleep are significantly affected, with males showing higher levels of impact than females.

            2.More males suffer academically and experience sleep disruption, pointing to gender-specific susceptibility.

## 4. Addiction Summary Metrics
- Question: What is the overall impact of social media addiction?
  ![Capture3](https://github.com/user-attachments/assets/aa8909d5-6ec0-4866-91a3-11f4101a8f31)

- Insight:

            1.4538 individuals are addicted.

            2.453 have their academics hampered.

            3.Sleep for this group is also noted as "Affected", indicating widespread health impacts.

## 5. Risk Level Distribution
- Question: How are users distributed across risk categories?
  ![Capture4](https://github.com/user-attachments/assets/ac674838-428e-4c9c-8209-d68dce3f83ca)

- Insight:

            1.66.23% (9K) fall under High Risk.

            2.25.64% (3K) are at Low Risk.

            3.Only 8.12% (1K) are at Medium Risk, showing the majority are at critical risk levels.

## 6. Addiction According to Social Media Platform
- Question: Which platforms are most associated with addiction?
  ![Capture5](https://github.com/user-attachments/assets/164e65e4-df9f-4712-b1e7-047dcd577ad1)

- Insight:

            1.Instagram and TikTok lead with the highest addiction scores.

            2.Facebook and WhatsApp follow, while platforms like LINE, Vkontakte, KakaoTalk show minimal impact.

            3.Indicates addiction is concentrated around a few dominant platforms.

