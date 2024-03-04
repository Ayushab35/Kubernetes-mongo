Certainly! Here's the content in a single .md file:

```markdown
# Docker Commands Cheat Sheet

This cheat sheet provides a summary of important Docker commands.

## Image Commands

### Pull an Image
```bash
docker pull <image_name>
```
Pulls an image from a registry.

### List Images
```bash
docker images
```
Lists all locally available images.

### Remove an Image
```bash
docker rmi <image_id>
```
Removes a specified image from the local machine.

## Container Commands

### Run a Container
```bash
docker run <options> <image_name>
```
Runs a container based on an image.

### List Containers
```bash
docker ps
```
Lists all running containers.

### List All Containers (Including Stopped)
```bash
docker ps -a
```
Lists all containers including stopped ones.

### Stop a Container
```bash
docker stop <container_id>
```
Stops a running container.

### Start a Stopped Container
```bash
docker start <container_id>
```
Starts a stopped container.

### Remove a Container
```bash
docker rm <container_id>
```
Removes a specified container.

### Remove All Stopped Containers
```bash
docker container prune
```
Removes all stopped containers.

## Network Commands

### List Networks
```bash
docker network ls
```
Lists all Docker networks.

### Create a Network
```bash
docker network create <network_name>
```
Creates a new Docker network.

### Connect a Container to a Network
```bash
docker network connect <network_name> <container_name>
```
Connects a container to a network.

### Disconnect a Container from a Network
```bash
docker network disconnect <network_name> <container_name>
```
Disconnects a container from a network.

## Volume Commands

### List Volumes
```bash
docker volume ls
```
Lists all Docker volumes.

### Create a Volume
```bash
docker volume create <volume_name>
```
Creates a new Docker volume.

### Remove a Volume
```bash
docker volume rm <volume_name>
```
Removes a specified Docker volume.

## System Commands

### Display Docker System Information
```bash
docker info
```
Displays system-wide information regarding Docker.

### Display Docker Version
```bash
docker version
```
Displays the Docker version information.

### Clean Up Docker Resources
```bash
docker system prune
```
Removes unused data including stopped containers, networks, and dangling images.

### Display Docker Disk Usage
```bash
docker system df
```
Displays disk usage by Docker.
