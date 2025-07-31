# Bellabeat Case Study

This repository contains a data analysis project exploring user behavior using Fitbit data provided by Bellabeat, a high-tech wellness company that manufactures health-focused smart devices. The goal is to uncover actionable insights that can inform Bellabeat’s marketing strategy.

## 📊 Tools & Technologies
- **R** with **RStudio**
- **SQL** chunks embedded in **R Markdown**
- **tidyverse** for data manipulation and visualization
- **ggplot2** for plotting
- **lubridate**, **dplyr**, **readr**, and other tidy tools
- Git and GitHub for version control

## 📁 Project Structure
```
bellabeat-case-study/
├── Fitabase Data 3.12.16-4.11.16/       # Raw Fitbit CSV data
├── BellaBeat_Data_Analysis_Case_Study-2025-07-25.Rmd   # R Markdown notebook
├── BellaBeat_Data_Analysis_Case_Study-2025-07-25.html  # Rendered output
├── README.md                            # Project overview (you’re writing this now)
├── .gitignore                           # Ignored files list
└── bellabeat-case-study.Rproj           # RStudio project file

```

## 📌 Key Steps in the Analysis
1. **Data Import & Cleaning**  
   Cleaned and merged daily, hourly, and minute-level Fitbit data using SQL and R.

2. **Exploratory Data Analysis (EDA)**  
   Used correlation matrices, time-series trends, and step-to-calorie regressions.

3. **User Segmentation**  
   Segmented users by activity and engagement (low, moderate, high).

4. **Insights & Recommendations**  
   Identified patterns in sleep, activity, and calorie burn that Bellabeat can use for targeted marketing.

## ✅ How to Run
1. Clone this repo to your local machine:
   ```bash
   git clone https://github.com/mikkelaustin/bellabeat-case-study.git
   ```
2. Open the RStudio Project file: `bellabeat-case-study.Rproj`
3. Open the R Markdown notebook and run it chunk by chunk.
4. Install any missing R packages listed at the top of the notebook.

## 🧠 Insights Summary
- Active users burn significantly more calories, particularly with consistent step counts.
- Users with consistent sleep patterns also tend to have more active lifestyles.
- Engagement segments helped identify distinct user behavior for marketing focus.

## 📄 License
This project is licensed under the MIT License — see the `LICENSE` file for details.

## 🙌 Acknowledgments
Fitbit data provided by Bellabeat via the [Google Data Analytics Capstone](https://www.coursera.org/learn/google-data-analytics-capstone) project.
