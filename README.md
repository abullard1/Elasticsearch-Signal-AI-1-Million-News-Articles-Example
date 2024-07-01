
# Elasticsearch Signal AI 1 Million News Articles Example

This repository contains a Jupyter notebook showcasing how to **index and search the Signal AI 1 Million News Articles dataset using Elasticsearch**. The project demonstrates the creation of indices, bulk indexing of documents, setup of custom pipelines, and execution of complex search queries.

## Setup Instructions

### Prerequisites
- [Docker](https://www.docker.com/products/docker-desktop/)
- [Docker Compose](https://docs.docker.com/compose/install/linux/) *(Included in Docker Desktop)*

### Installation Using Docker Compose

1. Clone the repository:
   ```
   git clone https://github.com/abullard1/Elasticsearch-Signal-AI-1-Million-News-Articles-Example.git
   cd Elasticsearch-Signal-AI-1-Million-News-Articles-Example
   ```

2. Build and start the Docker containers:
   ```
   docker-compose up -d
   ```

### Installation Using Docker Package

1. Log in to GitHub:
   ```
   docker login ghcr.io
   ```

2. Pull the Docker image from the GitHub Docker registry:
   ```
   docker pull ghcr.io/abullard1/elasticsearch-signal-ai-1-million-news-articles-example-docker-container:latest
   ```

3. Run the Docker container via Docker Desktop or CLI

### Verification

Verify the setup by accessing the following:
- **Elasticsearch Page:** [https://localhost:9200/](https://localhost:9200/)
- **Kibana Dashboard:** [http://localhost:5601/](http://localhost:5601/)

## Using the Jupyter Notebook

Once **Elasticsearch**, **Kibana**, and **Metricbeat** are up and running, interact with them using the provided Jupyter Notebook by executing the cells. Adjust parameters as needed based on your hardware and intent.
