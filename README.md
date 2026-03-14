# Dockerizing a Flask Web Application

This project demonstrates how a simple Python Flask web application can be containerized using Docker. Containerization packages the application and its dependencies together, allowing it to run consistently across different environments.

---

## Project Overview

The repository contains a basic Flask web application that is packaged and executed inside a Docker container. Using Docker simplifies deployment and ensures that the application behaves the same way regardless of where it is run.

---

## Technologies Used

* Python
* Flask
* Docker
* Dockerfile

---

## Project Structure

```
docker-web-app
│
├── app.py
├── requirements.txt
├── Dockerfile
├── README.md
└── screenshots
```

* **app.py** – Flask application source code
* **requirements.txt** – Python dependencies required by the application
* **Dockerfile** – Instructions used to build the Docker image
* **screenshots** – Contains screenshots of the Docker setup and running application

---

## How to Run This Project

### 1. Clone the repository

```
git clone https://github.com/maniishab/docker-web-app.git
```

### 2. Navigate to the project directory

```
cd docker-web-app
```

### 3. Build the Docker image

```
docker build -t flask-docker-app .
```

### 4. Run the Docker container

```
docker run -p 5000:5000 flask-docker-app
```

### 5. Open the application in a browser

```
http://<public-ip>:5000
```

The browser should display:

```
Hello from Docker Container!
```

---

## Project Screenshots

### Docker Images and Container

![Docker Images](screenshots/docker-images\&container.png)

### Web Application Running

![Web Application](screenshots/web-app-running.png)

---

## Learning Outcomes

* Understanding the basics of Docker and containerization
* Writing and using a Dockerfile
* Building Docker images
* Running applications inside containers
* Packaging applications with their dependencies for consistent deployment
