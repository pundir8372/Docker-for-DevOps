# Django Dockerized Application

## Overview

This repository contains a Django application that has been containerized using Docker. The application is designed to demonstrate how to set up a Django project with Docker, including the necessary configurations and best practices.

## Requirements

- **Docker**: Ensure you have Docker installed on your machine. [Install Docker](https://docs.docker.com/get-docker/)
- **Docker Compose**: If your application uses multiple services. [Install Docker Compose](https://docs.docker.com/compose/install/)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/pundir8372/Docker-for-DevOps.git
   cd Docker-for-DevOps/Projects/django-app
   
2. **Build the Docker image**
   ```bash
   docker build -t django-app

 4. **Run the Docker container**
    ```bash
    docker run -d -p 8000:8000 django-app  

Now you can access the application at http://127.0.0.1:8000.
