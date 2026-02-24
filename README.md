# 🎬 Netflix Content Strategy: Expansion and Production Trends (2015-2020)

## 📌 Project Overview
This project aims to analyze the global expansion for the Netflix catalog (2015 to 2020). The executive dashboard was built to provide clear insights into the platform's release pace, the balance between content formats (Movies vs. TV Shows) and the main international production hubs outside the United States.

## 🎲 Data Source
The data used in this project was obtained from a public dataset available on Kaggle. 
* **Dataset Link:** [Netflix Data](https://www.kaggle.com/datasets/rohitgrewal/netflix-data)

## 🎯 The Business Challenge
Imagine the Content Strategy team needs a quick overview to support the next round of investments. This dashboard was designed to answer 4 business questions:
1. **Pace and Global Impact:** What was the evolution of original production volume over years?
2. **Format Balance:** Is the catalog predominantly supported by movies, or do series already represent most of the content?
3. **International Expansion:** What are Netflix's largest production hubs outside the US market?
4. **Audience Focus:** Where is the highest volume of investment concentrated by genre?

## 🛠️ Tech Stack & Tools
* **Python:** Used for Exploratory Data Analysis (EDA). The initial data understanding and structural profiling were conducted using pandas and seaborn before modeling the data in the visualization tool.
* **Power BI:** Dashboard development, relational data modeling, and DataViz.
* **DAX Language:** Creation of calculated measures, time intelligence, and custom formatting.
* **Figma:** Layout grid prototyping and background design.

## 📈 Key Insights
* **The 2019 peak and 2020 drop:** The area chart reveals a continuous production escalation that reached its historical peak in 2019 (2,153 titles). In 2020, we see the first drop in the trend (2,009 titles), which can be a reflection of the global COVID-19 pandemic, that halted multiple movie and TV show productions.
* **Movie dominance:** Despite the growing number of TV shows, **Movies account for nearly 69%** of all content cataloged in the period, proving they are the baseline for catalog retention.
* **Asian and European hubs:** Excluding the US, **India** and the **United Kingdom** appear as the largest global producers, confirming the success of Netflix's content strategy for subscriber expansion.
* **International focus:** The "International Movies" genre leads the volume ranking by a wide margin (2.4K titles), validating the hypothesis of the insight above.

## ⚙️ Technical Assumptions and Design Decisions
To ensure the integrity of the analysis and the dashboard's usability, the following assumptions were made:
* **Timeframe scope (2015-2020):** The dataset was intentionally filtered using page-level filters, removing legacy data (movies from 1990 - 2019) that would generate visual noise.
* **UX and color psychology:** To maintain Netflix's visual identity without triggering negative cognitive biases associated with pure red in financial dashboards (indicating alerts/losses), a dark moderate red (`#A1343C`) was adopted. This ensured brand adherence and visual comfort in Dark Mode.
* **Country origin assumption:** While the original data dictionary states that the `Country` column indicates both the production or release locations, for the strategic scope of this project, I assumed this column strictly represents the **Country of origin/production**.

## ⚠️ Disclaimer
This is a personal portfolio project. Netflix and the Netflix logo are registered trademarks of Netflix. The logo used in this project is used strictly for educational and demonstration purposes.

## 🚀 How to view the project
* **[View the Colab Notebook here](https://colab.research.google.com/drive/1DM8Y8Objy6zPcs67i4fbR1aADyu20TD0?usp=sharing)**
* Download the `.pbix` file from this repository and open it in Power BI Desktop.
  * Preview:
    <img width="1531" height="860" alt="image" src="https://github.com/user-attachments/assets/9109df74-f58c-43a3-a0c8-e7849958bc13" />

  
