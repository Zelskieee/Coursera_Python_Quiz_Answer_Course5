# Practice Quiz: Work with containers on GCP
**Total points:** 10
**Score:** 100%

## Question 1
What is the purpose of building Docker images in containerization? 

- To run multiple Docker containers simultaneously.
- To manage Docker networks and volumes.
- To download and install Docker software on a host machine.
- **To create a lightweight, standalone, executable package that includes an application and its dependencies.**

## Question 2
Which of the following options correctly demonstrates the usage of the docker run command to start a Docker container with specific configurations? 

- docker run start -d mycontainer:latest
- docker run --image mycontainer:latest -p 8080:80
- docker run -v /host/path:/container/path myimage
- **docker run -it --name mycontainer myimage**

## Question 3
True or false: When running a docker logs command, you don’t have to write the entire container ID, as long as the initial characters uniquely identify the container. 

- **True**
- False

## Question 4
What is the purpose of the docker inspect command? 

- To create a new Docker container based on the provided configuration file.
- To start a stopped Docker container with the given name or ID.
- **To retrieve detailed information about a Docker object, such as a container, image, network, or volume.**
- To remove a specified Docker container from the system.

## Question 5
What is a common technique for debugging issues in Docker containers when troubleshooting runtime problems? 

- Modifying the host system configuration.
- **Inspecting container logs.**
- Changing the container image.
- Restarting the Docker Daemon.

## Question 6
What is the purpose of the docker pull command in Docker containerization? 

- To push changes made in a local container to the Docker Hub.
- To upload a Docker image to the Docker Hub repository.
- To create a new Docker container.
- **To download a Docker image from the Docker Hub repository to the local system.**

## Question 7
Which of the following options correctly demonstrates the command to push a Docker image to Google Artifact Registry? 

- docker push gcr.io:my-project/my-image:latest
- docker push my-image:latest gcr.io/my-project
- docker push my-image@gcr.io/my-project:latest
- **docker push gcr.io/my-project/my-image:latest**

## Question 8
Which Google Cloud Platform (GCP) service is specifically designed for orchestrating and managing Docker containers? 

- Google Cloud Storage
- Google Cloud SQL
- Google App Engine
- **Google Kubernetes Engine (GKE)**

## Question 9
Which Google Cloud Platform (GCP) service can be integrated with Docker to store and manage Docker images in a private repository? 

- Google Cloud Storage
- **Google Container Registry (GCR)**
- Google Cloud SQL
- Google App Engine

## Question 10
What is Google Kubernetes Engine (GKE) used for in the context of scaling containers on GCP? 

- Creating virtual machines for running containers.
- **Managed Kubernetes service for deploying, managing, and scaling containerized applications.**
- Google's proprietary containerization technology.
- A tool for designing container architectures.