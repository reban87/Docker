###🗒️**Docker Commands**

## 👉️**Basic Commands**
- ```docker version``` : To check client and server version
- ``` docker -v``` : To check the installed version
- ``` docker --version``` : To check for the installed version (same like above)
- ``` docker info``` : Gives details on installed docker in your system
- ``` docker --help``` : To get help (e.g ```docker run --help```)
- ``` docker login``` : Login to [Docker Hub](hub.docker.com) from the terminal


## 👉️** Commands related to images
- ```docker pull``` : It is used to pull images from dockerhub. (eg. ```docker pull ubuntu```)
- ```docker images --help``` : shows options for differnt flags
- ```docker images``` : To see list of images
- ``` docker images -q``` : q flag will give only the id of images
- ``` docker images -a``` : -a gives the all details of the image
- ```docker rmi --help```: It shows option to delete the images. (e.g ```docker rmi 113a43faa138``` : deleted image of that id)

## 👉️**To run containers
- ```docker run --help``` : Shows different flags for docker run

## 👉️**Commands on Docker Containers**
- ```docker ps``` : shows the containers 
- ```docker run -it ubuntu``` : we are selecting ubuntu container and running it and -it referes to interactive mode
- ```docker start container_id``` : Start the container with id 
- ```docker stop container_id``` : Stop the container


## 👉️**System Commands**
- ```docker stats``` : It shows stats like running memory usage. network input/output
- ```docker system df``` :  :Details on disc like images/caches
- ```docker system prune --help```: gives flags to remove stopped container networks that are not being used: **SENSITIVE COMMAND TO USE***


### 🔗️Helpful Links
- [Docker Hub](https://hub.docker.com/)
- [Documentation](https://docs.docker.com/engine/reference/commandline/ps/)







