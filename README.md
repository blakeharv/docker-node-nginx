# Docker Demo for Multiple Node Apps + NGINX proxy

### Pre-reqs:
 * Download docker for Mac: https://www.docker.com/products/docker#/mac
 * Click the Docker.app to start the Docker Daemon
 * Pull this repo and go to the folder

### Demo:

```sh
$ docker --version
# Docker version 1.12.1, build 6f9534c
$ docker info
# Env output if the daemon is running, otherwise an error

$ docker-compose up
# Will run all the things

# visit 'localhost' in the browser
```

### Questions:

 1. What is Docker and how does it work?
   * Some cool diagrams: https://www.docker.com/what-docker
   * Actually uses LXC under the hood: https://en.wikipedia.org/wiki/LXC
 2. What is a container registry and how does that work?
   * https://hub.docker.com/explore/
   * https://hub.docker.com/_/node/, https://hub.docker.com/_/buildpack-deps/, https://hub.docker.com/_/debian/
 3. Ok, I understand Docker, what's this have to do with the Tues workshop?
   * Container orchestration - image deployment, service discovery, fault recovery, scaling, etc.
   * Micro-client application development
   * Beyond giftcards with the Strangler
   
