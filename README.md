# Python-projects-On-Data-Science
Python Projects while learning Data Science from Coursera course IBM Data Science

# SpaceX Launch Records Dashboard

This project is a SpaceX Launch Records Dashboard built using Python and the Dash web framework. It allows users to explore and analyze SpaceX rocket launches based on various criteria. The dashboard provides the following features:

## Features

### 1. Launch Site Selection
- A dropdown list to enable the selection of launch sites.
- The default selection is for all SpaceX launch sites.
- Users can choose a specific launch site from the list.

### 2. Success Pie Chart
- A pie chart displaying the total successful launches count for all sites.
- If a specific launch site is selected, it shows the success vs. failed counts for that site.
- Provides an overview of the success rates for SpaceX launches.

### 3. Payload Range Slider
- A slider that allows users to select a payload range in kilograms.
- Users can specify the minimum and maximum payload mass.
- Helps in filtering launches based on payload mass.

### 4. Success vs. Payload Scatter Chart
- A scatter chart showing the correlation between payload mass and launch success.
- If a specific launch site is selected, it displays the correlation for that site.
- Users can visually analyze the relationship between payload mass and launch outcomes.

## Technologies Used

- Python: Used for data analysis and the backend of the web application.
- Dash: A Python web framework for building interactive web applications.
- Plotly: Used to create interactive and visually appealing charts.
- Pandas: Used for data manipulation and analysis.

## Usage

- Clone this repository to your local machine.
- Make sure you have the required Python packages installed.
- Run the Python script to start the SpaceX Launch Records Dashboard.
- Access the dashboard in your web browser and explore SpaceX launch data.


# US Domestic Airline Flights Performance Dashboard

## Overview

This GitHub repository hosts a Python application built using Dash, which serves as a US Domestic Airline Flights Performance Dashboard. The dashboard offers two main report types: "Yearly Airline Performance Report" and "Yearly Airline Delay Report." Users can select a report type and a specific year to view relevant performance statistics.

## Features

- **Report Types:** Users can choose between two report types:
  - *Yearly Airline Performance Report*: This report provides insights into monthly flight cancellations, average monthly flight time by airline, the percentage of diverted airport landings per reporting airline, and the number of flights originating from each U.S. state.
  - *Yearly Airline Delay Report*: This report offers information on average carrier delay, weather delay, NAS (National Airspace System) delay, security delay, and late aircraft delay times by airline.

- **Dropdown Selection:** Users can select the report type and specify the year for which they want to view the performance data.

- **Interactive Visualizations:** The dashboard includes interactive graphs and charts to present the performance data effectively. Some of the visualizations include bar charts, line charts, pie charts, choropleth maps, and treemaps.

## Technical Overview

- The application is built using the Dash framework, which is based on Python and designed for creating interactive web-based data visualizations.

- It reads the airline performance data from a CSV file containing detailed flight information.

- The data is filtered based on the selected year.

- The app provides a dynamic interface with callback functions that compute and display the appropriate graphs and charts based on the user's choices.

## Usage

This project is a valuable tool for exploring and analyzing U.S. domestic airline performance, whether it's related to flight cancellations, delays, or other aspects. Users can easily generate insights and visualize trends using this user-friendly dashboard.

Feel free to clone or fork this repository and use it to analyze airline performance data or as a reference for creating your own Dash-based data visualization projects.

## How to Run

To run the dashboard, make sure you have the required Python packages installed. Use the following command to start the app:

```bash
python your_app_name.py
