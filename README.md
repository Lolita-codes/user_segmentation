# User Segmentation
Analysis of user data for targeted ad campaigns and maketing.

## Project Objective
This project aims to segment users based on demographic and behavioral features to optimize ad targeting strategies and increase engagement and conversions.

## Methods Used
The analysis encompasses the following methods:  
o Preliminary Data Exploration  
o Descriptive Statistics  
o Data Cleaning  
o Data Visualization  
o Clustering

## Technologies Utilized
o Python  
o Pandas  
o NumPy  
o Seaborn  
o Matplotlib  
o Plotly  
o Scikit-Learn

## Project Description
The dataset consists of user profile information with features such as:  
o Demographics: Age, Gender, Location, Language, Education Level, Income Level.  
o Engagement Metrics: Likes and Reactions, Followed Accounts, Device Usage.  
o Online Behavior: Time Spent Online (weekday and weekend), Click-Through Rates (CTR), Conversion Rates, Ad Interaction Time.  
o Interests: Top Interests, a list of primary interests for each use.  

## Key Findings
● Age, Gender, Location, Language, Education Level, Device Usage and Income Level distributions were visualized using count plots to understand the demographic structure of the dataset.  
● Exploring metrics such as Time Spent Online (Weekdays and Weekends), Likes and Reactions, Click-Through Rates (CTR), Conversion Rates, and Ad Interaction Time showed higher engagement on weekends, suggesting prime times for ad campaigns. CTR, Ad interaction and Conversion Rates were examined to identify user responsiveness to ads.  
● Visualized the top 20 interests, giving insight into user preferences and enabling topic-based ad targeting.  
● Successfully segmented the user base into five distinct profiles:  

□ Cluster 0 - "Moderate Weekday Users":  
- Moderate time spent online during both weekdays (3.91 hours) and weekends (5.21 hours)
- Lower engagement in likes and reactions (2409) with a moderate click-through rate (0.15)
- Primarily female, age 25-34, with income in the 80k-100k range

□ Cluster 1 - "Engaged Weekend Warriors":  
- Low online time during weekdays (1.56 hours) but high on weekends (6.0 hours)  
- High engagement level in likes (5005) and the highest click-through rate (0.18)  
- Primarily male, age 35-44, income level 80k-100k
  
□ Cluster 2 - "Frequent Daily Users":  
- Balanced online time on both weekdays (3.02 hours) and weekends (2.58 hours)  
- High engagement (6862 likes) and a strong click-through rate (0.17)  
- Primarily male, age 25-34, with a lower income bracket (20k-40k)

□ Cluster 3 - "High-Income Viewers":  
- Moderate online time during both weekdays (3.08 hours) and weekends (5.77 hours)  
- High engagement (7458 likes) but a lower click-through rate (0.068)  
- Primarily female, age 25-34, with the highest income bracket (100k+)  

□ Cluster 4 - "Low-Engagement Users":  
- Lower time spent online during both weekdays (1.81 hours) and weekends (3.84 hours)  
- Low engagement (3021 likes) and the lowest click-through rate (0.057)  
- Primarily female, age 45-54, with a low-income level (0-20k)  

● A Radar Chart was used to visualize each cluster’s profile based on Time Spent Online (Weekdays and Weekends), Likes and Reactions, and CTR.  


Data credit: https://statso.io/user-profiling-case-study/

