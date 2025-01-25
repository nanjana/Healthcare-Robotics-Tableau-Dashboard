# Healthcare-Robotics-Tableau-Dashboard

## Dashboard Demonstration

Take a look at the **Healthcare Robotics Dashboard** in action! Click the link below to watch the video demonstration:

[Healthcare Robotics Dashboard - Short Video](https://drive.google.com/file/d/1Z3dVOZK4C1jcNqWdYl3kxLj3Rf3o11Cw/view?usp=drive_link)

## Snapshot of the Dashboard
[Snapshot of the Dashboard]()


This repository contains the code, data, and detailed explanation for a **Healthcare Robotics Dashboard** that provides insights into the performance, deployment, and efficiency of healthcare robotics across various countries and hospital types. The dashboard was built in Tableau to transform simulated raw data into actionable insights.

## Key Features
- **Global Robot Deployment Overview**: Visualize where robots are deployed and their performance across different regions.
- **Quarterly Trends Analysis**: Track trends in task volume, success rates, and error rates over time.
- **Operational Efficiency Insights**: Compare downtime, maintenance needs, and robot operating time across countries and hospital types.
- **Key Performance Indicators (KPIs)**:
  - Total Robots Deployed
  - Task Success Rate (%)
  - Cost Efficiency Per Task (USD)
  - Average Patient Satisfaction Score

## Project Highlights
- **Scenario**: Designed based on a hypothetical CEO’s requirements to analyze global deployment, quarterly trends, and operational efficiency of healthcare robots.
- **Interactive Filters**: Enable filtering by country and hospital type to provide deeper insights.
- **Tooltips**: Provide additional information on hover for all key metrics and visualizations.

## How It Works
### 1. Data Simulation
The dataset was simulated using Python and includes:
- **Robot Deployment Details**: Country, hospital type, deployment date.
- **Performance Metrics**: Daily task volume, success rate, error rate, downtime, and operating time.
- **Patient Insights**: Patient satisfaction scores for each robot deployment.

### 2. Dashboard Design
Using Tableau, the dataset was visualized to include:
- Interactive global maps.
- Line charts to analyze trends over time.
- Bar charts comparing operational efficiency by country.
- KPIs summarizing critical insights at a glance.

### 3. Key Steps
1. Simulated data using Python (`data_simulation.py`).
2. Loaded data into Tableau for analysis.
3. Built calculated fields and measures for KPIs.
4. Designed a purple-themed dashboard for readability and professional presentation.

## Installation
### Prerequisites
- [Python 3.7+](https://www.python.org/downloads/) for running the data simulation script.
- [Tableau](https://www.tableau.com/) for visualization.

## Run the Python script to generate the dataset:
- python Code.ipynb
- Open Tableau and load the generated dataset (healthcare_robotics_1.csv).
- Import the .twb or .twbx Tableau workbook to view the dashboard.

### Steps to Reproduce
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/healthcare-robotics-dashboard.git
   cd healthcare-robotics-dashboard
