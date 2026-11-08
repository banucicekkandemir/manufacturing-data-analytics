# Manufacturing Data Analytics

This project builds a small end-to-end data pipeline for simulated
batch manufacturing sensor data. Raw CSV data is validated with Python,
loaded into DuckDB, and transformed with SQL into analysis-ready tables.
The goal is to practise core data engineering concepts: ETL/ELT,
data quality, data modelling, and reproducibility.

**Data note:** all data is synthetic or simulated, for educational use only.

## Setup



Create and activate the environment:

    conda env create -f environment.yml
    conda activate mfg
