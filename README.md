# 8093Data-Visualization-Project

Presentation video link: https://youtu.be/kAzmYtwpmMc

# User Behavior Clustering in Ele.me Online Food Delivery
# Project Overview
This project analyzes user profiles in the online food delivery service Ele.me, with a focus on their recommendation system. By clustering 1.8 million user behavior records, the project visualizes key insights through interactive visualizations such as bubble charts, heatmaps, and parallel set graphs.
# Introduction
This project shifts the focus from traditional Click-Through Rate (CTR) analysis to the online food delivery industry, analyzing user behavior and traits within Ele.me’s recommendation system. By employing the K-Means algorithm, users are clustered based on traits like gender, VIP status, spending levels, and purchase frequency.
# Dataset
The dataset is a subset from Ele.me, including:
User Traits: Gender, VIP status, historical average price, sum of price over the last 30 days.
User Behavior: CTR indicators, activities (CTR and orders transacted) for the last 30 days.
Methods
Data Cleaning: Initial steps included removing noise and standardizing behavior features.
Clustering: K-Means algorithm was applied, optimized using the elbow method, dividing users into five groups.
Visualization: Built interactive visualizations with Plotly, and created an interactive dashboard using Dash.
# Results
Group Analysis: Bar and bubble charts compare CTR and order transactions of each group.
User Traits Analysis: Parallel set diagrams highlight relationships between user traits such as gender, VIP status, and spending levels.
Distribution Analysis: Heatmaps reveal patterns and trends across user traits within each group.
Visualizations
Bubble and Bar Charts: Compare user behavior across groups.
Parallel Set Diagrams: Show connections between multiple user traits.
Heatmaps: Visualize distribution and proportions across user traits.
# References
MulUBA: multi-level visual analytics of user behaviors for improving online shopping advertising
Additional references listed in the project report.
