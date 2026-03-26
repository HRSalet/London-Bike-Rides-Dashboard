# London Bike Rides

## 1. Overview

This Tableau dashboard offers detailed analytics and visualizations on the data provided for London bike rides. The dashboard monitors the pattern of bike rides, the correlation with the weather, and the time factor.

## 2. Purpose

This dashboard will allow stakeholders to identify peak usage hours, understand how weather conditions influence bike rentals, and analyze usage trends over time. This is beneficial in making informed decisions regarding bike fleet management, station optimization, and service delivery according to usage patterns.

## 3. Tech Stack<br>

The dashboard was built using the following tools and technologies:
- 📊 Tableau Public – Main data visualization platform used for report creation.
- 🐍 Python - Data Transformation and cleaning layer for reshaping and preparing the data.
- 🧠 LOD (Level of Detail) expressions – Used for calculated field, and dynamic visuals.
- 📁 File Format – .twb for development and .png for dashboard previews.

## 4. Data Source

Kaggle - [London Bike Rides Dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)

This dataset is based on London Bike Sharing. It contains 10 columns and more than 10000 rows.

## 5. Visualizations

The dashboard utilizes different types of visualizations to represent data in an easily understandable format, allows for deeper insights into the London bike rides.

**1. London Bike Rides (KPI)**<br>
This metric indicates the overall number of bike rides during the specified time frame. It also shows the time frame to easily understand the traffic and transportation data.

**2. Moving Average (Line Chart)**<br>
This graphic illustrates bike-sharing patterns, showcasing smoothed riding trends throughout the time frame with adjustable moving averages. Users can effortlessly engage with this visual by dragging and selecting on the timeline.

**3. Temperature Vs. Wind (Heatmap)**<br>
A heatmap showing the connection (correlation) between temperature and wind speed in relation to bike usage. Stakeholders can easily comprehend bike rides, irrespective of weather conditions. It also shows the timeframe for obtaining further details about biking trips.

**4. Weather Chart(Bar Chart)**<br>
This visualization represents the count of bike rides based on different weather conditions. Weather conditions include broken clouds, scattered clouds, clear, rain, cloudy, snowfall, and rain with thunderstorm. This visualization provides information about weather conditions at which the count of bike rides is at its highest. For example, at weather conditions like broken clouds, the count of bike rides is at its highest, and at weather conditions like rain with thunderstorm, the count of bike rides is at its lowest.

**5. Hour Chart(Bar Chart)**<br>
The visual represents the number of bikes ride based on different hours. If user interacts with this visual, it will display the hour and count for detailed analysis within a particular time range. For example, the maximum number of bike ride count occurs during morning hours based on a select time range, and the minimum occurs during early morning hours.

## 6. Filters
On the dashboard, interactive tools are used for better user experience. The dashboard has three filters placed on the top, out of which one is Moving Average Duration, used for entering numeric values based on the moving average period. The second filter is Moving Average Period, used for selecting the time period based on days, weeks, and months. The third filter is Moving Average filter, used for displaying data on an annual basis. This feature is used for analyzing the history, identifying the trends, and moving towards the future.

## 7. Screenshots

![Dashboard Preview](https://github.com/HRSalet/London-Bike-Rides-Dashboard/blob/main/Dashboard%20Snapshot.png)
