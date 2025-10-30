#  Automated Triathlete Performance Dashboard

An interactive Jupyter Notebook project designed to track, analyze, and visualize triathlete training performance across swim, bike, and run activities. This dashboard simulates weekly workout data, generates predictive insights, and presents trends through dynamic visualizations — showcasing skills in data cleaning, analysis, automation, and dashboard development.

---

##  Project Overview

This dashboard helps monitor and optimize triathlete training by:
- Simulating weekly workouts
- Aggregating performance metrics
- Visualizing trends and KPIs
- Predicting future performance
- Automating data updates

It reflects industry-level data analyst responsibilities such as trend monitoring, dashboard building, and performance reporting.

---

##  Features

- **Workout Tracking**: Logs daily swim, bike, and run sessions with distance, duration, and calories.
- **Weekly Summary**: Aggregates total weekly metrics per activity.
- **Data Visualization**:
  - Weekly distance trends
  - Predicted vs actual performance
  - KPIs: total distance, duration, calories, average pace
- **Predictive Insights**: Forecasts next week’s performance using historical averages.
- **Automated Data Simulation**: Adds new weekly data for continuous tracking.
- **Portfolio-Ready**: Clean, reproducible notebook with modular code and documentation.

---

##  Dataset Structure

Simulated or CSV-based data (`triathlete_data.csv`) with the following columns:

| Column Name     | Description                              |
|-----------------|------------------------------------------|
| `date`          | Date of the activity                     |
| `activity_type` | Type of activity: Swim, Bike, or Run     |
| `distance_km`   | Distance covered (in kilometers)         |
| `duration_min`  | Duration of the workout in minutes       |
| `calories`      | Calories burned during the activity      |

Data can be generated programmatically or loaded from file, and is updated weekly for ongoing analysis.

---

##  Technologies & Libraries

- **Python 3.9+**: Core programming language
- **Pandas**: Data cleaning and aggregation
- **NumPy**: Numeric computations and random simulation
- **Plotly Express**: Interactive charts and visualizations
- **Jupyter Notebook**: Code execution and documentation

---

##  Key Functions

- `weekly_summary(df)`: Aggregates weekly totals for each activity
- `predict_next_week(df)`: Forecasts next week’s distances using historical data
- `simulate_new_week(df)`: Adds a new week of simulated workouts

---

##  Visualizations

- **Weekly Distance Trends**: Line chart per activity
- **Activity KPIs**: Summary table of distance, duration, calories, pace
- **Predicted vs Actual**: Bar chart comparison
- **Automated Updates**: Dynamic chart reflecting new data additions

---

##  Project Workflow

1. **Data Generation / Loading**: Create or import workout data
2. **Data Cleaning & Preparation**: Validate types and handle missing values
3. **Analysis**: Compute summaries and KPIs
4. **Visualization**: Explore trends with Plotly
5. **Prediction & Automation**: Forecast and simulate future workouts
6. **Notebook Packaging**: Combine code, visuals, and documentation

---

##  Potential Extensions

- Integrate with **Streamlit** or **Dash** for web-based dashboards
- Add heart rate, pace, or cadence metrics
- Use machine learning for smarter predictions
- Track performance goals and send alerts
- Enable filtering by date range, activity type, or month

---

