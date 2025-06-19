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
```
## Run the Jupyter Notebook

Open `SocialMediaAnalysis.ipynb` in Jupyter Notebook and run all cells to perform data cleaning and exploratory data analysis.

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
| **Gender** | Balanced dataset with ~50% male and ~50% female respondents |
| **Average Daily Usage** | Approximately 5 hours per day, about 30% higher than healthy recommendations |
| **Most Addictive Platforms** | WhatsApp and Snapchat have the highest average addiction scores (~7.4/10) |
| **High Addiction Rate** | 28% of students have an addiction score above 7 |
| **Sleep Patterns** | Highly addicted students sleep about 1.6 hours less than low-addicted students |
| **Mental Health** | High usage correlates with lower mental health scores (4.97 vs. 6.71) |
| **Academic Impact** | 68% report a decline in grades due to excessive social media use |

