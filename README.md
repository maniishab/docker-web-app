 # Dockerizing a Flask Web Application

This project demonstrates how a simple Python Flask web application can be containerized using Docker. Containerization allows applications and their dependencies to be packaged together, ensuring consistent behavior across different environments.

---

## 🚀 Project Overview

The project includes a basic Flask web application that is packaged into a Docker container. Docker makes it possible to run the application reliably on any system without worrying about environment configuration differences.

---

## 🛠 Technologies Used

* **Python** – Programming language used for the application
* **Flask** – Lightweight web framework for building the web application
* **Docker** – Platform used to build and run containers
* **Dockerfile** – File containing instructions to build the Docker image

---

## 📂 Project Structure

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
* **requirements.txt** – Python dependencies required for the application
* **Dockerfile** – Instructions used by Docker to build the container image
* **screenshots** – Contains screenshots showing the application output

---

## ⚙️ How to Run This Project

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

## 📸 Project Screenshots

### Docker Images and Container

![Docker Images](screenshots/docker-images\&container.png)

### Web Application Running

![Web Application](screenshots/web-app-running.png)

---

## 📚 Learning Outcomes

* Understanding Docker and containerization concepts
* Writing and using a Dockerfile
* Building Docker images
* Running applications inside containers
* Packaging applications with their dependencies for consistent deployment
