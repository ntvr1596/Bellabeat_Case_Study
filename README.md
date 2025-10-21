# Bellabeat Capstone Case Study

![Bellabeat Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2e/Bellabeat_logo.svg/2560px-Bellabeat_logo.svg.png)

**Author:** Thirumala Nuthanapati  
**Language:** R | **Tools:** tidyverse, ggpubr, lubridate, janitor, skimr, ggrepel, here  
**Dataset:** [FitBit Fitness Tracker Data (Kaggle)](https://www.kaggle.com/code/thirumalanuthanapati/thirumala-capstone-case-study)  

---

## Project Overview

Bellabeat is a wellness technology company that creates health-focused smart devices. The goal of this project is to analyze smart device usage data to identify actionable insights and provide recommendations to improve **user engagement, product adoption, and marketing strategies**.

**Business Objective:**  
Identify patterns in the use of non-Bellabeat smart devices and suggest strategies for Bellabeat’s target audience, empowering women with personalized health insights.

**Key Stakeholders:**  
- Urška Sršen – Co-founder & Chief Creative Officer  
- Sando Mur – Co-founder & Mathematician  
- Bellabeat Marketing, Product Development, and Customer Service Teams  

---

## Data

**Source:** Kaggle – FitBit Fitness Tracker Data (via Mobius)  
**Timeframe:** 12th April – 12th May 2016  
**Format:** 18 CSV files containing activity, sleep, steps, calories, and heart rate data  

**Primary datasets analyzed:**  

| Dataset | Description |
|---------|-------------|
| `dailyActivity_merged` | Daily activity data: steps, distance, calories, intensity (33 users, 31 days) |
| `sleepDay_merged` | Daily sleep data (24 users, 31 days) |
| `hourlySteps_merged` | Hourly steps (33 users, 31 days) |

**Data Considerations:**  
- Small sample size (30–33 users) and potential sampling bias  
- Datasets cleaned to remove duplicates and standardize formats  

---

## Methodology

### 1. Data Cleaning & Preparation
- Removed duplicates and missing values  
- Standardized column names and formats across datasets  
- Converted date and time columns to proper formats  
- Merged daily activity and sleep datasets  

### 2. Analysis
- Classified users by activity levels: Sedentary, Lightly Active, Fairly Active, Very Active  
- Calculated daily averages: steps, calories, sleep  
- Explored hourly activity trends and correlation patterns  
- Categorized users by smart device usage: High, Moderate, Low  

### 3. Visualization
- Pie charts for user activity levels and device usage  
- Bar charts for daily and hourly activity  
- Scatter plots to identify correlations  
- Multi-faceted plots for usage analysis across user categories  

---

## Key Findings

- **Activity Patterns:** Most users meet daily step goals except Sundays; sleep duration below recommended 8 hours  
- **Correlation:** Positive correlation between steps and calories; no strong correlation between steps and sleep  
- **Device Usage:**  
  - High-frequency users: 50% (21–31 days)  
  - Moderate-frequency users: 12%  
  - Low-frequency users: 38%  
- **Time Worn:** High users rarely wear devices all day; moderate and low users wear devices mostly more than half a day  

---

## Recommendations for Bellabeat

1. **Daily Step Notifications & Encouragement**  
   - Personalized step reminders  
   - AI-powered goal recommendations  
   - Social challenges for engagement  

2. **Sleep Notifications & Support**  
   - Bedtime reminders, guided meditations, sleep-stage analysis  

3. **Gamification & Rewards**  
   - Points, badges, or NFT rewards for achieving milestones  

4. **Increase Device Usage**  
   - Promote features like water resistance, battery life, and stylish design  
   - Automated reminders and health-based insights  

5. **Personalized Data Insights**  
   - Predictive analytics for individual health recommendations  
   - Focus on target demographic (young/adult women)  

**Impact:** By leveraging these insights, Bellabeat can empower women, increase engagement, and enhance marketing strategies using data-driven recommendations.  

---
## How to Run
1. Place all datasets in the `data/` folder.  
2. Open the R notebook (`.ipynb`) in RStudio or Kaggle.  
3. Run all cells to reproduce the analysis and visualizations. 

---
 ## Author
Thirumala Venkat Raman Nuthanapati

---



