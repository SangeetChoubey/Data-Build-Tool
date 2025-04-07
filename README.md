# Data-Build-Tool
This repository provides insights into DBT Cloud models, runs, and projects. It helps analyze model run performance, identify bottlenecks, and optimize execution times for improved efficiency.


# DBT Cloud Job & Run Tracker

This repository provides a solution to fetch metadata about **DBT Cloud runs and jobs** using the **DBT Cloud APIs**, and load that data into a **PostgreSQL data warehouse**. Once the data is available in the warehouse, it can be analyzed using BI tools such as **Metabase** to monitor performance and identify optimization opportunities.

## 🔍 Overview

The goal of this project is to enable visibility into DBT job and run metrics by:

- Extracting job and run data from your DBT Cloud account using its API.
- Loading the fetched data into a PostgreSQL database.
- Visualizing historical job and run trends using BI tools like Metabase.

This helps in:

- Monitoring run times of various jobs.
- Identifying slow-performing models.
- Detecting trends or anomalies over time.
- Uncovering bottlenecks and opportunities for optimization in your DBT models.

## 🛠️ Tech Stack

- **DBT Cloud API** – for fetching metadata about jobs and runs.
- **Python** – for data extraction and loading logic.
- **PostgreSQL** – target warehouse for storing DBT metadata.
- **Metabase** – for building visual dashboards to analyze trends.

## 📈 Example Use Case

Once the data is loaded into PostgreSQL, you can build dashboards in Metabase showing:

- Average run time by job
- Historical run duration trends
- Frequency of failed vs. successful runs
- Time series analysis for each job or model

