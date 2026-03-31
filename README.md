# CIVE_202_PROJECT-3
# Project 3: Transportation Data Visualization and Simulation

## Overview
This project analyzes transportation trends and driving behavior using two datasets: the National Household Travel Survey (NHTS) and the Next Generation Simulation (NGSIM) data. The goal is to better understand vehicle characteristics and how vehicles move and interact on roadways.

Python is used to organize the data, create visualizations, and run a simulation using the Intelligent Driver Model (IDM). The results help show patterns in traffic behavior and vehicle interactions.

---

## Data Sources
- NHTS Dataset (vehicle characteristics such as make, age, fuel type, and urban category)
- NGSIM Dataset (vehicle trajectory data including position, speed, and acceleration)

---

## Methods
The datasets are loaded into Python using pandas and explored to identify useful variables. Several types of graphs are created using matplotlib, including:
- Bar chart (vehicle make)
- Histogram (vehicle age)
- Boxplot (vehicle age by urban category)
- Time-series plots (position, speed, acceleration, and gap distance)

A gap distance variable is calculated to analyze spacing between vehicles. An Intelligent Driver Model (IDM) simulation is also developed to model how a follower vehicle responds to a leader vehicle.

---

## How to Run the Code
1. Open the Jupyter Notebook file (`.ipynb`)
2. Run all cells from top to bottom
3. Make sure the NHTS and NGSIM CSV files are in the same folder as the notebook

---

## Results
The visualizations show trends in vehicle characteristics and driving behavior. The time-series plots illustrate how speed, position, and spacing change over time. The IDM simulation provides a comparison between simulated and real vehicle movement.

---

## Files Included
- Jupyter Notebook (`.ipynb`)
- NHTS dataset (`.csv`)
- NGSIM dataset (`.csv`)
- Annotated code document (Excel)
- Gantt chart
- Timesheet

---

## Author
Camdin Wagner McGuigan  
CIVE 202 – Civil Engineering Analysis II
