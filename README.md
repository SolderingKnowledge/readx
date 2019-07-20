 `npm install` to install dependencies
`npm start`  to start the project


`docker build -t containername .` should all lowercase the container name

 `docker run -it containername` to run docker container and you will end up in you root server.

Something like  `root@[ip_address]:/# ` it will end up in shell

To check docker is working, type on your docker shell `node -v` and in local terminal `node -v`
Congratulations!! - You will see now you will have 2 different versions of NodeJS.


To change node versions go to this link: https://hub.docker.com/explore/ -> https://hub.docker.com/_/node

### This is Dockerfile:

`FROM node:carbon` ,

`From node:11.15.0`

Once you change the version of Node then you need to ` exit ` then `docker build -t containername`



## Documentations for docker:

`docker run -it -d containername` -> to run without going inside the container, but in background


`docker ps`-> we can see all the containers that are running, it is like `ls` in terminal :)


`docker exec -it [containerID(whichIsHash)] bash` -> to access the container shell that is running

I put in the arrray so, you it means that is options.


`docker stop [containerId]` -> to stop docker container 