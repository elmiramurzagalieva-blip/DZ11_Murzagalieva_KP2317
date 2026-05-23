# Security Container with Quality Monitoring

Dockerized web application for malicious URL and content filtering with integrated Prometheus and Grafana monitoring stack.

## Description

This project implements a security container that filters incoming requests for malicious content including:
- Blacklisted domains;
- Suspicious patterns;
- Short link services.

All requests are logged to MySQL database. Prometheus collects application metrics, and Grafana provides real-time visualization for quality assessment.

## Features

- Flask-based web interface for URL/content checking
- MySQL database for request logging
- phpMyAdmin for database management
- Nginx as reverse proxy
- Prometheus metrics export
- Grafana dashboard with key quality indicators

## Quick Start

### Prerequisites
- Docker Desktop
- Docker Compose

### Run
docker-compose up -d

## Links
Docker Hub: https://hub.docker.com/r/elmiramurzagalieva/dz11-security-monitoring

## License
Educational project

## Author
Elmira Murzagalieva, KP-23-17
