Project Overview:
The Automated Triathlete Performance Dashboard is an interactive Jupyter Notebook project designed to track, analyze, and visualize the training performance of a triathlete over time. It simulates weekly workout data for swimming, biking, and running, and provides insights through visualizations, summary metrics, and predictive analysis for upcoming workouts.
This project demonstrates skills in data cleaning, analysis, visualization, and automation—aligned with industry-level data analyst responsibilities, such as dashboard building, trend monitoring, and performance insights.

Features

Workout Tracking: Records daily swimming, biking, and running sessions including distance, duration, and calories burned.

Weekly Summary: Aggregates total weekly distance, duration, and calories per activity.

Data Visualization:

Weekly trends in distance per activity.

Predicted vs actual weekly averages.

KPIs such as total distance, duration, calories, and average pace.

Predictive Insights: Estimates next week’s performance using historical averages.

Automated Data Simulation: Adds a new week of training data automatically for ongoing analysis.

Portfolio-Ready: Fully functional Jupyter Notebook with clean, reproducible code.

Dataset

The dataset simulates a triathlete’s workouts with the following columns:

Column Name	Description
date	Date of the activity
activity_type	Type of activity: Swim, Bike, or Run
distance_km	Distance covered (in kilometers)
duration_min	Duration of the workout in minutes
calories	Calories burned during the activity

The data can be generated programmatically or loaded from a CSV file (triathlete_data.csv).

Data can be automatically updated weekly for continuous monitoring.

echnologies & Libraries

Python 3.9+: Programming language for data manipulation and logic.

Pandas: Data cleaning, aggregation, and analysis.

NumPy: Numeric computations and simulation of random data.

Plotly Express: Interactive visualizations and charts.

Jupyter Notebook: Interactive environment for code, visualizations, and documentation.

Key Functions
1. weekly_summary(df)

Aggregates data on a weekly basis for each activity type, computing total distance, duration, and calories.

2. predict_next_week(df)

Predicts next week’s distance for each activity based on historical averages and random variation.

3. simulate_new_week(df)

Simulates a new week of workouts, automatically adding data to the dataset for ongoing analysis.

Visualizations

Weekly Distance Trends: Line chart displaying weekly distance for each activity.

Activity KPIs: Summary table including total distance, duration, calories, and average pace.

Predicted vs Actual: Bar chart comparing actual weekly average distances with predicted values.

Automated Updates: Dynamic visualization showing the impact of newly simulated weekly data.

Project Workflow

Data Generation / Loading:
Generate or load the triathlete dataset.

Data Cleaning & Preparation:
Ensure proper data types, handle missing values, and validate ranges.

Analysis:
Compute weekly summaries, total KPIs, and average metrics.

Visualization:
Create interactive charts using Plotly Express to explore trends and patterns.

Prediction & Automation:
Estimate next week’s performance and simulate new weeks of data.

Portfolio-Ready Notebook:
Combine code, visualizations, and documentation into a single, reproducible Jupyter Notebook.
Potential Extensions

Integrate with Streamlit or Dash to create an interactive web dashboard.

Include heart rate, pace, or cadence data for deeper analysis.

Implement machine learning models for more accurate next-week predictions.

Add performance goal tracking and progress alerts.

Enable filtering by month, activity, or custom date ranges.
