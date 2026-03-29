# Netflix-Data-Analysis-Project
End-to-end data analysis on Netflix dataset using Python, Pandas, and Visualization.
Project Overview

This project performs end-to-end data analysis on the Netflix Movies and TV Shows dataset to extract meaningful insights about content distribution, growth trends, audience targeting, and production patterns. The analysis includes data cleaning, manipulation, and visualization using Python.

# Business Problem

The objective of this project is to analyze Netflix’s content catalog to answer key business questions such as:

How has Netflix content grown over time?
What type of content dominates the platform (Movies vs TV Shows)?
Which countries contribute the most content?
What audience segments are primarily targeted?
What are the most common genres available on Netflix?
Dataset
Dataset Name: Netflix Movies and TV Shows Dataset
Source: Kaggle
Contains information about titles, directors, cast, country, release year, rating, duration, and genres.
# Tools and Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
# Data Cleaning Steps
Handled missing values in columns such as director, cast, country, rating, and duration
Removed rows with missing date values
Converted the date_added column to datetime format
Extracted year_added from date_added
Removed duplicate records
Standardized text values
# Data Manipulation and Analysis
Used groupby, value_counts, sorting, and filtering techniques
Analyzed content distribution by type, country, rating, and year
Extracted top contributors such as directors and actors
Compared movies and TV shows over time
# Key Insights
Movies dominate the Netflix catalog compared to TV shows
Content production increased significantly after 2015
The United States contributes the highest number of titles
Most content is targeted toward adult audiences (TV-MA, TV-14)
Certain directors contribute multiple titles to the platform
Countries like the USA, UK, and South Korea produce many TV shows
The highest number of titles were added between 2017 and 2019
Drama and Comedy are the most common genres
# Data Visualization

The project includes multiple types of visualizations:

Bar charts for category comparison
Line charts for trend analysis
Histogram and KDE plots for distribution
Box and violin plots for spread analysis
Scatter plots for relationships
Pie charts for proportional analysis
Heatmaps for correlation and comparisons
# Conclusion

Netflix has experienced rapid growth in its content library, with a strong emphasis on movies and content targeting adult audiences. The platform is heavily dominated by content from the United States, but there is significant opportunity for expansion in international markets and diverse audience segments.

# Future Improvements
Build an interactive dashboard using Power BI or Tableau
Perform recommendation system analysis
Apply machine learning for content prediction
Enhance analysis with more detailed genre breakdown
