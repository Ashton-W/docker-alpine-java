## Minimal Docker image with Java 7

[![Build Status](https://travis-ci.org/Ashton-W/docker-alpine-java-7.svg?branch=master)](https://travis-ci.org/Ashton-W/docker-alpine-java-7)

[![](https://badge.imagelayers.io/Ashton-W/docker-alpine-java-7:latest.svg)](https://imagelayers.io/?images=Ashton-W/docker-alpine-java-7:latest)

Basic [Docker](https://www.docker.com/) image to run [Java](https://www.java.com/) applications.
This is based off [Busybox](http://www.busybox.net/) to keep the size minimal (about 25% of an ubuntu-based image).

### Usage

Example: 

    docker run -it --rm Ashton-W/docker-alpine-java-7 java -version
