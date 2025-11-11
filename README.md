# Docker Compose Infrastructure

This repository contains the Docker Compose configuration for running the development infrastructure required by dependent applications. It provides all necessary services (databases, caches, message brokers, etc.) in a single, easy-to-start environment.

## Services

The following services are defined in this repository:

| Service      | Description                                      |
|-------------|--------------------------------------------------|
| `db`        | PostgreSQL database |
| `pgadmin`   | Web-based PostgreSQL administration tool |
| `mq`        | RabbitMQ message broker server |

---

## Getting Started

Clone the repository and start all services:

```bash
git clone https://github.com/DistCodeP7/docker-compose.git
cd docker-compose
docker-compose up -d