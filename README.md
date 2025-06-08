#  📊 Bellabeat Fitness Tracker Data Analysis with R

Welcome to my data analysis case study based on the Bellabeat Smart Device Dataset from Kaggle. This project follows the Google Data Analytics Capstone structure (Ask, Prepare, Process, Analyze, Share, Act) to explore user behavior and trends using Fitbit data. The ultimate goal is to derive marketing insights for Bellabeat, a wellness technology company focused on women’s health.


![Image](https://github.com/user-attachments/assets/228bac97-9445-49d5-930a-d990965a01ff)

🔗 View the full project on Kaggle: https://www.kaggle.com/code/mohammedabdulmuqtadi/bellabeat-fitbit

## 🧠 Business Task
Bellabeat aims to leverage insights from smart device usage to inform its marketing strategy. As a junior data analyst on the marketing team, I was tasked with analyzing Fitbit data to identify user activity trends and provide data-driven recommendations that could benefit one of Bellabeat's products, such as the Leaf, Time, or Spring.


## 📁 Data Source
Fitbit Fitness Tracker Data (CC0: Public Domain): Daily metrics from 30 users over 31 days, including steps, distance, calories, activity minutes, and sedentary behavior.

Dataset on Kaggle: https://www.kaggle.com/datasets/arashnic/fitbit

## 🔧 Tools Used
R Programming Language

tidyverse, lubridate, ggplot2, cluster


## 🧹 Data Preparation

![image](https://github.com/user-attachments/assets/6567c333-2b0a-4f2c-abf7-42232ab20b76)


Converted date format using lubridate::mdy()

Created a Ymd column for daily aggregation

Handled missing values using na.rm = TRUE

Scaled variables for clustering

## 📊 Exploratory Data Analysis
✅ Daily Activity Count
Bar chart showing several activity records per day to assess data availability and user engagement.

👣 Total and Average Daily Steps
Total Steps by Day: Line graph showing physical activity trends.

Average Steps: Revealed consistent drop-offs on weekends, useful for scheduling wellness reminders.

🛣️ Total and Average Distance
Analyzed the physical distance covered per day.

Helped estimate caloric expenditure and movement habits.

🔥 Calories vs Activity
Calories vs Steps and Calories vs Distance using scatter plots and linear regression.

A positive correlation was observed, supporting the idea that more activity leads to higher calorie burn.

## 🔍 Clustering Analysis
Performed K-Means Clustering on scaled features:

TotalSteps, VeryActiveMinutes, SedentaryMinutes, Calories

🔹 Cluster Visualization: Grouped users into 3 distinct behavior profiles:

![image](https://github.com/user-attachments/assets/fd649c99-adab-4846-bedc-892ef5af8cc4)


High Activity & Calories

Moderate Activity

Sedentary Users

This segmentation can guide personalized marketing strategies for Bellabeat products.

## 📈 Key Insights
Users show varying engagement levels; weekends typically show decreased activity.

Strong linear relationship between effort (steps/distance) and calories burned.

User behavior can be segmented into clear clusters — ideal for targeted messaging and feature customization.

## 📢 Marketing Recommendations
Based on the insights:

Personalized Plans: Tailor Bellabeat app features based on user cluster behavior.

Weekend Motivation Campaigns: Encourage movement during weekends with app challenges or reminders.

Data-Driven Feature Design: Use clustering to suggest health goals, hydration alerts, and mindfulness activities.

## 🏁 Conclusion
This case study helped me apply real-world data skills using R and demonstrate how data storytelling can drive smarter decisions in wellness technology. Thank you for exploring!

## 📌 Repository Highlights
📂 Cleaned and processed dataset

📈 Insightful visualizations

### 📎 Ready-to-use portfolio project for aspiring data analysts

Feel free to clone, fork, or reach out with any suggestions or feedback!
