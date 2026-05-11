# ⚡ Kafka + Spark Structured Streaming Pipeline with Airflow Orchestration

---

## 📌 Overview
An end-to-end **real-time data pipeline** integrating **Kafka**, **Spark Structured Streaming**, and **Apache Airflow**.  
- **Kafka producers** simulate live event streams (clickstream/transactions).  
- **Spark Structured Streaming** consumes, transforms, and aggregates data in micro-batches.  
- Results are written to a **partitioned data sink** for downstream analytics.  
- **Airflow DAGs** orchestrate the pipeline lifecycle, ensuring reliability and automation.

---

## 🛠️ Tech Stack
- **Python**
- **Apache Kafka**
- **Spark Structured Streaming**
- **Apache Airflow**
- **Docker**
- **Linux**

---

## 🚀 Features
- **Real-Time Streaming**: Kafka producers + Spark consumers for continuous ingestion.  
- **Pipeline Orchestration**: Airflow DAGs manage startup sequencing, health checks, reconciliation jobs, and failure alerting with retry logic.  
- **Exactly-Once Processing**: Kafka consumer offsets + Spark checkpointing ensure data accuracy.  
- **Operational Monitoring**:
  - Consumer lag tracking
  - Throughput measurement
  - Job latency analysis  
- **Runbook Documentation**: Covers failure modes, recovery steps, and scaling considerations.  

---

## 📈 Outcomes (to be updated)
- Demonstrates **real-time stream processing** and **pipeline orchestration**.  
- Validates **distributed systems design** and **operational monitoring**.  
- Directly maps to **Amazon DE infrastructure responsibilities**.  

---

## 📂 Project Structure
```bash
├── kafka/               # Kafka producer scripts
├── spark/               # Spark Structured Streaming jobs
├── airflow/             # Airflow DAGs for orchestration
├── docker/              # Docker setup files
├── tests/               # Unit & integration tests
├── .github/workflows/   # CI/CD pipeline configs
└── README.md            # Project documentation
