# Docker Commands

## Basic Docker Setup
- **Check Docker version:**  
  docker --version

## Working with Docker Images
- **Pull the latest Ubuntu image:**  
  docker pull ubuntu:latest

- **List all Docker images on your system:**  
  docker images

## Working with Docker Containers
- **Run an Ubuntu container:**  
  docker run ubuntu:latest

- **Run an Ubuntu container in detached mode with interactive terminal:**  
  docker run -dit ubuntu:latest

- **List running containers:**  
  docker ps

- **List all containers, including stopped ones:**  
  docker ps -a

## Managing Directories for Docker Projects
- **Create a directory named `docker-practice`:**  
  mkdir docker-practice

- **Remove the `docker-practice` directory:**  
  rm docker-practice

- **Create another directory named `docker-basic`:**  
  mkdir docker-basic

## Cloning and Building Docker Projects
- **Change to the `docker-basic` directory:**  
  cd docker-basic/

- **Clone a sample Java Docker project from GitHub:**  
  git clone https://github.com/LondheShubham153/simple-java-docker.git

- **Change to the cloned project directory:**  
  cd simple-java-docker

- **Build a Docker image from the `Dockerfile` in the project:**  
  docker build -t java-app .

## Running a Custom Docker Image
- **Run a container using the built Java app image:**  
  docker run java-app:latest

## Other Useful Commands
- **Clear the terminal screen:**  
  clear

- **List files in the current directory:**  
  ls

---


