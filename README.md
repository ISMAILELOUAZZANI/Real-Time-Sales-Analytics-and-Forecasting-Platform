# Real-Time Sales Analytics & Forecasting Platform

A professional end-to-end data analytics platform to monitor and forecast sales using real-time data streams and machine learning.

## Features

- Real-time sales data simulation and ingestion
- Data processing and aggregation
- Interactive dashboards (Streamlit)
- Machine Learning-based sales forecasting (Prophet)
- Dockerized deployment

## Quick Start

1. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
2. Simulate streaming data:
    ```
    python src/stream_simulator.py
    ```
3. Start the dashboard:
    ```
    streamlit run src/dashboard.py
    ```

## Project Structure

- `data/` — data and instructions
- `src/` — all source code
- `notebooks/` — EDA and model training
- `docker/` — Dockerfiles and deployment configs
- `results/` — screenshots and sample outputs