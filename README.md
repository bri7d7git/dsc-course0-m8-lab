# Commercial Jet Airline Safety Analysis (1983-2023)

##  Project Overview
This project provides a comprehensive data analysis of commercial and passenger jet airline safety to support structural underwriting decisions for aircraft insurers. Utilizing a historical dataset spanning 1948 to 2023, this analysis isolates professional aircraft builds operating within a modern 40-year operational lifecycle window (filtering data from **1983 onwards**). 

The goal is to identify specific manufacturers and structural factors that minimize total aircraft destruction and mitigate the likelihood of severe passenger injuries.

### Project Objectives

This project explores historical aviation accident data to identify patterns that can support insurance risk assessment and improve understanding of aviation safety. The main objectives are:

Evaluate aircraft manufacturer safety
Compare accident and hull-loss rates across major commercial aircraft manufacturers to identify models with stronger safety records.
Analyze aircraft design factors
Investigate whether structural characteristics, such as the number of engines, influence the likelihood of severe damage or passenger survival.
Examine environmental risks
Study how weather conditions affect the severity of injuries sustained during aviation accidents.
Build a transparent data preparation process
Clearly document every step used to clean, filter, and prepare the dataset, including how missing values and inconsistent records were handled.
### Key Safety Metrics

1. Total Destruction Rate

The Total Destruction Rate shows how often an aircraft was completely destroyed after an accident. It is calculated by dividing the number of total destruction (hull-loss) accidents by the total number of recorded accidents.

2. Severe Injury Rate

The Severe Injury Rate measures how many people on board suffered fatal or serious injuries during an accident. It is calculated by dividing the total number of fatal and serious injuries by the total number of people on board.

## Repository Structure
```text
├── data/
│   └── AviationData.csv       <-- Raw dataset
├── notebooks/
│   ├── Aviation_Accident_Cleaning.ipynb       <-- Data parsing and null handling
│   └── Aviation_Accident_Data_Analysis.ipynb   <-- EDA and visualizations
├── engine_analysis.png        <-- Saved chart image
├── weather_analysis.png       <-- Saved chart image
├── .gitignore
└── README.md                  <-- Project documentation # Aviation Accident Analysis


