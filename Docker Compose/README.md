## ***What is Docker Compose ?***
- tool for defining and running multi-container docker application
- use yaml files to configure application services ( **docker-compose.yml**)
- can start all services with a single command: **docker compose up**
- can stop all services with a single command: **docker compose down**
- can scale up selected services when required


## 1. Install Docker compose

**To check the Docker version**
``` docker-compose -v``` : these 3 commands shows the version that is installed
``` docker-compose version```
``` docker-compose --version```

For installation in linux:
```pip install -U docker-compose```

## 2. Create a docker compose file at any location on your system ```docker-compose.yml```

- ```mkdir DockerComposeFile```
- ``` cd DockerComposeFile```
- ```touch docker-compose.yml```
- ```vi docker-compose.yml```

## Inside the docker-compose.yml file. we will use nginx service for it now
```version:'3'```

```services:```

	web:
	  image:nginx
	
	database:
	  image: redis  
to get out from it: ```esc```+ ```:```+```w```+```q```+```!```

- ```cat docker-compose.yml```


## 3. Check the validity of file by command ```docker-compose-config```

## 4. Run docker-compose.yml file by command ```docker-compose up -d``` : to create container in application and -d is for staring in detached mode 

## 5. ```docker ps```
## 6. ```docker-compose down``` : to stop the service 


## How to scale sevices
```docker-compose up -d --scale "services"```






