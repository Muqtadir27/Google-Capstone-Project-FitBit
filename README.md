#  📊 Bellabeat Fitness Tracker Data Analysis with R

Bellabeat-Fitbit Data Analysis is a portfolio project based on the Google Data Analytics Capstone. It explores how smart device usage data can provide actionable insights for Bellabeat, a women-focused wellness technology company. Using Fitbit data, this analysis identifies user behavior patterns and proposes marketing strategies based on data-driven insights.

![Image](https://github.com/user-attachments/assets/228bac97-9445-49d5-930a-d990965a01ff)

```
🔗 View the full project on Kaggle: https://www.kaggle.com/code/mohammedabdulmuqtadi/bellabeat-fitbit
```

## 🌟 Features

📅 Daily Engagement Trends — Tracks activity frequency and consistency
👣 Step & Distance Analysis — Summarizes physical activity habits
🔥 Calories vs Effort Visualization — Understands energy expenditure patterns
🔍 Clustering — Groups users based on behavior using K-Means
📊 Data Visualizations — Clear plots using ggplot2


## 🛠️ Technology Stack
Language: R
### Libraries:
tidyverse – data wrangling
lubridate – date handling
ggplot2 – visualizations
cluster – K-Means clustering
Platform: Kaggle Notebooks


## 📂 Project Structure
```
bellabeat-fitbit.ipynb      # Main Kaggle R notebook
📊 Inline Visualizations     # ggplot2 graphs for trends, clusters, and correlations
📁 Dataset Source            # Fitbit public dataset on Kaggle (CSV files)
💡 Since this project was developed on Kaggle, it follows a notebook-centric structure. All analysis is done interactively in R within a single notebook.
```


## 🖥️ How to Run the Project
1. Visit the Kaggle Notebook
```
🔗 Kaggle Project Link: https://www.kaggle.com/code/mohammedabdulmuqtadi/bellabeat-fitbit

```
3. Click “Copy & Edit”
This will fork the notebook into your own Kaggle environment.
4. Run All Cells
Make sure all dependencies are available and the runtime is set to R.



## 📊 Key Analyses
✅ Date Conversion: Used lubridate::mdy() to create a clean daily date column (Ymd)
👣 Steps & Distance Trends: Summarized and visualized using group_by() and summarise()
🔥 Calories vs Activity: Used scatter plots + linear regression for calories vs steps/distance



## 🔍 K-Means Clustering: Clustered users into three groups:
High Activity & Calories
Moderate Activity
Sedentary Users



## 📈 Visualization Example:

![image](https://github.com/user-attachments/assets/fd649c99-adab-4846-bedc-892ef5af8cc4)

## 📢 Insights & Recommendations
🔍 Insights:
Engagement levels drop on weekends
Higher steps and distance correlate strongly with calorie burn
Users show distinct activity behavior profiles (clustered)
## 📈 Recommendations:
🎯 Personalized Plans: Adapt Bellabeat features per cluster type
📆 Weekend Challenges: Boost activity during low-engagement days
💧 Smart Suggestions: Recommend hydration, mindfulness, or rest based on patterns


## 🏁 Conclusion
This case study demonstrates the power of data storytelling using R. It not only showcases user behavior patterns from wearable data, but also offers actionable recommendations that Bellabeat can apply to enhance its product engagement and marketing strategy.


## 🤝 Contributing
While this was a solo case study project, feedback and improvements are always welcome!

To contribute:
```
bash
1. Fork the repository (Kaggle Notebook)
2. Add your own enhancements or visualizations
3. Share via Kaggle public sharing or PR on GitHub (if applicable)

```

## 📜 License
This project uses data released under CC0: Public Domain.
All analysis and visualizations by Mohammed Abdul Muqtadir. Feel free to reuse with credit.

## 📧 Contact
Mohammed Abdul Muqtadir

🌐 GitHub: Muqtadir27

📫 Email: abdulmuqtadir1027@gmail.com

## ❤️ Acknowledgments
Dataset: Fitbit Dataset – Kaggle by Mobius

Framework: Google Data Analytics Capstone – Coursera

Tools: R, tidyverse, ggplot2, cluster
