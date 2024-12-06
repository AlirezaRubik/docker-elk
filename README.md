# Docker ELK Stack with Filebeat Integration

This project provides a ready-to-use **Dockerized ELK (Elasticsearch, Logstash, Kibana)** stack integrated with **Filebeat** for real-time log monitoring and management. It also includes setup instructions for configuring Elasticsearch to manage logs efficiently.

## Features
- **Elasticsearch (E)**: Centralized log storage and powerful search capabilities.
- **Logstash (L)**: Log processing and transformation before storing in Elasticsearch.
- **Kibana (K)**: A user-friendly interface for visualizing logs and managing the stack.
- **Filebeat**: A lightweight log shipper for forwarding logs to Elasticsearch in real-time.
- **Custom Setup for Elasticsearch**: Predefined configurations for optimized performance.

---

## How to Use

### Option 1: Add ELK to an Existing Docker Folder
1. Copy the `elk` folder from this repository into the `docker` folder of your existing project.
2. Copy the `.env` file provided in this repository into the root of your `docker` folder.
3. Ensure your project includes a `logs` folder to store log files (e.g., `logs/logs.log`).

### Option 2: Set Up a Docker Folder from Scratch
1. If your project does not have a `docker` folder, you can copy the `docker` folder from this repository into the root of your project.
2. Copy the `.env` file into the newly added `docker` folder.
3. Create a `logs` folder in your project to store log files.

---

## Prerequisites
- **Docker** and **Docker Compose** must be installed on your system.
- Ensure your project has a `logs` folder to capture and analyze log files.

---

## Project Structure

---

## Setup Instructions
1. Clone this repository or copy the required folders/files into your project.
2. Run the following command in the `docker` directory to start the stack:
   ```bash
   docker-compose up -d
Access the following services:
Elasticsearch: http://localhost:9200
Kibana: http://localhost:5601
Alireza Alizadeh Aghdam
