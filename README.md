# Real-Time Data Processing with Docker, Linux & Apache Kafka

## Project Overview
Academic project completed at Seneca Polytechnic (CSP450, Fall 2023).

This project focuses on deploying and running a containerized Transactional Machine Learning (TML) application for real-time data processing and visualization.

## Technologies
- **Operating System:** Ubuntu Linux
- **Virtualization:** VMware
- **Containerization:** Docker
- **Streaming Technology:** Apache Kafka
- **Session Management:** TMUX
- **Dashboard:** Browser-based real-time TML visualization
- **Version Control:** GitHub

## Project Implementation
1. Created an Ubuntu Linux virtual machine using VMware.
2. Installed Docker and verified the installation.
3. Pulled and ran the TML application container.
4. Built a Docker image using the supplied Dockerfile.
5. Configured port 9005 to access the dashboard from the host.
6. Used Docker CLI to inspect and access running containers.
7. Used TMUX to inspect application sessions.
8. Accessed the real-time dashboard to visualize streaming predictions.

## Architecture
Ubuntu VM (VMware) → Docker Container → TML Application / Kafka Data Streams → Web Dashboard (Port 9005)

## Validation
The project included checking container status, inspecting TMUX sessions, and verifying that the dashboard displayed streaming data.

## Screenshots
Screenshots of the running dashboard, Docker containers, and TMUX sessions can be added here.

## Original Project Resources
The application and original Dockerfile were provided as part of the course materials.

Source: https://github.com/smaurice101/raspberrypi

## Academic Context
Seneca Polytechnic — CSP450, Fall 2023.

This repository documents the deployment and configuration work performed for the academic assignment. The underlying TML application was not developed from scratch as part of this project.
