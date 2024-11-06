# Elastic Stack Docker

This repository provides a Docker-based setup for deploying the Elastic Stack (Elasticsearch, Logstash, Kibana) quickly and easily. The setup is designed to streamline log aggregation, visualization, and real-time monitoring of applications.

## Features
- **Elasticsearch**: Stores and indexes log data.
- **Logstash**: Collects, processes, and forwards log data.
- **Kibana**: Visualizes and explores log data in dashboards.

## Prerequisites
- Docker and Docker Compose installed

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/mehtachandrashekhar/elastic-stack-docker.git
   ```
2. Navigate to the project directory:
   ```bash
   cd elastic-stack-docker
   ```
3. Run the stack:
   ```bash
   docker-compose up -d
   ```

## Configuration
Adjust settings in the `docker-compose.yml` file as needed, including volume paths and environment variables.

## Accessing Kibana
After the setup, access Kibana at [http://localhost:5601](http://localhost:5601) for data visualization.
