# docker container setup for AWS
[![Build Status](https://travis-ci.com/benhalverson/docker-kubernates-prod.svg?branch=master)](https://travis-ci.com/benhalverson/docker-kubernates-prod)

## Features include: 
  - local react dev server
  - running local tests
  - building on a CI server
  - auto deploying if the CI build passes

## Local dev

 - To run locally you can use `docker-compose up` to start the servers

 ## Production env
 - `docker ps` tells you the dockerID
 - `docker build .` to build the Dockerfile
 - `docker run -p 80:80 dockerID`