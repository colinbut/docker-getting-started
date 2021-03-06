# Getting Started with Docker

This mini project explores what it takes to get started in using Docker.

## Download

To download go to Docker website and hit the big download buttons for your operating system platform.
I use Mac OSX so i downloaded __Docker for Mac__. 
It used to be __Docker Toolbox__ where it used __VirtualBox__ to manage linux VMs.
And before that, some years ago now, it used to be __Boot2Docker__.

Note that if you've previously had Docker Toolbox then it can co-live with the new __Docker for Mac__
__Docker for Mac__ is very simple and very intuitive to use. Everything need to know is on the Docker website.


## Installation

Pretty straight forward in just following the docker guides on installation. For __Docker for Mac__ just double click the .dmg file and drag the Docker app to Applications folder.

## Docker Commands

The following docker commands are most used by me. Need to know.

```
docker version
```

```
docker --version
```

```
docker images
```

```
docker rmi <image id>
```

```
docker ps
```

```
docker ps -a
```

```
docker run <docker image>
```

```
docker rm <container id>
```

```
docker stop <container id>
```

```
docker start <container id>
```

```
docker restart <container id>
```

```
docker port
```

```
docker logs
```

```
docker build -t <tag name> .
```

```
docker run -d -P <tag name>
```

```
docker run -i -t <tag name>
```

```
docker run -d -p 8080:8080 --name <docker-container-name>
```

## General Usage

Common usage is:

- Develop your app and wrap it under docker container by writing a Dockerfile
- build this docker file
- save it if necessary
- load it if necessary
- run it (locally)
- tag it if necessary
- push it to docker registry (e.g. DockerHub)

- can also pull from docker registry 

