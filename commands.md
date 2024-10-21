# Docker Commands

## Basic Docker Setup
- **Check Docker version:**
  ```bash 
  docker --version

## Working with Docker Images
- **Pull the latest Ubuntu image:**
  ```bash
  docker pull ubuntu:latest

- **List all Docker images on your system:**
  ```bash
  docker images

## Working with Docker Containers
- **Run an Ubuntu container:**
  ```bash
  docker run ubuntu:latest

- **Run an Ubuntu container in detached mode with interactive terminal:**
  ```bash
  docker run -dit ubuntu:latest

- **List running containers:**
  ```bash
  docker ps

- **List all containers, including stopped ones:**
  ```bash
  docker ps -a

## Managing Directories for Docker Projects
- **Create a directory named `docker-practice`:**
  ```bash
  mkdir docker-practice

- **Remove the `docker-practice` directory:**
  ```bash
  rm docker-practice

- **Create another directory named `docker-basic`:**
  ```bash
  mkdir docker-basic

## Cloning and Building Docker Projects
- **Change to the `docker-basic` directory:**
  ```bash
  cd docker-basic/

- **Clone a sample Java Docker project from GitHub:**
  ```bash
  git clone https://github.com/LondheShubham153/simple-java-docker.git

- **Change to the cloned project directory:**
  ```bash
  cd simple-java-docker

- **Build a Docker image from the `Dockerfile` in the project:**
  ```bash
  docker build -t java-app .

## Running a Custom Docker Image
- **Run a container using the built Java app image:**
  ```bash
  docker run java-app:latest

## Other Useful Commands
- **Clear the terminal screen:**
  ```bash
  clear

- **List files in the current directory:**
  ```bash
  ls

---


