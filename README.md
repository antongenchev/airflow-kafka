# Airflow-Kafka Mini Data Streaming Project
This repository contains a minimal data streaming setup utilizing Apache Airflow and Kafka. It's based on the tutorial by CodeWithYou, which you can find here https://youtu.be/GqAcTrqKcrY?si=yUteXB5KiD3fkkyu. This setup can serve as a reusable template for other data streaming projects.

## Overview
This project demonstrates a simple streaming data pipeline that integrates Kafka with Airflow. It showcases how to produce and consume data in Kafka and orchestrate the entire data flow using Airflow.

## Getting Started
Ensure the following tools are installed:
-Docker
-Docker Compose

1. Clone this repository:
    git clone https://github.com/antongenchev/airflow-kafka.git
    cd airflow-kafka
2. Create a virtual environment
    virutalenv venv
    source venv/bin/activate (venv/bin)
3. Run the docker-compose. Please ensure there are no port conflicts
    docker compose up -d
4. Go to the Airflow Web UI http://localhost:8080 and start the DAG user-data-stream
