Here’s an improved and polished version of your Docker basics with added emojis:

---

# 🐳 Basic Docker Commands

### 1. `docker run`
👉 **Used to run an image, which becomes a container**.

### 2. `docker ps -a`
👉 **Lists all containers** (both running and stopped) to check their status.

### 3. `docker rm <container-id>`
👉 **Removes a container** by specifying its container ID.  
📝 Example: `docker rm <container-id>`

### 4. `docker rmi <image-name>`
👉 **Removes a Docker image**.  
📝 Example: `docker rmi nginx`

### 5. `docker pull <image-name>`
👉 **Downloads a Docker image from the Docker Hub** if it's not available locally.  
📝 Example: `docker pull nginx`

### 6. `docker exec -it <container-id> <command>`
👉 **Runs a command inside a running container**.  
- `-it` allows you to interactively provide input from the terminal.  
📝 Example: `docker exec -it <container-id> /bin/bash` (opens an interactive bash shell inside the container)

---

# ⚙️ Steps of Docker Process

### 1. `docker build .`
👉 **Builds an image from a Dockerfile** in the current directory.

### 2. `docker images`
👉 **Lists all Docker images** on the system.

### 3. `docker run <image-name>`
👉 **Runs the image and starts a container**.

---

# 🚀 Cleanup and Maintenance Commands

### 1. `docker rmi $(docker images -q)`
👉 **Removes all Docker images**.

### 2. `docker start $(docker ps -aq)`
👉 **Starts all stopped containers**.

### 3. `docker stop $(docker ps -aq)`
👉 **Stops all running containers**.

---
