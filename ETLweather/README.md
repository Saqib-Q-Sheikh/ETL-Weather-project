# ETL Weather Project 🌦️

This project is an **ETL (Extract, Transform, Load)** pipeline that fetches real-time weather data using the **Open-Meteo API** and loads it into a **PostgreSQL** database.  
It is built using **Apache Airflow** to automate and schedule the data pipeline.

## Project structure 
ETLweather/
├── dags/
│   └── weather_dag.py       # Main Airflow DAG file
├── data/
│   └── weather_data.csv     # Extracted and transformed data
├── logs/                    # Airflow logs
├── plugins/                 # Custom plugins (if needed)
└── requirements.txt         # Python dependencies


## Features

- ⛅ **Extract**: Pulls weather forecast data from the Open-Meteo API.
- 🧹 **Transform**: Processes and cleans the raw data, saving it to a CSV file.
- 🗄️ **Load**: Inserts the cleaned data into a PostgreSQL database.
- ⚙️ **Automated Scheduling**: Managed using Apache Airflow.
- ✅ **Error Handling & Logging**: Logs progress and errors for easy monitoring.

## Tech Stack

- **Python**
- **Apache Airflow**
- **PostgreSQL**
- **Pandas**
- **Open-Meteo API**
