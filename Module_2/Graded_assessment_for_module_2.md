# Practice Quiz: Graded assessment for module 2
**Total points:** 10
**Score:** 100%

## Question 1
Another developer asked where the central repository is for downloading containers. What should you tell them?

- **Docker Hub**
- Docker Host
- Docker Repo
- Docker Central

## Question 2
Your development team was tasked to pilot using Docker images in the company’s next big programming project. What components are included in a Docker image? Select all that apply.

- **Application code**
- Data files
- **Other running containers**
- **Configuration files**

## Question 3
You informed another programmer that Cloud Run can help them launch containers. They asked what the benefit is of using Cloud Run. What should you tell them?

- **It allows you to deploy code written in any programming language if you can put the code into a container.**
- It allows you to run an application in the background continuously.
- It allows you to reuse multiple containers at once for different programs.
- It allows you to assign it to a static IP address so that it can be accessed from anywhere.

## Question 4
You are developing a Python-based data processing application. One component of the application processes raw data, while another component analyzes the processed data. You want these components to easily exchange data. You also want to ensure that the processed data persists even if one of the containers restarts. Why are Pods in Kubernetes a good fit for this task? Select all that apply.

- **Pods enable data sharing.**
- Pods facilitate co-location.
- Pods simplify inter-container communication.
- **Pods share the same network namespace.**

## Question 5
Samantha, a lead developer, is explaining to her team how Kubernetes Deployments work. She mentions that Deployments use a specific resource to ensure the desired number of identical Pods are always running, even if some Pods fail or are deleted. What resource is Samantha referring to?

- Service
- **ReplicaSet**
- ConfigMap
- PersistentVolumeClaim

## Question 6
You’re setting up a Kubernetes cluster for a small application that you don’t plan to offer to the general public. It’s time to choose the machine type for your nodes. Which of the following is probably the best choice? 

- **A general-purpose machine**
- A compute-optimized machine 
- A memory-optimized machine
- An accelerator-optimized machine

## Question 7
You just got a new job in the IT department of a software firm. You overhear two of your new colleagues talking about the organization’s local development cluster. What do you think this cluster might be used for? Select all that apply.

- **Application development and testing.**
- Data storage to comply with data governance requirements.
- **Rapid iteration and debugging of applications before deploying them to production clusters.**
- To support low latency, particularly in zones with poor network connectivity.

## Question 8
You’ve decided to run your Docker containers on the Google Cloud Platform, and you’re about to choose which service to use. What are some advantages of Cloud Run? 

- **It’s a fully managed platform.**
- It can accommodate stateful applications.
- It has a huge amount of flexibility in its configuration. 
- **It can scale down to zero.**

## Question 9
Which of the following statements about containers are true? Select all that apply.

- You can use containers to describe the key properties of an application.
- You can use containers to scale applications outside the containers themselves.
- You can use containers to share applications with peer programmers.
- **You can use containers to test different instances of the same application.**

## Question 10
Samantha is a Python developer working on a web application that has a user interface, an API layer, and a database. She wants to enable communication between the API layer and the database, ensuring that these exchanges are internal to the application. Which Kubernetes service type should Samantha use to achieve this?

- NodePort
- **ClusterIP**
- LoadBalancer
- ExternalName