# COVID-19 Dataset Analysis with PySpark

## Project Overview
This project analyzes a COVID-19 dataset using PySpark, showcasing data cleaning, transformation, aggregation, and insights extraction. The dataset is sourced from Kaggle and contains global COVID-19 statistics, including confirmed cases, deaths, and recoveries. 

The goal is to provide an efficient and scalable approach to data analysis using Apache Spark.

---

## Features
- **Data Loading**: Reads and infers schema from a CSV dataset.
- **Data Cleaning**: Handles missing values through removal or substitution.
- **Data Aggregation**: Calculates total confirmed cases per country.
- **Data Transformation**: Adds a new column to compute the mortality rate.
- **Analysis**: Identifies countries with the highest mortality rates.
- **Time Series Analysis**: Calculates daily new cases per country using window functions.

---

## Prerequisites
To run this project, you need the following:
- **Python 3.x**
- **Apache Spark** (PySpark library)
- **COVID-19 dataset** from Kaggle: `covid_19_data.csv`

---

## Installation and Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Ponsankar-t/Covid-19_PySpark_BDA
   cd covid19-pyspark-analysis
