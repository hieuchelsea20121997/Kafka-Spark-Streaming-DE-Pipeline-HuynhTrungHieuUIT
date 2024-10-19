# Kafka-Spark-Streaming-DE-Pipeline-HuynhTrungHieuUIT
# Introduction
This project involves building a comprehensive end-to-end data engineering pipeline. It covers data ingestion, processing, and storage using a robust tech stack and Docker for scalability.
# System Architecture 
![image](https://github.com/user-attachments/assets/c32baf7b-5a31-4d95-b279-b6004d1d3841)
Data Source: Utilizes the Randomuser.me API for synthetic user data generation.

Apache Airflow: Acts as the pipeline orchestrator, coordinating tasks and managing data storage in PostgreSQL.

Apache Kafka & Zookeeper: Facilitates real-time data streaming and ensures message synchronization between PostgreSQL and other systems.

Confluent Control Center & Schema Registry: Provides oversight for Kafka and ensures proper schema management across the data stream.

Apache Spark: Handles large-scale data processing through a distributed architecture, utilizing both master and worker nodes for efficient computations.

Cassandra: Serves as the NoSQL database for storing processed data, ensuring high availability and scalability.
