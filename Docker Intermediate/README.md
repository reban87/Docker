### ***Docker Intermediate***

## What are images
- Docker Images are templates used to create Docker containers.
- Container is a running instance of image

## Where are Images stored?
Images are stored in Registries (e.g. docker hub)

##  Commands that can be used with Images

 Let us pull ```ubuntu version 18.04 ``` image from the docker hub
-  ```docker pull ubuntu:18.04```

- ```docker images --help``` : shows the flags with numeric ids

- ```doacker images -a``` : list all the available images

- ```docker images -q``` : gives only image ids

- ```docker images -f``` : -f is used to apply filters (e.g ```docker images -f "dagling=false"```)

📝 **dangling images** are the images which are associated with container or running container
 
 - ```dagling=false``` means images are not associated with containers
 - ```dagling=true``` means images are associated with containers


## 💿 Create a container from an image

- ```docker run --name myFirstContainer -it ubuntu bash``` **Comments** ```myFirstContainer```:Container Name , ```-it``` : interactive mode, ```ubuntu```: image

## Inspect the image

- ```docker inspect``` :inspect all the elements of docker

## Stop container

- ```docker stop container_name``` (e.g docker stop myFirstContainer)

## Remove container

- ```docker rm container_name``` (e.g docker rm myFirstContainer)

## Check the history

- ```docker history ubuntu``` : checks the history
