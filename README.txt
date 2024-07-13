# Logging System 

This project sets up a centralized logging system for a project system using ELK Stack (Elasticsearch, Logstash, Kibana) and Filebeat. The booking system comprises multiple services written in Symfony, Laravel, and Golang, each running on separate servers. The logs from these services are collected and centralized in Elasticsearch, allowing for monitoring and troubleshooting of the booking process.

## Project Structure

- `elasticsearch`: Configurations and setup for Elasticsearch.
- `kibana`: Configurations and setup for Kibana.
- `logstash`: Configurations and pipelines for Logstash.
- `filebeat`: Configurations for Filebeat for different services.

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/behnamhosseini/centralized-logging.git
   cd centralized-logging
   docker-compose up -




#bin/elasticsearch-service-tokens create elastic/kibana kibana
#docker exec -it elasticsearch /usr/share/elasticsearch/bin/elasticsearch-create-enrollment-token -s kibana
#bin/elasticsearch-setup-passwords interactive
