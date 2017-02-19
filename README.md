# python3-alpine-flask-docker [![Build Status](https://travis-ci.org/nikos/python3-alpine-flask-docker.svg?branch=master)](https://travis-ci.org/nikos/python3-alpine-flask-docker)  [![Image Info](https://images.microbadger.com/badges/image/nikos/alpine-python3-flask.svg)](https://microbadger.com/images/nikos/alpine-python3-flask)

Sample Docker container for a Python 3 Flask based application with minimal footprint.

Based on "standard" Python 3 Docker image making
use of Alpine Linux, see https://hub.docker.com/_/python/


## Build Docker image

Generate docker image:

`make build`


## Run Docker container

Spin up a container based on this docker image:

`make run`

Now you should be able to open http://0.0.0.0:5000 and see the demo Flask
app returning a friendly Hello page.

If you use docker machine (on Mac OS X or Windows)
please consult the docker inspect result to get the IP of the host machine
(see `make inspect`).
