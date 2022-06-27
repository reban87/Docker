# Docker
## What is DOCKER?

- Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package. 
- Docker is an open source project that automates the deployment of applications inside software containers 
## How Docker works?
![Image](https://github.com/reban87/Docker/blob/main/docker.png)
- A developer will define all the applications and its dependencies and its requirements which is called as **Docker File**.
- Docker File can be used to create **Docker Images**
- When we run docker image, we will get **Docker Containers**. So docker containers are the run time instances of docker image and these images can also be stored in an online cloud repositories which is **Docker Hub**
- In **Docker Hub** , there are many publicly available images and you can store your own docker images as well. 
- This image can be pulled to any environment like staging environment or test environment.
-

## Client-Server Architecture of Docker
![Image](https://github.com/reban87/Docker/blob/main/Docker%20architecture.jpg)
- The **daemon (server)** receives the commands from the Docker client through CLI or REST API's
- Docker client and daemon can be present on the same host (machine) or different hosts 

## Install Docker in Linux
- ```sudo yum -y update``` 
- ``` sudo yum install -y docker```
- ```docker```
-  ```docker --version```

## Start Docker
- ```start docker```
- ```sudo service docker start```
- ```sudo usermod-a-G docker "user"```
- ```docker info```
-  ```docker run hello-world``` : to run hello-world image
-  ```docker images``` : to get list of images present locally
-  ```docker ps``` : to get list of runnig containers
-  ```docker ps-a``` : to get list of all containers

## Stop Docker
```sudo service docker stop```

## Uninstall Docker
``` sudo yum remove docker```

## Helpful Links
- [ **Installation Related**](https://docs.docker.com/get-docker/)
- [**Installation Steps for amazon ec2**](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/create-container-image.html)

