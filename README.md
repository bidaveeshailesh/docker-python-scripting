# Docker Python Scripting

## 📌 Project Overview

This project demonstrates how to run **Python scripts inside a Docker container**.

The project combines Python scripting with Docker to provide a consistent environment for executing scripts and practicing basic automation concepts.

## 🏗️ Architecture

```text id="c4m8zr"
Python Script
     |
     v
 Dockerfile
     |
     v
 Docker Image
     |
     v
Docker Container
     |
     v
Python Script Execution
```

## 🛠️ Technologies Used

- Python
- Docker
- Dockerfile
- Linux
- Shell Scripting
- Git & GitHub

## ⚙️ How It Works

1. Create a Python script.
2. Create a Dockerfile.
3. Define the Python environment.
4. Build a Docker image.
5. Start a container from the image.
6. Execute the Python script inside the container.
7. View the script output.

## 🐳 Example Docker Commands

Build the image:

```bash id="8r0v8w"
docker build -t python-scripting .
```

Run the container:

```bash id="n7j1mq"
docker run python-scripting
```

View running containers:

```bash id="6b8r3q"
docker ps
```

## 📂 Example Project Structure

```text id="p2k6vz"
docker-python-scripting/
│
├── Dockerfile
├── script.py
└── README.md
```

## 🎯 What I Learned

- Python scripting
- Docker fundamentals
- Dockerfile creation
- Building Docker images
- Running containers
- Executing scripts inside containers
- Basic automation concepts
- Linux and DevOps practices

## 📂 Project Type

**Python / Docker / Automation / DevOps**

## 👨‍💻 Author

**Shailesh Bidave**

GitHub: [@bidaveeshailesh](https://github.com/bidaveeshailesh)
