📊✨ Social Media Usage Analysis
An end-to-end data project combining Python (Jupyter Notebook), Excel, and Power BI to uncover insights from global student social media usage patterns and their impact on academics and mental health.

📁 Project Structure
File	Description
countries of the world.csv	🌍 Raw country-wise geographical info
ss.csv	📌 Cleaned student survey data
SocialMediaAnalysis.ipynb	🐍 Python notebook for data cleaning & EDA
social_media.pbix	📈 Interactive Power BI dashboard

🌍 1️⃣ Raw Data
countries of the world.csv

Country, region, area, population — used for region-based enrichment.

ss.csv

705 survey responses about:

Daily usage hours

Most used platforms

Academic impact

Mental health score

Sleep hours

Conflicts due to social media

✅ Purpose: Provide a real scenario to analyze behavioral and academic trends.

📓 2️⃣ Python Analysis (SocialMediaAnalysis.ipynb)
✔️ What I Did:
✅ Loaded and merged data (pandas)

✅ Cleaned inconsistencies & missing values (numpy)

✅ Analyzed usage patterns by demographics

✅ Correlated usage with academic performance, sleep, and mental health (seaborn, matplotlib)

✅ Exported clean dataset for dashboarding

🔑 Key Findings:
Gender: ~50% Male & Female — balanced dataset.

Average Usage: ~5 hrs/day — about **30% higher than healthy recommendations.

Most Addictive Platforms: WhatsApp & Snapchat show highest average Addicted_Score (~7.4/10).

High Addiction: 28% students have Addicted_Score > 7.

Sleep: Highly addicted students sleep ~1.6 hrs less than others.

High: ~5.7 hrs/night vs. Low: ~7.3 hrs/night.

Mental Health: Heavy users have lower scores.

High addiction: 4.97/10, Low addiction: 6.71/10.

Conflicts: Strong positive correlation (0.93) between addiction and social conflicts.

📈 Correlation Highlights:

Relationship	Correlation
Addicted Score ↔️ Mental Health	-0.94 (strong negative)
Daily Usage ↔️ Sleep Hours	-0.79 (negative)
Daily Usage ↔️ Conflicts	0.80 (positive)

📊 3️⃣ Power BI Dashboard (social_media.pbix)
🎯 What I Built:
Dynamic Filters: Country, Gender, Platform.

Key KPIs: Average Usage, High vs. Low Addiction groups.

Impact Visuals: Charts showing how addiction affects:

📉 Academic scores

😴 Sleep

🧠 Mental health

🗣️ Social conflicts

🚀 Impactful Results:
KPI	Value	Insight
Avg Daily Usage	4.9 hrs	30% above recommended
High Addiction Rate	28%	~1 in 4 students highly addicted
Sleep Hours (High)	5.7 hrs	~1.6 hrs less than low addicted
Mental Health (High)	4.97/10	~25% lower than low addicted
Academic Impact	68%	Report decline in grades

✅ Conclusion: Higher social media usage strongly correlates with less sleep, lower mental well-being, more conflicts, and academic decline.
![social_media _page-0001](https://github.com/user-attachments/assets/656caae2-85cd-4112-b380-2d640b956b8b)


🛠️ Tools & Libraries Used
Tool	Purpose
🐍 Python	Core analysis & cleaning
📊 Pandas	Data manipulation
🔢 NumPy	Numerical operations
📈 Matplotlib & Seaborn	EDA & charts
📊 Excel	Initial data checks
📑 Jupyter Notebook	Interactive analysis
📊 Power BI	Interactive dashboard & KPIs

🚀 How to Use This Project
1️⃣ Open SocialMediaAnalysis.ipynb in Jupyter Notebook → Run cells for full EDA
2️⃣ Open social_media.pbix in Power BI Desktop → Explore dashboards
3️⃣ Connect to raw CSV files for reproducibility

📎 Author
Your Name Here
📧 sarthakchoubey2019@gmail.com
🔗 GitHub Profile: https://github.com/sarthak20244
