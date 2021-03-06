## **DockerFile**
- A text file with instructions to build image
- Automation of Docker image for image creation

## **Basic Instruction used in Docker files**
- FROM
- RUN
- CMD

## **Steps**
1. Create a file named Dockerfile ( ποΈIt is in your Terminal)
 **Procedure**:
- ```mkdir DockerFiles``` : Create a folder
- ``` cd DockerFiles```   : Go inside the folder
- ```touch DockerFiles``` : Create a file name DockerFiles without extension
- ```vim DockerFiles```   : It is used to edit on DockerFiles

2. **Add instruction in DockerFile**  
ποΈ you are inside the DockerFile to edit:  

**Press I in your keyboard to go to INSERT Mode**  
You can use a base image i.e ```ubuntu``` or a empty image i.e. ```scratch```

#### **Getting base image ubuntu**
- ```FROM ubuntu``` | ```FROM scratch```      : for empty image 	

- ```MAINTAINER REBAN <Reyban86@gmail.com>``` : It is better to specify the maintainer of the DockerFiles

- ```RUN apt-get update```		      : to run commands on the image

- If you want to run some command line during container creation then ποΈ:  
- ```CMD ["echo", "Hello World ...! from my first docker image"]```

- To get out from the **DockerFile** use below command ποΈ:  
- ```ESC```+ ```colon``` + ```w``` + ```q```+ ```!``` to exit : w is for writing


3. **Build dockerfile to create image**

- ```docker build location_of_dockerFile```
- ```docker build . ```  :for build the image
- ```docker build -t ImageName:Tag directory of file .``` (e.g  docker build -t . ``` ): we can give the tag number to our docker file

4. **Run image to create container**

-  ```docker images```
- ```docker run image_id```


## ποΈ **Useful Links:** 
- [DockerFile](https://github.com/wsargent/docker-cheat-sheet#dockerfile)
- [Documentation](https://docs.docker.com/engine/reference/builder/)





