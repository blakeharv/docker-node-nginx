# heroku-docker-node-nginx
Docker Demo...

### Pre-reqs:
 * Download docker for Mac: https://www.docker.com/products/docker#/mac
 * Download Heroku CLI: https://devcenter.heroku.com/articles/heroku-command-line
 * Heroku container docs: https://devcenter.heroku.com/articles/container-registry-and-runtime

````sh
# Verify basic plugins, apps

$ heroku --version
# heroku-toolbelt/3.43.12 (x86_64-darwin10.8.0) ruby/1.9.3
# heroku-cli/5.4.3-a5b1cb1 (darwin-amd64) go1.7.1

$ docker --version
# Docker version 1.12.1, build 6f9534c

# Additional Heroku setup

$ heroku login
$ heroku plugins:install heroku-container-registry
$ heroku container:login

$ git clone git@github.com:blakeharv/heroku-docker-node-nginx.git
````

### Questions:

 1. What is Docker and how does it work?
   * Some cool diagrams: https://www.docker.com/what-docker
   * Actually uses LXC under the hood: https://en.wikipedia.org/wiki/LXC
 2. What is a container registry and how does that work?
   * https://hub.docker.com/explore/
   * https://hub.docker.com/_/node/
